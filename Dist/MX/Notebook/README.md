MX - Tested Hardware & Statistics (Notebooks)
---------------------------------------------

A project to collect tested hardware configurations for MX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 282

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | [5369d059e6](https://linux-hardware.org/?probe=5369d059e6) | Apr 11, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | [46f9e8b140](https://linux-hardware.org/?probe=46f9e8b140) | Apr 07, 2022 |
| Acer          | Aspire A515-56              | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | 1101HA                      | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | Latitude 3190               | [45542e945e](https://linux-hardware.org/?probe=45542e945e) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Dell          | Latitude 3190               | [ffd3ee8119](https://linux-hardware.org/?probe=ffd3ee8119) | Mar 28, 2022 |
| Framework     | Laptop                      | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | [960989448e](https://linux-hardware.org/?probe=960989448e) | Mar 21, 2022 |
| Acer          | Extensa 5630                | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| Dell          | Latitude 3190               | [6d1ab0283d](https://linux-hardware.org/?probe=6d1ab0283d) | Mar 14, 2022 |
| Dell          | Latitude 3190               | [620f4d4f09](https://linux-hardware.org/?probe=620f4d4f09) | Mar 07, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | Latitude 3190               | [9637b88602](https://linux-hardware.org/?probe=9637b88602) | Feb 21, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Dell          | Latitude 3190               | [6340f68567](https://linux-hardware.org/?probe=6340f68567) | Feb 14, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude 3190               | [90df65f573](https://linux-hardware.org/?probe=90df65f573) | Feb 07, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| HP            | ProBook 6460b               | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Dell          | Latitude 3190               | [2e81dc022b](https://linux-hardware.org/?probe=2e81dc022b) | Jan 31, 2022 |
| Dell          | Latitude 3190               | [9b8e8549fd](https://linux-hardware.org/?probe=9b8e8549fd) | Jan 24, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| Dell          | Latitude 3190               | [3bb6a6428f](https://linux-hardware.org/?probe=3bb6a6428f) | Jan 10, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Dell          | Latitude 3190               | [2c483dc59d](https://linux-hardware.org/?probe=2c483dc59d) | Jan 03, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | 2000                        | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| Dell          | Latitude 3190               | [67cba6d321](https://linux-hardware.org/?probe=67cba6d321) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Dell          | Latitude 3190               | [1a96380872](https://linux-hardware.org/?probe=1a96380872) | Dec 20, 2021 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Dell          | Latitude 3190               | [5321909b8c](https://linux-hardware.org/?probe=5321909b8c) | Dec 13, 2021 |
| Dell          | Latitude 3190               | [9c532278f1](https://linux-hardware.org/?probe=9c532278f1) | Dec 06, 2021 |
| Toshiba       | Satellite L850-CJK          | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Dell          | Latitude 3190               | [700dd2459e](https://linux-hardware.org/?probe=700dd2459e) | Nov 29, 2021 |
| Lenovo        | Unknown                     | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Dell          | Latitude 3190               | [7f020f1d1f](https://linux-hardware.org/?probe=7f020f1d1f) | Nov 22, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Unknown       | Unknown                     | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Latitude 3190               | [f24ac635ba](https://linux-hardware.org/?probe=f24ac635ba) | Nov 15, 2021 |
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
| Dell          | Latitude 3190               | [e05975be8f](https://linux-hardware.org/?probe=e05975be8f) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Dell          | Latitude 3190               | [c5242a21e6](https://linux-hardware.org/?probe=c5242a21e6) | Oct 11, 2021 |
| Sony          | SVT13115FBS                 | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Dell          | Latitude 3190               | [bb6d2c2c67](https://linux-hardware.org/?probe=bb6d2c2c67) | Oct 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Lenovo        | ThinkPad L490 20Q5S0PR00    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer          | Aspire 4820T                | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| Dell          | Latitude 3190               | [6a71754838](https://linux-hardware.org/?probe=6a71754838) | Sep 27, 2021 |
| Dell          | Latitude 3190               | [c5f29e40e9](https://linux-hardware.org/?probe=c5f29e40e9) | Sep 20, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Lenovo        | ThinkPad P51 20HJS0TP00     | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo        | B40-45 20394                | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| Dell          | Latitude 3190               | [91b5632082](https://linux-hardware.org/?probe=91b5632082) | Sep 13, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| GTZS          | Unknown                     | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Dell          | Latitude 3190               | [76feb70b2f](https://linux-hardware.org/?probe=76feb70b2f) | Aug 30, 2021 |
| Dell          | Latitude 3190               | [bf62dc4914](https://linux-hardware.org/?probe=bf62dc4914) | Aug 23, 2021 |
| Dell          | Latitude 3190               | [1b11784345](https://linux-hardware.org/?probe=1b11784345) | Aug 16, 2021 |
| Pixus         | Rise                        | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| Dell          | Latitude 3190               | [bbef2b9d97](https://linux-hardware.org/?probe=bbef2b9d97) | Aug 09, 2021 |
| Dell          | Latitude 3190               | [61b56c3bd9](https://linux-hardware.org/?probe=61b56c3bd9) | Aug 02, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| Dell          | Latitude 3190               | [520fb53552](https://linux-hardware.org/?probe=520fb53552) | Jul 26, 2021 |
| Acer          | Aspire E5-574G              | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| Dell          | Latitude 3190               | [dc44dffece](https://linux-hardware.org/?probe=dc44dffece) | Jul 19, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3340               | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Dell          | Latitude 3190               | [701b0f5439](https://linux-hardware.org/?probe=701b0f5439) | Jul 12, 2021 |
| Acer          | Aspire one                  | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Dell          | Latitude 3190               | [6ca8a34d23](https://linux-hardware.org/?probe=6ca8a34d23) | Jul 05, 2021 |
| Dell          | Latitude 3190               | [ec46d1beb2](https://linux-hardware.org/?probe=ec46d1beb2) | Jun 28, 2021 |
| Dell          | Latitude 3190               | [c4cdd3a43c](https://linux-hardware.org/?probe=c4cdd3a43c) | Jun 21, 2021 |
| Dell          | Latitude 3190               | [5a6254c4af](https://linux-hardware.org/?probe=5a6254c4af) | Jun 14, 2021 |
| Medion        | P6669 MD60147               | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Dell          | Latitude 3190               | [e96a8c3e76](https://linux-hardware.org/?probe=e96a8c3e76) | Jun 07, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |
| Dell          | Latitude 3190               | [7bdec3eb56](https://linux-hardware.org/?probe=7bdec3eb56) | May 31, 2021 |
| Dell          | Vostro 3460                 | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| Dell          | Latitude 3190               | [8918c312ff](https://linux-hardware.org/?probe=8918c312ff) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Dell          | Latitude 3190               | [5ffc389a2a](https://linux-hardware.org/?probe=5ffc389a2a) | May 17, 2021 |
| Irbis         | TW94                        | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| Dell          | Latitude 3190               | [4eeed413e6](https://linux-hardware.org/?probe=4eeed413e6) | May 10, 2021 |
| Dell          | Latitude E6320              | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| Dell          | Latitude 3190               | [5caeaa658b](https://linux-hardware.org/?probe=5caeaa658b) | May 03, 2021 |
| Dell          | Latitude 3190               | [a046e7b3f8](https://linux-hardware.org/?probe=a046e7b3f8) | Apr 26, 2021 |
| Acer          | Extensa 5620                | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Dell          | Latitude 3190               | [c94ccb949b](https://linux-hardware.org/?probe=c94ccb949b) | Apr 19, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Intel         | ChiefRiver                  | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| Dell          | Latitude 3190               | [d0e46bf61f](https://linux-hardware.org/?probe=d0e46bf61f) | Apr 12, 2021 |
| ASUSTek       | G751JT                      | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| HP            | Falco                       | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| Dell          | Latitude 3190               | [2ff832079d](https://linux-hardware.org/?probe=2ff832079d) | Apr 05, 2021 |
| Dell          | Latitude 3190               | [3afafda719](https://linux-hardware.org/?probe=3afafda719) | Mar 29, 2021 |
| Dell          | Latitude 3190               | [d00e8dc9e8](https://linux-hardware.org/?probe=d00e8dc9e8) | Mar 22, 2021 |
| HP            | ZBook 17 G6                 | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| Dell          | Latitude 3190               | [83f4f1e1f1](https://linux-hardware.org/?probe=83f4f1e1f1) | Mar 15, 2021 |
| Dell          | Latitude E5470              | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| Dell          | Latitude 3190               | [8bb5c10a3c](https://linux-hardware.org/?probe=8bb5c10a3c) | Mar 08, 2021 |
| HP            | Notebook                    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Dell          | Latitude 3190               | [fb4469e67a](https://linux-hardware.org/?probe=fb4469e67a) | Mar 01, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Lenovo        | ThinkPad E425 1198CTO       | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| Dell          | Latitude 3190               | [6708c8b87a](https://linux-hardware.org/?probe=6708c8b87a) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | Mini 110-3500               | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| Google        | Gnawty                      | [2983bbfda3](https://linux-hardware.org/?probe=2983bbfda3) | Feb 11, 2021 |
| HP            | Notebook                    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| HP            | 15                          | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| Apple         | MacBook7,1                  | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Google        | Gnawty                      | [ee5279728d](https://linux-hardware.org/?probe=ee5279728d) | Feb 04, 2021 |
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
| HP            | Presario CQ57               | [16a2a0af55](https://linux-hardware.org/?probe=16a2a0af55) | Dec 31, 2020 |
| HP            | Presario CQ57               | [63b31db6e7](https://linux-hardware.org/?probe=63b31db6e7) | Dec 30, 2020 |
| HP            | Presario CQ57               | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [5b5f1330c5](https://linux-hardware.org/?probe=5b5f1330c5) | Dec 13, 2020 |
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
| Samsung       | 350V5C/351V5C/3540VC/344... | [f16c9341a8](https://linux-hardware.org/?probe=f16c9341a8) | Aug 21, 2020 |
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
| Medion        | AKOYA E1318T                | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |
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
| MSI           | GP63 Leopard 8RD            | [81806a4ddd](https://linux-hardware.org/?probe=81806a4ddd) | Jan 19, 2019 |
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


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MX 19   | 84        | 45.65%  |
| MX 21   | 42        | 22.83%  |
| MX 20   | 42        | 22.83%  |
| MX 18   | 12        | 6.52%   |
| MX 17   | 2         | 1.09%   |
| MX 18.1 | 1         | 0.54%   |
| MX 16.1 | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MX   | 176       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 32        | 16.33%  |
| 5.10.0-9-amd64             | 14        | 7.14%   |
| 5.10.0-5mx-amd64           | 13        | 6.63%   |
| 5.8.0-3-amd64              | 9         | 4.59%   |
| 5.10.0-13-amd64            | 8         | 4.08%   |
| 5.14.0-4mx-amd64           | 7         | 3.57%   |
| 5.10.0-11-amd64            | 6         | 3.06%   |
| 4.19.0-16-amd64            | 6         | 3.06%   |
| 4.19.0-14-amd64            | 6         | 3.06%   |
| 4.19.0-13-amd64            | 6         | 3.06%   |
| 5.6.0-2-amd64              | 5         | 2.55%   |
| 4.19.0-5-amd64             | 4         | 2.04%   |
| 4.19.0-17-amd64            | 4         | 2.04%   |
| 4.19.0-11-amd64            | 4         | 2.04%   |
| 5.10.0-8mx-amd64           | 3         | 1.53%   |
| 5.10.0-10-amd64            | 3         | 1.53%   |
| 4.19.0-9-amd64             | 3         | 1.53%   |
| 4.19.0-12-amd64            | 3         | 1.53%   |
| 4.19.0-1-amd64             | 3         | 1.53%   |
| 5.8.16-antix.1-amd64-smp   | 2         | 1.02%   |
| 5.6.10-antix.1-amd64-smp   | 2         | 1.02%   |
| 5.4.0-3-amd64              | 2         | 1.02%   |
| 5.10.0-8-amd64             | 2         | 1.02%   |
| 5.10.0-11-686-pae          | 2         | 1.02%   |
| 4.19.0-8-amd64             | 2         | 1.02%   |
| 4.19.0-16-686-pae          | 2         | 1.02%   |
| 4.15.0-1-amd64             | 2         | 1.02%   |
| 5.9.1-rt20avl1             | 1         | 0.51%   |
| 5.7.0-19.1-liquorix-amd64  | 1         | 0.51%   |
| 5.6.0-15.2-liquorix-amd64  | 1         | 0.51%   |
| 5.6.0-12.1-liquorix-amd64  | 1         | 0.51%   |
| 5.5.0-9.1-liquorix-amd64   | 1         | 0.51%   |
| 5.4.0-antix.1-amd64-smp    | 1         | 0.51%   |
| 5.4.0-13.3-liquorix-amd64  | 1         | 0.51%   |
| 5.4.0-11.2-liquorix-amd64  | 1         | 0.51%   |
| 5.4.0-10.2-liquorix-amd64  | 1         | 0.51%   |
| 5.3.10-antix.1-amd64-smp   | 1         | 0.51%   |
| 5.3.0-2-amd64              | 1         | 0.51%   |
| 5.3.0-10.1-liquorix-amd64  | 1         | 0.51%   |
| 5.2.8-antix.1-amd64-smp    | 1         | 0.51%   |
| 5.2.21-antix.2-amd64-smp   | 1         | 0.51%   |
| 5.2.21-antix.2-686-smp-pae | 1         | 0.51%   |
| 5.2.0-21.2-liquorix-amd64  | 1         | 0.51%   |
| 5.15.0-3mx-amd64           | 1         | 0.51%   |
| 5.15.0-1mx-amd64           | 1         | 0.51%   |
| 5.13.0-12.3-liquorix-amd64 | 1         | 0.51%   |
| 5.11.0-21.1-liquorix-amd64 | 1         | 0.51%   |
| 5.10.1-gnu                 | 1         | 0.51%   |
| 5.10.0-6.2-liquorix-amd64  | 1         | 0.51%   |
| 5.10.0-4mx-amd64           | 1         | 0.51%   |
| 5.10.0-13-686-pae          | 1         | 0.51%   |
| 5.10.0-11-686              | 1         | 0.51%   |
| 5.1.2-antix.1-amd64-smp    | 1         | 0.51%   |
| 5.0.0-9.2-liquorix-amd64   | 1         | 0.51%   |
| 4.9.246-0409246-lowlatency | 1         | 0.51%   |
| 4.9.193-antix.1-amd64-smp  | 1         | 0.51%   |
| 4.9.193-antix.1-486-smp    | 1         | 0.51%   |
| 4.19.174                   | 1         | 0.51%   |
| 4.19.0-6-686-pae           | 1         | 0.51%   |
| 4.19.0-18-amd64            | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.0   | 79        | 42.25%  |
| 5.10.0   | 50        | 26.74%  |
| 5.8.0    | 9         | 4.81%   |
| 5.6.0    | 7         | 3.74%   |
| 5.14.0   | 7         | 3.74%   |
| 5.4.0    | 6         | 3.21%   |
| 5.8.16   | 2         | 1.07%   |
| 5.6.10   | 2         | 1.07%   |
| 5.3.0    | 2         | 1.07%   |
| 5.2.21   | 2         | 1.07%   |
| 5.15.0   | 2         | 1.07%   |
| 4.9.193  | 2         | 1.07%   |
| 4.15.0   | 2         | 1.07%   |
| 5.9.1    | 1         | 0.53%   |
| 5.7.0    | 1         | 0.53%   |
| 5.5.0    | 1         | 0.53%   |
| 5.3.10   | 1         | 0.53%   |
| 5.2.8    | 1         | 0.53%   |
| 5.2.0    | 1         | 0.53%   |
| 5.13.0   | 1         | 0.53%   |
| 5.11.0   | 1         | 0.53%   |
| 5.10.1   | 1         | 0.53%   |
| 5.1.2    | 1         | 0.53%   |
| 5.0.0    | 1         | 0.53%   |
| 4.9.246  | 1         | 0.53%   |
| 4.19.174 | 1         | 0.53%   |
| 4.18.0   | 1         | 0.53%   |
| 3.16.0   | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 80        | 42.78%  |
| 5.10    | 51        | 27.27%  |
| 5.8     | 11        | 5.88%   |
| 5.6     | 9         | 4.81%   |
| 5.14    | 7         | 3.74%   |
| 5.4     | 6         | 3.21%   |
| 5.2     | 4         | 2.14%   |
| 5.3     | 3         | 1.6%    |
| 4.9     | 3         | 1.6%    |
| 5.15    | 2         | 1.07%   |
| 4.15    | 2         | 1.07%   |
| 5.9     | 1         | 0.53%   |
| 5.7     | 1         | 0.53%   |
| 5.5     | 1         | 0.53%   |
| 5.13    | 1         | 0.53%   |
| 5.11    | 1         | 0.53%   |
| 5.1     | 1         | 0.53%   |
| 5.0     | 1         | 0.53%   |
| 4.18    | 1         | 0.53%   |
| 3.16    | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 164       | 92.66%  |
| i686   | 13        | 7.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 127       | 70.95%  |
| KDE5            | 27        | 15.08%  |
| Budgie          | 5         | 2.79%   |
| i3              | 4         | 2.23%   |
| Unknown         | 4         | 2.23%   |
| MATE            | 2         | 1.12%   |
| Cinnamon        | 2         | 1.12%   |
| X-Cinnamon      | 1         | 0.56%   |
| Trinity         | 1         | 0.56%   |
| spectrwm        | 1         | 0.56%   |
| LXQt            | 1         | 0.56%   |
| LXDE            | 1         | 0.56%   |
| GNOME Flashback | 1         | 0.56%   |
| GNOME           | 1         | 0.56%   |
| fluxbox         | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 174       | 98.86%  |
| Tty  | 2         | 1.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 146       | 82.95%  |
| SDDM    | 23        | 13.07%  |
| SLiM    | 5         | 2.84%   |
| TDM     | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 58        | 31.87%  |
| Unknown | 55        | 30.22%  |
| de_DE   | 15        | 8.24%   |
| en_GB   | 8         | 4.4%    |
| ru_RU   | 7         | 3.85%   |
| sk_SK   | 6         | 3.3%    |
| pt_BR   | 5         | 2.75%   |
| it_IT   | 5         | 2.75%   |
| fr_FR   | 3         | 1.65%   |
| es_ES   | 3         | 1.65%   |
| pl_PL   | 2         | 1.1%    |
| en_IE   | 2         | 1.1%    |
| zh_CN   | 1         | 0.55%   |
| uk_UA   | 1         | 0.55%   |
| tr_TR   | 1         | 0.55%   |
| nl_NL   | 1         | 0.55%   |
| fr_BE   | 1         | 0.55%   |
| fi_FI   | 1         | 0.55%   |
| es_VE   | 1         | 0.55%   |
| es_PE   | 1         | 0.55%   |
| es_MX   | 1         | 0.55%   |
| es_CO   | 1         | 0.55%   |
| en_AU   | 1         | 0.55%   |
| de_CH   | 1         | 0.55%   |
| cs_CZ   | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 90        | 51.14%  |
| EFI  | 86        | 48.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 155       | 88.07%  |
| Overlay | 15        | 8.52%   |
| Btrfs   | 3         | 1.7%    |
| Xfs     | 1         | 0.57%   |
| F2fs    | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 103       | 58.19%  |
| MBR     | 71        | 40.11%  |
| Unknown | 3         | 1.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 142       | 80.23%  |
| Yes       | 35        | 19.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 59.09%  |
| Yes       | 72        | 40.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 41        | 23.3%   |
| Hewlett-Packard     | 29        | 16.48%  |
| ASUSTek Computer    | 21        | 11.93%  |
| Dell                | 19        | 10.8%   |
| Acer                | 17        | 9.66%   |
| Toshiba             | 7         | 3.98%   |
| Sony                | 7         | 3.98%   |
| Samsung Electronics | 4         | 2.27%   |
| MSI                 | 4         | 2.27%   |
| Medion              | 3         | 1.7%    |
| Fujitsu Siemens     | 3         | 1.7%    |
| Google              | 2         | 1.14%   |
| Gigabyte Technology | 2         | 1.14%   |
| Clevo               | 2         | 1.14%   |
| Apple               | 2         | 1.14%   |
| TUXEDO              | 1         | 0.57%   |
| Pixus               | 1         | 0.57%   |
| Panasonic           | 1         | 0.57%   |
| Packard Bell        | 1         | 0.57%   |
| Notebook            | 1         | 0.57%   |
| Irbis               | 1         | 0.57%   |
| Intel               | 1         | 0.57%   |
| Framework           | 1         | 0.57%   |
| eMachines           | 1         | 0.57%   |
| efirstview          | 1         | 0.57%   |
| Chuwi               | 1         | 0.57%   |
| Alienware           | 1         | 0.57%   |
| Unknown             | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP ProBook 650 G1                        | 2         | 1.14%   |
| Unknown                                  | 2         | 1.14%   |
| TUXEDO N7x0WU                            | 1         | 0.57%   |
| Toshiba Satellite P875                   | 1         | 0.57%   |
| Toshiba Satellite L850-CJK               | 1         | 0.57%   |
| Toshiba Satellite C70-B                  | 1         | 0.57%   |
| Toshiba Satellite C660                   | 1         | 0.57%   |
| Toshiba Satellite C50-A-12K              | 1         | 0.57%   |
| Toshiba Satellite A300                   | 1         | 0.57%   |
| Toshiba PORTEGE R705                     | 1         | 0.57%   |
| Sony VPCF23P1E                           | 1         | 0.57%   |
| Sony VPCF119FX                           | 1         | 0.57%   |
| Sony VPCEH2N1E                           | 1         | 0.57%   |
| Sony VPCEC3S1E                           | 1         | 0.57%   |
| Sony VGN-NR310FH                         | 1         | 0.57%   |
| Sony SVT13115FBS                         | 1         | 0.57%   |
| Sony SVE1513Q1ESI                        | 1         | 0.57%   |
| Samsung R780/R778                        | 1         | 0.57%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 0.57%   |
| Samsung 340XAA/350XAA/550XAA             | 1         | 0.57%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 0.57%   |
| Pixus Rise                               | 1         | 0.57%   |
| Panasonic CF-C1BT02EGE                   | 1         | 0.57%   |
| Packard Bell EasyNote TE11HC             | 1         | 0.57%   |
| Notebook W65_W67RZ1                      | 1         | 0.57%   |
| MSI MS-N033                              | 1         | 0.57%   |
| MSI GV62 8RD                             | 1         | 0.57%   |
| MSI GP63 Leopard 8RD                     | 1         | 0.57%   |
| MSI Alpha 15 B5EEK                       | 1         | 0.57%   |
| Medion P6669 MD60147                     | 1         | 0.57%   |
| Medion E6234                             | 1         | 0.57%   |
| Medion AKOYA E1318T                      | 1         | 0.57%   |
| Lenovo V145-15AST 81MT                   | 1         | 0.57%   |
| Lenovo ThinkPad X301 2776LBU             | 1         | 0.57%   |
| Lenovo ThinkPad X270 W10DG 20K5S0YT00    | 1         | 0.57%   |
| Lenovo ThinkPad X250 20CLS4YA00          | 1         | 0.57%   |
| Lenovo ThinkPad X220 4291WMQ             | 1         | 0.57%   |
| Lenovo ThinkPad X220 4291F52             | 1         | 0.57%   |
| Lenovo ThinkPad X201s 5413A19            | 1         | 0.57%   |
| Lenovo ThinkPad X201 3680MY9             | 1         | 0.57%   |
| Lenovo ThinkPad X1C 5th W10DG 20K4S0EC00 | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0013AU | 1         | 0.57%   |
| Lenovo ThinkPad W541 20EG0005MS          | 1         | 0.57%   |
| Lenovo ThinkPad W510 4875W17             | 1         | 0.57%   |
| Lenovo ThinkPad T60 20085TG              | 1         | 0.57%   |
| Lenovo ThinkPad T530 2394CJ9             | 1         | 0.57%   |
| Lenovo ThinkPad T440s 20AQ007SGE         | 1         | 0.57%   |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 0.57%   |
| Lenovo ThinkPad T440p 20AWS2T11D         | 1         | 0.57%   |
| Lenovo ThinkPad T440p 20AWA1NAUK         | 1         | 0.57%   |
| Lenovo ThinkPad T440p 20AW002VBR         | 1         | 0.57%   |
| Lenovo ThinkPad T430 23427YU             | 1         | 0.57%   |
| Lenovo ThinkPad T420 4236MBU             | 1         | 0.57%   |
| Lenovo ThinkPad T410 2537G99             | 1         | 0.57%   |
| Lenovo ThinkPad T400 2768WGB             | 1         | 0.57%   |
| Lenovo ThinkPad P51 20HJS0TP00           | 1         | 0.57%   |
| Lenovo ThinkPad L520 78595VG             | 1         | 0.57%   |
| Lenovo ThinkPad L490 20Q5S0PR00          | 1         | 0.57%   |
| Lenovo ThinkPad L412 0585W28             | 1         | 0.57%   |
| Lenovo ThinkPad E490 20N9S26G00          | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 30        | 17.05%  |
| Acer Aspire            | 12        | 6.82%   |
| Dell Latitude          | 9         | 5.11%   |
| Toshiba Satellite      | 6         | 3.41%   |
| HP Pavilion            | 6         | 3.41%   |
| HP EliteBook           | 5         | 2.84%   |
| Dell Inspiron          | 5         | 2.84%   |
| Lenovo IdeaPad         | 4         | 2.27%   |
| HP ProBook             | 4         | 2.27%   |
| ASUS TUF               | 3         | 1.7%    |
| Lenovo B590            | 2         | 1.14%   |
| HP ZBook               | 2         | 1.14%   |
| HP Laptop              | 2         | 1.14%   |
| HP Compaq              | 2         | 1.14%   |
| Dell Vostro            | 2         | 1.14%   |
| ASUS VivoBook          | 2         | 1.14%   |
| ASUS ROG               | 2         | 1.14%   |
| Acer Extensa           | 2         | 1.14%   |
| Unknown                | 2         | 1.14%   |
| TUXEDO N7x0WU          | 1         | 0.57%   |
| Toshiba PORTEGE        | 1         | 0.57%   |
| Sony VPCF23P1E         | 1         | 0.57%   |
| Sony VPCF119FX         | 1         | 0.57%   |
| Sony VPCEH2N1E         | 1         | 0.57%   |
| Sony VPCEC3S1E         | 1         | 0.57%   |
| Sony VGN-NR310FH       | 1         | 0.57%   |
| Sony SVT13115FBS       | 1         | 0.57%   |
| Sony SVE1513Q1ESI      | 1         | 0.57%   |
| Samsung R780           | 1         | 0.57%   |
| Samsung 350V5C         | 1         | 0.57%   |
| Samsung 340XAA         | 1         | 0.57%   |
| Samsung 305E4A         | 1         | 0.57%   |
| Pixus Rise             | 1         | 0.57%   |
| Panasonic CF-C1BT02EGE | 1         | 0.57%   |
| Packard Bell EasyNote  | 1         | 0.57%   |
| Notebook W65           | 1         | 0.57%   |
| MSI MS-N033            | 1         | 0.57%   |
| MSI GV62               | 1         | 0.57%   |
| MSI GP63               | 1         | 0.57%   |
| MSI Alpha              | 1         | 0.57%   |
| Medion P6669           | 1         | 0.57%   |
| Medion E6234           | 1         | 0.57%   |
| Medion AKOYA           | 1         | 0.57%   |
| Lenovo V145-15AST      | 1         | 0.57%   |
| Lenovo ThinkBook       | 1         | 0.57%   |
| Lenovo G400s           | 1         | 0.57%   |
| Lenovo B40-45          | 1         | 0.57%   |
| Irbis TW94             | 1         | 0.57%   |
| Intel ChiefRiver       | 1         | 0.57%   |
| HP Stream              | 1         | 0.57%   |
| HP Presario            | 1         | 0.57%   |
| HP Notebook            | 1         | 0.57%   |
| HP Mini                | 1         | 0.57%   |
| HP Falco               | 1         | 0.57%   |
| HP ENVY                | 1         | 0.57%   |
| HP 2000                | 1         | 0.57%   |
| HP 15                  | 1         | 0.57%   |
| Google Gnawty          | 1         | 0.57%   |
| Google Akemi           | 1         | 0.57%   |
| Gigabyte P15FV5        | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 19        | 10.8%   |
| 2011    | 18        | 10.23%  |
| 2018    | 17        | 9.66%   |
| 2012    | 17        | 9.66%   |
| 2014    | 14        | 7.95%   |
| 2013    | 13        | 7.39%   |
| 2021    | 12        | 6.82%   |
| 2016    | 11        | 6.25%   |
| 2015    | 10        | 5.68%   |
| 2019    | 9         | 5.11%   |
| 2008    | 9         | 5.11%   |
| 2017    | 7         | 3.98%   |
| 2009    | 6         | 3.41%   |
| 2020    | 5         | 2.84%   |
| 2007    | 4         | 2.27%   |
| 2006    | 2         | 1.14%   |
| 2005    | 2         | 1.14%   |
| Unknown | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 176       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 176       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 173       | 98.3%   |
| Yes  | 3         | 1.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 28.81%  |
| 3.01-4.0    | 36        | 20.34%  |
| 8.01-16.0   | 36        | 20.34%  |
| 16.01-24.0  | 20        | 11.3%   |
| 1.01-2.0    | 15        | 8.47%   |
| 2.01-3.0    | 7         | 3.95%   |
| 32.01-64.0  | 5         | 2.82%   |
| 0.51-1.0    | 4         | 2.26%   |
| 24.01-32.0  | 2         | 1.13%   |
| 64.01-256.0 | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 75        | 39.68%  |
| 2.01-3.0  | 40        | 21.16%  |
| 3.01-4.0  | 27        | 14.29%  |
| 0.51-1.0  | 27        | 14.29%  |
| 4.01-8.0  | 14        | 7.41%   |
| 8.01-16.0 | 4         | 2.12%   |
| 0.01-0.5  | 2         | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 129       | 72.47%  |
| 2      | 36        | 20.22%  |
| 3      | 9         | 5.06%   |
| 4      | 2         | 1.12%   |
| 0      | 2         | 1.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 62.71%  |
| Yes       | 66        | 37.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 88.64%  |
| No        | 20        | 11.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 96.59%  |
| No        | 6         | 3.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 72.73%  |
| No        | 48        | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 33        | 18.64%  |
| Germany     | 19        | 10.73%  |
| UK          | 10        | 5.65%   |
| Russia      | 7         | 3.95%   |
| Italy       | 7         | 3.95%   |
| Canada      | 7         | 3.95%   |
| Brazil      | 7         | 3.95%   |
| Spain       | 6         | 3.39%   |
| Slovakia    | 6         | 3.39%   |
| Netherlands | 6         | 3.39%   |
| France      | 5         | 2.82%   |
| Austria     | 5         | 2.82%   |
| Ukraine     | 4         | 2.26%   |
| Poland      | 4         | 2.26%   |
| Mexico      | 4         | 2.26%   |
| India       | 4         | 2.26%   |
| Thailand    | 3         | 1.69%   |
| Finland     | 3         | 1.69%   |
| Belgium     | 3         | 1.69%   |
| Portugal    | 2         | 1.13%   |
| Czechia     | 2         | 1.13%   |
| Colombia    | 2         | 1.13%   |
| China       | 2         | 1.13%   |
| Belarus     | 2         | 1.13%   |
| Australia   | 2         | 1.13%   |
| Vietnam     | 1         | 0.56%   |
| Venezuela   | 1         | 0.56%   |
| Turkey      | 1         | 0.56%   |
| Syria       | 1         | 0.56%   |
| Switzerland | 1         | 0.56%   |
| Sweden      | 1         | 0.56%   |
| Serbia      | 1         | 0.56%   |
| Romania     | 1         | 0.56%   |
| Philippines | 1         | 0.56%   |
| Peru        | 1         | 0.56%   |
| Norway      | 1         | 0.56%   |
| Nigeria     | 1         | 0.56%   |
| Malaysia    | 1         | 0.56%   |
| Latvia      | 1         | 0.56%   |
| Indonesia   | 1         | 0.56%   |
| Hungary     | 1         | 0.56%   |
| Greece      | 1         | 0.56%   |
| Croatia     | 1         | 0.56%   |
| Chile       | 1         | 0.56%   |
| Azerbaijan  | 1         | 0.56%   |
| Angola      | 1         | 0.56%   |
| Algeria     | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Bratislava      | 6         | 3.24%   |
| Vienna          | 5         | 2.7%    |
| Berlin          | 4         | 2.16%   |
| Los Angeles     | 3         | 1.62%   |
| St Petersburg   | 2         | 1.08%   |
| Oxford          | 2         | 1.08%   |
| Munich          | 2         | 1.08%   |
| Minsk           | 2         | 1.08%   |
| Madrid          | 2         | 1.08%   |
| Helsinki        | 2         | 1.08%   |
| Dnipro          | 2         | 1.08%   |
| Chiang Mai      | 2         | 1.08%   |
| Asansol         | 2         | 1.08%   |
| Amsterdam       | 2         | 1.08%   |
| Zurich          | 1         | 0.54%   |
| Zuidland        | 1         | 0.54%   |
| Zliv            | 1         | 0.54%   |
| Xalapa          | 1         | 0.54%   |
| Waycross        | 1         | 0.54%   |
| Warsaw          | 1         | 0.54%   |
| Vista           | 1         | 0.54%   |
| Vertou          | 1         | 0.54%   |
| Valencia        | 1         | 0.54%   |
| Uthai           | 1         | 0.54%   |
| Ulverston       | 1         | 0.54%   |
| Uelzen          | 1         | 0.54%   |
| Udine           | 1         | 0.54%   |
| Trivandrum      | 1         | 0.54%   |
| Torquay         | 1         | 0.54%   |
| Tampa           | 1         | 0.54%   |
| Taggia          | 1         | 0.54%   |
| Suzhou          | 1         | 0.54%   |
| Street          | 1         | 0.54%   |
| Steenwijk       | 1         | 0.54%   |
| Shenzhen        | 1         | 0.54%   |
| Schiedam        | 1         | 0.54%   |
| Saskatoon       | 1         | 0.54%   |
| Santa Pola      | 1         | 0.54%   |
| Salisbury       | 1         | 0.54%   |
| Saarlouis       | 1         | 0.54%   |
| Roseville       | 1         | 0.54%   |
| Romulus         | 1         | 0.54%   |
| Rochester       | 1         | 0.54%   |
| Rivne           | 1         | 0.54%   |
| Riga            | 1         | 0.54%   |
| Rensselaer      | 1         | 0.54%   |
| Relizane        | 1         | 0.54%   |
| Puerto Vallarta | 1         | 0.54%   |
| Prague          | 1         | 0.54%   |
| Powder Springs  | 1         | 0.54%   |
| Postbauer-Heng  | 1         | 0.54%   |
| Portsmouth      | 1         | 0.54%   |
| Porto           | 1         | 0.54%   |
| Portland        | 1         | 0.54%   |
| Piszczac        | 1         | 0.54%   |
| Philadelphia    | 1         | 0.54%   |
| Perm            | 1         | 0.54%   |
| Pelham          | 1         | 0.54%   |
| PÃ¡trai       | 1         | 0.54%   |
| Pateros         | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 31     | 13.16%  |
| Samsung Electronics | 28        | 35     | 12.28%  |
| Seagate             | 21        | 23     | 9.21%   |
| Kingston            | 18        | 18     | 7.89%   |
| Toshiba             | 15        | 16     | 6.58%   |
| Crucial             | 14        | 30     | 6.14%   |
| SanDisk             | 13        | 13     | 5.7%    |
| Unknown             | 12        | 15     | 5.26%   |
| SK Hynix            | 8         | 8      | 3.51%   |
| Hitachi             | 8         | 8      | 3.51%   |
| HGST                | 8         | 13     | 3.51%   |
| Intel               | 7         | 10     | 3.07%   |
| Transcend           | 4         | 4      | 1.75%   |
| PNY                 | 3         | 3      | 1.32%   |
| LITEON              | 3         | 3      | 1.32%   |
| DOGFISH             | 3         | 3      | 1.32%   |
| A-DATA Technology   | 3         | 5      | 1.32%   |
| PHISON              | 2         | 2      | 0.88%   |
| Micron Technology   | 2         | 6      | 0.88%   |
| KingSpec            | 2         | 2      | 0.88%   |
| KingDian            | 2         | 2      | 0.88%   |
| Fujitsu             | 2         | 2      | 0.88%   |
| ZTC                 | 1         | 1      | 0.44%   |
| Yeyian              | 1         | 1      | 0.44%   |
| Team                | 1         | 1      | 0.44%   |
| SPCC                | 1         | 1      | 0.44%   |
| SMART               | 1         | 1      | 0.44%   |
| Phison Electronics  | 1         | 2      | 0.44%   |
| Patriot             | 1         | 1      | 0.44%   |
| Netac               | 1         | 1      | 0.44%   |
| LITEONIT            | 1         | 1      | 0.44%   |
| Lexar               | 1         | 1      | 0.44%   |
| Lenovo              | 1         | 1      | 0.44%   |
| KingFast            | 1         | 1      | 0.44%   |
| Intenso             | 1         | 1      | 0.44%   |
| Indilinx            | 1         | 3      | 0.44%   |
| HUAWEI              | 1         | 1      | 0.44%   |
| GOODRAM             | 1         | 1      | 0.44%   |
| Gigabyte Technology | 1         | 1      | 0.44%   |
| GeIL                | 1         | 1      | 0.44%   |
| Corsair             | 1         | 1      | 0.44%   |
| Unknown             | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 6         | 2.55%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 2.13%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.7%    |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 1.28%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 1.28%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.28%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.28%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.85%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.85%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.85%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.85%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.85%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.85%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.85%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.85%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.85%   |
| Intel SSDSA2BW120G3H 120GB           | 2         | 0.85%   |
| Intel SSDPEKNW512G8 512GB            | 2         | 0.85%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.85%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.85%   |
| Dogfish SSD 128GB                    | 2         | 0.85%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.85%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.85%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.85%   |
| A-DATA SP600 32GB SSD                | 2         | 0.85%   |
| ZTC SM201-256G SSD                   | 1         | 0.43%   |
| Yeyian VALK 1000 120GB               | 1         | 0.43%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.43%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.43%   |
| WDC WD7500BPVX-00JC3T0 752GB         | 1         | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.43%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.43%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.43%   |
| WDC WD5000BPVT-60HXZT3 500GB         | 1         | 0.43%   |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 0.43%   |
| WDC WD3200LPVT-08G33T1 320GB         | 1         | 0.43%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.43%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 0.43%   |
| WDC WD2500BEVE-00WZT0 250GB          | 1         | 0.43%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.43%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.43%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.43%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 0.43%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.43%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.43%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.43%   |
| WDC PC SN730 NVMe 1024GB             | 1         | 0.43%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB   | 1         | 0.43%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 0.43%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 1         | 0.43%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 0.43%   |
| Unknown SS08G  8GB                   | 1         | 0.43%   |
| Unknown SLD64G  64GB                 | 1         | 0.43%   |
| Unknown SDW32G  32GB                 | 1         | 0.43%   |
| Unknown SD32G  32GB                  | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 21     | 28.77%  |
| Seagate             | 21        | 23     | 28.77%  |
| Toshiba             | 10        | 11     | 13.7%   |
| Hitachi             | 8         | 8      | 10.96%  |
| HGST                | 8         | 13     | 10.96%  |
| Samsung Electronics | 3         | 4      | 4.11%   |
| Fujitsu             | 2         | 2      | 2.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 24     | 17.43%  |
| Kingston            | 16        | 16     | 14.68%  |
| Crucial             | 13        | 28     | 11.93%  |
| SanDisk             | 12        | 12     | 11.01%  |
| Transcend           | 4         | 4      | 3.67%   |
| WDC                 | 3         | 3      | 2.75%   |
| SK Hynix            | 3         | 3      | 2.75%   |
| PNY                 | 3         | 3      | 2.75%   |
| LITEON              | 3         | 3      | 2.75%   |
| Intel               | 3         | 6      | 2.75%   |
| Dogfish             | 3         | 3      | 2.75%   |
| A-DATA Technology   | 3         | 5      | 2.75%   |
| Toshiba             | 2         | 2      | 1.83%   |
| Micron Technology   | 2         | 6      | 1.83%   |
| KingSpec            | 2         | 2      | 1.83%   |
| KingDian            | 2         | 2      | 1.83%   |
| ZTC                 | 1         | 1      | 0.92%   |
| Yeyian              | 1         | 1      | 0.92%   |
| Team                | 1         | 1      | 0.92%   |
| SPCC                | 1         | 1      | 0.92%   |
| SMART               | 1         | 1      | 0.92%   |
| PHISON              | 1         | 1      | 0.92%   |
| Patriot             | 1         | 1      | 0.92%   |
| Netac               | 1         | 1      | 0.92%   |
| LITEONIT            | 1         | 1      | 0.92%   |
| KingFast            | 1         | 1      | 0.92%   |
| Intenso             | 1         | 1      | 0.92%   |
| Indilinx            | 1         | 3      | 0.92%   |
| GOODRAM             | 1         | 1      | 0.92%   |
| Gigabyte Technology | 1         | 1      | 0.92%   |
| GeIL                | 1         | 1      | 0.92%   |
| Corsair             | 1         | 1      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 94        | 140    | 44.98%  |
| HDD     | 72        | 82     | 34.45%  |
| NVMe    | 27        | 34     | 12.92%  |
| MMC     | 15        | 18     | 7.18%   |
| Unknown | 1         | 1      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 141       | 221    | 76.22%  |
| NVMe | 27        | 34     | 14.59%  |
| MMC  | 15        | 18     | 8.11%   |
| SAS  | 2         | 2      | 1.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 118       | 158    | 73.29%  |
| 0.51-1.0   | 40        | 61     | 24.84%  |
| 1.01-2.0   | 2         | 2      | 1.24%   |
| 4.01-10.0  | 1         | 1      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 59        | 32.96%  |
| 251-500        | 29        | 16.2%   |
| 501-1000       | 29        | 16.2%   |
| 51-100         | 25        | 13.97%  |
| 21-50          | 15        | 8.38%   |
| 1-20           | 11        | 6.15%   |
| 1001-2000      | 7         | 3.91%   |
| Unknown        | 2         | 1.12%   |
| More than 3000 | 1         | 0.56%   |
| 2001-3000      | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 78        | 42.62%  |
| 21-50          | 29        | 15.85%  |
| 51-100         | 29        | 15.85%  |
| 101-250        | 20        | 10.93%  |
| 251-500        | 14        | 7.65%   |
| 501-1000       | 8         | 4.37%   |
| 1001-2000      | 2         | 1.09%   |
| Unknown        | 2         | 1.09%   |
| More than 3000 | 1         | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 10.34%  |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 3.45%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 3.45%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 3.45%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 3.45%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 3.45%   |
| Toshiba MK7575GSX 752GB                      | 1         | 2      | 3.45%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 3.45%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 3.45%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 3.45%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 3.45%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 3.45%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 3.45%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 3.45%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 3.45%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 3      | 3.45%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 3.45%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 3.45%   |
| Hitachi HTS543216L9SA02 160GB                | 1         | 1      | 3.45%   |
| Hitachi HTS542516K9SA00 160GB                | 1         | 1      | 3.45%   |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 3.45%   |
| HGST HTS545032A7E380 320GB                   | 1         | 1      | 3.45%   |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 3.45%   |
| Fujitsu MHZ2160BH G2 160GB                   | 1         | 1      | 3.45%   |
| Crucial CT512M550SSD1 512GB                  | 1         | 1      | 3.45%   |
| A-DATA Technology SU650 240GB SSD            | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 20.69%  |
| WDC                 | 5         | 5      | 17.24%  |
| Hitachi             | 4         | 4      | 13.79%  |
| Toshiba             | 3         | 4      | 10.34%  |
| HGST                | 3         | 4      | 10.34%  |
| Samsung Electronics | 2         | 3      | 6.9%    |
| SanDisk             | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Indilinx            | 1         | 3      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 26.09%  |
| WDC                 | 5         | 5      | 21.74%  |
| Hitachi             | 4         | 4      | 17.39%  |
| Toshiba             | 3         | 4      | 13.04%  |
| HGST                | 3         | 4      | 13.04%  |
| Samsung Electronics | 1         | 2      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 26     | 79.31%  |
| SSD  | 6         | 8      | 20.69%  |

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
| Works    | 143       | 219    | 75.26%  |
| Malfunc  | 28        | 34     | 14.74%  |
| Detected | 19        | 22     | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 135       | 72.97%  |
| AMD                          | 18        | 9.73%   |
| Sandisk                      | 7         | 3.78%   |
| Samsung Electronics          | 6         | 3.24%   |
| SK Hynix                     | 4         | 2.16%   |
| Nvidia                       | 4         | 2.16%   |
| Toshiba America Info Systems | 2         | 1.08%   |
| Phison Electronics           | 2         | 1.08%   |
| Kingston Technology Company  | 2         | 1.08%   |
| Silicon Motion               | 1         | 0.54%   |
| Silicon Image                | 1         | 0.54%   |
| Micron/Crucial Technology    | 1         | 0.54%   |
| Lenovo                       | 1         | 0.54%   |
| KIOXIA                       | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 9.55%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 8.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 7.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 6.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 6.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 4.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 3.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 3.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.51%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 2.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 2.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.51%   |
| Intel SSD 660P Series                                                            | 3         | 1.51%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.51%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 1.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.01%   |
| SK Hynix Gold P31 SSD                                                            | 2         | 1.01%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.01%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.01%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.01%   |
| SK Hynix BC511                                                                   | 1         | 0.5%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.5%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.5%    |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.5%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.5%    |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.5%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.5%    |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.5%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.5%    |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 0.5%    |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.5%    |
| Nvidia MCP51 IDE                                                                 | 1         | 0.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.5%    |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.5%    |
| KIOXIA Non-Volatile memory controller                                            | 1         | 0.5%    |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.5%    |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.5%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.5%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.5%    |
| Intel Non-Volatile memory controller                                             | 1         | 0.5%    |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 0.5%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.5%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 0.5%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 132       | 68.75%  |
| NVMe | 27        | 14.06%  |
| IDE  | 17        | 8.85%   |
| RAID | 16        | 8.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 150       | 85.23%  |
| AMD    | 26        | 14.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 3.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 2.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.7%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.14%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.14%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.14%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.14%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.14%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 1.14%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 1.14%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.14%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.14%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.14%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 1.14%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 2         | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.14%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 1.14%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.57%   |
| Intel Pentium M processor 1.80GHz             | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.57%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.57%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.57%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.57%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.57%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.57%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.57%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.57%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 0.57%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.57%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.57%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.57%   |
| Intel Core i7 CPU M 640 @ 2.80GHz             | 1         | 0.57%   |
| Intel Core i7 CPU L 620 @ 2.00GHz             | 1         | 0.57%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 47        | 26.7%   |
| Intel Core i7           | 43        | 24.43%  |
| Intel Celeron           | 15        | 8.52%   |
| Intel Core i3           | 11        | 6.25%   |
| Intel Atom              | 11        | 6.25%   |
| Intel Core 2 Duo        | 9         | 5.11%   |
| AMD Ryzen 7             | 7         | 3.98%   |
| Other                   | 5         | 2.84%   |
| Intel Pentium           | 3         | 1.7%    |
| AMD A6                  | 3         | 1.7%    |
| AMD Turion 64 X2 Mobile | 2         | 1.14%   |
| AMD Ryzen 5             | 2         | 1.14%   |
| AMD E1                  | 2         | 1.14%   |
| AMD E                   | 2         | 1.14%   |
| AMD A8                  | 2         | 1.14%   |
| AMD A4                  | 2         | 1.14%   |
| Intel Pentium Silver    | 1         | 0.57%   |
| Intel Pentium M         | 1         | 0.57%   |
| Intel Pentium Dual-Core | 1         | 0.57%   |
| Intel Core Duo          | 1         | 0.57%   |
| Intel Core 2            | 1         | 0.57%   |
| Intel Celeron M         | 1         | 0.57%   |
| AMD Sempron             | 1         | 0.57%   |
| AMD Ryzen 9             | 1         | 0.57%   |
| AMD Ryzen 3             | 1         | 0.57%   |
| AMD Athlon 64 X2        | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 104       | 59.09%  |
| 4      | 49        | 27.84%  |
| 1      | 10        | 5.68%   |
| 8      | 7         | 3.98%   |
| 6      | 6         | 3.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 176       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 124       | 70.45%  |
| 1      | 52        | 29.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 168       | 94.92%  |
| 32-bit         | 9         | 5.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 10.17%  |
| 0x306a9    | 17        | 9.6%    |
| 0x206a7    | 14        | 7.91%   |
| 0x406e3    | 9         | 5.08%   |
| 0x20655    | 8         | 4.52%   |
| 0x40651    | 7         | 3.95%   |
| 0x306c3    | 7         | 3.95%   |
| 0x806ea    | 5         | 2.82%   |
| 0x906ea    | 4         | 2.26%   |
| 0x806c1    | 4         | 2.26%   |
| 0x306d4    | 4         | 2.26%   |
| 0x30678    | 4         | 2.26%   |
| 0x20652    | 4         | 2.26%   |
| 0x106c2    | 4         | 2.26%   |
| 0x806e9    | 3         | 1.69%   |
| 0x706a1    | 3         | 1.69%   |
| 0x406c4    | 3         | 1.69%   |
| 0x1067a    | 3         | 1.69%   |
| 0x10676    | 3         | 1.69%   |
| 0x0a50000c | 3         | 1.69%   |
| 0x03000027 | 3         | 1.69%   |
| 0xa0652    | 2         | 1.13%   |
| 0x906e9    | 2         | 1.13%   |
| 0x806ec    | 2         | 1.13%   |
| 0x706e5    | 2         | 1.13%   |
| 0x6fd      | 2         | 1.13%   |
| 0x506e3    | 2         | 1.13%   |
| 0x30661    | 2         | 1.13%   |
| 0x106e5    | 2         | 1.13%   |
| 0x106ca    | 2         | 1.13%   |
| 0x08608103 | 2         | 1.13%   |
| 0x08108102 | 2         | 1.13%   |
| 0x0810100b | 2         | 1.13%   |
| 0x07030105 | 2         | 1.13%   |
| 0x0700010f | 2         | 1.13%   |
| 0x906ed    | 1         | 0.56%   |
| 0x806eb    | 1         | 0.56%   |
| 0x806d1    | 1         | 0.56%   |
| 0x706a8    | 1         | 0.56%   |
| 0x6fb      | 1         | 0.56%   |
| 0x6f2      | 1         | 0.56%   |
| 0x6ec      | 1         | 0.56%   |
| 0x6d8      | 1         | 0.56%   |
| 0x6d6      | 1         | 0.56%   |
| 0x506c9    | 1         | 0.56%   |
| 0x406c3    | 1         | 0.56%   |
| 0x10661    | 1         | 0.56%   |
| 0x08600104 | 1         | 0.56%   |
| 0x08101007 | 1         | 0.56%   |
| 0x07030104 | 1         | 0.56%   |
| 0x06006705 | 1         | 0.56%   |
| 0x05000119 | 1         | 0.56%   |
| 0x0500010d | 1         | 0.56%   |
| 0x02000057 | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 21        | 11.93%  |
| IvyBridge       | 19        | 10.8%   |
| SandyBridge     | 18        | 10.23%  |
| Haswell         | 14        | 7.95%   |
| Westmere        | 13        | 7.39%   |
| Skylake         | 12        | 6.82%   |
| Silvermont      | 10        | 5.68%   |
| Bonnell         | 8         | 4.55%   |
| Penryn          | 7         | 3.98%   |
| Core            | 5         | 2.84%   |
| TigerLake       | 4         | 2.27%   |
| Goldmont plus   | 4         | 2.27%   |
| Broadwell       | 4         | 2.27%   |
| Zen 3           | 3         | 1.7%    |
| Zen             | 3         | 1.7%    |
| Puma            | 3         | 1.7%    |
| P6              | 3         | 1.7%    |
| K8 Hammer       | 3         | 1.7%    |
| K10 Llano       | 3         | 1.7%    |
| IceLake         | 3         | 1.7%    |
| Zen+            | 2         | 1.14%   |
| Nehalem         | 2         | 1.14%   |
| Jaguar          | 2         | 1.14%   |
| CometLake       | 2         | 1.14%   |
| Bobcat          | 2         | 1.14%   |
| Unknown         | 2         | 1.14%   |
| Zen 2           | 1         | 0.57%   |
| K8 & K10 hybrid | 1         | 0.57%   |
| Goldmont        | 1         | 0.57%   |
| Excavator       | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 61.57%  |
| Nvidia | 43        | 19.91%  |
| AMD    | 40        | 18.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 7.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 6.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 3.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 3.07%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.75%   |
| Intel HD Graphics 620                                                                    | 4         | 1.75%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.32%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.32%   |
| Intel HD Graphics 530                                                                    | 3         | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.32%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.32%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 3         | 1.32%   |
| AMD Cezanne                                                                              | 3         | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.88%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.88%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.88%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.88%   |
| Intel HD Graphics 630                                                                    | 2         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.88%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.88%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.88%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.88%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.88%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.88%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                                  | 2         | 0.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.88%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.88%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.88%   |
| AMD Lucienne                                                                             | 2         | 0.88%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.44%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 1         | 0.44%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.44%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.44%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.44%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.44%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.44%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.44%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.44%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.44%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.44%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.44%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.44%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 97        | 55.11%  |
| Intel + Nvidia | 29        | 16.48%  |
| 1 x AMD        | 24        | 13.64%  |
| 1 x Nvidia     | 10        | 5.68%   |
| Intel + AMD    | 7         | 3.98%   |
| 2 x AMD        | 5         | 2.84%   |
| AMD + Nvidia   | 4         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 162       | 91.53%  |
| Proprietary | 12        | 6.78%   |
| Unknown     | 3         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 72.32%  |
| 0.01-0.5   | 24        | 13.56%  |
| 0.51-1.0   | 12        | 6.78%   |
| 1.01-2.0   | 11        | 6.21%   |
| 7.01-8.0   | 1         | 0.56%   |
| 3.01-4.0   | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 37        | 19.58%  |
| LG Display              | 29        | 15.34%  |
| Chimei Innolux          | 26        | 13.76%  |
| Samsung Electronics     | 21        | 11.11%  |
| BOE                     | 18        | 9.52%   |
| Lenovo                  | 10        | 5.29%   |
| Chi Mei Optoelectronics | 9         | 4.76%   |
| HannStar                | 4         | 2.12%   |
| Sharp                   | 3         | 1.59%   |
| PANDA                   | 3         | 1.59%   |
| LG Philips              | 3         | 1.59%   |
| InfoVision              | 3         | 1.59%   |
| Dell                    | 3         | 1.59%   |
| Ancor Communications    | 3         | 1.59%   |
| Sony                    | 2         | 1.06%   |
| Philips                 | 2         | 1.06%   |
| Hewlett-Packard         | 2         | 1.06%   |
| Goldstar                | 2         | 1.06%   |
| CPT                     | 2         | 1.06%   |
| Apple                   | 2         | 1.06%   |
| Vizio                   | 1         | 0.53%   |
| Panasonic               | 1         | 0.53%   |
| InnoLux Display         | 1         | 0.53%   |
| AOC                     | 1         | 0.53%   |
| Acer                    | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 2.12%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 3         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 3         | 1.59%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 1.06%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 1.06%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 1.06%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 1.06%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 1.06%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 1.06%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 1.06%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 340x190mm 15.3-inch            | 2         | 1.06%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                        | 1         | 0.53%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.53%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.53%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.53%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.53%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM00B6 1280x1024 376x301mm 19.0-inch     | 1         | 0.53%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch        | 1         | 0.53%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.53%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 1         | 0.53%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.53%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch                | 1         | 0.53%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 0.53%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 0.53%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 1         | 0.53%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 0.53%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 0.53%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 0.53%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 0.53%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 0.53%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch              | 1         | 0.53%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 1         | 0.53%   |
| LG Display LCD Monitor LGD04FC 1366x768 344x194mm 15.5-inch              | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 69        | 37.7%   |
| 1920x1080 (FHD)    | 66        | 36.07%  |
| 1600x900 (HD+)     | 11        | 6.01%   |
| 1280x800 (WXGA)    | 10        | 5.46%   |
| 1024x600           | 6         | 3.28%   |
| 3840x2160 (4K)     | 4         | 2.19%   |
| 1440x900 (WXGA+)   | 4         | 2.19%   |
| 2560x1440 (QHD)    | 2         | 1.09%   |
| 2560x1080          | 2         | 1.09%   |
| 1680x1050 (WSXGA+) | 2         | 1.09%   |
| 1280x1024 (SXGA)   | 2         | 1.09%   |
| 3840x2400          | 1         | 0.55%   |
| 2256x1504          | 1         | 0.55%   |
| 2160x1440          | 1         | 0.55%   |
| 1920x1200 (WUXGA)  | 1         | 0.55%   |
| 1400x1050          | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 80        | 42.55%  |
| 13     | 27        | 14.36%  |
| 14     | 24        | 12.77%  |
| 17     | 13        | 6.91%   |
| 10     | 7         | 3.72%   |
| 12     | 6         | 3.19%   |
| 24     | 5         | 2.66%   |
| 27     | 4         | 2.13%   |
| 23     | 4         | 2.13%   |
| 11     | 4         | 2.13%   |
| 19     | 3         | 1.6%    |
| 34     | 2         | 1.06%   |
| 20     | 2         | 1.06%   |
| 18     | 2         | 1.06%   |
| 43     | 1         | 0.53%   |
| 37     | 1         | 0.53%   |
| 32     | 1         | 0.53%   |
| 21     | 1         | 0.53%   |
| 16     | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 113       | 60.11%  |
| 201-300     | 30        | 15.96%  |
| 351-400     | 21        | 11.17%  |
| 501-600     | 13        | 6.91%   |
| 401-500     | 6         | 3.19%   |
| 701-800     | 3         | 1.6%    |
| 801-900     | 1         | 0.53%   |
| 901-1000    | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 147       | 84.48%  |
| 16/10 | 18        | 10.34%  |
| 3/2   | 4         | 2.3%    |
| 5/4   | 2         | 1.15%   |
| 21/9  | 2         | 1.15%   |
| 4/3   | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 80        | 42.55%  |
| 81-90          | 42        | 22.34%  |
| 121-130        | 12        | 6.38%   |
| 71-80          | 9         | 4.79%   |
| 201-250        | 8         | 4.26%   |
| 41-50          | 7         | 3.72%   |
| 61-70          | 6         | 3.19%   |
| 151-200        | 5         | 2.66%   |
| 51-60          | 4         | 2.13%   |
| 301-350        | 4         | 2.13%   |
| 351-500        | 3         | 1.6%    |
| 251-300        | 2         | 1.06%   |
| 141-150        | 2         | 1.06%   |
| 501-1000       | 2         | 1.06%   |
| 131-140        | 1         | 0.53%   |
| 111-120        | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 72        | 39.13%  |
| 121-160       | 64        | 34.78%  |
| 51-100        | 37        | 20.11%  |
| 161-240       | 8         | 4.35%   |
| More than 240 | 3         | 1.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 149       | 84.66%  |
| 2     | 25        | 14.2%   |
| 3     | 1         | 0.57%   |
| 0     | 1         | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 94        | 33.1%   |
| Realtek Semiconductor             | 82        | 28.87%  |
| Qualcomm Atheros                  | 53        | 18.66%  |
| Broadcom                          | 18        | 6.34%   |
| Marvell Technology Group          | 6         | 2.11%   |
| Nvidia                            | 4         | 1.41%   |
| MEDIATEK                          | 4         | 1.41%   |
| TP-Link                           | 3         | 1.06%   |
| Huawei Technologies               | 3         | 1.06%   |
| Sierra Wireless                   | 2         | 0.7%    |
| Ralink Technology                 | 2         | 0.7%    |
| Ralink                            | 2         | 0.7%    |
| Ericsson Business Mobile Networks | 2         | 0.7%    |
| Attansic Technology               | 2         | 0.7%    |
| Qualcomm                          | 1         | 0.35%   |
| JMicron Technology                | 1         | 0.35%   |
| Hewlett-Packard                   | 1         | 0.35%   |
| Google                            | 1         | 0.35%   |
| Dell                              | 1         | 0.35%   |
| Broadcom Limited                  | 1         | 0.35%   |
| ASIX Electronics                  | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 56        | 15.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 4.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 14        | 3.99%   |
| Intel Wireless 7260                                                            | 10        | 2.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 9         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 2.28%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 7         | 1.99%   |
| Intel Centrino Advanced-N 6200                                                 | 7         | 1.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 6         | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 6         | 1.71%   |
| Intel Wireless 8265 / 8275                                                     | 6         | 1.71%   |
| Intel Wireless 8260                                                            | 6         | 1.71%   |
| Intel Wireless 3165                                                            | 5         | 1.42%   |
| Intel Wi-Fi 6 AX200                                                            | 5         | 1.42%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 4         | 1.14%   |
| Intel Wireless 7265                                                            | 4         | 1.14%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.14%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.14%   |
| Intel Centrino Advanced-N 6235                                                 | 4         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 4         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.85%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 0.85%   |
| Intel Centrino Wireless-N 2230                                                 | 3         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 3         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 3         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2         | 0.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2         | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 2         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.57%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.57%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.57%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 2         | 0.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 2         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 2         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 2         | 0.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 0.57%   |
| Intel Centrino Ultimate-N 6300                                                 | 2         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.57%   |
| Ericsson Business Mobile Networks F5521gw                                      | 2         | 0.57%   |
| Broadcom BCM43225 802.11b/g/n                                                  | 2         | 0.57%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.57%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.28%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                            | 1         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 89        | 49.17%  |
| Qualcomm Atheros      | 43        | 23.76%  |
| Realtek Semiconductor | 24        | 13.26%  |
| Broadcom              | 13        | 7.18%   |
| MEDIATEK              | 3         | 1.66%   |
| TP-Link               | 2         | 1.1%    |
| Sierra Wireless       | 2         | 1.1%    |
| Ralink Technology     | 2         | 1.1%    |
| Ralink                | 2         | 1.1%    |
| Hewlett-Packard       | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 14        | 7.69%   |
| Intel Wireless 7260                                                                           | 10        | 5.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 9         | 4.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 7         | 3.85%   |
| Intel Centrino Advanced-N 6200                                                                | 7         | 3.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 6         | 3.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 6         | 3.3%    |
| Intel Wireless 8265 / 8275                                                                    | 6         | 3.3%    |
| Intel Wireless 8260                                                                           | 6         | 3.3%    |
| Intel Wireless 3165                                                                           | 5         | 2.75%   |
| Intel Wi-Fi 6 AX200                                                                           | 5         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 2.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4         | 2.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 4         | 2.2%    |
| Intel Wireless 7265                                                                           | 4         | 2.2%    |
| Intel Centrino Advanced-N 6235                                                                | 4         | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4         | 2.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 1.65%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 1.65%   |
| Intel Centrino Wireless-N 2230                                                                | 3         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 3         | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 3         | 1.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2         | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 2         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 2         | 1.1%    |
| Intel Wireless-AC 9260                                                                        | 2         | 1.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2         | 1.1%    |
| Intel Wi-Fi 6 AX201                                                                           | 2         | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 2         | 1.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 2         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 2         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2         | 1.1%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 2         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                                                | 2         | 1.1%    |
| Broadcom BCM43225 802.11b/g/n                                                                 | 2         | 1.1%    |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                                           | 1         | 0.55%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.55%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.55%   |
| Ralink RT2070 Wireless Adapter                                                                | 1         | 0.55%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.55%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1         | 0.55%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                                      | 1         | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 1         | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 0.55%   |
| Intel Centrino Wireless-N 2200                                                                | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 75        | 46.58%  |
| Intel                    | 43        | 26.71%  |
| Qualcomm Atheros         | 18        | 11.18%  |
| Marvell Technology Group | 6         | 3.73%   |
| Broadcom                 | 6         | 3.73%   |
| Nvidia                   | 4         | 2.48%   |
| Attansic Technology      | 2         | 1.24%   |
| TP-Link                  | 1         | 0.62%   |
| Qualcomm                 | 1         | 0.62%   |
| MediaTek                 | 1         | 0.62%   |
| JMicron Technology       | 1         | 0.62%   |
| Huawei Technologies      | 1         | 0.62%   |
| Broadcom Limited         | 1         | 0.62%   |
| ASIX Electronics         | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 56        | 34.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 10.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 4.91%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 4.91%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 3.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 2.45%   |
| Intel Ethernet Connection I219-V                                               | 4         | 2.45%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 2.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.84%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.23%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 1.23%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.23%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 1.23%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.61%   |
| Qualcomm Router CD-ROM                                                         | 1         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.61%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.61%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.61%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.61%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.61%   |
| MediaTek WP7                                                                   | 1         | 0.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.61%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.61%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.61%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.61%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.61%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.61%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.61%   |
| Huawei JAT-LX1                                                                 | 1         | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.61%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.61%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.61%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.61%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 51.2%   |
| Ethernet | 156       | 46.99%  |
| Modem    | 5         | 1.51%   |
| Unknown  | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 57.63%  |
| Ethernet | 109       | 41.6%   |
| Modem    | 1         | 0.38%   |
| Unknown  | 1         | 0.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 148       | 84.09%  |
| 1     | 25        | 14.2%   |
| 0     | 3         | 1.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 88.14%  |
| Yes  | 21        | 11.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 41.67%  |
| Qualcomm Atheros Communications | 13        | 9.85%   |
| Broadcom                        | 13        | 9.85%   |
| Realtek Semiconductor           | 11        | 8.33%   |
| IMC Networks                    | 8         | 6.06%   |
| Lite-On Technology              | 6         | 4.55%   |
| Cambridge Silicon Radio         | 6         | 4.55%   |
| Hewlett-Packard                 | 5         | 3.79%   |
| Foxconn / Hon Hai               | 4         | 3.03%   |
| Toshiba                         | 3         | 2.27%   |
| Dell                            | 3         | 2.27%   |
| Apple                           | 2         | 1.52%   |
| Ralink                          | 1         | 0.76%   |
| ASUSTek Computer                | 1         | 0.76%   |
| Alps Electric                   | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 22.73%  |
| Intel Bluetooth Device                                                              | 7         | 5.3%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 4.55%   |
| Realtek Bluetooth Radio                                                             | 5         | 3.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 3.79%   |
| Intel AX200 Bluetooth                                                               | 5         | 3.79%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 3.79%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 3.03%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 3.03%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 3.03%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 2.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.27%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.52%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.52%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.52%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.52%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.52%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.76%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.76%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.76%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.76%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.76%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.76%   |
| Lite-On Wireless_Device                                                             | 1         | 0.76%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.76%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.76%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.76%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.76%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.76%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.76%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.76%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.76%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.76%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.76%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.76%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.76%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.76%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.76%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 146       | 68.87%  |
| AMD                 | 31        | 14.62%  |
| Nvidia              | 27        | 12.74%  |
| GN Netcom           | 2         | 0.94%   |
| C-Media Electronics | 2         | 0.94%   |
| SteelSeries ApS     | 1         | 0.47%   |
| Plantronics         | 1         | 0.47%   |
| Mark of the Unicorn | 1         | 0.47%   |
| Unknown             | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 8.76%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 7.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 5.98%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 4.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 3.59%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.79%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.99%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 1.59%   |
| Nvidia Audio device                                                                               | 4         | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.59%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.2%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.8%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.8%    |
| C-Media Electronics USB Advanced Audio Device                                                     | 2         | 0.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.8%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.8%    |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.4%    |
| Plantronics BT600                                                                                 | 1         | 0.4%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.4%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.4%    |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.4%    |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.4%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.4%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.4%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.4%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.4%    |
| Mark of the Unicorn M Series                                                                      | 1         | 0.4%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.4%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.4%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.4%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.4%    |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.4%    |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.4%    |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 52        | 24.41%  |
| SK Hynix            | 41        | 19.25%  |
| Unknown             | 28        | 13.15%  |
| Micron Technology   | 24        | 11.27%  |
| Kingston            | 20        | 9.39%   |
| Crucial             | 10        | 4.69%   |
| Ramaxel Technology  | 6         | 2.82%   |
| A-DATA Technology   | 5         | 2.35%   |
| Smart               | 4         | 1.88%   |
| Unknown (ABCD)      | 3         | 1.41%   |
| Elpida              | 3         | 1.41%   |
| Transcend           | 2         | 0.94%   |
| Teikon              | 2         | 0.94%   |
| Nanya Technology    | 2         | 0.94%   |
| Unknown             | 2         | 0.94%   |
| Unknown (F301)      | 1         | 0.47%   |
| TRS STAR            | 1         | 0.47%   |
| Team                | 1         | 0.47%   |
| PNY                 | 1         | 0.47%   |
| Patriot             | 1         | 0.47%   |
| High Bridge         | 1         | 0.47%   |
| Corsair             | 1         | 0.47%   |
| Avant               | 1         | 0.47%   |
| Apacer              | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 2.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 2.15%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.72%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 4         | 1.72%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 4         | 1.72%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 3         | 1.29%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 3         | 1.29%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 1.29%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.29%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 2         | 0.86%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 0.86%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s              | 2         | 0.86%   |
| SK Hynix RAM HMT851S6AMR6A-PB 4096MB Chip DDR3 1600MT/s             | 2         | 0.86%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.86%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.86%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 2         | 0.86%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 2         | 0.86%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.86%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 0.86%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 0.86%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 2         | 0.86%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 0.86%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s               | 2         | 0.86%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.86%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.86%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 0.86%   |
| Unknown                                                             | 2         | 0.86%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 1         | 0.43%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DRAM                                  | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                           | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                              | 1         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DRAM                               | 1         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 0.43%   |
| Unknown RAM Module 1024MB Chip DDR 533MT/s                          | 1         | 0.43%   |
| Unknown (F301) RAM G2BT-4AFP00 16384MB SODIMM DDR4 2133MT/s         | 1         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 0.43%   |
| TRS STAR RAM Module 8GB SODIMM DDR3 1333MT/s                        | 1         | 0.43%   |
| Transcend RAM Module 1024MB SODIMM DDR 667MT/s                      | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 94        | 53.41%  |
| DDR4    | 51        | 28.98%  |
| DDR2    | 14        | 7.95%   |
| SDRAM   | 4         | 2.27%   |
| LPDDR4  | 4         | 2.27%   |
| DRAM    | 3         | 1.7%    |
| DDR     | 3         | 1.7%    |
| LPDDR3  | 2         | 1.14%   |
| Unknown | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 167       | 95.98%  |
| Row Of Chips | 3         | 1.72%   |
| Chip         | 3         | 1.72%   |
| DIMM         | 1         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 80        | 40.2%   |
| 8192  | 54        | 27.14%  |
| 2048  | 40        | 20.1%   |
| 16384 | 12        | 6.03%   |
| 1024  | 12        | 6.03%   |
| 32768 | 1         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 57        | 29.53%  |
| 2667    | 22        | 11.4%   |
| 1334    | 21        | 10.88%  |
| 3200    | 14        | 7.25%   |
| 2400    | 13        | 6.74%   |
| 1333    | 13        | 6.74%   |
| Unknown | 13        | 6.74%   |
| 667     | 9         | 4.66%   |
| 2133    | 7         | 3.63%   |
| 1067    | 6         | 3.11%   |
| 800     | 4         | 2.07%   |
| 4199    | 3         | 1.55%   |
| 3266    | 3         | 1.55%   |
| 1867    | 2         | 1.04%   |
| 533     | 2         | 1.04%   |
| 8400    | 1         | 0.52%   |
| 4267    | 1         | 0.52%   |
| 1777    | 1         | 0.52%   |
| 166     | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 50%     |
| HP LaserJet P2055 series           | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 26.57%  |
| Acer                                   | 15        | 10.49%  |
| Realtek Semiconductor                  | 12        | 8.39%   |
| Sunplus Innovation Technology          | 11        | 7.69%   |
| Microdia                               | 9         | 6.29%   |
| IMC Networks                           | 8         | 5.59%   |
| Lite-On Technology                     | 7         | 4.9%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.9%    |
| Suyin                                  | 6         | 4.2%    |
| Lenovo                                 | 5         | 3.5%    |
| Z-Star Microelectronics                | 3         | 2.1%    |
| Syntek                                 | 3         | 2.1%    |
| Quanta                                 | 3         | 2.1%    |
| Silicon Motion                         | 2         | 1.4%    |
| Ricoh                                  | 2         | 1.4%    |
| Xiongmai                               | 1         | 0.7%    |
| WaveRider Communications               | 1         | 0.7%    |
| Samsung Electronics                    | 1         | 0.7%    |
| Primax Electronics                     | 1         | 0.7%    |
| Logitech                               | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| Goodong Industry                       | 1         | 0.7%    |
| DJKANA1BIELN56                         | 1         | 0.7%    |
| Cubeternet                             | 1         | 0.7%    |
| Apple                                  | 1         | 0.7%    |
| Alcor Micro                            | 1         | 0.7%    |
| 8SSC20F27145V1SR1CF0AN1                | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 8         | 5.59%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 2.8%    |
| Lite-On Integrated Camera                                   | 4         | 2.8%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 2.8%    |
| Chicony USB 2.0 Camera                                      | 4         | 2.8%    |
| Syntek EasyCamera                                           | 3         | 2.1%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 2.1%    |
| Chicony TOSHIBA Web Camera - HD                             | 3         | 2.1%    |
| Chicony HP Truevision HD camera                             | 3         | 2.1%    |
| Acer Lenovo EasyCamera                                      | 3         | 2.1%    |
| Acer BisonCam, NB Pro                                       | 3         | 2.1%    |
| Sunplus HD WebCam                                           | 2         | 1.4%    |
| Sunplus ASUS USB2.0 Webcam                                  | 2         | 1.4%    |
| Ricoh USB2.0 Camera                                         | 2         | 1.4%    |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.4%    |
| Realtek USB Camera                                          | 2         | 1.4%    |
| Realtek Integrated_Webcam_HD                                | 2         | 1.4%    |
| Quanta VGA WebCam                                           | 2         | 1.4%    |
| Microdia Integrated Webcam                                  | 2         | 1.4%    |
| Lenovo Integrated Webcam [R5U877]                           | 2         | 1.4%    |
| Lenovo Integrated Webcam                                    | 2         | 1.4%    |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 1.4%    |
| Chicony HD WebCam                                           | 2         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 1.4%    |
| Acer SunplusIT INC. Integrated Camera                       | 2         | 1.4%    |
| Z-Star WebCam SCB-1900N                                     | 1         | 0.7%    |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.7%    |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.7%    |
| Xiongmai web camera                                         | 1         | 0.7%    |
| WaveRider USB Live camera                                   | 1         | 0.7%    |
| Suyin Sony Visual Communication Camera                      | 1         | 0.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.7%    |
| Suyin 1.3M HD WebCam                                        | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.7%    |
| Sunplus Dell Integrated Webcam                              | 1         | 0.7%    |
| Silicon Motion Web Camera                                   | 1         | 0.7%    |
| Silicon Motion Silicon Motion Camera                        | 1         | 0.7%    |
| Samsung Galaxy A5 (MTP)                                     | 1         | 0.7%    |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 0.7%    |
| Realtek Lenovo EasyCamera                                   | 1         | 0.7%    |
| Realtek Integrated Webcam                                   | 1         | 0.7%    |
| Realtek HD Webcam - Realtek                                 | 1         | 0.7%    |
| Realtek HD WebCam                                           | 1         | 0.7%    |
| Realtek 2SF001                                              | 1         | 0.7%    |
| Quanta HP Wide Vision HD Camera                             | 1         | 0.7%    |
| Primax Dell Laptop Integrated Webcam 2Mpix                  | 1         | 0.7%    |
| Microdia Webcam Vitade AF                                   | 1         | 0.7%    |
| Microdia WebCam SC-13HDL12639P                              | 1         | 0.7%    |
| Microdia Webcam                                             | 1         | 0.7%    |
| Microdia USB 2.0 Camera                                     | 1         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 0.7%    |
| Microdia Integrated_Webcam_HD                               | 1         | 0.7%    |
| Microdia HP Webcam-101                                      | 1         | 0.7%    |
| Logitech StreamCam                                          | 1         | 0.7%    |
| Lite-On HP Wide Vision FHD Camera                           | 1         | 0.7%    |
| Lite-On HP HD Webcam                                        | 1         | 0.7%    |
| Lite-On HP HD Camera                                        | 1         | 0.7%    |
| Lenovo UVC Camera                                           | 1         | 0.7%    |
| Importek TOSHIBA Web Camera - HD                            | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 43.33%  |
| Upek                       | 5         | 16.67%  |
| Synaptics                  | 4         | 13.33%  |
| Shenzhen Goodix Technology | 3         | 10%     |
| LighTuning Technology      | 2         | 6.67%   |
| AuthenTec                  | 2         | 6.67%   |
| STMicroelectronics         | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 3         | 10%     |
| Validity Sensors Synaptics WBDI                            | 3         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 6.67%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 3.33%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 3.33%   |
| Validity Sensors Fingerprint scanner                       | 1         | 3.33%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 3.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.33%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 3.33%   |
| LighTuning Fingerprint Reader                              | 1         | 3.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.33%   |
| AuthenTec AES2810                                          | 1         | 3.33%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 3.33%   |
| Unknown                                                    | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 36.36%  |
| Lenovo      | 3         | 27.27%  |
| Broadcom    | 3         | 27.27%  |
| O2 Micro    | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 36.36%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 18.18%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 111       | 62.01%  |
| 1     | 54        | 30.17%  |
| 2     | 14        | 7.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 32        | 39.51%  |
| Fingerprint reader       | 30        | 37.04%  |
| Chipcard                 | 10        | 12.35%  |
| Storage                  | 3         | 3.7%    |
| Net/wireless             | 2         | 2.47%   |
| Multimedia controller    | 2         | 2.47%   |
| Communication controller | 1         | 1.23%   |
| Bluetooth                | 1         | 1.23%   |

