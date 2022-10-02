MX - Tested Hardware & Statistics (Notebooks)
---------------------------------------------

A project to collect tested hardware configurations for MX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 296

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 250 G6 Notebook PC          | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| Dell          | Inspiron 5521               | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Apple         | MacBookAir7,2               | [d562164e67](https://linux-hardware.org/?probe=d562164e67) | Sep 12, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | [f8f2a6263a](https://linux-hardware.org/?probe=f8f2a6263a) | Sep 04, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Unknown       | Unknown                     | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Unknown       | Unknown                     | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Acer          | Extensa 5630                | [9ea053d8e8](https://linux-hardware.org/?probe=9ea053d8e8) | Aug 12, 2022 |
| Dell          | System XPS 15Z              | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Dell          | Vostro 3550                 | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| UMAX          | VisionBook-N12R             | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Alienware     | 13 R2                       | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| Sony          | VPCSB1V9R                   | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| Acer          | Aspire A515-56              | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Acer          | Nitro AN515-55              | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | 1101HA                      | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Acer          | Extensa 5630                | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| HP            | ProBook 6460b               | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | 2000                        | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Toshiba       | Satellite L850-CJK          | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | Unknown                     | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Unknown       | Unknown                     | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Dell          | Inspiron 3576               | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| Google        | Akemi                       | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Dell          | Latitude E7450              | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Dell          | Latitude 3190               | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Lenovo        | ThinkPad L520 78595VG       | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Sony          | SVT13115FBS                 | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Lenovo        | ThinkPad L490 20Q5S0PR00    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer          | Aspire 4820T                | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Lenovo        | ThinkPad P51 20HJS0TP00     | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo        | B40-45 20394                | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| GTZS          | Unknown                     | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Pixus         | Rise                        | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| Acer          | Aspire E5-574G              | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3340               | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Acer          | Aspire one                  | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Medion        | P6669 MD60147               | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |
| Dell          | Vostro 3460                 | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Irbis         | TW94                        | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| Dell          | Latitude E6320              | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| Acer          | Extensa 5620                | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Intel         | ChiefRiver                  | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASUSTek       | G751JT                      | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| HP            | Falco                       | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| HP            | ZBook 17 G6                 | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| Dell          | Latitude E5470              | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Lenovo        | ThinkPad E425 1198CTO       | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | Mini 110-3500               | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP            | Notebook                    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| HP            | 15                          | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| Apple         | MacBook7,1                  | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo         | P170EM                      | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Mini 110-3500               | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| Dell          | Latitude E5520              | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| Lenovo        | ThinkPad X220 4291WMQ       | [165b895e27](https://linux-hardware.org/?probe=165b895e27) | Dec 01, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer          | Aspire E5-571G              | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Toshiba       | Satellite A300              | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| HP            | Compaq 8510p (KM229AV)      | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| Acer          | Aspire SW5-015              | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| HP            | Pavilion 15                 | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo        | V145-15AST 81MT             | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Toshiba       | Satellite C660              | [a5f308c899](https://linux-hardware.org/?probe=a5f308c899) | Sep 21, 2020 |
| Lenovo        | ThinkPad T60 20085TG        | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire A114-32              | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| Acer          | Aspire 7520                 | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| HP            | Pavilion dv7                | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| HP            | ProBook 650 G1              | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Sony          | VPCF23P1E                   | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| Acer          | Aspire A315-41              | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo        | B590 20206                  | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Samsung       | R780/R778                   | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Clevo         | P150HMx                     | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| Dell          | Latitude E7440              | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| ASUSTek       | X455LAB                     | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook      | W65_W67RZ1                  | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Dell          | Inspiron 13-5378            | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| Medion        | Akoya E1318T                | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |
| Dell          | Latitude 3190               | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Acer          | Aspire 8943G                | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [370f5d5063](https://linux-hardware.org/?probe=370f5d5063) | Feb 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T11... | [9c888bfdde](https://linux-hardware.org/?probe=9c888bfdde) | Feb 11, 2020 |
| Lenovo        | ThinkPad X201 3680MY9       | [26a7c0e493](https://linux-hardware.org/?probe=26a7c0e493) | Feb 09, 2020 |
| Google        | Gnawty                      | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | [8865e9546b](https://linux-hardware.org/?probe=8865e9546b) | Feb 03, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | [f4779c95ce](https://linux-hardware.org/?probe=f4779c95ce) | Feb 03, 2020 |
| Acer          | Swift SF314-54G             | [48912b8dc6](https://linux-hardware.org/?probe=48912b8dc6) | Jan 19, 2020 |
| ASUSTek       | TUF Gaming FX505GT_TUF50... | [0abd5b1d73](https://linux-hardware.org/?probe=0abd5b1d73) | Jan 18, 2020 |
| Toshiba       | Satellite P875              | [b267e93d40](https://linux-hardware.org/?probe=b267e93d40) | Jan 15, 2020 |
| Toshiba       | Satellite P875              | [7e579fcba2](https://linux-hardware.org/?probe=7e579fcba2) | Jan 15, 2020 |
| MSI           | GP63 Leopard 8RD            | [0a8865c437](https://linux-hardware.org/?probe=0a8865c437) | Jan 13, 2020 |
| Packard Be... | EasyNote TE11HC             | [aa52528043](https://linux-hardware.org/?probe=aa52528043) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| HP            | Pavilion g6                 | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| Dell          | G3 3579                     | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Laptop 14-ck0xxx            | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| MSI           | MS-N033                     | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| ASUSTek       | 1005HA                      | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| ASUSTek       | X101CH                      | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| HP            | Laptop 14-cm0xxx            | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| MSI           | GP63 Leopard 8RD            | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| HP            | Pavilion g6                 | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| Lenovo        | ThinkPad X220 4291F52       | [e024139431](https://linux-hardware.org/?probe=e024139431) | Aug 29, 2019 |
| Lenovo        | ThinkPad X201s 5413A19      | [673c3629dc](https://linux-hardware.org/?probe=673c3629dc) | Aug 22, 2019 |
| Panasonic     | CF-C1BT02EGE                | [acbec08287](https://linux-hardware.org/?probe=acbec08287) | Aug 15, 2019 |
| MSI           | GP63 Leopard 8RD            | [bf82fba8fd](https://linux-hardware.org/?probe=bf82fba8fd) | Apr 29, 2019 |
| ASUSTek       | K55VM                       | [e967dd6404](https://linux-hardware.org/?probe=e967dd6404) | Mar 27, 2019 |
| MSI           | GP63 Leopard 8RD            | [67b484c4a0](https://linux-hardware.org/?probe=67b484c4a0) | Jan 19, 2019 |
| Toshiba       | Satellite C70-B             | [9b54677f2e](https://linux-hardware.org/?probe=9b54677f2e) | Oct 27, 2018 |
| MSI           | GP63 Leopard 8RD            | [ec89febb0c](https://linux-hardware.org/?probe=ec89febb0c) | Oct 27, 2018 |
| Dell          | Inspiron ME051              | [f789720dc4](https://linux-hardware.org/?probe=f789720dc4) | Nov 26, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| MX 19 | 85        | 37.44%  |
| MX 21 | 83        | 36.56%  |
| MX 20 | 43        | 18.94%  |
| MX 18 | 13        | 5.73%   |
| MX 17 | 2         | 0.88%   |
| MX 16 | 1         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MX   | 219       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 4.19.0-6-amd64            | 33        | 13.64%  |
| 5.10.0-9-amd64            | 14        | 5.79%   |
| 5.10.0-5mx-amd64          | 13        | 5.37%   |
| 5.10.0-13-amd64           | 13        | 5.37%   |
| 5.8.0-3-amd64             | 9         | 3.72%   |
| 5.10.0-16-amd64           | 9         | 3.72%   |
| 5.14.0-4mx-amd64          | 8         | 3.31%   |
| 5.10.0-14-amd64           | 6         | 2.48%   |
| 5.10.0-11-amd64           | 6         | 2.48%   |
| 4.19.0-16-amd64           | 6         | 2.48%   |
| 4.19.0-14-amd64           | 6         | 2.48%   |
| 4.19.0-13-amd64           | 6         | 2.48%   |
| 5.6.0-2-amd64             | 5         | 2.07%   |
| 5.16.0-5mx-amd64          | 4         | 1.65%   |
| 4.19.0-5-amd64            | 4         | 1.65%   |
| 4.19.0-17-amd64           | 4         | 1.65%   |
| 4.19.0-11-amd64           | 4         | 1.65%   |
| 5.10.0-8mx-amd64          | 3         | 1.24%   |
| 5.10.0-18-amd64           | 3         | 1.24%   |
| 5.10.0-17-amd64           | 3         | 1.24%   |
| 4.19.0-9-amd64            | 3         | 1.24%   |
| 4.19.0-12-amd64           | 3         | 1.24%   |
| 4.19.0-1-amd64            | 3         | 1.24%   |
| 5.8.16-antix.1-amd64-smp  | 2         | 0.83%   |
| 5.6.10-antix.1-amd64-smp  | 2         | 0.83%   |
| 5.4.0-3-amd64             | 2         | 0.83%   |
| 5.16.0-6mx-amd64          | 2         | 0.83%   |
| 5.10.0-8-amd64            | 2         | 0.83%   |
| 5.10.0-15-amd64           | 2         | 0.83%   |
| 5.10.0-13-686-pae         | 2         | 0.83%   |
| 5.10.0-11-686-pae         | 2         | 0.83%   |
| 5.10.0-10-amd64           | 2         | 0.83%   |
| 4.19.0-8-amd64            | 2         | 0.83%   |
| 4.19.0-16-686-pae         | 2         | 0.83%   |
| 4.15.0-1-amd64            | 2         | 0.83%   |
| 5.9.1-rt20avl1            | 1         | 0.41%   |
| 5.7.0-19.1-liquorix-amd64 | 1         | 0.41%   |
| 5.6.0-15.2-liquorix-amd64 | 1         | 0.41%   |
| 5.6.0-12.1-liquorix-amd64 | 1         | 0.41%   |
| 5.5.0-9.1-liquorix-amd64  | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.0   | 80        | 34.33%  |
| 5.10.0   | 79        | 33.91%  |
| 5.8.0    | 9         | 3.86%   |
| 5.16.0   | 8         | 3.43%   |
| 5.14.0   | 8         | 3.43%   |
| 5.6.0    | 7         | 3%      |
| 5.4.0    | 6         | 2.58%   |
| 5.17.0   | 4         | 1.72%   |
| 5.8.16   | 2         | 0.86%   |
| 5.6.10   | 2         | 0.86%   |
| 5.3.0    | 2         | 0.86%   |
| 5.2.21   | 2         | 0.86%   |
| 5.18.0   | 2         | 0.86%   |
| 5.15.0   | 2         | 0.86%   |
| 4.9.193  | 2         | 0.86%   |
| 4.15.0   | 2         | 0.86%   |
| 5.9.1    | 1         | 0.43%   |
| 5.7.0    | 1         | 0.43%   |
| 5.5.0    | 1         | 0.43%   |
| 5.3.10   | 1         | 0.43%   |
| 5.2.8    | 1         | 0.43%   |
| 5.2.0    | 1         | 0.43%   |
| 5.19.0   | 1         | 0.43%   |
| 5.13.0   | 1         | 0.43%   |
| 5.11.0   | 1         | 0.43%   |
| 5.10.1   | 1         | 0.43%   |
| 5.1.2    | 1         | 0.43%   |
| 5.0.0    | 1         | 0.43%   |
| 4.9.246  | 1         | 0.43%   |
| 4.19.174 | 1         | 0.43%   |
| 4.18.0   | 1         | 0.43%   |
| 3.16.0   | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 81        | 34.76%  |
| 5.10    | 80        | 34.33%  |
| 5.8     | 11        | 4.72%   |
| 5.6     | 9         | 3.86%   |
| 5.16    | 8         | 3.43%   |
| 5.14    | 8         | 3.43%   |
| 5.4     | 6         | 2.58%   |
| 5.2     | 4         | 1.72%   |
| 5.17    | 4         | 1.72%   |
| 5.3     | 3         | 1.29%   |
| 4.9     | 3         | 1.29%   |
| 5.18    | 2         | 0.86%   |
| 5.15    | 2         | 0.86%   |
| 4.15    | 2         | 0.86%   |
| 5.9     | 1         | 0.43%   |
| 5.7     | 1         | 0.43%   |
| 5.5     | 1         | 0.43%   |
| 5.19    | 1         | 0.43%   |
| 5.13    | 1         | 0.43%   |
| 5.11    | 1         | 0.43%   |
| 5.1     | 1         | 0.43%   |
| 5.0     | 1         | 0.43%   |
| 4.18    | 1         | 0.43%   |
| 3.16    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 206       | 93.64%  |
| i686   | 14        | 6.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 155       | 69.82%  |
| KDE5            | 35        | 15.77%  |
| Budgie          | 6         | 2.7%    |
| Unknown         | 6         | 2.7%    |
| i3              | 5         | 2.25%   |
| MATE            | 2         | 0.9%    |
| LXQt            | 2         | 0.9%    |
| GNOME           | 2         | 0.9%    |
| Cinnamon        | 2         | 0.9%    |
| X-Cinnamon      | 1         | 0.45%   |
| Trinity         | 1         | 0.45%   |
| spectrwm        | 1         | 0.45%   |
| LXDE            | 1         | 0.45%   |
| GNOME Flashback | 1         | 0.45%   |
| GNOME Classic   | 1         | 0.45%   |
| fluxbox         | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 216       | 98.63%  |
| Tty  | 3         | 1.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 176       | 79.64%  |
| SDDM    | 30        | 13.57%  |
| TDM     | 9         | 4.07%   |
| SLiM    | 5         | 2.26%   |
| Unknown | 1         | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 81        | 35.84%  |
| Unknown | 56        | 24.78%  |
| de_DE   | 22        | 9.73%   |
| en_GB   | 10        | 4.42%   |
| ru_RU   | 8         | 3.54%   |
| it_IT   | 7         | 3.1%    |
| sk_SK   | 6         | 2.65%   |
| pt_BR   | 5         | 2.21%   |
| fr_FR   | 4         | 1.77%   |
| es_ES   | 4         | 1.77%   |
| tr_TR   | 2         | 0.88%   |
| pl_PL   | 2         | 0.88%   |
| en_NZ   | 2         | 0.88%   |
| en_IE   | 2         | 0.88%   |
| en_AU   | 2         | 0.88%   |
| zh_CN   | 1         | 0.44%   |
| uk_UA   | 1         | 0.44%   |
| nl_NL   | 1         | 0.44%   |
| nb_NO   | 1         | 0.44%   |
| id_ID   | 1         | 0.44%   |
| fr_BE   | 1         | 0.44%   |
| fi_FI   | 1         | 0.44%   |
| es_VE   | 1         | 0.44%   |
| es_PE   | 1         | 0.44%   |
| es_MX   | 1         | 0.44%   |
| es_CO   | 1         | 0.44%   |
| de_CH   | 1         | 0.44%   |
| cs_CZ   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 117       | 53.42%  |
| BIOS | 102       | 46.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 189       | 86.3%   |
| Overlay | 23        | 10.5%   |
| Btrfs   | 4         | 1.83%   |
| Xfs     | 1         | 0.46%   |
| F2fs    | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 135       | 61.36%  |
| MBR     | 81        | 36.82%  |
| Unknown | 4         | 1.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 178       | 80.18%  |
| Yes       | 44        | 19.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 126       | 57.27%  |
| Yes       | 94        | 42.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 51        | 23.29%  |
| Hewlett-Packard     | 35        | 15.98%  |
| Dell                | 26        | 11.87%  |
| ASUSTek Computer    | 23        | 10.5%   |
| Acer                | 22        | 10.05%  |
| Toshiba             | 8         | 3.65%   |
| Sony                | 8         | 3.65%   |
| Samsung Electronics | 5         | 2.28%   |
| MSI                 | 5         | 2.28%   |
| Medion              | 4         | 1.83%   |
| Apple               | 4         | 1.83%   |
| Fujitsu Siemens     | 3         | 1.37%   |
| Alienware           | 3         | 1.37%   |
| Unknown             | 3         | 1.37%   |
| Notebook            | 2         | 0.91%   |
| Google              | 2         | 0.91%   |
| Gigabyte Technology | 2         | 0.91%   |
| Clevo               | 2         | 0.91%   |
| UMAX                | 1         | 0.46%   |
| TUXEDO              | 1         | 0.46%   |
| Pixus               | 1         | 0.46%   |
| Panasonic           | 1         | 0.46%   |
| Packard Bell        | 1         | 0.46%   |
| Irbis               | 1         | 0.46%   |
| Intel               | 1         | 0.46%   |
| Framework           | 1         | 0.46%   |
| eMachines           | 1         | 0.46%   |
| efirstview          | 1         | 0.46%   |
| Chuwi               | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 5         | 2.28%   |
| HP Stream Laptop 14-cb0XX           | 2         | 0.91%   |
| HP ProBook 650 G1                   | 2         | 0.91%   |
| UMAX VisionBook-N12R                | 1         | 0.46%   |
| TUXEDO N7x0WU                       | 1         | 0.46%   |
| Toshiba Satellite P875              | 1         | 0.46%   |
| Toshiba Satellite L850-CJK          | 1         | 0.46%   |
| Toshiba Satellite C845              | 1         | 0.46%   |
| Toshiba Satellite C70-B             | 1         | 0.46%   |
| Toshiba Satellite C660              | 1         | 0.46%   |
| Toshiba Satellite C50-A-12K         | 1         | 0.46%   |
| Toshiba Satellite A300              | 1         | 0.46%   |
| Toshiba PORTEGE R705                | 1         | 0.46%   |
| Sony VPCSB1V9R                      | 1         | 0.46%   |
| Sony VPCF23P1E                      | 1         | 0.46%   |
| Sony VPCF119FX                      | 1         | 0.46%   |
| Sony VPCEH2N1E                      | 1         | 0.46%   |
| Sony VPCEC3S1E                      | 1         | 0.46%   |
| Sony VGN-NR310FH                    | 1         | 0.46%   |
| Sony SVT13115FBS                    | 1         | 0.46%   |
| Sony SVE1513Q1ESI                   | 1         | 0.46%   |
| Samsung R780/R778                   | 1         | 0.46%   |
| Samsung NC210/NC110                 | 1         | 0.46%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.46%   |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.46%   |
| Samsung 305E4A/305E5A/305E7A        | 1         | 0.46%   |
| Pixus Rise                          | 1         | 0.46%   |
| Panasonic CF-C1BT02EGE              | 1         | 0.46%   |
| Packard Bell EasyNote TE11HC        | 1         | 0.46%   |
| Notebook W65_W67RZ1                 | 1         | 0.46%   |
| Notebook PD5x_7xPNP_PNN_PNT         | 1         | 0.46%   |
| MSI MS-N033                         | 1         | 0.46%   |
| MSI Modern 14 B11MOL                | 1         | 0.46%   |
| MSI GV62 8RD                        | 1         | 0.46%   |
| MSI GP63 Leopard 8RD                | 1         | 0.46%   |
| MSI Alpha 15 B5EEK                  | 1         | 0.46%   |
| Medion P6669 MD60147                | 1         | 0.46%   |
| Medion E6234                        | 1         | 0.46%   |
| Medion E14304                       | 1         | 0.46%   |
| Medion Akoya E1318T                 | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 35        | 15.98%  |
| Acer Aspire          | 13        | 5.94%   |
| Dell Latitude        | 10        | 4.57%   |
| Toshiba Satellite    | 7         | 3.2%    |
| HP Pavilion          | 7         | 3.2%    |
| Dell Inspiron        | 7         | 3.2%    |
| HP ProBook           | 6         | 2.74%   |
| Lenovo IdeaPad       | 5         | 2.28%   |
| HP EliteBook         | 5         | 2.28%   |
| Unknown              | 5         | 2.28%   |
| HP Laptop            | 3         | 1.37%   |
| Dell Vostro          | 3         | 1.37%   |
| ASUS TUF             | 3         | 1.37%   |
| Lenovo B590          | 2         | 0.91%   |
| HP ZBook             | 2         | 0.91%   |
| HP Stream            | 2         | 0.91%   |
| HP Compaq            | 2         | 0.91%   |
| Dell Precision       | 2         | 0.91%   |
| ASUS VivoBook        | 2         | 0.91%   |
| ASUS ROG             | 2         | 0.91%   |
| Alienware m15        | 2         | 0.91%   |
| Acer Swift           | 2         | 0.91%   |
| Acer Nitro           | 2         | 0.91%   |
| Acer Extensa         | 2         | 0.91%   |
| UMAX VisionBook-N12R | 1         | 0.46%   |
| TUXEDO N7x0WU        | 1         | 0.46%   |
| Toshiba PORTEGE      | 1         | 0.46%   |
| Sony VPCSB1V9R       | 1         | 0.46%   |
| Sony VPCF23P1E       | 1         | 0.46%   |
| Sony VPCF119FX       | 1         | 0.46%   |
| Sony VPCEH2N1E       | 1         | 0.46%   |
| Sony VPCEC3S1E       | 1         | 0.46%   |
| Sony VGN-NR310FH     | 1         | 0.46%   |
| Sony SVT13115FBS     | 1         | 0.46%   |
| Sony SVE1513Q1ESI    | 1         | 0.46%   |
| Samsung R780         | 1         | 0.46%   |
| Samsung NC210        | 1         | 0.46%   |
| Samsung 350V5C       | 1         | 0.46%   |
| Samsung 340XAA       | 1         | 0.46%   |
| Samsung 305E4A       | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 23        | 10.5%   |
| 2021    | 20        | 9.13%   |
| 2018    | 20        | 9.13%   |
| 2012    | 20        | 9.13%   |
| 2010    | 20        | 9.13%   |
| 2013    | 17        | 7.76%   |
| 2016    | 13        | 5.94%   |
| 2015    | 13        | 5.94%   |
| 2014    | 12        | 5.48%   |
| 2019    | 11        | 5.02%   |
| 2020    | 10        | 4.57%   |
| 2017    | 10        | 4.57%   |
| 2008    | 10        | 4.57%   |
| 2009    | 6         | 2.74%   |
| 2007    | 5         | 2.28%   |
| 2022    | 3         | 1.37%   |
| 2006    | 3         | 1.37%   |
| 2005    | 2         | 0.91%   |
| Unknown | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 219       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 218       | 99.54%  |
| Enabled  | 1         | 0.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 216       | 98.63%  |
| Yes  | 3         | 1.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 62        | 28.18%  |
| 3.01-4.0    | 46        | 20.91%  |
| 8.01-16.0   | 39        | 17.73%  |
| 16.01-24.0  | 31        | 14.09%  |
| 1.01-2.0    | 17        | 7.73%   |
| 32.01-64.0  | 9         | 4.09%   |
| 2.01-3.0    | 8         | 3.64%   |
| 0.51-1.0    | 4         | 1.82%   |
| 24.01-32.0  | 2         | 0.91%   |
| 64.01-256.0 | 2         | 0.91%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 93        | 39.57%  |
| 2.01-3.0  | 54        | 22.98%  |
| 3.01-4.0  | 33        | 14.04%  |
| 0.51-1.0  | 28        | 11.91%  |
| 4.01-8.0  | 19        | 8.09%   |
| 8.01-16.0 | 5         | 2.13%   |
| 0.01-0.5  | 3         | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 161       | 72.52%  |
| 2      | 46        | 20.72%  |
| 3      | 11        | 4.95%   |
| 4      | 2         | 0.9%    |
| 0      | 2         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 63.64%  |
| Yes       | 80        | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 85.39%  |
| No        | 32        | 14.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 96.8%   |
| No        | 7         | 3.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 74.55%  |
| No        | 56        | 25.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 44        | 20%     |
| Germany     | 26        | 11.82%  |
| UK          | 11        | 5%      |
| Italy       | 10        | 4.55%   |
| Canada      | 10        | 4.55%   |
| Russia      | 8         | 3.64%   |
| Brazil      | 8         | 3.64%   |
| Spain       | 7         | 3.18%   |
| Slovakia    | 7         | 3.18%   |
| Netherlands | 7         | 3.18%   |
| France      | 6         | 2.73%   |
| Austria     | 6         | 2.73%   |
| India       | 5         | 2.27%   |
| Ukraine     | 4         | 1.82%   |
| Poland      | 4         | 1.82%   |
| Mexico      | 4         | 1.82%   |
| Thailand    | 3         | 1.36%   |
| Finland     | 3         | 1.36%   |
| Czechia     | 3         | 1.36%   |
| Belgium     | 3         | 1.36%   |
| Australia   | 3         | 1.36%   |
| Turkey      | 2         | 0.91%   |
| Serbia      | 2         | 0.91%   |
| Romania     | 2         | 0.91%   |
| Portugal    | 2         | 0.91%   |
| Norway      | 2         | 0.91%   |
| New Zealand | 2         | 0.91%   |
| Indonesia   | 2         | 0.91%   |
| Colombia    | 2         | 0.91%   |
| China       | 2         | 0.91%   |
| Belarus     | 2         | 0.91%   |
| Vietnam     | 1         | 0.45%   |
| Venezuela   | 1         | 0.45%   |
| Syria       | 1         | 0.45%   |
| Switzerland | 1         | 0.45%   |
| Sweden      | 1         | 0.45%   |
| Philippines | 1         | 0.45%   |
| Peru        | 1         | 0.45%   |
| Nigeria     | 1         | 0.45%   |
| Malaysia    | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Vienna        | 6         | 2.64%   |
| Bratislava    | 6         | 2.64%   |
| Berlin        | 4         | 1.76%   |
| Munich        | 3         | 1.32%   |
| Montreal      | 3         | 1.32%   |
| Los Angeles   | 3         | 1.32%   |
| Warsaw        | 2         | 0.88%   |
| St Petersburg | 2         | 0.88%   |
| Rome          | 2         | 0.88%   |
| Prague        | 2         | 0.88%   |
| Patna         | 2         | 0.88%   |
| Oxford        | 2         | 0.88%   |
| Orange        | 2         | 0.88%   |
| Moscow        | 2         | 0.88%   |
| Minsk         | 2         | 0.88%   |
| Madrid        | 2         | 0.88%   |
| Istanbul      | 2         | 0.88%   |
| Doesburg      | 2         | 0.88%   |
| Dnipro        | 2         | 0.88%   |
| Cambridge     | 2         | 0.88%   |
| Buffalo       | 2         | 0.88%   |
| Bogotá       | 2         | 0.88%   |
| Amsterdam     | 2         | 0.88%   |
| Zurich        | 1         | 0.44%   |
| Xalapa        | 1         | 0.44%   |
| Wentzville    | 1         | 0.44%   |
| Waycross      | 1         | 0.44%   |
| Vasco da Gama | 1         | 0.44%   |
| Vancouver     | 1         | 0.44%   |
| Valencia      | 1         | 0.44%   |
| Uelzen        | 1         | 0.44%   |
| Tver          | 1         | 0.44%   |
| Tucson        | 1         | 0.44%   |
| Trzebinia     | 1         | 0.44%   |
| Trivandrum    | 1         | 0.44%   |
| Tampa         | 1         | 0.44%   |
| Taggia        | 1         | 0.44%   |
| Tacoma        | 1         | 0.44%   |
| Sydney        | 1         | 0.44%   |
| Suzhou        | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 44     | 12.77%  |
| WDC                 | 35        | 36     | 12.41%  |
| Seagate             | 29        | 31     | 10.28%  |
| Kingston            | 20        | 20     | 7.09%   |
| Crucial             | 18        | 28     | 6.38%   |
| Unknown             | 17        | 21     | 6.03%   |
| Toshiba             | 17        | 18     | 6.03%   |
| SanDisk             | 15        | 17     | 5.32%   |
| SK hynix            | 11        | 12     | 3.9%    |
| Intel               | 10        | 13     | 3.55%   |
| Hitachi             | 9         | 9      | 3.19%   |
| HGST                | 8         | 13     | 2.84%   |
| Transcend           | 4         | 4      | 1.42%   |
| PNY                 | 3         | 3      | 1.06%   |
| Micron Technology   | 3         | 7      | 1.06%   |
| LITEON              | 3         | 3      | 1.06%   |
| Dogfish             | 3         | 3      | 1.06%   |
| A-DATA Technology   | 3         | 5      | 1.06%   |
| Team                | 2         | 2      | 0.71%   |
| SPCC                | 2         | 2      | 0.71%   |
| Phison              | 2         | 2      | 0.71%   |
| Netac               | 2         | 2      | 0.71%   |
| KingSpec            | 2         | 2      | 0.71%   |
| KingDian            | 2         | 2      | 0.71%   |
| Indilinx            | 2         | 4      | 0.71%   |
| Fujitsu             | 2         | 2      | 0.71%   |
| Apple               | 2         | 4      | 0.71%   |
| Unknown             | 2         | 2      | 0.71%   |
| ZTC                 | 1         | 1      | 0.35%   |
| Yeyian              | 1         | 1      | 0.35%   |
| Smart               | 1         | 1      | 0.35%   |
| SABRENT             | 1         | 1      | 0.35%   |
| Phison Electronics  | 1         | 2      | 0.35%   |
| Patriot             | 1         | 1      | 0.35%   |
| OCZ                 | 1         | 1      | 0.35%   |
| LITEONIT            | 1         | 1      | 0.35%   |
| Lexar               | 1         | 1      | 0.35%   |
| Lenovo              | 1         | 1      | 0.35%   |
| KIOXIA              | 1         | 1      | 0.35%   |
| KingFast            | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 6         | 2.06%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 2.06%   |
| Samsung SSD 860 EVO 500GB           | 4         | 1.37%   |
| Crucial CT500MX500SSD1 500GB        | 4         | 1.37%   |
| Seagate ST1000LM048-2E7172 1TB      | 3         | 1.03%   |
| Kingston SV300S37A120G 120GB SSD    | 3         | 1.03%   |
| Intel SSDPEKNW512G8 512GB           | 3         | 1.03%   |
| HGST HTS541010A9E680 1TB            | 3         | 1.03%   |
| Crucial CT120BX500SSD1 120GB        | 3         | 1.03%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.69%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 2         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 0.69%   |
| Unknown SD32G  32GB                 | 2         | 0.69%   |
| Unknown BJTD4R  32GB                | 2         | 0.69%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.69%   |
| Toshiba MQ01ABD075 752GB            | 2         | 0.69%   |
| SK hynix HFM512GDJTNI-82A0A 512GB   | 2         | 0.69%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 2         | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.69%   |
| SanDisk SDSSDA120G 120GB            | 2         | 0.69%   |
| Samsung SSD 980 PRO 1TB             | 2         | 0.69%   |
| Samsung SSD 850 EVO 250GB           | 2         | 0.69%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2         | 0.69%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.69%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.69%   |
| Kingston OM8PCP3512F-AI1 512GB      | 2         | 0.69%   |
| Intel SSDSA2BW120G3H 120GB          | 2         | 0.69%   |
| Indilinx IND-S325S120G 120GB SSD    | 2         | 0.69%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 0.69%   |
| HGST HTS721010A9E630 1TB            | 2         | 0.69%   |
| Dogfish SSD 128GB                   | 2         | 0.69%   |
| Crucial CT250MX500SSD1 250GB        | 2         | 0.69%   |
| Crucial CT240BX500SSD1 240GB        | 2         | 0.69%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.69%   |
| A-DATA SP600 32GB SSD               | 2         | 0.69%   |
| Unknown                             | 2         | 0.69%   |
| ZTC SM201-256G                      | 1         | 0.34%   |
| Yeyian VALK 1000 120GB SSD          | 1         | 0.34%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1         | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 31     | 33.72%  |
| WDC                 | 25        | 25     | 29.07%  |
| Toshiba             | 10        | 11     | 11.63%  |
| Hitachi             | 9         | 9      | 10.47%  |
| HGST                | 8         | 13     | 9.3%    |
| Samsung Electronics | 3         | 4      | 3.49%   |
| Fujitsu             | 2         | 2      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 26     | 17.07%  |
| Crucial             | 17        | 26     | 13.82%  |
| Kingston            | 16        | 16     | 13.01%  |
| SanDisk             | 14        | 16     | 11.38%  |
| Transcend           | 4         | 4      | 3.25%   |
| WDC                 | 3         | 3      | 2.44%   |
| SK hynix            | 3         | 3      | 2.44%   |
| PNY                 | 3         | 3      | 2.44%   |
| LITEON              | 3         | 3      | 2.44%   |
| Intel               | 3         | 6      | 2.44%   |
| Dogfish             | 3         | 3      | 2.44%   |
| A-DATA Technology   | 3         | 5      | 2.44%   |
| Toshiba             | 2         | 2      | 1.63%   |
| SPCC                | 2         | 2      | 1.63%   |
| Netac               | 2         | 2      | 1.63%   |
| Micron Technology   | 2         | 6      | 1.63%   |
| KingSpec            | 2         | 2      | 1.63%   |
| KingDian            | 2         | 2      | 1.63%   |
| Indilinx            | 2         | 4      | 1.63%   |
| Apple               | 2         | 4      | 1.63%   |
| ZTC                 | 1         | 1      | 0.81%   |
| Yeyian              | 1         | 1      | 0.81%   |
| Team                | 1         | 1      | 0.81%   |
| Smart               | 1         | 1      | 0.81%   |
| Phison              | 1         | 1      | 0.81%   |
| Patriot             | 1         | 1      | 0.81%   |
| OCZ                 | 1         | 1      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| KingFast            | 1         | 1      | 0.81%   |
| Intenso             | 1         | 1      | 0.81%   |
| GOODRAM             | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |
| GeIL                | 1         | 1      | 0.81%   |
| Corsair             | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 107       | 152    | 41.15%  |
| HDD     | 85        | 95     | 32.69%  |
| NVMe    | 46        | 57     | 17.69%  |
| MMC     | 21        | 25     | 8.08%   |
| Unknown | 1         | 1      | 0.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 167       | 246    | 70.46%  |
| NVMe | 46        | 56     | 19.41%  |
| MMC  | 21        | 25     | 8.86%   |
| SAS  | 3         | 3      | 1.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 139       | 184    | 74.33%  |
| 0.51-1.0   | 44        | 59     | 23.53%  |
| 1.01-2.0   | 3         | 3      | 1.6%    |
| 4.01-10.0  | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 72        | 31.86%  |
| 251-500        | 40        | 17.7%   |
| 501-1000       | 34        | 15.04%  |
| 51-100         | 29        | 12.83%  |
| 21-50          | 20        | 8.85%   |
| 1-20           | 14        | 6.19%   |
| 1001-2000      | 9         | 3.98%   |
| More than 3000 | 3         | 1.33%   |
| 2001-3000      | 3         | 1.33%   |
| Unknown        | 2         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 97        | 41.99%  |
| 21-50          | 37        | 16.02%  |
| 51-100         | 32        | 13.85%  |
| 101-250        | 26        | 11.26%  |
| 251-500        | 22        | 9.52%   |
| 501-1000       | 10        | 4.33%   |
| 1001-2000      | 3         | 1.3%    |
| More than 3000 | 2         | 0.87%   |
| Unknown        | 2         | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 8.33%   |
| Indilinx IND-S325S120G 120GB SSD             | 2         | 4      | 5.56%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.78%   |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 2.78%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 2.78%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 2.78%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 2.78%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 2.78%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 2.78%   |
| Toshiba MK7575GSX 752GB                      | 1         | 2      | 2.78%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 2.78%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 2.78%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.78%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.78%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 2.78%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 2.78%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 2.78%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 2.78%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 2.78%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 2.78%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 2.78%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 2.78%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 2.78%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 2.78%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 2.78%   |
| Hitachi HTS543216L9SA02 160GB                | 1         | 1      | 2.78%   |
| Hitachi HTS542516K9SA00 160GB                | 1         | 1      | 2.78%   |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 2.78%   |
| HGST HTS545032A7E380 320GB                   | 1         | 1      | 2.78%   |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 2.78%   |
| Fujitsu MHZ2160BH G2 160GB                   | 1         | 1      | 2.78%   |
| Crucial CT512M550SSD1 512GB                  | 1         | 1      | 2.78%   |
| A-DATA Technology SU650 240GB SSD            | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 25%     |
| WDC                 | 7         | 7      | 19.44%  |
| Hitachi             | 5         | 5      | 13.89%  |
| Toshiba             | 3         | 4      | 8.33%   |
| HGST                | 3         | 4      | 8.33%   |
| Samsung Electronics | 2         | 3      | 5.56%   |
| Indilinx            | 2         | 4      | 5.56%   |
| SanDisk             | 1         | 1      | 2.78%   |
| Kingston            | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 31.03%  |
| WDC                 | 7         | 7      | 24.14%  |
| Hitachi             | 5         | 5      | 17.24%  |
| Toshiba             | 3         | 4      | 10.34%  |
| HGST                | 3         | 4      | 10.34%  |
| Samsung Electronics | 1         | 2      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 32     | 80.56%  |
| SSD  | 7         | 9      | 19.44%  |

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
| Works    | 176       | 259    | 73.95%  |
| Malfunc  | 35        | 41     | 14.71%  |
| Detected | 27        | 30     | 11.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 165       | 69.04%  |
| AMD                          | 21        | 8.79%   |
| Samsung Electronics          | 15        | 6.28%   |
| SanDisk                      | 8         | 3.35%   |
| SK hynix                     | 7         | 2.93%   |
| Nvidia                       | 5         | 2.09%   |
| Kingston Technology Company  | 4         | 1.67%   |
| Toshiba America Info Systems | 3         | 1.26%   |
| Phison Electronics           | 3         | 1.26%   |
| KIOXIA                       | 3         | 1.26%   |
| Silicon Motion               | 1         | 0.42%   |
| Silicon Image                | 1         | 0.42%   |
| Micron/Crucial Technology    | 1         | 0.42%   |
| Micron Technology            | 1         | 0.42%   |
| Lenovo                       | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 8.95%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 7.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 6.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 6.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 4.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 3.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 2.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.95%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 1.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.56%   |
| Intel SSD 660P Series                                                            | 4         | 1.56%   |
| SK hynix BC511                                                                   | 3         | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.17%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.78%   |
| SK hynix Gold P31 SSD                                                            | 2         | 0.78%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.78%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.78%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.78%   |
| Nvidia MCP67 AHCI Controller                                                     | 2         | 0.78%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 163       | 66.53%  |
| NVMe | 46        | 18.78%  |
| IDE  | 20        | 8.16%   |
| RAID | 16        | 6.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 187       | 85.39%  |
| AMD    | 32        | 14.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 2.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 5         | 2.28%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 5         | 2.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 1.83%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 1.83%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 4         | 1.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.37%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 3         | 1.37%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 1.37%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 1.37%   |
| Intel Core i3-4000M CPU @ 2.40GHz       | 3         | 1.37%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 3         | 1.37%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 3         | 1.37%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 0.91%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.91%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 0.91%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.91%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.91%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 2         | 0.91%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.91%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 0.91%   |
| Intel Core i7 CPU M 620 @ 2.67GHz       | 2         | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 0.91%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 2         | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.91%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.91%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 0.91%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 0.91%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 2         | 0.91%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 2         | 0.91%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 0.91%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 2         | 0.91%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 0.91%   |
| Intel Atom CPU N270 @ 1.60GHz           | 2         | 0.91%   |
| Intel Atom CPU N2600 @ 1.60GHz          | 2         | 0.91%   |
| Intel 12th Gen Core i7-12700H           | 2         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 53        | 24.2%   |
| Intel Core i5           | 53        | 24.2%   |
| Intel Celeron           | 22        | 10.05%  |
| Intel Core i3           | 17        | 7.76%   |
| Intel Atom              | 12        | 5.48%   |
| Other                   | 10        | 4.57%   |
| Intel Core 2 Duo        | 10        | 4.57%   |
| AMD Ryzen 7             | 9         | 4.11%   |
| AMD Ryzen 5             | 4         | 1.83%   |
| Intel Pentium           | 3         | 1.37%   |
| AMD Turion 64 X2 Mobile | 3         | 1.37%   |
| AMD A6                  | 3         | 1.37%   |
| AMD Ryzen 3             | 2         | 0.91%   |
| AMD E1                  | 2         | 0.91%   |
| AMD E                   | 2         | 0.91%   |
| AMD A8                  | 2         | 0.91%   |
| AMD A4                  | 2         | 0.91%   |
| Intel Pentium Silver    | 1         | 0.46%   |
| Intel Pentium M         | 1         | 0.46%   |
| Intel Pentium Dual-Core | 1         | 0.46%   |
| Intel Genuine           | 1         | 0.46%   |
| Intel Core Duo          | 1         | 0.46%   |
| Intel Core 2            | 1         | 0.46%   |
| Intel Celeron M         | 1         | 0.46%   |
| AMD Sempron             | 1         | 0.46%   |
| AMD Ryzen 9             | 1         | 0.46%   |
| AMD Athlon 64 X2        | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 128       | 58.45%  |
| 4      | 61        | 27.85%  |
| 1      | 10        | 4.57%   |
| 8      | 9         | 4.11%   |
| 6      | 9         | 4.11%   |
| 14     | 2         | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 219       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 154       | 70.32%  |
| 1      | 65        | 29.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 210       | 95.45%  |
| 32-bit         | 10        | 4.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 11.21%  |
| 0x206a7    | 20        | 8.97%   |
| 0x306a9    | 17        | 7.62%   |
| 0x406e3    | 10        | 4.48%   |
| 0x20655    | 9         | 4.04%   |
| 0x306c3    | 8         | 3.59%   |
| 0x40651    | 7         | 3.14%   |
| 0x906ea    | 6         | 2.69%   |
| 0x806ea    | 6         | 2.69%   |
| 0x806c1    | 6         | 2.69%   |
| 0x306d4    | 6         | 2.69%   |
| 0x806e9    | 5         | 2.24%   |
| 0x406c4    | 5         | 2.24%   |
| 0x706a1    | 4         | 1.79%   |
| 0x506e3    | 4         | 1.79%   |
| 0x30678    | 4         | 1.79%   |
| 0x20652    | 4         | 1.79%   |
| 0x106c2    | 4         | 1.79%   |
| 0x1067a    | 4         | 1.79%   |
| 0x0a50000c | 4         | 1.79%   |
| 0xa0652    | 3         | 1.35%   |
| 0x806ec    | 3         | 1.35%   |
| 0x706a8    | 3         | 1.35%   |
| 0x106ca    | 3         | 1.35%   |
| 0x10676    | 3         | 1.35%   |
| 0x08608103 | 3         | 1.35%   |
| 0x03000027 | 3         | 1.35%   |
| 0x906e9    | 2         | 0.9%    |
| 0x906a3    | 2         | 0.9%    |
| 0x706e5    | 2         | 0.9%    |
| 0x6fd      | 2         | 0.9%    |
| 0x506c9    | 2         | 0.9%    |
| 0x30661    | 2         | 0.9%    |
| 0x106e5    | 2         | 0.9%    |
| 0x08108102 | 2         | 0.9%    |
| 0x0810100b | 2         | 0.9%    |
| 0x07030105 | 2         | 0.9%    |
| 0x0700010f | 2         | 0.9%    |
| 0x906ed    | 1         | 0.45%   |
| 0x806eb    | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 27        | 12.33%  |
| SandyBridge      | 24        | 10.96%  |
| IvyBridge        | 20        | 9.13%   |
| Haswell          | 16        | 7.31%   |
| Skylake          | 15        | 6.85%   |
| Westmere         | 14        | 6.39%   |
| Silvermont       | 12        | 5.48%   |
| Bonnell          | 9         | 4.11%   |
| Penryn           | 8         | 3.65%   |
| TigerLake        | 7         | 3.2%    |
| Goldmont plus    | 7         | 3.2%    |
| Broadwell        | 6         | 2.74%   |
| Zen 3            | 5         | 2.28%   |
| Core             | 5         | 2.28%   |
| P6               | 4         | 1.83%   |
| K8 Hammer        | 4         | 1.83%   |
| IceLake          | 4         | 1.83%   |
| Unknown          | 4         | 1.83%   |
| Zen+             | 3         | 1.37%   |
| Zen              | 3         | 1.37%   |
| Puma             | 3         | 1.37%   |
| K10 Llano        | 3         | 1.37%   |
| CometLake        | 3         | 1.37%   |
| Zen 2            | 2         | 0.91%   |
| Nehalem          | 2         | 0.91%   |
| Jaguar           | 2         | 0.91%   |
| Goldmont         | 2         | 0.91%   |
| Bobcat           | 2         | 0.91%   |
| K8 & K10 hybrid  | 1         | 0.46%   |
| Excavator        | 1         | 0.46%   |
| Alderlake Hybrid | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 169       | 62.36%  |
| Nvidia | 55        | 20.3%   |
| AMD    | 47        | 17.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 7.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 6.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.82%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.46%   |
| Intel HD Graphics 620                                                                    | 6         | 2.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.76%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.76%   |
| Intel HD Graphics 530                                                                    | 5         | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.41%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.41%   |
| AMD Cezanne                                                                              | 4         | 1.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.06%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.06%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.06%   |
| AMD Lucienne                                                                             | 3         | 1.06%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 3         | 1.06%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.7%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.7%    |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.7%    |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.7%    |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 2         | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 120       | 54.79%  |
| Intel + Nvidia | 38        | 17.35%  |
| 1 x AMD        | 28        | 12.79%  |
| 1 x Nvidia     | 13        | 5.94%   |
| Intel + AMD    | 10        | 4.57%   |
| 2 x AMD        | 5         | 2.28%   |
| AMD + Nvidia   | 4         | 1.83%   |
| 2 x Intel      | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 200       | 90.09%  |
| Proprietary | 15        | 6.76%   |
| Unknown     | 7         | 3.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 167       | 75.91%  |
| 0.01-0.5   | 26        | 11.82%  |
| 1.01-2.0   | 13        | 5.91%   |
| 0.51-1.0   | 12        | 5.45%   |
| 7.01-8.0   | 1         | 0.45%   |
| 3.01-4.0   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 18.64%  |
| LG Display              | 35        | 14.83%  |
| Chimei Innolux          | 32        | 13.56%  |
| Samsung Electronics     | 27        | 11.44%  |
| BOE                     | 24        | 10.17%  |
| Lenovo                  | 12        | 5.08%   |
| Chi Mei Optoelectronics | 10        | 4.24%   |
| PANDA                   | 6         | 2.54%   |
| Hewlett-Packard         | 5         | 2.12%   |
| Sharp                   | 4         | 1.69%   |
| InfoVision              | 4         | 1.69%   |
| HannStar                | 4         | 1.69%   |
| Dell                    | 4         | 1.69%   |
| Apple                   | 4         | 1.69%   |
| LG Philips              | 3         | 1.27%   |
| Ancor Communications    | 3         | 1.27%   |
| Sony                    | 2         | 0.85%   |
| Philips                 | 2         | 0.85%   |
| Goldstar                | 2         | 0.85%   |
| CPT                     | 2         | 0.85%   |
| Vizio                   | 1         | 0.42%   |
| Sunplus                 | 1         | 0.42%   |
| Panasonic               | 1         | 0.42%   |
| LTM                     | 1         | 0.42%   |
| InnoLux Display         | 1         | 0.42%   |
| AOC                     | 1         | 0.42%   |
| Acer                    | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 1.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 1.69%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 3         | 1.27%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 2         | 0.85%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.85%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.85%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.85%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.85%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.85%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.85%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.85%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.85%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch            | 2         | 0.85%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                        | 1         | 0.42%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 0.42%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.42%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 0.42%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.42%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.42%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.42%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch     | 1         | 0.42%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch        | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 87        | 38.33%  |
| 1366x768 (WXGA)    | 81        | 35.68%  |
| 1600x900 (HD+)     | 12        | 5.29%   |
| 1280x800 (WXGA)    | 10        | 4.41%   |
| 1024x600           | 7         | 3.08%   |
| 3840x2160 (4K)     | 6         | 2.64%   |
| 1440x900 (WXGA+)   | 5         | 2.2%    |
| 2560x1440 (QHD)    | 3         | 1.32%   |
| 1680x1050 (WSXGA+) | 3         | 1.32%   |
| 1280x1024 (SXGA)   | 3         | 1.32%   |
| 2560x1080          | 2         | 0.88%   |
| 1920x1200 (WUXGA)  | 2         | 0.88%   |
| 1400x1050          | 2         | 0.88%   |
| 3840x2400          | 1         | 0.44%   |
| 2880x1800          | 1         | 0.44%   |
| 2256x1504          | 1         | 0.44%   |
| 2160x1440          | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 102       | 43.4%   |
| 13     | 31        | 13.19%  |
| 14     | 29        | 12.34%  |
| 17     | 16        | 6.81%   |
| 10     | 8         | 3.4%    |
| 11     | 7         | 2.98%   |
| 24     | 6         | 2.55%   |
| 12     | 6         | 2.55%   |
| 23     | 5         | 2.13%   |
| 19     | 5         | 2.13%   |
| 27     | 4         | 1.7%    |
| 34     | 2         | 0.85%   |
| 20     | 2         | 0.85%   |
| 18     | 2         | 0.85%   |
| 84     | 1         | 0.43%   |
| 46     | 1         | 0.43%   |
| 43     | 1         | 0.43%   |
| 40     | 1         | 0.43%   |
| 37     | 1         | 0.43%   |
| 32     | 1         | 0.43%   |
| 26     | 1         | 0.43%   |
| 25     | 1         | 0.43%   |
| 21     | 1         | 0.43%   |
| 16     | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 143       | 61.11%  |
| 201-300     | 35        | 14.96%  |
| 351-400     | 26        | 11.11%  |
| 501-600     | 16        | 6.84%   |
| 401-500     | 6         | 2.56%   |
| 701-800     | 3         | 1.28%   |
| 801-900     | 2         | 0.85%   |
| 1501-2000   | 1         | 0.43%   |
| 1001-1500   | 1         | 0.43%   |
| 901-1000    | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 182       | 83.87%  |
| 16/10 | 23        | 10.6%   |
| 5/4   | 4         | 1.84%   |
| 3/2   | 4         | 1.84%   |
| 4/3   | 2         | 0.92%   |
| 21/9  | 2         | 0.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 43.4%   |
| 81-90          | 51        | 21.7%   |
| 121-130        | 15        | 6.38%   |
| 71-80          | 9         | 3.83%   |
| 201-250        | 9         | 3.83%   |
| 41-50          | 8         | 3.4%    |
| 151-200        | 8         | 3.4%    |
| 51-60          | 7         | 2.98%   |
| 61-70          | 6         | 2.55%   |
| 301-350        | 4         | 1.7%    |
| 251-300        | 4         | 1.7%    |
| 501-1000       | 4         | 1.7%    |
| 351-500        | 3         | 1.28%   |
| 141-150        | 2         | 0.85%   |
| More than 1000 | 1         | 0.43%   |
| 131-140        | 1         | 0.43%   |
| 111-120        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 86        | 37.55%  |
| 101-120       | 82        | 35.81%  |
| 51-100        | 46        | 20.09%  |
| 161-240       | 10        | 4.37%   |
| More than 240 | 4         | 1.75%   |
| 1-50          | 1         | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 184       | 83.26%  |
| 2     | 29        | 13.12%  |
| 0     | 5         | 2.26%   |
| 3     | 3         | 1.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 117       | 33.24%  |
| Realtek Semiconductor             | 108       | 30.68%  |
| Qualcomm Atheros                  | 61        | 17.33%  |
| Broadcom                          | 22        | 6.25%   |
| Marvell Technology Group          | 6         | 1.7%    |
| Nvidia                            | 5         | 1.42%   |
| MediaTek                          | 4         | 1.14%   |
| TP-Link                           | 3         | 0.85%   |
| Sierra Wireless                   | 3         | 0.85%   |
| Huawei Technologies               | 3         | 0.85%   |
| Broadcom Limited                  | 3         | 0.85%   |
| Ralink Technology                 | 2         | 0.57%   |
| Ralink                            | 2         | 0.57%   |
| Ericsson Business Mobile Networks | 2         | 0.57%   |
| Attansic Technology               | 2         | 0.57%   |
| Samsung Electronics               | 1         | 0.28%   |
| Qualcomm                          | 1         | 0.28%   |
| Lenovo                            | 1         | 0.28%   |
| JMicron Technology                | 1         | 0.28%   |
| Hewlett-Packard                   | 1         | 0.28%   |
| Google                            | 1         | 0.28%   |
| Dell                              | 1         | 0.28%   |
| ASUSTek Computer                  | 1         | 0.28%   |
| ASIX Electronics                  | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 70        | 16.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 20        | 4.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 3.73%   |
| Intel Wireless 7260                                                     | 11        | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.1%    |
| Intel Wireless 8265 / 8275                                              | 8         | 1.86%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.86%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 1.86%   |
| Intel Wireless 8260                                                     | 7         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.63%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.4%    |
| Intel Wireless 3165                                                     | 6         | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.17%   |
| Intel Wireless 7265                                                     | 5         | 1.17%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.17%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.93%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.93%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.7%    |
| Realtek 802.11ac NIC                                                    | 3         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.7%    |
| Intel Ethernet Connection (5) I219-LM                                   | 3         | 0.7%    |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 111       | 49.12%  |
| Qualcomm Atheros      | 48        | 21.24%  |
| Realtek Semiconductor | 35        | 15.49%  |
| Broadcom              | 16        | 7.08%   |
| Sierra Wireless       | 3         | 1.33%   |
| MediaTek              | 3         | 1.33%   |
| TP-Link               | 2         | 0.88%   |
| Ralink Technology     | 2         | 0.88%   |
| Ralink                | 2         | 0.88%   |
| Broadcom Limited      | 2         | 0.88%   |
| Hewlett-Packard       | 1         | 0.44%   |
| ASUSTek Computer      | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 7.05%   |
| Intel Wireless 7260                                                     | 11        | 4.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 3.96%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.52%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 3.52%   |
| Intel Wireless 8260                                                     | 7         | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.08%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.64%   |
| Intel Wireless 3165                                                     | 6         | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 2.2%    |
| Intel Wireless 7265                                                     | 5         | 2.2%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.2%    |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.32%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.32%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.88%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 94        | 48.7%   |
| Intel                    | 49        | 25.39%  |
| Qualcomm Atheros         | 21        | 10.88%  |
| Broadcom                 | 7         | 3.63%   |
| Marvell Technology Group | 6         | 3.11%   |
| Nvidia                   | 5         | 2.59%   |
| Attansic Technology      | 2         | 1.04%   |
| TP-Link                  | 1         | 0.52%   |
| Samsung Electronics      | 1         | 0.52%   |
| Qualcomm                 | 1         | 0.52%   |
| MediaTek                 | 1         | 0.52%   |
| Lenovo                   | 1         | 0.52%   |
| JMicron Technology       | 1         | 0.52%   |
| Huawei Technologies      | 1         | 0.52%   |
| Broadcom Limited         | 1         | 0.52%   |
| ASIX Electronics         | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 70        | 35.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 20        | 10.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 4.08%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 4.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.55%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 2.04%   |
| Intel Ethernet Connection I219-V                                               | 4         | 2.04%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 2.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.53%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 1.53%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.02%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 1.02%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 1.02%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.02%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.02%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 1.02%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 1.02%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.51%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.51%   |
| Qualcomm Mobile Router                                                         | 1         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.51%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.51%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.51%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.51%   |
| MediaTek TECNO POVA 2                                                          | 1         | 0.51%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.51%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 212       | 52.35%  |
| Ethernet | 187       | 46.17%  |
| Modem    | 5         | 1.23%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 75.56%  |
| Ethernet | 54        | 24%     |
| Unknown  | 1         | 0.44%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 176       | 80.37%  |
| 1     | 38        | 17.35%  |
| 0     | 5         | 2.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 188       | 85.07%  |
| Yes  | 33        | 14.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 44.64%  |
| Broadcom                        | 18        | 10.71%  |
| Realtek Semiconductor           | 16        | 9.52%   |
| Qualcomm Atheros Communications | 16        | 9.52%   |
| IMC Networks                    | 8         | 4.76%   |
| Cambridge Silicon Radio         | 7         | 4.17%   |
| Lite-On Technology              | 6         | 3.57%   |
| Hewlett-Packard                 | 5         | 2.98%   |
| Foxconn / Hon Hai               | 4         | 2.38%   |
| Apple                           | 4         | 2.38%   |
| Toshiba                         | 3         | 1.79%   |
| Dell                            | 3         | 1.79%   |
| Ralink                          | 1         | 0.6%    |
| ASUSTek Computer                | 1         | 0.6%    |
| Alps Electric                   | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 37        | 22.02%  |
| Intel AX201 Bluetooth                                                               | 11        | 6.55%   |
| Realtek Bluetooth Radio                                                             | 10        | 5.95%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 4.76%   |
| Intel AX200 Bluetooth                                                               | 8         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 4.17%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.98%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 2.38%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 1.79%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.19%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.19%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.19%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.19%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.19%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.19%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.19%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.19%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.6%    |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.6%    |
| Toshiba BCM43142A0                                                                  | 1         | 0.6%    |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.6%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.6%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.6%    |
| Lite-On Wireless_Device                                                             | 1         | 0.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.6%    |
| Intel Bluetooth Device                                                              | 1         | 0.6%    |
| IMC Networks Bluetooth Device                                                       | 1         | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.6%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.6%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.6%    |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 183       | 68.03%  |
| Nvidia                | 38        | 14.13%  |
| AMD                   | 36        | 13.38%  |
| GN Netcom             | 2         | 0.74%   |
| C-Media Electronics   | 2         | 0.74%   |
| Texas Instruments     | 1         | 0.37%   |
| SteelSeries ApS       | 1         | 0.37%   |
| Realtek Semiconductor | 1         | 0.37%   |
| Plantronics           | 1         | 0.37%   |
| Mark of the Unicorn   | 1         | 0.37%   |
| Logitech              | 1         | 0.37%   |
| Lenovo                | 1         | 0.37%   |
| FIFINE 683 Microphone | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 8.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 7.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 5.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 5.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 5.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.86%   |
| AMD FCH Azalia Controller                                                                         | 9         | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.22%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.9%    |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.27%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.27%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.27%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.95%   |
| Nvidia Audio device                                                                               | 3         | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.95%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia MCP67 High Definition Audio                                                                | 2         | 0.63%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 23.77%  |
| SK hynix            | 56        | 21.13%  |
| Unknown             | 30        | 11.32%  |
| Micron Technology   | 27        | 10.19%  |
| Kingston            | 27        | 10.19%  |
| Crucial             | 14        | 5.28%   |
| Ramaxel Technology  | 7         | 2.64%   |
| Unknown (ABCD)      | 5         | 1.89%   |
| A-DATA Technology   | 5         | 1.89%   |
| Smart               | 4         | 1.51%   |
| Transcend           | 3         | 1.13%   |
| Nanya Technology    | 3         | 1.13%   |
| Elpida              | 3         | 1.13%   |
| Corsair             | 3         | 1.13%   |
| Teikon              | 2         | 0.75%   |
| Team                | 2         | 0.75%   |
| Unknown             | 2         | 0.75%   |
| Unknown (F301)      | 1         | 0.38%   |
| TRS STAR            | 1         | 0.38%   |
| PNY                 | 1         | 0.38%   |
| Patriot             | 1         | 0.38%   |
| Innodisk            | 1         | 0.38%   |
| High Bridge         | 1         | 0.38%   |
| Avant               | 1         | 0.38%   |
| Apacer              | 1         | 0.38%   |
| 48spaces            | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 2.07%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.72%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 1.38%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 4         | 1.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.38%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 1.38%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 1.38%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 1.03%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 3         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.03%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.03%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.03%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.69%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.69%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 2         | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.69%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 2         | 0.69%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.69%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.69%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.69%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.69%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.69%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.69%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.69%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.69%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 2         | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.69%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.69%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.69%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.69%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 111       | 50.45%  |
| DDR4    | 69        | 31.36%  |
| DDR2    | 16        | 7.27%   |
| LPDDR4  | 9         | 4.09%   |
| SDRAM   | 4         | 1.82%   |
| DDR     | 4         | 1.82%   |
| DRAM    | 3         | 1.36%   |
| LPDDR3  | 2         | 0.91%   |
| DDR5    | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 207       | 94.52%  |
| Row Of Chips | 8         | 3.65%   |
| Chip         | 3         | 1.37%   |
| DIMM         | 1         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 98        | 39.68%  |
| 8192  | 72        | 29.15%  |
| 2048  | 45        | 18.22%  |
| 16384 | 17        | 6.88%   |
| 1024  | 13        | 5.26%   |
| 32768 | 2         | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 68        | 28.22%  |
| 2667    | 30        | 12.45%  |
| 1334    | 23        | 9.54%   |
| 3200    | 22        | 9.13%   |
| 2400    | 22        | 9.13%   |
| 1333    | 15        | 6.22%   |
| Unknown | 15        | 6.22%   |
| 667     | 11        | 4.56%   |
| 2133    | 8         | 3.32%   |
| 1067    | 6         | 2.49%   |
| 800     | 4         | 1.66%   |
| 4267    | 3         | 1.24%   |
| 4199    | 3         | 1.24%   |
| 3266    | 3         | 1.24%   |
| 1867    | 2         | 0.83%   |
| 533     | 2         | 0.83%   |
| 8400    | 1         | 0.41%   |
| 4800    | 1         | 0.41%   |
| 1777    | 1         | 0.41%   |
| 166     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 25%     |
| HP LaserJet P2055 series           | 1         | 25%     |
| HP LaserJet 1022                   | 1         | 25%     |
| Brother DCP-L2540DW                | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 50%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 45        | 25.14%  |
| Acer                                   | 19        | 10.61%  |
| Realtek Semiconductor                  | 15        | 8.38%   |
| Sunplus Innovation Technology          | 13        | 7.26%   |
| Microdia                               | 13        | 7.26%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5.59%   |
| IMC Networks                           | 9         | 5.03%   |
| Lite-On Technology                     | 8         | 4.47%   |
| Suyin                                  | 7         | 3.91%   |
| Quanta                                 | 7         | 3.91%   |
| Lenovo                                 | 6         | 3.35%   |
| Z-Star Microelectronics                | 3         | 1.68%   |
| Syntek                                 | 3         | 1.68%   |
| Silicon Motion                         | 3         | 1.68%   |
| Ricoh                                  | 3         | 1.68%   |
| Luxvisions Innotech Limited            | 2         | 1.12%   |
| Alcor Micro                            | 2         | 1.12%   |
| Y Media                                | 1         | 0.56%   |
| Xiongmai                               | 1         | 0.56%   |
| WaveRider Communications               | 1         | 0.56%   |
| Samsung Electronics                    | 1         | 0.56%   |
| Primax Electronics                     | 1         | 0.56%   |
| Logitech                               | 1         | 0.56%   |
| Importek                               | 1         | 0.56%   |
| icSpring                               | 1         | 0.56%   |
| Goodong Industry                       | 1         | 0.56%   |
| Cubeternet                             | 1         | 0.56%   |
| Apple                                  | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 10        | 5.59%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 2.79%   |
| Lite-On Integrated Camera                                   | 5         | 2.79%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.23%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 2.23%   |
| Chicony USB 2.0 Camera                                      | 4         | 2.23%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 2.23%   |
| Chicony HP TrueVision HD Camera                             | 4         | 2.23%   |
| Acer BisonCam, NB Pro                                       | 4         | 2.23%   |
| Syntek EasyCamera                                           | 3         | 1.68%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 1.68%   |
| Microdia Integrated_Webcam_HD                               | 3         | 1.68%   |
| Lenovo Integrated Webcam [R5U877]                           | 3         | 1.68%   |
| Sunplus HD WebCam                                           | 2         | 1.12%   |
| Sunplus ASUS USB2.0 Webcam                                  | 2         | 1.12%   |
| Ricoh USB2.0 Camera                                         | 2         | 1.12%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.12%   |
| Realtek USB Camera                                          | 2         | 1.12%   |
| Quanta VGA WebCam                                           | 2         | 1.12%   |
| Quanta HD User Facing                                       | 2         | 1.12%   |
| Microdia USB 2.0 Camera                                     | 2         | 1.12%   |
| Microdia Integrated Webcam                                  | 2         | 1.12%   |
| Lenovo Integrated Webcam                                    | 2         | 1.12%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.12%   |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 1.12%   |
| Chicony HD WebCam                                           | 2         | 1.12%   |
| Chicony HD User Facing                                      | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 1.12%   |
| Acer SunplusIT INC. Integrated Camera                       | 2         | 1.12%   |
| Acer Lenovo Integrated Webcam                               | 2         | 1.12%   |
| Acer Lenovo EasyCamera                                      | 2         | 1.12%   |
| Acer Integrated Camera                                      | 2         | 1.12%   |
| Acer HD Webcam                                              | 2         | 1.12%   |
| Acer BisonCam,NB Pro                                        | 2         | 1.12%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 0.56%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.56%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.56%   |
| Y Media USB Camera                                          | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 41.67%  |
| Upek                       | 6         | 16.67%  |
| Synaptics                  | 5         | 13.89%  |
| AuthenTec                  | 4         | 11.11%  |
| Shenzhen Goodix Technology | 3         | 8.33%   |
| LighTuning Technology      | 2         | 5.56%   |
| STMicroelectronics         | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 8.33%   |
| Validity Sensors Synaptics WBDI                            | 3         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 5.56%   |
| Upek TCS5B Fingerprint sensor                              | 2         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 5.56%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 5.56%   |
| AuthenTec AES2810                                          | 2         | 5.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.78%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 2.78%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.78%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 2.78%   |
| LighTuning Fingerprint Reader                              | 1         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2.78%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.78%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.78%   |
| Unknown                                                    | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 6         | 37.5%   |
| Broadcom              | 5         | 31.25%  |
| Lenovo                | 3         | 18.75%  |
| O2 Micro              | 1         | 6.25%   |
| Advanced Card Systems | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 37.5%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 18.75%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 12.5%   |
| Broadcom 5880                                                                | 2         | 12.5%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| Advanced Card Systems ACR122U                                                | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 134       | 59.82%  |
| 1     | 69        | 30.8%   |
| 2     | 20        | 8.93%   |
| 3     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 49        | 44.95%  |
| Fingerprint reader       | 36        | 33.03%  |
| Chipcard                 | 14        | 12.84%  |
| Storage                  | 3         | 2.75%   |
| Multimedia controller    | 3         | 2.75%   |
| Net/wireless             | 2         | 1.83%   |
| Communication controller | 1         | 0.92%   |
| Bluetooth                | 1         | 0.92%   |

