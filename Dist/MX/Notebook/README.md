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

Total: 259

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 19 | 84        | 40.78%  |
| MX 21 | 63        | 30.58%  |
| MX 20 | 43        | 20.87%  |
| MX 18 | 13        | 6.31%   |
| MX 17 | 2         | 0.97%   |
| MX 16 | 1         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MX   | 198       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 32        | 14.55%  |
| 5.10.0-9-amd64             | 14        | 6.36%   |
| 5.10.0-5mx-amd64           | 13        | 5.91%   |
| 5.10.0-13-amd64            | 10        | 4.55%   |
| 5.8.0-3-amd64              | 9         | 4.09%   |
| 5.14.0-4mx-amd64           | 8         | 3.64%   |
| 5.10.0-14-amd64            | 6         | 2.73%   |
| 5.10.0-11-amd64            | 6         | 2.73%   |
| 4.19.0-16-amd64            | 6         | 2.73%   |
| 4.19.0-14-amd64            | 6         | 2.73%   |
| 4.19.0-13-amd64            | 6         | 2.73%   |
| 5.6.0-2-amd64              | 5         | 2.27%   |
| 5.16.0-5mx-amd64           | 4         | 1.82%   |
| 4.19.0-5-amd64             | 4         | 1.82%   |
| 4.19.0-17-amd64            | 4         | 1.82%   |
| 4.19.0-11-amd64            | 4         | 1.82%   |
| 5.10.0-8mx-amd64           | 3         | 1.36%   |
| 5.10.0-16-amd64            | 3         | 1.36%   |
| 4.19.0-9-amd64             | 3         | 1.36%   |
| 4.19.0-12-amd64            | 3         | 1.36%   |
| 4.19.0-1-amd64             | 3         | 1.36%   |
| 5.8.16-antix.1-amd64-smp   | 2         | 0.91%   |
| 5.6.10-antix.1-amd64-smp   | 2         | 0.91%   |
| 5.4.0-3-amd64              | 2         | 0.91%   |
| 5.16.0-6mx-amd64           | 2         | 0.91%   |
| 5.10.0-8-amd64             | 2         | 0.91%   |
| 5.10.0-15-amd64            | 2         | 0.91%   |
| 5.10.0-13-686-pae          | 2         | 0.91%   |
| 5.10.0-11-686-pae          | 2         | 0.91%   |
| 5.10.0-10-amd64            | 2         | 0.91%   |
| 4.19.0-8-amd64             | 2         | 0.91%   |
| 4.19.0-16-686-pae          | 2         | 0.91%   |
| 4.15.0-1-amd64             | 2         | 0.91%   |
| 5.9.1-rt20avl1             | 1         | 0.45%   |
| 5.7.0-19.1-liquorix-amd64  | 1         | 0.45%   |
| 5.6.0-15.2-liquorix-amd64  | 1         | 0.45%   |
| 5.6.0-12.1-liquorix-amd64  | 1         | 0.45%   |
| 5.5.0-9.1-liquorix-amd64   | 1         | 0.45%   |
| 5.4.0-antix.1-amd64-smp    | 1         | 0.45%   |
| 5.4.0-13.3-liquorix-amd64  | 1         | 0.45%   |
| 5.4.0-11.2-liquorix-amd64  | 1         | 0.45%   |
| 5.4.0-10.2-liquorix-amd64  | 1         | 0.45%   |
| 5.3.10-antix.1-amd64-smp   | 1         | 0.45%   |
| 5.3.0-2-amd64              | 1         | 0.45%   |
| 5.3.0-10.1-liquorix-amd64  | 1         | 0.45%   |
| 5.2.8-antix.1-amd64-smp    | 1         | 0.45%   |
| 5.2.21-antix.2-amd64-smp   | 1         | 0.45%   |
| 5.2.21-antix.2-686-smp-pae | 1         | 0.45%   |
| 5.2.0-21.2-liquorix-amd64  | 1         | 0.45%   |
| 5.17.0-5.2-liquorix-amd64  | 1         | 0.45%   |
| 5.17.0-1-amd64             | 1         | 0.45%   |
| 5.16.0-4mx-amd64           | 1         | 0.45%   |
| 5.15.0-3mx-amd64           | 1         | 0.45%   |
| 5.15.0-1mx-amd64           | 1         | 0.45%   |
| 5.13.0-12.3-liquorix-amd64 | 1         | 0.45%   |
| 5.11.0-21.1-liquorix-amd64 | 1         | 0.45%   |
| 5.10.1-gnu                 | 1         | 0.45%   |
| 5.10.0-9mx-amd64           | 1         | 0.45%   |
| 5.10.0-6.2-liquorix-amd64  | 1         | 0.45%   |
| 5.10.0-12-amd64            | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.0   | 79        | 37.44%  |
| 5.10.0   | 64        | 30.33%  |
| 5.8.0    | 9         | 4.27%   |
| 5.14.0   | 8         | 3.79%   |
| 5.6.0    | 7         | 3.32%   |
| 5.16.0   | 7         | 3.32%   |
| 5.4.0    | 6         | 2.84%   |
| 5.8.16   | 2         | 0.95%   |
| 5.6.10   | 2         | 0.95%   |
| 5.3.0    | 2         | 0.95%   |
| 5.2.21   | 2         | 0.95%   |
| 5.17.0   | 2         | 0.95%   |
| 5.15.0   | 2         | 0.95%   |
| 4.9.193  | 2         | 0.95%   |
| 4.15.0   | 2         | 0.95%   |
| 5.9.1    | 1         | 0.47%   |
| 5.7.0    | 1         | 0.47%   |
| 5.5.0    | 1         | 0.47%   |
| 5.3.10   | 1         | 0.47%   |
| 5.2.8    | 1         | 0.47%   |
| 5.2.0    | 1         | 0.47%   |
| 5.13.0   | 1         | 0.47%   |
| 5.11.0   | 1         | 0.47%   |
| 5.10.1   | 1         | 0.47%   |
| 5.1.2    | 1         | 0.47%   |
| 5.0.0    | 1         | 0.47%   |
| 4.9.246  | 1         | 0.47%   |
| 4.19.174 | 1         | 0.47%   |
| 4.18.0   | 1         | 0.47%   |
| 3.16.0   | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 80        | 37.91%  |
| 5.10    | 65        | 30.81%  |
| 5.8     | 11        | 5.21%   |
| 5.6     | 9         | 4.27%   |
| 5.14    | 8         | 3.79%   |
| 5.16    | 7         | 3.32%   |
| 5.4     | 6         | 2.84%   |
| 5.2     | 4         | 1.9%    |
| 5.3     | 3         | 1.42%   |
| 4.9     | 3         | 1.42%   |
| 5.17    | 2         | 0.95%   |
| 5.15    | 2         | 0.95%   |
| 4.15    | 2         | 0.95%   |
| 5.9     | 1         | 0.47%   |
| 5.7     | 1         | 0.47%   |
| 5.5     | 1         | 0.47%   |
| 5.13    | 1         | 0.47%   |
| 5.11    | 1         | 0.47%   |
| 5.1     | 1         | 0.47%   |
| 5.0     | 1         | 0.47%   |
| 4.18    | 1         | 0.47%   |
| 3.16    | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 185       | 92.96%  |
| i686   | 14        | 7.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 142       | 70.65%  |
| KDE5            | 32        | 15.92%  |
| Budgie          | 5         | 2.49%   |
| Unknown         | 5         | 2.49%   |
| i3              | 4         | 1.99%   |
| MATE            | 2         | 1%      |
| GNOME           | 2         | 1%      |
| Cinnamon        | 2         | 1%      |
| X-Cinnamon      | 1         | 0.5%    |
| Trinity         | 1         | 0.5%    |
| spectrwm        | 1         | 0.5%    |
| LXQt            | 1         | 0.5%    |
| LXDE            | 1         | 0.5%    |
| GNOME Flashback | 1         | 0.5%    |
| fluxbox         | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 195       | 98.48%  |
| Tty  | 3         | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 158       | 79%     |
| SDDM    | 27        | 13.5%   |
| TDM     | 9         | 4.5%    |
| SLiM    | 5         | 2.5%    |
| Unknown | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 73        | 35.61%  |
| Unknown | 56        | 27.32%  |
| de_DE   | 18        | 8.78%   |
| en_GB   | 10        | 4.88%   |
| ru_RU   | 8         | 3.9%    |
| sk_SK   | 6         | 2.93%   |
| pt_BR   | 5         | 2.44%   |
| it_IT   | 5         | 2.44%   |
| fr_FR   | 3         | 1.46%   |
| es_ES   | 3         | 1.46%   |
| pl_PL   | 2         | 0.98%   |
| en_IE   | 2         | 0.98%   |
| en_AU   | 2         | 0.98%   |
| zh_CN   | 1         | 0.49%   |
| uk_UA   | 1         | 0.49%   |
| tr_TR   | 1         | 0.49%   |
| nl_NL   | 1         | 0.49%   |
| fr_BE   | 1         | 0.49%   |
| fi_FI   | 1         | 0.49%   |
| es_VE   | 1         | 0.49%   |
| es_PE   | 1         | 0.49%   |
| es_MX   | 1         | 0.49%   |
| es_CO   | 1         | 0.49%   |
| de_CH   | 1         | 0.49%   |
| cs_CZ   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 104       | 52.53%  |
| BIOS | 94        | 47.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 172       | 86.87%  |
| Overlay | 19        | 9.6%    |
| Btrfs   | 4         | 2.02%   |
| Xfs     | 1         | 0.51%   |
| F2fs    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 121       | 60.8%   |
| MBR     | 75        | 37.69%  |
| Unknown | 3         | 1.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 160       | 80%     |
| Yes       | 40        | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 115       | 57.79%  |
| Yes       | 84        | 42.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 45        | 22.73%  |
| Hewlett-Packard     | 32        | 16.16%  |
| Dell                | 22        | 11.11%  |
| ASUSTek Computer    | 22        | 11.11%  |
| Acer                | 20        | 10.1%   |
| Toshiba             | 8         | 4.04%   |
| Sony                | 8         | 4.04%   |
| Samsung Electronics | 4         | 2.02%   |
| MSI                 | 4         | 2.02%   |
| Medion              | 4         | 2.02%   |
| Fujitsu Siemens     | 3         | 1.52%   |
| Apple               | 3         | 1.52%   |
| Alienware           | 3         | 1.52%   |
| Google              | 2         | 1.01%   |
| Gigabyte Technology | 2         | 1.01%   |
| Clevo               | 2         | 1.01%   |
| Unknown             | 2         | 1.01%   |
| UMAX                | 1         | 0.51%   |
| TUXEDO              | 1         | 0.51%   |
| Pixus               | 1         | 0.51%   |
| Panasonic           | 1         | 0.51%   |
| Packard Bell        | 1         | 0.51%   |
| Notebook            | 1         | 0.51%   |
| Irbis               | 1         | 0.51%   |
| Intel               | 1         | 0.51%   |
| Framework           | 1         | 0.51%   |
| eMachines           | 1         | 0.51%   |
| efirstview          | 1         | 0.51%   |
| Chuwi               | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 4         | 2.02%   |
| HP Stream Laptop 14-cb0XX                | 2         | 1.01%   |
| HP ProBook 650 G1                        | 2         | 1.01%   |
| UMAX VisionBook-N12R                     | 1         | 0.51%   |
| TUXEDO N7x0WU                            | 1         | 0.51%   |
| Toshiba Satellite P875                   | 1         | 0.51%   |
| Toshiba Satellite L850-CJK               | 1         | 0.51%   |
| Toshiba Satellite C845                   | 1         | 0.51%   |
| Toshiba Satellite C70-B                  | 1         | 0.51%   |
| Toshiba Satellite C660                   | 1         | 0.51%   |
| Toshiba Satellite C50-A-12K              | 1         | 0.51%   |
| Toshiba Satellite A300                   | 1         | 0.51%   |
| Toshiba PORTEGE R705                     | 1         | 0.51%   |
| Sony VPCSB1V9R                           | 1         | 0.51%   |
| Sony VPCF23P1E                           | 1         | 0.51%   |
| Sony VPCF119FX                           | 1         | 0.51%   |
| Sony VPCEH2N1E                           | 1         | 0.51%   |
| Sony VPCEC3S1E                           | 1         | 0.51%   |
| Sony VGN-NR310FH                         | 1         | 0.51%   |
| Sony SVT13115FBS                         | 1         | 0.51%   |
| Sony SVE1513Q1ESI                        | 1         | 0.51%   |
| Samsung R780/R778                        | 1         | 0.51%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 0.51%   |
| Samsung 340XAA/350XAA/550XAA             | 1         | 0.51%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 0.51%   |
| Pixus Rise                               | 1         | 0.51%   |
| Panasonic CF-C1BT02EGE                   | 1         | 0.51%   |
| Packard Bell EasyNote TE11HC             | 1         | 0.51%   |
| Notebook W65_W67RZ1                      | 1         | 0.51%   |
| MSI MS-N033                              | 1         | 0.51%   |
| MSI GV62 8RD                             | 1         | 0.51%   |
| MSI GP63 Leopard 8RD                     | 1         | 0.51%   |
| MSI Alpha 15 B5EEK                       | 1         | 0.51%   |
| Medion P6669 MD60147                     | 1         | 0.51%   |
| Medion E6234                             | 1         | 0.51%   |
| Medion E14304                            | 1         | 0.51%   |
| Medion Akoya E1318T                      | 1         | 0.51%   |
| Lenovo V145-15AST 81MT                   | 1         | 0.51%   |
| Lenovo ThinkPad X301 2776LBU             | 1         | 0.51%   |
| Lenovo ThinkPad X270 W10DG 20K5S0YT00    | 1         | 0.51%   |
| Lenovo ThinkPad X250 20CLS4YA00          | 1         | 0.51%   |
| Lenovo ThinkPad X220 4291WMQ             | 1         | 0.51%   |
| Lenovo ThinkPad X220 4291F52             | 1         | 0.51%   |
| Lenovo ThinkPad X201s 5413A19            | 1         | 0.51%   |
| Lenovo ThinkPad X201 3680MY9             | 1         | 0.51%   |
| Lenovo ThinkPad X1C 5th W10DG 20K4S0EC00 | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0013AU | 1         | 0.51%   |
| Lenovo ThinkPad W541 20EG0005MS          | 1         | 0.51%   |
| Lenovo ThinkPad W510 4875W17             | 1         | 0.51%   |
| Lenovo ThinkPad T60 20085TG              | 1         | 0.51%   |
| Lenovo ThinkPad T530 2394CJ9             | 1         | 0.51%   |
| Lenovo ThinkPad T440s 20AQ007SGE         | 1         | 0.51%   |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 0.51%   |
| Lenovo ThinkPad T440p 20AWS2T11D         | 1         | 0.51%   |
| Lenovo ThinkPad T440p 20AWA1NAUK         | 1         | 0.51%   |
| Lenovo ThinkPad T440p 20AW002VBR         | 1         | 0.51%   |
| Lenovo ThinkPad T430 23427YU             | 1         | 0.51%   |
| Lenovo ThinkPad T420 4236MBU             | 1         | 0.51%   |
| Lenovo ThinkPad T410 2537G99             | 1         | 0.51%   |
| Lenovo ThinkPad T400 2768WGB             | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 30        | 15.15%  |
| Acer Aspire            | 13        | 6.57%   |
| Dell Latitude          | 10        | 5.05%   |
| Toshiba Satellite      | 7         | 3.54%   |
| HP ProBook             | 6         | 3.03%   |
| HP Pavilion            | 6         | 3.03%   |
| Dell Inspiron          | 6         | 3.03%   |
| Lenovo IdeaPad         | 5         | 2.53%   |
| HP EliteBook           | 5         | 2.53%   |
| Unknown                | 4         | 2.02%   |
| Dell Vostro            | 3         | 1.52%   |
| ASUS TUF               | 3         | 1.52%   |
| Lenovo B590            | 2         | 1.01%   |
| HP ZBook               | 2         | 1.01%   |
| HP Stream              | 2         | 1.01%   |
| HP Laptop              | 2         | 1.01%   |
| HP Compaq              | 2         | 1.01%   |
| ASUS VivoBook          | 2         | 1.01%   |
| ASUS ROG               | 2         | 1.01%   |
| Alienware m15          | 2         | 1.01%   |
| Acer Swift             | 2         | 1.01%   |
| Acer Extensa           | 2         | 1.01%   |
| UMAX VisionBook-N12R   | 1         | 0.51%   |
| TUXEDO N7x0WU          | 1         | 0.51%   |
| Toshiba PORTEGE        | 1         | 0.51%   |
| Sony VPCSB1V9R         | 1         | 0.51%   |
| Sony VPCF23P1E         | 1         | 0.51%   |
| Sony VPCF119FX         | 1         | 0.51%   |
| Sony VPCEH2N1E         | 1         | 0.51%   |
| Sony VPCEC3S1E         | 1         | 0.51%   |
| Sony VGN-NR310FH       | 1         | 0.51%   |
| Sony SVT13115FBS       | 1         | 0.51%   |
| Sony SVE1513Q1ESI      | 1         | 0.51%   |
| Samsung R780           | 1         | 0.51%   |
| Samsung 350V5C         | 1         | 0.51%   |
| Samsung 340XAA         | 1         | 0.51%   |
| Samsung 305E4A         | 1         | 0.51%   |
| Pixus Rise             | 1         | 0.51%   |
| Panasonic CF-C1BT02EGE | 1         | 0.51%   |
| Packard Bell EasyNote  | 1         | 0.51%   |
| Notebook W65           | 1         | 0.51%   |
| MSI MS-N033            | 1         | 0.51%   |
| MSI GV62               | 1         | 0.51%   |
| MSI GP63               | 1         | 0.51%   |
| MSI Alpha              | 1         | 0.51%   |
| Medion P6669           | 1         | 0.51%   |
| Medion E6234           | 1         | 0.51%   |
| Medion E14304          | 1         | 0.51%   |
| Medion Akoya           | 1         | 0.51%   |
| Lenovo V145-15AST      | 1         | 0.51%   |
| Lenovo ThinkBook       | 1         | 0.51%   |
| Lenovo S130-11IGM      | 1         | 0.51%   |
| Lenovo Legion          | 1         | 0.51%   |
| Lenovo G400s           | 1         | 0.51%   |
| Lenovo B40-45          | 1         | 0.51%   |
| Irbis TW94             | 1         | 0.51%   |
| Intel ChiefRiver       | 1         | 0.51%   |
| HP Presario            | 1         | 0.51%   |
| HP Notebook            | 1         | 0.51%   |
| HP Mini                | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 20        | 10.1%   |
| 2018    | 19        | 9.6%    |
| 2012    | 19        | 9.6%    |
| 2010    | 19        | 9.6%    |
| 2021    | 15        | 7.58%   |
| 2013    | 15        | 7.58%   |
| 2014    | 13        | 6.57%   |
| 2016    | 12        | 6.06%   |
| 2015    | 12        | 6.06%   |
| 2019    | 10        | 5.05%   |
| 2020    | 9         | 4.55%   |
| 2008    | 9         | 4.55%   |
| 2017    | 7         | 3.54%   |
| 2009    | 6         | 3.03%   |
| 2007    | 5         | 2.53%   |
| 2006    | 3         | 1.52%   |
| 2022    | 2         | 1.01%   |
| 2005    | 2         | 1.01%   |
| Unknown | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 198       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 198       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 195       | 98.48%  |
| Yes  | 3         | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 56        | 28.14%  |
| 3.01-4.0    | 44        | 22.11%  |
| 8.01-16.0   | 39        | 19.6%   |
| 16.01-24.0  | 24        | 12.06%  |
| 1.01-2.0    | 15        | 7.54%   |
| 2.01-3.0    | 8         | 4.02%   |
| 32.01-64.0  | 6         | 3.02%   |
| 0.51-1.0    | 4         | 2.01%   |
| 24.01-32.0  | 2         | 1.01%   |
| 64.01-256.0 | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 83        | 39.15%  |
| 2.01-3.0  | 51        | 24.06%  |
| 3.01-4.0  | 29        | 13.68%  |
| 0.51-1.0  | 27        | 12.74%  |
| 4.01-8.0  | 15        | 7.08%   |
| 8.01-16.0 | 5         | 2.36%   |
| 0.01-0.5  | 2         | 0.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 144       | 71.64%  |
| 2      | 43        | 21.39%  |
| 3      | 10        | 4.98%   |
| 4      | 2         | 1%      |
| 0      | 2         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 125       | 62.81%  |
| Yes       | 74        | 37.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 85.86%  |
| No        | 28        | 14.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 96.97%  |
| No        | 6         | 3.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 72.73%  |
| No        | 54        | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 40        | 20.1%   |
| Germany     | 21        | 10.55%  |
| UK          | 11        | 5.53%   |
| Canada      | 10        | 5.03%   |
| Russia      | 8         | 4.02%   |
| Brazil      | 8         | 4.02%   |
| Slovakia    | 7         | 3.52%   |
| Netherlands | 7         | 3.52%   |
| Italy       | 7         | 3.52%   |
| Spain       | 6         | 3.02%   |
| Austria     | 6         | 3.02%   |
| India       | 5         | 2.51%   |
| France      | 5         | 2.51%   |
| Ukraine     | 4         | 2.01%   |
| Poland      | 4         | 2.01%   |
| Mexico      | 4         | 2.01%   |
| Thailand    | 3         | 1.51%   |
| Finland     | 3         | 1.51%   |
| Czechia     | 3         | 1.51%   |
| Belgium     | 3         | 1.51%   |
| Australia   | 3         | 1.51%   |
| Serbia      | 2         | 1.01%   |
| Romania     | 2         | 1.01%   |
| Portugal    | 2         | 1.01%   |
| Colombia    | 2         | 1.01%   |
| China       | 2         | 1.01%   |
| Belarus     | 2         | 1.01%   |
| Vietnam     | 1         | 0.5%    |
| Venezuela   | 1         | 0.5%    |
| Turkey      | 1         | 0.5%    |
| Syria       | 1         | 0.5%    |
| Switzerland | 1         | 0.5%    |
| Sweden      | 1         | 0.5%    |
| Philippines | 1         | 0.5%    |
| Peru        | 1         | 0.5%    |
| Norway      | 1         | 0.5%    |
| Nigeria     | 1         | 0.5%    |
| Malaysia    | 1         | 0.5%    |
| Latvia      | 1         | 0.5%    |
| Indonesia   | 1         | 0.5%    |
| Hungary     | 1         | 0.5%    |
| Greece      | 1         | 0.5%    |
| Chile       | 1         | 0.5%    |
| Azerbaijan  | 1         | 0.5%    |
| Angola      | 1         | 0.5%    |
| Algeria     | 1         | 0.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 6         | 2.93%   |
| Bratislava                | 6         | 2.93%   |
| Berlin                    | 4         | 1.95%   |
| Munich                    | 3         | 1.46%   |
| Montreal                  | 3         | 1.46%   |
| Los Angeles               | 3         | 1.46%   |
| Warsaw                    | 2         | 0.98%   |
| St Petersburg             | 2         | 0.98%   |
| Prague                    | 2         | 0.98%   |
| Patna                     | 2         | 0.98%   |
| Oxford                    | 2         | 0.98%   |
| Orange                    | 2         | 0.98%   |
| Moscow                    | 2         | 0.98%   |
| Minsk                     | 2         | 0.98%   |
| Madrid                    | 2         | 0.98%   |
| Doesburg                  | 2         | 0.98%   |
| Dnipro                    | 2         | 0.98%   |
| Buffalo                   | 2         | 0.98%   |
| Bogotá                   | 2         | 0.98%   |
| Amsterdam                 | 2         | 0.98%   |
| Zurich                    | 1         | 0.49%   |
| Xalapa                    | 1         | 0.49%   |
| Wentzville                | 1         | 0.49%   |
| Waycross                  | 1         | 0.49%   |
| Vasco da Gama             | 1         | 0.49%   |
| Vancouver                 | 1         | 0.49%   |
| Valencia                  | 1         | 0.49%   |
| Uelzen                    | 1         | 0.49%   |
| Tver                      | 1         | 0.49%   |
| Trzebinia                 | 1         | 0.49%   |
| Trivandrum                | 1         | 0.49%   |
| Tampa                     | 1         | 0.49%   |
| Taggia                    | 1         | 0.49%   |
| Tacoma                    | 1         | 0.49%   |
| Sydney                    | 1         | 0.49%   |
| Suzhou                    | 1         | 0.49%   |
| Surprise                  | 1         | 0.49%   |
| Spijkenisse               | 1         | 0.49%   |
| Siegen                    | 1         | 0.49%   |
| Shenzhen                  | 1         | 0.49%   |
| Schiedam                  | 1         | 0.49%   |
| Schaarbeek                | 1         | 0.49%   |
| Saskatoon                 | 1         | 0.49%   |
| Santa Pola                | 1         | 0.49%   |
| San Giovanni in Persiceto | 1         | 0.49%   |
| Saarlouis                 | 1         | 0.49%   |
| Rüsselsheim am Main      | 1         | 0.49%   |
| Rusko                     | 1         | 0.49%   |
| Roseville                 | 1         | 0.49%   |
| Romulus                   | 1         | 0.49%   |
| Rochester                 | 1         | 0.49%   |
| Rivne                     | 1         | 0.49%   |
| Riga                      | 1         | 0.49%   |
| Rensselaer                | 1         | 0.49%   |
| Relizane                  | 1         | 0.49%   |
| Reinbek                   | 1         | 0.49%   |
| Puerto Vallarta           | 1         | 0.49%   |
| Powder Springs            | 1         | 0.49%   |
| Postbauer-Heng            | 1         | 0.49%   |
| Portsmouth                | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 34     | 12.84%  |
| Samsung Electronics | 31        | 38     | 12.06%  |
| Seagate             | 25        | 27     | 9.73%   |
| Kingston            | 18        | 18     | 7%      |
| Crucial             | 17        | 26     | 6.61%   |
| Unknown             | 16        | 20     | 6.23%   |
| Toshiba             | 16        | 17     | 6.23%   |
| SanDisk             | 14        | 15     | 5.45%   |
| SK hynix            | 11        | 12     | 4.28%   |
| Hitachi             | 8         | 8      | 3.11%   |
| HGST                | 8         | 13     | 3.11%   |
| Intel               | 7         | 10     | 2.72%   |
| Transcend           | 4         | 4      | 1.56%   |
| PNY                 | 3         | 3      | 1.17%   |
| Micron Technology   | 3         | 7      | 1.17%   |
| LITEON              | 3         | 3      | 1.17%   |
| Dogfish             | 3         | 3      | 1.17%   |
| A-DATA Technology   | 3         | 5      | 1.17%   |
| SPCC                | 2         | 2      | 0.78%   |
| Phison              | 2         | 2      | 0.78%   |
| Netac               | 2         | 2      | 0.78%   |
| KingSpec            | 2         | 2      | 0.78%   |
| KingDian            | 2         | 2      | 0.78%   |
| Fujitsu             | 2         | 2      | 0.78%   |
| Unknown             | 2         | 2      | 0.78%   |
| ZTC                 | 1         | 1      | 0.39%   |
| Yeyian              | 1         | 1      | 0.39%   |
| Team                | 1         | 1      | 0.39%   |
| Smart               | 1         | 1      | 0.39%   |
| SABRENT             | 1         | 1      | 0.39%   |
| Phison Electronics  | 1         | 2      | 0.39%   |
| Patriot             | 1         | 1      | 0.39%   |
| OCZ                 | 1         | 1      | 0.39%   |
| LITEONIT            | 1         | 1      | 0.39%   |
| Lexar               | 1         | 1      | 0.39%   |
| Lenovo              | 1         | 1      | 0.39%   |
| KingFast            | 1         | 1      | 0.39%   |
| Intenso             | 1         | 1      | 0.39%   |
| Indilinx            | 1         | 3      | 0.39%   |
| HUAWEI              | 1         | 1      | 0.39%   |
| GOODRAM             | 1         | 1      | 0.39%   |
| Gigabyte Technology | 1         | 1      | 0.39%   |
| GeIL                | 1         | 1      | 0.39%   |
| Corsair             | 1         | 1      | 0.39%   |
| Apple               | 1         | 2      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 6         | 2.26%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.89%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.51%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 1.13%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 1.13%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.13%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.13%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 1.13%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.75%   |
| Unknown SD32G  32GB                  | 2         | 0.75%   |
| Unknown BJTD4R  32GB                 | 2         | 0.75%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.75%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.75%   |
| SK hynix HFM512GDJTNI-82A0A 512GB    | 2         | 0.75%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.75%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.75%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.75%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.75%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.75%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.75%   |
| Intel SSDSA2BW120G3H 120GB           | 2         | 0.75%   |
| Intel SSDPEKNW512G8 512GB            | 2         | 0.75%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.75%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.75%   |
| Dogfish SSD 128GB                    | 2         | 0.75%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.75%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.75%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.75%   |
| A-DATA SP600 32GB SSD                | 2         | 0.75%   |
| Unknown                              | 2         | 0.75%   |
| ZTC SM201-256G                       | 1         | 0.38%   |
| Yeyian VALK 1000 120GB SSD           | 1         | 0.38%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.38%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.38%   |
| WDC WD7500BPVX-00JC3T0 752GB         | 1         | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.38%   |
| WDC WD5000LPVX-08V0TT5 500GB         | 1         | 0.38%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.38%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.38%   |
| WDC WD5000BPVT-60HXZT3 500GB         | 1         | 0.38%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 0.38%   |
| WDC WD3200LPVT-08G33T1 320GB         | 1         | 0.38%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.38%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.38%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 0.38%   |
| WDC WD2500BEVE-00WZT0 250GB          | 1         | 0.38%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.38%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.38%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.38%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 0.38%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 0.38%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.38%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.38%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.38%   |
| WDC PC SN730 NVMe 1024GB             | 1         | 0.38%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB   | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 27     | 31.25%  |
| WDC                 | 23        | 23     | 28.75%  |
| Toshiba             | 10        | 11     | 12.5%   |
| Hitachi             | 8         | 8      | 10%     |
| HGST                | 8         | 13     | 10%     |
| Samsung Electronics | 3         | 4      | 3.75%   |
| Fujitsu             | 2         | 2      | 2.5%    |
| SABRENT             | 1         | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 24     | 16.24%  |
| Kingston            | 16        | 16     | 13.68%  |
| Crucial             | 16        | 24     | 13.68%  |
| SanDisk             | 13        | 14     | 11.11%  |
| Transcend           | 4         | 4      | 3.42%   |
| WDC                 | 3         | 3      | 2.56%   |
| SK hynix            | 3         | 3      | 2.56%   |
| PNY                 | 3         | 3      | 2.56%   |
| LITEON              | 3         | 3      | 2.56%   |
| Intel               | 3         | 6      | 2.56%   |
| Dogfish             | 3         | 3      | 2.56%   |
| A-DATA Technology   | 3         | 5      | 2.56%   |
| Toshiba             | 2         | 2      | 1.71%   |
| SPCC                | 2         | 2      | 1.71%   |
| Netac               | 2         | 2      | 1.71%   |
| Micron Technology   | 2         | 6      | 1.71%   |
| KingSpec            | 2         | 2      | 1.71%   |
| KingDian            | 2         | 2      | 1.71%   |
| ZTC                 | 1         | 1      | 0.85%   |
| Yeyian              | 1         | 1      | 0.85%   |
| Team                | 1         | 1      | 0.85%   |
| Smart               | 1         | 1      | 0.85%   |
| Phison              | 1         | 1      | 0.85%   |
| Patriot             | 1         | 1      | 0.85%   |
| OCZ                 | 1         | 1      | 0.85%   |
| LITEONIT            | 1         | 1      | 0.85%   |
| KingFast            | 1         | 1      | 0.85%   |
| Intenso             | 1         | 1      | 0.85%   |
| Indilinx            | 1         | 3      | 0.85%   |
| GOODRAM             | 1         | 1      | 0.85%   |
| Gigabyte Technology | 1         | 1      | 0.85%   |
| GeIL                | 1         | 1      | 0.85%   |
| Corsair             | 1         | 1      | 0.85%   |
| Apple               | 1         | 2      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 101       | 143    | 42.8%   |
| HDD     | 79        | 89     | 33.47%  |
| NVMe    | 35        | 44     | 14.83%  |
| MMC     | 20        | 24     | 8.47%   |
| Unknown | 1         | 1      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 154       | 230    | 72.64%  |
| NVMe | 35        | 44     | 16.51%  |
| MMC  | 20        | 24     | 9.43%   |
| SAS  | 3         | 3      | 1.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 129       | 172    | 73.71%  |
| 0.51-1.0   | 42        | 56     | 24%     |
| 1.01-2.0   | 3         | 3      | 1.71%   |
| 3.01-4.0   | 1         | 1      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 66        | 32.51%  |
| 251-500        | 33        | 16.26%  |
| 501-1000       | 31        | 15.27%  |
| 51-100         | 28        | 13.79%  |
| 21-50          | 18        | 8.87%   |
| 1-20           | 12        | 5.91%   |
| 1001-2000      | 8         | 3.94%   |
| More than 3000 | 3         | 1.48%   |
| 2001-3000      | 2         | 0.99%   |
| Unknown        | 2         | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 88        | 42.31%  |
| 21-50          | 35        | 16.83%  |
| 51-100         | 29        | 13.94%  |
| 101-250        | 24        | 11.54%  |
| 251-500        | 16        | 7.69%   |
| 501-1000       | 9         | 4.33%   |
| 1001-2000      | 3         | 1.44%   |
| More than 3000 | 2         | 0.96%   |
| Unknown        | 2         | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 9.38%   |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 3.13%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 3.13%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 3.13%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 3.13%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 3.13%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 3.13%   |
| Toshiba MK7575GSX 752GB                      | 1         | 2      | 3.13%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 3.13%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 3.13%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 3.13%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 3.13%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 3.13%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 3.13%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 3.13%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 3.13%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 3.13%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 3.13%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 3      | 3.13%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 3.13%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 3.13%   |
| Hitachi HTS543216L9SA02 160GB                | 1         | 1      | 3.13%   |
| Hitachi HTS542516K9SA00 160GB                | 1         | 1      | 3.13%   |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 3.13%   |
| HGST HTS545032A7E380 320GB                   | 1         | 1      | 3.13%   |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 3.13%   |
| Fujitsu MHZ2160BH G2 160GB                   | 1         | 1      | 3.13%   |
| Crucial CT512M550SSD1 512GB                  | 1         | 1      | 3.13%   |
| A-DATA Technology SU650 240GB SSD            | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 25%     |
| WDC                 | 6         | 6      | 18.75%  |
| Hitachi             | 4         | 4      | 12.5%   |
| Toshiba             | 3         | 4      | 9.38%   |
| HGST                | 3         | 4      | 9.38%   |
| Samsung Electronics | 2         | 3      | 6.25%   |
| SanDisk             | 1         | 1      | 3.13%   |
| Kingston            | 1         | 1      | 3.13%   |
| Indilinx            | 1         | 3      | 3.13%   |
| Fujitsu             | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 30.77%  |
| WDC                 | 6         | 6      | 23.08%  |
| Hitachi             | 4         | 4      | 15.38%  |
| Toshiba             | 3         | 4      | 11.54%  |
| HGST                | 3         | 4      | 11.54%  |
| Samsung Electronics | 1         | 2      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 29     | 81.25%  |
| SSD  | 6         | 8      | 18.75%  |

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
| Works    | 160       | 236    | 74.07%  |
| Malfunc  | 31        | 37     | 14.35%  |
| Detected | 25        | 28     | 11.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 150       | 70.42%  |
| AMD                          | 20        | 9.39%   |
| Samsung Electronics          | 10        | 4.69%   |
| SanDisk                      | 8         | 3.76%   |
| SK hynix                     | 7         | 3.29%   |
| Nvidia                       | 5         | 2.35%   |
| Toshiba America Info Systems | 2         | 0.94%   |
| Phison Electronics           | 2         | 0.94%   |
| KIOXIA                       | 2         | 0.94%   |
| Kingston Technology Company  | 2         | 0.94%   |
| Silicon Motion               | 1         | 0.47%   |
| Silicon Image                | 1         | 0.47%   |
| Micron/Crucial Technology    | 1         | 0.47%   |
| Micron Technology            | 1         | 0.47%   |
| Lenovo                       | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 9.17%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 18        | 7.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 15        | 6.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 6.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 5.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 3.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 3.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 2.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 2.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.75%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.75%   |
| SK hynix BC511                                                                   | 3         | 1.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.31%   |
| Intel SSD 660P Series                                                            | 3         | 1.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.31%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.87%   |
| SK hynix Gold P31 SSD                                                            | 2         | 0.87%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.87%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.87%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.87%   |
| Nvidia MCP67 AHCI Controller                                                     | 2         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.87%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.44%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.44%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.44%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.44%   |
| Samsung Electronics SATA controller                                              | 1         | 0.44%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.44%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.44%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.44%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.44%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.44%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.44%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.44%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.44%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.44%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.44%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.44%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.44%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.44%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 147       | 67.12%  |
| NVMe | 35        | 15.98%  |
| IDE  | 20        | 9.13%   |
| RAID | 17        | 7.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 168       | 84.85%  |
| AMD    | 30        | 15.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 3.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 2.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 2.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.02%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 2.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.52%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 3         | 1.52%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.52%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.01%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.01%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.01%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.01%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 1.01%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.01%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 1.01%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.01%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.01%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 1.01%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 1.01%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.01%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.01%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.01%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 1.01%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 2         | 1.01%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.01%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.01%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 1.01%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.51%   |
| Intel Pentium M processor 1.80GHz             | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.51%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.51%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.51%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.51%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 0.51%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.51%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.51%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.51%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.51%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.51%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 0.51%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.51%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.51%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.51%   |
| Intel Core i7 CPU M 640 @ 2.80GHz             | 1         | 0.51%   |
| Intel Core i7 CPU L 620 @ 2.00GHz             | 1         | 0.51%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 50        | 25.25%  |
| Intel Core i7           | 46        | 23.23%  |
| Intel Celeron           | 21        | 10.61%  |
| Intel Core i3           | 14        | 7.07%   |
| Intel Atom              | 11        | 5.56%   |
| Intel Core 2 Duo        | 9         | 4.55%   |
| AMD Ryzen 7             | 8         | 4.04%   |
| Other                   | 7         | 3.54%   |
| Intel Pentium           | 3         | 1.52%   |
| AMD Turion 64 X2 Mobile | 3         | 1.52%   |
| AMD Ryzen 5             | 3         | 1.52%   |
| AMD A6                  | 3         | 1.52%   |
| AMD Ryzen 3             | 2         | 1.01%   |
| AMD E1                  | 2         | 1.01%   |
| AMD E                   | 2         | 1.01%   |
| AMD A8                  | 2         | 1.01%   |
| AMD A4                  | 2         | 1.01%   |
| Intel Pentium Silver    | 1         | 0.51%   |
| Intel Pentium M         | 1         | 0.51%   |
| Intel Pentium Dual-Core | 1         | 0.51%   |
| Intel Genuine           | 1         | 0.51%   |
| Intel Core Duo          | 1         | 0.51%   |
| Intel Core 2            | 1         | 0.51%   |
| Intel Celeron M         | 1         | 0.51%   |
| AMD Sempron             | 1         | 0.51%   |
| AMD Ryzen 9             | 1         | 0.51%   |
| AMD Athlon 64 X2        | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 118       | 59.6%   |
| 4      | 53        | 26.77%  |
| 1      | 10        | 5.05%   |
| 8      | 8         | 4.04%   |
| 6      | 8         | 4.04%   |
| 14     | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 198       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 137       | 69.19%  |
| 1      | 61        | 30.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 189       | 94.97%  |
| 32-bit         | 10        | 5.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 11.5%   |
| 0x206a7    | 18        | 9%      |
| 0x306a9    | 17        | 8.5%    |
| 0x406e3    | 9         | 4.5%    |
| 0x306c3    | 8         | 4%      |
| 0x20655    | 8         | 4%      |
| 0x40651    | 7         | 3.5%    |
| 0x906ea    | 5         | 2.5%    |
| 0x806ea    | 5         | 2.5%    |
| 0x406c4    | 5         | 2.5%    |
| 0x806e9    | 4         | 2%      |
| 0x806c1    | 4         | 2%      |
| 0x706a1    | 4         | 2%      |
| 0x306d4    | 4         | 2%      |
| 0x30678    | 4         | 2%      |
| 0x20652    | 4         | 2%      |
| 0x106c2    | 4         | 2%      |
| 0xa0652    | 3         | 1.5%    |
| 0x1067a    | 3         | 1.5%    |
| 0x10676    | 3         | 1.5%    |
| 0x0a50000c | 3         | 1.5%    |
| 0x03000027 | 3         | 1.5%    |
| 0x906e9    | 2         | 1%      |
| 0x806ec    | 2         | 1%      |
| 0x706e5    | 2         | 1%      |
| 0x706a8    | 2         | 1%      |
| 0x6fd      | 2         | 1%      |
| 0x506e3    | 2         | 1%      |
| 0x506c9    | 2         | 1%      |
| 0x30661    | 2         | 1%      |
| 0x106e5    | 2         | 1%      |
| 0x106ca    | 2         | 1%      |
| 0x08608103 | 2         | 1%      |
| 0x08108102 | 2         | 1%      |
| 0x0810100b | 2         | 1%      |
| 0x07030105 | 2         | 1%      |
| 0x0700010f | 2         | 1%      |
| 0x906ed    | 1         | 0.5%    |
| 0x906a3    | 1         | 0.5%    |
| 0x806eb    | 1         | 0.5%    |
| 0x806d1    | 1         | 0.5%    |
| 0x6fb      | 1         | 0.5%    |
| 0x6f2      | 1         | 0.5%    |
| 0x6ec      | 1         | 0.5%    |
| 0x6e8      | 1         | 0.5%    |
| 0x6d8      | 1         | 0.5%    |
| 0x6d6      | 1         | 0.5%    |
| 0x406c3    | 1         | 0.5%    |
| 0x10661    | 1         | 0.5%    |
| 0x0a50000b | 1         | 0.5%    |
| 0x08600106 | 1         | 0.5%    |
| 0x08600104 | 1         | 0.5%    |
| 0x08108109 | 1         | 0.5%    |
| 0x08101007 | 1         | 0.5%    |
| 0x07030104 | 1         | 0.5%    |
| 0x06006705 | 1         | 0.5%    |
| 0x05000119 | 1         | 0.5%    |
| 0x0500010d | 1         | 0.5%    |
| 0x02000057 | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 11.62%  |
| SandyBridge      | 22        | 11.11%  |
| IvyBridge        | 19        | 9.6%    |
| Haswell          | 15        | 7.58%   |
| Westmere         | 13        | 6.57%   |
| Skylake          | 12        | 6.06%   |
| Silvermont       | 12        | 6.06%   |
| Bonnell          | 8         | 4.04%   |
| Penryn           | 7         | 3.54%   |
| Goldmont plus    | 6         | 3.03%   |
| TigerLake        | 5         | 2.53%   |
| Core             | 5         | 2.53%   |
| Broadwell        | 5         | 2.53%   |
| Zen 3            | 4         | 2.02%   |
| P6               | 4         | 2.02%   |
| K8 Hammer        | 4         | 2.02%   |
| Icelake          | 4         | 2.02%   |
| Zen+             | 3         | 1.52%   |
| Zen              | 3         | 1.52%   |
| Puma             | 3         | 1.52%   |
| K10 Llano        | 3         | 1.52%   |
| CometLake        | 3         | 1.52%   |
| Zen 2            | 2         | 1.01%   |
| Nehalem          | 2         | 1.01%   |
| Jaguar           | 2         | 1.01%   |
| Goldmont         | 2         | 1.01%   |
| Bobcat           | 2         | 1.01%   |
| Unknown          | 2         | 1.01%   |
| K8 & K10 hybrid  | 1         | 0.51%   |
| Excavator        | 1         | 0.51%   |
| Alderlake Hybrid | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 151       | 62.14%  |
| Nvidia | 48        | 19.75%  |
| AMD    | 44        | 18.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 7.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 7.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 3.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.73%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.34%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.95%   |
| Intel HD Graphics 620                                                                    | 5         | 1.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.56%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.17%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.17%   |
| Intel HD Graphics 530                                                                    | 3         | 1.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.17%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 3         | 1.17%   |
| AMD Cezanne                                                                              | 3         | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.78%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.78%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.78%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.78%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.78%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                                 | 2         | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.78%   |
| Intel HD Graphics 630                                                                    | 2         | 0.78%   |
| Intel HD Graphics 500                                                                    | 2         | 0.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.78%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.78%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.78%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.78%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.78%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                                  | 2         | 0.78%   |
| AMD Renoir                                                                               | 2         | 0.78%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.78%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.78%   |
| AMD Lucienne                                                                             | 2         | 0.78%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.39%   |
| Nvidia TU117M                                                                            | 1         | 0.39%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.39%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 1         | 0.39%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.39%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.39%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.39%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.39%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.39%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 110       | 55.56%  |
| Intel + Nvidia | 32        | 16.16%  |
| 1 x AMD        | 26        | 13.13%  |
| 1 x Nvidia     | 12        | 6.06%   |
| Intel + AMD    | 9         | 4.55%   |
| 2 x AMD        | 5         | 2.53%   |
| AMD + Nvidia   | 4         | 2.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 181       | 90.5%   |
| Proprietary | 14        | 7%      |
| Unknown     | 5         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 148       | 74.37%  |
| 0.01-0.5   | 25        | 12.56%  |
| 1.01-2.0   | 12        | 6.03%   |
| 0.51-1.0   | 12        | 6.03%   |
| 7.01-8.0   | 1         | 0.5%    |
| 3.01-4.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 40        | 18.87%  |
| LG Display              | 32        | 15.09%  |
| Chimei Innolux          | 30        | 14.15%  |
| Samsung Electronics     | 24        | 11.32%  |
| BOE                     | 18        | 8.49%   |
| Lenovo                  | 10        | 4.72%   |
| Chi Mei Optoelectronics | 10        | 4.72%   |
| PANDA                   | 6         | 2.83%   |
| InfoVision              | 4         | 1.89%   |
| HannStar                | 4         | 1.89%   |
| Dell                    | 4         | 1.89%   |
| Sharp                   | 3         | 1.42%   |
| LG Philips              | 3         | 1.42%   |
| Hewlett-Packard         | 3         | 1.42%   |
| Apple                   | 3         | 1.42%   |
| Ancor Communications    | 3         | 1.42%   |
| Sony                    | 2         | 0.94%   |
| Philips                 | 2         | 0.94%   |
| Goldstar                | 2         | 0.94%   |
| CPT                     | 2         | 0.94%   |
| Vizio                   | 1         | 0.47%   |
| Sunplus                 | 1         | 0.47%   |
| Panasonic               | 1         | 0.47%   |
| LTM                     | 1         | 0.47%   |
| InnoLux Display         | 1         | 0.47%   |
| AOC                     | 1         | 0.47%   |
| Acer                    | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 4         | 1.89%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 1.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.42%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.94%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.94%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.94%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.94%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 0.94%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.94%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.94%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch            | 2         | 0.94%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                        | 1         | 0.47%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 0.47%   |
| Sony LCD Monitor SNY06FA 1600x900 310x170mm 13.9-inch                    | 1         | 0.47%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 0.47%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch     | 1         | 0.47%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 340x190mm 15.3-inch        | 1         | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.47%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.47%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.47%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch                | 1         | 0.47%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 0.47%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 0.47%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                  | 1         | 0.47%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 1         | 0.47%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                        | 1         | 0.47%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 0.47%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 0.47%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 0.47%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 0.47%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 0.47%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch              | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 76        | 37.25%  |
| 1366x768 (WXGA)    | 76        | 37.25%  |
| 1600x900 (HD+)     | 11        | 5.39%   |
| 1280x800 (WXGA)    | 10        | 4.9%    |
| 1024x600           | 6         | 2.94%   |
| 3840x2160 (4K)     | 5         | 2.45%   |
| 1440x900 (WXGA+)   | 5         | 2.45%   |
| 1280x1024 (SXGA)   | 3         | 1.47%   |
| 2560x1440 (QHD)    | 2         | 0.98%   |
| 2560x1080          | 2         | 0.98%   |
| 1680x1050 (WSXGA+) | 2         | 0.98%   |
| 1400x1050          | 2         | 0.98%   |
| 3840x2400          | 1         | 0.49%   |
| 2256x1504          | 1         | 0.49%   |
| 2160x1440          | 1         | 0.49%   |
| 1920x1200 (WUXGA)  | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 90        | 42.65%  |
| 13     | 30        | 14.22%  |
| 14     | 26        | 12.32%  |
| 17     | 13        | 6.16%   |
| 11     | 7         | 3.32%   |
| 10     | 7         | 3.32%   |
| 12     | 6         | 2.84%   |
| 24     | 5         | 2.37%   |
| 23     | 5         | 2.37%   |
| 19     | 5         | 2.37%   |
| 27     | 4         | 1.9%    |
| 34     | 2         | 0.95%   |
| 20     | 2         | 0.95%   |
| 18     | 2         | 0.95%   |
| 84     | 1         | 0.47%   |
| 43     | 1         | 0.47%   |
| 40     | 1         | 0.47%   |
| 37     | 1         | 0.47%   |
| 32     | 1         | 0.47%   |
| 21     | 1         | 0.47%   |
| 16     | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 127       | 60.19%  |
| 201-300     | 34        | 16.11%  |
| 351-400     | 23        | 10.9%   |
| 501-600     | 14        | 6.64%   |
| 401-500     | 6         | 2.84%   |
| 701-800     | 3         | 1.42%   |
| 801-900     | 2         | 0.95%   |
| 1501-2000   | 1         | 0.47%   |
| 901-1000    | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 163       | 83.59%  |
| 16/10 | 20        | 10.26%  |
| 5/4   | 4         | 2.05%   |
| 3/2   | 4         | 2.05%   |
| 4/3   | 2         | 1.03%   |
| 21/9  | 2         | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 42.65%  |
| 81-90          | 47        | 22.27%  |
| 121-130        | 12        | 5.69%   |
| 71-80          | 9         | 4.27%   |
| 201-250        | 9         | 4.27%   |
| 51-60          | 7         | 3.32%   |
| 41-50          | 7         | 3.32%   |
| 151-200        | 7         | 3.32%   |
| 61-70          | 6         | 2.84%   |
| 301-350        | 4         | 1.9%    |
| 351-500        | 3         | 1.42%   |
| 501-1000       | 3         | 1.42%   |
| 251-300        | 2         | 0.95%   |
| 141-150        | 2         | 0.95%   |
| More than 1000 | 1         | 0.47%   |
| 131-140        | 1         | 0.47%   |
| 111-120        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 76        | 36.89%  |
| 121-160       | 75        | 36.41%  |
| 51-100        | 43        | 20.87%  |
| 161-240       | 9         | 4.37%   |
| More than 240 | 3         | 1.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 167       | 83.92%  |
| 2     | 27        | 13.57%  |
| 0     | 3         | 1.51%   |
| 3     | 2         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 104       | 32.5%   |
| Realtek Semiconductor             | 97        | 30.31%  |
| Qualcomm Atheros                  | 58        | 18.13%  |
| Broadcom                          | 19        | 5.94%   |
| Marvell Technology Group          | 6         | 1.88%   |
| Nvidia                            | 5         | 1.56%   |
| MediaTek                          | 4         | 1.25%   |
| TP-Link                           | 3         | 0.94%   |
| Huawei Technologies               | 3         | 0.94%   |
| Broadcom Limited                  | 3         | 0.94%   |
| Sierra Wireless                   | 2         | 0.63%   |
| Ralink Technology                 | 2         | 0.63%   |
| Ralink                            | 2         | 0.63%   |
| Ericsson Business Mobile Networks | 2         | 0.63%   |
| Attansic Technology               | 2         | 0.63%   |
| Samsung Electronics               | 1         | 0.31%   |
| Qualcomm                          | 1         | 0.31%   |
| JMicron Technology                | 1         | 0.31%   |
| Hewlett-Packard                   | 1         | 0.31%   |
| Google                            | 1         | 0.31%   |
| Dell                              | 1         | 0.31%   |
| ASUSTek Computer                  | 1         | 0.31%   |
| ASIX Electronics                  | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 63        | 16.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 4.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 15        | 3.86%   |
| Intel Wireless 7260                                                            | 11        | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 2.06%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 2.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 7         | 1.8%    |
| Intel Centrino Advanced-N 6200                                                 | 7         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 6         | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 6         | 1.54%   |
| Intel Wireless 8265 / 8275                                                     | 6         | 1.54%   |
| Intel Wireless 8260                                                            | 6         | 1.54%   |
| Intel Wireless 3165                                                            | 6         | 1.54%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 5         | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 1.29%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 5         | 1.29%   |
| Intel Wireless 7265                                                            | 5         | 1.29%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.29%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.03%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.03%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.03%   |
| Intel Centrino Advanced-N 6235                                                 | 4         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 4         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 3         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 0.77%   |
| Intel Wi-Fi 6 AX201                                                            | 3         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 3         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 3         | 0.77%   |
| Intel Centrino Wireless-N 2230                                                 | 3         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 3         | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 0.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.51%   |
| Realtek 802.11n WLAN Adapter                                                   | 2         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 2         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.51%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.51%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.51%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.51%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 2         | 0.51%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 2         | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 0.51%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 0.51%   |
| Intel Centrino Ultimate-N 6300                                                 | 2         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.51%   |
| Ericsson Business Mobile Networks F5521gw                                      | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 99        | 48.29%  |
| Qualcomm Atheros      | 46        | 22.44%  |
| Realtek Semiconductor | 32        | 15.61%  |
| Broadcom              | 13        | 6.34%   |
| MediaTek              | 3         | 1.46%   |
| TP-Link               | 2         | 0.98%   |
| Sierra Wireless       | 2         | 0.98%   |
| Ralink Technology     | 2         | 0.98%   |
| Ralink                | 2         | 0.98%   |
| Broadcom Limited      | 2         | 0.98%   |
| Hewlett-Packard       | 1         | 0.49%   |
| ASUSTek Computer      | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 15        | 7.28%   |
| Intel Wireless 7260                                                                           | 11        | 5.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 9         | 4.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 7         | 3.4%    |
| Intel Centrino Advanced-N 6200                                                                | 7         | 3.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 2.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 6         | 2.91%   |
| Intel Wireless 8265 / 8275                                                                    | 6         | 2.91%   |
| Intel Wireless 8260                                                                           | 6         | 2.91%   |
| Intel Wireless 3165                                                                           | 6         | 2.91%   |
| Intel Wi-Fi 6 AX200                                                                           | 6         | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5         | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 2.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 5         | 2.43%   |
| Intel Wireless 7265                                                                           | 5         | 2.43%   |
| Intel Centrino Advanced-N 6235                                                                | 4         | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 1.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3         | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 1.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 3         | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 1.46%   |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 1.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 3         | 1.46%   |
| Intel Centrino Wireless-N 2230                                                                | 3         | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 3         | 1.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 0.97%   |
| Realtek 802.11n WLAN Adapter                                                                  | 2         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2         | 0.97%   |
| Intel Wireless-AC 9260                                                                        | 2         | 0.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 2         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2         | 0.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 2         | 0.97%   |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 0.97%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 2         | 0.97%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                                           | 1         | 0.49%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.49%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.49%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.49%   |
| Ralink RT2070 Wireless Adapter                                                                | 1         | 0.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.49%   |
| Intel Wireless 3160                                                                           | 1         | 0.49%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1         | 0.49%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                                      | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 84        | 48%     |
| Intel                    | 43        | 24.57%  |
| Qualcomm Atheros         | 20        | 11.43%  |
| Broadcom                 | 7         | 4%      |
| Marvell Technology Group | 6         | 3.43%   |
| Nvidia                   | 5         | 2.86%   |
| Attansic Technology      | 2         | 1.14%   |
| TP-Link                  | 1         | 0.57%   |
| Samsung Electronics      | 1         | 0.57%   |
| Qualcomm                 | 1         | 0.57%   |
| MediaTek                 | 1         | 0.57%   |
| JMicron Technology       | 1         | 0.57%   |
| Huawei Technologies      | 1         | 0.57%   |
| Broadcom Limited         | 1         | 0.57%   |
| ASIX Electronics         | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 63        | 35.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 9.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 4.52%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 4.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.82%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 2.26%   |
| Intel Ethernet Connection I219-V                                               | 4         | 2.26%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 2.26%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.13%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.13%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.13%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 1.13%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 1.13%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.13%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.13%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 1.13%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 1.13%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.56%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                               | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.56%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.56%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.56%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.56%   |
| MediaTek RMX3085                                                               | 1         | 0.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.56%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.56%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.56%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.56%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.56%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.56%   |
| Huawei LYA-L09                                                                 | 1         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.56%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.56%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 192       | 52.17%  |
| Ethernet | 170       | 46.2%   |
| Modem    | 5         | 1.36%   |
| Unknown  | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 155       | 75.24%  |
| Ethernet | 50        | 24.27%  |
| Unknown  | 1         | 0.49%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 160       | 80.81%  |
| 1     | 33        | 16.67%  |
| 0     | 5         | 2.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 174       | 87%     |
| Yes  | 26        | 13%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 43.24%  |
| Realtek Semiconductor           | 14        | 9.46%   |
| Qualcomm Atheros Communications | 14        | 9.46%   |
| Broadcom                        | 14        | 9.46%   |
| IMC Networks                    | 8         | 5.41%   |
| Cambridge Silicon Radio         | 7         | 4.73%   |
| Lite-On Technology              | 6         | 4.05%   |
| Hewlett-Packard                 | 5         | 3.38%   |
| Foxconn / Hon Hai               | 4         | 2.7%    |
| Toshiba                         | 3         | 2.03%   |
| Dell                            | 3         | 2.03%   |
| Apple                           | 3         | 2.03%   |
| Ralink                          | 1         | 0.68%   |
| ASUSTek Computer                | 1         | 0.68%   |
| Alps Electric                   | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 34        | 22.97%  |
| Intel AX201 Bluetooth                                                               | 9         | 6.08%   |
| Realtek Bluetooth Radio                                                             | 7         | 4.73%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 4.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 4.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 4.05%   |
| Intel AX200 Bluetooth                                                               | 6         | 4.05%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.38%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 3.38%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.7%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 2.7%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 2.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.03%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.03%   |
| Intel Bluetooth Device                                                              | 3         | 2.03%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.35%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.35%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.35%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.35%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.35%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.35%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.68%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.68%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.68%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.68%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.68%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.68%   |
| Lite-On Wireless_Device                                                             | 1         | 0.68%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.68%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.68%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.68%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.68%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.68%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.68%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.68%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.68%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.68%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.68%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.68%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.68%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.68%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 164       | 68.33%  |
| AMD                   | 34        | 14.17%  |
| Nvidia                | 32        | 13.33%  |
| GN Netcom             | 2         | 0.83%   |
| C-Media Electronics   | 2         | 0.83%   |
| Texas Instruments     | 1         | 0.42%   |
| SteelSeries ApS       | 1         | 0.42%   |
| Realtek Semiconductor | 1         | 0.42%   |
| Plantronics           | 1         | 0.42%   |
| Mark of the Unicorn   | 1         | 0.42%   |
| FIFINE 683 Microphone | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 8.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 7.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 6.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 5.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 4.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.53%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.47%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.77%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.77%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.06%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.06%   |
| Nvidia Audio device                                                                               | 3         | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.06%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.71%   |
| Nvidia MCP67 High Definition Audio                                                                | 2         | 0.71%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.71%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 2         | 0.71%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.71%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.71%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.35%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.35%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.35%   |
| Plantronics BT600                                                                                 | 1         | 0.35%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.35%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.35%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.35%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.35%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Mark of the Unicorn M Series                                                                      | 1         | 0.35%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.35%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.35%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 56        | 23.53%  |
| SK hynix            | 48        | 20.17%  |
| Unknown             | 30        | 12.61%  |
| Micron Technology   | 26        | 10.92%  |
| Kingston            | 23        | 9.66%   |
| Crucial             | 11        | 4.62%   |
| Ramaxel Technology  | 6         | 2.52%   |
| Unknown (ABCD)      | 5         | 2.1%    |
| A-DATA Technology   | 5         | 2.1%    |
| Smart               | 4         | 1.68%   |
| Transcend           | 3         | 1.26%   |
| Nanya Technology    | 3         | 1.26%   |
| Elpida              | 3         | 1.26%   |
| Corsair             | 3         | 1.26%   |
| Teikon              | 2         | 0.84%   |
| Unknown             | 2         | 0.84%   |
| Unknown (F301)      | 1         | 0.42%   |
| TRS STAR            | 1         | 0.42%   |
| Team                | 1         | 0.42%   |
| PNY                 | 1         | 0.42%   |
| Patriot             | 1         | 0.42%   |
| High Bridge         | 1         | 0.42%   |
| Avant               | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 2.29%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.91%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 1.53%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 4         | 1.53%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 4         | 1.53%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 1.53%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 1.53%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.15%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.15%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 3         | 1.15%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 1.15%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.76%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.76%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 2         | 0.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.76%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.76%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.76%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.76%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.76%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.76%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.76%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 2         | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.76%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.76%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.76%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.76%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.76%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.76%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.76%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 2         | 0.76%   |
| Kingston RAM HP16D3LS1KEGR/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| Unknown                                                          | 2         | 0.76%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.38%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DRAM                               | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                        | 1         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.38%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.38%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.38%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 1         | 0.38%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.38%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 102       | 51.26%  |
| DDR4    | 58        | 29.15%  |
| DDR2    | 16        | 8.04%   |
| LPDDR4  | 8         | 4.02%   |
| SDRAM   | 4         | 2.01%   |
| DDR     | 4         | 2.01%   |
| DRAM    | 3         | 1.51%   |
| LPDDR3  | 2         | 1.01%   |
| DDR5    | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 188       | 94.95%  |
| Row Of Chips | 6         | 3.03%   |
| Chip         | 3         | 1.52%   |
| DIMM         | 1         | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 93        | 41.33%  |
| 8192  | 62        | 27.56%  |
| 2048  | 43        | 19.11%  |
| 16384 | 13        | 5.78%   |
| 1024  | 13        | 5.78%   |
| 32768 | 1         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 62        | 28.7%   |
| 2667    | 25        | 11.57%  |
| 1334    | 22        | 10.19%  |
| 3200    | 17        | 7.87%   |
| 2400    | 17        | 7.87%   |
| Unknown | 15        | 6.94%   |
| 1333    | 14        | 6.48%   |
| 667     | 10        | 4.63%   |
| 2133    | 8         | 3.7%    |
| 1067    | 6         | 2.78%   |
| 800     | 4         | 1.85%   |
| 4199    | 3         | 1.39%   |
| 3266    | 3         | 1.39%   |
| 4267    | 2         | 0.93%   |
| 1867    | 2         | 0.93%   |
| 533     | 2         | 0.93%   |
| 8400    | 1         | 0.46%   |
| 4800    | 1         | 0.46%   |
| 1777    | 1         | 0.46%   |
| 166     | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 33.33%  |
| HP LaserJet P2055 series           | 1         | 33.33%  |
| HP LaserJet 1022                   | 1         | 33.33%  |

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
| Chicony Electronics                    | 41        | 25.47%  |
| Acer                                   | 15        | 9.32%   |
| Realtek Semiconductor                  | 14        | 8.7%    |
| Sunplus Innovation Technology          | 13        | 8.07%   |
| Microdia                               | 10        | 6.21%   |
| IMC Networks                           | 9         | 5.59%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.59%   |
| Suyin                                  | 7         | 4.35%   |
| Lite-On Technology                     | 7         | 4.35%   |
| Quanta                                 | 5         | 3.11%   |
| Lenovo                                 | 5         | 3.11%   |
| Z-Star Microelectronics                | 3         | 1.86%   |
| Syntek                                 | 3         | 1.86%   |
| Ricoh                                  | 3         | 1.86%   |
| Silicon Motion                         | 2         | 1.24%   |
| Luxvisions Innotech Limited            | 2         | 1.24%   |
| Alcor Micro                            | 2         | 1.24%   |
| Y Media                                | 1         | 0.62%   |
| Xiongmai                               | 1         | 0.62%   |
| WaveRider Communications               | 1         | 0.62%   |
| Samsung Electronics                    | 1         | 0.62%   |
| Primax Electronics                     | 1         | 0.62%   |
| Logitech                               | 1         | 0.62%   |
| Importek                               | 1         | 0.62%   |
| icSpring                               | 1         | 0.62%   |
| Goodong Industry                       | 1         | 0.62%   |
| Cubeternet                             | 1         | 0.62%   |
| Apple                                  | 1         | 0.62%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 5.59%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 3.11%   |
| Lite-On Integrated Camera                                   | 4         | 2.48%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 2.48%   |
| Chicony USB 2.0 Camera                                      | 4         | 2.48%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 2.48%   |
| Acer BisonCam, NB Pro                                       | 4         | 2.48%   |
| Syntek EasyCamera                                           | 3         | 1.86%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 1.86%   |
| Realtek Integrated_Webcam_HD                                | 3         | 1.86%   |
| Chicony HP Truevision HD camera                             | 3         | 1.86%   |
| Sunplus HD WebCam                                           | 2         | 1.24%   |
| Sunplus ASUS USB2.0 Webcam                                  | 2         | 1.24%   |
| Ricoh USB2.0 Camera                                         | 2         | 1.24%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.24%   |
| Realtek USB Camera                                          | 2         | 1.24%   |
| Quanta VGA WebCam                                           | 2         | 1.24%   |
| Quanta HD User Facing                                       | 2         | 1.24%   |
| Microdia USB 2.0 Camera                                     | 2         | 1.24%   |
| Microdia Integrated Webcam                                  | 2         | 1.24%   |
| Lite-On HP HD Camera                                        | 2         | 1.24%   |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 1.24%   |
| Lenovo Integrated Webcam                                    | 2         | 1.24%   |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 1.24%   |
| Chicony HD WebCam                                           | 2         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 1.24%   |
| Acer SunplusIT INC. Integrated Camera                       | 2         | 1.24%   |
| Acer Lenovo Integrated Webcam                               | 2         | 1.24%   |
| Acer Lenovo EasyCamera                                      | 2         | 1.24%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 0.62%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.62%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.62%   |
| Y Media USB Camera                                          | 1         | 0.62%   |
| Xiongmai web camera                                         | 1         | 0.62%   |
| WaveRider USB Live camera                                   | 1         | 0.62%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.62%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.62%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.62%   |
| Suyin 1.3M HD WebCam                                        | 1         | 0.62%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.62%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.62%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 0.62%   |
| Sunplus Dell Integrated Webcam                              | 1         | 0.62%   |
| Silicon Motion Web Camera                                   | 1         | 0.62%   |
| Silicon Motion Silicon Motion Camera                        | 1         | 0.62%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 0.62%   |
| Ricoh Integrated Webcam                                     | 1         | 0.62%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 0.62%   |
| Realtek Lenovo EasyCamera                                   | 1         | 0.62%   |
| Realtek Integrated Webcam                                   | 1         | 0.62%   |
| Realtek HD Webcam - Realtek                                 | 1         | 0.62%   |
| Realtek HD WebCam                                           | 1         | 0.62%   |
| Realtek EasyCamera                                          | 1         | 0.62%   |
| Realtek 2SF001                                              | 1         | 0.62%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 0.62%   |
| Primax Dell Laptop Integrated Webcam 2Mpix                  | 1         | 0.62%   |
| Microdia WebCam SC-13HDL12639P                              | 1         | 0.62%   |
| Microdia Webcam                                             | 1         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 43.75%  |
| Upek                       | 5         | 15.63%  |
| Synaptics                  | 4         | 12.5%   |
| Shenzhen Goodix Technology | 3         | 9.38%   |
| AuthenTec                  | 3         | 9.38%   |
| LighTuning Technology      | 2         | 6.25%   |
| STMicroelectronics         | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 9.38%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 3         | 9.38%   |
| Validity Sensors Synaptics WBDI                            | 3         | 9.38%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 3.13%   |
| Validity Sensors Fingerprint scanner                       | 1         | 3.13%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 3.13%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.13%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.13%   |
| LighTuning Fingerprint Reader                              | 1         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.13%   |
| AuthenTec AES2810                                          | 1         | 3.13%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 3.13%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 3.13%   |
| Unknown                                                    | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 33.33%  |
| Lenovo                | 3         | 25%     |
| Broadcom              | 3         | 25%     |
| O2 Micro              | 1         | 8.33%   |
| Advanced Card Systems | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 33.33%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Advanced Card Systems ACR122U                                                | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 126       | 62.38%  |
| 1     | 61        | 30.2%   |
| 2     | 15        | 7.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 38        | 42.22%  |
| Fingerprint reader       | 32        | 35.56%  |
| Chipcard                 | 10        | 11.11%  |
| Storage                  | 3         | 3.33%   |
| Multimedia controller    | 3         | 3.33%   |
| Net/wireless             | 2         | 2.22%   |
| Communication controller | 1         | 1.11%   |
| Bluetooth                | 1         | 1.11%   |

