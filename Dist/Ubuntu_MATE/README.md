Ubuntu MATE - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE/Notebook/README.md).

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

Total: 1956

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B85M-D3H                    | Desktop     | [b6128fb3e9](https://linux-hardware.org/?probe=b6128fb3e9) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [64cf10c762](https://linux-hardware.org/?probe=64cf10c762) | Feb 26, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [fb3c4afbaa](https://linux-hardware.org/?probe=fb3c4afbaa) | Feb 26, 2023 |
| Sony          | VGN-Z21WRN_B                | Notebook    | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b1a38edcc2](https://linux-hardware.org/?probe=b1a38edcc2) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [24b1205b0c](https://linux-hardware.org/?probe=24b1205b0c) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | Notebook    | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [ea8027e95b](https://linux-hardware.org/?probe=ea8027e95b) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| ASUSTek       | P5K                         | Desktop     | [1769888b2b](https://linux-hardware.org/?probe=1769888b2b) | Feb 23, 2023 |
| ASUSTek       | P5QL-E                      | Desktop     | [52c9ec67bf](https://linux-hardware.org/?probe=52c9ec67bf) | Feb 23, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| HP            | 85A2                        | All in one  | [c9f6d95fb2](https://linux-hardware.org/?probe=c9f6d95fb2) | Feb 21, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [e1a9b1b0fa](https://linux-hardware.org/?probe=e1a9b1b0fa) | Feb 21, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [fa50111733](https://linux-hardware.org/?probe=fa50111733) | Feb 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e08dcd6c59](https://linux-hardware.org/?probe=e08dcd6c59) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2b56edae65](https://linux-hardware.org/?probe=2b56edae65) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [dde311dcb2](https://linux-hardware.org/?probe=dde311dcb2) | Feb 19, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [68dcf39492](https://linux-hardware.org/?probe=68dcf39492) | Feb 18, 2023 |
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
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| Lenovo        | ThinkPad T470 20HES13701    | Notebook    | [9c839fa75b](https://linux-hardware.org/?probe=9c839fa75b) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ba06eb3e9c](https://linux-hardware.org/?probe=ba06eb3e9c) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [127e027611](https://linux-hardware.org/?probe=127e027611) | Feb 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [14bde69d96](https://linux-hardware.org/?probe=14bde69d96) | Feb 10, 2023 |
| MSI           | MS-B120                     | Mini pc     | [1d365cbddd](https://linux-hardware.org/?probe=1d365cbddd) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Lenovo        | ThinkPad T470 20HES13701    | Notebook    | [fef1f72c3a](https://linux-hardware.org/?probe=fef1f72c3a) | Feb 09, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| HP            | 240 G3                      | Notebook    | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| HP            | Presario CQ56               | Notebook    | [3c6de43677](https://linux-hardware.org/?probe=3c6de43677) | Feb 05, 2023 |
| BESSTAR Te... | CB9                         | Mini pc     | [23fe29b164](https://linux-hardware.org/?probe=23fe29b164) | Feb 05, 2023 |
| Sony          | VPCEH1E1E                   | Notebook    | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4644d239d7](https://linux-hardware.org/?probe=4644d239d7) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [6f95748149](https://linux-hardware.org/?probe=6f95748149) | Jan 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4333734c92](https://linux-hardware.org/?probe=4333734c92) | Jan 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [609a89ca14](https://linux-hardware.org/?probe=609a89ca14) | Jan 27, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [6ed204eca5](https://linux-hardware.org/?probe=6ed204eca5) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [a3a0a3a505](https://linux-hardware.org/?probe=a3a0a3a505) | Jan 25, 2023 |
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
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3525b1f86](https://linux-hardware.org/?probe=e3525b1f86) | Jan 21, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [91dea34a76](https://linux-hardware.org/?probe=91dea34a76) | Jan 20, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [08502cda27](https://linux-hardware.org/?probe=08502cda27) | Jan 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| HP            | 1495                        | Desktop     | [3f6b7a9b73](https://linux-hardware.org/?probe=3f6b7a9b73) | Jan 19, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [e652633643](https://linux-hardware.org/?probe=e652633643) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [c2b8de2fdf](https://linux-hardware.org/?probe=c2b8de2fdf) | Jan 17, 2023 |
| Dell          | Latitude 5410               | Notebook    | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [e76a4c32dc](https://linux-hardware.org/?probe=e76a4c32dc) | Jan 17, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [e8cc3131fc](https://linux-hardware.org/?probe=e8cc3131fc) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [d30e9b41ef](https://linux-hardware.org/?probe=d30e9b41ef) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [a265db8e50](https://linux-hardware.org/?probe=a265db8e50) | Jan 15, 2023 |
| HP            | 805A                        | Desktop     | [5fdeec8d8a](https://linux-hardware.org/?probe=5fdeec8d8a) | Jan 14, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | Notebook    | [b4629bd83f](https://linux-hardware.org/?probe=b4629bd83f) | Jan 14, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [d92542c9e8](https://linux-hardware.org/?probe=d92542c9e8) | Jan 14, 2023 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [aa53c5066d](https://linux-hardware.org/?probe=aa53c5066d) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cdd815de42](https://linux-hardware.org/?probe=cdd815de42) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ff52c2505f](https://linux-hardware.org/?probe=ff52c2505f) | Jan 13, 2023 |
| HP            | 15                          | Notebook    | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e83827b548](https://linux-hardware.org/?probe=e83827b548) | Jan 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0e81ffb471](https://linux-hardware.org/?probe=0e81ffb471) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [88ffbf550c](https://linux-hardware.org/?probe=88ffbf550c) | Jan 11, 2023 |
| Acer          | AO756                       | Notebook    | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [e14b3158f3](https://linux-hardware.org/?probe=e14b3158f3) | Jan 10, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [433ba8749a](https://linux-hardware.org/?probe=433ba8749a) | Jan 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [03505c402c](https://linux-hardware.org/?probe=03505c402c) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7ee7875a97](https://linux-hardware.org/?probe=7ee7875a97) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [75def9e004](https://linux-hardware.org/?probe=75def9e004) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [b30f449318](https://linux-hardware.org/?probe=b30f449318) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [efd4eaee02](https://linux-hardware.org/?probe=efd4eaee02) | Jan 07, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [c5a401b596](https://linux-hardware.org/?probe=c5a401b596) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8b7d2f1a46](https://linux-hardware.org/?probe=8b7d2f1a46) | Jan 07, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a8fb72e94a](https://linux-hardware.org/?probe=a8fb72e94a) | Jan 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05c69304bb](https://linux-hardware.org/?probe=05c69304bb) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [2cb5d2f306](https://linux-hardware.org/?probe=2cb5d2f306) | Jan 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fc365670d0](https://linux-hardware.org/?probe=fc365670d0) | Jan 05, 2023 |
| Dell          | Precision 7520              | Notebook    | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| Acer          | Aspire 5530                 | Notebook    | [8c12909b0a](https://linux-hardware.org/?probe=8c12909b0a) | Jan 04, 2023 |
| Dell          | G5 5590                     | Notebook    | [c0bba3f9fd](https://linux-hardware.org/?probe=c0bba3f9fd) | Jan 04, 2023 |
| Dell          | G5 5590                     | Notebook    | [cb89cf0f00](https://linux-hardware.org/?probe=cb89cf0f00) | Jan 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [73de62ce79](https://linux-hardware.org/?probe=73de62ce79) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [03ca911bb7](https://linux-hardware.org/?probe=03ca911bb7) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0eb54f1078](https://linux-hardware.org/?probe=0eb54f1078) | Jan 01, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [13c0ee7f2d](https://linux-hardware.org/?probe=13c0ee7f2d) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a323cc954e](https://linux-hardware.org/?probe=a323cc954e) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [531e60d101](https://linux-hardware.org/?probe=531e60d101) | Dec 30, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [c286883155](https://linux-hardware.org/?probe=c286883155) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7ac222385a](https://linux-hardware.org/?probe=7ac222385a) | Dec 28, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [faf2c0e5d7](https://linux-hardware.org/?probe=faf2c0e5d7) | Dec 28, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [0a5cad12c2](https://linux-hardware.org/?probe=0a5cad12c2) | Dec 26, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f113c7d475](https://linux-hardware.org/?probe=f113c7d475) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| Toshiba       | Satellite C50D-C            | Notebook    | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [a4447312cc](https://linux-hardware.org/?probe=a4447312cc) | Dec 23, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| HP            | Compaq Presario CQ61        | Notebook    | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c3835ed07f](https://linux-hardware.org/?probe=c3835ed07f) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [af260af715](https://linux-hardware.org/?probe=af260af715) | Dec 19, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [ac787dc7dc](https://linux-hardware.org/?probe=ac787dc7dc) | Dec 17, 2022 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [e47e7c18c9](https://linux-hardware.org/?probe=e47e7c18c9) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP            | 2215                        | Desktop     | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [a69be3386b](https://linux-hardware.org/?probe=a69be3386b) | Dec 16, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| HP            | 14                          | Notebook    | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Dell          | 0P67HD A00                  | Desktop     | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| Biostar       | A320MH                      | Desktop     | [31cc96d1d3](https://linux-hardware.org/?probe=31cc96d1d3) | Dec 11, 2022 |
| MSI           | H81M-E34                    | Desktop     | [a9cc317647](https://linux-hardware.org/?probe=a9cc317647) | Dec 11, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b7a944c773](https://linux-hardware.org/?probe=b7a944c773) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [118d4ebca0](https://linux-hardware.org/?probe=118d4ebca0) | Dec 11, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c57f5be505](https://linux-hardware.org/?probe=c57f5be505) | Dec 10, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [7a6c67f095](https://linux-hardware.org/?probe=7a6c67f095) | Dec 09, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [3caa213ecf](https://linux-hardware.org/?probe=3caa213ecf) | Dec 04, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [c41ea027f7](https://linux-hardware.org/?probe=c41ea027f7) | Dec 04, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1b37803020](https://linux-hardware.org/?probe=1b37803020) | Dec 04, 2022 |
| Intel         | H61                         | Desktop     | [4050e46b94](https://linux-hardware.org/?probe=4050e46b94) | Dec 03, 2022 |
| HP            | 14                          | Notebook    | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e61b6313fa](https://linux-hardware.org/?probe=e61b6313fa) | Dec 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [9964cb6fe2](https://linux-hardware.org/?probe=9964cb6fe2) | Nov 30, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | Notebook    | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Getac         | S410                        | Notebook    | [3df44aa3af](https://linux-hardware.org/?probe=3df44aa3af) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ef9a6b217c](https://linux-hardware.org/?probe=ef9a6b217c) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [29b92290e8](https://linux-hardware.org/?probe=29b92290e8) | Nov 22, 2022 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [f01dec11e4](https://linux-hardware.org/?probe=f01dec11e4) | Nov 21, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [39a6819014](https://linux-hardware.org/?probe=39a6819014) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| NEC Comput... | PC-VK27MCZDM                | Notebook    | [fce4afe996](https://linux-hardware.org/?probe=fce4afe996) | Nov 19, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [a09398bb26](https://linux-hardware.org/?probe=a09398bb26) | Nov 18, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Chuwi         | X312B                       | Notebook    | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Chuwi         | X312B                       | Notebook    | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| MSI           | Z97I GAMING AC              | Desktop     | [b0a5c0251f](https://linux-hardware.org/?probe=b0a5c0251f) | Nov 15, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Dell          | Latitude D630               | Notebook    | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | Notebook    | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Intel         | H61                         | Desktop     | [7d93f12ac4](https://linux-hardware.org/?probe=7d93f12ac4) | Nov 11, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [1117e533c3](https://linux-hardware.org/?probe=1117e533c3) | Nov 11, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Microsoft     | Surface 2                   | Tablet      | [0cab1d9501](https://linux-hardware.org/?probe=0cab1d9501) | Nov 10, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [6e773a6bf0](https://linux-hardware.org/?probe=6e773a6bf0) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [5264f28363](https://linux-hardware.org/?probe=5264f28363) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | Notebook    | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| Dell          | Studio 1558                 | Notebook    | [8b5cb100a8](https://linux-hardware.org/?probe=8b5cb100a8) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [65c0f5965b](https://linux-hardware.org/?probe=65c0f5965b) | Nov 04, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [4b580ecb2b](https://linux-hardware.org/?probe=4b580ecb2b) | Nov 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [c47ee488a5](https://linux-hardware.org/?probe=c47ee488a5) | Nov 03, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [34c050ed44](https://linux-hardware.org/?probe=34c050ed44) | Nov 03, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [ada830a489](https://linux-hardware.org/?probe=ada830a489) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | Desktop     | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [e4af6d51f3](https://linux-hardware.org/?probe=e4af6d51f3) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [600587e66a](https://linux-hardware.org/?probe=600587e66a) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [e1709bf653](https://linux-hardware.org/?probe=e1709bf653) | Oct 28, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [05cffb09e0](https://linux-hardware.org/?probe=05cffb09e0) | Oct 28, 2022 |
| Samsung       | 760XBE                      | Notebook    | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Samsung       | 760XBE                      | Notebook    | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Dell          | Precision 7760              | Notebook    | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [7640c7a49f](https://linux-hardware.org/?probe=7640c7a49f) | Oct 20, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| HP            | ENVY Sleekbook 6            | Notebook    | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Dell          | 0DPRF9 A00                  | All in one  | [3d0b820b58](https://linux-hardware.org/?probe=3d0b820b58) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| HP            | ENVY x360                   | Convertible | [b299af0bca](https://linux-hardware.org/?probe=b299af0bca) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
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
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [92e65a376a](https://linux-hardware.org/?probe=92e65a376a) | Oct 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HP            | 15                          | Notebook    | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [682eb02d48](https://linux-hardware.org/?probe=682eb02d48) | Sep 22, 2022 |
| Dell          | Precision 7760              | Notebook    | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [1573d65d2d](https://linux-hardware.org/?probe=1573d65d2d) | Sep 18, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| Dell          | Precision 7520              | Notebook    | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [8774a8312b](https://linux-hardware.org/?probe=8774a8312b) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a86e9d966b](https://linux-hardware.org/?probe=a86e9d966b) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [e36022370b](https://linux-hardware.org/?probe=e36022370b) | Sep 08, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| Dell          | Precision 7760              | Notebook    | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | 18E4                        | Desktop     | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | Desktop     | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Dell          | Latitude 5285               | Tablet      | [4e75bec854](https://linux-hardware.org/?probe=4e75bec854) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2d66cac294](https://linux-hardware.org/?probe=2d66cac294) | Aug 28, 2022 |
| HP            | Pavilion dv5                | Notebook    | [dd2f0b859b](https://linux-hardware.org/?probe=dd2f0b859b) | Aug 24, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| AZW           | GK55                        | Desktop     | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| ASUSTek       | M4A78-E                     | Desktop     | [76028e78e9](https://linux-hardware.org/?probe=76028e78e9) | Aug 19, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [e8b519c4de](https://linux-hardware.org/?probe=e8b519c4de) | Aug 18, 2022 |
| ASUSTek       | UX32A                       | Notebook    | [99bb55bc78](https://linux-hardware.org/?probe=99bb55bc78) | Aug 17, 2022 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [a5ed221478](https://linux-hardware.org/?probe=a5ed221478) | Aug 17, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| MSI           | MS-77311                    | Desktop     | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [9655bf78d0](https://linux-hardware.org/?probe=9655bf78d0) | Aug 05, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Google        | Swanky                      | Notebook    | [f54bdd7887](https://linux-hardware.org/?probe=f54bdd7887) | Aug 04, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [40099f2516](https://linux-hardware.org/?probe=40099f2516) | Aug 03, 2022 |
| HP            | 8433 11                     | Desktop     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Google        | Swanky                      | Notebook    | [daac706167](https://linux-hardware.org/?probe=daac706167) | Aug 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b44bebcab6](https://linux-hardware.org/?probe=b44bebcab6) | Aug 01, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3aa2ff8224](https://linux-hardware.org/?probe=3aa2ff8224) | Jul 29, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [5d5fd15071](https://linux-hardware.org/?probe=5d5fd15071) | Jul 28, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [19572ca302](https://linux-hardware.org/?probe=19572ca302) | Jul 27, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [59d8bb1e10](https://linux-hardware.org/?probe=59d8bb1e10) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [a8bcc56e78](https://linux-hardware.org/?probe=a8bcc56e78) | Jul 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5795e098d2](https://linux-hardware.org/?probe=5795e098d2) | Jul 26, 2022 |
| ONDA          | H110-MINI V3.00 Ver:3.00    | Desktop     | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| MSI           | 2AE0                        | Desktop     | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | Desktop     | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Dell          | Latitude E4200              | Notebook    | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| BESSTAR Te... | CB9                         | Mini pc     | [faa42224f0](https://linux-hardware.org/?probe=faa42224f0) | Jul 18, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [3e74ebae5a](https://linux-hardware.org/?probe=3e74ebae5a) | Jul 14, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| Sony          | VPCEB1S1E                   | Notebook    | [d35015a369](https://linux-hardware.org/?probe=d35015a369) | Jul 12, 2022 |
| Dell          | Latitude XT                 | Notebook    | [9d9deeace5](https://linux-hardware.org/?probe=9d9deeace5) | Jul 10, 2022 |
| Dell          | Latitude XT                 | Notebook    | [b0a096fb7d](https://linux-hardware.org/?probe=b0a096fb7d) | Jul 10, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0cdcc2c0e0](https://linux-hardware.org/?probe=0cdcc2c0e0) | Jul 10, 2022 |
| MicroByte     | ezbook                      | Notebook    | [0f08faf963](https://linux-hardware.org/?probe=0f08faf963) | Jul 08, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [5f1b339a57](https://linux-hardware.org/?probe=5f1b339a57) | Jul 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [cce90ecbf2](https://linux-hardware.org/?probe=cce90ecbf2) | Jul 04, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e0c6593aee](https://linux-hardware.org/?probe=e0c6593aee) | Jul 04, 2022 |
| Dell          | 0M6C7G A00                  | Desktop     | [5eee0db64f](https://linux-hardware.org/?probe=5eee0db64f) | Jul 03, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| HP            | 2B0D A01                    | All in one  | [43b3fd0fd4](https://linux-hardware.org/?probe=43b3fd0fd4) | Jul 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [87eecce08e](https://linux-hardware.org/?probe=87eecce08e) | Jun 30, 2022 |
| MicroByte     | ezbook                      | Notebook    | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | Notebook    | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| MSI           | H81M-E33                    | Desktop     | [0685f37e2c](https://linux-hardware.org/?probe=0685f37e2c) | Jun 22, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0112d58d4e](https://linux-hardware.org/?probe=0112d58d4e) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e048d9df09](https://linux-hardware.org/?probe=e048d9df09) | Jun 17, 2022 |
| Google        | Kled                        | Notebook    | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | Notebook    | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| MSI           | 3664h                       | Desktop     | [5fbb22c653](https://linux-hardware.org/?probe=5fbb22c653) | Jun 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [94abe2c8af](https://linux-hardware.org/?probe=94abe2c8af) | Jun 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [efc9e12c05](https://linux-hardware.org/?probe=efc9e12c05) | Jun 12, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [3de31234b3](https://linux-hardware.org/?probe=3de31234b3) | Jun 12, 2022 |
| Dell          | 0HV8FN A01                  | Desktop     | [33d201cb1d](https://linux-hardware.org/?probe=33d201cb1d) | Jun 10, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| HP            | 3397                        | Desktop     | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [d9e8d3957e](https://linux-hardware.org/?probe=d9e8d3957e) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | Notebook    | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3b4483236d](https://linux-hardware.org/?probe=3b4483236d) | Jun 05, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [20544feb00](https://linux-hardware.org/?probe=20544feb00) | Jun 03, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [73746e5672](https://linux-hardware.org/?probe=73746e5672) | Jun 03, 2022 |
| Dell          | Precision M6500             | Notebook    | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Fujitsu       | LIFEBOOK E5511              | Notebook    | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | Notebook    | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| INP           | i1000BTS                    | Desktop     | [95da2ada33](https://linux-hardware.org/?probe=95da2ada33) | May 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| Medion        | Akoya E6415                 | Notebook    | [32545030d4](https://linux-hardware.org/?probe=32545030d4) | May 16, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [c8900ed973](https://linux-hardware.org/?probe=c8900ed973) | May 15, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [8b912c2c4f](https://linux-hardware.org/?probe=8b912c2c4f) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [4d68e6fd8d](https://linux-hardware.org/?probe=4d68e6fd8d) | May 12, 2022 |
| HP            | 3031h                       | Desktop     | [4a57ff5761](https://linux-hardware.org/?probe=4a57ff5761) | May 10, 2022 |
| Unknown       | HX90                        | Desktop     | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | Notebook    | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [86c82d9ca0](https://linux-hardware.org/?probe=86c82d9ca0) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [a55c5c5c9f](https://linux-hardware.org/?probe=a55c5c5c9f) | May 03, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | 8433 11                     | Desktop     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| TYAN Compu... | S7012                       | Server      | [018f293210](https://linux-hardware.org/?probe=018f293210) | Apr 28, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4dd8fa1d2f](https://linux-hardware.org/?probe=4dd8fa1d2f) | Apr 27, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [fc283a78af](https://linux-hardware.org/?probe=fc283a78af) | Apr 26, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [bbb54a4f60](https://linux-hardware.org/?probe=bbb54a4f60) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [b2b220b65d](https://linux-hardware.org/?probe=b2b220b65d) | Apr 25, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [d3d995a41b](https://linux-hardware.org/?probe=d3d995a41b) | Apr 24, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [26fa0f202c](https://linux-hardware.org/?probe=26fa0f202c) | Apr 20, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [83ffe21604](https://linux-hardware.org/?probe=83ffe21604) | Apr 18, 2022 |
| Dell          | 0X9M3X A05                  | Desktop     | [f049c88dfe](https://linux-hardware.org/?probe=f049c88dfe) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [81dced5e0a](https://linux-hardware.org/?probe=81dced5e0a) | Apr 16, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [d7811dbd43](https://linux-hardware.org/?probe=d7811dbd43) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [52d05bca1d](https://linux-hardware.org/?probe=52d05bca1d) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7a9f6e1de7](https://linux-hardware.org/?probe=7a9f6e1de7) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| Samsung       | R505                        | Notebook    | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| Dell          | Latitude E5400              | Notebook    | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [c640615939](https://linux-hardware.org/?probe=c640615939) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a54c91912a](https://linux-hardware.org/?probe=a54c91912a) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [5e31d89c28](https://linux-hardware.org/?probe=5e31d89c28) | Apr 09, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| Gigabyte      | H470M DS3H                  | Desktop     | [bbfc43c637](https://linux-hardware.org/?probe=bbfc43c637) | Apr 05, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [5f45322780](https://linux-hardware.org/?probe=5f45322780) | Apr 04, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [42cf748563](https://linux-hardware.org/?probe=42cf748563) | Apr 03, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [8340e366fc](https://linux-hardware.org/?probe=8340e366fc) | Mar 28, 2022 |
| Toshiba       | Satellite L755D             | Notebook    | [d99ccc2771](https://linux-hardware.org/?probe=d99ccc2771) | Mar 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [3a8a0e2c0c](https://linux-hardware.org/?probe=3a8a0e2c0c) | Mar 26, 2022 |
| Dell          | 05KX61 A00                  | Server      | [77d570f7ae](https://linux-hardware.org/?probe=77d570f7ae) | Mar 25, 2022 |
| Dell          | Studio 1558                 | Notebook    | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Dell          | Vostro 3350                 | Notebook    | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| HP            | 802E                        | Desktop     | [b15f756d65](https://linux-hardware.org/?probe=b15f756d65) | Mar 21, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| HP            | 3397                        | Desktop     | [fe1ae429b1](https://linux-hardware.org/?probe=fe1ae429b1) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| HP            | Pavilion dv7                | Notebook    | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [220c4f69b0](https://linux-hardware.org/?probe=220c4f69b0) | Mar 15, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [7bbbcc53c1](https://linux-hardware.org/?probe=7bbbcc53c1) | Mar 14, 2022 |
| Dell          | OptiPlex 980                | Desktop     | [14cf2b23f7](https://linux-hardware.org/?probe=14cf2b23f7) | Mar 14, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [d59f0b152c](https://linux-hardware.org/?probe=d59f0b152c) | Mar 10, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [776d052837](https://linux-hardware.org/?probe=776d052837) | Mar 09, 2022 |
| Packard Be... | EasyNote MH35               | Notebook    | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [6382c70064](https://linux-hardware.org/?probe=6382c70064) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [8e3573295d](https://linux-hardware.org/?probe=8e3573295d) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [d57f5c8ce3](https://linux-hardware.org/?probe=d57f5c8ce3) | Mar 07, 2022 |
| Medion        | MS-7797                     | Desktop     | [88982d8ccb](https://linux-hardware.org/?probe=88982d8ccb) | Mar 05, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [f23d0b2728](https://linux-hardware.org/?probe=f23d0b2728) | Mar 05, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [b18f6804d6](https://linux-hardware.org/?probe=b18f6804d6) | Mar 02, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [43c3e7c4a0](https://linux-hardware.org/?probe=43c3e7c4a0) | Mar 02, 2022 |
| Lenovo        | U310                        | Notebook    | [856a65502e](https://linux-hardware.org/?probe=856a65502e) | Feb 28, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| Intel         | H55                         | Desktop     | [2f52a73f85](https://linux-hardware.org/?probe=2f52a73f85) | Feb 27, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [beeb081772](https://linux-hardware.org/?probe=beeb081772) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| Pegatron      | Narra6                      | Desktop     | [ad9a06f14d](https://linux-hardware.org/?probe=ad9a06f14d) | Feb 25, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [09aca1c435](https://linux-hardware.org/?probe=09aca1c435) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [35c00d5889](https://linux-hardware.org/?probe=35c00d5889) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [265235f4f4](https://linux-hardware.org/?probe=265235f4f4) | Feb 21, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| Lenovo        | ThinkPad T460p 20FW000VU... | Notebook    | [9cbb915f78](https://linux-hardware.org/?probe=9cbb915f78) | Feb 18, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [0747de6777](https://linux-hardware.org/?probe=0747de6777) | Feb 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [b6459dbb39](https://linux-hardware.org/?probe=b6459dbb39) | Feb 12, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [e58751112a](https://linux-hardware.org/?probe=e58751112a) | Feb 11, 2022 |
| Notebook      | NK50S5_SZ                   | Notebook    | [c5a3485d32](https://linux-hardware.org/?probe=c5a3485d32) | Feb 11, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [6f66651cd1](https://linux-hardware.org/?probe=6f66651cd1) | Feb 10, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [7c3fa0c43b](https://linux-hardware.org/?probe=7c3fa0c43b) | Feb 08, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3d6c666b77](https://linux-hardware.org/?probe=3d6c666b77) | Feb 08, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [6bb9884c12](https://linux-hardware.org/?probe=6bb9884c12) | Feb 08, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [74ebb0645d](https://linux-hardware.org/?probe=74ebb0645d) | Feb 06, 2022 |
| HP            | Notebook                    | Notebook    | [69071da574](https://linux-hardware.org/?probe=69071da574) | Feb 06, 2022 |
| Acer          | Aspire 7735                 | Notebook    | [38d97cd9da](https://linux-hardware.org/?probe=38d97cd9da) | Feb 06, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [451c540217](https://linux-hardware.org/?probe=451c540217) | Feb 05, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [4dc312f4f3](https://linux-hardware.org/?probe=4dc312f4f3) | Feb 02, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f317005b0a](https://linux-hardware.org/?probe=f317005b0a) | Feb 02, 2022 |
| Lenovo        | NOK                         | Desktop     | [8905840b45](https://linux-hardware.org/?probe=8905840b45) | Feb 02, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |
| HP            | 8434 11                     | Desktop     | [76a7851e7f](https://linux-hardware.org/?probe=76a7851e7f) | Jan 28, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8f2181125e](https://linux-hardware.org/?probe=8f2181125e) | Jan 27, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [fab2b2828e](https://linux-hardware.org/?probe=fab2b2828e) | Jan 26, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [8062682731](https://linux-hardware.org/?probe=8062682731) | Jan 25, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [47e447f5da](https://linux-hardware.org/?probe=47e447f5da) | Jan 25, 2022 |
| Sony          | VPCF13Z1R                   | Notebook    | [7aff0d5c29](https://linux-hardware.org/?probe=7aff0d5c29) | Jan 25, 2022 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [cad36b0eba](https://linux-hardware.org/?probe=cad36b0eba) | Jan 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [868c5fe3a4](https://linux-hardware.org/?probe=868c5fe3a4) | Jan 24, 2022 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [a4b48a8427](https://linux-hardware.org/?probe=a4b48a8427) | Jan 23, 2022 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [622bf721f3](https://linux-hardware.org/?probe=622bf721f3) | Jan 23, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [55067d6afe](https://linux-hardware.org/?probe=55067d6afe) | Jan 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [37730388fd](https://linux-hardware.org/?probe=37730388fd) | Jan 21, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | Desktop     | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| HP            | 8455                        | Desktop     | [fbf272366c](https://linux-hardware.org/?probe=fbf272366c) | Jan 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [512b021ab8](https://linux-hardware.org/?probe=512b021ab8) | Jan 19, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [09e824f68b](https://linux-hardware.org/?probe=09e824f68b) | Jan 19, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | Desktop     | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | Desktop     | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [597677191c](https://linux-hardware.org/?probe=597677191c) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [b68364ed90](https://linux-hardware.org/?probe=b68364ed90) | Jan 19, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [8314cd9ba6](https://linux-hardware.org/?probe=8314cd9ba6) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [9fedcb7ff7](https://linux-hardware.org/?probe=9fedcb7ff7) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [48871270a2](https://linux-hardware.org/?probe=48871270a2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [ca38c856e1](https://linux-hardware.org/?probe=ca38c856e1) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a4df88b38f](https://linux-hardware.org/?probe=a4df88b38f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a745b9add0](https://linux-hardware.org/?probe=a745b9add0) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [b69abe6fd4](https://linux-hardware.org/?probe=b69abe6fd4) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [9753f9164a](https://linux-hardware.org/?probe=9753f9164a) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [2d7a6e6cb6](https://linux-hardware.org/?probe=2d7a6e6cb6) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [51484889f9](https://linux-hardware.org/?probe=51484889f9) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4ca462c89a](https://linux-hardware.org/?probe=4ca462c89a) | Jan 18, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c4c9f4b0a9](https://linux-hardware.org/?probe=c4c9f4b0a9) | Jan 18, 2022 |
| HP            | 8434 11                     | Desktop     | [4a128d2bb2](https://linux-hardware.org/?probe=4a128d2bb2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [97d4bc7367](https://linux-hardware.org/?probe=97d4bc7367) | Jan 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [7ae2819a6f](https://linux-hardware.org/?probe=7ae2819a6f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [e86d0cc284](https://linux-hardware.org/?probe=e86d0cc284) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [022f56a960](https://linux-hardware.org/?probe=022f56a960) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [0d2a09f683](https://linux-hardware.org/?probe=0d2a09f683) | Jan 18, 2022 |
| HP            | 8455                        | Desktop     | [639182896b](https://linux-hardware.org/?probe=639182896b) | Jan 18, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [556d0fb884](https://linux-hardware.org/?probe=556d0fb884) | Jan 18, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3d19d1297](https://linux-hardware.org/?probe=c3d19d1297) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | Desktop     | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [3c8e26636b](https://linux-hardware.org/?probe=3c8e26636b) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6438d5a5af](https://linux-hardware.org/?probe=6438d5a5af) | Jan 15, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [89d70da207](https://linux-hardware.org/?probe=89d70da207) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ae80854830](https://linux-hardware.org/?probe=ae80854830) | Jan 15, 2022 |
| ZOTAC         | NM10                        | Desktop     | [d758728651](https://linux-hardware.org/?probe=d758728651) | Jan 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d2fa7ede7](https://linux-hardware.org/?probe=9d2fa7ede7) | Jan 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2fbac2ebd5](https://linux-hardware.org/?probe=2fbac2ebd5) | Jan 12, 2022 |
| HPE           | ML10Gen9                    | Server      | [03f2d30df2](https://linux-hardware.org/?probe=03f2d30df2) | Jan 11, 2022 |
| Dell          | Latitude E5400              | Notebook    | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| HP            | 3397                        | Desktop     | [38a4d731fe](https://linux-hardware.org/?probe=38a4d731fe) | Jan 08, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [4103077e59](https://linux-hardware.org/?probe=4103077e59) | Jan 08, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [858d718984](https://linux-hardware.org/?probe=858d718984) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [faef08af10](https://linux-hardware.org/?probe=faef08af10) | Jan 06, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [55ac013e1e](https://linux-hardware.org/?probe=55ac013e1e) | Jan 06, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [f3838abaaf](https://linux-hardware.org/?probe=f3838abaaf) | Jan 04, 2022 |
| HP            | ProLiant DL120 G7           | Server      | [70c39995ec](https://linux-hardware.org/?probe=70c39995ec) | Jan 03, 2022 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [9eb9340d47](https://linux-hardware.org/?probe=9eb9340d47) | Jan 02, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| ASRock        | 870iCafe R2.0               | Desktop     | [f67cc91b2e](https://linux-hardware.org/?probe=f67cc91b2e) | Dec 31, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [5a25a3ab14](https://linux-hardware.org/?probe=5a25a3ab14) | Dec 31, 2021 |
| Gigabyte      | MZ71-CE0-00 01000100        | Server      | [6d2ee30f72](https://linux-hardware.org/?probe=6d2ee30f72) | Dec 31, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e637f730e7](https://linux-hardware.org/?probe=e637f730e7) | Dec 31, 2021 |
| MSI           | H81M-P33                    | Desktop     | [4c225dc457](https://linux-hardware.org/?probe=4c225dc457) | Dec 30, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [82163f143b](https://linux-hardware.org/?probe=82163f143b) | Dec 29, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | Desktop     | [e32af6a3de](https://linux-hardware.org/?probe=e32af6a3de) | Dec 26, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | Notebook    | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [62abb9d0ef](https://linux-hardware.org/?probe=62abb9d0ef) | Dec 25, 2021 |
| Lenovo        | U310                        | Notebook    | [fa57a69141](https://linux-hardware.org/?probe=fa57a69141) | Dec 24, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [1fbef2b76c](https://linux-hardware.org/?probe=1fbef2b76c) | Dec 23, 2021 |
| HP            | Pavilion dv4                | Notebook    | [7152c2fcd9](https://linux-hardware.org/?probe=7152c2fcd9) | Dec 22, 2021 |
| Lenovo        | G580 2189                   | Notebook    | [843f8c04fe](https://linux-hardware.org/?probe=843f8c04fe) | Dec 21, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [8f53f4e97c](https://linux-hardware.org/?probe=8f53f4e97c) | Dec 19, 2021 |
| AZW           | GK mini                     | Mini pc     | [bb4770d627](https://linux-hardware.org/?probe=bb4770d627) | Dec 17, 2021 |
| HP            | ENVY Notebook               | Notebook    | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| Acer          | Aspire ES1-523              | Notebook    | [66a8186276](https://linux-hardware.org/?probe=66a8186276) | Dec 15, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [3bd9548bab](https://linux-hardware.org/?probe=3bd9548bab) | Dec 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| ASUSTek       | X751BP                      | Notebook    | [e1acc83725](https://linux-hardware.org/?probe=e1acc83725) | Dec 06, 2021 |
| MSI           | H61M-S20                    | Desktop     | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [2cd39490da](https://linux-hardware.org/?probe=2cd39490da) | Dec 02, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [50acb69e6e](https://linux-hardware.org/?probe=50acb69e6e) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Dell          | Latitude E6400              | Notebook    | [170f397883](https://linux-hardware.org/?probe=170f397883) | Dec 02, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0d26ec246](https://linux-hardware.org/?probe=d0d26ec246) | Dec 01, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [3b06bfa748](https://linux-hardware.org/?probe=3b06bfa748) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| HP            | 3646h                       | Desktop     | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | Desktop     | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6b7ec76b64](https://linux-hardware.org/?probe=6b7ec76b64) | Nov 28, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [9b13286f92](https://linux-hardware.org/?probe=9b13286f92) | Nov 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3d2583b1f1](https://linux-hardware.org/?probe=3d2583b1f1) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| Dell          | 0T656F A01                  | Desktop     | [06f4633f1b](https://linux-hardware.org/?probe=06f4633f1b) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [8b5c3b008f](https://linux-hardware.org/?probe=8b5c3b008f) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bf8ac4dc12](https://linux-hardware.org/?probe=bf8ac4dc12) | Nov 24, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [bb170a308c](https://linux-hardware.org/?probe=bb170a308c) | Nov 24, 2021 |
| HPE           | ML10Gen9                    | Server      | [141f8709dd](https://linux-hardware.org/?probe=141f8709dd) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| Dell          | Precision 5560              | Notebook    | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [b8f5329824](https://linux-hardware.org/?probe=b8f5329824) | Nov 22, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [da444f9b8f](https://linux-hardware.org/?probe=da444f9b8f) | Nov 22, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [a13103a9ad](https://linux-hardware.org/?probe=a13103a9ad) | Nov 20, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [63f392ea8b](https://linux-hardware.org/?probe=63f392ea8b) | Nov 18, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |
| Dell          | 0G261D A00                  | Desktop     | [1bb376a60b](https://linux-hardware.org/?probe=1bb376a60b) | Nov 17, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [162531d482](https://linux-hardware.org/?probe=162531d482) | Nov 16, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [8a6de2970d](https://linux-hardware.org/?probe=8a6de2970d) | Nov 15, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2cdd151d75](https://linux-hardware.org/?probe=2cdd151d75) | Nov 14, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Notebook    | [e881f41269](https://linux-hardware.org/?probe=e881f41269) | Nov 14, 2021 |
| Dell          | Latitude E6410              | Notebook    | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| AMI           | Unknown                     | Notebook    | [d1cd5b09e1](https://linux-hardware.org/?probe=d1cd5b09e1) | Nov 12, 2021 |
| Toshiba       | Satellite C665              | Notebook    | [a136cdd51d](https://linux-hardware.org/?probe=a136cdd51d) | Nov 11, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [61bfe5dfa7](https://linux-hardware.org/?probe=61bfe5dfa7) | Nov 11, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [1971073b86](https://linux-hardware.org/?probe=1971073b86) | Nov 10, 2021 |
| HP            | ZBook 15                    | Notebook    | [835fb0e921](https://linux-hardware.org/?probe=835fb0e921) | Nov 10, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [dd8a96b615](https://linux-hardware.org/?probe=dd8a96b615) | Nov 09, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [89aff3881c](https://linux-hardware.org/?probe=89aff3881c) | Nov 09, 2021 |
| ASUSTek       | A55BM-E                     | Desktop     | [fd25737c58](https://linux-hardware.org/?probe=fd25737c58) | Nov 09, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [c0b1971c18](https://linux-hardware.org/?probe=c0b1971c18) | Nov 09, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| Rockchip      | Unknown                     | Soc         | [de559ac6d9](https://linux-hardware.org/?probe=de559ac6d9) | Nov 08, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e21897758d](https://linux-hardware.org/?probe=e21897758d) | Nov 07, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [914d585adc](https://linux-hardware.org/?probe=914d585adc) | Nov 07, 2021 |
| GPD           | P2 MAX                      | Notebook    | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| AZW           | SEi                         | Notebook    | [6d9a86e769](https://linux-hardware.org/?probe=6d9a86e769) | Nov 02, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [05e3caa05c](https://linux-hardware.org/?probe=05e3caa05c) | Nov 02, 2021 |
| MSI           | GE76 Raider 11UG            | Notebook    | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [60ffb9d428](https://linux-hardware.org/?probe=60ffb9d428) | Oct 31, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [7eaeae034c](https://linux-hardware.org/?probe=7eaeae034c) | Oct 29, 2021 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [6e1fbe4dde](https://linux-hardware.org/?probe=6e1fbe4dde) | Oct 27, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Dell          | Precision 7520              | Notebook    | [83df635945](https://linux-hardware.org/?probe=83df635945) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [4946a6a02c](https://linux-hardware.org/?probe=4946a6a02c) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [0ad429cea5](https://linux-hardware.org/?probe=0ad429cea5) | Oct 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [cd2454732b](https://linux-hardware.org/?probe=cd2454732b) | Oct 25, 2021 |
| HP            | G70                         | Notebook    | [68fb8430c2](https://linux-hardware.org/?probe=68fb8430c2) | Oct 24, 2021 |
| HP            | G70                         | Notebook    | [3e2c50a321](https://linux-hardware.org/?probe=3e2c50a321) | Oct 24, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [4ba408d68c](https://linux-hardware.org/?probe=4ba408d68c) | Oct 23, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [e82ee9096e](https://linux-hardware.org/?probe=e82ee9096e) | Oct 23, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [3e15c8708a](https://linux-hardware.org/?probe=3e15c8708a) | Oct 23, 2021 |
| Rockchip      | Unknown                     | Soc         | [e7c44d5f41](https://linux-hardware.org/?probe=e7c44d5f41) | Oct 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [27b0a66ceb](https://linux-hardware.org/?probe=27b0a66ceb) | Oct 20, 2021 |
| Lenovo        | ThinkPad L512 2598A59       | Notebook    | [0bc832bd49](https://linux-hardware.org/?probe=0bc832bd49) | Oct 19, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [34a5253469](https://linux-hardware.org/?probe=34a5253469) | Oct 16, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [2bc2b5c1d6](https://linux-hardware.org/?probe=2bc2b5c1d6) | Oct 15, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [b4660289b3](https://linux-hardware.org/?probe=b4660289b3) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| Dell          | Latitude E6440              | Notebook    | [383edb4c99](https://linux-hardware.org/?probe=383edb4c99) | Oct 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6c0867e544](https://linux-hardware.org/?probe=6c0867e544) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [b566b7f862](https://linux-hardware.org/?probe=b566b7f862) | Oct 13, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [a8e5248d3d](https://linux-hardware.org/?probe=a8e5248d3d) | Oct 13, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [26453872b1](https://linux-hardware.org/?probe=26453872b1) | Oct 12, 2021 |
| ASUSTek       | N43SL                       | Notebook    | [c5adc8860e](https://linux-hardware.org/?probe=c5adc8860e) | Oct 09, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [044c6efa0d](https://linux-hardware.org/?probe=044c6efa0d) | Oct 08, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [fe1c549ed6](https://linux-hardware.org/?probe=fe1c549ed6) | Oct 05, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [219e5cd0d5](https://linux-hardware.org/?probe=219e5cd0d5) | Oct 04, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [f0ff9a911e](https://linux-hardware.org/?probe=f0ff9a911e) | Oct 03, 2021 |
| Dell          | Latitude E6440              | Notebook    | [a8884539e7](https://linux-hardware.org/?probe=a8884539e7) | Oct 02, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b535b99341](https://linux-hardware.org/?probe=b535b99341) | Sep 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [f04c751d60](https://linux-hardware.org/?probe=f04c751d60) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5f6c245dc5](https://linux-hardware.org/?probe=5f6c245dc5) | Sep 28, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [5422d3bf1d](https://linux-hardware.org/?probe=5422d3bf1d) | Sep 27, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [060da3d3ab](https://linux-hardware.org/?probe=060da3d3ab) | Sep 26, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ed937ed1cd](https://linux-hardware.org/?probe=ed937ed1cd) | Sep 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2e1581c3b3](https://linux-hardware.org/?probe=2e1581c3b3) | Sep 24, 2021 |
| Entroware     | Aether                      | Notebook    | [c65a69857f](https://linux-hardware.org/?probe=c65a69857f) | Sep 22, 2021 |
| HP            | 8265                        | Desktop     | [f840aed42d](https://linux-hardware.org/?probe=f840aed42d) | Sep 21, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a5211dc1bb](https://linux-hardware.org/?probe=a5211dc1bb) | Sep 21, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [13298e0f6b](https://linux-hardware.org/?probe=13298e0f6b) | Sep 19, 2021 |
| HP            | 3397                        | Desktop     | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [3c40bbda61](https://linux-hardware.org/?probe=3c40bbda61) | Sep 18, 2021 |
| HP            | 1497                        | Desktop     | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASRock        | H110M-STX                   | Desktop     | [6bb90d3b07](https://linux-hardware.org/?probe=6bb90d3b07) | Sep 16, 2021 |
| Medion        | MS-7797                     | Desktop     | [f2f5579dc5](https://linux-hardware.org/?probe=f2f5579dc5) | Sep 15, 2021 |
| Medion        | MS-7797                     | Desktop     | [6ca6bee736](https://linux-hardware.org/?probe=6ca6bee736) | Sep 15, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | Notebook    | [6e8ca97f4b](https://linux-hardware.org/?probe=6e8ca97f4b) | Sep 14, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | Notebook    | [e0b0d2d509](https://linux-hardware.org/?probe=e0b0d2d509) | Sep 13, 2021 |
| Teclast       | F15S                        | Notebook    | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | Notebook    | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Lenovo        | ThinkPad T420 42361P0       | Notebook    | [24f3d09047](https://linux-hardware.org/?probe=24f3d09047) | Sep 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [6670bba1d8](https://linux-hardware.org/?probe=6670bba1d8) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | Notebook    | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | Notebook    | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Digibras      | NH4CU53                     | Notebook    | [5f2f500f7a](https://linux-hardware.org/?probe=5f2f500f7a) | Sep 10, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
| Intel         | DH67CL AAG10212-204         | Desktop     | [e9d68ab5e4](https://linux-hardware.org/?probe=e9d68ab5e4) | Sep 09, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [14109edfc9](https://linux-hardware.org/?probe=14109edfc9) | Sep 07, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [cb82d03efe](https://linux-hardware.org/?probe=cb82d03efe) | Sep 07, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [d05cb87743](https://linux-hardware.org/?probe=d05cb87743) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Acer          | Spin SP111-33               | Convertible | [2a5ddf7be8](https://linux-hardware.org/?probe=2a5ddf7be8) | Sep 05, 2021 |
| HP            | 3396                        | Desktop     | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | Notebook    | [54c321b6bd](https://linux-hardware.org/?probe=54c321b6bd) | Sep 04, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | Notebook    | [812cc9220c](https://linux-hardware.org/?probe=812cc9220c) | Sep 01, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [c594736488](https://linux-hardware.org/?probe=c594736488) | Aug 30, 2021 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [16250b0c12](https://linux-hardware.org/?probe=16250b0c12) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [41e440c2e5](https://linux-hardware.org/?probe=41e440c2e5) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e086d2eb61](https://linux-hardware.org/?probe=e086d2eb61) | Aug 29, 2021 |
| MSI           | 2A9C                        | Desktop     | [57601d98f3](https://linux-hardware.org/?probe=57601d98f3) | Aug 28, 2021 |
| Notebook      | NK50S5_SZ                   | Notebook    | [6cba599e57](https://linux-hardware.org/?probe=6cba599e57) | Aug 27, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c375ab72c5](https://linux-hardware.org/?probe=c375ab72c5) | Aug 25, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [d3e14ad15a](https://linux-hardware.org/?probe=d3e14ad15a) | Aug 25, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [b28b036f78](https://linux-hardware.org/?probe=b28b036f78) | Aug 22, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a1189f529](https://linux-hardware.org/?probe=1a1189f529) | Aug 21, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [19cfd7b8f5](https://linux-hardware.org/?probe=19cfd7b8f5) | Aug 21, 2021 |
| Packard Be... | EasyNote SL65               | Notebook    | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| GPD           | MicroPC                     | Notebook    | [7fa0c4e3c4](https://linux-hardware.org/?probe=7fa0c4e3c4) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | Notebook    | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [635d8e55e7](https://linux-hardware.org/?probe=635d8e55e7) | Aug 17, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| Acer          | Extensa 5630                | Notebook    | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| ASRock        | M3A785GMH/128M              | Desktop     | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| HP            | Notebook                    | Notebook    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| MSI           | X79A-GD45                   | Desktop     | [c5b78e1a01](https://linux-hardware.org/?probe=c5b78e1a01) | Aug 13, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [cfe37f86a3](https://linux-hardware.org/?probe=cfe37f86a3) | Aug 12, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6776a424d5](https://linux-hardware.org/?probe=6776a424d5) | Aug 11, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [bbfbd42562](https://linux-hardware.org/?probe=bbfbd42562) | Aug 07, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | Notebook    | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | Notebook    | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| Notebook      | N24_25GU                    | Notebook    | [2e67e53ad7](https://linux-hardware.org/?probe=2e67e53ad7) | Aug 05, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASRock        | Q1900M                      | Desktop     | [700f4a0ca1](https://linux-hardware.org/?probe=700f4a0ca1) | Aug 02, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [e706b18dd8](https://linux-hardware.org/?probe=e706b18dd8) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | Notebook    | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Dell          | Vostro 1520                 | Notebook    | [af01145277](https://linux-hardware.org/?probe=af01145277) | Jul 28, 2021 |
| Clevo         | M720R                       | Notebook    | [a52f0f2d7c](https://linux-hardware.org/?probe=a52f0f2d7c) | Jul 27, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| HP            | Laptop 15z-ef1xxx           | Notebook    | [d72c30940e](https://linux-hardware.org/?probe=d72c30940e) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [e8e43c77ca](https://linux-hardware.org/?probe=e8e43c77ca) | Jul 23, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [6dcb19e468](https://linux-hardware.org/?probe=6dcb19e468) | Jul 23, 2021 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [db7104ee10](https://linux-hardware.org/?probe=db7104ee10) | Jul 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [647fe69592](https://linux-hardware.org/?probe=647fe69592) | Jul 22, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [8b355a2630](https://linux-hardware.org/?probe=8b355a2630) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| System76      | Galago Pro                  | Notebook    | [c74e5f1cf9](https://linux-hardware.org/?probe=c74e5f1cf9) | Jul 17, 2021 |
| MSI           | H61M-E33                    | Desktop     | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [14ce128e1a](https://linux-hardware.org/?probe=14ce128e1a) | Jul 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f656b6c149](https://linux-hardware.org/?probe=f656b6c149) | Jul 16, 2021 |
| Dell          | Studio 1558                 | Notebook    | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | Notebook    | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [6001052e23](https://linux-hardware.org/?probe=6001052e23) | Jul 15, 2021 |
| Toshiba       | Satellite C850-BMK          | Notebook    | [d92515e12e](https://linux-hardware.org/?probe=d92515e12e) | Jul 14, 2021 |
| HP            | Pavilion 17                 | Notebook    | [628e42055f](https://linux-hardware.org/?probe=628e42055f) | Jul 12, 2021 |
| Lenovo        | Tilapia CRB                 | Desktop     | [da1f0d65ec](https://linux-hardware.org/?probe=da1f0d65ec) | Jul 12, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [d49086311b](https://linux-hardware.org/?probe=d49086311b) | Jul 12, 2021 |
| Fujitsu       | LIFEBOOK E5511              | Notebook    | [4c13b21a8c](https://linux-hardware.org/?probe=4c13b21a8c) | Jul 10, 2021 |
| Unknown       | TB-4000                     | Desktop     | [fb3e1984b0](https://linux-hardware.org/?probe=fb3e1984b0) | Jul 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [ae14beb6fd](https://linux-hardware.org/?probe=ae14beb6fd) | Jul 09, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [7adcf7dc7c](https://linux-hardware.org/?probe=7adcf7dc7c) | Jul 09, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [ebd157141b](https://linux-hardware.org/?probe=ebd157141b) | Jul 08, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [4b2c3ea073](https://linux-hardware.org/?probe=4b2c3ea073) | Jul 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cce6c3a767](https://linux-hardware.org/?probe=cce6c3a767) | Jul 06, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b6c1f36f1f](https://linux-hardware.org/?probe=b6c1f36f1f) | Jul 04, 2021 |
| ASUSTek       | Z170-AR                     | Desktop     | [37343856a5](https://linux-hardware.org/?probe=37343856a5) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | Notebook    | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [9bb3c8dbe9](https://linux-hardware.org/?probe=9bb3c8dbe9) | Jul 02, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [820725cbbd](https://linux-hardware.org/?probe=820725cbbd) | Jun 30, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [dcf91492a2](https://linux-hardware.org/?probe=dcf91492a2) | Jun 29, 2021 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [55bdc0f976](https://linux-hardware.org/?probe=55bdc0f976) | Jun 28, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| HP            | Pavilion g6                 | Notebook    | [3cfb1f50dc](https://linux-hardware.org/?probe=3cfb1f50dc) | Jun 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [772a91651b](https://linux-hardware.org/?probe=772a91651b) | Jun 26, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [4b13ffc6ce](https://linux-hardware.org/?probe=4b13ffc6ce) | Jun 26, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [4fdc27b018](https://linux-hardware.org/?probe=4fdc27b018) | Jun 25, 2021 |
| HP            | Pavilion dv7                | Notebook    | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [7fba4b1b78](https://linux-hardware.org/?probe=7fba4b1b78) | Jun 23, 2021 |
| Acer          | V7-710                      | Notebook    | [fe9a84f137](https://linux-hardware.org/?probe=fe9a84f137) | Jun 23, 2021 |
| Dell          | Latitude E6400              | Notebook    | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| HP            | 1495                        | Desktop     | [03ab704550](https://linux-hardware.org/?probe=03ab704550) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [c71b41c7a8](https://linux-hardware.org/?probe=c71b41c7a8) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [f39e5005bd](https://linux-hardware.org/?probe=f39e5005bd) | Jun 20, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [7bf43ae0d0](https://linux-hardware.org/?probe=7bf43ae0d0) | Jun 19, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [9a4e288f49](https://linux-hardware.org/?probe=9a4e288f49) | Jun 19, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d41809b4c9](https://linux-hardware.org/?probe=d41809b4c9) | Jun 19, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [b10313d89f](https://linux-hardware.org/?probe=b10313d89f) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [32538ae4b8](https://linux-hardware.org/?probe=32538ae4b8) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [882855d037](https://linux-hardware.org/?probe=882855d037) | Jun 17, 2021 |
| eMachines     | EL1352                      | Desktop     | [f175ae71f2](https://linux-hardware.org/?probe=f175ae71f2) | Jun 16, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [0616fdb086](https://linux-hardware.org/?probe=0616fdb086) | Jun 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [3d47d96665](https://linux-hardware.org/?probe=3d47d96665) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c9bea47caa](https://linux-hardware.org/?probe=c9bea47caa) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c9c757474a](https://linux-hardware.org/?probe=c9c757474a) | Jun 12, 2021 |
| Dell          | Latitude D520               | Notebook    | [5f08e309ae](https://linux-hardware.org/?probe=5f08e309ae) | Jun 11, 2021 |
| Dell          | Latitude E6510              | Notebook    | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| Acer          | Aspire 7730G                | Notebook    | [4d314b5039](https://linux-hardware.org/?probe=4d314b5039) | Jun 10, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23dc47130c](https://linux-hardware.org/?probe=23dc47130c) | Jun 10, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [1ab4ff25ab](https://linux-hardware.org/?probe=1ab4ff25ab) | Jun 10, 2021 |
| HP            | Pavilion 17                 | Notebook    | [b234c99d47](https://linux-hardware.org/?probe=b234c99d47) | Jun 08, 2021 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [95708a9a82](https://linux-hardware.org/?probe=95708a9a82) | Jun 07, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [865f37b773](https://linux-hardware.org/?probe=865f37b773) | Jun 06, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b5aa561890](https://linux-hardware.org/?probe=b5aa561890) | Jun 05, 2021 |
| ASUSTek       | K73SJ                       | Notebook    | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | Notebook    | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [af16143ad8](https://linux-hardware.org/?probe=af16143ad8) | Jun 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [d732611ebb](https://linux-hardware.org/?probe=d732611ebb) | Jun 02, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [3f2f789273](https://linux-hardware.org/?probe=3f2f789273) | Jun 01, 2021 |
| HP            | Pavilion g6                 | Notebook    | [0245da9040](https://linux-hardware.org/?probe=0245da9040) | May 31, 2021 |
| Lenovo        | 3102 NOK                    | Desktop     | [3d1a8cffc3](https://linux-hardware.org/?probe=3d1a8cffc3) | May 31, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [913ea68973](https://linux-hardware.org/?probe=913ea68973) | May 31, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23a20d91ef](https://linux-hardware.org/?probe=23a20d91ef) | May 31, 2021 |
| Dell          | 0PC5F7 A02                  | Desktop     | [86611a5efe](https://linux-hardware.org/?probe=86611a5efe) | May 31, 2021 |
| Inventec      | Z CLASS A02                 | Desktop     | [7fc4815cbd](https://linux-hardware.org/?probe=7fc4815cbd) | May 29, 2021 |
| ASUSTek       | GL12CX                      | Desktop     | [d95dd524bc](https://linux-hardware.org/?probe=d95dd524bc) | May 28, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [cf31dd498a](https://linux-hardware.org/?probe=cf31dd498a) | May 26, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [8e44c9edaf](https://linux-hardware.org/?probe=8e44c9edaf) | May 26, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [3a2f765228](https://linux-hardware.org/?probe=3a2f765228) | May 26, 2021 |
| HP            | Pavilion                    | Notebook    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| HP            | 635                         | Notebook    | [acff9705ee](https://linux-hardware.org/?probe=acff9705ee) | May 26, 2021 |
| Dell          | G7 7500                     | Notebook    | [65cb46fe46](https://linux-hardware.org/?probe=65cb46fe46) | May 25, 2021 |
| HP            | 635                         | Notebook    | [b96dfdc2fa](https://linux-hardware.org/?probe=b96dfdc2fa) | May 24, 2021 |
| Dell          | Precision M4800             | Notebook    | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a9539e0359](https://linux-hardware.org/?probe=a9539e0359) | May 24, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [74e472db93](https://linux-hardware.org/?probe=74e472db93) | May 23, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | Notebook    | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [d328ce9f69](https://linux-hardware.org/?probe=d328ce9f69) | May 18, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [6b9dbebe2f](https://linux-hardware.org/?probe=6b9dbebe2f) | May 18, 2021 |
| Acer          | C-AXC-605                   | Desktop     | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [c56840df98](https://linux-hardware.org/?probe=c56840df98) | May 17, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f1592b156b](https://linux-hardware.org/?probe=f1592b156b) | May 16, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [dec38c20c6](https://linux-hardware.org/?probe=dec38c20c6) | May 15, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | Notebook    | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | Notebook    | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [ea47dfa580](https://linux-hardware.org/?probe=ea47dfa580) | May 13, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [bbefe7273f](https://linux-hardware.org/?probe=bbefe7273f) | May 13, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [e39d859a43](https://linux-hardware.org/?probe=e39d859a43) | May 12, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [6b07e6e09b](https://linux-hardware.org/?probe=6b07e6e09b) | May 12, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [2a8297469f](https://linux-hardware.org/?probe=2a8297469f) | May 11, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [33a95ff348](https://linux-hardware.org/?probe=33a95ff348) | May 10, 2021 |
| Dell          | Precision M4500             | Notebook    | [407d9c0748](https://linux-hardware.org/?probe=407d9c0748) | May 10, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [40a8a145e6](https://linux-hardware.org/?probe=40a8a145e6) | May 10, 2021 |
| Dell          | G7 7588                     | Notebook    | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | Notebook    | [d0fb43caf0](https://linux-hardware.org/?probe=d0fb43caf0) | May 08, 2021 |
| HP            | Pavilion 17                 | Notebook    | [32ea31fd5f](https://linux-hardware.org/?probe=32ea31fd5f) | May 07, 2021 |
| Cube          | i18-L                       | Notebook    | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [714a70d40a](https://linux-hardware.org/?probe=714a70d40a) | May 07, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [9db6c930c1](https://linux-hardware.org/?probe=9db6c930c1) | May 06, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [efc8ac4c79](https://linux-hardware.org/?probe=efc8ac4c79) | May 06, 2021 |
| HP            | Pavilion                    | Notebook    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_MATE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu MATE 20.04 | 623       | 47.09%  |
| Ubuntu MATE 18.04 | 262       | 19.8%   |
| Ubuntu MATE 22.04 | 183       | 13.83%  |
| Ubuntu MATE 20.10 | 53        | 4.01%   |
| Ubuntu MATE 19.10 | 48        | 3.63%   |
| Ubuntu MATE 21.10 | 45        | 3.4%    |
| Ubuntu MATE 21.04 | 42        | 3.17%   |
| Ubuntu MATE 22.10 | 29        | 2.19%   |
| Ubuntu MATE 16.04 | 21        | 1.59%   |
| Ubuntu MATE       | 6         | 0.45%   |
| Ubuntu MATE 23.04 | 3         | 0.23%   |
| Ubuntu MATE 19.04 | 2         | 0.15%   |
| Ubuntu MATE 18.10 | 2         | 0.15%   |
| Ubuntu MATE 17.04 | 2         | 0.15%   |
| Ubuntu MATE 16.10 | 1         | 0.08%   |
| Ubuntu MATE 15.04 | 1         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Ubuntu MATE | 1275      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 56        | 3.81%   |
| 5.4.0-48-generic   | 44        | 2.99%   |
| 5.4.0-52-generic   | 35        | 2.38%   |
| 5.4.0-47-generic   | 31        | 2.11%   |
| 5.15.0-56-generic  | 30        | 2.04%   |
| 5.4.0-65-generic   | 23        | 1.56%   |
| 5.4.0-58-generic   | 19        | 1.29%   |
| 5.4.0-40-generic   | 18        | 1.22%   |
| 5.15.0-47-generic  | 18        | 1.22%   |
| 4.15.0-163-generic | 17        | 1.16%   |
| 5.4.0-45-generic   | 16        | 1.09%   |
| 5.3.0-46-generic   | 16        | 1.09%   |
| 5.3.0-40-generic   | 16        | 1.09%   |
| 5.8.0-48-generic   | 15        | 1.02%   |
| 5.15.0-48-generic  | 15        | 1.02%   |
| 5.15.0-46-generic  | 14        | 0.95%   |
| 5.4.0-94-generic   | 13        | 0.88%   |
| 5.3.0-42-generic   | 13        | 0.88%   |
| 5.15.0-58-generic  | 13        | 0.88%   |
| 5.11.0-40-generic  | 13        | 0.88%   |
| 5.8.0-50-generic   | 12        | 0.82%   |
| 5.4.0-81-generic   | 12        | 0.82%   |
| 5.4.0-56-generic   | 12        | 0.82%   |
| 5.15.0-52-generic  | 12        | 0.82%   |
| 5.15.0-43-generic  | 12        | 0.82%   |
| 5.4.0-26-generic   | 11        | 0.75%   |
| 5.15.0-60-generic  | 11        | 0.75%   |
| 5.15.0-40-generic  | 11        | 0.75%   |
| 5.13.0-30-generic  | 11        | 0.75%   |
| 5.4.0-89-generic   | 10        | 0.68%   |
| 5.4.0-74-generic   | 10        | 0.68%   |
| 5.4.0-66-generic   | 10        | 0.68%   |
| 5.4.0-31-generic   | 10        | 0.68%   |
| 5.4.0-29-generic   | 10        | 0.68%   |
| 5.3.0-51-generic   | 10        | 0.68%   |
| 5.3.0-28-generic   | 10        | 0.68%   |
| 5.13.0-39-generic  | 10        | 0.68%   |
| 5.8.0-59-generic   | 9         | 0.61%   |
| 5.4.0-80-generic   | 9         | 0.61%   |
| 5.4.0-70-generic   | 9         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 511       | 38.08%  |
| 5.15.0  | 194       | 14.46%  |
| 5.3.0   | 118       | 8.79%   |
| 5.8.0   | 105       | 7.82%   |
| 4.15.0  | 99        | 7.38%   |
| 5.11.0  | 96        | 7.15%   |
| 5.13.0  | 88        | 6.56%   |
| 5.19.0  | 30        | 2.24%   |
| 5.0.0   | 15        | 1.12%   |
| 4.4.0   | 9         | 0.67%   |
| 5.14.0  | 8         | 0.6%    |
| 5.17.0  | 4         | 0.3%    |
| 5.10.27 | 4         | 0.3%    |
| 4.9.277 | 4         | 0.3%    |
| 4.18.0  | 4         | 0.3%    |
| 5.18.0  | 3         | 0.22%   |
| 4.10.0  | 3         | 0.22%   |
| 6.1.12  | 2         | 0.15%   |
| 5.4.2   | 2         | 0.15%   |
| 5.10.5  | 2         | 0.15%   |
| 5.10.0  | 2         | 0.15%   |
| 4.4.154 | 2         | 0.15%   |
| 6.2.0   | 1         | 0.07%   |
| 6.1.8   | 1         | 0.07%   |
| 6.1.11  | 1         | 0.07%   |
| 6.0.8   | 1         | 0.07%   |
| 5.9.3   | 1         | 0.07%   |
| 5.9.1   | 1         | 0.07%   |
| 5.9.0   | 1         | 0.07%   |
| 5.8.17  | 1         | 0.07%   |
| 5.8.16  | 1         | 0.07%   |
| 5.7.6   | 1         | 0.07%   |
| 5.7.0   | 1         | 0.07%   |
| 5.6.7   | 1         | 0.07%   |
| 5.6.5   | 1         | 0.07%   |
| 5.5.5   | 1         | 0.07%   |
| 5.5.11  | 1         | 0.07%   |
| 5.4.167 | 1         | 0.07%   |
| 5.17.1  | 1         | 0.07%   |
| 5.16.0  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 514       | 38.33%  |
| 5.15    | 199       | 14.84%  |
| 5.3     | 118       | 8.8%    |
| 5.8     | 107       | 7.98%   |
| 4.15    | 99        | 7.38%   |
| 5.11    | 96        | 7.16%   |
| 5.13    | 88        | 6.56%   |
| 5.19    | 30        | 2.24%   |
| 5.0     | 15        | 1.12%   |
| 4.4     | 12        | 0.89%   |
| 5.14    | 8         | 0.6%    |
| 5.10    | 8         | 0.6%    |
| 4.9     | 6         | 0.45%   |
| 5.17    | 5         | 0.37%   |
| 6.1     | 4         | 0.3%    |
| 4.18    | 4         | 0.3%    |
| 5.9     | 3         | 0.22%   |
| 5.18    | 3         | 0.22%   |
| 4.14    | 3         | 0.22%   |
| 4.10    | 3         | 0.22%   |
| 5.7     | 2         | 0.15%   |
| 5.6     | 2         | 0.15%   |
| 5.5     | 2         | 0.15%   |
| 5.12    | 2         | 0.15%   |
| 6.2     | 1         | 0.07%   |
| 6.0     | 1         | 0.07%   |
| 5.16    | 1         | 0.07%   |
| 4.8     | 1         | 0.07%   |
| 4.13    | 1         | 0.07%   |
| 3.19    | 1         | 0.07%   |
| 3.16    | 1         | 0.07%   |
| 3.14    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1147      | 89.96%  |
| i686    | 73        | 5.73%   |
| aarch64 | 45        | 3.53%   |
| armv7l  | 9         | 0.71%   |
| ppc     | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 1247      | 97.73%  |
| Cinnamon   | 7         | 0.55%   |
| KDE5       | 6         | 0.47%   |
| X-Cinnamon | 5         | 0.39%   |
| GNOME      | 5         | 0.39%   |
| Trinity    | 2         | 0.16%   |
| Budgie     | 2         | 0.16%   |
| XFCE       | 1         | 0.08%   |
| i3         | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1238      | 96.95%  |
| Tty     | 25        | 1.96%   |
| Wayland | 14        | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 487       | 36.81%  |
| Unknown | 449       | 33.94%  |
| TDM     | 309       | 23.36%  |
| GDM     | 36        | 2.72%   |
| GDM3    | 31        | 2.34%   |
| SDDM    | 5         | 0.38%   |
| SLiM    | 3         | 0.23%   |
| LXDM    | 3         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 430       | 33.39%  |
| pt_BR   | 114       | 8.85%   |
| de_DE   | 113       | 8.77%   |
| fr_FR   | 109       | 8.46%   |
| en_GB   | 64        | 4.97%   |
| it_IT   | 56        | 4.35%   |
| es_ES   | 39        | 3.03%   |
| ru_RU   | 38        | 2.95%   |
| Unknown | 35        | 2.72%   |
| el_GR   | 34        | 2.64%   |
| en_CA   | 29        | 2.25%   |
| C       | 29        | 2.25%   |
| en_AU   | 22        | 1.71%   |
| es_AR   | 15        | 1.16%   |
| pl_PL   | 14        | 1.09%   |
| hu_HU   | 11        | 0.85%   |
| nl_NL   | 9         | 0.7%    |
| en_IN   | 9         | 0.7%    |
| sv_SE   | 8         | 0.62%   |
| de_CH   | 8         | 0.62%   |
| fi_FI   | 7         | 0.54%   |
| es_PE   | 7         | 0.54%   |
| ru_UA   | 6         | 0.47%   |
| cs_CZ   | 6         | 0.47%   |
| es_VE   | 4         | 0.31%   |
| es_MX   | 4         | 0.31%   |
| es_CL   | 4         | 0.31%   |
| en_PH   | 4         | 0.31%   |
| en_IL   | 4         | 0.31%   |
| de_AT   | 4         | 0.31%   |
| pt_PT   | 3         | 0.23%   |
| nl_BE   | 3         | 0.23%   |
| hr_HR   | 3         | 0.23%   |
| fr_CA   | 3         | 0.23%   |
| da_DK   | 3         | 0.23%   |
| ca_ES   | 3         | 0.23%   |
| zh_TW   | 2         | 0.16%   |
| zh_CN   | 2         | 0.16%   |
| ja_JP   | 2         | 0.16%   |
| fr_BE   | 2         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 726       | 55.93%  |
| EFI  | 572       | 44.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1168      | 91.18%  |
| Overlay | 49        | 3.83%   |
| Btrfs   | 21        | 1.64%   |
| Zfs     | 17        | 1.33%   |
| Unknown | 9         | 0.7%    |
| Xfs     | 8         | 0.62%   |
| Ext3    | 3         | 0.23%   |
| Jfs     | 2         | 0.16%   |
| Aufs    | 2         | 0.16%   |
| ExX4    | 1         | 0.08%   |
| Ext2    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 552       | 42.4%   |
| GPT     | 490       | 37.63%  |
| MBR     | 260       | 19.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1105      | 85.59%  |
| Yes       | 186       | 14.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 862       | 66.56%  |
| Yes       | 433       | 33.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 213       | 16.71%  |
| ASUSTek Computer        | 197       | 15.45%  |
| Dell                    | 175       | 13.73%  |
| Lenovo                  | 152       | 11.92%  |
| Gigabyte Technology     | 70        | 5.49%   |
| MSI                     | 64        | 5.02%   |
| Acer                    | 54        | 4.24%   |
| Raspberry Pi Foundation | 38        | 2.98%   |
| ASRock                  | 35        | 2.75%   |
| Intel                   | 34        | 2.67%   |
| Toshiba                 | 25        | 1.96%   |
| Unknown                 | 16        | 1.25%   |
| Sony                    | 15        | 1.18%   |
| Apple                   | 14        | 1.1%    |
| Samsung Electronics     | 13        | 1.02%   |
| Fujitsu                 | 11        | 0.86%   |
| Hardkernel              | 10        | 0.78%   |
| Medion                  | 9         | 0.71%   |
| Notebook                | 7         | 0.55%   |
| Supermicro              | 6         | 0.47%   |
| Packard Bell            | 6         | 0.47%   |
| Pegatron                | 5         | 0.39%   |
| Positivo                | 4         | 0.31%   |
| Fujitsu Siemens         | 4         | 0.31%   |
| ECS                     | 4         | 0.31%   |
| Biostar                 | 4         | 0.31%   |
| TUXEDO                  | 3         | 0.24%   |
| TrekStor                | 3         | 0.24%   |
| Quanta                  | 3         | 0.24%   |
| LG Electronics          | 3         | 0.24%   |
| Google                  | 3         | 0.24%   |
| eMachines               | 3         | 0.24%   |
| Clevo                   | 3         | 0.24%   |
| Chuwi                   | 3         | 0.24%   |
| AZW                     | 3         | 0.24%   |
| Wortmann AG             | 2         | 0.16%   |
| TYAN Computer           | 2         | 0.16%   |
| System76                | 2         | 0.16%   |
| Semp Toshiba            | 2         | 0.16%   |
| Rockchip                | 2         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 26        | 2.04%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 10        | 0.78%   |
| HP Compaq Elite 8300 SFF           | 10        | 0.78%   |
| ASUS All Series                    | 10        | 0.78%   |
| RPi Raspberry Pi 4 Model B Rev 1.2 | 8         | 0.63%   |
| RPi Raspberry Pi                   | 8         | 0.63%   |
| HP ProDesk 600 G1 SFF              | 8         | 0.63%   |
| HP Compaq 6005 Pro SFF PC          | 8         | 0.63%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 7         | 0.55%   |
| HP Pavilion g6                     | 6         | 0.47%   |
| Hardkernel ODROID-N2Plus           | 6         | 0.47%   |
| Dell Latitude E6410                | 6         | 0.47%   |
| HP Pavilion dv7                    | 5         | 0.39%   |
| Dell OptiPlex 3010                 | 5         | 0.39%   |
| Dell Latitude E6420                | 5         | 0.39%   |
| MSI MS-7817                        | 4         | 0.31%   |
| Lenovo IdeaPad 3 15IIL05 81WE      | 4         | 0.31%   |
| HP Notebook                        | 4         | 0.31%   |
| HP Compaq 6200 Pro SFF PC          | 4         | 0.31%   |
| Dell OptiPlex GX520                | 4         | 0.31%   |
| Dell OptiPlex 755                  | 4         | 0.31%   |
| Dell OptiPlex 390                  | 4         | 0.31%   |
| Dell OptiPlex 360                  | 4         | 0.31%   |
| ASUS M5A97 R2.0                    | 4         | 0.31%   |
| ASRock B450M Pro4                  | 4         | 0.31%   |
| TrekStor Surfbook A13B             | 3         | 0.24%   |
| RPi Raspberry Pi 3 Model B Rev 1.2 | 3         | 0.24%   |
| HP ProLiant MicroServer            | 3         | 0.24%   |
| HP Compaq 8000 Elite SFF PC        | 3         | 0.24%   |
| HP 15                              | 3         | 0.24%   |
| Gigabyte B450M DS3H                | 3         | 0.24%   |
| Dell Precision M4800               | 3         | 0.24%   |
| Dell OptiPlex GX620                | 3         | 0.24%   |
| Dell OptiPlex 330                  | 3         | 0.24%   |
| Dell Latitude E6500                | 3         | 0.24%   |
| ASUS M5A78L-M/USB3                 | 3         | 0.24%   |
| Acer Aspire ES1-523                | 3         | 0.24%   |
| Toshiba Satellite C660             | 2         | 0.16%   |
| Toshiba Satellite A200             | 2         | 0.16%   |
| Supermicro H8DG6/H8DGi             | 2         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 70        | 5.49%   |
| Dell OptiPlex            | 49        | 3.84%   |
| HP Compaq                | 43        | 3.37%   |
| Dell Latitude            | 42        | 3.29%   |
| RPi Raspberry            | 38        | 2.98%   |
| HP Pavilion              | 38        | 2.98%   |
| Acer Aspire              | 37        | 2.9%    |
| Lenovo IdeaPad           | 29        | 2.27%   |
| Dell Precision           | 27        | 2.12%   |
| Unknown                  | 26        | 2.04%   |
| HP EliteBook             | 24        | 1.88%   |
| Dell Inspiron            | 24        | 1.88%   |
| Toshiba Satellite        | 23        | 1.8%    |
| ASUS PRIME               | 20        | 1.57%   |
| Lenovo ThinkCentre       | 16        | 1.25%   |
| ASUS ROG                 | 14        | 1.1%    |
| HP ProBook               | 13        | 1.02%   |
| HP ProDesk               | 10        | 0.78%   |
| Dell XPS                 | 10        | 0.78%   |
| ASUS All                 | 10        | 0.78%   |
| Fujitsu LIFEBOOK         | 9         | 0.71%   |
| Dell Vostro              | 9         | 0.71%   |
| HP Laptop                | 8         | 0.63%   |
| ASUS VivoBook            | 8         | 0.63%   |
| HP ZBook                 | 7         | 0.55%   |
| ASUS TUF                 | 7         | 0.55%   |
| Lenovo ThinkBook         | 6         | 0.47%   |
| HP ProLiant              | 6         | 0.47%   |
| HP 250                   | 6         | 0.47%   |
| Hardkernel ODROID-N2Plus | 6         | 0.47%   |
| ASUS M5A97               | 6         | 0.47%   |
| ASUS M5A78L-M            | 6         | 0.47%   |
| Packard Bell EasyNote    | 5         | 0.39%   |
| HP ENVY                  | 5         | 0.39%   |
| HP EliteDesk             | 5         | 0.39%   |
| Acer TravelMate          | 5         | 0.39%   |
| MSI MS-7817              | 4         | 0.31%   |
| Lenovo IdeaPadFlex       | 4         | 0.31%   |
| HP Stream                | 4         | 0.31%   |
| HP Notebook              | 4         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 124       | 9.73%   |
| 2012    | 116       | 9.1%    |
| 2020    | 110       | 8.63%   |
| 2018    | 106       | 8.31%   |
| 2013    | 96        | 7.53%   |
| 2019    | 79        | 6.2%    |
| 2010    | 75        | 5.88%   |
| 2014    | 72        | 5.65%   |
| 2008    | 70        | 5.49%   |
| 2009    | 66        | 5.18%   |
| 2021    | 64        | 5.02%   |
| 2017    | 62        | 4.86%   |
| 2015    | 58        | 4.55%   |
| 2016    | 53        | 4.16%   |
| 2007    | 37        | 2.9%    |
| Unknown | 37        | 2.9%    |
| 2006    | 22        | 1.73%   |
| 2022    | 13        | 1.02%   |
| 2005    | 12        | 0.94%   |
| 2023    | 1         | 0.08%   |
| 2004    | 1         | 0.08%   |
| 2003    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 636       | 49.88%  |
| Desktop        | 506       | 39.69%  |
| System on chip | 52        | 4.08%   |
| Mini pc        | 25        | 1.96%   |
| Convertible    | 17        | 1.33%   |
| All in one     | 15        | 1.18%   |
| Server         | 15        | 1.18%   |
| Tablet         | 9         | 0.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1198      | 93.52%  |
| Enabled  | 83        | 6.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1271      | 99.69%  |
| Yes  | 4         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 343       | 26.63%  |
| 4.01-8.0        | 259       | 20.11%  |
| 8.01-16.0       | 200       | 15.53%  |
| 16.01-24.0      | 191       | 14.83%  |
| 32.01-64.0      | 101       | 7.84%   |
| 1.01-2.0        | 71        | 5.51%   |
| 64.01-256.0     | 52        | 4.04%   |
| 2.01-3.0        | 31        | 2.41%   |
| 24.01-32.0      | 19        | 1.48%   |
| 0.51-1.0        | 19        | 1.48%   |
| More than 256.0 | 1         | 0.08%   |
| 0.01-0.5        | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 485       | 35.3%   |
| 2.01-3.0   | 305       | 22.2%   |
| 0.51-1.0   | 193       | 14.05%  |
| 4.01-8.0   | 159       | 11.57%  |
| 3.01-4.0   | 152       | 11.06%  |
| 8.01-16.0  | 42        | 3.06%   |
| 0.01-0.5   | 21        | 1.53%   |
| 24.01-32.0 | 8         | 0.58%   |
| 16.01-24.0 | 5         | 0.36%   |
| 32.01-64.0 | 4         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 795       | 60.83%  |
| 2      | 323       | 24.71%  |
| 3      | 98        | 7.5%    |
| 4      | 42        | 3.21%   |
| 5      | 15        | 1.15%   |
| 6      | 10        | 0.77%   |
| 0      | 8         | 0.61%   |
| 7      | 6         | 0.46%   |
| 10     | 3         | 0.23%   |
| 11     | 2         | 0.15%   |
| 8      | 2         | 0.15%   |
| 20     | 1         | 0.08%   |
| 12     | 1         | 0.08%   |
| 9      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 662       | 51.52%  |
| Yes       | 623       | 48.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1112      | 87.15%  |
| No        | 164       | 12.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 879       | 68.4%   |
| No        | 406       | 31.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 644       | 50.16%  |
| No        | 640       | 49.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 178       | 13.87%  |
| Germany     | 142       | 11.07%  |
| Brazil      | 133       | 10.37%  |
| France      | 118       | 9.2%    |
| Italy       | 71        | 5.53%   |
| UK          | 63        | 4.91%   |
| Russia      | 62        | 4.83%   |
| Spain       | 56        | 4.36%   |
| Greece      | 41        | 3.2%    |
| Canada      | 30        | 2.34%   |
| Australia   | 23        | 1.79%   |
| Netherlands | 20        | 1.56%   |
| Argentina   | 20        | 1.56%   |
| Switzerland | 17        | 1.33%   |
| Hungary     | 17        | 1.33%   |
| Ukraine     | 16        | 1.25%   |
| Poland      | 15        | 1.17%   |
| Belgium     | 15        | 1.17%   |
| Sweden      | 13        | 1.01%   |
| India       | 13        | 1.01%   |
| Finland     | 13        | 1.01%   |
| Turkey      | 12        | 0.94%   |
| Austria     | 12        | 0.94%   |
| Czechia     | 11        | 0.86%   |
| Romania     | 9         | 0.7%    |
| Norway      | 9         | 0.7%    |
| Mexico      | 9         | 0.7%    |
| Portugal    | 8         | 0.62%   |
| Indonesia   | 8         | 0.62%   |
| Peru        | 7         | 0.55%   |
| Chile       | 7         | 0.55%   |
| Thailand    | 6         | 0.47%   |
| Denmark     | 6         | 0.47%   |
| Croatia     | 6         | 0.47%   |
| Venezuela   | 5         | 0.39%   |
| Taiwan      | 5         | 0.39%   |
| Philippines | 4         | 0.31%   |
| Japan       | 4         | 0.31%   |
| Israel      | 4         | 0.31%   |
| Estonia     | 4         | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Sao Paulo        | 76        | 5.63%   |
| Paris            | 25        | 1.85%   |
| Moscow           | 21        | 1.56%   |
| Thessaloniki     | 19        | 1.41%   |
| Berlin           | 17        | 1.26%   |
| Athens           | 17        | 1.26%   |
| Rome             | 11        | 0.81%   |
| St Petersburg    | 9         | 0.67%   |
| Madrid           | 8         | 0.59%   |
| Budapest         | 8         | 0.59%   |
| Melbourne        | 7         | 0.52%   |
| Zurich           | 6         | 0.44%   |
| Manchester       | 6         | 0.44%   |
| Kyiv             | 6         | 0.44%   |
| Hamburg          | 6         | 0.44%   |
| Amsterdam        | 6         | 0.44%   |
| Vienna           | 5         | 0.37%   |
| Rio de Janeiro   | 5         | 0.37%   |
| Munich           | 5         | 0.37%   |
| Montpellier      | 5         | 0.37%   |
| Mannheim         | 5         | 0.37%   |
| Los Angeles      | 5         | 0.37%   |
| Helsinki         | 5         | 0.37%   |
| Cologne          | 5         | 0.37%   |
| Barcelona        | 5         | 0.37%   |
| Southampton      | 4         | 0.3%    |
| Perth            | 4         | 0.3%    |
| Milan            | 4         | 0.3%    |
| Genoa            | 4         | 0.3%    |
| Essen            | 4         | 0.3%    |
| Ely              | 4         | 0.3%    |
| Cleveland        | 4         | 0.3%    |
| Bucharest        | 4         | 0.3%    |
| Brisbane         | 4         | 0.3%    |
| Bengaluru        | 4         | 0.3%    |
| Zagreb           | 3         | 0.22%   |
| Windsor          | 3         | 0.22%   |
| West Stockbridge | 3         | 0.22%   |
| Vancouver        | 3         | 0.22%   |
| Toronto          | 3         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 303       | 482    | 16.69%  |
| WDC                       | 292       | 430    | 16.08%  |
| Samsung Electronics       | 267       | 396    | 14.7%   |
| Toshiba                   | 118       | 167    | 6.5%    |
| Unknown                   | 114       | 150    | 6.28%   |
| Kingston                  | 104       | 128    | 5.73%   |
| SanDisk                   | 81        | 96     | 4.46%   |
| Hitachi                   | 71        | 85     | 3.91%   |
| Crucial                   | 66        | 93     | 3.63%   |
| Intel                     | 40        | 50     | 2.2%    |
| SK hynix                  | 36        | 46     | 1.98%   |
| A-DATA Technology         | 25        | 26     | 1.38%   |
| HGST                      | 19        | 26     | 1.05%   |
| China                     | 18        | 22     | 0.99%   |
| Fujitsu                   | 16        | 17     | 0.88%   |
| Phison                    | 14        | 15     | 0.77%   |
| PNY                       | 13        | 14     | 0.72%   |
| Micron Technology         | 12        | 13     | 0.66%   |
| KIOXIA                    | 11        | 12     | 0.61%   |
| SPCC                      | 8         | 14     | 0.44%   |
| Patriot                   | 8         | 10     | 0.44%   |
| Intenso                   | 8         | 11     | 0.44%   |
| Silicon Motion            | 7         | 8      | 0.39%   |
| Maxtor                    | 7         | 12     | 0.39%   |
| JMicron Technology        | 7         | 10     | 0.39%   |
| Corsair                   | 7         | 8      | 0.39%   |
| LITEON                    | 6         | 7      | 0.33%   |
| Transcend                 | 5         | 8      | 0.28%   |
| LITEONIT                  | 5         | 6      | 0.28%   |
| KingSpec                  | 5         | 6      | 0.28%   |
| Hewlett-Packard           | 5         | 6      | 0.28%   |
| Apacer                    | 5         | 6      | 0.28%   |
| Unknown                   | 5         | 5      | 0.28%   |
| OCZ                       | 4         | 4      | 0.22%   |
| Netac                     | 4         | 4      | 0.22%   |
| Micron/Crucial Technology | 4         | 8      | 0.22%   |
| SABRENT                   | 3         | 3      | 0.17%   |
| Plextor                   | 3         | 3      | 0.17%   |
| Phison Electronics        | 3         | 3      | 0.17%   |
| LaCie                     | 3         | 3      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 30        | 1.5%    |
| Seagate ST500DM002-1BD142 500GB     | 24        | 1.2%    |
| Unknown MMC Card  64GB              | 21        | 1.05%   |
| Kingston SA400S37120G 120GB SSD     | 20        | 1%      |
| Kingston SA400S37240G 240GB SSD     | 16        | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB            | 15        | 0.75%   |
| Samsung SSD 860 EVO 500GB           | 15        | 0.75%   |
| Toshiba MQ01ABF050 500GB            | 13        | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB      | 12        | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB      | 12        | 0.6%    |
| Kingston SV300S37A120G 120GB SSD    | 11        | 0.55%   |
| Unknown MMC Card  16GB              | 10        | 0.5%    |
| Toshiba DT01ACA050 500GB            | 10        | 0.5%    |
| Seagate ST3500418AS 500GB           | 10        | 0.5%    |
| Seagate ST1000DM003-1ER162 1TB      | 10        | 0.5%    |
| Kingston SA400S37480G 480GB SSD     | 10        | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB            | 9         | 0.45%   |
| Unknown MMC Card  128GB             | 9         | 0.45%   |
| Toshiba DT01ACA100 1TB              | 9         | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB      | 9         | 0.45%   |
| Samsung SSD 850 EVO 250GB           | 9         | 0.45%   |
| Seagate ST9500325AS 500GB           | 8         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB     | 8         | 0.4%    |
| WDC WD5000AAKX-003CA0 500GB         | 7         | 0.35%   |
| Toshiba MQ01ABD100 1TB              | 7         | 0.35%   |
| Toshiba DT01ACA200 2TB              | 7         | 0.35%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB      | 7         | 0.35%   |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB      | 7         | 0.35%   |
| Seagate Expansion 1TB               | 7         | 0.35%   |
| SanDisk SSD PLUS 480GB              | 7         | 0.35%   |
| SanDisk SDSSDA240G 240GB            | 7         | 0.35%   |
| Samsung NVMe SSD Drive 500GB        | 7         | 0.35%   |
| Crucial CT500MX500SSD1 500GB        | 7         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 6         | 0.3%    |
| WDC WD5000AAKX-083CA1 500GB         | 6         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 302       | 478    | 36.56%  |
| WDC                 | 245       | 358    | 29.66%  |
| Toshiba             | 97        | 140    | 11.74%  |
| Hitachi             | 71        | 85     | 8.6%    |
| Samsung Electronics | 42        | 53     | 5.08%   |
| HGST                | 19        | 26     | 2.3%    |
| Fujitsu             | 16        | 17     | 1.94%   |
| Unknown             | 7         | 10     | 0.85%   |
| Maxtor              | 6         | 10     | 0.73%   |
| JMicron Technology  | 4         | 5      | 0.48%   |
| SABRENT             | 3         | 3      | 0.36%   |
| IBM/Hitachi         | 2         | 2      | 0.24%   |
| Hewlett-Packard     | 2         | 3      | 0.24%   |
| ASMT109x            | 2         | 3      | 0.24%   |
| USB3.0              | 1         | 1      | 0.12%   |
| SAGE                | 1         | 1      | 0.12%   |
| LaCie               | 1         | 1      | 0.12%   |
| KESU                | 1         | 3      | 0.12%   |
| DAS                 | 1         | 6      | 0.12%   |
| ASMT                | 1         | 2      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |
| Apricorn            | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 145       | 200    | 24.62%  |
| Kingston            | 89        | 106    | 15.11%  |
| SanDisk             | 65        | 77     | 11.04%  |
| Crucial             | 63        | 90     | 10.7%   |
| WDC                 | 33        | 45     | 5.6%    |
| A-DATA Technology   | 22        | 23     | 3.74%   |
| Intel               | 21        | 29     | 3.57%   |
| China               | 17        | 21     | 2.89%   |
| PNY                 | 13        | 14     | 2.21%   |
| Toshiba             | 8         | 10     | 1.36%   |
| SK hynix            | 7         | 9      | 1.19%   |
| Intenso             | 7         | 10     | 1.19%   |
| SPCC                | 6         | 11     | 1.02%   |
| Patriot             | 6         | 8      | 1.02%   |
| Transcend           | 5         | 8      | 0.85%   |
| LITEONIT            | 5         | 6      | 0.85%   |
| LITEON              | 5         | 6      | 0.85%   |
| KingSpec            | 5         | 6      | 0.85%   |
| Apacer              | 5         | 6      | 0.85%   |
| OCZ                 | 4         | 4      | 0.68%   |
| Micron Technology   | 4         | 5      | 0.68%   |
| Plextor             | 3         | 3      | 0.51%   |
| Netac               | 3         | 3      | 0.51%   |
| Verbatim            | 2         | 4      | 0.34%   |
| Vaseky              | 2         | 2      | 0.34%   |
| Team                | 2         | 2      | 0.34%   |
| Seagate             | 2         | 2      | 0.34%   |
| FORESEE             | 2         | 2      | 0.34%   |
| Corsair             | 2         | 2      | 0.34%   |
| BAITITON            | 2         | 2      | 0.34%   |
| Argon               | 2         | 3      | 0.34%   |
| AMD                 | 2         | 2      | 0.34%   |
| WDC WDS2            | 1         | 1      | 0.17%   |
| Unknown             | 1         | 2      | 0.17%   |
| TO Exter            | 1         | 1      | 0.17%   |
| Super Talent        | 1         | 1      | 0.17%   |
| SMI                 | 1         | 1      | 0.17%   |
| Smart               | 1         | 1      | 0.17%   |
| RZX                 | 1         | 1      | 0.17%   |
| NGFF                | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 706       | 1209   | 43.1%   |
| SSD     | 521       | 754    | 31.81%  |
| NVMe    | 279       | 381    | 17.03%  |
| MMC     | 105       | 140    | 6.41%   |
| Unknown | 27        | 31     | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1016      | 1889   | 68.93%  |
| NVMe | 279       | 381    | 18.93%  |
| MMC  | 105       | 140    | 7.12%   |
| SAS  | 74        | 105    | 5.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 795       | 1139   | 60.92%  |
| 0.51-1.0   | 318       | 491    | 24.37%  |
| 1.01-2.0   | 114       | 182    | 8.74%   |
| 3.01-4.0   | 34        | 48     | 2.61%   |
| 4.01-10.0  | 27        | 66     | 2.07%   |
| 2.01-3.0   | 15        | 28     | 1.15%   |
| 10.01-20.0 | 2         | 9      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 342       | 25.79%  |
| 251-500        | 321       | 24.21%  |
| 501-1000       | 196       | 14.78%  |
| 1001-2000      | 109       | 8.22%   |
| 51-100         | 91        | 6.86%   |
| More than 3000 | 77        | 5.81%   |
| 21-50          | 62        | 4.68%   |
| 1-20           | 57        | 4.3%    |
| 2001-3000      | 42        | 3.17%   |
| Unknown        | 29        | 2.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 452       | 33.19%  |
| 21-50          | 209       | 15.35%  |
| 101-250        | 189       | 13.88%  |
| 51-100         | 168       | 12.33%  |
| 251-500        | 122       | 8.96%   |
| 501-1000       | 82        | 6.02%   |
| 1001-2000      | 52        | 3.82%   |
| More than 3000 | 32        | 2.35%   |
| Unknown        | 29        | 2.13%   |
| 2001-3000      | 27        | 1.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 9         | 9      | 5.63%   |
| Seagate ST320LT007-9ZV142 320GB       | 5         | 5      | 3.13%   |
| WDC WD5000AAKX-083CA1 500GB           | 4         | 4      | 2.5%    |
| Seagate ST3500418AS 500GB             | 4         | 4      | 2.5%    |
| WDC WD5000AAKX-003CA0 500GB           | 2         | 2      | 1.25%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 2         | 2      | 1.25%   |
| WDC WD2500AAKX-753CA1 250GB           | 2         | 2      | 1.25%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 4      | 1.25%   |
| Unknown MM0500EANCR 500GB             | 2         | 5      | 1.25%   |
| Toshiba MK7559GSXP 752GB              | 2         | 2      | 1.25%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 1.25%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 1.25%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.25%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.25%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 1.25%   |
| Seagate ST2000DM001-9YN164 2TB        | 2         | 3      | 1.25%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 1.25%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 2      | 1.25%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 1.25%   |
| Samsung Electronics HD502HJ 500GB     | 2         | 2      | 1.25%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 1.25%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 1.25%   |
| Hitachi HTS542516K9SA00 160GB         | 2         | 2      | 1.25%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.63%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 1      | 0.63%   |
| WDC WD7500BPVT-75HXZT1 752GB          | 1         | 1      | 0.63%   |
| WDC WD7500BPVT-22A1YT0 752GB          | 1         | 1      | 0.63%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.63%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 2      | 0.63%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1         | 1      | 0.63%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 0.63%   |
| WDC WD40EFAX-68JH4N0 4TB              | 1         | 2      | 0.63%   |
| WDC WD3200BEKT-60V5T1 320GB           | 1         | 1      | 0.63%   |
| WDC WD3200AAJS-40VWA1 320GB           | 1         | 1      | 0.63%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.63%   |
| WDC WD2500YS-01SHB1 256GB             | 1         | 1      | 0.63%   |
| WDC WD2500BEKT-60A25T1 250GB          | 1         | 1      | 0.63%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 1      | 0.63%   |
| WDC WD2500AAJS-75M0A0 250GB           | 1         | 1      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 56     | 33.76%  |
| WDC                 | 37        | 45     | 23.57%  |
| Samsung Electronics | 14        | 18     | 8.92%   |
| Hitachi             | 11        | 11     | 7.01%   |
| Toshiba             | 8         | 8      | 5.1%    |
| Intel               | 5         | 6      | 3.18%   |
| Kingston            | 3         | 4      | 1.91%   |
| Unknown             | 2         | 5      | 1.27%   |
| SanDisk             | 2         | 2      | 1.27%   |
| OCZ                 | 2         | 2      | 1.27%   |
| Maxtor              | 2         | 2      | 1.27%   |
| Fujitsu             | 2         | 2      | 1.27%   |
| Crucial             | 2         | 2      | 1.27%   |
| China               | 2         | 2      | 1.27%   |
| A-DATA Technology   | 2         | 3      | 1.27%   |
| Vaseky              | 1         | 1      | 0.64%   |
| SK hynix            | 1         | 4      | 0.64%   |
| NGFF                | 1         | 1      | 0.64%   |
| Netac               | 1         | 1      | 0.64%   |
| IBM/Hitachi         | 1         | 1      | 0.64%   |
| HGST                | 1         | 2      | 0.64%   |
| Eluktro             | 1         | 1      | 0.64%   |
| DAS                 | 1         | 3      | 0.64%   |
| ASMT                | 1         | 2      | 0.64%   |
| Apricorn            | 1         | 1      | 0.64%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 56     | 42.06%  |
| WDC                 | 36        | 44     | 28.57%  |
| Hitachi             | 11        | 11     | 8.73%   |
| Toshiba             | 8         | 8      | 6.35%   |
| Samsung Electronics | 7         | 8      | 5.56%   |
| Unknown             | 2         | 5      | 1.59%   |
| Maxtor              | 2         | 2      | 1.59%   |
| Fujitsu             | 2         | 2      | 1.59%   |
| IBM/Hitachi         | 1         | 1      | 0.79%   |
| HGST                | 1         | 2      | 0.79%   |
| DAS                 | 1         | 3      | 0.79%   |
| ASMT                | 1         | 2      | 0.79%   |
| Apricorn            | 1         | 1      | 0.79%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 120       | 145    | 79.47%  |
| SSD  | 25        | 26     | 16.56%  |
| NVMe | 6         | 14     | 3.97%   |

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
| Detected | 644       | 1285   | 46.2%   |
| Works    | 603       | 1045   | 43.26%  |
| Malfunc  | 147       | 185    | 10.55%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 856       | 58.35%  |
| AMD                              | 227       | 15.47%  |
| Samsung Electronics              | 97        | 6.61%   |
| SanDisk                          | 37        | 2.52%   |
| SK hynix                         | 26        | 1.77%   |
| Phison Electronics               | 26        | 1.77%   |
| Nvidia                           | 26        | 1.77%   |
| ASMedia Technology               | 23        | 1.57%   |
| Marvell Technology Group         | 19        | 1.3%    |
| Kingston Technology Company      | 18        | 1.23%   |
| Toshiba America Info Systems     | 17        | 1.16%   |
| Silicon Motion                   | 14        | 0.95%   |
| JMicron Technology               | 12        | 0.82%   |
| KIOXIA                           | 9         | 0.61%   |
| Silicon Integrated Systems [SiS] | 8         | 0.55%   |
| Micron Technology                | 8         | 0.55%   |
| Micron/Crucial Technology        | 7         | 0.48%   |
| VIA Technologies                 | 6         | 0.41%   |
| ADATA Technology                 | 6         | 0.41%   |
| LSI Logic / Symbios Logic        | 4         | 0.27%   |
| Union Memory (Shenzhen)          | 3         | 0.2%    |
| Solid State Storage Technology   | 3         | 0.2%    |
| Hewlett-Packard                  | 3         | 0.2%    |
| Realtek Semiconductor            | 2         | 0.14%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.14%   |
| Silicon Image                    | 1         | 0.07%   |
| Lite-On Technology               | 1         | 0.07%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| Integrated Technology Express    | 1         | 0.07%   |
| Broadcom / LSI                   | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |
| 3ware                            | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 124       | 7.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 67        | 3.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 67        | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 48        | 2.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 47        | 2.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 46        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 45        | 2.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 43        | 2.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 42        | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 38        | 2.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 36        | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 33        | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 26        | 1.49%   |
| Samsung NVMe SSD Controller 980                                                         | 25        | 1.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25        | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 25        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 25        | 1.43%   |
| AMD 400 Series Chipset SATA Controller                                                  | 24        | 1.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 22        | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 22        | 1.26%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 20        | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 19        | 1.09%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 19        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 19        | 1.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 18        | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17        | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 16        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15        | 0.86%   |
| Nvidia MCP61 SATA Controller                                                            | 15        | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 15        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15        | 0.86%   |
| Intel SATA Controller [RAID mode]                                                       | 14        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 14        | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 14        | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 13        | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 13        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 894       | 59.21%  |
| NVMe | 277       | 18.34%  |
| IDE  | 248       | 16.42%  |
| RAID | 83        | 5.5%    |
| SAS  | 6         | 0.4%    |
| SCSI | 2         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 950       | 74.51%  |
| AMD          | 269       | 21.1%   |
| ARM          | 54        | 4.24%   |
| PowerBook5,6 | 1         | 0.08%   |
| CentaurHauls | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 45        | 3.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 0.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 10        | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 0.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.55%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 7         | 0.55%   |
| AMD Phenom II X4 B97 Processor                | 7         | 0.55%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 6         | 0.47%   |
| Intel Pentium 4 CPU 3.00GHz                   | 6         | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.47%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 6         | 0.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.47%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 6         | 0.47%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 6         | 0.47%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 6         | 0.47%   |
| Intel Celeron CPU G1840 @ 2.80GHz             | 6         | 0.47%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 0.47%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 0.47%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 6         | 0.47%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 6         | 0.47%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 5         | 0.39%   |
| Intel Pentium D CPU 2.80GHz                   | 5         | 0.39%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 5         | 0.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.39%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 5         | 0.39%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 5         | 0.39%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.39%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 5         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 248       | 19.45%  |
| Intel Core i7                  | 196       | 15.37%  |
| Other                          | 102       | 8%      |
| Intel Core i3                  | 101       | 7.92%   |
| Intel Celeron                  | 73        | 5.73%   |
| Intel Core 2 Duo               | 67        | 5.25%   |
| Intel Pentium                  | 47        | 3.69%   |
| AMD Ryzen 5                    | 46        | 3.61%   |
| Intel Xeon                     | 34        | 2.67%   |
| Intel Atom                     | 29        | 2.27%   |
| AMD Ryzen 7                    | 29        | 2.27%   |
| AMD FX                         | 21        | 1.65%   |
| Intel Pentium Dual-Core        | 20        | 1.57%   |
| Intel Core 2 Quad              | 18        | 1.41%   |
| AMD Athlon II X2               | 18        | 1.41%   |
| AMD Ryzen 3                    | 14        | 1.1%    |
| AMD Ryzen 9                    | 13        | 1.02%   |
| AMD Phenom II X4               | 13        | 1.02%   |
| AMD A6                         | 11        | 0.86%   |
| Intel Pentium 4                | 10        | 0.78%   |
| Intel Genuine                  | 10        | 0.78%   |
| AMD A4                         | 10        | 0.78%   |
| AMD A8                         | 9         | 0.71%   |
| Intel Core i9                  | 8         | 0.63%   |
| Intel Core 2                   | 8         | 0.63%   |
| AMD Athlon                     | 7         | 0.55%   |
| Intel Pentium Dual             | 6         | 0.47%   |
| Intel Pentium D                | 6         | 0.47%   |
| ARM BCM                        | 6         | 0.47%   |
| Intel Pentium Silver           | 5         | 0.39%   |
| AMD Turion 64 X2 Mobile        | 5         | 0.39%   |
| AMD E                          | 5         | 0.39%   |
| AMD Athlon II X4               | 5         | 0.39%   |
| AMD Athlon 64 X2               | 5         | 0.39%   |
| AMD Ryzen 7 PRO                | 4         | 0.31%   |
| AMD E1                         | 4         | 0.31%   |
| AMD A10                        | 4         | 0.31%   |
| Intel Core m3                  | 3         | 0.24%   |
| Intel Core Duo                 | 3         | 0.24%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 553       | 43.27%  |
| 4       | 484       | 37.87%  |
| 6       | 88        | 6.89%   |
| 8       | 58        | 4.54%   |
| 1       | 44        | 3.44%   |
| 16      | 13        | 1.02%   |
| 12      | 13        | 1.02%   |
| 3       | 9         | 0.7%    |
| 10      | 7         | 0.55%   |
| 24      | 3         | 0.23%   |
| Unknown | 3         | 0.23%   |
| 32      | 2         | 0.16%   |
| 14      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1246      | 97.65%  |
| 2       | 26        | 2.04%   |
| 4       | 2         | 0.16%   |
| Unknown | 2         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 695       | 54.38%  |
| 1       | 580       | 45.38%  |
| Unknown | 3         | 0.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1212      | 94.98%  |
| Unknown        | 36        | 2.82%   |
| 32-bit         | 25        | 1.96%   |
| 64-bit         | 3         | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 291       | 22.13%  |
| 0x306a9    | 90        | 6.84%   |
| 0x206a7    | 84        | 6.39%   |
| 0x306c3    | 70        | 5.32%   |
| 0x1067a    | 56        | 4.26%   |
| 0x806ec    | 27        | 2.05%   |
| 0x6fd      | 24        | 1.83%   |
| 0x906e9    | 23        | 1.75%   |
| 0x806ea    | 23        | 1.75%   |
| 0x010000c8 | 23        | 1.75%   |
| 0x906ea    | 22        | 1.67%   |
| 0x806c1    | 22        | 1.67%   |
| 0x506e3    | 22        | 1.67%   |
| 0x40651    | 20        | 1.52%   |
| 0x20655    | 20        | 1.52%   |
| 0x30678    | 19        | 1.44%   |
| 0x306d4    | 18        | 1.37%   |
| 0x806e9    | 17        | 1.29%   |
| 0x406c4    | 17        | 1.29%   |
| 0x10676    | 16        | 1.22%   |
| 0x706e5    | 13        | 0.99%   |
| 0x406e3    | 13        | 0.99%   |
| 0x08108109 | 12        | 0.91%   |
| 0x06000852 | 12        | 0.91%   |
| 0x706a1    | 10        | 0.76%   |
| 0x6fb      | 10        | 0.76%   |
| 0x106e5    | 10        | 0.76%   |
| 0x08701021 | 10        | 0.76%   |
| 0x06001119 | 10        | 0.76%   |
| 0xa0671    | 9         | 0.68%   |
| 0x906ed    | 9         | 0.68%   |
| 0x20652    | 9         | 0.68%   |
| 0x0a50000c | 9         | 0.68%   |
| 0x08600106 | 9         | 0.68%   |
| 0x106ca    | 8         | 0.61%   |
| 0xf41      | 7         | 0.53%   |
| 0x806d1    | 7         | 0.53%   |
| 0x706a8    | 7         | 0.53%   |
| 0x08108102 | 7         | 0.53%   |
| 0x08101016 | 7         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 157       | 12.29%  |
| Haswell          | 111       | 8.69%   |
| SandyBridge      | 110       | 8.61%   |
| IvyBridge        | 106       | 8.3%    |
| Penryn           | 84        | 6.58%   |
| Unknown          | 70        | 5.48%   |
| Core             | 51        | 3.99%   |
| K10              | 50        | 3.92%   |
| Silvermont       | 47        | 3.68%   |
| Skylake          | 44        | 3.45%   |
| Zen 2            | 40        | 3.13%   |
| Westmere         | 38        | 2.98%   |
| Zen+             | 30        | 2.35%   |
| Piledriver       | 30        | 2.35%   |
| Icelake          | 28        | 2.19%   |
| Zen              | 25        | 1.96%   |
| TigerLake        | 24        | 1.88%   |
| Broadwell        | 23        | 1.8%    |
| Goldmont plus    | 21        | 1.64%   |
| CometLake        | 20        | 1.57%   |
| Zen 3            | 19        | 1.49%   |
| K8 Hammer        | 19        | 1.49%   |
| NetBurst         | 18        | 1.41%   |
| Nehalem          | 18        | 1.41%   |
| Bonnell          | 17        | 1.33%   |
| Excavator        | 14        | 1.1%    |
| P6               | 13        | 1.02%   |
| Puma             | 9         | 0.7%    |
| Bobcat           | 9         | 0.7%    |
| Goldmont         | 7         | 0.55%   |
| K8 & K10 hybrid  | 5         | 0.39%   |
| Jaguar           | 5         | 0.39%   |
| Bulldozer        | 5         | 0.39%   |
| Alderlake Hybrid | 5         | 0.39%   |
| Steamroller      | 3         | 0.23%   |
| K10 Llano        | 2         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 728       | 51.63%  |
| Nvidia                           | 345       | 24.47%  |
| AMD                              | 316       | 22.41%  |
| Matrox Electronics Systems       | 7         | 0.5%    |
| Silicon Integrated Systems [SiS] | 6         | 0.43%   |
| ASPEED Technology                | 5         | 0.35%   |
| VIA Technologies                 | 3         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 73        | 5.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 62        | 4.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41        | 2.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 24        | 1.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 1.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 1.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.58%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 1.58%   |
| Intel UHD Graphics 620                                                                   | 22        | 1.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 1.51%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 22        | 1.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.44%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 19        | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.17%   |
| AMD Renoir                                                                               | 17        | 1.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 1.1%    |
| Nvidia GT218 [GeForce 210]                                                               | 15        | 1.03%   |
| Intel HD Graphics 630                                                                    | 15        | 1.03%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 14        | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14        | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 0.89%   |
| Intel HD Graphics 530                                                                    | 13        | 0.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 0.83%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 12        | 0.83%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 12        | 0.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 0.83%   |
| Intel HD Graphics 620                                                                    | 11        | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.76%   |
| AMD RS880 [Radeon HD 4200]                                                               | 11        | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 0.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10        | 0.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 9         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 563       | 44.05%  |
| 1 x AMD                  | 251       | 19.64%  |
| 1 x Nvidia               | 210       | 16.43%  |
| Intel + Nvidia           | 116       | 9.08%   |
| Other                    | 55        | 4.3%    |
| Intel + AMD              | 34        | 2.66%   |
| 2 x AMD                  | 14        | 1.1%    |
| AMD + Nvidia             | 11        | 0.86%   |
| 1 x SiS                  | 6         | 0.47%   |
| 1 x Matrox               | 4         | 0.31%   |
| 1 x VIA                  | 3         | 0.23%   |
| Nvidia + Matrox          | 3         | 0.23%   |
| 2 x Nvidia               | 2         | 0.16%   |
| 1 x ASPEED               | 2         | 0.16%   |
| AMD + ASPEED             | 2         | 0.16%   |
| Nvidia + ASPEED          | 1         | 0.08%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 975       | 75.82%  |
| Proprietary | 214       | 16.64%  |
| Unknown     | 97        | 7.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 736       | 56.57%  |
| 1.01-2.0   | 166       | 12.76%  |
| 0.01-0.5   | 159       | 12.22%  |
| 0.51-1.0   | 107       | 8.22%   |
| 3.01-4.0   | 71        | 5.46%   |
| 7.01-8.0   | 33        | 2.54%   |
| 5.01-6.0   | 16        | 1.23%   |
| 2.01-3.0   | 7         | 0.54%   |
| 16.01-24.0 | 3         | 0.23%   |
| 8.01-16.0  | 2         | 0.15%   |
| 4.01-5.0   | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 201       | 15%     |
| AU Optronics            | 138       | 10.3%   |
| Dell                    | 127       | 9.48%   |
| LG Display              | 107       | 7.99%   |
| Chimei Innolux          | 91        | 6.79%   |
| BOE                     | 78        | 5.82%   |
| Goldstar                | 76        | 5.67%   |
| Hewlett-Packard         | 61        | 4.55%   |
| Acer                    | 47        | 3.51%   |
| Philips                 | 40        | 2.99%   |
| BenQ                    | 28        | 2.09%   |
| Ancor Communications    | 27        | 2.01%   |
| AOC                     | 26        | 1.94%   |
| Chi Mei Optoelectronics | 25        | 1.87%   |
| ViewSonic               | 17        | 1.27%   |
| Sharp                   | 15        | 1.12%   |
| Lenovo                  | 15        | 1.12%   |
| Iiyama                  | 14        | 1.04%   |
| Apple                   | 14        | 1.04%   |
| Unknown                 | 13        | 0.97%   |
| PANDA                   | 13        | 0.97%   |
| Sony                    | 11        | 0.82%   |
| LG Electronics          | 9         | 0.67%   |
| LG Philips              | 8         | 0.6%    |
| HannStar                | 8         | 0.6%    |
| ASUSTek Computer        | 8         | 0.6%    |
| NEC Computers           | 7         | 0.52%   |
| Eizo                    | 7         | 0.52%   |
| Vizio                   | 6         | 0.45%   |
| InfoVision              | 5         | 0.37%   |
| Fujitsu Siemens         | 5         | 0.37%   |
| Toshiba                 | 4         | 0.3%    |
| Packard Bell            | 4         | 0.3%    |
| Medion                  | 4         | 0.3%    |
| Gateway                 | 4         | 0.3%    |
| Belinea                 | 4         | 0.3%    |
| RTK                     | 3         | 0.22%   |
| LGD                     | 3         | 0.22%   |
| Insignia                | 3         | 0.22%   |
| InnoLux Display         | 3         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                         | 31        | 2.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 11        | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 7         | 0.5%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 6         | 0.43%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 5         | 0.36%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                         | 5         | 0.36%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch             | 4         | 0.29%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 4         | 0.29%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 4         | 0.29%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 4         | 0.29%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 4         | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 4         | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 4         | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 4         | 0.29%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                     | 3         | 0.22%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 3         | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch      | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 3         | 0.22%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 337x270mm 17.0-inch               | 3         | 0.22%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 3         | 0.22%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 3         | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 3         | 0.22%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                 | 3         | 0.22%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                     | 3         | 0.22%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                          | 3         | 0.22%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                         | 3         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 3         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 3         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 3         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch          | 3         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 3         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 3         | 0.22%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                     | 3         | 0.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 486       | 37.88%  |
| 1366x768 (WXGA)    | 249       | 19.41%  |
| 1280x1024 (SXGA)   | 112       | 8.73%   |
| 1600x900 (HD+)     | 59        | 4.6%    |
| 3840x2160 (4K)     | 58        | 4.52%   |
| 2560x1440 (QHD)    | 43        | 3.35%   |
| 1680x1050 (WSXGA+) | 42        | 3.27%   |
| 1440x900 (WXGA+)   | 41        | 3.2%    |
| 1920x1200 (WUXGA)  | 34        | 2.65%   |
| 1280x800 (WXGA)    | 33        | 2.57%   |
| 1360x768           | 23        | 1.79%   |
| Unknown            | 18        | 1.4%    |
| 1024x600           | 11        | 0.86%   |
| 3440x1440          | 10        | 0.78%   |
| 3840x1080          | 9         | 0.7%    |
| 1600x1200          | 9         | 0.7%    |
| 2560x1600          | 6         | 0.47%   |
| 2560x1080          | 4         | 0.31%   |
| 1024x768 (XGA)     | 4         | 0.31%   |
| 2160x1440          | 3         | 0.23%   |
| 1280x720 (HD)      | 3         | 0.23%   |
| 3200x1800 (QHD+)   | 2         | 0.16%   |
| 2880x1800          | 2         | 0.16%   |
| 1920x540           | 2         | 0.16%   |
| 1920x1280          | 2         | 0.16%   |
| 1400x1050          | 2         | 0.16%   |
| 6400x1080          | 1         | 0.08%   |
| 5840x1440          | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 5040x1050          | 1         | 0.08%   |
| 4240x1440          | 1         | 0.08%   |
| 3840x2400          | 1         | 0.08%   |
| 3840x1200          | 1         | 0.08%   |
| 3200x1080          | 1         | 0.08%   |
| 3000x1920          | 1         | 0.08%   |
| 2880x900           | 1         | 0.08%   |
| 2880x1620          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2640x1024          | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 293       | 22.01%  |
| 17      | 143       | 10.74%  |
| 14      | 93        | 6.99%   |
| 13      | 89        | 6.69%   |
| 24      | 86        | 6.46%   |
| 23      | 80        | 6.01%   |
| 21      | 79        | 5.94%   |
| Unknown | 79        | 5.94%   |
| 27      | 75        | 5.63%   |
| 19      | 51        | 3.83%   |
| 18      | 38        | 2.85%   |
| 31      | 32        | 2.4%    |
| 22      | 28        | 2.1%    |
| 12      | 22        | 1.65%   |
| 20      | 21        | 1.58%   |
| 11      | 19        | 1.43%   |
| 10      | 15        | 1.13%   |
| 34      | 13        | 0.98%   |
| 84      | 9         | 0.68%   |
| 40      | 9         | 0.68%   |
| 72      | 8         | 0.6%    |
| 32      | 6         | 0.45%   |
| 46      | 5         | 0.38%   |
| 25      | 5         | 0.38%   |
| 54      | 4         | 0.3%    |
| 33      | 4         | 0.3%    |
| 16      | 4         | 0.3%    |
| 52      | 3         | 0.23%   |
| 42      | 3         | 0.23%   |
| 36      | 2         | 0.15%   |
| 74      | 1         | 0.08%   |
| 65      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 57      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 48      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 41      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 29      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 497       | 37.82%  |
| 501-600     | 226       | 17.2%   |
| 401-500     | 184       | 14%     |
| 351-400     | 112       | 8.52%   |
| 201-300     | 98        | 7.46%   |
| Unknown     | 79        | 6.01%   |
| 601-700     | 42        | 3.2%    |
| 701-800     | 25        | 1.9%    |
| 1501-2000   | 18        | 1.37%   |
| 1001-1500   | 18        | 1.37%   |
| 801-900     | 10        | 0.76%   |
| 901-1000    | 4         | 0.3%    |
| 101-200     | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 851       | 69.58%  |
| 16/10   | 154       | 12.59%  |
| 5/4     | 100       | 8.18%   |
| Unknown | 67        | 5.48%   |
| 4/3     | 17        | 1.39%   |
| 3/2     | 14        | 1.14%   |
| 21/9    | 13        | 1.06%   |
| 6/5     | 4         | 0.33%   |
| 32/9    | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |
| 0.62    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 286       | 21.68%  |
| 201-250        | 210       | 15.92%  |
| 81-90          | 143       | 10.84%  |
| 141-150        | 108       | 8.19%   |
| 151-200        | 94        | 7.13%   |
| Unknown        | 79        | 5.99%   |
| 301-350        | 75        | 5.69%   |
| 351-500        | 56        | 4.25%   |
| 121-130        | 54        | 4.09%   |
| 251-300        | 42        | 3.18%   |
| 71-80          | 36        | 2.73%   |
| More than 1000 | 29        | 2.2%    |
| 501-1000       | 23        | 1.74%   |
| 61-70          | 22        | 1.67%   |
| 51-60          | 19        | 1.44%   |
| 41-50          | 15        | 1.14%   |
| 131-140        | 14        | 1.06%   |
| 91-100         | 7         | 0.53%   |
| 111-120        | 6         | 0.45%   |
| 1-40           | 1         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 507       | 39.42%  |
| 101-120       | 325       | 25.27%  |
| 121-160       | 269       | 20.92%  |
| Unknown       | 79        | 6.14%   |
| 161-240       | 53        | 4.12%   |
| 1-50          | 38        | 2.95%   |
| More than 240 | 15        | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1022      | 79.47%  |
| 2     | 181       | 14.07%  |
| 0     | 63        | 4.9%    |
| 3     | 19        | 1.48%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 645       | 35.04%  |
| Intel                             | 571       | 31.02%  |
| Qualcomm Atheros                  | 201       | 10.92%  |
| Broadcom                          | 122       | 6.63%   |
| Broadcom Limited                  | 37        | 2.01%   |
| Ralink                            | 25        | 1.36%   |
| Marvell Technology Group          | 25        | 1.36%   |
| Ralink Technology                 | 24        | 1.3%    |
| Nvidia                            | 22        | 1.2%    |
| TP-Link                           | 21        | 1.14%   |
| Qualcomm Atheros Communications   | 10        | 0.54%   |
| ASIX Electronics                  | 9         | 0.49%   |
| Sierra Wireless                   | 8         | 0.43%   |
| Microchip Technology              | 8         | 0.43%   |
| Silicon Integrated Systems [SiS]  | 7         | 0.38%   |
| MediaTek                          | 7         | 0.38%   |
| ASUSTek Computer                  | 7         | 0.38%   |
| NetGear                           | 6         | 0.33%   |
| D-Link                            | 6         | 0.33%   |
| Attansic Technology               | 6         | 0.33%   |
| Aquantia                          | 6         | 0.33%   |
| Xiaomi                            | 5         | 0.27%   |
| Ericsson Business Mobile Networks | 5         | 0.27%   |
| VIA Technologies                  | 4         | 0.22%   |
| Huawei Technologies               | 4         | 0.22%   |
| Edimax Technology                 | 4         | 0.22%   |
| D-Link System                     | 4         | 0.22%   |
| Samsung Electronics               | 3         | 0.16%   |
| Hewlett-Packard                   | 3         | 0.16%   |
| QLogic                            | 2         | 0.11%   |
| Microsoft                         | 2         | 0.11%   |
| Linksys                           | 2         | 0.11%   |
| JMicron Technology                | 2         | 0.11%   |
| FIBOCOM                           | 2         | 0.11%   |
| DisplayLink                       | 2         | 0.11%   |
| Dell                              | 2         | 0.11%   |
| Belkin Components                 | 2         | 0.11%   |
| ZyDAS                             | 1         | 0.05%   |
| U.S. Robotics                     | 1         | 0.05%   |
| U-Blox                            | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 425       | 19.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 96        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 66        | 3.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 34        | 1.57%   |
| Intel Wi-Fi 6 AX200                                               | 34        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 31        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 30        | 1.39%   |
| Intel Wireless 7265                                               | 29        | 1.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 1.2%    |
| Intel Wireless 8265 / 8275                                        | 25        | 1.16%   |
| Intel Wireless 7260                                               | 25        | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 1.02%   |
| Intel Wireless 3165                                               | 22        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 21        | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 20        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 18        | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 17        | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 0.79%   |
| Intel I211 Gigabit Network Connection                             | 17        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 0.79%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 15        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 0.69%   |
| Nvidia MCP61 Ethernet                                             | 14        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.6%    |
| Intel Wireless 8260                                               | 13        | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 12        | 0.55%   |
| Realtek 802.11ac NIC                                              | 12        | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.51%   |
| Intel Centrino Advanced-N 6235                                    | 11        | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 396       | 42.22%  |
| Realtek Semiconductor           | 166       | 17.7%   |
| Qualcomm Atheros                | 158       | 16.84%  |
| Broadcom                        | 58        | 6.18%   |
| Ralink                          | 25        | 2.67%   |
| Ralink Technology               | 24        | 2.56%   |
| Broadcom Limited                | 23        | 2.45%   |
| TP-Link                         | 21        | 2.24%   |
| Qualcomm Atheros Communications | 10        | 1.07%   |
| Sierra Wireless                 | 8         | 0.85%   |
| ASUSTek Computer                | 7         | 0.75%   |
| NetGear                         | 6         | 0.64%   |
| MediaTek                        | 6         | 0.64%   |
| Edimax Technology               | 4         | 0.43%   |
| D-Link                          | 4         | 0.43%   |
| Microsoft                       | 2         | 0.21%   |
| Linksys                         | 2         | 0.21%   |
| FIBOCOM                         | 2         | 0.21%   |
| Dell                            | 2         | 0.21%   |
| Belkin Components               | 2         | 0.21%   |
| ZyDAS                           | 1         | 0.11%   |
| Xiaomi                          | 1         | 0.11%   |
| U.S. Robotics                   | 1         | 0.11%   |
| Tenda                           | 1         | 0.11%   |
| Sitecom Europe                  | 1         | 0.11%   |
| Quectel Wireless Solutions      | 1         | 0.11%   |
| Qualcomm                        | 1         | 0.11%   |
| IMC Networks                    | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| Gemtek                          | 1         | 0.11%   |
| D-Link System                   | 1         | 0.11%   |
| AVM                             | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 3.61%   |
| Intel Wi-Fi 6 AX200                                                     | 34        | 3.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 31        | 3.29%   |
| Intel Wireless 7265                                                     | 29        | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 2.97%   |
| Intel Wireless 8265 / 8275                                              | 25        | 2.65%   |
| Intel Wireless 7260                                                     | 25        | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.34%   |
| Intel Wireless 3165                                                     | 22        | 2.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 2.23%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 2.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 1.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 1.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.59%   |
| Intel Wireless 8260                                                     | 13        | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 1.27%   |
| Realtek 802.11ac NIC                                                    | 12        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.17%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 10        | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 1.06%   |
| Ralink MT7601U Wireless Adapter                                         | 10        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 1.06%   |
| Intel Wireless 3160                                                     | 9         | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 9         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 8         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 0.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 8         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 571       | 49.1%   |
| Intel                            | 330       | 28.37%  |
| Broadcom                         | 70        | 6.02%   |
| Qualcomm Atheros                 | 65        | 5.59%   |
| Marvell Technology Group         | 25        | 2.15%   |
| Nvidia                           | 22        | 1.89%   |
| Broadcom Limited                 | 15        | 1.29%   |
| ASIX Electronics                 | 9         | 0.77%   |
| Microchip Technology             | 8         | 0.69%   |
| Silicon Integrated Systems [SiS] | 6         | 0.52%   |
| Attansic Technology              | 6         | 0.52%   |
| Aquantia                         | 6         | 0.52%   |
| Xiaomi                           | 4         | 0.34%   |
| VIA Technologies                 | 4         | 0.34%   |
| Samsung Electronics              | 3         | 0.26%   |
| Huawei Technologies              | 3         | 0.26%   |
| D-Link System                    | 3         | 0.26%   |
| QLogic                           | 2         | 0.17%   |
| JMicron Technology               | 2         | 0.17%   |
| DisplayLink                      | 2         | 0.17%   |
| D-Link                           | 2         | 0.17%   |
| Netchip Technology               | 1         | 0.09%   |
| Mellanox Technologies            | 1         | 0.09%   |
| MediaTek                         | 1         | 0.09%   |
| Lenovo                           | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 425       | 35.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 96        | 8.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 66        | 5.5%    |
| Intel Ethernet Connection I217-LM                                 | 30        | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 17        | 1.42%   |
| Intel Ethernet Controller I225-V                                  | 15        | 1.25%   |
| Intel Ethernet Connection (2) I219-V                              | 15        | 1.25%   |
| Nvidia MCP61 Ethernet                                             | 14        | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 1.08%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 1.08%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 1%      |
| Intel Ethernet Connection I217-V                                  | 11        | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 8         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.67%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 7         | 0.58%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 7         | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 6         | 0.5%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 6         | 0.5%    |
| Attansic AR8152 v2.0 Fast Ethernet                                | 6         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 0.42%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 5         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1109      | 55.23%  |
| WiFi     | 878       | 43.73%  |
| Modem    | 19        | 0.95%   |
| Unknown  | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 682       | 52.91%  |
| Ethernet | 607       | 47.09%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 658       | 51.33%  |
| 1     | 525       | 40.95%  |
| 0     | 66        | 5.15%   |
| 3     | 21        | 1.64%   |
| 4     | 8         | 0.62%   |
| 6     | 2         | 0.16%   |
| 14    | 1         | 0.08%   |
| 5     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 1096      | 85.09%  |
| Yes     | 191       | 14.83%  |
| Unknown | 1         | 0.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 304       | 46.27%  |
| Realtek Semiconductor           | 63        | 9.59%   |
| Broadcom                        | 55        | 8.37%   |
| Qualcomm Atheros Communications | 47        | 7.15%   |
| Cambridge Silicon Radio         | 44        | 6.7%    |
| IMC Networks                    | 25        | 3.81%   |
| Dell                            | 20        | 3.04%   |
| Lite-On Technology              | 18        | 2.74%   |
| Foxconn / Hon Hai               | 15        | 2.28%   |
| Apple                           | 15        | 2.28%   |
| ASUSTek Computer                | 11        | 1.67%   |
| Hewlett-Packard                 | 10        | 1.52%   |
| Ralink                          | 8         | 1.22%   |
| Toshiba                         | 5         | 0.76%   |
| Foxconn International           | 3         | 0.46%   |
| Ralink Technology               | 2         | 0.3%    |
| Integrated System Solution      | 2         | 0.3%    |
| Belkin Components               | 2         | 0.3%    |
| Alps Electric                   | 2         | 0.3%    |
| Unknown                         | 1         | 0.15%   |
| TRENDnet                        | 1         | 0.15%   |
| Qcom                            | 1         | 0.15%   |
| MediaTek                        | 1         | 0.15%   |
| Conwise Technology              | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 119       | 18.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 56        | 8.52%   |
| Intel AX201 Bluetooth                                                               | 52        | 7.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 44        | 6.7%    |
| Realtek Bluetooth Radio                                                             | 39        | 5.94%   |
| Intel AX200 Bluetooth                                                               | 33        | 5.02%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 18        | 2.74%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 2.28%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 1.98%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 12        | 1.83%   |
| IMC Networks Bluetooth Device                                                       | 12        | 1.83%   |
| Dell DW375 Bluetooth Module                                                         | 12        | 1.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 11        | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 10        | 1.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 9         | 1.37%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 1.22%   |
| Intel AX210 Bluetooth                                                               | 7         | 1.07%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.07%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 7         | 1.07%   |
| Lite-On Bluetooth Device                                                            | 6         | 0.91%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 0.91%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 0.91%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.91%   |
| Apple Bluetooth HCI                                                                 | 6         | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 0.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 0.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 5         | 0.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 0.76%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 0.76%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.61%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 4         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 4         | 0.61%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 0.61%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.46%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 0.46%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.46%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 3         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 907       | 54.84%  |
| AMD                                            | 314       | 18.98%  |
| Nvidia                                         | 276       | 16.69%  |
| C-Media Electronics                            | 30        | 1.81%   |
| Logitech                                       | 10        | 0.6%    |
| Creative Labs                                  | 9         | 0.54%   |
| Silicon Integrated Systems [SiS]               | 8         | 0.48%   |
| Realtek Semiconductor                          | 7         | 0.42%   |
| JMTek                                          | 7         | 0.42%   |
| GN Netcom                                      | 6         | 0.36%   |
| Generalplus Technology                         | 6         | 0.36%   |
| ASUSTek Computer                               | 6         | 0.36%   |
| Corsair                                        | 5         | 0.3%    |
| VIA Technologies                               | 4         | 0.24%   |
| Kingston Technology                            | 4         | 0.24%   |
| Hewlett-Packard                                | 4         | 0.24%   |
| Razer USA                                      | 3         | 0.18%   |
| Plantronics                                    | 3         | 0.18%   |
| Lenovo                                         | 3         | 0.18%   |
| Creative Technology                            | 3         | 0.18%   |
| Tenx Technology                                | 2         | 0.12%   |
| Sony                                           | 2         | 0.12%   |
| Meizu                                          | 2         | 0.12%   |
| Jieli Technology                               | 2         | 0.12%   |
| Focusrite-Novation                             | 2         | 0.12%   |
| Dell                                           | 2         | 0.12%   |
| D&M Holdings (Denon/Marantz)                   | 2         | 0.12%   |
| Conexant Systems                               | 2         | 0.12%   |
| Cambridge Silicon Radio                        | 2         | 0.12%   |
| BEHRINGER International                        | 2         | 0.12%   |
| Alesis                                         | 2         | 0.12%   |
| XMOS                                           | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting           | 1         | 0.06%   |
| Texas Instruments                              | 1         | 0.06%   |
| TerraTec Electronic                            | 1         | 0.06%   |
| SmartAction                                    | 1         | 0.06%   |
| Siemens Information and Communication Products | 1         | 0.06%   |
| No brand                                       | 1         | 0.06%   |
| Micro Star International                       | 1         | 0.06%   |
| Medeli Electronics                             | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 106       | 5.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 100       | 5.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 77        | 3.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 75        | 3.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 71        | 3.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 66        | 3.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 61        | 3.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 58        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 46        | 2.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 40        | 2.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 37        | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 36        | 1.85%   |
| AMD FCH Azalia Controller                                                                         | 33        | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 29        | 1.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 1.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 27        | 1.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 26        | 1.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 1.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 24        | 1.24%   |
| Intel 8 Series HD Audio Controller                                                                | 24        | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 1.18%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 22        | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 22        | 1.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 1.13%   |
| Nvidia High Definition Audio Controller                                                           | 21        | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 21        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.98%   |
| Intel 200 Series PCH HD Audio                                                                     | 19        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 18        | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 17        | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 17        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 17        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.82%   |
| Nvidia MCP61 High Definition Audio                                                                | 15        | 0.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 14        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 172       | 18.86%  |
| SK hynix                                         | 143       | 15.68%  |
| Kingston                                         | 126       | 13.82%  |
| Unknown                                          | 115       | 12.61%  |
| Micron Technology                                | 79        | 8.66%   |
| Crucial                                          | 59        | 6.47%   |
| Corsair                                          | 48        | 5.26%   |
| G.Skill                                          | 27        | 2.96%   |
| Ramaxel Technology                               | 21        | 2.3%    |
| Nanya Technology                                 | 21        | 2.3%    |
| Elpida                                           | 15        | 1.64%   |
| Unknown (ABCD)                                   | 12        | 1.32%   |
| Smart                                            | 11        | 1.21%   |
| A-DATA Technology                                | 10        | 1.1%    |
| Team                                             | 6         | 0.66%   |
| Teikon                                           | 5         | 0.55%   |
| Patriot                                          | 5         | 0.55%   |
| Unknown                                          | 4         | 0.44%   |
| Qimonda                                          | 3         | 0.33%   |
| HBS                                              | 3         | 0.33%   |
| GOODRAM                                          | 3         | 0.33%   |
| Transcend                                        | 2         | 0.22%   |
| Silicon Power                                    | 2         | 0.22%   |
| Netlist                                          | 2         | 0.22%   |
| Unknown (9B0D)                                   | 1         | 0.11%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.11%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.11%   |
| Unknown (0x0C26)                                 | 1         | 0.11%   |
| Unknown (00FFFFFFFFFFFFFF)                       | 1         | 0.11%   |
| Unifosa                                          | 1         | 0.11%   |
| Toshiba                                          | 1         | 0.11%   |
| Timetec                                          | 1         | 0.11%   |
| Neo Forza                                        | 1         | 0.11%   |
| Kreton                                           | 1         | 0.11%   |
| Hewlett-Packard                                  | 1         | 0.11%   |
| Goldenmars                                       | 1         | 0.11%   |
| Golden Empire                                    | 1         | 0.11%   |
| GeIL                                             | 1         | 0.11%   |
| Eluktro                                          | 1         | 0.11%   |
| Atermiter                                        | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 1.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.61%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.51%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.51%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                    | 5         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                       | 4         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 4         | 0.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.41%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 4         | 0.41%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.41%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.41%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                     | 4         | 0.41%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 4         | 0.41%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 4         | 0.41%   |
| Unknown                                                          | 4         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.31%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 3         | 0.31%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 0.31%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.31%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 3         | 0.31%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 3         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 321       | 40.63%  |
| DDR4    | 290       | 36.71%  |
| DDR2    | 61        | 7.72%   |
| SDRAM   | 31        | 3.92%   |
| Unknown | 25        | 3.16%   |
| LPDDR4  | 23        | 2.91%   |
| LPDDR3  | 17        | 2.15%   |
| DDR     | 15        | 1.9%    |
| DRAM    | 3         | 0.38%   |
| DDR5    | 3         | 0.38%   |
| LPDDR5  | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 431       | 54.83%  |
| DIMM         | 308       | 39.19%  |
| Row Of Chips | 41        | 5.22%   |
| Chip         | 4         | 0.51%   |
| RIMM         | 1         | 0.13%   |
| Unknown      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 270       | 31.54%  |
| 8192  | 260       | 30.37%  |
| 2048  | 145       | 16.94%  |
| 16384 | 112       | 13.08%  |
| 1024  | 33        | 3.86%   |
| 32768 | 29        | 3.39%   |
| 512   | 4         | 0.47%   |
| 1536  | 1         | 0.12%   |
| 256   | 1         | 0.12%   |
| 32    | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 201       | 23.84%  |
| 3200    | 97        | 11.51%  |
| 2667    | 94        | 11.15%  |
| 1333    | 80        | 9.49%   |
| 2400    | 63        | 7.47%   |
| 1334    | 34        | 4.03%   |
| 2133    | 32        | 3.8%    |
| 800     | 30        | 3.56%   |
| 667     | 30        | 3.56%   |
| Unknown | 26        | 3.08%   |
| 1066    | 14        | 1.66%   |
| 3266    | 13        | 1.54%   |
| 1067    | 11        | 1.3%    |
| 533     | 10        | 1.19%   |
| 1867    | 9         | 1.07%   |
| 3600    | 8         | 0.95%   |
| 4199    | 7         | 0.83%   |
| 3400    | 7         | 0.83%   |
| 2048    | 6         | 0.71%   |
| 4267    | 5         | 0.59%   |
| 3000    | 5         | 0.59%   |
| 2933    | 5         | 0.59%   |
| 3466    | 4         | 0.47%   |
| 975     | 4         | 0.47%   |
| 49926   | 3         | 0.36%   |
| 3800    | 3         | 0.36%   |
| 2800    | 3         | 0.36%   |
| 2666    | 3         | 0.36%   |
| 1866    | 3         | 0.36%   |
| 400     | 3         | 0.36%   |
| 266     | 3         | 0.36%   |
| 8400    | 2         | 0.24%   |
| 4800    | 2         | 0.24%   |
| 3866    | 2         | 0.24%   |
| 3733    | 2         | 0.24%   |
| 3534    | 2         | 0.24%   |
| 3100    | 2         | 0.24%   |
| 1648    | 2         | 0.24%   |
| 6400    | 1         | 0.12%   |
| 6000    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 16        | 29.63%  |
| Brother Industries     | 9         | 16.67%  |
| Samsung Electronics    | 7         | 12.96%  |
| Seiko Epson            | 5         | 9.26%   |
| Canon                  | 5         | 9.26%   |
| Dymo-CoStar            | 4         | 7.41%   |
| QinHeng Electronics    | 2         | 3.7%    |
| STMicroelectronics     | 1         | 1.85%   |
| Prolific Technology    | 1         | 1.85%   |
| Panasonic (Matsushita) | 1         | 1.85%   |
| Lexmark International  | 1         | 1.85%   |
| Graphtec America       | 1         | 1.85%   |
| BIXOLON                | 1         | 1.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother Printer                                           | 3         | 5.45%   |
| Seiko Epson Printer                                       | 2         | 3.64%   |
| Samsung SCX-4200 series                                   | 2         | 3.64%   |
| Samsung M2020 Series                                      | 2         | 3.64%   |
| QinHeng CH340S                                            | 2         | 3.64%   |
| HP LaserJet Professional P 1102w                          | 2         | 3.64%   |
| HP Deskjet F4500 series                                   | 2         | 3.64%   |
| HP DeskJet 2700 series                                    | 2         | 3.64%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 3.64%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.82%   |
| Seiko Epson XP-4100 Series                                | 1         | 1.82%   |
| Seiko Epson WF-2010 Series                                | 1         | 1.82%   |
| Seiko Epson L310 Series                                   | 1         | 1.82%   |
| Samsung M2070 Series                                      | 1         | 1.82%   |
| Samsung CLX-8380 Series                                   | 1         | 1.82%   |
| Samsung CLX-4190 Series                                   | 1         | 1.82%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.82%   |
| Panasonic (Matsushita) KX-MB2130RU                        | 1         | 1.82%   |
| Lexmark International InkJet Color Printer                | 1         | 1.82%   |
| HP Officejet 4500 G510a-f                                 | 1         | 1.82%   |
| HP LaserJet Professional P1102w                           | 1         | 1.82%   |
| HP LaserJet 1022                                          | 1         | 1.82%   |
| HP LaserJet 1020                                          | 1         | 1.82%   |
| HP DeskJet F300 series                                    | 1         | 1.82%   |
| HP DeskJet 845c                                           | 1         | 1.82%   |
| HP Deskjet 3050 J610 series                               | 1         | 1.82%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 1.82%   |
| HP DeskJet 2130 series                                    | 1         | 1.82%   |
| HP color LaserJet 4650                                    | 1         | 1.82%   |
| Graphtec America Graphtec Printer                         | 1         | 1.82%   |
| Dymo-CoStar LabelWriter 310                               | 1         | 1.82%   |
| Dymo-CoStar DYMO LabelWriter 320                          | 1         | 1.82%   |
| Canon PIXMA MG2500 Series                                 | 1         | 1.82%   |
| Canon Pixma iP4500 Printer                                | 1         | 1.82%   |
| Canon LiDE 400                                            | 1         | 1.82%   |
| Canon LBP7010C/7018C                                      | 1         | 1.82%   |
| Canon LaserShot LBP-1120 Printer                          | 1         | 1.82%   |
| Brother MFC-L2710DN series                                | 1         | 1.82%   |
| Brother HL-3170CDW series                                 | 1         | 1.82%   |
| Brother HL-3140CW series                                  | 1         | 1.82%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 6         | 40%     |
| Seiko Epson                                    | 5         | 33.33%  |
| Hewlett-Packard                                | 2         | 13.33%  |
| Siemens Information and Communication Products | 1         | 6.67%   |
| Acer Peripherals (now BenQ)                    | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                         | 2         | 13.33%  |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 6.67%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]                                | 1         | 6.67%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                               | 1         | 6.67%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                              | 1         | 6.67%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                            | 1         | 6.67%   |
| Seiko Epson ES-D400 [GT-S80]                                                    | 1         | 6.67%   |
| HP ScanJet G4010                                                                | 1         | 6.67%   |
| HP ScanJet 4370                                                                 | 1         | 6.67%   |
| Canon CanoScan N1240U/LiDE 30                                                   | 1         | 6.67%   |
| Canon CanoScan LIDE 25                                                          | 1         | 6.67%   |
| Canon CanoScan LiDE 210                                                         | 1         | 6.67%   |
| Canon CanoScan LiDE 120                                                         | 1         | 6.67%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                     | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 173       | 25.4%   |
| Acer                                   | 56        | 8.22%   |
| Microdia                               | 55        | 8.08%   |
| IMC Networks                           | 46        | 6.75%   |
| Logitech                               | 43        | 6.31%   |
| Realtek Semiconductor                  | 40        | 5.87%   |
| Sunplus Innovation Technology          | 32        | 4.7%    |
| Cheng Uei Precision Industry (Foxlink) | 32        | 4.7%    |
| Quanta                                 | 24        | 3.52%   |
| Suyin                                  | 20        | 2.94%   |
| Syntek                                 | 18        | 2.64%   |
| Ricoh                                  | 17        | 2.5%    |
| Apple                                  | 15        | 2.2%    |
| Lite-On Technology                     | 12        | 1.76%   |
| Silicon Motion                         | 11        | 1.62%   |
| Alcor Micro                            | 7         | 1.03%   |
| Samsung Electronics                    | 6         | 0.88%   |
| Luxvisions Innotech Limited            | 6         | 0.88%   |
| Z-Star Microelectronics                | 5         | 0.73%   |
| Lenovo                                 | 5         | 0.73%   |
| Importek                               | 5         | 0.73%   |
| Microsoft                              | 4         | 0.59%   |
| ARC International                      | 4         | 0.59%   |
| Primax Electronics                     | 3         | 0.44%   |
| KYE Systems (Mouse Systems)            | 3         | 0.44%   |
| Generalplus Technology                 | 3         | 0.44%   |
| Creative Technology                    | 3         | 0.44%   |
| ALi                                    | 3         | 0.44%   |
| Unknown                                | 2         | 0.29%   |
| Sunplus Technology                     | 2         | 0.29%   |
| Ruision                                | 2         | 0.29%   |
| Razer USA                              | 2         | 0.29%   |
| LG Electronics                         | 2         | 0.29%   |
| DigiTech                               | 2         | 0.29%   |
| Cubeternet                             | 2         | 0.29%   |
| Aveo Technology                        | 2         | 0.29%   |
| Y Media                                | 1         | 0.15%   |
| U0AS01A-0                              | 1         | 0.15%   |
| Sonix Technology                       | 1         | 0.15%   |
| SJ-180517-N                            | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 29        | 4.23%   |
| Acer Integrated Camera                                  | 18        | 2.63%   |
| Chicony HD WebCam                                       | 17        | 2.48%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 15        | 2.19%   |
| Realtek Integrated_Webcam_HD                            | 12        | 1.75%   |
| Microdia Integrated_Webcam_HD                           | 11        | 1.61%   |
| Sunplus Integrated_Webcam_HD                            | 10        | 1.46%   |
| Syntek Integrated Camera                                | 9         | 1.31%   |
| Logitech Webcam C270                                    | 9         | 1.31%   |
| IMC Networks Integrated Camera                          | 9         | 1.31%   |
| Chicony USB2.0 VGA UVC WebCam                           | 9         | 1.31%   |
| Chicony USB2.0 Camera                                   | 9         | 1.31%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 7         | 1.02%   |
| Logitech HD Pro Webcam C920                             | 7         | 1.02%   |
| Chicony HP HD Camera                                    | 7         | 1.02%   |
| Apple iPhone 5/5C/5S/6/SE                               | 7         | 1.02%   |
| Acer BisonCam, NB Pro                                   | 7         | 1.02%   |
| Samsung Galaxy A5 (MTP)                                 | 6         | 0.88%   |
| Ricoh HD Webcam                                         | 6         | 0.88%   |
| Realtek USB Camera                                      | 6         | 0.88%   |
| Quanta HD User Facing                                   | 6         | 0.88%   |
| Microdia Integrated Webcam                              | 6         | 0.88%   |
| Chicony USB 2.0 Camera                                  | 6         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 6         | 0.88%   |
| Acer Lenovo Integrated Webcam                           | 6         | 0.88%   |
| Microdia Webcam Vitade AF                               | 5         | 0.73%   |
| Chicony VGA Webcam                                      | 5         | 0.73%   |
| Chicony HP Webcam                                       | 5         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 5         | 0.73%   |
| Acer Lenovo EasyCamera                                  | 5         | 0.73%   |
| Syntek Lenovo EasyCamera                                | 4         | 0.58%   |
| Suyin HP TrueVision HD Integrated Webcam                | 4         | 0.58%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 4         | 0.58%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 4         | 0.58%   |
| Quanta HP HD Camera                                     | 4         | 0.58%   |
| Microdia USB 2.0 Camera                                 | 4         | 0.58%   |
| Chicony Integrated Camera (1280x720@30)                 | 4         | 0.58%   |
| Chicony HP Truevision HD                                | 4         | 0.58%   |
| Chicony FJ Camera                                       | 4         | 0.58%   |
| ARC International Camera                                | 4         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 49        | 40.5%   |
| Synaptics                  | 27        | 22.31%  |
| Shenzhen Goodix Technology | 15        | 12.4%   |
| Upek                       | 9         | 7.44%   |
| Elan Microelectronics      | 7         | 5.79%   |
| AuthenTec                  | 6         | 4.96%   |
| STMicroelectronics         | 3         | 2.48%   |
| LighTuning Technology      | 3         | 2.48%   |
| Samsung Electronics        | 1         | 0.83%   |
| Focal-systems.Corp         | 1         | 0.83%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 7.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 6.61%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 6.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 5.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 5.79%   |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 5.79%   |
| Unknown                                                                    | 7         | 5.79%   |
| Validity Sensors VFS491                                                    | 5         | 4.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 4.13%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 3.31%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.48%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.48%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 2.48%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.48%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 2.48%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.65%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.65%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.65%   |
| Synaptics  WBDI                                                            | 2         | 1.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.65%   |
| AuthenTec AES1600                                                          | 2         | 1.65%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.83%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.83%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.83%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.83%   |
| Synaptics WBDI Device                                                      | 1         | 0.83%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.83%   |
| Samsung Fingerprint Device                                                 | 1         | 0.83%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.83%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.83%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.83%   |
| AuthenTec AES2810                                                          | 1         | 0.83%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 37        | 48.05%  |
| Alcor Micro           | 19        | 24.68%  |
| Upek                  | 4         | 5.19%   |
| O2 Micro              | 4         | 5.19%   |
| Lenovo                | 3         | 3.9%    |
| Advanced Card Systems | 3         | 3.9%    |
| SCM Microsystems      | 2         | 2.6%    |
| Gemalto (was Gemplus) | 2         | 2.6%    |
| Realtek Semiconductor | 1         | 1.3%    |
| Kobil Systems         | 1         | 1.3%    |
| Chicony Electronics   | 1         | 1.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 24.68%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 15.58%  |
| Broadcom 58200                                                               | 8         | 10.39%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.19%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.19%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.9%    |
| Broadcom 5880                                                                | 3         | 3.9%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 2.6%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 2.6%    |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.3%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.3%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.3%    |
| Kobil Systems Smart Token                                                    | 1         | 1.3%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.3%    |
| Advanced Card Systems ACR122U                                                | 1         | 1.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 945       | 73.09%  |
| 1     | 275       | 21.27%  |
| 2     | 56        | 4.33%   |
| 3     | 13        | 1.01%   |
| 8     | 2         | 0.15%   |
| 5     | 1         | 0.08%   |
| 4     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 122       | 28.24%  |
| Graphics card            | 101       | 23.38%  |
| Chipcard                 | 71        | 16.44%  |
| Net/wireless             | 34        | 7.87%   |
| Camera                   | 16        | 3.7%    |
| Communication controller | 14        | 3.24%   |
| Bluetooth                | 14        | 3.24%   |
| Storage                  | 11        | 2.55%   |
| Multimedia controller    | 10        | 2.31%   |
| Unassigned class         | 7         | 1.62%   |
| Modem                    | 7         | 1.62%   |
| Sound                    | 6         | 1.39%   |
| Network                  | 5         | 1.16%   |
| Flash memory             | 4         | 0.93%   |
| Card reader              | 4         | 0.93%   |
| Net/ethernet             | 2         | 0.46%   |
| Tv card                  | 1         | 0.23%   |
| Storage/ata              | 1         | 0.23%   |
| Firewire controller      | 1         | 0.23%   |
| Dvb card                 | 1         | 0.23%   |

