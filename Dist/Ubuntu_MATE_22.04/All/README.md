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

Total: 296

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                | Computers | Percent |
|----------------------------------------|-----------|---------|
| 5.15.0-56-generic                      | 25        | 13.59%  |
| 5.15.0-47-generic                      | 18        | 9.78%   |
| 5.15.0-48-generic                      | 13        | 7.07%   |
| 5.15.0-52-generic                      | 11        | 5.98%   |
| 5.15.0-46-generic                      | 11        | 5.98%   |
| 5.15.0-40-generic                      | 9         | 4.89%   |
| 5.15.0-43-generic                      | 8         | 4.35%   |
| 5.15.0-25-generic                      | 8         | 4.35%   |
| 5.15.0-58-generic                      | 7         | 3.8%    |
| 5.15.0-53-generic                      | 7         | 3.8%    |
| 5.15.0-27-generic                      | 7         | 3.8%    |
| 5.15.0-50-generic                      | 6         | 3.26%   |
| 5.15.0-41-generic                      | 6         | 3.26%   |
| 5.15.0-57-generic                      | 5         | 2.72%   |
| 5.15.0-30-generic                      | 4         | 2.17%   |
| 5.15.0-37-generic                      | 3         | 1.63%   |
| 5.15.0-58-lowlatency                   | 2         | 1.09%   |
| 5.15.0-56-lowlatency                   | 2         | 1.09%   |
| 5.15.0-52-lowlatency                   | 2         | 1.09%   |
| 5.15.0-39-generic                      | 2         | 1.09%   |
| 5.15.0-35-generic                      | 2         | 1.09%   |
| 5.14.0-1054-oem                        | 2         | 1.09%   |
| 6.1.8-x64v1-xanmod1                    | 1         | 0.54%   |
| 6.0.8-x64v1-xanmod1                    | 1         | 0.54%   |
| 5.18.0-odroid-arm64                    | 1         | 0.54%   |
| 5.18.0-1-generic                       | 1         | 0.54%   |
| 5.18.0-051800-generic                  | 1         | 0.54%   |
| 5.17.1-051701-generic                  | 1         | 0.54%   |
| 5.17.0-rc4-next-20220217-g21d89a4d51a7 | 1         | 0.54%   |
| 5.17.0-1003-oem                        | 1         | 0.54%   |
| 5.15.0-59-generic                      | 1         | 0.54%   |
| 5.15.0-46-lowlatency                   | 1         | 0.54%   |
| 5.15.0-33-generic                      | 1         | 0.54%   |
| 5.15.0-23-generic                      | 1         | 0.54%   |
| 5.15.0-22-generic                      | 1         | 0.54%   |
| 5.15.0-18-generic                      | 1         | 0.54%   |
| 5.15.0-11-generic                      | 1         | 0.54%   |
| 5.15.0-1023-raspi                      | 1         | 0.54%   |
| 5.15.0-1022-raspi                      | 1         | 0.54%   |
| 5.15.0-1021-raspi                      | 1         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 153       | 92.17%  |
| 5.18.0  | 3         | 1.81%   |
| 5.17.0  | 2         | 1.2%    |
| 5.14.0  | 2         | 1.2%    |
| 5.13.0  | 2         | 1.2%    |
| 6.1.8   | 1         | 0.6%    |
| 6.0.8   | 1         | 0.6%    |
| 5.17.1  | 1         | 0.6%    |
| 4.9.337 | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 153       | 92.17%  |
| 5.18    | 3         | 1.81%   |
| 5.17    | 3         | 1.81%   |
| 5.14    | 2         | 1.2%    |
| 5.13    | 2         | 1.2%    |
| 6.1     | 1         | 0.6%    |
| 6.0     | 1         | 0.6%    |
| 4.9     | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 159       | 96.95%  |
| aarch64 | 4         | 2.44%   |
| armv7l  | 1         | 0.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| MATE   | 161       | 98.17%  |
| KDE5   | 2         | 1.22%   |
| Budgie | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 156       | 95.12%  |
| Wayland | 4         | 2.44%   |
| Tty     | 4         | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 135       | 80.84%  |
| GDM3    | 17        | 10.18%  |
| Unknown | 14        | 8.38%   |
| SDDM    | 1         | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 65        | 39.16%  |
| fr_FR | 18        | 10.84%  |
| de_DE | 17        | 10.24%  |
| it_IT | 13        | 7.83%   |
| ru_RU | 6         | 3.61%   |
| en_CA | 6         | 3.61%   |
| en_GB | 5         | 3.01%   |
| en_AU | 5         | 3.01%   |
| pt_BR | 4         | 2.41%   |
| C     | 4         | 2.41%   |
| fi_FI | 3         | 1.81%   |
| de_CH | 3         | 1.81%   |
| pl_PL | 2         | 1.2%    |
| hu_HU | 2         | 1.2%    |
| hr_HR | 2         | 1.2%    |
| es_ES | 2         | 1.2%    |
| zh_CN | 1         | 0.6%    |
| pt_PT | 1         | 0.6%    |
| nl_NL | 1         | 0.6%    |
| es_PE | 1         | 0.6%    |
| es_AR | 1         | 0.6%    |
| en_IL | 1         | 0.6%    |
| el_GR | 1         | 0.6%    |
| de_AT | 1         | 0.6%    |
| da_DK | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 86        | 50.29%  |
| EFI  | 85        | 49.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 150       | 90.91%  |
| Overlay | 5         | 3.03%   |
| Zfs     | 4         | 2.42%   |
| Btrfs   | 3         | 1.82%   |
| Xfs     | 2         | 1.21%   |
| Jfs     | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 115       | 68.05%  |
| Unknown | 36        | 21.3%   |
| MBR     | 18        | 10.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 134       | 81.71%  |
| Yes       | 30        | 18.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 62.87%  |
| Yes       | 62        | 37.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 31        | 18.9%   |
| Hewlett-Packard         | 30        | 18.29%  |
| Lenovo                  | 21        | 12.8%   |
| Dell                    | 17        | 10.37%  |
| MSI                     | 9         | 5.49%   |
| Gigabyte Technology     | 8         | 4.88%   |
| Acer                    | 7         | 4.27%   |
| ASRock                  | 5         | 3.05%   |
| Apple                   | 5         | 3.05%   |
| Intel                   | 4         | 2.44%   |
| Toshiba                 | 2         | 1.22%   |
| Raspberry Pi Foundation | 2         | 1.22%   |
| HUAWEI                  | 2         | 1.22%   |
| Hardkernel              | 2         | 1.22%   |
| Google                  | 2         | 1.22%   |
| Unknown                 | 2         | 1.22%   |
| TYAN Computer           | 1         | 0.61%   |
| TrekStor                | 1         | 0.61%   |
| Sony                    | 1         | 0.61%   |
| Notebook                | 1         | 0.61%   |
| Microsoft               | 1         | 0.61%   |
| MicroByte               | 1         | 0.61%   |
| Medion                  | 1         | 0.61%   |
| LincPlus                | 1         | 0.61%   |
| LG Electronics          | 1         | 0.61%   |
| IPASON                  | 1         | 0.61%   |
| HYPERPC                 | 1         | 0.61%   |
| HONOR                   | 1         | 0.61%   |
| Compaq                  | 1         | 0.61%   |
| Chuwi                   | 1         | 0.61%   |
| AZW                     | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP Compaq Elite 8300 SFF             | 2         | 1.22%   |
| Hardkernel ODROID-N2Plus             | 2         | 1.22%   |
| Unknown                              | 2         | 1.22%   |
| TYAN S7012                           | 1         | 0.61%   |
| TrekStor Surfbook A13B               | 1         | 0.61%   |
| Toshiba Satellite P50-B-10Z          | 1         | 0.61%   |
| Toshiba Satellite C50D-A-133         | 1         | 0.61%   |
| Sony VPCEA36FG                       | 1         | 0.61%   |
| RPi Raspberry Pi 400 Rev 1.1         | 1         | 0.61%   |
| RPi Raspberry Pi                     | 1         | 0.61%   |
| Notebook NJx0MU                      | 1         | 0.61%   |
| MSI p6-2330                          | 1         | 0.61%   |
| MSI MS-7C56                          | 1         | 0.61%   |
| MSI MS-7C09                          | 1         | 0.61%   |
| MSI MS-7C02                          | 1         | 0.61%   |
| MSI MS-7982                          | 1         | 0.61%   |
| MSI MS-7817                          | 1         | 0.61%   |
| MSI MS-7758                          | 1         | 0.61%   |
| MSI MS-7599                          | 1         | 0.61%   |
| MSI B02311                           | 1         | 0.61%   |
| Microsoft Surface 2                  | 1         | 0.61%   |
| MicroByte ezbook                     | 1         | 0.61%   |
| Medion MS-7797                       | 1         | 0.61%   |
| LincPlus LINNCPLUS P1                | 1         | 0.61%   |
| LG 17Z990-R.AAS8U1                   | 1         | 0.61%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 0.61%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 0.61%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 0.61%   |
| Lenovo ThinkPad T430 2347G5U         | 1         | 0.61%   |
| Lenovo ThinkPad T420 4238LY7         | 1         | 0.61%   |
| Lenovo ThinkPad T15 Gen 1 20S6S1HN00 | 1         | 0.61%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 0.61%   |
| Lenovo ThinkPad R61 8918DEG          | 1         | 0.61%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 0.61%   |
| Lenovo ThinkCentre M710q 10MQSC0N00  | 1         | 0.61%   |
| Lenovo ThinkCentre M710q 10MQS0FR01  | 1         | 0.61%   |
| Lenovo ThinkBook 16p Gen 2 20YM      | 1         | 0.61%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 1         | 0.61%   |
| Lenovo T530-28ICB                    | 1         | 0.61%   |
| Lenovo IdeaPadFlex 6-14IKB 81EM      | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 8         | 4.88%   |
| Dell Latitude            | 6         | 3.66%   |
| Lenovo IdeaPad           | 5         | 3.05%   |
| HP Pavilion              | 4         | 2.44%   |
| HP Compaq                | 4         | 2.44%   |
| Dell Precision           | 4         | 2.44%   |
| ASUS ROG                 | 4         | 2.44%   |
| ASUS PRIME               | 4         | 2.44%   |
| Acer Aspire              | 4         | 2.44%   |
| HP EliteDesk             | 3         | 1.83%   |
| HP EliteBook             | 3         | 1.83%   |
| Dell Inspiron            | 3         | 1.83%   |
| ASUS VivoBook            | 3         | 1.83%   |
| Toshiba Satellite        | 2         | 1.22%   |
| RPi Raspberry            | 2         | 1.22%   |
| Lenovo ThinkCentre       | 2         | 1.22%   |
| Lenovo ThinkBook         | 2         | 1.22%   |
| HP ZBook                 | 2         | 1.22%   |
| HP ProLiant              | 2         | 1.22%   |
| HP ProBook               | 2         | 1.22%   |
| HP ENVY                  | 2         | 1.22%   |
| HP 15                    | 2         | 1.22%   |
| Hardkernel ODROID-N2Plus | 2         | 1.22%   |
| Dell XPS                 | 2         | 1.22%   |
| Dell OptiPlex            | 2         | 1.22%   |
| ASUS TUF                 | 2         | 1.22%   |
| ASUS ASUS                | 2         | 1.22%   |
| Acer TravelMate          | 2         | 1.22%   |
| Unknown                  | 2         | 1.22%   |
| TYAN S7012               | 1         | 0.61%   |
| TrekStor Surfbook        | 1         | 0.61%   |
| Sony VPCEA36FG           | 1         | 0.61%   |
| Notebook NJx0MU          | 1         | 0.61%   |
| MSI p6-2330              | 1         | 0.61%   |
| MSI MS-7C56              | 1         | 0.61%   |
| MSI MS-7C09              | 1         | 0.61%   |
| MSI MS-7C02              | 1         | 0.61%   |
| MSI MS-7982              | 1         | 0.61%   |
| MSI MS-7817              | 1         | 0.61%   |
| MSI MS-7758              | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 27        | 16.46%  |
| 2020    | 16        | 9.76%   |
| 2018    | 16        | 9.76%   |
| 2012    | 15        | 9.15%   |
| 2013    | 12        | 7.32%   |
| 2019    | 10        | 6.1%    |
| 2014    | 10        | 6.1%    |
| 2022    | 8         | 4.88%   |
| 2011    | 8         | 4.88%   |
| 2010    | 8         | 4.88%   |
| 2009    | 7         | 4.27%   |
| 2017    | 6         | 3.66%   |
| 2016    | 5         | 3.05%   |
| 2015    | 4         | 2.44%   |
| Unknown | 4         | 2.44%   |
| 2008    | 3         | 1.83%   |
| 2007    | 3         | 1.83%   |
| 2006    | 2         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 84        | 51.22%  |
| Desktop        | 64        | 39.02%  |
| System on chip | 4         | 2.44%   |
| Tablet         | 3         | 1.83%   |
| Convertible    | 3         | 1.83%   |
| Mini pc        | 3         | 1.83%   |
| All in one     | 2         | 1.22%   |
| Server         | 1         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 157       | 94.01%  |
| Enabled  | 10        | 5.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 162       | 98.78%  |
| Yes  | 2         | 1.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 40        | 24.39%  |
| 3.01-4.0    | 31        | 18.9%   |
| 8.01-16.0   | 31        | 18.9%   |
| 16.01-24.0  | 25        | 15.24%  |
| 32.01-64.0  | 22        | 13.41%  |
| 64.01-256.0 | 7         | 4.27%   |
| 24.01-32.0  | 4         | 2.44%   |
| 1.01-2.0    | 3         | 1.83%   |
| 2.01-3.0    | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 50        | 28.74%  |
| 1.01-2.0   | 50        | 28.74%  |
| 4.01-8.0   | 33        | 18.97%  |
| 3.01-4.0   | 23        | 13.22%  |
| 8.01-16.0  | 9         | 5.17%   |
| 0.51-1.0   | 8         | 4.6%    |
| 24.01-32.0 | 1         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 98        | 59.76%  |
| 2      | 29        | 17.68%  |
| 3      | 18        | 10.98%  |
| 4      | 11        | 6.71%   |
| 6      | 4         | 2.44%   |
| 5      | 2         | 1.22%   |
| 20     | 1         | 0.61%   |
| 7      | 1         | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 56.71%  |
| Yes       | 71        | 43.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 80.49%  |
| No        | 32        | 19.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 79.27%  |
| No        | 34        | 20.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 63.03%  |
| No        | 61        | 36.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 29        | 17.68%  |
| Germany     | 20        | 12.2%   |
| France      | 17        | 10.37%  |
| Italy       | 16        | 9.76%   |
| Russia      | 6         | 3.66%   |
| Brazil      | 6         | 3.66%   |
| UK          | 5         | 3.05%   |
| Spain       | 5         | 3.05%   |
| Canada      | 5         | 3.05%   |
| Turkey      | 4         | 2.44%   |
| Hungary     | 4         | 2.44%   |
| Finland     | 4         | 2.44%   |
| Australia   | 4         | 2.44%   |
| Switzerland | 3         | 1.83%   |
| Portugal    | 3         | 1.83%   |
| Greece      | 3         | 1.83%   |
| Croatia     | 3         | 1.83%   |
| Serbia      | 2         | 1.22%   |
| Poland      | 2         | 1.22%   |
| Estonia     | 2         | 1.22%   |
| Belgium     | 2         | 1.22%   |
| Austria     | 2         | 1.22%   |
| Ukraine     | 1         | 0.61%   |
| Slovenia    | 1         | 0.61%   |
| Romania     | 1         | 0.61%   |
| Peru        | 1         | 0.61%   |
| Paraguay    | 1         | 0.61%   |
| New Zealand | 1         | 0.61%   |
| Netherlands | 1         | 0.61%   |
| Israel      | 1         | 0.61%   |
| Isle of Man | 1         | 0.61%   |
| India       | 1         | 0.61%   |
| Georgia     | 1         | 0.61%   |
| Denmark     | 1         | 0.61%   |
| Colombia    | 1         | 0.61%   |
| China       | 1         | 0.61%   |
| Chile       | 1         | 0.61%   |
| Bulgaria    | 1         | 0.61%   |
| Argentina   | 1         | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Mannheim         | 3         | 1.78%   |
| Berlin           | 3         | 1.78%   |
| Zagreb           | 2         | 1.18%   |
| West Stockbridge | 2         | 1.18%   |
| Warsaw           | 2         | 1.18%   |
| Vancouver        | 2         | 1.18%   |
| Turku            | 2         | 1.18%   |
| Rome             | 2         | 1.18%   |
| Paris            | 2         | 1.18%   |
| Olathe           | 2         | 1.18%   |
| Moscow           | 2         | 1.18%   |
| Melbourne        | 2         | 1.18%   |
| Lansdale         | 2         | 1.18%   |
| Belgrade         | 2         | 1.18%   |
| Zottegem         | 1         | 0.59%   |
| York             | 1         | 0.59%   |
| Xining           | 1         | 0.59%   |
| Whanganui        | 1         | 0.59%   |
| Washington       | 1         | 0.59%   |
| Viroflay         | 1         | 0.59%   |
| Villeurbanne     | 1         | 0.59%   |
| Viana do Castelo | 1         | 0.59%   |
| Velyki Mosty     | 1         | 0.59%   |
| Vaudoy-en-Brie   | 1         | 0.59%   |
| Varna            | 1         | 0.59%   |
| Valenciennes     | 1         | 0.59%   |
| Tula             | 1         | 0.59%   |
| Trenton          | 1         | 0.59%   |
| Toulouse         | 1         | 0.59%   |
| Toulon           | 1         | 0.59%   |
| Torring          | 1         | 0.59%   |
| Thane            | 1         | 0.59%   |
| Terrace          | 1         | 0.59%   |
| Tel Aviv         | 1         | 0.59%   |
| Tartu            | 1         | 0.59%   |
| Taranto          | 1         | 0.59%   |
| Talence          | 1         | 0.59%   |
| Talcahuano       | 1         | 0.59%   |
| Stuttgart        | 1         | 0.59%   |
| St Petersburg    | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 42        | 69     | 16.94%  |
| WDC                   | 32        | 50     | 12.9%   |
| Seagate               | 29        | 51     | 11.69%  |
| SanDisk               | 15        | 20     | 6.05%   |
| Crucial               | 15        | 19     | 6.05%   |
| Toshiba               | 13        | 21     | 5.24%   |
| Unknown               | 12        | 18     | 4.84%   |
| Kingston              | 10        | 14     | 4.03%   |
| SK hynix              | 6         | 6      | 2.42%   |
| A-DATA Technology     | 6         | 6      | 2.42%   |
| Phison                | 5         | 5      | 2.02%   |
| Hitachi               | 5         | 5      | 2.02%   |
| SPCC                  | 4         | 6      | 1.61%   |
| KingSpec              | 3         | 3      | 1.21%   |
| Intel                 | 3         | 3      | 1.21%   |
| HGST                  | 3         | 3      | 1.21%   |
| China                 | 3         | 3      | 1.21%   |
| Phison Electronics    | 2         | 2      | 0.81%   |
| Netac                 | 2         | 2      | 0.81%   |
| Micron Technology     | 2         | 2      | 0.81%   |
| KIOXIA                | 2         | 2      | 0.81%   |
| Corsair               | 2         | 2      | 0.81%   |
| Unknown               | 2         | 2      | 0.81%   |
| WDC WDS2              | 1         | 1      | 0.4%    |
| Verbatim              | 1         | 2      | 0.4%    |
| UMIS                  | 1         | 2      | 0.4%    |
| SSSTC                 | 1         | 1      | 0.4%    |
| RZX                   | 1         | 1      | 0.4%    |
| Realtek Semiconductor | 1         | 2      | 0.4%    |
| Patriot               | 1         | 1      | 0.4%    |
| NGFF                  | 1         | 1      | 0.4%    |
| Maxtor                | 1         | 1      | 0.4%    |
| LITEONIT              | 1         | 1      | 0.4%    |
| LITEON                | 1         | 1      | 0.4%    |
| Lenovo                | 1         | 1      | 0.4%    |
| Kston                 | 1         | 1      | 0.4%    |
| KIOXIA-EXCERIA        | 1         | 1      | 0.4%    |
| Kimtigo               | 1         | 1      | 0.4%    |
| KESU                  | 1         | 1      | 0.4%    |
| JMicron Technology    | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Crucial CT1000BX500SSD1 1TB                         | 4         | 1.4%    |
| Seagate ST500DM002-1BD142 500GB                     | 3         | 1.05%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3         | 1.05%   |
| Samsung SSD 870 QVO 1TB                             | 3         | 1.05%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 1.05%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 1.05%   |
| Crucial CT2000MX500SSD1 2TB                         | 3         | 1.05%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 2         | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB                            | 2         | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 0.7%    |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.7%    |
| Seagate ST9500325AS 500GB                           | 2         | 0.7%    |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.7%    |
| Seagate ST2000LM015-2E8174 2TB                      | 2         | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 0.7%    |
| Seagate ST1000DM003-1ER162 1TB                      | 2         | 0.7%    |
| SanDisk SSD PLUS 480GB                              | 2         | 0.7%    |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.7%    |
| Samsung SSD 980 1TB                                 | 2         | 0.7%    |
| Samsung SSD 870 QVO 2TB                             | 2         | 0.7%    |
| Samsung MZVLQ512HBLU-00BH1 512GB                    | 2         | 0.7%    |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.7%    |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.7%    |
| Unknown                                             | 2         | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.35%   |
| WDC WDS2 50G2B0B-00YS 250GB SSD                     | 1         | 0.35%   |
| WDC WDS100T2B0C 1TB                                 | 1         | 0.35%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.35%   |
| WDC WD800JD-22JNC0 69GB                             | 1         | 0.35%   |
| WDC WD8001FZBX-00ASYA0 8TB                          | 1         | 0.35%   |
| WDC WD6400AAKS-00E4A0 640GB                         | 1         | 0.35%   |
| WDC WD60 EFAX-68JH4N1 6TB                           | 1         | 0.35%   |
| WDC WD5003AZEX-00K1GA0 500GB                        | 1         | 0.35%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 0.35%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1         | 0.35%   |
| WDC WD5000AZLX-75K2TA0 500GB                        | 1         | 0.35%   |
| WDC WD5000AAKX-08ERMA0 500GB                        | 1         | 0.35%   |
| WDC WD5000AAKX-003CA0 500GB                         | 1         | 0.35%   |
| WDC WD5000AAKS-65TMA0 500GB                         | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 45     | 34.94%  |
| Seagate             | 29        | 51     | 34.94%  |
| Toshiba             | 10        | 17     | 12.05%  |
| Hitachi             | 5         | 5      | 6.02%   |
| HGST                | 3         | 3      | 3.61%   |
| Samsung Electronics | 2         | 5      | 2.41%   |
| Maxtor              | 1         | 1      | 1.2%    |
| KESU                | 1         | 1      | 1.2%    |
| Hewlett-Packard     | 1         | 2      | 1.2%    |
| DAS                 | 1         | 6      | 1.2%    |
| ASMedia             | 1         | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 28     | 22.58%  |
| Crucial             | 15        | 19     | 16.13%  |
| SanDisk             | 11        | 14     | 11.83%  |
| Kingston            | 7         | 10     | 7.53%   |
| A-DATA Technology   | 5         | 5      | 5.38%   |
| SPCC                | 3         | 5      | 3.23%   |
| KingSpec            | 3         | 3      | 3.23%   |
| China               | 3         | 3      | 3.23%   |
| WDC                 | 2         | 2      | 2.15%   |
| WDC WDS2            | 1         | 1      | 1.08%   |
| Verbatim            | 1         | 2      | 1.08%   |
| Unknown             | 1         | 1      | 1.08%   |
| Toshiba             | 1         | 2      | 1.08%   |
| SK hynix            | 1         | 1      | 1.08%   |
| RZX                 | 1         | 1      | 1.08%   |
| Patriot             | 1         | 1      | 1.08%   |
| NGFF                | 1         | 1      | 1.08%   |
| Netac               | 1         | 1      | 1.08%   |
| Micron Technology   | 1         | 1      | 1.08%   |
| LITEONIT            | 1         | 1      | 1.08%   |
| LITEON              | 1         | 1      | 1.08%   |
| Kston               | 1         | 1      | 1.08%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.08%   |
| JMicron Technology  | 1         | 1      | 1.08%   |
| Intenso             | 1         | 1      | 1.08%   |
| Intel               | 1         | 1      | 1.08%   |
| GOODRAM             | 1         | 1      | 1.08%   |
| Corsair             | 1         | 1      | 1.08%   |
| BAITITON            | 1         | 1      | 1.08%   |
| ASMT                | 1         | 1      | 1.08%   |
| Apple               | 1         | 1      | 1.08%   |
| addlink             | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 77        | 114    | 35%     |
| HDD     | 68        | 137    | 30.91%  |
| NVMe    | 59        | 80     | 26.82%  |
| MMC     | 12        | 17     | 5.45%   |
| Unknown | 4         | 5      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 232    | 56.78%  |
| NVMe | 59        | 80     | 29.65%  |
| SAS  | 15        | 24     | 7.54%   |
| MMC  | 12        | 17     | 6.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 131    | 52.66%  |
| 0.51-1.0   | 42        | 65     | 24.85%  |
| 1.01-2.0   | 20        | 25     | 11.83%  |
| 3.01-4.0   | 10        | 13     | 5.92%   |
| 4.01-10.0  | 6         | 11     | 3.55%   |
| 2.01-3.0   | 2         | 6      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 45        | 26.63%  |
| 251-500        | 39        | 23.08%  |
| 501-1000       | 23        | 13.61%  |
| More than 3000 | 15        | 8.88%   |
| 1001-2000      | 14        | 8.28%   |
| 51-100         | 10        | 5.92%   |
| 21-50          | 8         | 4.73%   |
| 1-20           | 8         | 4.73%   |
| 2001-3000      | 5         | 2.96%   |
| Unknown        | 2         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 26.63%  |
| 101-250        | 28        | 16.57%  |
| 21-50          | 27        | 15.98%  |
| 51-100         | 22        | 13.02%  |
| 251-500        | 12        | 7.1%    |
| 501-1000       | 12        | 7.1%    |
| More than 3000 | 10        | 5.92%   |
| 1001-2000      | 8         | 4.73%   |
| 2001-3000      | 3         | 1.78%   |
| Unknown        | 2         | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 3         | 3      | 18.75%  |
| WDC WD5000AADS-00S9B0 500GB                  | 1         | 1      | 6.25%   |
| WDC WD1001FALS-40Y6A0 1TB                    | 1         | 1      | 6.25%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 6.25%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 960 PRO 1TB          | 1         | 1      | 6.25%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 6.25%   |
| NGFF 2280 256GB SSD                          | 1         | 1      | 6.25%   |
| Netac SSD 256GB                              | 1         | 1      | 6.25%   |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 6.25%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 6.25%   |
| DAS TerraMaster 500GB                        | 1         | 3      | 6.25%   |
| China SSD 180GB                              | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 37.5%   |
| WDC                 | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 2      | 12.5%   |
| NGFF                | 1         | 1      | 6.25%   |
| Netac               | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| DAS                 | 1         | 3      | 6.25%   |
| China               | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 60%     |
| WDC     | 2         | 2      | 20%     |
| Hitachi | 1         | 1      | 10%     |
| DAS     | 1         | 3      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 12     | 60%     |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 2         | 2      | 13.33%  |

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
| Works    | 99        | 189    | 53.8%   |
| Detected | 70        | 146    | 38.04%  |
| Malfunc  | 15        | 18     | 8.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 102       | 49.51%  |
| AMD                            | 36        | 17.48%  |
| Samsung Electronics            | 22        | 10.68%  |
| Phison Electronics             | 9         | 4.37%   |
| SanDisk                        | 7         | 3.4%    |
| SK hynix                       | 4         | 1.94%   |
| Kingston Technology Company    | 4         | 1.94%   |
| ASMedia Technology             | 4         | 1.94%   |
| Toshiba America Info Systems   | 3         | 1.46%   |
| Silicon Motion                 | 2         | 0.97%   |
| KIOXIA                         | 2         | 0.97%   |
| ADATA Technology               | 2         | 0.97%   |
| Union Memory (Shenzhen)        | 1         | 0.49%   |
| Solid State Storage Technology | 1         | 0.49%   |
| Realtek Semiconductor          | 1         | 0.49%   |
| Nvidia                         | 1         | 0.49%   |
| Micron Technology              | 1         | 0.49%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.49%   |
| Marvell Technology Group       | 1         | 0.49%   |
| Lenovo                         | 1         | 0.49%   |
| Hewlett-Packard                | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 8.75%   |
| Samsung NVMe SSD Controller 980                                                | 11        | 4.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 3.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7         | 2.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.5%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 2.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 2.08%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 1.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.67%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 1.67%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.67%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.67%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 1.25%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.25%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.83%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.83%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.83%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 118       | 54.63%  |
| NVMe | 59        | 27.31%  |
| IDE  | 21        | 9.72%   |
| RAID | 18        | 8.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 116       | 70.73%  |
| AMD    | 43        | 26.22%  |
| ARM    | 5         | 3.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ARM Processor                               | 4         | 2.44%   |
| Intel Core i7-3517U CPU @ 1.90GHz           | 3         | 1.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.83%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.22%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.22%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2         | 1.22%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2         | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.22%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.22%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 1.22%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.22%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.61%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1         | 0.61%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1         | 0.61%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.61%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1         | 0.61%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.61%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.61%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.61%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.61%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.61%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1         | 0.61%   |
| Intel Pentium 4 CPU 3.06GHz                 | 1         | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.61%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.61%   |
| Intel Core i7-8705G CPU @ 3.10GHz           | 1         | 0.61%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.61%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1         | 0.61%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.61%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.61%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.61%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 17.68%  |
| Intel Core i7           | 25        | 15.24%  |
| Other                   | 23        | 14.02%  |
| Intel Core i3           | 13        | 7.93%   |
| AMD Ryzen 5             | 13        | 7.93%   |
| Intel Core 2 Duo        | 8         | 4.88%   |
| Intel Celeron           | 8         | 4.88%   |
| Intel Pentium           | 6         | 3.66%   |
| AMD Ryzen 7             | 6         | 3.66%   |
| Intel Xeon              | 5         | 3.05%   |
| AMD Ryzen 3             | 3         | 1.83%   |
| AMD Athlon II X2        | 3         | 1.83%   |
| AMD A6                  | 3         | 1.83%   |
| AMD Ryzen 9             | 2         | 1.22%   |
| AMD A8                  | 2         | 1.22%   |
| AMD A4                  | 2         | 1.22%   |
| Intel Pentium Silver    | 1         | 0.61%   |
| Intel Pentium Dual-Core | 1         | 0.61%   |
| Intel Pentium 4         | 1         | 0.61%   |
| Intel Core 2 Quad       | 1         | 0.61%   |
| AMD Turion II Neo       | 1         | 0.61%   |
| AMD Turion 64 Mobile    | 1         | 0.61%   |
| AMD Ryzen 7 PRO         | 1         | 0.61%   |
| AMD Phenom II X6        | 1         | 0.61%   |
| AMD FX                  | 1         | 0.61%   |
| AMD E1                  | 1         | 0.61%   |
| AMD E                   | 1         | 0.61%   |
| AMD Athlon X2           | 1         | 0.61%   |
| AMD Athlon II X4        | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 68        | 41.46%  |
| 2       | 56        | 34.15%  |
| 6       | 17        | 10.37%  |
| 8       | 11        | 6.71%   |
| 1       | 4         | 2.44%   |
| 12      | 3         | 1.83%   |
| Unknown | 2         | 1.22%   |
| 16      | 1         | 0.61%   |
| 14      | 1         | 0.61%   |
| 10      | 1         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 160       | 97.56%  |
| 2       | 2         | 1.22%   |
| Unknown | 2         | 1.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 103       | 62.8%   |
| 1       | 59        | 35.98%  |
| Unknown | 2         | 1.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 163       | 99.39%  |
| Unknown        | 1         | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 39.77%  |
| 0x306a9    | 9         | 5.26%   |
| 0x806c1    | 7         | 4.09%   |
| 0x806ec    | 4         | 2.34%   |
| 0x506e3    | 4         | 2.34%   |
| 0x306c3    | 4         | 2.34%   |
| 0x206a7    | 4         | 2.34%   |
| 0x0a50000c | 4         | 2.34%   |
| 0xa0671    | 3         | 1.75%   |
| 0x906ea    | 3         | 1.75%   |
| 0x906e9    | 3         | 1.75%   |
| 0x806ea    | 3         | 1.75%   |
| 0x806d1    | 3         | 1.75%   |
| 0x40651    | 3         | 1.75%   |
| 0x20655    | 3         | 1.75%   |
| 0x1067a    | 3         | 1.75%   |
| 0x08108109 | 3         | 1.75%   |
| 0x706e5    | 2         | 1.17%   |
| 0x706a8    | 2         | 1.17%   |
| 0x6fd      | 2         | 1.17%   |
| 0x506c9    | 2         | 1.17%   |
| 0x30678    | 2         | 1.17%   |
| 0x08608103 | 2         | 1.17%   |
| 0x0700010f | 2         | 1.17%   |
| 0x06001119 | 2         | 1.17%   |
| 0xa0653    | 1         | 0.58%   |
| 0x906ed    | 1         | 0.58%   |
| 0x906c0    | 1         | 0.58%   |
| 0x906a3    | 1         | 0.58%   |
| 0x90672    | 1         | 0.58%   |
| 0x806eb    | 1         | 0.58%   |
| 0x806e9    | 1         | 0.58%   |
| 0x6fb      | 1         | 0.58%   |
| 0x406c4    | 1         | 0.58%   |
| 0x306f2    | 1         | 0.58%   |
| 0x206d7    | 1         | 0.58%   |
| 0x206c2    | 1         | 0.58%   |
| 0x106e5    | 1         | 0.58%   |
| 0x10677    | 1         | 0.58%   |
| 0x10676    | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 12.65%  |
| IvyBridge        | 15        | 9.04%   |
| Unknown          | 14        | 8.43%   |
| Haswell          | 13        | 7.83%   |
| IceLake          | 9         | 5.42%   |
| TigerLake        | 8         | 4.82%   |
| Penryn           | 7         | 4.22%   |
| Zen+             | 6         | 3.61%   |
| Zen 3            | 6         | 3.61%   |
| Westmere         | 6         | 3.61%   |
| Skylake          | 6         | 3.61%   |
| SandyBridge      | 6         | 3.61%   |
| K10              | 6         | 3.61%   |
| Zen 2            | 5         | 3.01%   |
| Zen              | 5         | 3.01%   |
| Silvermont       | 4         | 2.41%   |
| Goldmont plus    | 4         | 2.41%   |
| Piledriver       | 3         | 1.81%   |
| Core             | 3         | 1.81%   |
| Nehalem          | 2         | 1.2%    |
| Jaguar           | 2         | 1.2%    |
| Goldmont         | 2         | 1.2%    |
| Excavator        | 2         | 1.2%    |
| CometLake        | 2         | 1.2%    |
| Alderlake Hybrid | 2         | 1.2%    |
| Puma             | 1         | 0.6%    |
| NetBurst         | 1         | 0.6%    |
| K8 Hammer        | 1         | 0.6%    |
| K8 & K10 hybrid  | 1         | 0.6%    |
| Bulldozer        | 1         | 0.6%    |
| Broadwell        | 1         | 0.6%    |
| Bobcat           | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 89        | 47.85%  |
| AMD                        | 53        | 28.49%  |
| Nvidia                     | 42        | 22.58%  |
| Matrox Electronics Systems | 1         | 0.54%   |
| ASPEED Technology          | 1         | 0.54%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 9         | 4.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 3.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 2.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 2.13%   |
| Intel HD Graphics 530                                                       | 4         | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 4         | 2.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 2.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 1.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 1.6%    |
| Intel UHD Graphics 620                                                      | 3         | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.6%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 3         | 1.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 1.6%    |
| AMD Renoir                                                                  | 3         | 1.6%    |
| AMD Lucienne                                                                | 3         | 1.6%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.06%   |
| Nvidia GM108M [GeForce MX130]                                               | 2         | 1.06%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.06%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2         | 1.06%   |
| Intel JasperLake [UHD Graphics]                                             | 2         | 1.06%   |
| Intel HD Graphics 630                                                       | 2         | 1.06%   |
| Intel HD Graphics 620                                                       | 2         | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 2         | 1.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 1.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.53%   |
| Nvidia TU117M                                                               | 1         | 0.53%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.53%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 41.46%  |
| 1 x AMD        | 40        | 24.39%  |
| 1 x Nvidia     | 24        | 14.63%  |
| Intel + Nvidia | 13        | 7.93%   |
| Intel + AMD    | 6         | 3.66%   |
| Other          | 5         | 3.05%   |
| AMD + Nvidia   | 5         | 3.05%   |
| 2 x AMD        | 1         | 0.61%   |
| 1 x Matrox     | 1         | 0.61%   |
| AMD + ASPEED   | 1         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 131       | 79.88%  |
| Proprietary | 25        | 15.24%  |
| Unknown     | 8         | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 68.48%  |
| 0.01-0.5   | 17        | 10.3%   |
| 0.51-1.0   | 13        | 7.88%   |
| 1.01-2.0   | 9         | 5.45%   |
| 3.01-4.0   | 6         | 3.64%   |
| 5.01-6.0   | 4         | 2.42%   |
| 7.01-8.0   | 1         | 0.61%   |
| 2.01-3.0   | 1         | 0.61%   |
| 8.01-16.0  | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 27        | 14.59%  |
| BOE                     | 17        | 9.19%   |
| Chimei Innolux          | 16        | 8.65%   |
| Goldstar                | 12        | 6.49%   |
| AU Optronics            | 12        | 6.49%   |
| LG Display              | 11        | 5.95%   |
| Dell                    | 10        | 5.41%   |
| Acer                    | 9         | 4.86%   |
| Philips                 | 8         | 4.32%   |
| Hewlett-Packard         | 7         | 3.78%   |
| Apple                   | 5         | 2.7%    |
| Lenovo                  | 4         | 2.16%   |
| Iiyama                  | 4         | 2.16%   |
| Chi Mei Optoelectronics | 4         | 2.16%   |
| BenQ                    | 4         | 2.16%   |
| Ancor Communications    | 4         | 2.16%   |
| PANDA                   | 3         | 1.62%   |
| AOC                     | 3         | 1.62%   |
| Vizio                   | 2         | 1.08%   |
| ViewSonic               | 2         | 1.08%   |
| Sony                    | 2         | 1.08%   |
| Sharp                   | 2         | 1.08%   |
| Westinghouse            | 1         | 0.54%   |
| VMO                     | 1         | 0.54%   |
| Vita                    | 1         | 0.54%   |
| Unknown                 | 1         | 0.54%   |
| Toshiba                 | 1         | 0.54%   |
| Sceptre Tech            | 1         | 0.54%   |
| Packard Bell            | 1         | 0.54%   |
| NEC Computers           | 1         | 0.54%   |
| Medion                  | 1         | 0.54%   |
| LG Philips              | 1         | 0.54%   |
| Insignia                | 1         | 0.54%   |
| IBM                     | 1         | 0.54%   |
| Hitachi                 | 1         | 0.54%   |
| HannStar                | 1         | 0.54%   |
| Gateway                 | 1         | 0.54%   |
| CS_                     | 1         | 0.54%   |
| ASUSTek Computer        | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                | 2         | 1.07%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 1.07%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 2         | 1.07%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 2         | 1.07%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch               | 2         | 1.07%   |
| Acer K272HL H ACR087E 1920x1080 597x336mm 27.0-inch                  | 2         | 1.07%   |
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                   | 2         | 1.07%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch         | 1         | 0.53%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch            | 1         | 0.53%   |
| Vizio XVT553SV VIZ0063 1920x1080 1210x680mm 54.6-inch                | 1         | 0.53%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                 | 1         | 0.53%   |
| Vita LCD Monitor VIT0780 1920x1080                                   | 1         | 0.53%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch        | 1         | 0.53%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch        | 1         | 0.53%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                 | 1         | 0.53%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch             | 1         | 0.53%   |
| Sony Nvidia Defaul t Flat Panel SNY05FA 1366x768 309x174mm 14.0-inch | 1         | 0.53%   |
| Sony LCD Monitor TV 3840x1080                                        | 1         | 0.53%   |
| Sony LCD Monitor TV                                                  | 1         | 0.53%   |
| Sharp LCD Monitor SHP1526 1920x1280 274x183mm 13.0-inch              | 1         | 0.53%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 0.53%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch               | 1         | 0.53%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1         | 0.53%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch  | 1         | 0.53%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch  | 1         | 0.53%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 0.53%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch   | 1         | 0.53%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch    | 1         | 0.53%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch    | 1         | 0.53%   |
| Samsung Electronics S24E650 SAM0CB9 1920x1080 521x293mm 23.5-inch    | 1         | 0.53%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1         | 0.53%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch    | 1         | 0.53%   |
| Samsung Electronics S22E450 SAM0C79 1920x1080 477x268mm 21.5-inch    | 1         | 0.53%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1         | 0.53%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 83        | 49.11%  |
| 1366x768 (WXGA)    | 26        | 15.38%  |
| 2560x1440 (QHD)    | 9         | 5.33%   |
| 3840x2160 (4K)     | 8         | 4.73%   |
| 1440x900 (WXGA+)   | 8         | 4.73%   |
| 1680x1050 (WSXGA+) | 6         | 3.55%   |
| 1280x800 (WXGA)    | 4         | 2.37%   |
| 3440x1440          | 3         | 1.78%   |
| 2560x1600          | 3         | 1.78%   |
| 1280x1024 (SXGA)   | 3         | 1.78%   |
| 2160x1440          | 2         | 1.18%   |
| 1920x1280          | 2         | 1.18%   |
| 1920x1200 (WUXGA)  | 2         | 1.18%   |
| 1600x900 (HD+)     | 2         | 1.18%   |
| 1360x768           | 2         | 1.18%   |
| 3840x2400          | 1         | 0.59%   |
| 3840x1080          | 1         | 0.59%   |
| 2880x1620          | 1         | 0.59%   |
| 2560x1080          | 1         | 0.59%   |
| 1280x720 (HD)      | 1         | 0.59%   |
| Unknown            | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 40        | 21.98%  |
| 27      | 20        | 10.99%  |
| 23      | 15        | 8.24%   |
| 13      | 15        | 8.24%   |
| 24      | 14        | 7.69%   |
| 21      | 14        | 7.69%   |
| 17      | 14        | 7.69%   |
| 14      | 11        | 6.04%   |
| 31      | 9         | 4.95%   |
| 34      | 4         | 2.2%    |
| 19      | 4         | 2.2%    |
| 54      | 3         | 1.65%   |
| 22      | 3         | 1.65%   |
| 12      | 3         | 1.65%   |
| Unknown | 3         | 1.65%   |
| 18      | 2         | 1.1%    |
| 11      | 2         | 1.1%    |
| 84      | 1         | 0.55%   |
| 74      | 1         | 0.55%   |
| 40      | 1         | 0.55%   |
| 28      | 1         | 0.55%   |
| 25      | 1         | 0.55%   |
| 16      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 36.11%  |
| 501-600     | 46        | 25.56%  |
| 401-500     | 23        | 12.78%  |
| 601-700     | 12        | 6.67%   |
| 201-300     | 11        | 6.11%   |
| 351-400     | 10        | 5.56%   |
| 701-800     | 4         | 2.22%   |
| 1001-1500   | 3         | 1.67%   |
| Unknown     | 3         | 1.67%   |
| 1501-2000   | 2         | 1.11%   |
| 801-900     | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 117       | 75%     |
| 16/10   | 26        | 16.67%  |
| 5/4     | 4         | 2.56%   |
| 3/2     | 4         | 2.56%   |
| 21/9    | 4         | 2.56%   |
| Unknown | 1         | 0.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 21.79%  |
| 201-250        | 35        | 19.55%  |
| 81-90          | 22        | 12.29%  |
| 301-350        | 20        | 11.17%  |
| 351-500        | 14        | 7.82%   |
| 151-200        | 8         | 4.47%   |
| 121-130        | 8         | 4.47%   |
| 141-150        | 6         | 3.35%   |
| More than 1000 | 5         | 2.79%   |
| 251-300        | 5         | 2.79%   |
| 71-80          | 4         | 2.23%   |
| 61-70          | 3         | 1.68%   |
| Unknown        | 3         | 1.68%   |
| 51-60          | 2         | 1.12%   |
| 131-140        | 2         | 1.12%   |
| 111-120        | 1         | 0.56%   |
| 501-1000       | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 64        | 37.43%  |
| 121-160       | 44        | 25.73%  |
| 101-120       | 43        | 25.15%  |
| 161-240       | 11        | 6.43%   |
| 1-50          | 5         | 2.92%   |
| Unknown       | 3         | 1.75%   |
| More than 240 | 1         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 124       | 75.15%  |
| 2     | 33        | 20%     |
| 0     | 5         | 3.03%   |
| 3     | 2         | 1.21%   |
| 4     | 1         | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 89        | 38.86%  |
| Intel                             | 83        | 36.24%  |
| Broadcom                          | 16        | 6.99%   |
| Qualcomm Atheros                  | 13        | 5.68%   |
| Ralink                            | 4         | 1.75%   |
| TP-Link                           | 3         | 1.31%   |
| Broadcom Limited                  | 3         | 1.31%   |
| ASIX Electronics                  | 3         | 1.31%   |
| Qualcomm Atheros Communications   | 2         | 0.87%   |
| MediaTek                          | 2         | 0.87%   |
| Marvell Technology Group          | 2         | 0.87%   |
| Ericsson Business Mobile Networks | 2         | 0.87%   |
| Raspberry Pi                      | 1         | 0.44%   |
| Quectel Wireless Solutions        | 1         | 0.44%   |
| Nvidia                            | 1         | 0.44%   |
| NetGear                           | 1         | 0.44%   |
| Microchip Technology              | 1         | 0.44%   |
| AVM                               | 1         | 0.44%   |
| ASUSTek Computer                  | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 54        | 19.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 3.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.5%    |
| Intel Wireless 8265 / 8275                                              | 7         | 2.5%    |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 2.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.79%   |
| Realtek 802.11ac NIC                                                    | 5         | 1.79%   |
| Intel Ethernet Controller I225-V                                        | 5         | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.43%   |
| Intel Wireless 7265                                                     | 4         | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.43%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 1.07%   |
| Intel Wireless 3165                                                     | 3         | 1.07%   |
| Intel Wireless 3160                                                     | 3         | 1.07%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.07%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 1.07%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.07%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 3         | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.07%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 1.07%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 0.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.71%   |
| Intel Wireless 7260                                                     | 2         | 0.71%   |
| Intel WiFi Link 5100                                                    | 2         | 0.71%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 0.71%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 48.53%  |
| Realtek Semiconductor           | 35        | 25.74%  |
| Qualcomm Atheros                | 10        | 7.35%   |
| Broadcom                        | 8         | 5.88%   |
| Ralink                          | 4         | 2.94%   |
| TP-Link                         | 3         | 2.21%   |
| Qualcomm Atheros Communications | 2         | 1.47%   |
| MediaTek                        | 2         | 1.47%   |
| Broadcom Limited                | 2         | 1.47%   |
| Quectel Wireless Solutions      | 1         | 0.74%   |
| NetGear                         | 1         | 0.74%   |
| AVM                             | 1         | 0.74%   |
| ASUSTek Computer                | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 5.11%   |
| Intel Wireless 8265 / 8275                                              | 7         | 5.11%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 4.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.65%   |
| Realtek 802.11ac NIC                                                    | 5         | 3.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 2.92%   |
| Intel Wireless 7265                                                     | 4         | 2.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 2.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.19%   |
| Intel Wireless 3165                                                     | 3         | 2.19%   |
| Intel Wireless 3160                                                     | 3         | 2.19%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 2.19%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.19%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.19%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.46%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.46%   |
| Intel Wireless 7260                                                     | 2         | 1.46%   |
| Intel WiFi Link 5100                                                    | 2         | 1.46%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.46%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.46%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.73%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.73%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.73%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.73%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.73%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.73%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 70        | 51.85%  |
| Intel                    | 43        | 31.85%  |
| Broadcom                 | 10        | 7.41%   |
| Qualcomm Atheros         | 4         | 2.96%   |
| ASIX Electronics         | 3         | 2.22%   |
| Marvell Technology Group | 2         | 1.48%   |
| Nvidia                   | 1         | 0.74%   |
| Microchip Technology     | 1         | 0.74%   |
| Broadcom Limited         | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 54        | 38.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 6.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 4.29%   |
| Intel Ethernet Controller I225-V                                               | 5         | 3.57%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 2.14%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 2.14%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 2.14%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 2.14%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 2.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.43%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 1.43%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 1.43%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.43%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.43%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.43%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.43%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2         | 1.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.71%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.71%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.71%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.71%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 0.71%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.71%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.71%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.71%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.71%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1         | 0.71%   |
| Intel Ethernet Connection (16) I219-LM                                         | 1         | 0.71%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.71%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.71%   |
| Intel 82576 Gigabit Network Connection                                         | 1         | 0.71%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.71%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 132       | 49.81%  |
| WiFi     | 130       | 49.06%  |
| Modem    | 3         | 1.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 55.56%  |
| Ethernet | 76        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 87        | 53.05%  |
| 1     | 65        | 39.63%  |
| 0     | 6         | 3.66%   |
| 3     | 4         | 2.44%   |
| 4     | 2         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 111       | 67.27%  |
| Yes  | 54        | 32.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 47.62%  |
| Realtek Semiconductor           | 17        | 16.19%  |
| Broadcom                        | 10        | 9.52%   |
| IMC Networks                    | 7         | 6.67%   |
| Cambridge Silicon Radio         | 5         | 4.76%   |
| Apple                           | 5         | 4.76%   |
| Ralink                          | 2         | 1.9%    |
| Toshiba                         | 1         | 0.95%   |
| Qualcomm Atheros Communications | 1         | 0.95%   |
| MediaTek                        | 1         | 0.95%   |
| Integrated System Solution      | 1         | 0.95%   |
| Hewlett-Packard                 | 1         | 0.95%   |
| Foxconn International           | 1         | 0.95%   |
| Foxconn / Hon Hai               | 1         | 0.95%   |
| Belkin Components               | 1         | 0.95%   |
| ASUSTek Computer                | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 17        | 16.19%  |
| Intel Bluetooth wireless interface                                                  | 16        | 15.24%  |
| Realtek Bluetooth Radio                                                             | 12        | 11.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 3.81%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 3.81%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.86%   |
| Intel AX210 Bluetooth                                                               | 3         | 2.86%   |
| Intel AX200 Bluetooth                                                               | 3         | 2.86%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.9%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.9%    |
| IMC Networks Bluetooth Device                                                       | 2         | 1.9%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 2         | 1.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.9%    |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.9%    |
| Apple Bluetooth Host Controller                                                     | 2         | 1.9%    |
| Toshiba Bluetooth Device                                                            | 1         | 0.95%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.95%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.95%   |
| MediaTek Wireless_Device                                                            | 1         | 0.95%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.95%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.95%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.95%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.95%   |
| Broadcom Bluetooth 3.0 USB Dongle                                                   | 1         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.95%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.95%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.95%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.95%   |
| Belkin Components F8T013 Bluetooth Adapter                                          | 1         | 0.95%   |
| ASUS Bluetooth Radio                                                                | 1         | 0.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 112       | 49.12%  |
| AMD                     | 52        | 22.81%  |
| Nvidia                  | 35        | 15.35%  |
| C-Media Electronics     | 7         | 3.07%   |
| ASUSTek Computer        | 4         | 1.75%   |
| Generalplus Technology  | 3         | 1.32%   |
| Logitech                | 2         | 0.88%   |
| JMTek                   | 2         | 0.88%   |
| TerraTec Electronic     | 1         | 0.44%   |
| Meizu                   | 1         | 0.44%   |
| Kingston Technology     | 1         | 0.44%   |
| GN Netcom               | 1         | 0.44%   |
| DSEA A/S                | 1         | 0.44%   |
| Creative Technology     | 1         | 0.44%   |
| Corsair                 | 1         | 0.44%   |
| Cambridge Silicon Radio | 1         | 0.44%   |
| BlackWeb                | 1         | 0.44%   |
| Anlya.cn                | 1         | 0.44%   |
| Alesis                  | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 20        | 7.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 5.93%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 2.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 2.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 2.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 2.22%   |
| AMD FCH Azalia Controller                                                  | 6         | 2.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.85%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.85%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.48%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.11%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.11%   |
| Generalplus Technology USB Audio Device                                    | 3         | 1.11%   |
| ASUSTek Computer USB Audio                                                 | 3         | 1.11%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.11%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.74%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 19.7%   |
| SK hynix            | 24        | 18.18%  |
| Kingston            | 16        | 12.12%  |
| Unknown             | 13        | 9.85%   |
| Micron Technology   | 13        | 9.85%   |
| Crucial             | 13        | 9.85%   |
| Corsair             | 9         | 6.82%   |
| Unknown (ABCD)      | 4         | 3.03%   |
| G.Skill             | 4         | 3.03%   |
| Nanya Technology    | 3         | 2.27%   |
| Ramaxel Technology  | 2         | 1.52%   |
| Unifosa             | 1         | 0.76%   |
| Hewlett-Packard     | 1         | 0.76%   |
| HBS                 | 1         | 0.76%   |
| A-DATA Technology   | 1         | 0.76%   |
| Unknown             | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 2.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 2.1%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.4%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.4%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.7%    |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.7%    |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.7%    |
| Unknown RAM Module 4GB DIMM                                      | 1         | 0.7%    |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.7%    |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.7%    |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s          | 1         | 0.7%    |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.7%    |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 0.7%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.7%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.7%    |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s              | 1         | 0.7%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s             | 1         | 0.7%    |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.7%    |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.7%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.7%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 56        | 49.12%  |
| DDR3    | 39        | 34.21%  |
| LPDDR4  | 7         | 6.14%   |
| DDR2    | 6         | 5.26%   |
| DDR5    | 2         | 1.75%   |
| SDRAM   | 1         | 0.88%   |
| LPDDR3  | 1         | 0.88%   |
| DDR     | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 57.63%  |
| DIMM         | 39        | 33.05%  |
| Row Of Chips | 9         | 7.63%   |
| Chip         | 1         | 0.85%   |
| Unknown      | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 47        | 37.01%  |
| 4096  | 38        | 29.92%  |
| 16384 | 23        | 18.11%  |
| 2048  | 12        | 9.45%   |
| 32768 | 4         | 3.15%   |
| 1024  | 3         | 2.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 26        | 21.31%  |
| 3200    | 23        | 18.85%  |
| 2667    | 15        | 12.3%   |
| 2400    | 15        | 12.3%   |
| 1333    | 9         | 7.38%   |
| Unknown | 4         | 3.28%   |
| 2133    | 3         | 2.46%   |
| 1334    | 3         | 2.46%   |
| 4800    | 2         | 1.64%   |
| 4267    | 2         | 1.64%   |
| 3600    | 2         | 1.64%   |
| 800     | 2         | 1.64%   |
| 667     | 2         | 1.64%   |
| 4000    | 1         | 0.82%   |
| 3466    | 1         | 0.82%   |
| 3400    | 1         | 0.82%   |
| 3333    | 1         | 0.82%   |
| 3100    | 1         | 0.82%   |
| 2800    | 1         | 0.82%   |
| 2747    | 1         | 0.82%   |
| 2666    | 1         | 0.82%   |
| 2048    | 1         | 0.82%   |
| 1867    | 1         | 0.82%   |
| 1866    | 1         | 0.82%   |
| 1648    | 1         | 0.82%   |
| 1067    | 1         | 0.82%   |
| 1066    | 1         | 0.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP ScanJet G4010        | 1         | 33.33%  |
| Canon CanoScan LiDE 120 | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 24        | 24.49%  |
| Realtek Semiconductor                  | 12        | 12.24%  |
| Logitech                               | 8         | 8.16%   |
| IMC Networks                           | 7         | 7.14%   |
| Quanta                                 | 6         | 6.12%   |
| Syntek                                 | 5         | 5.1%    |
| Apple                                  | 5         | 5.1%    |
| Suyin                                  | 4         | 4.08%   |
| Microdia                               | 4         | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.06%   |
| Acer                                   | 3         | 3.06%   |
| Sunplus Innovation Technology          | 2         | 2.04%   |
| Luxvisions Innotech Limited            | 2         | 2.04%   |
| Lite-On Technology                     | 2         | 2.04%   |
| ARC International                      | 2         | 2.04%   |
| Z-Star Microelectronics                | 1         | 1.02%   |
| U0AS01A-0                              | 1         | 1.02%   |
| Sonix Technology                       | 1         | 1.02%   |
| Ricoh                                  | 1         | 1.02%   |
| Razer USA                              | 1         | 1.02%   |
| Microsoft                              | 1         | 1.02%   |
| Lenovo                                 | 1         | 1.02%   |
| Generalplus Technology                 | 1         | 1.02%   |
| Alcor Micro                            | 1         | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Syntek Integrated Camera                      | 4         | 4.08%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 4.08%   |
| Chicony HP HD Camera                          | 4         | 4.08%   |
| Realtek USB Camera                            | 3         | 3.06%   |
| Microdia Webcam Vitade AF                     | 3         | 3.06%   |
| Chicony integrated camera                     | 3         | 3.06%   |
| Apple Built-in iSight                         | 3         | 3.06%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 2.04%   |
| Realtek MTD camera                            | 2         | 2.04%   |
| Realtek Integrated_Webcam_HD                  | 2         | 2.04%   |
| Realtek Integrated Webcam HD                  | 2         | 2.04%   |
| Quanta HD User Facing                         | 2         | 2.04%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.04%   |
| Logitech Webcam C270                          | 2         | 2.04%   |
| IMC Networks Integrated Camera                | 2         | 2.04%   |
| Chicony HP Webcam                             | 2         | 2.04%   |
| Chicony HD User Facing                        | 2         | 2.04%   |
| ARC International Camera                      | 2         | 2.04%   |
| Acer Integrated Camera                        | 2         | 2.04%   |
| Z-Star HP 3-MegaPixel Webcam GX607AA          | 1         | 1.02%   |
| U0AS01A-0 U0AS01A-0                           | 1         | 1.02%   |
| Syntek Lenovo EasyCamera                      | 1         | 1.02%   |
| Suyin USB 2.0 Camera                          | 1         | 1.02%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 1.02%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 1.02%   |
| Sunplus HP Truevision HD                      | 1         | 1.02%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 1.02%   |
| Ricoh Dell Laptop Integrated Webcam           | 1         | 1.02%   |
| Realtek NexiGo N660P FHD Webcam               | 1         | 1.02%   |
| Realtek Laptop_Integrated_Webcam_HD           | 1         | 1.02%   |
| Realtek HP 1.0MP High Definition Webcam       | 1         | 1.02%   |
| Razer USA Gaming Webcam [Kiyo]                | 1         | 1.02%   |
| Quanta ov9734_techfront_camera                | 1         | 1.02%   |
| Quanta HP Webcam-101                          | 1         | 1.02%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.02%   |
| Quanta Chromebook HD Camera                   | 1         | 1.02%   |
| Microsoft LifeCam VX-500 [1357]               | 1         | 1.02%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.02%   |
| Logitech Webcam C925e                         | 1         | 1.02%   |
| Logitech StreamCam                            | 1         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 25%     |
| Synaptics                  | 4         | 25%     |
| Shenzhen Goodix Technology | 4         | 25%     |
| Upek                       | 2         | 12.5%   |
| Elan Microelectronics      | 1         | 6.25%   |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 6.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Synaptics  WBDI                                                            | 1         | 6.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                                           | 1         | 6.25%   |
| AuthenTec AES1600                                                          | 1         | 6.25%   |
| Unknown                                                                    | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 7         | 46.67%  |
| Alcor Micro           | 4         | 26.67%  |
| Upek                  | 1         | 6.67%   |
| SCM Microsystems      | 1         | 6.67%   |
| O2 Micro              | 1         | 6.67%   |
| Advanced Card Systems | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 4         | 26.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 13.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.67%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Broadcom 5880                                                                | 1         | 6.67%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 119       | 71.69%  |
| 1     | 37        | 22.29%  |
| 2     | 7         | 4.22%   |
| 3     | 3         | 1.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 16        | 28.57%  |
| Chipcard              | 15        | 26.79%  |
| Net/wireless          | 6         | 10.71%  |
| Graphics card         | 6         | 10.71%  |
| Bluetooth             | 5         | 8.93%   |
| Camera                | 3         | 5.36%   |
| Unassigned class      | 1         | 1.79%   |
| Network               | 1         | 1.79%   |
| Multimedia controller | 1         | 1.79%   |
| Flash memory          | 1         | 1.79%   |
| Card reader           | 1         | 1.79%   |

