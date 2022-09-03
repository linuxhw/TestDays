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

Total: 276

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 19 | 84        | 38.89%  |
| MX 21 | 73        | 33.8%   |
| MX 20 | 43        | 19.91%  |
| MX 18 | 13        | 6.02%   |
| MX 17 | 2         | 0.93%   |
| MX 16 | 1         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MX   | 208       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 32        | 13.91%  |
| 5.10.0-9-amd64             | 14        | 6.09%   |
| 5.10.0-5mx-amd64           | 13        | 5.65%   |
| 5.10.0-13-amd64            | 12        | 5.22%   |
| 5.8.0-3-amd64              | 9         | 3.91%   |
| 5.14.0-4mx-amd64           | 8         | 3.48%   |
| 5.10.0-16-amd64            | 8         | 3.48%   |
| 5.10.0-14-amd64            | 6         | 2.61%   |
| 5.10.0-11-amd64            | 6         | 2.61%   |
| 4.19.0-16-amd64            | 6         | 2.61%   |
| 4.19.0-14-amd64            | 6         | 2.61%   |
| 4.19.0-13-amd64            | 6         | 2.61%   |
| 5.6.0-2-amd64              | 5         | 2.17%   |
| 5.16.0-5mx-amd64           | 4         | 1.74%   |
| 4.19.0-5-amd64             | 4         | 1.74%   |
| 4.19.0-17-amd64            | 4         | 1.74%   |
| 4.19.0-11-amd64            | 4         | 1.74%   |
| 5.10.0-8mx-amd64           | 3         | 1.3%    |
| 4.19.0-9-amd64             | 3         | 1.3%    |
| 4.19.0-12-amd64            | 3         | 1.3%    |
| 4.19.0-1-amd64             | 3         | 1.3%    |
| 5.8.16-antix.1-amd64-smp   | 2         | 0.87%   |
| 5.6.10-antix.1-amd64-smp   | 2         | 0.87%   |
| 5.4.0-3-amd64              | 2         | 0.87%   |
| 5.16.0-6mx-amd64           | 2         | 0.87%   |
| 5.10.0-8-amd64             | 2         | 0.87%   |
| 5.10.0-17-amd64            | 2         | 0.87%   |
| 5.10.0-15-amd64            | 2         | 0.87%   |
| 5.10.0-13-686-pae          | 2         | 0.87%   |
| 5.10.0-11-686-pae          | 2         | 0.87%   |
| 5.10.0-10-amd64            | 2         | 0.87%   |
| 4.19.0-8-amd64             | 2         | 0.87%   |
| 4.19.0-16-686-pae          | 2         | 0.87%   |
| 4.15.0-1-amd64             | 2         | 0.87%   |
| 5.9.1-rt20avl1             | 1         | 0.43%   |
| 5.7.0-19.1-liquorix-amd64  | 1         | 0.43%   |
| 5.6.0-15.2-liquorix-amd64  | 1         | 0.43%   |
| 5.6.0-12.1-liquorix-amd64  | 1         | 0.43%   |
| 5.5.0-9.1-liquorix-amd64   | 1         | 0.43%   |
| 5.4.0-antix.1-amd64-smp    | 1         | 0.43%   |
| 5.4.0-13.3-liquorix-amd64  | 1         | 0.43%   |
| 5.4.0-11.2-liquorix-amd64  | 1         | 0.43%   |
| 5.4.0-10.2-liquorix-amd64  | 1         | 0.43%   |
| 5.3.10-antix.1-amd64-smp   | 1         | 0.43%   |
| 5.3.0-2-amd64              | 1         | 0.43%   |
| 5.3.0-10.1-liquorix-amd64  | 1         | 0.43%   |
| 5.2.8-antix.1-amd64-smp    | 1         | 0.43%   |
| 5.2.21-antix.2-amd64-smp   | 1         | 0.43%   |
| 5.2.21-antix.2-686-smp-pae | 1         | 0.43%   |
| 5.2.0-21.2-liquorix-amd64  | 1         | 0.43%   |
| 5.18.0-3-amd64             | 1         | 0.43%   |
| 5.17.0-5.2-liquorix-amd64  | 1         | 0.43%   |
| 5.17.0-1-amd64             | 1         | 0.43%   |
| 5.16.0-4mx-amd64           | 1         | 0.43%   |
| 5.15.0-3mx-amd64           | 1         | 0.43%   |
| 5.15.0-1mx-amd64           | 1         | 0.43%   |
| 5.13.0-12.3-liquorix-amd64 | 1         | 0.43%   |
| 5.11.0-21.1-liquorix-amd64 | 1         | 0.43%   |
| 5.10.1-gnu                 | 1         | 0.43%   |
| 5.10.0-9mx-amd64           | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.0   | 79        | 35.75%  |
| 5.10.0   | 73        | 33.03%  |
| 5.8.0    | 9         | 4.07%   |
| 5.14.0   | 8         | 3.62%   |
| 5.6.0    | 7         | 3.17%   |
| 5.16.0   | 7         | 3.17%   |
| 5.4.0    | 6         | 2.71%   |
| 5.8.16   | 2         | 0.9%    |
| 5.6.10   | 2         | 0.9%    |
| 5.3.0    | 2         | 0.9%    |
| 5.2.21   | 2         | 0.9%    |
| 5.17.0   | 2         | 0.9%    |
| 5.15.0   | 2         | 0.9%    |
| 4.9.193  | 2         | 0.9%    |
| 4.15.0   | 2         | 0.9%    |
| 5.9.1    | 1         | 0.45%   |
| 5.7.0    | 1         | 0.45%   |
| 5.5.0    | 1         | 0.45%   |
| 5.3.10   | 1         | 0.45%   |
| 5.2.8    | 1         | 0.45%   |
| 5.2.0    | 1         | 0.45%   |
| 5.18.0   | 1         | 0.45%   |
| 5.13.0   | 1         | 0.45%   |
| 5.11.0   | 1         | 0.45%   |
| 5.10.1   | 1         | 0.45%   |
| 5.1.2    | 1         | 0.45%   |
| 5.0.0    | 1         | 0.45%   |
| 4.9.246  | 1         | 0.45%   |
| 4.19.174 | 1         | 0.45%   |
| 4.18.0   | 1         | 0.45%   |
| 3.16.0   | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 80        | 36.2%   |
| 5.10    | 74        | 33.48%  |
| 5.8     | 11        | 4.98%   |
| 5.6     | 9         | 4.07%   |
| 5.14    | 8         | 3.62%   |
| 5.16    | 7         | 3.17%   |
| 5.4     | 6         | 2.71%   |
| 5.2     | 4         | 1.81%   |
| 5.3     | 3         | 1.36%   |
| 4.9     | 3         | 1.36%   |
| 5.17    | 2         | 0.9%    |
| 5.15    | 2         | 0.9%    |
| 4.15    | 2         | 0.9%    |
| 5.9     | 1         | 0.45%   |
| 5.7     | 1         | 0.45%   |
| 5.5     | 1         | 0.45%   |
| 5.18    | 1         | 0.45%   |
| 5.13    | 1         | 0.45%   |
| 5.11    | 1         | 0.45%   |
| 5.1     | 1         | 0.45%   |
| 5.0     | 1         | 0.45%   |
| 4.18    | 1         | 0.45%   |
| 3.16    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 195       | 93.3%   |
| i686   | 14        | 6.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 146       | 69.19%  |
| KDE5            | 34        | 16.11%  |
| Budgie          | 6         | 2.84%   |
| Unknown         | 6         | 2.84%   |
| i3              | 4         | 1.9%    |
| MATE            | 2         | 0.95%   |
| LXQt            | 2         | 0.95%   |
| GNOME           | 2         | 0.95%   |
| Cinnamon        | 2         | 0.95%   |
| X-Cinnamon      | 1         | 0.47%   |
| Trinity         | 1         | 0.47%   |
| spectrwm        | 1         | 0.47%   |
| LXDE            | 1         | 0.47%   |
| GNOME Flashback | 1         | 0.47%   |
| GNOME Classic   | 1         | 0.47%   |
| fluxbox         | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 205       | 98.56%  |
| Tty  | 3         | 1.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 166       | 79.05%  |
| SDDM    | 29        | 13.81%  |
| TDM     | 9         | 4.29%   |
| SLiM    | 5         | 2.38%   |
| Unknown | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 77        | 35.81%  |
| Unknown | 56        | 26.05%  |
| de_DE   | 19        | 8.84%   |
| en_GB   | 10        | 4.65%   |
| ru_RU   | 8         | 3.72%   |
| sk_SK   | 6         | 2.79%   |
| pt_BR   | 5         | 2.33%   |
| it_IT   | 5         | 2.33%   |
| fr_FR   | 4         | 1.86%   |
| es_ES   | 4         | 1.86%   |
| tr_TR   | 2         | 0.93%   |
| pl_PL   | 2         | 0.93%   |
| en_IE   | 2         | 0.93%   |
| en_AU   | 2         | 0.93%   |
| zh_CN   | 1         | 0.47%   |
| uk_UA   | 1         | 0.47%   |
| nl_NL   | 1         | 0.47%   |
| nb_NO   | 1         | 0.47%   |
| id_ID   | 1         | 0.47%   |
| fr_BE   | 1         | 0.47%   |
| fi_FI   | 1         | 0.47%   |
| es_VE   | 1         | 0.47%   |
| es_PE   | 1         | 0.47%   |
| es_MX   | 1         | 0.47%   |
| es_CO   | 1         | 0.47%   |
| de_CH   | 1         | 0.47%   |
| cs_CZ   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 110       | 52.88%  |
| BIOS | 98        | 47.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 180       | 86.54%  |
| Overlay | 21        | 10.1%   |
| Btrfs   | 4         | 1.92%   |
| Xfs     | 1         | 0.48%   |
| F2fs    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 128       | 61.24%  |
| MBR     | 77        | 36.84%  |
| Unknown | 4         | 1.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 80%     |
| Yes       | 42        | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 57.42%  |
| Yes       | 89        | 42.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 48        | 23.08%  |
| Hewlett-Packard     | 33        | 15.87%  |
| Dell                | 24        | 11.54%  |
| ASUSTek Computer    | 22        | 10.58%  |
| Acer                | 21        | 10.1%   |
| Toshiba             | 8         | 3.85%   |
| Sony                | 8         | 3.85%   |
| Samsung Electronics | 5         | 2.4%    |
| MSI                 | 4         | 1.92%   |
| Medion              | 4         | 1.92%   |
| Apple               | 4         | 1.92%   |
| Fujitsu Siemens     | 3         | 1.44%   |
| Alienware           | 3         | 1.44%   |
| Unknown             | 3         | 1.44%   |
| Google              | 2         | 0.96%   |
| Gigabyte Technology | 2         | 0.96%   |
| Clevo               | 2         | 0.96%   |
| UMAX                | 1         | 0.48%   |
| TUXEDO              | 1         | 0.48%   |
| Pixus               | 1         | 0.48%   |
| Panasonic           | 1         | 0.48%   |
| Packard Bell        | 1         | 0.48%   |
| Notebook            | 1         | 0.48%   |
| Irbis               | 1         | 0.48%   |
| Intel               | 1         | 0.48%   |
| Framework           | 1         | 0.48%   |
| eMachines           | 1         | 0.48%   |
| efirstview          | 1         | 0.48%   |
| Chuwi               | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 2.4%    |
| HP Stream Laptop 14-cb0XX                | 2         | 0.96%   |
| HP ProBook 650 G1                        | 2         | 0.96%   |
| UMAX VisionBook-N12R                     | 1         | 0.48%   |
| TUXEDO N7x0WU                            | 1         | 0.48%   |
| Toshiba Satellite P875                   | 1         | 0.48%   |
| Toshiba Satellite L850-CJK               | 1         | 0.48%   |
| Toshiba Satellite C845                   | 1         | 0.48%   |
| Toshiba Satellite C70-B                  | 1         | 0.48%   |
| Toshiba Satellite C660                   | 1         | 0.48%   |
| Toshiba Satellite C50-A-12K              | 1         | 0.48%   |
| Toshiba Satellite A300                   | 1         | 0.48%   |
| Toshiba PORTEGE R705                     | 1         | 0.48%   |
| Sony VPCSB1V9R                           | 1         | 0.48%   |
| Sony VPCF23P1E                           | 1         | 0.48%   |
| Sony VPCF119FX                           | 1         | 0.48%   |
| Sony VPCEH2N1E                           | 1         | 0.48%   |
| Sony VPCEC3S1E                           | 1         | 0.48%   |
| Sony VGN-NR310FH                         | 1         | 0.48%   |
| Sony SVT13115FBS                         | 1         | 0.48%   |
| Sony SVE1513Q1ESI                        | 1         | 0.48%   |
| Samsung R780/R778                        | 1         | 0.48%   |
| Samsung NC210/NC110                      | 1         | 0.48%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 0.48%   |
| Samsung 340XAA/350XAA/550XAA             | 1         | 0.48%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 0.48%   |
| Pixus Rise                               | 1         | 0.48%   |
| Panasonic CF-C1BT02EGE                   | 1         | 0.48%   |
| Packard Bell EasyNote TE11HC             | 1         | 0.48%   |
| Notebook W65_W67RZ1                      | 1         | 0.48%   |
| MSI MS-N033                              | 1         | 0.48%   |
| MSI GV62 8RD                             | 1         | 0.48%   |
| MSI GP63 Leopard 8RD                     | 1         | 0.48%   |
| MSI Alpha 15 B5EEK                       | 1         | 0.48%   |
| Medion P6669 MD60147                     | 1         | 0.48%   |
| Medion E6234                             | 1         | 0.48%   |
| Medion E14304                            | 1         | 0.48%   |
| Medion Akoya E1318T                      | 1         | 0.48%   |
| Lenovo V145-15AST 81MT                   | 1         | 0.48%   |
| Lenovo ThinkPad X301 2776LBU             | 1         | 0.48%   |
| Lenovo ThinkPad X270 W10DG 20K5S0YT00    | 1         | 0.48%   |
| Lenovo ThinkPad X250 20CLS4YA00          | 1         | 0.48%   |
| Lenovo ThinkPad X220 4291WMQ             | 1         | 0.48%   |
| Lenovo ThinkPad X220 4291F52             | 1         | 0.48%   |
| Lenovo ThinkPad X201s 5413A19            | 1         | 0.48%   |
| Lenovo ThinkPad X201 3680MY9             | 1         | 0.48%   |
| Lenovo ThinkPad X1C 5th W10DG 20K4S0EC00 | 1         | 0.48%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0013AU | 1         | 0.48%   |
| Lenovo ThinkPad W541 20EG0005MS          | 1         | 0.48%   |
| Lenovo ThinkPad W510 4875W17             | 1         | 0.48%   |
| Lenovo ThinkPad T60 20085TG              | 1         | 0.48%   |
| Lenovo ThinkPad T560 20FJS0EP00          | 1         | 0.48%   |
| Lenovo ThinkPad T530 2394CJ9             | 1         | 0.48%   |
| Lenovo ThinkPad T500 2241VL9             | 1         | 0.48%   |
| Lenovo ThinkPad T440s 20AQ007SGE         | 1         | 0.48%   |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 0.48%   |
| Lenovo ThinkPad T440p 20AWS2T11D         | 1         | 0.48%   |
| Lenovo ThinkPad T440p 20AWA1NAUK         | 1         | 0.48%   |
| Lenovo ThinkPad T440p 20AW002VBR         | 1         | 0.48%   |
| Lenovo ThinkPad T430 23427YU             | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 33        | 15.87%  |
| Acer Aspire            | 13        | 6.25%   |
| Dell Latitude          | 10        | 4.81%   |
| Toshiba Satellite      | 7         | 3.37%   |
| HP ProBook             | 6         | 2.88%   |
| HP Pavilion            | 6         | 2.88%   |
| Dell Inspiron          | 6         | 2.88%   |
| Lenovo IdeaPad         | 5         | 2.4%    |
| HP EliteBook           | 5         | 2.4%    |
| Unknown                | 5         | 2.4%    |
| HP Laptop              | 3         | 1.44%   |
| Dell Vostro            | 3         | 1.44%   |
| ASUS TUF               | 3         | 1.44%   |
| Lenovo B590            | 2         | 0.96%   |
| HP ZBook               | 2         | 0.96%   |
| HP Stream              | 2         | 0.96%   |
| HP Compaq              | 2         | 0.96%   |
| ASUS VivoBook          | 2         | 0.96%   |
| ASUS ROG               | 2         | 0.96%   |
| Alienware m15          | 2         | 0.96%   |
| Acer Swift             | 2         | 0.96%   |
| Acer Extensa           | 2         | 0.96%   |
| UMAX VisionBook-N12R   | 1         | 0.48%   |
| TUXEDO N7x0WU          | 1         | 0.48%   |
| Toshiba PORTEGE        | 1         | 0.48%   |
| Sony VPCSB1V9R         | 1         | 0.48%   |
| Sony VPCF23P1E         | 1         | 0.48%   |
| Sony VPCF119FX         | 1         | 0.48%   |
| Sony VPCEH2N1E         | 1         | 0.48%   |
| Sony VPCEC3S1E         | 1         | 0.48%   |
| Sony VGN-NR310FH       | 1         | 0.48%   |
| Sony SVT13115FBS       | 1         | 0.48%   |
| Sony SVE1513Q1ESI      | 1         | 0.48%   |
| Samsung R780           | 1         | 0.48%   |
| Samsung NC210          | 1         | 0.48%   |
| Samsung 350V5C         | 1         | 0.48%   |
| Samsung 340XAA         | 1         | 0.48%   |
| Samsung 305E4A         | 1         | 0.48%   |
| Pixus Rise             | 1         | 0.48%   |
| Panasonic CF-C1BT02EGE | 1         | 0.48%   |
| Packard Bell EasyNote  | 1         | 0.48%   |
| Notebook W65           | 1         | 0.48%   |
| MSI MS-N033            | 1         | 0.48%   |
| MSI GV62               | 1         | 0.48%   |
| MSI GP63               | 1         | 0.48%   |
| MSI Alpha              | 1         | 0.48%   |
| Medion P6669           | 1         | 0.48%   |
| Medion E6234           | 1         | 0.48%   |
| Medion E14304          | 1         | 0.48%   |
| Medion Akoya           | 1         | 0.48%   |
| Lenovo V145-15AST      | 1         | 0.48%   |
| Lenovo ThinkBook       | 1         | 0.48%   |
| Lenovo S130-11IGM      | 1         | 0.48%   |
| Lenovo Legion          | 1         | 0.48%   |
| Lenovo G400s           | 1         | 0.48%   |
| Lenovo B40-45          | 1         | 0.48%   |
| Irbis TW94             | 1         | 0.48%   |
| Intel ChiefRiver       | 1         | 0.48%   |
| HP Presario            | 1         | 0.48%   |
| HP Notebook            | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 22        | 10.58%  |
| 2010    | 20        | 9.62%   |
| 2018    | 19        | 9.13%   |
| 2012    | 19        | 9.13%   |
| 2021    | 17        | 8.17%   |
| 2013    | 17        | 8.17%   |
| 2016    | 13        | 6.25%   |
| 2015    | 13        | 6.25%   |
| 2014    | 12        | 5.77%   |
| 2019    | 10        | 4.81%   |
| 2008    | 10        | 4.81%   |
| 2020    | 9         | 4.33%   |
| 2017    | 8         | 3.85%   |
| 2009    | 6         | 2.88%   |
| 2007    | 5         | 2.4%    |
| 2006    | 3         | 1.44%   |
| 2022    | 2         | 0.96%   |
| 2005    | 2         | 0.96%   |
| Unknown | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 208       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 208       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 205       | 98.56%  |
| Yes  | 3         | 1.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 59        | 28.23%  |
| 3.01-4.0    | 45        | 21.53%  |
| 8.01-16.0   | 39        | 18.66%  |
| 16.01-24.0  | 27        | 12.92%  |
| 1.01-2.0    | 17        | 8.13%   |
| 2.01-3.0    | 8         | 3.83%   |
| 32.01-64.0  | 7         | 3.35%   |
| 0.51-1.0    | 4         | 1.91%   |
| 24.01-32.0  | 2         | 0.96%   |
| 64.01-256.0 | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 89        | 39.91%  |
| 2.01-3.0  | 52        | 23.32%  |
| 3.01-4.0  | 31        | 13.9%   |
| 0.51-1.0  | 28        | 12.56%  |
| 4.01-8.0  | 15        | 6.73%   |
| 8.01-16.0 | 5         | 2.24%   |
| 0.01-0.5  | 3         | 1.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 153       | 72.51%  |
| 2      | 44        | 20.85%  |
| 3      | 10        | 4.74%   |
| 4      | 2         | 0.95%   |
| 0      | 2         | 0.95%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 132       | 63.16%  |
| Yes       | 77        | 36.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 178       | 85.58%  |
| No        | 30        | 14.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 201       | 96.63%  |
| No        | 7         | 3.37%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 73.21%  |
| No        | 56        | 26.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 42        | 20.1%   |
| Germany     | 23        | 11%     |
| UK          | 11        | 5.26%   |
| Canada      | 10        | 4.78%   |
| Russia      | 8         | 3.83%   |
| Brazil      | 8         | 3.83%   |
| Spain       | 7         | 3.35%   |
| Slovakia    | 7         | 3.35%   |
| Netherlands | 7         | 3.35%   |
| Italy       | 7         | 3.35%   |
| France      | 6         | 2.87%   |
| Austria     | 6         | 2.87%   |
| India       | 5         | 2.39%   |
| Ukraine     | 4         | 1.91%   |
| Poland      | 4         | 1.91%   |
| Mexico      | 4         | 1.91%   |
| Thailand    | 3         | 1.44%   |
| Finland     | 3         | 1.44%   |
| Czechia     | 3         | 1.44%   |
| Belgium     | 3         | 1.44%   |
| Australia   | 3         | 1.44%   |
| Turkey      | 2         | 0.96%   |
| Serbia      | 2         | 0.96%   |
| Romania     | 2         | 0.96%   |
| Portugal    | 2         | 0.96%   |
| Norway      | 2         | 0.96%   |
| Indonesia   | 2         | 0.96%   |
| Colombia    | 2         | 0.96%   |
| China       | 2         | 0.96%   |
| Belarus     | 2         | 0.96%   |
| Vietnam     | 1         | 0.48%   |
| Venezuela   | 1         | 0.48%   |
| Syria       | 1         | 0.48%   |
| Switzerland | 1         | 0.48%   |
| Sweden      | 1         | 0.48%   |
| Philippines | 1         | 0.48%   |
| Peru        | 1         | 0.48%   |
| Nigeria     | 1         | 0.48%   |
| Malaysia    | 1         | 0.48%   |
| Latvia      | 1         | 0.48%   |
| Hungary     | 1         | 0.48%   |
| Greece      | 1         | 0.48%   |
| Ghana       | 1         | 0.48%   |
| Chile       | 1         | 0.48%   |
| Azerbaijan  | 1         | 0.48%   |
| Angola      | 1         | 0.48%   |
| Algeria     | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 6         | 2.79%   |
| Bratislava                | 6         | 2.79%   |
| Berlin                    | 4         | 1.86%   |
| Munich                    | 3         | 1.4%    |
| Montreal                  | 3         | 1.4%    |
| Los Angeles               | 3         | 1.4%    |
| Warsaw                    | 2         | 0.93%   |
| St Petersburg             | 2         | 0.93%   |
| Prague                    | 2         | 0.93%   |
| Patna                     | 2         | 0.93%   |
| Oxford                    | 2         | 0.93%   |
| Orange                    | 2         | 0.93%   |
| Moscow                    | 2         | 0.93%   |
| Minsk                     | 2         | 0.93%   |
| Madrid                    | 2         | 0.93%   |
| Istanbul                  | 2         | 0.93%   |
| Doesburg                  | 2         | 0.93%   |
| Dnipro                    | 2         | 0.93%   |
| Buffalo                   | 2         | 0.93%   |
| Bogotá                   | 2         | 0.93%   |
| Amsterdam                 | 2         | 0.93%   |
| Zurich                    | 1         | 0.47%   |
| Xalapa                    | 1         | 0.47%   |
| Wentzville                | 1         | 0.47%   |
| Waycross                  | 1         | 0.47%   |
| Vasco da Gama             | 1         | 0.47%   |
| Vancouver                 | 1         | 0.47%   |
| Valencia                  | 1         | 0.47%   |
| Uelzen                    | 1         | 0.47%   |
| Tver                      | 1         | 0.47%   |
| Tucson                    | 1         | 0.47%   |
| Trzebinia                 | 1         | 0.47%   |
| Trivandrum                | 1         | 0.47%   |
| Tampa                     | 1         | 0.47%   |
| Taggia                    | 1         | 0.47%   |
| Tacoma                    | 1         | 0.47%   |
| Sydney                    | 1         | 0.47%   |
| Suzhou                    | 1         | 0.47%   |
| Surprise                  | 1         | 0.47%   |
| Stadtilm                  | 1         | 0.47%   |
| Spijkenisse               | 1         | 0.47%   |
| Siegen                    | 1         | 0.47%   |
| Shenzhen                  | 1         | 0.47%   |
| Schiedam                  | 1         | 0.47%   |
| Schaarbeek                | 1         | 0.47%   |
| Saskatoon                 | 1         | 0.47%   |
| Santa Pola                | 1         | 0.47%   |
| San Giovanni in Persiceto | 1         | 0.47%   |
| Saarlouis                 | 1         | 0.47%   |
| Rüsselsheim am Main      | 1         | 0.47%   |
| Rusko                     | 1         | 0.47%   |
| Roseville                 | 1         | 0.47%   |
| Romulus                   | 1         | 0.47%   |
| Rochester                 | 1         | 0.47%   |
| Rivne                     | 1         | 0.47%   |
| Riga                      | 1         | 0.47%   |
| Rensselaer                | 1         | 0.47%   |
| Relizane                  | 1         | 0.47%   |
| Reinbek                   | 1         | 0.47%   |
| Puerto Vallarta           | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 36     | 13.11%  |
| Samsung Electronics | 32        | 40     | 11.99%  |
| Seagate             | 25        | 27     | 9.36%   |
| Kingston            | 18        | 18     | 6.74%   |
| Crucial             | 18        | 27     | 6.74%   |
| Unknown             | 16        | 20     | 5.99%   |
| Toshiba             | 16        | 17     | 5.99%   |
| SanDisk             | 15        | 17     | 5.62%   |
| SK hynix            | 11        | 12     | 4.12%   |
| Hitachi             | 9         | 9      | 3.37%   |
| HGST                | 8         | 13     | 3%      |
| Intel               | 7         | 10     | 2.62%   |
| Transcend           | 4         | 4      | 1.5%    |
| PNY                 | 3         | 3      | 1.12%   |
| Micron Technology   | 3         | 7      | 1.12%   |
| LITEON              | 3         | 3      | 1.12%   |
| Dogfish             | 3         | 3      | 1.12%   |
| A-DATA Technology   | 3         | 5      | 1.12%   |
| Team                | 2         | 2      | 0.75%   |
| SPCC                | 2         | 2      | 0.75%   |
| Phison              | 2         | 2      | 0.75%   |
| Netac               | 2         | 2      | 0.75%   |
| KingSpec            | 2         | 2      | 0.75%   |
| KingDian            | 2         | 2      | 0.75%   |
| Indilinx            | 2         | 4      | 0.75%   |
| Fujitsu             | 2         | 2      | 0.75%   |
| Apple               | 2         | 3      | 0.75%   |
| Unknown             | 2         | 2      | 0.75%   |
| ZTC                 | 1         | 1      | 0.37%   |
| Yeyian              | 1         | 1      | 0.37%   |
| Smart               | 1         | 1      | 0.37%   |
| SABRENT             | 1         | 1      | 0.37%   |
| Phison Electronics  | 1         | 2      | 0.37%   |
| Patriot             | 1         | 1      | 0.37%   |
| OCZ                 | 1         | 1      | 0.37%   |
| LITEONIT            | 1         | 1      | 0.37%   |
| Lexar               | 1         | 1      | 0.37%   |
| Lenovo              | 1         | 1      | 0.37%   |
| KIOXIA              | 1         | 1      | 0.37%   |
| KingFast            | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| HUAWEI              | 1         | 1      | 0.37%   |
| GOODRAM             | 1         | 1      | 0.37%   |
| Gigabyte Technology | 1         | 1      | 0.37%   |
| GeIL                | 1         | 1      | 0.37%   |
| Corsair             | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 6         | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.81%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.45%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 1.45%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 1.09%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 1.09%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.09%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 1.09%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.72%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.72%   |
| Unknown SD32G  32GB                  | 2         | 0.72%   |
| Unknown BJTD4R  32GB                 | 2         | 0.72%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.72%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.72%   |
| SK hynix HFM512GDJTNI-82A0A 512GB    | 2         | 0.72%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.72%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.72%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.72%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.72%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.72%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.72%   |
| Intel SSDSA2BW120G3H 120GB           | 2         | 0.72%   |
| Intel SSDPEKNW512G8 512GB            | 2         | 0.72%   |
| Indilinx IND-S325S120G 120GB SSD     | 2         | 0.72%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.72%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.72%   |
| Dogfish SSD 128GB                    | 2         | 0.72%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.72%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.72%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.72%   |
| A-DATA SP600 32GB SSD                | 2         | 0.72%   |
| Unknown                              | 2         | 0.72%   |
| ZTC SM201-256G                       | 1         | 0.36%   |
| Yeyian VALK 1000 120GB SSD           | 1         | 0.36%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.36%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.36%   |
| WDC WD7500BPVX-00JC3T0 752GB         | 1         | 0.36%   |
| WDC WD5000LPVX-08V0TT5 500GB         | 1         | 0.36%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.36%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.36%   |
| WDC WD5000BPVT-60HXZT3 500GB         | 1         | 0.36%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 0.36%   |
| WDC WD3200LPVT-08G33T1 320GB         | 1         | 0.36%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.36%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.36%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.36%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 0.36%   |
| WDC WD2500BEVE-00WZT0 250GB          | 1         | 0.36%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.36%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.36%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.36%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 0.36%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 0.36%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.36%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.36%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 25     | 30.12%  |
| Seagate             | 25        | 27     | 30.12%  |
| Toshiba             | 10        | 11     | 12.05%  |
| Hitachi             | 9         | 9      | 10.84%  |
| HGST                | 8         | 13     | 9.64%   |
| Samsung Electronics | 3         | 4      | 3.61%   |
| Fujitsu             | 2         | 2      | 2.41%   |
| SABRENT             | 1         | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 25     | 16.39%  |
| Crucial             | 17        | 25     | 13.93%  |
| Kingston            | 16        | 16     | 13.11%  |
| SanDisk             | 14        | 16     | 11.48%  |
| Transcend           | 4         | 4      | 3.28%   |
| WDC                 | 3         | 3      | 2.46%   |
| SK hynix            | 3         | 3      | 2.46%   |
| PNY                 | 3         | 3      | 2.46%   |
| LITEON              | 3         | 3      | 2.46%   |
| Intel               | 3         | 6      | 2.46%   |
| Dogfish             | 3         | 3      | 2.46%   |
| A-DATA Technology   | 3         | 5      | 2.46%   |
| Toshiba             | 2         | 2      | 1.64%   |
| SPCC                | 2         | 2      | 1.64%   |
| Netac               | 2         | 2      | 1.64%   |
| Micron Technology   | 2         | 6      | 1.64%   |
| KingSpec            | 2         | 2      | 1.64%   |
| KingDian            | 2         | 2      | 1.64%   |
| Indilinx            | 2         | 4      | 1.64%   |
| Apple               | 2         | 3      | 1.64%   |
| ZTC                 | 1         | 1      | 0.82%   |
| Yeyian              | 1         | 1      | 0.82%   |
| Team                | 1         | 1      | 0.82%   |
| Smart               | 1         | 1      | 0.82%   |
| Phison              | 1         | 1      | 0.82%   |
| Patriot             | 1         | 1      | 0.82%   |
| OCZ                 | 1         | 1      | 0.82%   |
| LITEONIT            | 1         | 1      | 0.82%   |
| KingFast            | 1         | 1      | 0.82%   |
| Intenso             | 1         | 1      | 0.82%   |
| GOODRAM             | 1         | 1      | 0.82%   |
| Gigabyte Technology | 1         | 1      | 0.82%   |
| GeIL                | 1         | 1      | 0.82%   |
| Corsair             | 1         | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 106       | 149    | 42.91%  |
| HDD     | 82        | 92     | 33.2%   |
| NVMe    | 38        | 47     | 15.38%  |
| MMC     | 20        | 24     | 8.1%    |
| Unknown | 1         | 1      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 162       | 239    | 72.65%  |
| NVMe | 38        | 47     | 17.04%  |
| MMC  | 20        | 24     | 8.97%   |
| SAS  | 3         | 3      | 1.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 138       | 182    | 75.41%  |
| 0.51-1.0   | 41        | 55     | 22.4%   |
| 1.01-2.0   | 3         | 3      | 1.64%   |
| 4.01-10.0  | 1         | 1      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 70        | 32.71%  |
| 251-500        | 36        | 16.82%  |
| 501-1000       | 32        | 14.95%  |
| 51-100         | 28        | 13.08%  |
| 21-50          | 19        | 8.88%   |
| 1-20           | 13        | 6.07%   |
| 1001-2000      | 8         | 3.74%   |
| More than 3000 | 3         | 1.4%    |
| 2001-3000      | 3         | 1.4%    |
| Unknown        | 2         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 93        | 42.47%  |
| 21-50          | 37        | 16.89%  |
| 51-100         | 30        | 13.7%   |
| 101-250        | 24        | 10.96%  |
| 251-500        | 18        | 8.22%   |
| 501-1000       | 10        | 4.57%   |
| 1001-2000      | 3         | 1.37%   |
| More than 3000 | 2         | 0.91%   |
| Unknown        | 2         | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 8.57%   |
| Indilinx IND-S325S120G 120GB SSD             | 2         | 4      | 5.71%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.86%   |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 2.86%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 2.86%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 2.86%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 2.86%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 2.86%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 2.86%   |
| Toshiba MK7575GSX 752GB                      | 1         | 2      | 2.86%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 2.86%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 2.86%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.86%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.86%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 2.86%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 2.86%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 2.86%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 2.86%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 2.86%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 2.86%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 2.86%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 2.86%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 2.86%   |
| Hitachi HTS543216L9SA02 160GB                | 1         | 1      | 2.86%   |
| Hitachi HTS542516K9SA00 160GB                | 1         | 1      | 2.86%   |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 2.86%   |
| HGST HTS545032A7E380 320GB                   | 1         | 1      | 2.86%   |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 2.86%   |
| Fujitsu MHZ2160BH G2 160GB                   | 1         | 1      | 2.86%   |
| Crucial CT512M550SSD1 512GB                  | 1         | 1      | 2.86%   |
| A-DATA Technology SU650 240GB SSD            | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 22.86%  |
| WDC                 | 7         | 7      | 20%     |
| Hitachi             | 5         | 5      | 14.29%  |
| Toshiba             | 3         | 4      | 8.57%   |
| HGST                | 3         | 4      | 8.57%   |
| Samsung Electronics | 2         | 3      | 5.71%   |
| Indilinx            | 2         | 4      | 5.71%   |
| SanDisk             | 1         | 1      | 2.86%   |
| Kingston            | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |
| Crucial             | 1         | 1      | 2.86%   |
| A-DATA Technology   | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 28.57%  |
| WDC                 | 7         | 7      | 25%     |
| Hitachi             | 5         | 5      | 17.86%  |
| Toshiba             | 3         | 4      | 10.71%  |
| HGST                | 3         | 4      | 10.71%  |
| Samsung Electronics | 1         | 2      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 31     | 80%     |
| SSD  | 7         | 9      | 20%     |

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
| Works    | 166       | 244    | 73.45%  |
| Malfunc  | 34        | 40     | 15.04%  |
| Detected | 26        | 29     | 11.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 157       | 69.78%  |
| AMD                          | 21        | 9.33%   |
| Samsung Electronics          | 12        | 5.33%   |
| SanDisk                      | 8         | 3.56%   |
| SK hynix                     | 7         | 3.11%   |
| Nvidia                       | 5         | 2.22%   |
| Phison Electronics           | 3         | 1.33%   |
| KIOXIA                       | 3         | 1.33%   |
| Toshiba America Info Systems | 2         | 0.89%   |
| Kingston Technology Company  | 2         | 0.89%   |
| Silicon Motion               | 1         | 0.44%   |
| Silicon Image                | 1         | 0.44%   |
| Micron/Crucial Technology    | 1         | 0.44%   |
| Micron Technology            | 1         | 0.44%   |
| Lenovo                       | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 8.71%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 7.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 6.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 6.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 4.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 3.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 3.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 2.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 2.07%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 2.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 2.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.66%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.66%   |
| SK hynix BC511                                                                   | 3         | 1.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.24%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.24%   |
| Intel SSD 660P Series                                                            | 3         | 1.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.24%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 1.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.24%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.83%   |
| SK hynix Gold P31 SSD                                                            | 2         | 0.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.83%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.83%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.83%   |
| Nvidia MCP67 AHCI Controller                                                     | 2         | 0.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.83%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.41%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.41%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.41%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.41%   |
| Samsung Electronics SATA controller                                              | 1         | 0.41%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.41%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.41%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.41%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.41%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.41%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.41%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.41%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.41%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.41%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.41%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.41%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.41%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.41%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 156       | 67.53%  |
| NVMe | 38        | 16.45%  |
| IDE  | 20        | 8.66%   |
| RAID | 17        | 7.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 176       | 84.62%  |
| AMD    | 32        | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 2.88%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 2.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.92%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 1.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.44%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 3         | 1.44%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.44%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 1.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.96%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.96%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.96%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.96%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.96%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.96%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.96%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.96%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.96%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.96%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.96%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 0.96%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 2         | 0.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.96%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.96%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 0.96%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.48%   |
| Intel Pentium M processor 1.80GHz             | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.48%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.48%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.48%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.48%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 0.48%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.48%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.48%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.48%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.48%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.48%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 0.48%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.48%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 0.48%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.48%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.48%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.48%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 50        | 24.04%  |
| Intel Core i5           | 50        | 24.04%  |
| Intel Celeron           | 21        | 10.1%   |
| Intel Core i3           | 16        | 7.69%   |
| Intel Atom              | 12        | 5.77%   |
| Intel Core 2 Duo        | 10        | 4.81%   |
| AMD Ryzen 7             | 9         | 4.33%   |
| Other                   | 7         | 3.37%   |
| AMD Ryzen 5             | 4         | 1.92%   |
| Intel Pentium           | 3         | 1.44%   |
| AMD Turion 64 X2 Mobile | 3         | 1.44%   |
| AMD A6                  | 3         | 1.44%   |
| AMD Ryzen 3             | 2         | 0.96%   |
| AMD E1                  | 2         | 0.96%   |
| AMD E                   | 2         | 0.96%   |
| AMD A8                  | 2         | 0.96%   |
| AMD A4                  | 2         | 0.96%   |
| Intel Pentium Silver    | 1         | 0.48%   |
| Intel Pentium M         | 1         | 0.48%   |
| Intel Pentium Dual-Core | 1         | 0.48%   |
| Intel Genuine           | 1         | 0.48%   |
| Intel Core Duo          | 1         | 0.48%   |
| Intel Core 2            | 1         | 0.48%   |
| Intel Celeron M         | 1         | 0.48%   |
| AMD Sempron             | 1         | 0.48%   |
| AMD Ryzen 9             | 1         | 0.48%   |
| AMD Athlon 64 X2        | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 124       | 59.62%  |
| 4      | 55        | 26.44%  |
| 1      | 10        | 4.81%   |
| 8      | 9         | 4.33%   |
| 6      | 9         | 4.33%   |
| 14     | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 208       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 146       | 70.19%  |
| 1      | 62        | 29.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 199       | 95.22%  |
| 32-bit         | 10        | 4.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 11.37%  |
| 0x206a7    | 19        | 9%      |
| 0x306a9    | 17        | 8.06%   |
| 0x406e3    | 10        | 4.74%   |
| 0x20655    | 9         | 4.27%   |
| 0x306c3    | 8         | 3.79%   |
| 0x40651    | 7         | 3.32%   |
| 0x906ea    | 5         | 2.37%   |
| 0x806ea    | 5         | 2.37%   |
| 0x406c4    | 5         | 2.37%   |
| 0x306d4    | 5         | 2.37%   |
| 0x806e9    | 4         | 1.9%    |
| 0x806c1    | 4         | 1.9%    |
| 0x706a1    | 4         | 1.9%    |
| 0x30678    | 4         | 1.9%    |
| 0x20652    | 4         | 1.9%    |
| 0x106c2    | 4         | 1.9%    |
| 0x1067a    | 4         | 1.9%    |
| 0x0a50000c | 4         | 1.9%    |
| 0xa0652    | 3         | 1.42%   |
| 0x506e3    | 3         | 1.42%   |
| 0x106ca    | 3         | 1.42%   |
| 0x10676    | 3         | 1.42%   |
| 0x08608103 | 3         | 1.42%   |
| 0x03000027 | 3         | 1.42%   |
| 0x906e9    | 2         | 0.95%   |
| 0x806ec    | 2         | 0.95%   |
| 0x706e5    | 2         | 0.95%   |
| 0x706a8    | 2         | 0.95%   |
| 0x6fd      | 2         | 0.95%   |
| 0x506c9    | 2         | 0.95%   |
| 0x30661    | 2         | 0.95%   |
| 0x106e5    | 2         | 0.95%   |
| 0x08108102 | 2         | 0.95%   |
| 0x0810100b | 2         | 0.95%   |
| 0x07030105 | 2         | 0.95%   |
| 0x0700010f | 2         | 0.95%   |
| 0x906ed    | 1         | 0.47%   |
| 0x906a3    | 1         | 0.47%   |
| 0x806eb    | 1         | 0.47%   |
| 0x806d1    | 1         | 0.47%   |
| 0x6fb      | 1         | 0.47%   |
| 0x6f2      | 1         | 0.47%   |
| 0x6ec      | 1         | 0.47%   |
| 0x6e8      | 1         | 0.47%   |
| 0x6d8      | 1         | 0.47%   |
| 0x6d6      | 1         | 0.47%   |
| 0x406c3    | 1         | 0.47%   |
| 0x40661    | 1         | 0.47%   |
| 0x10661    | 1         | 0.47%   |
| 0x0a50000b | 1         | 0.47%   |
| 0x08600106 | 1         | 0.47%   |
| 0x08600104 | 1         | 0.47%   |
| 0x08108109 | 1         | 0.47%   |
| 0x08101007 | 1         | 0.47%   |
| 0x07030104 | 1         | 0.47%   |
| 0x06006705 | 1         | 0.47%   |
| 0x05000119 | 1         | 0.47%   |
| 0x0500010d | 1         | 0.47%   |
| 0x02000057 | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 23        | 11.06%  |
| KabyLake         | 23        | 11.06%  |
| IvyBridge        | 19        | 9.13%   |
| Haswell          | 16        | 7.69%   |
| Westmere         | 14        | 6.73%   |
| Skylake          | 14        | 6.73%   |
| Silvermont       | 12        | 5.77%   |
| Bonnell          | 9         | 4.33%   |
| Penryn           | 8         | 3.85%   |
| Goldmont plus    | 6         | 2.88%   |
| Broadwell        | 6         | 2.88%   |
| Zen 3            | 5         | 2.4%    |
| TigerLake        | 5         | 2.4%    |
| Core             | 5         | 2.4%    |
| P6               | 4         | 1.92%   |
| K8 Hammer        | 4         | 1.92%   |
| Icelake          | 4         | 1.92%   |
| Zen+             | 3         | 1.44%   |
| Zen              | 3         | 1.44%   |
| Puma             | 3         | 1.44%   |
| K10 Llano        | 3         | 1.44%   |
| CometLake        | 3         | 1.44%   |
| Unknown          | 3         | 1.44%   |
| Zen 2            | 2         | 0.96%   |
| Nehalem          | 2         | 0.96%   |
| Jaguar           | 2         | 0.96%   |
| Goldmont         | 2         | 0.96%   |
| Bobcat           | 2         | 0.96%   |
| K8 & K10 hybrid  | 1         | 0.48%   |
| Excavator        | 1         | 0.48%   |
| Alderlake Hybrid | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 158       | 61.72%  |
| Nvidia | 52        | 20.31%  |
| AMD    | 46        | 17.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 7.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 6.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.6%    |
| Intel UHD Graphics 620                                                                   | 6         | 2.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.86%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.86%   |
| Intel HD Graphics 620                                                                    | 5         | 1.86%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.86%   |
| Intel HD Graphics 530                                                                    | 4         | 1.49%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.49%   |
| AMD Cezanne                                                                              | 4         | 1.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.12%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.12%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.12%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.12%   |
| AMD Lucienne                                                                             | 3         | 1.12%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 3         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.74%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.74%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.74%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.74%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 2         | 0.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.74%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.74%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 2         | 0.74%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.74%   |
| Intel HD Graphics 630                                                                    | 2         | 0.74%   |
| Intel HD Graphics 500                                                                    | 2         | 0.74%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.74%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.74%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.74%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.74%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                                  | 2         | 0.74%   |
| AMD Renoir                                                                               | 2         | 0.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.74%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.74%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.37%   |
| Nvidia TU117M                                                                            | 1         | 0.37%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.37%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 1         | 0.37%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.37%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.37%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.37%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 113       | 54.33%  |
| Intel + Nvidia | 35        | 16.83%  |
| 1 x AMD        | 28        | 13.46%  |
| 1 x Nvidia     | 13        | 6.25%   |
| Intel + AMD    | 9         | 4.33%   |
| 2 x AMD        | 5         | 2.4%    |
| AMD + Nvidia   | 4         | 1.92%   |
| 2 x Intel      | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 189       | 90%     |
| Proprietary | 15        | 7.14%   |
| Unknown     | 6         | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 74.64%  |
| 0.01-0.5   | 26        | 12.44%  |
| 1.01-2.0   | 13        | 6.22%   |
| 0.51-1.0   | 12        | 5.74%   |
| 7.01-8.0   | 1         | 0.48%   |
| 3.01-4.0   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 19.28%  |
| LG Display              | 32        | 14.35%  |
| Chimei Innolux          | 32        | 14.35%  |
| Samsung Electronics     | 25        | 11.21%  |
| BOE                     | 19        | 8.52%   |
| Lenovo                  | 12        | 5.38%   |
| Chi Mei Optoelectronics | 10        | 4.48%   |
| PANDA                   | 6         | 2.69%   |
| InfoVision              | 4         | 1.79%   |
| Hewlett-Packard         | 4         | 1.79%   |
| HannStar                | 4         | 1.79%   |
| Dell                    | 4         | 1.79%   |
| Apple                   | 4         | 1.79%   |
| Sharp                   | 3         | 1.35%   |
| LG Philips              | 3         | 1.35%   |
| Ancor Communications    | 3         | 1.35%   |
| Sony                    | 2         | 0.9%    |
| Philips                 | 2         | 0.9%    |
| Goldstar                | 2         | 0.9%    |
| CPT                     | 2         | 0.9%    |
| Vizio                   | 1         | 0.45%   |
| Sunplus                 | 1         | 0.45%   |
| Panasonic               | 1         | 0.45%   |
| LTM                     | 1         | 0.45%   |
| InnoLux Display         | 1         | 0.45%   |
| AOC                     | 1         | 0.45%   |
| Acer                    | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 1.79%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 1.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.35%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.9%    |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.9%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.9%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.9%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.9%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.9%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.9%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x174mm 14.0-inch          | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.9%    |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.9%    |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch            | 2         | 0.9%    |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                        | 1         | 0.45%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 0.45%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.45%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 0.45%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.45%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.45%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch     | 1         | 0.45%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 340x190mm 15.3-inch        | 1         | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.45%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch    | 1         | 0.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 1         | 0.45%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch                | 1         | 0.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 0.45%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 0.45%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                  | 1         | 0.45%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch              | 1         | 0.45%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                        | 1         | 0.45%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 0.45%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 0.45%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 81        | 37.85%  |
| 1366x768 (WXGA)    | 78        | 36.45%  |
| 1600x900 (HD+)     | 11        | 5.14%   |
| 1280x800 (WXGA)    | 10        | 4.67%   |
| 1024x600           | 7         | 3.27%   |
| 3840x2160 (4K)     | 5         | 2.34%   |
| 1440x900 (WXGA+)   | 5         | 2.34%   |
| 1680x1050 (WSXGA+) | 3         | 1.4%    |
| 1280x1024 (SXGA)   | 3         | 1.4%    |
| 2560x1440 (QHD)    | 2         | 0.93%   |
| 2560x1080          | 2         | 0.93%   |
| 1400x1050          | 2         | 0.93%   |
| 3840x2400          | 1         | 0.47%   |
| 2880x1800          | 1         | 0.47%   |
| 2256x1504          | 1         | 0.47%   |
| 2160x1440          | 1         | 0.47%   |
| 1920x1200 (WUXGA)  | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 96        | 43.24%  |
| 13     | 30        | 13.51%  |
| 14     | 27        | 12.16%  |
| 17     | 14        | 6.31%   |
| 10     | 8         | 3.6%    |
| 11     | 7         | 3.15%   |
| 12     | 6         | 2.7%    |
| 24     | 5         | 2.25%   |
| 23     | 5         | 2.25%   |
| 19     | 5         | 2.25%   |
| 27     | 4         | 1.8%    |
| 34     | 2         | 0.9%    |
| 21     | 2         | 0.9%    |
| 20     | 2         | 0.9%    |
| 18     | 2         | 0.9%    |
| 84     | 1         | 0.45%   |
| 46     | 1         | 0.45%   |
| 43     | 1         | 0.45%   |
| 40     | 1         | 0.45%   |
| 37     | 1         | 0.45%   |
| 32     | 1         | 0.45%   |
| 16     | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 134       | 60.36%  |
| 201-300     | 35        | 15.77%  |
| 351-400     | 24        | 10.81%  |
| 501-600     | 14        | 6.31%   |
| 401-500     | 7         | 3.15%   |
| 701-800     | 3         | 1.35%   |
| 801-900     | 2         | 0.9%    |
| 1501-2000   | 1         | 0.45%   |
| 1001-1500   | 1         | 0.45%   |
| 901-1000    | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 171       | 83.41%  |
| 16/10 | 22        | 10.73%  |
| 5/4   | 4         | 1.95%   |
| 3/2   | 4         | 1.95%   |
| 4/3   | 2         | 0.98%   |
| 21/9  | 2         | 0.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 96        | 43.24%  |
| 81-90          | 48        | 21.62%  |
| 121-130        | 13        | 5.86%   |
| 71-80          | 9         | 4.05%   |
| 201-250        | 9         | 4.05%   |
| 41-50          | 8         | 3.6%    |
| 151-200        | 8         | 3.6%    |
| 51-60          | 7         | 3.15%   |
| 61-70          | 6         | 2.7%    |
| 301-350        | 4         | 1.8%    |
| 501-1000       | 4         | 1.8%    |
| 351-500        | 3         | 1.35%   |
| 251-300        | 2         | 0.9%    |
| 141-150        | 2         | 0.9%    |
| More than 1000 | 1         | 0.45%   |
| 131-140        | 1         | 0.45%   |
| 111-120        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 80        | 36.87%  |
| 101-120       | 79        | 36.41%  |
| 51-100        | 44        | 20.28%  |
| 161-240       | 10        | 4.61%   |
| More than 240 | 3         | 1.38%   |
| 1-50          | 1         | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 174       | 83.25%  |
| 2     | 29        | 13.88%  |
| 0     | 4         | 1.91%   |
| 3     | 2         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 108       | 32.34%  |
| Realtek Semiconductor             | 102       | 30.54%  |
| Qualcomm Atheros                  | 60        | 17.96%  |
| Broadcom                          | 21        | 6.29%   |
| Marvell Technology Group          | 6         | 1.8%    |
| Nvidia                            | 5         | 1.5%    |
| MediaTek                          | 4         | 1.2%    |
| TP-Link                           | 3         | 0.9%    |
| Sierra Wireless                   | 3         | 0.9%    |
| Huawei Technologies               | 3         | 0.9%    |
| Broadcom Limited                  | 3         | 0.9%    |
| Ralink Technology                 | 2         | 0.6%    |
| Ralink                            | 2         | 0.6%    |
| Ericsson Business Mobile Networks | 2         | 0.6%    |
| Attansic Technology               | 2         | 0.6%    |
| Samsung Electronics               | 1         | 0.3%    |
| Qualcomm                          | 1         | 0.3%    |
| JMicron Technology                | 1         | 0.3%    |
| Hewlett-Packard                   | 1         | 0.3%    |
| Google                            | 1         | 0.3%    |
| Dell                              | 1         | 0.3%    |
| ASUSTek Computer                  | 1         | 0.3%    |
| ASIX Electronics                  | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 66        | 16.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 18        | 4.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 15        | 3.68%   |
| Intel Wireless 7260                                                            | 11        | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 1.96%   |
| Intel Wireless 8260                                                            | 7         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 7         | 1.72%   |
| Intel Centrino Advanced-N 6200                                                 | 7         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 6         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 6         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 6         | 1.47%   |
| Intel Wireless 8265 / 8275                                                     | 6         | 1.47%   |
| Intel Wireless 3165                                                            | 6         | 1.47%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 5         | 1.23%   |
| Intel Wireless 7265                                                            | 5         | 1.23%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.23%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.98%   |
| Intel Ethernet Connection I219-V                                               | 4         | 0.98%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 0.98%   |
| Intel Centrino Advanced-N 6235                                                 | 4         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 4         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 3         | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 3         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 0.74%   |
| Intel Wi-Fi 6 AX201                                                            | 3         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 3         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 3         | 0.74%   |
| Intel Centrino Wireless-N 2230                                                 | 3         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 3         | 0.74%   |
| TP-Link TL-WN722N v2                                                           | 2         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.49%   |
| Realtek 802.11n WLAN Adapter                                                   | 2         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 2         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.49%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.49%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.49%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.49%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 2         | 0.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 0.49%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 2         | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 102       | 47.66%  |
| Qualcomm Atheros      | 47        | 21.96%  |
| Realtek Semiconductor | 35        | 16.36%  |
| Broadcom              | 15        | 7.01%   |
| MediaTek              | 3         | 1.4%    |
| TP-Link               | 2         | 0.93%   |
| Sierra Wireless       | 2         | 0.93%   |
| Ralink Technology     | 2         | 0.93%   |
| Ralink                | 2         | 0.93%   |
| Broadcom Limited      | 2         | 0.93%   |
| Hewlett-Packard       | 1         | 0.47%   |
| ASUSTek Computer      | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 15        | 6.98%   |
| Intel Wireless 7260                                                                           | 11        | 5.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 9         | 4.19%   |
| Intel Wireless 8260                                                                           | 7         | 3.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 7         | 3.26%   |
| Intel Centrino Advanced-N 6200                                                                | 7         | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 6         | 2.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 2.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 6         | 2.79%   |
| Intel Wireless 8265 / 8275                                                                    | 6         | 2.79%   |
| Intel Wireless 3165                                                                           | 6         | 2.79%   |
| Intel Wi-Fi 6 AX200                                                                           | 6         | 2.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 2.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 5         | 2.33%   |
| Intel Wireless 7265                                                                           | 5         | 2.33%   |
| Intel Centrino Advanced-N 6235                                                                | 4         | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 4         | 1.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3         | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 1.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 3         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 3         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 1.4%    |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 1.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 1.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 3         | 1.4%    |
| Intel Centrino Wireless-N 2230                                                                | 3         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 1.4%    |
| TP-Link TL-WN722N v2                                                                          | 2         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 0.93%   |
| Realtek 802.11n WLAN Adapter                                                                  | 2         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2         | 0.93%   |
| Intel Wireless-AC 9260                                                                        | 2         | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2         | 0.93%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 2         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2         | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 2         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 0.93%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 2         | 0.93%   |
| Sierra Wireless EM7455                                                                        | 1         | 0.47%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                                           | 1         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 0.47%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.47%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.47%   |
| Ralink RT2070 Wireless Adapter                                                                | 1         | 0.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.47%   |
| Intel Wireless 3160                                                                           | 1         | 0.47%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 88        | 47.83%  |
| Intel                    | 46        | 25%     |
| Qualcomm Atheros         | 21        | 11.41%  |
| Broadcom                 | 7         | 3.8%    |
| Marvell Technology Group | 6         | 3.26%   |
| Nvidia                   | 5         | 2.72%   |
| Attansic Technology      | 2         | 1.09%   |
| TP-Link                  | 1         | 0.54%   |
| Sierra Wireless          | 1         | 0.54%   |
| Samsung Electronics      | 1         | 0.54%   |
| Qualcomm                 | 1         | 0.54%   |
| MediaTek                 | 1         | 0.54%   |
| JMicron Technology       | 1         | 0.54%   |
| Huawei Technologies      | 1         | 0.54%   |
| Broadcom Limited         | 1         | 0.54%   |
| ASIX Electronics         | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 66        | 35.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 18        | 9.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 4.28%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 4.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.67%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 2.14%   |
| Intel Ethernet Connection I219-V                                               | 4         | 2.14%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 2.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.6%    |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.07%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.07%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.07%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.07%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 1.07%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 1.07%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.07%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.07%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.07%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.07%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 1.07%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 1.07%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.53%   |
| Sierra Wireless EM7345 4G LTE                                                  | 1         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Qualcomm Nokia X100                                                            | 1         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.53%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.53%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.53%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.53%   |
| MediaTek Infinix HOT 9                                                         | 1         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.53%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.53%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.53%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.53%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.53%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.53%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.53%   |
| Huawei JNY-LX1                                                                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.53%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.53%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 201       | 52.21%  |
| Ethernet | 178       | 46.23%  |
| Modem    | 5         | 1.3%    |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 160       | 74.77%  |
| Ethernet | 53        | 24.77%  |
| Unknown  | 1         | 0.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 167       | 80.29%  |
| 1     | 36        | 17.31%  |
| 0     | 5         | 2.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 180       | 85.71%  |
| Yes  | 30        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 42.04%  |
| Broadcom                        | 17        | 10.83%  |
| Realtek Semiconductor           | 16        | 10.19%  |
| Qualcomm Atheros Communications | 15        | 9.55%   |
| IMC Networks                    | 8         | 5.1%    |
| Cambridge Silicon Radio         | 7         | 4.46%   |
| Lite-On Technology              | 6         | 3.82%   |
| Hewlett-Packard                 | 5         | 3.18%   |
| Foxconn / Hon Hai               | 4         | 2.55%   |
| Apple                           | 4         | 2.55%   |
| Toshiba                         | 3         | 1.91%   |
| Dell                            | 3         | 1.91%   |
| Ralink                          | 1         | 0.64%   |
| ASUSTek Computer                | 1         | 0.64%   |
| Alps Electric                   | 1         | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 35        | 22.29%  |
| Realtek Bluetooth Radio                                                             | 9         | 5.73%   |
| Intel AX201 Bluetooth                                                               | 9         | 5.73%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 5.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 4.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 3.82%   |
| Intel AX200 Bluetooth                                                               | 6         | 3.82%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 3.82%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.18%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.55%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 2.55%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.91%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 1.91%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.27%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.27%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.27%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.27%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.27%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.27%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.64%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.64%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.64%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.64%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.64%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.64%   |
| Lite-On Wireless_Device                                                             | 1         | 0.64%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.64%   |
| Intel Bluetooth Device                                                              | 1         | 0.64%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.64%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.64%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.64%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.64%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.64%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.64%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.64%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.64%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.64%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.64%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.64%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.64%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 172       | 67.98%  |
| AMD                   | 36        | 14.23%  |
| Nvidia                | 35        | 13.83%  |
| GN Netcom             | 2         | 0.79%   |
| C-Media Electronics   | 2         | 0.79%   |
| Texas Instruments     | 1         | 0.4%    |
| SteelSeries ApS       | 1         | 0.4%    |
| Realtek Semiconductor | 1         | 0.4%    |
| Plantronics           | 1         | 0.4%    |
| Mark of the Unicorn   | 1         | 0.4%    |
| FIFINE 683 Microphone | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 8.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 7.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 6.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 5.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 5.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 3.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 3.01%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.34%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.01%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.67%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1%      |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1%      |
| Nvidia Audio device                                                                               | 3         | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1%      |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1%      |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 1%      |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia MCP67 High Definition Audio                                                                | 2         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.67%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 2         | 0.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.67%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.67%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.33%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.33%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.33%   |
| Plantronics BT600                                                                                 | 1         | 0.33%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.33%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.33%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.33%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.33%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.33%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.33%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.33%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.33%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.33%   |
| Mark of the Unicorn M Series                                                                      | 1         | 0.33%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.33%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 58        | 23.2%   |
| SK hynix            | 54        | 21.6%   |
| Unknown             | 30        | 12%     |
| Micron Technology   | 26        | 10.4%   |
| Kingston            | 25        | 10%     |
| Crucial             | 12        | 4.8%    |
| Ramaxel Technology  | 6         | 2.4%    |
| Unknown (ABCD)      | 5         | 2%      |
| A-DATA Technology   | 5         | 2%      |
| Smart               | 4         | 1.6%    |
| Transcend           | 3         | 1.2%    |
| Nanya Technology    | 3         | 1.2%    |
| Elpida              | 3         | 1.2%    |
| Corsair             | 3         | 1.2%    |
| Teikon              | 2         | 0.8%    |
| Unknown             | 2         | 0.8%    |
| Unknown (F301)      | 1         | 0.4%    |
| TRS STAR            | 1         | 0.4%    |
| Team                | 1         | 0.4%    |
| PNY                 | 1         | 0.4%    |
| Patriot             | 1         | 0.4%    |
| High Bridge         | 1         | 0.4%    |
| Avant               | 1         | 0.4%    |
| Apacer              | 1         | 0.4%    |
| 48spaces            | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 6         | 2.19%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 5         | 1.82%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 4         | 1.46%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 1.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.46%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 4         | 1.46%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 4         | 1.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 3         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.09%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 3         | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.09%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 1.09%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.09%   |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 2         | 0.73%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 2         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 0.73%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 2         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.73%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.73%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 2         | 0.73%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 2         | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.73%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.73%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.73%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 0.73%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 2         | 0.73%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 2         | 0.73%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s               | 2         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.73%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 2         | 0.73%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s               | 2         | 0.73%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 2         | 0.73%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s           | 2         | 0.73%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.73%   |
| Kingston RAM HP16D3LS1KEGR/4G 4GB SODIMM DDR3 1600MT/s              | 2         | 0.73%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s             | 2         | 0.73%   |
| Unknown                                                             | 2         | 0.73%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.36%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                          | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DRAM                                  | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                           | 1         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 1         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 109       | 52.15%  |
| DDR4    | 61        | 29.19%  |
| DDR2    | 16        | 7.66%   |
| LPDDR4  | 8         | 3.83%   |
| SDRAM   | 4         | 1.91%   |
| DDR     | 4         | 1.91%   |
| DRAM    | 3         | 1.44%   |
| LPDDR3  | 2         | 0.96%   |
| DDR5    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 198       | 95.19%  |
| Row Of Chips | 6         | 2.88%   |
| Chip         | 3         | 1.44%   |
| DIMM         | 1         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 96        | 41.03%  |
| 8192  | 65        | 27.78%  |
| 2048  | 45        | 19.23%  |
| 16384 | 14        | 5.98%   |
| 1024  | 13        | 5.56%   |
| 32768 | 1         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 66        | 28.95%  |
| 2667    | 26        | 11.4%   |
| 1334    | 23        | 10.09%  |
| 3200    | 20        | 8.77%   |
| 2400    | 18        | 7.89%   |
| 1333    | 15        | 6.58%   |
| Unknown | 15        | 6.58%   |
| 667     | 11        | 4.82%   |
| 2133    | 8         | 3.51%   |
| 1067    | 6         | 2.63%   |
| 800     | 4         | 1.75%   |
| 4199    | 3         | 1.32%   |
| 3266    | 3         | 1.32%   |
| 4267    | 2         | 0.88%   |
| 1867    | 2         | 0.88%   |
| 533     | 2         | 0.88%   |
| 8400    | 1         | 0.44%   |
| 4800    | 1         | 0.44%   |
| 1777    | 1         | 0.44%   |
| 166     | 1         | 0.44%   |

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
| Chicony Electronics                    | 41        | 24.4%   |
| Acer                                   | 16        | 9.52%   |
| Realtek Semiconductor                  | 14        | 8.33%   |
| Sunplus Innovation Technology          | 13        | 7.74%   |
| Microdia                               | 12        | 7.14%   |
| IMC Networks                           | 9         | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.36%   |
| Lite-On Technology                     | 8         | 4.76%   |
| Suyin                                  | 7         | 4.17%   |
| Quanta                                 | 6         | 3.57%   |
| Lenovo                                 | 6         | 3.57%   |
| Z-Star Microelectronics                | 3         | 1.79%   |
| Syntek                                 | 3         | 1.79%   |
| Silicon Motion                         | 3         | 1.79%   |
| Ricoh                                  | 3         | 1.79%   |
| Luxvisions Innotech Limited            | 2         | 1.19%   |
| Alcor Micro                            | 2         | 1.19%   |
| Y Media                                | 1         | 0.6%    |
| Xiongmai                               | 1         | 0.6%    |
| WaveRider Communications               | 1         | 0.6%    |
| Samsung Electronics                    | 1         | 0.6%    |
| Primax Electronics                     | 1         | 0.6%    |
| Logitech                               | 1         | 0.6%    |
| Importek                               | 1         | 0.6%    |
| icSpring                               | 1         | 0.6%    |
| Goodong Industry                       | 1         | 0.6%    |
| Cubeternet                             | 1         | 0.6%    |
| Apple                                  | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 5.36%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 2.98%   |
| Lite-On Integrated Camera                                   | 5         | 2.98%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 2.38%   |
| Chicony USB 2.0 Camera                                      | 4         | 2.38%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 2.38%   |
| Acer BisonCam, NB Pro                                       | 4         | 2.38%   |
| Syntek EasyCamera                                           | 3         | 1.79%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 1.79%   |
| Lenovo Integrated Webcam [R5U877]                           | 3         | 1.79%   |
| Chicony HP Truevision HD camera                             | 3         | 1.79%   |
| Sunplus HD WebCam                                           | 2         | 1.19%   |
| Sunplus ASUS USB2.0 Webcam                                  | 2         | 1.19%   |
| Ricoh USB2.0 Camera                                         | 2         | 1.19%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.19%   |
| Realtek USB Camera                                          | 2         | 1.19%   |
| Quanta VGA WebCam                                           | 2         | 1.19%   |
| Quanta HD User Facing                                       | 2         | 1.19%   |
| Microdia USB 2.0 Camera                                     | 2         | 1.19%   |
| Microdia Integrated_Webcam_HD                               | 2         | 1.19%   |
| Microdia Integrated Webcam                                  | 2         | 1.19%   |
| Lenovo Integrated Webcam                                    | 2         | 1.19%   |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 1.19%   |
| Chicony HD WebCam                                           | 2         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 1.19%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.19%   |
| Acer SunplusIT INC. Integrated Camera                       | 2         | 1.19%   |
| Acer Lenovo Integrated Webcam                               | 2         | 1.19%   |
| Acer Lenovo EasyCamera                                      | 2         | 1.19%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 0.6%    |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.6%    |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.6%    |
| Y Media USB Camera                                          | 1         | 0.6%    |
| Xiongmai web camera                                         | 1         | 0.6%    |
| WaveRider USB Live camera                                   | 1         | 0.6%    |
| Suyin Sony Visual Communication Camera                      | 1         | 0.6%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.6%    |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.6%    |
| Suyin 1.3M HD WebCam                                        | 1         | 0.6%    |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.6%    |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.6%    |
| Sunplus Integrated_Webcam_FHD                               | 1         | 0.6%    |
| Sunplus Dell Integrated Webcam                              | 1         | 0.6%    |
| Silicon Motion WebCam SCB-0385N                             | 1         | 0.6%    |
| Silicon Motion Web Camera                                   | 1         | 0.6%    |
| Silicon Motion Silicon Motion Camera                        | 1         | 0.6%    |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.6%    |
| Ricoh Integrated Webcam                                     | 1         | 0.6%    |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 0.6%    |
| Realtek Lenovo EasyCamera                                   | 1         | 0.6%    |
| Realtek Integrated Webcam                                   | 1         | 0.6%    |
| Realtek HD Webcam - Realtek                                 | 1         | 0.6%    |
| Realtek HD WebCam                                           | 1         | 0.6%    |
| Realtek EasyCamera                                          | 1         | 0.6%    |
| Quanta HP Wide Vision HD Camera                             | 1         | 0.6%    |
| Quanta HP TrueVision HD Camera                              | 1         | 0.6%    |
| Primax Dell Laptop Integrated Webcam 2Mpix                  | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 42.86%  |
| Upek                       | 6         | 17.14%  |
| Synaptics                  | 4         | 11.43%  |
| AuthenTec                  | 4         | 11.43%  |
| Shenzhen Goodix Technology | 3         | 8.57%   |
| LighTuning Technology      | 2         | 5.71%   |
| STMicroelectronics         | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 11.43%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 11.43%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 8.57%   |
| Validity Sensors Synaptics WBDI                            | 3         | 8.57%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 5.71%   |
| Upek TCS5B Fingerprint sensor                              | 2         | 5.71%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 5.71%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 5.71%   |
| AuthenTec AES2810                                          | 2         | 5.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.86%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.86%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.86%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.86%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 2.86%   |
| LighTuning Fingerprint Reader                              | 1         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2.86%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.86%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.86%   |
| Unknown                                                    | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 35.71%  |
| Broadcom              | 4         | 28.57%  |
| Lenovo                | 3         | 21.43%  |
| O2 Micro              | 1         | 7.14%   |
| Advanced Card Systems | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 35.71%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 21.43%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| Broadcom 5880                                                                | 1         | 7.14%   |
| Advanced Card Systems ACR122U                                                | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 130       | 61.32%  |
| 1     | 65        | 30.66%  |
| 2     | 16        | 7.55%   |
| 3     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 42        | 42.42%  |
| Fingerprint reader       | 35        | 35.35%  |
| Chipcard                 | 12        | 12.12%  |
| Storage                  | 3         | 3.03%   |
| Multimedia controller    | 3         | 3.03%   |
| Net/wireless             | 2         | 2.02%   |
| Communication controller | 1         | 1.01%   |
| Bluetooth                | 1         | 1.01%   |

