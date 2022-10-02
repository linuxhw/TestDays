MX 21 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_21/Desktop/README.md) and [notebooks](/Dist/MX_21/Notebook/README.md).

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

Total: 179

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f97d2b97ad](https://linux-hardware.org/?probe=f97d2b97ad) | Oct 01, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | Notebook    | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [d562164e67](https://linux-hardware.org/?probe=d562164e67) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | Notebook    | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [83e026f682](https://linux-hardware.org/?probe=83e026f682) | Aug 12, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | Notebook    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | Notebook    | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| MP            | MS-7848                     | Desktop     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Dell          | 0DR845                      | Desktop     | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| Alienware     | 13 R2                       | Notebook    | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | Notebook    | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [77c632ea8e](https://linux-hardware.org/?probe=77c632ea8e) | Jul 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | Desktop     | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c21cd1f8f3](https://linux-hardware.org/?probe=c21cd1f8f3) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-9-amd64             | 18        | 12.77%  |
| 5.10.0-13-amd64            | 18        | 12.77%  |
| 5.14.0-4mx-amd64           | 13        | 9.22%   |
| 5.10.0-16-amd64            | 13        | 9.22%   |
| 5.16.0-5mx-amd64           | 9         | 6.38%   |
| 5.10.0-11-amd64            | 8         | 5.67%   |
| 5.10.0-15-amd64            | 6         | 4.26%   |
| 5.10.0-14-amd64            | 6         | 4.26%   |
| 5.10.0-18-amd64            | 5         | 3.55%   |
| 5.10.0-17-amd64            | 4         | 2.84%   |
| 5.10.0-10-amd64            | 4         | 2.84%   |
| 5.16.0-6mx-amd64           | 3         | 2.13%   |
| 5.18.0-4mx-amd64           | 2         | 1.42%   |
| 5.16.0-4mx-amd64           | 2         | 1.42%   |
| 5.16.0-18.1-liquorix-amd64 | 2         | 1.42%   |
| 5.14.0-3mx-amd64           | 2         | 1.42%   |
| 5.10.0-8-amd64             | 2         | 1.42%   |
| 5.10.0-13-686-pae          | 2         | 1.42%   |
| 5.10.0-12-amd64            | 2         | 1.42%   |
| 5.10.0-11-686-pae          | 2         | 1.42%   |
| 5.19.0-4.2-liquorix-amd64  | 1         | 0.71%   |
| 5.19.0-12.1-liquorix-amd64 | 1         | 0.71%   |
| 5.18.0-3-amd64             | 1         | 0.71%   |
| 5.17.0-5.2-liquorix-amd64  | 1         | 0.71%   |
| 5.17.0-3mx-amd64           | 1         | 0.71%   |
| 5.17.0-2mx-amd64           | 1         | 0.71%   |
| 5.17.0-1mx-amd64           | 1         | 0.71%   |
| 5.17.0-1-amd64             | 1         | 0.71%   |
| 5.16.0-rc5-hwmon-next+     | 1         | 0.71%   |
| 5.15.0-3mx-amd64           | 1         | 0.71%   |
| 5.15.0-2-amd64             | 1         | 0.71%   |
| 5.15.0-0.bpo.2-amd64       | 1         | 0.71%   |
| 5.14.0-2mx-amd64           | 1         | 0.71%   |
| 5.10.52-antix.1-amd64-smp  | 1         | 0.71%   |
| 5.10.111-tkg-cfs           | 1         | 0.71%   |
| 5.10.0-5mx-amd64           | 1         | 0.71%   |
| 5.10.0-18-686-pae          | 1         | 0.71%   |
| 5.10.0-11-686              | 1         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 89        | 64.96%  |
| 5.16.0   | 17        | 12.41%  |
| 5.14.0   | 16        | 11.68%  |
| 5.17.0   | 5         | 3.65%   |
| 5.18.0   | 3         | 2.19%   |
| 5.15.0   | 3         | 2.19%   |
| 5.19.0   | 2         | 1.46%   |
| 5.10.52  | 1         | 0.73%   |
| 5.10.111 | 1         | 0.73%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 91        | 66.42%  |
| 5.16    | 17        | 12.41%  |
| 5.14    | 16        | 11.68%  |
| 5.17    | 5         | 3.65%   |
| 5.18    | 3         | 2.19%   |
| 5.15    | 3         | 2.19%   |
| 5.19    | 2         | 1.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 128       | 96.24%  |
| i686   | 5         | 3.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 92        | 69.17%  |
| KDE5             | 29        | 21.8%   |
| Unknown          | 3         | 2.26%   |
| lightdm-xsession | 2         | 1.5%    |
| GNOME            | 2         | 1.5%    |
| Budgie           | 2         | 1.5%    |
| LXQt             | 1         | 0.75%   |
| i3               | 1         | 0.75%   |
| GNOME Classic    | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 131       | 98.5%   |
| Tty  | 2         | 1.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 102       | 76.69%  |
| SDDM    | 28        | 21.05%  |
| SLiM    | 2         | 1.5%    |
| Unknown | 1         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 67        | 50%     |
| de_DE   | 24        | 17.91%  |
| it_IT   | 4         | 2.99%   |
| en_GB   | 4         | 2.99%   |
| ru_RU   | 3         | 2.24%   |
| pt_BR   | 3         | 2.24%   |
| fr_FR   | 3         | 2.24%   |
| es_ES   | 3         | 2.24%   |
| en_NZ   | 3         | 2.24%   |
| de_CH   | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| tr_TR   | 2         | 1.49%   |
| pl_PL   | 2         | 1.49%   |
| fi_FI   | 2         | 1.49%   |
| sv_SE   | 1         | 0.75%   |
| sk_SK   | 1         | 0.75%   |
| nb_NO   | 1         | 0.75%   |
| id_ID   | 1         | 0.75%   |
| hu_HU   | 1         | 0.75%   |
| es_PE   | 1         | 0.75%   |
| es_MX   | 1         | 0.75%   |
| en_AU   | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 83        | 62.41%  |
| BIOS | 50        | 37.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 109       | 81.95%  |
| Overlay  | 16        | 12.03%  |
| Btrfs    | 4         | 3.01%   |
| Xfs      | 1         | 0.75%   |
| Reiserfs | 1         | 0.75%   |
| F2fs     | 1         | 0.75%   |
| Ext3     | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 95        | 71.43%  |
| MBR     | 36        | 27.07%  |
| Unknown | 2         | 1.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 67.91%  |
| Yes       | 43        | 32.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 52.99%  |
| No        | 63        | 47.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 21        | 15.79%  |
| ASUSTek Computer    | 18        | 13.53%  |
| Hewlett-Packard     | 15        | 11.28%  |
| Dell                | 14        | 10.53%  |
| Gigabyte Technology | 8         | 6.02%   |
| MSI                 | 7         | 5.26%   |
| Apple               | 7         | 5.26%   |
| Acer                | 6         | 4.51%   |
| Sony                | 5         | 3.76%   |
| Samsung Electronics | 3         | 2.26%   |
| Alienware           | 3         | 2.26%   |
| Medion              | 2         | 1.5%    |
| Intel               | 2         | 1.5%    |
| Fujitsu Siemens     | 2         | 1.5%    |
| ASRock              | 2         | 1.5%    |
| Unknown             | 2         | 1.5%    |
| ZOTAC               | 1         | 0.75%   |
| TUXEDO              | 1         | 0.75%   |
| Toshiba             | 1         | 0.75%   |
| Sun Microsystems    | 1         | 0.75%   |
| Notebook            | 1         | 0.75%   |
| MP                  | 1         | 0.75%   |
| Microsoft           | 1         | 0.75%   |
| Huanan              | 1         | 0.75%   |
| GALAX               | 1         | 0.75%   |
| Fujitsu             | 1         | 0.75%   |
| Framework           | 1         | 0.75%   |
| efirstview          | 1         | 0.75%   |
| Chuwi               | 1         | 0.75%   |
| Biostar             | 1         | 0.75%   |
| AZW                 | 1         | 0.75%   |
| AOpen               | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 3         | 2.26%   |
| Dell OptiPlex 755                            | 2         | 1.5%    |
| ASUS All Series                              | 2         | 1.5%    |
| Apple Macmini6,2                             | 2         | 1.5%    |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.75%   |
| TUXEDO N7x0WU                                | 1         | 0.75%   |
| Toshiba Satellite C845                       | 1         | 0.75%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.75%   |
| Sony VPCSB1V9R                               | 1         | 0.75%   |
| Sony VPCF119FX                               | 1         | 0.75%   |
| Sony VPCEH2N1E                               | 1         | 0.75%   |
| Sony VPCEC3S1E                               | 1         | 0.75%   |
| Sony SVE1513Q1ESI                            | 1         | 0.75%   |
| Samsung NC210/NC110                          | 1         | 0.75%   |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 0.75%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.75%   |
| Notebook PD5x_7xPNP_PNN_PNT                  | 1         | 0.75%   |
| MSI MS-7C91                                  | 1         | 0.75%   |
| MSI MS-7A34                                  | 1         | 0.75%   |
| MSI MS-7917                                  | 1         | 0.75%   |
| MSI MS-7758                                  | 1         | 0.75%   |
| MSI Modern 14 B11MOL                         | 1         | 0.75%   |
| MSI GV62 8RD                                 | 1         | 0.75%   |
| MSI Alpha 15 B5EEK                           | 1         | 0.75%   |
| MP MS-7848                                   | 1         | 0.75%   |
| Microsoft Surface Pro 7                      | 1         | 0.75%   |
| Medion E14304                                | 1         | 0.75%   |
| Medion Akoya P5330 E MD8876/2458             | 1         | 0.75%   |
| Lenovo Yoga 7 14ITL5 82BH                    | 1         | 0.75%   |
| Lenovo V15-IGL 82C3                          | 1         | 0.75%   |
| Lenovo ThinkStation P620 30E0CTO1WW          | 1         | 0.75%   |
| Lenovo ThinkPad W541 20EG0005MS              | 1         | 0.75%   |
| Lenovo ThinkPad T560 20FJS0EP00              | 1         | 0.75%   |
| Lenovo ThinkPad T500 2241VL9                 | 1         | 0.75%   |
| Lenovo ThinkPad T480 20L50004MZ              | 1         | 0.75%   |
| Lenovo ThinkPad T440p 20AW002VBR             | 1         | 0.75%   |
| Lenovo ThinkPad T430 23427YU                 | 1         | 0.75%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00A8GE       | 1         | 0.75%   |
| Lenovo ThinkPad L512 44444WG                 | 1         | 0.75%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS         | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 9         | 6.77%   |
| Dell OptiPlex        | 4         | 3.01%   |
| HP ProBook           | 3         | 2.26%   |
| HP EliteBook         | 3         | 2.26%   |
| Dell Latitude        | 3         | 2.26%   |
| ASUS ROG             | 3         | 2.26%   |
| Unknown              | 3         | 2.26%   |
| Lenovo IdeaPad       | 2         | 1.5%    |
| HP Compaq            | 2         | 1.5%    |
| Gigabyte B550M       | 2         | 1.5%    |
| Dell Precision       | 2         | 1.5%    |
| Dell Inspiron        | 2         | 1.5%    |
| ASUS P5GC-MX         | 2         | 1.5%    |
| ASUS All             | 2         | 1.5%    |
| Apple Macmini6       | 2         | 1.5%    |
| Alienware m15        | 2         | 1.5%    |
| Acer Nitro           | 2         | 1.5%    |
| Acer Aspire          | 2         | 1.5%    |
| ZOTAC ZBOX-ECM73070C | 1         | 0.75%   |
| TUXEDO N7x0WU        | 1         | 0.75%   |
| Toshiba Satellite    | 1         | 0.75%   |
| Sun Microsystems Sun | 1         | 0.75%   |
| Sony VPCSB1V9R       | 1         | 0.75%   |
| Sony VPCF119FX       | 1         | 0.75%   |
| Sony VPCEH2N1E       | 1         | 0.75%   |
| Sony VPCEC3S1E       | 1         | 0.75%   |
| Sony SVE1513Q1ESI    | 1         | 0.75%   |
| Samsung NC210        | 1         | 0.75%   |
| Samsung 350V5C       | 1         | 0.75%   |
| Samsung 340XAA       | 1         | 0.75%   |
| Notebook PD5x        | 1         | 0.75%   |
| MSI MS-7C91          | 1         | 0.75%   |
| MSI MS-7A34          | 1         | 0.75%   |
| MSI MS-7917          | 1         | 0.75%   |
| MSI MS-7758          | 1         | 0.75%   |
| MSI Modern           | 1         | 0.75%   |
| MSI GV62             | 1         | 0.75%   |
| MSI Alpha            | 1         | 0.75%   |
| MP MS-7848           | 1         | 0.75%   |
| Microsoft Surface    | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 21        | 15.79%  |
| 2020    | 15        | 11.28%  |
| 2015    | 11        | 8.27%   |
| 2018    | 9         | 6.77%   |
| 2011    | 9         | 6.77%   |
| 2010    | 9         | 6.77%   |
| 2019    | 8         | 6.02%   |
| 2012    | 8         | 6.02%   |
| 2016    | 7         | 5.26%   |
| 2013    | 7         | 5.26%   |
| 2007    | 7         | 5.26%   |
| 2017    | 5         | 3.76%   |
| 2014    | 5         | 3.76%   |
| 2022    | 3         | 2.26%   |
| 2009    | 3         | 2.26%   |
| 2008    | 3         | 2.26%   |
| 2006    | 1         | 0.75%   |
| 2005    | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 83        | 62.41%  |
| Desktop     | 38        | 28.57%  |
| Convertible | 4         | 3.01%   |
| Mini pc     | 4         | 3.01%   |
| All in one  | 2         | 1.5%    |
| Tablet      | 1         | 0.75%   |
| Server      | 1         | 0.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 131       | 98.5%   |
| Enabled  | 2         | 1.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 133       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 35        | 26.32%  |
| 8.01-16.0   | 26        | 19.55%  |
| 16.01-24.0  | 24        | 18.05%  |
| 3.01-4.0    | 19        | 14.29%  |
| 32.01-64.0  | 16        | 12.03%  |
| 2.01-3.0    | 4         | 3.01%   |
| 64.01-256.0 | 3         | 2.26%   |
| 1.01-2.0    | 3         | 2.26%   |
| 24.01-32.0  | 2         | 1.5%    |
| 0.51-1.0    | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 52        | 37.41%  |
| 2.01-3.0   | 39        | 28.06%  |
| 3.01-4.0   | 19        | 13.67%  |
| 4.01-8.0   | 14        | 10.07%  |
| 0.51-1.0   | 7         | 5.04%   |
| 8.01-16.0  | 6         | 4.32%   |
| 16.01-24.0 | 1         | 0.72%   |
| 0.01-0.5   | 1         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 54.48%  |
| 2      | 33        | 24.63%  |
| 3      | 19        | 14.18%  |
| 4      | 5         | 3.73%   |
| 5      | 2         | 1.49%   |
| 8      | 1         | 0.75%   |
| 0      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 63.91%  |
| Yes       | 48        | 36.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 84.21%  |
| No        | 21        | 15.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 79.7%   |
| No        | 27        | 20.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 61.65%  |
| No        | 51        | 38.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 37        | 27.61%  |
| Germany     | 22        | 16.42%  |
| Italy       | 7         | 5.22%   |
| Canada      | 6         | 4.48%   |
| Brazil      | 5         | 3.73%   |
| Switzerland | 3         | 2.24%   |
| Spain       | 3         | 2.24%   |
| Russia      | 3         | 2.24%   |
| Poland      | 3         | 2.24%   |
| New Zealand | 3         | 2.24%   |
| Netherlands | 3         | 2.24%   |
| India       | 3         | 2.24%   |
| France      | 3         | 2.24%   |
| Finland     | 3         | 2.24%   |
| UK          | 2         | 1.49%   |
| Turkey      | 2         | 1.49%   |
| Serbia      | 2         | 1.49%   |
| Indonesia   | 2         | 1.49%   |
| Belgium     | 2         | 1.49%   |
| Austria     | 2         | 1.49%   |
| Australia   | 2         | 1.49%   |
| Venezuela   | 1         | 0.75%   |
| Sweden      | 1         | 0.75%   |
| Slovakia    | 1         | 0.75%   |
| Romania     | 1         | 0.75%   |
| Peru        | 1         | 0.75%   |
| Norway      | 1         | 0.75%   |
| Mexico      | 1         | 0.75%   |
| Malaysia    | 1         | 0.75%   |
| Hungary     | 1         | 0.75%   |
| Greece      | 1         | 0.75%   |
| Ghana       | 1         | 0.75%   |
| Estonia     | 1         | 0.75%   |
| Egypt       | 1         | 0.75%   |
| Czechia     | 1         | 0.75%   |
| Belarus     | 1         | 0.75%   |
| Azerbaijan  | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Cambridge     | 3         | 2.19%   |
| Berlin        | 3         | 2.19%   |
| Vienna        | 2         | 1.46%   |
| Vasco da Gama | 2         | 1.46%   |
| St Petersburg | 2         | 1.46%   |
| Portland      | 2         | 1.46%   |
| Orange        | 2         | 1.46%   |
| Montreal      | 2         | 1.46%   |
| Istanbul      | 2         | 1.46%   |
| Helsinki      | 2         | 1.46%   |
| Ettingen      | 2         | 1.46%   |
| Doesburg      | 2         | 1.46%   |
| Zurich        | 1         | 0.73%   |
| Waycross      | 1         | 0.73%   |
| Warsaw        | 1         | 0.73%   |
| Volos         | 1         | 0.73%   |
| Vilhelmina    | 1         | 0.73%   |
| Vancouver     | 1         | 0.73%   |
| Vaidasoo      | 1         | 0.73%   |
| Uelzen        | 1         | 0.73%   |
| Tupelo        | 1         | 0.73%   |
| Tucson        | 1         | 0.73%   |
| Taggia        | 1         | 0.73%   |
| Tacoma        | 1         | 0.73%   |
| Sydney        | 1         | 0.73%   |
| Surprise      | 1         | 0.73%   |
| Stevens Point | 1         | 0.73%   |
| Stadtilm      | 1         | 0.73%   |
| Soest         | 1         | 0.73%   |
| Seelbach      | 1         | 0.73%   |
| Seedorf       | 1         | 0.73%   |
| Schaarbeek    | 1         | 0.73%   |
| Saskatoon     | 1         | 0.73%   |
| San Diego     | 1         | 0.73%   |
| Saarlouis     | 1         | 0.73%   |
| Rzeszów      | 1         | 0.73%   |
| Rosporden     | 1         | 0.73%   |
| Roseville     | 1         | 0.73%   |
| Rome          | 1         | 0.73%   |
| Rochester     | 1         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 53     | 18.81%  |
| Seagate             | 31        | 40     | 15.35%  |
| WDC                 | 27        | 31     | 13.37%  |
| Kingston            | 14        | 14     | 6.93%   |
| Crucial             | 14        | 22     | 6.93%   |
| Unknown             | 8         | 9      | 3.96%   |
| SK hynix            | 7         | 8      | 3.47%   |
| SanDisk             | 7         | 8      | 3.47%   |
| Toshiba             | 5         | 5      | 2.48%   |
| Intel               | 5         | 5      | 2.48%   |
| Transcend           | 4         | 4      | 1.98%   |
| PNY                 | 3         | 4      | 1.49%   |
| LITEON              | 3         | 3      | 1.49%   |
| Hitachi             | 3         | 3      | 1.49%   |
| Dogfish             | 3         | 3      | 1.49%   |
| Apple               | 3         | 6      | 1.49%   |
| SPCC                | 2         | 2      | 0.99%   |
| OCZ                 | 2         | 2      | 0.99%   |
| Netac               | 2         | 2      | 0.99%   |
| Micron Technology   | 2         | 2      | 0.99%   |
| GOODRAM             | 2         | 2      | 0.99%   |
| Corsair             | 2         | 2      | 0.99%   |
| Team                | 1         | 1      | 0.5%    |
| Silicon Motion      | 1         | 1      | 0.5%    |
| SABRENT             | 1         | 1      | 0.5%    |
| Phison              | 1         | 1      | 0.5%    |
| Maxtor              | 1         | 1      | 0.5%    |
| KIOXIA              | 1         | 1      | 0.5%    |
| Indilinx            | 1         | 1      | 0.5%    |
| Gigabyte Technology | 1         | 1      | 0.5%    |
| GeIL                | 1         | 1      | 0.5%    |
| Fujitsu             | 1         | 1      | 0.5%    |
| Avant               | 1         | 1      | 0.5%    |
| Apacer              | 1         | 1      | 0.5%    |
| Acer                | 1         | 1      | 0.5%    |
| A-DATA Technology   | 1         | 1      | 0.5%    |
| Unknown             | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD   | 5         | 2.2%    |
| Samsung SSD 850 EVO 250GB         | 4         | 1.76%   |
| Seagate ST2000DM008-2FR102 2TB    | 3         | 1.32%   |
| Samsung SSD 980 PRO 1TB           | 3         | 1.32%   |
| Samsung SSD 970 EVO Plus 1TB      | 3         | 1.32%   |
| Samsung SSD 860 EVO 500GB         | 3         | 1.32%   |
| Kingston SA400S37240G 240GB SSD   | 3         | 1.32%   |
| Crucial CT120BX500SSD1 120GB      | 3         | 1.32%   |
| Unknown SD32G  32GB               | 2         | 0.88%   |
| Toshiba DT01ACA100 1TB            | 2         | 0.88%   |
| SK hynix HFM512GDJTNI-82A0A 512GB | 2         | 0.88%   |
| Seagate ST500LT012-9WS142 500GB   | 2         | 0.88%   |
| Seagate ST500LM021-1KJ152 500GB   | 2         | 0.88%   |
| Seagate ST3500413AS 500GB         | 2         | 0.88%   |
| Seagate ST1000LM035-1RK172 1TB    | 2         | 0.88%   |
| Samsung SSD 860 EVO M.2 500GB     | 2         | 0.88%   |
| Samsung SSD 860 EVO 1TB           | 2         | 0.88%   |
| Samsung SSD 850 EVO 1TB           | 2         | 0.88%   |
| Kingston OM8PCP3512F-AI1 512GB    | 2         | 0.88%   |
| Dogfish SSD 128GB                 | 2         | 0.88%   |
| Crucial CT500P2SSD8 500GB         | 2         | 0.88%   |
| Crucial CT500MX500SSD1 500GB      | 2         | 0.88%   |
| Crucial CT240BX500SSD1 240GB      | 2         | 0.88%   |
| Corsair MP400 2TB                 | 2         | 0.88%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 1         | 0.44%   |
| WDC WDS500G2B0B-00YS70 500GB SSD  | 1         | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1         | 0.44%   |
| WDC WDS100T1X0E-00AFY0 1TB        | 1         | 0.44%   |
| WDC WD800AAJS-60M0A0 80GB         | 1         | 0.44%   |
| WDC WD60EZRZ-00RWYB1 6TB          | 1         | 0.44%   |
| WDC WD60EFRX-68L0BN1 6TB          | 1         | 0.44%   |
| WDC WD5002AALX-00J37A0 500GB      | 1         | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 0.44%   |
| WDC WD5000LPVX-08V0TT5 500GB      | 1         | 0.44%   |
| WDC WD5000LPLX-08ZNTT0 500GB      | 1         | 0.44%   |
| WDC WD5000LPCX-22VHAT0 500GB      | 1         | 0.44%   |
| WDC WD5000AVCS-632DY1 500GB       | 1         | 0.44%   |
| WDC WD5000AAKS-40V6A0 500GB       | 1         | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1         | 0.44%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 40     | 49.21%  |
| WDC                 | 18        | 22     | 28.57%  |
| Samsung Electronics | 4         | 4      | 6.35%   |
| Toshiba             | 3         | 3      | 4.76%   |
| Hitachi             | 3         | 3      | 4.76%   |
| Unknown             | 1         | 1      | 1.59%   |
| Maxtor              | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 30     | 28.41%  |
| Crucial             | 12        | 19     | 13.64%  |
| Kingston            | 10        | 10     | 11.36%  |
| SanDisk             | 7         | 8      | 7.95%   |
| Transcend           | 4         | 4      | 4.55%   |
| LITEON              | 3         | 3      | 3.41%   |
| Dogfish             | 3         | 3      | 3.41%   |
| Apple               | 3         | 5      | 3.41%   |
| WDC                 | 2         | 2      | 2.27%   |
| SPCC                | 2         | 2      | 2.27%   |
| PNY                 | 2         | 2      | 2.27%   |
| OCZ                 | 2         | 2      | 2.27%   |
| Netac               | 2         | 2      | 2.27%   |
| GOODRAM             | 2         | 2      | 2.27%   |
| Micron Technology   | 1         | 1      | 1.14%   |
| Intel               | 1         | 1      | 1.14%   |
| Indilinx            | 1         | 1      | 1.14%   |
| Gigabyte Technology | 1         | 1      | 1.14%   |
| GeIL                | 1         | 1      | 1.14%   |
| Avant               | 1         | 1      | 1.14%   |
| Apacer              | 1         | 1      | 1.14%   |
| Acer                | 1         | 1      | 1.14%   |
| A-DATA Technology   | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 71        | 103    | 38.8%   |
| HDD  | 58        | 76     | 31.69%  |
| NVMe | 46        | 57     | 25.14%  |
| MMC  | 8         | 9      | 4.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 173    | 63.29%  |
| NVMe | 46        | 56     | 29.11%  |
| MMC  | 8         | 9      | 5.06%   |
| SAS  | 4         | 7      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 114    | 62.5%   |
| 0.51-1.0   | 34        | 45     | 26.56%  |
| 1.01-2.0   | 10        | 14     | 7.81%   |
| 3.01-4.0   | 2         | 2      | 1.56%   |
| 2.01-3.0   | 1         | 1      | 0.78%   |
| 4.01-10.0  | 1         | 3      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 25.74%  |
| 251-500        | 31        | 22.79%  |
| 501-1000       | 22        | 16.18%  |
| 21-50          | 10        | 7.35%   |
| 1001-2000      | 10        | 7.35%   |
| More than 3000 | 8         | 5.88%   |
| 1-20           | 8         | 5.88%   |
| 51-100         | 8         | 5.88%   |
| 2001-3000      | 4         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 33.81%  |
| 21-50          | 26        | 18.71%  |
| 101-250        | 21        | 15.11%  |
| 51-100         | 16        | 11.51%  |
| 251-500        | 14        | 10.07%  |
| 1001-2000      | 7         | 5.04%   |
| 501-1000       | 4         | 2.88%   |
| More than 3000 | 3         | 2.16%   |
| 2001-3000      | 1         | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB              | 2         | 2      | 7.14%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 3.57%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 3.57%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 3.57%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 3.57%   |
| WDC WD10EADS-98M2B0 1TB                      | 1         | 1      | 3.57%   |
| WDC WD10EADS-00M2B0 1TB                      | 1         | 1      | 3.57%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 3.57%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 3.57%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 3.57%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 3.57%   |
| Seagate ST380815AS 80GB                      | 1         | 1      | 3.57%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 3.57%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 3.57%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1      | 3.57%   |
| Seagate ST320LT012-1DG14C 320GB              | 1         | 2      | 3.57%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 3.57%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 2      | 3.57%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 3.57%   |
| Maxtor 4K040H2 40GB                          | 1         | 1      | 3.57%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 3.57%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 3.57%   |
| GOODRAM SSDPR-CL100-480-G3 480GB             | 1         | 1      | 3.57%   |
| Crucial CT512M550SSD1 512GB                  | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 46.43%  |
| WDC                 | 6         | 6      | 21.43%  |
| Samsung Electronics | 4         | 5      | 14.29%  |
| Maxtor              | 1         | 1      | 3.57%   |
| Indilinx            | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| GOODRAM             | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 14     | 65%     |
| WDC     | 5         | 5      | 25%     |
| Maxtor  | 1         | 1      | 5%      |
| Hitachi | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 21     | 70.37%  |
| SSD  | 8         | 9      | 29.63%  |

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
| Works    | 113       | 196    | 73.38%  |
| Malfunc  | 27        | 30     | 17.53%  |
| Detected | 14        | 19     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 96        | 57.14%  |
| Samsung Electronics          | 19        | 11.31%  |
| AMD                          | 14        | 8.33%   |
| SK hynix                     | 7         | 4.17%   |
| SanDisk                      | 7         | 4.17%   |
| Phison Electronics           | 5         | 2.98%   |
| Kingston Technology Company  | 4         | 2.38%   |
| Nvidia                       | 3         | 1.79%   |
| ASMedia Technology           | 3         | 1.79%   |
| Micron/Crucial Technology    | 2         | 1.19%   |
| KIOXIA                       | 2         | 1.19%   |
| ULi Electronics              | 1         | 0.6%    |
| Toshiba America Info Systems | 1         | 0.6%    |
| Silicon Motion               | 1         | 0.6%    |
| Silicon Image                | 1         | 0.6%    |
| Micron Technology            | 1         | 0.6%    |
| Broadcom / LSI               | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 6.22%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 4.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 3.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 3.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 2.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 2.07%   |
| Phison E12 NVMe Controller                                                       | 4         | 2.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 2.07%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 2.07%   |
| SK hynix BC511                                                                   | 3         | 1.55%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.55%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.55%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.55%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.55%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.55%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.55%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.04%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.04%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 1.04%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.04%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 1.04%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.04%   |
| Intel 82Q35 Express PT IDER Controller                                           | 2         | 1.04%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 93        | 56.02%  |
| NVMe | 46        | 27.71%  |
| IDE  | 19        | 11.45%  |
| RAID | 7         | 4.22%   |
| SCSI | 1         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 108       | 81.2%   |
| AMD    | 25        | 18.8%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.26%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 2.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.26%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 2.26%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.5%    |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 1.5%    |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 1.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.5%    |
| Intel Core i5-3350P CPU @ 3.10GHz             | 2         | 1.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.5%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.5%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.5%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.5%    |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.5%    |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.5%    |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.75%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.75%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.75%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.75%   |
| Intel Pentium M processor 1.80GHz             | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.75%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 1         | 0.75%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 0.75%   |
| Intel Core i9-10850K CPU @ 3.60GHz            | 1         | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.75%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 0.75%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.75%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.75%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.75%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 27        | 20.3%   |
| Intel Core i5           | 27        | 20.3%   |
| Intel Core i3           | 15        | 11.28%  |
| Other                   | 11        | 8.27%   |
| AMD Ryzen 7             | 11        | 8.27%   |
| Intel Celeron           | 9         | 6.77%   |
| Intel Core 2 Duo        | 8         | 6.02%   |
| AMD Ryzen 5             | 5         | 3.76%   |
| Intel Atom              | 3         | 2.26%   |
| Intel Xeon              | 2         | 1.5%    |
| Intel Pentium Silver    | 2         | 1.5%    |
| AMD Ryzen 9             | 2         | 1.5%    |
| AMD Ryzen 3             | 2         | 1.5%    |
| Intel Pentium M         | 1         | 0.75%   |
| Intel Pentium Dual-Core | 1         | 0.75%   |
| Intel Pentium Dual      | 1         | 0.75%   |
| Intel Genuine           | 1         | 0.75%   |
| Intel Core i9           | 1         | 0.75%   |
| AMD Turion 64 X2 Mobile | 1         | 0.75%   |
| AMD Sempron             | 1         | 0.75%   |
| AMD Ryzen Threadripper  | 1         | 0.75%   |
| AMD Phenom II X4        | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 53        | 39.85%  |
| 4      | 47        | 35.34%  |
| 8      | 13        | 9.77%   |
| 6      | 11        | 8.27%   |
| 12     | 3         | 2.26%   |
| 1      | 3         | 2.26%   |
| 14     | 2         | 1.5%    |
| 10     | 1         | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 132       | 99.25%  |
| 2      | 1         | 0.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 91        | 68.42%  |
| 1      | 42        | 31.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 130       | 97.74%  |
| 32-bit         | 3         | 2.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 11.11%  |
| 0x306a9    | 10        | 7.41%   |
| 0x206a7    | 10        | 7.41%   |
| 0x506e3    | 6         | 4.44%   |
| 0x20655    | 6         | 4.44%   |
| 0x806c1    | 5         | 3.7%    |
| 0x306c3    | 5         | 3.7%    |
| 0x1067a    | 5         | 3.7%    |
| 0x406e3    | 4         | 2.96%   |
| 0x0a50000c | 4         | 2.96%   |
| 0xa0652    | 3         | 2.22%   |
| 0x906ea    | 3         | 2.22%   |
| 0x806ea    | 3         | 2.22%   |
| 0x706a8    | 3         | 2.22%   |
| 0x6fd      | 3         | 2.22%   |
| 0xa0653    | 2         | 1.48%   |
| 0x906a3    | 2         | 1.48%   |
| 0x806e9    | 2         | 1.48%   |
| 0x706a1    | 2         | 1.48%   |
| 0x406c4    | 2         | 1.48%   |
| 0x306f2    | 2         | 1.48%   |
| 0x306d4    | 2         | 1.48%   |
| 0x30678    | 2         | 1.48%   |
| 0x08701021 | 2         | 1.48%   |
| 0x08608103 | 2         | 1.48%   |
| 0x08600106 | 2         | 1.48%   |
| 0x0800820d | 2         | 1.48%   |
| 0xa0671    | 1         | 0.74%   |
| 0xa0655    | 1         | 0.74%   |
| 0x906ed    | 1         | 0.74%   |
| 0x806ec    | 1         | 0.74%   |
| 0x806eb    | 1         | 0.74%   |
| 0x806d1    | 1         | 0.74%   |
| 0x706e5    | 1         | 0.74%   |
| 0x6fb      | 1         | 0.74%   |
| 0x6e8      | 1         | 0.74%   |
| 0x6d6      | 1         | 0.74%   |
| 0x506c9    | 1         | 0.74%   |
| 0x406c3    | 1         | 0.74%   |
| 0x40661    | 1         | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 11        | 8.27%   |
| KabyLake         | 11        | 8.27%   |
| IvyBridge        | 11        | 8.27%   |
| Haswell          | 11        | 8.27%   |
| Skylake          | 10        | 7.52%   |
| Zen 3            | 8         | 6.02%   |
| Westmere         | 7         | 5.26%   |
| TigerLake        | 6         | 4.51%   |
| Penryn           | 6         | 4.51%   |
| CometLake        | 6         | 4.51%   |
| Zen+             | 5         | 3.76%   |
| Zen 2            | 5         | 3.76%   |
| Silvermont       | 5         | 3.76%   |
| Goldmont plus    | 5         | 3.76%   |
| IceLake          | 4         | 3.01%   |
| Core             | 4         | 3.01%   |
| Unknown          | 3         | 2.26%   |
| P6               | 2         | 1.5%    |
| Nehalem          | 2         | 1.5%    |
| K8 Hammer        | 2         | 1.5%    |
| Broadwell        | 2         | 1.5%    |
| Bonnell          | 2         | 1.5%    |
| Zen              | 1         | 0.75%   |
| K8 & K10 hybrid  | 1         | 0.75%   |
| K10              | 1         | 0.75%   |
| Goldmont         | 1         | 0.75%   |
| Alderlake Hybrid | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 89        | 53.94%  |
| Nvidia | 47        | 28.48%  |
| AMD    | 29        | 17.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 6.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 3.55%   |
| Intel HD Graphics 530                                                                    | 5         | 2.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.96%   |
| AMD Cezanne                                                                              | 5         | 2.96%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 2.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.37%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 1.78%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.18%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 1.18%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.18%   |
| Intel HD Graphics 620                                                                    | 2         | 1.18%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.18%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.18%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.18%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 1.18%   |
| AMD Renoir                                                                               | 2         | 1.18%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2         | 1.18%   |
| AMD Lucienne                                                                             | 2         | 1.18%   |
| Nvidia TU117M                                                                            | 1         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.59%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.59%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.59%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.59%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.59%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 59        | 44.36%  |
| 1 x Nvidia     | 23        | 17.29%  |
| Intel + Nvidia | 21        | 15.79%  |
| 1 x AMD        | 20        | 15.04%  |
| Intel + AMD    | 5         | 3.76%   |
| AMD + Nvidia   | 3         | 2.26%   |
| 2 x Intel      | 1         | 0.75%   |
| 2 x AMD        | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 102       | 75.56%  |
| Proprietary | 25        | 18.52%  |
| Unknown     | 8         | 5.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 69.92%  |
| 0.01-0.5   | 10        | 7.52%   |
| 7.01-8.0   | 8         | 6.02%   |
| 1.01-2.0   | 7         | 5.26%   |
| 0.51-1.0   | 7         | 5.26%   |
| 3.01-4.0   | 6         | 4.51%   |
| 8.01-16.0  | 2         | 1.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 12.33%  |
| Chimei Innolux          | 15        | 10.27%  |
| AU Optronics            | 15        | 10.27%  |
| LG Display              | 12        | 8.22%   |
| BOE                     | 12        | 8.22%   |
| Hewlett-Packard         | 7         | 4.79%   |
| Acer                    | 6         | 4.11%   |
| Dell                    | 5         | 3.42%   |
| Apple                   | 5         | 3.42%   |
| Sharp                   | 4         | 2.74%   |
| PANDA                   | 4         | 2.74%   |
| Goldstar                | 4         | 2.74%   |
| Fujitsu Siemens         | 4         | 2.74%   |
| Ancor Communications    | 4         | 2.74%   |
| Lenovo                  | 3         | 2.05%   |
| Chi Mei Optoelectronics | 3         | 2.05%   |
| AOC                     | 3         | 2.05%   |
| Sony                    | 2         | 1.37%   |
| Philips                 | 2         | 1.37%   |
| Medion                  | 2         | 1.37%   |
| Iiyama                  | 2         | 1.37%   |
| Vizio                   | 1         | 0.68%   |
| Vestel Elektronik       | 1         | 0.68%   |
| Sunplus                 | 1         | 0.68%   |
| SAC                     | 1         | 0.68%   |
| Panasonic               | 1         | 0.68%   |
| NEC Computers           | 1         | 0.68%   |
| MiTAC                   | 1         | 0.68%   |
| LTM                     | 1         | 0.68%   |
| InfoVision              | 1         | 0.68%   |
| Hitachi                 | 1         | 0.68%   |
| Grundig                 | 1         | 0.68%   |
| Gigabyte Technology     | 1         | 0.68%   |
| Eizo                    | 1         | 0.68%   |
| CPT                     | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 1.35%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 1.35%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 1.35%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 1.35%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 1.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.35%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                       | 1         | 0.68%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch       | 1         | 0.68%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 0.68%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.68%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 0.68%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.68%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.68%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.68%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch     | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch      | 1         | 0.68%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch         | 1         | 0.68%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.68%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.68%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch        | 1         | 0.68%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 1020x570mm 46.0-inch   | 1         | 0.68%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch        | 1         | 0.68%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 1         | 0.68%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                    | 1         | 0.68%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                 | 1         | 0.68%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 0.68%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 0.68%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 0.68%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 40.29%  |
| 1366x768 (WXGA)    | 28        | 20.14%  |
| 3840x2160 (4K)     | 11        | 7.91%   |
| 2560x1440 (QHD)    | 8         | 5.76%   |
| 1680x1050 (WSXGA+) | 7         | 5.04%   |
| 1600x900 (HD+)     | 4         | 2.88%   |
| 1280x1024 (SXGA)   | 4         | 2.88%   |
| 1920x1200 (WUXGA)  | 3         | 2.16%   |
| 1440x900 (WXGA+)   | 3         | 2.16%   |
| 3440x1440          | 2         | 1.44%   |
| 2560x1080          | 2         | 1.44%   |
| 1280x800 (WXGA)    | 2         | 1.44%   |
| 3840x2400          | 1         | 0.72%   |
| 2880x1800          | 1         | 0.72%   |
| 2736x1824          | 1         | 0.72%   |
| 2256x1504          | 1         | 0.72%   |
| 2160x1440          | 1         | 0.72%   |
| 1400x1050          | 1         | 0.72%   |
| 1360x768           | 1         | 0.72%   |
| 1280x720 (HD)      | 1         | 0.72%   |
| 1024x600           | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46        | 31.94%  |
| 27      | 11        | 7.64%   |
| 13      | 11        | 7.64%   |
| 23      | 10        | 6.94%   |
| 17      | 9         | 6.25%   |
| 14      | 9         | 6.25%   |
| 24      | 6         | 4.17%   |
| 22      | 6         | 4.17%   |
| 31      | 5         | 3.47%   |
| 11      | 5         | 3.47%   |
| 34      | 4         | 2.78%   |
| 21      | 4         | 2.78%   |
| 19      | 4         | 2.78%   |
| 84      | 3         | 2.08%   |
| 54      | 1         | 0.69%   |
| 46      | 1         | 0.69%   |
| 40      | 1         | 0.69%   |
| 26      | 1         | 0.69%   |
| 25      | 1         | 0.69%   |
| 20      | 1         | 0.69%   |
| 18      | 1         | 0.69%   |
| 16      | 1         | 0.69%   |
| 12      | 1         | 0.69%   |
| 10      | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 61        | 42.96%  |
| 501-600     | 27        | 19.01%  |
| 401-500     | 13        | 9.15%   |
| 201-300     | 13        | 9.15%   |
| 351-400     | 12        | 8.45%   |
| 601-700     | 5         | 3.52%   |
| 701-800     | 4         | 2.82%   |
| 1501-2000   | 3         | 2.11%   |
| 1001-1500   | 2         | 1.41%   |
| 801-900     | 1         | 0.7%    |
| Unknown     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 103       | 76.3%   |
| 16/10 | 19        | 14.07%  |
| 5/4   | 5         | 3.7%    |
| 21/9  | 4         | 2.96%   |
| 3/2   | 3         | 2.22%   |
| 4/3   | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 31.25%  |
| 201-250        | 21        | 14.58%  |
| 81-90          | 18        | 12.5%   |
| 301-350        | 11        | 7.64%   |
| 351-500        | 9         | 6.25%   |
| 151-200        | 8         | 5.56%   |
| 121-130        | 8         | 5.56%   |
| 51-60          | 5         | 3.47%   |
| 251-300        | 5         | 3.47%   |
| More than 1000 | 4         | 2.78%   |
| 71-80          | 3         | 2.08%   |
| 141-150        | 2         | 1.39%   |
| 501-1000       | 2         | 1.39%   |
| 41-50          | 1         | 0.69%   |
| 91-100         | 1         | 0.69%   |
| Unknown        | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 50        | 36.23%  |
| 121-160       | 42        | 30.43%  |
| 101-120       | 31        | 22.46%  |
| 161-240       | 6         | 4.35%   |
| More than 240 | 5         | 3.62%   |
| 1-50          | 3         | 2.17%   |
| Unknown       | 1         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 103       | 76.3%   |
| 2     | 20        | 14.81%  |
| 0     | 7         | 5.19%   |
| 3     | 5         | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 68        | 33.33%  |
| Intel                    | 67        | 32.84%  |
| Qualcomm Atheros         | 25        | 12.25%  |
| Broadcom                 | 11        | 5.39%   |
| TP-Link                  | 5         | 2.45%   |
| Ralink Technology        | 4         | 1.96%   |
| Marvell Technology Group | 4         | 1.96%   |
| Nvidia                   | 3         | 1.47%   |
| MediaTek                 | 3         | 1.47%   |
| Broadcom Limited         | 3         | 1.47%   |
| Xiaomi                   | 1         | 0.49%   |
| Sierra Wireless          | 1         | 0.49%   |
| Samsung Electronics      | 1         | 0.49%   |
| Microsoft                | 1         | 0.49%   |
| Mercucys                 | 1         | 0.49%   |
| Lenovo                   | 1         | 0.49%   |
| Edimax Technology        | 1         | 0.49%   |
| Dell                     | 1         | 0.49%   |
| AVM                      | 1         | 0.49%   |
| ASUSTek Computer         | 1         | 0.49%   |
| Aquantia                 | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 49        | 20.59%  |
| Intel Wi-Fi 6 AX200                                                     | 10        | 4.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.1%    |
| Intel Wireless 8260                                                     | 5         | 2.1%    |
| Intel Wireless 8265 / 8275                                              | 4         | 1.68%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 1.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 1.26%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.26%   |
| Intel Wireless 7260                                                     | 3         | 1.26%   |
| Intel I211 Gigabit Network Connection                                   | 3         | 1.26%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.84%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.84%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 2         | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.84%   |
| Intel Wireless 7265                                                     | 2         | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.84%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.84%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.84%   |
| Intel Ethernet Connection (2) I218-V                                    | 2         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.84%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 2         | 0.84%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 2         | 0.84%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                       | 2         | 0.84%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 2         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 0.84%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 0.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 45.61%  |
| Realtek Semiconductor | 20        | 17.54%  |
| Qualcomm Atheros      | 16        | 14.04%  |
| Broadcom              | 7         | 6.14%   |
| TP-Link               | 4         | 3.51%   |
| Ralink Technology     | 4         | 3.51%   |
| MediaTek              | 3         | 2.63%   |
| Broadcom Limited      | 3         | 2.63%   |
| Sierra Wireless       | 1         | 0.88%   |
| Mercucys              | 1         | 0.88%   |
| Edimax Technology     | 1         | 0.88%   |
| AVM                   | 1         | 0.88%   |
| ASUSTek Computer      | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 8.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.39%   |
| Intel Wireless 8260                                                     | 5         | 4.39%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.51%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 3.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 2.63%   |
| Realtek 802.11ac NIC                                                    | 3         | 2.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 2.63%   |
| Intel Wireless 7260                                                     | 3         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.75%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.75%   |
| Intel Wireless 7265                                                     | 2         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.75%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.75%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.75%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.88%   |
| Sierra Wireless EM7455                                                  | 1         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.88%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.88%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.88%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.88%   |
| Realtek B1690189192                                                     | 1         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.88%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 50%     |
| Intel                    | 28        | 24.14%  |
| Qualcomm Atheros         | 11        | 9.48%   |
| Broadcom                 | 6         | 5.17%   |
| Marvell Technology Group | 4         | 3.45%   |
| Nvidia                   | 3         | 2.59%   |
| Xiaomi                   | 1         | 0.86%   |
| TP-Link                  | 1         | 0.86%   |
| Samsung Electronics      | 1         | 0.86%   |
| Microsoft                | 1         | 0.86%   |
| Lenovo                   | 1         | 0.86%   |
| Aquantia                 | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 49        | 39.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 5.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 2.44%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 2.44%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.44%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.63%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 2         | 1.63%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.63%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.63%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.63%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.63%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 1.63%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 2         | 1.63%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 1.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.81%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.81%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.81%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.81%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.81%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.81%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.81%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                              | 1         | 0.81%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.81%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.81%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.81%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 112       | 51.14%  |
| WiFi     | 106       | 48.4%   |
| Modem    | 1         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 61.43%  |
| Ethernet | 54        | 38.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 53.38%  |
| 1     | 57        | 42.86%  |
| 3     | 3         | 2.26%   |
| 0     | 2         | 1.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 97        | 72.39%  |
| Yes  | 37        | 27.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 48.19%  |
| Apple                           | 8         | 9.64%   |
| Qualcomm Atheros Communications | 7         | 8.43%   |
| Realtek Semiconductor           | 6         | 7.23%   |
| Cambridge Silicon Radio         | 5         | 6.02%   |
| Broadcom                        | 5         | 6.02%   |
| IMC Networks                    | 3         | 3.61%   |
| Foxconn / Hon Hai               | 3         | 3.61%   |
| ASUSTek Computer                | 3         | 3.61%   |
| Lite-On Technology              | 1         | 1.2%    |
| Hewlett-Packard                 | 1         | 1.2%    |
| Dell                            | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 16.87%  |
| Intel AX200 Bluetooth                                                               | 10        | 12.05%  |
| Intel AX201 Bluetooth                                                               | 8         | 9.64%   |
| Realtek Bluetooth Radio                                                             | 5         | 6.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 6.02%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 4.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 4.82%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 3.61%   |
| IMC Networks Wireless_Device                                                        | 2         | 2.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 2.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 2.41%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.41%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.2%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.2%    |
| Lite-On Wireless_Device                                                             | 1         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.2%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.2%    |
| Intel Bluetooth Device                                                              | 1         | 1.2%    |
| Intel AX210 Bluetooth                                                               | 1         | 1.2%    |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.2%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.2%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.2%    |
| Broadcom HP Portable Valentine                                                      | 1         | 1.2%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.2%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.2%    |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 1.2%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.2%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 1.2%    |
| Apple Bluetooth HCI                                                                 | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 106       | 53.81%  |
| Nvidia                     | 38        | 19.29%  |
| AMD                        | 29        | 14.72%  |
| C-Media Electronics        | 4         | 2.03%   |
| ROCCAT                     | 2         | 1.02%   |
| Creative Labs              | 2         | 1.02%   |
| Unknown                    | 1         | 0.51%   |
| Texas Instruments          | 1         | 0.51%   |
| TerraTec Electronic        | 1         | 0.51%   |
| Shenzhen Riitek Technology | 1         | 0.51%   |
| Schiit Audio               | 1         | 0.51%   |
| Realtek Semiconductor      | 1         | 0.51%   |
| Razer USA                  | 1         | 0.51%   |
| Plantronics                | 1         | 0.51%   |
| Logitech                   | 1         | 0.51%   |
| LG Electronics             | 1         | 0.51%   |
| Lenovo                     | 1         | 0.51%   |
| JMTek                      | 1         | 0.51%   |
| GN Netcom                  | 1         | 0.51%   |
| FIFINE 683 Microphone      | 1         | 0.51%   |
| BEHRINGER International    | 1         | 0.51%   |
| Apple                      | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 6.31%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 5.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 4.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 3.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.25%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 1.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 1.8%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.8%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.35%   |
| Nvidia Audio device                                                                               | 3         | 1.35%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.35%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.35%   |
| ROCCAT Khan AIMO                                                                                  | 2         | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.9%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.9%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.9%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.9%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 20.39%  |
| SK hynix            | 27        | 17.76%  |
| Kingston            | 20        | 13.16%  |
| Unknown             | 19        | 12.5%   |
| Micron Technology   | 11        | 7.24%   |
| Crucial             | 9         | 5.92%   |
| Corsair             | 9         | 5.92%   |
| G.Skill             | 5         | 3.29%   |
| Nanya Technology    | 3         | 1.97%   |
| Unknown             | 3         | 1.97%   |
| Unknown (ABCD)      | 2         | 1.32%   |
| Transcend           | 2         | 1.32%   |
| Smart               | 2         | 1.32%   |
| A-DATA Technology   | 2         | 1.32%   |
| Team                | 1         | 0.66%   |
| Ramaxel Technology  | 1         | 0.66%   |
| PNY                 | 1         | 0.66%   |
| Innodisk            | 1         | 0.66%   |
| Elpida              | 1         | 0.66%   |
| Avant               | 1         | 0.66%   |
| 48spaces            | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.83%   |
| Unknown                                                          | 3         | 1.83%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 1.22%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.22%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2         | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.22%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.22%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.22%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 1.22%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 1.22%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.22%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.22%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.22%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 2         | 1.22%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.22%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM                                      | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.61%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s               | 1         | 0.61%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                 | 1         | 0.61%   |
| Team RAM Elite-1600 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 43.94%  |
| DDR3    | 50        | 37.88%  |
| DDR2    | 10        | 7.58%   |
| LPDDR4  | 6         | 4.55%   |
| SDRAM   | 2         | 1.52%   |
| DDR     | 2         | 1.52%   |
| Unknown | 2         | 1.52%   |
| DRAM    | 1         | 0.76%   |
| DDR5    | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 67.42%  |
| DIMM         | 36        | 27.27%  |
| Row Of Chips | 7         | 5.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 52        | 35.86%  |
| 4096  | 48        | 33.1%   |
| 2048  | 23        | 15.86%  |
| 16384 | 12        | 8.28%   |
| 32768 | 5         | 3.45%   |
| 1024  | 5         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 24        | 17.27%  |
| 3200    | 23        | 16.55%  |
| 2667    | 14        | 10.07%  |
| 1333    | 14        | 10.07%  |
| 2400    | 12        | 8.63%   |
| Unknown | 9         | 6.47%   |
| 2133    | 8         | 5.76%   |
| 667     | 6         | 4.32%   |
| 3600    | 4         | 2.88%   |
| 1334    | 3         | 2.16%   |
| 4267    | 2         | 1.44%   |
| 3400    | 2         | 1.44%   |
| 2666    | 2         | 1.44%   |
| 2048    | 2         | 1.44%   |
| 333     | 2         | 1.44%   |
| 4800    | 1         | 0.72%   |
| 4199    | 1         | 0.72%   |
| 3733    | 1         | 0.72%   |
| 3466    | 1         | 0.72%   |
| 2933    | 1         | 0.72%   |
| 1866    | 1         | 0.72%   |
| 1800    | 1         | 0.72%   |
| 1639    | 1         | 0.72%   |
| 1400    | 1         | 0.72%   |
| 1067    | 1         | 0.72%   |
| 800     | 1         | 0.72%   |
| 166     | 1         | 0.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Brother Industries | 2         | 40%     |
| Canon              | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 20%     |
| HP LaserJet 1022         | 1         | 20%     |
| Canon MF641C             | 1         | 20%     |
| Brother MFC-7340         | 1         | 20%     |
| Brother DCP-L2540DW      | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 21.43%  |
| Acer                                   | 9         | 10.71%  |
| Microdia                               | 7         | 8.33%   |
| Realtek Semiconductor                  | 6         | 7.14%   |
| Logitech                               | 6         | 7.14%   |
| Sunplus Innovation Technology          | 4         | 4.76%   |
| Lite-On Technology                     | 4         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.76%   |
| Quanta                                 | 3         | 3.57%   |
| IMC Networks                           | 3         | 3.57%   |
| Apple                                  | 3         | 3.57%   |
| Suyin                                  | 2         | 2.38%   |
| Silicon Motion                         | 2         | 2.38%   |
| Ricoh                                  | 2         | 2.38%   |
| Microsoft                              | 2         | 2.38%   |
| Z-Star Microelectronics                | 1         | 1.19%   |
| Y Media                                | 1         | 1.19%   |
| Primax Electronics                     | 1         | 1.19%   |
| Luxvisions Innotech Limited            | 1         | 1.19%   |
| LG Electronics                         | 1         | 1.19%   |
| Lenovo                                 | 1         | 1.19%   |
| Goodong Industry                       | 1         | 1.19%   |
| Generalplus Technology                 | 1         | 1.19%   |
| Alcor Micro                            | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 3         | 3.57%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.38%   |
| Quanta HD User Facing                               | 2         | 2.38%   |
| Microsoft LifeCam HD-3000                           | 2         | 2.38%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.38%   |
| Logitech Webcam C930e                               | 2         | 2.38%   |
| Logitech Webcam C270                                | 2         | 2.38%   |
| Chicony HD User Facing                              | 2         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 2.38%   |
| Acer Integrated Camera                              | 2         | 2.38%   |
| Acer BisonCam,NB Pro                                | 2         | 2.38%   |
| Acer BisonCam, NB Pro                               | 2         | 2.38%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.19%   |
| Y Media USB Camera                                  | 1         | 1.19%   |
| Suyin Sony Visual Communication Camera              | 1         | 1.19%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.19%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.19%   |
| Sunplus HD 720P webcam                              | 1         | 1.19%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 1.19%   |
| Silicon Motion Web Camera                           | 1         | 1.19%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.19%   |
| Ricoh Integrated Webcam                             | 1         | 1.19%   |
| Realtek USB Camera                                  | 1         | 1.19%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.19%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.19%   |
| Realtek Integrated Webcam HD                        | 1         | 1.19%   |
| Realtek Integrated Webcam                           | 1         | 1.19%   |
| Realtek EasyCamera                                  | 1         | 1.19%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.19%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 1.19%   |
| Microdia Webcam Vitade AF                           | 1         | 1.19%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 1.19%   |
| Microdia Webcam                                     | 1         | 1.19%   |
| Microdia USB 2.0 Camera                             | 1         | 1.19%   |
| Microdia Laptop_Integrated_Webcam_2HDM              | 1         | 1.19%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.19%   |
| Logitech StreamCam                                  | 1         | 1.19%   |
| Logitech HD Webcam C615                             | 1         | 1.19%   |
| Lite-On Integrated Camera                           | 1         | 1.19%   |
| Lite-On HP HD Webcam                                | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 38.46%  |
| Shenzhen Goodix Technology | 3         | 23.08%  |
| Synaptics                  | 2         | 15.38%  |
| AuthenTec                  | 2         | 15.38%  |
| Upek                       | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 3         | 23.08%  |
| Validity Sensors VFS495 Fingerprint Reader       | 2         | 15.38%  |
| Shenzhen Goodix  FingerPrint Device              | 2         | 15.38%  |
| Upek TCS5B Fingerprint sensor                    | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader               | 1         | 7.69%   |
| AuthenTec AES2810                                | 1         | 7.69%   |
| AuthenTec AES1660 Fingerprint Sensor             | 1         | 7.69%   |
| Unknown                                          | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 3         | 50%     |
| Alcor Micro           | 2         | 33.33%  |
| Advanced Card Systems | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 16.67%  |
| Advanced Card Systems ACR122U                  | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 66.91%  |
| 1     | 34        | 25%     |
| 2     | 10        | 7.35%   |
| 3     | 1         | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 27        | 50.94%  |
| Fingerprint reader       | 13        | 24.53%  |
| Chipcard                 | 5         | 9.43%   |
| Unassigned class         | 3         | 5.66%   |
| Multimedia controller    | 2         | 3.77%   |
| Net/wireless             | 1         | 1.89%   |
| Dvb card                 | 1         | 1.89%   |
| Communication controller | 1         | 1.89%   |

