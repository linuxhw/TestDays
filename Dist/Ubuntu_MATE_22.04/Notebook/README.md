Ubuntu MATE 22.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 235

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | [14751f18b3](https://linux-hardware.org/?probe=14751f18b3) | Apr 01, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| Notebook      | NJx0MU                      | [bd4eec08fb](https://linux-hardware.org/?probe=bd4eec08fb) | Mar 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Notebook      | NJx0MU                      | [5a95cd6ad5](https://linux-hardware.org/?probe=5a95cd6ad5) | Mar 26, 2023 |
| ASUSTek       | X550LN                      | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| Notebook      | NJx0MU                      | [cd8f53a887](https://linux-hardware.org/?probe=cd8f53a887) | Mar 19, 2023 |
| Notebook      | NJx0MU                      | [45a412e241](https://linux-hardware.org/?probe=45a412e241) | Mar 18, 2023 |
| ASUSTek       | X550LN                      | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| ASUSTek       | K93SV                       | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [406d19d44f](https://linux-hardware.org/?probe=406d19d44f) | Mar 12, 2023 |
| Notebook      | NJx0MU                      | [d5426d5f1e](https://linux-hardware.org/?probe=d5426d5f1e) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | [729d9395f0](https://linux-hardware.org/?probe=729d9395f0) | Mar 11, 2023 |
| HP            | Laptop 15s-eq0xxx           | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| HP            | Presario CQ61               | [0eab7ae44e](https://linux-hardware.org/?probe=0eab7ae44e) | Mar 09, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | [cb7ac03a2a](https://linux-hardware.org/?probe=cb7ac03a2a) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | [48cf9d748f](https://linux-hardware.org/?probe=48cf9d748f) | Mar 05, 2023 |
| Notebook      | NJx0MU                      | [05934ca860](https://linux-hardware.org/?probe=05934ca860) | Mar 04, 2023 |
| Acer          | Aspire ES1-523              | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | [be909f0882](https://linux-hardware.org/?probe=be909f0882) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | [884979d592](https://linux-hardware.org/?probe=884979d592) | Mar 01, 2023 |
| Notebook      | NJx0MU                      | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| Sony          | VGN-Z21WRN_B                | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Notebook      | NJx0MU                      | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| HP            | Laptop 15s-fq5xxx           | [fa50111733](https://linux-hardware.org/?probe=fa50111733) | Feb 20, 2023 |
| Notebook      | NJx0MU                      | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | [e08dcd6c59](https://linux-hardware.org/?probe=e08dcd6c59) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | [e2cc024607](https://linux-hardware.org/?probe=e2cc024607) | Feb 18, 2023 |
| Sony          | VPCEB2Z1E                   | [5c172121ab](https://linux-hardware.org/?probe=5c172121ab) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Notebook      | NJx0MU                      | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| ASUSTek       | X541UAK                     | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Acer          | Aspire ES1-523              | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| HP            | 240 G3                      | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| Sony          | VPCEH1E1E                   | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Notebook      | NJx0MU                      | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Dell          | Precision 7550              | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Notebook      | NJx0MU                      | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Notebook      | NJx0MU                      | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [4333734c92](https://linux-hardware.org/?probe=4333734c92) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Notebook      | NJx0MU                      | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| Notebook      | NJx0MU                      | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Google        | Relm                        | [44fb1d9db1](https://linux-hardware.org/?probe=44fb1d9db1) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| Dell          | Latitude 5410               | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| Notebook      | NJx0MU                      | [e76a4c32dc](https://linux-hardware.org/?probe=e76a4c32dc) | Jan 17, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | [b4629bd83f](https://linux-hardware.org/?probe=b4629bd83f) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | [cdd815de42](https://linux-hardware.org/?probe=cdd815de42) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | [ff52c2505f](https://linux-hardware.org/?probe=ff52c2505f) | Jan 13, 2023 |
| HP            | 15                          | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| Notebook      | NJx0MU                      | [03505c402c](https://linux-hardware.org/?probe=03505c402c) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | [7ee7875a97](https://linux-hardware.org/?probe=7ee7875a97) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | [efd4eaee02](https://linux-hardware.org/?probe=efd4eaee02) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | [8b7d2f1a46](https://linux-hardware.org/?probe=8b7d2f1a46) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | [05c69304bb](https://linux-hardware.org/?probe=05c69304bb) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [2cb5d2f306](https://linux-hardware.org/?probe=2cb5d2f306) | Jan 05, 2023 |
| Notebook      | NJx0MU                      | [fc365670d0](https://linux-hardware.org/?probe=fc365670d0) | Jan 05, 2023 |
| Dell          | Precision 7520              | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| Acer          | Aspire 5530                 | [8c12909b0a](https://linux-hardware.org/?probe=8c12909b0a) | Jan 04, 2023 |
| Lenovo        | G500 20236                  | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| Notebook      | NJx0MU                      | [0eb54f1078](https://linux-hardware.org/?probe=0eb54f1078) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [7ac222385a](https://linux-hardware.org/?probe=7ac222385a) | Dec 28, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [faf2c0e5d7](https://linux-hardware.org/?probe=faf2c0e5d7) | Dec 28, 2022 |
| HP            | ZBook 17 G5                 | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f113c7d475](https://linux-hardware.org/?probe=f113c7d475) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Acer          | TravelMate 7730             | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| HP            | Compaq Presario CQ61        | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | [ac787dc7dc](https://linux-hardware.org/?probe=ac787dc7dc) | Dec 17, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | [e47e7c18c9](https://linux-hardware.org/?probe=e47e7c18c9) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| ASUSTek       | X550LN                      | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| HUAWEI        | KPL-W0X                     | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Notebook      | NJx0MU                      | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| HP            | 14                          | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Notebook      | NJx0MU                      | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| HP            | 14                          | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| HP            | ProBook 450 G6              | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Notebook      | NJx0MU                      | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Notebook      | NJx0MU                      | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Dell          | Latitude D630               | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Precision 7760              | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| HP            | ENVY Sleekbook 6            | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Acer          | Aspire 7750G                | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Chuwi         | GemiBook Pro                | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Chuwi         | GemiBook Pro                | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Dell          | Precision 7760              | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| Acer          | Aspire 5050                 | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Precision 7760              | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | Notebook                    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| LincPlus      | LINNCPLUS P1                | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| Dell          | Latitude 7420               | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| HP            | EliteBook 745 G5            | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| HP            | 15 Notebook PC              | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HONOR         | BOHK-WAX9X                  | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| Dell          | Latitude E4200              | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Compaq        | Presario CQ-23              | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| MicroByte     | ezbook                      | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Google        | Kled                        | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| Intel         | Kabylake Platform           | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Apple         | MacBook5,1                  | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| Apple         | MacBookPro6,2               | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Apple         | MacBookPro9,1               | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| IPASON        | MaxBook P1                  | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.0-56-generic      | 14        | 11.76%  |
| 5.15.0-58-generic      | 10        | 8.4%    |
| 5.15.0-53-generic      | 7         | 5.88%   |
| 5.15.0-52-generic      | 7         | 5.88%   |
| 5.15.0-43-generic      | 7         | 5.88%   |
| 5.15.0-47-generic      | 6         | 5.04%   |
| 5.15.0-46-generic      | 6         | 5.04%   |
| 5.15.0-25-generic      | 6         | 5.04%   |
| 5.15.0-60-generic      | 5         | 4.2%    |
| 5.15.0-48-generic      | 5         | 4.2%    |
| 5.15.0-40-generic      | 4         | 3.36%   |
| 5.19.0-35-generic      | 3         | 2.52%   |
| 5.19.0-32-generic      | 3         | 2.52%   |
| 5.15.0-67-generic      | 3         | 2.52%   |
| 5.15.0-57-generic      | 3         | 2.52%   |
| 5.15.0-41-generic      | 3         | 2.52%   |
| 5.15.0-30-generic      | 3         | 2.52%   |
| 5.15.0-27-generic      | 3         | 2.52%   |
| 5.15.0-52-lowlatency   | 2         | 1.68%   |
| 6.2.3-x64v1-xanmod1    | 1         | 0.84%   |
| 6.1.8-x64v1-xanmod1    | 1         | 0.84%   |
| 6.0.8-x64v1-xanmod1    | 1         | 0.84%   |
| 5.19.0-38-generic      | 1         | 0.84%   |
| 5.19.0-1021-lowlatency | 1         | 0.84%   |
| 5.19.0-1018-lowlatency | 1         | 0.84%   |
| 5.18.0-051800-generic  | 1         | 0.84%   |
| 5.17.1-051701-generic  | 1         | 0.84%   |
| 5.17.0-1003-oem        | 1         | 0.84%   |
| 5.15.0-58-lowlatency   | 1         | 0.84%   |
| 5.15.0-56-lowlatency   | 1         | 0.84%   |
| 5.15.0-50-generic      | 1         | 0.84%   |
| 5.15.0-46-lowlatency   | 1         | 0.84%   |
| 5.15.0-39-generic      | 1         | 0.84%   |
| 5.15.0-37-generic      | 1         | 0.84%   |
| 5.15.0-35-generic      | 1         | 0.84%   |
| 5.15.0-33-generic      | 1         | 0.84%   |
| 5.15.0-18-generic      | 1         | 0.84%   |
| 5.14.0-1054-oem        | 1         | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 92        | 86.79%  |
| 5.19.0  | 7         | 6.6%    |
| 6.2.3   | 1         | 0.94%   |
| 6.1.8   | 1         | 0.94%   |
| 6.0.8   | 1         | 0.94%   |
| 5.18.0  | 1         | 0.94%   |
| 5.17.1  | 1         | 0.94%   |
| 5.17.0  | 1         | 0.94%   |
| 5.14.0  | 1         | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 92        | 86.79%  |
| 5.19    | 7         | 6.6%    |
| 5.17    | 2         | 1.89%   |
| 6.2     | 1         | 0.94%   |
| 6.1     | 1         | 0.94%   |
| 6.0     | 1         | 0.94%   |
| 5.18    | 1         | 0.94%   |
| 5.14    | 1         | 0.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 102       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| MATE  | 101       | 99.02%  |
| GNOME | 1         | 0.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 100       | 98.04%  |
| Wayland | 1         | 0.98%   |
| Tty     | 1         | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 87        | 84.47%  |
| Unknown | 9         | 8.74%   |
| GDM3    | 7         | 6.8%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 37        | 35.58%  |
| fr_FR | 16        | 15.38%  |
| de_DE | 14        | 13.46%  |
| it_IT | 7         | 6.73%   |
| ru_RU | 6         | 5.77%   |
| en_AU | 3         | 2.88%   |
| pt_BR | 2         | 1.92%   |
| pl_PL | 2         | 1.92%   |
| fi_FI | 2         | 1.92%   |
| es_MX | 2         | 1.92%   |
| es_ES | 2         | 1.92%   |
| en_GB | 2         | 1.92%   |
| en_CA | 2         | 1.92%   |
| C     | 2         | 1.92%   |
| zh_TW | 1         | 0.96%   |
| zh_CN | 1         | 0.96%   |
| hu_HU | 1         | 0.96%   |
| el_GR | 1         | 0.96%   |
| de_CH | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 54.72%  |
| BIOS | 48        | 45.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 90        | 88.24%  |
| Overlay | 5         | 4.9%    |
| Zfs     | 3         | 2.94%   |
| Btrfs   | 2         | 1.96%   |
| Xfs     | 1         | 0.98%   |
| Jfs     | 1         | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 79        | 75.96%  |
| Unknown | 16        | 15.38%  |
| MBR     | 9         | 8.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 88.24%  |
| Yes       | 12        | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 65.38%  |
| Yes       | 36        | 34.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 22.55%  |
| Lenovo              | 18        | 17.65%  |
| ASUSTek Computer    | 13        | 12.75%  |
| Dell                | 12        | 11.76%  |
| Acer                | 7         | 6.86%   |
| Sony                | 4         | 3.92%   |
| Apple               | 4         | 3.92%   |
| HUAWEI              | 3         | 2.94%   |
| Toshiba             | 2         | 1.96%   |
| Intel               | 2         | 1.96%   |
| Google              | 2         | 1.96%   |
| TrekStor            | 1         | 0.98%   |
| SLIMBOOK            | 1         | 0.98%   |
| Samsung Electronics | 1         | 0.98%   |
| Notebook            | 1         | 0.98%   |
| MicroByte           | 1         | 0.98%   |
| LincPlus            | 1         | 0.98%   |
| LG Electronics      | 1         | 0.98%   |
| IPASON              | 1         | 0.98%   |
| HYPERPC             | 1         | 0.98%   |
| HONOR               | 1         | 0.98%   |
| Compaq              | 1         | 0.98%   |
| Chuwi               | 1         | 0.98%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| TrekStor Surfbook A13B               | 1         | 0.98%   |
| Toshiba Satellite P50-B-10Z          | 1         | 0.98%   |
| Toshiba Satellite C50D-A-133         | 1         | 0.98%   |
| Sony VPCEH1E1E                       | 1         | 0.98%   |
| Sony VPCEB2Z1E                       | 1         | 0.98%   |
| Sony VPCEA36FG                       | 1         | 0.98%   |
| Sony VGN-Z21WRN_B                    | 1         | 0.98%   |
| SLIMBOOK TITAN                       | 1         | 0.98%   |
| Samsung 905S3G/906S3G/915S3G/9305SG  | 1         | 0.98%   |
| Notebook NJx0MU                      | 1         | 0.98%   |
| MicroByte ezbook                     | 1         | 0.98%   |
| LincPlus LINNCPLUS P1                | 1         | 0.98%   |
| LG 17Z990-R.AAS8U1                   | 1         | 0.98%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 0.98%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 0.98%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 0.98%   |
| Lenovo ThinkPad T430 2347G5U         | 1         | 0.98%   |
| Lenovo ThinkPad T420 4238LY7         | 1         | 0.98%   |
| Lenovo ThinkPad T15 Gen 1 20S6S1HN00 | 1         | 0.98%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 0.98%   |
| Lenovo ThinkPad SL 2746AHG           | 1         | 0.98%   |
| Lenovo ThinkPad R61 8918DEG          | 1         | 0.98%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 0.98%   |
| Lenovo ThinkBook 16p Gen 2 20YM      | 1         | 0.98%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 1         | 0.98%   |
| Lenovo IdeaPad S145-14IIL 81W6       | 1         | 0.98%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 1         | 0.98%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 0.98%   |
| Lenovo IdeaPad 3 15ALC6 82KU         | 1         | 0.98%   |
| Lenovo IdeaPad 130-15AST 81H5        | 1         | 0.98%   |
| Lenovo G500 20236                    | 1         | 0.98%   |
| IPASON MaxBook P1                    | 1         | 0.98%   |
| Intel Kabylake Platform              | 1         | 0.98%   |
| Intel H81U                           | 1         | 0.98%   |
| HYPERPC PLAY                         | 1         | 0.98%   |
| HUAWEI KPL-W0X                       | 1         | 0.98%   |
| HUAWEI KLVD-WXX9                     | 1         | 0.98%   |
| HUAWEI BOHB-WAX9                     | 1         | 0.98%   |
| HONOR BOHK-WAX9X                     | 1         | 0.98%   |
| HP ZBook 17 G5                       | 1         | 0.98%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 9         | 8.82%   |
| Lenovo IdeaPad     | 5         | 4.9%    |
| Dell Precision     | 4         | 3.92%   |
| Dell Latitude      | 4         | 3.92%   |
| Acer Aspire        | 4         | 3.92%   |
| HP Pavilion        | 3         | 2.94%   |
| HP Laptop          | 3         | 2.94%   |
| HP EliteBook       | 3         | 2.94%   |
| Dell Inspiron      | 3         | 2.94%   |
| ASUS VivoBook      | 3         | 2.94%   |
| ASUS ASUS          | 3         | 2.94%   |
| Toshiba Satellite  | 2         | 1.96%   |
| Lenovo ThinkBook   | 2         | 1.96%   |
| HP ZBook           | 2         | 1.96%   |
| HP Stream          | 2         | 1.96%   |
| HP ProBook         | 2         | 1.96%   |
| HP 15              | 2         | 1.96%   |
| Acer TravelMate    | 2         | 1.96%   |
| TrekStor Surfbook  | 1         | 0.98%   |
| Sony VPCEH1E1E     | 1         | 0.98%   |
| Sony VPCEB2Z1E     | 1         | 0.98%   |
| Sony VPCEA36FG     | 1         | 0.98%   |
| Sony VGN-Z21WRN    | 1         | 0.98%   |
| SLIMBOOK TITAN     | 1         | 0.98%   |
| Samsung 905S3G     | 1         | 0.98%   |
| Notebook NJx0MU    | 1         | 0.98%   |
| MicroByte ezbook   | 1         | 0.98%   |
| LincPlus LINNCPLUS | 1         | 0.98%   |
| LG 17Z990-R.AAS8U1 | 1         | 0.98%   |
| Lenovo V15         | 1         | 0.98%   |
| Lenovo G500        | 1         | 0.98%   |
| IPASON MaxBook     | 1         | 0.98%   |
| Intel Kabylake     | 1         | 0.98%   |
| Intel H81U         | 1         | 0.98%   |
| HYPERPC PLAY       | 1         | 0.98%   |
| HUAWEI KPL-W0X     | 1         | 0.98%   |
| HUAWEI KLVD-WXX9   | 1         | 0.98%   |
| HUAWEI BOHB-WAX9   | 1         | 0.98%   |
| HONOR BOHK-WAX9X   | 1         | 0.98%   |
| HP Presario        | 1         | 0.98%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 21        | 20.59%  |
| 2020 | 10        | 9.8%    |
| 2019 | 8         | 7.84%   |
| 2018 | 8         | 7.84%   |
| 2012 | 8         | 7.84%   |
| 2022 | 6         | 5.88%   |
| 2014 | 6         | 5.88%   |
| 2013 | 5         | 4.9%    |
| 2010 | 5         | 4.9%    |
| 2008 | 5         | 4.9%    |
| 2016 | 4         | 3.92%   |
| 2011 | 4         | 3.92%   |
| 2009 | 4         | 3.92%   |
| 2015 | 3         | 2.94%   |
| 2017 | 2         | 1.96%   |
| 2007 | 2         | 1.96%   |
| 2006 | 1         | 0.98%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 102       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 96        | 91.43%  |
| Enabled  | 9         | 8.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 100       | 98.04%  |
| Yes  | 2         | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 28.43%  |
| 3.01-4.0    | 28        | 27.45%  |
| 8.01-16.0   | 18        | 17.65%  |
| 16.01-24.0  | 12        | 11.76%  |
| 32.01-64.0  | 7         | 6.86%   |
| 2.01-3.0    | 3         | 2.94%   |
| 64.01-256.0 | 3         | 2.94%   |
| 24.01-32.0  | 2         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 32        | 28.57%  |
| 1.01-2.0   | 32        | 28.57%  |
| 3.01-4.0   | 19        | 16.96%  |
| 4.01-8.0   | 16        | 14.29%  |
| 8.01-16.0  | 7         | 6.25%   |
| 0.51-1.0   | 5         | 4.46%   |
| 24.01-32.0 | 1         | 0.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 76.47%  |
| 2      | 18        | 17.65%  |
| 3      | 6         | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 62.75%  |
| Yes       | 38        | 37.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 73.53%  |
| No        | 27        | 26.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 87.38%  |
| No        | 13        | 12.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| France      | 15        | 14.71%  |
| Germany     | 13        | 12.75%  |
| USA         | 11        | 10.78%  |
| Italy       | 9         | 8.82%   |
| Spain       | 6         | 5.88%   |
| Russia      | 5         | 4.9%    |
| Brazil      | 4         | 3.92%   |
| UK          | 3         | 2.94%   |
| Turkey      | 3         | 2.94%   |
| Poland      | 3         | 2.94%   |
| Serbia      | 2         | 1.96%   |
| Mexico      | 2         | 1.96%   |
| Hungary     | 2         | 1.96%   |
| Greece      | 2         | 1.96%   |
| Finland     | 2         | 1.96%   |
| Estonia     | 2         | 1.96%   |
| Australia   | 2         | 1.96%   |
| Ukraine     | 1         | 0.98%   |
| Thailand    | 1         | 0.98%   |
| Switzerland | 1         | 0.98%   |
| Slovenia    | 1         | 0.98%   |
| Romania     | 1         | 0.98%   |
| Paraguay    | 1         | 0.98%   |
| Netherlands | 1         | 0.98%   |
| Libya       | 1         | 0.98%   |
| India       | 1         | 0.98%   |
| Hong Kong   | 1         | 0.98%   |
| Georgia     | 1         | 0.98%   |
| Colombia    | 1         | 0.98%   |
| China       | 1         | 0.98%   |
| Chile       | 1         | 0.98%   |
| Bulgaria    | 1         | 0.98%   |
| Belgium     | 1         | 0.98%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 3         | 2.86%   |
| Mannheim         | 3         | 2.86%   |
| Warsaw           | 2         | 1.9%    |
| Moscow           | 2         | 1.9%    |
| Belgrade         | 2         | 1.9%    |
| Xining           | 1         | 0.95%   |
| Viroflay         | 1         | 0.95%   |
| Villeurbanne     | 1         | 0.95%   |
| Vaudoy-en-Brie   | 1         | 0.95%   |
| Varna            | 1         | 0.95%   |
| Valenciennes     | 1         | 0.95%   |
| Turku            | 1         | 0.95%   |
| Tula             | 1         | 0.95%   |
| Tripoli          | 1         | 0.95%   |
| Toulouse         | 1         | 0.95%   |
| Thane            | 1         | 0.95%   |
| Tartu            | 1         | 0.95%   |
| Talcahuano       | 1         | 0.95%   |
| Seville          | 1         | 0.95%   |
| Settimo Torinese | 1         | 0.95%   |
| Sarospatak       | 1         | 0.95%   |
| Sao Paulo        | 1         | 0.95%   |
| Saint-Nicolas    | 1         | 0.95%   |
| Rostov-on-Don    | 1         | 0.95%   |
| Rome             | 1         | 0.95%   |
| Rennes           | 1         | 0.95%   |
| Porto Alegre     | 1         | 0.95%   |
| Piedmont         | 1         | 0.95%   |
| Perreuil         | 1         | 0.95%   |
| Pau              | 1         | 0.95%   |
| Pärnu           | 1         | 0.95%   |
| Ortuella         | 1         | 0.95%   |
| Olympia          | 1         | 0.95%   |
| Olathe           | 1         | 0.95%   |
| Odesa            | 1         | 0.95%   |
| Novara           | 1         | 0.95%   |
| Nova Gorica      | 1         | 0.95%   |
| Norwich          | 1         | 0.95%   |
| North Wilkesboro | 1         | 0.95%   |
| Nogales          | 1         | 0.95%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 23        | 36     | 18.11%  |
| Seagate               | 10        | 11     | 7.87%   |
| Unknown               | 9         | 11     | 7.09%   |
| Toshiba               | 8         | 11     | 6.3%    |
| Crucial               | 8         | 10     | 6.3%    |
| SanDisk               | 7         | 9      | 5.51%   |
| SK hynix              | 6         | 6      | 4.72%   |
| Kingston              | 6         | 7      | 4.72%   |
| WDC                   | 5         | 5      | 3.94%   |
| Micron Technology     | 3         | 3      | 2.36%   |
| KIOXIA                | 3         | 3      | 2.36%   |
| Intel                 | 3         | 3      | 2.36%   |
| HGST                  | 3         | 3      | 2.36%   |
| A-DATA Technology     | 3         | 3      | 2.36%   |
| SPCC                  | 2         | 4      | 1.57%   |
| Phison                | 2         | 2      | 1.57%   |
| KingSpec              | 2         | 2      | 1.57%   |
| Hitachi               | 2         | 2      | 1.57%   |
| China                 | 2         | 2      | 1.57%   |
| WDC WDS2              | 1         | 1      | 0.79%   |
| Verbatim              | 1         | 4      | 0.79%   |
| UMIS                  | 1         | 2      | 0.79%   |
| Silicon Motion        | 1         | 1      | 0.79%   |
| Realtek Semiconductor | 1         | 2      | 0.79%   |
| Patriot               | 1         | 1      | 0.79%   |
| OCZ                   | 1         | 1      | 0.79%   |
| Netac                 | 1         | 1      | 0.79%   |
| LITEONIT              | 1         | 1      | 0.79%   |
| Lenovo                | 1         | 1      | 0.79%   |
| Kston                 | 1         | 1      | 0.79%   |
| JMicron Technology    | 1         | 1      | 0.79%   |
| Intenso               | 1         | 1      | 0.79%   |
| Hjwdz                 | 1         | 1      | 0.79%   |
| Gigabyte Technology   | 1         | 1      | 0.79%   |
| faspeed               | 1         | 1      | 0.79%   |
| Corsair               | 1         | 1      | 0.79%   |
| Apple                 | 1         | 1      | 0.79%   |
| addlink               | 1         | 1      | 0.79%   |
| ADATA Technology      | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 3         | 2.27%   |
| Toshiba MQ01ABF050 500GB             | 3         | 2.27%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.52%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.52%   |
| Samsung MZVLQ512HBLU-00BH1 512GB     | 2         | 1.52%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 1.52%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.52%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 1.52%   |
| WDC WDS2 50G2B0B-00YS 250GB SSD      | 1         | 0.76%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 1         | 0.76%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.76%   |
| WDC WD10SPZX-22Z10T0 1TB             | 1         | 0.76%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB | 1         | 0.76%   |
| Verbatim Vi550 S3 512GB SSD          | 1         | 0.76%   |
| Unknown xD/SD/M.S.                   | 1         | 0.76%   |
| Unknown SLD64G  64GB                 | 1         | 0.76%   |
| Unknown SC64G  64GB                  | 1         | 0.76%   |
| Unknown MMC Card  7GB                | 1         | 0.76%   |
| Unknown MMC Card  64GB               | 1         | 0.76%   |
| Unknown MMC Card  16GB               | 1         | 0.76%   |
| Unknown CJTD4R  64GB                 | 1         | 0.76%   |
| Unknown Biwin  64GB                  | 1         | 0.76%   |
| UMIS RPJTJ256MEE1OWX 256GB           | 1         | 0.76%   |
| Toshiba THNSNK256GVN8 256GB SSD      | 1         | 0.76%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.76%   |
| Toshiba MK3259GSXP 320GB             | 1         | 0.76%   |
| Toshiba KBG40ZNT256G MEMORY 256GB    | 1         | 0.76%   |
| Toshiba KBG30ZMV256G 256GB           | 1         | 0.76%   |
| SPCC Solid State Disk 1024GB         | 1         | 0.76%   |
| SPCC M.2 PCIe SSD 1TB                | 1         | 0.76%   |
| SK hynix SC311 SATA 256GB SSD        | 1         | 0.76%   |
| SK hynix PC611 NVMe 1TB              | 1         | 0.76%   |
| SK hynix PC401 NVMe 1TB              | 1         | 0.76%   |
| SK hynix HFM512GD3JX013N 512GB       | 1         | 0.76%   |
| SK hynix HFM128GDJTNG-8310A 128GB    | 1         | 0.76%   |
| SK hynix BC511 NVMe 256GB            | 1         | 0.76%   |
| Silicon Motion PCIe-8 SSD 256GB      | 1         | 0.76%   |
| Seagate ST9500420AS 500GB            | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 43.48%  |
| Toshiba | 5         | 7      | 21.74%  |
| WDC     | 3         | 3      | 13.04%  |
| HGST    | 3         | 3      | 13.04%  |
| Hitachi | 2         | 2      | 8.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 17.65%  |
| Crucial             | 8         | 10     | 15.69%  |
| SanDisk             | 5         | 6      | 9.8%    |
| Kingston            | 5         | 6      | 9.8%    |
| A-DATA Technology   | 3         | 3      | 5.88%   |
| KingSpec            | 2         | 2      | 3.92%   |
| China               | 2         | 2      | 3.92%   |
| WDC WDS2            | 1         | 1      | 1.96%   |
| Verbatim            | 1         | 4      | 1.96%   |
| Toshiba             | 1         | 2      | 1.96%   |
| SPCC                | 1         | 3      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| Patriot             | 1         | 1      | 1.96%   |
| OCZ                 | 1         | 1      | 1.96%   |
| Netac               | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| LITEONIT            | 1         | 1      | 1.96%   |
| Kston               | 1         | 1      | 1.96%   |
| JMicron Technology  | 1         | 1      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| Corsair             | 1         | 1      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| addlink             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 43        | 62     | 36.75%  |
| NVMe    | 41        | 57     | 35.04%  |
| HDD     | 22        | 26     | 18.8%   |
| MMC     | 8         | 10     | 6.84%   |
| Unknown | 3         | 3      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 82     | 50.86%  |
| NVMe | 41        | 57     | 35.34%  |
| SAS  | 8         | 9      | 6.9%    |
| MMC  | 8         | 10     | 6.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 56     | 66.67%  |
| 0.51-1.0   | 15        | 18     | 21.74%  |
| 1.01-2.0   | 6         | 11     | 8.7%    |
| 3.01-4.0   | 1         | 2      | 1.45%   |
| 4.01-10.0  | 1         | 1      | 1.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 32.38%  |
| 251-500        | 26        | 24.76%  |
| 21-50          | 8         | 7.62%   |
| 501-1000       | 8         | 7.62%   |
| 1001-2000      | 7         | 6.67%   |
| 1-20           | 7         | 6.67%   |
| 51-100         | 7         | 6.67%   |
| 2001-3000      | 4         | 3.81%   |
| More than 3000 | 3         | 2.86%   |
| Unknown        | 1         | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 35        | 33.02%  |
| 21-50          | 20        | 18.87%  |
| 101-250        | 17        | 16.04%  |
| 51-100         | 13        | 12.26%  |
| 251-500        | 7         | 6.6%    |
| 501-1000       | 5         | 4.72%   |
| 1001-2000      | 4         | 3.77%   |
| 2001-3000      | 3         | 2.83%   |
| More than 3000 | 1         | 0.94%   |
| Unknown        | 1         | 0.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                    | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 11.11%  |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 11.11%  |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 11.11%  |
| OCZ VERTEX3 240GB SSD                        | 1         | 1      | 11.11%  |
| Netac SSD 256GB                              | 1         | 1      | 11.11%  |
| Kingston SA400S37240G 240GB SSD              | 1         | 1      | 11.11%  |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 11.11%  |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| OCZ                 | 1         | 1      | 11.11%  |
| Netac               | 1         | 1      | 11.11%  |
| Kingston            | 1         | 1      | 11.11%  |
| Intel               | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 75%     |
| Hitachi | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 4      | 44.44%  |
| HDD  | 4         | 4      | 44.44%  |
| NVMe | 1         | 1      | 11.11%  |

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
| Works    | 63        | 83     | 55.75%  |
| Detected | 41        | 66     | 36.28%  |
| Malfunc  | 9         | 9      | 7.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 61        | 50.41%  |
| AMD                          | 16        | 13.22%  |
| Samsung Electronics          | 14        | 11.57%  |
| SK hynix                     | 5         | 4.13%   |
| SanDisk                      | 4         | 3.31%   |
| KIOXIA                       | 4         | 3.31%   |
| Phison Electronics           | 3         | 2.48%   |
| Toshiba America Info Systems | 2         | 1.65%   |
| Nvidia                       | 2         | 1.65%   |
| Micron Technology            | 2         | 1.65%   |
| Union Memory (Shenzhen)      | 1         | 0.83%   |
| Silicon Motion               | 1         | 0.83%   |
| Realtek Semiconductor        | 1         | 0.83%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.83%   |
| Marvell Technology Group     | 1         | 0.83%   |
| Lenovo                       | 1         | 0.83%   |
| Kingston Technology Company  | 1         | 0.83%   |
| ADATA Technology             | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 13        | 10%     |
| Samsung NVMe SSD Controller 980                                                        | 9         | 6.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 9         | 6.92%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 3.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 4         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 3.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 2.31%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 2.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 2.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.31%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 1.54%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 1.54%   |
| Micron NVMe Storage Controller                                                         | 2         | 1.54%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 1.54%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 1.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 2         | 1.54%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 1.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.54%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.77%   |
| Toshiba America Info Systems Toshiba America Info SATA controller                      | 1         | 0.77%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.77%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 0.77%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.77%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 1         | 0.77%   |
| SK hynix BC511                                                                         | 1         | 0.77%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.77%   |
| Silicon Motion Non-Volatile memory controller                                          | 1         | 0.77%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.77%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 66        | 53.23%  |
| NVMe | 41        | 33.06%  |
| RAID | 10        | 8.06%   |
| IDE  | 7         | 5.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 74.51%  |
| AMD    | 26        | 25.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-3517U CPU @ 1.90GHz           | 3         | 2.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.94%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.96%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 2         | 1.96%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.96%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.96%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 2         | 1.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.96%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.96%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 1.96%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 1.96%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.98%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.98%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.98%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.98%   |
| Intel Pentium CPU B940 @ 2.00GHz            | 1         | 0.98%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.98%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.98%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.98%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.98%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 0.98%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.98%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 0.98%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.98%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 0.98%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.98%   |
| Intel Core i7 CPU X 920 @ 2.00GHz           | 1         | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.98%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.98%   |
| Intel Core i5-4300Y CPU @ 1.60GHz           | 1         | 0.98%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 0.98%   |
| Intel Core i5-3380M CPU @ 2.90GHz           | 1         | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 0.98%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 0.98%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 0.98%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 0.98%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 16        | 15.69%  |
| Intel Core i5           | 15        | 14.71%  |
| Other                   | 12        | 11.76%  |
| Intel Celeron           | 10        | 9.8%    |
| Intel Core i3           | 8         | 7.84%   |
| Intel Core 2 Duo        | 8         | 7.84%   |
| AMD Ryzen 7             | 5         | 4.9%    |
| AMD Ryzen 5             | 5         | 4.9%    |
| Intel Pentium           | 4         | 3.92%   |
| AMD Ryzen 9             | 2         | 1.96%   |
| AMD Ryzen 3             | 2         | 1.96%   |
| AMD A6                  | 2         | 1.96%   |
| AMD A4                  | 2         | 1.96%   |
| Intel Xeon              | 1         | 0.98%   |
| Intel Pentium Silver    | 1         | 0.98%   |
| Intel Pentium Dual-Core | 1         | 0.98%   |
| AMD Turion 64 X2 Mobile | 1         | 0.98%   |
| AMD Turion 64 Mobile    | 1         | 0.98%   |
| AMD Sempron             | 1         | 0.98%   |
| AMD Ryzen 7 PRO         | 1         | 0.98%   |
| AMD Quad-Core           | 1         | 0.98%   |
| AMD E1                  | 1         | 0.98%   |
| AMD Athlon X2           | 1         | 0.98%   |
| AMD A8                  | 1         | 0.98%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 45.1%   |
| 4      | 39        | 38.24%  |
| 8      | 8         | 7.84%   |
| 6      | 5         | 4.9%    |
| 1      | 2         | 1.96%   |
| 14     | 1         | 0.98%   |
| 10     | 1         | 0.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 102       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 65        | 63.73%  |
| 1      | 37        | 36.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 102       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 37.04%  |
| 0x806c1    | 6         | 5.56%   |
| 0x306a9    | 6         | 5.56%   |
| 0x806ec    | 5         | 4.63%   |
| 0x806d1    | 3         | 2.78%   |
| 0x40651    | 3         | 2.78%   |
| 0x30678    | 3         | 2.78%   |
| 0x206a7    | 3         | 2.78%   |
| 0x1067a    | 3         | 2.78%   |
| 0x0a50000c | 3         | 2.78%   |
| 0x0700010f | 3         | 2.78%   |
| 0x706e5    | 2         | 1.85%   |
| 0x706a8    | 2         | 1.85%   |
| 0x506c9    | 2         | 1.85%   |
| 0x10676    | 2         | 1.85%   |
| 0x08608103 | 2         | 1.85%   |
| 0x08108109 | 2         | 1.85%   |
| 0x906e9    | 1         | 0.93%   |
| 0x906c0    | 1         | 0.93%   |
| 0x906a4    | 1         | 0.93%   |
| 0x906a3    | 1         | 0.93%   |
| 0x806eb    | 1         | 0.93%   |
| 0x806ea    | 1         | 0.93%   |
| 0x806e9    | 1         | 0.93%   |
| 0x706a1    | 1         | 0.93%   |
| 0x6fd      | 1         | 0.93%   |
| 0x6fb      | 1         | 0.93%   |
| 0x506e3    | 1         | 0.93%   |
| 0x406e3    | 1         | 0.93%   |
| 0x406c4    | 1         | 0.93%   |
| 0x20655    | 1         | 0.93%   |
| 0x08608102 | 1         | 0.93%   |
| 0x08101016 | 1         | 0.93%   |
| 0x07030105 | 1         | 0.93%   |
| 0x02000032 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 10.68%  |
| IvyBridge        | 10        | 9.71%   |
| TigerLake        | 7         | 6.8%    |
| Silvermont       | 6         | 5.83%   |
| Penryn           | 6         | 5.83%   |
| IceLake          | 6         | 5.83%   |
| Unknown          | 6         | 5.83%   |
| Haswell          | 5         | 4.85%   |
| Zen 3            | 4         | 3.88%   |
| SandyBridge      | 4         | 3.88%   |
| Goldmont plus    | 4         | 3.88%   |
| Zen+             | 3         | 2.91%   |
| Zen 2            | 3         | 2.91%   |
| Westmere         | 3         | 2.91%   |
| Jaguar           | 3         | 2.91%   |
| Core             | 3         | 2.91%   |
| Zen              | 2         | 1.94%   |
| Skylake          | 2         | 1.94%   |
| Puma             | 2         | 1.94%   |
| K8 Hammer        | 2         | 1.94%   |
| Goldmont         | 2         | 1.94%   |
| Excavator        | 2         | 1.94%   |
| Alderlake Hybrid | 2         | 1.94%   |
| Nehalem          | 1         | 0.97%   |
| K8 & K10 hybrid  | 1         | 0.97%   |
| K10              | 1         | 0.97%   |
| CometLake        | 1         | 0.97%   |
| Broadwell        | 1         | 0.97%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 53.23%  |
| AMD    | 31        | 25%     |
| Nvidia | 27        | 21.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 7.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 4.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 3.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 3.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 2.38%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.38%   |
| AMD Renoir                                                                               | 3         | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.38%   |
| AMD Lucienne                                                                             | 3         | 2.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 2.38%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.59%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.59%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.59%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.59%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.59%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.79%   |
| Nvidia TU117M                                                                            | 1         | 0.79%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.79%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.79%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.79%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.79%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.79%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.79%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 0.79%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.79%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.79%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.79%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.79%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                       | 1         | 0.79%   |
| Nvidia G98M [GeForce G 103M]                                                             | 1         | 0.79%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 48.04%  |
| 1 x AMD        | 20        | 19.61%  |
| Intel + Nvidia | 12        | 11.76%  |
| 1 x Nvidia     | 10        | 9.8%    |
| Intel + AMD    | 5         | 4.9%    |
| AMD + Nvidia   | 5         | 4.9%    |
| 2 x AMD        | 1         | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 83        | 81.37%  |
| Proprietary | 15        | 14.71%  |
| Unknown     | 4         | 3.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 73.79%  |
| 0.01-0.5   | 14        | 13.59%  |
| 0.51-1.0   | 6         | 5.83%   |
| 1.01-2.0   | 4         | 3.88%   |
| 7.01-8.0   | 1         | 0.97%   |
| 5.01-6.0   | 1         | 0.97%   |
| 3.01-4.0   | 1         | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 20        | 17.09%  |
| Chimei Innolux          | 16        | 13.68%  |
| Samsung Electronics     | 14        | 11.97%  |
| AU Optronics            | 14        | 11.97%  |
| LG Display              | 11        | 9.4%    |
| Chi Mei Optoelectronics | 4         | 3.42%   |
| Apple                   | 4         | 3.42%   |
| PANDA                   | 3         | 2.56%   |
| Dell                    | 3         | 2.56%   |
| Sony                    | 2         | 1.71%   |
| Sharp                   | 2         | 1.71%   |
| Lenovo                  | 2         | 1.71%   |
| Iiyama                  | 2         | 1.71%   |
| BenQ                    | 2         | 1.71%   |
| AOC                     | 2         | 1.71%   |
| ViewSonic               | 1         | 0.85%   |
| Unknown                 | 1         | 0.85%   |
| Toshiba                 | 1         | 0.85%   |
| Sceptre Tech            | 1         | 0.85%   |
| Quanta Display          | 1         | 0.85%   |
| Philips                 | 1         | 0.85%   |
| LGD                     | 1         | 0.85%   |
| LG Philips              | 1         | 0.85%   |
| IBM                     | 1         | 0.85%   |
| Hitachi                 | 1         | 0.85%   |
| Hewlett-Packard         | 1         | 0.85%   |
| HannStar                | 1         | 0.85%   |
| Goldstar                | 1         | 0.85%   |
| CS_                     | 1         | 0.85%   |
| Ancor Communications    | 1         | 0.85%   |
| Acer                    | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 2         | 1.71%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 2         | 1.71%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 2         | 1.71%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 1.71%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.71%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 2         | 1.71%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch         | 1         | 0.85%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 0.85%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 0.85%   |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.85%   |
| Sceptre Tech E24 SPT099D 1920x1080 409x230mm 18.5-inch                | 1         | 0.85%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch   | 1         | 0.85%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch    | 1         | 0.85%   |
| Samsung Electronics S24F350 SAM0D22 1920x1080 521x293mm 23.5-inch     | 1         | 0.85%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch     | 1         | 0.85%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 890x500mm 40.2-inch | 1         | 0.85%   |
| Samsung Electronics 173HT02-T01 SEC5044 1920x1080 382x215mm 17.3-inch | 1         | 0.85%   |
| Quanta Display LCD Monitor QDS0027 1280x800 331x207mm 15.4-inch       | 1         | 0.85%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 1         | 0.85%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.85%   |
| LGD LCD Monitor 1366x768                                              | 1         | 0.85%   |
| LG Philips LCD Monitor LPLA106 1440x900 367x230mm 17.1-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0724 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 42.59%  |
| 1366x768 (WXGA)    | 32        | 29.63%  |
| 2560x1440 (QHD)    | 6         | 5.56%   |
| 1440x900 (WXGA+)   | 5         | 4.63%   |
| 1280x800 (WXGA)    | 5         | 4.63%   |
| 3840x2160 (4K)     | 3         | 2.78%   |
| 2560x1600          | 2         | 1.85%   |
| 2160x1440          | 2         | 1.85%   |
| 1680x1050 (WSXGA+) | 2         | 1.85%   |
| 1600x900 (HD+)     | 2         | 1.85%   |
| 3840x2400          | 1         | 0.93%   |
| 2880x1620          | 1         | 0.93%   |
| 1920x1200 (WUXGA)  | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 48        | 41.38%  |
| 13      | 13        | 11.21%  |
| 14      | 12        | 10.34%  |
| 17      | 10        | 8.62%   |
| 27      | 9         | 7.76%   |
| 24      | 5         | 4.31%   |
| 21      | 3         | 2.59%   |
| 11      | 3         | 2.59%   |
| 54      | 2         | 1.72%   |
| 23      | 2         | 1.72%   |
| 12      | 2         | 1.72%   |
| 84      | 1         | 0.86%   |
| 31      | 1         | 0.86%   |
| 25      | 1         | 0.86%   |
| 22      | 1         | 0.86%   |
| 18      | 1         | 0.86%   |
| 16      | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 59.13%  |
| 501-600     | 16        | 13.91%  |
| 201-300     | 11        | 9.57%   |
| 351-400     | 10        | 8.7%    |
| 401-500     | 5         | 4.35%   |
| 1001-1500   | 2         | 1.74%   |
| 601-700     | 1         | 0.87%   |
| 1501-2000   | 1         | 0.87%   |
| Unknown     | 1         | 0.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 79        | 79.8%   |
| 16/10   | 17        | 17.17%  |
| 3/2     | 2         | 2.02%   |
| Unknown | 1         | 1.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 40%     |
| 81-90          | 21        | 18.26%  |
| 301-350        | 9         | 7.83%   |
| 201-250        | 8         | 6.96%   |
| 121-130        | 8         | 6.96%   |
| 71-80          | 4         | 3.48%   |
| More than 1000 | 3         | 2.61%   |
| 51-60          | 3         | 2.61%   |
| 251-300        | 3         | 2.61%   |
| 61-70          | 2         | 1.74%   |
| 131-140        | 2         | 1.74%   |
| 91-100         | 2         | 1.74%   |
| 351-500        | 1         | 0.87%   |
| 141-150        | 1         | 0.87%   |
| 111-120        | 1         | 0.87%   |
| Unknown        | 1         | 0.87%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 41        | 36.61%  |
| 101-120       | 34        | 30.36%  |
| 51-100        | 22        | 19.64%  |
| 161-240       | 11        | 9.82%   |
| 1-50          | 2         | 1.79%   |
| More than 240 | 1         | 0.89%   |
| Unknown       | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 77        | 75.49%  |
| 2     | 18        | 17.65%  |
| 0     | 4         | 3.92%   |
| 3     | 2         | 1.96%   |
| 4     | 1         | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 57        | 37.75%  |
| Realtek Semiconductor             | 53        | 35.1%   |
| Qualcomm Atheros                  | 13        | 8.61%   |
| Broadcom                          | 8         | 5.3%    |
| Broadcom Limited                  | 3         | 1.99%   |
| Ralink                            | 2         | 1.32%   |
| Nvidia                            | 2         | 1.32%   |
| Marvell Technology Group          | 2         | 1.32%   |
| Ericsson Business Mobile Networks | 2         | 1.32%   |
| ASIX Electronics                  | 2         | 1.32%   |
| TP-Link                           | 1         | 0.66%   |
| Quectel Wireless Solutions        | 1         | 0.66%   |
| Qualcomm Atheros Communications   | 1         | 0.66%   |
| Microchip Technology              | 1         | 0.66%   |
| MediaTek                          | 1         | 0.66%   |
| DisplayLink                       | 1         | 0.66%   |
| D-Link System                     | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 24        | 12.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 6.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 8         | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 5         | 2.63%   |
| Intel Wi-Fi 6 AX201                                                            | 5         | 2.63%   |
| Intel Wi-Fi 6 AX200                                                            | 5         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 5         | 2.63%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.58%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 1.58%   |
| Realtek 802.11ac NIC                                                           | 3         | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 1.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 3         | 1.58%   |
| Intel WiFi Link 5100                                                           | 3         | 1.58%   |
| Intel Centrino Wireless-N 2230                                                 | 3         | 1.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 1.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 2         | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.05%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 2         | 1.05%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.05%   |
| Intel Wireless 7265                                                            | 2         | 1.05%   |
| Intel Wireless 7260                                                            | 2         | 1.05%   |
| Intel Wireless 3165                                                            | 2         | 1.05%   |
| Intel Wireless 3160                                                            | 2         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 2         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 1.05%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 2         | 1.05%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.05%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.05%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 2         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 51.82%  |
| Realtek Semiconductor           | 26        | 23.64%  |
| Qualcomm Atheros                | 12        | 10.91%  |
| Broadcom                        | 6         | 5.45%   |
| Ralink                          | 2         | 1.82%   |
| Broadcom Limited                | 2         | 1.82%   |
| TP-Link                         | 1         | 0.91%   |
| Quectel Wireless Solutions      | 1         | 0.91%   |
| Qualcomm Atheros Communications | 1         | 0.91%   |
| MediaTek                        | 1         | 0.91%   |
| D-Link System                   | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 7.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.5%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 4.5%    |
| Intel Wi-Fi 6 AX200                                                     | 5         | 4.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 4.5%    |
| Intel Wireless 8265 / 8275                                              | 4         | 3.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.7%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.7%    |
| Realtek 802.11ac NIC                                                    | 3         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.7%    |
| Intel WiFi Link 5100                                                    | 3         | 2.7%    |
| Intel Centrino Wireless-N 2230                                          | 3         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.8%    |
| Intel Wireless 7265                                                     | 2         | 1.8%    |
| Intel Wireless 7260                                                     | 2         | 1.8%    |
| Intel Wireless 3165                                                     | 2         | 1.8%    |
| Intel Wireless 3160                                                     | 2         | 1.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.8%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.8%    |
| TP-Link 802.11ac NIC                                                    | 1         | 0.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.9%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.9%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.9%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.9%    |
| Quectel Wireless Solutions EM12G-ACER                                   | 1         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.9%    |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.9%    |
| Intel Wireless 8260                                                     | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 52.63%  |
| Intel                    | 21        | 27.63%  |
| Broadcom                 | 4         | 5.26%   |
| Qualcomm Atheros         | 2         | 2.63%   |
| Nvidia                   | 2         | 2.63%   |
| Marvell Technology Group | 2         | 2.63%   |
| ASIX Electronics         | 2         | 2.63%   |
| Microchip Technology     | 1         | 1.32%   |
| DisplayLink              | 1         | 1.32%   |
| Broadcom Limited         | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 24        | 31.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 15.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 5.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 2.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 2.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.6%    |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 2.6%    |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 2.6%    |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 2.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 2.6%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 2.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.3%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.3%    |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 1.3%    |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 1.3%    |
| Intel I210 Gigabit Network Connection                                          | 1         | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.3%    |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.3%    |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.3%    |
| Intel Ethernet Connection (16) I219-LM                                         | 1         | 1.3%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.3%    |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 1.3%    |
| Intel 82566MC Gigabit Network Connection                                       | 1         | 1.3%    |
| DisplayLink Kensington SD3600 Dual Video Dock                                  | 1         | 1.3%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.3%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 1.3%    |
| Broadcom Limited NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 56.98%  |
| Ethernet | 75        | 41.9%   |
| Modem    | 2         | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 79.28%  |
| Ethernet | 23        | 20.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 71        | 69.61%  |
| 1     | 30        | 29.41%  |
| 0     | 1         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 66        | 64.71%  |
| Yes  | 36        | 35.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 46.15%  |
| Realtek Semiconductor           | 16        | 17.58%  |
| Broadcom                        | 9         | 9.89%   |
| IMC Networks                    | 6         | 6.59%   |
| Apple                           | 4         | 4.4%    |
| Qualcomm Atheros Communications | 3         | 3.3%    |
| Cambridge Silicon Radio         | 3         | 3.3%    |
| Ralink                          | 2         | 2.2%    |
| Foxconn / Hon Hai               | 2         | 2.2%    |
| Toshiba                         | 1         | 1.1%    |
| Lite-On Technology              | 1         | 1.1%    |
| Hewlett-Packard                 | 1         | 1.1%    |
| Foxconn International           | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 15        | 16.48%  |
| Realtek Bluetooth Radio                                                             | 14        | 15.38%  |
| Intel Bluetooth wireless interface                                                  | 10        | 10.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 6.59%   |
| Intel AX200 Bluetooth                                                               | 5         | 5.49%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 4.4%    |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 3.3%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.2%    |
| Ralink RT3290 Bluetooth                                                             | 2         | 2.2%    |
| Intel AX210 Bluetooth                                                               | 2         | 2.2%    |
| IMC Networks Bluetooth Device                                                       | 2         | 2.2%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 2.2%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.2%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 2.2%    |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.2%    |
| Apple Bluetooth Host Controller                                                     | 2         | 2.2%    |
| Toshiba Bluetooth Device                                                            | 1         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.1%    |
| IMC Networks Wireless_Device                                                        | 1         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.1%    |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 1.1%    |
| Broadcom Bluetooth 3.0 Dongle                                                       | 1         | 1.1%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.1%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.1%    |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 75        | 58.59%  |
| AMD                    | 27        | 21.09%  |
| Nvidia                 | 20        | 15.63%  |
| C-Media Electronics    | 2         | 1.56%   |
| Meizu                  | 1         | 0.78%   |
| Generalplus Technology | 1         | 0.78%   |
| DSEA A/S               | 1         | 0.78%   |
| ASUSTek Computer       | 1         | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 9.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 6.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 4.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 4.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 3.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 5         | 3.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.58%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 2.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 2.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.58%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.58%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.94%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 1.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.94%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.29%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.29%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.29%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.29%   |
| Nvidia stereo controller                                                                          | 1         | 0.65%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.65%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.65%   |
| Meizu HiFi DAC Headphone Amplifier                                                                | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 26.09%  |
| SK hynix            | 21        | 22.83%  |
| Micron Technology   | 15        | 16.3%   |
| Unknown             | 10        | 10.87%  |
| Kingston            | 9         | 9.78%   |
| Unknown (ABCD)      | 4         | 4.35%   |
| Crucial             | 4         | 4.35%   |
| Nanya Technology    | 2         | 2.17%   |
| G.Skill             | 2         | 2.17%   |
| Ramaxel Technology  | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 3.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 3.92%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 2.94%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.96%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.96%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.96%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.96%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.98%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.98%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.98%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.98%   |
| Unknown RAM Module 2GB SODIMM 1067MT/s                           | 1         | 0.98%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.98%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.98%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.98%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.98%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.98%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 800MT/s            | 1         | 0.98%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1333MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.98%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 0.98%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 0.98%   |
| Samsung RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.98%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 37        | 46.25%  |
| DDR3    | 25        | 31.25%  |
| DDR2    | 7         | 8.75%   |
| LPDDR4  | 6         | 7.5%    |
| SDRAM   | 2         | 2.5%    |
| LPDDR3  | 1         | 1.25%   |
| DDR5    | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 86.75%  |
| Row Of Chips | 9         | 10.84%  |
| Chip         | 1         | 1.2%    |
| Unknown      | 1         | 1.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 32        | 35.96%  |
| 4096  | 29        | 32.58%  |
| 2048  | 12        | 13.48%  |
| 16384 | 10        | 11.24%  |
| 1024  | 4         | 4.49%   |
| 32768 | 2         | 2.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 26        | 30.23%  |
| 1600    | 19        | 22.09%  |
| 2400    | 11        | 12.79%  |
| 2667    | 8         | 9.3%    |
| Unknown | 4         | 4.65%   |
| 1334    | 3         | 3.49%   |
| 667     | 3         | 3.49%   |
| 2048    | 2         | 2.33%   |
| 1067    | 2         | 2.33%   |
| 4800    | 1         | 1.16%   |
| 4267    | 1         | 1.16%   |
| 2133    | 1         | 1.16%   |
| 1867    | 1         | 1.16%   |
| 1333    | 1         | 1.16%   |
| 1066    | 1         | 1.16%   |
| 975     | 1         | 1.16%   |
| 800     | 1         | 1.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M2070 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26        | 26.8%   |
| Realtek Semiconductor                  | 11        | 11.34%  |
| IMC Networks                           | 9         | 9.28%   |
| Quanta                                 | 8         | 8.25%   |
| Microdia                               | 6         | 6.19%   |
| Syntek                                 | 5         | 5.15%   |
| Suyin                                  | 4         | 4.12%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.12%   |
| Apple                                  | 3         | 3.09%   |
| Sunplus Innovation Technology          | 2         | 2.06%   |
| Silicon Motion                         | 2         | 2.06%   |
| Ricoh                                  | 2         | 2.06%   |
| Luxvisions Innotech Limited            | 2         | 2.06%   |
| Lenovo                                 | 2         | 2.06%   |
| Bison Electronics                      | 2         | 2.06%   |
| Acer                                   | 2         | 2.06%   |
| SunplusIT                              | 1         | 1.03%   |
| Sonix Technology                       | 1         | 1.03%   |
| Razer USA                              | 1         | 1.03%   |
| Logitech                               | 1         | 1.03%   |
| Lite-On Technology                     | 1         | 1.03%   |
| ARC International                      | 1         | 1.03%   |
| Alcor Micro                            | 1         | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 5         | 5.15%   |
| Syntek Integrated Camera                      | 4         | 4.12%   |
| Chicony HP HD Camera                          | 4         | 4.12%   |
| Realtek USB Camera                            | 3         | 3.09%   |
| Realtek Integrated_Webcam_HD                  | 3         | 3.09%   |
| Chicony HP Webcam                             | 3         | 3.09%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 2.06%   |
| Realtek USB2.0 camera                         | 2         | 2.06%   |
| Quanta HP TrueVision HD Camera                | 2         | 2.06%   |
| Quanta HD User Facing                         | 2         | 2.06%   |
| Microdia Webcam Vitade AF                     | 2         | 2.06%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.06%   |
| Lenovo CNF7237&CNF7238                        | 2         | 2.06%   |
| IMC Networks Integrated Camera                | 2         | 2.06%   |
| Chicony Integrated IR Camera                  | 2         | 2.06%   |
| Chicony integrated camera                     | 2         | 2.06%   |
| Chicony HP Truevision HD camera               | 2         | 2.06%   |
| Chicony HD User Facing                        | 2         | 2.06%   |
| Apple Built-in iSight                         | 2         | 2.06%   |
| Syntek Lenovo EasyCamera                      | 1         | 1.03%   |
| Suyin USB 2.0 Camera                          | 1         | 1.03%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 1.03%   |
| SunplusIT PC Camera                           | 1         | 1.03%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 1.03%   |
| Sunplus HP Truevision HD                      | 1         | 1.03%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 1.03%   |
| Silicon Motion WebCam SC-10HDD13335N          | 1         | 1.03%   |
| Silicon Motion HP Webcam-101                  | 1         | 1.03%   |
| Ricoh Sony Vaio Integrated Webcam             | 1         | 1.03%   |
| Ricoh Dell Laptop Integrated Webcam           | 1         | 1.03%   |
| Realtek NexiGo N960E FHD Webcam               | 1         | 1.03%   |
| Realtek Laptop_Integrated_Webcam_HD           | 1         | 1.03%   |
| Realtek Integrated Webcam HD                  | 1         | 1.03%   |
| Razer USA Gaming Webcam [Kiyo]                | 1         | 1.03%   |
| Quanta ov9734_techfront_camera                | 1         | 1.03%   |
| Quanta Lenovo EasyCamera                      | 1         | 1.03%   |
| Quanta HP Webcam-101                          | 1         | 1.03%   |
| Quanta HD Camera                              | 1         | 1.03%   |
| Microdia Webcam                               | 1         | 1.03%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 23.53%  |
| Upek                       | 4         | 23.53%  |
| Shenzhen Goodix Technology | 4         | 23.53%  |
| Synaptics                  | 2         | 11.76%  |
| Elan Microelectronics      | 2         | 11.76%  |
| AuthenTec                  | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 23.53%  |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 23.53%  |
| Elan ELAN:ARM-M4                                                           | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 5.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 5.88%   |
| AuthenTec AES1600                                                          | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
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


| Model                                                                        | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 60        | 58.25%  |
| 1     | 31        | 30.1%   |
| 2     | 10        | 9.71%   |
| 4     | 1         | 0.97%   |
| 3     | 1         | 0.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 17        | 32.08%  |
| Chipcard              | 15        | 28.3%   |
| Graphics card         | 7         | 13.21%  |
| Camera                | 4         | 7.55%   |
| Bluetooth             | 4         | 7.55%   |
| Net/wireless          | 3         | 5.66%   |
| Multimedia controller | 1         | 1.89%   |
| Flash memory          | 1         | 1.89%   |
| Dvb card              | 1         | 1.89%   |

