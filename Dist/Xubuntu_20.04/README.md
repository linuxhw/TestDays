Xubuntu 20.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_20.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_20.04/Notebook/README.md).

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

Total: 2552

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad L13 20R4S4WG00     | Notebook    | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | Notebook    | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| Medion        | E15407                      | Notebook    | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | Notebook    | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| HP            | 2B29                        | Desktop     | [d2ab16d631](https://linux-hardware.org/?probe=d2ab16d631) | May 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [64aa376623](https://linux-hardware.org/?probe=64aa376623) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d6adaef7cc](https://linux-hardware.org/?probe=d6adaef7cc) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c848e4649e](https://linux-hardware.org/?probe=c848e4649e) | May 28, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [a1315854db](https://linux-hardware.org/?probe=a1315854db) | May 23, 2022 |
| ASUSTek       | X510UA                      | Notebook    | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | Notebook    | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | Notebook    | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Acer          | Aspire G7750                | Desktop     | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| HP            | 158A                        | Desktop     | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| ECS           | Asterope                    | Desktop     | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [cace04f39a](https://linux-hardware.org/?probe=cace04f39a) | May 12, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | Notebook    | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [573e425cb6](https://linux-hardware.org/?probe=573e425cb6) | May 08, 2022 |
| HP            | Compaq 6820s                | Notebook    | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| HP            | 3397                        | Desktop     | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| HP            | 158A                        | Desktop     | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Unknown       | Intel X79                   | Desktop     | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Dell          | Inspiron 3135               | Notebook    | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [36bbd53ec1](https://linux-hardware.org/?probe=36bbd53ec1) | Apr 23, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5a662b428e](https://linux-hardware.org/?probe=5a662b428e) | Apr 21, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [481e87aa23](https://linux-hardware.org/?probe=481e87aa23) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| HP            | 18E5                        | Desktop     | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [521cf503e2](https://linux-hardware.org/?probe=521cf503e2) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| HP            | Compaq 6730s                | Notebook    | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | Notebook    | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | Notebook    | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | Notebook    | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [0123ade8f7](https://linux-hardware.org/?probe=0123ade8f7) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [6280e20fbe](https://linux-hardware.org/?probe=6280e20fbe) | Apr 11, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Toshiba       | NB505                       | Notebook    | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Dell          | Latitude 5521               | Notebook    | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [c081f43e18](https://linux-hardware.org/?probe=c081f43e18) | Apr 05, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| MSI           | GX70 3CC                    | Notebook    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | 18E5                        | Desktop     | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| Dell          | 0WM839 A00                  | All in one  | [b5edf6760d](https://linux-hardware.org/?probe=b5edf6760d) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| Medion        | Crawler E25                 | Notebook    | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| HP            | 21B4 A01                    | Desktop     | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Lenovo        | 36FD SDK0J40709 WIN 3259... | All in one  | [75410d5871](https://linux-hardware.org/?probe=75410d5871) | Mar 27, 2022 |
| Toshiba       | NB505                       | Notebook    | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| Pegatron      | Benicia                     | Desktop     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | Notebook    | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| ASUSTek       | X501A                       | Notebook    | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | Notebook    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| ECS           | H87H3-M                     | Desktop     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | Notebook    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| Dell          | Inspiron 7437               | Notebook    | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Acer          | Aspire X1920                | Desktop     | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| Dell          | 0RW199                      | Desktop     | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | Notebook    | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [aa341bdff4](https://linux-hardware.org/?probe=aa341bdff4) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | Notebook    | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | Notebook    | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| LG Electro... | 22V240 FAB3                 | All in one  | [23b20c26f2](https://linux-hardware.org/?probe=23b20c26f2) | Feb 24, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| MSI           | G41M-P25                    | Desktop     | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| Dell          | Vostro V130                 | Notebook    | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| ASRock        | K10N78M                     | Desktop     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | Notebook    | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| MSI           | A55M-P33                    | Desktop     | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| Gateway       | M-6307                      | Notebook    | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [4cb6628353](https://linux-hardware.org/?probe=4cb6628353) | Feb 14, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [43ac6b6d18](https://linux-hardware.org/?probe=43ac6b6d18) | Feb 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6f11ea4988](https://linux-hardware.org/?probe=6f11ea4988) | Feb 14, 2022 |
| Sony          | VPCEB3E1E                   | Notebook    | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| HP            | 3031h                       | Desktop     | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| HP            | ProBook 650 G3              | Notebook    | [54a5c321be](https://linux-hardware.org/?probe=54a5c321be) | Feb 08, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| Unknown       | Intel X79                   | Desktop     | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1feae56050](https://linux-hardware.org/?probe=1feae56050) | Feb 06, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | Notebook    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [a2fc96b3dc](https://linux-hardware.org/?probe=a2fc96b3dc) | Feb 05, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e4b5396bf7](https://linux-hardware.org/?probe=e4b5396bf7) | Feb 04, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f0d4a99870](https://linux-hardware.org/?probe=f0d4a99870) | Feb 04, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| Dell          | 0XCR8D A01                  | Desktop     | [a68034b1e8](https://linux-hardware.org/?probe=a68034b1e8) | Feb 03, 2022 |
| HP            | 872E                        | Mini pc     | [8366a84cdb](https://linux-hardware.org/?probe=8366a84cdb) | Feb 02, 2022 |
| HP            | 872E                        | Mini pc     | [533e06f8ac](https://linux-hardware.org/?probe=533e06f8ac) | Feb 02, 2022 |
| Dell          | 051FJ8 A00                  | Desktop     | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [172fc399f5](https://linux-hardware.org/?probe=172fc399f5) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bba0be98c7](https://linux-hardware.org/?probe=bba0be98c7) | Feb 01, 2022 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [27b9e98a16](https://linux-hardware.org/?probe=27b9e98a16) | Feb 01, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [20e43b8b53](https://linux-hardware.org/?probe=20e43b8b53) | Jan 29, 2022 |
| Dell          | Studio 1450                 | Notebook    | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| ASRock        | M3A UCC                     | Desktop     | [8ca7699b4c](https://linux-hardware.org/?probe=8ca7699b4c) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [8d1af3f3af](https://linux-hardware.org/?probe=8d1af3f3af) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [321264426f](https://linux-hardware.org/?probe=321264426f) | Jan 26, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| HP            | G42                         | Notebook    | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | Notebook    | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e0197893fc](https://linux-hardware.org/?probe=e0197893fc) | Jan 24, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [b7fb25920a](https://linux-hardware.org/?probe=b7fb25920a) | Jan 23, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [77545529dc](https://linux-hardware.org/?probe=77545529dc) | Jan 21, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Lenovo        | B590 37612MG                | Notebook    | [cc8d1271b0](https://linux-hardware.org/?probe=cc8d1271b0) | Jan 21, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [6906b181eb](https://linux-hardware.org/?probe=6906b181eb) | Jan 20, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b6de24e7df](https://linux-hardware.org/?probe=b6de24e7df) | Jan 20, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [452df44e84](https://linux-hardware.org/?probe=452df44e84) | Jan 20, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [44b718700d](https://linux-hardware.org/?probe=44b718700d) | Jan 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [262dcaf21e](https://linux-hardware.org/?probe=262dcaf21e) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [5187874180](https://linux-hardware.org/?probe=5187874180) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| Dell          | Latitude D630               | Notebook    | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [a8699a0a00](https://linux-hardware.org/?probe=a8699a0a00) | Jan 18, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | Notebook    | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [2afe3ef5cc](https://linux-hardware.org/?probe=2afe3ef5cc) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | Notebook    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Dell          | 0PP150 A00                  | Desktop     | [554774c3c8](https://linux-hardware.org/?probe=554774c3c8) | Jan 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [d735255913](https://linux-hardware.org/?probe=d735255913) | Jan 15, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [368d168909](https://linux-hardware.org/?probe=368d168909) | Jan 15, 2022 |
| Insyde        | Braswell                    | Notebook    | [a5bca1e5e8](https://linux-hardware.org/?probe=a5bca1e5e8) | Jan 14, 2022 |
| Dell          | Latitude 5480               | Notebook    | [d95c781c2e](https://linux-hardware.org/?probe=d95c781c2e) | Jan 14, 2022 |
| Dell          | Latitude 5480               | Notebook    | [d58108295c](https://linux-hardware.org/?probe=d58108295c) | Jan 14, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | Desktop     | [78902354bb](https://linux-hardware.org/?probe=78902354bb) | Jan 14, 2022 |
| HP            | 829A                        | Mini pc     | [9526ea61c6](https://linux-hardware.org/?probe=9526ea61c6) | Jan 13, 2022 |
| ASUSTek       | M4A78L-M                    | Desktop     | [dfb87ada40](https://linux-hardware.org/?probe=dfb87ada40) | Jan 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6892ab87e1](https://linux-hardware.org/?probe=6892ab87e1) | Jan 13, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [7606a573d6](https://linux-hardware.org/?probe=7606a573d6) | Jan 12, 2022 |
| Lenovo        | IdeaPad S415 Touch 20319    | Notebook    | [d59706fc52](https://linux-hardware.org/?probe=d59706fc52) | Jan 11, 2022 |
| HP            | 3031h                       | Desktop     | [46b02ff904](https://linux-hardware.org/?probe=46b02ff904) | Jan 11, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [b01004055c](https://linux-hardware.org/?probe=b01004055c) | Jan 11, 2022 |
| MOTION        | KEX00                       | Notebook    | [8e36590e72](https://linux-hardware.org/?probe=8e36590e72) | Jan 10, 2022 |
| HP            | 3031h                       | Desktop     | [2e78e6c7f8](https://linux-hardware.org/?probe=2e78e6c7f8) | Jan 10, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [bbcda99dab](https://linux-hardware.org/?probe=bbcda99dab) | Jan 10, 2022 |
| Alienware     | m15 R3                      | Notebook    | [8cff8c6d3f](https://linux-hardware.org/?probe=8cff8c6d3f) | Jan 09, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [7f20d8ac9a](https://linux-hardware.org/?probe=7f20d8ac9a) | Jan 09, 2022 |
| Acer          | Extensa 5620                | Notebook    | [41a1c7001c](https://linux-hardware.org/?probe=41a1c7001c) | Jan 08, 2022 |
| MSI           | H61M-P23                    | Desktop     | [14690b4128](https://linux-hardware.org/?probe=14690b4128) | Jan 08, 2022 |
| Sony          | SVF15A190X                  | Notebook    | [6d729a76af](https://linux-hardware.org/?probe=6d729a76af) | Jan 08, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [65c164f304](https://linux-hardware.org/?probe=65c164f304) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [ef69bbfd12](https://linux-hardware.org/?probe=ef69bbfd12) | Jan 07, 2022 |
| Dell          | Latitude E6500              | Notebook    | [8355df56a3](https://linux-hardware.org/?probe=8355df56a3) | Jan 07, 2022 |
| Gateway       | NV53A                       | Notebook    | [2e67e3a86e](https://linux-hardware.org/?probe=2e67e3a86e) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| HP            | 0AA8h                       | Desktop     | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [aefb321446](https://linux-hardware.org/?probe=aefb321446) | Jan 04, 2022 |
| HP            | 0AA8h                       | Desktop     | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Intel         | DP35DP AAD81073-209         | Desktop     | [f6ec40d0f8](https://linux-hardware.org/?probe=f6ec40d0f8) | Jan 01, 2022 |
| Packard Be... | EasyNote TK87               | Notebook    | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [127df37eab](https://linux-hardware.org/?probe=127df37eab) | Jan 01, 2022 |
| HP            | G60                         | Notebook    | [08350a2b75](https://linux-hardware.org/?probe=08350a2b75) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [fc6d58d758](https://linux-hardware.org/?probe=fc6d58d758) | Jan 01, 2022 |
| Dell          | Inspiron 5765               | Notebook    | [c3a91857b3](https://linux-hardware.org/?probe=c3a91857b3) | Jan 01, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [f1c3532217](https://linux-hardware.org/?probe=f1c3532217) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| ECS           | G41T-M2                     | Desktop     | [6b4159a357](https://linux-hardware.org/?probe=6b4159a357) | Dec 29, 2021 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [2ab97853e3](https://linux-hardware.org/?probe=2ab97853e3) | Dec 29, 2021 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [bc14137c9c](https://linux-hardware.org/?probe=bc14137c9c) | Dec 29, 2021 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| HP            | EliteBook 8440p (VD484AV... | Notebook    | [ba4cf422e7](https://linux-hardware.org/?probe=ba4cf422e7) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [6a61931dde](https://linux-hardware.org/?probe=6a61931dde) | Dec 26, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [00c1f1b6df](https://linux-hardware.org/?probe=00c1f1b6df) | Dec 26, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| ASRock        | A75M-ITX                    | Desktop     | [1070ea74d9](https://linux-hardware.org/?probe=1070ea74d9) | Dec 25, 2021 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [a14e38d07e](https://linux-hardware.org/?probe=a14e38d07e) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [2ef30c62b5](https://linux-hardware.org/?probe=2ef30c62b5) | Dec 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [6eec25d058](https://linux-hardware.org/?probe=6eec25d058) | Dec 24, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [602d3e0afd](https://linux-hardware.org/?probe=602d3e0afd) | Dec 23, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3b47550de1](https://linux-hardware.org/?probe=3b47550de1) | Dec 23, 2021 |
| HP            | 3398                        | Desktop     | [759e3821b8](https://linux-hardware.org/?probe=759e3821b8) | Dec 22, 2021 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [c26a2c5c03](https://linux-hardware.org/?probe=c26a2c5c03) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| Google        | Nami                        | Notebook    | [045f17f15d](https://linux-hardware.org/?probe=045f17f15d) | Dec 22, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [d29b59a855](https://linux-hardware.org/?probe=d29b59a855) | Dec 21, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [22f2f5c84b](https://linux-hardware.org/?probe=22f2f5c84b) | Dec 21, 2021 |
| HP            | 18E7                        | Desktop     | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [32340d057e](https://linux-hardware.org/?probe=32340d057e) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [8986819d3f](https://linux-hardware.org/?probe=8986819d3f) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a94bf3ef84](https://linux-hardware.org/?probe=a94bf3ef84) | Dec 19, 2021 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [e3c5530718](https://linux-hardware.org/?probe=e3c5530718) | Dec 19, 2021 |
| Dell          | 0VD5HY A04                  | Desktop     | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| ASUSTek       | P5GC-MX                     | Desktop     | [499a024e97](https://linux-hardware.org/?probe=499a024e97) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [7c3c9b5cdd](https://linux-hardware.org/?probe=7c3c9b5cdd) | Dec 17, 2021 |
| Dell          | System XPS L502X            | Notebook    | [4588c107ed](https://linux-hardware.org/?probe=4588c107ed) | Dec 16, 2021 |
| Biostar       | H110MHC                     | Desktop     | [bb74f304fd](https://linux-hardware.org/?probe=bb74f304fd) | Dec 16, 2021 |
| Packard Be... | EasyNote TK13BZ             | Notebook    | [e08d4e940c](https://linux-hardware.org/?probe=e08d4e940c) | Dec 15, 2021 |
| Toshiba       | Satellite A105              | Notebook    | [4bddc587d8](https://linux-hardware.org/?probe=4bddc587d8) | Dec 15, 2021 |
| MSI           | MS-B0501 100                | Desktop     | [ca4048db98](https://linux-hardware.org/?probe=ca4048db98) | Dec 14, 2021 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [aa8da2e23c](https://linux-hardware.org/?probe=aa8da2e23c) | Dec 14, 2021 |
| Gateway       | NV53A                       | Notebook    | [1912b6b8c5](https://linux-hardware.org/?probe=1912b6b8c5) | Dec 14, 2021 |
| ASUSTek       | X55U                        | Notebook    | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [c6fcad51e9](https://linux-hardware.org/?probe=c6fcad51e9) | Dec 13, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Dell          | 073MMW A00                  | Desktop     | [c5c064c84f](https://linux-hardware.org/?probe=c5c064c84f) | Dec 13, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [1617abd2f4](https://linux-hardware.org/?probe=1617abd2f4) | Dec 12, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [1f799f28c2](https://linux-hardware.org/?probe=1f799f28c2) | Dec 12, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [22b04adc28](https://linux-hardware.org/?probe=22b04adc28) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [11ff47f723](https://linux-hardware.org/?probe=11ff47f723) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [0dd637c0b8](https://linux-hardware.org/?probe=0dd637c0b8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [1b7f8b1fb9](https://linux-hardware.org/?probe=1b7f8b1fb9) | Dec 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8684f34a9e](https://linux-hardware.org/?probe=8684f34a9e) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | Notebook    | [f0c57ccd03](https://linux-hardware.org/?probe=f0c57ccd03) | Dec 10, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [c505dc1521](https://linux-hardware.org/?probe=c505dc1521) | Dec 09, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [a4f61b0f15](https://linux-hardware.org/?probe=a4f61b0f15) | Dec 09, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [2c5d450c67](https://linux-hardware.org/?probe=2c5d450c67) | Dec 08, 2021 |
| Acer          | Veriton E430 v1.0           | Desktop     | [5c857f1bb6](https://linux-hardware.org/?probe=5c857f1bb6) | Dec 08, 2021 |
| ECS           | Nettle2                     | Desktop     | [bb67b27e67](https://linux-hardware.org/?probe=bb67b27e67) | Dec 07, 2021 |
| Dell          | 01W26N A00                  | Desktop     | [7c3e61ec94](https://linux-hardware.org/?probe=7c3e61ec94) | Dec 06, 2021 |
| Acer          | Aspire 5336                 | Notebook    | [ce9d41eb2f](https://linux-hardware.org/?probe=ce9d41eb2f) | Dec 06, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [b4382c3b38](https://linux-hardware.org/?probe=b4382c3b38) | Dec 04, 2021 |
| Gigabyte      | EP35-DS4                    | Desktop     | [570104ad1e](https://linux-hardware.org/?probe=570104ad1e) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [bc211e09fd](https://linux-hardware.org/?probe=bc211e09fd) | Dec 04, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2e34a3a698](https://linux-hardware.org/?probe=2e34a3a698) | Dec 04, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [9f1502866b](https://linux-hardware.org/?probe=9f1502866b) | Dec 03, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [093fef7eaa](https://linux-hardware.org/?probe=093fef7eaa) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [674712f2a1](https://linux-hardware.org/?probe=674712f2a1) | Dec 03, 2021 |
| Toshiba       | Satellite L870-196          | Notebook    | [15ed850b16](https://linux-hardware.org/?probe=15ed850b16) | Dec 02, 2021 |
| Medion        | H81M-P33                    | Desktop     | [29b3a27675](https://linux-hardware.org/?probe=29b3a27675) | Dec 02, 2021 |
| Dell          | Latitude 5401               | Notebook    | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| HP            | 2000                        | Notebook    | [f16b490828](https://linux-hardware.org/?probe=f16b490828) | Dec 01, 2021 |
| HP            | 0AA4h                       | Desktop     | [f7438f59ac](https://linux-hardware.org/?probe=f7438f59ac) | Dec 01, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [90453b887a](https://linux-hardware.org/?probe=90453b887a) | Dec 01, 2021 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [190d1b6a29](https://linux-hardware.org/?probe=190d1b6a29) | Dec 01, 2021 |
| ASUSTek       | E203NAS                     | Notebook    | [c400f4df81](https://linux-hardware.org/?probe=c400f4df81) | Nov 30, 2021 |
| Shuttle       | NC03U                       | Desktop     | [2453ada3ba](https://linux-hardware.org/?probe=2453ada3ba) | Nov 30, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [6d6caad964](https://linux-hardware.org/?probe=6d6caad964) | Nov 29, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [29e9d64420](https://linux-hardware.org/?probe=29e9d64420) | Nov 29, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [85f288d39b](https://linux-hardware.org/?probe=85f288d39b) | Nov 29, 2021 |
| Samsung       | R530/R730/P590              | Notebook    | [0bbf67316b](https://linux-hardware.org/?probe=0bbf67316b) | Nov 28, 2021 |
| Acer          | EG43LMK                     | Desktop     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [d0170808b3](https://linux-hardware.org/?probe=d0170808b3) | Nov 27, 2021 |
| HP            | 0AA8h                       | Desktop     | [1d80d6636e](https://linux-hardware.org/?probe=1d80d6636e) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [71d58a102c](https://linux-hardware.org/?probe=71d58a102c) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [d9b3bd7851](https://linux-hardware.org/?probe=d9b3bd7851) | Nov 26, 2021 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [c795d5132c](https://linux-hardware.org/?probe=c795d5132c) | Nov 26, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [8b1485f27d](https://linux-hardware.org/?probe=8b1485f27d) | Nov 25, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [311cb04cc5](https://linux-hardware.org/?probe=311cb04cc5) | Nov 25, 2021 |
| HP            | Pavilion 17                 | Notebook    | [43944b4f78](https://linux-hardware.org/?probe=43944b4f78) | Nov 24, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [5a583ec569](https://linux-hardware.org/?probe=5a583ec569) | Nov 24, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [76361c26c6](https://linux-hardware.org/?probe=76361c26c6) | Nov 24, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d61128f6f4](https://linux-hardware.org/?probe=d61128f6f4) | Nov 24, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [fe8ad04ad3](https://linux-hardware.org/?probe=fe8ad04ad3) | Nov 23, 2021 |
| TrekStor      | Primetab T13B               | Tablet      | [19b9435dff](https://linux-hardware.org/?probe=19b9435dff) | Nov 23, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [39d84bdde8](https://linux-hardware.org/?probe=39d84bdde8) | Nov 22, 2021 |
| Alienware     | M17x                        | Notebook    | [13acf7a3f9](https://linux-hardware.org/?probe=13acf7a3f9) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | Notebook    | [65a59cf71c](https://linux-hardware.org/?probe=65a59cf71c) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | Notebook    | [55d87b9d59](https://linux-hardware.org/?probe=55d87b9d59) | Nov 22, 2021 |
| ASUSTek       | M3N78-EM                    | Desktop     | [b358f07f1d](https://linux-hardware.org/?probe=b358f07f1d) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| ASUSTek       | M3N78-EM                    | Desktop     | [930c018424](https://linux-hardware.org/?probe=930c018424) | Nov 20, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [53462f848a](https://linux-hardware.org/?probe=53462f848a) | Nov 20, 2021 |
| Dell          | 014GRG A02                  | Desktop     | [c23455dd49](https://linux-hardware.org/?probe=c23455dd49) | Nov 20, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [b75a64f96a](https://linux-hardware.org/?probe=b75a64f96a) | Nov 19, 2021 |
| ASUSTek       | B150-PLUS                   | Desktop     | [3c4c353831](https://linux-hardware.org/?probe=3c4c353831) | Nov 19, 2021 |
| Lenovo        | ThinkPad T61 766511G        | Notebook    | [e1c74cc580](https://linux-hardware.org/?probe=e1c74cc580) | Nov 19, 2021 |
| HP            | ProBook 650 G3              | Notebook    | [def83e3614](https://linux-hardware.org/?probe=def83e3614) | Nov 19, 2021 |
| MSI           | 3666h                       | Desktop     | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | GT75VR 7RE                  | Notebook    | [02a0e2b5c8](https://linux-hardware.org/?probe=02a0e2b5c8) | Nov 19, 2021 |
| ONE-NETBOO... | A1                          | Notebook    | [aff2f60770](https://linux-hardware.org/?probe=aff2f60770) | Nov 19, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [fc86b0fc2e](https://linux-hardware.org/?probe=fc86b0fc2e) | Nov 18, 2021 |
| MSI           | 3666h                       | Desktop     | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [befbf7345c](https://linux-hardware.org/?probe=befbf7345c) | Nov 17, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [dfba89a8f0](https://linux-hardware.org/?probe=dfba89a8f0) | Nov 17, 2021 |
| HP            | 0AA8h                       | Desktop     | [5cd5f5de04](https://linux-hardware.org/?probe=5cd5f5de04) | Nov 16, 2021 |
| ASRock        | H470 Phantom Gaming 4       | Desktop     | [07ef26c830](https://linux-hardware.org/?probe=07ef26c830) | Nov 16, 2021 |
| Dell          | Latitude 7370               | Notebook    | [b43fadb11c](https://linux-hardware.org/?probe=b43fadb11c) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Apple         | Mac-F2218EC8                | All in one  | [93af642a5d](https://linux-hardware.org/?probe=93af642a5d) | Nov 15, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [dad15363d9](https://linux-hardware.org/?probe=dad15363d9) | Nov 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| Dell          | Latitude E6430              | Notebook    | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | Desktop     | [a8398f9036](https://linux-hardware.org/?probe=a8398f9036) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [78651b05bb](https://linux-hardware.org/?probe=78651b05bb) | Nov 13, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [746f0808f4](https://linux-hardware.org/?probe=746f0808f4) | Nov 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [178497a15b](https://linux-hardware.org/?probe=178497a15b) | Nov 12, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [51d1a5ac24](https://linux-hardware.org/?probe=51d1a5ac24) | Nov 12, 2021 |
| ASUSTek       | X501A                       | Notebook    | [f1eb057027](https://linux-hardware.org/?probe=f1eb057027) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [269b146e10](https://linux-hardware.org/?probe=269b146e10) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Lenovo        | ThinkPad T410 2537MT3       | Notebook    | [76965c829b](https://linux-hardware.org/?probe=76965c829b) | Nov 09, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [3ecf7775d6](https://linux-hardware.org/?probe=3ecf7775d6) | Nov 09, 2021 |
| Sony          | VPCF13M1E                   | Notebook    | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9456930b53](https://linux-hardware.org/?probe=9456930b53) | Nov 08, 2021 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | Notebook    | [685c3c0f3f](https://linux-hardware.org/?probe=685c3c0f3f) | Nov 08, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f40b389872](https://linux-hardware.org/?probe=f40b389872) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [d7a0b05df7](https://linux-hardware.org/?probe=d7a0b05df7) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [425b956614](https://linux-hardware.org/?probe=425b956614) | Nov 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [cd1647c038](https://linux-hardware.org/?probe=cd1647c038) | Nov 07, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [53cfd83c43](https://linux-hardware.org/?probe=53cfd83c43) | Nov 07, 2021 |
| System76      | Oryx Pro                    | Notebook    | [39d1d14e62](https://linux-hardware.org/?probe=39d1d14e62) | Nov 07, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ed14748445](https://linux-hardware.org/?probe=ed14748445) | Nov 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b4c93f107b](https://linux-hardware.org/?probe=b4c93f107b) | Nov 07, 2021 |
| NCR           | Pocono BIOS.3.1             | Desktop     | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| Dell          | G3 3500                     | Notebook    | [acc14d7efc](https://linux-hardware.org/?probe=acc14d7efc) | Nov 07, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d864187bdc](https://linux-hardware.org/?probe=d864187bdc) | Nov 06, 2021 |
| Dell          | Precision M4600             | Notebook    | [acd5115099](https://linux-hardware.org/?probe=acd5115099) | Nov 06, 2021 |
| MSI           | GL63 8RC                    | Notebook    | [068ed7518b](https://linux-hardware.org/?probe=068ed7518b) | Nov 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [ea3cdd3cc4](https://linux-hardware.org/?probe=ea3cdd3cc4) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [617d2f5444](https://linux-hardware.org/?probe=617d2f5444) | Nov 06, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [305cca4bc8](https://linux-hardware.org/?probe=305cca4bc8) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0c1490178d](https://linux-hardware.org/?probe=0c1490178d) | Nov 06, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [d7fe8595a3](https://linux-hardware.org/?probe=d7fe8595a3) | Nov 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [9d85113feb](https://linux-hardware.org/?probe=9d85113feb) | Nov 05, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f8c0647646](https://linux-hardware.org/?probe=f8c0647646) | Nov 05, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8859c97474](https://linux-hardware.org/?probe=8859c97474) | Nov 05, 2021 |
| Toshiba       | Satellite P745              | Notebook    | [59b3468fb9](https://linux-hardware.org/?probe=59b3468fb9) | Nov 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [603fac0b2e](https://linux-hardware.org/?probe=603fac0b2e) | Nov 04, 2021 |
| Dell          | Latitude D630               | Notebook    | [f212896c99](https://linux-hardware.org/?probe=f212896c99) | Nov 04, 2021 |
| Dell          | Precision M4600             | Notebook    | [155f9ec4f4](https://linux-hardware.org/?probe=155f9ec4f4) | Nov 04, 2021 |
| Medion        | MS-7366                     | Desktop     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [9fd353eaff](https://linux-hardware.org/?probe=9fd353eaff) | Nov 04, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [86dd6331fc](https://linux-hardware.org/?probe=86dd6331fc) | Nov 02, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [29af280c0e](https://linux-hardware.org/?probe=29af280c0e) | Nov 01, 2021 |
| ASUSTek       | P2540UA                     | Notebook    | [f10ce209c4](https://linux-hardware.org/?probe=f10ce209c4) | Nov 01, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [22b5b29b32](https://linux-hardware.org/?probe=22b5b29b32) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [c1965ee087](https://linux-hardware.org/?probe=c1965ee087) | Nov 01, 2021 |
| MSI           | GL63 8RC                    | Notebook    | [ad6c3506c1](https://linux-hardware.org/?probe=ad6c3506c1) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [22728e37fe](https://linux-hardware.org/?probe=22728e37fe) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [68a5bdc18a](https://linux-hardware.org/?probe=68a5bdc18a) | Oct 31, 2021 |
| Dell          | Precision M4600             | Notebook    | [f442df91a1](https://linux-hardware.org/?probe=f442df91a1) | Oct 31, 2021 |
| Khadas        | VIM3                        | Soc         | [14bc5c234d](https://linux-hardware.org/?probe=14bc5c234d) | Oct 30, 2021 |
| VIT           | P3400                       | Notebook    | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Acer          | Aspire X3990                | Desktop     | [967427d98c](https://linux-hardware.org/?probe=967427d98c) | Oct 29, 2021 |
| Acer          | Aspire X3990                | Desktop     | [7ccc4b3004](https://linux-hardware.org/?probe=7ccc4b3004) | Oct 29, 2021 |
| sunxi         | Libre Computer Board ALL... | Soc         | [8f5ad2889e](https://linux-hardware.org/?probe=8f5ad2889e) | Oct 29, 2021 |
| HP            | 8433 11                     | Desktop     | [6183f8775b](https://linux-hardware.org/?probe=6183f8775b) | Oct 29, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [48434e75fb](https://linux-hardware.org/?probe=48434e75fb) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [13addb7994](https://linux-hardware.org/?probe=13addb7994) | Oct 28, 2021 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [5ce9661292](https://linux-hardware.org/?probe=5ce9661292) | Oct 28, 2021 |
| HP            | Compaq 6730s                | Notebook    | [8bc4483616](https://linux-hardware.org/?probe=8bc4483616) | Oct 27, 2021 |
| Khadas        | VIM3                        | Soc         | [ef5d046e03](https://linux-hardware.org/?probe=ef5d046e03) | Oct 27, 2021 |
| HP            | Pavilion g4                 | Notebook    | [90f6743fbd](https://linux-hardware.org/?probe=90f6743fbd) | Oct 27, 2021 |
| ASUSTek       | X501A                       | Notebook    | [2e47dd4121](https://linux-hardware.org/?probe=2e47dd4121) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [2c2443341f](https://linux-hardware.org/?probe=2c2443341f) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [16306ffb37](https://linux-hardware.org/?probe=16306ffb37) | Oct 25, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Alienware     | m17 R4                      | Notebook    | [5c569c3982](https://linux-hardware.org/?probe=5c569c3982) | Oct 24, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2b52b81540](https://linux-hardware.org/?probe=2b52b81540) | Oct 24, 2021 |
| HP            | Compaq 6730s                | Notebook    | [587b440ce4](https://linux-hardware.org/?probe=587b440ce4) | Oct 24, 2021 |
| Dell          | 042P49 A00                  | Desktop     | [7bb7c6c3cb](https://linux-hardware.org/?probe=7bb7c6c3cb) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [68f1525bef](https://linux-hardware.org/?probe=68f1525bef) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [1146299277](https://linux-hardware.org/?probe=1146299277) | Oct 23, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [cb8b850048](https://linux-hardware.org/?probe=cb8b850048) | Oct 23, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [0273030434](https://linux-hardware.org/?probe=0273030434) | Oct 22, 2021 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [f76ae4b159](https://linux-hardware.org/?probe=f76ae4b159) | Oct 22, 2021 |
| HP            | kip                         | Notebook    | [18f48f3a5b](https://linux-hardware.org/?probe=18f48f3a5b) | Oct 22, 2021 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [ba467258aa](https://linux-hardware.org/?probe=ba467258aa) | Oct 21, 2021 |
| HP            | Notebook                    | Notebook    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [6be3808b94](https://linux-hardware.org/?probe=6be3808b94) | Oct 21, 2021 |
| HP            | 1998                        | Desktop     | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Lenovo        | IdeaPad U550 20034,3749     | Notebook    | [3bbec8b8fd](https://linux-hardware.org/?probe=3bbec8b8fd) | Oct 21, 2021 |
| Dell          | 0PU052                      | Desktop     | [7e7d0bc489](https://linux-hardware.org/?probe=7e7d0bc489) | Oct 21, 2021 |
| ASUSTek       | PRIME H310T                 | Desktop     | [b0e10a4766](https://linux-hardware.org/?probe=b0e10a4766) | Oct 20, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [a119d97189](https://linux-hardware.org/?probe=a119d97189) | Oct 20, 2021 |
| Toshiba       | Satellite Pro C850-1G8      | Notebook    | [8ad9f2f898](https://linux-hardware.org/?probe=8ad9f2f898) | Oct 20, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [7fb2681427](https://linux-hardware.org/?probe=7fb2681427) | Oct 20, 2021 |
| Lenovo        | B5400 s20278Q               | Notebook    | [c71ca98310](https://linux-hardware.org/?probe=c71ca98310) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [a2aee507a3](https://linux-hardware.org/?probe=a2aee507a3) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [5a3e03b67e](https://linux-hardware.org/?probe=5a3e03b67e) | Oct 19, 2021 |
| Dell          | 0KX11M A04                  | Server      | [df26c4e8c4](https://linux-hardware.org/?probe=df26c4e8c4) | Oct 19, 2021 |
| Samsung       | R530/R730/P590              | Notebook    | [e76e147759](https://linux-hardware.org/?probe=e76e147759) | Oct 19, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [555bb7179c](https://linux-hardware.org/?probe=555bb7179c) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [63cab5e07f](https://linux-hardware.org/?probe=63cab5e07f) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [355e464f7f](https://linux-hardware.org/?probe=355e464f7f) | Oct 19, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [235b6e8d1a](https://linux-hardware.org/?probe=235b6e8d1a) | Oct 18, 2021 |
| Acer          | Extensa 5630                | Notebook    | [4823b348aa](https://linux-hardware.org/?probe=4823b348aa) | Oct 18, 2021 |
| HP            | 8717                        | Desktop     | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Latitude E6440              | Notebook    | [640d2341de](https://linux-hardware.org/?probe=640d2341de) | Oct 17, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [9debdd654c](https://linux-hardware.org/?probe=9debdd654c) | Oct 15, 2021 |
| NCR           | Pocono BIOS.3.1             | Desktop     | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b9218a0347](https://linux-hardware.org/?probe=b9218a0347) | Oct 15, 2021 |
| Supermicro    | X8DTH                       | Server      | [ad4abe60cd](https://linux-hardware.org/?probe=ad4abe60cd) | Oct 13, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [ef126ad790](https://linux-hardware.org/?probe=ef126ad790) | Oct 13, 2021 |
| Clientron     | Pineview-D                  | Desktop     | [59bf0b789c](https://linux-hardware.org/?probe=59bf0b789c) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [125473d905](https://linux-hardware.org/?probe=125473d905) | Oct 13, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [6163de66f1](https://linux-hardware.org/?probe=6163de66f1) | Oct 12, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e922eda008](https://linux-hardware.org/?probe=e922eda008) | Oct 12, 2021 |
| eMachines     | G730                        | Notebook    | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Foxconn       | 2AB1h                       | Desktop     | [6216ce3f5c](https://linux-hardware.org/?probe=6216ce3f5c) | Oct 12, 2021 |
| HP            | ProBook 650 G4              | Notebook    | [ea1c62ead1](https://linux-hardware.org/?probe=ea1c62ead1) | Oct 12, 2021 |
| Dell          | Latitude 7370               | Notebook    | [348b718b2b](https://linux-hardware.org/?probe=348b718b2b) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [56135a7fa6](https://linux-hardware.org/?probe=56135a7fa6) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [d7676eeb32](https://linux-hardware.org/?probe=d7676eeb32) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [c49cbf2f7a](https://linux-hardware.org/?probe=c49cbf2f7a) | Oct 11, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [6d2f43a452](https://linux-hardware.org/?probe=6d2f43a452) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [6beb9ddceb](https://linux-hardware.org/?probe=6beb9ddceb) | Oct 09, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [a4da124d05](https://linux-hardware.org/?probe=a4da124d05) | Oct 08, 2021 |
| Dell          | Precision 5540              | Notebook    | [b59369e8e7](https://linux-hardware.org/?probe=b59369e8e7) | Oct 08, 2021 |
| Multilaser    | UB32X                       | Notebook    | [e5e22df913](https://linux-hardware.org/?probe=e5e22df913) | Oct 08, 2021 |
| Gigabyte      | X38-DS4                     | Desktop     | [5e06d3cb35](https://linux-hardware.org/?probe=5e06d3cb35) | Oct 08, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [248c508eb0](https://linux-hardware.org/?probe=248c508eb0) | Oct 07, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [0735063fbe](https://linux-hardware.org/?probe=0735063fbe) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [399430cdbe](https://linux-hardware.org/?probe=399430cdbe) | Oct 06, 2021 |
| Lenovo        | ThinkPad E14 20RA0016RT     | Notebook    | [d09fddd2b5](https://linux-hardware.org/?probe=d09fddd2b5) | Oct 06, 2021 |
| Lenovo        | ThinkCentre A55 92658HG     | Desktop     | [edc1f2768d](https://linux-hardware.org/?probe=edc1f2768d) | Oct 05, 2021 |
| Acer          | Aspire X1430                | Desktop     | [0864e39368](https://linux-hardware.org/?probe=0864e39368) | Oct 05, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [697843fefc](https://linux-hardware.org/?probe=697843fefc) | Oct 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [9ba5143844](https://linux-hardware.org/?probe=9ba5143844) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [e8fd995776](https://linux-hardware.org/?probe=e8fd995776) | Oct 03, 2021 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [37caf69047](https://linux-hardware.org/?probe=37caf69047) | Oct 02, 2021 |
| Sony          | VGN-NR38E_S                 | Notebook    | [8cb5fc39c1](https://linux-hardware.org/?probe=8cb5fc39c1) | Oct 01, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [5cccf30dd4](https://linux-hardware.org/?probe=5cccf30dd4) | Oct 01, 2021 |
| ASUSTek       | K53E                        | Notebook    | [c98e6e26ce](https://linux-hardware.org/?probe=c98e6e26ce) | Oct 01, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [f107c84c00](https://linux-hardware.org/?probe=f107c84c00) | Sep 30, 2021 |
| Insyde        | Harrisonville               | Desktop     | [2b7a8ba5fc](https://linux-hardware.org/?probe=2b7a8ba5fc) | Sep 30, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | Notebook    | [73a0747f86](https://linux-hardware.org/?probe=73a0747f86) | Sep 29, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [8fa77435f7](https://linux-hardware.org/?probe=8fa77435f7) | Sep 29, 2021 |
| HP            | 2175                        | Desktop     | [856907ec52](https://linux-hardware.org/?probe=856907ec52) | Sep 28, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [97872be09f](https://linux-hardware.org/?probe=97872be09f) | Sep 28, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [c79d4daf0a](https://linux-hardware.org/?probe=c79d4daf0a) | Sep 28, 2021 |
| ASUSTek       | PRIME H310T                 | Desktop     | [58721f0765](https://linux-hardware.org/?probe=58721f0765) | Sep 28, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [fc1d74c246](https://linux-hardware.org/?probe=fc1d74c246) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [87dd9f48a9](https://linux-hardware.org/?probe=87dd9f48a9) | Sep 26, 2021 |
| Dell          | Studio 1558                 | Notebook    | [05f781c843](https://linux-hardware.org/?probe=05f781c843) | Sep 25, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [ce0d8f233c](https://linux-hardware.org/?probe=ce0d8f233c) | Sep 24, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [6160d9149f](https://linux-hardware.org/?probe=6160d9149f) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| HP            | Compaq 6710b (GB889ET#AB... | Notebook    | [2fcbe348d6](https://linux-hardware.org/?probe=2fcbe348d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| HP            | Notebook                    | Notebook    | [0253eca654](https://linux-hardware.org/?probe=0253eca654) | Sep 22, 2021 |
| HP            | Notebook                    | Notebook    | [9afc140a7e](https://linux-hardware.org/?probe=9afc140a7e) | Sep 22, 2021 |
| HP            | 21F5                        | Desktop     | [d6613e1901](https://linux-hardware.org/?probe=d6613e1901) | Sep 22, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [aabfa3e289](https://linux-hardware.org/?probe=aabfa3e289) | Sep 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | Desktop     | [7abd7a20df](https://linux-hardware.org/?probe=7abd7a20df) | Sep 21, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [87a47d3bc8](https://linux-hardware.org/?probe=87a47d3bc8) | Sep 20, 2021 |
| Clevo         | W760SUB                     | Notebook    | [8ae1ea1d6b](https://linux-hardware.org/?probe=8ae1ea1d6b) | Sep 20, 2021 |
| HP            | ProBook 4510s               | Notebook    | [721b35cbcb](https://linux-hardware.org/?probe=721b35cbcb) | Sep 19, 2021 |
| NCR           | Pocono                      | Desktop     | [bbd821ad81](https://linux-hardware.org/?probe=bbd821ad81) | Sep 18, 2021 |
| Lenovo        | G460 0677                   | Notebook    | [6f23b54ef5](https://linux-hardware.org/?probe=6f23b54ef5) | Sep 17, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [ad597e71b6](https://linux-hardware.org/?probe=ad597e71b6) | Sep 16, 2021 |
| Dell          | Latitude D630               | Notebook    | [260bb1528f](https://linux-hardware.org/?probe=260bb1528f) | Sep 15, 2021 |
| Dell          | Inspiron 3437               | Notebook    | [67069e48f0](https://linux-hardware.org/?probe=67069e48f0) | Sep 15, 2021 |
| Lenovo        | G480 20150                  | Notebook    | [d7d8be3a08](https://linux-hardware.org/?probe=d7d8be3a08) | Sep 15, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [ea9fbdbba6](https://linux-hardware.org/?probe=ea9fbdbba6) | Sep 14, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [c7f133cbb9](https://linux-hardware.org/?probe=c7f133cbb9) | Sep 14, 2021 |
| Foxconn       | 2A8C                        | Desktop     | [f7b2ed152f](https://linux-hardware.org/?probe=f7b2ed152f) | Sep 12, 2021 |
| HP            | 15                          | Notebook    | [d88dbb5aa3](https://linux-hardware.org/?probe=d88dbb5aa3) | Sep 12, 2021 |
| HP            | Pavilion dm4                | Notebook    | [a10c76835b](https://linux-hardware.org/?probe=a10c76835b) | Sep 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [bced59049e](https://linux-hardware.org/?probe=bced59049e) | Sep 11, 2021 |
| Samsung       | 930QCG                      | Convertible | [2169c592d9](https://linux-hardware.org/?probe=2169c592d9) | Sep 11, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e2ad40d8c1](https://linux-hardware.org/?probe=e2ad40d8c1) | Sep 10, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | Notebook    | [3abbaccc90](https://linux-hardware.org/?probe=3abbaccc90) | Sep 09, 2021 |
| ASUSTek       | M3N18L T-M3N8200            | Desktop     | [bd8410bceb](https://linux-hardware.org/?probe=bd8410bceb) | Sep 09, 2021 |
| MSI           | GF75 Thin 9SD               | Notebook    | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | ProBook 4510s               | Notebook    | [b2e4641005](https://linux-hardware.org/?probe=b2e4641005) | Sep 09, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [3ca698d670](https://linux-hardware.org/?probe=3ca698d670) | Sep 09, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [37bd4db385](https://linux-hardware.org/?probe=37bd4db385) | Sep 09, 2021 |
| Itautec       | Infoway a7420               | Notebook    | [282046f0c0](https://linux-hardware.org/?probe=282046f0c0) | Sep 09, 2021 |
| HP            | G60                         | Notebook    | [065e03350f](https://linux-hardware.org/?probe=065e03350f) | Sep 09, 2021 |
| HP            | G60                         | Notebook    | [4d35031cdf](https://linux-hardware.org/?probe=4d35031cdf) | Sep 09, 2021 |
| Biostar       | G41D3C                      | Desktop     | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [7b81d32161](https://linux-hardware.org/?probe=7b81d32161) | Sep 07, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7ff32b60eb](https://linux-hardware.org/?probe=7ff32b60eb) | Sep 05, 2021 |
| Apple         | Mac-F2208EC8                | Mini pc     | [452356fda6](https://linux-hardware.org/?probe=452356fda6) | Sep 05, 2021 |
| Dell          | Latitude E4310              | Notebook    | [5e7233f129](https://linux-hardware.org/?probe=5e7233f129) | Sep 05, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [631ee4fd97](https://linux-hardware.org/?probe=631ee4fd97) | Sep 05, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [441840f603](https://linux-hardware.org/?probe=441840f603) | Sep 04, 2021 |
| HP            | 14                          | Notebook    | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Gateway       | NV57H                       | Notebook    | [5ccb66dc7c](https://linux-hardware.org/?probe=5ccb66dc7c) | Sep 03, 2021 |
| OEM           | BayTrail JHS365             | Desktop     | [e82d82c85b](https://linux-hardware.org/?probe=e82d82c85b) | Sep 03, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [899954b326](https://linux-hardware.org/?probe=899954b326) | Sep 02, 2021 |
| Acer          | Aspire XC-603G              | Desktop     | [888a6f7244](https://linux-hardware.org/?probe=888a6f7244) | Sep 02, 2021 |
| HP            | 3032h                       | Desktop     | [4b261dcd37](https://linux-hardware.org/?probe=4b261dcd37) | Sep 02, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [b9fdcaf2f7](https://linux-hardware.org/?probe=b9fdcaf2f7) | Sep 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e47d2dc721](https://linux-hardware.org/?probe=e47d2dc721) | Sep 02, 2021 |
| Acer          | Aspire E1-772               | Notebook    | [2b6d07434a](https://linux-hardware.org/?probe=2b6d07434a) | Sep 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ee916ec895](https://linux-hardware.org/?probe=ee916ec895) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | Notebook    | [4c1d560351](https://linux-hardware.org/?probe=4c1d560351) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [6afc243dea](https://linux-hardware.org/?probe=6afc243dea) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| Lenovo        | ThinkPad X395 20NLS0J400    | Notebook    | [cd2fa55d01](https://linux-hardware.org/?probe=cd2fa55d01) | Sep 01, 2021 |
| MSI           | Z97-G43                     | Desktop     | [364baf5248](https://linux-hardware.org/?probe=364baf5248) | Aug 31, 2021 |
| ASRock        | Q1900M                      | Desktop     | [bdb4eba3e4](https://linux-hardware.org/?probe=bdb4eba3e4) | Aug 31, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [0631958800](https://linux-hardware.org/?probe=0631958800) | Aug 29, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [89c397b882](https://linux-hardware.org/?probe=89c397b882) | Aug 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | 15                          | Notebook    | [8e64e4a38f](https://linux-hardware.org/?probe=8e64e4a38f) | Aug 26, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | Notebook    | [932fb79537](https://linux-hardware.org/?probe=932fb79537) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [aa1a98a9d6](https://linux-hardware.org/?probe=aa1a98a9d6) | Aug 25, 2021 |
| MSI           | MS-163K Ver                 | Notebook    | [836a501df0](https://linux-hardware.org/?probe=836a501df0) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Lenovo        | B40-45 20394                | Notebook    | [551749a1af](https://linux-hardware.org/?probe=551749a1af) | Aug 25, 2021 |
| Notebook      | W970SUW                     | Notebook    | [231346d40a](https://linux-hardware.org/?probe=231346d40a) | Aug 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [fae18649fd](https://linux-hardware.org/?probe=fae18649fd) | Aug 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [f0824b7193](https://linux-hardware.org/?probe=f0824b7193) | Aug 24, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | Notebook    | [74c2a834e7](https://linux-hardware.org/?probe=74c2a834e7) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [8d43ff5f35](https://linux-hardware.org/?probe=8d43ff5f35) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [23fcf2122e](https://linux-hardware.org/?probe=23fcf2122e) | Aug 23, 2021 |
| Dell          | Studio 1569                 | Notebook    | [600cbb330c](https://linux-hardware.org/?probe=600cbb330c) | Aug 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f128b4ee5a](https://linux-hardware.org/?probe=f128b4ee5a) | Aug 23, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [08e78aa61d](https://linux-hardware.org/?probe=08e78aa61d) | Aug 23, 2021 |
| Acer          | Aspire XC-603G              | Desktop     | [3aca23ef5f](https://linux-hardware.org/?probe=3aca23ef5f) | Aug 22, 2021 |
| Foxconn       | 2A8C                        | Desktop     | [f3ae3bb84c](https://linux-hardware.org/?probe=f3ae3bb84c) | Aug 21, 2021 |
| ASUSTek       | X501A                       | Notebook    | [e9784e8db3](https://linux-hardware.org/?probe=e9784e8db3) | Aug 21, 2021 |
| Alienware     | 0N4R4N A00                  | Desktop     | [bf5947b943](https://linux-hardware.org/?probe=bf5947b943) | Aug 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | Notebook    | [fb7ab1b2d1](https://linux-hardware.org/?probe=fb7ab1b2d1) | Aug 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [df5f5f1ab4](https://linux-hardware.org/?probe=df5f5f1ab4) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [42ab0a8ca5](https://linux-hardware.org/?probe=42ab0a8ca5) | Aug 20, 2021 |
| Acer          | Aspire X1470                | Desktop     | [79d5cfd4fd](https://linux-hardware.org/?probe=79d5cfd4fd) | Aug 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [6651af56b1](https://linux-hardware.org/?probe=6651af56b1) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | Notebook    | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [a0e952ee9c](https://linux-hardware.org/?probe=a0e952ee9c) | Aug 19, 2021 |
| Google        | Kip                         | Notebook    | [11ba4592bc](https://linux-hardware.org/?probe=11ba4592bc) | Aug 19, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [37a5e6b984](https://linux-hardware.org/?probe=37a5e6b984) | Aug 18, 2021 |
| HP            | 255 G1                      | Notebook    | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [a5b305d6f5](https://linux-hardware.org/?probe=a5b305d6f5) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [dbb548b728](https://linux-hardware.org/?probe=dbb548b728) | Aug 18, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [ce21a853bc](https://linux-hardware.org/?probe=ce21a853bc) | Aug 18, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9e4e9c3dea](https://linux-hardware.org/?probe=9e4e9c3dea) | Aug 17, 2021 |
| Lenovo        | B5400 s20278Q               | Notebook    | [24ebde0d00](https://linux-hardware.org/?probe=24ebde0d00) | Aug 17, 2021 |
| Dell          | Latitude E4310              | Notebook    | [489bf81791](https://linux-hardware.org/?probe=489bf81791) | Aug 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4740529a1f](https://linux-hardware.org/?probe=4740529a1f) | Aug 17, 2021 |
| MSI           | Boston                      | Desktop     | [eb189f6da8](https://linux-hardware.org/?probe=eb189f6da8) | Aug 17, 2021 |
| HP            | 0B54h D                     | Desktop     | [f68a448d75](https://linux-hardware.org/?probe=f68a448d75) | Aug 17, 2021 |
| Gateway       | SX2185                      | Desktop     | [6e9745ae09](https://linux-hardware.org/?probe=6e9745ae09) | Aug 17, 2021 |
| HP            | 0B54h D                     | Desktop     | [9fd9d289f2](https://linux-hardware.org/?probe=9fd9d289f2) | Aug 17, 2021 |
| Lenovo        | ThinkPad W540 20BHS0KY08    | Notebook    | [6ba4712f8d](https://linux-hardware.org/?probe=6ba4712f8d) | Aug 16, 2021 |
| Dell          | Vostro 3491                 | Notebook    | [0f23db87f7](https://linux-hardware.org/?probe=0f23db87f7) | Aug 16, 2021 |
| HP            | ProBook 6470b               | Notebook    | [f42e212309](https://linux-hardware.org/?probe=f42e212309) | Aug 14, 2021 |
| ASUSTek       | B85-PLUS                    | Desktop     | [10fd5746f0](https://linux-hardware.org/?probe=10fd5746f0) | Aug 14, 2021 |
| HP            | Compaq 8710w                | Notebook    | [1e1d518b29](https://linux-hardware.org/?probe=1e1d518b29) | Aug 14, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [3ff1b8f6dc](https://linux-hardware.org/?probe=3ff1b8f6dc) | Aug 14, 2021 |
| Lenovo        | ThinkPad W540 20BHS1HR00    | Notebook    | [514e20d875](https://linux-hardware.org/?probe=514e20d875) | Aug 14, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [23b1aab5c3](https://linux-hardware.org/?probe=23b1aab5c3) | Aug 13, 2021 |
| Toshiba       | Satellite P205D             | Notebook    | [95f23ff5ec](https://linux-hardware.org/?probe=95f23ff5ec) | Aug 13, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e78e29878](https://linux-hardware.org/?probe=2e78e29878) | Aug 12, 2021 |
| Dell          | Vostro 3491                 | Notebook    | [125085e464](https://linux-hardware.org/?probe=125085e464) | Aug 12, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [a0023fa7d2](https://linux-hardware.org/?probe=a0023fa7d2) | Aug 12, 2021 |
| HP            | 0B54h D                     | Desktop     | [49eb423362](https://linux-hardware.org/?probe=49eb423362) | Aug 11, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [4a660bcb77](https://linux-hardware.org/?probe=4a660bcb77) | Aug 11, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [0cf6373ba8](https://linux-hardware.org/?probe=0cf6373ba8) | Aug 10, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [adee49adad](https://linux-hardware.org/?probe=adee49adad) | Aug 10, 2021 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0b019ac936](https://linux-hardware.org/?probe=0b019ac936) | Aug 09, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [c2ed04ce87](https://linux-hardware.org/?probe=c2ed04ce87) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| Dell          | 0WMJ54 A00                  | Desktop     | [d577241d35](https://linux-hardware.org/?probe=d577241d35) | Aug 08, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [6f97e49163](https://linux-hardware.org/?probe=6f97e49163) | Aug 08, 2021 |
| Toshiba       | Satellite P205D             | Notebook    | [827f451413](https://linux-hardware.org/?probe=827f451413) | Aug 07, 2021 |
| Toshiba       | Satellite P205D             | Notebook    | [a39bd5d78b](https://linux-hardware.org/?probe=a39bd5d78b) | Aug 07, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [c45499e754](https://linux-hardware.org/?probe=c45499e754) | Aug 07, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [7d3f237f02](https://linux-hardware.org/?probe=7d3f237f02) | Aug 07, 2021 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [a642818617](https://linux-hardware.org/?probe=a642818617) | Aug 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [c3ac112d1b](https://linux-hardware.org/?probe=c3ac112d1b) | Aug 06, 2021 |
| Notebook      | P65_P67RGRERA               | Notebook    | [07d63d9efc](https://linux-hardware.org/?probe=07d63d9efc) | Aug 06, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [01a2971d58](https://linux-hardware.org/?probe=01a2971d58) | Aug 06, 2021 |
| Acer          | Aspire ES1-111              | Notebook    | [5f5802297c](https://linux-hardware.org/?probe=5f5802297c) | Aug 05, 2021 |
| ASUSTek       | X455YA                      | Notebook    | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| Lenovo        | G460 0677                   | Notebook    | [18dd5bf1b0](https://linux-hardware.org/?probe=18dd5bf1b0) | Aug 05, 2021 |
| Dell          | 0PN455 A00                  | All in one  | [3936fd702b](https://linux-hardware.org/?probe=3936fd702b) | Aug 04, 2021 |
| HP            | EliteBook x360 1040 G7 N... | Convertible | [ca10831a1e](https://linux-hardware.org/?probe=ca10831a1e) | Aug 04, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [3bca4552ab](https://linux-hardware.org/?probe=3bca4552ab) | Aug 04, 2021 |
| HP            | 1998                        | Desktop     | [e6d0744e85](https://linux-hardware.org/?probe=e6d0744e85) | Aug 04, 2021 |
| HP            | 1998                        | Desktop     | [b3b909d152](https://linux-hardware.org/?probe=b3b909d152) | Aug 04, 2021 |
| HP            | 2000                        | Notebook    | [27633bfd4b](https://linux-hardware.org/?probe=27633bfd4b) | Aug 03, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [8076357ae9](https://linux-hardware.org/?probe=8076357ae9) | Aug 03, 2021 |
| Lenovo        | G460 0677                   | Notebook    | [1563cdbde9](https://linux-hardware.org/?probe=1563cdbde9) | Aug 02, 2021 |
| HP            | 3646h                       | Desktop     | [60fb363058](https://linux-hardware.org/?probe=60fb363058) | Aug 02, 2021 |
| HP            | 2B29                        | Desktop     | [06babd8c13](https://linux-hardware.org/?probe=06babd8c13) | Aug 01, 2021 |
| HP            | 0B54h D                     | Desktop     | [a7f0b16b1f](https://linux-hardware.org/?probe=a7f0b16b1f) | Jul 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0aae2dd454](https://linux-hardware.org/?probe=0aae2dd454) | Jul 30, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [fb919a9b90](https://linux-hardware.org/?probe=fb919a9b90) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [fb839f1401](https://linux-hardware.org/?probe=fb839f1401) | Jul 30, 2021 |
| Lenovo        | ThinkPad T500 2241CG9       | Notebook    | [912d324ee3](https://linux-hardware.org/?probe=912d324ee3) | Jul 29, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [90e216200b](https://linux-hardware.org/?probe=90e216200b) | Jul 29, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4e46cf5851](https://linux-hardware.org/?probe=4e46cf5851) | Jul 29, 2021 |
| Sony          | SVE1512C6EB                 | Notebook    | [e1ce6add06](https://linux-hardware.org/?probe=e1ce6add06) | Jul 28, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [0a30fad96c](https://linux-hardware.org/?probe=0a30fad96c) | Jul 27, 2021 |
| HP            | 15                          | Notebook    | [6b1274ba87](https://linux-hardware.org/?probe=6b1274ba87) | Jul 27, 2021 |
| HP            | 15                          | Notebook    | [28f688d410](https://linux-hardware.org/?probe=28f688d410) | Jul 27, 2021 |
| BANGHO        | Suma 1025                   | Tablet      | [a8fd7a9a44](https://linux-hardware.org/?probe=a8fd7a9a44) | Jul 26, 2021 |
| MSI           | MS-7181                     | Desktop     | [f2c624a258](https://linux-hardware.org/?probe=f2c624a258) | Jul 26, 2021 |
| WinFast       | 6100M2MA FAB1.0             | Desktop     | [f994eb2a66](https://linux-hardware.org/?probe=f994eb2a66) | Jul 26, 2021 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [36a4037b9d](https://linux-hardware.org/?probe=36a4037b9d) | Jul 26, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [15aef595c1](https://linux-hardware.org/?probe=15aef595c1) | Jul 26, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [9a8bc84b14](https://linux-hardware.org/?probe=9a8bc84b14) | Jul 26, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [69bc249119](https://linux-hardware.org/?probe=69bc249119) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d6e4e7f445](https://linux-hardware.org/?probe=d6e4e7f445) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [7d7ebd3f1e](https://linux-hardware.org/?probe=7d7ebd3f1e) | Jul 25, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [56198fa6c1](https://linux-hardware.org/?probe=56198fa6c1) | Jul 24, 2021 |
| Dell          | 03KWTV A02                  | Desktop     | [b292aa69b5](https://linux-hardware.org/?probe=b292aa69b5) | Jul 24, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [94f41122bf](https://linux-hardware.org/?probe=94f41122bf) | Jul 24, 2021 |
| HP            | Notebook                    | Notebook    | [75e72e2359](https://linux-hardware.org/?probe=75e72e2359) | Jul 24, 2021 |
| HP            | 1589                        | Desktop     | [2885bdaad2](https://linux-hardware.org/?probe=2885bdaad2) | Jul 23, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [a81a047059](https://linux-hardware.org/?probe=a81a047059) | Jul 23, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [3cc56271ad](https://linux-hardware.org/?probe=3cc56271ad) | Jul 23, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [46032a26c5](https://linux-hardware.org/?probe=46032a26c5) | Jul 23, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [a76718434c](https://linux-hardware.org/?probe=a76718434c) | Jul 23, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [b125a65313](https://linux-hardware.org/?probe=b125a65313) | Jul 22, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| Dell          | Latitude E6330              | Notebook    | [772c8f269b](https://linux-hardware.org/?probe=772c8f269b) | Jul 21, 2021 |
| HP            | Unknown                     | Notebook    | [3f71deefd5](https://linux-hardware.org/?probe=3f71deefd5) | Jul 20, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [63865e14f0](https://linux-hardware.org/?probe=63865e14f0) | Jul 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2895631c36](https://linux-hardware.org/?probe=2895631c36) | Jul 19, 2021 |
| HP            | Laptop 17-by4xxx            | Notebook    | [d66405d958](https://linux-hardware.org/?probe=d66405d958) | Jul 19, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [f8767723e4](https://linux-hardware.org/?probe=f8767723e4) | Jul 18, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [29e1b14111](https://linux-hardware.org/?probe=29e1b14111) | Jul 18, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [088adbd181](https://linux-hardware.org/?probe=088adbd181) | Jul 18, 2021 |
| ASRock        | 880GM-LE                    | Desktop     | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [561ed2dd58](https://linux-hardware.org/?probe=561ed2dd58) | Jul 18, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [838188303a](https://linux-hardware.org/?probe=838188303a) | Jul 17, 2021 |
| Samsung       | R530/R730/P530              | Notebook    | [f95d4bb8f5](https://linux-hardware.org/?probe=f95d4bb8f5) | Jul 17, 2021 |
| Dell          | 0VNP2H A00                  | Desktop     | [167ec81986](https://linux-hardware.org/?probe=167ec81986) | Jul 17, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [8263a1f725](https://linux-hardware.org/?probe=8263a1f725) | Jul 17, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| Lenovo        | ThinkPad E485 20KU001CGE    | Notebook    | [4a42a910a2](https://linux-hardware.org/?probe=4a42a910a2) | Jul 15, 2021 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [ebbe4a088d](https://linux-hardware.org/?probe=ebbe4a088d) | Jul 15, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [3f9fb487ad](https://linux-hardware.org/?probe=3f9fb487ad) | Jul 15, 2021 |
| ASUSTek       | M3A-H/HDMI                  | Desktop     | [6c97b09b3f](https://linux-hardware.org/?probe=6c97b09b3f) | Jul 14, 2021 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [d871a17735](https://linux-hardware.org/?probe=d871a17735) | Jul 14, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [46fb536e9d](https://linux-hardware.org/?probe=46fb536e9d) | Jul 13, 2021 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [ee2fa49a14](https://linux-hardware.org/?probe=ee2fa49a14) | Jul 13, 2021 |
| HP            | 0A64h                       | Desktop     | [317c62b0b9](https://linux-hardware.org/?probe=317c62b0b9) | Jul 13, 2021 |
| HP            | 0A64h                       | Desktop     | [7495976a12](https://linux-hardware.org/?probe=7495976a12) | Jul 13, 2021 |
| Lenovo        | ThinkPad W530 24479Q7       | Notebook    | [1feeb254be](https://linux-hardware.org/?probe=1feeb254be) | Jul 12, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [03c69f44e3](https://linux-hardware.org/?probe=03c69f44e3) | Jul 12, 2021 |
| Dell          | Inspiron 5485               | Notebook    | [d97549e586](https://linux-hardware.org/?probe=d97549e586) | Jul 11, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [6103626346](https://linux-hardware.org/?probe=6103626346) | Jul 11, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bb0f20f7a9](https://linux-hardware.org/?probe=bb0f20f7a9) | Jul 10, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [5416b8d0da](https://linux-hardware.org/?probe=5416b8d0da) | Jul 10, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [9f1b7a37f2](https://linux-hardware.org/?probe=9f1b7a37f2) | Jul 07, 2021 |
| HP            | Laptop 17-by4xxx            | Notebook    | [bd9ce451e8](https://linux-hardware.org/?probe=bd9ce451e8) | Jul 07, 2021 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [252d84e173](https://linux-hardware.org/?probe=252d84e173) | Jul 05, 2021 |
| Acer          | AOD270                      | Notebook    | [c829f9921a](https://linux-hardware.org/?probe=c829f9921a) | Jul 05, 2021 |
| MSI           | Boston                      | Desktop     | [72f1bfa2f0](https://linux-hardware.org/?probe=72f1bfa2f0) | Jul 05, 2021 |
| MSI           | Boston                      | Desktop     | [ff82275c70](https://linux-hardware.org/?probe=ff82275c70) | Jul 04, 2021 |
| ASRock        | J4105M                      | Desktop     | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | Desktop     | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [7974efd1a4](https://linux-hardware.org/?probe=7974efd1a4) | Jul 03, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [d14f09dc2d](https://linux-hardware.org/?probe=d14f09dc2d) | Jul 03, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [dc682f3aa6](https://linux-hardware.org/?probe=dc682f3aa6) | Jul 02, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [fca2998afc](https://linux-hardware.org/?probe=fca2998afc) | Jul 02, 2021 |
| Sony          | SVE1512C6EB                 | Notebook    | [76ce4f7188](https://linux-hardware.org/?probe=76ce4f7188) | Jul 01, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [0854799759](https://linux-hardware.org/?probe=0854799759) | Jul 01, 2021 |
| Lenovo        | ThinkPad T61 7661V9Z        | Notebook    | [ca7c8358f6](https://linux-hardware.org/?probe=ca7c8358f6) | Jul 01, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [e0e0307e93](https://linux-hardware.org/?probe=e0e0307e93) | Jun 30, 2021 |
| ASUSTek       | X501A                       | Notebook    | [0a17576c5f](https://linux-hardware.org/?probe=0a17576c5f) | Jun 30, 2021 |
| HP            | Notebook                    | Notebook    | [998cae7006](https://linux-hardware.org/?probe=998cae7006) | Jun 30, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [d5ed944b9b](https://linux-hardware.org/?probe=d5ed944b9b) | Jun 29, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [a4a339a28c](https://linux-hardware.org/?probe=a4a339a28c) | Jun 29, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [ad2829b254](https://linux-hardware.org/?probe=ad2829b254) | Jun 29, 2021 |
| Dell          | Inspiron 7773               | Notebook    | [fb0644646a](https://linux-hardware.org/?probe=fb0644646a) | Jun 28, 2021 |
| Dell          | Inspiron 5485               | Notebook    | [6b66b2cf07](https://linux-hardware.org/?probe=6b66b2cf07) | Jun 27, 2021 |
| Dell          | Latitude E6400              | Notebook    | [8d3183f3b8](https://linux-hardware.org/?probe=8d3183f3b8) | Jun 27, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [a505e284ec](https://linux-hardware.org/?probe=a505e284ec) | Jun 27, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1e4e8c8638](https://linux-hardware.org/?probe=1e4e8c8638) | Jun 27, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [6e8a57b8cf](https://linux-hardware.org/?probe=6e8a57b8cf) | Jun 26, 2021 |
| Lenovo        | ThinkStation D20 4158CM1    | Desktop     | [004bd0bb8e](https://linux-hardware.org/?probe=004bd0bb8e) | Jun 26, 2021 |
| HP            | G72                         | Notebook    | [1d1f4771a9](https://linux-hardware.org/?probe=1d1f4771a9) | Jun 26, 2021 |
| Dell          | Latitude E5410              | Notebook    | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c40b02d888](https://linux-hardware.org/?probe=c40b02d888) | Jun 24, 2021 |
| HP            | 0AA8h                       | Desktop     | [8de391044c](https://linux-hardware.org/?probe=8de391044c) | Jun 24, 2021 |
| HP            | 0AA8h                       | Desktop     | [a477bc402f](https://linux-hardware.org/?probe=a477bc402f) | Jun 24, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [f697fb056b](https://linux-hardware.org/?probe=f697fb056b) | Jun 24, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e966d318da](https://linux-hardware.org/?probe=e966d318da) | Jun 23, 2021 |
| Acer          | Aspire 7250                 | Notebook    | [e0311af549](https://linux-hardware.org/?probe=e0311af549) | Jun 23, 2021 |
| Medion        | P17609                      | Notebook    | [663f74686e](https://linux-hardware.org/?probe=663f74686e) | Jun 22, 2021 |
| Medion        | P17609                      | Notebook    | [268469bcbb](https://linux-hardware.org/?probe=268469bcbb) | Jun 22, 2021 |
| MSI           | B350M PRO-VDH               | Desktop     | [c1009474e9](https://linux-hardware.org/?probe=c1009474e9) | Jun 21, 2021 |
| Lenovo        | ThinkPad L412 44034KG       | Notebook    | [5834d217ea](https://linux-hardware.org/?probe=5834d217ea) | Jun 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [d2519fe6fd](https://linux-hardware.org/?probe=d2519fe6fd) | Jun 21, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [e93b924262](https://linux-hardware.org/?probe=e93b924262) | Jun 20, 2021 |
| Lenovo        | ThinkPad X230 23255JU       | Notebook    | [0a92a62b0e](https://linux-hardware.org/?probe=0a92a62b0e) | Jun 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d5ebc8bdc6](https://linux-hardware.org/?probe=d5ebc8bdc6) | Jun 18, 2021 |
| Acer          | Aspire VN7-791              | Notebook    | [ec33c41167](https://linux-hardware.org/?probe=ec33c41167) | Jun 17, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7729db091d](https://linux-hardware.org/?probe=7729db091d) | Jun 17, 2021 |
| Dell          | 0WG855                      | Desktop     | [02b09ef628](https://linux-hardware.org/?probe=02b09ef628) | Jun 17, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [8492ea1603](https://linux-hardware.org/?probe=8492ea1603) | Jun 15, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [fb27aaebe4](https://linux-hardware.org/?probe=fb27aaebe4) | Jun 15, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [79b77baeb0](https://linux-hardware.org/?probe=79b77baeb0) | Jun 15, 2021 |
| MSI           | B350M PRO-VDH               | Desktop     | [b2d3b7546a](https://linux-hardware.org/?probe=b2d3b7546a) | Jun 15, 2021 |
| Gigabyte      | H55M-USB3                   | Desktop     | [3372e4c0ab](https://linux-hardware.org/?probe=3372e4c0ab) | Jun 14, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [bb04e3d7e3](https://linux-hardware.org/?probe=bb04e3d7e3) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [aea22f2fcb](https://linux-hardware.org/?probe=aea22f2fcb) | Jun 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [821204c4fa](https://linux-hardware.org/?probe=821204c4fa) | Jun 13, 2021 |
| HP            | 1589                        | Desktop     | [531fd7a206](https://linux-hardware.org/?probe=531fd7a206) | Jun 12, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [28cc50b8af](https://linux-hardware.org/?probe=28cc50b8af) | Jun 11, 2021 |
| Gigabyte      | H81M-D2W                    | Desktop     | [a5cf29d3fa](https://linux-hardware.org/?probe=a5cf29d3fa) | Jun 11, 2021 |
| Dell          | Latitude 7390               | Notebook    | [38724f6fd8](https://linux-hardware.org/?probe=38724f6fd8) | Jun 11, 2021 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [6b3ad983d3](https://linux-hardware.org/?probe=6b3ad983d3) | Jun 11, 2021 |
| Packard Be... | WMCP78M                     | Desktop     | [c267385b22](https://linux-hardware.org/?probe=c267385b22) | Jun 11, 2021 |
| HP            | Compaq 6730s                | Notebook    | [c2207a656d](https://linux-hardware.org/?probe=c2207a656d) | Jun 10, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [f14555d2b6](https://linux-hardware.org/?probe=f14555d2b6) | Jun 09, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [fb7b10919d](https://linux-hardware.org/?probe=fb7b10919d) | Jun 09, 2021 |
| ASUSTek       | X510UQ                      | Notebook    | [78ae37cf88](https://linux-hardware.org/?probe=78ae37cf88) | Jun 09, 2021 |
| Quanta        | QL3 TBD                     | Notebook    | [bdb6375793](https://linux-hardware.org/?probe=bdb6375793) | Jun 08, 2021 |
| Gigabyte      | 945PL-S3                    | Desktop     | [885dc78ef1](https://linux-hardware.org/?probe=885dc78ef1) | Jun 08, 2021 |
| Gateway       | SX2185                      | Desktop     | [541a86ceb1](https://linux-hardware.org/?probe=541a86ceb1) | Jun 08, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [7dd86b4c8f](https://linux-hardware.org/?probe=7dd86b4c8f) | Jun 07, 2021 |
| Intel         | H61                         | Desktop     | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [91ec4b799a](https://linux-hardware.org/?probe=91ec4b799a) | Jun 07, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [b16595a449](https://linux-hardware.org/?probe=b16595a449) | Jun 07, 2021 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [5319df9212](https://linux-hardware.org/?probe=5319df9212) | Jun 06, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [64d9cfa382](https://linux-hardware.org/?probe=64d9cfa382) | Jun 06, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [b3d1e1b346](https://linux-hardware.org/?probe=b3d1e1b346) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | Notebook    | [44f5d57c9d](https://linux-hardware.org/?probe=44f5d57c9d) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | Notebook    | [47473943ab](https://linux-hardware.org/?probe=47473943ab) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4760acae27](https://linux-hardware.org/?probe=4760acae27) | Jun 06, 2021 |
| Acer          | AOD270                      | Notebook    | [bf1409a0a6](https://linux-hardware.org/?probe=bf1409a0a6) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [94cafae76b](https://linux-hardware.org/?probe=94cafae76b) | Jun 06, 2021 |
| ASUSTek       | X55U                        | Notebook    | [4a44c680de](https://linux-hardware.org/?probe=4a44c680de) | Jun 05, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [216d963387](https://linux-hardware.org/?probe=216d963387) | Jun 05, 2021 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [f9626d011c](https://linux-hardware.org/?probe=f9626d011c) | Jun 05, 2021 |
| HP            | G72                         | Notebook    | [dfae1b630a](https://linux-hardware.org/?probe=dfae1b630a) | Jun 05, 2021 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [4ce3673d2d](https://linux-hardware.org/?probe=4ce3673d2d) | Jun 04, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [8684efd5c9](https://linux-hardware.org/?probe=8684efd5c9) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [6710e0bf1c](https://linux-hardware.org/?probe=6710e0bf1c) | Jun 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5dbe42cf75](https://linux-hardware.org/?probe=5dbe42cf75) | Jun 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [07eb1feeb4](https://linux-hardware.org/?probe=07eb1feeb4) | Jun 03, 2021 |
| HP            | 3032h                       | Desktop     | [dade0cb1d6](https://linux-hardware.org/?probe=dade0cb1d6) | Jun 03, 2021 |
| Packard Be... | IMEDIA S2110A               | Desktop     | [34a921fd71](https://linux-hardware.org/?probe=34a921fd71) | Jun 03, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [56dc35f6b4](https://linux-hardware.org/?probe=56dc35f6b4) | Jun 03, 2021 |
| Lenovo        | ThinkPad T430s 2356H9G      | Notebook    | [1c45dc94ec](https://linux-hardware.org/?probe=1c45dc94ec) | Jun 02, 2021 |
| HP            | 8836                        | Mini pc     | [da34e7c710](https://linux-hardware.org/?probe=da34e7c710) | Jun 02, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7fea036197](https://linux-hardware.org/?probe=7fea036197) | Jun 01, 2021 |
| QTQD          | Unknown                     | Desktop     | [f7d66120da](https://linux-hardware.org/?probe=f7d66120da) | Jun 01, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [5b590117dd](https://linux-hardware.org/?probe=5b590117dd) | Jun 01, 2021 |
| MSI           | B250M PRO-VD                | Desktop     | [c90bb6eca1](https://linux-hardware.org/?probe=c90bb6eca1) | May 31, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e2cabcdb94](https://linux-hardware.org/?probe=e2cabcdb94) | May 31, 2021 |
| Acer          | Aspire E5-772G              | Notebook    | [fdb63cb152](https://linux-hardware.org/?probe=fdb63cb152) | May 31, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [f0d0f92fd9](https://linux-hardware.org/?probe=f0d0f92fd9) | May 31, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [9756ce58fc](https://linux-hardware.org/?probe=9756ce58fc) | May 31, 2021 |
| HP            | 3032h                       | Desktop     | [ea009f77d1](https://linux-hardware.org/?probe=ea009f77d1) | May 31, 2021 |
| NCR           | Pocono                      | Desktop     | [73bfada83a](https://linux-hardware.org/?probe=73bfada83a) | May 30, 2021 |
| Notebook      | N85_87HP6                   | Notebook    | [241e2fc9bd](https://linux-hardware.org/?probe=241e2fc9bd) | May 30, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [f109707413](https://linux-hardware.org/?probe=f109707413) | May 29, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [c323a8132a](https://linux-hardware.org/?probe=c323a8132a) | May 29, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [a9971ed939](https://linux-hardware.org/?probe=a9971ed939) | May 29, 2021 |
| Lenovo        | ThinkPad T470 20HES0FX00    | Notebook    | [5adbf6a949](https://linux-hardware.org/?probe=5adbf6a949) | May 28, 2021 |
| HP            | 158Ch                       | Mini pc     | [15268c0ccc](https://linux-hardware.org/?probe=15268c0ccc) | May 28, 2021 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [ff239ad52e](https://linux-hardware.org/?probe=ff239ad52e) | May 28, 2021 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [756904bec1](https://linux-hardware.org/?probe=756904bec1) | May 27, 2021 |
| HP            | 18E7                        | Desktop     | [dbb0731dd9](https://linux-hardware.org/?probe=dbb0731dd9) | May 27, 2021 |
| Acer          | Aspire E5-573               | Notebook    | [2427d069a8](https://linux-hardware.org/?probe=2427d069a8) | May 27, 2021 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [bfc07a5d3b](https://linux-hardware.org/?probe=bfc07a5d3b) | May 25, 2021 |
| Dell          | Latitude E6330              | Notebook    | [7f740d929f](https://linux-hardware.org/?probe=7f740d929f) | May 25, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [09ca813f06](https://linux-hardware.org/?probe=09ca813f06) | May 25, 2021 |
| ASRock        | H110M-ITX/ac                | Desktop     | [f03f0287f4](https://linux-hardware.org/?probe=f03f0287f4) | May 24, 2021 |
| Apple         | Mac-F2208EC8                | Mini pc     | [9adeb0bd4e](https://linux-hardware.org/?probe=9adeb0bd4e) | May 23, 2021 |
| Dell          | Latitude E6330              | Notebook    | [3dee60820b](https://linux-hardware.org/?probe=3dee60820b) | May 22, 2021 |
| ECS           | H61H2-M2                    | Desktop     | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [d62c1cc4aa](https://linux-hardware.org/?probe=d62c1cc4aa) | May 22, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [b71f289496](https://linux-hardware.org/?probe=b71f289496) | May 22, 2021 |
| Packard Be... | EasyNote NX69HR             | Notebook    | [1e6a01d9bd](https://linux-hardware.org/?probe=1e6a01d9bd) | May 21, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [6b411d236a](https://linux-hardware.org/?probe=6b411d236a) | May 20, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [850cd6457d](https://linux-hardware.org/?probe=850cd6457d) | May 20, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [5e0b431cb8](https://linux-hardware.org/?probe=5e0b431cb8) | May 19, 2021 |
| Schenker      | XMG CORE 14 XCO14L20        | Notebook    | [65baefcf59](https://linux-hardware.org/?probe=65baefcf59) | May 19, 2021 |
| Acer          | H57M01                      | Desktop     | [8b9e2fb5f2](https://linux-hardware.org/?probe=8b9e2fb5f2) | May 19, 2021 |
| Dell          | Latitude E6320              | Notebook    | [b9503f222c](https://linux-hardware.org/?probe=b9503f222c) | May 19, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [a177654d13](https://linux-hardware.org/?probe=a177654d13) | May 19, 2021 |
| Dell          | Precision M6500             | Notebook    | [e56c7ef208](https://linux-hardware.org/?probe=e56c7ef208) | May 18, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [ed8c410826](https://linux-hardware.org/?probe=ed8c410826) | May 18, 2021 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [21bb7408e3](https://linux-hardware.org/?probe=21bb7408e3) | May 18, 2021 |
| Gigabyte      | C847N                       | Desktop     | [7a17d8efef](https://linux-hardware.org/?probe=7a17d8efef) | May 17, 2021 |
| Gigabyte      | C847N                       | Desktop     | [deb3c6a79f](https://linux-hardware.org/?probe=deb3c6a79f) | May 17, 2021 |
| Toshiba       | Satellite L500D             | Notebook    | [959bafa5bd](https://linux-hardware.org/?probe=959bafa5bd) | May 17, 2021 |
| Lenovo        | ThinkPad R61 8934F9U        | Notebook    | [1747f3d32a](https://linux-hardware.org/?probe=1747f3d32a) | May 17, 2021 |
| Acer          | H57M01                      | Desktop     | [a80686767d](https://linux-hardware.org/?probe=a80686767d) | May 16, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [22921fb0b7](https://linux-hardware.org/?probe=22921fb0b7) | May 16, 2021 |
| Intel         | BTC-T37                     | Desktop     | [dcfc697c0a](https://linux-hardware.org/?probe=dcfc697c0a) | May 16, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [0299025f98](https://linux-hardware.org/?probe=0299025f98) | May 15, 2021 |
| Acer          | TPDS05 R3700                | Desktop     | [9abf1ed283](https://linux-hardware.org/?probe=9abf1ed283) | May 15, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [8b2100d9ad](https://linux-hardware.org/?probe=8b2100d9ad) | May 14, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [48f873b6de](https://linux-hardware.org/?probe=48f873b6de) | May 14, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [7b40989bc7](https://linux-hardware.org/?probe=7b40989bc7) | May 13, 2021 |
| HP            | 8836                        | Mini pc     | [ddeee57dbd](https://linux-hardware.org/?probe=ddeee57dbd) | May 13, 2021 |
| Dell          | Latitude E6330              | Notebook    | [11ae9c15ac](https://linux-hardware.org/?probe=11ae9c15ac) | May 13, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [63e4da1d94](https://linux-hardware.org/?probe=63e4da1d94) | May 13, 2021 |
| ASUSTek       | 1215N                       | Notebook    | [2e4383bd79](https://linux-hardware.org/?probe=2e4383bd79) | May 13, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [acff281d6b](https://linux-hardware.org/?probe=acff281d6b) | May 12, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a3f9e2334a](https://linux-hardware.org/?probe=a3f9e2334a) | May 11, 2021 |
| Dell          | 0CU409                      | Desktop     | [151b11acfc](https://linux-hardware.org/?probe=151b11acfc) | May 11, 2021 |
| HP            | 15                          | Notebook    | [85eb4cc12d](https://linux-hardware.org/?probe=85eb4cc12d) | May 11, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [1ddf49c752](https://linux-hardware.org/?probe=1ddf49c752) | May 10, 2021 |
| Dell          | 0CU409                      | Desktop     | [3ea181ca1b](https://linux-hardware.org/?probe=3ea181ca1b) | May 10, 2021 |
| HP            | Compaq 6730s                | Notebook    | [3592dd32d6](https://linux-hardware.org/?probe=3592dd32d6) | May 10, 2021 |
| Packard Be... | AAXSKB-VA                   | All in one  | [a586c561cc](https://linux-hardware.org/?probe=a586c561cc) | May 09, 2021 |
| Medion        | H110H4-CM2                  | Desktop     | [c622bcf1bb](https://linux-hardware.org/?probe=c622bcf1bb) | May 09, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [17e30b0724](https://linux-hardware.org/?probe=17e30b0724) | May 09, 2021 |
| Acer          | H57M01                      | Desktop     | [ec79128c45](https://linux-hardware.org/?probe=ec79128c45) | May 09, 2021 |
| Acer          | Aspire 5740                 | Notebook    | [ed5c778d4f](https://linux-hardware.org/?probe=ed5c778d4f) | May 09, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [75220f50b9](https://linux-hardware.org/?probe=75220f50b9) | May 08, 2021 |
| Toshiba       | Satellite P755              | Notebook    | [aabbaa4370](https://linux-hardware.org/?probe=aabbaa4370) | May 08, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [4c3fc6257c](https://linux-hardware.org/?probe=4c3fc6257c) | May 07, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [eb32404ebf](https://linux-hardware.org/?probe=eb32404ebf) | May 07, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [c8a5492bbe](https://linux-hardware.org/?probe=c8a5492bbe) | May 06, 2021 |
| Lenovo        | ThinkStation D30 4223B35    | Desktop     | [e3c6a7b793](https://linux-hardware.org/?probe=e3c6a7b793) | May 06, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [d03c007deb](https://linux-hardware.org/?probe=d03c007deb) | May 06, 2021 |
| HP            | 2B05                        | Desktop     | [0bfbf859ca](https://linux-hardware.org/?probe=0bfbf859ca) | May 05, 2021 |
| Dell          | Latitude D630               | Notebook    | [bfcc642ec6](https://linux-hardware.org/?probe=bfcc642ec6) | May 05, 2021 |
| Huanan        | X58-RX3.0 V111              | Desktop     | [5181d65714](https://linux-hardware.org/?probe=5181d65714) | May 04, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e1b742d511](https://linux-hardware.org/?probe=e1b742d511) | May 04, 2021 |
| HP            | 198E                        | Desktop     | [396de7f15d](https://linux-hardware.org/?probe=396de7f15d) | May 03, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| Dell          | 02YRK5 A02                  | Desktop     | [0ff2e7f046](https://linux-hardware.org/?probe=0ff2e7f046) | May 02, 2021 |
| MSI           | Z490M-S01                   | Desktop     | [b2de3af507](https://linux-hardware.org/?probe=b2de3af507) | May 02, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [3f22b7b8c7](https://linux-hardware.org/?probe=3f22b7b8c7) | May 02, 2021 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [f22a2df347](https://linux-hardware.org/?probe=f22a2df347) | May 01, 2021 |
| ASUSTek       | X553MA                      | Notebook    | [24844a899b](https://linux-hardware.org/?probe=24844a899b) | Apr 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0deafa542c](https://linux-hardware.org/?probe=0deafa542c) | Apr 29, 2021 |
| ASUSTek       | X553MA                      | Notebook    | [2a6a48781c](https://linux-hardware.org/?probe=2a6a48781c) | Apr 29, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [04d81bb2f6](https://linux-hardware.org/?probe=04d81bb2f6) | Apr 29, 2021 |
| Lenovo        | ZHAOYANG K43c-80 81HX       | Notebook    | [de6628af88](https://linux-hardware.org/?probe=de6628af88) | Apr 27, 2021 |
| HP            | 15                          | Notebook    | [85c3bbf6d2](https://linux-hardware.org/?probe=85c3bbf6d2) | Apr 26, 2021 |
| HP            | 15                          | Notebook    | [8b59240afa](https://linux-hardware.org/?probe=8b59240afa) | Apr 26, 2021 |
| Dell          | Latitude E6540              | Notebook    | [a3f162170c](https://linux-hardware.org/?probe=a3f162170c) | Apr 26, 2021 |
| Acer          | FC51GM                      | Desktop     | [ace5e495f5](https://linux-hardware.org/?probe=ace5e495f5) | Apr 26, 2021 |
| Lenovo        | ThinkPad X230 2320JPU       | Notebook    | [a3fbebddc1](https://linux-hardware.org/?probe=a3fbebddc1) | Apr 26, 2021 |
| HP            | 21B4 A01                    | Desktop     | [9193163279](https://linux-hardware.org/?probe=9193163279) | Apr 26, 2021 |
| Chuwi         | Hi10 plus tablet            | Tablet      | [03f22f7870](https://linux-hardware.org/?probe=03f22f7870) | Apr 25, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [7ecfe05882](https://linux-hardware.org/?probe=7ecfe05882) | Apr 25, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [f6e266a897](https://linux-hardware.org/?probe=f6e266a897) | Apr 25, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [69ec5d246b](https://linux-hardware.org/?probe=69ec5d246b) | Apr 25, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [32aae9ea9a](https://linux-hardware.org/?probe=32aae9ea9a) | Apr 24, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [8f49103dc5](https://linux-hardware.org/?probe=8f49103dc5) | Apr 24, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [fe82c2f357](https://linux-hardware.org/?probe=fe82c2f357) | Apr 23, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [bf61694de7](https://linux-hardware.org/?probe=bf61694de7) | Apr 22, 2021 |
| HP            | 339A                        | Desktop     | [ed44deea1a](https://linux-hardware.org/?probe=ed44deea1a) | Apr 21, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [2517cbf080](https://linux-hardware.org/?probe=2517cbf080) | Apr 20, 2021 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [74f5215b3f](https://linux-hardware.org/?probe=74f5215b3f) | Apr 20, 2021 |
| Lenovo        | B5400 s20278Q               | Notebook    | [48b8cfd930](https://linux-hardware.org/?probe=48b8cfd930) | Apr 20, 2021 |
| ASUSTek       | K52Jr                       | Notebook    | [685e2a3341](https://linux-hardware.org/?probe=685e2a3341) | Apr 20, 2021 |
| MSI           | 770-G45                     | Desktop     | [85ebceeb24](https://linux-hardware.org/?probe=85ebceeb24) | Apr 20, 2021 |
| Dell          | 0M5DCD A02                  | Desktop     | [ef0ddc38ce](https://linux-hardware.org/?probe=ef0ddc38ce) | Apr 19, 2021 |
| Dell          | Vostro V130                 | Notebook    | [36a06dbff2](https://linux-hardware.org/?probe=36a06dbff2) | Apr 19, 2021 |
| HP            | 8836                        | Mini pc     | [e2448e1de1](https://linux-hardware.org/?probe=e2448e1de1) | Apr 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1c4386aedf](https://linux-hardware.org/?probe=1c4386aedf) | Apr 19, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [6e75e7c288](https://linux-hardware.org/?probe=6e75e7c288) | Apr 19, 2021 |
| Dell          | 0KRC95 A03                  | Desktop     | [61da77da82](https://linux-hardware.org/?probe=61da77da82) | Apr 18, 2021 |
| HP            | 3047h                       | Desktop     | [c426bd5393](https://linux-hardware.org/?probe=c426bd5393) | Apr 18, 2021 |
| Acer          | E1-510                      | Notebook    | [d5a5b71d6a](https://linux-hardware.org/?probe=d5a5b71d6a) | Apr 17, 2021 |
| Acer          | Acadia V1.40                | Notebook    | [46bad3ecf2](https://linux-hardware.org/?probe=46bad3ecf2) | Apr 17, 2021 |
| Dell          | Latitude E5440              | Notebook    | [3423e4a8a9](https://linux-hardware.org/?probe=3423e4a8a9) | Apr 17, 2021 |
| Huanan        | X58-RX3.0 V111              | Desktop     | [52841d2dbf](https://linux-hardware.org/?probe=52841d2dbf) | Apr 17, 2021 |
| HP            | ML110 G4                    | Desktop     | [443a299302](https://linux-hardware.org/?probe=443a299302) | Apr 17, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [1797098345](https://linux-hardware.org/?probe=1797098345) | Apr 16, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [bc633becd7](https://linux-hardware.org/?probe=bc633becd7) | Apr 16, 2021 |
| Dell          | 0M5DCD A02                  | Desktop     | [91f1b586b4](https://linux-hardware.org/?probe=91f1b586b4) | Apr 16, 2021 |
| Acer          | TPDS05 R3700                | Desktop     | [4c7b9482f3](https://linux-hardware.org/?probe=4c7b9482f3) | Apr 15, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [0751d8f0d6](https://linux-hardware.org/?probe=0751d8f0d6) | Apr 15, 2021 |
| MSI           | GS63 7RD                    | Notebook    | [0e3e856520](https://linux-hardware.org/?probe=0e3e856520) | Apr 15, 2021 |
| Acer          | E1-510                      | Notebook    | [a831e2fdb1](https://linux-hardware.org/?probe=a831e2fdb1) | Apr 15, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [fa885b5df7](https://linux-hardware.org/?probe=fa885b5df7) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [bfe9ff4cf7](https://linux-hardware.org/?probe=bfe9ff4cf7) | Apr 14, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [e24c5b97f6](https://linux-hardware.org/?probe=e24c5b97f6) | Apr 14, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [87fa4f3888](https://linux-hardware.org/?probe=87fa4f3888) | Apr 13, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [6c2469b32a](https://linux-hardware.org/?probe=6c2469b32a) | Apr 11, 2021 |
| ASUSTek       | N750JK                      | Notebook    | [38117d02be](https://linux-hardware.org/?probe=38117d02be) | Apr 11, 2021 |
| Acer          | Aspire X1430                | Desktop     | [b3b59b7e37](https://linux-hardware.org/?probe=b3b59b7e37) | Apr 11, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [56f187f014](https://linux-hardware.org/?probe=56f187f014) | Apr 11, 2021 |
| ASRock        | H270M-ITX/ac                | Desktop     | [071ce283c1](https://linux-hardware.org/?probe=071ce283c1) | Apr 11, 2021 |
| ASRock        | H270M-ITX/ac                | Desktop     | [73cf10f10a](https://linux-hardware.org/?probe=73cf10f10a) | Apr 11, 2021 |
| ASRock        | B450M/ac                    | Desktop     | [ef79828d94](https://linux-hardware.org/?probe=ef79828d94) | Apr 11, 2021 |
| Dell          | 0GM819                      | Desktop     | [95f4b4a653](https://linux-hardware.org/?probe=95f4b4a653) | Apr 10, 2021 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [2189f9be68](https://linux-hardware.org/?probe=2189f9be68) | Apr 10, 2021 |
| MSI           | GL62M 7REX                  | Notebook    | [8ee2678b38](https://linux-hardware.org/?probe=8ee2678b38) | Apr 10, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [e97c041e12](https://linux-hardware.org/?probe=e97c041e12) | Apr 10, 2021 |
| MSI           | 970A-G43                    | Desktop     | [4618a9eef4](https://linux-hardware.org/?probe=4618a9eef4) | Apr 09, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [cb6c7d5ecb](https://linux-hardware.org/?probe=cb6c7d5ecb) | Apr 09, 2021 |
| ASUSTek       | P5VD2-VM SE                 | Desktop     | [922a324d57](https://linux-hardware.org/?probe=922a324d57) | Apr 09, 2021 |
| HP            | EG157AA-ABF m1260.fr        | Desktop     | [cf4f87aefd](https://linux-hardware.org/?probe=cf4f87aefd) | Apr 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [8b9cd8bac1](https://linux-hardware.org/?probe=8b9cd8bac1) | Apr 07, 2021 |
| ASUSTek       | X302LA                      | Notebook    | [e1432d67a7](https://linux-hardware.org/?probe=e1432d67a7) | Apr 06, 2021 |
| Clevo         | M7x0S                       | Notebook    | [e3cc77148f](https://linux-hardware.org/?probe=e3cc77148f) | Apr 06, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a66003eab5](https://linux-hardware.org/?probe=a66003eab5) | Apr 05, 2021 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [987824d49a](https://linux-hardware.org/?probe=987824d49a) | Apr 05, 2021 |
| Biostar       | TB250-BTC                   | Desktop     | [a1b3b845a7](https://linux-hardware.org/?probe=a1b3b845a7) | Apr 05, 2021 |
| Biostar       | TB250-BTC                   | Desktop     | [908171f266](https://linux-hardware.org/?probe=908171f266) | Apr 05, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [c7f9905fe5](https://linux-hardware.org/?probe=c7f9905fe5) | Apr 05, 2021 |
| Medion        | E7216                       | Notebook    | [df0198f099](https://linux-hardware.org/?probe=df0198f099) | Apr 04, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e15be45763](https://linux-hardware.org/?probe=e15be45763) | Apr 04, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [cb5204d13b](https://linux-hardware.org/?probe=cb5204d13b) | Apr 04, 2021 |
| Lenovo        | ThinkPad R61 8934F9U        | Notebook    | [8e7e380b3b](https://linux-hardware.org/?probe=8e7e380b3b) | Apr 04, 2021 |
| ASUSTek       | B150I PRO GAMING/AURA       | Desktop     | [b33866b71b](https://linux-hardware.org/?probe=b33866b71b) | Apr 03, 2021 |
| Lenovo        | ThinkPad X200T 7453CTO      | Notebook    | [0e029ba8c4](https://linux-hardware.org/?probe=0e029ba8c4) | Apr 03, 2021 |
| Gateway       | NV57H                       | Notebook    | [2474e1aa77](https://linux-hardware.org/?probe=2474e1aa77) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| Lenovo        | ThinkPad W520 4284A95       | Notebook    | [2cc9f7db66](https://linux-hardware.org/?probe=2cc9f7db66) | Apr 03, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [327a4888d5](https://linux-hardware.org/?probe=327a4888d5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [ddda7566c5](https://linux-hardware.org/?probe=ddda7566c5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [5fb915669a](https://linux-hardware.org/?probe=5fb915669a) | Apr 03, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba3e536b64](https://linux-hardware.org/?probe=ba3e536b64) | Apr 02, 2021 |
| Packard Be... | AAXSKB-VA                   | All in one  | [81fd1fec47](https://linux-hardware.org/?probe=81fd1fec47) | Apr 01, 2021 |
| Dell          | Latitude D630               | Notebook    | [3a68abfa65](https://linux-hardware.org/?probe=3a68abfa65) | Mar 31, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [b16cab1e51](https://linux-hardware.org/?probe=b16cab1e51) | Mar 31, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [cb9797346b](https://linux-hardware.org/?probe=cb9797346b) | Mar 30, 2021 |
| Huanan        | X58-RX3.0 V111              | Desktop     | [c18bd3abe8](https://linux-hardware.org/?probe=c18bd3abe8) | Mar 30, 2021 |
| Dell          | Latitude E6430              | Notebook    | [bf705c8135](https://linux-hardware.org/?probe=bf705c8135) | Mar 30, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [1cc1db9dc1](https://linux-hardware.org/?probe=1cc1db9dc1) | Mar 30, 2021 |
| ASRock        | K10N78D                     | Desktop     | [500f4c7c38](https://linux-hardware.org/?probe=500f4c7c38) | Mar 29, 2021 |
| Lenovo        | ThinkPad X200T 7453CTO      | Notebook    | [815692ace4](https://linux-hardware.org/?probe=815692ace4) | Mar 28, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [ef5acde9af](https://linux-hardware.org/?probe=ef5acde9af) | Mar 28, 2021 |
| Dell          | System XPS L502X            | Notebook    | [7986186fbc](https://linux-hardware.org/?probe=7986186fbc) | Mar 28, 2021 |
| eMachines     | EL1850                      | Desktop     | [7c2d95778c](https://linux-hardware.org/?probe=7c2d95778c) | Mar 27, 2021 |
| Acer          | Ferrari IV                  | Notebook    | [60873d0a0e](https://linux-hardware.org/?probe=60873d0a0e) | Mar 27, 2021 |
| Toshiba       | Satellite E45W-C            | Notebook    | [8429536a24](https://linux-hardware.org/?probe=8429536a24) | Mar 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [47323e14e8](https://linux-hardware.org/?probe=47323e14e8) | Mar 26, 2021 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [8ce30ac5a9](https://linux-hardware.org/?probe=8ce30ac5a9) | Mar 26, 2021 |
| Direkt-Tek    | DTLAPY116-1                 | Notebook    | [e6ff85a54d](https://linux-hardware.org/?probe=e6ff85a54d) | Mar 26, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [51a3bc61bb](https://linux-hardware.org/?probe=51a3bc61bb) | Mar 25, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [7aa91d503d](https://linux-hardware.org/?probe=7aa91d503d) | Mar 25, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [15d116776f](https://linux-hardware.org/?probe=15d116776f) | Mar 25, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [f4c0a5e9a8](https://linux-hardware.org/?probe=f4c0a5e9a8) | Mar 25, 2021 |
| Lenovo        | ThinkPad T420 4236GH6       | Notebook    | [102d74838a](https://linux-hardware.org/?probe=102d74838a) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [3d99b46431](https://linux-hardware.org/?probe=3d99b46431) | Mar 25, 2021 |
| HP            | 3646h                       | Desktop     | [b529769ddc](https://linux-hardware.org/?probe=b529769ddc) | Mar 25, 2021 |
| Dell          | Latitude E4300              | Notebook    | [7734046382](https://linux-hardware.org/?probe=7734046382) | Mar 25, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [0d1ffacb54](https://linux-hardware.org/?probe=0d1ffacb54) | Mar 24, 2021 |
| Lenovo        | ThinkPad T495 20NJ0015SP    | Notebook    | [f5ed2fe938](https://linux-hardware.org/?probe=f5ed2fe938) | Mar 23, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [7eb9b157fc](https://linux-hardware.org/?probe=7eb9b157fc) | Mar 23, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [56e94aaad4](https://linux-hardware.org/?probe=56e94aaad4) | Mar 23, 2021 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [ca09a97564](https://linux-hardware.org/?probe=ca09a97564) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire A317-52              | Notebook    | [bb22a21887](https://linux-hardware.org/?probe=bb22a21887) | Mar 22, 2021 |
| Acer          | Aspire A317-52              | Notebook    | [655572af16](https://linux-hardware.org/?probe=655572af16) | Mar 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | Desktop     | [ee93b490f0](https://linux-hardware.org/?probe=ee93b490f0) | Mar 22, 2021 |
| Lenovo        | IdeaPad N585                | Notebook    | [081d063f0a](https://linux-hardware.org/?probe=081d063f0a) | Mar 22, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [070c4000e1](https://linux-hardware.org/?probe=070c4000e1) | Mar 22, 2021 |
| ASUSTek       | ET2013I                     | All in one  | [11466c75b0](https://linux-hardware.org/?probe=11466c75b0) | Mar 21, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [47aef26ec8](https://linux-hardware.org/?probe=47aef26ec8) | Mar 21, 2021 |
| ASUSTek       | X51RL                       | Notebook    | [0451b6db0a](https://linux-hardware.org/?probe=0451b6db0a) | Mar 21, 2021 |
| ASUSTek       | ET2013I                     | All in one  | [37c46dab6e](https://linux-hardware.org/?probe=37c46dab6e) | Mar 20, 2021 |
| ASUSTek       | X553MA                      | Notebook    | [01899b17ca](https://linux-hardware.org/?probe=01899b17ca) | Mar 20, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [06ae75152b](https://linux-hardware.org/?probe=06ae75152b) | Mar 20, 2021 |
| Lenovo        | V560                        | Notebook    | [0f271bca24](https://linux-hardware.org/?probe=0f271bca24) | Mar 20, 2021 |
| Lenovo        | V560                        | Notebook    | [841e4c52d6](https://linux-hardware.org/?probe=841e4c52d6) | Mar 20, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [8a1a88952c](https://linux-hardware.org/?probe=8a1a88952c) | Mar 19, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [deb06f914c](https://linux-hardware.org/?probe=deb06f914c) | Mar 19, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [9c2537edc4](https://linux-hardware.org/?probe=9c2537edc4) | Mar 18, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [0fa936cf65](https://linux-hardware.org/?probe=0fa936cf65) | Mar 18, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [45a9198d77](https://linux-hardware.org/?probe=45a9198d77) | Mar 18, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [946190bdea](https://linux-hardware.org/?probe=946190bdea) | Mar 18, 2021 |
| MSI           | Z97-G43                     | Desktop     | [984145ba36](https://linux-hardware.org/?probe=984145ba36) | Mar 18, 2021 |
| ASRock        | AB350M Pro4 R2.0            | Desktop     | [d5ddb563ac](https://linux-hardware.org/?probe=d5ddb563ac) | Mar 18, 2021 |
| Dell          | 01G5C3 A02                  | Server      | [d4ccc85620](https://linux-hardware.org/?probe=d4ccc85620) | Mar 17, 2021 |
| ASRock        | AB350M Pro4 R2.0            | Desktop     | [af9b948ec2](https://linux-hardware.org/?probe=af9b948ec2) | Mar 17, 2021 |
| Toshiba       | Satellite L775              | Notebook    | [559738d7ef](https://linux-hardware.org/?probe=559738d7ef) | Mar 17, 2021 |
| Intel         | X99                         | Desktop     | [eff3e65d6d](https://linux-hardware.org/?probe=eff3e65d6d) | Mar 17, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [7e50de86dc](https://linux-hardware.org/?probe=7e50de86dc) | Mar 17, 2021 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [0d75059dc8](https://linux-hardware.org/?probe=0d75059dc8) | Mar 17, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7cc0dfac27](https://linux-hardware.org/?probe=7cc0dfac27) | Mar 17, 2021 |
| Intel         | X99                         | Desktop     | [1f84949851](https://linux-hardware.org/?probe=1f84949851) | Mar 17, 2021 |
| Dell          | Latitude 7480               | Notebook    | [149339b634](https://linux-hardware.org/?probe=149339b634) | Mar 17, 2021 |
| MSI           | A88XM-E45                   | Desktop     | [96048dac39](https://linux-hardware.org/?probe=96048dac39) | Mar 17, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [f58f87e21c](https://linux-hardware.org/?probe=f58f87e21c) | Mar 16, 2021 |
| HP            | 2B17                        | Desktop     | [753cbbeb9e](https://linux-hardware.org/?probe=753cbbeb9e) | Mar 16, 2021 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [10c1219043](https://linux-hardware.org/?probe=10c1219043) | Mar 15, 2021 |
| Notebook      | N14xWU                      | Notebook    | [0d11ae6b23](https://linux-hardware.org/?probe=0d11ae6b23) | Mar 15, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3a99165c4b](https://linux-hardware.org/?probe=3a99165c4b) | Mar 15, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [5cfa71c7c9](https://linux-hardware.org/?probe=5cfa71c7c9) | Mar 14, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6e5981a1c8](https://linux-hardware.org/?probe=6e5981a1c8) | Mar 14, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [4a8a3fbe80](https://linux-hardware.org/?probe=4a8a3fbe80) | Mar 14, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [296f4ef1fc](https://linux-hardware.org/?probe=296f4ef1fc) | Mar 14, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [9d9f8210f0](https://linux-hardware.org/?probe=9d9f8210f0) | Mar 14, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| MSI           | GE76 Raider 10UH            | Notebook    | [33402f594e](https://linux-hardware.org/?probe=33402f594e) | Mar 13, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [708eb1bf51](https://linux-hardware.org/?probe=708eb1bf51) | Mar 13, 2021 |
| MSI           | GE76 Raider 10UH            | Notebook    | [791c8ef629](https://linux-hardware.org/?probe=791c8ef629) | Mar 13, 2021 |
| HP            | 339A                        | Desktop     | [355b85c060](https://linux-hardware.org/?probe=355b85c060) | Mar 13, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [c0f324b6aa](https://linux-hardware.org/?probe=c0f324b6aa) | Mar 13, 2021 |
| HP            | 18E7                        | Desktop     | [c0793d8023](https://linux-hardware.org/?probe=c0793d8023) | Mar 13, 2021 |
| HP            | 339A                        | Desktop     | [a24b4dd571](https://linux-hardware.org/?probe=a24b4dd571) | Mar 13, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [d20831473f](https://linux-hardware.org/?probe=d20831473f) | Mar 12, 2021 |
| HP            | 212B                        | Desktop     | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [cc36a18a02](https://linux-hardware.org/?probe=cc36a18a02) | Mar 12, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [5ac5e5625a](https://linux-hardware.org/?probe=5ac5e5625a) | Mar 12, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [c46b3d0202](https://linux-hardware.org/?probe=c46b3d0202) | Mar 11, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ac5ebc37a0](https://linux-hardware.org/?probe=ac5ebc37a0) | Mar 11, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a4da5e59df](https://linux-hardware.org/?probe=a4da5e59df) | Mar 11, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [b69ca67a4f](https://linux-hardware.org/?probe=b69ca67a4f) | Mar 11, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [5f4e258cd5](https://linux-hardware.org/?probe=5f4e258cd5) | Mar 11, 2021 |
| HP            | 15                          | Notebook    | [08233bfc88](https://linux-hardware.org/?probe=08233bfc88) | Mar 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0d5694c1b3](https://linux-hardware.org/?probe=0d5694c1b3) | Mar 10, 2021 |
| ASUSTek       | P5K Premium                 | Desktop     | [868aaae2fd](https://linux-hardware.org/?probe=868aaae2fd) | Mar 09, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [f088cd5cf8](https://linux-hardware.org/?probe=f088cd5cf8) | Mar 08, 2021 |
| HP            | Pavilion 17                 | Notebook    | [4c4d69f2f4](https://linux-hardware.org/?probe=4c4d69f2f4) | Mar 08, 2021 |
| HP            | 21B4 A01                    | Desktop     | [1b6837c321](https://linux-hardware.org/?probe=1b6837c321) | Mar 08, 2021 |
| Toshiba       | TECRA M7                    | Notebook    | [a40f61b08a](https://linux-hardware.org/?probe=a40f61b08a) | Mar 08, 2021 |
| HP            | 339A                        | Desktop     | [dd14e6b8f8](https://linux-hardware.org/?probe=dd14e6b8f8) | Mar 08, 2021 |
| Gigabyte      | 970-GAMING                  | Desktop     | [f05a49c047](https://linux-hardware.org/?probe=f05a49c047) | Mar 08, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [a590a174be](https://linux-hardware.org/?probe=a590a174be) | Mar 07, 2021 |
| ASUSTek       | P5K Premium                 | Desktop     | [551f3363c1](https://linux-hardware.org/?probe=551f3363c1) | Mar 07, 2021 |
| MSI           | MS-1727                     | Notebook    | [cb6654e18b](https://linux-hardware.org/?probe=cb6654e18b) | Mar 06, 2021 |
| Dell          | Latitude E6530              | Notebook    | [141e382738](https://linux-hardware.org/?probe=141e382738) | Mar 06, 2021 |
| HP            | 212B                        | Desktop     | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| HP            | Pavilion 15                 | Notebook    | [bf7c710709](https://linux-hardware.org/?probe=bf7c710709) | Mar 05, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| HP            | Pavilion 15                 | Notebook    | [15bbeb15c3](https://linux-hardware.org/?probe=15bbeb15c3) | Mar 05, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [ff72c4978e](https://linux-hardware.org/?probe=ff72c4978e) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| Dell          | System XPS L502X            | Notebook    | [9b0f41d77e](https://linux-hardware.org/?probe=9b0f41d77e) | Mar 03, 2021 |
| Schenker      | XMG CORE 17(M20, RTX 206... | Notebook    | [18912b688f](https://linux-hardware.org/?probe=18912b688f) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [bfa3a17409](https://linux-hardware.org/?probe=bfa3a17409) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4b9649e87e](https://linux-hardware.org/?probe=4b9649e87e) | Mar 02, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [39f661106f](https://linux-hardware.org/?probe=39f661106f) | Mar 01, 2021 |
| Medion        | WIM2220                     | Notebook    | [7f1eead610](https://linux-hardware.org/?probe=7f1eead610) | Mar 01, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [97a2208e46](https://linux-hardware.org/?probe=97a2208e46) | Feb 28, 2021 |
| Dell          | Latitude E6330              | Notebook    | [64767019e5](https://linux-hardware.org/?probe=64767019e5) | Feb 28, 2021 |
| Unknown       | Intel X79                   | Desktop     | [85e2bda5cc](https://linux-hardware.org/?probe=85e2bda5cc) | Feb 28, 2021 |
| Unknown       | Intel X79                   | Desktop     | [cbe66f456c](https://linux-hardware.org/?probe=cbe66f456c) | Feb 28, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [1d638916dd](https://linux-hardware.org/?probe=1d638916dd) | Feb 27, 2021 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [0f52aff29d](https://linux-hardware.org/?probe=0f52aff29d) | Feb 27, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [9057e2fabf](https://linux-hardware.org/?probe=9057e2fabf) | Feb 27, 2021 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [ba907b59a6](https://linux-hardware.org/?probe=ba907b59a6) | Feb 27, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [3ccc6c99ce](https://linux-hardware.org/?probe=3ccc6c99ce) | Feb 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [27cfc26b43](https://linux-hardware.org/?probe=27cfc26b43) | Feb 26, 2021 |
| Lenovo        | ThinkPad T480 20L5000AFR    | Notebook    | [8b1b96af72](https://linux-hardware.org/?probe=8b1b96af72) | Feb 26, 2021 |
| HP            | ProBook 6465b               | Notebook    | [a046d9bd06](https://linux-hardware.org/?probe=a046d9bd06) | Feb 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ffde1aad10](https://linux-hardware.org/?probe=ffde1aad10) | Feb 25, 2021 |
| Gateway       | LT40                        | Notebook    | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [8912ddde77](https://linux-hardware.org/?probe=8912ddde77) | Feb 23, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [97f3e486f0](https://linux-hardware.org/?probe=97f3e486f0) | Feb 22, 2021 |
| ASUSTek       | K43TK                       | Notebook    | [d004408c66](https://linux-hardware.org/?probe=d004408c66) | Feb 22, 2021 |
| HP            | Compaq 6735b                | Notebook    | [103297afaf](https://linux-hardware.org/?probe=103297afaf) | Feb 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [d4273cb949](https://linux-hardware.org/?probe=d4273cb949) | Feb 22, 2021 |
| ASUSTek       | P5K                         | Desktop     | [26b7e4d025](https://linux-hardware.org/?probe=26b7e4d025) | Feb 22, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [4d9a43cd2c](https://linux-hardware.org/?probe=4d9a43cd2c) | Feb 22, 2021 |
| Dell          | Latitude E6420              | Notebook    | [5c9fa0347d](https://linux-hardware.org/?probe=5c9fa0347d) | Feb 21, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [f61ed1e295](https://linux-hardware.org/?probe=f61ed1e295) | Feb 20, 2021 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [6e9ac2a13d](https://linux-hardware.org/?probe=6e9ac2a13d) | Feb 20, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [3a32460b92](https://linux-hardware.org/?probe=3a32460b92) | Feb 19, 2021 |
| ASUSTek       | A4110                       | Desktop     | [26905e1ebd](https://linux-hardware.org/?probe=26905e1ebd) | Feb 19, 2021 |
| ASUSTek       | 1015PE                      | Notebook    | [16f37f6676](https://linux-hardware.org/?probe=16f37f6676) | Feb 18, 2021 |
| eMachines     | WMCP61M                     | Desktop     | [087382e171](https://linux-hardware.org/?probe=087382e171) | Feb 18, 2021 |
| eMachines     | WMCP61M                     | Desktop     | [a1a77aa715](https://linux-hardware.org/?probe=a1a77aa715) | Feb 18, 2021 |
| Dell          | System XPS L502X            | Notebook    | [c5d51e09ab](https://linux-hardware.org/?probe=c5d51e09ab) | Feb 18, 2021 |
| Toshiba       | TECRA M7                    | Notebook    | [1754c58f4f](https://linux-hardware.org/?probe=1754c58f4f) | Feb 18, 2021 |
| HP            | Pavilion dv2500             | Notebook    | [fd5bd80a7d](https://linux-hardware.org/?probe=fd5bd80a7d) | Feb 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [10ee841597](https://linux-hardware.org/?probe=10ee841597) | Feb 17, 2021 |
| Biostar       | H61MLC                      | Desktop     | [be5a5130e5](https://linux-hardware.org/?probe=be5a5130e5) | Feb 17, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [5d25709db0](https://linux-hardware.org/?probe=5d25709db0) | Feb 17, 2021 |
| HP            | Pavilion dv2500             | Notebook    | [532a81acd0](https://linux-hardware.org/?probe=532a81acd0) | Feb 17, 2021 |
| ASUSTek       | N550JK                      | Notebook    | [9d76fe4c9a](https://linux-hardware.org/?probe=9d76fe4c9a) | Feb 16, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [1d94335b59](https://linux-hardware.org/?probe=1d94335b59) | Feb 16, 2021 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [74f31779a2](https://linux-hardware.org/?probe=74f31779a2) | Feb 15, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [299705d145](https://linux-hardware.org/?probe=299705d145) | Feb 15, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [a8669fea8d](https://linux-hardware.org/?probe=a8669fea8d) | Feb 15, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [8248e0b63a](https://linux-hardware.org/?probe=8248e0b63a) | Feb 14, 2021 |
| Seco          | C40 C                       | Desktop     | [1d98beaf5d](https://linux-hardware.org/?probe=1d98beaf5d) | Feb 14, 2021 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [4679546f16](https://linux-hardware.org/?probe=4679546f16) | Feb 14, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [bd2590461c](https://linux-hardware.org/?probe=bd2590461c) | Feb 13, 2021 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [6ff21c8f17](https://linux-hardware.org/?probe=6ff21c8f17) | Feb 13, 2021 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [2a1ba44e02](https://linux-hardware.org/?probe=2a1ba44e02) | Feb 12, 2021 |
| Gateway       | SX2185                      | Desktop     | [650152fe14](https://linux-hardware.org/?probe=650152fe14) | Feb 12, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [922c8b7dfd](https://linux-hardware.org/?probe=922c8b7dfd) | Feb 11, 2021 |
| Dell          | Latitude D830               | Notebook    | [77e54cbe3e](https://linux-hardware.org/?probe=77e54cbe3e) | Feb 10, 2021 |
| Lenovo        | ThinkPad X201 3680PKG       | Notebook    | [c93bf320d7](https://linux-hardware.org/?probe=c93bf320d7) | Feb 10, 2021 |
| Sony          | VPCEH1AFX                   | Notebook    | [9a652ce0c0](https://linux-hardware.org/?probe=9a652ce0c0) | Feb 10, 2021 |
| HP            | Notebook                    | Notebook    | [e9512b4333](https://linux-hardware.org/?probe=e9512b4333) | Feb 09, 2021 |
| HP            | Notebook                    | Notebook    | [1fa1c10289](https://linux-hardware.org/?probe=1fa1c10289) | Feb 09, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [232dc2ff7f](https://linux-hardware.org/?probe=232dc2ff7f) | Feb 09, 2021 |
| Dell          | Inspiron 5490               | Notebook    | [3644971313](https://linux-hardware.org/?probe=3644971313) | Feb 09, 2021 |
| Lenovo        | ThinkCentre M58 8910B4U     | Desktop     | [1ac9efa4af](https://linux-hardware.org/?probe=1ac9efa4af) | Feb 08, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [c35f0c5e8f](https://linux-hardware.org/?probe=c35f0c5e8f) | Feb 08, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [f4015df0c9](https://linux-hardware.org/?probe=f4015df0c9) | Feb 08, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [d4efd5185b](https://linux-hardware.org/?probe=d4efd5185b) | Feb 08, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [2efcdc0fc3](https://linux-hardware.org/?probe=2efcdc0fc3) | Feb 08, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [5e431277e8](https://linux-hardware.org/?probe=5e431277e8) | Feb 08, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [f487bd28cd](https://linux-hardware.org/?probe=f487bd28cd) | Feb 07, 2021 |
| ASUSTek       | P5G41-M LE                  | Desktop     | [760db7896e](https://linux-hardware.org/?probe=760db7896e) | Feb 07, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [67b240fcfb](https://linux-hardware.org/?probe=67b240fcfb) | Feb 06, 2021 |
| ASUSTek       | K56CM                       | Notebook    | [cdb06fd1e3](https://linux-hardware.org/?probe=cdb06fd1e3) | Feb 06, 2021 |
| ASUSTek       | K56CM                       | Notebook    | [177d8987e5](https://linux-hardware.org/?probe=177d8987e5) | Feb 06, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [75c312983b](https://linux-hardware.org/?probe=75c312983b) | Feb 06, 2021 |
| Sony          | SVF1421E2EW                 | Notebook    | [95111e84c2](https://linux-hardware.org/?probe=95111e84c2) | Feb 06, 2021 |
| Unknown       | Unknown                     | Soc         | [15a8630182](https://linux-hardware.org/?probe=15a8630182) | Feb 06, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [cf78c04cc2](https://linux-hardware.org/?probe=cf78c04cc2) | Feb 06, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [aeb4ab8839](https://linux-hardware.org/?probe=aeb4ab8839) | Feb 06, 2021 |
| Sony          | VGN-AR71S                   | Notebook    | [a5c6539aca](https://linux-hardware.org/?probe=a5c6539aca) | Feb 05, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [b3e301a9ed](https://linux-hardware.org/?probe=b3e301a9ed) | Feb 05, 2021 |
| Jumper        | EZbook                      | Notebook    | [084a3c40f3](https://linux-hardware.org/?probe=084a3c40f3) | Feb 05, 2021 |
| ASUSTek       | P5VD2-MX                    | Desktop     | [f0f594baaf](https://linux-hardware.org/?probe=f0f594baaf) | Feb 04, 2021 |
| ASRock        | HM87-MXM                    | Desktop     | [95efd1e9a2](https://linux-hardware.org/?probe=95efd1e9a2) | Feb 04, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [04273ebc86](https://linux-hardware.org/?probe=04273ebc86) | Feb 04, 2021 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4f4e9cc810](https://linux-hardware.org/?probe=4f4e9cc810) | Feb 04, 2021 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [a3dadb268d](https://linux-hardware.org/?probe=a3dadb268d) | Feb 03, 2021 |
| Lenovo        | ThinkPad X230 2320JPU       | Notebook    | [62582d4d7f](https://linux-hardware.org/?probe=62582d4d7f) | Feb 03, 2021 |
| Lenovo        | ThinkPad X230 2320JPU       | Notebook    | [0ee5585f96](https://linux-hardware.org/?probe=0ee5585f96) | Feb 03, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [61c97edba3](https://linux-hardware.org/?probe=61c97edba3) | Feb 03, 2021 |
| Dell          | System XPS L502X            | Notebook    | [1204db7bcd](https://linux-hardware.org/?probe=1204db7bcd) | Feb 03, 2021 |
| Dell          | System XPS L502X            | Notebook    | [7b564d8b8f](https://linux-hardware.org/?probe=7b564d8b8f) | Feb 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7954ba7fc4](https://linux-hardware.org/?probe=7954ba7fc4) | Feb 02, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [56f886b83b](https://linux-hardware.org/?probe=56f886b83b) | Feb 02, 2021 |
| Acer          | AOD257                      | Notebook    | [6516a78368](https://linux-hardware.org/?probe=6516a78368) | Feb 01, 2021 |
| Acer          | AOD257                      | Notebook    | [f435e31f67](https://linux-hardware.org/?probe=f435e31f67) | Feb 01, 2021 |
| Lenovo        | ThinkPad T510 4484Y1X       | Notebook    | [49bbbfe6d1](https://linux-hardware.org/?probe=49bbbfe6d1) | Feb 01, 2021 |
| HP            | 1589                        | Desktop     | [9f0f12f814](https://linux-hardware.org/?probe=9f0f12f814) | Jan 31, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [ccf18d4e4e](https://linux-hardware.org/?probe=ccf18d4e4e) | Jan 31, 2021 |
| Packard Be... | IMEDIA S3840                | Desktop     | [c0a7dff96d](https://linux-hardware.org/?probe=c0a7dff96d) | Jan 31, 2021 |
| Lenovo        | G500s 20245                 | Notebook    | [68cd2bf232](https://linux-hardware.org/?probe=68cd2bf232) | Jan 31, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [529126337c](https://linux-hardware.org/?probe=529126337c) | Jan 31, 2021 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [bf72f555cb](https://linux-hardware.org/?probe=bf72f555cb) | Jan 31, 2021 |
| Dell          | Latitude D630               | Notebook    | [e4bd287d04](https://linux-hardware.org/?probe=e4bd287d04) | Jan 31, 2021 |
| Dell          | Inspiron 7720               | Notebook    | [557eb8d8f0](https://linux-hardware.org/?probe=557eb8d8f0) | Jan 29, 2021 |
| Dell          | Inspiron 7720               | Notebook    | [6239b8c7b8](https://linux-hardware.org/?probe=6239b8c7b8) | Jan 29, 2021 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [e745405951](https://linux-hardware.org/?probe=e745405951) | Jan 29, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [193f9e8bab](https://linux-hardware.org/?probe=193f9e8bab) | Jan 28, 2021 |
| Samsung       | Q330                        | Notebook    | [0120157b2e](https://linux-hardware.org/?probe=0120157b2e) | Jan 28, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [c0dd8179cd](https://linux-hardware.org/?probe=c0dd8179cd) | Jan 28, 2021 |
| HP            | 18E5                        | Desktop     | [2a72f13e4c](https://linux-hardware.org/?probe=2a72f13e4c) | Jan 27, 2021 |
| HP            | Compaq 15                   | Notebook    | [863dcc43b8](https://linux-hardware.org/?probe=863dcc43b8) | Jan 27, 2021 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [bc5255260e](https://linux-hardware.org/?probe=bc5255260e) | Jan 26, 2021 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [66c8d532cc](https://linux-hardware.org/?probe=66c8d532cc) | Jan 26, 2021 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [068a50df4d](https://linux-hardware.org/?probe=068a50df4d) | Jan 26, 2021 |
| Dell          | Latitude 7490               | Notebook    | [f7dfec504b](https://linux-hardware.org/?probe=f7dfec504b) | Jan 26, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [b78244d995](https://linux-hardware.org/?probe=b78244d995) | Jan 26, 2021 |
| Dell          | Inspiron 7720               | Notebook    | [923d51902b](https://linux-hardware.org/?probe=923d51902b) | Jan 25, 2021 |
| Clevo         | W760T/M740T/M760T           | Notebook    | [4b75664c6f](https://linux-hardware.org/?probe=4b75664c6f) | Jan 25, 2021 |
| NEC Comput... | IS8XM                       | Desktop     | [5ef77bc965](https://linux-hardware.org/?probe=5ef77bc965) | Jan 25, 2021 |
| HP            | Pavilion dv6                | Notebook    | [27d7eb5a92](https://linux-hardware.org/?probe=27d7eb5a92) | Jan 25, 2021 |
| NCR           | Pocono                      | Desktop     | [8bd94573e3](https://linux-hardware.org/?probe=8bd94573e3) | Jan 25, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [2855a371c3](https://linux-hardware.org/?probe=2855a371c3) | Jan 24, 2021 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [27d1050290](https://linux-hardware.org/?probe=27d1050290) | Jan 24, 2021 |
| HP            | 2AFE                        | Desktop     | [f9e753f06a](https://linux-hardware.org/?probe=f9e753f06a) | Jan 23, 2021 |
| MSI           | B85-G43                     | Desktop     | [4955170f6b](https://linux-hardware.org/?probe=4955170f6b) | Jan 23, 2021 |
| Lenovo        | 3718 No DPK                 | All in one  | [bf45cb3ed6](https://linux-hardware.org/?probe=bf45cb3ed6) | Jan 23, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [a16e38020e](https://linux-hardware.org/?probe=a16e38020e) | Jan 23, 2021 |
| Lenovo        | ThinkPad W540 20BG001KGE    | Notebook    | [22b00ab4e5](https://linux-hardware.org/?probe=22b00ab4e5) | Jan 23, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [875db98e08](https://linux-hardware.org/?probe=875db98e08) | Jan 23, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [bf6fd8e5ac](https://linux-hardware.org/?probe=bf6fd8e5ac) | Jan 22, 2021 |
| HP            | Pavilion g7                 | Notebook    | [1e465cca1b](https://linux-hardware.org/?probe=1e465cca1b) | Jan 22, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [2f3b56a94e](https://linux-hardware.org/?probe=2f3b56a94e) | Jan 22, 2021 |
| MSI           | G41TM-E43                   | Desktop     | [2d830938bf](https://linux-hardware.org/?probe=2d830938bf) | Jan 21, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [79ea9e0ea5](https://linux-hardware.org/?probe=79ea9e0ea5) | Jan 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8d943aea44](https://linux-hardware.org/?probe=8d943aea44) | Jan 21, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [ba6a60bdac](https://linux-hardware.org/?probe=ba6a60bdac) | Jan 20, 2021 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [5f6d7de9fe](https://linux-hardware.org/?probe=5f6d7de9fe) | Jan 20, 2021 |
| Dell          | Inspiron 5490               | Notebook    | [9dab1fde54](https://linux-hardware.org/?probe=9dab1fde54) | Jan 20, 2021 |
| Dell          | 033FF6 A00                  | Desktop     | [37d767af07](https://linux-hardware.org/?probe=37d767af07) | Jan 20, 2021 |
| Intel         | DG31GL AAE33912-200         | Desktop     | [14491b53d7](https://linux-hardware.org/?probe=14491b53d7) | Jan 20, 2021 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [cd75d76c4a](https://linux-hardware.org/?probe=cd75d76c4a) | Jan 19, 2021 |
| Dell          | Latitude D430               | Notebook    | [e364de4914](https://linux-hardware.org/?probe=e364de4914) | Jan 19, 2021 |
| Dell          | Latitude D430               | Notebook    | [632ede8190](https://linux-hardware.org/?probe=632ede8190) | Jan 19, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [039ce9b983](https://linux-hardware.org/?probe=039ce9b983) | Jan 19, 2021 |
| HP            | Notebook                    | Notebook    | [5724cfe110](https://linux-hardware.org/?probe=5724cfe110) | Jan 19, 2021 |
| Medion        | WIM2220                     | Notebook    | [ac6c69073e](https://linux-hardware.org/?probe=ac6c69073e) | Jan 17, 2021 |
| Acer          | Aspire 5741                 | Notebook    | [15311207d3](https://linux-hardware.org/?probe=15311207d3) | Jan 17, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [3cbd0f0cda](https://linux-hardware.org/?probe=3cbd0f0cda) | Jan 17, 2021 |
| HP            | 18E5                        | Desktop     | [5af2f3397e](https://linux-hardware.org/?probe=5af2f3397e) | Jan 17, 2021 |
| Intel         | NUC5i5RYB H40999-508        | Mini pc     | [7078c228ee](https://linux-hardware.org/?probe=7078c228ee) | Jan 17, 2021 |
| Samsung       | DP700A3D-A01IT SEC_SW_RE... | All in one  | [738c727e3e](https://linux-hardware.org/?probe=738c727e3e) | Jan 17, 2021 |
| ASL           | Fusion JHS652               | Desktop     | [446053ce45](https://linux-hardware.org/?probe=446053ce45) | Jan 17, 2021 |
| Google        | Zako                        | Desktop     | [dec016baf8](https://linux-hardware.org/?probe=dec016baf8) | Jan 17, 2021 |
| Dell          | 07PR60 A01                  | Desktop     | [c28e9c99eb](https://linux-hardware.org/?probe=c28e9c99eb) | Jan 17, 2021 |
| Dell          | 07PR60 A01                  | Desktop     | [d97f00549e](https://linux-hardware.org/?probe=d97f00549e) | Jan 17, 2021 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [81d37f44c6](https://linux-hardware.org/?probe=81d37f44c6) | Jan 16, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [f9111a7765](https://linux-hardware.org/?probe=f9111a7765) | Jan 16, 2021 |
| HP            | 2129                        | Desktop     | [449a9223a3](https://linux-hardware.org/?probe=449a9223a3) | Jan 15, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [113406e67d](https://linux-hardware.org/?probe=113406e67d) | Jan 15, 2021 |
| Toshiba       | Satellite Pro C660          | Notebook    | [85263df56a](https://linux-hardware.org/?probe=85263df56a) | Jan 14, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [a6c21535b6](https://linux-hardware.org/?probe=a6c21535b6) | Jan 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [80270e2d6e](https://linux-hardware.org/?probe=80270e2d6e) | Jan 13, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| ASUSTek       | BU401LG                     | Notebook    | [38da8474f2](https://linux-hardware.org/?probe=38da8474f2) | Jan 12, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [3ddef39d9e](https://linux-hardware.org/?probe=3ddef39d9e) | Jan 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [33653bbaea](https://linux-hardware.org/?probe=33653bbaea) | Jan 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [71609aabd3](https://linux-hardware.org/?probe=71609aabd3) | Jan 11, 2021 |
| Lenovo        | ThinkPad P52 20M9001GMX     | Notebook    | [ffdee2c6e0](https://linux-hardware.org/?probe=ffdee2c6e0) | Jan 11, 2021 |
| ASRock        | 880GM-LE                    | Desktop     | [21afeee128](https://linux-hardware.org/?probe=21afeee128) | Jan 11, 2021 |
| Dell          | Latitude E6400              | Notebook    | [83d8d95301](https://linux-hardware.org/?probe=83d8d95301) | Jan 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0265add193](https://linux-hardware.org/?probe=0265add193) | Jan 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8b0a9a71b3](https://linux-hardware.org/?probe=8b0a9a71b3) | Jan 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [497bf4005e](https://linux-hardware.org/?probe=497bf4005e) | Jan 10, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [8227f44e5c](https://linux-hardware.org/?probe=8227f44e5c) | Jan 10, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [18722316d8](https://linux-hardware.org/?probe=18722316d8) | Jan 10, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [cc3cbc6c76](https://linux-hardware.org/?probe=cc3cbc6c76) | Jan 10, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [679698e4f1](https://linux-hardware.org/?probe=679698e4f1) | Jan 09, 2021 |
| ASUSTek       | X553MA                      | Notebook    | [a8dacfffee](https://linux-hardware.org/?probe=a8dacfffee) | Jan 09, 2021 |
| Foxconn       | 2A92                        | Desktop     | [88f28ae2bf](https://linux-hardware.org/?probe=88f28ae2bf) | Jan 09, 2021 |
| HP            | 3648h                       | Desktop     | [95ce8ac6d8](https://linux-hardware.org/?probe=95ce8ac6d8) | Jan 09, 2021 |
| Foxconn       | 2A92                        | Desktop     | [4b75fd00b3](https://linux-hardware.org/?probe=4b75fd00b3) | Jan 09, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [e5a628c858](https://linux-hardware.org/?probe=e5a628c858) | Jan 09, 2021 |
| HP            | 2B46                        | Desktop     | [9fc7425e3d](https://linux-hardware.org/?probe=9fc7425e3d) | Jan 09, 2021 |
| Dell          | Latitude E6400              | Notebook    | [a12b8f8f80](https://linux-hardware.org/?probe=a12b8f8f80) | Jan 08, 2021 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | Desktop     | [f09e35f12c](https://linux-hardware.org/?probe=f09e35f12c) | Jan 08, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [0e8be5137f](https://linux-hardware.org/?probe=0e8be5137f) | Jan 08, 2021 |
| ASUSTek       | P5LD2-VM SE                 | Desktop     | [71eec0354c](https://linux-hardware.org/?probe=71eec0354c) | Jan 07, 2021 |
| HP            | 158A                        | Desktop     | [0539eeeeb8](https://linux-hardware.org/?probe=0539eeeeb8) | Jan 07, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [f224060be4](https://linux-hardware.org/?probe=f224060be4) | Jan 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [4a237e25c2](https://linux-hardware.org/?probe=4a237e25c2) | Jan 06, 2021 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [391d558985](https://linux-hardware.org/?probe=391d558985) | Jan 06, 2021 |
| Dell          | 0RY007                      | Desktop     | [91aeb1441d](https://linux-hardware.org/?probe=91aeb1441d) | Jan 05, 2021 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [efea79c15d](https://linux-hardware.org/?probe=efea79c15d) | Jan 05, 2021 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [b90f6eeebf](https://linux-hardware.org/?probe=b90f6eeebf) | Jan 05, 2021 |
| HP            | Pavilion dv6                | Notebook    | [f7f371d643](https://linux-hardware.org/?probe=f7f371d643) | Jan 05, 2021 |
| Dell          | 0X501H A03                  | Desktop     | [64a89d74d6](https://linux-hardware.org/?probe=64a89d74d6) | Jan 05, 2021 |
| Samsung       | 530U3C/530U4C               | Notebook    | [5bc500f949](https://linux-hardware.org/?probe=5bc500f949) | Jan 04, 2021 |
| Acer          | WMCP78M                     | Desktop     | [c5a4dd4ee4](https://linux-hardware.org/?probe=c5a4dd4ee4) | Jan 04, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [d1bdd46e5a](https://linux-hardware.org/?probe=d1bdd46e5a) | Jan 04, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [467cca1579](https://linux-hardware.org/?probe=467cca1579) | Jan 04, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [dbab55b2da](https://linux-hardware.org/?probe=dbab55b2da) | Jan 04, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [49395e2b5a](https://linux-hardware.org/?probe=49395e2b5a) | Jan 04, 2021 |
| Acer          | Extensa 5230                | Notebook    | [4415e4e70d](https://linux-hardware.org/?probe=4415e4e70d) | Jan 04, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [2df37718ac](https://linux-hardware.org/?probe=2df37718ac) | Jan 04, 2021 |
| AMI           | Intel                       | Notebook    | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| HP            | Elite x2 1012 G1 Tablet     | Notebook    | [b0b6d27ef9](https://linux-hardware.org/?probe=b0b6d27ef9) | Jan 03, 2021 |
| HP            | Elite x2 1012 G1 Tablet     | Notebook    | [39fa2bb12d](https://linux-hardware.org/?probe=39fa2bb12d) | Jan 03, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [bb166b2faa](https://linux-hardware.org/?probe=bb166b2faa) | Jan 03, 2021 |
| Unknown       | Intel X79                   | Desktop     | [6184467f17](https://linux-hardware.org/?probe=6184467f17) | Jan 02, 2021 |
| HP            | Pavilion dv7                | Notebook    | [69c177d931](https://linux-hardware.org/?probe=69c177d931) | Jan 02, 2021 |
| HP            | Pavilion dv7                | Notebook    | [35bda93da4](https://linux-hardware.org/?probe=35bda93da4) | Jan 02, 2021 |
| MSI           | P55-CD53                    | Desktop     | [4d4128c3a2](https://linux-hardware.org/?probe=4d4128c3a2) | Jan 01, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [403e79415b](https://linux-hardware.org/?probe=403e79415b) | Jan 01, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [492bf814a7](https://linux-hardware.org/?probe=492bf814a7) | Dec 31, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [120cc88a70](https://linux-hardware.org/?probe=120cc88a70) | Dec 31, 2020 |
| Dell          | 0K83V0 A00                  | Desktop     | [3bcb7a7dc7](https://linux-hardware.org/?probe=3bcb7a7dc7) | Dec 31, 2020 |
| Dell          | 07PR60 A01                  | Desktop     | [de6e7ceac7](https://linux-hardware.org/?probe=de6e7ceac7) | Dec 31, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [db7addea20](https://linux-hardware.org/?probe=db7addea20) | Dec 30, 2020 |
| ASUSTek       | H81M-P                      | Desktop     | [e532649d15](https://linux-hardware.org/?probe=e532649d15) | Dec 30, 2020 |
| HP            | Notebook                    | Notebook    | [638aeddfe5](https://linux-hardware.org/?probe=638aeddfe5) | Dec 29, 2020 |
| Dell          | Inspiron 3541               | Notebook    | [dc6edaf97d](https://linux-hardware.org/?probe=dc6edaf97d) | Dec 29, 2020 |
| Medion        | MS-7728                     | Desktop     | [1c026dd4cb](https://linux-hardware.org/?probe=1c026dd4cb) | Dec 29, 2020 |
| HP            | 2B29                        | Desktop     | [3161742f5a](https://linux-hardware.org/?probe=3161742f5a) | Dec 28, 2020 |
| HP            | EliteBook 745 G6            | Notebook    | [abbb1bd093](https://linux-hardware.org/?probe=abbb1bd093) | Dec 28, 2020 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [e12068dde4](https://linux-hardware.org/?probe=e12068dde4) | Dec 28, 2020 |
| Dell          | Inspiron 7348               | Notebook    | [843004563b](https://linux-hardware.org/?probe=843004563b) | Dec 28, 2020 |
| HP            | Pavilion dv7                | Notebook    | [a076317396](https://linux-hardware.org/?probe=a076317396) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | Notebook    | [fbc4b89320](https://linux-hardware.org/?probe=fbc4b89320) | Dec 28, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [41ce3f2b0a](https://linux-hardware.org/?probe=41ce3f2b0a) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [b5761576fc](https://linux-hardware.org/?probe=b5761576fc) | Dec 27, 2020 |
| MSI           | MS-B1831                    | Desktop     | [8aeb261956](https://linux-hardware.org/?probe=8aeb261956) | Dec 27, 2020 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [567058f9d7](https://linux-hardware.org/?probe=567058f9d7) | Dec 27, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9f886b4496](https://linux-hardware.org/?probe=9f886b4496) | Dec 27, 2020 |
| Clevo         | W35_37ET                    | Notebook    | [7623914c7d](https://linux-hardware.org/?probe=7623914c7d) | Dec 27, 2020 |
| Acer          | Aspire A515-43              | Notebook    | [cdd77b000b](https://linux-hardware.org/?probe=cdd77b000b) | Dec 27, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [96b3895113](https://linux-hardware.org/?probe=96b3895113) | Dec 26, 2020 |
| ASRock        | X570M Pro4                  | Desktop     | [6c57972a71](https://linux-hardware.org/?probe=6c57972a71) | Dec 26, 2020 |
| ASUSTek       | P8P67 LE                    | Desktop     | [627ed8e703](https://linux-hardware.org/?probe=627ed8e703) | Dec 25, 2020 |
| ASUSTek       | M4A88T-M                    | Desktop     | [67714f54b0](https://linux-hardware.org/?probe=67714f54b0) | Dec 25, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [9f73be02e9](https://linux-hardware.org/?probe=9f73be02e9) | Dec 24, 2020 |
| Acer          | Aspire A515-55              | Notebook    | [8dae06d8e5](https://linux-hardware.org/?probe=8dae06d8e5) | Dec 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [b47b8aade9](https://linux-hardware.org/?probe=b47b8aade9) | Dec 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [9c3c5c774e](https://linux-hardware.org/?probe=9c3c5c774e) | Dec 24, 2020 |
| Acer          | Extensa 5235                | Notebook    | [3ddcc1fd9e](https://linux-hardware.org/?probe=3ddcc1fd9e) | Dec 24, 2020 |
| Acer          | Extensa 5235                | Notebook    | [4b5b00203c](https://linux-hardware.org/?probe=4b5b00203c) | Dec 24, 2020 |
| Acer          | Extensa 5235                | Notebook    | [847b5cf2ab](https://linux-hardware.org/?probe=847b5cf2ab) | Dec 24, 2020 |
| MSI           | MS-B1831                    | Desktop     | [2ece565439](https://linux-hardware.org/?probe=2ece565439) | Dec 23, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [084780fb78](https://linux-hardware.org/?probe=084780fb78) | Dec 23, 2020 |
| ECS           | H110M-C3D/C3V               | Desktop     | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| Acer          | Extensa 215-31              | Notebook    | [d3dd4986ae](https://linux-hardware.org/?probe=d3dd4986ae) | Dec 23, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [1a60b18b20](https://linux-hardware.org/?probe=1a60b18b20) | Dec 23, 2020 |
| HP            | 18E4                        | Desktop     | [2c5cdbbd62](https://linux-hardware.org/?probe=2c5cdbbd62) | Dec 23, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [183d05951e](https://linux-hardware.org/?probe=183d05951e) | Dec 22, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [1937524c32](https://linux-hardware.org/?probe=1937524c32) | Dec 22, 2020 |
| HP            | 2B34                        | Desktop     | [e0d288fe64](https://linux-hardware.org/?probe=e0d288fe64) | Dec 22, 2020 |
| HP            | Pavilion dv6                | Notebook    | [5e3b4a96ff](https://linux-hardware.org/?probe=5e3b4a96ff) | Dec 22, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [edd17e8864](https://linux-hardware.org/?probe=edd17e8864) | Dec 22, 2020 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [51114c4b75](https://linux-hardware.org/?probe=51114c4b75) | Dec 22, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [53291d247a](https://linux-hardware.org/?probe=53291d247a) | Dec 21, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | Notebook    | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| ECS           | nForce3-A                   | Desktop     | [0150835d63](https://linux-hardware.org/?probe=0150835d63) | Dec 21, 2020 |
| ECS           | nForce3-A                   | Desktop     | [c08a9c2d3a](https://linux-hardware.org/?probe=c08a9c2d3a) | Dec 21, 2020 |
| Unknown       | mqmaker MiQi                | Desktop     | [7113abee46](https://linux-hardware.org/?probe=7113abee46) | Dec 21, 2020 |
| Dell          | XPS L701X                   | Notebook    | [c730aaa61e](https://linux-hardware.org/?probe=c730aaa61e) | Dec 21, 2020 |
| HP            | 158A                        | Desktop     | [d48f153026](https://linux-hardware.org/?probe=d48f153026) | Dec 21, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7f70318f1](https://linux-hardware.org/?probe=c7f70318f1) | Dec 21, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [03cb85a270](https://linux-hardware.org/?probe=03cb85a270) | Dec 21, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [445ca5b97b](https://linux-hardware.org/?probe=445ca5b97b) | Dec 21, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [e30f78c281](https://linux-hardware.org/?probe=e30f78c281) | Dec 20, 2020 |
| ASUSTek       | M3N78-EMH HDMI              | Desktop     | [72db0d0125](https://linux-hardware.org/?probe=72db0d0125) | Dec 20, 2020 |
| ASUSTek       | M4A88T-M                    | Desktop     | [ee7d610e8e](https://linux-hardware.org/?probe=ee7d610e8e) | Dec 20, 2020 |
| ASUSTek       | P52F                        | Notebook    | [cffa620df7](https://linux-hardware.org/?probe=cffa620df7) | Dec 19, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [a129449d5f](https://linux-hardware.org/?probe=a129449d5f) | Dec 19, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [6c3965a41f](https://linux-hardware.org/?probe=6c3965a41f) | Dec 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ca9265e9b1](https://linux-hardware.org/?probe=ca9265e9b1) | Dec 18, 2020 |
| Gigabyte      | GA-770T-D3L                 | Desktop     | [f819b316d4](https://linux-hardware.org/?probe=f819b316d4) | Dec 17, 2020 |
| Apple         | MacBookPro14,1              | Notebook    | [16916f679a](https://linux-hardware.org/?probe=16916f679a) | Dec 17, 2020 |
| HP            | EliteBook 2540p             | Notebook    | [0a896a3335](https://linux-hardware.org/?probe=0a896a3335) | Dec 17, 2020 |
| HP            | Pavilion dv7                | Notebook    | [efdb11d251](https://linux-hardware.org/?probe=efdb11d251) | Dec 17, 2020 |
| Sony          | VGN-AR41E                   | Notebook    | [52ca609559](https://linux-hardware.org/?probe=52ca609559) | Dec 17, 2020 |
| Sony          | VGN-AR41E                   | Notebook    | [8e8aaf9c2e](https://linux-hardware.org/?probe=8e8aaf9c2e) | Dec 17, 2020 |
| HP            | ZBook 17 G6                 | Notebook    | [d253ffd0f9](https://linux-hardware.org/?probe=d253ffd0f9) | Dec 16, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [d99338778f](https://linux-hardware.org/?probe=d99338778f) | Dec 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [94b7599bed](https://linux-hardware.org/?probe=94b7599bed) | Dec 16, 2020 |
| Acer          | Acadia V1.45                | Notebook    | [f03c43a6cc](https://linux-hardware.org/?probe=f03c43a6cc) | Dec 16, 2020 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8226cd7051](https://linux-hardware.org/?probe=8226cd7051) | Dec 15, 2020 |
| Dell          | Inspiron 7348               | Notebook    | [3f25978672](https://linux-hardware.org/?probe=3f25978672) | Dec 15, 2020 |
| Dell          | Inspiron 7348               | Notebook    | [a83aeea4c8](https://linux-hardware.org/?probe=a83aeea4c8) | Dec 15, 2020 |
| Toshiba       | Satellite T110              | Notebook    | [a6aa049d77](https://linux-hardware.org/?probe=a6aa049d77) | Dec 14, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [c70d8ca3f9](https://linux-hardware.org/?probe=c70d8ca3f9) | Dec 14, 2020 |
| Dell          | Inspiron 5737               | Notebook    | [a91a5b0027](https://linux-hardware.org/?probe=a91a5b0027) | Dec 13, 2020 |
| Dell          | Latitude E5550              | Notebook    | [b515199940](https://linux-hardware.org/?probe=b515199940) | Dec 13, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [fb9204c5ef](https://linux-hardware.org/?probe=fb9204c5ef) | Dec 13, 2020 |
| Sony          | VGN-FZ31M                   | Notebook    | [a66ff4c9f1](https://linux-hardware.org/?probe=a66ff4c9f1) | Dec 13, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [2494a33ba4](https://linux-hardware.org/?probe=2494a33ba4) | Dec 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e5430b607e](https://linux-hardware.org/?probe=e5430b607e) | Dec 13, 2020 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [a9a1ba9727](https://linux-hardware.org/?probe=a9a1ba9727) | Dec 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [5b197971ae](https://linux-hardware.org/?probe=5b197971ae) | Dec 13, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [9e347f10ee](https://linux-hardware.org/?probe=9e347f10ee) | Dec 12, 2020 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [dbfe4f7f45](https://linux-hardware.org/?probe=dbfe4f7f45) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [0b3c20a9d9](https://linux-hardware.org/?probe=0b3c20a9d9) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [1aedfd747c](https://linux-hardware.org/?probe=1aedfd747c) | Dec 12, 2020 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [98d5a20a00](https://linux-hardware.org/?probe=98d5a20a00) | Dec 12, 2020 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [168e6322d7](https://linux-hardware.org/?probe=168e6322d7) | Dec 12, 2020 |
| Medion        | E6228                       | Notebook    | [c9781fc6c2](https://linux-hardware.org/?probe=c9781fc6c2) | Dec 11, 2020 |
| Medion        | E6228                       | Notebook    | [dffd73069b](https://linux-hardware.org/?probe=dffd73069b) | Dec 11, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [5a4110ac7b](https://linux-hardware.org/?probe=5a4110ac7b) | Dec 11, 2020 |
| Apple         | MacBookAir3,2               | Notebook    | [da600a761d](https://linux-hardware.org/?probe=da600a761d) | Dec 10, 2020 |
| HP            | 15                          | Notebook    | [350e3446db](https://linux-hardware.org/?probe=350e3446db) | Dec 10, 2020 |
| Acer          | Aspire 5630                 | Notebook    | [3833d0f90a](https://linux-hardware.org/?probe=3833d0f90a) | Dec 10, 2020 |
| Dell          | Inspiron 1521               | Notebook    | [8c9ebdaf0f](https://linux-hardware.org/?probe=8c9ebdaf0f) | Dec 10, 2020 |
| ASUSTek       | X550MJ                      | Notebook    | [66ed5909f8](https://linux-hardware.org/?probe=66ed5909f8) | Dec 10, 2020 |
| Alienware     | m15 R3                      | Notebook    | [78038bb251](https://linux-hardware.org/?probe=78038bb251) | Dec 09, 2020 |
| ASUSTek       | P2540UA                     | Notebook    | [318bce5e19](https://linux-hardware.org/?probe=318bce5e19) | Dec 09, 2020 |
| Acer          | Aspire 9300                 | Notebook    | [07a152f778](https://linux-hardware.org/?probe=07a152f778) | Dec 08, 2020 |
| Medion        | MS-7728                     | Desktop     | [e1af3f1d3c](https://linux-hardware.org/?probe=e1af3f1d3c) | Dec 08, 2020 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [f9f42752ca](https://linux-hardware.org/?probe=f9f42752ca) | Dec 07, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [8a8d020fab](https://linux-hardware.org/?probe=8a8d020fab) | Dec 07, 2020 |
| Medion        | Akoya S4220 MD99660         | Notebook    | [b07a7e906e](https://linux-hardware.org/?probe=b07a7e906e) | Dec 07, 2020 |
| HP            | 2B29                        | Desktop     | [7a5d8033c4](https://linux-hardware.org/?probe=7a5d8033c4) | Dec 06, 2020 |
| ECS           | G31T-M7                     | Desktop     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| HP            | Pavilion dv7                | Notebook    | [b9d9d59b79](https://linux-hardware.org/?probe=b9d9d59b79) | Dec 04, 2020 |
| Dell          | Latitude E5440              | Notebook    | [c88b8d642b](https://linux-hardware.org/?probe=c88b8d642b) | Dec 04, 2020 |
| Dell          | Latitude E5440              | Notebook    | [4ff22fe0e6](https://linux-hardware.org/?probe=4ff22fe0e6) | Dec 04, 2020 |
| Acer          | Aspire 5630                 | Notebook    | [ce8aa59be7](https://linux-hardware.org/?probe=ce8aa59be7) | Dec 04, 2020 |
| HP            | 2B29                        | Desktop     | [0de16218a6](https://linux-hardware.org/?probe=0de16218a6) | Dec 04, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [6c9e7e4bad](https://linux-hardware.org/?probe=6c9e7e4bad) | Dec 03, 2020 |
| HP            | Pavilion ZV6100 (EK857EA... | Notebook    | [07c5d7ba93](https://linux-hardware.org/?probe=07c5d7ba93) | Dec 03, 2020 |
| HP            | Pavilion 15                 | Notebook    | [ac2be8ed07](https://linux-hardware.org/?probe=ac2be8ed07) | Dec 02, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [caa54ddfda](https://linux-hardware.org/?probe=caa54ddfda) | Dec 02, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [8dc6bd07d9](https://linux-hardware.org/?probe=8dc6bd07d9) | Dec 02, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [368f2012de](https://linux-hardware.org/?probe=368f2012de) | Dec 02, 2020 |
| HP            | 304Ah                       | Desktop     | [e0127b5745](https://linux-hardware.org/?probe=e0127b5745) | Dec 02, 2020 |
| ASUSTek       | STRIX B250G GAMING          | Desktop     | [442ae34c4c](https://linux-hardware.org/?probe=442ae34c4c) | Dec 02, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [ac50d99982](https://linux-hardware.org/?probe=ac50d99982) | Dec 02, 2020 |
| Alienware     | m15 R3                      | Notebook    | [0ead98cec4](https://linux-hardware.org/?probe=0ead98cec4) | Dec 01, 2020 |
| ASRock        | B450M Pro4-F                | Desktop     | [1e395f258f](https://linux-hardware.org/?probe=1e395f258f) | Dec 01, 2020 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [f500a90ee5](https://linux-hardware.org/?probe=f500a90ee5) | Dec 01, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [a03742bc98](https://linux-hardware.org/?probe=a03742bc98) | Dec 01, 2020 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [edda2cb008](https://linux-hardware.org/?probe=edda2cb008) | Dec 01, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [1703cc2678](https://linux-hardware.org/?probe=1703cc2678) | Dec 01, 2020 |
| Medion        | E3216 MD60900               | Convertible | [dd2ec5cd24](https://linux-hardware.org/?probe=dd2ec5cd24) | Nov 30, 2020 |
| Medion        | E6228                       | Notebook    | [ea3b2898fd](https://linux-hardware.org/?probe=ea3b2898fd) | Nov 30, 2020 |
| HP            | ProLiant DL380 G7           | Server      | [a9f0e5dec4](https://linux-hardware.org/?probe=a9f0e5dec4) | Nov 30, 2020 |
| HP            | 2B29                        | Desktop     | [0f5898cf39](https://linux-hardware.org/?probe=0f5898cf39) | Nov 29, 2020 |
| MSI           | MS-7387                     | Desktop     | [c0b3272c7c](https://linux-hardware.org/?probe=c0b3272c7c) | Nov 29, 2020 |
| HP            | ProLiant ML370 G6           | Desktop     | [0c4b40cafd](https://linux-hardware.org/?probe=0c4b40cafd) | Nov 29, 2020 |
| ASRock        | 990FX Extreme4              | Desktop     | [2168e642ab](https://linux-hardware.org/?probe=2168e642ab) | Nov 29, 2020 |
| eMachines     | EL1352                      | Desktop     | [b7646b7bf3](https://linux-hardware.org/?probe=b7646b7bf3) | Nov 29, 2020 |
| HP            | Pavilion ZV6100 (EK857EA... | Notebook    | [93b1f4cfd7](https://linux-hardware.org/?probe=93b1f4cfd7) | Nov 28, 2020 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [5de3c42e69](https://linux-hardware.org/?probe=5de3c42e69) | Nov 28, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [294c2bf2e7](https://linux-hardware.org/?probe=294c2bf2e7) | Nov 28, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [8b7bafb647](https://linux-hardware.org/?probe=8b7bafb647) | Nov 28, 2020 |
| Samsung       | N150P/N210P                 | Notebook    | [0c58a0472f](https://linux-hardware.org/?probe=0c58a0472f) | Nov 28, 2020 |
| Lenovo        | ThinkCentre M58 7360A24     | Desktop     | [44fbb2b2f8](https://linux-hardware.org/?probe=44fbb2b2f8) | Nov 27, 2020 |
| Lenovo        | ThinkCentre M58 7360A24     | Desktop     | [d45b996432](https://linux-hardware.org/?probe=d45b996432) | Nov 27, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [c3ba6d54c1](https://linux-hardware.org/?probe=c3ba6d54c1) | Nov 27, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [2ff8c7a3f8](https://linux-hardware.org/?probe=2ff8c7a3f8) | Nov 26, 2020 |
| Dell          | Latitude 7480               | Notebook    | [550fab0637](https://linux-hardware.org/?probe=550fab0637) | Nov 26, 2020 |
| Notebook      | N150CU                      | Notebook    | [d72b191f9e](https://linux-hardware.org/?probe=d72b191f9e) | Nov 26, 2020 |
| Dell          | 0GXM1W A02                  | Desktop     | [baca597036](https://linux-hardware.org/?probe=baca597036) | Nov 26, 2020 |
| Clevo         | P170HMx                     | Notebook    | [7fb9c2c988](https://linux-hardware.org/?probe=7fb9c2c988) | Nov 26, 2020 |
| HP            | 15                          | Notebook    | [8cae83f5f4](https://linux-hardware.org/?probe=8cae83f5f4) | Nov 26, 2020 |
| Dell          | Vostro 5470                 | Notebook    | [7f0e50a415](https://linux-hardware.org/?probe=7f0e50a415) | Nov 25, 2020 |
| Dell          | 0GXM1W A02                  | Desktop     | [06de0c3923](https://linux-hardware.org/?probe=06de0c3923) | Nov 25, 2020 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [936daa5428](https://linux-hardware.org/?probe=936daa5428) | Nov 25, 2020 |
| Lenovo        | G580 2689NHG                | Notebook    | [98ea230530](https://linux-hardware.org/?probe=98ea230530) | Nov 24, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [2074f71e04](https://linux-hardware.org/?probe=2074f71e04) | Nov 24, 2020 |
| MSI           | GT70                        | Notebook    | [a1b226924c](https://linux-hardware.org/?probe=a1b226924c) | Nov 23, 2020 |
| ASRock        | 990FX Extreme4              | Desktop     | [deffb50091](https://linux-hardware.org/?probe=deffb50091) | Nov 23, 2020 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0ddc71518c](https://linux-hardware.org/?probe=0ddc71518c) | Nov 22, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7e1033e8f3](https://linux-hardware.org/?probe=7e1033e8f3) | Nov 22, 2020 |
| Lenovo        | ThinkPad T400 2765TDG       | Notebook    | [eda69b4a56](https://linux-hardware.org/?probe=eda69b4a56) | Nov 22, 2020 |
| Acer          | Extensa 2519                | Notebook    | [515d8fccc9](https://linux-hardware.org/?probe=515d8fccc9) | Nov 22, 2020 |
| Acer          | Aspire E1-571G              | Notebook    | [49a53faaa4](https://linux-hardware.org/?probe=49a53faaa4) | Nov 22, 2020 |
| ASUSTek       | M4A78L-M                    | Desktop     | [2c715cff4c](https://linux-hardware.org/?probe=2c715cff4c) | Nov 22, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c5b35954b5](https://linux-hardware.org/?probe=c5b35954b5) | Nov 22, 2020 |
| Acer          | Aspire VN7-793G             | Notebook    | [79f11201bc](https://linux-hardware.org/?probe=79f11201bc) | Nov 22, 2020 |
| ASUSTek       | 1215B                       | Notebook    | [ade349b4c4](https://linux-hardware.org/?probe=ade349b4c4) | Nov 22, 2020 |
| ASUSTek       | N752VX                      | Notebook    | [4bd973e49c](https://linux-hardware.org/?probe=4bd973e49c) | Nov 22, 2020 |
| ASUSTek       | M4A77T                      | Desktop     | [8f463afca3](https://linux-hardware.org/?probe=8f463afca3) | Nov 22, 2020 |
| ASUSTek       | M4A77T                      | Desktop     | [8e1b9c4d71](https://linux-hardware.org/?probe=8e1b9c4d71) | Nov 22, 2020 |
| Acer          | Aspire E3-111               | Notebook    | [4d3a6bbf1f](https://linux-hardware.org/?probe=4d3a6bbf1f) | Nov 21, 2020 |
| HP            | Pavilion 15                 | Notebook    | [3ac387736a](https://linux-hardware.org/?probe=3ac387736a) | Nov 21, 2020 |
| ASUSTek       | 1215B                       | Notebook    | [fac0ef4c3c](https://linux-hardware.org/?probe=fac0ef4c3c) | Nov 21, 2020 |
| HP            | Pavilion 15                 | Notebook    | [5fbf0650cf](https://linux-hardware.org/?probe=5fbf0650cf) | Nov 21, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [27460225c6](https://linux-hardware.org/?probe=27460225c6) | Nov 21, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [3c4541bbf8](https://linux-hardware.org/?probe=3c4541bbf8) | Nov 21, 2020 |
| Dell          | Inspiron 5490               | Notebook    | [e07e0b4e45](https://linux-hardware.org/?probe=e07e0b4e45) | Nov 20, 2020 |
| Acer          | Aspire 9300                 | Notebook    | [13f5a3ccc7](https://linux-hardware.org/?probe=13f5a3ccc7) | Nov 20, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [a4d5dd679f](https://linux-hardware.org/?probe=a4d5dd679f) | Nov 20, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [9f67caa394](https://linux-hardware.org/?probe=9f67caa394) | Nov 20, 2020 |
| HP            | 3397                        | Desktop     | [8c4414f5e6](https://linux-hardware.org/?probe=8c4414f5e6) | Nov 20, 2020 |
| Dell          | Latitude E6430              | Notebook    | [a1d7b0f9ab](https://linux-hardware.org/?probe=a1d7b0f9ab) | Nov 20, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [03c7c3bfc7](https://linux-hardware.org/?probe=03c7c3bfc7) | Nov 20, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [d46cf5e259](https://linux-hardware.org/?probe=d46cf5e259) | Nov 20, 2020 |
| ASRock        | Q1900M                      | Desktop     | [2d0b876209](https://linux-hardware.org/?probe=2d0b876209) | Nov 20, 2020 |
| Lenovo        | ThinkPad R61 8935WFB        | Notebook    | [b82d043b71](https://linux-hardware.org/?probe=b82d043b71) | Nov 18, 2020 |
| Toshiba       | Satellite C650D             | Notebook    | [630b2da17a](https://linux-hardware.org/?probe=630b2da17a) | Nov 18, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [90e2e642cf](https://linux-hardware.org/?probe=90e2e642cf) | Nov 18, 2020 |
| Acer          | Aspire E1-532G              | Notebook    | [dd90b2f3e2](https://linux-hardware.org/?probe=dd90b2f3e2) | Nov 18, 2020 |
| HP            | Pavilion 15                 | Notebook    | [853af87cc9](https://linux-hardware.org/?probe=853af87cc9) | Nov 18, 2020 |
| HP            | Pavilion 15                 | Notebook    | [ff48c24c41](https://linux-hardware.org/?probe=ff48c24c41) | Nov 18, 2020 |
| Gigabyte      | G41M-Combo                  | Desktop     | [34ac1118fc](https://linux-hardware.org/?probe=34ac1118fc) | Nov 18, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [f900377694](https://linux-hardware.org/?probe=f900377694) | Nov 18, 2020 |
| ASUSTek       | H81M-P                      | Desktop     | [32ccf4d815](https://linux-hardware.org/?probe=32ccf4d815) | Nov 18, 2020 |
| Gigabyte      | G41M-Combo                  | Desktop     | [43fc3c5473](https://linux-hardware.org/?probe=43fc3c5473) | Nov 17, 2020 |
| Acer          | Aspire 5745                 | Notebook    | [2bcfe42ea3](https://linux-hardware.org/?probe=2bcfe42ea3) | Nov 17, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [1095dc2ac3](https://linux-hardware.org/?probe=1095dc2ac3) | Nov 17, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [303ae16f51](https://linux-hardware.org/?probe=303ae16f51) | Nov 17, 2020 |
| Dell          | 0F6X5P A00                  | Desktop     | [c5ed241b08](https://linux-hardware.org/?probe=c5ed241b08) | Nov 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2cc03df5d0](https://linux-hardware.org/?probe=2cc03df5d0) | Nov 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [a8aff7471b](https://linux-hardware.org/?probe=a8aff7471b) | Nov 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [8a88ea0405](https://linux-hardware.org/?probe=8a88ea0405) | Nov 16, 2020 |
| Acer          | Lugano M                    | Notebook    | [464da49516](https://linux-hardware.org/?probe=464da49516) | Nov 15, 2020 |
| Lenovo        | ThinkPad T530 24292VG       | Notebook    | [3460614c7f](https://linux-hardware.org/?probe=3460614c7f) | Nov 15, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [ac8f81ddbc](https://linux-hardware.org/?probe=ac8f81ddbc) | Nov 15, 2020 |
| Acer          | Aspire 3100                 | Notebook    | [a572cc3368](https://linux-hardware.org/?probe=a572cc3368) | Nov 15, 2020 |
| Dell          | Latitude 5480               | Notebook    | [ed7aa46a28](https://linux-hardware.org/?probe=ed7aa46a28) | Nov 15, 2020 |
| Dell          | Latitude 5480               | Notebook    | [6ac2d1d34a](https://linux-hardware.org/?probe=6ac2d1d34a) | Nov 15, 2020 |
| HP            | 18E5                        | Desktop     | [9da8cd466f](https://linux-hardware.org/?probe=9da8cd466f) | Nov 15, 2020 |
| Fujitsu       | FMVA0803F                   | Notebook    | [c9a2921775](https://linux-hardware.org/?probe=c9a2921775) | Nov 14, 2020 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [be10f2c608](https://linux-hardware.org/?probe=be10f2c608) | Nov 13, 2020 |
| MSI           | Z77A-G45                    | Desktop     | [f3741b744f](https://linux-hardware.org/?probe=f3741b744f) | Nov 13, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [6fe876bc14](https://linux-hardware.org/?probe=6fe876bc14) | Nov 13, 2020 |
| HP            | 8158 A01                    | Mini pc     | [94367a9427](https://linux-hardware.org/?probe=94367a9427) | Nov 13, 2020 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [c79b58ba5b](https://linux-hardware.org/?probe=c79b58ba5b) | Nov 13, 2020 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [52b1f1d052](https://linux-hardware.org/?probe=52b1f1d052) | Nov 12, 2020 |
| ASUSTek       | PRIME X370-A                | Desktop     | [6618ea7285](https://linux-hardware.org/?probe=6618ea7285) | Nov 12, 2020 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [79ba5e5e77](https://linux-hardware.org/?probe=79ba5e5e77) | Nov 11, 2020 |
| Acer          | Ferrari IV                  | Notebook    | [88cfdbff04](https://linux-hardware.org/?probe=88cfdbff04) | Nov 11, 2020 |
| Dynabook      | PORTEGE X30L-G              | Notebook    | [0499612b59](https://linux-hardware.org/?probe=0499612b59) | Nov 10, 2020 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [d5dfd8ab5b](https://linux-hardware.org/?probe=d5dfd8ab5b) | Nov 10, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4b9d9c67b8](https://linux-hardware.org/?probe=4b9d9c67b8) | Nov 09, 2020 |
| HP            | 0A00h                       | Desktop     | [5515bf006a](https://linux-hardware.org/?probe=5515bf006a) | Nov 08, 2020 |
| Medion        | WIM2220                     | Notebook    | [f9bd17f677](https://linux-hardware.org/?probe=f9bd17f677) | Nov 08, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [12f811448a](https://linux-hardware.org/?probe=12f811448a) | Nov 08, 2020 |
| HP            | Notebook                    | Notebook    | [c3d389a569](https://linux-hardware.org/?probe=c3d389a569) | Nov 08, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | Desktop     | [d584773eee](https://linux-hardware.org/?probe=d584773eee) | Nov 08, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [2fd2c8389d](https://linux-hardware.org/?probe=2fd2c8389d) | Nov 08, 2020 |
| Medion        | WIM2220                     | Notebook    | [e1f3023c5f](https://linux-hardware.org/?probe=e1f3023c5f) | Nov 07, 2020 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [58a8f1077b](https://linux-hardware.org/?probe=58a8f1077b) | Nov 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3ecd75648c](https://linux-hardware.org/?probe=3ecd75648c) | Nov 06, 2020 |
| Medion        | MS-7797                     | Desktop     | [7e6563d31c](https://linux-hardware.org/?probe=7e6563d31c) | Nov 06, 2020 |
| Medion        | Akoya S4220 MD99660         | Notebook    | [7f1c16bcda](https://linux-hardware.org/?probe=7f1c16bcda) | Nov 06, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [424e7b661d](https://linux-hardware.org/?probe=424e7b661d) | Nov 06, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [ac6556242f](https://linux-hardware.org/?probe=ac6556242f) | Nov 06, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [56d223bda7](https://linux-hardware.org/?probe=56d223bda7) | Nov 06, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [233cd75348](https://linux-hardware.org/?probe=233cd75348) | Nov 05, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [44061b6a41](https://linux-hardware.org/?probe=44061b6a41) | Nov 05, 2020 |
| ASUSTek       | E203NA                      | Notebook    | [83f3bbfada](https://linux-hardware.org/?probe=83f3bbfada) | Nov 05, 2020 |
| HP            | EliteBook 2760p             | Notebook    | [d1cad27e6f](https://linux-hardware.org/?probe=d1cad27e6f) | Nov 05, 2020 |
| Intel         | H61                         | Desktop     | [071d57e367](https://linux-hardware.org/?probe=071d57e367) | Nov 05, 2020 |
| NEC Comput... | IS8XM                       | Desktop     | [ca22c03b0e](https://linux-hardware.org/?probe=ca22c03b0e) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [c0ad42acb0](https://linux-hardware.org/?probe=c0ad42acb0) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [b5e6f52433](https://linux-hardware.org/?probe=b5e6f52433) | Nov 04, 2020 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [554b898a54](https://linux-hardware.org/?probe=554b898a54) | Nov 04, 2020 |
| ASUSTek       | X205TAW                     | Notebook    | [56c7b66e60](https://linux-hardware.org/?probe=56c7b66e60) | Nov 04, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f27791145e](https://linux-hardware.org/?probe=f27791145e) | Nov 03, 2020 |
| ASRock        | HM87-MXM                    | Desktop     | [d47723e369](https://linux-hardware.org/?probe=d47723e369) | Nov 03, 2020 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [78592ddb24](https://linux-hardware.org/?probe=78592ddb24) | Nov 03, 2020 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [07d94fa2e4](https://linux-hardware.org/?probe=07d94fa2e4) | Nov 03, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [5a8d4603be](https://linux-hardware.org/?probe=5a8d4603be) | Nov 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f17218d86](https://linux-hardware.org/?probe=4f17218d86) | Nov 03, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [d16cbe4e3e](https://linux-hardware.org/?probe=d16cbe4e3e) | Nov 03, 2020 |
| Gigabyte      | X570 UD                     | Desktop     | [607e02b996](https://linux-hardware.org/?probe=607e02b996) | Nov 02, 2020 |
| HP            | 0A58h                       | Desktop     | [796cd4ef09](https://linux-hardware.org/?probe=796cd4ef09) | Nov 02, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [55c65411a0](https://linux-hardware.org/?probe=55c65411a0) | Nov 01, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [9f09e4b2e0](https://linux-hardware.org/?probe=9f09e4b2e0) | Nov 01, 2020 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0c68f62b6e](https://linux-hardware.org/?probe=0c68f62b6e) | Nov 01, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | Notebook    | [51449a174d](https://linux-hardware.org/?probe=51449a174d) | Nov 01, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8e7396c5f2](https://linux-hardware.org/?probe=8e7396c5f2) | Nov 01, 2020 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [e19809dbbb](https://linux-hardware.org/?probe=e19809dbbb) | Oct 31, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [563415fbf4](https://linux-hardware.org/?probe=563415fbf4) | Oct 31, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [57d7a8f5f7](https://linux-hardware.org/?probe=57d7a8f5f7) | Oct 31, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [4497b97240](https://linux-hardware.org/?probe=4497b97240) | Oct 31, 2020 |
| Medion        | Akoya S4220 MD99660         | Notebook    | [bb717a9e21](https://linux-hardware.org/?probe=bb717a9e21) | Oct 31, 2020 |
| HP            | 3397                        | Desktop     | [cf461d2903](https://linux-hardware.org/?probe=cf461d2903) | Oct 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [81dba199eb](https://linux-hardware.org/?probe=81dba199eb) | Oct 31, 2020 |
| ASUSTek       | M4A785-M                    | Desktop     | [af85b28568](https://linux-hardware.org/?probe=af85b28568) | Oct 31, 2020 |
| Notebook      | N13_N140ZU                  | Notebook    | [9994e807e6](https://linux-hardware.org/?probe=9994e807e6) | Oct 30, 2020 |
| ASUSTek       | K56CB                       | Notebook    | [913a11339e](https://linux-hardware.org/?probe=913a11339e) | Oct 30, 2020 |
| HP            | 304Ah                       | Desktop     | [ebc4ca37d5](https://linux-hardware.org/?probe=ebc4ca37d5) | Oct 30, 2020 |
| Dell          | 04GJJT A00                  | Desktop     | [fc31c33025](https://linux-hardware.org/?probe=fc31c33025) | Oct 30, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [b916a2471b](https://linux-hardware.org/?probe=b916a2471b) | Oct 29, 2020 |
| Foxconn       | 2AB1h                       | Desktop     | [dd42a7e94c](https://linux-hardware.org/?probe=dd42a7e94c) | Oct 29, 2020 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b4ce37aee1](https://linux-hardware.org/?probe=b4ce37aee1) | Oct 29, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [121844b238](https://linux-hardware.org/?probe=121844b238) | Oct 28, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [7df4485d80](https://linux-hardware.org/?probe=7df4485d80) | Oct 28, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| Nvidia        | Tegra                       | Soc         | [b07982f83b](https://linux-hardware.org/?probe=b07982f83b) | Oct 27, 2020 |
| Dell          | 0K83V0 A00                  | Desktop     | [caa3f7d5c2](https://linux-hardware.org/?probe=caa3f7d5c2) | Oct 27, 2020 |
| Dell          | 0K83V0 A00                  | Desktop     | [8fc67df632](https://linux-hardware.org/?probe=8fc67df632) | Oct 27, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [f52d2d566a](https://linux-hardware.org/?probe=f52d2d566a) | Oct 27, 2020 |
| Lenovo        | G505s 20255                 | Notebook    | [178a94abbf](https://linux-hardware.org/?probe=178a94abbf) | Oct 26, 2020 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [4a9c6cd2af](https://linux-hardware.org/?probe=4a9c6cd2af) | Oct 26, 2020 |
| HP            | 3397                        | Desktop     | [0c7f93cb53](https://linux-hardware.org/?probe=0c7f93cb53) | Oct 26, 2020 |
| Acer          | Extensa 5230                | Notebook    | [b9b92019bc](https://linux-hardware.org/?probe=b9b92019bc) | Oct 25, 2020 |
| Dell          | 0Y5DDC A00                  | Desktop     | [4a6901b354](https://linux-hardware.org/?probe=4a6901b354) | Oct 25, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [f507c9b3e5](https://linux-hardware.org/?probe=f507c9b3e5) | Oct 25, 2020 |
| Toshiba       | Satellite P50t-B-113        | Notebook    | [6c087ce8ea](https://linux-hardware.org/?probe=6c087ce8ea) | Oct 24, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d1cf725e54](https://linux-hardware.org/?probe=d1cf725e54) | Oct 24, 2020 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [e3920e0ddd](https://linux-hardware.org/?probe=e3920e0ddd) | Oct 24, 2020 |
| Lenovo        | ThinkPad X230 2325TRN       | Notebook    | [4ff5dbb2c4](https://linux-hardware.org/?probe=4ff5dbb2c4) | Oct 23, 2020 |
| Acer          | Aspire 5733Z                | Notebook    | [3ac448e0a6](https://linux-hardware.org/?probe=3ac448e0a6) | Oct 23, 2020 |
| Dell          | 0X9M3X A03                  | Desktop     | [0fbdc774f7](https://linux-hardware.org/?probe=0fbdc774f7) | Oct 23, 2020 |
| Dell          | Vostro 3350                 | Notebook    | [88e849444f](https://linux-hardware.org/?probe=88e849444f) | Oct 22, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [e8b5a5c6c1](https://linux-hardware.org/?probe=e8b5a5c6c1) | Oct 22, 2020 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [89eeb34dbc](https://linux-hardware.org/?probe=89eeb34dbc) | Oct 22, 2020 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [bdee704ce9](https://linux-hardware.org/?probe=bdee704ce9) | Oct 22, 2020 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [e9eab6369f](https://linux-hardware.org/?probe=e9eab6369f) | Oct 22, 2020 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [ee3c78e7f9](https://linux-hardware.org/?probe=ee3c78e7f9) | Oct 22, 2020 |
| HP            | 18E7                        | Desktop     | [9b75d72659](https://linux-hardware.org/?probe=9b75d72659) | Oct 21, 2020 |
| Lenovo        | ThinkPad X220 42919L5       | Notebook    | [730e9b72a8](https://linux-hardware.org/?probe=730e9b72a8) | Oct 21, 2020 |
| MSI           | B85M-E45                    | Desktop     | [7d562c5a0b](https://linux-hardware.org/?probe=7d562c5a0b) | Oct 21, 2020 |
| HP            | 1589                        | Desktop     | [97e2a8328c](https://linux-hardware.org/?probe=97e2a8328c) | Oct 21, 2020 |
| HP            | 1589                        | Desktop     | [c01a481fe5](https://linux-hardware.org/?probe=c01a481fe5) | Oct 21, 2020 |
| HP            | ProLiant DL360p Gen8        | Server      | [12d0d76c15](https://linux-hardware.org/?probe=12d0d76c15) | Oct 20, 2020 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [6542fc1f81](https://linux-hardware.org/?probe=6542fc1f81) | Oct 20, 2020 |
| sunxi         | Banana Pi BPI-M1-Plus       | Soc         | [4bf63ad755](https://linux-hardware.org/?probe=4bf63ad755) | Oct 20, 2020 |
| ASUSTek       | N552VW                      | Notebook    | [6893d4927d](https://linux-hardware.org/?probe=6893d4927d) | Oct 20, 2020 |
| Acer          | Aspire A515-55              | Notebook    | [aea22ab01a](https://linux-hardware.org/?probe=aea22ab01a) | Oct 20, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [cc871fe1eb](https://linux-hardware.org/?probe=cc871fe1eb) | Oct 20, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [039517f9b1](https://linux-hardware.org/?probe=039517f9b1) | Oct 19, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8892c91b74](https://linux-hardware.org/?probe=8892c91b74) | Oct 19, 2020 |
| MouseCompu... | NG-N-i5730                  | Notebook    | [7748ae5522](https://linux-hardware.org/?probe=7748ae5522) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [2c05125698](https://linux-hardware.org/?probe=2c05125698) | Oct 19, 2020 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [72afc70aea](https://linux-hardware.org/?probe=72afc70aea) | Oct 19, 2020 |
| ASUSTek       | X550EA                      | Notebook    | [27074cf7ae](https://linux-hardware.org/?probe=27074cf7ae) | Oct 18, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [fe557d9bf0](https://linux-hardware.org/?probe=fe557d9bf0) | Oct 18, 2020 |
| Intel         | DH67CF AAG10215-207         | Desktop     | [bdad9ec53e](https://linux-hardware.org/?probe=bdad9ec53e) | Oct 18, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [9e5b81cf31](https://linux-hardware.org/?probe=9e5b81cf31) | Oct 17, 2020 |
| HP            | 82F2 A01                    | Desktop     | [9f775578b2](https://linux-hardware.org/?probe=9f775578b2) | Oct 17, 2020 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [05d6ef0ede](https://linux-hardware.org/?probe=05d6ef0ede) | Oct 17, 2020 |
| Lenovo        | ThinkPad 10 20C10024GE      | Tablet      | [1d6f4c02a1](https://linux-hardware.org/?probe=1d6f4c02a1) | Oct 17, 2020 |
| Lenovo        | ThinkPad 10 20C10024GE      | Tablet      | [d87741381c](https://linux-hardware.org/?probe=d87741381c) | Oct 17, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [877be0d702](https://linux-hardware.org/?probe=877be0d702) | Oct 16, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [10afcab1dd](https://linux-hardware.org/?probe=10afcab1dd) | Oct 16, 2020 |
| Lenovo        | ThinkPad W540 20BG001KGE    | Notebook    | [f7a51ece15](https://linux-hardware.org/?probe=f7a51ece15) | Oct 16, 2020 |
| HP            | 655                         | Notebook    | [8d521629e4](https://linux-hardware.org/?probe=8d521629e4) | Oct 16, 2020 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [4c66a9acab](https://linux-hardware.org/?probe=4c66a9acab) | Oct 16, 2020 |
| Positivo      | Mobile                      | Notebook    | [211c5d812f](https://linux-hardware.org/?probe=211c5d812f) | Oct 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cacf226be4](https://linux-hardware.org/?probe=cacf226be4) | Oct 16, 2020 |
| HP            | 3397                        | Desktop     | [33fdc768a1](https://linux-hardware.org/?probe=33fdc768a1) | Oct 15, 2020 |
| ASRock        | 970 Extreme4                | Desktop     | [da013f2159](https://linux-hardware.org/?probe=da013f2159) | Oct 15, 2020 |
| Dynabook      | PORTEGE X30L-G              | Notebook    | [00ad2832f0](https://linux-hardware.org/?probe=00ad2832f0) | Oct 15, 2020 |
| HP            | Pavilion 15                 | Notebook    | [ded3ec96e6](https://linux-hardware.org/?probe=ded3ec96e6) | Oct 15, 2020 |
| HP            | Pavilion dv6                | Notebook    | [aa66ea4d86](https://linux-hardware.org/?probe=aa66ea4d86) | Oct 15, 2020 |
| Hardkernel    | ODROID-C2                   | Soc         | [08ef6e888c](https://linux-hardware.org/?probe=08ef6e888c) | Oct 15, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [753273ae7d](https://linux-hardware.org/?probe=753273ae7d) | Oct 14, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [aea7dc9a63](https://linux-hardware.org/?probe=aea7dc9a63) | Oct 14, 2020 |
| Positivo      | Mobile                      | Notebook    | [bcbe9b6892](https://linux-hardware.org/?probe=bcbe9b6892) | Oct 14, 2020 |
| ASRock        | 990FX Professional          | Desktop     | [97ce7ab2bc](https://linux-hardware.org/?probe=97ce7ab2bc) | Oct 12, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b12687c62b](https://linux-hardware.org/?probe=b12687c62b) | Oct 12, 2020 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [ec63552e89](https://linux-hardware.org/?probe=ec63552e89) | Oct 11, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [6694a38429](https://linux-hardware.org/?probe=6694a38429) | Oct 11, 2020 |
| OEGStone      | C4100/C5100                 | Notebook    | [b3a5e6dbc7](https://linux-hardware.org/?probe=b3a5e6dbc7) | Oct 11, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [964d90f42f](https://linux-hardware.org/?probe=964d90f42f) | Oct 11, 2020 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [847655cb40](https://linux-hardware.org/?probe=847655cb40) | Oct 10, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [6427fb47dd](https://linux-hardware.org/?probe=6427fb47dd) | Oct 10, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [57c0796f7d](https://linux-hardware.org/?probe=57c0796f7d) | Oct 10, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [ac0d496c41](https://linux-hardware.org/?probe=ac0d496c41) | Oct 10, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [1c591aa639](https://linux-hardware.org/?probe=1c591aa639) | Oct 10, 2020 |
| HP            | ENVY m7 Notebook            | Notebook    | [c3d45b395f](https://linux-hardware.org/?probe=c3d45b395f) | Oct 10, 2020 |
| HP            | 1495                        | Desktop     | [95e7609af2](https://linux-hardware.org/?probe=95e7609af2) | Oct 10, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [19ef25af06](https://linux-hardware.org/?probe=19ef25af06) | Oct 09, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [44119852e3](https://linux-hardware.org/?probe=44119852e3) | Oct 09, 2020 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3712afebf5](https://linux-hardware.org/?probe=3712afebf5) | Oct 09, 2020 |
| Apple         | MacBookPro6,2               | Notebook    | [90be6b4795](https://linux-hardware.org/?probe=90be6b4795) | Oct 09, 2020 |
| HP            | 304Ah                       | Desktop     | [c05b24bee0](https://linux-hardware.org/?probe=c05b24bee0) | Oct 09, 2020 |
| ASUSTek       | K53E                        | Notebook    | [57d6280b99](https://linux-hardware.org/?probe=57d6280b99) | Oct 09, 2020 |
| HP            | Compaq 6510b                | Notebook    | [cf190a85ea](https://linux-hardware.org/?probe=cf190a85ea) | Oct 08, 2020 |
| HP            | 0A64h                       | Desktop     | [83fa351a56](https://linux-hardware.org/?probe=83fa351a56) | Oct 07, 2020 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [6a427182ad](https://linux-hardware.org/?probe=6a427182ad) | Oct 07, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [b65be0bf44](https://linux-hardware.org/?probe=b65be0bf44) | Oct 07, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| MSI           | 970A-G46                    | Desktop     | [299e4a7770](https://linux-hardware.org/?probe=299e4a7770) | Oct 07, 2020 |
| HP            | Notebook                    | Notebook    | [5152b94329](https://linux-hardware.org/?probe=5152b94329) | Oct 07, 2020 |
| HP            | G72                         | Notebook    | [9ffd6f9800](https://linux-hardware.org/?probe=9ffd6f9800) | Oct 06, 2020 |
| Dell          | Latitude E6330              | Notebook    | [3eeb1d435a](https://linux-hardware.org/?probe=3eeb1d435a) | Oct 06, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [37ee142080](https://linux-hardware.org/?probe=37ee142080) | Oct 05, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [36889b5833](https://linux-hardware.org/?probe=36889b5833) | Oct 05, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [56667ca59e](https://linux-hardware.org/?probe=56667ca59e) | Oct 05, 2020 |
| Gigabyte      | P55M-UD2                    | Desktop     | [cf07ea3801](https://linux-hardware.org/?probe=cf07ea3801) | Oct 05, 2020 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [2d6256e8c5](https://linux-hardware.org/?probe=2d6256e8c5) | Oct 05, 2020 |
| Supermicro    | X11SPL-F                    | Server      | [4d0ed95e02](https://linux-hardware.org/?probe=4d0ed95e02) | Oct 05, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [a88be898c1](https://linux-hardware.org/?probe=a88be898c1) | Oct 05, 2020 |
| Toshiba       | STI NA 1402                 | Notebook    | [563e501126](https://linux-hardware.org/?probe=563e501126) | Oct 05, 2020 |
| MSI           | MEG X570 ACE                | Desktop     | [707d8920a5](https://linux-hardware.org/?probe=707d8920a5) | Oct 04, 2020 |
| HP            | 0A64h                       | Desktop     | [212a85da51](https://linux-hardware.org/?probe=212a85da51) | Oct 04, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | Notebook    | [bea20b3463](https://linux-hardware.org/?probe=bea20b3463) | Oct 04, 2020 |
| Dell          | 0TP406                      | Desktop     | [b9e8cd1651](https://linux-hardware.org/?probe=b9e8cd1651) | Oct 04, 2020 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [8174433592](https://linux-hardware.org/?probe=8174433592) | Oct 04, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [55c36c93a4](https://linux-hardware.org/?probe=55c36c93a4) | Oct 03, 2020 |
| HP            | G62                         | Notebook    | [549f82b3ab](https://linux-hardware.org/?probe=549f82b3ab) | Oct 03, 2020 |
| HP            | G62                         | Notebook    | [d5f754a79b](https://linux-hardware.org/?probe=d5f754a79b) | Oct 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3c907dd84e](https://linux-hardware.org/?probe=3c907dd84e) | Oct 03, 2020 |
| Toshiba       | STI NA 1402                 | Notebook    | [06bd99a96d](https://linux-hardware.org/?probe=06bd99a96d) | Oct 03, 2020 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [8d23390737](https://linux-hardware.org/?probe=8d23390737) | Oct 03, 2020 |
| Dell          | 0F0XJ6 A11                  | Server      | [ba4ffbda6d](https://linux-hardware.org/?probe=ba4ffbda6d) | Oct 03, 2020 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [b1aeaa645b](https://linux-hardware.org/?probe=b1aeaa645b) | Oct 03, 2020 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [45bfa5eb3c](https://linux-hardware.org/?probe=45bfa5eb3c) | Oct 03, 2020 |
| HP            | 82F2 A01                    | Desktop     | [624aa6976f](https://linux-hardware.org/?probe=624aa6976f) | Oct 02, 2020 |
| Dell          | 0PU052                      | Desktop     | [e2e65a1fa7](https://linux-hardware.org/?probe=e2e65a1fa7) | Oct 02, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [b82b064a51](https://linux-hardware.org/?probe=b82b064a51) | Oct 02, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| ASUSTek       | P5K                         | Desktop     | [c1c290f102](https://linux-hardware.org/?probe=c1c290f102) | Oct 02, 2020 |
| HP            | Pavilion g6                 | Notebook    | [877d5394f3](https://linux-hardware.org/?probe=877d5394f3) | Oct 02, 2020 |
| Dell          | 0M863N A00                  | Desktop     | [4ffc77e348](https://linux-hardware.org/?probe=4ffc77e348) | Oct 02, 2020 |
| Dell          | 0M863N A00                  | Desktop     | [3719f7c699](https://linux-hardware.org/?probe=3719f7c699) | Oct 02, 2020 |
| Sony          | VGN-AW11M_H                 | Notebook    | [93eb90689f](https://linux-hardware.org/?probe=93eb90689f) | Oct 02, 2020 |
| ASUSTek       | Z87-A                       | Desktop     | [63e9e30049](https://linux-hardware.org/?probe=63e9e30049) | Oct 02, 2020 |
| Intel         | DG41TX AAE78178-303         | Desktop     | [2ba4c11c35](https://linux-hardware.org/?probe=2ba4c11c35) | Oct 02, 2020 |
| Dell          | 0WR7PY A02                  | Desktop     | [44ffa409aa](https://linux-hardware.org/?probe=44ffa409aa) | Oct 01, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [07387013eb](https://linux-hardware.org/?probe=07387013eb) | Sep 30, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [2d569d7877](https://linux-hardware.org/?probe=2d569d7877) | Sep 30, 2020 |
| HP            | Pavilion dv6                | Notebook    | [e579b3a47a](https://linux-hardware.org/?probe=e579b3a47a) | Sep 30, 2020 |
| ASUSTek       | K53E                        | Notebook    | [57b9033911](https://linux-hardware.org/?probe=57b9033911) | Sep 30, 2020 |
| HP            | 1495                        | Desktop     | [0b848e88ef](https://linux-hardware.org/?probe=0b848e88ef) | Sep 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [cfb285ef78](https://linux-hardware.org/?probe=cfb285ef78) | Sep 29, 2020 |
| Schenker      | VIA_14_SVI14E20             | Notebook    | [431de74e18](https://linux-hardware.org/?probe=431de74e18) | Sep 29, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0f6dc81b18](https://linux-hardware.org/?probe=0f6dc81b18) | Sep 29, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [601b9c7dcf](https://linux-hardware.org/?probe=601b9c7dcf) | Sep 29, 2020 |
| HP            | Pavilion tx1000             | Notebook    | [45aaad469b](https://linux-hardware.org/?probe=45aaad469b) | Sep 29, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [97d6fcdf95](https://linux-hardware.org/?probe=97d6fcdf95) | Sep 28, 2020 |
| Acer          | Aspire SW3-013              | Notebook    | [40c00a9cd5](https://linux-hardware.org/?probe=40c00a9cd5) | Sep 27, 2020 |
| Acer          | Aspire SW3-013              | Notebook    | [2f3245e837](https://linux-hardware.org/?probe=2f3245e837) | Sep 27, 2020 |
| Acer          | Aspire SW3-013              | Notebook    | [271ab121ee](https://linux-hardware.org/?probe=271ab121ee) | Sep 27, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [d42399006f](https://linux-hardware.org/?probe=d42399006f) | Sep 27, 2020 |
| ASUSTek       | K53E                        | Notebook    | [04740b7dad](https://linux-hardware.org/?probe=04740b7dad) | Sep 26, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [853e25d0f9](https://linux-hardware.org/?probe=853e25d0f9) | Sep 26, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [30a2037cce](https://linux-hardware.org/?probe=30a2037cce) | Sep 26, 2020 |
| Intel         | H61                         | Desktop     | [0ddeefc2fc](https://linux-hardware.org/?probe=0ddeefc2fc) | Sep 26, 2020 |
| HP            | 0AA8h                       | Desktop     | [244549772f](https://linux-hardware.org/?probe=244549772f) | Sep 25, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [cb3c08ee24](https://linux-hardware.org/?probe=cb3c08ee24) | Sep 25, 2020 |
| Intel         | H61                         | Desktop     | [87b485d42f](https://linux-hardware.org/?probe=87b485d42f) | Sep 25, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [175875ac7b](https://linux-hardware.org/?probe=175875ac7b) | Sep 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a6630164b8](https://linux-hardware.org/?probe=a6630164b8) | Sep 25, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [052bf49b84](https://linux-hardware.org/?probe=052bf49b84) | Sep 25, 2020 |
| Itautec       | W7655                       | Notebook    | [5878935978](https://linux-hardware.org/?probe=5878935978) | Sep 25, 2020 |
| HP            | 0AA8h                       | Desktop     | [80cbff87bd](https://linux-hardware.org/?probe=80cbff87bd) | Sep 24, 2020 |
| Acer          | Extensa 5630                | Notebook    | [c405a4cab9](https://linux-hardware.org/?probe=c405a4cab9) | Sep 24, 2020 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [918e747daf](https://linux-hardware.org/?probe=918e747daf) | Sep 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c52887d7df](https://linux-hardware.org/?probe=c52887d7df) | Sep 24, 2020 |
| Dell          | 02K9CR A01                  | Desktop     | [c2e31c7ce8](https://linux-hardware.org/?probe=c2e31c7ce8) | Sep 24, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [6e5da39670](https://linux-hardware.org/?probe=6e5da39670) | Sep 24, 2020 |
| Positivo      | POS-AG31AP                  | Desktop     | [9dc1ba771f](https://linux-hardware.org/?probe=9dc1ba771f) | Sep 23, 2020 |
| Dell          | 0F6X5P A00                  | Desktop     | [a1cbd8f918](https://linux-hardware.org/?probe=a1cbd8f918) | Sep 23, 2020 |
| Notebook      | W65_67SJ                    | Notebook    | [da03090968](https://linux-hardware.org/?probe=da03090968) | Sep 23, 2020 |
| Lenovo        | S206                        | Notebook    | [b4d2c25f69](https://linux-hardware.org/?probe=b4d2c25f69) | Sep 22, 2020 |
| ASUSTek       | N752VX                      | Notebook    | [357b0ba973](https://linux-hardware.org/?probe=357b0ba973) | Sep 22, 2020 |
| Dell          | 0X501H A03                  | Desktop     | [ebeee4544c](https://linux-hardware.org/?probe=ebeee4544c) | Sep 22, 2020 |
| HP            | Compaq 6510b                | Notebook    | [9b9a4b4614](https://linux-hardware.org/?probe=9b9a4b4614) | Sep 22, 2020 |
| Dell          | 0F6X5P A00                  | Desktop     | [0b548f3a3f](https://linux-hardware.org/?probe=0b548f3a3f) | Sep 22, 2020 |
| Dell          | XPS L701X                   | Notebook    | [e825e50fce](https://linux-hardware.org/?probe=e825e50fce) | Sep 21, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e66100f134](https://linux-hardware.org/?probe=e66100f134) | Sep 21, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [f0cc956336](https://linux-hardware.org/?probe=f0cc956336) | Sep 21, 2020 |
| Dell          | Latitude E4300              | Notebook    | [b80743fa09](https://linux-hardware.org/?probe=b80743fa09) | Sep 21, 2020 |
| Dell          | 0X501H A03                  | Desktop     | [4a8ba3857a](https://linux-hardware.org/?probe=4a8ba3857a) | Sep 21, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [3feb39014a](https://linux-hardware.org/?probe=3feb39014a) | Sep 20, 2020 |
| Acer          | Aspire X3400G               | Desktop     | [80fdbf7a1b](https://linux-hardware.org/?probe=80fdbf7a1b) | Sep 20, 2020 |
| ASUSTek       | F5VL                        | Notebook    | [f385221573](https://linux-hardware.org/?probe=f385221573) | Sep 20, 2020 |
| HP            | ProBook 4540s               | Notebook    | [9423eb5acb](https://linux-hardware.org/?probe=9423eb5acb) | Sep 20, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9bb6aefa2c](https://linux-hardware.org/?probe=9bb6aefa2c) | Sep 20, 2020 |
| Dell          | 0M877N A01                  | Server      | [8630cbf1b7](https://linux-hardware.org/?probe=8630cbf1b7) | Sep 20, 2020 |
| HP            | Compaq 6510b                | Notebook    | [3487aab3a6](https://linux-hardware.org/?probe=3487aab3a6) | Sep 20, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [66d1e7ec35](https://linux-hardware.org/?probe=66d1e7ec35) | Sep 20, 2020 |
| Dell          | Latitude E6440              | Notebook    | [f58584fa2c](https://linux-hardware.org/?probe=f58584fa2c) | Sep 20, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [bfbb7fc847](https://linux-hardware.org/?probe=bfbb7fc847) | Sep 19, 2020 |
| Lenovo        | ThinkPad T590 20N4004UMB    | Notebook    | [be3d2c8855](https://linux-hardware.org/?probe=be3d2c8855) | Sep 19, 2020 |
| HP            | Compaq 6510b                | Notebook    | [b7382d2141](https://linux-hardware.org/?probe=b7382d2141) | Sep 19, 2020 |
| Acer          | Aspire A515-44G             | Notebook    | [cf221f1b18](https://linux-hardware.org/?probe=cf221f1b18) | Sep 19, 2020 |
| HP            | ProBook 6550b               | Notebook    | [58aeb4c973](https://linux-hardware.org/?probe=58aeb4c973) | Sep 19, 2020 |
| HP            | Pavilion g7                 | Notebook    | [7a81ae667b](https://linux-hardware.org/?probe=7a81ae667b) | Sep 19, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| HP            | Pavilion g7                 | Notebook    | [767609618f](https://linux-hardware.org/?probe=767609618f) | Sep 19, 2020 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [bdae1a68a5](https://linux-hardware.org/?probe=bdae1a68a5) | Sep 18, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f5941e6787](https://linux-hardware.org/?probe=f5941e6787) | Sep 17, 2020 |
| ASRock        | X99 WS-E/10G                | Desktop     | [cd3238583f](https://linux-hardware.org/?probe=cd3238583f) | Sep 17, 2020 |
| Dell          | Vostro 3550                 | Notebook    | [ef71fe525d](https://linux-hardware.org/?probe=ef71fe525d) | Sep 17, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d4d25586c0](https://linux-hardware.org/?probe=d4d25586c0) | Sep 16, 2020 |
| ASRock        | X99 WS-E/10G                | Desktop     | [bf1047170e](https://linux-hardware.org/?probe=bf1047170e) | Sep 16, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [aef0cb23ec](https://linux-hardware.org/?probe=aef0cb23ec) | Sep 16, 2020 |
| HP            | 1495                        | Desktop     | [94de1a6e23](https://linux-hardware.org/?probe=94de1a6e23) | Sep 16, 2020 |
| Toshiba       | QOSMIO F50                  | Notebook    | [b60fe2f9e5](https://linux-hardware.org/?probe=b60fe2f9e5) | Sep 16, 2020 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [bea802e1b6](https://linux-hardware.org/?probe=bea802e1b6) | Sep 16, 2020 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | Notebook    | [8178cca0f9](https://linux-hardware.org/?probe=8178cca0f9) | Sep 16, 2020 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [4693e5b345](https://linux-hardware.org/?probe=4693e5b345) | Sep 15, 2020 |
| PCWare        | IPMH310G                    | Desktop     | [7231f076bd](https://linux-hardware.org/?probe=7231f076bd) | Sep 15, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [38af2c7f94](https://linux-hardware.org/?probe=38af2c7f94) | Sep 15, 2020 |
| PCWare        | IPMH310G                    | Desktop     | [181e5467d9](https://linux-hardware.org/?probe=181e5467d9) | Sep 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [2399ed18fd](https://linux-hardware.org/?probe=2399ed18fd) | Sep 14, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [d2d1e581b0](https://linux-hardware.org/?probe=d2d1e581b0) | Sep 14, 2020 |
| ASUSTek       | P6X58D-E                    | Desktop     | [09428a86cd](https://linux-hardware.org/?probe=09428a86cd) | Sep 14, 2020 |
| Toshiba       | Satellite U505              | Notebook    | [20507a8670](https://linux-hardware.org/?probe=20507a8670) | Sep 14, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [3f22ea2e15](https://linux-hardware.org/?probe=3f22ea2e15) | Sep 13, 2020 |
| ECS           | G31T-M7                     | Desktop     | [70c5208ec6](https://linux-hardware.org/?probe=70c5208ec6) | Sep 13, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [d58a689a0b](https://linux-hardware.org/?probe=d58a689a0b) | Sep 13, 2020 |
| Lenovo        | ThinkCentre M58p 6234DK6    | Desktop     | [f8dc9acb3f](https://linux-hardware.org/?probe=f8dc9acb3f) | Sep 13, 2020 |
| Lenovo        | ThinkCentre M58p 6234DK6    | Desktop     | [9f4325cb06](https://linux-hardware.org/?probe=9f4325cb06) | Sep 13, 2020 |
| Dell          | 0WG864                      | Desktop     | [fa12f9413f](https://linux-hardware.org/?probe=fa12f9413f) | Sep 12, 2020 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [960c7e17db](https://linux-hardware.org/?probe=960c7e17db) | Sep 12, 2020 |
| Dell          | 0WG864                      | Desktop     | [456382938e](https://linux-hardware.org/?probe=456382938e) | Sep 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [40bde8d392](https://linux-hardware.org/?probe=40bde8d392) | Sep 11, 2020 |
| Dell          | Latitude E5500              | Notebook    | [eb1361e23c](https://linux-hardware.org/?probe=eb1361e23c) | Sep 11, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [76836fadd2](https://linux-hardware.org/?probe=76836fadd2) | Sep 10, 2020 |
| ASRock        | X79 Extreme4                | Desktop     | [7cd6a3625c](https://linux-hardware.org/?probe=7cd6a3625c) | Sep 10, 2020 |
| HP            | ENVY m7 Notebook            | Notebook    | [6f870ff739](https://linux-hardware.org/?probe=6f870ff739) | Sep 10, 2020 |
| Positivo      | S14SL01                     | Notebook    | [3effdfe886](https://linux-hardware.org/?probe=3effdfe886) | Sep 09, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [4fdffb335a](https://linux-hardware.org/?probe=4fdffb335a) | Sep 08, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [7c9c74b288](https://linux-hardware.org/?probe=7c9c74b288) | Sep 08, 2020 |
| Lenovo        | ThinkStation D20 4158CM1    | Desktop     | [a6077c212e](https://linux-hardware.org/?probe=a6077c212e) | Sep 08, 2020 |
| ASUSTek       | H87-PLUS                    | Desktop     | [ad2897518b](https://linux-hardware.org/?probe=ad2897518b) | Sep 08, 2020 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [dd876ba784](https://linux-hardware.org/?probe=dd876ba784) | Sep 08, 2020 |
| ASRock        | ALiveNF6P-VSTA              | Desktop     | [42997fd9bd](https://linux-hardware.org/?probe=42997fd9bd) | Sep 08, 2020 |
| Google        | Auron_Yuna                  | Notebook    | [a4d1cd047b](https://linux-hardware.org/?probe=a4d1cd047b) | Sep 07, 2020 |
| Google        | Auron_Yuna                  | Notebook    | [676f8c83ec](https://linux-hardware.org/?probe=676f8c83ec) | Sep 07, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [c234184be5](https://linux-hardware.org/?probe=c234184be5) | Sep 07, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [84a01a41b1](https://linux-hardware.org/?probe=84a01a41b1) | Sep 06, 2020 |
| HP            | 339A                        | Desktop     | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [5a10409a8a](https://linux-hardware.org/?probe=5a10409a8a) | Sep 06, 2020 |
| Lenovo        | ThinkPad A485 20MVS0N300    | Notebook    | [6ad17e6cf7](https://linux-hardware.org/?probe=6ad17e6cf7) | Sep 05, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [cfe26c9023](https://linux-hardware.org/?probe=cfe26c9023) | Sep 05, 2020 |
| ASRock        | Z87E-ITX                    | Desktop     | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| Lenovo        | G780                        | Notebook    | [386777b221](https://linux-hardware.org/?probe=386777b221) | Sep 05, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [57a46b9db8](https://linux-hardware.org/?probe=57a46b9db8) | Sep 05, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4d40f1808](https://linux-hardware.org/?probe=d4d40f1808) | Sep 04, 2020 |
| Lenovo        | ThinkPad L440 20ASS10F00    | Notebook    | [cb6b544787](https://linux-hardware.org/?probe=cb6b544787) | Sep 04, 2020 |
| HP            | Compaq 6730b (KE717AV)      | Notebook    | [026b6d0abc](https://linux-hardware.org/?probe=026b6d0abc) | Sep 04, 2020 |
| ASUSTek       | H87-PLUS                    | Desktop     | [1602fc1f70](https://linux-hardware.org/?probe=1602fc1f70) | Sep 04, 2020 |
| Lenovo        | ThinkPad T480s 20L7001YU... | Notebook    | [a73e5916b6](https://linux-hardware.org/?probe=a73e5916b6) | Sep 04, 2020 |
| HP            | Pavilion g7                 | Notebook    | [7c130ac6c9](https://linux-hardware.org/?probe=7c130ac6c9) | Sep 04, 2020 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [7d6b9f9f5c](https://linux-hardware.org/?probe=7d6b9f9f5c) | Sep 04, 2020 |
| MSI           | Z77A-G45                    | Desktop     | [278850fdd4](https://linux-hardware.org/?probe=278850fdd4) | Sep 04, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [af1f6c2cd7](https://linux-hardware.org/?probe=af1f6c2cd7) | Sep 04, 2020 |
| Medion        | MS-7797                     | Desktop     | [cae7e7f201](https://linux-hardware.org/?probe=cae7e7f201) | Sep 04, 2020 |
| ASRock        | Q2900-ITX                   | Desktop     | [1707f849a6](https://linux-hardware.org/?probe=1707f849a6) | Sep 04, 2020 |
| Dell          | 0Y5DDC A00                  | Desktop     | [beef376967](https://linux-hardware.org/?probe=beef376967) | Sep 04, 2020 |
| Medion        | MS-7708                     | Desktop     | [c58e461f9d](https://linux-hardware.org/?probe=c58e461f9d) | Sep 03, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [18e8b1b893](https://linux-hardware.org/?probe=18e8b1b893) | Sep 03, 2020 |
| AWOW          | PC BOX                      | Mini pc     | [1e3e739887](https://linux-hardware.org/?probe=1e3e739887) | Sep 03, 2020 |
| ASRock        | B450 Pro4                   | Desktop     | [4b4eb09724](https://linux-hardware.org/?probe=4b4eb09724) | Sep 03, 2020 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [71b56d3a36](https://linux-hardware.org/?probe=71b56d3a36) | Sep 03, 2020 |
| Compaq        | Presario CQ-23              | Notebook    | [ab765182a8](https://linux-hardware.org/?probe=ab765182a8) | Sep 02, 2020 |
| Acer          | Batman A01                  | Desktop     | [e9d0e3d9d4](https://linux-hardware.org/?probe=e9d0e3d9d4) | Sep 02, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [e8bbe1674e](https://linux-hardware.org/?probe=e8bbe1674e) | Sep 01, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | Desktop     | [89e7ddc6ec](https://linux-hardware.org/?probe=89e7ddc6ec) | Sep 01, 2020 |
| Lenovo        | IdeaPad S300 9803           | Notebook    | [ca3bc94ba8](https://linux-hardware.org/?probe=ca3bc94ba8) | Sep 01, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [f0e36418ea](https://linux-hardware.org/?probe=f0e36418ea) | Sep 01, 2020 |
| Medion        | MS-7857                     | Desktop     | [9ab3e2ae3f](https://linux-hardware.org/?probe=9ab3e2ae3f) | Aug 31, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [d038b4c40e](https://linux-hardware.org/?probe=d038b4c40e) | Aug 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e6af6f9a47](https://linux-hardware.org/?probe=e6af6f9a47) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [64ba8fde9d](https://linux-hardware.org/?probe=64ba8fde9d) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [b37b0d860d](https://linux-hardware.org/?probe=b37b0d860d) | Aug 31, 2020 |
| Shuttle       | FH87                        | Desktop     | [087c5627a0](https://linux-hardware.org/?probe=087c5627a0) | Aug 30, 2020 |
| Medion        | MS-7857                     | Desktop     | [311d3d4895](https://linux-hardware.org/?probe=311d3d4895) | Aug 30, 2020 |
| Toshiba       | Satellite Pro P200          | Notebook    | [0490fe7f0a](https://linux-hardware.org/?probe=0490fe7f0a) | Aug 30, 2020 |
| Toshiba       | Satellite Pro P200          | Notebook    | [ff2e799a8c](https://linux-hardware.org/?probe=ff2e799a8c) | Aug 30, 2020 |
| Dell          | Vostro V130                 | Notebook    | [b117f2985f](https://linux-hardware.org/?probe=b117f2985f) | Aug 30, 2020 |
| Dell          | 0JC474                      | Desktop     | [0f799b70a5](https://linux-hardware.org/?probe=0f799b70a5) | Aug 29, 2020 |
| ASRock        | H170M Pro4                  | Desktop     | [10d84618d9](https://linux-hardware.org/?probe=10d84618d9) | Aug 29, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [efd7cd5751](https://linux-hardware.org/?probe=efd7cd5751) | Aug 29, 2020 |
| HP            | ProBook 4540s               | Notebook    | [615e7d9dfa](https://linux-hardware.org/?probe=615e7d9dfa) | Aug 29, 2020 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e46d6617a9](https://linux-hardware.org/?probe=e46d6617a9) | Aug 28, 2020 |
| Intel         | NUC7i7DNB J83500-202        | Mini pc     | [60b16780a6](https://linux-hardware.org/?probe=60b16780a6) | Aug 28, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [2fcea8b22c](https://linux-hardware.org/?probe=2fcea8b22c) | Aug 28, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [e7ae81e74c](https://linux-hardware.org/?probe=e7ae81e74c) | Aug 28, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [a5642b7562](https://linux-hardware.org/?probe=a5642b7562) | Aug 28, 2020 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [cae2109038](https://linux-hardware.org/?probe=cae2109038) | Aug 27, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [9cc05b2a9e](https://linux-hardware.org/?probe=9cc05b2a9e) | Aug 27, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [c3ce30ea06](https://linux-hardware.org/?probe=c3ce30ea06) | Aug 27, 2020 |
| ASUSTek       | Zephyrus M15 GU502LU_GU5... | Notebook    | [eecce44ac2](https://linux-hardware.org/?probe=eecce44ac2) | Aug 27, 2020 |
| ASRock        | B85 Pro4                    | Desktop     | [b75833748d](https://linux-hardware.org/?probe=b75833748d) | Aug 26, 2020 |
| ASUSTek       | X99-E                       | Desktop     | [c3e2a36b7e](https://linux-hardware.org/?probe=c3e2a36b7e) | Aug 25, 2020 |
| Dell          | Inspiron 7720               | Notebook    | [9f2a48a228](https://linux-hardware.org/?probe=9f2a48a228) | Aug 25, 2020 |
| NCR           | Pocono                      | Desktop     | [96fac7c428](https://linux-hardware.org/?probe=96fac7c428) | Aug 25, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [5bad10f24c](https://linux-hardware.org/?probe=5bad10f24c) | Aug 24, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [a69dacee1d](https://linux-hardware.org/?probe=a69dacee1d) | Aug 24, 2020 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [9ecd34fe2e](https://linux-hardware.org/?probe=9ecd34fe2e) | Aug 24, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [dbabe28124](https://linux-hardware.org/?probe=dbabe28124) | Aug 24, 2020 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [00834d5b62](https://linux-hardware.org/?probe=00834d5b62) | Aug 23, 2020 |
| Acer          | Sabine Platform             | Notebook    | [6ce3231440](https://linux-hardware.org/?probe=6ce3231440) | Aug 23, 2020 |
| HP            | HDX 18                      | Notebook    | [14f2f4a2e9](https://linux-hardware.org/?probe=14f2f4a2e9) | Aug 23, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [d54dcde59f](https://linux-hardware.org/?probe=d54dcde59f) | Aug 23, 2020 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0a3570e8fc](https://linux-hardware.org/?probe=0a3570e8fc) | Aug 23, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [25ba90f7f1](https://linux-hardware.org/?probe=25ba90f7f1) | Aug 23, 2020 |
| HP            | ProBook 4540s               | Notebook    | [d802ce490d](https://linux-hardware.org/?probe=d802ce490d) | Aug 23, 2020 |
| MSI           | MS-B0501 100                | Desktop     | [12c7b9ccc6](https://linux-hardware.org/?probe=12c7b9ccc6) | Aug 22, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [4cf98e3cbe](https://linux-hardware.org/?probe=4cf98e3cbe) | Aug 22, 2020 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [bc5631611b](https://linux-hardware.org/?probe=bc5631611b) | Aug 21, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [7286ec156e](https://linux-hardware.org/?probe=7286ec156e) | Aug 21, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [da3fea7987](https://linux-hardware.org/?probe=da3fea7987) | Aug 21, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [1e45d060b4](https://linux-hardware.org/?probe=1e45d060b4) | Aug 21, 2020 |
| HP            | Compaq 6735s                | Notebook    | [529e1a4543](https://linux-hardware.org/?probe=529e1a4543) | Aug 21, 2020 |
| Dell          | 0PU052                      | Desktop     | [ad5edd5c3c](https://linux-hardware.org/?probe=ad5edd5c3c) | Aug 21, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [edec3485d0](https://linux-hardware.org/?probe=edec3485d0) | Aug 21, 2020 |
| LG Electro... | P420-N.AE21G                | Notebook    | [6da1523a4e](https://linux-hardware.org/?probe=6da1523a4e) | Aug 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [532be87782](https://linux-hardware.org/?probe=532be87782) | Aug 20, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [76d74f26bd](https://linux-hardware.org/?probe=76d74f26bd) | Aug 20, 2020 |
| HP            | 3397                        | Desktop     | [fcdcfc7812](https://linux-hardware.org/?probe=fcdcfc7812) | Aug 20, 2020 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d4c9b039ff](https://linux-hardware.org/?probe=d4c9b039ff) | Aug 20, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [083a1b24a2](https://linux-hardware.org/?probe=083a1b24a2) | Aug 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [f3b36c38ff](https://linux-hardware.org/?probe=f3b36c38ff) | Aug 19, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [45fc7c3afb](https://linux-hardware.org/?probe=45fc7c3afb) | Aug 19, 2020 |
| HP            | Presario CQ57               | Notebook    | [618315e687](https://linux-hardware.org/?probe=618315e687) | Aug 19, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [b2e7162b8f](https://linux-hardware.org/?probe=b2e7162b8f) | Aug 19, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [49081ef429](https://linux-hardware.org/?probe=49081ef429) | Aug 19, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [d053bf3f76](https://linux-hardware.org/?probe=d053bf3f76) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [2551496802](https://linux-hardware.org/?probe=2551496802) | Aug 18, 2020 |
| Biostar       | G41-M7                      | Desktop     | [dc33e9b8b5](https://linux-hardware.org/?probe=dc33e9b8b5) | Aug 18, 2020 |
| Biostar       | G41-M7                      | Desktop     | [c9bd27ee3c](https://linux-hardware.org/?probe=c9bd27ee3c) | Aug 18, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [85145bb93c](https://linux-hardware.org/?probe=85145bb93c) | Aug 18, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [ea5ade72ff](https://linux-hardware.org/?probe=ea5ade72ff) | Aug 17, 2020 |
| HP            | Pavilion g6                 | Notebook    | [5e19a0ff8c](https://linux-hardware.org/?probe=5e19a0ff8c) | Aug 17, 2020 |
| Lenovo        | ThinkPad L420 7829AZ2       | Notebook    | [af5c485d91](https://linux-hardware.org/?probe=af5c485d91) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [dfd46d88c4](https://linux-hardware.org/?probe=dfd46d88c4) | Aug 16, 2020 |
| MSI           | E350DM-E33                  | Desktop     | [67f718b80b](https://linux-hardware.org/?probe=67f718b80b) | Aug 16, 2020 |
| MSI           | E350DM-E33                  | Desktop     | [df8f51adcb](https://linux-hardware.org/?probe=df8f51adcb) | Aug 16, 2020 |
| Positivo      | W253BUQ                     | Notebook    | [7c4e62a873](https://linux-hardware.org/?probe=7c4e62a873) | Aug 16, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [064e495c95](https://linux-hardware.org/?probe=064e495c95) | Aug 16, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [cdeea77503](https://linux-hardware.org/?probe=cdeea77503) | Aug 16, 2020 |
| Dell          | 0PU052                      | Desktop     | [f7616a2cae](https://linux-hardware.org/?probe=f7616a2cae) | Aug 16, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [56bbbd14d5](https://linux-hardware.org/?probe=56bbbd14d5) | Aug 16, 2020 |
| Gigabyte      | P35T-DQ6                    | Desktop     | [5a25041427](https://linux-hardware.org/?probe=5a25041427) | Aug 15, 2020 |
| Acer          | Aspire 4732Z                | Notebook    | [de0e2d7288](https://linux-hardware.org/?probe=de0e2d7288) | Aug 15, 2020 |
| Toshiba       | Satellite C650              | Notebook    | [4d6e3b95a0](https://linux-hardware.org/?probe=4d6e3b95a0) | Aug 15, 2020 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [f644ab6ee2](https://linux-hardware.org/?probe=f644ab6ee2) | Aug 14, 2020 |
| Dell          | Latitude E5500              | Notebook    | [360533c325](https://linux-hardware.org/?probe=360533c325) | Aug 14, 2020 |
| Pegatron      | IPM41-D3                    | Desktop     | [e51377d34f](https://linux-hardware.org/?probe=e51377d34f) | Aug 14, 2020 |
| MSI           | MS-163K Ver                 | Notebook    | [fac6732273](https://linux-hardware.org/?probe=fac6732273) | Aug 14, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [998c9d10e0](https://linux-hardware.org/?probe=998c9d10e0) | Aug 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [4dfd05b279](https://linux-hardware.org/?probe=4dfd05b279) | Aug 13, 2020 |
| Dell          | Latitude E6430              | Notebook    | [f5187f4aef](https://linux-hardware.org/?probe=f5187f4aef) | Aug 12, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [fe39d25754](https://linux-hardware.org/?probe=fe39d25754) | Aug 11, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [c40dc64451](https://linux-hardware.org/?probe=c40dc64451) | Aug 11, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [09d2e03b31](https://linux-hardware.org/?probe=09d2e03b31) | Aug 11, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [3adcca1e19](https://linux-hardware.org/?probe=3adcca1e19) | Aug 11, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [6633d497ea](https://linux-hardware.org/?probe=6633d497ea) | Aug 11, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [437b159ba3](https://linux-hardware.org/?probe=437b159ba3) | Aug 10, 2020 |
| HP            | 1998                        | Desktop     | [98779de9f0](https://linux-hardware.org/?probe=98779de9f0) | Aug 09, 2020 |
| Dell          | 0RW199                      | Desktop     | [5d2cb2e44b](https://linux-hardware.org/?probe=5d2cb2e44b) | Aug 09, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [a48c2316a3](https://linux-hardware.org/?probe=a48c2316a3) | Aug 09, 2020 |
| Dell          | 0JC474                      | Desktop     | [f7f2128996](https://linux-hardware.org/?probe=f7f2128996) | Aug 08, 2020 |
| Toshiba       | Satellite C850D-11F         | Notebook    | [1a4440eb8a](https://linux-hardware.org/?probe=1a4440eb8a) | Aug 08, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Toshiba       | Satellite C850D-11F         | Notebook    | [0c919133d7](https://linux-hardware.org/?probe=0c919133d7) | Aug 08, 2020 |
| Acer          | Sabine Platform             | Notebook    | [dbbfd9b9be](https://linux-hardware.org/?probe=dbbfd9b9be) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| Toshiba       | Satellite C670D-11K         | Notebook    | [3c59ce7fed](https://linux-hardware.org/?probe=3c59ce7fed) | Aug 07, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [9708e21a27](https://linux-hardware.org/?probe=9708e21a27) | Aug 07, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [6d195fc501](https://linux-hardware.org/?probe=6d195fc501) | Aug 06, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [57b132081d](https://linux-hardware.org/?probe=57b132081d) | Aug 06, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [c0dde75b94](https://linux-hardware.org/?probe=c0dde75b94) | Aug 06, 2020 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [ab2cdb31ec](https://linux-hardware.org/?probe=ab2cdb31ec) | Aug 05, 2020 |
| Dell          | 0RY206                      | Desktop     | [52b96832f5](https://linux-hardware.org/?probe=52b96832f5) | Aug 05, 2020 |
| Dell          | 0RY206                      | Desktop     | [fea85531ff](https://linux-hardware.org/?probe=fea85531ff) | Aug 05, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [a5dbd582ed](https://linux-hardware.org/?probe=a5dbd582ed) | Aug 04, 2020 |
| Dell          | Latitude D630               | Notebook    | [0505fb0e7c](https://linux-hardware.org/?probe=0505fb0e7c) | Aug 04, 2020 |
| HP            | Presario C700               | Notebook    | [db954beda7](https://linux-hardware.org/?probe=db954beda7) | Aug 04, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [9c24d40f13](https://linux-hardware.org/?probe=9c24d40f13) | Aug 03, 2020 |
| LG Electro... | 22V270 2                    | All in one  | [c9f5d29162](https://linux-hardware.org/?probe=c9f5d29162) | Aug 02, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [52a7e36042](https://linux-hardware.org/?probe=52a7e36042) | Aug 02, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [42ee50d658](https://linux-hardware.org/?probe=42ee50d658) | Aug 02, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [88fc41cab0](https://linux-hardware.org/?probe=88fc41cab0) | Aug 01, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [6ce85894b6](https://linux-hardware.org/?probe=6ce85894b6) | Aug 01, 2020 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [2a5cd28ee2](https://linux-hardware.org/?probe=2a5cd28ee2) | Aug 01, 2020 |
| MSI           | A75MA-G55                   | Desktop     | [f6e27145ee](https://linux-hardware.org/?probe=f6e27145ee) | Aug 01, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [9b0eb8f018](https://linux-hardware.org/?probe=9b0eb8f018) | Aug 01, 2020 |
| Dell          | 0RW199                      | Desktop     | [336760aa9b](https://linux-hardware.org/?probe=336760aa9b) | Jul 31, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [f79f3b002e](https://linux-hardware.org/?probe=f79f3b002e) | Jul 31, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [99c73340ba](https://linux-hardware.org/?probe=99c73340ba) | Jul 31, 2020 |
| HP            | 15                          | Notebook    | [337dcd22df](https://linux-hardware.org/?probe=337dcd22df) | Jul 30, 2020 |
| Dell          | 0VNP2H A02                  | Desktop     | [def480a828](https://linux-hardware.org/?probe=def480a828) | Jul 29, 2020 |
| HP            | G42                         | Notebook    | [80828bd820](https://linux-hardware.org/?probe=80828bd820) | Jul 29, 2020 |
| Dell          | 0M863N A00                  | Desktop     | [0359c45784](https://linux-hardware.org/?probe=0359c45784) | Jul 29, 2020 |
| Dell          | 0M863N A00                  | Desktop     | [6b435bdcb8](https://linux-hardware.org/?probe=6b435bdcb8) | Jul 29, 2020 |
| Acer          | EQ35M                       | Desktop     | [0a38bdbb37](https://linux-hardware.org/?probe=0a38bdbb37) | Jul 29, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [bfa97b70c7](https://linux-hardware.org/?probe=bfa97b70c7) | Jul 29, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [ff0e1e29b9](https://linux-hardware.org/?probe=ff0e1e29b9) | Jul 28, 2020 |
| Positivo      | C14RV01                     | Notebook    | [0d536d2855](https://linux-hardware.org/?probe=0d536d2855) | Jul 28, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [1020cd5f83](https://linux-hardware.org/?probe=1020cd5f83) | Jul 28, 2020 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [94a586edcd](https://linux-hardware.org/?probe=94a586edcd) | Jul 28, 2020 |
| HP            | Presario C700               | Notebook    | [d03a7b9127](https://linux-hardware.org/?probe=d03a7b9127) | Jul 28, 2020 |
| HP            | Presario C700               | Notebook    | [b6fdfa5ae6](https://linux-hardware.org/?probe=b6fdfa5ae6) | Jul 28, 2020 |
| Positivo      | POS-PIG41BO POSITIVO        | Desktop     | [c815c1ad30](https://linux-hardware.org/?probe=c815c1ad30) | Jul 27, 2020 |
| HP            | Compaq 6535b                | Notebook    | [235208ffe1](https://linux-hardware.org/?probe=235208ffe1) | Jul 27, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [26e62910da](https://linux-hardware.org/?probe=26e62910da) | Jul 26, 2020 |
| Google        | Liara                       | Notebook    | [93778f0294](https://linux-hardware.org/?probe=93778f0294) | Jul 26, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [4976009eba](https://linux-hardware.org/?probe=4976009eba) | Jul 26, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [5e834a1db4](https://linux-hardware.org/?probe=5e834a1db4) | Jul 26, 2020 |
| LG Electro... | 22V270 2                    | All in one  | [43eef5d15f](https://linux-hardware.org/?probe=43eef5d15f) | Jul 26, 2020 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [d573d41540](https://linux-hardware.org/?probe=d573d41540) | Jul 25, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| HP            | 1497                        | Desktop     | [ef31cca294](https://linux-hardware.org/?probe=ef31cca294) | Jul 25, 2020 |
| Apple         | Mac-F22C86C8                | Mini pc     | [ba999e7825](https://linux-hardware.org/?probe=ba999e7825) | Jul 25, 2020 |
| HP            | Pavilion dv4                | Notebook    | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| Positivo      | POS-MI945AA                 | Desktop     | [70488a83b5](https://linux-hardware.org/?probe=70488a83b5) | Jul 25, 2020 |
| Acer          | Nitro AN515-51              | Notebook    | [9c0b965190](https://linux-hardware.org/?probe=9c0b965190) | Jul 25, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [71c07410ee](https://linux-hardware.org/?probe=71c07410ee) | Jul 25, 2020 |
| Multilaser    | PC231                       | Notebook    | [348ab5d244](https://linux-hardware.org/?probe=348ab5d244) | Jul 24, 2020 |
| Acer          | Sabine Platform             | Notebook    | [043e933c74](https://linux-hardware.org/?probe=043e933c74) | Jul 24, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [810f713a78](https://linux-hardware.org/?probe=810f713a78) | Jul 24, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| Positivo      | N1103                       | Notebook    | [552c0c0605](https://linux-hardware.org/?probe=552c0c0605) | Jul 24, 2020 |
| MSI           | G31TM-P35                   | Desktop     | [956c575a24](https://linux-hardware.org/?probe=956c575a24) | Jul 24, 2020 |
| HP            | Presario C700               | Notebook    | [afb4c089f1](https://linux-hardware.org/?probe=afb4c089f1) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [9818a6e8d5](https://linux-hardware.org/?probe=9818a6e8d5) | Jul 24, 2020 |
| Lenovo        | G460 0677                   | Notebook    | [d22e5d2715](https://linux-hardware.org/?probe=d22e5d2715) | Jul 24, 2020 |
| ASUSTek       | X550CA                      | Notebook    | [24d8f4daa8](https://linux-hardware.org/?probe=24d8f4daa8) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [a80a673e14](https://linux-hardware.org/?probe=a80a673e14) | Jul 24, 2020 |
| Toshiba       | STI 910133                  | Desktop     | [21c7264a49](https://linux-hardware.org/?probe=21c7264a49) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [8973f15f3c](https://linux-hardware.org/?probe=8973f15f3c) | Jul 24, 2020 |
| ASUSTek       | PRIME B250M-PLUS/BR         | Desktop     | [974995c15c](https://linux-hardware.org/?probe=974995c15c) | Jul 24, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [a308ee2a62](https://linux-hardware.org/?probe=a308ee2a62) | Jul 24, 2020 |
| ASRock        | A320M-HD                    | Desktop     | [2a85bda9fa](https://linux-hardware.org/?probe=2a85bda9fa) | Jul 24, 2020 |
| ASUSTek       | B150M-C D3/BR               | Desktop     | [b46f40c38a](https://linux-hardware.org/?probe=b46f40c38a) | Jul 24, 2020 |
| Lenovo        | G400s VILG1                 | Notebook    | [0c8815e6d9](https://linux-hardware.org/?probe=0c8815e6d9) | Jul 24, 2020 |
| HP            | 1790                        | Desktop     | [7e30cf0101](https://linux-hardware.org/?probe=7e30cf0101) | Jul 23, 2020 |
| Lenovo        | G460 0677                   | Notebook    | [c43dd028ea](https://linux-hardware.org/?probe=c43dd028ea) | Jul 23, 2020 |
| HP            | Presario CQ56               | Notebook    | [93cc43e52e](https://linux-hardware.org/?probe=93cc43e52e) | Jul 23, 2020 |
| HP            | Presario CQ56               | Notebook    | [5eb29c4d14](https://linux-hardware.org/?probe=5eb29c4d14) | Jul 23, 2020 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [c96a8407b9](https://linux-hardware.org/?probe=c96a8407b9) | Jul 22, 2020 |
| HP            | Notebook                    | Notebook    | [431d1d1482](https://linux-hardware.org/?probe=431d1d1482) | Jul 22, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [644eeb1f68](https://linux-hardware.org/?probe=644eeb1f68) | Jul 22, 2020 |
| HP            | 2AF7                        | Desktop     | [fadc92035e](https://linux-hardware.org/?probe=fadc92035e) | Jul 22, 2020 |
| Dell          | Latitude E6520              | Notebook    | [de12c01408](https://linux-hardware.org/?probe=de12c01408) | Jul 21, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [cbad09cb89](https://linux-hardware.org/?probe=cbad09cb89) | Jul 21, 2020 |
| HP            | ProLiant ML10 v2            | Desktop     | [84badf8a6a](https://linux-hardware.org/?probe=84badf8a6a) | Jul 21, 2020 |
| HP            | Pavilion DV9000 (RY715EA... | Notebook    | [b3c779f8be](https://linux-hardware.org/?probe=b3c779f8be) | Jul 21, 2020 |
| Toshiba       | Satellite C650              | Notebook    | [6d522083a5](https://linux-hardware.org/?probe=6d522083a5) | Jul 20, 2020 |
| MSI           | A75MA-G55                   | Desktop     | [9061f7d6fb](https://linux-hardware.org/?probe=9061f7d6fb) | Jul 20, 2020 |
| HP            | 158A                        | Desktop     | [68f61abed8](https://linux-hardware.org/?probe=68f61abed8) | Jul 20, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | Desktop     | [f25b0e7108](https://linux-hardware.org/?probe=f25b0e7108) | Jul 19, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [79c11f4f35](https://linux-hardware.org/?probe=79c11f4f35) | Jul 19, 2020 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [a51dee5095](https://linux-hardware.org/?probe=a51dee5095) | Jul 19, 2020 |
| Google        | Liara                       | Notebook    | [c131819f50](https://linux-hardware.org/?probe=c131819f50) | Jul 18, 2020 |
| MSI           | CX61 2QF                    | Notebook    | [47f6147b6e](https://linux-hardware.org/?probe=47f6147b6e) | Jul 18, 2020 |
| ASUSTek       | X201EP                      | Notebook    | [d45bd20693](https://linux-hardware.org/?probe=d45bd20693) | Jul 18, 2020 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [f076c0e711](https://linux-hardware.org/?probe=f076c0e711) | Jul 18, 2020 |
| Lenovo        | ThinkPad W530 24479Q7       | Notebook    | [f4ce1f339d](https://linux-hardware.org/?probe=f4ce1f339d) | Jul 17, 2020 |
| HP            | Pavilion 15                 | Notebook    | [1b5882adc2](https://linux-hardware.org/?probe=1b5882adc2) | Jul 17, 2020 |
| Dell          | Vostro 3360                 | Notebook    | [22cf25df0d](https://linux-hardware.org/?probe=22cf25df0d) | Jul 17, 2020 |
| Pegatron      | 2AC2                        | Desktop     | [a7985ac6dc](https://linux-hardware.org/?probe=a7985ac6dc) | Jul 17, 2020 |
| Toshiba       | Satellite U305              | Notebook    | [a08a02467a](https://linux-hardware.org/?probe=a08a02467a) | Jul 16, 2020 |
| Dell          | 0GM819                      | Desktop     | [b1fc765931](https://linux-hardware.org/?probe=b1fc765931) | Jul 15, 2020 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [acc1fde47a](https://linux-hardware.org/?probe=acc1fde47a) | Jul 15, 2020 |
| Apple         | MacBook7,1                  | Notebook    | [4a2c480573](https://linux-hardware.org/?probe=4a2c480573) | Jul 14, 2020 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [a50c792692](https://linux-hardware.org/?probe=a50c792692) | Jul 14, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [6afbd4537c](https://linux-hardware.org/?probe=6afbd4537c) | Jul 14, 2020 |
| Toshiba       | Satellite C650              | Notebook    | [f0caedbdd0](https://linux-hardware.org/?probe=f0caedbdd0) | Jul 14, 2020 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [019ca65c62](https://linux-hardware.org/?probe=019ca65c62) | Jul 14, 2020 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [6458f60483](https://linux-hardware.org/?probe=6458f60483) | Jul 14, 2020 |
| Dell          | Latitude D630               | Notebook    | [5347cbcf05](https://linux-hardware.org/?probe=5347cbcf05) | Jul 14, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [0f840e8f40](https://linux-hardware.org/?probe=0f840e8f40) | Jul 13, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [c77dba0448](https://linux-hardware.org/?probe=c77dba0448) | Jul 13, 2020 |
| Dell          | Latitude E6520              | Notebook    | [a339b5cccc](https://linux-hardware.org/?probe=a339b5cccc) | Jul 13, 2020 |
| HP            | 304Ah                       | Desktop     | [5e67b190e0](https://linux-hardware.org/?probe=5e67b190e0) | Jul 13, 2020 |
| HP            | 0A54h                       | Desktop     | [944573af57](https://linux-hardware.org/?probe=944573af57) | Jul 13, 2020 |
| Unknown       | A6VMX                       | Desktop     | [c1db401dad](https://linux-hardware.org/?probe=c1db401dad) | Jul 13, 2020 |
| HP            | 158A                        | Desktop     | [f5c2d58594](https://linux-hardware.org/?probe=f5c2d58594) | Jul 13, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [478381d890](https://linux-hardware.org/?probe=478381d890) | Jul 12, 2020 |
| Medion        | MS-7616                     | Desktop     | [c0bca959eb](https://linux-hardware.org/?probe=c0bca959eb) | Jul 12, 2020 |
| Acer          | AOD257                      | Notebook    | [eb1b54bd86](https://linux-hardware.org/?probe=eb1b54bd86) | Jul 12, 2020 |
| ASUSTek       | 1005PE                      | Notebook    | [0f179f8719](https://linux-hardware.org/?probe=0f179f8719) | Jul 12, 2020 |
| eMachines     | EL1352                      | Desktop     | [95bca495a4](https://linux-hardware.org/?probe=95bca495a4) | Jul 11, 2020 |
| Foxconn       | 8657MF-series               | Desktop     | [3c9a2f5db5](https://linux-hardware.org/?probe=3c9a2f5db5) | Jul 11, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d78422bc37](https://linux-hardware.org/?probe=d78422bc37) | Jul 11, 2020 |
| Dell          | 0RW199                      | Desktop     | [d3a2cbaa35](https://linux-hardware.org/?probe=d3a2cbaa35) | Jul 11, 2020 |
| Lenovo        | G460 0677                   | Notebook    | [c5a0c92162](https://linux-hardware.org/?probe=c5a0c92162) | Jul 11, 2020 |
| Acer          | Extensa X2610G              | Desktop     | [12b9c02a39](https://linux-hardware.org/?probe=12b9c02a39) | Jul 11, 2020 |
| Dell          | Latitude D630               | Notebook    | [77fa436b56](https://linux-hardware.org/?probe=77fa436b56) | Jul 11, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [8a1cc0ea02](https://linux-hardware.org/?probe=8a1cc0ea02) | Jul 11, 2020 |
| Apple         | MacBook7,1                  | Notebook    | [214192cc63](https://linux-hardware.org/?probe=214192cc63) | Jul 10, 2020 |
| HP            | 158A                        | Desktop     | [52e8f357cc](https://linux-hardware.org/?probe=52e8f357cc) | Jul 10, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [33ab28c151](https://linux-hardware.org/?probe=33ab28c151) | Jul 10, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [fdd8fdf7b1](https://linux-hardware.org/?probe=fdd8fdf7b1) | Jul 09, 2020 |
| Dell          | Latitude E7270              | Notebook    | [a4e36dcb8e](https://linux-hardware.org/?probe=a4e36dcb8e) | Jul 09, 2020 |
| Dell          | 0F6X5P A00                  | Desktop     | [39f78be0f7](https://linux-hardware.org/?probe=39f78be0f7) | Jul 08, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [6c87fe867b](https://linux-hardware.org/?probe=6c87fe867b) | Jul 07, 2020 |
| Dell          | Latitude E7270              | Notebook    | [360112322b](https://linux-hardware.org/?probe=360112322b) | Jul 07, 2020 |
| HP            | 1790                        | Desktop     | [2cef9e73a0](https://linux-hardware.org/?probe=2cef9e73a0) | Jul 07, 2020 |
| HP            | 1790                        | Desktop     | [01fcef55ed](https://linux-hardware.org/?probe=01fcef55ed) | Jul 07, 2020 |
| Intel         | DX38BT AAD85848-503         | Desktop     | [6884fbae7e](https://linux-hardware.org/?probe=6884fbae7e) | Jul 07, 2020 |
| Unknown       | Unknown                     | Desktop     | [84ef219ac1](https://linux-hardware.org/?probe=84ef219ac1) | Jul 07, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [7faeeccd7e](https://linux-hardware.org/?probe=7faeeccd7e) | Jul 07, 2020 |
| Intel         | DP55WG AAE57269-406         | Desktop     | [2207d5fce7](https://linux-hardware.org/?probe=2207d5fce7) | Jul 06, 2020 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [b066fd06df](https://linux-hardware.org/?probe=b066fd06df) | Jul 06, 2020 |
| HP            | G62                         | Notebook    | [ba604ce99d](https://linux-hardware.org/?probe=ba604ce99d) | Jul 06, 2020 |
| Dell          | 0PTTT9 A01                  | Desktop     | [9f5a7645a2](https://linux-hardware.org/?probe=9f5a7645a2) | Jul 06, 2020 |
| Unknown       | Unknown                     | Desktop     | [b47a2fdc9f](https://linux-hardware.org/?probe=b47a2fdc9f) | Jul 05, 2020 |
| ASUSTek       | M4N78-AM V2                 | Desktop     | [f19b8c2801](https://linux-hardware.org/?probe=f19b8c2801) | Jul 05, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [ebe0e51b56](https://linux-hardware.org/?probe=ebe0e51b56) | Jul 05, 2020 |
| Dell          | 0VNP2H A02                  | Desktop     | [4a6497b51d](https://linux-hardware.org/?probe=4a6497b51d) | Jul 04, 2020 |
| Acer          | Aspire ES1-512              | Notebook    | [35d93bfedf](https://linux-hardware.org/?probe=35d93bfedf) | Jul 04, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [51ecc177d5](https://linux-hardware.org/?probe=51ecc177d5) | Jul 04, 2020 |
| Dell          | Latitude E6420              | Notebook    | [f3a048144b](https://linux-hardware.org/?probe=f3a048144b) | Jul 04, 2020 |
| Lenovo        | ThinkPad L470 20J4002FMH    | Notebook    | [f5262493e1](https://linux-hardware.org/?probe=f5262493e1) | Jul 03, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [e37c3a0ba5](https://linux-hardware.org/?probe=e37c3a0ba5) | Jul 03, 2020 |
| HP            | Pavilion g4                 | Notebook    | [21261aa7d1](https://linux-hardware.org/?probe=21261aa7d1) | Jul 01, 2020 |
| Dell          | 0CR984 A01                  | Desktop     | [e7c68c86df](https://linux-hardware.org/?probe=e7c68c86df) | Jun 30, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [bb6d6e1681](https://linux-hardware.org/?probe=bb6d6e1681) | Jun 30, 2020 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [81cb2b3479](https://linux-hardware.org/?probe=81cb2b3479) | Jun 30, 2020 |
| Acer          | Veriton X4630G              | Desktop     | [504ec0d230](https://linux-hardware.org/?probe=504ec0d230) | Jun 30, 2020 |
| MSI           | D2415 S26361-D2415-A10      | Desktop     | [cdeb87380b](https://linux-hardware.org/?probe=cdeb87380b) | Jun 30, 2020 |
| Dell          | 084J0R A00                  | Desktop     | [1d98c0ae1e](https://linux-hardware.org/?probe=1d98c0ae1e) | Jun 30, 2020 |
| Dell          | 0RW199                      | Desktop     | [eb2e75e011](https://linux-hardware.org/?probe=eb2e75e011) | Jun 29, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [dece2951c4](https://linux-hardware.org/?probe=dece2951c4) | Jun 29, 2020 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [2c94b496ce](https://linux-hardware.org/?probe=2c94b496ce) | Jun 29, 2020 |
| ASRock        | J3455M                      | Desktop     | [0fc2987e1c](https://linux-hardware.org/?probe=0fc2987e1c) | Jun 29, 2020 |
| Toshiba       | Satellite C870D-11T         | Notebook    | [dc5b9f0738](https://linux-hardware.org/?probe=dc5b9f0738) | Jun 28, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [51b7fb4eed](https://linux-hardware.org/?probe=51b7fb4eed) | Jun 28, 2020 |
| HP            | ProBook 6460b               | Notebook    | [f1ab7d5b8c](https://linux-hardware.org/?probe=f1ab7d5b8c) | Jun 28, 2020 |
| ASUSTek       | S551LB                      | Notebook    | [0a8aa9f0da](https://linux-hardware.org/?probe=0a8aa9f0da) | Jun 28, 2020 |
| ASUSTek       | S551LB                      | Notebook    | [667945db63](https://linux-hardware.org/?probe=667945db63) | Jun 28, 2020 |
| Intel         | HURONRIVER                  | Notebook    | [e748e1f03d](https://linux-hardware.org/?probe=e748e1f03d) | Jun 28, 2020 |
| Intel         | HURONRIVER                  | Notebook    | [319de108aa](https://linux-hardware.org/?probe=319de108aa) | Jun 28, 2020 |
| Acer          | Aspire X3400G               | Desktop     | [8ecd5df128](https://linux-hardware.org/?probe=8ecd5df128) | Jun 27, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [19c8257ed1](https://linux-hardware.org/?probe=19c8257ed1) | Jun 26, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a56bd9dd64](https://linux-hardware.org/?probe=a56bd9dd64) | Jun 26, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [1adcab5b3c](https://linux-hardware.org/?probe=1adcab5b3c) | Jun 26, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [4642aa5c7e](https://linux-hardware.org/?probe=4642aa5c7e) | Jun 26, 2020 |
| CAPTIVA       | Unknown                     | Notebook    | [a05874290f](https://linux-hardware.org/?probe=a05874290f) | Jun 26, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [5f75d137ed](https://linux-hardware.org/?probe=5f75d137ed) | Jun 26, 2020 |
| Dell          | 0RW203                      | Desktop     | [8ba004d478](https://linux-hardware.org/?probe=8ba004d478) | Jun 25, 2020 |
| Unknown       | T3 MRD                      | Notebook    | [e713023e67](https://linux-hardware.org/?probe=e713023e67) | Jun 25, 2020 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [063d50afa1](https://linux-hardware.org/?probe=063d50afa1) | Jun 25, 2020 |
| Dell          | Studio 1535                 | Notebook    | [effa9a2180](https://linux-hardware.org/?probe=effa9a2180) | Jun 25, 2020 |
| HP            | 14                          | Notebook    | [4de0326f3b](https://linux-hardware.org/?probe=4de0326f3b) | Jun 24, 2020 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [1af9bd68bf](https://linux-hardware.org/?probe=1af9bd68bf) | Jun 24, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [176c1bcb0a](https://linux-hardware.org/?probe=176c1bcb0a) | Jun 24, 2020 |
| Dell          | Latitude E5510              | Notebook    | [f00a0fb5c0](https://linux-hardware.org/?probe=f00a0fb5c0) | Jun 24, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [22b31e99cc](https://linux-hardware.org/?probe=22b31e99cc) | Jun 24, 2020 |
| Dell          | 0RW203                      | Desktop     | [7e50eb34dc](https://linux-hardware.org/?probe=7e50eb34dc) | Jun 24, 2020 |
| Dell          | 0RW203                      | Desktop     | [b853674a1a](https://linux-hardware.org/?probe=b853674a1a) | Jun 24, 2020 |
| Dell          | 0RW199                      | Desktop     | [c74695aacf](https://linux-hardware.org/?probe=c74695aacf) | Jun 24, 2020 |
| LIVEFAN       | Unknown                     | Notebook    | [e2374d060c](https://linux-hardware.org/?probe=e2374d060c) | Jun 23, 2020 |
| Nvidia        | NF-MCP68                    | Desktop     | [6b42b5244e](https://linux-hardware.org/?probe=6b42b5244e) | Jun 23, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [48f5b587fe](https://linux-hardware.org/?probe=48f5b587fe) | Jun 23, 2020 |
| Lenovo        | ThinkStation D20 4158CM1    | Desktop     | [59660a488b](https://linux-hardware.org/?probe=59660a488b) | Jun 22, 2020 |
| Lenovo        | ThinkStation D20 4158CM1    | Desktop     | [d1ef95aafa](https://linux-hardware.org/?probe=d1ef95aafa) | Jun 22, 2020 |
| Dell          | Inspiron 5423               | Notebook    | [cf43eb493f](https://linux-hardware.org/?probe=cf43eb493f) | Jun 22, 2020 |
| HP            | 15                          | Notebook    | [aa5d7e28d3](https://linux-hardware.org/?probe=aa5d7e28d3) | Jun 21, 2020 |
| ASRock        | ALiveNF7G-GLAN              | Desktop     | [747c29d2f3](https://linux-hardware.org/?probe=747c29d2f3) | Jun 21, 2020 |
| Dell          | Inspiron 11-3162            | Notebook    | [1591961f13](https://linux-hardware.org/?probe=1591961f13) | Jun 21, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [9e3d4f423a](https://linux-hardware.org/?probe=9e3d4f423a) | Jun 21, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [07027013e9](https://linux-hardware.org/?probe=07027013e9) | Jun 21, 2020 |
| Dell          | Latitude E6430              | Notebook    | [742518866d](https://linux-hardware.org/?probe=742518866d) | Jun 21, 2020 |
| Dell          | Latitude E6430              | Notebook    | [a3708e4a03](https://linux-hardware.org/?probe=a3708e4a03) | Jun 21, 2020 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [31741c6aa1](https://linux-hardware.org/?probe=31741c6aa1) | Jun 21, 2020 |
| MSI           | MS-163K Ver                 | Notebook    | [76f39989ef](https://linux-hardware.org/?probe=76f39989ef) | Jun 21, 2020 |
| ASRock        | A75M-HVS                    | Desktop     | [729f379298](https://linux-hardware.org/?probe=729f379298) | Jun 20, 2020 |
| Dell          | 0RW199                      | Desktop     | [afdc1b6a20](https://linux-hardware.org/?probe=afdc1b6a20) | Jun 20, 2020 |
| HP            | 3032h                       | Desktop     | [b95914d3ef](https://linux-hardware.org/?probe=b95914d3ef) | Jun 20, 2020 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b22002ee7d](https://linux-hardware.org/?probe=b22002ee7d) | Jun 20, 2020 |
| HP            | 3032h                       | Desktop     | [7daea29a60](https://linux-hardware.org/?probe=7daea29a60) | Jun 19, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [48e5b1d9fe](https://linux-hardware.org/?probe=48e5b1d9fe) | Jun 19, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [e32526b458](https://linux-hardware.org/?probe=e32526b458) | Jun 18, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [fd9ebdb043](https://linux-hardware.org/?probe=fd9ebdb043) | Jun 18, 2020 |
| Unknown       | T3 MRD                      | Notebook    | [f6a1ada662](https://linux-hardware.org/?probe=f6a1ada662) | Jun 18, 2020 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [02c5eb9954](https://linux-hardware.org/?probe=02c5eb9954) | Jun 18, 2020 |
| Unknown       | T3 MRD                      | Notebook    | [998b0f0d52](https://linux-hardware.org/?probe=998b0f0d52) | Jun 18, 2020 |
| Dell          | 0WG233                      | Desktop     | [a830ee5f45](https://linux-hardware.org/?probe=a830ee5f45) | Jun 18, 2020 |
| Dell          | 0WG233                      | Desktop     | [29530016f6](https://linux-hardware.org/?probe=29530016f6) | Jun 18, 2020 |
| Dell          | 084J0R A00                  | Desktop     | [bb9b6a638d](https://linux-hardware.org/?probe=bb9b6a638d) | Jun 17, 2020 |
| Dell          | 084J0R A00                  | Desktop     | [b5ed051f73](https://linux-hardware.org/?probe=b5ed051f73) | Jun 17, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [28fa360e16](https://linux-hardware.org/?probe=28fa360e16) | Jun 17, 2020 |
| HP            | ProBook 6460b               | Notebook    | [4b0b074c7d](https://linux-hardware.org/?probe=4b0b074c7d) | Jun 17, 2020 |
| Dell          | Studio 1535                 | Notebook    | [dc7f250d15](https://linux-hardware.org/?probe=dc7f250d15) | Jun 17, 2020 |
| MSI           | D2415 S26361-D2415-A10      | Desktop     | [047a92b8b5](https://linux-hardware.org/?probe=047a92b8b5) | Jun 17, 2020 |
| HP            | 1497                        | Desktop     | [7e8347d308](https://linux-hardware.org/?probe=7e8347d308) | Jun 17, 2020 |
| MSI           | MS-163K Ver                 | Notebook    | [5d37279473](https://linux-hardware.org/?probe=5d37279473) | Jun 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0293417e94](https://linux-hardware.org/?probe=0293417e94) | Jun 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53c2e605c2](https://linux-hardware.org/?probe=53c2e605c2) | Jun 16, 2020 |
| Dell          | Inspiron 3582               | Notebook    | [9ce1f0b968](https://linux-hardware.org/?probe=9ce1f0b968) | Jun 16, 2020 |
| Dell          | 03NVJ6 A00                  | Desktop     | [a129d8050e](https://linux-hardware.org/?probe=a129d8050e) | Jun 16, 2020 |
| ASUSTek       | F5RL                        | Notebook    | [6a1a56701c](https://linux-hardware.org/?probe=6a1a56701c) | Jun 15, 2020 |
| Qbex          | H61H2-M2                    | Desktop     | [41819671fb](https://linux-hardware.org/?probe=41819671fb) | Jun 15, 2020 |
| ASUSTek       | M4N78-AM V2                 | Desktop     | [388c7aac3a](https://linux-hardware.org/?probe=388c7aac3a) | Jun 15, 2020 |
| NCR           | Pocono                      | Desktop     | [a44ee61726](https://linux-hardware.org/?probe=a44ee61726) | Jun 15, 2020 |
| Unknown       | P4M800CE-8237               | Desktop     | [1e85cb931c](https://linux-hardware.org/?probe=1e85cb931c) | Jun 14, 2020 |
| Acer          | Swift SF314-57G             | Notebook    | [3e717eb1c2](https://linux-hardware.org/?probe=3e717eb1c2) | Jun 14, 2020 |
| ASRock        | 870 Extreme3                | Desktop     | [6fd6b24f09](https://linux-hardware.org/?probe=6fd6b24f09) | Jun 14, 2020 |
| ASRock        | 870 Extreme3                | Desktop     | [cff93a50da](https://linux-hardware.org/?probe=cff93a50da) | Jun 14, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [a3681caed5](https://linux-hardware.org/?probe=a3681caed5) | Jun 14, 2020 |
| ECS           | Z77H2-A2X Deluxe            | Desktop     | [5bb6af2e45](https://linux-hardware.org/?probe=5bb6af2e45) | Jun 14, 2020 |
| ECS           | Z77H2-A2X Deluxe            | Desktop     | [c06f108477](https://linux-hardware.org/?probe=c06f108477) | Jun 14, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Dell          | 0KP561                      | Desktop     | [0a700a55b8](https://linux-hardware.org/?probe=0a700a55b8) | Jun 13, 2020 |
| ASRock        | P67 Pro3                    | Desktop     | [deaf1b5c77](https://linux-hardware.org/?probe=deaf1b5c77) | Jun 13, 2020 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [2680b47951](https://linux-hardware.org/?probe=2680b47951) | Jun 13, 2020 |
| Sony          | VAIO                        | All in one  | [cfdcac5734](https://linux-hardware.org/?probe=cfdcac5734) | Jun 13, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1f5d5cf1de](https://linux-hardware.org/?probe=1f5d5cf1de) | Jun 12, 2020 |
| Dell          | G3 3590                     | Notebook    | [f9e9753ae2](https://linux-hardware.org/?probe=f9e9753ae2) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | Notebook    | [ce8deb0caa](https://linux-hardware.org/?probe=ce8deb0caa) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | Notebook    | [cc0f65e016](https://linux-hardware.org/?probe=cc0f65e016) | Jun 12, 2020 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [46f3f502e7](https://linux-hardware.org/?probe=46f3f502e7) | Jun 12, 2020 |
| Dell          | G3 3590                     | Notebook    | [d4035154be](https://linux-hardware.org/?probe=d4035154be) | Jun 12, 2020 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [4765048ec9](https://linux-hardware.org/?probe=4765048ec9) | Jun 12, 2020 |
| Dell          | Latitude D630               | Notebook    | [93500e7aa5](https://linux-hardware.org/?probe=93500e7aa5) | Jun 11, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [ab4e5215f2](https://linux-hardware.org/?probe=ab4e5215f2) | Jun 11, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | Desktop     | [e30aeca065](https://linux-hardware.org/?probe=e30aeca065) | Jun 11, 2020 |
| HP            | ENVY m7 Notebook            | Notebook    | [7407e48fab](https://linux-hardware.org/?probe=7407e48fab) | Jun 11, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [053fd50552](https://linux-hardware.org/?probe=053fd50552) | Jun 11, 2020 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [a3e534b4f8](https://linux-hardware.org/?probe=a3e534b4f8) | Jun 10, 2020 |
| Acer          | Aspire ES1-523              | Notebook    | [ebd72429b9](https://linux-hardware.org/?probe=ebd72429b9) | Jun 10, 2020 |
| Samsung       | 270E5G/270E5U               | Notebook    | [36bfc8f6c5](https://linux-hardware.org/?probe=36bfc8f6c5) | Jun 10, 2020 |
| HP            | ENVY m7 Notebook            | Notebook    | [3927770241](https://linux-hardware.org/?probe=3927770241) | Jun 10, 2020 |
| Toshiba       | TECRA R940                  | Notebook    | [3c4e99be53](https://linux-hardware.org/?probe=3c4e99be53) | Jun 10, 2020 |
| Toshiba       | TECRA R940                  | Notebook    | [feceb292e9](https://linux-hardware.org/?probe=feceb292e9) | Jun 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2f9e1d63ca](https://linux-hardware.org/?probe=2f9e1d63ca) | Jun 10, 2020 |
| Fujitsu       | LIFEBOOK P772               | Notebook    | [0589b2e0a0](https://linux-hardware.org/?probe=0589b2e0a0) | Jun 10, 2020 |
| Fujitsu       | LIFEBOOK P772               | Notebook    | [957ad12749](https://linux-hardware.org/?probe=957ad12749) | Jun 09, 2020 |
| HP            | Pavilion dv7                | Notebook    | [618623cb06](https://linux-hardware.org/?probe=618623cb06) | Jun 08, 2020 |
| Intel         | D54250WYK H13922-304        | Desktop     | [3447a97b5f](https://linux-hardware.org/?probe=3447a97b5f) | Jun 07, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [bf878163f2](https://linux-hardware.org/?probe=bf878163f2) | Jun 07, 2020 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [b35f2a71dd](https://linux-hardware.org/?probe=b35f2a71dd) | Jun 07, 2020 |
| ASRock        | B85 Pro4                    | Desktop     | [a24fcca14f](https://linux-hardware.org/?probe=a24fcca14f) | Jun 06, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [a59a5c001f](https://linux-hardware.org/?probe=a59a5c001f) | Jun 06, 2020 |
| Lenovo        | ThinkPad T430 23499K1       | Notebook    | [ea30f4cbe1](https://linux-hardware.org/?probe=ea30f4cbe1) | Jun 06, 2020 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [c60bd8dd4d](https://linux-hardware.org/?probe=c60bd8dd4d) | Jun 06, 2020 |
| Acer          | EG43M                       | Desktop     | [52485c6237](https://linux-hardware.org/?probe=52485c6237) | Jun 06, 2020 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [747637fba1](https://linux-hardware.org/?probe=747637fba1) | Jun 05, 2020 |
| Qbex          | H61H2-M2                    | Desktop     | [77201fbc96](https://linux-hardware.org/?probe=77201fbc96) | Jun 05, 2020 |
| ASUSTek       | P8B75-M                     | Desktop     | [c2d585b9a7](https://linux-hardware.org/?probe=c2d585b9a7) | Jun 05, 2020 |
| Samsung       | DP700A3D-A01IT SEC_SW_RE... | All in one  | [9745994a4b](https://linux-hardware.org/?probe=9745994a4b) | Jun 05, 2020 |
| Acer          | Predator G3620              | Desktop     | [2b5cf13491](https://linux-hardware.org/?probe=2b5cf13491) | Jun 05, 2020 |
| Acer          | Predator G3620              | Desktop     | [6120afc333](https://linux-hardware.org/?probe=6120afc333) | Jun 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [9e464080d3](https://linux-hardware.org/?probe=9e464080d3) | Jun 04, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [0185bed721](https://linux-hardware.org/?probe=0185bed721) | Jun 04, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [867a7d511c](https://linux-hardware.org/?probe=867a7d511c) | Jun 04, 2020 |
| HP            | Pavilion 15                 | Notebook    | [c9413e0257](https://linux-hardware.org/?probe=c9413e0257) | Jun 04, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [546a8d0043](https://linux-hardware.org/?probe=546a8d0043) | Jun 04, 2020 |
| Samsung       | DP700A3D-A01IT SEC_SW_RE... | All in one  | [21f0a224b0](https://linux-hardware.org/?probe=21f0a224b0) | Jun 03, 2020 |
| Acer          | Extensa 5220                | Notebook    | [355c030bd6](https://linux-hardware.org/?probe=355c030bd6) | Jun 03, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [fdffe7ecc3](https://linux-hardware.org/?probe=fdffe7ecc3) | Jun 03, 2020 |
| Dell          | 0CT017                      | Desktop     | [7a9a09ec49](https://linux-hardware.org/?probe=7a9a09ec49) | Jun 03, 2020 |
| Dell          | Inspiron 5755               | Notebook    | [af7730ea54](https://linux-hardware.org/?probe=af7730ea54) | Jun 03, 2020 |
| Gigabyte      | H110N-CF                    | Desktop     | [3e9da1e0fc](https://linux-hardware.org/?probe=3e9da1e0fc) | Jun 02, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c9f4ab0214](https://linux-hardware.org/?probe=c9f4ab0214) | Jun 02, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [140ac80aa0](https://linux-hardware.org/?probe=140ac80aa0) | Jun 02, 2020 |
| Dell          | Latitude E6410              | Notebook    | [0bb101f56b](https://linux-hardware.org/?probe=0bb101f56b) | Jun 02, 2020 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [de39075832](https://linux-hardware.org/?probe=de39075832) | Jun 02, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [ae024bfee6](https://linux-hardware.org/?probe=ae024bfee6) | Jun 01, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [028577a611](https://linux-hardware.org/?probe=028577a611) | Jun 01, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [3ad2ae8185](https://linux-hardware.org/?probe=3ad2ae8185) | Jun 01, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [8774f73788](https://linux-hardware.org/?probe=8774f73788) | Jun 01, 2020 |
| ASUSTek       | M5A88-M                     | Desktop     | [afcc06eda5](https://linux-hardware.org/?probe=afcc06eda5) | May 31, 2020 |
| HP            | 1497                        | Desktop     | [5d74a91abd](https://linux-hardware.org/?probe=5d74a91abd) | May 31, 2020 |
| HP            | Notebook                    | Notebook    | [f449afb80f](https://linux-hardware.org/?probe=f449afb80f) | May 31, 2020 |
| Lenovo        | ThinkPad R500 273232G       | Notebook    | [f739a36965](https://linux-hardware.org/?probe=f739a36965) | May 31, 2020 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [659d266fe7](https://linux-hardware.org/?probe=659d266fe7) | May 30, 2020 |
| Acer          | Aspire 5251                 | Notebook    | [bb2843d8ef](https://linux-hardware.org/?probe=bb2843d8ef) | May 30, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [b3a2d13cf4](https://linux-hardware.org/?probe=b3a2d13cf4) | May 30, 2020 |
| Dell          | 0GXM1W A02                  | Desktop     | [dcfdf5c797](https://linux-hardware.org/?probe=dcfdf5c797) | May 30, 2020 |
| Positivo      | V142N_4G                    | Notebook    | [d802ce99e3](https://linux-hardware.org/?probe=d802ce99e3) | May 30, 2020 |
| Dell          | Latitude D630               | Notebook    | [f89cfc029e](https://linux-hardware.org/?probe=f89cfc029e) | May 29, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [458224380d](https://linux-hardware.org/?probe=458224380d) | May 29, 2020 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [e07f3a61e2](https://linux-hardware.org/?probe=e07f3a61e2) | May 29, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [315a06e722](https://linux-hardware.org/?probe=315a06e722) | May 29, 2020 |
| LIVEFAN       | Unknown                     | Notebook    | [529dcde0bb](https://linux-hardware.org/?probe=529dcde0bb) | May 29, 2020 |
| ASUSTek       | S500CA                      | Notebook    | [5ee4fa628a](https://linux-hardware.org/?probe=5ee4fa628a) | May 29, 2020 |
| HP            | EliteBook x360 1030 G3      | Convertible | [6da2ba3ed0](https://linux-hardware.org/?probe=6da2ba3ed0) | May 28, 2020 |
| HP            | 1497                        | Desktop     | [0260e1cca8](https://linux-hardware.org/?probe=0260e1cca8) | May 28, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [95565ae92d](https://linux-hardware.org/?probe=95565ae92d) | May 27, 2020 |
| HP            | Spectre x360 Convertible    | Convertible | [d258888474](https://linux-hardware.org/?probe=d258888474) | May 27, 2020 |
| MSI           | Z97 MPOWER                  | Desktop     | [526e3a4646](https://linux-hardware.org/?probe=526e3a4646) | May 27, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | Desktop     | [0315d9c9c4](https://linux-hardware.org/?probe=0315d9c9c4) | May 27, 2020 |
| ASUSTek       | B150M-A                     | Desktop     | [6e5665e630](https://linux-hardware.org/?probe=6e5665e630) | May 27, 2020 |
| ASUSTek       | B150M-A                     | Desktop     | [b56e76e2e2](https://linux-hardware.org/?probe=b56e76e2e2) | May 27, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [1beb03698d](https://linux-hardware.org/?probe=1beb03698d) | May 27, 2020 |
| ASRock        | 985GM-GS3 FX                | Desktop     | [bde47e7839](https://linux-hardware.org/?probe=bde47e7839) | May 27, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [92badc70b3](https://linux-hardware.org/?probe=92badc70b3) | May 27, 2020 |
| Lenovo        | ThinkPad W530 24479Q7       | Notebook    | [b0e7a334cf](https://linux-hardware.org/?probe=b0e7a334cf) | May 26, 2020 |
| Lenovo        | ThinkPad W530 24479Q7       | Notebook    | [288fd814c0](https://linux-hardware.org/?probe=288fd814c0) | May 26, 2020 |
| Dell          | Latitude E6330              | Notebook    | [8255a6bf31](https://linux-hardware.org/?probe=8255a6bf31) | May 26, 2020 |
| Dell          | 0M858N A01                  | Desktop     | [1f0f11722b](https://linux-hardware.org/?probe=1f0f11722b) | May 26, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [0cfc0d7106](https://linux-hardware.org/?probe=0cfc0d7106) | May 26, 2020 |
| Toshiba       | PORTEGE R600                | Notebook    | [705c8aa483](https://linux-hardware.org/?probe=705c8aa483) | May 25, 2020 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [19610eb160](https://linux-hardware.org/?probe=19610eb160) | May 25, 2020 |
| ASUSTek       | P7H55                       | Desktop     | [4533b1206a](https://linux-hardware.org/?probe=4533b1206a) | May 25, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [e8253aea47](https://linux-hardware.org/?probe=e8253aea47) | May 25, 2020 |
| ASUSTek       | F5SL                        | Notebook    | [947c9e7acf](https://linux-hardware.org/?probe=947c9e7acf) | May 25, 2020 |
| ASUSTek       | F5SL                        | Notebook    | [f61f397a5c](https://linux-hardware.org/?probe=f61f397a5c) | May 25, 2020 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [c41528bf74](https://linux-hardware.org/?probe=c41528bf74) | May 25, 2020 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [122ff2be33](https://linux-hardware.org/?probe=122ff2be33) | May 25, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [daa996c0be](https://linux-hardware.org/?probe=daa996c0be) | May 24, 2020 |
| Acer          | Prespa M                    | Notebook    | [890a8d820f](https://linux-hardware.org/?probe=890a8d820f) | May 24, 2020 |
| Acer          | TravelMate 6594e            | Notebook    | [defbcb9f08](https://linux-hardware.org/?probe=defbcb9f08) | May 24, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | Desktop     | [66e358b202](https://linux-hardware.org/?probe=66e358b202) | May 24, 2020 |
| Toshiba       | Satellite L745              | Notebook    | [e4b4a942e4](https://linux-hardware.org/?probe=e4b4a942e4) | May 24, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [63e6a5472b](https://linux-hardware.org/?probe=63e6a5472b) | May 24, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c993e8d96e](https://linux-hardware.org/?probe=c993e8d96e) | May 24, 2020 |
| AOpen         | D1001 C26361-D1001          | Desktop     | [1c0ca9ced6](https://linux-hardware.org/?probe=1c0ca9ced6) | May 24, 2020 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [40df9d3c34](https://linux-hardware.org/?probe=40df9d3c34) | May 24, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [5729788ce3](https://linux-hardware.org/?probe=5729788ce3) | May 24, 2020 |
| Lenovo        | ThinkPad E480 20KN001NMC    | Notebook    | [1dcc1bede5](https://linux-hardware.org/?probe=1dcc1bede5) | May 24, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [884a9eb467](https://linux-hardware.org/?probe=884a9eb467) | May 24, 2020 |
| Acer          | Aspire ES1-311              | Notebook    | [cb043c4b53](https://linux-hardware.org/?probe=cb043c4b53) | May 24, 2020 |
| Notebook      | N230WU                      | Notebook    | [4c723c24e5](https://linux-hardware.org/?probe=4c723c24e5) | May 23, 2020 |
| ASUSTek       | S500CA                      | Notebook    | [72ff9768d5](https://linux-hardware.org/?probe=72ff9768d5) | May 23, 2020 |
| HP            | ENVY 17                     | Notebook    | [0c49cafa69](https://linux-hardware.org/?probe=0c49cafa69) | May 23, 2020 |
| Medion        | E122X                       | Notebook    | [e371cad88d](https://linux-hardware.org/?probe=e371cad88d) | May 23, 2020 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [07c8fff8c3](https://linux-hardware.org/?probe=07c8fff8c3) | May 23, 2020 |
| Lenovo        | ThinkPad T420 4178A53       | Notebook    | [9962738ccd](https://linux-hardware.org/?probe=9962738ccd) | May 22, 2020 |
| Lenovo        | ThinkPad T61 889701U        | Notebook    | [d23b6592e3](https://linux-hardware.org/?probe=d23b6592e3) | May 22, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [85443edb8d](https://linux-hardware.org/?probe=85443edb8d) | May 22, 2020 |
| HP            | ENVY 17                     | Notebook    | [8ad079156b](https://linux-hardware.org/?probe=8ad079156b) | May 22, 2020 |
| Clevo         | P170HMx                     | Notebook    | [b396ced50a](https://linux-hardware.org/?probe=b396ced50a) | May 21, 2020 |
| HP            | Presario C700               | Notebook    | [272a600f69](https://linux-hardware.org/?probe=272a600f69) | May 21, 2020 |
| MSI           | GE65 Raider 9SE             | Notebook    | [25b78cf2ec](https://linux-hardware.org/?probe=25b78cf2ec) | May 20, 2020 |
| Gigabyte      | P55M-UD2                    | Desktop     | [6898645243](https://linux-hardware.org/?probe=6898645243) | May 20, 2020 |
| Acer          | Aspire E5-771G              | Notebook    | [f7b2da81eb](https://linux-hardware.org/?probe=f7b2da81eb) | May 20, 2020 |
| HP            | ENVY 17                     | Notebook    | [d23283d49c](https://linux-hardware.org/?probe=d23283d49c) | May 19, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [f88515ee3b](https://linux-hardware.org/?probe=f88515ee3b) | May 19, 2020 |
| HP            | Notebook                    | Notebook    | [035439ee14](https://linux-hardware.org/?probe=035439ee14) | May 18, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [a623e40ce4](https://linux-hardware.org/?probe=a623e40ce4) | May 18, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [986ae187fd](https://linux-hardware.org/?probe=986ae187fd) | May 18, 2020 |
| ASRock        | N68-GS4 FX                  | Desktop     | [93091cc8d8](https://linux-hardware.org/?probe=93091cc8d8) | May 17, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [8a0cfc27c5](https://linux-hardware.org/?probe=8a0cfc27c5) | May 17, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| HP            | G42                         | Notebook    | [832933728c](https://linux-hardware.org/?probe=832933728c) | May 17, 2020 |
| Dell          | Inspiron 13-5368            | Notebook    | [3374aba2b6](https://linux-hardware.org/?probe=3374aba2b6) | May 17, 2020 |
| Acer          | Aspire XC-230               | Desktop     | [20a5ed6ba5](https://linux-hardware.org/?probe=20a5ed6ba5) | May 17, 2020 |
| Acer          | Aspire XC-230               | Desktop     | [848203d79a](https://linux-hardware.org/?probe=848203d79a) | May 16, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [603bccc705](https://linux-hardware.org/?probe=603bccc705) | May 16, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [0c373b0975](https://linux-hardware.org/?probe=0c373b0975) | May 16, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [bc8159c07e](https://linux-hardware.org/?probe=bc8159c07e) | May 16, 2020 |
| Acer          | Aspire_8950G                | Notebook    | [63d11ebb5a](https://linux-hardware.org/?probe=63d11ebb5a) | May 16, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [9a52c07d15](https://linux-hardware.org/?probe=9a52c07d15) | May 16, 2020 |
| Apple         | MacBookPro2,2               | Notebook    | [e36974f7cc](https://linux-hardware.org/?probe=e36974f7cc) | May 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [96677ee210](https://linux-hardware.org/?probe=96677ee210) | May 16, 2020 |
| Dell          | 0T568R A00                  | Desktop     | [067d6bd987](https://linux-hardware.org/?probe=067d6bd987) | May 16, 2020 |
| Apple         | MacBookAir1,1               | Notebook    | [90d4b67805](https://linux-hardware.org/?probe=90d4b67805) | May 16, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [74c38f38a9](https://linux-hardware.org/?probe=74c38f38a9) | May 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [15d0451825](https://linux-hardware.org/?probe=15d0451825) | May 16, 2020 |
| Lenovo        | ThinkPad T480s 20L7001LM... | Notebook    | [b6a2b0bd14](https://linux-hardware.org/?probe=b6a2b0bd14) | May 16, 2020 |
| Razer         | Blade                       | Notebook    | [8f9c962e1a](https://linux-hardware.org/?probe=8f9c962e1a) | May 16, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [c8e1bcf62b](https://linux-hardware.org/?probe=c8e1bcf62b) | May 16, 2020 |
| HP            | Notebook                    | Notebook    | [17b0d4b1b2](https://linux-hardware.org/?probe=17b0d4b1b2) | May 16, 2020 |
| Acer          | Aspire 5741                 | Notebook    | [6ea2978d3e](https://linux-hardware.org/?probe=6ea2978d3e) | May 15, 2020 |
| Notebook      | W65_W67RB                   | Notebook    | [970c88b78b](https://linux-hardware.org/?probe=970c88b78b) | May 15, 2020 |
| Notebook      | W65_W67RB                   | Notebook    | [341206a6dd](https://linux-hardware.org/?probe=341206a6dd) | May 15, 2020 |
| Acer          | Extensa 5630                | Notebook    | [6131a1471a](https://linux-hardware.org/?probe=6131a1471a) | May 15, 2020 |
| ASUSTek       | P5KC                        | Desktop     | [430457f5ee](https://linux-hardware.org/?probe=430457f5ee) | May 15, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4d70fb1cea](https://linux-hardware.org/?probe=4d70fb1cea) | May 14, 2020 |
| Toshiba       | Satellite L505              | Notebook    | [7d745ed98a](https://linux-hardware.org/?probe=7d745ed98a) | May 14, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d8691a0cb1](https://linux-hardware.org/?probe=d8691a0cb1) | May 14, 2020 |
| Gigabyte      | X299X AORUS MASTER          | Desktop     | [e9d37a665e](https://linux-hardware.org/?probe=e9d37a665e) | May 14, 2020 |
| HP            | 339A                        | Desktop     | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| Toshiba       | Satellite L505              | Notebook    | [93a4312b88](https://linux-hardware.org/?probe=93a4312b88) | May 14, 2020 |
| Dell          | Precision M4800             | Notebook    | [72621ff337](https://linux-hardware.org/?probe=72621ff337) | May 13, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [18edcf9cc0](https://linux-hardware.org/?probe=18edcf9cc0) | May 12, 2020 |
| Gigabyte      | H81M-S2V                    | Desktop     | [735da03dae](https://linux-hardware.org/?probe=735da03dae) | May 12, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [fedf72db4b](https://linux-hardware.org/?probe=fedf72db4b) | May 12, 2020 |
| Dell          | Inspiron 11-3162            | Notebook    | [afa9d2d85a](https://linux-hardware.org/?probe=afa9d2d85a) | May 12, 2020 |
| ASUSTek       | 1015PE                      | Notebook    | [fe2737f573](https://linux-hardware.org/?probe=fe2737f573) | May 11, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b511620a0f](https://linux-hardware.org/?probe=b511620a0f) | May 11, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [26b8c415b9](https://linux-hardware.org/?probe=26b8c415b9) | May 11, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [2fe7775c8f](https://linux-hardware.org/?probe=2fe7775c8f) | May 11, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e9ce0e160a](https://linux-hardware.org/?probe=e9ce0e160a) | May 11, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [93c6b04873](https://linux-hardware.org/?probe=93c6b04873) | May 11, 2020 |
| Fujitsu Si... | LIFEBOOK C1410              | Notebook    | [af84a18545](https://linux-hardware.org/?probe=af84a18545) | May 11, 2020 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [4951f4a759](https://linux-hardware.org/?probe=4951f4a759) | May 11, 2020 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [1b9e4e9933](https://linux-hardware.org/?probe=1b9e4e9933) | May 11, 2020 |
| Fujitsu Si... | AMILO Xi 2550               | Notebook    | [ecbe56efa5](https://linux-hardware.org/?probe=ecbe56efa5) | May 11, 2020 |
| Fujitsu Si... | AMILO Xi 2550               | Notebook    | [20e12d59df](https://linux-hardware.org/?probe=20e12d59df) | May 11, 2020 |
| ASUSTek       | 1015PE                      | Notebook    | [556e006e89](https://linux-hardware.org/?probe=556e006e89) | May 11, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [84a92bf084](https://linux-hardware.org/?probe=84a92bf084) | May 11, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [6e911b9178](https://linux-hardware.org/?probe=6e911b9178) | May 11, 2020 |
| Clevo         | M540SR VT6363A              | Notebook    | [88ab93ca71](https://linux-hardware.org/?probe=88ab93ca71) | May 11, 2020 |
| Clevo         | M540SR VT6363A              | Notebook    | [d0895133b1](https://linux-hardware.org/?probe=d0895133b1) | May 11, 2020 |
| Toshiba       | Satellite C50-A-1DV         | Notebook    | [c4f8923ec1](https://linux-hardware.org/?probe=c4f8923ec1) | May 11, 2020 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [350782a4b1](https://linux-hardware.org/?probe=350782a4b1) | May 11, 2020 |
| HP            | Pavilion g6                 | Notebook    | [383dfd1cc0](https://linux-hardware.org/?probe=383dfd1cc0) | May 11, 2020 |
| MSI           | X299 GAMING M7 ACK          | Desktop     | [98aab5531b](https://linux-hardware.org/?probe=98aab5531b) | May 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ac3a34c4c0](https://linux-hardware.org/?probe=ac3a34c4c0) | May 11, 2020 |
| Acer          | Extensa 5630                | Notebook    | [fdeefe8947](https://linux-hardware.org/?probe=fdeefe8947) | May 10, 2020 |
| Fujitsu Si... | LIFEBOOK C1410              | Notebook    | [ad96f73112](https://linux-hardware.org/?probe=ad96f73112) | May 10, 2020 |
| Lenovo        | G400s 20244                 | Notebook    | [c53de49fbc](https://linux-hardware.org/?probe=c53de49fbc) | May 10, 2020 |
| Apple         | MacBookAir1,1               | Notebook    | [779a5f09e3](https://linux-hardware.org/?probe=779a5f09e3) | May 09, 2020 |
| Medion        | E5217                       | Notebook    | [4b29f60f4e](https://linux-hardware.org/?probe=4b29f60f4e) | May 09, 2020 |
| MSI           | CX61 2QF                    | Notebook    | [01e152927b](https://linux-hardware.org/?probe=01e152927b) | May 09, 2020 |
| Apple         | MacBookAir1,1               | Notebook    | [506802bbae](https://linux-hardware.org/?probe=506802bbae) | May 09, 2020 |
| Samsung       | NC20/NB20                   | Notebook    | [085b83a79c](https://linux-hardware.org/?probe=085b83a79c) | May 09, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [efad785981](https://linux-hardware.org/?probe=efad785981) | May 09, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [a91bfd9548](https://linux-hardware.org/?probe=a91bfd9548) | May 09, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [eaa4095c1a](https://linux-hardware.org/?probe=eaa4095c1a) | May 09, 2020 |
| HP            | Compaq 6715b (RM179UA#AB... | Notebook    | [4296f094b5](https://linux-hardware.org/?probe=4296f094b5) | May 09, 2020 |
| ASRock        | N68-GS4 FX                  | Desktop     | [8a18014920](https://linux-hardware.org/?probe=8a18014920) | May 09, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [78e4f8dc9f](https://linux-hardware.org/?probe=78e4f8dc9f) | May 09, 2020 |
| HP            | Pavilion dm4                | Notebook    | [bd82108066](https://linux-hardware.org/?probe=bd82108066) | May 08, 2020 |
| ASUSTek       | E205SA                      | Notebook    | [a45b866546](https://linux-hardware.org/?probe=a45b866546) | May 08, 2020 |
| MSI           | X99S SLI PLUS               | Desktop     | [a48b719552](https://linux-hardware.org/?probe=a48b719552) | May 08, 2020 |
| ASRock        | N68-GS4 FX                  | Desktop     | [f70ba23054](https://linux-hardware.org/?probe=f70ba23054) | May 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [050c997025](https://linux-hardware.org/?probe=050c997025) | May 08, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [3b00d6e44c](https://linux-hardware.org/?probe=3b00d6e44c) | May 08, 2020 |
| HP            | Compaq 6715b (RM179UA#AB... | Notebook    | [7687cc3b72](https://linux-hardware.org/?probe=7687cc3b72) | May 08, 2020 |
| HP            | 805D                        | Desktop     | [16daf16986](https://linux-hardware.org/?probe=16daf16986) | May 07, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [0bc279404d](https://linux-hardware.org/?probe=0bc279404d) | May 07, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [50334e7c7f](https://linux-hardware.org/?probe=50334e7c7f) | May 07, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [0088c78042](https://linux-hardware.org/?probe=0088c78042) | May 07, 2020 |
| Dell          | 0GU083 A00                  | Desktop     | [5f05efe407](https://linux-hardware.org/?probe=5f05efe407) | May 06, 2020 |
| Exo           | CloudbookE15                | Notebook    | [b9b02e2bec](https://linux-hardware.org/?probe=b9b02e2bec) | May 06, 2020 |
| BCM           | MX280NI                     | Desktop     | [69678caf19](https://linux-hardware.org/?probe=69678caf19) | May 06, 2020 |
| BCM           | MX280NI                     | Desktop     | [f8a9460c9e](https://linux-hardware.org/?probe=f8a9460c9e) | May 06, 2020 |
| ASUSTek       | E205SA                      | Notebook    | [82cb9394d8](https://linux-hardware.org/?probe=82cb9394d8) | May 06, 2020 |
| ASUSTek       | P8H61-I LX R2.0             | Desktop     | [0ac9cd75b4](https://linux-hardware.org/?probe=0ac9cd75b4) | May 06, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [e7912d8ef0](https://linux-hardware.org/?probe=e7912d8ef0) | May 06, 2020 |
| Dell          | 0T568R A00                  | Desktop     | [b2771ebd93](https://linux-hardware.org/?probe=b2771ebd93) | May 06, 2020 |
| Apple         | Mac-F22C86C8                | Mini pc     | [434aab6c89](https://linux-hardware.org/?probe=434aab6c89) | May 06, 2020 |
| Lenovo        | ThinkStation S30 0569B38    | Desktop     | [21286af23b](https://linux-hardware.org/?probe=21286af23b) | May 06, 2020 |
| EVGA          | P55 SLI LE E653 Ibex Pea... | Desktop     | [251ae449b6](https://linux-hardware.org/?probe=251ae449b6) | May 06, 2020 |
| HP            | Unknown                     | Notebook    | [a264169708](https://linux-hardware.org/?probe=a264169708) | May 06, 2020 |
| Toshiba       | Satellite L755              | Notebook    | [118ae8d50e](https://linux-hardware.org/?probe=118ae8d50e) | May 06, 2020 |
| HP            | Notebook                    | Notebook    | [27e6f036c6](https://linux-hardware.org/?probe=27e6f036c6) | May 05, 2020 |
| Exo           | CloudbookE15                | Notebook    | [651f6e4a76](https://linux-hardware.org/?probe=651f6e4a76) | May 05, 2020 |
| Exo           | CloudbookE15                | Notebook    | [101bb597a7](https://linux-hardware.org/?probe=101bb597a7) | May 05, 2020 |
| MSI           | Z68A-G45                    | Desktop     | [6a2075dd33](https://linux-hardware.org/?probe=6a2075dd33) | May 04, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [28c7267fc9](https://linux-hardware.org/?probe=28c7267fc9) | May 04, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [cdcaff95eb](https://linux-hardware.org/?probe=cdcaff95eb) | May 04, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [f5f2719121](https://linux-hardware.org/?probe=f5f2719121) | May 04, 2020 |
| ASUSTek       | X55A                        | Notebook    | [4b731fa568](https://linux-hardware.org/?probe=4b731fa568) | May 04, 2020 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [07ca6e636a](https://linux-hardware.org/?probe=07ca6e636a) | May 03, 2020 |
| Lenovo        | ThinkPad P53 20QN004WRT     | Notebook    | [c1903a008d](https://linux-hardware.org/?probe=c1903a008d) | May 03, 2020 |
| Lenovo        | ThinkCentre M91p 4524CB9    | Desktop     | [94dc4b06b1](https://linux-hardware.org/?probe=94dc4b06b1) | May 03, 2020 |
| HP            | Pavilion 15                 | Notebook    | [40862aa266](https://linux-hardware.org/?probe=40862aa266) | May 02, 2020 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [eb9a4676cb](https://linux-hardware.org/?probe=eb9a4676cb) | May 02, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [95aefb5e5e](https://linux-hardware.org/?probe=95aefb5e5e) | May 01, 2020 |
| Dell          | Precision 7740              | Notebook    | [98f79195c4](https://linux-hardware.org/?probe=98f79195c4) | May 01, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [e43d2cdc83](https://linux-hardware.org/?probe=e43d2cdc83) | Apr 30, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [1862a67c79](https://linux-hardware.org/?probe=1862a67c79) | Apr 30, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [1e4c905191](https://linux-hardware.org/?probe=1e4c905191) | Apr 30, 2020 |
| Lenovo        | ThinkPad SL410 2842K3U      | Notebook    | [e3a8739ead](https://linux-hardware.org/?probe=e3a8739ead) | Apr 29, 2020 |
| Dell          | 0FJ030                      | Desktop     | [8cae3f8b96](https://linux-hardware.org/?probe=8cae3f8b96) | Apr 29, 2020 |
| Lenovo        | ThinkPad Edge E130 3358C... | Notebook    | [2bc6ee441e](https://linux-hardware.org/?probe=2bc6ee441e) | Apr 29, 2020 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [12d882022e](https://linux-hardware.org/?probe=12d882022e) | Apr 29, 2020 |
| ASUSTek       | X401A1                      | Notebook    | [730d39b054](https://linux-hardware.org/?probe=730d39b054) | Apr 29, 2020 |
| HP            | Pavilion x360 11 Convert... | Convertible | [b52080da68](https://linux-hardware.org/?probe=b52080da68) | Apr 28, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [8481b529ee](https://linux-hardware.org/?probe=8481b529ee) | Apr 28, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [78415a9613](https://linux-hardware.org/?probe=78415a9613) | Apr 28, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [c57cc50f1f](https://linux-hardware.org/?probe=c57cc50f1f) | Apr 28, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [fcbff20d29](https://linux-hardware.org/?probe=fcbff20d29) | Apr 28, 2020 |
| ASRock        | AOD790GX/128M               | Desktop     | [8ba6b55d11](https://linux-hardware.org/?probe=8ba6b55d11) | Apr 28, 2020 |
| ASUSTek       | P5K                         | Desktop     | [c77f4d5237](https://linux-hardware.org/?probe=c77f4d5237) | Apr 28, 2020 |
| HP            | ProLiant DL360e Gen8        | Server      | [0469c4e1aa](https://linux-hardware.org/?probe=0469c4e1aa) | Apr 28, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [b98a1c50e8](https://linux-hardware.org/?probe=b98a1c50e8) | Apr 28, 2020 |
| Medion        | B350A4-EM                   | Desktop     | [3163f6a0fa](https://linux-hardware.org/?probe=3163f6a0fa) | Apr 28, 2020 |
| Toshiba       | Satellite L755              | Notebook    | [ae82feb6e1](https://linux-hardware.org/?probe=ae82feb6e1) | Apr 28, 2020 |
| Toshiba       | Satellite L755              | Notebook    | [e869421a7f](https://linux-hardware.org/?probe=e869421a7f) | Apr 28, 2020 |
| HP            | 3397                        | Desktop     | [bdcea30c27](https://linux-hardware.org/?probe=bdcea30c27) | Apr 27, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [afa4e06e15](https://linux-hardware.org/?probe=afa4e06e15) | Apr 27, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [ffb05ac445](https://linux-hardware.org/?probe=ffb05ac445) | Apr 27, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1c46568976](https://linux-hardware.org/?probe=1c46568976) | Apr 26, 2020 |
| EVGA          | 120-LF-E650                 | Desktop     | [b79bcdee65](https://linux-hardware.org/?probe=b79bcdee65) | Apr 26, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [90b21482b9](https://linux-hardware.org/?probe=90b21482b9) | Apr 26, 2020 |
| Lenovo        | ThinkPad 11e 20D90020US     | Notebook    | [1d8bd2f104](https://linux-hardware.org/?probe=1d8bd2f104) | Apr 26, 2020 |
| ASUSTek       | P8Z68-V                     | Desktop     | [a5d4bc9b8a](https://linux-hardware.org/?probe=a5d4bc9b8a) | Apr 25, 2020 |
| Apple         | Mac-F2208EC8                | Mini pc     | [e257409de8](https://linux-hardware.org/?probe=e257409de8) | Apr 25, 2020 |
| ASRock        | G31M-GS                     | Desktop     | [2c7362b9cb](https://linux-hardware.org/?probe=2c7362b9cb) | Apr 25, 2020 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [4672efc222](https://linux-hardware.org/?probe=4672efc222) | Apr 25, 2020 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [aed74d2030](https://linux-hardware.org/?probe=aed74d2030) | Apr 25, 2020 |
| Dell          | Latitude E6410              | Notebook    | [294557e292](https://linux-hardware.org/?probe=294557e292) | Apr 25, 2020 |
| HP            | Elite Dragonfly             | Convertible | [575f7dcc91](https://linux-hardware.org/?probe=575f7dcc91) | Apr 24, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [7fe6ce5446](https://linux-hardware.org/?probe=7fe6ce5446) | Apr 24, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [047b4bf38a](https://linux-hardware.org/?probe=047b4bf38a) | Apr 24, 2020 |
| Acer          | Extensa 5235                | Notebook    | [b7739ceed9](https://linux-hardware.org/?probe=b7739ceed9) | Apr 23, 2020 |
| Toshiba       | dynabook BX/571KW           | Notebook    | [9ba95d923c](https://linux-hardware.org/?probe=9ba95d923c) | Apr 22, 2020 |
| HP            | 3397                        | Desktop     | [f9141c1b9d](https://linux-hardware.org/?probe=f9141c1b9d) | Apr 20, 2020 |
| Dell          | Latitude E6540              | Notebook    | [0a2c664d30](https://linux-hardware.org/?probe=0a2c664d30) | Apr 19, 2020 |
| Toshiba       | dynabook BX/571KW           | Notebook    | [b8dba9c83d](https://linux-hardware.org/?probe=b8dba9c83d) | Apr 13, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [ede3c6ed12](https://linux-hardware.org/?probe=ede3c6ed12) | Apr 12, 2020 |
| Dell          | Latitude E6540              | Notebook    | [1daf9c5f1a](https://linux-hardware.org/?probe=1daf9c5f1a) | Apr 10, 2020 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [e42a1e57a6](https://linux-hardware.org/?probe=e42a1e57a6) | Apr 07, 2020 |
| Dell          | Latitude 3450               | Notebook    | [7b91402f3f](https://linux-hardware.org/?probe=7b91402f3f) | Apr 06, 2020 |
| Dell          | Latitude 3450               | Notebook    | [db82b8f83d](https://linux-hardware.org/?probe=db82b8f83d) | Apr 06, 2020 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [27dca0b99c](https://linux-hardware.org/?probe=27dca0b99c) | Apr 05, 2020 |
| Acer          | AOD260                      | Notebook    | [c3fe3f443d](https://linux-hardware.org/?probe=c3fe3f443d) | Apr 02, 2020 |
| HP            | ProBook 4540s               | Notebook    | [7d8a63ba3c](https://linux-hardware.org/?probe=7d8a63ba3c) | Feb 19, 2020 |
| ASUSTek       | GL753VD                     | Notebook    | [cc5e432717](https://linux-hardware.org/?probe=cc5e432717) | Feb 02, 2020 |
| Gigabyte      | H170M-DS3H-CF               | Desktop     | [28730747e6](https://linux-hardware.org/?probe=28730747e6) | Jan 07, 2020 |
| Unknown       | Unknown                     | Soc         | [eb16c41069](https://linux-hardware.org/?probe=eb16c41069) | Dec 14, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_20.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 97        | 4.89%   |
| 5.4.0-48-generic    | 53        | 2.67%   |
| 5.11.0-27-generic   | 48        | 2.42%   |
| 5.4.0-52-generic    | 47        | 2.37%   |
| 5.4.0-29-generic    | 46        | 2.32%   |
| 5.4.0-58-generic    | 45        | 2.27%   |
| 5.4.0-65-generic    | 42        | 2.12%   |
| 5.4.0-54-generic    | 40        | 2.02%   |
| 5.4.0-42-lowlatency | 40        | 2.02%   |
| 5.4.0-26-generic    | 38        | 1.92%   |
| 5.4.0-40-generic    | 35        | 1.77%   |
| 5.4.0-47-generic    | 33        | 1.66%   |
| 5.4.0-37-generic    | 33        | 1.66%   |
| 5.4.0-31-generic    | 30        | 1.51%   |
| 5.4.0-29-lowlatency | 27        | 1.36%   |
| 5.4.0-66-generic    | 26        | 1.31%   |
| 5.4.0-33-generic    | 25        | 1.26%   |
| 5.4.0-89-generic    | 23        | 1.16%   |
| 5.8.0-53-generic    | 22        | 1.11%   |
| 5.4.0-40-lowlatency | 21        | 1.06%   |
| 5.8.0-43-generic    | 20        | 1.01%   |
| 5.4.0-91-generic    | 20        | 1.01%   |
| 5.4.0-72-generic    | 20        | 1.01%   |
| 5.4.0-70-generic    | 20        | 1.01%   |
| 5.11.0-37-generic   | 20        | 1.01%   |
| 5.4.0-58-lowlatency | 19        | 0.96%   |
| 5.4.0-56-generic    | 19        | 0.96%   |
| 5.13.0-30-generic   | 19        | 0.96%   |
| 5.4.0-77-generic    | 18        | 0.91%   |
| 5.4.0-65-lowlatency | 18        | 0.91%   |
| 5.4.0-45-generic    | 18        | 0.91%   |
| 5.4.0-37-lowlatency | 18        | 0.91%   |
| 5.4.0-67-generic    | 17        | 0.86%   |
| 5.4.0-53-generic    | 17        | 0.86%   |
| 5.4.0-52-lowlatency | 17        | 0.86%   |
| 5.4.0-81-generic    | 16        | 0.81%   |
| 5.8.0-50-generic    | 15        | 0.76%   |
| 5.4.0-80-generic    | 15        | 0.76%   |
| 5.4.0-74-generic    | 15        | 0.76%   |
| 5.4.0-48-lowlatency | 15        | 0.76%   |
| 5.4.0-107-generic   | 15        | 0.76%   |
| 5.11.0-40-generic   | 15        | 0.76%   |
| 5.11.0-38-generic   | 15        | 0.76%   |
| 5.8.0-55-generic    | 14        | 0.71%   |
| 5.4.0-73-generic    | 14        | 0.71%   |
| 5.4.0-47-lowlatency | 14        | 0.71%   |
| 5.13.0-39-generic   | 14        | 0.71%   |
| 5.8.0-59-generic    | 13        | 0.66%   |
| 5.8.0-48-generic    | 13        | 0.66%   |
| 5.4.0-90-generic    | 13        | 0.66%   |
| 5.4.0-64-generic    | 13        | 0.66%   |
| 5.4.0-62-generic    | 13        | 0.66%   |
| 5.4.0-60-generic    | 13        | 0.66%   |
| 5.4.0-51-generic    | 13        | 0.66%   |
| 5.4.0-26-lowlatency | 13        | 0.66%   |
| 5.11.0-44-generic   | 12        | 0.61%   |
| 5.11.0-34-generic   | 12        | 0.61%   |
| 5.8.0-44-generic    | 11        | 0.55%   |
| 5.4.0-88-generic    | 11        | 0.55%   |
| 5.4.0-39-generic    | 11        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 1218      | 69.28%  |
| 5.11.0   | 199       | 11.32%  |
| 5.8.0    | 168       | 9.56%   |
| 5.13.0   | 103       | 5.86%   |
| 5.10.0   | 5         | 0.28%   |
| 5.6.0    | 3         | 0.17%   |
| 5.14.0   | 3         | 0.17%   |
| 5.9.0    | 2         | 0.11%   |
| 5.7.7    | 2         | 0.11%   |
| 5.7.6    | 2         | 0.11%   |
| 5.7.0    | 2         | 0.11%   |
| 5.3.0    | 2         | 0.11%   |
| 5.12.12  | 2         | 0.11%   |
| 5.12.10  | 2         | 0.11%   |
| 4.4.254  | 2         | 0.11%   |
| 4.15.0   | 2         | 0.11%   |
| 5.9.8    | 1         | 0.06%   |
| 5.9.6    | 1         | 0.06%   |
| 5.9.16   | 1         | 0.06%   |
| 5.9.14   | 1         | 0.06%   |
| 5.9.1    | 1         | 0.06%   |
| 5.8.5    | 1         | 0.06%   |
| 5.8.18   | 1         | 0.06%   |
| 5.8.16   | 1         | 0.06%   |
| 5.8.13   | 1         | 0.06%   |
| 5.8.1    | 1         | 0.06%   |
| 5.7.17   | 1         | 0.06%   |
| 5.7.1    | 1         | 0.06%   |
| 5.6.6    | 1         | 0.06%   |
| 5.6.19   | 1         | 0.06%   |
| 5.4.67   | 1         | 0.06%   |
| 5.4.65   | 1         | 0.06%   |
| 5.4.64   | 1         | 0.06%   |
| 5.4.107  | 1         | 0.06%   |
| 5.17.0   | 1         | 0.06%   |
| 5.16.0   | 1         | 0.06%   |
| 5.15.36  | 1         | 0.06%   |
| 5.15.1   | 1         | 0.06%   |
| 5.15.0   | 1         | 0.06%   |
| 5.14.9   | 1         | 0.06%   |
| 5.14.8   | 1         | 0.06%   |
| 5.14.2   | 1         | 0.06%   |
| 5.12.2   | 1         | 0.06%   |
| 5.12.17  | 1         | 0.06%   |
| 5.11.16  | 1         | 0.06%   |
| 5.11.11  | 1         | 0.06%   |
| 5.10.60  | 1         | 0.06%   |
| 5.10.33  | 1         | 0.06%   |
| 5.10.27  | 1         | 0.06%   |
| 5.10.13  | 1         | 0.06%   |
| 5.10.11  | 1         | 0.06%   |
| 4.9.253  | 1         | 0.06%   |
| 4.9.241  | 1         | 0.06%   |
| 4.9.140  | 1         | 0.06%   |
| 4.4.194  | 1         | 0.06%   |
| 4.4.0    | 1         | 0.06%   |
| 4.19.219 | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1222      | 69.59%  |
| 5.11    | 200       | 11.39%  |
| 5.8     | 173       | 9.85%   |
| 5.13    | 103       | 5.87%   |
| 5.10    | 10        | 0.57%   |
| 5.7     | 8         | 0.46%   |
| 5.9     | 7         | 0.4%    |
| 5.14    | 6         | 0.34%   |
| 5.6     | 5         | 0.28%   |
| 5.12    | 5         | 0.28%   |
| 4.4     | 4         | 0.23%   |
| 5.15    | 3         | 0.17%   |
| 4.9     | 3         | 0.17%   |
| 5.3     | 2         | 0.11%   |
| 4.15    | 2         | 0.11%   |
| 5.17    | 1         | 0.06%   |
| 5.16    | 1         | 0.06%   |
| 4.19    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1700      | 98.72%  |
| aarch64 | 17        | 0.99%   |
| armv7l  | 5         | 0.29%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 1654      | 96.05%  |
| GNOME           | 47        | 2.73%   |
| KDE5            | 5         | 0.29%   |
| i3              | 5         | 0.29%   |
| Unity           | 3         | 0.17%   |
| LXQt            | 2         | 0.12%   |
| GNOME Flashback | 2         | 0.12%   |
| X-Cinnamon      | 1         | 0.06%   |
| MATE            | 1         | 0.06%   |
| ICEWM           | 1         | 0.06%   |
| Cinnamon        | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1678      | 97.44%  |
| Tty     | 34        | 1.97%   |
| Wayland | 6         | 0.35%   |
| Web     | 3         | 0.17%   |
| Unknown | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 933       | 52.86%  |
| LightDM | 446       | 25.27%  |
| TDM     | 340       | 19.26%  |
| GDM     | 28        | 1.59%   |
| GDM3    | 11        | 0.62%   |
| SDDM    | 4         | 0.23%   |
| XDM     | 3         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 585       | 33.89%  |
| de_DE | 195       | 11.3%   |
| fr_FR | 162       | 9.39%   |
| pt_BR | 99        | 5.74%   |
| C     | 82        | 4.75%   |
| it_IT | 78        | 4.52%   |
| en_GB | 71        | 4.11%   |
| ru_RU | 61        | 3.53%   |
| en_CA | 45        | 2.61%   |
| es_ES | 38        | 2.2%    |
| pl_PL | 33        | 1.91%   |
| en_AU | 24        | 1.39%   |
| ja_JP | 21        | 1.22%   |
| nl_NL | 20        | 1.16%   |
| es_AR | 20        | 1.16%   |
| hu_HU | 18        | 1.04%   |
| en_IN | 12        | 0.7%    |
| cs_CZ | 11        | 0.64%   |
| es_MX | 10        | 0.58%   |
| sv_SE | 9         | 0.52%   |
| de_CH | 9         | 0.52%   |
| de_AT | 9         | 0.52%   |
| fr_CA | 8         | 0.46%   |
| fi_FI | 8         | 0.46%   |
| fr_BE | 7         | 0.41%   |
| ru_UA | 6         | 0.35%   |
| es_CO | 6         | 0.35%   |
| pt_PT | 5         | 0.29%   |
| ro_RO | 4         | 0.23%   |
| en_ZA | 4         | 0.23%   |
| en_NZ | 4         | 0.23%   |
| el_GR | 4         | 0.23%   |
| zh_TW | 3         | 0.17%   |
| zh_CN | 3         | 0.17%   |
| uk_UA | 3         | 0.17%   |
| tr_TR | 3         | 0.17%   |
| sl_SI | 3         | 0.17%   |
| nl_BE | 3         | 0.17%   |
| lt_LT | 3         | 0.17%   |
| id_ID | 3         | 0.17%   |
| fr_CH | 3         | 0.17%   |
| es_UY | 3         | 0.17%   |
| en_SG | 3         | 0.17%   |
| da_DK | 3         | 0.17%   |
| sk_SK | 2         | 0.12%   |
| nb_NO | 2         | 0.12%   |
| es_NI | 2         | 0.12%   |
| es_CL | 2         | 0.12%   |
| en_PH | 2         | 0.12%   |
| bg_BG | 2         | 0.12%   |
| th_TH | 1         | 0.06%   |
| lv_LV | 1         | 0.06%   |
| es_VE | 1         | 0.06%   |
| es_PE | 1         | 0.06%   |
| es_EC | 1         | 0.06%   |
| es_CR | 1         | 0.06%   |
| en_IL | 1         | 0.06%   |
| en_IE | 1         | 0.06%   |
| bs_BA | 1         | 0.06%   |
| ar_EG | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1028      | 59.32%  |
| EFI  | 705       | 40.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1585      | 91.83%  |
| Overlay | 81        | 4.69%   |
| Btrfs   | 25        | 1.45%   |
| Zfs     | 18        | 1.04%   |
| Xfs     | 8         | 0.46%   |
| Ext2    | 4         | 0.23%   |
| Ext3    | 3         | 0.17%   |
| Unknown | 2         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1107      | 64.17%  |
| GPT     | 374       | 21.68%  |
| MBR     | 244       | 14.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1440      | 82.24%  |
| Yes       | 311       | 17.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1112      | 63.72%  |
| Yes       | 633       | 36.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 292       | 16.96%  |
| ASUSTek Computer               | 252       | 14.63%  |
| Dell                           | 223       | 12.95%  |
| Lenovo                         | 212       | 12.31%  |
| Acer                           | 104       | 6.04%   |
| Gigabyte Technology            | 97        | 5.63%   |
| MSI                            | 73        | 4.24%   |
| ASRock                         | 70        | 4.07%   |
| Toshiba                        | 49        | 2.85%   |
| Apple                          | 34        | 1.97%   |
| Intel                          | 28        | 1.63%   |
| Medion                         | 26        | 1.51%   |
| Samsung Electronics            | 22        | 1.28%   |
| Fujitsu                        | 21        | 1.22%   |
| Sony                           | 15        | 0.87%   |
| Unknown                        | 15        | 0.87%   |
| Notebook                       | 12        | 0.7%    |
| Packard Bell                   | 10        | 0.58%   |
| Fujitsu Siemens                | 10        | 0.58%   |
| ECS                            | 10        | 0.58%   |
| Raspberry Pi Foundation        | 9         | 0.52%   |
| Positivo                       | 8         | 0.46%   |
| Pegatron                       | 7         | 0.41%   |
| Foxconn                        | 7         | 0.41%   |
| Clevo                          | 7         | 0.41%   |
| AMI                            | 5         | 0.29%   |
| HUAWEI                         | 4         | 0.23%   |
| Google                         | 4         | 0.23%   |
| Gateway                        | 4         | 0.23%   |
| eMachines                      | 4         | 0.23%   |
| Biostar                        | 4         | 0.23%   |
| TUXEDO                         | 3         | 0.17%   |
| Schenker                       | 3         | 0.17%   |
| Nvidia                         | 3         | 0.17%   |
| LG Electronics                 | 3         | 0.17%   |
| Itautec                        | 3         | 0.17%   |
| Alienware                      | 3         | 0.17%   |
| Supermicro                     | 2         | 0.12%   |
| sunxi                          | 2         | 0.12%   |
| Shuttle                        | 2         | 0.12%   |
| Semp Toshiba                   | 2         | 0.12%   |
| Razer                          | 2         | 0.12%   |
| NCR                            | 2         | 0.12%   |
| Multilaser                     | 2         | 0.12%   |
| Insyde                         | 2         | 0.12%   |
| Hardkernel                     | 2         | 0.12%   |
| GPU Company                    | 2         | 0.12%   |
| Exo                            | 2         | 0.12%   |
| EVGA                           | 2         | 0.12%   |
| Dynabook                       | 2         | 0.12%   |
| AAEON                          | 2         | 0.12%   |
| Xunlong                        | 1         | 0.06%   |
| WinFast                        | 1         | 0.06%   |
| VIT                            | 1         | 0.06%   |
| UNOWHY                         | 1         | 0.06%   |
| TrekStor                       | 1         | 0.06%   |
| System76                       | 1         | 0.06%   |
| Shenzhen Amediatech Technology | 1         | 0.06%   |
| Seco                           | 1         | 0.06%   |
| Quanta                         | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 23        | 1.34%   |
| ASUS All Series                        | 14        | 0.81%   |
| HP Notebook                            | 11        | 0.64%   |
| Dell Latitude D630                     | 8         | 0.46%   |
| Dell OptiPlex 7010                     | 7         | 0.41%   |
| HP Pavilion dv6                        | 6         | 0.35%   |
| Dell Latitude E6430                    | 6         | 0.35%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.35%   |
| HP 15                                  | 5         | 0.29%   |
| Dell OptiPlex 780                      | 5         | 0.29%   |
| MSI MS-7B79                            | 4         | 0.23%   |
| HP ProDesk 405 G6 Desktop Mini PC      | 4         | 0.23%   |
| HP Pavilion dv7                        | 4         | 0.23%   |
| HP EliteBook 8560p                     | 4         | 0.23%   |
| HP Compaq Elite 8300 SFF               | 4         | 0.23%   |
| Gigabyte B450M DS3H                    | 4         | 0.23%   |
| Dell OptiPlex 9020                     | 4         | 0.23%   |
| Dell OptiPlex 760                      | 4         | 0.23%   |
| Dell OptiPlex 755                      | 4         | 0.23%   |
| Dell OptiPlex 390                      | 4         | 0.23%   |
| Dell Latitude E6330                    | 4         | 0.23%   |
| ASUS TUF Gaming X570-PLUS              | 4         | 0.23%   |
| ASRock N68C-S UCC                      | 4         | 0.23%   |
| Apple Macmini4,1                       | 4         | 0.23%   |
| Toshiba Satellite A100                 | 3         | 0.17%   |
| Toshiba PORTEGE R930                   | 3         | 0.17%   |
| RPi Raspberry Pi 4 Model B Rev 1.4     | 3         | 0.17%   |
| RPi Raspberry Pi 4 Model B Rev 1.1     | 3         | 0.17%   |
| MSI MS-7A34                            | 3         | 0.17%   |
| MSI MS-7721                            | 3         | 0.17%   |
| MSI MS-7693                            | 3         | 0.17%   |
| Intel H61                              | 3         | 0.17%   |
| HP Z420 Workstation                    | 3         | 0.17%   |
| HP ProDesk 600 G1 SFF                  | 3         | 0.17%   |
| HP ProBook 4540s                       | 3         | 0.17%   |
| HP Presario C700                       | 3         | 0.17%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 3         | 0.17%   |
| HP Pavilion g7                         | 3         | 0.17%   |
| HP Pavilion g6                         | 3         | 0.17%   |
| HP Pavilion dv6500                     | 3         | 0.17%   |
| HP Pavilion 17                         | 3         | 0.17%   |
| HP Pavilion 15                         | 3         | 0.17%   |
| HP G42                                 | 3         | 0.17%   |
| HP EliteDesk 800 G1 SFF                | 3         | 0.17%   |
| HP Compaq dc7900 Convertible Minitower | 3         | 0.17%   |
| HP Compaq 8100 Elite SFF PC            | 3         | 0.17%   |
| HP Compaq 6200 Pro MT PC               | 3         | 0.17%   |
| Gigabyte H61M-USB3V                    | 3         | 0.17%   |
| Fujitsu ESPRIMO E705                   | 3         | 0.17%   |
| Dell Precision WorkStation T7400       | 3         | 0.17%   |
| Dell OptiPlex 990                      | 3         | 0.17%   |
| Dell Latitude E6540                    | 3         | 0.17%   |
| Dell Latitude 7480                     | 3         | 0.17%   |
| Dell Inspiron 7720                     | 3         | 0.17%   |
| Dell Inspiron 5566                     | 3         | 0.17%   |
| ASUS X553MA                            | 3         | 0.17%   |
| ASUS TUF Gaming B550M-PLUS             | 3         | 0.17%   |
| ASUS T100HAN                           | 3         | 0.17%   |
| ASUS P5K                               | 3         | 0.17%   |
| Apple MacPro5,1                        | 3         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 108       | 6.27%   |
| Acer Aspire           | 68        | 3.95%   |
| Dell Latitude         | 62        | 3.6%    |
| Dell Inspiron         | 56        | 3.25%   |
| HP Compaq             | 52        | 3.02%   |
| HP Pavilion           | 51        | 2.96%   |
| Dell OptiPlex         | 44        | 2.56%   |
| Toshiba Satellite     | 39        | 2.26%   |
| HP EliteBook          | 33        | 1.92%   |
| Lenovo IdeaPad        | 32        | 1.86%   |
| ASUS PRIME            | 24        | 1.39%   |
| Unknown               | 23        | 1.34%   |
| HP ProBook            | 21        | 1.22%   |
| ASUS VivoBook         | 21        | 1.22%   |
| HP Laptop             | 19        | 1.1%    |
| Lenovo ThinkCentre    | 17        | 0.99%   |
| Dell Precision        | 16        | 0.93%   |
| Dell Vostro           | 14        | 0.81%   |
| ASUS All              | 14        | 0.81%   |
| HP ProDesk            | 12        | 0.7%    |
| HP Notebook           | 12        | 0.7%    |
| ASUS TUF              | 12        | 0.7%    |
| Acer Extensa          | 11        | 0.64%   |
| Fujitsu ESPRIMO       | 10        | 0.58%   |
| RPi Raspberry         | 9         | 0.52%   |
| ASUS ROG              | 9         | 0.52%   |
| Dell Studio           | 8         | 0.46%   |
| Dell XPS              | 7         | 0.41%   |
| Lenovo IdeaCentre     | 6         | 0.35%   |
| HP ProLiant           | 6         | 0.35%   |
| HP ENVY               | 6         | 0.35%   |
| HP EliteDesk          | 6         | 0.35%   |
| Fujitsu LIFEBOOK      | 6         | 0.35%   |
| Toshiba PORTEGE       | 5         | 0.29%   |
| Packard Bell EasyNote | 5         | 0.29%   |
| HP Presario           | 5         | 0.29%   |
| HP 15                 | 5         | 0.29%   |
| Gigabyte B450M        | 5         | 0.29%   |
| Dell PowerEdge        | 5         | 0.29%   |
| Acer Veriton          | 5         | 0.29%   |
| Acer Nitro            | 5         | 0.29%   |
| Packard Bell IMEDIA   | 4         | 0.23%   |
| MSI MS-7B79           | 4         | 0.23%   |
| Medion Akoya          | 4         | 0.23%   |
| Lenovo ThinkStation   | 4         | 0.23%   |
| Lenovo IdeaPadFlex    | 4         | 0.23%   |
| HP OMEN               | 4         | 0.23%   |
| HP 255                | 4         | 0.23%   |
| HP 250                | 4         | 0.23%   |
| Gigabyte X570         | 4         | 0.23%   |
| Fujitsu Siemens AMILO | 4         | 0.23%   |
| ASUS P5KPL-AM         | 4         | 0.23%   |
| ASUS P5K              | 4         | 0.23%   |
| ASUS M5A78L-M         | 4         | 0.23%   |
| ASRock N68C-S         | 4         | 0.23%   |
| ASRock B450M          | 4         | 0.23%   |
| Apple Macmini4        | 4         | 0.23%   |
| Samsung R530          | 3         | 0.17%   |
| MSI MS-7A34           | 3         | 0.17%   |
| MSI MS-7721           | 3         | 0.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 167       | 9.7%    |
| 2011    | 159       | 9.23%   |
| 2013    | 149       | 8.65%   |
| 2010    | 139       | 8.07%   |
| 2019    | 125       | 7.26%   |
| 2018    | 114       | 6.62%   |
| 2008    | 112       | 6.5%    |
| 2014    | 106       | 6.16%   |
| 2009    | 105       | 6.1%    |
| 2020    | 103       | 5.98%   |
| 2017    | 102       | 5.92%   |
| 2007    | 91        | 5.28%   |
| 2015    | 82        | 4.76%   |
| 2016    | 67        | 3.89%   |
| 2021    | 41        | 2.38%   |
| 2006    | 29        | 1.68%   |
| Unknown | 20        | 1.16%   |
| 2005    | 10        | 0.58%   |
| 2022    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 914       | 53.08%  |
| Desktop        | 711       | 41.29%  |
| Mini pc        | 22        | 1.28%   |
| All in one     | 22        | 1.28%   |
| System on chip | 20        | 1.16%   |
| Convertible    | 20        | 1.16%   |
| Server         | 9         | 0.52%   |
| Tablet         | 4         | 0.23%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1620      | 93.8%   |
| Enabled  | 107       | 6.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1717      | 99.71%  |
| Yes  | 5         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 478       | 27.46%  |
| 4.01-8.0    | 366       | 21.02%  |
| 8.01-16.0   | 277       | 15.91%  |
| 16.01-24.0  | 261       | 14.99%  |
| 1.01-2.0    | 143       | 8.21%   |
| 32.01-64.0  | 101       | 5.8%    |
| 2.01-3.0    | 37        | 2.13%   |
| 64.01-256.0 | 36        | 2.07%   |
| 0.51-1.0    | 22        | 1.26%   |
| 24.01-32.0  | 19        | 1.09%   |
| 0.01-0.5    | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 872       | 46.46%  |
| 2.01-3.0   | 402       | 21.42%  |
| 0.51-1.0   | 233       | 12.41%  |
| 4.01-8.0   | 170       | 9.06%   |
| 3.01-4.0   | 141       | 7.51%   |
| 8.01-16.0  | 45        | 2.4%    |
| 24.01-32.0 | 5         | 0.27%   |
| 16.01-24.0 | 5         | 0.27%   |
| 0.01-0.5   | 4         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1030      | 58.32%  |
| 2      | 455       | 25.76%  |
| 3      | 153       | 8.66%   |
| 4      | 57        | 3.23%   |
| 5      | 28        | 1.59%   |
| 0      | 21        | 1.19%   |
| 6      | 10        | 0.57%   |
| 7      | 7         | 0.4%    |
| 10     | 2         | 0.11%   |
| 9      | 2         | 0.11%   |
| 8      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 927       | 53.68%  |
| No        | 800       | 46.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1565      | 90.83%  |
| No        | 158       | 9.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1241      | 71.53%  |
| No        | 494       | 28.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 951       | 54.59%  |
| Yes       | 791       | 45.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 313       | 18.1%   |
| Germany                | 234       | 13.53%  |
| France                 | 167       | 9.66%   |
| Brazil                 | 106       | 6.13%   |
| Canada                 | 90        | 5.21%   |
| Italy                  | 89        | 5.15%   |
| Russia                 | 74        | 4.28%   |
| UK                     | 70        | 4.05%   |
| Spain                  | 56        | 3.24%   |
| Netherlands            | 54        | 3.12%   |
| Poland                 | 37        | 2.14%   |
| Australia              | 26        | 1.5%    |
| Japan                  | 25        | 1.45%   |
| Argentina              | 24        | 1.39%   |
| Ukraine                | 21        | 1.21%   |
| Belgium                | 21        | 1.21%   |
| Sweden                 | 19        | 1.1%    |
| Hungary                | 18        | 1.04%   |
| Mexico                 | 17        | 0.98%   |
| Finland                | 17        | 0.98%   |
| Portugal               | 16        | 0.93%   |
| Czechia                | 15        | 0.87%   |
| Austria                | 14        | 0.81%   |
| India                  | 12        | 0.69%   |
| Greece                 | 12        | 0.69%   |
| Switzerland            | 11        | 0.64%   |
| Romania                | 11        | 0.64%   |
| Indonesia              | 11        | 0.64%   |
| Bulgaria               | 9         | 0.52%   |
| Turkey                 | 8         | 0.46%   |
| Slovenia               | 7         | 0.4%    |
| Norway                 | 7         | 0.4%    |
| Colombia               | 7         | 0.4%    |
| Denmark                | 6         | 0.35%   |
| Thailand               | 5         | 0.29%   |
| Lithuania              | 5         | 0.29%   |
| Uruguay                | 4         | 0.23%   |
| South Africa           | 4         | 0.23%   |
| Slovakia               | 4         | 0.23%   |
| Singapore              | 4         | 0.23%   |
| Serbia                 | 4         | 0.23%   |
| Philippines            | 4         | 0.23%   |
| New Zealand            | 4         | 0.23%   |
| Chile                  | 4         | 0.23%   |
| Belarus                | 4         | 0.23%   |
| Taiwan                 | 3         | 0.17%   |
| Latvia                 | 3         | 0.17%   |
| China                  | 3         | 0.17%   |
| Bosnia and Herzegovina | 3         | 0.17%   |
| Algeria                | 3         | 0.17%   |
| Venezuela              | 2         | 0.12%   |
| Puerto Rico            | 2         | 0.12%   |
| Nicaragua              | 2         | 0.12%   |
| Luxembourg             | 2         | 0.12%   |
| Israel                 | 2         | 0.12%   |
| Ireland                | 2         | 0.12%   |
| Iran                   | 2         | 0.12%   |
| Iceland                | 2         | 0.12%   |
| Estonia                | 2         | 0.12%   |
| Croatia                | 2         | 0.12%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 23        | 1.27%   |
| Québec           | 19        | 1.05%   |
| Berlin            | 19        | 1.05%   |
| Moscow            | 16        | 0.88%   |
| Hamburg           | 16        | 0.88%   |
| Munich            | 13        | 0.72%   |
| Warsaw            | 12        | 0.66%   |
| Sao Paulo         | 12        | 0.66%   |
| Budapest          | 12        | 0.66%   |
| Amsterdam         | 12        | 0.66%   |
| Sydney            | 11        | 0.61%   |
| Rome              | 11        | 0.61%   |
| Rio de Janeiro    | 10        | 0.55%   |
| Milan             | 10        | 0.55%   |
| Montreal          | 9         | 0.5%    |
| Madrid            | 9         | 0.5%    |
| Vancouver         | 8         | 0.44%   |
| Toronto           | 8         | 0.44%   |
| St Petersburg     | 8         | 0.44%   |
| Frankfurt am Main | 8         | 0.44%   |
| Cologne           | 8         | 0.44%   |
| Chicago           | 8         | 0.44%   |
| Barcelona         | 8         | 0.44%   |
| Athens            | 8         | 0.44%   |
| Vienna            | 7         | 0.39%   |
| Kyiv              | 7         | 0.39%   |
| Helsinki          | 7         | 0.39%   |
| Belo Horizonte    | 7         | 0.39%   |
| Lisbon            | 6         | 0.33%   |
| Leipzig           | 6         | 0.33%   |
| Karlsruhe         | 6         | 0.33%   |
| Sofia             | 5         | 0.28%   |
| Seattle           | 5         | 0.28%   |
| Saint Paul        | 5         | 0.28%   |
| Pittsburgh        | 5         | 0.28%   |
| Denver            | 5         | 0.28%   |
| Bamberg           | 5         | 0.28%   |
| Yokohama          | 4         | 0.22%   |
| Waterford         | 4         | 0.22%   |
| Turin             | 4         | 0.22%   |
| Tampere           | 4         | 0.22%   |
| Springfield       | 4         | 0.22%   |
| Singapore         | 4         | 0.22%   |
| Mannheim          | 4         | 0.22%   |
| Levis             | 4         | 0.22%   |
| Helmond           | 4         | 0.22%   |
| Hanover           | 4         | 0.22%   |
| Buenos Aires      | 4         | 0.22%   |
| Bogotá           | 4         | 0.22%   |
| Wuppertal         | 3         | 0.17%   |
| Wroclaw           | 3         | 0.17%   |
| Washington        | 3         | 0.17%   |
| Voskresensk       | 3         | 0.17%   |
| Vilnius           | 3         | 0.17%   |
| Varna             | 3         | 0.17%   |
| Suwanee           | 3         | 0.17%   |
| Shinjuku          | 3         | 0.17%   |
| Salvador          | 3         | 0.17%   |
| Rostov-on-Don     | 3         | 0.17%   |
| Riga              | 3         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 448       | 655    | 18.34%  |
| WDC                       | 425       | 599    | 17.4%   |
| Samsung Electronics       | 342       | 460    | 14%     |
| Toshiba                   | 161       | 195    | 6.59%   |
| Unknown                   | 125       | 151    | 5.12%   |
| Hitachi                   | 113       | 146    | 4.63%   |
| Kingston                  | 110       | 138    | 4.5%    |
| SanDisk                   | 94        | 121    | 3.85%   |
| Crucial                   | 70        | 89     | 2.87%   |
| HGST                      | 52        | 61     | 2.13%   |
| Intel                     | 49        | 73     | 2.01%   |
| SK Hynix                  | 38        | 42     | 1.56%   |
| A-DATA Technology         | 38        | 46     | 1.56%   |
| Fujitsu                   | 26        | 33     | 1.06%   |
| Micron Technology         | 22        | 24     | 0.9%    |
| China                     | 22        | 23     | 0.9%    |
| MAXTOR                    | 18        | 23     | 0.74%   |
| Patriot                   | 17        | 20     | 0.7%    |
| Intenso                   | 17        | 23     | 0.7%    |
| PNY                       | 14        | 19     | 0.57%   |
| Transcend                 | 12        | 13     | 0.49%   |
| Phison                    | 12        | 14     | 0.49%   |
| OCZ                       | 12        | 16     | 0.49%   |
| KIOXIA                    | 11        | 13     | 0.45%   |
| LITEON                    | 9         | 11     | 0.37%   |
| Apacer                    | 9         | 10     | 0.37%   |
| SPCC                      | 7         | 10     | 0.29%   |
| Silicon Motion            | 7         | 7      | 0.29%   |
| LITEONIT                  | 7         | 9      | 0.29%   |
| Hewlett-Packard           | 7         | 8      | 0.29%   |
| Apple                     | 7         | 10     | 0.29%   |
| JMicron                   | 6         | 6      | 0.25%   |
| ASMT                      | 6         | 8      | 0.25%   |
| Smartbuy                  | 4         | 4      | 0.16%   |
| KingSpec                  | 4         | 5      | 0.16%   |
| KingDian                  | 4         | 4      | 0.16%   |
| GOODRAM                   | 4         | 5      | 0.16%   |
| XPG                       | 3         | 8      | 0.12%   |
| USB3.0                    | 3         | 4      | 0.12%   |
| Team                      | 3         | 4      | 0.12%   |
| SABRENT                   | 3         | 3      | 0.12%   |
| Realtek Semiconductor     | 3         | 5      | 0.12%   |
| Netac                     | 3         | 3      | 0.12%   |
| Mushkin                   | 3         | 3      | 0.12%   |
| Lexar                     | 3         | 3      | 0.12%   |
| Kingmax                   | 3         | 3      | 0.12%   |
| Gigabyte Technology       | 3         | 4      | 0.12%   |
| DREVO                     | 3         | 3      | 0.12%   |
| Corsair                   | 3         | 3      | 0.12%   |
| Unknown                   | 3         | 3      | 0.12%   |
| WD MediaMax               | 2         | 2      | 0.08%   |
| Union Memory (Shenzhen)   | 2         | 2      | 0.08%   |
| TO Exter                  | 2         | 2      | 0.08%   |
| SUNEAST                   | 2         | 3      | 0.08%   |
| SSSTC                     | 2         | 2      | 0.08%   |
| SSK                       | 2         | 2      | 0.08%   |
| OWC                       | 2         | 2      | 0.08%   |
| OCZ-VERTEX3               | 2         | 2      | 0.08%   |
| Micron/Crucial Technology | 2         | 3      | 0.08%   |
| LaCie                     | 2         | 4      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 28        | 1.04%   |
| Seagate ST500DM002-1BD142 500GB     | 23        | 0.85%   |
| Kingston SA400S37240G 240GB SSD     | 23        | 0.85%   |
| Kingston SA400S37480G 480GB SSD     | 22        | 0.81%   |
| Samsung SSD 850 EVO 250GB           | 21        | 0.78%   |
| Samsung SSD 860 EVO 500GB           | 20        | 0.74%   |
| Seagate ST500LT012-1DG142 500GB     | 18        | 0.67%   |
| Unknown MMC Card  64GB              | 17        | 0.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 16        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 16        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB      | 16        | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB      | 14        | 0.52%   |
| Seagate Expansion 4TB               | 13        | 0.48%   |
| Samsung SSD 860 EVO 1TB             | 13        | 0.48%   |
| HGST HTS721010A9E630 1TB            | 13        | 0.48%   |
| Crucial CT500MX500SSD1 500GB        | 13        | 0.48%   |
| Unknown SD/MMC/MS PRO 999GB         | 12        | 0.44%   |
| Unknown MMC Card  128GB             | 12        | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB      | 12        | 0.44%   |
| Kingston SA400S37120G 120GB SSD     | 12        | 0.44%   |
| Toshiba MQ01ABD100 1TB              | 11        | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB      | 11        | 0.41%   |
| Kingston SV300S37A120G 120GB SSD    | 11        | 0.41%   |
| Unknown MMC Card  16GB              | 10        | 0.37%   |
| Toshiba MQ01ABF050 500GB            | 10        | 0.37%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 0.37%   |
| Seagate ST3500418AS 500GB           | 10        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB      | 10        | 0.37%   |
| Samsung NVMe SSD Drive 512GB        | 10        | 0.37%   |
| Samsung HM321HI 320GB               | 10        | 0.37%   |
| Seagate ST31000524AS 1TB            | 9         | 0.33%   |
| Patriot Burst 120GB SSD             | 9         | 0.33%   |
| HGST HTS541010A9E680 1TB            | 9         | 0.33%   |
| Crucial CT240BX500SSD1 240GB        | 9         | 0.33%   |
| Crucial CT1000MX500SSD1 1TB         | 9         | 0.33%   |
| Toshiba DT01ACA100 1TB              | 8         | 0.3%    |
| SK Hynix NVMe SSD Drive 256GB       | 8         | 0.3%    |
| Seagate ST380815AS 80GB             | 8         | 0.3%    |
| Seagate ST31000528AS 1TB            | 8         | 0.3%    |
| Seagate ST1000DM003-1ER162 1TB      | 8         | 0.3%    |
| SanDisk SSD PLUS 240GB              | 8         | 0.3%    |
| Samsung SSD 860 EVO 250GB           | 8         | 0.3%    |
| Samsung SSD 850 EVO 500GB           | 8         | 0.3%    |
| Samsung NVMe SSD Drive 1TB          | 8         | 0.3%    |
| WDC WD10EZEX-00BN5A0 1TB            | 7         | 0.26%   |
| Seagate ST9250315AS 250GB           | 7         | 0.26%   |
| Seagate ST4000DM004-2CV104 4TB      | 7         | 0.26%   |
| Seagate ST3250310AS 250GB           | 7         | 0.26%   |
| Samsung SSD 840 EVO 250GB           | 7         | 0.26%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 6         | 0.22%   |
| WDC WD10JPVX-22JC3T0 1TB            | 6         | 0.22%   |
| Toshiba MQ04ABF100 1TB              | 6         | 0.22%   |
| Toshiba MQ01ABD050 500GB            | 6         | 0.22%   |
| Seagate ST9500420AS 500GB           | 6         | 0.22%   |
| Seagate ST2000DM006-2DM164 2TB      | 6         | 0.22%   |
| Seagate ST2000DM001-1ER164 2TB      | 6         | 0.22%   |
| Seagate Backup+ Hub BK 8TB          | 6         | 0.22%   |
| Samsung SSD 860 QVO 1TB             | 6         | 0.22%   |
| Samsung SSD 840 Series 250GB        | 6         | 0.22%   |
| Samsung SSD 840 Series 120GB        | 6         | 0.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 440       | 644    | 34.51%  |
| WDC                 | 367       | 517    | 28.78%  |
| Toshiba             | 131       | 160    | 10.27%  |
| Hitachi             | 113       | 146    | 8.86%   |
| Samsung Electronics | 90        | 114    | 7.06%   |
| HGST                | 52        | 61     | 4.08%   |
| Fujitsu             | 26        | 33     | 2.04%   |
| MAXTOR              | 17        | 22     | 1.33%   |
| Unknown             | 13        | 15     | 1.02%   |
| ASMT                | 5         | 7      | 0.39%   |
| Intenso             | 4         | 5      | 0.31%   |
| WD MediaMax         | 2         | 2      | 0.16%   |
| SABRENT             | 2         | 2      | 0.16%   |
| Hewlett-Packard     | 2         | 2      | 0.16%   |
| USB3.0              | 1         | 2      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| LaCie               | 1         | 3      | 0.08%   |
| ICY BOX             | 1         | 1      | 0.08%   |
| HPE                 | 1         | 4      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| ExcelStor           | 1         | 1      | 0.08%   |
| CLOVER              | 1         | 1      | 0.08%   |
| Apricorn            | 1         | 1      | 0.08%   |
| Apple               | 1         | 1      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 176       | 227    | 22.83%  |
| Kingston            | 100       | 126    | 12.97%  |
| SanDisk             | 76        | 100    | 9.86%   |
| Crucial             | 65        | 84     | 8.43%   |
| WDC                 | 38        | 46     | 4.93%   |
| A-DATA Technology   | 33        | 40     | 4.28%   |
| Intel               | 22        | 33     | 2.85%   |
| China               | 21        | 22     | 2.72%   |
| Patriot             | 17        | 20     | 2.2%    |
| Micron Technology   | 16        | 17     | 2.08%   |
| Toshiba             | 14        | 17     | 1.82%   |
| PNY                 | 14        | 19     | 1.82%   |
| SK Hynix            | 12        | 12     | 1.56%   |
| Transcend           | 11        | 11     | 1.43%   |
| OCZ                 | 11        | 14     | 1.43%   |
| Intenso             | 11        | 13     | 1.43%   |
| LITEON              | 9         | 11     | 1.17%   |
| Apacer              | 9         | 10     | 1.17%   |
| SPCC                | 7         | 10     | 0.91%   |
| LITEONIT            | 7         | 9      | 0.91%   |
| Unknown             | 5         | 6      | 0.65%   |
| Smartbuy            | 4         | 4      | 0.52%   |
| KingDian            | 4         | 4      | 0.52%   |
| JMicron             | 4         | 4      | 0.52%   |
| Hewlett-Packard     | 4         | 6      | 0.52%   |
| GOODRAM             | 4         | 5      | 0.52%   |
| Apple               | 4         | 5      | 0.52%   |
| Team                | 3         | 4      | 0.39%   |
| Seagate             | 3         | 3      | 0.39%   |
| Mushkin             | 3         | 3      | 0.39%   |
| Lexar               | 3         | 3      | 0.39%   |
| KingSpec            | 3         | 4      | 0.39%   |
| Kingmax             | 3         | 3      | 0.39%   |
| DREVO               | 3         | 3      | 0.39%   |
| Corsair             | 3         | 3      | 0.39%   |
| USB3.0              | 2         | 2      | 0.26%   |
| TO Exter            | 2         | 2      | 0.26%   |
| SUNEAST             | 2         | 3      | 0.26%   |
| OWC                 | 2         | 2      | 0.26%   |
| OCZ-VERTEX3         | 2         | 2      | 0.26%   |
| Netac               | 2         | 2      | 0.26%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.26%   |
| Integral            | 2         | 2      | 0.26%   |
| Gigabyte Technology | 2         | 3      | 0.26%   |
| FORESEE             | 2         | 2      | 0.26%   |
| DOGFISH             | 2         | 3      | 0.26%   |
| Zheino              | 1         | 1      | 0.13%   |
| WDC WDS             | 1         | 1      | 0.13%   |
| Verbatim            | 1         | 1      | 0.13%   |
| Vaseky              | 1         | 1      | 0.13%   |
| TrekStor            | 1         | 1      | 0.13%   |
| TCSUNBOW            | 1         | 1      | 0.13%   |
| Super Talent        | 1         | 1      | 0.13%   |
| SABRENT             | 1         | 1      | 0.13%   |
| Qumox               | 1         | 1      | 0.13%   |
| PLEXTOR             | 1         | 1      | 0.13%   |
| Pioneer             | 1         | 1      | 0.13%   |
| PHISON              | 1         | 2      | 0.13%   |
| OCZ-VERTEX2         | 1         | 1      | 0.13%   |
| Mercury             | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1056      | 1747   | 48.6%   |
| SSD     | 690       | 957    | 31.75%  |
| NVMe    | 282       | 355    | 12.98%  |
| MMC     | 111       | 134    | 5.11%   |
| Unknown | 34        | 40     | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1456      | 2604   | 74.55%  |
| NVMe | 282       | 355    | 14.44%  |
| MMC  | 111       | 134    | 5.68%   |
| SAS  | 104       | 140    | 5.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1139      | 1697   | 62.58%  |
| 0.51-1.0   | 449       | 636    | 24.67%  |
| 1.01-2.0   | 119       | 188    | 6.54%   |
| 3.01-4.0   | 47        | 78     | 2.58%   |
| 4.01-10.0  | 35        | 55     | 1.92%   |
| 2.01-3.0   | 28        | 47     | 1.54%   |
| 10.01-20.0 | 2         | 2      | 0.11%   |
| 0          | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 553       | 31.12%  |
| 251-500        | 412       | 23.19%  |
| 501-1000       | 246       | 13.84%  |
| 51-100         | 135       | 7.6%    |
| 1001-2000      | 122       | 6.87%   |
| 21-50          | 98        | 5.51%   |
| More than 3000 | 80        | 4.5%    |
| 1-20           | 75        | 4.22%   |
| 2001-3000      | 45        | 2.53%   |
| Unknown        | 11        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 705       | 38.32%  |
| 21-50          | 327       | 17.77%  |
| 101-250        | 270       | 14.67%  |
| 51-100         | 210       | 11.41%  |
| 251-500        | 123       | 6.68%   |
| 501-1000       | 91        | 4.95%   |
| 1001-2000      | 52        | 2.83%   |
| More than 3000 | 30        | 1.63%   |
| 2001-3000      | 21        | 1.14%   |
| Unknown        | 11        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 2.1%    |
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 2.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 2.1%    |
| WDC WD7500BPKX-00HPJT0 752GB          | 2         | 2      | 1.4%    |
| WDC WD4000FYYZ-01UL1B1 4TB            | 2         | 3      | 1.4%    |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 2      | 1.4%    |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 1.4%    |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.4%    |
| Kingston SA400S37240G 240GB SSD       | 2         | 2      | 1.4%    |
| Hitachi HTS725032A9A364 320GB         | 2         | 2      | 1.4%    |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 1.4%    |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 1.4%    |
| WDC WD7500BPVT-80HXZT3 752GB          | 1         | 1      | 0.7%    |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.7%    |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 0.7%    |
| WDC WD5000LPVX-08V0TT5 500GB          | 1         | 1      | 0.7%    |
| WDC WD5000LPCX-00VHAT0 500GB          | 1         | 1      | 0.7%    |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 0.7%    |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 1      | 0.7%    |
| WDC WD5000AAKS-22V1A0 500GB           | 1         | 1      | 0.7%    |
| WDC WD400EB-00CPF0 40GB               | 1         | 1      | 0.7%    |
| WDC WD3200BEVT-75ZCT1 320GB           | 1         | 1      | 0.7%    |
| WDC WD3200AVJS-63TBA0 320GB           | 1         | 1      | 0.7%    |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 0.7%    |
| WDC WD3200AAJS-08L7A0 320GB           | 1         | 1      | 0.7%    |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 2      | 0.7%    |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 1      | 0.7%    |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 0.7%    |
| WDC WD1600AAJS-00L7A0 160GB           | 1         | 1      | 0.7%    |
| WDC WD10SPCX-24HWST1 1TB              | 1         | 1      | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 2      | 0.7%    |
| WDC WD10JPVT-08A1YT2 1TB              | 1         | 1      | 0.7%    |
| WDC WD10EZRX-00A8LB0 1TB              | 1         | 1      | 0.7%    |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 0.7%    |
| WDC WD10EFRX-68PJCN0 1TB              | 1         | 1      | 0.7%    |
| WDC WD10EFRX-68JCSN0 1TB              | 1         | 1      | 0.7%    |
| WDC WD10EAVS-22D7B0 1TB               | 1         | 1      | 0.7%    |
| WDC WD10EADX-22TDHB0 1TB              | 1         | 1      | 0.7%    |
| WDC WD10EADS-22M2B0 1TB               | 1         | 1      | 0.7%    |
| Unknown PSSBN016GA27MC0 16GB SSD      | 1         | 1      | 0.7%    |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 0.7%    |
| Toshiba MK7575GSX 752GB               | 1         | 1      | 0.7%    |
| Toshiba MK7559GSXP 752GB              | 1         | 2      | 0.7%    |
| Toshiba MK5076GSX 500GB               | 1         | 1      | 0.7%    |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 0.7%    |
| Toshiba MK3276GSX -63 320GB           | 1         | 2      | 0.7%    |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 0.7%    |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 0.7%    |
| Toshiba MK2552GSX 250GB               | 1         | 1      | 0.7%    |
| Toshiba HDWD110 1TB                   | 1         | 1      | 0.7%    |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 0.7%    |
| SK Hynix SH920 2.5 7MM 256GB SSD      | 1         | 1      | 0.7%    |
| SK Hynix SC401 SATA 512GB SSD         | 1         | 1      | 0.7%    |
| SK Hynix SC308 SATA 512GB SSD         | 1         | 1      | 0.7%    |
| SK Hynix HFS128G39MNC-2300A 128GB SSD | 1         | 1      | 0.7%    |
| SK Hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 0.7%    |
| Seagate ST980411ASG 80GB              | 1         | 1      | 0.7%    |
| Seagate ST980310AS 80GB               | 1         | 1      | 0.7%    |
| Seagate ST95005620AS 500GB            | 1         | 1      | 0.7%    |
| Seagate ST9500423AS 500GB             | 1         | 1      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 43     | 28.57%  |
| WDC                 | 31        | 36     | 22.14%  |
| Toshiba             | 13        | 15     | 9.29%   |
| Hitachi             | 10        | 10     | 7.14%   |
| Samsung Electronics | 8         | 10     | 5.71%   |
| SK Hynix            | 5         | 5      | 3.57%   |
| HGST                | 5         | 6      | 3.57%   |
| Kingston            | 4         | 4      | 2.86%   |
| Fujitsu             | 4         | 5      | 2.86%   |
| A-DATA Technology   | 3         | 4      | 2.14%   |
| OCZ                 | 2         | 2      | 1.43%   |
| Micron Technology   | 2         | 2      | 1.43%   |
| Intel               | 2         | 2      | 1.43%   |
| Unknown             | 1         | 1      | 0.71%   |
| SanDisk             | 1         | 1      | 0.71%   |
| Mushkin             | 1         | 1      | 0.71%   |
| MAXTOR              | 1         | 1      | 0.71%   |
| LDLC                | 1         | 1      | 0.71%   |
| ICY BOX             | 1         | 1      | 0.71%   |
| FORESEE             | 1         | 1      | 0.71%   |
| Crucial             | 1         | 1      | 0.71%   |
| China               | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |
| Apacer              | 1         | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 43     | 35.71%  |
| WDC                 | 31        | 36     | 27.68%  |
| Toshiba             | 13        | 15     | 11.61%  |
| Hitachi             | 10        | 10     | 8.93%   |
| Samsung Electronics | 7         | 9      | 6.25%   |
| HGST                | 5         | 6      | 4.46%   |
| Fujitsu             | 4         | 5      | 3.57%   |
| MAXTOR              | 1         | 1      | 0.89%   |
| ICY BOX             | 1         | 1      | 0.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 107       | 126    | 79.26%  |
| SSD  | 26        | 27     | 19.26%  |
| NVMe | 2         | 2      | 1.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB           | 1         | 1      | 33.33%  |
| Seagate ST500DM002-1BC142 500GB  | 1         | 1      | 33.33%  |
| A-DATA Technology SP800 32GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 1         | 1      | 33.33%  |
| Seagate           | 1         | 1      | 33.33%  |
| A-DATA Technology | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1158      | 2243   | 63.56%  |
| Works    | 528       | 832    | 28.98%  |
| Malfunc  | 133       | 155    | 7.3%    |
| Failed   | 3         | 3      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1185      | 60.61%  |
| AMD                              | 325       | 16.62%  |
| Samsung Electronics              | 98        | 5.01%   |
| Nvidia                           | 56        | 2.86%   |
| Sandisk                          | 45        | 2.3%    |
| ASMedia Technology               | 30        | 1.53%   |
| JMicron Technology               | 29        | 1.48%   |
| Marvell Technology Group         | 23        | 1.18%   |
| SK Hynix                         | 21        | 1.07%   |
| VIA Technologies                 | 16        | 0.82%   |
| Toshiba America Info Systems     | 14        | 0.72%   |
| Phison Electronics               | 12        | 0.61%   |
| KIOXIA                           | 12        | 0.61%   |
| Kingston Technology Company      | 10        | 0.51%   |
| ADATA Technology                 | 9         | 0.46%   |
| Silicon Motion                   | 8         | 0.41%   |
| LSI Logic / Symbios Logic        | 8         | 0.41%   |
| Micron Technology                | 7         | 0.36%   |
| Silicon Integrated Systems [SiS] | 6         | 0.31%   |
| Micron/Crucial Technology        | 6         | 0.31%   |
| Realtek Semiconductor            | 5         | 0.26%   |
| Broadcom / LSI                   | 5         | 0.26%   |
| Silicon Image                    | 4         | 0.2%    |
| Hewlett-Packard                  | 4         | 0.2%    |
| Union Memory (Shenzhen)          | 3         | 0.15%   |
| Seagate Technology               | 2         | 0.1%    |
| Promise Technology               | 2         | 0.1%    |
| Integrated Technology Express    | 2         | 0.1%    |
| Apple                            | 2         | 0.1%    |
| Adaptec                          | 2         | 0.1%    |
| Solid State Storage Technology   | 1         | 0.05%   |
| OCZ Technology Group             | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 201       | 8.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 91        | 3.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 79        | 3.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 64        | 2.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 62        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 60        | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 58        | 2.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 55        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 53        | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 53        | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 53        | 2.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 49        | 2.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 47        | 1.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 47        | 1.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 42        | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 36        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 36        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 34        | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 33        | 1.36%   |
| Intel SATA Controller [RAID mode]                                                       | 31        | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 31        | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 31        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 29        | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 28        | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 27        | 1.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24        | 0.99%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 21        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 21        | 0.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 21        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 21        | 0.86%   |
| Nvidia MCP61 SATA Controller                                                            | 20        | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 20        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 19        | 0.78%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 19        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18        | 0.74%   |
| Nvidia MCP61 IDE                                                                        | 17        | 0.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 17        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 16        | 0.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 16        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 16        | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 15        | 0.62%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14        | 0.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 14        | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 14        | 0.58%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 13        | 0.53%   |
| Samsung NVMe SSD Controller 980                                                         | 13        | 0.53%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 13        | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12        | 0.49%   |
| KIOXIA Non-Volatile memory controller                                                   | 12        | 0.49%   |
| AMD FCH IDE Controller                                                                  | 12        | 0.49%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12        | 0.49%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12        | 0.49%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 11        | 0.45%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11        | 0.45%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 11        | 0.45%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 11        | 0.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 11        | 0.45%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 10        | 0.41%   |
| Phison E12 NVMe Controller                                                              | 10        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1229      | 59.26%  |
| IDE  | 428       | 20.64%  |
| NVMe | 274       | 13.21%  |
| RAID | 127       | 6.12%   |
| SAS  | 9         | 0.43%   |
| SCSI | 7         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1302      | 75.61%  |
| AMD          | 396       | 23%     |
| ARM          | 22        | 1.28%   |
| CentaurHauls | 2         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 17        | 0.98%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 14        | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 12        | 0.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 12        | 0.69%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 11        | 0.64%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 10        | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 0.58%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 10        | 0.58%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 10        | 0.58%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 10        | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 9         | 0.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 9         | 0.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 9         | 0.52%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 9         | 0.52%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 9         | 0.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.46%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 8         | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.46%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 8         | 0.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 0.46%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 8         | 0.46%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 8         | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.46%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 8         | 0.46%   |
| AMD FX-8350 Eight-Core Processor              | 8         | 0.46%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 7         | 0.4%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.4%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.4%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 7         | 0.4%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 7         | 0.4%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 7         | 0.4%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 7         | 0.4%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 0.4%    |
| Intel Atom CPU Z3735F @ 1.33GHz               | 7         | 0.4%    |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 0.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.4%    |
| AMD Phenom II X4 955 Processor                | 7         | 0.4%    |
| AMD E1-1200 APU with Radeon HD Graphics       | 7         | 0.4%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 6         | 0.35%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 6         | 0.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 0.35%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 6         | 0.35%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 6         | 0.35%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 6         | 0.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 0.35%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 6         | 0.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 326       | 18.87%  |
| Intel Core i7           | 270       | 15.63%  |
| Intel Core i3           | 138       | 7.99%   |
| Intel Core 2 Duo        | 138       | 7.99%   |
| Intel Celeron           | 103       | 5.96%   |
| Intel Pentium           | 64        | 3.7%    |
| AMD Ryzen 5             | 58        | 3.36%   |
| Other                   | 52        | 3.01%   |
| Intel Xeon              | 48        | 2.78%   |
| Intel Atom              | 45        | 2.6%    |
| AMD Ryzen 7             | 41        | 2.37%   |
| Intel Pentium Dual-Core | 39        | 2.26%   |
| AMD FX                  | 25        | 1.45%   |
| Intel Core 2 Quad       | 24        | 1.39%   |
| Intel Core 2            | 22        | 1.27%   |
| AMD A8                  | 21        | 1.22%   |
| Intel Pentium Dual      | 19        | 1.1%    |
| AMD A6                  | 18        | 1.04%   |
| AMD Ryzen 3             | 16        | 0.93%   |
| AMD Phenom II X4        | 16        | 0.93%   |
| AMD Athlon II X2        | 16        | 0.93%   |
| AMD E1                  | 14        | 0.81%   |
| AMD A10                 | 14        | 0.81%   |
| AMD Athlon 64 X2        | 13        | 0.75%   |
| AMD A4                  | 12        | 0.69%   |
| AMD Ryzen 9             | 11        | 0.64%   |
| AMD E                   | 11        | 0.64%   |
| AMD Turion 64 X2 Mobile | 9         | 0.52%   |
| Intel Core i9           | 8         | 0.46%   |
| AMD Ryzen 7 PRO         | 8         | 0.46%   |
| AMD Athlon              | 8         | 0.46%   |
| AMD E2                  | 7         | 0.41%   |
| Intel Pentium Silver    | 6         | 0.35%   |
| Intel Genuine           | 6         | 0.35%   |
| AMD Ryzen 5 PRO         | 6         | 0.35%   |
| AMD Athlon II X4        | 6         | 0.35%   |
| Intel Pentium D         | 5         | 0.29%   |
| Intel Pentium 4         | 5         | 0.29%   |
| AMD Sempron             | 5         | 0.29%   |
| AMD Phenom II X6        | 5         | 0.29%   |
| AMD Phenom              | 5         | 0.29%   |
| AMD C-60                | 4         | 0.23%   |
| AMD Athlon II X3        | 4         | 0.23%   |
| AMD Athlon 64           | 4         | 0.23%   |
| Intel Pentium Gold      | 3         | 0.17%   |
| ARM Allwinner           | 3         | 0.17%   |
| AMD Turion 64 Mobile    | 3         | 0.17%   |
| AMD Ryzen Threadripper  | 3         | 0.17%   |
| AMD Athlon X2           | 3         | 0.17%   |
| AMD Athlon II           | 3         | 0.17%   |
| Intel Core m7           | 2         | 0.12%   |
| Intel Core m5           | 2         | 0.12%   |
| Intel Celeron Dual-Core | 2         | 0.12%   |
| AMD Turion              | 2         | 0.12%   |
| AMD Phenom II X2        | 2         | 0.12%   |
| AMD GX                  | 2         | 0.12%   |
| AMD C-50                | 2         | 0.12%   |
| AMD Athlon Dual Core    | 2         | 0.12%   |
| Intel Xeon Gold         | 1         | 0.06%   |
| Intel Core m3           | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 845       | 48.96%  |
| 4      | 618       | 35.81%  |
| 6      | 100       | 5.79%   |
| 8      | 73        | 4.23%   |
| 1      | 56        | 3.24%   |
| 12     | 15        | 0.87%   |
| 3      | 8         | 0.46%   |
| 16     | 6         | 0.35%   |
| 10     | 2         | 0.12%   |
| 24     | 1         | 0.06%   |
| 20     | 1         | 0.06%   |
| 14     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1702      | 98.84%  |
| 2      | 20        | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 897       | 52%     |
| 1      | 828       | 48%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1705      | 99.01%  |
| Unknown        | 17        | 0.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 200       | 11.41%  |
| 0x206a7    | 147       | 8.39%   |
| 0x306a9    | 128       | 7.3%    |
| 0x1067a    | 111       | 6.33%   |
| 0x306c3    | 88        | 5.02%   |
| 0x6fd      | 54        | 3.08%   |
| 0x20655    | 43        | 2.45%   |
| 0x10676    | 37        | 2.11%   |
| 0x506e3    | 34        | 1.94%   |
| 0x30678    | 32        | 1.83%   |
| 0x806ea    | 31        | 1.77%   |
| 0x010000c8 | 31        | 1.77%   |
| 0x906ea    | 28        | 1.6%    |
| 0x406e3    | 28        | 1.6%    |
| 0x40651    | 28        | 1.6%    |
| 0x08108109 | 27        | 1.54%   |
| 0x906e9    | 26        | 1.48%   |
| 0x806ec    | 25        | 1.43%   |
| 0x20652    | 24        | 1.37%   |
| 0x406c4    | 23        | 1.31%   |
| 0x806e9    | 22        | 1.25%   |
| 0x306d4    | 22        | 1.25%   |
| 0x6fb      | 21        | 1.2%    |
| 0x06000852 | 20        | 1.14%   |
| 0x05000119 | 20        | 1.14%   |
| 0x6f6      | 19        | 1.08%   |
| 0x08701021 | 19        | 1.08%   |
| 0x0800820d | 18        | 1.03%   |
| 0x106e5    | 17        | 0.97%   |
| 0xa0652    | 16        | 0.91%   |
| 0x806c1    | 16        | 0.91%   |
| 0x406c3    | 16        | 0.91%   |
| 0x07030105 | 16        | 0.91%   |
| 0x0700010f | 16        | 0.91%   |
| 0x706a1    | 15        | 0.86%   |
| 0x906ed    | 13        | 0.74%   |
| 0x706e5    | 13        | 0.74%   |
| 0x106ca    | 13        | 0.74%   |
| 0x06001119 | 13        | 0.74%   |
| 0x506c9    | 12        | 0.68%   |
| 0x03000027 | 12        | 0.68%   |
| 0x206d7    | 11        | 0.63%   |
| 0x08108102 | 11        | 0.63%   |
| 0x106a5    | 8         | 0.46%   |
| 0x08600106 | 8         | 0.46%   |
| 0x0810100b | 8         | 0.46%   |
| 0x010000db | 8         | 0.46%   |
| 0x6fa      | 7         | 0.4%    |
| 0x306f2    | 7         | 0.4%    |
| 0x206c2    | 7         | 0.4%    |
| 0x05000029 | 7         | 0.4%    |
| 0x010000c7 | 7         | 0.4%    |
| 0x306e4    | 6         | 0.34%   |
| 0x10661    | 6         | 0.34%   |
| 0x08701013 | 6         | 0.34%   |
| 0x30661    | 5         | 0.29%   |
| 0x0a50000c | 5         | 0.29%   |
| 0x08001137 | 5         | 0.29%   |
| 0x06003106 | 5         | 0.29%   |
| 0x0600063e | 5         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 169       | 9.8%    |
| SandyBridge      | 166       | 9.62%   |
| Penryn           | 159       | 9.22%   |
| IvyBridge        | 141       | 8.17%   |
| Haswell          | 140       | 8.12%   |
| Core             | 114       | 6.61%   |
| Westmere         | 80        | 4.64%   |
| Silvermont       | 77        | 4.46%   |
| Skylake          | 70        | 4.06%   |
| K10              | 61        | 3.54%   |
| Zen+             | 57        | 3.3%    |
| Zen 2            | 46        | 2.67%   |
| K8 Hammer        | 38        | 2.2%    |
| Piledriver       | 36        | 2.09%   |
| Zen              | 31        | 1.8%    |
| Unknown          | 30        | 1.74%   |
| Bobcat           | 28        | 1.62%   |
| CometLake        | 27        | 1.57%   |
| Nehalem          | 26        | 1.51%   |
| Broadwell        | 25        | 1.45%   |
| Puma             | 21        | 1.22%   |
| Goldmont plus    | 21        | 1.22%   |
| Bonnell          | 20        | 1.16%   |
| TigerLake        | 19        | 1.1%    |
| IceLake          | 19        | 1.1%    |
| Jaguar           | 17        | 0.99%   |
| Goldmont         | 16        | 0.93%   |
| Excavator        | 16        | 0.93%   |
| Zen 3            | 13        | 0.75%   |
| K10 Llano        | 12        | 0.7%    |
| NetBurst         | 11        | 0.64%   |
| K8 & K10 hybrid  | 7         | 0.41%   |
| Steamroller      | 6         | 0.35%   |
| Bulldozer        | 5         | 0.29%   |
| Alderlake Hybrid | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 947       | 48.94%  |
| Nvidia                           | 526       | 27.18%  |
| AMD                              | 443       | 22.89%  |
| Matrox Electronics Systems       | 9         | 0.47%   |
| VIA Technologies                 | 6         | 0.31%   |
| Silicon Integrated Systems [SiS] | 3         | 0.16%   |
| ASPEED Technology                | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 115       | 5.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 81        | 4.01%   |
| Intel Core Processor Integrated Graphics Controller                                      | 51        | 2.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 2.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 40        | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 39        | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 1.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 36        | 1.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 36        | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 35        | 1.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 35        | 1.73%   |
| Intel UHD Graphics 620                                                                   | 33        | 1.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 1.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 1.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 29        | 1.44%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 26        | 1.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 25        | 1.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 20        | 0.99%   |
| Intel HD Graphics 620                                                                    | 20        | 0.99%   |
| Intel HD Graphics 530                                                                    | 19        | 0.94%   |
| AMD Renoir                                                                               | 18        | 0.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 0.84%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 16        | 0.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 0.74%   |
| Intel HD Graphics 630                                                                    | 15        | 0.74%   |
| Intel HD Graphics 5500                                                                   | 15        | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 15        | 0.74%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 15        | 0.74%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 12        | 0.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 12        | 0.59%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 12        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 0.54%   |
| Intel HD Graphics 500                                                                    | 11        | 0.54%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 9         | 0.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 9         | 0.45%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 8         | 0.4%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 8         | 0.4%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 8         | 0.4%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 0.4%    |
| Nvidia TU117M                                                                            | 7         | 0.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7         | 0.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 7         | 0.35%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 7         | 0.35%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 7         | 0.35%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 7         | 0.35%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 7         | 0.35%   |
| AMD RS880 [Radeon HD 4250]                                                               | 7         | 0.35%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 7         | 0.35%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 6         | 0.3%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.3%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 6         | 0.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 744       | 43.01%  |
| 1 x Nvidia               | 355       | 20.52%  |
| 1 x AMD                  | 355       | 20.52%  |
| Intel + Nvidia           | 144       | 8.32%   |
| Intel + AMD              | 43        | 2.49%   |
| 2 x AMD                  | 25        | 1.45%   |
| Other                    | 23        | 1.33%   |
| AMD + Nvidia             | 16        | 0.92%   |
| 1 x Matrox               | 7         | 0.4%    |
| 1 x VIA                  | 6         | 0.35%   |
| 2 x Nvidia               | 4         | 0.23%   |
| 1 x SiS                  | 3         | 0.17%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.06%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.06%   |
| Nvidia + ASPEED          | 1         | 0.06%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.06%   |
| AMD + Matrox             | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1362      | 78.55%  |
| Proprietary | 294       | 16.96%  |
| Unknown     | 78        | 4.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 892       | 51.12%  |
| 0.01-0.5   | 280       | 16.05%  |
| 1.01-2.0   | 199       | 11.4%   |
| 0.51-1.0   | 192       | 11%     |
| 3.01-4.0   | 108       | 6.19%   |
| 7.01-8.0   | 37        | 2.12%   |
| 5.01-6.0   | 22        | 1.26%   |
| 2.01-3.0   | 7         | 0.4%    |
| 8.01-16.0  | 7         | 0.4%    |
| 4.01-5.0   | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 260       | 14.26%  |
| AU Optronics            | 198       | 10.86%  |
| LG Display              | 172       | 9.43%   |
| Dell                    | 113       | 6.2%    |
| Chimei Innolux          | 111       | 6.09%   |
| BOE                     | 100       | 5.49%   |
| Hewlett-Packard         | 77        | 4.22%   |
| Goldstar                | 76        | 4.17%   |
| Acer                    | 65        | 3.57%   |
| Philips                 | 47        | 2.58%   |
| Chi Mei Optoelectronics | 45        | 2.47%   |
| Lenovo                  | 44        | 2.41%   |
| Ancor Communications    | 36        | 1.97%   |
| BenQ                    | 31        | 1.7%    |
| AOC                     | 31        | 1.7%    |
| Apple                   | 27        | 1.48%   |
| LG Philips              | 23        | 1.26%   |
| HannStar                | 22        | 1.21%   |
| Unknown                 | 21        | 1.15%   |
| ViewSonic               | 20        | 1.1%    |
| Sony                    | 20        | 1.1%    |
| LG Electronics          | 18        | 0.99%   |
| Fujitsu Siemens         | 18        | 0.99%   |
| Iiyama                  | 17        | 0.93%   |
| Sharp                   | 16        | 0.88%   |
| Panasonic               | 14        | 0.77%   |
| InfoVision              | 13        | 0.71%   |
| NEC Computers           | 10        | 0.55%   |
| Toshiba                 | 8         | 0.44%   |
| PANDA                   | 8         | 0.44%   |
| Medion                  | 8         | 0.44%   |
| Eizo                    | 8         | 0.44%   |
| Vizio                   | 7         | 0.38%   |
| Lenovo Group Limited    | 5         | 0.27%   |
| ASUSTek Computer        | 5         | 0.27%   |
| Vestel Elektronik       | 4         | 0.22%   |
| MStar                   | 4         | 0.22%   |
| LPL                     | 4         | 0.22%   |
| LGD                     | 4         | 0.22%   |
| Idek Iiyama             | 4         | 0.22%   |
| DENON                   | 4         | 0.22%   |
| CPT                     | 4         | 0.22%   |
| CHR                     | 4         | 0.22%   |
| RTK                     | 3         | 0.16%   |
| Nvidia                  | 3         | 0.16%   |
| IBM                     | 3         | 0.16%   |
| Haier                   | 3         | 0.16%   |
| CSO                     | 3         | 0.16%   |
| Tech Concepts           | 2         | 0.11%   |
| Sceptre Tech            | 2         | 0.11%   |
| RS                      | 2         | 0.11%   |
| Packard Bell            | 2         | 0.11%   |
| ONN                     | 2         | 0.11%   |
| OEM                     | 2         | 0.11%   |
| MSI                     | 2         | 0.11%   |
| IOD                     | 2         | 0.11%   |
| Insignia                | 2         | 0.11%   |
| InnoLux Display         | 2         | 0.11%   |
| HPN                     | 2         | 0.11%   |
| Gateway                 | 2         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 9         | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 8         | 0.43%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 8         | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.43%   |
| Panasonic TV MEIA296 1360x768                                            | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.32%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 5         | 0.27%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 4         | 0.21%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 4         | 0.21%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch        | 4         | 0.21%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 4         | 0.21%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                         | 4         | 0.21%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.21%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.21%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                  | 4         | 0.21%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 4         | 0.21%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 4         | 0.21%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.21%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 4         | 0.21%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.21%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 4         | 0.21%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch            | 4         | 0.21%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 4         | 0.21%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 4         | 0.21%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch    | 4         | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 3         | 0.16%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch     | 3         | 0.16%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 3         | 0.16%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 3         | 0.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 3         | 0.16%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                       | 3         | 0.16%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                       | 3         | 0.16%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.16%   |
| LPL LCD Monitor 1440x900                                                 | 3         | 0.16%   |
| LG Philips LP154WX4-TLAB LPL3D01 1280x800 331x207mm 15.4-inch            | 3         | 0.16%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 3         | 0.16%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch              | 3         | 0.16%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.16%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.16%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 3         | 0.16%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 3         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 647       | 36.45%  |
| 1366x768 (WXGA)    | 400       | 22.54%  |
| 1280x1024 (SXGA)   | 92        | 5.18%   |
| 1600x900 (HD+)     | 89        | 5.01%   |
| 1440x900 (WXGA+)   | 87        | 4.9%    |
| 1280x800 (WXGA)    | 86        | 4.85%   |
| 3840x2160 (4K)     | 73        | 4.11%   |
| 1680x1050 (WSXGA+) | 66        | 3.72%   |
| 1920x1200 (WUXGA)  | 41        | 2.31%   |
| 2560x1440 (QHD)    | 39        | 2.2%    |
| Unknown            | 32        | 1.8%    |
| 1360x768           | 16        | 0.9%    |
| 3840x1080          | 12        | 0.68%   |
| 1024x600           | 12        | 0.68%   |
| 1600x1200          | 10        | 0.56%   |
| 1024x768 (XGA)     | 10        | 0.56%   |
| 1920x540           | 7         | 0.39%   |
| 1280x720 (HD)      | 6         | 0.34%   |
| 3440x1440          | 5         | 0.28%   |
| 2560x1600          | 5         | 0.28%   |
| 2560x1080          | 4         | 0.23%   |
| 5120x1440          | 3         | 0.17%   |
| 3840x1200          | 3         | 0.17%   |
| 3200x1800 (QHD+)   | 3         | 0.17%   |
| 3200x1080          | 3         | 0.17%   |
| 2880x1800          | 3         | 0.17%   |
| 3286x1080          | 2         | 0.11%   |
| 2960x1050          | 2         | 0.11%   |
| 2288x1287          | 2         | 0.11%   |
| 5760x2160          | 1         | 0.06%   |
| 5760x1200          | 1         | 0.06%   |
| 5280x2160          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 3840x2400          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |
| 3360x1080          | 1         | 0.06%   |
| 3280x1080          | 1         | 0.06%   |
| 3200x900           | 1         | 0.06%   |
| 2640x768           | 1         | 0.06%   |
| 2304x1440          | 1         | 0.06%   |
| 1920x1280          | 1         | 0.06%   |
| 1680x945           | 1         | 0.06%   |
| 1280x768           | 1         | 0.06%   |
| 1024x576           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 417       | 23.04%  |
| 14      | 153       | 8.45%   |
| Unknown | 153       | 8.45%   |
| 13      | 138       | 7.62%   |
| 17      | 127       | 7.02%   |
| 24      | 107       | 5.91%   |
| 21      | 96        | 5.3%    |
| 23      | 94        | 5.19%   |
| 19      | 90        | 4.97%   |
| 27      | 76        | 4.2%    |
| 18      | 49        | 2.71%   |
| 20      | 41        | 2.27%   |
| 22      | 40        | 2.21%   |
| 31      | 33        | 1.82%   |
| 12      | 32        | 1.77%   |
| 11      | 29        | 1.6%    |
| 10      | 16        | 0.88%   |
| 84      | 15        | 0.83%   |
| 72      | 10        | 0.55%   |
| 40      | 10        | 0.55%   |
| 54      | 9         | 0.5%    |
| 32      | 9         | 0.5%    |
| 34      | 8         | 0.44%   |
| 25      | 8         | 0.44%   |
| 26      | 7         | 0.39%   |
| 16      | 7         | 0.39%   |
| 52      | 5         | 0.28%   |
| 48      | 5         | 0.28%   |
| 28      | 4         | 0.22%   |
| 37      | 3         | 0.17%   |
| 57      | 2         | 0.11%   |
| 49      | 2         | 0.11%   |
| 47      | 2         | 0.11%   |
| 29      | 2         | 0.11%   |
| 142     | 1         | 0.06%   |
| 74      | 1         | 0.06%   |
| 69      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 60      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |
| 41      | 1         | 0.06%   |
| 39      | 1         | 0.06%   |
| 38      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 670       | 37.43%  |
| 501-600        | 271       | 15.14%  |
| 401-500        | 253       | 14.13%  |
| 351-400        | 156       | 8.72%   |
| Unknown        | 153       | 8.55%   |
| 201-300        | 145       | 8.1%    |
| 601-700        | 51        | 2.85%   |
| 1001-1500      | 28        | 1.56%   |
| 1501-2000      | 27        | 1.51%   |
| 701-800        | 17        | 0.95%   |
| 801-900        | 15        | 0.84%   |
| 901-1000       | 2         | 0.11%   |
| More than 2000 | 1         | 0.06%   |
| 101-200        | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1116      | 66.99%  |
| 16/10   | 271       | 16.27%  |
| Unknown | 141       | 8.46%   |
| 5/4     | 89        | 5.34%   |
| 4/3     | 25        | 1.5%    |
| 3/2     | 8         | 0.48%   |
| 21/9    | 8         | 0.48%   |
| 6/5     | 3         | 0.18%   |
| 32/9    | 1         | 0.06%   |
| 3.20    | 1         | 0.06%   |
| 1.96    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 419       | 23.28%  |
| 201-250        | 273       | 15.17%  |
| 81-90          | 233       | 12.94%  |
| 151-200        | 164       | 9.11%   |
| Unknown        | 153       | 8.5%    |
| 301-350        | 80        | 4.44%   |
| 141-150        | 74        | 4.11%   |
| 121-130        | 68        | 3.78%   |
| 351-500        | 53        | 2.94%   |
| 71-80          | 52        | 2.89%   |
| More than 1000 | 51        | 2.83%   |
| 251-300        | 49        | 2.72%   |
| 61-70          | 31        | 1.72%   |
| 51-60          | 29        | 1.61%   |
| 131-140        | 23        | 1.28%   |
| 501-1000       | 22        | 1.22%   |
| 41-50          | 16        | 0.89%   |
| 91-100         | 6         | 0.33%   |
| 111-120        | 3         | 0.17%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 641       | 36.65%  |
| 101-120       | 481       | 27.5%   |
| 121-160       | 365       | 20.87%  |
| Unknown       | 153       | 8.75%   |
| 161-240       | 50        | 2.86%   |
| 1-50          | 46        | 2.63%   |
| More than 240 | 13        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1425      | 81.48%  |
| 2     | 231       | 13.21%  |
| 0     | 74        | 4.23%   |
| 3     | 16        | 0.91%   |
| 4     | 3         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 911       | 34.89%  |
| Intel                                 | 752       | 28.8%   |
| Qualcomm Atheros                      | 313       | 11.99%  |
| Broadcom                              | 193       | 7.39%   |
| Nvidia                                | 46        | 1.76%   |
| Marvell Technology Group              | 45        | 1.72%   |
| Ralink Technology                     | 39        | 1.49%   |
| Broadcom Limited                      | 37        | 1.42%   |
| TP-Link                               | 32        | 1.23%   |
| Ralink                                | 31        | 1.19%   |
| Qualcomm Atheros Communications       | 17        | 0.65%   |
| Samsung Electronics                   | 15        | 0.57%   |
| Huawei Technologies                   | 13        | 0.5%    |
| D-Link System                         | 11        | 0.42%   |
| NetGear                               | 10        | 0.38%   |
| JMicron Technology                    | 10        | 0.38%   |
| Sierra Wireless                       | 9         | 0.34%   |
| VIA Technologies                      | 8         | 0.31%   |
| D-Link                                | 8         | 0.31%   |
| MediaTek                              | 7         | 0.27%   |
| Ericsson Business Mobile Networks     | 6         | 0.23%   |
| Edimax Technology                     | 6         | 0.23%   |
| DisplayLink                           | 6         | 0.23%   |
| Xiaomi                                | 5         | 0.19%   |
| Silicon Integrated Systems [SiS]      | 5         | 0.19%   |
| ASUSTek Computer                      | 5         | 0.19%   |
| Qualcomm                              | 4         | 0.15%   |
| Linksys                               | 4         | 0.15%   |
| Lenovo                                | 4         | 0.15%   |
| Belkin Components                     | 4         | 0.15%   |
| AVM                                   | 4         | 0.15%   |
| Attansic Technology                   | 4         | 0.15%   |
| ASIX Electronics                      | 4         | 0.15%   |
| Aquantia                              | 4         | 0.15%   |
| TRENDnet                              | 3         | 0.11%   |
| Microsoft                             | 3         | 0.11%   |
| Fibocom                               | 3         | 0.11%   |
| Dell                                  | 3         | 0.11%   |
| Motorola PCS                          | 2         | 0.08%   |
| LG Electronics                        | 2         | 0.08%   |
| IMC Networks                          | 2         | 0.08%   |
| Arduino SA                            | 2         | 0.08%   |
| AMD                                   | 2         | 0.08%   |
| 3Com                                  | 2         | 0.08%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| ZyDAS                                 | 1         | 0.04%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.04%   |
| Van Ooijen Technische Informatica     | 1         | 0.04%   |
| Toshiba                               | 1         | 0.04%   |
| STMicroelectronics                    | 1         | 0.04%   |
| Philips (or NXP)                      | 1         | 0.04%   |
| Novatek Microelectronics              | 1         | 0.04%   |
| Mellanox Technologies                 | 1         | 0.04%   |
| Manta                                 | 1         | 0.04%   |
| LSI                                   | 1         | 0.04%   |
| IBM                                   | 1         | 0.04%   |
| Hewlett-Packard                       | 1         | 0.04%   |
| Apple                                 | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 605       | 19.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 147       | 4.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 93        | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 49        | 1.62%   |
| Intel Wi-Fi 6 AX200                                                     | 44        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 42        | 1.39%   |
| Intel Ethernet Connection I217-LM                                       | 38        | 1.25%   |
| Intel Wireless 8265 / 8275                                              | 33        | 1.09%   |
| Intel Wireless 7260                                                     | 32        | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 31        | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 30        | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 30        | 0.99%   |
| Intel Wireless 7265                                                     | 28        | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 26        | 0.86%   |
| Intel 82579V Gigabit Network Connection                                 | 23        | 0.76%   |
| Intel I211 Gigabit Network Connection                                   | 22        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 22        | 0.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 21        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 19        | 0.63%   |
| Nvidia MCP61 Ethernet                                                   | 19        | 0.63%   |
| Intel Wireless-AC 9260                                                  | 19        | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                    | 19        | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 18        | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 18        | 0.59%   |
| Intel Wireless 8260                                                     | 18        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 17        | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 17        | 0.56%   |
| Intel 82577LM Gigabit Network Connection                                | 17        | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 16        | 0.53%   |
| Ralink MT7601U Wireless Adapter                                         | 16        | 0.53%   |
| Intel Wireless 3165                                                     | 16        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 0.53%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 0.53%   |
| Qualcomm Atheros AR9271 802.11n                                         | 15        | 0.49%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 0.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 15        | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                       | 14        | 0.46%   |
| Intel Ethernet Connection I217-V                                        | 14        | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 0.46%   |
| Intel 82567LM Gigabit Network Connection                                | 14        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 13        | 0.43%   |
| Intel Wireless 3160                                                     | 13        | 0.43%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 0.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 12        | 0.4%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 12        | 0.4%    |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.4%    |
| Intel 82574L Gigabit Network Connection                                 | 12        | 0.4%    |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 0.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 11        | 0.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 0.36%   |
| Intel Ethernet Connection (7) I219-V                                    | 11        | 0.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 0.36%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 11        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 493       | 37.49%  |
| Qualcomm Atheros                      | 256       | 19.47%  |
| Realtek Semiconductor                 | 236       | 17.95%  |
| Broadcom                              | 118       | 8.97%   |
| Ralink Technology                     | 39        | 2.97%   |
| Ralink                                | 31        | 2.36%   |
| TP-Link                               | 30        | 2.28%   |
| Broadcom Limited                      | 18        | 1.37%   |
| Qualcomm Atheros Communications       | 17        | 1.29%   |
| NetGear                               | 10        | 0.76%   |
| Sierra Wireless                       | 9         | 0.68%   |
| D-Link                                | 8         | 0.61%   |
| D-Link System                         | 7         | 0.53%   |
| Edimax Technology                     | 6         | 0.46%   |
| ASUSTek Computer                      | 5         | 0.38%   |
| Linksys                               | 4         | 0.3%    |
| Belkin Components                     | 4         | 0.3%    |
| AVM                                   | 4         | 0.3%    |
| TRENDnet                              | 3         | 0.23%   |
| Microsoft                             | 3         | 0.23%   |
| Fibocom                               | 3         | 0.23%   |
| IMC Networks                          | 2         | 0.15%   |
| ZyXEL Communications                  | 1         | 0.08%   |
| ZyDAS                                 | 1         | 0.08%   |
| Qualcomm                              | 1         | 0.08%   |
| Philips (or NXP)                      | 1         | 0.08%   |
| MEDIATEK                              | 1         | 0.08%   |
| Marvell Technology Group              | 1         | 0.08%   |
| Hewlett-Packard                       | 1         | 0.08%   |
| Dell                                  | 1         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 49        | 3.68%   |
| Intel Wi-Fi 6 AX200                                                     | 44        | 3.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 42        | 3.16%   |
| Intel Wireless 8265 / 8275                                              | 33        | 2.48%   |
| Intel Wireless 7260                                                     | 32        | 2.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 31        | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 30        | 2.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 30        | 2.26%   |
| Intel Wireless 7265                                                     | 28        | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 2.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 26        | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 1.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 19        | 1.43%   |
| Intel Wireless-AC 9260                                                  | 19        | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 18        | 1.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 18        | 1.35%   |
| Intel Wireless 8260                                                     | 18        | 1.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 17        | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 16        | 1.2%    |
| Ralink MT7601U Wireless Adapter                                         | 16        | 1.2%    |
| Intel Wireless 3165                                                     | 16        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.2%    |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.2%    |
| Qualcomm Atheros AR9271 802.11n                                         | 15        | 1.13%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 1.05%   |
| Intel Wireless 3160                                                     | 13        | 0.98%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 0.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 12        | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 12        | 0.9%    |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 11        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 0.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 11        | 0.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 10        | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.75%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 10        | 0.75%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 10        | 0.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 9         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 0.68%   |
| Intel WiFi Link 5100                                                    | 9         | 0.68%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.68%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 0.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 9         | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 8         | 0.6%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.6%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 7         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.53%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 7         | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 812       | 49.12%  |
| Intel                            | 448       | 27.1%   |
| Broadcom                         | 96        | 5.81%   |
| Qualcomm Atheros                 | 91        | 5.51%   |
| Nvidia                           | 46        | 2.78%   |
| Marvell Technology Group         | 44        | 2.66%   |
| Broadcom Limited                 | 19        | 1.15%   |
| Samsung Electronics              | 15        | 0.91%   |
| JMicron Technology               | 10        | 0.6%    |
| VIA Technologies                 | 8         | 0.48%   |
| Huawei Technologies              | 8         | 0.48%   |
| MediaTek                         | 6         | 0.36%   |
| DisplayLink                      | 6         | 0.36%   |
| Xiaomi                           | 5         | 0.3%    |
| Silicon Integrated Systems [SiS] | 5         | 0.3%    |
| Lenovo                           | 4         | 0.24%   |
| D-Link System                    | 4         | 0.24%   |
| Attansic Technology              | 4         | 0.24%   |
| ASIX Electronics                 | 4         | 0.24%   |
| Aquantia                         | 4         | 0.24%   |
| Qualcomm                         | 3         | 0.18%   |
| TP-Link                          | 2         | 0.12%   |
| Motorola PCS                     | 2         | 0.12%   |
| LG Electronics                   | 2         | 0.12%   |
| 3Com                             | 2         | 0.12%   |
| Mellanox Technologies            | 1         | 0.06%   |
| IBM                              | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 605       | 36.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 147       | 8.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 93        | 5.55%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 2.27%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 1.37%   |
| Intel I211 Gigabit Network Connection                             | 22        | 1.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22        | 1.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 21        | 1.25%   |
| Nvidia MCP61 Ethernet                                             | 19        | 1.13%   |
| Intel Ethernet Connection (2) I219-V                              | 19        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 17        | 1.01%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 14        | 0.84%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.78%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 0.6%    |
| Nvidia MCP77 Ethernet                                             | 10        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.6%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 10        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 9         | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 8         | 0.48%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 8         | 0.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 7         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 7         | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 7         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.42%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.36%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6         | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.36%   |
| Nvidia MCP51 Ethernet Controller                                  | 6         | 0.36%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 6         | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6         | 0.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.36%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.36%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.36%   |
| Intel 82573L Gigabit Ethernet Controller                          | 6         | 0.36%   |
| Huawei MAR-LX1A                                                   | 6         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5         | 0.3%    |
| Nvidia MCP79 Ethernet                                             | 5         | 0.3%    |
| Intel PRO/100 VE Network Connection                               | 5         | 0.3%    |
| Intel Ethernet Connection (5) I219-LM                             | 5         | 0.3%    |
| Intel 82578DC Gigabit Network Connection                          | 5         | 0.3%    |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1564      | 55.25%  |
| WiFi     | 1241      | 43.84%  |
| Modem    | 24        | 0.85%   |
| Unknown  | 2         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 987       | 55.73%  |
| Ethernet | 784       | 44.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 953       | 55.15%  |
| 1     | 682       | 39.47%  |
| 0     | 55        | 3.18%   |
| 3     | 27        | 1.56%   |
| 4     | 10        | 0.58%   |
| 5     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1502      | 85.98%  |
| Yes  | 245       | 14.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 324       | 40.6%   |
| Qualcomm Atheros Communications | 81        | 10.15%  |
| Realtek Semiconductor           | 73        | 9.15%   |
| Broadcom                        | 72        | 9.02%   |
| Cambridge Silicon Radio         | 54        | 6.77%   |
| Apple                           | 31        | 3.88%   |
| IMC Networks                    | 28        | 3.51%   |
| Lite-On Technology              | 27        | 3.38%   |
| Dell                            | 22        | 2.76%   |
| Hewlett-Packard                 | 18        | 2.26%   |
| Foxconn / Hon Hai               | 18        | 2.26%   |
| Ralink                          | 10        | 1.25%   |
| Toshiba                         | 8         | 1%      |
| ASUSTek Computer                | 8         | 1%      |
| Integrated System Solution      | 5         | 0.63%   |
| Alps Electric                   | 4         | 0.5%    |
| Chicony Electronics             | 3         | 0.38%   |
| Realtek                         | 2         | 0.25%   |
| Edimax Technology               | 2         | 0.25%   |
| TP-Link                         | 1         | 0.13%   |
| Taiyo Yuden                     | 1         | 0.13%   |
| Sitecom Europe                  | 1         | 0.13%   |
| Ralink Technology               | 1         | 0.13%   |
| Qcom                            | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |
| Conwise Technology              | 1         | 0.13%   |
| Unknown                         | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 134       | 16.77%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 54        | 6.76%   |
| Intel AX201 Bluetooth                                 | 47        | 5.88%   |
| Intel AX200 Bluetooth                                 | 45        | 5.63%   |
| Qualcomm Atheros  Bluetooth Device                    | 43        | 5.38%   |
| Realtek Bluetooth Radio                               | 35        | 4.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 35        | 4.38%   |
| Realtek  Bluetooth 4.2 Adapter                        | 22        | 2.75%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 22        | 2.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 18        | 2.25%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 16        | 2%      |
| Intel Wireless-AC 3168 Bluetooth                      | 14        | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                           | 13        | 1.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 12        | 1.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 12        | 1.5%    |
| Lite-On Bluetooth Device                              | 11        | 1.38%   |
| Apple Bluetooth Host Controller                       | 11        | 1.38%   |
| Ralink RT3290 Bluetooth                               | 10        | 1.25%   |
| IMC Networks Bluetooth Device                         | 10        | 1.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 10        | 1.25%   |
| Realtek RTL8723B Bluetooth                            | 8         | 1%      |
| Realtek 802.11ac WLAN Adapter                         | 8         | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 8         | 1%      |
| Lite-On Atheros AR3012 Bluetooth                      | 7         | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 7         | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 7         | 0.88%   |
| Apple Bluetooth HCI                                   | 7         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 6         | 0.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 6         | 0.75%   |
| IMC Networks Bluetooth Radio                          | 6         | 0.75%   |
| HP Broadcom 2070 Bluetooth Combo                      | 6         | 0.75%   |
| Dell DW375 Bluetooth Module                           | 6         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 6         | 0.75%   |
| Apple Bluetooth USB Host Controller                   | 6         | 0.75%   |
| Foxconn / Hon Hai BCM20702A0                          | 5         | 0.63%   |
| Broadcom BCM2045 Bluetooth                            | 5         | 0.63%   |
| Intel AX210 Bluetooth                                 | 4         | 0.5%    |
| Dell Wireless 365 Bluetooth                           | 4         | 0.5%    |
| Dell Wireless 360 Bluetooth                           | 4         | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                      | 4         | 0.5%    |
| Broadcom HP Portable Valentine                        | 4         | 0.5%    |
| Broadcom HP Portable SoftSailing                      | 4         | 0.5%    |
| Broadcom BCM2070 Bluetooth Device                     | 4         | 0.5%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 4         | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 4         | 0.5%    |
| Toshiba Integrated Bluetooth HCI                      | 3         | 0.38%   |
| Integrated System Solution Bluetooth Device           | 3         | 0.38%   |
| IMC Networks Bluetooth                                | 3         | 0.38%   |
| IMC Networks BCM20702A0                               | 3         | 0.38%   |
| Dell Wireless 370 Bluetooth Mini-card                 | 3         | 0.38%   |
| Chicony Bluetooth Radio                               | 3         | 0.38%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 3         | 0.38%   |
| Broadcom ANYCOM Blue USB-UHE 200/250                  | 3         | 0.38%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)            | 2         | 0.25%   |
| Realtek Bluetooth Radio                               | 2         | 0.25%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 2         | 0.25%   |
| Qualcomm Atheros Bluetooth                            | 2         | 0.25%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 2         | 0.25%   |
| IMC Networks Bluetooth USB Host Controller            | 2         | 0.25%   |
| IMC Networks Bluetooth module                         | 2         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1228      | 53.21%  |
| AMD                                             | 447       | 19.37%  |
| Nvidia                                          | 392       | 16.98%  |
| C-Media Electronics                             | 36        | 1.56%   |
| Creative Labs                                   | 28        | 1.21%   |
| Logitech                                        | 19        | 0.82%   |
| VIA Technologies                                | 16        | 0.69%   |
| Texas Instruments                               | 12        | 0.52%   |
| GN Netcom                                       | 9         | 0.39%   |
| Yamaha                                          | 8         | 0.35%   |
| Focusrite-Novation                              | 8         | 0.35%   |
| Silicon Integrated Systems [SiS]                | 6         | 0.26%   |
| Sennheiser Communications                       | 5         | 0.22%   |
| Realtek Semiconductor                           | 5         | 0.22%   |
| M-Audio                                         | 5         | 0.22%   |
| Lenovo                                          | 5         | 0.22%   |
| Generalplus Technology                          | 5         | 0.22%   |
| Plantronics                                     | 4         | 0.17%   |
| TEAC                                            | 3         | 0.13%   |
| JMTek                                           | 3         | 0.13%   |
| EGO SYStems                                     | 3         | 0.13%   |
| Creative Technology                             | 3         | 0.13%   |
| BEHRINGER International                         | 3         | 0.13%   |
| AKAI Professional M.I.                          | 3         | 0.13%   |
| ZOOM                                            | 2         | 0.09%   |
| PreSonus Audio Electronics                      | 2         | 0.09%   |
| KORG                                            | 2         | 0.09%   |
| ESI Audiotechnik                                | 2         | 0.09%   |
| Corsair                                         | 2         | 0.09%   |
| Cambridge Silicon Radio                         | 2         | 0.09%   |
| ASUSTek Computer                                | 2         | 0.09%   |
| Alesis                                          | 2         | 0.09%   |
| XMOS                                            | 1         | 0.04%   |
| Xilinx                                          | 1         | 0.04%   |
| Unknown                                         | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.04%   |
| Textech International                           | 1         | 0.04%   |
| TerraTec Electronic                             | 1         | 0.04%   |
| Tenx Technology                                 | 1         | 0.04%   |
| Syntek                                          | 1         | 0.04%   |
| Sony                                            | 1         | 0.04%   |
| SAVITECH                                        | 1         | 0.04%   |
| Samson Technologies                             | 1         | 0.04%   |
| Roland                                          | 1         | 0.04%   |
| Razer USA                                       | 1         | 0.04%   |
| QinHeng Electronics                             | 1         | 0.04%   |
| Pioneer DJ                                      | 1         | 0.04%   |
| Philips (or NXP)                                | 1         | 0.04%   |
| Onkyo                                           | 1         | 0.04%   |
| Native Instruments                              | 1         | 0.04%   |
| Microchip Technology                            | 1         | 0.04%   |
| Line6                                           | 1         | 0.04%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.04%   |
| Lautsprecher Teufel                             | 1         | 0.04%   |
| Holtek Semiconductor                            | 1         | 0.04%   |
| HiFimeDIY Audio                                 | 1         | 0.04%   |
| FiiO Electronics Technology                     | 1         | 0.04%   |
| Ensoniq                                         | 1         | 0.04%   |
| Elitegroup Computer Systems (ECS)               | 1         | 0.04%   |
| Elite Silicon                                   | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 148       | 5.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 138       | 5.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 93        | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 91        | 3.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 89        | 3.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 87        | 3.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 87        | 3.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 84        | 3.12%   |
| AMD FCH Azalia Controller                                                                         | 83        | 3.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 76        | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 69        | 2.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 64        | 2.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 54        | 2%      |
| AMD Kabini HDMI/DP Audio                                                                          | 43        | 1.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 39        | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 37        | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 36        | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 35        | 1.3%    |
| Nvidia High Definition Audio Controller                                                           | 34        | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 33        | 1.22%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 33        | 1.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 32        | 1.19%   |
| Intel 8 Series HD Audio Controller                                                                | 32        | 1.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 31        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 29        | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 28        | 1.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 27        | 1%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 0.93%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 23        | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 22        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 22        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 22        | 0.82%   |
| AMD Wrestler HDMI Audio                                                                           | 22        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 21        | 0.78%   |
| Nvidia MCP61 High Definition Audio                                                                | 20        | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 20        | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 19        | 0.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 16        | 0.59%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 16        | 0.59%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 16        | 0.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 16        | 0.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 15        | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 0.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 0.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 15        | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 0.48%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 13        | 0.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 0.48%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 13        | 0.48%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 12        | 0.45%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 0.41%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 11        | 0.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 11        | 0.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 11        | 0.41%   |
| AMD Trinity HDMI Audio Controller                                                                 | 11        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 197       | 22.04%  |
| SK Hynix                                         | 157       | 17.56%  |
| Unknown                                          | 139       | 15.55%  |
| Kingston                                         | 100       | 11.19%  |
| Micron Technology                                | 75        | 8.39%   |
| Crucial                                          | 52        | 5.82%   |
| Corsair                                          | 30        | 3.36%   |
| G.Skill                                          | 24        | 2.68%   |
| Elpida                                           | 23        | 2.57%   |
| Ramaxel Technology                               | 16        | 1.79%   |
| A-DATA Technology                                | 12        | 1.34%   |
| Nanya Technology                                 | 10        | 1.12%   |
| Unknown (ABCD)                                   | 7         | 0.78%   |
| Smart                                            | 7         | 0.78%   |
| Team                                             | 6         | 0.67%   |
| GOODRAM                                          | 6         | 0.67%   |
| Transcend                                        | 5         | 0.56%   |
| Unifosa                                          | 3         | 0.34%   |
| Patriot                                          | 3         | 0.34%   |
| Avant                                            | 2         | 0.22%   |
| Apacer                                           | 2         | 0.22%   |
| Walton Chaintech                                 | 1         | 0.11%   |
| V-GeN                                            | 1         | 0.11%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.11%   |
| Unknown (0x0043415455000000)                     | 1         | 0.11%   |
| Toshiba                                          | 1         | 0.11%   |
| TIMETEC                                          | 1         | 0.11%   |
| Teikon                                           | 1         | 0.11%   |
| SMART Brazil                                     | 1         | 0.11%   |
| SHARETRONIC                                      | 1         | 0.11%   |
| Sesame                                           | 1         | 0.11%   |
| Positivo                                         | 1         | 0.11%   |
| PNY                                              | 1         | 0.11%   |
| Memox                                            | 1         | 0.11%   |
| GEIL                                             | 1         | 0.11%   |
| CSX                                              | 1         | 0.11%   |
| Axiom                                            | 1         | 0.11%   |
| ASint Technology                                 | 1         | 0.11%   |
| Unknown                                          | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 10        | 1.02%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 9         | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 8         | 0.82%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 7         | 0.72%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 6         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                 | 6         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 6         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 6         | 0.61%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 6         | 0.61%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 6         | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 6         | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 6         | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 6         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 6         | 0.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 6         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 5         | 0.51%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 5         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 5         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 5         | 0.51%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 5         | 0.51%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 5         | 0.51%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                 | 5         | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s       | 5         | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 5         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 5         | 0.51%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s         | 5         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 4         | 0.41%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 4         | 0.41%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 4         | 0.41%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s      | 4         | 0.41%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 4         | 0.41%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s         | 4         | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 4         | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 4         | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 4         | 0.41%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s      | 4         | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 0.41%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 4         | 0.41%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 4         | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 4         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 4         | 0.41%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                   | 3         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                 | 3         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 3         | 0.31%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 3         | 0.31%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 3         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 3         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 3         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 3         | 0.31%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s        | 3         | 0.31%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s            | 3         | 0.31%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 3         | 0.31%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 3         | 0.31%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s         | 3         | 0.31%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s          | 3         | 0.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.31%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 3         | 0.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 3         | 0.31%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 0.31%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s      | 3         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 319       | 40.59%  |
| DDR4    | 290       | 36.9%   |
| DDR2    | 74        | 9.41%   |
| SDRAM   | 31        | 3.94%   |
| Unknown | 25        | 3.18%   |
| LPDDR4  | 19        | 2.42%   |
| LPDDR3  | 16        | 2.04%   |
| DDR     | 9         | 1.15%   |
| DRAM    | 2         | 0.25%   |
| EEPROM  | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 459       | 59.38%  |
| DIMM         | 276       | 35.71%  |
| Row Of Chips | 31        | 4.01%   |
| Chip         | 5         | 0.65%   |
| FB-DIMM      | 1         | 0.13%   |
| Unknown      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 284       | 33.29%  |
| 8192  | 252       | 29.54%  |
| 2048  | 160       | 18.76%  |
| 16384 | 91        | 10.67%  |
| 1024  | 48        | 5.63%   |
| 32768 | 11        | 1.29%   |
| 512   | 5         | 0.59%   |
| 1536  | 1         | 0.12%   |
| 1     | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 190       | 22.67%  |
| 2667    | 125       | 14.92%  |
| 1333    | 77        | 9.19%   |
| 3200    | 68        | 8.11%   |
| 2400    | 62        | 7.4%    |
| 667     | 38        | 4.53%   |
| 2133    | 34        | 4.06%   |
| 1334    | 34        | 4.06%   |
| 800     | 34        | 4.06%   |
| Unknown | 28        | 3.34%   |
| 1066    | 14        | 1.67%   |
| 1067    | 13        | 1.55%   |
| 1867    | 12        | 1.43%   |
| 1866    | 12        | 1.43%   |
| 3600    | 11        | 1.31%   |
| 3266    | 10        | 1.19%   |
| 2666    | 9         | 1.07%   |
| 4199    | 8         | 0.95%   |
| 4267    | 6         | 0.72%   |
| 1800    | 6         | 0.72%   |
| 533     | 6         | 0.72%   |
| 3000    | 5         | 0.6%    |
| 2048    | 4         | 0.48%   |
| 400     | 4         | 0.48%   |
| 3800    | 3         | 0.36%   |
| 49926   | 2         | 0.24%   |
| 3400    | 2         | 0.24%   |
| 2800    | 2         | 0.24%   |
| 2733    | 2         | 0.24%   |
| 2200    | 2         | 0.24%   |
| 1639    | 2         | 0.24%   |
| 975     | 2         | 0.24%   |
| 4333    | 1         | 0.12%   |
| 4000    | 1         | 0.12%   |
| 3533    | 1         | 0.12%   |
| 3466    | 1         | 0.12%   |
| 3100    | 1         | 0.12%   |
| 2933    | 1         | 0.12%   |
| 2866    | 1         | 0.12%   |
| 2000    | 1         | 0.12%   |
| 333     | 1         | 0.12%   |
| 200     | 1         | 0.12%   |
| 33      | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 30        | 37.97%  |
| Brother Industries    | 17        | 21.52%  |
| Canon                 | 13        | 16.46%  |
| Samsung Electronics   | 5         | 6.33%   |
| Zebra                 | 4         | 5.06%   |
| Seiko Epson           | 3         | 3.8%    |
| STMicroelectronics    | 1         | 1.27%   |
| QinHeng Electronics   | 1         | 1.27%   |
| Prolific Technology   | 1         | 1.27%   |
| Pantum                | 1         | 1.27%   |
| Lexmark International | 1         | 1.27%   |
| Kyocera               | 1         | 1.27%   |
| Dymo-CoStar           | 1         | 1.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet 400 M401dne                                               | 4         | 5.06%   |
| Zebra ZP 450 Printer                                                  | 3         | 3.8%    |
| HP LaserJet P1005                                                     | 3         | 3.8%    |
| Seiko Epson L222 Series                                               | 2         | 2.53%   |
| HP OfficeJet Pro 7730 series                                          | 2         | 2.53%   |
| HP LaserJet 1320                                                      | 2         | 2.53%   |
| HP DeskJet 3700 series                                                | 2         | 2.53%   |
| Brother HL-L2320D series                                              | 2         | 2.53%   |
| Brother HL-5370DW series                                              | 2         | 2.53%   |
| Brother HL-5340 series                                                | 2         | 2.53%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 1.27%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 1.27%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 1.27%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 1.27%   |
| Samsung SCX-4200 series                                               | 1         | 1.27%   |
| Samsung ML-2525W Series                                               | 1         | 1.27%   |
| Samsung M2070 Series                                                  | 1         | 1.27%   |
| Samsung M2020 Series                                                  | 1         | 1.27%   |
| QinHeng CH340S                                                        | 1         | 1.27%   |
| Prolific PL2305 Parallel Port                                         | 1         | 1.27%   |
| Pantum P2000 Series                                                   | 1         | 1.27%   |
| Lexmark International E360d                                           | 1         | 1.27%   |
| Kyocera Mita FS-920                                                   | 1         | 1.27%   |
| HP OfficeJet Pro 9010 series                                          | 1         | 1.27%   |
| HP Officejet Pro 6230                                                 | 1         | 1.27%   |
| HP LaserJet P2055 series                                              | 1         | 1.27%   |
| HP LaserJet P2015 series                                              | 1         | 1.27%   |
| HP LaserJet P1006                                                     | 1         | 1.27%   |
| HP LaserJet M14-M17                                                   | 1         | 1.27%   |
| HP LaserJet CP 1025                                                   | 1         | 1.27%   |
| HP LaserJet 1020                                                      | 1         | 1.27%   |
| HP LaserJet 1018                                                      | 1         | 1.27%   |
| HP ENVY 4520 series                                                   | 1         | 1.27%   |
| HP Deskjet F4400 series                                               | 1         | 1.27%   |
| HP DeskJet F300 series                                                | 1         | 1.27%   |
| HP DeskJet F2100 Printer series                                       | 1         | 1.27%   |
| HP DeskJet 5850c                                                      | 1         | 1.27%   |
| HP DeskJet 3630 series                                                | 1         | 1.27%   |
| HP Deskjet 3050A                                                      | 1         | 1.27%   |
| HP Color LaserJet CP1215                                              | 1         | 1.27%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 1         | 1.27%   |
| Canon TS6400 series                                                   | 1         | 1.27%   |
| Canon TS3300 series                                                   | 1         | 1.27%   |
| Canon TS3100 series                                                   | 1         | 1.27%   |
| Canon TR8500 series                                                   | 1         | 1.27%   |
| Canon PIXMA MX530 Series                                              | 1         | 1.27%   |
| Canon PIXMA MP190                                                     | 1         | 1.27%   |
| Canon PIXMA MG3600 Series                                             | 1         | 1.27%   |
| Canon MG2400 series                                                   | 1         | 1.27%   |
| Canon LBP6230/6240                                                    | 1         | 1.27%   |
| Canon LBP6000                                                         | 1         | 1.27%   |
| Canon iP4700 series                                                   | 1         | 1.27%   |
| Canon G6000 series                                                    | 1         | 1.27%   |
| Canon E4200 series                                                    | 1         | 1.27%   |
| Brother MFC-L2710DW series                                            | 1         | 1.27%   |
| Brother MFC-7460DN                                                    | 1         | 1.27%   |
| Brother HL-L2395DW series                                             | 1         | 1.27%   |
| Brother HL-L2340D series                                              | 1         | 1.27%   |
| Brother HL-5150D series                                               | 1         | 1.27%   |
| Brother HL-2270DW Laser Printer                                       | 1         | 1.27%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 61.11%  |
| Seiko Epson     | 4         | 22.22%  |
| Hewlett-Packard | 3         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 2         | 11.11%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5.56%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 5.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5.56%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 5.56%   |
| HP ScanJet 82x0C                                            | 1         | 5.56%   |
| HP ScanJet 5590                                             | 1         | 5.56%   |
| HP ScanJet 3570c                                            | 1         | 5.56%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 5.56%   |
| Canon CanoScan LiDE 90                                      | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                      | 1         | 5.56%   |
| Canon CanoScan LiDE 220                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 210                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 200                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 120                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 110                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 100                                     | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 237       | 25.08%  |
| Microdia                               | 71        | 7.51%   |
| IMC Networks                           | 63        | 6.67%   |
| Realtek Semiconductor                  | 61        | 6.46%   |
| Acer                                   | 57        | 6.03%   |
| Logitech                               | 50        | 5.29%   |
| Sunplus Innovation Technology          | 49        | 5.19%   |
| Suyin                                  | 44        | 4.66%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 3.28%   |
| Apple                                  | 29        | 3.07%   |
| Quanta                                 | 28        | 2.96%   |
| Lite-On Technology                     | 26        | 2.75%   |
| Syntek                                 | 22        | 2.33%   |
| Silicon Motion                         | 19        | 2.01%   |
| Alcor Micro                            | 17        | 1.8%    |
| Ricoh                                  | 16        | 1.69%   |
| Samsung Electronics                    | 12        | 1.27%   |
| Microsoft                              | 11        | 1.16%   |
| Lenovo                                 | 8         | 0.85%   |
| Z-Star Microelectronics                | 6         | 0.63%   |
| Importek                               | 6         | 0.63%   |
| MacroSilicon                           | 5         | 0.53%   |
| Luxvisions Innotech Limited            | 5         | 0.53%   |
| Jieli Technology                       | 5         | 0.53%   |
| ALi                                    | 5         | 0.53%   |
| OmniVision Technologies                | 4         | 0.42%   |
| Generalplus Technology                 | 4         | 0.42%   |
| GEMBIRD                                | 4         | 0.42%   |
| DigiTech                               | 4         | 0.42%   |
| ARC International                      | 4         | 0.42%   |
| Trust                                  | 3         | 0.32%   |
| Sunplus Technology                     | 3         | 0.32%   |
| Primax Electronics                     | 3         | 0.32%   |
| Cubeternet                             | 3         | 0.32%   |
| Creative Technology                    | 3         | 0.32%   |
| Unknown                                | 2         | 0.21%   |
| Razer USA                              | 2         | 0.21%   |
| Hewlett-Packard                        | 2         | 0.21%   |
| Genesys Logic                          | 2         | 0.21%   |
| Arkmicro Technologies                  | 2         | 0.21%   |
| USB3.0 HD Audio Capture                | 1         | 0.11%   |
| USB Camera                             | 1         | 0.11%   |
| Tobii AB                               | 1         | 0.11%   |
| Sunplus IT                             | 1         | 0.11%   |
| Sonix Technology                       | 1         | 0.11%   |
| PrehKeyTec                             | 1         | 0.11%   |
| Pixart Imaging                         | 1         | 0.11%   |
| OPPO Electronics                       | 1         | 0.11%   |
| Novatek Microelectronics               | 1         | 0.11%   |
| Nintendo                               | 1         | 0.11%   |
| Mimaki Engineering                     | 1         | 0.11%   |
| Magic Control Technology               | 1         | 0.11%   |
| Linux Foundation                       | 1         | 0.11%   |
| KYE Systems (Mouse Systems)            | 1         | 0.11%   |
| Intel                                  | 1         | 0.11%   |
| Huawei Technologies                    | 1         | 0.11%   |
| Aveo Technology                        | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 35        | 3.68%   |
| Chicony USB 2.0 Camera                                      | 18        | 1.89%   |
| Realtek Integrated_Webcam_HD                                | 17        | 1.79%   |
| Microdia Integrated_Webcam_HD                               | 15        | 1.58%   |
| Logitech Webcam C270                                        | 14        | 1.47%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 13        | 1.37%   |
| IMC Networks Integrated Camera                              | 13        | 1.37%   |
| Samsung Galaxy A5 (MTP)                                     | 12        | 1.26%   |
| Chicony TOSHIBA Web Camera - HD                             | 12        | 1.26%   |
| Chicony HP Truevision HD                                    | 12        | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 11        | 1.16%   |
| Acer Lenovo EasyCamera                                      | 11        | 1.16%   |
| Sunplus Integrated_Webcam_HD                                | 10        | 1.05%   |
| Microdia Integrated Webcam                                  | 10        | 1.05%   |
| Logitech HD Pro Webcam C920                                 | 10        | 1.05%   |
| Lite-On Integrated Camera                                   | 10        | 1.05%   |
| Chicony USB2.0 VGA UVC WebCam                               | 10        | 1.05%   |
| Acer Integrated Camera                                      | 10        | 1.05%   |
| Lite-On HP HD Camera                                        | 9         | 0.95%   |
| Chicony HD WebCam                                           | 9         | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE                                   | 9         | 0.95%   |
| Apple Built-in iSight                                       | 9         | 0.95%   |
| Alcor Micro SHUNCCM2MP                                      | 9         | 0.95%   |
| Syntek Lenovo EasyCamera                                    | 8         | 0.84%   |
| Syntek Integrated Camera                                    | 8         | 0.84%   |
| Suyin HP TrueVision HD                                      | 8         | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 8         | 0.84%   |
| Chicony Lenovo EasyCamera                                   | 8         | 0.84%   |
| Chicony USB2.0 Camera                                       | 7         | 0.74%   |
| Chicony Integrated Camera (1280x720@30)                     | 7         | 0.74%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 6         | 0.63%   |
| Quanta HP TrueVision HD Camera                              | 6         | 0.63%   |
| IMC Networks UVC VGA Webcam                                 | 6         | 0.63%   |
| Chicony FJ Camera                                           | 6         | 0.63%   |
| Acer BisonCam, NB Pro                                       | 6         | 0.63%   |
| Sunplus HD WebCam                                           | 5         | 0.53%   |
| Quanta HP Webcam                                            | 5         | 0.53%   |
| Microdia Webcam Vitade AF                                   | 5         | 0.53%   |
| Microdia Sonix USB 2.0 Camera                               | 5         | 0.53%   |
| Jieli USB PHY 2.0                                           | 5         | 0.53%   |
| Chicony WebCam                                              | 5         | 0.53%   |
| Chicony USB2.0 HD UVC WebCam                                | 5         | 0.53%   |
| Chicony HP HD Webcam [Fixed]                                | 5         | 0.53%   |
| Chicony HP HD Webcam                                        | 5         | 0.53%   |
| Chicony HP HD Camera                                        | 5         | 0.53%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 4         | 0.42%   |
| Suyin Acer CrystalEye Webcam                                | 4         | 0.42%   |
| Sunplus Asus Webcam                                         | 4         | 0.42%   |
| Realtek USB Camera                                          | 4         | 0.42%   |
| Realtek Integrated Webcam HD                                | 4         | 0.42%   |
| Realtek HP Truevision HD integrated webcam                  | 4         | 0.42%   |
| Realtek Acer 640 x 480 laptop camera                        | 4         | 0.42%   |
| OmniVision OV2640 Webcam                                    | 4         | 0.42%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 4         | 0.42%   |
| Microdia Dell Integrated HD Webcam                          | 4         | 0.42%   |
| MacroSilicon USB Video                                      | 4         | 0.42%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 4         | 0.42%   |
| IMC Networks USB Camera                                     | 4         | 0.42%   |
| IMC Networks Integrated Webcam                              | 4         | 0.42%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]           | 4         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 71        | 41.04%  |
| Synaptics                  | 38        | 21.97%  |
| AuthenTec                  | 28        | 16.18%  |
| Upek                       | 10        | 5.78%   |
| Shenzhen Goodix Technology | 9         | 5.2%    |
| LighTuning Technology      | 7         | 4.05%   |
| STMicroelectronics         | 6         | 3.47%   |
| Elan Microelectronics      | 3         | 1.73%   |
| Samsung Electronics        | 1         | 0.58%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 10.4%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 8.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 5.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 4.62%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 4.62%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 4.62%   |
| AuthenTec AES2810                                                          | 8         | 4.62%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 4.62%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 4.05%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 4.05%   |
| Validity Sensors VFS491                                                    | 6         | 3.47%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 3.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.47%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 3.47%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 3.47%   |
| Unknown                                                                    | 6         | 3.47%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.31%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.31%   |
| AuthenTec AES1600                                                          | 4         | 2.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.73%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.73%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.16%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.16%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.16%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.16%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.16%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.16%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.58%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.58%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.58%   |
| Synaptics WBDI Device                                                      | 1         | 0.58%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.58%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.58%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.58%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.58%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 33        | 34.74%  |
| Alcor Micro               | 26        | 27.37%  |
| O2 Micro                  | 15        | 15.79%  |
| Lenovo                    | 8         | 8.42%   |
| Upek                      | 7         | 7.37%   |
| OmniKey                   | 3         | 3.16%   |
| Fujitsu Siemens Computers | 1         | 1.05%   |
| Cherry                    | 1         | 1.05%   |
| C3PO                      | 1         | 1.05%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 27.37%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 14        | 14.74%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 13.68%  |
| Broadcom 5880                                                                | 8         | 8.42%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 7.37%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 7.37%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 7.37%   |
| Broadcom 58200                                                               | 5         | 5.26%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 2.11%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 1.05%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.05%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 1.05%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.05%   |
| Cherry SmartTerminal XX44                                                    | 1         | 1.05%   |
| C3PO USB SMART CARD READER                                                   | 1         | 1.05%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1305      | 74.87%  |
| 1     | 358       | 20.54%  |
| 2     | 65        | 3.73%   |
| 3     | 8         | 0.46%   |
| 4     | 4         | 0.23%   |
| 5     | 2         | 0.11%   |
| 10    | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 173       | 32.77%  |
| Graphics card            | 93        | 17.61%  |
| Chipcard                 | 92        | 17.42%  |
| Net/wireless             | 57        | 10.8%   |
| Communication controller | 17        | 3.22%   |
| Unassigned class         | 15        | 2.84%   |
| Camera                   | 14        | 2.65%   |
| Bluetooth                | 12        | 2.27%   |
| Multimedia controller    | 11        | 2.08%   |
| Card reader              | 10        | 1.89%   |
| Storage                  | 9         | 1.7%    |
| Sound                    | 9         | 1.7%    |
| Net/ethernet             | 5         | 0.95%   |
| Flash memory             | 5         | 0.95%   |
| Network                  | 2         | 0.38%   |
| Modem                    | 2         | 0.38%   |
| Storage/raid             | 1         | 0.19%   |
| Dvb card                 | 1         | 0.19%   |

