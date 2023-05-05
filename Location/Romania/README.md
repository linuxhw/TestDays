Linux in Romania - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Romania/Desktop/README.md) and [notebooks](/Location/Romania/Notebook/README.md).

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

Total: 2508

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d1b974c33a](https://linux-hardware.org/?probe=d1b974c33a) | May 01, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [01458c55a9](https://linux-hardware.org/?probe=01458c55a9) | Apr 28, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [df53e54c69](https://linux-hardware.org/?probe=df53e54c69) | Apr 28, 2023 |
| Acer          | Aspire 5110                 | Notebook    | [b43b059257](https://linux-hardware.org/?probe=b43b059257) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [92ac292547](https://linux-hardware.org/?probe=92ac292547) | Apr 24, 2023 |
| Acer          | Aspire V5-122P              | Notebook    | [baf567c71f](https://linux-hardware.org/?probe=baf567c71f) | Apr 23, 2023 |
| Samsung       | 730QDA                      | Convertible | [a6fef02901](https://linux-hardware.org/?probe=a6fef02901) | Apr 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [481c5a9169](https://linux-hardware.org/?probe=481c5a9169) | Apr 23, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Allview       | Allbook J                   | Notebook    | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [1127dfa79c](https://linux-hardware.org/?probe=1127dfa79c) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| Allview       | Allbook J                   | Notebook    | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [356ff49c7c](https://linux-hardware.org/?probe=356ff49c7c) | Apr 13, 2023 |
| HP            | 1495                        | Desktop     | [569a6f28f4](https://linux-hardware.org/?probe=569a6f28f4) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | Notebook    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| ASUSTek       | X55U                        | Notebook    | [0abf7df439](https://linux-hardware.org/?probe=0abf7df439) | Apr 06, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [0fbd47b12e](https://linux-hardware.org/?probe=0fbd47b12e) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [90796fbad9](https://linux-hardware.org/?probe=90796fbad9) | Mar 31, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [5d5862d22a](https://linux-hardware.org/?probe=5d5862d22a) | Mar 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5be11a9a6e](https://linux-hardware.org/?probe=5be11a9a6e) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [bfa850ddad](https://linux-hardware.org/?probe=bfa850ddad) | Mar 29, 2023 |
| HP            | 3047h                       | Desktop     | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [577947c9d3](https://linux-hardware.org/?probe=577947c9d3) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [08e7388619](https://linux-hardware.org/?probe=08e7388619) | Mar 27, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [bef27b5a10](https://linux-hardware.org/?probe=bef27b5a10) | Mar 26, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [daac2899b2](https://linux-hardware.org/?probe=daac2899b2) | Mar 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [84af25ca8c](https://linux-hardware.org/?probe=84af25ca8c) | Mar 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| Acer          | V5-131                      | Notebook    | [f35bd55401](https://linux-hardware.org/?probe=f35bd55401) | Mar 26, 2023 |
| Acer          | TravelMate 5744             | Notebook    | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [c5b2997e80](https://linux-hardware.org/?probe=c5b2997e80) | Mar 21, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [4a4c44f0dd](https://linux-hardware.org/?probe=4a4c44f0dd) | Mar 18, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ceb794a09f](https://linux-hardware.org/?probe=ceb794a09f) | Mar 17, 2023 |
| ASUSTek       | P9X79 WS                    | Desktop     | [29e03bb7ce](https://linux-hardware.org/?probe=29e03bb7ce) | Mar 17, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [8912f590e3](https://linux-hardware.org/?probe=8912f590e3) | Mar 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [d56d3939f9](https://linux-hardware.org/?probe=d56d3939f9) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | Notebook    | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a3a158ccf2](https://linux-hardware.org/?probe=a3a158ccf2) | Mar 08, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [72d0284bdd](https://linux-hardware.org/?probe=72d0284bdd) | Mar 05, 2023 |
| HP            | Compaq 6735b                | Notebook    | [8c664182a2](https://linux-hardware.org/?probe=8c664182a2) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9fba7bceb7](https://linux-hardware.org/?probe=9fba7bceb7) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [71d6eee071](https://linux-hardware.org/?probe=71d6eee071) | Mar 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2dea6717ae](https://linux-hardware.org/?probe=2dea6717ae) | Mar 02, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [46954919f7](https://linux-hardware.org/?probe=46954919f7) | Feb 27, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [60e1742e7e](https://linux-hardware.org/?probe=60e1742e7e) | Feb 27, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [ea8bb4c0e4](https://linux-hardware.org/?probe=ea8bb4c0e4) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [22cf774ac0](https://linux-hardware.org/?probe=22cf774ac0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | Notebook    | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0f251d6bbf](https://linux-hardware.org/?probe=0f251d6bbf) | Feb 23, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [bf6718f1d0](https://linux-hardware.org/?probe=bf6718f1d0) | Feb 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [91567566be](https://linux-hardware.org/?probe=91567566be) | Feb 21, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [c205da78c9](https://linux-hardware.org/?probe=c205da78c9) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [dc294f018e](https://linux-hardware.org/?probe=dc294f018e) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [e614d24613](https://linux-hardware.org/?probe=e614d24613) | Feb 17, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [f36e84dcaf](https://linux-hardware.org/?probe=f36e84dcaf) | Feb 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| HP            | 0AA8h                       | Desktop     | [e7bbc5903b](https://linux-hardware.org/?probe=e7bbc5903b) | Feb 15, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [1360d3227f](https://linux-hardware.org/?probe=1360d3227f) | Feb 10, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [fa2a1dba2d](https://linux-hardware.org/?probe=fa2a1dba2d) | Feb 09, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [e7b8536ad4](https://linux-hardware.org/?probe=e7b8536ad4) | Feb 09, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [a2729c9880](https://linux-hardware.org/?probe=a2729c9880) | Feb 08, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [6161d6b31d](https://linux-hardware.org/?probe=6161d6b31d) | Feb 08, 2023 |
| HP            | 1494                        | Desktop     | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| HP            | 1494                        | Desktop     | [a582a0d6c7](https://linux-hardware.org/?probe=a582a0d6c7) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0c14eb04ce](https://linux-hardware.org/?probe=0c14eb04ce) | Feb 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [2f47f8d73d](https://linux-hardware.org/?probe=2f47f8d73d) | Feb 05, 2023 |
| Toshiba       | Satellite C55-A-168         | Notebook    | [e92c2babc4](https://linux-hardware.org/?probe=e92c2babc4) | Feb 05, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [a2ff80e7dd](https://linux-hardware.org/?probe=a2ff80e7dd) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [2791787281](https://linux-hardware.org/?probe=2791787281) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [e2ad5b033f](https://linux-hardware.org/?probe=e2ad5b033f) | Jan 31, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [6c3dd54582](https://linux-hardware.org/?probe=6c3dd54582) | Jan 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| ASRock        | J4125M                      | Desktop     | [535c1b6821](https://linux-hardware.org/?probe=535c1b6821) | Jan 30, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [da2056876e](https://linux-hardware.org/?probe=da2056876e) | Jan 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [b7377ee894](https://linux-hardware.org/?probe=b7377ee894) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [5d58c53672](https://linux-hardware.org/?probe=5d58c53672) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b352f0af44](https://linux-hardware.org/?probe=b352f0af44) | Jan 27, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3e65f42529](https://linux-hardware.org/?probe=3e65f42529) | Jan 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [e030231e2c](https://linux-hardware.org/?probe=e030231e2c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [5b2fd24ed7](https://linux-hardware.org/?probe=5b2fd24ed7) | Jan 24, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [ac4fa9fd5f](https://linux-hardware.org/?probe=ac4fa9fd5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [36d99ec94e](https://linux-hardware.org/?probe=36d99ec94e) | Jan 22, 2023 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [cd23d81f65](https://linux-hardware.org/?probe=cd23d81f65) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [a7ba34fed5](https://linux-hardware.org/?probe=a7ba34fed5) | Jan 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | V5WE2                       | Notebook    | [021281441e](https://linux-hardware.org/?probe=021281441e) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
| Dell          | Precision M6600             | Notebook    | [478f51f2be](https://linux-hardware.org/?probe=478f51f2be) | Jan 17, 2023 |
| MSI           | 970A-G43                    | Desktop     | [086e04b65f](https://linux-hardware.org/?probe=086e04b65f) | Jan 17, 2023 |
| Dell          | Precision M6600             | Notebook    | [7511681884](https://linux-hardware.org/?probe=7511681884) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [bf8115e391](https://linux-hardware.org/?probe=bf8115e391) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6584beb723](https://linux-hardware.org/?probe=6584beb723) | Jan 15, 2023 |
| Gigabyte      | H67M-D2-B3                  | Desktop     | [6a4e71bb84](https://linux-hardware.org/?probe=6a4e71bb84) | Jan 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [020abf67f6](https://linux-hardware.org/?probe=020abf67f6) | Jan 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [f32463429a](https://linux-hardware.org/?probe=f32463429a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [6f39a15710](https://linux-hardware.org/?probe=6f39a15710) | Jan 13, 2023 |
| ASUSTek       | X406UAR                     | Notebook    | [68da6f6220](https://linux-hardware.org/?probe=68da6f6220) | Jan 13, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [f12439ce42](https://linux-hardware.org/?probe=f12439ce42) | Jan 13, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0eb36758be](https://linux-hardware.org/?probe=0eb36758be) | Jan 13, 2023 |
| HP            | 21F5                        | Desktop     | [141aa3faa6](https://linux-hardware.org/?probe=141aa3faa6) | Jan 12, 2023 |
| ASUSTek       | X406UAR                     | Notebook    | [729e2e0d41](https://linux-hardware.org/?probe=729e2e0d41) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [de94c3e313](https://linux-hardware.org/?probe=de94c3e313) | Jan 12, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [564c992a69](https://linux-hardware.org/?probe=564c992a69) | Jan 11, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [9a698e2879](https://linux-hardware.org/?probe=9a698e2879) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| Acer          | TMP645-M                    | Notebook    | [8e0b2f5e90](https://linux-hardware.org/?probe=8e0b2f5e90) | Jan 10, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [afe262fc54](https://linux-hardware.org/?probe=afe262fc54) | Jan 09, 2023 |
| ASUSTek       | K50IE                       | Notebook    | [4fdb15502c](https://linux-hardware.org/?probe=4fdb15502c) | Jan 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [fc35d7e62b](https://linux-hardware.org/?probe=fc35d7e62b) | Jan 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [69cda32447](https://linux-hardware.org/?probe=69cda32447) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [c4ae03416f](https://linux-hardware.org/?probe=c4ae03416f) | Jan 07, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [cc98c43ea0](https://linux-hardware.org/?probe=cc98c43ea0) | Jan 07, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Neousys Te... | POC-200 Series              | Notebook    | [7c37ff8631](https://linux-hardware.org/?probe=7c37ff8631) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [acbd8114d2](https://linux-hardware.org/?probe=acbd8114d2) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [3fb1b015e3](https://linux-hardware.org/?probe=3fb1b015e3) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [cdb2bf4725](https://linux-hardware.org/?probe=cdb2bf4725) | Jan 02, 2023 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [6ae9b30e34](https://linux-hardware.org/?probe=6ae9b30e34) | Jan 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| Lenovo        | No DPK                      | Desktop     | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [57a42cabf6](https://linux-hardware.org/?probe=57a42cabf6) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [9a6b000b23](https://linux-hardware.org/?probe=9a6b000b23) | Dec 23, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [2892951c9c](https://linux-hardware.org/?probe=2892951c9c) | Dec 23, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [ddc35a5b0d](https://linux-hardware.org/?probe=ddc35a5b0d) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [6306be2273](https://linux-hardware.org/?probe=6306be2273) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [cf8576151f](https://linux-hardware.org/?probe=cf8576151f) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [20544e55bb](https://linux-hardware.org/?probe=20544e55bb) | Dec 14, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d087536cbf](https://linux-hardware.org/?probe=d087536cbf) | Dec 14, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [20c4b98c2c](https://linux-hardware.org/?probe=20c4b98c2c) | Dec 14, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| MSI           | MS-B1591                    | Desktop     | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [05c7382806](https://linux-hardware.org/?probe=05c7382806) | Dec 11, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a7a3ccf712](https://linux-hardware.org/?probe=a7a3ccf712) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [83b02f1ffb](https://linux-hardware.org/?probe=83b02f1ffb) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [e7495f12e4](https://linux-hardware.org/?probe=e7495f12e4) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [fd65cfedda](https://linux-hardware.org/?probe=fd65cfedda) | Dec 07, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a35bac4078](https://linux-hardware.org/?probe=a35bac4078) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b387887bb6](https://linux-hardware.org/?probe=b387887bb6) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [d5ada57985](https://linux-hardware.org/?probe=d5ada57985) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3d64de28f5](https://linux-hardware.org/?probe=3d64de28f5) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | Notebook    | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b7a1fc62d1](https://linux-hardware.org/?probe=b7a1fc62d1) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [16679f50e3](https://linux-hardware.org/?probe=16679f50e3) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a178e673c3](https://linux-hardware.org/?probe=a178e673c3) | Nov 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c1d5a26691](https://linux-hardware.org/?probe=c1d5a26691) | Nov 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6c797b4554](https://linux-hardware.org/?probe=6c797b4554) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [b8379d261b](https://linux-hardware.org/?probe=b8379d261b) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2089ec3efb](https://linux-hardware.org/?probe=2089ec3efb) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Allview       | Allbook H                   | Notebook    | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [30916d8420](https://linux-hardware.org/?probe=30916d8420) | Nov 16, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | Notebook    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | Notebook    | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | Notebook    | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9e8ec19352](https://linux-hardware.org/?probe=9e8ec19352) | Oct 26, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [478ba58d34](https://linux-hardware.org/?probe=478ba58d34) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| ASUSTek       | V222GAR                     | All in one  | [e7e07dca5c](https://linux-hardware.org/?probe=e7e07dca5c) | Oct 12, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [79236a7a89](https://linux-hardware.org/?probe=79236a7a89) | Oct 11, 2022 |
| Medion        | Akoya E6239                 | Notebook    | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [abc991002e](https://linux-hardware.org/?probe=abc991002e) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| HP            | 2AED                        | All in one  | [9092720ed6](https://linux-hardware.org/?probe=9092720ed6) | Oct 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [cf4537f9cb](https://linux-hardware.org/?probe=cf4537f9cb) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | Notebook    | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [11f99758e6](https://linux-hardware.org/?probe=11f99758e6) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | Notebook    | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [deed57ec88](https://linux-hardware.org/?probe=deed57ec88) | Sep 23, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | Notebook    | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [d52ac897f4](https://linux-hardware.org/?probe=d52ac897f4) | Sep 15, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Dell          | Latitude E7470              | Notebook    | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| Dell          | Latitude 7410               | Notebook    | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [ca6a3b3fba](https://linux-hardware.org/?probe=ca6a3b3fba) | Aug 12, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1fe8a14d3b](https://linux-hardware.org/?probe=1fe8a14d3b) | Aug 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Unknown       | 1.0                         | Desktop     | [4394243123](https://linux-hardware.org/?probe=4394243123) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| Unknown       | 1.0                         | Desktop     | [545d9cf73c](https://linux-hardware.org/?probe=545d9cf73c) | Aug 04, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| HP            | 8704                        | Desktop     | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | Notebook    | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [892229b650](https://linux-hardware.org/?probe=892229b650) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [84cd652e24](https://linux-hardware.org/?probe=84cd652e24) | Jul 16, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | Notebook    | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | Notebook    | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | Notebook    | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| HP            | ProBook 4310s               | Notebook    | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [457aa90e64](https://linux-hardware.org/?probe=457aa90e64) | Jul 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| HP            | 1790                        | Desktop     | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | Notebook    | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | Notebook    | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | Notebook    | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| HP            | 0AA8h                       | Desktop     | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | Notebook    | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [9fe037820e](https://linux-hardware.org/?probe=9fe037820e) | May 05, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [a8e967a378](https://linux-hardware.org/?probe=a8e967a378) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | Notebook    | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | Notebook    | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | Notebook    | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | Notebook    | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | Notebook    | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a3a204ed56](https://linux-hardware.org/?probe=a3a204ed56) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| Dell          | Latitude E6440              | Notebook    | [33955db41e](https://linux-hardware.org/?probe=33955db41e) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| HP            | Pavilion 17                 | Notebook    | [acb0c7fd0e](https://linux-hardware.org/?probe=acb0c7fd0e) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [a572c901ca](https://linux-hardware.org/?probe=a572c901ca) | Apr 15, 2022 |
| HP            | Pavilion 17                 | Notebook    | [014f42ecee](https://linux-hardware.org/?probe=014f42ecee) | Apr 15, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9709ffeb9a](https://linux-hardware.org/?probe=9709ffeb9a) | Apr 14, 2022 |
| Dell          | System XPS L702X            | Notebook    | [9ed530100f](https://linux-hardware.org/?probe=9ed530100f) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [5fea9b2c3a](https://linux-hardware.org/?probe=5fea9b2c3a) | Apr 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dd2c447b48](https://linux-hardware.org/?probe=dd2c447b48) | Apr 07, 2022 |
| HP            | 0AA8h                       | Desktop     | [0de7915496](https://linux-hardware.org/?probe=0de7915496) | Apr 06, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| Lenovo        | B590 37612LG                | Notebook    | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| HP            | 1790                        | Desktop     | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [13aa7656f3](https://linux-hardware.org/?probe=13aa7656f3) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [62982f1e80](https://linux-hardware.org/?probe=62982f1e80) | Apr 02, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [4c887e357d](https://linux-hardware.org/?probe=4c887e357d) | Mar 31, 2022 |
| HP            | 250 G4                      | Notebook    | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [c2d3fbb93e](https://linux-hardware.org/?probe=c2d3fbb93e) | Mar 30, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ffde31bd20](https://linux-hardware.org/?probe=ffde31bd20) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2bbea411a6](https://linux-hardware.org/?probe=2bbea411a6) | Mar 24, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [c55e29b1e9](https://linux-hardware.org/?probe=c55e29b1e9) | Mar 22, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [ce6cc28ca1](https://linux-hardware.org/?probe=ce6cc28ca1) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| Gigabyte      | AERO 15 YD                  | Notebook    | [35da4bbe2c](https://linux-hardware.org/?probe=35da4bbe2c) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [626ee37f9b](https://linux-hardware.org/?probe=626ee37f9b) | Mar 21, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a93c59159d](https://linux-hardware.org/?probe=a93c59159d) | Mar 20, 2022 |
| Acer          | Swift SF514-55GT            | Notebook    | [ae09c5da41](https://linux-hardware.org/?probe=ae09c5da41) | Mar 20, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [7e8098be12](https://linux-hardware.org/?probe=7e8098be12) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a3a8154156](https://linux-hardware.org/?probe=a3a8154156) | Mar 17, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [d678cbb1cc](https://linux-hardware.org/?probe=d678cbb1cc) | Mar 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5da90f10f4](https://linux-hardware.org/?probe=5da90f10f4) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [28303b98cc](https://linux-hardware.org/?probe=28303b98cc) | Mar 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a339fe7a39](https://linux-hardware.org/?probe=a339fe7a39) | Mar 13, 2022 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [509c41b106](https://linux-hardware.org/?probe=509c41b106) | Mar 13, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c82a0d33a2](https://linux-hardware.org/?probe=c82a0d33a2) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [6034a2269a](https://linux-hardware.org/?probe=6034a2269a) | Mar 09, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [385d1914ee](https://linux-hardware.org/?probe=385d1914ee) | Mar 07, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [3b3220eeee](https://linux-hardware.org/?probe=3b3220eeee) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [6d26072b9e](https://linux-hardware.org/?probe=6d26072b9e) | Mar 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [53d74176e9](https://linux-hardware.org/?probe=53d74176e9) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [73881ad12e](https://linux-hardware.org/?probe=73881ad12e) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Dell          | 0XHGV1 A02                  | Desktop     | [768657efd5](https://linux-hardware.org/?probe=768657efd5) | Mar 03, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [6090fb66ea](https://linux-hardware.org/?probe=6090fb66ea) | Mar 02, 2022 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [c56a98389f](https://linux-hardware.org/?probe=c56a98389f) | Mar 01, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c57b3c9081](https://linux-hardware.org/?probe=c57b3c9081) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [a7034fd62e](https://linux-hardware.org/?probe=a7034fd62e) | Feb 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0P900      | Tablet      | [61c4a46887](https://linux-hardware.org/?probe=61c4a46887) | Feb 26, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [800ecfe818](https://linux-hardware.org/?probe=800ecfe818) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [402a27e190](https://linux-hardware.org/?probe=402a27e190) | Feb 24, 2022 |
| ASUSTek       | X55U                        | Notebook    | [c7c38f077d](https://linux-hardware.org/?probe=c7c38f077d) | Feb 24, 2022 |
| HP            | 84DE                        | All in one  | [43184fd6bf](https://linux-hardware.org/?probe=43184fd6bf) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6083eed5da](https://linux-hardware.org/?probe=6083eed5da) | Feb 21, 2022 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [38a194c33d](https://linux-hardware.org/?probe=38a194c33d) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [c64a5b4adf](https://linux-hardware.org/?probe=c64a5b4adf) | Feb 20, 2022 |
| MSI           | MS-7392                     | Desktop     | [308ed6c0c6](https://linux-hardware.org/?probe=308ed6c0c6) | Feb 20, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [417a759484](https://linux-hardware.org/?probe=417a759484) | Feb 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [dfc7dad0ee](https://linux-hardware.org/?probe=dfc7dad0ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad P50 20ENS0FQ00     | Notebook    | [8d8e30fdfb](https://linux-hardware.org/?probe=8d8e30fdfb) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [be010e2d04](https://linux-hardware.org/?probe=be010e2d04) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [f6383e06d7](https://linux-hardware.org/?probe=f6383e06d7) | Feb 16, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [13989d56ec](https://linux-hardware.org/?probe=13989d56ec) | Feb 14, 2022 |
| MSI           | EX620                       | Notebook    | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e48e07387e](https://linux-hardware.org/?probe=e48e07387e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [be994742e1](https://linux-hardware.org/?probe=be994742e1) | Feb 13, 2022 |
| HP            | 09F8h                       | Desktop     | [d887fef9ff](https://linux-hardware.org/?probe=d887fef9ff) | Feb 13, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [6b45115b9e](https://linux-hardware.org/?probe=6b45115b9e) | Feb 13, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eeeac91ae4](https://linux-hardware.org/?probe=eeeac91ae4) | Feb 13, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [a016adec7d](https://linux-hardware.org/?probe=a016adec7d) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [a4eac4d7b8](https://linux-hardware.org/?probe=a4eac4d7b8) | Feb 11, 2022 |
| Lenovo        | NOK                         | Desktop     | [f860aaeaf3](https://linux-hardware.org/?probe=f860aaeaf3) | Feb 11, 2022 |
| HP            | 0AA8h                       | Desktop     | [a78b5c3460](https://linux-hardware.org/?probe=a78b5c3460) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| Lenovo        | ThinkPad T410 2522Y15       | Notebook    | [66a496ba4c](https://linux-hardware.org/?probe=66a496ba4c) | Feb 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7d600bcdc7](https://linux-hardware.org/?probe=7d600bcdc7) | Feb 08, 2022 |
| Lenovo        | ThinkPad L380 20M5003FUK    | Notebook    | [fe486b4de6](https://linux-hardware.org/?probe=fe486b4de6) | Feb 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS3W300    | Notebook    | [a49c14ab70](https://linux-hardware.org/?probe=a49c14ab70) | Feb 06, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [275d33a826](https://linux-hardware.org/?probe=275d33a826) | Feb 06, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [23b715cc77](https://linux-hardware.org/?probe=23b715cc77) | Feb 05, 2022 |
| Allview       | Allbook H                   | Notebook    | [f1ba3f22c4](https://linux-hardware.org/?probe=f1ba3f22c4) | Feb 05, 2022 |
| Gigabyte      | P35-DS3R                    | Desktop     | [3164a5ed5b](https://linux-hardware.org/?probe=3164a5ed5b) | Feb 05, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [4975c3b6b7](https://linux-hardware.org/?probe=4975c3b6b7) | Feb 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [5eaea69c49](https://linux-hardware.org/?probe=5eaea69c49) | Feb 04, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [d554447e6b](https://linux-hardware.org/?probe=d554447e6b) | Feb 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [4aa3aa1f30](https://linux-hardware.org/?probe=4aa3aa1f30) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [1e330f1e0e](https://linux-hardware.org/?probe=1e330f1e0e) | Feb 02, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [5d9bab6a00](https://linux-hardware.org/?probe=5d9bab6a00) | Feb 02, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [94fefac9e1](https://linux-hardware.org/?probe=94fefac9e1) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [b80429c5fe](https://linux-hardware.org/?probe=b80429c5fe) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [7c2762f41c](https://linux-hardware.org/?probe=7c2762f41c) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [2aa45a8d1b](https://linux-hardware.org/?probe=2aa45a8d1b) | Jan 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [43b14c0f42](https://linux-hardware.org/?probe=43b14c0f42) | Jan 31, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [b61bba90ad](https://linux-hardware.org/?probe=b61bba90ad) | Jan 30, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Acer          | Extensa 2510                | Notebook    | [1fcabc0254](https://linux-hardware.org/?probe=1fcabc0254) | Jan 26, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6d62bb9596](https://linux-hardware.org/?probe=6d62bb9596) | Jan 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [ded9015aff](https://linux-hardware.org/?probe=ded9015aff) | Jan 23, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [6ab6d3c8b2](https://linux-hardware.org/?probe=6ab6d3c8b2) | Jan 23, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [d90de3e8f7](https://linux-hardware.org/?probe=d90de3e8f7) | Jan 21, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [3609f04919](https://linux-hardware.org/?probe=3609f04919) | Jan 19, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [8e66dbbe5c](https://linux-hardware.org/?probe=8e66dbbe5c) | Jan 19, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [d4187f35fd](https://linux-hardware.org/?probe=d4187f35fd) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| Dell          | MXG071                      | Notebook    | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | Notebook    | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Samsung       | R580/R590                   | Notebook    | [be1e77de84](https://linux-hardware.org/?probe=be1e77de84) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [342f6f2beb](https://linux-hardware.org/?probe=342f6f2beb) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [34f103b8d2](https://linux-hardware.org/?probe=34f103b8d2) | Jan 16, 2022 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [12db3650f6](https://linux-hardware.org/?probe=12db3650f6) | Jan 14, 2022 |
| MSI           | 2A9C                        | Desktop     | [09004ce71d](https://linux-hardware.org/?probe=09004ce71d) | Jan 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [15dd95fdfd](https://linux-hardware.org/?probe=15dd95fdfd) | Jan 14, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [615ed31a98](https://linux-hardware.org/?probe=615ed31a98) | Jan 13, 2022 |
| Acer          | Aspire T3-710 V:1.1         | Desktop     | [088a0a9608](https://linux-hardware.org/?probe=088a0a9608) | Jan 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [5f41c8e050](https://linux-hardware.org/?probe=5f41c8e050) | Jan 12, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| HP            | 843B                        | Desktop     | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [1630e680bc](https://linux-hardware.org/?probe=1630e680bc) | Jan 06, 2022 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [3e7d72e09a](https://linux-hardware.org/?probe=3e7d72e09a) | Jan 06, 2022 |
| Chuwi         | Hero Book                   | Notebook    | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Dell          | Inspiron 7586               | Convertible | [9a480f9de9](https://linux-hardware.org/?probe=9a480f9de9) | Jan 04, 2022 |
| ASUSTek       | X550VL                      | Notebook    | [46ed51f6ef](https://linux-hardware.org/?probe=46ed51f6ef) | Jan 04, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [0132076c85](https://linux-hardware.org/?probe=0132076c85) | Jan 04, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [76350af57f](https://linux-hardware.org/?probe=76350af57f) | Jan 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a7217db810](https://linux-hardware.org/?probe=a7217db810) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [286ce69daf](https://linux-hardware.org/?probe=286ce69daf) | Jan 02, 2022 |
| HP            | 1497                        | Desktop     | [540458f943](https://linux-hardware.org/?probe=540458f943) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [f5eafcc9e4](https://linux-hardware.org/?probe=f5eafcc9e4) | Jan 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [50a5dc78eb](https://linux-hardware.org/?probe=50a5dc78eb) | Jan 02, 2022 |
| MSI           | EX705                       | Notebook    | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [a8b3cc88b1](https://linux-hardware.org/?probe=a8b3cc88b1) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [af923f06cc](https://linux-hardware.org/?probe=af923f06cc) | Dec 29, 2021 |
| Dell          | Latitude E5420m             | Notebook    | [6f5af5da5c](https://linux-hardware.org/?probe=6f5af5da5c) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [a7a37c26c7](https://linux-hardware.org/?probe=a7a37c26c7) | Dec 29, 2021 |
| Dream Mach... | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [c3f88b03df](https://linux-hardware.org/?probe=c3f88b03df) | Dec 28, 2021 |
| Lenovo        | ThinkStation E20 4220RF8    | Desktop     | [e525340bef](https://linux-hardware.org/?probe=e525340bef) | Dec 28, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [82a0c6cd43](https://linux-hardware.org/?probe=82a0c6cd43) | Dec 28, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b2b9ea9e60](https://linux-hardware.org/?probe=b2b9ea9e60) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 4291B78       | Notebook    | [2c8a912b3e](https://linux-hardware.org/?probe=2c8a912b3e) | Dec 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [e4dc4b8711](https://linux-hardware.org/?probe=e4dc4b8711) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1f334f4c1c](https://linux-hardware.org/?probe=1f334f4c1c) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| HP            | 18E7                        | Desktop     | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [6748ebc68a](https://linux-hardware.org/?probe=6748ebc68a) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [00868d9166](https://linux-hardware.org/?probe=00868d9166) | Dec 17, 2021 |
| HP            | 1998                        | Desktop     | [9bfa0ed638](https://linux-hardware.org/?probe=9bfa0ed638) | Dec 17, 2021 |
| Timi          | TM1701                      | Notebook    | [f063712cce](https://linux-hardware.org/?probe=f063712cce) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ac40d89d27](https://linux-hardware.org/?probe=ac40d89d27) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [7da5a1020d](https://linux-hardware.org/?probe=7da5a1020d) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | Notebook    | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [b68de5799e](https://linux-hardware.org/?probe=b68de5799e) | Dec 12, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [5d06e53d08](https://linux-hardware.org/?probe=5d06e53d08) | Dec 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ed065155fb](https://linux-hardware.org/?probe=ed065155fb) | Dec 11, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7fe98389c6](https://linux-hardware.org/?probe=7fe98389c6) | Dec 11, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [5be7aac3a2](https://linux-hardware.org/?probe=5be7aac3a2) | Dec 09, 2021 |
| ASUSTek       | V241FA                      | All in one  | [60c6c7ea7c](https://linux-hardware.org/?probe=60c6c7ea7c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [98f25277f5](https://linux-hardware.org/?probe=98f25277f5) | Dec 08, 2021 |
| ASRockRack    | E3C232D4U-V1L               | Desktop     | [139a75e689](https://linux-hardware.org/?probe=139a75e689) | Dec 07, 2021 |
| Dell          | Inspiron 7586               | Convertible | [53604c12d1](https://linux-hardware.org/?probe=53604c12d1) | Dec 05, 2021 |
| INET          | Z12B                        | Mini pc     | [95470b9d91](https://linux-hardware.org/?probe=95470b9d91) | Dec 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c6db4a61b](https://linux-hardware.org/?probe=1c6db4a61b) | Dec 03, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [902395fcce](https://linux-hardware.org/?probe=902395fcce) | Dec 03, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [ad91050095](https://linux-hardware.org/?probe=ad91050095) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [e73cda5c1e](https://linux-hardware.org/?probe=e73cda5c1e) | Dec 02, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [d3040ac7d5](https://linux-hardware.org/?probe=d3040ac7d5) | Nov 30, 2021 |
| Allview       | Allbook J                   | Notebook    | [957074dbe3](https://linux-hardware.org/?probe=957074dbe3) | Nov 30, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [317b686b33](https://linux-hardware.org/?probe=317b686b33) | Nov 29, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [c323b490bf](https://linux-hardware.org/?probe=c323b490bf) | Nov 26, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| Medion        | E7218                       | Notebook    | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| HP            | Compaq 2510p                | Notebook    | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [eb7191f8cb](https://linux-hardware.org/?probe=eb7191f8cb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [1169bef865](https://linux-hardware.org/?probe=1169bef865) | Nov 22, 2021 |
| HP            | Compaq 2510p                | Notebook    | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb48a45349](https://linux-hardware.org/?probe=bb48a45349) | Nov 22, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9a83e53e34](https://linux-hardware.org/?probe=9a83e53e34) | Nov 22, 2021 |
| ASUSTek       | X450CP                      | Notebook    | [7228a5157c](https://linux-hardware.org/?probe=7228a5157c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [04fa536869](https://linux-hardware.org/?probe=04fa536869) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [097de81570](https://linux-hardware.org/?probe=097de81570) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell          | Latitude 7410               | Notebook    | [226f912726](https://linux-hardware.org/?probe=226f912726) | Nov 18, 2021 |
| ASUSTek       | K53U                        | Notebook    | [8b542e61d9](https://linux-hardware.org/?probe=8b542e61d9) | Nov 18, 2021 |
| Dell          | Latitude E7470              | Notebook    | [0358863974](https://linux-hardware.org/?probe=0358863974) | Nov 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2e7ed34d33](https://linux-hardware.org/?probe=2e7ed34d33) | Nov 16, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6677eae4da](https://linux-hardware.org/?probe=6677eae4da) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [1292ab6f15](https://linux-hardware.org/?probe=1292ab6f15) | Nov 14, 2021 |
| Dell          | Latitude E6410              | Notebook    | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [463e1f35a9](https://linux-hardware.org/?probe=463e1f35a9) | Nov 13, 2021 |
| Sony          | SVF14N1E2ES                 | Notebook    | [a04441e5cd](https://linux-hardware.org/?probe=a04441e5cd) | Nov 13, 2021 |
| Dell          | Precision 3541              | Notebook    | [8f6085ab9d](https://linux-hardware.org/?probe=8f6085ab9d) | Nov 12, 2021 |
| Packard Be... | EasyNote TN36               | Notebook    | [17ebc64721](https://linux-hardware.org/?probe=17ebc64721) | Nov 11, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [e70882b3fd](https://linux-hardware.org/?probe=e70882b3fd) | Nov 11, 2021 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b79aef683b](https://linux-hardware.org/?probe=b79aef683b) | Nov 11, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [c32869e5a8](https://linux-hardware.org/?probe=c32869e5a8) | Nov 08, 2021 |
| ASUSTek       | A58M-K                      | Desktop     | [0dbc01db57](https://linux-hardware.org/?probe=0dbc01db57) | Nov 08, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [c0ef5646a8](https://linux-hardware.org/?probe=c0ef5646a8) | Nov 07, 2021 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [6dd5b7f191](https://linux-hardware.org/?probe=6dd5b7f191) | Nov 06, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [c1bd9abdd2](https://linux-hardware.org/?probe=c1bd9abdd2) | Nov 03, 2021 |
| HP            | 18E4                        | Desktop     | [1c3ea795a0](https://linux-hardware.org/?probe=1c3ea795a0) | Nov 03, 2021 |
| HP            | 18E4                        | Desktop     | [4994f5c700](https://linux-hardware.org/?probe=4994f5c700) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| Dell          | G3 3579                     | Notebook    | [f9fdeb003b](https://linux-hardware.org/?probe=f9fdeb003b) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [8cdb34dbc8](https://linux-hardware.org/?probe=8cdb34dbc8) | Nov 01, 2021 |
| Lenovo        | ThinkPad T430 2349U15       | Notebook    | [c9d8efc9b9](https://linux-hardware.org/?probe=c9d8efc9b9) | Oct 31, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [f31e6e3dd0](https://linux-hardware.org/?probe=f31e6e3dd0) | Oct 29, 2021 |
| ASUSTek       | V241EA                      | All in one  | [243713e97a](https://linux-hardware.org/?probe=243713e97a) | Oct 28, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Dell          | 07T4MC A11                  | Desktop     | [219a3a234f](https://linux-hardware.org/?probe=219a3a234f) | Oct 27, 2021 |
| Dell          | 07T4MC A11                  | Desktop     | [870145802c](https://linux-hardware.org/?probe=870145802c) | Oct 27, 2021 |
| Dell          | Latitude E5450              | Notebook    | [fb61a77e5c](https://linux-hardware.org/?probe=fb61a77e5c) | Oct 26, 2021 |
| IBM           | 82121QG                     | Desktop     | [765d524e7f](https://linux-hardware.org/?probe=765d524e7f) | Oct 26, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| Lenovo        | ThinkPad X230 2325SWF       | Notebook    | [64f9882936](https://linux-hardware.org/?probe=64f9882936) | Oct 25, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [69a5d79a58](https://linux-hardware.org/?probe=69a5d79a58) | Oct 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [9b3e361eb7](https://linux-hardware.org/?probe=9b3e361eb7) | Oct 24, 2021 |
| Dell          | Latitude E7470              | Notebook    | [69a251cc1f](https://linux-hardware.org/?probe=69a251cc1f) | Oct 22, 2021 |
| Dell          | Latitude E7470              | Notebook    | [96ef0ee68c](https://linux-hardware.org/?probe=96ef0ee68c) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [21379aad70](https://linux-hardware.org/?probe=21379aad70) | Oct 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f0c049fc34](https://linux-hardware.org/?probe=f0c049fc34) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d550d04ac7](https://linux-hardware.org/?probe=d550d04ac7) | Oct 20, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [8563f3786e](https://linux-hardware.org/?probe=8563f3786e) | Oct 19, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [ac37b3fd23](https://linux-hardware.org/?probe=ac37b3fd23) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [cbf3c67be2](https://linux-hardware.org/?probe=cbf3c67be2) | Oct 18, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [cc0290a8df](https://linux-hardware.org/?probe=cc0290a8df) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [0b2123c367](https://linux-hardware.org/?probe=0b2123c367) | Oct 16, 2021 |
| Dell          | Latitude E7470              | Notebook    | [3bbcb85b9f](https://linux-hardware.org/?probe=3bbcb85b9f) | Oct 16, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| ASRock        | A75 Extreme6                | Desktop     | [5735bac676](https://linux-hardware.org/?probe=5735bac676) | Oct 16, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [fd95402aa1](https://linux-hardware.org/?probe=fd95402aa1) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [538c0f7723](https://linux-hardware.org/?probe=538c0f7723) | Oct 14, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [b59de957b3](https://linux-hardware.org/?probe=b59de957b3) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [a427a26f34](https://linux-hardware.org/?probe=a427a26f34) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1965a71536](https://linux-hardware.org/?probe=1965a71536) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6166a72ec2](https://linux-hardware.org/?probe=6166a72ec2) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [0acb396573](https://linux-hardware.org/?probe=0acb396573) | Oct 11, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [ea162f9171](https://linux-hardware.org/?probe=ea162f9171) | Oct 10, 2021 |
| HP            | 3031h                       | Desktop     | [eb48a6bfe5](https://linux-hardware.org/?probe=eb48a6bfe5) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [d79188a009](https://linux-hardware.org/?probe=d79188a009) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [aae51881da](https://linux-hardware.org/?probe=aae51881da) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [efb88027ec](https://linux-hardware.org/?probe=efb88027ec) | Oct 09, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [ec7609239e](https://linux-hardware.org/?probe=ec7609239e) | Oct 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1f29f9efba](https://linux-hardware.org/?probe=1f29f9efba) | Oct 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2236b91c55](https://linux-hardware.org/?probe=2236b91c55) | Oct 05, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [d23574ecf1](https://linux-hardware.org/?probe=d23574ecf1) | Oct 04, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [97333f9cab](https://linux-hardware.org/?probe=97333f9cab) | Oct 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [2f89b6fcf1](https://linux-hardware.org/?probe=2f89b6fcf1) | Oct 03, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [06d254591f](https://linux-hardware.org/?probe=06d254591f) | Oct 02, 2021 |
| Lenovo        | ThinkPad T470 20HES0FA02    | Notebook    | [b368193a4e](https://linux-hardware.org/?probe=b368193a4e) | Oct 02, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [02d6cacb04](https://linux-hardware.org/?probe=02d6cacb04) | Sep 30, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [032d34e75b](https://linux-hardware.org/?probe=032d34e75b) | Sep 28, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [68a76785a0](https://linux-hardware.org/?probe=68a76785a0) | Sep 27, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [3cbca1757f](https://linux-hardware.org/?probe=3cbca1757f) | Sep 26, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [7baf276ca0](https://linux-hardware.org/?probe=7baf276ca0) | Sep 26, 2021 |
| Alienware     | 17 R2                       | Notebook    | [cbe7430492](https://linux-hardware.org/?probe=cbe7430492) | Sep 26, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [c91cad59c2](https://linux-hardware.org/?probe=c91cad59c2) | Sep 25, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [a44995aac4](https://linux-hardware.org/?probe=a44995aac4) | Sep 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| HP            | EliteBook 8530p             | Notebook    | [8002401481](https://linux-hardware.org/?probe=8002401481) | Sep 23, 2021 |
| Dell          | 0GM819                      | Desktop     | [708ca8f58a](https://linux-hardware.org/?probe=708ca8f58a) | Sep 22, 2021 |
| Dell          | 0GM819                      | Desktop     | [37f5afac35](https://linux-hardware.org/?probe=37f5afac35) | Sep 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [f6dfc42935](https://linux-hardware.org/?probe=f6dfc42935) | Sep 22, 2021 |
| MSI           | A55M-E33                    | Desktop     | [695bc5477d](https://linux-hardware.org/?probe=695bc5477d) | Sep 22, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| ASUSTek       | GL752VW                     | Notebook    | [ec4b89fd42](https://linux-hardware.org/?probe=ec4b89fd42) | Sep 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [75c71d1f1e](https://linux-hardware.org/?probe=75c71d1f1e) | Sep 20, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [7b95b06b4d](https://linux-hardware.org/?probe=7b95b06b4d) | Sep 20, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [3a0a2208fb](https://linux-hardware.org/?probe=3a0a2208fb) | Sep 20, 2021 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [c7e3f44f44](https://linux-hardware.org/?probe=c7e3f44f44) | Sep 19, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [c0b5da7979](https://linux-hardware.org/?probe=c0b5da7979) | Sep 19, 2021 |
| Acer          | AOA110                      | Notebook    | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | Notebook    | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | Notebook    | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| HP            | 3397                        | Desktop     | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [252914c6d3](https://linux-hardware.org/?probe=252914c6d3) | Sep 16, 2021 |
| Supermicro    | X11SSL-CF                   | Server      | [50169a0ffb](https://linux-hardware.org/?probe=50169a0ffb) | Sep 15, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | Desktop     | [d47952ec42](https://linux-hardware.org/?probe=d47952ec42) | Sep 15, 2021 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | Desktop     | [9c310e15bd](https://linux-hardware.org/?probe=9c310e15bd) | Sep 15, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [1493a2eae1](https://linux-hardware.org/?probe=1493a2eae1) | Sep 15, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [8966b3a7b5](https://linux-hardware.org/?probe=8966b3a7b5) | Sep 14, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [8bd6acee77](https://linux-hardware.org/?probe=8bd6acee77) | Sep 13, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [da1dd9bb01](https://linux-hardware.org/?probe=da1dd9bb01) | Sep 13, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [bc6963f758](https://linux-hardware.org/?probe=bc6963f758) | Sep 11, 2021 |
| Packard Be... | EasyNote MV86               | Notebook    | [ea018cddf2](https://linux-hardware.org/?probe=ea018cddf2) | Sep 10, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [151a3381f0](https://linux-hardware.org/?probe=151a3381f0) | Sep 09, 2021 |
| Dell          | Inspiron 5520               | Notebook    | [835f9cb8a1](https://linux-hardware.org/?probe=835f9cb8a1) | Sep 07, 2021 |
| Dell          | Latitude 7410               | Notebook    | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell          | Latitude 7410               | Notebook    | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [576b96b6da](https://linux-hardware.org/?probe=576b96b6da) | Sep 06, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [638993c7b0](https://linux-hardware.org/?probe=638993c7b0) | Sep 06, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [bb0ef0735f](https://linux-hardware.org/?probe=bb0ef0735f) | Sep 05, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | Notebook    | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| ASUSTek       | D340MC-C                    | Desktop     | [cf81a7ddc2](https://linux-hardware.org/?probe=cf81a7ddc2) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [47c2053681](https://linux-hardware.org/?probe=47c2053681) | Sep 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| HP            | 18E9                        | Desktop     | [22f86af485](https://linux-hardware.org/?probe=22f86af485) | Sep 01, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [4765b87a68](https://linux-hardware.org/?probe=4765b87a68) | Sep 01, 2021 |
| MSI           | A88XM-E35                   | Desktop     | [66070c788f](https://linux-hardware.org/?probe=66070c788f) | Sep 01, 2021 |
| HP            | 3032h                       | Desktop     | [7d94cc3baa](https://linux-hardware.org/?probe=7d94cc3baa) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [cd80e1ebb2](https://linux-hardware.org/?probe=cd80e1ebb2) | Aug 31, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [c2b7f1ee7c](https://linux-hardware.org/?probe=c2b7f1ee7c) | Aug 30, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [301be6f800](https://linux-hardware.org/?probe=301be6f800) | Aug 30, 2021 |
| MSI           | MS-16Y1                     | Notebook    | [a9801b616e](https://linux-hardware.org/?probe=a9801b616e) | Aug 29, 2021 |
| HP            | 18E9                        | Desktop     | [539f181954](https://linux-hardware.org/?probe=539f181954) | Aug 29, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [0a9f1f10d8](https://linux-hardware.org/?probe=0a9f1f10d8) | Aug 29, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [fd9d91270d](https://linux-hardware.org/?probe=fd9d91270d) | Aug 29, 2021 |
| ASUSTek       | X450CP                      | Notebook    | [d646ffd8db](https://linux-hardware.org/?probe=d646ffd8db) | Aug 29, 2021 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [30d745e8d3](https://linux-hardware.org/?probe=30d745e8d3) | Aug 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [954900ccc6](https://linux-hardware.org/?probe=954900ccc6) | Aug 28, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [03a89677c0](https://linux-hardware.org/?probe=03a89677c0) | Aug 26, 2021 |
| HP            | Presario CQ57               | Notebook    | [4b863ffc87](https://linux-hardware.org/?probe=4b863ffc87) | Aug 25, 2021 |
| HP            | 84DE                        | All in one  | [11f4f1348a](https://linux-hardware.org/?probe=11f4f1348a) | Aug 25, 2021 |
| HP            | 84DE                        | All in one  | [ba6157396c](https://linux-hardware.org/?probe=ba6157396c) | Aug 25, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f534340eab](https://linux-hardware.org/?probe=f534340eab) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4f6bd2a75e](https://linux-hardware.org/?probe=4f6bd2a75e) | Aug 22, 2021 |
| HP            | Presario CQ57               | Notebook    | [a45389ec74](https://linux-hardware.org/?probe=a45389ec74) | Aug 21, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [eb664f1a19](https://linux-hardware.org/?probe=eb664f1a19) | Aug 20, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [cf9c1726af](https://linux-hardware.org/?probe=cf9c1726af) | Aug 19, 2021 |
| HP            | 1587h                       | Desktop     | [3ddbdb3101](https://linux-hardware.org/?probe=3ddbdb3101) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | Pavilion dv6                | Notebook    | [40cd012d76](https://linux-hardware.org/?probe=40cd012d76) | Aug 18, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [8cf3477dd1](https://linux-hardware.org/?probe=8cf3477dd1) | Aug 18, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7465dcb16d](https://linux-hardware.org/?probe=7465dcb16d) | Aug 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [8bf5049adc](https://linux-hardware.org/?probe=8bf5049adc) | Aug 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [92e25a1c2c](https://linux-hardware.org/?probe=92e25a1c2c) | Aug 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [4b4a995bad](https://linux-hardware.org/?probe=4b4a995bad) | Aug 15, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| HP            | 630                         | Notebook    | [eda8d23dba](https://linux-hardware.org/?probe=eda8d23dba) | Aug 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c8b1a45676](https://linux-hardware.org/?probe=c8b1a45676) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [20a828b938](https://linux-hardware.org/?probe=20a828b938) | Aug 11, 2021 |
| ASUSTek       | X550JX                      | Notebook    | [da2cacc763](https://linux-hardware.org/?probe=da2cacc763) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [86ab410358](https://linux-hardware.org/?probe=86ab410358) | Aug 10, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [d7ad85015d](https://linux-hardware.org/?probe=d7ad85015d) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [99763e52f1](https://linux-hardware.org/?probe=99763e52f1) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | Notebook    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| HP            | 2AE2                        | Desktop     | [e8a9a769fe](https://linux-hardware.org/?probe=e8a9a769fe) | Aug 07, 2021 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [1d3167cdf0](https://linux-hardware.org/?probe=1d3167cdf0) | Aug 05, 2021 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [3118d29bf0](https://linux-hardware.org/?probe=3118d29bf0) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [1a6e7a1825](https://linux-hardware.org/?probe=1a6e7a1825) | Aug 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [a7feba2af0](https://linux-hardware.org/?probe=a7feba2af0) | Aug 04, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [a7c1a61e9f](https://linux-hardware.org/?probe=a7c1a61e9f) | Aug 03, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [d58be51f72](https://linux-hardware.org/?probe=d58be51f72) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [64dcd58bc3](https://linux-hardware.org/?probe=64dcd58bc3) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [462a00dded](https://linux-hardware.org/?probe=462a00dded) | Aug 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5f2773a82c](https://linux-hardware.org/?probe=5f2773a82c) | Aug 02, 2021 |
| Gigabyte      | P75-D3                      | Desktop     | [5f0bee42c2](https://linux-hardware.org/?probe=5f0bee42c2) | Aug 01, 2021 |
| HP            | 2AE2                        | Desktop     | [61acec4a9c](https://linux-hardware.org/?probe=61acec4a9c) | Aug 01, 2021 |
| HP            | 2AE2                        | Desktop     | [3de122823e](https://linux-hardware.org/?probe=3de122823e) | Aug 01, 2021 |
| HP            | 15                          | Notebook    | [715128c8f0](https://linux-hardware.org/?probe=715128c8f0) | Jul 31, 2021 |
| Toshiba       | Satellite Z30-B             | Notebook    | [af9632e99f](https://linux-hardware.org/?probe=af9632e99f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T410 2537CJ0       | Notebook    | [3722a27c42](https://linux-hardware.org/?probe=3722a27c42) | Jul 28, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f448eea5b9](https://linux-hardware.org/?probe=f448eea5b9) | Jul 27, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [a5cc51aec1](https://linux-hardware.org/?probe=a5cc51aec1) | Jul 26, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [9e05add91a](https://linux-hardware.org/?probe=9e05add91a) | Jul 26, 2021 |
| HP            | 1850                        | Desktop     | [76e386707a](https://linux-hardware.org/?probe=76e386707a) | Jul 24, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [7fa1d5f6ab](https://linux-hardware.org/?probe=7fa1d5f6ab) | Jul 24, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [b0ce1bc8f5](https://linux-hardware.org/?probe=b0ce1bc8f5) | Jul 24, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [11daeb0d8d](https://linux-hardware.org/?probe=11daeb0d8d) | Jul 24, 2021 |
| HP            | 0AA8h                       | Desktop     | [a04f3a673d](https://linux-hardware.org/?probe=a04f3a673d) | Jul 23, 2021 |
| HP            | 0AA8h                       | Desktop     | [b3bbc0186c](https://linux-hardware.org/?probe=b3bbc0186c) | Jul 22, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [9f6c5866ae](https://linux-hardware.org/?probe=9f6c5866ae) | Jul 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [74f54d66b2](https://linux-hardware.org/?probe=74f54d66b2) | Jul 20, 2021 |
| Toshiba       | Satellite C660D             | Notebook    | [039468c7c5](https://linux-hardware.org/?probe=039468c7c5) | Jul 18, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [f50ab25a97](https://linux-hardware.org/?probe=f50ab25a97) | Jul 17, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [594955a00b](https://linux-hardware.org/?probe=594955a00b) | Jul 17, 2021 |
| HP            | 3047h                       | Desktop     | [ac149ca840](https://linux-hardware.org/?probe=ac149ca840) | Jul 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e2c9b58e23](https://linux-hardware.org/?probe=e2c9b58e23) | Jul 17, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [14ce128e1a](https://linux-hardware.org/?probe=14ce128e1a) | Jul 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f656b6c149](https://linux-hardware.org/?probe=f656b6c149) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d1105aa53f](https://linux-hardware.org/?probe=d1105aa53f) | Jul 16, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [a2a1798503](https://linux-hardware.org/?probe=a2a1798503) | Jul 15, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [14b9ddda83](https://linux-hardware.org/?probe=14b9ddda83) | Jul 14, 2021 |
| Dell          | 0X9X1W A00                  | Desktop     | [702d489268](https://linux-hardware.org/?probe=702d489268) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [876c8173d3](https://linux-hardware.org/?probe=876c8173d3) | Jul 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f9d7bd513c](https://linux-hardware.org/?probe=f9d7bd513c) | Jul 13, 2021 |
| Lenovo        | 3102 NOK                    | Desktop     | [71974ffb04](https://linux-hardware.org/?probe=71974ffb04) | Jul 12, 2021 |
| Biostar       | N61PA-M2S                   | Desktop     | [346b5914bf](https://linux-hardware.org/?probe=346b5914bf) | Jul 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c9c8fdd393](https://linux-hardware.org/?probe=c9c8fdd393) | Jul 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [76dc55b00e](https://linux-hardware.org/?probe=76dc55b00e) | Jul 11, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [e6d4cd2e90](https://linux-hardware.org/?probe=e6d4cd2e90) | Jul 10, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 208       | 11.32%  |
| Ubuntu 18.04       | 106       | 5.77%   |
| Ubuntu 22.04       | 65        | 3.54%   |
| BlackPanther 18.1  | 59        | 3.21%   |
| OpenMandriva 4.2   | 45        | 2.45%   |
| OpenMandriva 4.3   | 44        | 2.39%   |
| Manjaro            | 29        | 1.58%   |
| Debian 11          | 29        | 1.58%   |
| Arch               | 28        | 1.52%   |
| ROSA R10           | 27        | 1.47%   |
| KDE neon 20.04     | 24        | 1.31%   |
| Zorin 16           | 23        | 1.25%   |
| Pop!_OS 21.04      | 23        | 1.25%   |
| Ubuntu 21.10       | 20        | 1.09%   |
| Pop!_OS 20.04      | 20        | 1.09%   |
| Endless 3.7.8      | 20        | 1.09%   |
| Arch Rolling       | 20        | 1.09%   |
| Zorin 15           | 19        | 1.03%   |
| Fedora 35          | 19        | 1.03%   |
| Ubuntu 20.10       | 18        | 0.98%   |
| Pop!_OS 22.04      | 18        | 0.98%   |
| OpenMandriva 23.01 | 18        | 0.98%   |
| Endless 3.9.5      | 18        | 0.98%   |
| Endless 3.9.1      | 18        | 0.98%   |
| ArcoLinux Rolling  | 18        | 0.98%   |
| Ubuntu 19.10       | 17        | 0.92%   |
| Ubuntu 21.04       | 16        | 0.87%   |
| Ubuntu 19.04       | 15        | 0.82%   |
| Pop!_OS 20.10      | 15        | 0.82%   |
| Linux Mint 20.2    | 15        | 0.82%   |
| Fedora 34          | 15        | 0.82%   |
| Endless 3.8.6      | 15        | 0.82%   |
| Endless 3.8.0      | 15        | 0.82%   |
| Linux Mint 20.3    | 14        | 0.76%   |
| Linux Mint 20.1    | 14        | 0.76%   |
| Fedora 36          | 14        | 0.76%   |
| Ubuntu 22.10       | 13        | 0.71%   |
| ROSA R9            | 13        | 0.71%   |
| Pop!_OS 21.10      | 13        | 0.71%   |
| Debian 10          | 13        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 475       | 27.97%  |
| Endless       | 248       | 14.61%  |
| OpenMandriva  | 123       | 7.24%   |
| Linux Mint    | 91        | 5.36%   |
| Fedora        | 90        | 5.3%    |
| Pop!_OS       | 84        | 4.95%   |
| ROSA          | 65        | 3.83%   |
| BlackPanther  | 61        | 3.59%   |
| Manjaro       | 58        | 3.42%   |
| Debian        | 49        | 2.89%   |
| Arch          | 47        | 2.77%   |
| Zorin         | 45        | 2.65%   |
| KDE neon      | 29        | 1.71%   |
| Xubuntu       | 22        | 1.3%    |
| Kubuntu       | 21        | 1.24%   |
| ArcoLinux     | 20        | 1.18%   |
| openSUSE      | 15        | 0.88%   |
| Clear Linux   | 14        | 0.82%   |
| Ubuntu Unity  | 13        | 0.77%   |
| Kali          | 10        | 0.59%   |
| Gentoo        | 10        | 0.59%   |
| Elementary    | 10        | 0.59%   |
| Ubuntu MATE   | 9         | 0.53%   |
| EndeavourOS   | 8         | 0.47%   |
| SteamOS       | 7         | 0.41%   |
| Peppermint    | 7         | 0.41%   |
| Garuda Linux  | 7         | 0.41%   |
| Linux Lite    | 6         | 0.35%   |
| Lubuntu       | 5         | 0.29%   |
| LMDE          | 5         | 0.29%   |
| Raspbian      | 4         | 0.24%   |
| MX            | 4         | 0.24%   |
| CentOS        | 4         | 0.24%   |
| Ubuntu Budgie | 3         | 0.18%   |
| Solus         | 3         | 0.18%   |
| Nobara        | 3         | 0.18%   |
| Ubuntu Studio | 2         | 0.12%   |
| RHEL          | 2         | 0.12%   |
| Q4OS          | 2         | 0.12%   |
| Oracle Linux  | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 70        | 3.62%   |
| 5.4.0-42-generic                | 50        | 2.58%   |
| 4.18.16-desktop-1bP             | 45        | 2.32%   |
| 5.10.14-desktop-1omv4002        | 44        | 2.27%   |
| 5.16.7-desktop-1omv4003         | 37        | 1.91%   |
| 5.4.0-19-generic                | 32        | 1.65%   |
| 5.3.0-28-generic                | 26        | 1.34%   |
| 5.3.0-23-generic                | 18        | 0.93%   |
| 6.1.1-desktop-1omv2290          | 17        | 0.88%   |
| 4.18.0-15-generic               | 17        | 0.88%   |
| 5.11.0-35-generic               | 16        | 0.83%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 16        | 0.83%   |
| 5.0.0-25-generic                | 15        | 0.77%   |
| 5.6.14-desktop-2bP              | 14        | 0.72%   |
| 5.4.0-40-generic                | 14        | 0.72%   |
| 5.3.0-46-generic                | 13        | 0.67%   |
| 5.15.0-58-generic               | 13        | 0.67%   |
| 5.0.0-20-generic                | 12        | 0.62%   |
| 5.4.0-52-generic                | 11        | 0.57%   |
| 5.4.0-29-generic                | 11        | 0.57%   |
| 5.4.0-26-generic                | 11        | 0.57%   |
| 5.3.0-19-generic                | 11        | 0.57%   |
| 5.15.0-52-generic               | 11        | 0.57%   |
| 5.4.0-56-generic                | 10        | 0.52%   |
| 5.4.0-54-generic                | 10        | 0.52%   |
| 5.15.0-56-generic               | 10        | 0.52%   |
| 5.13.0-28-generic               | 10        | 0.52%   |
| 5.11.0-7620-generic             | 10        | 0.52%   |
| 5.11.0-43-generic               | 10        | 0.52%   |
| 5.0.0-37-generic                | 10        | 0.52%   |
| 4.15.0-15-generic               | 10        | 0.52%   |
| 5.8.0-50-generic                | 9         | 0.46%   |
| 5.4.0-7634-generic              | 9         | 0.46%   |
| 5.4.0-74-generic                | 9         | 0.46%   |
| 5.4.0-66-generic                | 9         | 0.46%   |
| 5.4.0-47-generic                | 9         | 0.46%   |
| 5.4.0-37-generic                | 9         | 0.46%   |
| 5.4.0-31-generic                | 9         | 0.46%   |
| 5.3.0-51-generic                | 9         | 0.46%   |
| 5.15.0-48-generic               | 9         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 304       | 16.43%  |
| 5.8.0   | 151       | 8.16%   |
| 5.3.0   | 117       | 6.32%   |
| 5.15.0  | 111       | 6%      |
| 5.11.0  | 98        | 5.3%    |
| 4.15.0  | 97        | 5.24%   |
| 5.0.0   | 80        | 4.32%   |
| 5.13.0  | 67        | 3.62%   |
| 4.18.0  | 52        | 2.81%   |
| 5.10.14 | 45        | 2.43%   |
| 4.18.16 | 45        | 2.43%   |
| 5.16.7  | 37        | 2%      |
| 5.10.0  | 37        | 2%      |
| 5.19.0  | 32        | 1.73%   |
| 6.1.1   | 20        | 1.08%   |
| 4.9.60  | 18        | 0.97%   |
| 5.6.14  | 15        | 0.81%   |
| 4.9.20  | 15        | 0.81%   |
| 4.19.0  | 11        | 0.59%   |
| 6.1.12  | 10        | 0.54%   |
| 4.13.0  | 10        | 0.54%   |
| 6.2.6   | 8         | 0.43%   |
| 4.9.76  | 8         | 0.43%   |
| 6.0.11  | 7         | 0.38%   |
| 5.8.18  | 7         | 0.38%   |
| 5.16.13 | 7         | 0.38%   |
| 6.0.0   | 6         | 0.32%   |
| 5.18.10 | 6         | 0.32%   |
| 5.17.0  | 6         | 0.32%   |
| 6.0.6   | 5         | 0.27%   |
| 6.0.12  | 5         | 0.27%   |
| 5.9.16  | 5         | 0.27%   |
| 5.9.0   | 5         | 0.27%   |
| 5.18.12 | 5         | 0.27%   |
| 5.18.0  | 5         | 0.27%   |
| 5.15.8  | 5         | 0.27%   |
| 5.15.12 | 5         | 0.27%   |
| 5.14.0  | 5         | 0.27%   |
| 5.8.3   | 4         | 0.22%   |
| 5.4.18  | 4         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 326       | 17.81%  |
| 5.8     | 178       | 9.73%   |
| 5.15    | 155       | 8.47%   |
| 5.3     | 127       | 6.94%   |
| 5.11    | 112       | 6.12%   |
| 5.10    | 105       | 5.74%   |
| 4.18    | 99        | 5.41%   |
| 4.15    | 97        | 5.3%    |
| 5.0     | 85        | 4.64%   |
| 5.13    | 74        | 4.04%   |
| 5.16    | 69        | 3.77%   |
| 5.19    | 51        | 2.79%   |
| 4.9     | 50        | 2.73%   |
| 6.1     | 44        | 2.4%    |
| 6.0     | 35        | 1.91%   |
| 5.6     | 29        | 1.58%   |
| 5.18    | 26        | 1.42%   |
| 5.9     | 22        | 1.2%    |
| 5.17    | 22        | 1.2%    |
| 5.14    | 19        | 1.04%   |
| 6.2     | 18        | 0.98%   |
| 5.12    | 18        | 0.98%   |
| 4.19    | 14        | 0.77%   |
| 5.7     | 10        | 0.55%   |
| 4.13    | 10        | 0.55%   |
| 4.1     | 8         | 0.44%   |
| 5.5     | 7         | 0.38%   |
| 5.2     | 5         | 0.27%   |
| 5.1     | 4         | 0.22%   |
| 4.8     | 3         | 0.16%   |
| 4.12    | 2         | 0.11%   |
| 4.4     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |
| 3.10    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1595      | 97.43%  |
| i686    | 34        | 2.08%   |
| armv7l  | 4         | 0.24%   |
| aarch64 | 4         | 0.24%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 805       | 47.21%  |
| KDE5             | 316       | 18.53%  |
| Unknown          | 224       | 13.14%  |
| XFCE             | 91        | 5.34%   |
| X-Cinnamon       | 65        | 3.81%   |
| KDE4             | 44        | 2.58%   |
| KDE              | 39        | 2.29%   |
| MATE             | 27        | 1.58%   |
| Unity            | 13        | 0.76%   |
| Cinnamon         | 13        | 0.76%   |
| LXQt             | 12        | 0.7%    |
| LXDE             | 12        | 0.7%    |
| Pantheon         | 8         | 0.47%   |
| i3               | 7         | 0.41%   |
| Budgie           | 4         | 0.23%   |
| Openbox          | 3         | 0.18%   |
| GNOME Classic    | 3         | 0.18%   |
| Deepin           | 3         | 0.18%   |
| xmonad           | 2         | 0.12%   |
| sway             | 2         | 0.12%   |
| GNOME Flashback  | 2         | 0.12%   |
| awesome          | 2         | 0.12%   |
| sussy_bspwm      | 1         | 0.06%   |
| lightdm-xsession | 1         | 0.06%   |
| jwm              | 1         | 0.06%   |
| Hyprland         | 1         | 0.06%   |
| GNUstep          | 1         | 0.06%   |
| GNOME-Flashback  | 1         | 0.06%   |
| dusk             | 1         | 0.06%   |
| bspwm            | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1317      | 78.63%  |
| Wayland     | 187       | 11.16%  |
| Unknown     | 148       | 8.84%   |
| Tty         | 22        | 1.31%   |
| Unspecified | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 934       | 54.75%  |
| SDDM    | 280       | 16.41%  |
| GDM     | 168       | 9.85%   |
| GDM3    | 127       | 7.44%   |
| LightDM | 103       | 6.04%   |
| KDM     | 44        | 2.58%   |
| TDM     | 41        | 2.4%    |
| XDM     | 3         | 0.18%   |
| SLiM    | 3         | 0.18%   |
| Ly      | 1         | 0.06%   |
| LXDM    | 1         | 0.06%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 978       | 57.97%  |
| Unknown     | 310       | 18.38%  |
| ro_RO       | 290       | 17.19%  |
| en_GB       | 31        | 1.84%   |
| C           | 24        | 1.42%   |
| hu_HU       | 13        | 0.77%   |
| it_IT       | 10        | 0.59%   |
| es_ES       | 6         | 0.36%   |
| de_DE       | 4         | 0.24%   |
| fr_FR       | 3         | 0.18%   |
| en_IL       | 3         | 0.18%   |
| ru_RU       | 2         | 0.12%   |
| en_IN       | 2         | 0.12%   |
| en_AG       | 2         | 0.12%   |
| nl_NL       | 1         | 0.06%   |
| fr_CH       | 1         | 0.06%   |
| es_MX       | 1         | 0.06%   |
| en_US.UTF8  | 1         | 0.06%   |
| en_US.utf-8 | 1         | 0.06%   |
| en_DE       | 1         | 0.06%   |
| en_CA       | 1         | 0.06%   |
| en_001      | 1         | 0.06%   |
| C.UTF8      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 840       | 50.3%   |
| BIOS | 830       | 49.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1211      | 72.13%  |
| Overlay | 172       | 10.24%  |
| Unknown | 154       | 9.17%   |
| Btrfs   | 105       | 6.25%   |
| Xfs     | 17        | 1.01%   |
| Tmpfs   | 7         | 0.42%   |
| Zfs     | 5         | 0.3%    |
| F2fs    | 3         | 0.18%   |
| Ext2    | 3         | 0.18%   |
| Jfs     | 1         | 0.06%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 966       | 57.84%  |
| GPT     | 474       | 28.38%  |
| MBR     | 230       | 13.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1440      | 86.38%  |
| Yes       | 227       | 13.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1205      | 72.2%   |
| Yes       | 464       | 27.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 429       | 26.24%  |
| Lenovo                  | 259       | 15.84%  |
| Dell                    | 192       | 11.74%  |
| Hewlett-Packard         | 189       | 11.56%  |
| Gigabyte Technology     | 119       | 7.28%   |
| Acer                    | 112       | 6.85%   |
| MSI                     | 76        | 4.65%   |
| ASRock                  | 45        | 2.75%   |
| Toshiba                 | 24        | 1.47%   |
| Intel                   | 15        | 0.92%   |
| Fujitsu Siemens         | 14        | 0.86%   |
| Apple                   | 13        | 0.8%    |
| Complet                 | 12        | 0.73%   |
| Sony                    | 10        | 0.61%   |
| Medion                  | 9         | 0.55%   |
| Unknown                 | 9         | 0.55%   |
| Raspberry Pi Foundation | 8         | 0.49%   |
| HUAWEI                  | 8         | 0.49%   |
| Fujitsu                 | 8         | 0.49%   |
| Samsung Electronics     | 7         | 0.43%   |
| Valve                   | 6         | 0.37%   |
| Pegatron                | 6         | 0.37%   |
| Foxconn                 | 6         | 0.37%   |
| Chuwi                   | 5         | 0.31%   |
| Allview                 | 5         | 0.31%   |
| Packard Bell            | 4         | 0.24%   |
| Alienware               | 3         | 0.18%   |
| TUXEDO                  | 2         | 0.12%   |
| Timi                    | 2         | 0.12%   |
| Supermicro              | 2         | 0.12%   |
| IBM                     | 2         | 0.12%   |
| AMI                     | 2         | 0.12%   |
| ZOTAC                   | 1         | 0.06%   |
| Visual Fan              | 1         | 0.06%   |
| VALE                    | 1         | 0.06%   |
| Thomson                 | 1         | 0.06%   |
| SLIMBOOK                | 1         | 0.06%   |
| Prestigio               | 1         | 0.06%   |
| Panasonic               | 1         | 0.06%   |
| OEM_MB                  | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS X541NA                                | 17        | 1.04%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 16        | 0.98%   |
| ASUS All Series                            | 13        | 0.8%    |
| Unknown                                    | 12        | 0.73%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 0.61%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 9         | 0.55%   |
| Gigabyte B450M DS3H                        | 7         | 0.43%   |
| Dell XPS 15 9530                           | 7         | 0.43%   |
| Complet MY8312                             | 7         | 0.43%   |
| ASUS X406UAR                               | 7         | 0.43%   |
| Valve Jupiter                              | 6         | 0.37%   |
| Lenovo Legion Y530-15ICH 81FV              | 6         | 0.37%   |
| ASUS X541UVK                               | 6         | 0.37%   |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.37%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.37%   |
| Lenovo V330-15IKB 81AX                     | 5         | 0.31%   |
| ASUS X541UAK                               | 5         | 0.31%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.31%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.31%   |
| Acer Aspire A315-21G                       | 5         | 0.31%   |
| MSI MS-7996                                | 4         | 0.24%   |
| MSI MS-7721                                | 4         | 0.24%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.24%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.24%   |
| Lenovo G510 20238                          | 4         | 0.24%   |
| HP Notebook                                | 4         | 0.24%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 4         | 0.24%   |
| Dell OptiPlex 7010                         | 4         | 0.24%   |
| Dell Latitude E6410                        | 4         | 0.24%   |
| Dell Inspiron 5558                         | 4         | 0.24%   |
| Dell Inspiron 1545                         | 4         | 0.24%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.24%   |
| ASUS X542UAR                               | 4         | 0.24%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.24%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 4         | 0.24%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 4         | 0.24%   |
| ASUS GL552JX                               | 4         | 0.24%   |
| Acer Aspire E5-573G                        | 4         | 0.24%   |
| Acer Aspire E1-531                         | 4         | 0.24%   |
| RPi Raspberry Pi                           | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUS VivoBook           | 113       | 6.91%   |
| Lenovo IdeaPad          | 79        | 4.83%   |
| Lenovo ThinkPad         | 78        | 4.77%   |
| Acer Aspire             | 74        | 4.53%   |
| Dell Latitude           | 53        | 3.24%   |
| Dell Inspiron           | 48        | 2.94%   |
| HP Compaq               | 34        | 2.08%   |
| ASUS PRIME              | 30        | 1.83%   |
| HP EliteBook            | 29        | 1.77%   |
| Dell OptiPlex           | 29        | 1.77%   |
| HP ProBook              | 27        | 1.65%   |
| ASUS ROG                | 27        | 1.65%   |
| Toshiba Satellite       | 23        | 1.41%   |
| HP Pavilion             | 21        | 1.28%   |
| Lenovo Legion           | 20        | 1.22%   |
| Dell XPS                | 19        | 1.16%   |
| ASUS ASUS               | 18        | 1.1%    |
| ASUS X541NA             | 17        | 1.04%   |
| ASUS TUF                | 17        | 1.04%   |
| Lenovo ThinkCentre      | 16        | 0.98%   |
| HP Laptop               | 15        | 0.92%   |
| ASUS All                | 13        | 0.8%    |
| Dell Vostro             | 12        | 0.73%   |
| Unknown                 | 12        | 0.73%   |
| Dell Precision          | 11        | 0.67%   |
| ASUS ZenBook            | 11        | 0.67%   |
| Fujitsu Siemens ESPRIMO | 9         | 0.55%   |
| RPi Raspberry           | 8         | 0.49%   |
| Lenovo ThinkBook        | 8         | 0.49%   |
| Gigabyte B450M          | 8         | 0.49%   |
| Acer Nitro              | 8         | 0.49%   |
| Lenovo Yoga             | 7         | 0.43%   |
| HP ZBook                | 7         | 0.43%   |
| HP 250                  | 7         | 0.43%   |
| Complet MY8312          | 7         | 0.43%   |
| ASUS X406UAR            | 7         | 0.43%   |
| Acer Extensa            | 7         | 0.43%   |
| Valve Jupiter           | 6         | 0.37%   |
| Gigabyte X570           | 6         | 0.37%   |
| Dell System             | 6         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 206       | 12.6%   |
| 2018    | 191       | 11.68%  |
| 2017    | 136       | 8.32%   |
| 2020    | 131       | 8.01%   |
| 2013    | 111       | 6.79%   |
| 2015    | 109       | 6.67%   |
| 2021    | 99        | 6.06%   |
| 2011    | 92        | 5.63%   |
| 2012    | 90        | 5.5%    |
| 2014    | 84        | 5.14%   |
| 2010    | 74        | 4.53%   |
| 2016    | 69        | 4.22%   |
| 2008    | 66        | 4.04%   |
| 2007    | 56        | 3.43%   |
| 2009    | 55        | 3.36%   |
| 2022    | 34        | 2.08%   |
| 2006    | 17        | 1.04%   |
| Unknown | 8         | 0.49%   |
| 2005    | 5         | 0.31%   |
| 2004    | 2         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1061      | 64.89%  |
| Desktop        | 497       | 30.4%   |
| All in one     | 22        | 1.35%   |
| Convertible    | 16        | 0.98%   |
| Mini pc        | 15        | 0.92%   |
| Tablet         | 9         | 0.55%   |
| System on chip | 8         | 0.49%   |
| Server         | 7         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1564      | 94.96%  |
| Enabled  | 83        | 5.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1635      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 454       | 27.25%  |
| 4.01-8.0        | 391       | 23.47%  |
| 8.01-16.0       | 298       | 17.89%  |
| 16.01-24.0      | 266       | 15.97%  |
| 32.01-64.0      | 104       | 6.24%   |
| 1.01-2.0        | 73        | 4.38%   |
| 64.01-256.0     | 31        | 1.86%   |
| 24.01-32.0      | 17        | 1.02%   |
| 2.01-3.0        | 17        | 1.02%   |
| 0.51-1.0        | 14        | 0.84%   |
| More than 256.0 | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 695       | 37.94%  |
| 2.01-3.0    | 452       | 24.67%  |
| 3.01-4.0    | 210       | 11.46%  |
| 0.51-1.0    | 185       | 10.1%   |
| 4.01-8.0    | 180       | 9.83%   |
| 8.01-16.0   | 58        | 3.17%   |
| 0.01-0.5    | 41        | 2.24%   |
| 16.01-24.0  | 5         | 0.27%   |
| 32.01-64.0  | 2         | 0.11%   |
| 24.01-32.0  | 2         | 0.11%   |
| 64.01-256.0 | 2         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1104      | 65.52%  |
| 2      | 380       | 22.55%  |
| 3      | 106       | 6.29%   |
| 4      | 43        | 2.55%   |
| 5      | 19        | 1.13%   |
| 0      | 14        | 0.83%   |
| 6      | 6         | 0.36%   |
| 9      | 4         | 0.24%   |
| 7      | 3         | 0.18%   |
| 8      | 2         | 0.12%   |
| 24     | 1         | 0.06%   |
| 15     | 1         | 0.06%   |
| 14     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1002      | 60.8%   |
| Yes       | 646       | 39.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1349      | 82.46%  |
| No        | 287       | 17.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1262      | 76.62%  |
| No        | 385       | 23.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1013      | 61.25%  |
| No        | 641       | 38.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Romania | 1635      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 529       | 30.42%  |
| Cluj-Napoca           | 122       | 7.02%   |
| Iasi                  | 86        | 4.95%   |
| Timișoara            | 61        | 3.51%   |
| Brasov                | 47        | 2.7%    |
| Târgu Mureş         | 44        | 2.53%   |
| Ploieşti             | 40        | 2.3%    |
| Constanța            | 35        | 2.01%   |
| Sibiu                 | 33        | 1.9%    |
| Oradea                | 31        | 1.78%   |
| Piteşti              | 26        | 1.5%    |
| Arad                  | 26        | 1.5%    |
| Craiova               | 22        | 1.27%   |
| Popesti-Leordeni      | 21        | 1.21%   |
| Galati                | 18        | 1.04%   |
| Baia Mare             | 18        | 1.04%   |
| Zalău                | 17        | 0.98%   |
| Voluntari             | 15        | 0.86%   |
| Râmnicu Vâlcea      | 14        | 0.81%   |
| Bacau                 | 14        | 0.81%   |
| Satu Mare             | 13        | 0.75%   |
| Miercurea-Ciuc        | 13        | 0.75%   |
| Targoviste            | 12        | 0.69%   |
| Piatra Neamţ         | 12        | 0.69%   |
| Botosani              | 12        | 0.69%   |
| Floresti              | 11        | 0.63%   |
| Braila                | 11        | 0.63%   |
| Reşiţa              | 10        | 0.58%   |
| Focşani              | 10        | 0.58%   |
| Drobeta-Turnu Severin | 10        | 0.58%   |
| Alba Iulia            | 10        | 0.58%   |
| Tulcea                | 8         | 0.46%   |
| Târgu Jiu            | 8         | 0.46%   |
| Sfantu Gheorghe       | 8         | 0.46%   |
| Mediaş               | 8         | 0.46%   |
| Beiuș                | 8         | 0.46%   |
| Deva                  | 7         | 0.4%    |
| Alexandria            | 7         | 0.4%    |
| Sighetu Marmaţiei    | 6         | 0.35%   |
| Pantelimon            | 6         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 347       | 501    | 15.07%  |
| Seagate                     | 343       | 530    | 14.89%  |
| Samsung Electronics         | 296       | 397    | 12.85%  |
| Kingston                    | 274       | 370    | 11.9%   |
| Toshiba                     | 166       | 207    | 7.21%   |
| SanDisk                     | 89        | 106    | 3.86%   |
| Unknown                     | 84        | 112    | 3.65%   |
| A-DATA Technology           | 82        | 102    | 3.56%   |
| Intel                       | 77        | 96     | 3.34%   |
| SK hynix                    | 63        | 85     | 2.74%   |
| Hitachi                     | 62        | 80     | 2.69%   |
| HGST                        | 60        | 76     | 2.61%   |
| Micron Technology           | 37        | 45     | 1.61%   |
| Crucial                     | 32        | 39     | 1.39%   |
| Patriot                     | 22        | 26     | 0.96%   |
| Phison                      | 16        | 19     | 0.69%   |
| Maxtor                      | 16        | 23     | 0.69%   |
| Hewlett-Packard             | 13        | 15     | 0.56%   |
| SPCC                        | 12        | 15     | 0.52%   |
| Kingston Technology Company | 12        | 13     | 0.52%   |
| KIOXIA                      | 11        | 11     | 0.48%   |
| OCZ                         | 9         | 18     | 0.39%   |
| FORESEE                     | 9         | 10     | 0.39%   |
| Corsair                     | 9         | 14     | 0.39%   |
| XPG                         | 8         | 12     | 0.35%   |
| Transcend                   | 7         | 9      | 0.3%    |
| Realtek Semiconductor       | 7         | 8      | 0.3%    |
| Gigabyte Technology         | 7         | 7      | 0.3%    |
| Fujitsu                     | 7         | 8      | 0.3%    |
| Kingmax                     | 6         | 7      | 0.26%   |
| China                       | 6         | 6      | 0.26%   |
| Apple                       | 6         | 9      | 0.26%   |
| Team                        | 5         | 5      | 0.22%   |
| Silicon Motion              | 5         | 5      | 0.22%   |
| Plextor                     | 5         | 5      | 0.22%   |
| Phison Electronics          | 5         | 5      | 0.22%   |
| Netac                       | 5         | 7      | 0.22%   |
| GOODRAM                     | 5         | 5      | 0.22%   |
| ASMT                        | 5         | 5      | 0.22%   |
| Emtec                       | 4         | 4      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 64        | 2.59%   |
| Toshiba MQ01ABF050 500GB                          | 45        | 1.82%   |
| Seagate ST1000LM035-1RK172 970GB                  | 44        | 1.78%   |
| Seagate ST500LT012-1DG142 500GB                   | 29        | 1.17%   |
| Kingston SA400S37120G 120GB SSD                   | 29        | 1.17%   |
| Kingston SA400S37480G 480GB SSD                   | 28        | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB                    | 25        | 1.01%   |
| Kingston SV300S37A120G 120GB SSD                  | 22        | 0.89%   |
| Toshiba MQ04ABF100 1TB                            | 21        | 0.85%   |
| Samsung NVMe SSD Drive 512GB                      | 21        | 0.85%   |
| Unknown MMC Card  32GB                            | 20        | 0.81%   |
| HGST HTS721010A9E630 1TB                          | 20        | 0.81%   |
| SanDisk NVMe SSD Drive 256GB                      | 18        | 0.73%   |
| Samsung SSD 860 EVO 500GB                         | 18        | 0.73%   |
| Samsung SSD 850 EVO 250GB                         | 18        | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 17        | 0.69%   |
| SanDisk NVMe SSD Drive 512GB                      | 16        | 0.65%   |
| Seagate ST500DM002-1BD142 500GB                   | 14        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 14        | 0.57%   |
| Kingston SV300S37A240G 240GB SSD                  | 14        | 0.57%   |
| Toshiba MQ01ABD100 1TB                            | 13        | 0.53%   |
| A-DATA SU650 240GB SSD                            | 13        | 0.53%   |
| SK hynix NVMe SSD Drive 512GB                     | 12        | 0.49%   |
| Seagate Expansion 4TB                             | 12        | 0.49%   |
| Patriot Burst 120GB SSD                           | 12        | 0.49%   |
| Kingston SUV400S37120G 120GB SSD                  | 12        | 0.49%   |
| Intel NVMe SSD Drive 512GB                        | 12        | 0.49%   |
| Toshiba DT01ACA050 500GB                          | 11        | 0.44%   |
| Samsung SSD 860 EVO 250GB                         | 11        | 0.44%   |
| Samsung NVMe SSD Drive 256GB                      | 11        | 0.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 11        | 0.44%   |
| HGST HTS545050A7E680 500GB                        | 11        | 0.44%   |
| Unknown MMC Card  64GB                            | 10        | 0.4%    |
| Kingston RBUSNS8180DS3256GJ 256GB SSD             | 9         | 0.36%   |
| Kingston RBUSC180DS37256GJ 256GB SSD              | 9         | 0.36%   |
| HGST HTS541010A9E680 1TB                          | 9         | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 8         | 0.32%   |
| SK hynix HFS256G39TND-N210A 256GB SSD             | 8         | 0.32%   |
| Samsung SSD 860 QVO 1TB                           | 8         | 0.32%   |
| Samsung SSD 850 EVO 500GB                         | 8         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 341       | 524    | 35.12%  |
| WDC                 | 291       | 431    | 29.97%  |
| Toshiba             | 143       | 177    | 14.73%  |
| Hitachi             | 62        | 80     | 6.39%   |
| HGST                | 60        | 76     | 6.18%   |
| Samsung Electronics | 32        | 38     | 3.3%    |
| Maxtor              | 15        | 22     | 1.54%   |
| Unknown             | 7         | 8      | 0.72%   |
| Fujitsu             | 7         | 8      | 0.72%   |
| Apple               | 3         | 4      | 0.31%   |
| IBM/Hitachi         | 2         | 2      | 0.21%   |
| Hewlett-Packard     | 2         | 3      | 0.21%   |
| LaCie               | 1         | 6      | 0.1%    |
| Intenso             | 1         | 1      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| ASMT109x            | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 237       | 316    | 31.35%  |
| Samsung Electronics | 128       | 175    | 16.93%  |
| A-DATA Technology   | 76        | 96     | 10.05%  |
| SanDisk             | 39        | 50     | 5.16%   |
| Crucial             | 28        | 35     | 3.7%    |
| Intel               | 27        | 30     | 3.57%   |
| WDC                 | 23        | 27     | 3.04%   |
| SK hynix            | 21        | 29     | 2.78%   |
| Patriot             | 21        | 25     | 2.78%   |
| Micron Technology   | 14        | 15     | 1.85%   |
| SPCC                | 12        | 15     | 1.59%   |
| Toshiba             | 10        | 11     | 1.32%   |
| OCZ                 | 9         | 18     | 1.19%   |
| Hewlett-Packard     | 9         | 9      | 1.19%   |
| FORESEE             | 9         | 10     | 1.19%   |
| Corsair             | 7         | 11     | 0.93%   |
| Transcend           | 6         | 8      | 0.79%   |
| Kingmax             | 6         | 7      | 0.79%   |
| Gigabyte Technology | 6         | 6      | 0.79%   |
| China               | 6         | 6      | 0.79%   |
| Team                | 5         | 5      | 0.66%   |
| Netac               | 5         | 7      | 0.66%   |
| GOODRAM             | 5         | 5      | 0.66%   |
| Emtec               | 4         | 4      | 0.53%   |
| ASMT                | 4         | 4      | 0.53%   |
| Apacer              | 4         | 5      | 0.53%   |
| Verbatim            | 3         | 5      | 0.4%    |
| TO Exter            | 3         | 5      | 0.4%    |
| PNY                 | 3         | 4      | 0.4%    |
| LITEON              | 3         | 3      | 0.4%    |
| Teclast             | 2         | 2      | 0.26%   |
| LITEONIT            | 2         | 2      | 0.26%   |
| Lite-On             | 2         | 2      | 0.26%   |
| Wibtek              | 1         | 1      | 0.13%   |
| W800S               | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |
| OCZ-VERTEX3         | 1         | 1      | 0.13%   |
| MicroFrom           | 1         | 1      | 0.13%   |
| Maxtor              | 1         | 1      | 0.13%   |
| Kston               | 1         | 5      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 845       | 1384   | 40.7%   |
| SSD     | 678       | 975    | 32.66%  |
| NVMe    | 464       | 626    | 22.35%  |
| MMC     | 73        | 97     | 3.52%   |
| Unknown | 16        | 21     | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1238      | 2284   | 67.28%  |
| NVMe | 464       | 626    | 25.22%  |
| MMC  | 73        | 97     | 3.97%   |
| SAS  | 65        | 96     | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 965       | 1527   | 63.7%   |
| 0.51-1.0   | 413       | 564    | 27.26%  |
| 1.01-2.0   | 73        | 115    | 4.82%   |
| 3.01-4.0   | 30        | 51     | 1.98%   |
| 4.01-10.0  | 16        | 49     | 1.06%   |
| 2.01-3.0   | 14        | 47     | 0.92%   |
| 10.01-20.0 | 4         | 6      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 482       | 27.56%  |
| 251-500        | 384       | 21.96%  |
| 501-1000       | 272       | 15.55%  |
| 1-20           | 169       | 9.66%   |
| 51-100         | 121       | 6.92%   |
| 1001-2000      | 96        | 5.49%   |
| 21-50          | 78        | 4.46%   |
| Unknown        | 74        | 4.23%   |
| More than 3000 | 39        | 2.23%   |
| 2001-3000      | 34        | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 720       | 40%     |
| 21-50          | 359       | 19.94%  |
| 101-250        | 194       | 10.78%  |
| 51-100         | 191       | 10.61%  |
| 251-500        | 107       | 5.94%   |
| 501-1000       | 86        | 4.78%   |
| Unknown        | 74        | 4.11%   |
| 1001-2000      | 46        | 2.56%   |
| More than 3000 | 16        | 0.89%   |
| 2001-3000      | 7         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB        | 7         | 7      | 3.55%   |
| HGST HTS545050A7E680 500GB           | 4         | 4      | 2.03%   |
| HGST HTS541010A9E680 1TB             | 4         | 4      | 2.03%   |
| WDC WD5000AAKX-001CA0 500GB          | 3         | 3      | 1.52%   |
| WDC WD3200AAJS-60Z0A0 320GB          | 3         | 6      | 1.52%   |
| Seagate ST9500420AS 500GB            | 3         | 3      | 1.52%   |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 1.52%   |
| WDC WD5000AADS-00S9B0 500GB          | 2         | 2      | 1.02%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB | 2         | 2      | 1.02%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2      | 1.02%   |
| Seagate STM3250318AS 250GB           | 2         | 3      | 1.02%   |
| Seagate ST95005620AS 500GB           | 2         | 5      | 1.02%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 1.02%   |
| Seagate ST9160821AS 160GB            | 2         | 2      | 1.02%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 3      | 1.02%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 2      | 1.02%   |
| Seagate ST3500320AS 500GB            | 2         | 3      | 1.02%   |
| Seagate ST3500312CS 500GB            | 2         | 2      | 1.02%   |
| Seagate ST3250318AS 250GB            | 2         | 3      | 1.02%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 2      | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2      | 1.02%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 3      | 1.02%   |
| OCZ ARC100 240GB SSD                 | 2         | 2      | 1.02%   |
| Maxtor STM3250310AS 250GB            | 2         | 3      | 1.02%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 2      | 1.02%   |
| Hitachi HTS725032A9A364 320GB        | 2         | 2      | 1.02%   |
| Hitachi HTS545016B9A300 160GB        | 2         | 2      | 1.02%   |
| Apacer 16GB SATA Flash Drive SSD     | 2         | 3      | 1.02%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 1      | 0.51%   |
| WDC WD7500BPVT-60HXZT3 752GB         | 1         | 2      | 0.51%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 1      | 0.51%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 0.51%   |
| WDC WD5000BPKT-60PK4T0 500GB         | 1         | 2      | 0.51%   |
| WDC WD5000BEVT-60A0RT0 500GB         | 1         | 1      | 0.51%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 1      | 0.51%   |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 4      | 0.51%   |
| WDC WD400EB-00CPF0 40GB              | 1         | 1      | 0.51%   |
| WDC WD400BD-08JMC0 40GB              | 1         | 1      | 0.51%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 0.51%   |
| WDC WD3200AVVS-63L2B0 320GB          | 1         | 1      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 62     | 25%     |
| WDC                 | 44        | 67     | 23.4%   |
| Hitachi             | 22        | 25     | 11.7%   |
| HGST                | 14        | 14     | 7.45%   |
| Samsung Electronics | 13        | 14     | 6.91%   |
| Toshiba             | 11        | 12     | 5.85%   |
| Maxtor              | 6         | 8      | 3.19%   |
| SK hynix            | 5         | 5      | 2.66%   |
| Kingston            | 5         | 5      | 2.66%   |
| Patriot             | 2         | 2      | 1.06%   |
| OCZ                 | 2         | 2      | 1.06%   |
| Intel               | 2         | 2      | 1.06%   |
| Hewlett-Packard     | 2         | 2      | 1.06%   |
| Fujitsu             | 2         | 2      | 1.06%   |
| Apacer              | 2         | 3      | 1.06%   |
| A-DATA Technology   | 2         | 2      | 1.06%   |
| Teclast             | 1         | 1      | 0.53%   |
| SanDisk             | 1         | 1      | 0.53%   |
| Plextor             | 1         | 1      | 0.53%   |
| Micron Technology   | 1         | 1      | 0.53%   |
| LITEONIT            | 1         | 1      | 0.53%   |
| Crucial             | 1         | 1      | 0.53%   |
| Corsair             | 1         | 4      | 0.53%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 62     | 30.52%  |
| WDC                 | 41        | 64     | 26.62%  |
| Hitachi             | 22        | 25     | 14.29%  |
| HGST                | 14        | 14     | 9.09%   |
| Toshiba             | 11        | 12     | 7.14%   |
| Samsung Electronics | 11        | 12     | 7.14%   |
| Maxtor              | 6         | 8      | 3.9%    |
| Fujitsu             | 2         | 2      | 1.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 143       | 199    | 80.79%  |
| SSD  | 33        | 37     | 18.64%  |
| NVMe | 1         | 1      | 0.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 33.33%  |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 33.33%  |
| Seagate ST3160215A 160GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1047      | 1885   | 58.59%  |
| Works    | 569       | 978    | 31.84%  |
| Malfunc  | 168       | 237    | 9.4%    |
| Failed   | 3         | 3      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1208      | 59.8%   |
| AMD                              | 261       | 12.92%  |
| Samsung Electronics              | 155       | 7.67%   |
| SanDisk                          | 83        | 4.11%   |
| Kingston Technology Company      | 54        | 2.67%   |
| SK hynix                         | 41        | 2.03%   |
| Micron Technology                | 23        | 1.14%   |
| Phison Electronics               | 21        | 1.04%   |
| ASMedia Technology               | 19        | 0.94%   |
| Nvidia                           | 16        | 0.79%   |
| Marvell Technology Group         | 16        | 0.79%   |
| ADATA Technology                 | 16        | 0.79%   |
| JMicron Technology               | 15        | 0.74%   |
| Toshiba America Info Systems     | 14        | 0.69%   |
| KIOXIA                           | 13        | 0.64%   |
| Realtek Semiconductor            | 12        | 0.59%   |
| Silicon Motion                   | 10        | 0.5%    |
| Lite-On Technology               | 6         | 0.3%    |
| Silicon Integrated Systems [SiS] | 5         | 0.25%   |
| Micron/Crucial Technology        | 5         | 0.25%   |
| VIA Technologies                 | 4         | 0.2%    |
| Silicon Image                    | 4         | 0.2%    |
| LSI Logic / Symbios Logic        | 4         | 0.2%    |
| Broadcom / LSI                   | 4         | 0.2%    |
| Union Memory (Shenzhen)          | 2         | 0.1%    |
| Solid State Storage Technology   | 2         | 0.1%    |
| Seagate Technology               | 2         | 0.1%    |
| Lenovo                           | 2         | 0.1%    |
| Integrated Technology Express    | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 191       | 8.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 106       | 4.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 91        | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 72        | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 70        | 3.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 67        | 2.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 58        | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 48        | 2.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 47        | 2.02%   |
| Samsung NVMe SSD Controller 980                                                | 40        | 1.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 39        | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 39        | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 36        | 1.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 36        | 1.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 36        | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 33        | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 31        | 1.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 31        | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 30        | 1.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 29        | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 28        | 1.2%    |
| Kingston Company A2000 NVMe SSD                                                | 27        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 27        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 26        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 26        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 1.03%   |
| Micron NVMe Storage Controller                                                 | 23        | 0.99%   |
| Intel SSD 660P Series                                                          | 23        | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 23        | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 22        | 0.94%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 21        | 0.9%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 21        | 0.9%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 21        | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 20        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 20        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 0.77%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 18        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1216      | 58.46%  |
| NVMe | 473       | 22.74%  |
| IDE  | 224       | 10.77%  |
| RAID | 160       | 7.69%   |
| SAS  | 7         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1294      | 79.14%  |
| AMD    | 333       | 20.37%  |
| ARM    | 8         | 0.49%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 39        | 2.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 26        | 1.59%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 1.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 1.16%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 18        | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 16        | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 0.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 0.79%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 11        | 0.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.67%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 11        | 0.67%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 11        | 0.67%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 0.61%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 10        | 0.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 10        | 0.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 9         | 0.55%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 9         | 0.55%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 0.55%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 9         | 0.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.55%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 8         | 0.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.49%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 8         | 0.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 8         | 0.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.49%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 0.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 0.49%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.49%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 7         | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 7         | 0.43%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 7         | 0.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 314       | 19.19%  |
| Intel Core i5           | 314       | 19.19%  |
| Intel Core i3           | 176       | 10.76%  |
| Intel Celeron           | 140       | 8.56%   |
| Other                   | 85        | 5.2%    |
| AMD Ryzen 5             | 80        | 4.89%   |
| Intel Core 2 Duo        | 79        | 4.83%   |
| AMD Ryzen 7             | 73        | 4.46%   |
| Intel Pentium           | 53        | 3.24%   |
| Intel Atom              | 27        | 1.65%   |
| AMD Ryzen 3             | 24        | 1.47%   |
| Intel Xeon              | 22        | 1.34%   |
| Intel Pentium Dual-Core | 21        | 1.28%   |
| AMD Ryzen 9             | 18        | 1.1%    |
| Intel Core 2 Quad       | 17        | 1.04%   |
| AMD A4                  | 17        | 1.04%   |
| Intel Core 2            | 13        | 0.79%   |
| AMD FX                  | 13        | 0.79%   |
| AMD A8                  | 12        | 0.73%   |
| Intel Core i9           | 11        | 0.67%   |
| Intel Genuine           | 10        | 0.61%   |
| Intel Pentium Dual      | 9         | 0.55%   |
| AMD Phenom II X4        | 7         | 0.43%   |
| AMD Ryzen 7 PRO         | 6         | 0.37%   |
| AMD E                   | 6         | 0.37%   |
| AMD Athlon              | 6         | 0.37%   |
| AMD Ryzen Threadripper  | 5         | 0.31%   |
| AMD E2                  | 5         | 0.31%   |
| Intel Pentium Silver    | 4         | 0.24%   |
| Intel Celeron M         | 4         | 0.24%   |
| ARM BCM                 | 4         | 0.24%   |
| AMD Sempron             | 4         | 0.24%   |
| AMD Athlon II X4        | 4         | 0.24%   |
| AMD Athlon II X3        | 3         | 0.18%   |
| AMD Athlon 64 X2        | 3         | 0.18%   |
| AMD A6                  | 3         | 0.18%   |
| AMD A10                 | 3         | 0.18%   |
| Intel Pentium Gold      | 2         | 0.12%   |
| Intel Pentium D         | 2         | 0.12%   |
| Intel Pentium 4         | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 735       | 44.95%  |
| 4      | 570       | 34.86%  |
| 6      | 125       | 7.65%   |
| 8      | 112       | 6.85%   |
| 1      | 40        | 2.45%   |
| 12     | 19        | 1.16%   |
| 3      | 10        | 0.61%   |
| 10     | 7         | 0.43%   |
| 16     | 6         | 0.37%   |
| 14     | 4         | 0.24%   |
| 32     | 3         | 0.18%   |
| 24     | 2         | 0.12%   |
| 64     | 1         | 0.06%   |
| 20     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1623      | 99.27%  |
| 2      | 12        | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1043      | 63.75%  |
| 1      | 591       | 36.12%  |
| 4      | 2         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1540      | 93.85%  |
| Unknown        | 87        | 5.3%    |
| 32-bit         | 14        | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 320       | 18.98%  |
| 0x206a7    | 86        | 5.1%    |
| 0x306c3    | 83        | 4.92%   |
| 0x306a9    | 79        | 4.69%   |
| 0x1067a    | 61        | 3.62%   |
| 0x906ea    | 56        | 3.32%   |
| 0x806ea    | 56        | 3.32%   |
| 0x806ec    | 54        | 3.2%    |
| 0x706a1    | 48        | 2.85%   |
| 0x906e9    | 43        | 2.55%   |
| 0x40651    | 38        | 2.25%   |
| 0x506c9    | 34        | 2.02%   |
| 0x806e9    | 32        | 1.9%    |
| 0x506e3    | 32        | 1.9%    |
| 0x20655    | 31        | 1.84%   |
| 0x806c1    | 29        | 1.72%   |
| 0x306d4    | 28        | 1.66%   |
| 0x10676    | 25        | 1.48%   |
| 0x806eb    | 24        | 1.42%   |
| 0x406e3    | 23        | 1.36%   |
| 0x0a50000c | 22        | 1.3%    |
| 0x6fd      | 20        | 1.19%   |
| 0x706e5    | 19        | 1.13%   |
| 0x010000c8 | 18        | 1.07%   |
| 0x08108109 | 17        | 1.01%   |
| 0x406c4    | 16        | 0.95%   |
| 0x08108102 | 16        | 0.95%   |
| 0xa0652    | 13        | 0.77%   |
| 0x906ed    | 12        | 0.71%   |
| 0x6fb      | 12        | 0.71%   |
| 0x0810100b | 12        | 0.71%   |
| 0x06001119 | 12        | 0.71%   |
| 0x706a8    | 11        | 0.65%   |
| 0x406c3    | 11        | 0.65%   |
| 0x08701021 | 11        | 0.65%   |
| 0x08600104 | 11        | 0.65%   |
| 0x08701013 | 10        | 0.59%   |
| 0x0800820d | 10        | 0.59%   |
| 0x30678    | 9         | 0.53%   |
| 0x08600106 | 9         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 327       | 19.94%  |
| Haswell          | 148       | 9.02%   |
| SandyBridge      | 100       | 6.1%    |
| Penryn           | 93        | 5.67%   |
| IvyBridge        | 93        | 5.67%   |
| Skylake          | 71        | 4.33%   |
| Goldmont plus    | 67        | 4.09%   |
| Core             | 59        | 3.6%    |
| Zen+             | 58        | 3.54%   |
| Zen 2            | 58        | 3.54%   |
| Westmere         | 50        | 3.05%   |
| Silvermont       | 46        | 2.8%    |
| Zen 3            | 44        | 2.68%   |
| Unknown          | 43        | 2.62%   |
| Broadwell        | 41        | 2.5%    |
| Goldmont         | 39        | 2.38%   |
| Zen              | 38        | 2.32%   |
| TigerLake        | 38        | 2.32%   |
| IceLake          | 30        | 1.83%   |
| CometLake        | 30        | 1.83%   |
| K10              | 28        | 1.71%   |
| Piledriver       | 27        | 1.65%   |
| Excavator        | 17        | 1.04%   |
| Alderlake Hybrid | 14        | 0.85%   |
| P6               | 12        | 0.73%   |
| K8 Hammer        | 12        | 0.73%   |
| Nehalem          | 10        | 0.61%   |
| Bonnell          | 10        | 0.61%   |
| Bobcat           | 8         | 0.49%   |
| Puma             | 6         | 0.37%   |
| NetBurst         | 6         | 0.37%   |
| K8 & K10 hybrid  | 4         | 0.24%   |
| K10 Llano        | 4         | 0.24%   |
| Steamroller      | 3         | 0.18%   |
| Jaguar           | 3         | 0.18%   |
| Tremont          | 2         | 0.12%   |
| Bulldozer        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1045      | 51.89%  |
| Nvidia                           | 547       | 27.16%  |
| AMD                              | 408       | 20.26%  |
| Silicon Integrated Systems [SiS] | 5         | 0.25%   |
| Matrox Electronics Systems       | 4         | 0.2%    |
| ASPEED Technology                | 4         | 0.2%    |
| VIA Technologies                 | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 76        | 3.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 64        | 3.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 61        | 2.95%   |
| Intel UHD Graphics 620                                                                   | 54        | 2.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 51        | 2.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 50        | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 40        | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 40        | 1.93%   |
| Intel HD Graphics 620                                                                    | 39        | 1.89%   |
| Intel HD Graphics 5500                                                                   | 37        | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 37        | 1.79%   |
| Intel HD Graphics 630                                                                    | 36        | 1.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 33        | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 30        | 1.45%   |
| Intel HD Graphics 530                                                                    | 28        | 1.35%   |
| Intel HD Graphics 500                                                                    | 28        | 1.35%   |
| AMD Renoir                                                                               | 28        | 1.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 27        | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 23        | 1.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 23        | 1.11%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 21        | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 21        | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 21        | 1.02%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.73%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 15        | 0.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15        | 0.73%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 14        | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14        | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 14        | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 701       | 42.72%  |
| 1 x AMD        | 292       | 17.79%  |
| Intel + Nvidia | 275       | 16.76%  |
| 1 x Nvidia     | 234       | 14.26%  |
| Intel + AMD    | 58        | 3.53%   |
| AMD + Nvidia   | 37        | 2.25%   |
| 2 x AMD        | 20        | 1.22%   |
| Other          | 8         | 0.49%   |
| 1 x SiS        | 5         | 0.3%    |
| 1 x Matrox     | 4         | 0.24%   |
| 1 x ASPEED     | 3         | 0.18%   |
| 2 x Nvidia     | 2         | 0.12%   |
| 1 x VIA        | 1         | 0.06%   |
| AMD + ASPEED   | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1298      | 78.48%  |
| Proprietary | 311       | 18.8%   |
| Unknown     | 45        | 2.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 929       | 55.04%  |
| 1.01-2.0   | 236       | 13.98%  |
| 0.01-0.5   | 180       | 10.66%  |
| 3.01-4.0   | 124       | 7.35%   |
| 0.51-1.0   | 111       | 6.58%   |
| 7.01-8.0   | 55        | 3.26%   |
| 5.01-6.0   | 35        | 2.07%   |
| 2.01-3.0   | 9         | 0.53%   |
| 8.01-16.0  | 8         | 0.47%   |
| 16.01-24.0 | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 219       | 12.67%  |
| Samsung Electronics     | 210       | 12.15%  |
| Chimei Innolux          | 186       | 10.76%  |
| BOE                     | 180       | 10.42%  |
| LG Display              | 175       | 10.13%  |
| Dell                    | 116       | 6.71%   |
| Goldstar                | 82        | 4.75%   |
| Philips                 | 64        | 3.7%    |
| PANDA                   | 43        | 2.49%   |
| BenQ                    | 42        | 2.43%   |
| Lenovo                  | 35        | 2.03%   |
| Chi Mei Optoelectronics | 34        | 1.97%   |
| Hewlett-Packard         | 30        | 1.74%   |
| Acer                    | 28        | 1.62%   |
| Sharp                   | 27        | 1.56%   |
| AOC                     | 27        | 1.56%   |
| Ancor Communications    | 26        | 1.5%    |
| Fujitsu Siemens         | 18        | 1.04%   |
| ASUSTek Computer        | 15        | 0.87%   |
| LG Philips              | 13        | 0.75%   |
| LG Electronics          | 12        | 0.69%   |
| Unknown                 | 10        | 0.58%   |
| Apple                   | 10        | 0.58%   |
| Sony                    | 7         | 0.41%   |
| KTC                     | 7         | 0.41%   |
| CSO                     | 7         | 0.41%   |
| Vestel Elektronik       | 6         | 0.35%   |
| Lenovo Group Limited    | 6         | 0.35%   |
| InfoVision              | 6         | 0.35%   |
| Eizo                    | 6         | 0.35%   |
| Toshiba                 | 5         | 0.29%   |
| Panasonic               | 5         | 0.29%   |
| ViewSonic               | 4         | 0.23%   |
| LGD                     | 4         | 0.23%   |
| Iiyama                  | 4         | 0.23%   |
| HannStar                | 4         | 0.23%   |
| CPT                     | 4         | 0.23%   |
| InnoLux Display         | 3         | 0.17%   |
| Belinea                 | 3         | 0.17%   |
| Analogix                | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 1.47%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 22        | 1.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 1.19%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 1.13%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.73%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 13        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 10        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.56%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 10        | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.56%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 9         | 0.51%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 9         | 0.51%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 8         | 0.45%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 8         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 8         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.45%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.4%    |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 7         | 0.4%    |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 6         | 0.34%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 6         | 0.34%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 6         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 6         | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.34%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.28%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 5         | 0.28%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 5         | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 753       | 45.31%  |
| 1366x768 (WXGA)    | 367       | 22.08%  |
| 1280x1024 (SXGA)   | 72        | 4.33%   |
| 3840x2160 (4K)     | 68        | 4.09%   |
| 1600x900 (HD+)     | 57        | 3.43%   |
| 2560x1440 (QHD)    | 54        | 3.25%   |
| 1680x1050 (WSXGA+) | 47        | 2.83%   |
| 1280x800 (WXGA)    | 38        | 2.29%   |
| 1920x1200 (WUXGA)  | 30        | 1.81%   |
| 1440x900 (WXGA+)   | 28        | 1.68%   |
| Unknown            | 19        | 1.14%   |
| 1360x768           | 14        | 0.84%   |
| 2560x1080          | 12        | 0.72%   |
| 3200x1800 (QHD+)   | 11        | 0.66%   |
| 2880x1800          | 11        | 0.66%   |
| 3440x1440          | 9         | 0.54%   |
| 2560x1600          | 8         | 0.48%   |
| 3840x1080          | 7         | 0.42%   |
| 1024x768 (XGA)     | 7         | 0.42%   |
| 1024x600           | 7         | 0.42%   |
| 2160x1440          | 6         | 0.36%   |
| 800x1280           | 5         | 0.3%    |
| 5120x1440          | 2         | 0.12%   |
| 3840x2400          | 2         | 0.12%   |
| 1920x540           | 2         | 0.12%   |
| 1600x1200          | 2         | 0.12%   |
| 1400x1050          | 2         | 0.12%   |
| 1280x720 (HD)      | 2         | 0.12%   |
| 800x600            | 1         | 0.06%   |
| 7680x1440          | 1         | 0.06%   |
| 6400x1440          | 1         | 0.06%   |
| 6000x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 4960x1080          | 1         | 0.06%   |
| 3926x1440          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3600x1200          | 1         | 0.06%   |
| 3360x1080          | 1         | 0.06%   |
| 3286x1080          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 657       | 38.44%  |
| 14      | 124       | 7.26%   |
| 13      | 111       | 6.5%    |
| 24      | 104       | 6.09%   |
| 17      | 103       | 6.03%   |
| 23      | 97        | 5.68%   |
| 21      | 91        | 5.32%   |
| 27      | 77        | 4.51%   |
| Unknown | 76        | 4.45%   |
| 19      | 49        | 2.87%   |
| 22      | 32        | 1.87%   |
| 18      | 27        | 1.58%   |
| 31      | 21        | 1.23%   |
| 34      | 19        | 1.11%   |
| 12      | 18        | 1.05%   |
| 84      | 15        | 0.88%   |
| 20      | 11        | 0.64%   |
| 16      | 9         | 0.53%   |
| 54      | 8         | 0.47%   |
| 10      | 8         | 0.47%   |
| 11      | 7         | 0.41%   |
| 72      | 6         | 0.35%   |
| 32      | 6         | 0.35%   |
| 65      | 4         | 0.23%   |
| 40      | 4         | 0.23%   |
| 28      | 3         | 0.18%   |
| 26      | 3         | 0.18%   |
| 25      | 3         | 0.18%   |
| 52      | 2         | 0.12%   |
| 29      | 2         | 0.12%   |
| 8       | 2         | 0.12%   |
| 7       | 2         | 0.12%   |
| 142     | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 860       | 50.83%  |
| 501-600        | 263       | 15.54%  |
| 401-500        | 171       | 10.11%  |
| 351-400        | 132       | 7.8%    |
| 201-300        | 82        | 4.85%   |
| Unknown        | 76        | 4.49%   |
| 601-700        | 32        | 1.89%   |
| 701-800        | 25        | 1.48%   |
| 1501-2000      | 21        | 1.24%   |
| 1001-1500      | 18        | 1.06%   |
| 801-900        | 5         | 0.3%    |
| 101-200        | 2         | 0.12%   |
| 901-1000       | 2         | 0.12%   |
| 1-100          | 2         | 0.12%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1246      | 78.22%  |
| 16/10   | 160       | 10.04%  |
| Unknown | 64        | 4.02%   |
| 5/4     | 63        | 3.95%   |
| 21/9    | 22        | 1.38%   |
| 4/3     | 14        | 0.88%   |
| 3/2     | 12        | 0.75%   |
| 6/5     | 5         | 0.31%   |
| 0.62    | 3         | 0.19%   |
| 0.67    | 2         | 0.13%   |
| 32/9    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 658       | 38.71%  |
| 201-250        | 265       | 15.59%  |
| 81-90          | 196       | 11.53%  |
| 151-200        | 89        | 5.24%   |
| 301-350        | 80        | 4.71%   |
| Unknown        | 76        | 4.47%   |
| 121-130        | 68        | 4%      |
| 351-500        | 48        | 2.82%   |
| 141-150        | 46        | 2.71%   |
| More than 1000 | 37        | 2.18%   |
| 71-80          | 37        | 2.18%   |
| 251-300        | 35        | 2.06%   |
| 61-70          | 16        | 0.94%   |
| 131-140        | 10        | 0.59%   |
| 501-1000       | 10        | 0.59%   |
| 41-50          | 8         | 0.47%   |
| 51-60          | 7         | 0.41%   |
| 111-120        | 6         | 0.35%   |
| 1-40           | 4         | 0.24%   |
| 91-100         | 4         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 498       | 29.7%   |
| 101-120       | 497       | 29.64%  |
| 51-100        | 481       | 28.68%  |
| Unknown       | 76        | 4.53%   |
| 161-240       | 67        | 4%      |
| More than 240 | 31        | 1.85%   |
| 1-50          | 27        | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1409      | 84.57%  |
| 2     | 179       | 10.74%  |
| 0     | 54        | 3.24%   |
| 3     | 23        | 1.38%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 936       | 39.11%  |
| Intel                             | 711       | 29.71%  |
| Qualcomm Atheros                  | 287       | 11.99%  |
| Broadcom                          | 131       | 5.47%   |
| TP-Link                           | 52        | 2.17%   |
| MediaTek                          | 43        | 1.8%    |
| Broadcom Limited                  | 24        | 1%      |
| Ralink                            | 23        | 0.96%   |
| Ralink Technology                 | 22        | 0.92%   |
| Marvell Technology Group          | 22        | 0.92%   |
| Nvidia                            | 14        | 0.59%   |
| ASUSTek Computer                  | 12        | 0.5%    |
| Huawei Technologies               | 9         | 0.38%   |
| Samsung Electronics               | 8         | 0.33%   |
| D-Link                            | 8         | 0.33%   |
| Ericsson Business Mobile Networks | 7         | 0.29%   |
| Xiaomi                            | 6         | 0.25%   |
| Qualcomm Atheros Communications   | 6         | 0.25%   |
| ASIX Electronics                  | 6         | 0.25%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.21%   |
| Microsoft                         | 5         | 0.21%   |
| Hewlett-Packard                   | 5         | 0.21%   |
| Aquantia                          | 5         | 0.21%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.17%   |
| JMicron Technology                | 4         | 0.17%   |
| VIA Technologies                  | 3         | 0.13%   |
| Standard Microsystems             | 2         | 0.08%   |
| Lenovo                            | 2         | 0.08%   |
| IMC Networks                      | 2         | 0.08%   |
| Giga-Byte Technology              | 2         | 0.08%   |
| FIBOCOM                           | 2         | 0.08%   |
| Edimax Technology                 | 2         | 0.08%   |
| Dell                              | 2         | 0.08%   |
| D-Link System                     | 2         | 0.08%   |
| Belkin Components                 | 2         | 0.08%   |
| U-Blox                            | 1         | 0.04%   |
| Texas Instruments                 | 1         | 0.04%   |
| Sierra Wireless                   | 1         | 0.04%   |
| Qualcomm                          | 1         | 0.04%   |
| QLogic                            | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 614       | 21.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 120       | 4.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 76        | 2.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 60        | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 2.07%   |
| Intel Wireless 8265 / 8275                                        | 57        | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 53        | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 49        | 1.75%   |
| Intel Wi-Fi 6 AX200                                               | 48        | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 43        | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 38        | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 37        | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 35        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 33        | 1.18%   |
| Intel Wi-Fi 6 AX201                                               | 31        | 1.11%   |
| Intel I211 Gigabit Network Connection                             | 29        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 27        | 0.96%   |
| Intel Wireless 7265                                               | 26        | 0.93%   |
| Intel Wireless 7260                                               | 26        | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 24        | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 24        | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23        | 0.82%   |
| Intel Wireless 8260                                               | 22        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 22        | 0.79%   |
| Intel Wireless 3165                                               | 20        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 20        | 0.71%   |
| Intel Wireless 3160                                               | 19        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 19        | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 0.57%   |
| Intel Centrino Advanced-N 6200                                    | 16        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 15        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 15        | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 14        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 540       | 40.88%  |
| Realtek Semiconductor           | 279       | 21.12%  |
| Qualcomm Atheros                | 233       | 17.64%  |
| Broadcom                        | 84        | 6.36%   |
| TP-Link                         | 44        | 3.33%   |
| MediaTek                        | 37        | 2.8%    |
| Ralink                          | 23        | 1.74%   |
| Ralink Technology               | 22        | 1.67%   |
| Broadcom Limited                | 12        | 0.91%   |
| ASUSTek Computer                | 12        | 0.91%   |
| D-Link                          | 8         | 0.61%   |
| Qualcomm Atheros Communications | 6         | 0.45%   |
| Microsoft                       | 5         | 0.38%   |
| IMC Networks                    | 2         | 0.15%   |
| FIBOCOM                         | 2         | 0.15%   |
| Edimax Technology               | 2         | 0.15%   |
| Belkin Components               | 2         | 0.15%   |
| Sierra Wireless                 | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| Qcom                            | 1         | 0.08%   |
| NetGear                         | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Mercucys                        | 1         | 0.08%   |
| D-Link System                   | 1         | 0.08%   |
| Belkin                          | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 76        | 5.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 60        | 4.52%   |
| Intel Wireless 8265 / 8275                                              | 57        | 4.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 53        | 3.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 49        | 3.69%   |
| Intel Wi-Fi 6 AX200                                                     | 48        | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 3.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 38        | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 37        | 2.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 2.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 33        | 2.48%   |
| Intel Wi-Fi 6 AX201                                                     | 31        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 27        | 2.03%   |
| Intel Wireless 7265                                                     | 26        | 1.96%   |
| Intel Wireless 7260                                                     | 26        | 1.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 24        | 1.81%   |
| Intel Wireless 8260                                                     | 22        | 1.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 22        | 1.66%   |
| Intel Wireless 3165                                                     | 20        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 1.51%   |
| Intel Wireless 3160                                                     | 19        | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.2%    |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.2%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 15        | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 1.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.75%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 0.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 9         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.68%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.6%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 7         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 796       | 56.21%  |
| Intel                            | 349       | 24.65%  |
| Qualcomm Atheros                 | 86        | 6.07%   |
| Broadcom                         | 68        | 4.8%    |
| Marvell Technology Group         | 22        | 1.55%   |
| Nvidia                           | 14        | 0.99%   |
| Broadcom Limited                 | 12        | 0.85%   |
| TP-Link                          | 8         | 0.56%   |
| Huawei Technologies              | 7         | 0.49%   |
| Xiaomi                           | 6         | 0.42%   |
| Samsung Electronics              | 6         | 0.42%   |
| MediaTek                         | 6         | 0.42%   |
| ASIX Electronics                 | 6         | 0.42%   |
| Aquantia                         | 5         | 0.35%   |
| Silicon Integrated Systems [SiS] | 4         | 0.28%   |
| JMicron Technology               | 4         | 0.28%   |
| VIA Technologies                 | 3         | 0.21%   |
| Standard Microsystems            | 2         | 0.14%   |
| Lenovo                           | 2         | 0.14%   |
| Giga-Byte Technology             | 2         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.07%   |
| QLogic                           | 1         | 0.07%   |
| HMD Global                       | 1         | 0.07%   |
| Google                           | 1         | 0.07%   |
| DisplayLink                      | 1         | 0.07%   |
| Dell                             | 1         | 0.07%   |
| D-Link System                    | 1         | 0.07%   |
| 3Com                             | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 614       | 42.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 120       | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 4.02%   |
| Intel I211 Gigabit Network Connection                             | 29        | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 1.87%   |
| Intel Ethernet Connection I217-LM                                 | 24        | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23        | 1.6%    |
| Intel Ethernet Connection (2) I219-V                              | 19        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 1.18%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 9         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 8         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8         | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 8         | 0.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.49%   |
| Nvidia MCP61 Ethernet                                             | 7         | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 6         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.42%   |
| MediaTek PRESIDENT_GOLD_10                                        | 6         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1347      | 51.08%  |
| WiFi     | 1260      | 47.78%  |
| Modem    | 25        | 0.95%   |
| Unknown  | 5         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1010      | 59.41%  |
| Ethernet | 689       | 40.53%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 887       | 54.18%  |
| 1     | 682       | 41.66%  |
| 0     | 33        | 2.02%   |
| 3     | 29        | 1.77%   |
| 4     | 4         | 0.24%   |
| 8     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1415      | 84.68%  |
| Yes  | 256       | 15.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 425       | 41.67%  |
| IMC Networks                    | 140       | 13.73%  |
| Realtek Semiconductor           | 121       | 11.86%  |
| Qualcomm Atheros Communications | 71        | 6.96%   |
| Lite-On Technology              | 52        | 5.1%    |
| Broadcom                        | 40        | 3.92%   |
| Cambridge Silicon Radio         | 31        | 3.04%   |
| ASUSTek Computer                | 26        | 2.55%   |
| Foxconn / Hon Hai               | 23        | 2.25%   |
| Dell                            | 18        | 1.76%   |
| Hewlett-Packard                 | 14        | 1.37%   |
| Toshiba                         | 12        | 1.18%   |
| Apple                           | 10        | 0.98%   |
| Ralink                          | 9         | 0.88%   |
| MediaTek                        | 5         | 0.49%   |
| Realtek                         | 3         | 0.29%   |
| Alps Electric                   | 3         | 0.29%   |
| SINO WEALTH                     | 2         | 0.2%    |
| Integrated System Solution      | 2         | 0.2%    |
| Chicony Electronics             | 2         | 0.2%    |
| USI                             | 1         | 0.1%    |
| TP-Link                         | 1         | 0.1%    |
| Ralink Technology               | 1         | 0.1%    |
| Opticis                         | 1         | 0.1%    |
| Micro Star International        | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Conwise Technology              | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |
| Askey Computer                  | 1         | 0.1%    |
| Accel Semiconductor             | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 176       | 17.25%  |
| IMC Networks Bluetooth Radio                        | 87        | 8.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 85        | 8.33%   |
| Realtek Bluetooth Radio                             | 82        | 8.04%   |
| Intel AX201 Bluetooth                               | 76        | 7.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 48        | 4.71%   |
| Intel AX200 Bluetooth                               | 47        | 4.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31        | 3.04%   |
| IMC Networks Bluetooth Device                       | 29        | 2.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 24        | 2.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.76%   |
| IMC Networks Wireless_Device                        | 18        | 1.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 18        | 1.76%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 12        | 1.18%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 1.08%   |
| Lite-On Bluetooth Device                            | 10        | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 0.98%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.88%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.69%   |
| Broadcom BCM2045A0                                  | 7         | 0.69%   |
| Toshiba Bluetooth Device                            | 6         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.59%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.49%   |
| MediaTek Wireless_Device                            | 5         | 0.49%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.49%   |
| Intel AX210 Bluetooth                               | 5         | 0.49%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.49%   |
| ASUS ASUS USB-BT500                                 | 5         | 0.49%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.39%   |
| Apple Bluetooth Host Controller                     | 4         | 0.39%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 0.29%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1248      | 57.88%  |
| AMD                                          | 381       | 17.67%  |
| Nvidia                                       | 347       | 16.09%  |
| C-Media Electronics                          | 33        | 1.53%   |
| Creative Labs                                | 21        | 0.97%   |
| Logitech                                     | 12        | 0.56%   |
| GN Netcom                                    | 9         | 0.42%   |
| Creative Technology                          | 9         | 0.42%   |
| Trust                                        | 6         | 0.28%   |
| ASUSTek Computer                             | 6         | 0.28%   |
| Texas Instruments                            | 5         | 0.23%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.23%   |
| Kingston Technology                          | 5         | 0.23%   |
| Giga-Byte Technology                         | 5         | 0.23%   |
| Realtek Semiconductor                        | 4         | 0.19%   |
| Plantronics                                  | 4         | 0.19%   |
| VIA Technologies                             | 3         | 0.14%   |
| Tenx Technology                              | 3         | 0.14%   |
| Razer USA                                    | 3         | 0.14%   |
| Generalplus Technology                       | 3         | 0.14%   |
| DSEA A/S                                     | 3         | 0.14%   |
| Dell                                         | 3         | 0.14%   |
| XMOS                                         | 2         | 0.09%   |
| Sennheiser Communications                    | 2         | 0.09%   |
| Lenovo                                       | 2         | 0.09%   |
| JMTek                                        | 2         | 0.09%   |
| GYROCOM C&C                                  | 2         | 0.09%   |
| Focusrite-Novation                           | 2         | 0.09%   |
| Corsair                                      | 2         | 0.09%   |
| Audio-Technica                               | 2         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.05%   |
| Unknown                                      | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| TEAC                                         | 1         | 0.05%   |
| Studiologic                                  | 1         | 0.05%   |
| Sony                                         | 1         | 0.05%   |
| Samson Technologies                          | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.05%   |
| Nam Tai E&E Products                         | 1         | 0.05%   |
| iCreate Technologies                         | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 140       | 5.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 129       | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 97        | 3.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 88        | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 85        | 3.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 74        | 2.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 68        | 2.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 67        | 2.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 66        | 2.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 59        | 2.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 55        | 2.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 54        | 2.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 54        | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 52        | 2.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 50        | 1.95%   |
| Intel 8 Series HD Audio Controller                                                                | 49        | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 48        | 1.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 45        | 1.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 40        | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 39        | 1.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 1.52%   |
| Intel Broadwell-U Audio Controller                                                                | 39        | 1.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 38        | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 38        | 1.48%   |
| AMD FCH Azalia Controller                                                                         | 34        | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 33        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 33        | 1.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 32        | 1.25%   |
| Intel 200 Series PCH HD Audio                                                                     | 31        | 1.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 31        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 30        | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 24        | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 24        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 21        | 0.82%   |
| Intel CM238 HD Audio Controller                                                                   | 21        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 20        | 0.78%   |
| Nvidia High Definition Audio Controller                                                           | 20        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 20        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 19        | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 18        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 208       | 22.76%  |
| SK hynix                     | 159       | 17.4%   |
| Kingston                     | 137       | 14.99%  |
| Micron Technology            | 86        | 9.41%   |
| Unknown                      | 77        | 8.42%   |
| Corsair                      | 66        | 7.22%   |
| Ramaxel Technology           | 26        | 2.84%   |
| Crucial                      | 26        | 2.84%   |
| A-DATA Technology            | 24        | 2.63%   |
| Nanya Technology             | 20        | 2.19%   |
| Elpida                       | 19        | 2.08%   |
| G.Skill                      | 14        | 1.53%   |
| Unknown (ABCD)               | 9         | 0.98%   |
| Kingmax                      | 8         | 0.88%   |
| Unknown                      | 5         | 0.55%   |
| Patriot                      | 4         | 0.44%   |
| Apacer                       | 4         | 0.44%   |
| Transcend                    | 2         | 0.22%   |
| Silicon Power                | 2         | 0.22%   |
| Qimonda                      | 2         | 0.22%   |
| GOODRAM                      | 2         | 0.22%   |
| Unknown (0x7FDA000000000000) | 1         | 0.11%   |
| Unknown (0B45)               | 1         | 0.11%   |
| Team                         | 1         | 0.11%   |
| TakeMS                       | 1         | 0.11%   |
| Super Talent                 | 1         | 0.11%   |
| SK_Hynix                     | 1         | 0.11%   |
| SHARETRONIC                  | 1         | 0.11%   |
| S                            | 1         | 0.11%   |
| Kingmax Semiconductor        | 1         | 0.11%   |
| Infineon                     | 1         | 0.11%   |
| H                            | 1         | 0.11%   |
| Exceleram                    | 1         | 0.11%   |
| Avant                        | 1         | 0.11%   |
| ASint Technology             | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.19%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.09%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.99%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.89%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.79%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 8         | 0.79%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 7         | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.69%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 6         | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.6%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 5         | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.5%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.5%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.5%    |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                | 5         | 0.5%    |
| Unknown                                                          | 5         | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 4         | 0.4%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.4%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 4         | 0.4%    |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 4         | 0.4%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 4         | 0.4%    |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s              | 4         | 0.4%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.4%    |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 4         | 0.4%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 0.4%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 3         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 366       | 46.98%  |
| DDR3    | 265       | 34.02%  |
| DDR2    | 50        | 6.42%   |
| SDRAM   | 29        | 3.72%   |
| Unknown | 21        | 2.7%    |
| LPDDR4  | 19        | 2.44%   |
| LPDDR3  | 13        | 1.67%   |
| DDR5    | 7         | 0.9%    |
| DDR     | 4         | 0.51%   |
| LPDDR5  | 3         | 0.39%   |
| DRAM    | 2         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 470       | 61.28%  |
| DIMM         | 257       | 33.51%  |
| Row Of Chips | 34        | 4.43%   |
| Chip         | 4         | 0.52%   |
| RIMM         | 1         | 0.13%   |
| FB-DIMM      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 309       | 36.7%   |
| 4096  | 256       | 30.4%   |
| 2048  | 107       | 12.71%  |
| 16384 | 101       | 12%     |
| 1024  | 48        | 5.7%    |
| 32768 | 16        | 1.9%    |
| 512   | 5         | 0.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 172       | 19.77%  |
| 2667    | 132       | 15.17%  |
| 3200    | 114       | 13.1%   |
| 2400    | 85        | 9.77%   |
| 1333    | 57        | 6.55%   |
| 1334    | 38        | 4.37%   |
| 2133    | 35        | 4.02%   |
| 800     | 28        | 3.22%   |
| 667     | 26        | 2.99%   |
| 3600    | 21        | 2.41%   |
| Unknown | 18        | 2.07%   |
| 3266    | 14        | 1.61%   |
| 1067    | 9         | 1.03%   |
| 3400    | 8         | 0.92%   |
| 1867    | 8         | 0.92%   |
| 975     | 8         | 0.92%   |
| 4267    | 7         | 0.8%    |
| 3000    | 7         | 0.8%    |
| 1866    | 6         | 0.69%   |
| 4800    | 5         | 0.57%   |
| 2933    | 5         | 0.57%   |
| 1066    | 5         | 0.57%   |
| 533     | 5         | 0.57%   |
| 4199    | 4         | 0.46%   |
| 2800    | 4         | 0.46%   |
| 2048    | 4         | 0.46%   |
| 6400    | 3         | 0.34%   |
| 4266    | 3         | 0.34%   |
| 3866    | 3         | 0.34%   |
| 3733    | 3         | 0.34%   |
| 3500    | 3         | 0.34%   |
| 3466    | 3         | 0.34%   |
| 2666    | 3         | 0.34%   |
| 400     | 3         | 0.34%   |
| 1800    | 2         | 0.23%   |
| 1648    | 2         | 0.23%   |
| 1639    | 2         | 0.23%   |
| 49926   | 1         | 0.11%   |
| 8192    | 1         | 0.11%   |
| 5808    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 23.53%  |
| Canon                 | 9         | 17.65%  |
| Samsung Electronics   | 8         | 15.69%  |
| Brother Industries    | 8         | 15.69%  |
| Seiko Epson           | 7         | 13.73%  |
| Xerox                 | 2         | 3.92%   |
| Lexmark International | 2         | 3.92%   |
| Zebra                 | 1         | 1.96%   |
| QinHeng Electronics   | 1         | 1.96%   |
| ATEN International    | 1         | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                      | 2         | 3.92%   |
| Seiko Epson L3110 Series                      | 2         | 3.92%   |
| Samsung M2070 Series                          | 2         | 3.92%   |
| Samsung Composite Device                      | 2         | 3.92%   |
| Lexmark International InkJet Color Printer    | 2         | 3.92%   |
| Canon MF4010 series                           | 2         | 3.92%   |
| Brother HL-1110 series                        | 2         | 3.92%   |
| Zebra GK420t Label Printer                    | 1         | 1.96%   |
| Xerox Phaser 6130N                            | 1         | 1.96%   |
| Xerox Phaser 3020                             | 1         | 1.96%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.96%   |
| Seiko Epson L6160 Series                      | 1         | 1.96%   |
| Seiko Epson L396 Series                       | 1         | 1.96%   |
| Samsung ML-216x Series Laser Printer          | 1         | 1.96%   |
| Samsung M267x 287x Series                     | 1         | 1.96%   |
| Samsung M2020 Series                          | 1         | 1.96%   |
| Samsung CLP-310 Color Laser Printer           | 1         | 1.96%   |
| QinHeng CH340S                                | 1         | 1.96%   |
| HP LaserJet M14-M17                           | 1         | 1.96%   |
| HP LaserJet 3050                              | 1         | 1.96%   |
| HP LaserJet 1022                              | 1         | 1.96%   |
| HP LaserJet 1018                              | 1         | 1.96%   |
| HP Laser 107w                                 | 1         | 1.96%   |
| HP Deskjet F4500 series                       | 1         | 1.96%   |
| HP DeskJet F2492 All-in-One                   | 1         | 1.96%   |
| HP Deskjet 3050A                              | 1         | 1.96%   |
| HP DeskJet 2700 series                        | 1         | 1.96%   |
| HP DeskJet 2300 series                        | 1         | 1.96%   |
| HP DeskJet 2130 series                        | 1         | 1.96%   |
| HP Deskjet 2050 J510                          | 1         | 1.96%   |
| Canon PIXMA MP280                             | 1         | 1.96%   |
| Canon PIXMA MP250                             | 1         | 1.96%   |
| Canon MF4320-4350                             | 1         | 1.96%   |
| Canon MF3200 series                           | 1         | 1.96%   |
| Canon MF3110                                  | 1         | 1.96%   |
| Canon LiDE 300                                | 1         | 1.96%   |
| Canon iP7200 series                           | 1         | 1.96%   |
| Brother MFC-7420                              | 1         | 1.96%   |
| Brother HL-5380DN series                      | 1         | 1.96%   |
| Brother HL-5250DN Printer                     | 1         | 1.96%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 239       | 22.42%  |
| Chicony Electronics                    | 212       | 19.89%  |
| Realtek Semiconductor                  | 94        | 8.82%   |
| Microdia                               | 78        | 7.32%   |
| Sunplus Innovation Technology          | 58        | 5.44%   |
| Quanta                                 | 47        | 4.41%   |
| Acer                                   | 40        | 3.75%   |
| Bison Electronics                      | 34        | 3.19%   |
| Syntek                                 | 28        | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 2.53%   |
| Alcor Micro                            | 24        | 2.25%   |
| Lite-On Technology                     | 23        | 2.16%   |
| Logitech                               | 20        | 1.88%   |
| Suyin                                  | 19        | 1.78%   |
| Sonix Technology                       | 14        | 1.31%   |
| Apple                                  | 12        | 1.13%   |
| Samsung Electronics                    | 11        | 1.03%   |
| Ricoh                                  | 9         | 0.84%   |
| Microsoft                              | 9         | 0.84%   |
| Luxvisions Innotech Limited            | 8         | 0.75%   |
| Silicon Motion                         | 7         | 0.66%   |
| Z-Star Microelectronics                | 6         | 0.56%   |
| OmniVision Technologies                | 5         | 0.47%   |
| ALi                                    | 4         | 0.38%   |
| Lenovo                                 | 3         | 0.28%   |
| GEMBIRD                                | 3         | 0.28%   |
| Cubeternet                             | 3         | 0.28%   |
| Sunplus Technology                     | 2         | 0.19%   |
| Primax Electronics                     | 2         | 0.19%   |
| Jieli Technology                       | 2         | 0.19%   |
| Importek                               | 2         | 0.19%   |
| Genesys Logic                          | 2         | 0.19%   |
| Aveo Technology                        | 2         | 0.19%   |
| WaveRider Communications               | 1         | 0.09%   |
| Unknown                                | 1         | 0.09%   |
| Trust                                  | 1         | 0.09%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.09%   |
| Philips (or NXP)                       | 1         | 0.09%   |
| Novatek Microelectronics               | 1         | 0.09%   |
| Nikon                                  | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam            | 104       | 9.74%   |
| IMC Networks USB2.0 HD UVC WebCam             | 76        | 7.12%   |
| Chicony Integrated Camera                     | 46        | 4.31%   |
| Realtek Integrated_Webcam_HD                  | 30        | 2.81%   |
| IMC Networks Integrated Camera                | 24        | 2.25%   |
| Microdia Integrated_Webcam_HD                 | 21        | 1.97%   |
| Chicony USB2.0 VGA UVC WebCam                 | 17        | 1.59%   |
| Syntek Integrated Camera                      | 16        | 1.5%    |
| Chicony HD WebCam                             | 16        | 1.5%    |
| Acer Integrated Camera                        | 16        | 1.5%    |
| Chicony USB2.0 HD UVC WebCam                  | 13        | 1.22%   |
| Sunplus HD WebCam                             | 12        | 1.12%   |
| Realtek USB Camera                            | 12        | 1.12%   |
| Samsung Galaxy series, misc. (MTP mode)       | 11        | 1.03%   |
| Chicony TOSHIBA Web Camera - HD               | 11        | 1.03%   |
| Sonix USB2.0 HD UVC WebCam                    | 10        | 0.94%   |
| Quanta VGA WebCam                             | 10        | 0.94%   |
| Chicony HP Webcam                             | 9         | 0.84%   |
| Chicony EasyCamera                            | 9         | 0.84%   |
| Bison SunplusIT Integrated Camera             | 9         | 0.84%   |
| Microdia Integrated Webcam                    | 8         | 0.75%   |
| Lite-On Integrated Camera                     | 8         | 0.75%   |
| Alcor Micro USB 2.0 PC Camera                 | 8         | 0.75%   |
| Sunplus Integrated_Webcam_HD                  | 7         | 0.66%   |
| Realtek USB2.0 VGA UVC WebCam                 | 7         | 0.66%   |
| Realtek USB2.0 HD UVC WebCam                  | 7         | 0.66%   |
| Microsoft LifeCam HD-3000                     | 7         | 0.66%   |
| Microdia Camera                               | 7         | 0.66%   |
| IMC Networks USB2.0 UVC HD Webcam             | 7         | 0.66%   |
| Chicony VGA WebCam                            | 7         | 0.66%   |
| Bison Lenovo EasyCamera                       | 7         | 0.66%   |
| Alcor Micro SHUNCCM2MP                        | 7         | 0.66%   |
| Syntek EasyCamera                             | 6         | 0.56%   |
| Sunplus ASUS Webcam                           | 6         | 0.56%   |
| Realtek Lenovo EasyCamera                     | 6         | 0.56%   |
| Realtek Integrated Webcam                     | 6         | 0.56%   |
| Quanta HD WebCam                              | 6         | 0.56%   |
| Chicony HP HD Webcam                          | 6         | 0.56%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 6         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 6         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 56        | 35.9%   |
| Synaptics                  | 39        | 25%     |
| Shenzhen Goodix Technology | 19        | 12.18%  |
| Elan Microelectronics      | 12        | 7.69%   |
| Upek                       | 11        | 7.05%   |
| AuthenTec                  | 8         | 5.13%   |
| LighTuning Technology      | 6         | 3.85%   |
| Focal-systems.Corp         | 2         | 1.28%   |
| STMicroelectronics         | 1         | 0.64%   |
| Samsung Electronics        | 1         | 0.64%   |
| GDMicroelectronics         | 1         | 0.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 12        | 7.69%   |
| Synaptics  WBDI                                                            | 11        | 7.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 6.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 5.77%   |
| Elan ELAN:Fingerprint                                                      | 9         | 5.77%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 5.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.85%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 3.85%   |
| AuthenTec AES2810                                                          | 6         | 3.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 3.21%   |
| Validity Sensors VFS491                                                    | 4         | 2.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.92%   |
| Synaptics WBDI                                                             | 3         | 1.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.92%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.92%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.92%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.28%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.28%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.28%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.28%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.28%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.28%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 1.28%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.64%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.64%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.64%   |
| Synaptics UWP WBDI                                                         | 1         | 0.64%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.64%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.64%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.64%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.64%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.64%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.64%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 39        | 54.93%  |
| Alcor Micro               | 16        | 22.54%  |
| Lenovo                    | 5         | 7.04%   |
| Upek                      | 4         | 5.63%   |
| O2 Micro                  | 3         | 4.23%   |
| Gemalto (was Gemplus)     | 1         | 1.41%   |
| Fujitsu Siemens Computers | 1         | 1.41%   |
| Chicony Electronics       | 1         | 1.41%   |
| Aladdin Knowledge Systems | 1         | 1.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 22.54%  |
| Broadcom 58200                                                               | 12        | 16.9%   |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 14.08%  |
| Broadcom 5880                                                                | 9         | 12.68%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 11.27%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 7.04%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.63%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 4.23%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.41%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.41%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.41%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1209      | 72.74%  |
| 1     | 371       | 22.32%  |
| 2     | 73        | 4.39%   |
| 3     | 7         | 0.42%   |
| 10    | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 155       | 28.97%  |
| Graphics card            | 117       | 21.87%  |
| Net/wireless             | 65        | 12.15%  |
| Chipcard                 | 65        | 12.15%  |
| Multimedia controller    | 32        | 5.98%   |
| Communication controller | 21        | 3.93%   |
| Camera                   | 18        | 3.36%   |
| Bluetooth                | 16        | 2.99%   |
| Storage                  | 14        | 2.62%   |
| Sound                    | 7         | 1.31%   |
| Card reader              | 5         | 0.93%   |
| Unassigned class         | 4         | 0.75%   |
| Network                  | 3         | 0.56%   |
| Net/ethernet             | 3         | 0.56%   |
| Storage/ide              | 2         | 0.37%   |
| Flash memory             | 2         | 0.37%   |
| Unclassified device      | 1         | 0.19%   |
| Storage/raid             | 1         | 0.19%   |
| Storage/nvme             | 1         | 0.19%   |
| Modem                    | 1         | 0.19%   |
| Firewire controller      | 1         | 0.19%   |
| Dvb card                 | 1         | 0.19%   |

