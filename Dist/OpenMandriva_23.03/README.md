OpenMandriva 23.03 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.03.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_23.03/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_23.03/Notebook/README.md).

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

Total: 1880

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z97-K                       | Desktop     | [849ecb3c82](https://linux-hardware.org/?probe=849ecb3c82) | Sep 06, 2023 |
| Toshiba       | Satellite C850-1DZ          | Notebook    | [cf916c2f33](https://linux-hardware.org/?probe=cf916c2f33) | Sep 05, 2023 |
| Dell          | Precision M4800             | Notebook    | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [c2da44c04f](https://linux-hardware.org/?probe=c2da44c04f) | Sep 04, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [922ff6eddb](https://linux-hardware.org/?probe=922ff6eddb) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [6ca26976b6](https://linux-hardware.org/?probe=6ca26976b6) | Sep 04, 2023 |
| ASRock        | FM2A78M-HD+                 | Desktop     | [a2d8c14a71](https://linux-hardware.org/?probe=a2d8c14a71) | Sep 03, 2023 |
| Intel         | H81                         | Desktop     | [75aabbccf5](https://linux-hardware.org/?probe=75aabbccf5) | Sep 03, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| Biostar       | N68S3B                      | Desktop     | [fc063709f7](https://linux-hardware.org/?probe=fc063709f7) | Sep 02, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | Notebook    | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| Intel         | H110                        | Desktop     | [05970c6811](https://linux-hardware.org/?probe=05970c6811) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| Biostar       | G41D3                       | Desktop     | [0d4f48c335](https://linux-hardware.org/?probe=0d4f48c335) | Aug 31, 2023 |
| HP            | 3047h                       | Desktop     | [5a35a1ebd1](https://linux-hardware.org/?probe=5a35a1ebd1) | Aug 30, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [c95eb85e58](https://linux-hardware.org/?probe=c95eb85e58) | Aug 30, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [04424409ef](https://linux-hardware.org/?probe=04424409ef) | Aug 29, 2023 |
| Intel         | DG45ID AAE27729-312         | Desktop     | [add370815d](https://linux-hardware.org/?probe=add370815d) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| ASUSTek       | M3N78-EH                    | Desktop     | [c0fb869905](https://linux-hardware.org/?probe=c0fb869905) | Aug 29, 2023 |
| Sony          | VPCEB43FG                   | Notebook    | [99812c6c56](https://linux-hardware.org/?probe=99812c6c56) | Aug 28, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bf483bc8d3](https://linux-hardware.org/?probe=bf483bc8d3) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ded7284a37](https://linux-hardware.org/?probe=ded7284a37) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [248f2a9745](https://linux-hardware.org/?probe=248f2a9745) | Aug 27, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [4e72e77dc6](https://linux-hardware.org/?probe=4e72e77dc6) | Aug 27, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [ff832aca4a](https://linux-hardware.org/?probe=ff832aca4a) | Aug 26, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [b407522eb0](https://linux-hardware.org/?probe=b407522eb0) | Aug 25, 2023 |
| Dell          | G5 5590                     | Notebook    | [c13a60889c](https://linux-hardware.org/?probe=c13a60889c) | Aug 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f37fa5636](https://linux-hardware.org/?probe=3f37fa5636) | Aug 25, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [928ea69caf](https://linux-hardware.org/?probe=928ea69caf) | Aug 24, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [109de7a1ae](https://linux-hardware.org/?probe=109de7a1ae) | Aug 23, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3f2ff7e9c7](https://linux-hardware.org/?probe=3f2ff7e9c7) | Aug 22, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [0bba785aee](https://linux-hardware.org/?probe=0bba785aee) | Aug 21, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [33ad1ac951](https://linux-hardware.org/?probe=33ad1ac951) | Aug 21, 2023 |
| Dell          | Latitude E5520              | Notebook    | [35f02a2ea2](https://linux-hardware.org/?probe=35f02a2ea2) | Aug 19, 2023 |
| Dell          | Latitude E6500              | Notebook    | [5d1f16198a](https://linux-hardware.org/?probe=5d1f16198a) | Aug 18, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c8eaccabf2](https://linux-hardware.org/?probe=c8eaccabf2) | Aug 18, 2023 |
| Dell          | 0XFWHV A00                  | Desktop     | [0ddde115f9](https://linux-hardware.org/?probe=0ddde115f9) | Aug 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [945643bffa](https://linux-hardware.org/?probe=945643bffa) | Aug 16, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [fb77a4db86](https://linux-hardware.org/?probe=fb77a4db86) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8f1803298d](https://linux-hardware.org/?probe=8f1803298d) | Aug 15, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [b74079b9cd](https://linux-hardware.org/?probe=b74079b9cd) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | Notebook    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [d7f0d8e9cd](https://linux-hardware.org/?probe=d7f0d8e9cd) | Aug 15, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [b2ee5cedbe](https://linux-hardware.org/?probe=b2ee5cedbe) | Aug 14, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [1bb822c058](https://linux-hardware.org/?probe=1bb822c058) | Aug 13, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c24273512e](https://linux-hardware.org/?probe=c24273512e) | Aug 13, 2023 |
| Lenovo        | ThinkPad E595 20NF0006GE    | Notebook    | [c9c068e82b](https://linux-hardware.org/?probe=c9c068e82b) | Aug 13, 2023 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [42772eba76](https://linux-hardware.org/?probe=42772eba76) | Aug 13, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [60746f5bad](https://linux-hardware.org/?probe=60746f5bad) | Aug 13, 2023 |
| Sony          | SVE1112M1EW                 | Notebook    | [353fb8c6ff](https://linux-hardware.org/?probe=353fb8c6ff) | Aug 13, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [61908d704c](https://linux-hardware.org/?probe=61908d704c) | Aug 13, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [1cb123d894](https://linux-hardware.org/?probe=1cb123d894) | Aug 12, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [a32f4633c2](https://linux-hardware.org/?probe=a32f4633c2) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | Notebook    | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | Notebook    | [1b7c441369](https://linux-hardware.org/?probe=1b7c441369) | Aug 12, 2023 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [edd47d65b6](https://linux-hardware.org/?probe=edd47d65b6) | Aug 12, 2023 |
| ZOTAC         | ZBOXNANO-ID67/ID68/ID69     | Mini pc     | [169c6d3b85](https://linux-hardware.org/?probe=169c6d3b85) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [8903899ce9](https://linux-hardware.org/?probe=8903899ce9) | Aug 11, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| HP            | x360 310 G2 PC              | Convertible | [a60b6f6ca2](https://linux-hardware.org/?probe=a60b6f6ca2) | Aug 11, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [4856b9b32f](https://linux-hardware.org/?probe=4856b9b32f) | Aug 11, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [fad80ecff3](https://linux-hardware.org/?probe=fad80ecff3) | Aug 11, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | Notebook    | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Google        | Kip                         | Notebook    | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| HP            | 2215                        | Desktop     | [40ace58487](https://linux-hardware.org/?probe=40ace58487) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | Notebook    | [6802a19338](https://linux-hardware.org/?probe=6802a19338) | Aug 10, 2023 |
| Acer          | Extensa 5630                | Notebook    | [1cc3eaf69a](https://linux-hardware.org/?probe=1cc3eaf69a) | Aug 10, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [279ed1e2d5](https://linux-hardware.org/?probe=279ed1e2d5) | Aug 10, 2023 |
| MSI           | A68HM-E33                   | Desktop     | [be692e44b5](https://linux-hardware.org/?probe=be692e44b5) | Aug 10, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [e3cf4cec26](https://linux-hardware.org/?probe=e3cf4cec26) | Aug 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d073a53c85](https://linux-hardware.org/?probe=d073a53c85) | Aug 08, 2023 |
| Lenovo        | ThinkPad X220 4290C37       | Notebook    | [125ac0cbd3](https://linux-hardware.org/?probe=125ac0cbd3) | Aug 08, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [84c3eefc94](https://linux-hardware.org/?probe=84c3eefc94) | Aug 08, 2023 |
| HP            | Laptop 14-dq3xxx            | Notebook    | [c547f01fbb](https://linux-hardware.org/?probe=c547f01fbb) | Aug 08, 2023 |
| Acer          | AO756                       | Notebook    | [1ea1658ac0](https://linux-hardware.org/?probe=1ea1658ac0) | Aug 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c04ac90ce8](https://linux-hardware.org/?probe=c04ac90ce8) | Aug 07, 2023 |
| Digiboard     | NM70-I                      | Desktop     | [280ee6d8fe](https://linux-hardware.org/?probe=280ee6d8fe) | Aug 07, 2023 |
| ASUSTek       | P5GDC                       | Desktop     | [82fefe395d](https://linux-hardware.org/?probe=82fefe395d) | Aug 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [691c44286e](https://linux-hardware.org/?probe=691c44286e) | Aug 06, 2023 |
| MSI           | H310M PRO-D                 | Desktop     | [201844f73e](https://linux-hardware.org/?probe=201844f73e) | Aug 06, 2023 |
| GPD           | G1618-03                    | Notebook    | [070d548515](https://linux-hardware.org/?probe=070d548515) | Aug 06, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [27792f16e2](https://linux-hardware.org/?probe=27792f16e2) | Aug 06, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [af35c9ce49](https://linux-hardware.org/?probe=af35c9ce49) | Aug 05, 2023 |
| Dell          | Precision M2800             | Notebook    | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| Medion        | B550A4-EM                   | Desktop     | [f1bf2b93c1](https://linux-hardware.org/?probe=f1bf2b93c1) | Aug 05, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [9db6bfdcfa](https://linux-hardware.org/?probe=9db6bfdcfa) | Aug 05, 2023 |
| Intel         | H81                         | Desktop     | [4441a1a1ca](https://linux-hardware.org/?probe=4441a1a1ca) | Aug 05, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [ba3a2e1773](https://linux-hardware.org/?probe=ba3a2e1773) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S9R500    | Notebook    | [3624b5e366](https://linux-hardware.org/?probe=3624b5e366) | Aug 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [e7810a04a9](https://linux-hardware.org/?probe=e7810a04a9) | Aug 04, 2023 |
| Acer          | Aspire 8943G                | Notebook    | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| ASRock        | G31M-S                      | Desktop     | [02bb341cc9](https://linux-hardware.org/?probe=02bb341cc9) | Aug 04, 2023 |
| GFAST         | N150                        | Notebook    | [bccc2874df](https://linux-hardware.org/?probe=bccc2874df) | Aug 04, 2023 |
| MANCER        | A320M-DA 1006               | Desktop     | [573affec7b](https://linux-hardware.org/?probe=573affec7b) | Aug 04, 2023 |
| HP            | 844C                        | Desktop     | [36185008dc](https://linux-hardware.org/?probe=36185008dc) | Aug 03, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [3acda608a1](https://linux-hardware.org/?probe=3acda608a1) | Aug 03, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [a3401e5a4b](https://linux-hardware.org/?probe=a3401e5a4b) | Aug 03, 2023 |
| HP            | 8767 A                      | Desktop     | [2cf5a8cce4](https://linux-hardware.org/?probe=2cf5a8cce4) | Aug 03, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [c9e70623fc](https://linux-hardware.org/?probe=c9e70623fc) | Aug 02, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [522acc7a8e](https://linux-hardware.org/?probe=522acc7a8e) | Aug 02, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [52c54dc66e](https://linux-hardware.org/?probe=52c54dc66e) | Aug 02, 2023 |
| Dell          | Precision M4500             | Notebook    | [b425204301](https://linux-hardware.org/?probe=b425204301) | Aug 02, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | Desktop     | [5cbdefa7c5](https://linux-hardware.org/?probe=5cbdefa7c5) | Aug 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [70c8bcf589](https://linux-hardware.org/?probe=70c8bcf589) | Aug 02, 2023 |
| MSI           | Modern 15 A10M              | Notebook    | [bab451a11e](https://linux-hardware.org/?probe=bab451a11e) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| ASRock        | H410M-HDV/M.2               | Desktop     | [71a11bdffd](https://linux-hardware.org/?probe=71a11bdffd) | Aug 02, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ef89d48d6](https://linux-hardware.org/?probe=7ef89d48d6) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [be8a59432a](https://linux-hardware.org/?probe=be8a59432a) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [e51e841817](https://linux-hardware.org/?probe=e51e841817) | Jul 31, 2023 |
| Dell          | Latitude E6430              | Notebook    | [9dcf92cce9](https://linux-hardware.org/?probe=9dcf92cce9) | Jul 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e11390bc86](https://linux-hardware.org/?probe=e11390bc86) | Jul 31, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [a0394c8f0b](https://linux-hardware.org/?probe=a0394c8f0b) | Jul 30, 2023 |
| MSI           | MS-B1591                    | Desktop     | [9bdfd87437](https://linux-hardware.org/?probe=9bdfd87437) | Jul 30, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [eb332b024d](https://linux-hardware.org/?probe=eb332b024d) | Jul 30, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [7d262746c9](https://linux-hardware.org/?probe=7d262746c9) | Jul 30, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [18f28e3fb6](https://linux-hardware.org/?probe=18f28e3fb6) | Jul 29, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | Notebook    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [be08c309d2](https://linux-hardware.org/?probe=be08c309d2) | Jul 29, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a70852def5](https://linux-hardware.org/?probe=a70852def5) | Jul 29, 2023 |
| Lenovo        | 3111 NOK                    | Desktop     | [bced6fb88a](https://linux-hardware.org/?probe=bced6fb88a) | Jul 29, 2023 |
| HP            | 86F3 00100                  | All in one  | [485fcbfa5d](https://linux-hardware.org/?probe=485fcbfa5d) | Jul 29, 2023 |
| ASUSTek       | X102BA                      | Notebook    | [488aa4c5b4](https://linux-hardware.org/?probe=488aa4c5b4) | Jul 29, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [4d3abb525e](https://linux-hardware.org/?probe=4d3abb525e) | Jul 28, 2023 |
| A14CR         | Unknown                     | Notebook    | [4ceb4f6761](https://linux-hardware.org/?probe=4ceb4f6761) | Jul 27, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d6a4c29101](https://linux-hardware.org/?probe=d6a4c29101) | Jul 27, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4fc2e4c331](https://linux-hardware.org/?probe=4fc2e4c331) | Jul 26, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [5af2ea35ee](https://linux-hardware.org/?probe=5af2ea35ee) | Jul 26, 2023 |
| Lenovo        | ThinkPad E555 20DH0027UK    | Notebook    | [b7bf821032](https://linux-hardware.org/?probe=b7bf821032) | Jul 26, 2023 |
| ASRock        | B85M                        | Desktop     | [d69487eb8d](https://linux-hardware.org/?probe=d69487eb8d) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [3cb7454711](https://linux-hardware.org/?probe=3cb7454711) | Jul 25, 2023 |
| Positivo      | G800                        | Notebook    | [5dd0f188f8](https://linux-hardware.org/?probe=5dd0f188f8) | Jul 25, 2023 |
| ASUSTek       | P50IJ                       | Notebook    | [d8aff1255a](https://linux-hardware.org/?probe=d8aff1255a) | Jul 25, 2023 |
| Dell          | 0RY206                      | Desktop     | [5f16b7ecda](https://linux-hardware.org/?probe=5f16b7ecda) | Jul 25, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [4b9680f094](https://linux-hardware.org/?probe=4b9680f094) | Jul 25, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [6fc7661aae](https://linux-hardware.org/?probe=6fc7661aae) | Jul 25, 2023 |
| HP            | 1495                        | Desktop     | [99072e94e8](https://linux-hardware.org/?probe=99072e94e8) | Jul 25, 2023 |
| MSI           | 2A9C                        | Desktop     | [83e6501c96](https://linux-hardware.org/?probe=83e6501c96) | Jul 25, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [8f4eb83f05](https://linux-hardware.org/?probe=8f4eb83f05) | Jul 25, 2023 |
| ZOTAC         | ZBOX-BI322                  | Mini pc     | [f595927b7b](https://linux-hardware.org/?probe=f595927b7b) | Jul 25, 2023 |
| HP            | 8350                        | Desktop     | [51c4120395](https://linux-hardware.org/?probe=51c4120395) | Jul 25, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a68492f27e](https://linux-hardware.org/?probe=a68492f27e) | Jul 25, 2023 |
| Toshiba       | IS 1442                     | Notebook    | [3a66df4c2d](https://linux-hardware.org/?probe=3a66df4c2d) | Jul 25, 2023 |
| Dell          | Latitude 7490               | Notebook    | [066e3b9518](https://linux-hardware.org/?probe=066e3b9518) | Jul 25, 2023 |
| PCWare        | IPMH61R3 8MB                | Desktop     | [dcbde0a01d](https://linux-hardware.org/?probe=dcbde0a01d) | Jul 24, 2023 |
| HP            | 198E                        | Desktop     | [c2f7b19d13](https://linux-hardware.org/?probe=c2f7b19d13) | Jul 24, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [06e3fae658](https://linux-hardware.org/?probe=06e3fae658) | Jul 24, 2023 |
| HP            | 212B                        | Desktop     | [3e033bf376](https://linux-hardware.org/?probe=3e033bf376) | Jul 24, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [41246e91c0](https://linux-hardware.org/?probe=41246e91c0) | Jul 24, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [7f6b8fc2db](https://linux-hardware.org/?probe=7f6b8fc2db) | Jul 23, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [e382c4d40c](https://linux-hardware.org/?probe=e382c4d40c) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [8982fa467c](https://linux-hardware.org/?probe=8982fa467c) | Jul 23, 2023 |
| ASUSTek       | NARRA                       | Desktop     | [2c0dc7397a](https://linux-hardware.org/?probe=2c0dc7397a) | Jul 23, 2023 |
| HP            | Notebook                    | Notebook    | [1a4ba0be2f](https://linux-hardware.org/?probe=1a4ba0be2f) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | Notebook    | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ecce500445](https://linux-hardware.org/?probe=ecce500445) | Jul 22, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [d387ed9d0c](https://linux-hardware.org/?probe=d387ed9d0c) | Jul 22, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [b5fe1f6fca](https://linux-hardware.org/?probe=b5fe1f6fca) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| Packard Be... | EasyNote SL65               | Notebook    | [f66a4415f3](https://linux-hardware.org/?probe=f66a4415f3) | Jul 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [55f5c5bd48](https://linux-hardware.org/?probe=55f5c5bd48) | Jul 21, 2023 |
| Chuwi         | M01ALWR310-ADA90A           | Mini pc     | [0274c94523](https://linux-hardware.org/?probe=0274c94523) | Jul 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fe0c696d47](https://linux-hardware.org/?probe=fe0c696d47) | Jul 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [556e4cd2c9](https://linux-hardware.org/?probe=556e4cd2c9) | Jul 21, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [c058e8c58e](https://linux-hardware.org/?probe=c058e8c58e) | Jul 20, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [08fccc55c8](https://linux-hardware.org/?probe=08fccc55c8) | Jul 20, 2023 |
| ASUSTek       | M11AD                       | Desktop     | [8a8cb2c3e4](https://linux-hardware.org/?probe=8a8cb2c3e4) | Jul 20, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| ASRock        | G41C-GS R2.0                | Desktop     | [3ed4a6a897](https://linux-hardware.org/?probe=3ed4a6a897) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [cacf2d88c9](https://linux-hardware.org/?probe=cacf2d88c9) | Jul 19, 2023 |
| LG Electro... | P420-G.BE42P1               | Notebook    | [9dea573574](https://linux-hardware.org/?probe=9dea573574) | Jul 18, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [96f08b7598](https://linux-hardware.org/?probe=96f08b7598) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 20RDS1G700     | Notebook    | [6ad3194fd9](https://linux-hardware.org/?probe=6ad3194fd9) | Jul 18, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [4d18b60338](https://linux-hardware.org/?probe=4d18b60338) | Jul 18, 2023 |
| AZW           | Gemini J45                  | Desktop     | [0ed36a4286](https://linux-hardware.org/?probe=0ed36a4286) | Jul 18, 2023 |
| ASUSTek       | K46CB                       | Notebook    | [144d523bf1](https://linux-hardware.org/?probe=144d523bf1) | Jul 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [babb224527](https://linux-hardware.org/?probe=babb224527) | Jul 18, 2023 |
| HP            | G42                         | Notebook    | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f4bc253638](https://linux-hardware.org/?probe=f4bc253638) | Jul 17, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [a62fb79aac](https://linux-hardware.org/?probe=a62fb79aac) | Jul 17, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [082165532b](https://linux-hardware.org/?probe=082165532b) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | Notebook    | [6d453b900a](https://linux-hardware.org/?probe=6d453b900a) | Jul 17, 2023 |
| HP            | 18E8                        | Desktop     | [606aa1f34d](https://linux-hardware.org/?probe=606aa1f34d) | Jul 16, 2023 |
| Toshiba       | TECRA A10                   | Notebook    | [0740ca470e](https://linux-hardware.org/?probe=0740ca470e) | Jul 16, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [f2432a7a2a](https://linux-hardware.org/?probe=f2432a7a2a) | Jul 15, 2023 |
| Dell          | 073MMW A03                  | Desktop     | [f76738403e](https://linux-hardware.org/?probe=f76738403e) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| Lenovo        | ThinkPad T400 6474C53       | Notebook    | [e9db1ea8a6](https://linux-hardware.org/?probe=e9db1ea8a6) | Jul 15, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [a4a4102548](https://linux-hardware.org/?probe=a4a4102548) | Jul 15, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdc2d91a25](https://linux-hardware.org/?probe=fdc2d91a25) | Jul 15, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [252f8adf16](https://linux-hardware.org/?probe=252f8adf16) | Jul 15, 2023 |
| HP            | 83EB                        | All in one  | [9a1012bd0d](https://linux-hardware.org/?probe=9a1012bd0d) | Jul 14, 2023 |
| Packard Be... | EasyNote LM85               | Notebook    | [3efd87a0d8](https://linux-hardware.org/?probe=3efd87a0d8) | Jul 14, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [4df76c784c](https://linux-hardware.org/?probe=4df76c784c) | Jul 13, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [23fef6418b](https://linux-hardware.org/?probe=23fef6418b) | Jul 13, 2023 |
| Acer          | Veriton E430G               | Desktop     | [f52d631cce](https://linux-hardware.org/?probe=f52d631cce) | Jul 13, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [be2db3ecfa](https://linux-hardware.org/?probe=be2db3ecfa) | Jul 13, 2023 |
| Dell          | 0WC7KF A00                  | All in one  | [71309341ec](https://linux-hardware.org/?probe=71309341ec) | Jul 13, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [6130474cb1](https://linux-hardware.org/?probe=6130474cb1) | Jul 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d2dd2ac514](https://linux-hardware.org/?probe=d2dd2ac514) | Jul 13, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4e99483733](https://linux-hardware.org/?probe=4e99483733) | Jul 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e241cdbe45](https://linux-hardware.org/?probe=e241cdbe45) | Jul 12, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [ce55d97846](https://linux-hardware.org/?probe=ce55d97846) | Jul 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Dell          | Inspiron 5749               | Notebook    | [0421d22945](https://linux-hardware.org/?probe=0421d22945) | Jul 11, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [68ee3dff51](https://linux-hardware.org/?probe=68ee3dff51) | Jul 11, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [1ed238ea9b](https://linux-hardware.org/?probe=1ed238ea9b) | Jul 11, 2023 |
| Lenovo        | ThinkPad T430 23501B3       | Notebook    | [8f1d64206e](https://linux-hardware.org/?probe=8f1d64206e) | Jul 11, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [a714d595da](https://linux-hardware.org/?probe=a714d595da) | Jul 10, 2023 |
| Unknown       | 1.0                         | Desktop     | [dcf11d8f40](https://linux-hardware.org/?probe=dcf11d8f40) | Jul 10, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [9a58539b66](https://linux-hardware.org/?probe=9a58539b66) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [84738fcbb3](https://linux-hardware.org/?probe=84738fcbb3) | Jul 10, 2023 |
| Dell          | Latitude 3490               | Notebook    | [67de502259](https://linux-hardware.org/?probe=67de502259) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [96ca518dc6](https://linux-hardware.org/?probe=96ca518dc6) | Jul 09, 2023 |
| AZW           | U55                         | Mini pc     | [274a292b6d](https://linux-hardware.org/?probe=274a292b6d) | Jul 09, 2023 |
| Alienware     | 17                          | Notebook    | [90e6911a60](https://linux-hardware.org/?probe=90e6911a60) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6a3712ec9](https://linux-hardware.org/?probe=c6a3712ec9) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [26896deb1e](https://linux-hardware.org/?probe=26896deb1e) | Jul 09, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [a29509646a](https://linux-hardware.org/?probe=a29509646a) | Jul 08, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [d6a3964ff7](https://linux-hardware.org/?probe=d6a3964ff7) | Jul 08, 2023 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [f36d062c95](https://linux-hardware.org/?probe=f36d062c95) | Jul 08, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Acer          | TravelMate 5335             | Notebook    | [7422cf6091](https://linux-hardware.org/?probe=7422cf6091) | Jul 08, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [df243ca59d](https://linux-hardware.org/?probe=df243ca59d) | Jul 08, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [1cc2699f88](https://linux-hardware.org/?probe=1cc2699f88) | Jul 08, 2023 |
| HP            | 158B                        | Desktop     | [aad7455bc5](https://linux-hardware.org/?probe=aad7455bc5) | Jul 08, 2023 |
| Toshiba       | dynabook R73/Y              | Notebook    | [37e3897f65](https://linux-hardware.org/?probe=37e3897f65) | Jul 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [ac0f0dd893](https://linux-hardware.org/?probe=ac0f0dd893) | Jul 08, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [05d0b7e769](https://linux-hardware.org/?probe=05d0b7e769) | Jul 07, 2023 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [0b81f2e9b0](https://linux-hardware.org/?probe=0b81f2e9b0) | Jul 07, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [de87cf7e95](https://linux-hardware.org/?probe=de87cf7e95) | Jul 07, 2023 |
| Medion        | Unknown                     | Notebook    | [8fd3bc8734](https://linux-hardware.org/?probe=8fd3bc8734) | Jul 07, 2023 |
| Dell          | 09D2HH A00                  | Desktop     | [2885be7e12](https://linux-hardware.org/?probe=2885be7e12) | Jul 07, 2023 |
| Google        | Lick                        | Notebook    | [aa3d137fcf](https://linux-hardware.org/?probe=aa3d137fcf) | Jul 07, 2023 |
| HP            | 0A50h                       | Desktop     | [125782672d](https://linux-hardware.org/?probe=125782672d) | Jul 06, 2023 |
| Dell          | Latitude E5450              | Notebook    | [0a1677c02e](https://linux-hardware.org/?probe=0a1677c02e) | Jul 06, 2023 |
| Toshiba       | Satellite P200D             | Notebook    | [609a275664](https://linux-hardware.org/?probe=609a275664) | Jul 06, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [e21418b71f](https://linux-hardware.org/?probe=e21418b71f) | Jul 06, 2023 |
| HP            | 212A                        | Desktop     | [7f7a7fa2e1](https://linux-hardware.org/?probe=7f7a7fa2e1) | Jul 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [037db5066a](https://linux-hardware.org/?probe=037db5066a) | Jul 05, 2023 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [d3738bf0c4](https://linux-hardware.org/?probe=d3738bf0c4) | Jul 05, 2023 |
| HP            | 550                         | Notebook    | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [5b561a0e00](https://linux-hardware.org/?probe=5b561a0e00) | Jul 05, 2023 |
| Packard Be... | IPOWER                      | Notebook    | [3c116708b4](https://linux-hardware.org/?probe=3c116708b4) | Jul 05, 2023 |
| Standard      | ECT                         | Notebook    | [42f38309b9](https://linux-hardware.org/?probe=42f38309b9) | Jul 04, 2023 |
| Lenovo        | ThinkPad L520 5015A12       | Notebook    | [0cb85712d9](https://linux-hardware.org/?probe=0cb85712d9) | Jul 04, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [9ec1de725f](https://linux-hardware.org/?probe=9ec1de725f) | Jul 04, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [464ff62eaf](https://linux-hardware.org/?probe=464ff62eaf) | Jul 04, 2023 |
| eMachines     | Padus                       | Notebook    | [008b3a48cd](https://linux-hardware.org/?probe=008b3a48cd) | Jul 04, 2023 |
| Biostar       | TA970                       | Desktop     | [31aec054d7](https://linux-hardware.org/?probe=31aec054d7) | Jul 04, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [c4dcbea71d](https://linux-hardware.org/?probe=c4dcbea71d) | Jul 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [08fb6b76ce](https://linux-hardware.org/?probe=08fb6b76ce) | Jul 03, 2023 |
| Lenovo        | Aptio CRB SDK0J40679 WIN... | Mini pc     | [40f510325d](https://linux-hardware.org/?probe=40f510325d) | Jul 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [1b82430294](https://linux-hardware.org/?probe=1b82430294) | Jul 02, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [e112fcd006](https://linux-hardware.org/?probe=e112fcd006) | Jul 02, 2023 |
| Alienware     | 18                          | Notebook    | [7898671060](https://linux-hardware.org/?probe=7898671060) | Jul 02, 2023 |
| HP            | 1497                        | Desktop     | [e282eb8fe1](https://linux-hardware.org/?probe=e282eb8fe1) | Jul 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [f78c4a1930](https://linux-hardware.org/?probe=f78c4a1930) | Jul 01, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [fc639c945e](https://linux-hardware.org/?probe=fc639c945e) | Jul 01, 2023 |
| HP            | 550                         | Notebook    | [7681694808](https://linux-hardware.org/?probe=7681694808) | Jul 01, 2023 |
| Acer          | JM11-MS                     | Notebook    | [ad02c854e0](https://linux-hardware.org/?probe=ad02c854e0) | Jul 01, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [af3e6790e4](https://linux-hardware.org/?probe=af3e6790e4) | Jun 30, 2023 |
| HP            | 8056                        | Desktop     | [32d1199c51](https://linux-hardware.org/?probe=32d1199c51) | Jun 30, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [ef54ec3027](https://linux-hardware.org/?probe=ef54ec3027) | Jun 30, 2023 |
| Lenovo        | ThinkPad L430 246634S       | Notebook    | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [6d3d6e002f](https://linux-hardware.org/?probe=6d3d6e002f) | Jun 30, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [99e1623ea0](https://linux-hardware.org/?probe=99e1623ea0) | Jun 29, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [7dffb9055b](https://linux-hardware.org/?probe=7dffb9055b) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a77c825995](https://linux-hardware.org/?probe=a77c825995) | Jun 29, 2023 |
| Dell          | System XPS L321X            | Notebook    | [abf6b8b341](https://linux-hardware.org/?probe=abf6b8b341) | Jun 29, 2023 |
| Acer          | Aspire 5830TG               | Notebook    | [8c001b69bb](https://linux-hardware.org/?probe=8c001b69bb) | Jun 29, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [20f509028b](https://linux-hardware.org/?probe=20f509028b) | Jun 29, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [0286d2f5e5](https://linux-hardware.org/?probe=0286d2f5e5) | Jun 29, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [404728f350](https://linux-hardware.org/?probe=404728f350) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| MSI           | MS-7438 100                 | Desktop     | [4d0d23065e](https://linux-hardware.org/?probe=4d0d23065e) | Jun 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2f50312c02](https://linux-hardware.org/?probe=2f50312c02) | Jun 29, 2023 |
| Lenovo        | ThinkPad L520 50153CJ       | Notebook    | [1793064ee5](https://linux-hardware.org/?probe=1793064ee5) | Jun 29, 2023 |
| Huanan        | X99-BD4 V1.31               | Desktop     | [fcd9a6b1e2](https://linux-hardware.org/?probe=fcd9a6b1e2) | Jun 28, 2023 |
| Acer          | EG43M                       | Desktop     | [e6d28dd1e5](https://linux-hardware.org/?probe=e6d28dd1e5) | Jun 28, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | Desktop     | [1114cf7328](https://linux-hardware.org/?probe=1114cf7328) | Jun 28, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Foxconn       | G41MD                       | Desktop     | [926a733402](https://linux-hardware.org/?probe=926a733402) | Jun 27, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [cb47380993](https://linux-hardware.org/?probe=cb47380993) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2ed9f4248c](https://linux-hardware.org/?probe=2ed9f4248c) | Jun 27, 2023 |
| PCsmart       | PCSGOB14p-C                 | Notebook    | [a45977461f](https://linux-hardware.org/?probe=a45977461f) | Jun 27, 2023 |
| MSI           | PRO B660M-B DDR4            | Desktop     | [09f4e0e86a](https://linux-hardware.org/?probe=09f4e0e86a) | Jun 27, 2023 |
| Kennex        | POS-PIG41BA                 | Desktop     | [90addad9e1](https://linux-hardware.org/?probe=90addad9e1) | Jun 27, 2023 |
| Clevo         | M540SS Bottom               | Notebook    | [4b613733a0](https://linux-hardware.org/?probe=4b613733a0) | Jun 27, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [89858274fd](https://linux-hardware.org/?probe=89858274fd) | Jun 27, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [4557637b8a](https://linux-hardware.org/?probe=4557637b8a) | Jun 26, 2023 |
| HP            | 8430 1000                   | All in one  | [cba036b5d2](https://linux-hardware.org/?probe=cba036b5d2) | Jun 26, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [6aba51f328](https://linux-hardware.org/?probe=6aba51f328) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [713bfcdf62](https://linux-hardware.org/?probe=713bfcdf62) | Jun 26, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [734e60af76](https://linux-hardware.org/?probe=734e60af76) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [501d3b5530](https://linux-hardware.org/?probe=501d3b5530) | Jun 25, 2023 |
| Intel         | H61                         | Desktop     | [8013deae02](https://linux-hardware.org/?probe=8013deae02) | Jun 25, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [f58c462a34](https://linux-hardware.org/?probe=f58c462a34) | Jun 25, 2023 |
| Biostar       | G31M+                       | Desktop     | [d8347c5f07](https://linux-hardware.org/?probe=d8347c5f07) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Dell          | Precision M6400             | Notebook    | [b68c09e274](https://linux-hardware.org/?probe=b68c09e274) | Jun 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [186a7eedb6](https://linux-hardware.org/?probe=186a7eedb6) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | Notebook    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [bce89b670d](https://linux-hardware.org/?probe=bce89b670d) | Jun 25, 2023 |
| Medion        | H110H4-CM2                  | Desktop     | [49df9d792a](https://linux-hardware.org/?probe=49df9d792a) | Jun 25, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [6760d73caf](https://linux-hardware.org/?probe=6760d73caf) | Jun 24, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [785d3130e7](https://linux-hardware.org/?probe=785d3130e7) | Jun 24, 2023 |
| HP            | G62                         | Notebook    | [e8187f4fb6](https://linux-hardware.org/?probe=e8187f4fb6) | Jun 24, 2023 |
| Dell          | Latitude 3180               | Notebook    | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [5d4d2adebe](https://linux-hardware.org/?probe=5d4d2adebe) | Jun 24, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [76dd0fc5f1](https://linux-hardware.org/?probe=76dd0fc5f1) | Jun 24, 2023 |
| HP            | Compaq 610                  | Notebook    | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| HP            | 1495                        | Desktop     | [eab7d15f02](https://linux-hardware.org/?probe=eab7d15f02) | Jun 23, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [39d5409264](https://linux-hardware.org/?probe=39d5409264) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4ab121533a](https://linux-hardware.org/?probe=4ab121533a) | Jun 23, 2023 |
| Huanan        | X79 V6.11                   | Desktop     | [e94687bb6b](https://linux-hardware.org/?probe=e94687bb6b) | Jun 23, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [f135825cec](https://linux-hardware.org/?probe=f135825cec) | Jun 23, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [167de0618f](https://linux-hardware.org/?probe=167de0618f) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| Sony          | VAIO                        | All in one  | [8eda132a31](https://linux-hardware.org/?probe=8eda132a31) | Jun 22, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8454119675](https://linux-hardware.org/?probe=8454119675) | Jun 22, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [ba9d7c939a](https://linux-hardware.org/?probe=ba9d7c939a) | Jun 22, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [cc0794fa6e](https://linux-hardware.org/?probe=cc0794fa6e) | Jun 21, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [5c9111463c](https://linux-hardware.org/?probe=5c9111463c) | Jun 21, 2023 |
| Sony          | VGN-NS21M_W                 | Notebook    | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| Acer          | One S1002                   | Notebook    | [f7b8d25603](https://linux-hardware.org/?probe=f7b8d25603) | Jun 21, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [9f5f612aa7](https://linux-hardware.org/?probe=9f5f612aa7) | Jun 21, 2023 |
| HP            | Notebook                    | Notebook    | [3460bcb864](https://linux-hardware.org/?probe=3460bcb864) | Jun 20, 2023 |
| Positivo      | POS-ECIG41BSA               | Desktop     | [abaf6ee67e](https://linux-hardware.org/?probe=abaf6ee67e) | Jun 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [f84ddd7cac](https://linux-hardware.org/?probe=f84ddd7cac) | Jun 20, 2023 |
| Acer          | Aspire F5-771G              | Notebook    | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| Gigabyte      | GA-E350N                    | Desktop     | [dc5ab95b15](https://linux-hardware.org/?probe=dc5ab95b15) | Jun 19, 2023 |
| Dell          | System XPS L502X            | Notebook    | [463e017820](https://linux-hardware.org/?probe=463e017820) | Jun 19, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | Notebook    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4bafdb9349](https://linux-hardware.org/?probe=4bafdb9349) | Jun 18, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [7348297d40](https://linux-hardware.org/?probe=7348297d40) | Jun 18, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [fac7a3587a](https://linux-hardware.org/?probe=fac7a3587a) | Jun 18, 2023 |
| GEEKOM        | MiniAir 11                  | Server      | [ac5a7b3810](https://linux-hardware.org/?probe=ac5a7b3810) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [bb3ad00508](https://linux-hardware.org/?probe=bb3ad00508) | Jun 17, 2023 |
| Lenovo        | ThinkPad P50 20EQS4840B     | Notebook    | [a60f1ae93e](https://linux-hardware.org/?probe=a60f1ae93e) | Jun 17, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3050f49c99](https://linux-hardware.org/?probe=3050f49c99) | Jun 17, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [eebb6ba229](https://linux-hardware.org/?probe=eebb6ba229) | Jun 17, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [d415965e91](https://linux-hardware.org/?probe=d415965e91) | Jun 17, 2023 |
| Monster       | HUMA H4 V5.2                | Notebook    | [491797a556](https://linux-hardware.org/?probe=491797a556) | Jun 17, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [2149968671](https://linux-hardware.org/?probe=2149968671) | Jun 16, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [4dae4ff7c6](https://linux-hardware.org/?probe=4dae4ff7c6) | Jun 16, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ebedbde736](https://linux-hardware.org/?probe=ebedbde736) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [f242fcd667](https://linux-hardware.org/?probe=f242fcd667) | Jun 15, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [75c2da2c37](https://linux-hardware.org/?probe=75c2da2c37) | Jun 15, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [20ddd7a28b](https://linux-hardware.org/?probe=20ddd7a28b) | Jun 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [699dd5b23e](https://linux-hardware.org/?probe=699dd5b23e) | Jun 15, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [4b99537b32](https://linux-hardware.org/?probe=4b99537b32) | Jun 15, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [d512f1865e](https://linux-hardware.org/?probe=d512f1865e) | Jun 15, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [d7689b11ad](https://linux-hardware.org/?probe=d7689b11ad) | Jun 14, 2023 |
| HP            | 2820h                       | Desktop     | [41fa36550a](https://linux-hardware.org/?probe=41fa36550a) | Jun 14, 2023 |
| HP            | 81B3                        | Desktop     | [9ba98d3c27](https://linux-hardware.org/?probe=9ba98d3c27) | Jun 14, 2023 |
| ASRock        | QC5000-ITX/PH               | Desktop     | [b50d647073](https://linux-hardware.org/?probe=b50d647073) | Jun 14, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [2ae3c4aaca](https://linux-hardware.org/?probe=2ae3c4aaca) | Jun 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [83d9a91c16](https://linux-hardware.org/?probe=83d9a91c16) | Jun 13, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [c74f83bbea](https://linux-hardware.org/?probe=c74f83bbea) | Jun 13, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [456a49b146](https://linux-hardware.org/?probe=456a49b146) | Jun 13, 2023 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [878dc2b05f](https://linux-hardware.org/?probe=878dc2b05f) | Jun 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [34cfc4a037](https://linux-hardware.org/?probe=34cfc4a037) | Jun 13, 2023 |
| Biostar       | A520MH                      | Desktop     | [70760c5e70](https://linux-hardware.org/?probe=70760c5e70) | Jun 12, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11d46971fa](https://linux-hardware.org/?probe=11d46971fa) | Jun 12, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| HP            | 339A                        | Desktop     | [348ce53f71](https://linux-hardware.org/?probe=348ce53f71) | Jun 10, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [03660fb140](https://linux-hardware.org/?probe=03660fb140) | Jun 10, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [f0d5120461](https://linux-hardware.org/?probe=f0d5120461) | Jun 10, 2023 |
| HP            | G42                         | Notebook    | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | Notebook    | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| Acer          | Predator G3600              | Desktop     | [02a0cf3a71](https://linux-hardware.org/?probe=02a0cf3a71) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| HP            | 09E0h                       | Desktop     | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| HP            | 87A4 10100                  | All in one  | [3c67e34a5e](https://linux-hardware.org/?probe=3c67e34a5e) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [fd037bb738](https://linux-hardware.org/?probe=fd037bb738) | Jun 08, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [369f5d3044](https://linux-hardware.org/?probe=369f5d3044) | Jun 07, 2023 |
| HP            | 8169                        | Desktop     | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| Kraftway      | KWH510                      | Desktop     | [3a5ccb373b](https://linux-hardware.org/?probe=3a5ccb373b) | Jun 07, 2023 |
| HP            | 2B34                        | Desktop     | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [bdea2092aa](https://linux-hardware.org/?probe=bdea2092aa) | Jun 06, 2023 |
| HP            | 822A                        | Desktop     | [8cf8694f03](https://linux-hardware.org/?probe=8cf8694f03) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Intel         | E5 V1.0                     | Desktop     | [077c08c2dc](https://linux-hardware.org/?probe=077c08c2dc) | Jun 06, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| Acer          | EQ45LM                      | Desktop     | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| HP            | 8265                        | Desktop     | [7afc259b97](https://linux-hardware.org/?probe=7afc259b97) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| NEC Comput... | MS-AD611                    | All in one  | [219795e31d](https://linux-hardware.org/?probe=219795e31d) | Jun 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [48d99dbec6](https://linux-hardware.org/?probe=48d99dbec6) | Jun 05, 2023 |
| ASRock        | B150M Pro4                  | Desktop     | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [697cc43136](https://linux-hardware.org/?probe=697cc43136) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Acer          | Veriton X4630G V:1.0        | Desktop     | [5106e40f32](https://linux-hardware.org/?probe=5106e40f32) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| Foxconn       | G41MD                       | Desktop     | [f988a585c9](https://linux-hardware.org/?probe=f988a585c9) | Jun 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [094889a0e2](https://linux-hardware.org/?probe=094889a0e2) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [5d6b08920f](https://linux-hardware.org/?probe=5d6b08920f) | Jun 03, 2023 |
| ECS           | G31T-M                      | Desktop     | [55d38b75c7](https://linux-hardware.org/?probe=55d38b75c7) | Jun 03, 2023 |
| Compaq        | 420                         | Notebook    | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| ASUSTek       | PRIME A520M-A               | Desktop     | [7dac003c12](https://linux-hardware.org/?probe=7dac003c12) | Jun 03, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70a097a219](https://linux-hardware.org/?probe=70a097a219) | Jun 02, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f22933cdb1](https://linux-hardware.org/?probe=f22933cdb1) | Jun 01, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| Teclast       | X4                          | Tablet      | [2392aa748a](https://linux-hardware.org/?probe=2392aa748a) | Jun 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | Desktop     | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | Notebook    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| OEM           | Intel H81                   | Desktop     | [b62ec659fa](https://linux-hardware.org/?probe=b62ec659fa) | Jun 01, 2023 |
| Inventec      | 0PY33N A01                  | Mini pc     | [01452a68b3](https://linux-hardware.org/?probe=01452a68b3) | May 31, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [483bf9a882](https://linux-hardware.org/?probe=483bf9a882) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| Dell          | System Vostro 3450          | Notebook    | [ae337aeb9c](https://linux-hardware.org/?probe=ae337aeb9c) | May 31, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [11bab4bc11](https://linux-hardware.org/?probe=11bab4bc11) | May 30, 2023 |
| Timi          | RedmiBook 14 II             | Notebook    | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ea55e0ac39](https://linux-hardware.org/?probe=ea55e0ac39) | May 30, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | Notebook    | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f762140894](https://linux-hardware.org/?probe=f762140894) | May 30, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [48359795cc](https://linux-hardware.org/?probe=48359795cc) | May 30, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fb729f1358](https://linux-hardware.org/?probe=fb729f1358) | May 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a46f523ea2](https://linux-hardware.org/?probe=a46f523ea2) | May 29, 2023 |
| MSI           | P67A-GD65                   | Desktop     | [fe5e3bcd7b](https://linux-hardware.org/?probe=fe5e3bcd7b) | May 29, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| Google        | Auron_Paine                 | Notebook    | [66fd27934f](https://linux-hardware.org/?probe=66fd27934f) | May 29, 2023 |
| Gigabyte      | Z690 UD                     | Desktop     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| Lenovo        | ThinkPad W541 20EF000MUS    | Notebook    | [44c1329399](https://linux-hardware.org/?probe=44c1329399) | May 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [42b817db26](https://linux-hardware.org/?probe=42b817db26) | May 29, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [1db96272fe](https://linux-hardware.org/?probe=1db96272fe) | May 29, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ece00aac41](https://linux-hardware.org/?probe=ece00aac41) | May 29, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | Notebook    | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [af1bb009ca](https://linux-hardware.org/?probe=af1bb009ca) | May 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8436530b0](https://linux-hardware.org/?probe=b8436530b0) | May 28, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | Notebook    | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [b1213efe40](https://linux-hardware.org/?probe=b1213efe40) | May 28, 2023 |
| Acer          | Aspire 7540                 | Notebook    | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| Gateway       | DT55                        | Desktop     | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [ad8e3ea3ea](https://linux-hardware.org/?probe=ad8e3ea3ea) | May 27, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [3904ffdddf](https://linux-hardware.org/?probe=3904ffdddf) | May 27, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [f2181d0270](https://linux-hardware.org/?probe=f2181d0270) | May 27, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [bfc89878ce](https://linux-hardware.org/?probe=bfc89878ce) | May 27, 2023 |
| Dell          | 0TP412                      | Desktop     | [112fa3015f](https://linux-hardware.org/?probe=112fa3015f) | May 27, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [bc1c76bb8f](https://linux-hardware.org/?probe=bc1c76bb8f) | May 27, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [b0435ce0dc](https://linux-hardware.org/?probe=b0435ce0dc) | May 27, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [3900a03a2c](https://linux-hardware.org/?probe=3900a03a2c) | May 27, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3e9709dc25](https://linux-hardware.org/?probe=3e9709dc25) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| MSI           | B250M BAZOOKA               | Desktop     | [2bfe50d945](https://linux-hardware.org/?probe=2bfe50d945) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [5977804b94](https://linux-hardware.org/?probe=5977804b94) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| Dell          | Latitude 5290               | Notebook    | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [5d54a10d85](https://linux-hardware.org/?probe=5d54a10d85) | May 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c897394a34](https://linux-hardware.org/?probe=c897394a34) | May 26, 2023 |
| Fujitsu Si... | D2464-A1 S26361-D2464-A1    | Desktop     | [313c8a3663](https://linux-hardware.org/?probe=313c8a3663) | May 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| Acer          | Aspire M3910                | Desktop     | [f4dedc13f9](https://linux-hardware.org/?probe=f4dedc13f9) | May 25, 2023 |
| MSI           | Z590 PLUS                   | Desktop     | [1f531f4e58](https://linux-hardware.org/?probe=1f531f4e58) | May 25, 2023 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [41eac45c5e](https://linux-hardware.org/?probe=41eac45c5e) | May 25, 2023 |
| LG Electro... | 22V280 FAB1                 | All in one  | [0df1994f25](https://linux-hardware.org/?probe=0df1994f25) | May 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [a8dd30a7bb](https://linux-hardware.org/?probe=a8dd30a7bb) | May 25, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [cbcfc55949](https://linux-hardware.org/?probe=cbcfc55949) | May 25, 2023 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [b6b7396e06](https://linux-hardware.org/?probe=b6b7396e06) | May 25, 2023 |
| Timi          | TM1701                      | Notebook    | [c883337466](https://linux-hardware.org/?probe=c883337466) | May 24, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [1247209c34](https://linux-hardware.org/?probe=1247209c34) | May 24, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [701c6c3410](https://linux-hardware.org/?probe=701c6c3410) | May 24, 2023 |
| Lenovo        | 318E SDK0L22692 WIN 3792... | Desktop     | [5fb6f16a6d](https://linux-hardware.org/?probe=5fb6f16a6d) | May 24, 2023 |
| Gigabyte      | 8I945GZME-RH                | Desktop     | [3b4c63eddb](https://linux-hardware.org/?probe=3b4c63eddb) | May 24, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [cd798092df](https://linux-hardware.org/?probe=cd798092df) | May 23, 2023 |
| Intel         | H61                         | Desktop     | [794ecc6c43](https://linux-hardware.org/?probe=794ecc6c43) | May 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [c13217076b](https://linux-hardware.org/?probe=c13217076b) | May 23, 2023 |
| Dell          | 0H19HD A06                  | Server      | [25975db1c4](https://linux-hardware.org/?probe=25975db1c4) | May 23, 2023 |
| Lenovo        | ThinkPad L520 5017A62       | Notebook    | [a8d01c9adb](https://linux-hardware.org/?probe=a8d01c9adb) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| Foxconn       | G41MD                       | Desktop     | [a3a8a67867](https://linux-hardware.org/?probe=a3a8a67867) | May 23, 2023 |
| Dell          | 0X2YVY A00                  | All in one  | [cf15aa9b1a](https://linux-hardware.org/?probe=cf15aa9b1a) | May 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76db4a03a1](https://linux-hardware.org/?probe=76db4a03a1) | May 22, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | Notebook    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| HP            | 2AF3                        | Desktop     | [e70a1c12fb](https://linux-hardware.org/?probe=e70a1c12fb) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [c5d385dd80](https://linux-hardware.org/?probe=c5d385dd80) | May 22, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [2f1b921a18](https://linux-hardware.org/?probe=2f1b921a18) | May 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [63a27f785d](https://linux-hardware.org/?probe=63a27f785d) | May 22, 2023 |
| Dell          | Latitude E6230              | Notebook    | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| ASUSTek       | K84L                        | Notebook    | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [816fffab13](https://linux-hardware.org/?probe=816fffab13) | May 21, 2023 |
| Teclast       | X4                          | Tablet      | [9dc0b8fa7b](https://linux-hardware.org/?probe=9dc0b8fa7b) | May 21, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [0ef682fa85](https://linux-hardware.org/?probe=0ef682fa85) | May 21, 2023 |
| Philco        | 14H                         | Notebook    | [5dbb0cb3b7](https://linux-hardware.org/?probe=5dbb0cb3b7) | May 21, 2023 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | Notebook    | [03afaf2468](https://linux-hardware.org/?probe=03afaf2468) | May 21, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [1c5c9709dd](https://linux-hardware.org/?probe=1c5c9709dd) | May 21, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [906ba8b65c](https://linux-hardware.org/?probe=906ba8b65c) | May 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7ff619a028](https://linux-hardware.org/?probe=7ff619a028) | May 21, 2023 |
| ASUSTek       | N53TK                       | Notebook    | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [2aff70d7c9](https://linux-hardware.org/?probe=2aff70d7c9) | May 21, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| ASRock        | Q1900M                      | Desktop     | [0290a65c70](https://linux-hardware.org/?probe=0290a65c70) | May 21, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [e9b749f2ba](https://linux-hardware.org/?probe=e9b749f2ba) | May 21, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [0deaff38f5](https://linux-hardware.org/?probe=0deaff38f5) | May 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [c3af6442c9](https://linux-hardware.org/?probe=c3af6442c9) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [e1939cff8f](https://linux-hardware.org/?probe=e1939cff8f) | May 21, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [ed99950768](https://linux-hardware.org/?probe=ed99950768) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [b68e5e0285](https://linux-hardware.org/?probe=b68e5e0285) | May 20, 2023 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [f39a134aa1](https://linux-hardware.org/?probe=f39a134aa1) | May 20, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Dell          | Latitude 5285               | Notebook    | [0db3cfd34e](https://linux-hardware.org/?probe=0db3cfd34e) | May 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b563edd887](https://linux-hardware.org/?probe=b563edd887) | May 20, 2023 |
| Foxconn       | G41MD                       | Desktop     | [1a649b0512](https://linux-hardware.org/?probe=1a649b0512) | May 20, 2023 |
| HP            | 250 G2                      | Notebook    | [e3b94752ac](https://linux-hardware.org/?probe=e3b94752ac) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | Notebook    | [1094884573](https://linux-hardware.org/?probe=1094884573) | May 19, 2023 |
| ASRock        | Z590M Pro4                  | Desktop     | [d039ed90c5](https://linux-hardware.org/?probe=d039ed90c5) | May 19, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| ASUSTek       | F7Se                        | Notebook    | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| Lenovo        | ThinkPad L560 20F2S1JP03    | Notebook    | [d0dd999b33](https://linux-hardware.org/?probe=d0dd999b33) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [82dca1cbb8](https://linux-hardware.org/?probe=82dca1cbb8) | May 18, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Toshiba       | Satellite L850-1HQ          | Notebook    | [d16c26b474](https://linux-hardware.org/?probe=d16c26b474) | May 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [05379205f4](https://linux-hardware.org/?probe=05379205f4) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b30dee1244](https://linux-hardware.org/?probe=b30dee1244) | May 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [df73f83c15](https://linux-hardware.org/?probe=df73f83c15) | May 18, 2023 |
| Google        | Auron_Paine                 | Notebook    | [a836fcd48f](https://linux-hardware.org/?probe=a836fcd48f) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | Notebook    | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| Fujitsu       | D3420-U1 S26361-D3420-U1    | Desktop     | [958b2ab1f9](https://linux-hardware.org/?probe=958b2ab1f9) | May 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| NEC Comput... | SK15 3A3B                   | All in one  | [80a4b43ab9](https://linux-hardware.org/?probe=80a4b43ab9) | May 17, 2023 |
| Fujitsu       | LIFEBOOK P728               | Convertible | [55db12e408](https://linux-hardware.org/?probe=55db12e408) | May 17, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [cfe4d9071b](https://linux-hardware.org/?probe=cfe4d9071b) | May 16, 2023 |
| Maxtang       | FP650 V1.0                  | Desktop     | [8f1eba846a](https://linux-hardware.org/?probe=8f1eba846a) | May 16, 2023 |
| Foxconn       | P35A01                      | Desktop     | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [652d9e0fa9](https://linux-hardware.org/?probe=652d9e0fa9) | May 15, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [eee39f2f10](https://linux-hardware.org/?probe=eee39f2f10) | May 15, 2023 |
| Samsung       | R428/P428                   | Notebook    | [1d93335f58](https://linux-hardware.org/?probe=1d93335f58) | May 15, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [02da78340f](https://linux-hardware.org/?probe=02da78340f) | May 15, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3ca79ab5f8](https://linux-hardware.org/?probe=3ca79ab5f8) | May 15, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| HP            | 8436                        | Desktop     | [ae94b377fd](https://linux-hardware.org/?probe=ae94b377fd) | May 15, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [7380a83f05](https://linux-hardware.org/?probe=7380a83f05) | May 14, 2023 |
| HP            | Pavilion dv8                | Notebook    | [422d1fd213](https://linux-hardware.org/?probe=422d1fd213) | May 14, 2023 |
| ASUSTek       | M2A-MX                      | Desktop     | [43c0de16a2](https://linux-hardware.org/?probe=43c0de16a2) | May 14, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [6fdf42b8a9](https://linux-hardware.org/?probe=6fdf42b8a9) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | Desktop     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Precision M4500             | Notebook    | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | Notebook    | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Intel         | H61                         | Desktop     | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | Desktop     | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [95974d7e97](https://linux-hardware.org/?probe=95974d7e97) | May 12, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [bd1c748eed](https://linux-hardware.org/?probe=bd1c748eed) | May 12, 2023 |
| HP            | 0A58h                       | Desktop     | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| Toshiba       | Satellite C75-A             | Notebook    | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [989d8eef43](https://linux-hardware.org/?probe=989d8eef43) | May 11, 2023 |
| Acer          | Extensa 5220                | Notebook    | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [7e1600284a](https://linux-hardware.org/?probe=7e1600284a) | May 11, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [10b9d3a925](https://linux-hardware.org/?probe=10b9d3a925) | May 11, 2023 |
| Acer          | Aspire E1-521               | Notebook    | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [040f5917ec](https://linux-hardware.org/?probe=040f5917ec) | May 10, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [8376015b15](https://linux-hardware.org/?probe=8376015b15) | May 10, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [2710a15a04](https://linux-hardware.org/?probe=2710a15a04) | May 10, 2023 |
| Intel         | X58M                        | Desktop     | [666b002908](https://linux-hardware.org/?probe=666b002908) | May 10, 2023 |
| Samsung       | X420/X520                   | Notebook    | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [8f7bcc525d](https://linux-hardware.org/?probe=8f7bcc525d) | May 10, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [f86702afcf](https://linux-hardware.org/?probe=f86702afcf) | May 10, 2023 |
| Dell          | Precision M3800             | Notebook    | [e7b0097a72](https://linux-hardware.org/?probe=e7b0097a72) | May 09, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f7cb6c9251](https://linux-hardware.org/?probe=f7cb6c9251) | May 09, 2023 |
| HP            | 304Ah                       | Desktop     | [7c6a6b156f](https://linux-hardware.org/?probe=7c6a6b156f) | May 09, 2023 |
| Dell          | Latitude 5420               | Notebook    | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| Fujitsu       | FMVA0500TP                  | Notebook    | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Acer          | EG43M                       | Desktop     | [01704e814c](https://linux-hardware.org/?probe=01704e814c) | May 09, 2023 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0bca52bcc5](https://linux-hardware.org/?probe=0bca52bcc5) | May 09, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [8ebde36ef2](https://linux-hardware.org/?probe=8ebde36ef2) | May 09, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [57b843a3ca](https://linux-hardware.org/?probe=57b843a3ca) | May 09, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [6b8d3c96c5](https://linux-hardware.org/?probe=6b8d3c96c5) | May 09, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1d9699c86f](https://linux-hardware.org/?probe=1d9699c86f) | May 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [531adb6cae](https://linux-hardware.org/?probe=531adb6cae) | May 09, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [53d91dca3c](https://linux-hardware.org/?probe=53d91dca3c) | May 08, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [5bc5ccdcad](https://linux-hardware.org/?probe=5bc5ccdcad) | May 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [acf61a6132](https://linux-hardware.org/?probe=acf61a6132) | May 08, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| HP            | 15                          | Notebook    | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| Dell          | 0T656F A01                  | Desktop     | [94294c8cf0](https://linux-hardware.org/?probe=94294c8cf0) | May 08, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [e7b77f5cf0](https://linux-hardware.org/?probe=e7b77f5cf0) | May 08, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [22bd54d6d1](https://linux-hardware.org/?probe=22bd54d6d1) | May 08, 2023 |
| Acer          | Aspire ES1-132              | Notebook    | [10a13dcd68](https://linux-hardware.org/?probe=10a13dcd68) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| ASUSTek       | X202E                       | Notebook    | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| HP            | 15                          | Notebook    | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [47388f4553](https://linux-hardware.org/?probe=47388f4553) | May 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3530619c98](https://linux-hardware.org/?probe=3530619c98) | May 07, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [46a87a6448](https://linux-hardware.org/?probe=46a87a6448) | May 07, 2023 |
| Dell          | 0R230R A00                  | Desktop     | [16611a8ed6](https://linux-hardware.org/?probe=16611a8ed6) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b734a6d6f3](https://linux-hardware.org/?probe=b734a6d6f3) | May 07, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d63bc9aeca](https://linux-hardware.org/?probe=d63bc9aeca) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [68e1c1b5a4](https://linux-hardware.org/?probe=68e1c1b5a4) | May 07, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [9eef570443](https://linux-hardware.org/?probe=9eef570443) | May 07, 2023 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [305cc49ac0](https://linux-hardware.org/?probe=305cc49ac0) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [99fbd772e8](https://linux-hardware.org/?probe=99fbd772e8) | May 07, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [895855ed9a](https://linux-hardware.org/?probe=895855ed9a) | May 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Gigabyte      | H470M K                     | Desktop     | [655bbe4068](https://linux-hardware.org/?probe=655bbe4068) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3ea9b926d](https://linux-hardware.org/?probe=f3ea9b926d) | May 06, 2023 |
| Dell          | System XPS L702X            | Notebook    | [210b876fe7](https://linux-hardware.org/?probe=210b876fe7) | May 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b3bf20b454](https://linux-hardware.org/?probe=b3bf20b454) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Alienware     | 0R3FWM A00                  | Desktop     | [c6dbe0270a](https://linux-hardware.org/?probe=c6dbe0270a) | May 06, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [c964ce47c2](https://linux-hardware.org/?probe=c964ce47c2) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [094b22cf5a](https://linux-hardware.org/?probe=094b22cf5a) | May 06, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [d5456946bb](https://linux-hardware.org/?probe=d5456946bb) | May 06, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [03076cae9a](https://linux-hardware.org/?probe=03076cae9a) | May 06, 2023 |
| ASRock        | Q270 Pro BTC+               | Desktop     | [4fc3d2c86f](https://linux-hardware.org/?probe=4fc3d2c86f) | May 05, 2023 |
| ASUSTek       | K75DE                       | Notebook    | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| ASUSTek       | X401A1                      | Notebook    | [3fa1a1e9f0](https://linux-hardware.org/?probe=3fa1a1e9f0) | May 05, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [edcdedd65a](https://linux-hardware.org/?probe=edcdedd65a) | May 05, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [09bd22441b](https://linux-hardware.org/?probe=09bd22441b) | May 05, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [ffb03b8bd4](https://linux-hardware.org/?probe=ffb03b8bd4) | May 05, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [6f2b69becc](https://linux-hardware.org/?probe=6f2b69becc) | May 05, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ca84298b9d](https://linux-hardware.org/?probe=ca84298b9d) | May 05, 2023 |
| Dell          | 0PU052                      | Desktop     | [03c6b8486e](https://linux-hardware.org/?probe=03c6b8486e) | May 05, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [f5717fc896](https://linux-hardware.org/?probe=f5717fc896) | May 04, 2023 |
| ASRock        | Z590 Steel Legend           | Desktop     | [d36cec198b](https://linux-hardware.org/?probe=d36cec198b) | May 04, 2023 |
| Medion        | E6232                       | Notebook    | [38b433b485](https://linux-hardware.org/?probe=38b433b485) | May 04, 2023 |
| Gateway       | NE46R                       | Notebook    | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [579c16cd5c](https://linux-hardware.org/?probe=579c16cd5c) | May 04, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Fujitsu       | FMVA705ABS                  | Notebook    | [99cb877cba](https://linux-hardware.org/?probe=99cb877cba) | May 04, 2023 |
| Toshiba       | dynabook SS M42 210E/3W     | Notebook    | [ad7f7da4e4](https://linux-hardware.org/?probe=ad7f7da4e4) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [6116c0df52](https://linux-hardware.org/?probe=6116c0df52) | May 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [92c9651e22](https://linux-hardware.org/?probe=92c9651e22) | May 04, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [2dabac74e0](https://linux-hardware.org/?probe=2dabac74e0) | May 03, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [d8ec895bea](https://linux-hardware.org/?probe=d8ec895bea) | May 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| Acer          | H57M01                      | Desktop     | [affe73e1a5](https://linux-hardware.org/?probe=affe73e1a5) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | Notebook    | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| Dell          | Latitude E6540              | Notebook    | [e9f23b9574](https://linux-hardware.org/?probe=e9f23b9574) | May 03, 2023 |
| Positivo      | W2150G                      | All in one  | [38c2a94baa](https://linux-hardware.org/?probe=38c2a94baa) | May 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [cb2a0efe72](https://linux-hardware.org/?probe=cb2a0efe72) | May 02, 2023 |
| Unknown       | 1.0                         | Desktop     | [5f99ebeed7](https://linux-hardware.org/?probe=5f99ebeed7) | May 02, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| American M... | IPPBT-RO                    | All in one  | [a2921975cd](https://linux-hardware.org/?probe=a2921975cd) | May 02, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [583642a695](https://linux-hardware.org/?probe=583642a695) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| HP            | 3031h                       | Desktop     | [84140549cd](https://linux-hardware.org/?probe=84140549cd) | May 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [00dc63bf78](https://linux-hardware.org/?probe=00dc63bf78) | May 01, 2023 |
| Lenovo        | ThinkCentre M71e 5033A1U    | Desktop     | [2e39bbf0cf](https://linux-hardware.org/?probe=2e39bbf0cf) | May 01, 2023 |
| Samsung       | 950QDB                      | Convertible | [ecae18f163](https://linux-hardware.org/?probe=ecae18f163) | May 01, 2023 |
| HP            | 3033h                       | Desktop     | [31a4e00c60](https://linux-hardware.org/?probe=31a4e00c60) | May 01, 2023 |
| HP            | 3648h                       | Desktop     | [38ab69c4e2](https://linux-hardware.org/?probe=38ab69c4e2) | May 01, 2023 |
| HP            | Compaq 8510w                | Notebook    | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [15c04364fa](https://linux-hardware.org/?probe=15c04364fa) | May 01, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [4b23b933b5](https://linux-hardware.org/?probe=4b23b933b5) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [e7905065dd](https://linux-hardware.org/?probe=e7905065dd) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | Desktop     | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| HP            | Notebook                    | Notebook    | [4cece109d5](https://linux-hardware.org/?probe=4cece109d5) | Apr 30, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [fdba59c054](https://linux-hardware.org/?probe=fdba59c054) | Apr 30, 2023 |
| Acer          | AO725                       | Notebook    | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [ac7894081f](https://linux-hardware.org/?probe=ac7894081f) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | Desktop     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| MSI           | A68HM GRENADE               | Desktop     | [938aa1cb46](https://linux-hardware.org/?probe=938aa1cb46) | Apr 30, 2023 |
| HP            | Compaq 6720s                | Notebook    | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [fd991056e0](https://linux-hardware.org/?probe=fd991056e0) | Apr 30, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [41c212fa2c](https://linux-hardware.org/?probe=41c212fa2c) | Apr 30, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [de172b8988](https://linux-hardware.org/?probe=de172b8988) | Apr 30, 2023 |
| Intel         | H61                         | Desktop     | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [8f07407e1a](https://linux-hardware.org/?probe=8f07407e1a) | Apr 29, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [a684ad4938](https://linux-hardware.org/?probe=a684ad4938) | Apr 29, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | Notebook    | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| Toshiba       | PORTEGE R830                | Notebook    | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [0f22698060](https://linux-hardware.org/?probe=0f22698060) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| MSI           | MS-9661 SA                  | Server      | [1888fa6df7](https://linux-hardware.org/?probe=1888fa6df7) | Apr 29, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| Dell          | Latitude 7390               | Notebook    | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| Medion        | X6816                       | Notebook    | [2c1807dad7](https://linux-hardware.org/?probe=2c1807dad7) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [7e7da68aa3](https://linux-hardware.org/?probe=7e7da68aa3) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [5fe84b74b0](https://linux-hardware.org/?probe=5fe84b74b0) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| Sony          | SVF15212CXW                 | Notebook    | [5d5367dc0e](https://linux-hardware.org/?probe=5d5367dc0e) | Apr 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| HP            | ProBook 4330s               | Notebook    | [955f91641b](https://linux-hardware.org/?probe=955f91641b) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| Lenovo        | ThinkPad R61 8943DJG        | Notebook    | [afc3fc578e](https://linux-hardware.org/?probe=afc3fc578e) | Apr 27, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [da50afdd1c](https://linux-hardware.org/?probe=da50afdd1c) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2099cafe74](https://linux-hardware.org/?probe=2099cafe74) | Apr 27, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [91930613cb](https://linux-hardware.org/?probe=91930613cb) | Apr 27, 2023 |
| MSI           | A78M-E35 V2                 | Desktop     | [5eb0f9d104](https://linux-hardware.org/?probe=5eb0f9d104) | Apr 27, 2023 |
| NEC Comput... | PC-LE150C2                  | Notebook    | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [32960eca65](https://linux-hardware.org/?probe=32960eca65) | Apr 27, 2023 |
| Dell          | Latitude E6400              | Notebook    | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| Samsung       | 950QED                      | Convertible | [0135cc3aa4](https://linux-hardware.org/?probe=0135cc3aa4) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [21577119ad](https://linux-hardware.org/?probe=21577119ad) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| Biostar       | H610MH                      | Desktop     | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | Notebook    | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [208f6823ed](https://linux-hardware.org/?probe=208f6823ed) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [b8b58af983](https://linux-hardware.org/?probe=b8b58af983) | Apr 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4f1e4da37e](https://linux-hardware.org/?probe=4f1e4da37e) | Apr 26, 2023 |
| Intel         | H81                         | Desktop     | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| ASUSTek       | X550VQ                      | Notebook    | [3c7d8a0268](https://linux-hardware.org/?probe=3c7d8a0268) | Apr 26, 2023 |
| HP            | 83E2                        | Desktop     | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [8a0cd0bb6e](https://linux-hardware.org/?probe=8a0cd0bb6e) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| Dell          | 0RCGCR A04                  | Server      | [8ef63cb2de](https://linux-hardware.org/?probe=8ef63cb2de) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [2e6de51ded](https://linux-hardware.org/?probe=2e6de51ded) | Apr 26, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e2f309bb08](https://linux-hardware.org/?probe=e2f309bb08) | Apr 25, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| Login Info... | LOG-S14BW01-CD              | Notebook    | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [0a58f3fa51](https://linux-hardware.org/?probe=0a58f3fa51) | Apr 25, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [3c1551d7be](https://linux-hardware.org/?probe=3c1551d7be) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | Notebook    | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| HP            | Compaq 15                   | Notebook    | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [a437a858a4](https://linux-hardware.org/?probe=a437a858a4) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Toshiba       | Satellite L305D             | Notebook    | [1bbf3a5e9c](https://linux-hardware.org/?probe=1bbf3a5e9c) | Apr 25, 2023 |
| ICL           | RAYbook Si1512              | Notebook    | [6aa907fd2e](https://linux-hardware.org/?probe=6aa907fd2e) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [418c2c626e](https://linux-hardware.org/?probe=418c2c626e) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | Notebook    | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| Dell          | Latitude XT2                | Notebook    | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [d9ad034d8c](https://linux-hardware.org/?probe=d9ad034d8c) | Apr 24, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [0842334fa2](https://linux-hardware.org/?probe=0842334fa2) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6531aafbfe](https://linux-hardware.org/?probe=6531aafbfe) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | Notebook    | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [538ebf1f96](https://linux-hardware.org/?probe=538ebf1f96) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| Shenzhen M... | F6CQW                       | Desktop     | [c2be3dd62b](https://linux-hardware.org/?probe=c2be3dd62b) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [cc80f06375](https://linux-hardware.org/?probe=cc80f06375) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Toshiba       | dynabook BX/67TG            | Notebook    | [5349d462cd](https://linux-hardware.org/?probe=5349d462cd) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [93790f1835](https://linux-hardware.org/?probe=93790f1835) | Apr 23, 2023 |
| Acer          | Spin SP315-51               | Convertible | [42da7880dd](https://linux-hardware.org/?probe=42da7880dd) | Apr 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6115e5ccd4](https://linux-hardware.org/?probe=6115e5ccd4) | Apr 22, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [e2276c080b](https://linux-hardware.org/?probe=e2276c080b) | Apr 22, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [9d1c8d691f](https://linux-hardware.org/?probe=9d1c8d691f) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [2ff545a3fc](https://linux-hardware.org/?probe=2ff545a3fc) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| HP            | ProBook 4330s               | Notebook    | [f6608ffee2](https://linux-hardware.org/?probe=f6608ffee2) | Apr 22, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [485f002152](https://linux-hardware.org/?probe=485f002152) | Apr 22, 2023 |
| Fujitsu       | FJNB037                     | Desktop     | [00e5e30f9b](https://linux-hardware.org/?probe=00e5e30f9b) | Apr 22, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [2d1b73d846](https://linux-hardware.org/?probe=2d1b73d846) | Apr 22, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [8f3546722b](https://linux-hardware.org/?probe=8f3546722b) | Apr 22, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Acer          | Spin SP314-51               | Convertible | [5fd72bcee7](https://linux-hardware.org/?probe=5fd72bcee7) | Apr 22, 2023 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | Desktop     | [617f821f9a](https://linux-hardware.org/?probe=617f821f9a) | Apr 22, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [015e857f63](https://linux-hardware.org/?probe=015e857f63) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| HP            | 18E5                        | Desktop     | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [422eb87f07](https://linux-hardware.org/?probe=422eb87f07) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| HP            | Compaq 6720s                | Notebook    | [b980c3c57d](https://linux-hardware.org/?probe=b980c3c57d) | Apr 21, 2023 |
| MouseCompu... | Z87-S01                     | Desktop     | [8caff0d2f2](https://linux-hardware.org/?probe=8caff0d2f2) | Apr 21, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [da51714544](https://linux-hardware.org/?probe=da51714544) | Apr 21, 2023 |
| ASRock        | P43DE                       | Desktop     | [8f2c0ecc69](https://linux-hardware.org/?probe=8f2c0ecc69) | Apr 21, 2023 |
| ASRock        | Z270 Taichi                 | Desktop     | [faf3402431](https://linux-hardware.org/?probe=faf3402431) | Apr 21, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [11ea81f23c](https://linux-hardware.org/?probe=11ea81f23c) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | Notebook    | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f2fc6a5da5](https://linux-hardware.org/?probe=f2fc6a5da5) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | Desktop     | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [eeff4cd84c](https://linux-hardware.org/?probe=eeff4cd84c) | Apr 20, 2023 |
| HP            | G62                         | Notebook    | [a0096bb254](https://linux-hardware.org/?probe=a0096bb254) | Apr 20, 2023 |
| Gigabyte      | H81N                        | Desktop     | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| MSI           | GE62 6QD                    | Notebook    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Toshiba       | dynabook T451/46EW          | Notebook    | [e45702b9aa](https://linux-hardware.org/?probe=e45702b9aa) | Apr 20, 2023 |
| Intel         | H61S                        | Desktop     | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [14d03d2dd7](https://linux-hardware.org/?probe=14d03d2dd7) | Apr 19, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| HP            | 18E4                        | Desktop     | [1bd96a017f](https://linux-hardware.org/?probe=1bd96a017f) | Apr 19, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [a31036cae1](https://linux-hardware.org/?probe=a31036cae1) | Apr 19, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [6a0eced5fc](https://linux-hardware.org/?probe=6a0eced5fc) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | Notebook    | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [0ff08e0727](https://linux-hardware.org/?probe=0ff08e0727) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [9c7e865b56](https://linux-hardware.org/?probe=9c7e865b56) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | Notebook    | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| ECS           | BSW-MINI                    | Desktop     | [5d3161092f](https://linux-hardware.org/?probe=5d3161092f) | Apr 19, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [5fa6c74be4](https://linux-hardware.org/?probe=5fa6c74be4) | Apr 19, 2023 |
| MSI           | 0B58h                       | Desktop     | [6473456480](https://linux-hardware.org/?probe=6473456480) | Apr 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [c5639cddcb](https://linux-hardware.org/?probe=c5639cddcb) | Apr 19, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4e95dc284c](https://linux-hardware.org/?probe=4e95dc284c) | Apr 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6fae9a24fb](https://linux-hardware.org/?probe=6fae9a24fb) | Apr 19, 2023 |
| HP            | 8309                        | Desktop     | [d82a6a4488](https://linux-hardware.org/?probe=d82a6a4488) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| MSI           | MS-7235                     | Desktop     | [efaeac524b](https://linux-hardware.org/?probe=efaeac524b) | Apr 18, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [76aabd80a0](https://linux-hardware.org/?probe=76aabd80a0) | Apr 18, 2023 |
| Acer          | AO722                       | Notebook    | [5fe24a9991](https://linux-hardware.org/?probe=5fe24a9991) | Apr 18, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [10693010af](https://linux-hardware.org/?probe=10693010af) | Apr 18, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [34c47b4141](https://linux-hardware.org/?probe=34c47b4141) | Apr 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [fb3d31599f](https://linux-hardware.org/?probe=fb3d31599f) | Apr 18, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [99ea2c7790](https://linux-hardware.org/?probe=99ea2c7790) | Apr 18, 2023 |
| NEC Comput... | MS-7451VM                   | Desktop     | [dc094ceba3](https://linux-hardware.org/?probe=dc094ceba3) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [4c6abc2653](https://linux-hardware.org/?probe=4c6abc2653) | Apr 18, 2023 |
| ASUSTek       | P5QC                        | Desktop     | [7d47aa511b](https://linux-hardware.org/?probe=7d47aa511b) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [dc707578c9](https://linux-hardware.org/?probe=dc707578c9) | Apr 18, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [9eb59318e2](https://linux-hardware.org/?probe=9eb59318e2) | Apr 18, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [d8995dacdc](https://linux-hardware.org/?probe=d8995dacdc) | Apr 18, 2023 |
| Acer          | FQ965M MP                   | Desktop     | [9be9793747](https://linux-hardware.org/?probe=9be9793747) | Apr 18, 2023 |
| Fujitsu       | FMVNA6HE                    | Notebook    | [609572e6f7](https://linux-hardware.org/?probe=609572e6f7) | Apr 18, 2023 |
| Lenovo        | ThinkPad P53 20QN001YUS     | Notebook    | [59549202bd](https://linux-hardware.org/?probe=59549202bd) | Apr 18, 2023 |
| HP            | 18E9                        | Desktop     | [8c36235f13](https://linux-hardware.org/?probe=8c36235f13) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [8944559c50](https://linux-hardware.org/?probe=8944559c50) | Apr 17, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | Notebook    | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Samsung       | 930QED                      | Convertible | [fdfe04c5c9](https://linux-hardware.org/?probe=fdfe04c5c9) | Apr 17, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8166aa6314](https://linux-hardware.org/?probe=8166aa6314) | Apr 17, 2023 |
| HP            | 1850                        | Desktop     | [fa2fa68792](https://linux-hardware.org/?probe=fa2fa68792) | Apr 17, 2023 |
| HP            | 8062                        | Desktop     | [a2558d47e8](https://linux-hardware.org/?probe=a2558d47e8) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| Medion        | E16401                      | Notebook    | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| Dell          | Latitude D830               | Notebook    | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | Notebook    | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| ASRock        | X99 Extreme4                | Desktop     | [e375be2ea6](https://linux-hardware.org/?probe=e375be2ea6) | Apr 17, 2023 |
| Medion        | MS-7728                     | Desktop     | [1da2d605db](https://linux-hardware.org/?probe=1da2d605db) | Apr 16, 2023 |
| Acer          | Aspire X3950                | Desktop     | [5a9abbd85f](https://linux-hardware.org/?probe=5a9abbd85f) | Apr 16, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [0134b33f82](https://linux-hardware.org/?probe=0134b33f82) | Apr 16, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6ac02f43f2](https://linux-hardware.org/?probe=6ac02f43f2) | Apr 16, 2023 |
| Samsung       | 950QDB                      | Convertible | [29ae07c7f1](https://linux-hardware.org/?probe=29ae07c7f1) | Apr 16, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [19a6cddfe0](https://linux-hardware.org/?probe=19a6cddfe0) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a2596e8d06](https://linux-hardware.org/?probe=a2596e8d06) | Apr 16, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [71643d03ec](https://linux-hardware.org/?probe=71643d03ec) | Apr 16, 2023 |
| Dell          | Precision 7510              | Notebook    | [abb2d93e32](https://linux-hardware.org/?probe=abb2d93e32) | Apr 16, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [fedecfd9ff](https://linux-hardware.org/?probe=fedecfd9ff) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Foxconn       | ALOE                        | Desktop     | [702f958604](https://linux-hardware.org/?probe=702f958604) | Apr 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | Desktop     | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| ASUSTek       | K73E                        | Notebook    | [9ab8e37631](https://linux-hardware.org/?probe=9ab8e37631) | Apr 15, 2023 |
| Fujitsu Si... | ESPRIMO Mobile X9515        | Notebook    | [82ffd0e4bd](https://linux-hardware.org/?probe=82ffd0e4bd) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [6c711c5197](https://linux-hardware.org/?probe=6c711c5197) | Apr 15, 2023 |
| Dell          | Precision 7730              | Notebook    | [0e434903ec](https://linux-hardware.org/?probe=0e434903ec) | Apr 15, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c655afe860](https://linux-hardware.org/?probe=c655afe860) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | Notebook    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [8a75d034c7](https://linux-hardware.org/?probe=8a75d034c7) | Apr 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [e17175b9ac](https://linux-hardware.org/?probe=e17175b9ac) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [83d43e489d](https://linux-hardware.org/?probe=83d43e489d) | Apr 15, 2023 |
| GPD           | G1619-01                    | Notebook    | [2edac2c38e](https://linux-hardware.org/?probe=2edac2c38e) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [e412c388d8](https://linux-hardware.org/?probe=e412c388d8) | Apr 15, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [51259c6f0a](https://linux-hardware.org/?probe=51259c6f0a) | Apr 15, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [82abb09c06](https://linux-hardware.org/?probe=82abb09c06) | Apr 15, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [dfed605628](https://linux-hardware.org/?probe=dfed605628) | Apr 15, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [a359e8f3ea](https://linux-hardware.org/?probe=a359e8f3ea) | Apr 15, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [f960c27052](https://linux-hardware.org/?probe=f960c27052) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [f3b7c9c255](https://linux-hardware.org/?probe=f3b7c9c255) | Apr 14, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [44cdfb0917](https://linux-hardware.org/?probe=44cdfb0917) | Apr 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [a5cb4f9095](https://linux-hardware.org/?probe=a5cb4f9095) | Apr 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [8a5b5b102c](https://linux-hardware.org/?probe=8a5b5b102c) | Apr 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3741318176](https://linux-hardware.org/?probe=3741318176) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [d7d5674aa5](https://linux-hardware.org/?probe=d7d5674aa5) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [e3f3f9fd2b](https://linux-hardware.org/?probe=e3f3f9fd2b) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [62bdfa97bd](https://linux-hardware.org/?probe=62bdfa97bd) | Apr 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.03/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 6.2.6-desktop-1omv2390      | 1786      | 95.61%  |
| 6.2.2-desktop-1omv2390      | 43        | 2.3%    |
| 6.1.1-desktop-1omv2290      | 13        | 0.7%    |
| 6.2.1-desktop-1omv2390      | 8         | 0.43%   |
| 5.16.13-desktop-1omv4003    | 6         | 0.32%   |
| 6.1.4-desktop-1omv2301      | 4         | 0.21%   |
| 6.3.5-desktop-3omv2390      | 2         | 0.11%   |
| 6.2.8-desktop-1omv2390      | 2         | 0.11%   |
| 6.4.11-desktop-1omv2390     | 1         | 0.05%   |
| 6.2.7-desktop-1omv2390      | 1         | 0.05%   |
| 6.2.10-desktop-2.0omv4.9mjn | 1         | 0.05%   |
| 6.1.22-xanmod1              | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 1786      | 95.61%  |
| 6.2.2   | 43        | 2.3%    |
| 6.1.1   | 13        | 0.7%    |
| 6.2.1   | 8         | 0.43%   |
| 5.16.13 | 6         | 0.32%   |
| 6.1.4   | 4         | 0.21%   |
| 6.3.5   | 2         | 0.11%   |
| 6.2.8   | 2         | 0.11%   |
| 6.4.11  | 1         | 0.05%   |
| 6.2.7   | 1         | 0.05%   |
| 6.2.10  | 1         | 0.05%   |
| 6.1.22  | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 1841      | 98.55%  |
| 6.1     | 18        | 0.96%   |
| 5.16    | 6         | 0.32%   |
| 6.3     | 2         | 0.11%   |
| 6.4     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1868      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 1588      | 85.01%  |
| GNOME    | 150       | 8.03%   |
| LXQt     | 113       | 6.05%   |
| Cinnamon | 7         | 0.37%   |
| XFCE     | 3         | 0.16%   |
| Budgie   | 3         | 0.16%   |
| Unknown  | 3         | 0.16%   |
| DWM      | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1718      | 91.97%  |
| Wayland | 150       | 8.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1709      | 91.49%  |
| GDM     | 151       | 8.08%   |
| LightDM | 6         | 0.32%   |
| Unknown | 2         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 882       | 47.22%  |
| de_DE | 147       | 7.87%   |
| fr_FR | 112       | 6%      |
| ru_RU | 102       | 5.46%   |
| en_GB | 84        | 4.5%    |
| pt_BR | 75        | 4.01%   |
| pl_PL | 72        | 3.85%   |
| it_IT | 68        | 3.64%   |
| es_ES | 40        | 2.14%   |
| es_MX | 36        | 1.93%   |
| en_CA | 29        | 1.55%   |
| en_AU | 23        | 1.23%   |
| cs_CZ | 19        | 1.02%   |
| hu_HU | 16        | 0.86%   |
| en_IN | 14        | 0.75%   |
| de_AT | 12        | 0.64%   |
| nl_NL | 11        | 0.59%   |
| es_AR | 9         | 0.48%   |
| tr_TR | 8         | 0.43%   |
| ja_JP | 8         | 0.43%   |
| fr_CA | 8         | 0.43%   |
| fr_BE | 8         | 0.43%   |
| es_VE | 8         | 0.43%   |
| de_CH | 8         | 0.43%   |
| da_DK | 7         | 0.37%   |
| pt_PT | 6         | 0.32%   |
| nl_BE | 5         | 0.27%   |
| es_CO | 5         | 0.27%   |
| fr_CH | 4         | 0.21%   |
| es_UY | 4         | 0.21%   |
| es_PE | 4         | 0.21%   |
| en_ZA | 4         | 0.21%   |
| en_NZ | 4         | 0.21%   |
| UTF-8 | 3         | 0.16%   |
| es_CL | 3         | 0.16%   |
| en_AG | 3         | 0.16%   |
| es_CR | 2         | 0.11%   |
| en_SG | 2         | 0.11%   |
| en_PH | 2         | 0.11%   |
| en_DK | 2         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1110      | 59.42%  |
| BIOS | 758       | 40.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 912       | 48.82%  |
| Overlay  | 812       | 43.47%  |
| Btrfs    | 104       | 5.57%   |
| Xfs      | 20        | 1.07%   |
| F2fs     | 14        | 0.75%   |
| Ext3     | 3         | 0.16%   |
| Jfs      | 2         | 0.11%   |
| Reiserfs | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1481      | 79.28%  |
| MBR     | 386       | 20.66%  |
| Unknown | 1         | 0.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 960       | 51.39%  |
| Yes       | 908       | 48.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1062      | 56.85%  |
| Yes       | 806       | 43.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 278       | 14.88%  |
| Lenovo              | 254       | 13.6%   |
| Hewlett-Packard     | 242       | 12.96%  |
| Dell                | 211       | 11.3%   |
| Gigabyte Technology | 132       | 7.07%   |
| Acer                | 124       | 6.64%   |
| MSI                 | 112       | 6%      |
| ASRock              | 75        | 4.01%   |
| Toshiba             | 44        | 2.36%   |
| Intel               | 33        | 1.77%   |
| Fujitsu             | 33        | 1.77%   |
| Samsung Electronics | 27        | 1.45%   |
| Apple               | 24        | 1.28%   |
| Sony                | 17        | 0.91%   |
| Biostar             | 17        | 0.91%   |
| Unknown             | 17        | 0.91%   |
| Foxconn             | 13        | 0.7%    |
| Packard Bell        | 11        | 0.59%   |
| Medion              | 10        | 0.54%   |
| Fujitsu Siemens     | 10        | 0.54%   |
| Microsoft           | 9         | 0.48%   |
| Chuwi               | 9         | 0.48%   |
| Notebook            | 8         | 0.43%   |
| AZW                 | 8         | 0.43%   |
| Positivo            | 7         | 0.37%   |
| ECS                 | 7         | 0.37%   |
| Pegatron            | 6         | 0.32%   |
| HUAWEI              | 6         | 0.32%   |
| GPU Company         | 5         | 0.27%   |
| Google              | 5         | 0.27%   |
| Alienware           | 5         | 0.27%   |
| TUXEDO              | 4         | 0.21%   |
| NEC Computers       | 4         | 0.21%   |
| LG Electronics      | 4         | 0.21%   |
| eMachines           | 4         | 0.21%   |
| ZOTAC               | 3         | 0.16%   |
| Timi                | 3         | 0.16%   |
| lapbook             | 3         | 0.16%   |
| Kiano               | 3         | 0.16%   |
| Huanan              | 3         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 22        | 1.18%   |
| ASUS All Series                             | 10        | 0.54%   |
| HP Notebook                                 | 9         | 0.48%   |
| Dell OptiPlex 7010                          | 9         | 0.48%   |
| ASUS PRIME A320M-K                          | 7         | 0.37%   |
| Gigabyte Z77M-D3H                           | 6         | 0.32%   |
| ASUS S551LN                                 | 6         | 0.32%   |
| MSI MS-7C02                                 | 5         | 0.27%   |
| MSI MS-7B86                                 | 5         | 0.27%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 5         | 0.27%   |
| Lenovo IdeaPad 1 14ADA05 82GW               | 5         | 0.27%   |
| Intel H61                                   | 5         | 0.27%   |
| Toshiba Satellite L655                      | 4         | 0.21%   |
| Samsung 950XCJ/951XCJ/950XCR                | 4         | 0.21%   |
| Samsung 950QED                              | 4         | 0.21%   |
| MSI MS-7C56                                 | 4         | 0.21%   |
| MSI MS-7817                                 | 4         | 0.21%   |
| MSI MS-7721                                 | 4         | 0.21%   |
| Lenovo V15-ADA 82C7                         | 4         | 0.21%   |
| Lenovo IdeaPad 3 15ALC6 82KU                | 4         | 0.21%   |
| HP Pavilion Notebook                        | 4         | 0.21%   |
| HP EliteDesk 800 G1 SFF                     | 4         | 0.21%   |
| HP 250 G6 Notebook PC                       | 4         | 0.21%   |
| Foxconn G41MD                               | 4         | 0.21%   |
| Dell OptiPlex 9020                          | 4         | 0.21%   |
| Dell OptiPlex 3020                          | 4         | 0.21%   |
| Dell Latitude 7490                          | 4         | 0.21%   |
| Dell Inspiron 1720                          | 4         | 0.21%   |
| ASUS P5G41T-M LX                            | 4         | 0.21%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)          | 3         | 0.16%   |
| MSI MS-7C91                                 | 3         | 0.16%   |
| MSI MS-7C52                                 | 3         | 0.16%   |
| Lenovo V145-15AST 81MT                      | 3         | 0.16%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 3         | 0.16%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3001LUK        | 3         | 0.16%   |
| Lenovo IdeaPad S145-15AST 81N3              | 3         | 0.16%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2         | 3         | 0.16%   |
| Lenovo G50-70 20351                         | 3         | 0.16%   |
| lapbook S15 PRO                             | 3         | 0.16%   |
| Kiano Elegance 14.2                         | 3         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 93        | 4.98%   |
| Acer Aspire             | 86        | 4.6%    |
| Lenovo IdeaPad          | 58        | 3.1%    |
| Dell OptiPlex           | 53        | 2.84%   |
| Dell Latitude           | 53        | 2.84%   |
| Dell Inspiron           | 48        | 2.57%   |
| ASUS PRIME              | 45        | 2.41%   |
| HP Pavilion             | 40        | 2.14%   |
| HP Compaq               | 39        | 2.09%   |
| Toshiba Satellite       | 36        | 1.93%   |
| Lenovo ThinkCentre      | 24        | 1.28%   |
| HP Laptop               | 24        | 1.28%   |
| Dell Precision          | 23        | 1.23%   |
| HP EliteBook            | 22        | 1.18%   |
| ASUS VivoBook           | 22        | 1.18%   |
| Unknown                 | 22        | 1.18%   |
| ASUS ROG                | 17        | 0.91%   |
| HP EliteDesk            | 15        | 0.8%    |
| ASUS TUF                | 15        | 0.8%    |
| Dell Vostro             | 14        | 0.75%   |
| HP ProBook              | 13        | 0.7%    |
| Fujitsu LIFEBOOK        | 13        | 0.7%    |
| Lenovo IdeaCentre       | 10        | 0.54%   |
| Fujitsu ESPRIMO         | 10        | 0.54%   |
| Dell XPS                | 10        | 0.54%   |
| ASUS All                | 10        | 0.54%   |
| Acer Veriton            | 10        | 0.54%   |
| Microsoft Surface       | 9         | 0.48%   |
| HP ProDesk              | 9         | 0.48%   |
| HP Notebook             | 9         | 0.48%   |
| ASUS M5A78L-M           | 8         | 0.43%   |
| Packard Bell EasyNote   | 7         | 0.37%   |
| Lenovo Yoga             | 7         | 0.37%   |
| Lenovo Legion           | 7         | 0.37%   |
| Fujitsu Siemens ESPRIMO | 7         | 0.37%   |
| Toshiba dynabook        | 6         | 0.32%   |
| HP OMEN                 | 6         | 0.32%   |
| HP 250                  | 6         | 0.32%   |
| Gigabyte Z77M-D3H       | 6         | 0.32%   |
| Gigabyte GA-78LMT-USB3  | 6         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 176       | 9.42%   |
| 2012    | 167       | 8.94%   |
| 2020    | 151       | 8.08%   |
| 2011    | 144       | 7.71%   |
| 2018    | 142       | 7.6%    |
| 2019    | 139       | 7.44%   |
| 2013    | 124       | 6.64%   |
| 2014    | 110       | 5.89%   |
| 2017    | 109       | 5.84%   |
| 2010    | 105       | 5.62%   |
| 2015    | 100       | 5.35%   |
| 2016    | 92        | 4.93%   |
| 2008    | 81        | 4.34%   |
| 2022    | 80        | 4.28%   |
| 2009    | 66        | 3.53%   |
| 2007    | 52        | 2.78%   |
| 2006    | 16        | 0.86%   |
| 2023    | 9         | 0.48%   |
| 2005    | 3         | 0.16%   |
| 2004    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 928       | 49.68%  |
| Desktop     | 830       | 44.43%  |
| Mini pc     | 32        | 1.71%   |
| All in one  | 31        | 1.66%   |
| Convertible | 28        | 1.5%    |
| Tablet      | 12        | 0.64%   |
| Server      | 7         | 0.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1868      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1862      | 99.68%  |
| Yes  | 6         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 558       | 29.87%  |
| 3.01-4.0        | 378       | 20.24%  |
| 16.01-24.0      | 345       | 18.47%  |
| 8.01-16.0       | 295       | 15.79%  |
| 32.01-64.0      | 129       | 6.91%   |
| 1.01-2.0        | 53        | 2.84%   |
| 2.01-3.0        | 37        | 1.98%   |
| 64.01-256.0     | 34        | 1.82%   |
| 24.01-32.0      | 32        | 1.71%   |
| 0.51-1.0        | 4         | 0.21%   |
| More than 256.0 | 3         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 1178      | 63.06%  |
| 2.01-3.0  | 473       | 25.32%  |
| 0.51-1.0  | 105       | 5.62%   |
| 3.01-4.0  | 83        | 4.44%   |
| 4.01-8.0  | 18        | 0.96%   |
| 0.01-0.5  | 10        | 0.54%   |
| 8.01-16.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1064      | 56.96%  |
| 2      | 480       | 25.7%   |
| 3      | 155       | 8.3%    |
| 4      | 80        | 4.28%   |
| 5      | 35        | 1.87%   |
| 0      | 27        | 1.45%   |
| 6      | 14        | 0.75%   |
| 7      | 5         | 0.27%   |
| 8      | 4         | 0.21%   |
| 10     | 2         | 0.11%   |
| 13     | 1         | 0.05%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1046      | 56%     |
| Yes       | 822       | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1655      | 88.6%   |
| No        | 213       | 11.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1349      | 72.22%  |
| No        | 519       | 27.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1025      | 54.87%  |
| No        | 843       | 45.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 243       | 13.01%  |
| Germany      | 188       | 10.06%  |
| Russia       | 123       | 6.58%   |
| Brazil       | 121       | 6.48%   |
| France       | 111       | 5.94%   |
| Italy        | 101       | 5.41%   |
| Poland       | 94        | 5.03%   |
| UK           | 77        | 4.12%   |
| Canada       | 61        | 3.27%   |
| Spain        | 54        | 2.89%   |
| Japan        | 54        | 2.89%   |
| India        | 33        | 1.77%   |
| Australia    | 33        | 1.77%   |
| Mexico       | 32        | 1.71%   |
| Netherlands  | 28        | 1.5%    |
| Czechia      | 25        | 1.34%   |
| Finland      | 24        | 1.28%   |
| Hungary      | 20        | 1.07%   |
| Argentina    | 20        | 1.07%   |
| Indonesia    | 17        | 0.91%   |
| Belgium      | 17        | 0.91%   |
| Switzerland  | 16        | 0.86%   |
| Denmark      | 14        | 0.75%   |
| Austria      | 14        | 0.75%   |
| Romania      | 13        | 0.7%    |
| Colombia     | 13        | 0.7%    |
| Venezuela    | 12        | 0.64%   |
| Sweden       | 12        | 0.64%   |
| Portugal     | 12        | 0.64%   |
| Greece       | 12        | 0.64%   |
| Bulgaria     | 12        | 0.64%   |
| Slovakia     | 10        | 0.54%   |
| Peru         | 10        | 0.54%   |
| Norway       | 10        | 0.54%   |
| China        | 10        | 0.54%   |
| Turkey       | 9         | 0.48%   |
| South Africa | 9         | 0.48%   |
| Malaysia     | 8         | 0.43%   |
| Chile        | 8         | 0.43%   |
| Belarus      | 8         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 25        | 1.34%   |
| Milan          | 18        | 0.96%   |
| Warsaw         | 17        | 0.91%   |
| St Petersburg  | 15        | 0.8%    |
| Hamburg        | 14        | 0.75%   |
| Berlin         | 14        | 0.75%   |
| Rio de Janeiro | 12        | 0.64%   |
| Helsinki       | 12        | 0.64%   |
| Montreal       | 11        | 0.59%   |
| Rome           | 10        | 0.54%   |
| Paris          | 10        | 0.54%   |
| Brisbane       | 10        | 0.54%   |
| Vienna         | 9         | 0.48%   |
| Munich         | 9         | 0.48%   |
| Sydney         | 7         | 0.37%   |
| Seattle        | 7         | 0.37%   |
| Prague         | 7         | 0.37%   |
| Mexico City    | 7         | 0.37%   |
| Lima           | 7         | 0.37%   |
| Kuala Lumpur   | 7         | 0.37%   |
| Budapest       | 7         | 0.37%   |
| Athens         | 7         | 0.37%   |
| Yokohama       | 6         | 0.32%   |
| Ufa            | 6         | 0.32%   |
| Sao Paulo      | 6         | 0.32%   |
| Santiago       | 6         | 0.32%   |
| Montevideo     | 6         | 0.32%   |
| Los Angeles    | 6         | 0.32%   |
| Krakow         | 6         | 0.32%   |
| Hexham         | 6         | 0.32%   |
| Freeport       | 6         | 0.32%   |
| Cologne        | 6         | 0.32%   |
| Bogotá        | 6         | 0.32%   |
| Bengaluru      | 6         | 0.32%   |
| Singapore      | 5         | 0.27%   |
| San Jose       | 5         | 0.27%   |
| Pescara        | 5         | 0.27%   |
| Montpellier    | 5         | 0.27%   |
| Melbourne      | 5         | 0.27%   |
| Madrid         | 5         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 403       | 468    | 14.47%  |
| WDC                 | 402       | 487    | 14.43%  |
| Samsung Electronics | 324       | 397    | 11.63%  |
| Toshiba             | 191       | 198    | 6.86%   |
| Kingston            | 172       | 198    | 6.18%   |
| Crucial             | 143       | 158    | 5.13%   |
| SanDisk             | 105       | 116    | 3.77%   |
| Hitachi             | 98        | 103    | 3.52%   |
| Unknown             | 74        | 81     | 2.66%   |
| HGST                | 48        | 51     | 1.72%   |
| China               | 48        | 50     | 1.72%   |
| A-DATA Technology   | 48        | 51     | 1.72%   |
| SPCC                | 47        | 52     | 1.69%   |
| Intel               | 47        | 48     | 1.69%   |
| SK hynix            | 37        | 37     | 1.33%   |
| Micron Technology   | 34        | 34     | 1.22%   |
| PNY                 | 29        | 30     | 1.04%   |
| Transcend           | 22        | 22     | 0.79%   |
| Patriot             | 22        | 22     | 0.79%   |
| JMicron Technology  | 22        | 22     | 0.79%   |
| Phison              | 19        | 20     | 0.68%   |
| Netac               | 19        | 20     | 0.68%   |
| Intenso             | 17        | 18     | 0.61%   |
| GOODRAM             | 17        | 18     | 0.61%   |
| Maxtor              | 15        | 16     | 0.54%   |
| KIOXIA              | 15        | 15     | 0.54%   |
| KingSpec            | 14        | 14     | 0.5%    |
| Gigabyte Technology | 13        | 13     | 0.47%   |
| Team                | 12        | 12     | 0.43%   |
| Apacer              | 12        | 13     | 0.43%   |
| XPG                 | 11        | 13     | 0.39%   |
| LITEON              | 10        | 10     | 0.36%   |
| Apple               | 10        | 11     | 0.36%   |
| Unknown             | 10        | 11     | 0.36%   |
| SABRENT             | 9         | 9      | 0.32%   |
| KIOXIA-EXCERIA      | 9         | 9      | 0.32%   |
| Silicon Motion      | 8         | 8      | 0.29%   |
| Fujitsu             | 8         | 8      | 0.29%   |
| Corsair             | 8         | 8      | 0.29%   |
| Verbatim            | 7         | 7      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 31        | 1.02%   |
| Seagate ST500DM002-1BD142 500GB    | 25        | 0.82%   |
| Toshiba DT01ACA100 1TB             | 24        | 0.79%   |
| Kingston SA400S37480G 480GB SSD    | 24        | 0.79%   |
| Crucial CT500MX500SSD1 500GB       | 22        | 0.73%   |
| Crucial CT240BX500SSD1 240GB       | 21        | 0.69%   |
| Toshiba MQ01ABD100 1TB             | 20        | 0.66%   |
| Toshiba MQ01ABF050 500GB           | 19        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB     | 18        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB     | 16        | 0.53%   |
| Unknown SD/MMC/MS PRO 1GB          | 15        | 0.49%   |
| Seagate ST500LT012-1DG142 500GB    | 15        | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB     | 15        | 0.49%   |
| Samsung SSD 860 EVO 500GB          | 15        | 0.49%   |
| Kingston SA400S37120G 120GB SSD    | 15        | 0.49%   |
| Crucial CT480BX500SSD1 480GB       | 15        | 0.49%   |
| Samsung SSD 860 EVO 250GB          | 13        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB        | 13        | 0.43%   |
| Toshiba MQ04ABF100 1TB             | 12        | 0.4%    |
| SPCC Solid State Disk 512GB        | 12        | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 12        | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB     | 12        | 0.4%    |
| SanDisk NVMe SSD Drive 1TB         | 12        | 0.4%    |
| JMicron Generic 1TB                | 12        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 11        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB           | 11        | 0.36%   |
| Toshiba DT01ACA050 500GB           | 11        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD   | 11        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 10        | 0.33%   |
| Seagate ST9500325AS 500GB          | 10        | 0.33%   |
| Seagate ST3500418AS 500GB          | 10        | 0.33%   |
| Seagate ST1000LM048-2E7172 1TB     | 10        | 0.33%   |
| Samsung SSD 970 EVO Plus 1TB       | 10        | 0.33%   |
| Samsung SSD 860 EVO 1TB            | 10        | 0.33%   |
| Samsung SSD 850 EVO 500GB          | 10        | 0.33%   |
| Crucial CT1000BX500SSD1 1TB        | 10        | 0.33%   |
| Unknown                            | 10        | 0.33%   |
| Toshiba HDWD110 1TB                | 9         | 0.3%    |
| Seagate ST2000DM001-1ER164 2TB     | 9         | 0.3%    |
| Samsung SSD 850 EVO 250GB          | 9         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 393       | 454    | 34.87%  |
| WDC                 | 302       | 357    | 26.8%   |
| Toshiba             | 168       | 173    | 14.91%  |
| Hitachi             | 98        | 103    | 8.7%    |
| HGST                | 48        | 51     | 4.26%   |
| Samsung Electronics | 47        | 53     | 4.17%   |
| Unknown             | 15        | 15     | 1.33%   |
| Maxtor              | 14        | 15     | 1.24%   |
| SABRENT             | 8         | 8      | 0.71%   |
| Fujitsu             | 8         | 8      | 0.71%   |
| Apple               | 5         | 5      | 0.44%   |
| WD MediaMax         | 2         | 2      | 0.18%   |
| StoreJet            | 2         | 2      | 0.18%   |
| Intenso             | 2         | 2      | 0.18%   |
| External            | 2         | 2      | 0.18%   |
| ExcelStor           | 2         | 2      | 0.18%   |
| USB3.0              | 1         | 1      | 0.09%   |
| USB                 | 1         | 1      | 0.09%   |
| SSK                 | 1         | 1      | 0.09%   |
| SAGE                | 1         | 1      | 0.09%   |
| RSH-319             | 1         | 1      | 0.09%   |
| QUANTUM             | 1         | 1      | 0.09%   |
| MaxDigital          | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| KESU                | 1         | 1      | 0.09%   |
| Initio              | 1         | 1      | 0.09%   |
| Hewlett-Packard     | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 160       | 184    | 14.69%  |
| Kingston            | 125       | 144    | 11.48%  |
| Crucial             | 117       | 122    | 10.74%  |
| SanDisk             | 79        | 86     | 7.25%   |
| WDC                 | 66        | 73     | 6.06%   |
| China               | 48        | 50     | 4.41%   |
| SPCC                | 38        | 40     | 3.49%   |
| A-DATA Technology   | 38        | 40     | 3.49%   |
| PNY                 | 24        | 25     | 2.2%    |
| Intel               | 22        | 22     | 2.02%   |
| Patriot             | 21        | 21     | 1.93%   |
| Transcend           | 18        | 18     | 1.65%   |
| Micron Technology   | 18        | 18     | 1.65%   |
| Netac               | 17        | 18     | 1.56%   |
| JMicron Technology  | 16        | 16     | 1.47%   |
| Toshiba             | 15        | 15     | 1.38%   |
| Intenso             | 15        | 15     | 1.38%   |
| GOODRAM             | 15        | 16     | 1.38%   |
| KingSpec            | 12        | 12     | 1.1%    |
| SK hynix            | 11        | 11     | 1.01%   |
| LITEON              | 10        | 10     | 0.92%   |
| Gigabyte Technology | 10        | 10     | 0.92%   |
| Apacer              | 9         | 9      | 0.83%   |
| Team                | 8         | 8      | 0.73%   |
| Verbatim            | 7         | 7      | 0.64%   |
| OCZ                 | 7         | 9      | 0.64%   |
| Seagate             | 6         | 6      | 0.55%   |
| Unknown             | 6         | 7      | 0.55%   |
| Teclast             | 5         | 5      | 0.46%   |
| KingFast            | 5         | 5      | 0.46%   |
| KingDian            | 5         | 5      | 0.46%   |
| XrayDisk            | 4         | 4      | 0.37%   |
| Mushkin             | 4         | 4      | 0.37%   |
| Lexar               | 4         | 4      | 0.37%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.37%   |
| Emtec               | 4         | 4      | 0.37%   |
| ASMT                | 4         | 4      | 0.37%   |
| Wibtek              | 3         | 3      | 0.28%   |
| ShiJi               | 3         | 3      | 0.28%   |
| Leven               | 3         | 3      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 943       | 1263   | 38.71%  |
| SSD     | 911       | 1163   | 37.4%   |
| NVMe    | 491       | 585    | 20.16%  |
| MMC     | 63        | 66     | 2.59%   |
| Unknown | 28        | 33     | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1525      | 2278   | 68.2%   |
| NVMe | 489       | 581    | 21.87%  |
| SAS  | 159       | 185    | 7.11%   |
| MMC  | 63        | 66     | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1182      | 1532   | 61.31%  |
| 0.51-1.0        | 546       | 648    | 28.32%  |
| 1.01-2.0        | 127       | 155    | 6.59%   |
| 2.01-3.0        | 28        | 31     | 1.45%   |
| 3.01-4.0        | 22        | 29     | 1.14%   |
| 4.01-10.0       | 19        | 26     | 0.99%   |
| 10.01-20.0      | 3         | 4      | 0.16%   |
| More than 100.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 618       | 33.08%  |
| 101-250        | 388       | 20.77%  |
| 251-500        | 299       | 16.01%  |
| 501-1000       | 168       | 8.99%   |
| 51-100         | 111       | 5.94%   |
| 21-50          | 105       | 5.62%   |
| Unknown        | 72        | 3.85%   |
| 1001-2000      | 62        | 3.32%   |
| 2001-3000      | 24        | 1.28%   |
| More than 3000 | 21        | 1.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1461      | 78.21%  |
| 21-50          | 131       | 7.01%   |
| Unknown        | 72        | 3.85%   |
| 101-250        | 59        | 3.16%   |
| 51-100         | 57        | 3.05%   |
| 251-500        | 38        | 2.03%   |
| 501-1000       | 33        | 1.77%   |
| 1001-2000      | 7         | 0.37%   |
| More than 3000 | 5         | 0.27%   |
| 2001-3000      | 5         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 13        | 13     | 2.55%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 7         | 7      | 1.37%   |
| Seagate ST9500325AS 500GB            | 7         | 7      | 1.37%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 6      | 1.18%   |
| Seagate ST3500418AS 500GB            | 6         | 6      | 1.18%   |
| Hitachi HDS721010CLA332 1TB          | 6         | 6      | 1.18%   |
| HGST HTS541010A9E680 1TB             | 6         | 6      | 1.18%   |
| WDC WD5000AAKX-001CA0 500GB          | 5         | 5      | 0.98%   |
| Toshiba MQ01ABD100 1TB               | 5         | 5      | 0.98%   |
| Toshiba MQ01ABD050 500GB             | 5         | 5      | 0.98%   |
| Hitachi HTS723232A7A364 320GB        | 5         | 5      | 0.98%   |
| HGST HTS545050A7E680 500GB           | 5         | 5      | 0.98%   |
| HGST HTS545050A7E380 500GB           | 5         | 5      | 0.98%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.78%   |
| Seagate ST3320418AS 320GB            | 4         | 4      | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 4      | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 4      | 0.78%   |
| Hitachi HTS547575A9E384 752GB        | 4         | 4      | 0.78%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 0.78%   |
| WDC WD10EALX-009BA0 1TB              | 3         | 3      | 0.59%   |
| Toshiba MQ04ABF100 1TB               | 3         | 3      | 0.59%   |
| Toshiba DT01ACA100 1TB               | 3         | 3      | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB      | 3         | 3      | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.59%   |
| Seagate ST3500413AS 500GB            | 3         | 3      | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB       | 3         | 4      | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 3      | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 3      | 0.59%   |
| Samsung Electronics HD103SI 1TB      | 3         | 3      | 0.59%   |
| Netac SSD 120GB                      | 3         | 3      | 0.59%   |
| LITEON CV8-8E128-HP 128GB SSD        | 3         | 3      | 0.59%   |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 2      | 0.39%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 2      | 0.39%   |
| WDC WD3200AAKS-61L9A0 320GB          | 2         | 2      | 0.39%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 2      | 0.39%   |
| WDC WD10EARS-00Y5B1 1TB              | 2         | 2      | 0.39%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2         | 2      | 0.39%   |
| WDC WD Blue SA510 M.2 2280 500GB SSD | 2         | 2      | 0.39%   |
| Toshiba MQ01ABD075 752GB             | 2         | 2      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 142    | 28.14%  |
| WDC                 | 107       | 116    | 21.36%  |
| Toshiba             | 46        | 46     | 9.18%   |
| Hitachi             | 46        | 47     | 9.18%   |
| Samsung Electronics | 30        | 31     | 5.99%   |
| HGST                | 27        | 28     | 5.39%   |
| Intel               | 14        | 14     | 2.79%   |
| Maxtor              | 9         | 10     | 1.8%    |
| Kingston            | 8         | 9      | 1.6%    |
| China               | 7         | 7      | 1.4%    |
| SK hynix            | 6         | 6      | 1.2%    |
| Fujitsu             | 6         | 6      | 1.2%    |
| SanDisk             | 5         | 5      | 1%      |
| Netac               | 4         | 4      | 0.8%    |
| KingSpec            | 4         | 4      | 0.8%    |
| Intenso             | 4         | 4      | 0.8%    |
| Crucial             | 4         | 4      | 0.8%    |
| A-DATA Technology   | 4         | 4      | 0.8%    |
| SPCC                | 3         | 3      | 0.6%    |
| LITEON              | 3         | 3      | 0.6%    |
| ExcelStor           | 2         | 2      | 0.4%    |
| Apple               | 2         | 2      | 0.4%    |
| WD MediaMax         | 1         | 1      | 0.2%    |
| Transcend           | 1         | 1      | 0.2%    |
| Teclast             | 1         | 1      | 0.2%    |
| Team                | 1         | 1      | 0.2%    |
| SATAFIRM            | 1         | 1      | 0.2%    |
| SAGE                | 1         | 1      | 0.2%    |
| RSH-319             | 1         | 1      | 0.2%    |
| QUANTUM             | 1         | 1      | 0.2%    |
| Plextor             | 1         | 1      | 0.2%    |
| Patriot             | 1         | 1      | 0.2%    |
| OCZ                 | 1         | 1      | 0.2%    |
| Micron Technology   | 1         | 1      | 0.2%    |
| KingDian            | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| Indilinx            | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| Fanxiang            | 1         | 1      | 0.2%    |
| BAITITON            | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 142    | 34.56%  |
| WDC                 | 100       | 108    | 24.51%  |
| Hitachi             | 46        | 47     | 11.27%  |
| Toshiba             | 45        | 45     | 11.03%  |
| HGST                | 27        | 28     | 6.62%   |
| Samsung Electronics | 26        | 27     | 6.37%   |
| Maxtor              | 9         | 10     | 2.21%   |
| Fujitsu             | 6         | 6      | 1.47%   |
| ExcelStor           | 2         | 2      | 0.49%   |
| Apple               | 2         | 2      | 0.49%   |
| WD MediaMax         | 1         | 1      | 0.25%   |
| SAGE                | 1         | 1      | 0.25%   |
| RSH-319             | 1         | 1      | 0.25%   |
| QUANTUM             | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 379       | 421    | 80.13%  |
| SSD  | 85        | 86     | 17.97%  |
| NVMe | 9         | 9      | 1.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800JD-00MSA1 80GB           | 1         | 1      | 7.69%   |
| WDC WD3200BPVT-00JJ5T0 320GB      | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-00YZCA0 160GB      | 1         | 1      | 7.69%   |
| Toshiba MK3261GSYN 320GB          | 1         | 1      | 7.69%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 7.69%   |
| Seagate ST9320423AS 320GB         | 1         | 1      | 7.69%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 7.69%   |
| Samsung Electronics HM250HI 250GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD252HJ 250GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD103UJ 1TB   | 1         | 1      | 7.69%   |
| HGST HTS545050B7E660 500GB        | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 38.46%  |
| WDC                 | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Seagate             | 2         | 2      | 15.38%  |
| HGST                | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1523      | 2343   | 69.1%   |
| Malfunc  | 460       | 516    | 20.87%  |
| Detected | 208       | 238    | 9.44%   |
| Failed   | 13        | 13     | 0.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1295      | 55.92%  |
| AMD                                     | 401       | 17.31%  |
| Samsung Electronics                     | 143       | 6.17%   |
| SanDisk                                 | 76        | 3.28%   |
| Kingston Technology Company             | 53        | 2.29%   |
| Phison Electronics                      | 50        | 2.16%   |
| Micron/Crucial Technology               | 32        | 1.38%   |
| ASMedia Technology                      | 32        | 1.38%   |
| Nvidia                                  | 31        | 1.34%   |
| Silicon Motion                          | 29        | 1.25%   |
| SK hynix                                | 24        | 1.04%   |
| KIOXIA                                  | 19        | 0.82%   |
| ADATA Technology                        | 19        | 0.82%   |
| Micron Technology                       | 16        | 0.69%   |
| Marvell Technology Group                | 13        | 0.56%   |
| JMicron Technology                      | 12        | 0.52%   |
| Toshiba America Info Systems            | 11        | 0.47%   |
| VIA Technologies                        | 9         | 0.39%   |
| MAXIO Technology (Hangzhou)             | 9         | 0.39%   |
| Union Memory (Shenzhen)                 | 6         | 0.26%   |
| Realtek Semiconductor                   | 6         | 0.26%   |
| Solid State Storage Technology          | 5         | 0.22%   |
| Seagate Technology                      | 3         | 0.13%   |
| Broadcom / LSI                          | 3         | 0.13%   |
| Biwin Storage Technology                | 3         | 0.13%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.09%   |
| Shenzhen Longsys Electronics            | 2         | 0.09%   |
| Netac Technology                        | 2         | 0.09%   |
| Lenovo                                  | 2         | 0.09%   |
| Transcend                               | 1         | 0.04%   |
| Silicon Image                           | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| Promise Technology                      | 1         | 0.04%   |
| LSI Logic / Symbios Logic               | 1         | 0.04%   |
| Lite-On Technology                      | 1         | 0.04%   |
| Integrated Technology Express           | 1         | 0.04%   |
| Apple                                   | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 247       | 9.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 101       | 3.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 91        | 3.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 88        | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 66        | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 53        | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 52        | 1.92%   |
| AMD 400 Series Chipset SATA Controller                                                  | 52        | 1.92%   |
| Samsung NVMe SSD Controller 980                                                         | 50        | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50        | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 48        | 1.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 48        | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 47        | 1.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 46        | 1.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 46        | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 43        | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 42        | 1.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 41        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 41        | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 38        | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 35        | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 33        | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 33        | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 32        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 32        | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 30        | 1.11%   |
| Intel SATA Controller [RAID mode]                                                       | 30        | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 30        | 1.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 30        | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 29        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 27        | 1%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 24        | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 23        | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 23        | 0.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 23        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 23        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 23        | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 23        | 0.85%   |
| Phison PS5013 E13 NVMe Controller                                                       | 21        | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 21        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1462      | 61.71%  |
| NVMe | 487       | 20.56%  |
| IDE  | 288       | 12.16%  |
| RAID | 126       | 5.32%   |
| SAS  | 5         | 0.21%   |
| SCSI | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1391      | 74.46%  |
| AMD    | 477       | 25.54%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics        | 19        | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 0.91%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 16        | 0.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 13        | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 13        | 0.7%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 13        | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 12        | 0.64%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.64%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 11        | 0.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 11        | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 11        | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.59%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 11        | 0.59%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 11        | 0.59%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 11        | 0.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 11        | 0.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 10        | 0.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 10        | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 10        | 0.54%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 0.54%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.54%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 9         | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.48%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 9         | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 9         | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.48%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 9         | 0.48%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.48%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 9         | 0.48%   |
| AMD 3020e with Radeon Graphics                | 9         | 0.48%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 8         | 0.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 391       | 20.93%  |
| Intel Core i7           | 230       | 12.31%  |
| Intel Core i3           | 203       | 10.87%  |
| Intel Celeron           | 134       | 7.17%   |
| AMD Ryzen 5             | 127       | 6.8%    |
| Other                   | 117       | 6.26%   |
| Intel Core 2 Duo        | 103       | 5.51%   |
| Intel Pentium           | 65        | 3.48%   |
| AMD Ryzen 7             | 64        | 3.43%   |
| AMD Ryzen 3             | 35        | 1.87%   |
| Intel Pentium Dual-Core | 31        | 1.66%   |
| Intel Xeon              | 30        | 1.61%   |
| AMD FX                  | 27        | 1.45%   |
| AMD A8                  | 23        | 1.23%   |
| Intel Core 2 Quad       | 21        | 1.12%   |
| AMD A4                  | 18        | 0.96%   |
| Intel Pentium Dual      | 17        | 0.91%   |
| AMD Ryzen 9             | 16        | 0.86%   |
| AMD A6                  | 15        | 0.8%    |
| AMD Athlon              | 14        | 0.75%   |
| AMD A10                 | 13        | 0.7%    |
| Intel Core 2            | 11        | 0.59%   |
| AMD Athlon II X2        | 11        | 0.59%   |
| AMD Athlon 64 X2        | 11        | 0.59%   |
| Intel Pentium Silver    | 10        | 0.54%   |
| Intel Atom              | 10        | 0.54%   |
| Intel Genuine           | 8         | 0.43%   |
| Intel Core i9           | 8         | 0.43%   |
| Intel Pentium Gold      | 7         | 0.37%   |
| AMD Phenom II X6        | 6         | 0.32%   |
| AMD E                   | 6         | 0.32%   |
| AMD E1                  | 5         | 0.27%   |
| Intel Celeron Dual-Core | 4         | 0.21%   |
| AMD Turion 64 X2 Mobile | 4         | 0.21%   |
| AMD Ryzen 5 PRO         | 4         | 0.21%   |
| AMD Athlon X4           | 4         | 0.21%   |
| AMD A12                 | 4         | 0.21%   |
| Intel Pentium 4         | 3         | 0.16%   |
| AMD Sempron             | 3         | 0.16%   |
| AMD Ryzen 7 PRO         | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 908       | 48.61%  |
| 4      | 572       | 30.62%  |
| 6      | 173       | 9.26%   |
| 8      | 102       | 5.46%   |
| 1      | 54        | 2.89%   |
| 12     | 16        | 0.86%   |
| 14     | 13        | 0.7%    |
| 3      | 12        | 0.64%   |
| 16     | 9         | 0.48%   |
| 10     | 6         | 0.32%   |
| 24     | 3         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1861      | 99.63%  |
| 2      | 7         | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1125      | 60.22%  |
| 1      | 729       | 39.03%  |
| 4      | 10        | 0.54%   |
| 8      | 3         | 0.16%   |
| 16     | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1868      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1403      | 75.11%  |
| 0x08108109 | 46        | 2.46%   |
| 0x0a50000c | 29        | 1.55%   |
| 0x0a50000d | 25        | 1.34%   |
| 0x08701021 | 25        | 1.34%   |
| 0x06001119 | 23        | 1.23%   |
| 0x08608103 | 17        | 0.91%   |
| 0x06006705 | 16        | 0.86%   |
| 0x010000c8 | 15        | 0.8%    |
| 0x0800820d | 14        | 0.75%   |
| 0x06003106 | 14        | 0.75%   |
| 0x08101016 | 13        | 0.7%    |
| 0x06000822 | 11        | 0.59%   |
| 0x08108102 | 10        | 0.54%   |
| 0x0600611a | 10        | 0.54%   |
| 0x0a20120a | 9         | 0.48%   |
| 0x0a201016 | 9         | 0.48%   |
| 0x08200103 | 9         | 0.48%   |
| 0x0500010d | 9         | 0.48%   |
| 0x08600106 | 8         | 0.43%   |
| 0x0700010b | 7         | 0.37%   |
| 0x010000b6 | 7         | 0.37%   |
| 0x07030105 | 6         | 0.32%   |
| 0x05000101 | 6         | 0.32%   |
| 0x010000bf | 6         | 0.32%   |
| 0x0a201025 | 5         | 0.27%   |
| 0x08600104 | 5         | 0.27%   |
| 0x0810100b | 5         | 0.27%   |
| 0x0600081c | 5         | 0.27%   |
| 0x206a7    | 4         | 0.21%   |
| 0x08608102 | 4         | 0.21%   |
| 0x08600103 | 4         | 0.21%   |
| 0x03000027 | 4         | 0.21%   |
| 0x08701030 | 3         | 0.16%   |
| 0x08701013 | 3         | 0.16%   |
| 0x08600109 | 3         | 0.16%   |
| 0x0800820b | 3         | 0.16%   |
| 0x02000057 | 3         | 0.16%   |
| 0x02000032 | 3         | 0.16%   |
| 0x00000000 | 3         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 223       | 11.94%  |
| Haswell          | 153       | 8.19%   |
| IvyBridge        | 150       | 8.03%   |
| SandyBridge      | 144       | 7.71%   |
| Penryn           | 130       | 6.96%   |
| Skylake          | 114       | 6.1%    |
| Zen 3            | 83        | 4.44%   |
| Zen+             | 74        | 3.96%   |
| Core             | 74        | 3.96%   |
| Westmere         | 57        | 3.05%   |
| Zen 2            | 54        | 2.89%   |
| Silvermont       | 53        | 2.84%   |
| Piledriver       | 50        | 2.68%   |
| TigerLake        | 47        | 2.52%   |
| Goldmont plus    | 45        | 2.41%   |
| K10              | 41        | 2.19%   |
| Broadwell        | 41        | 2.19%   |
| IceLake          | 37        | 1.98%   |
| CometLake        | 37        | 1.98%   |
| Zen              | 36        | 1.93%   |
| Alderlake Hybrid | 34        | 1.82%   |
| Excavator        | 30        | 1.61%   |
| Unknown          | 28        | 1.5%    |
| K8 Hammer        | 20        | 1.07%   |
| Goldmont         | 19        | 1.02%   |
| Bobcat           | 16        | 0.86%   |
| Steamroller      | 15        | 0.8%    |
| Nehalem          | 12        | 0.64%   |
| Tremont          | 9         | 0.48%   |
| Jaguar           | 9         | 0.48%   |
| Puma             | 7         | 0.37%   |
| Bonnell          | 7         | 0.37%   |
| K8 & K10 hybrid  | 6         | 0.32%   |
| K10 Llano        | 6         | 0.32%   |
| NetBurst         | 3         | 0.16%   |
| Bulldozer        | 3         | 0.16%   |
| Gracemont        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1071      | 51.42%  |
| AMD                                          | 513       | 24.63%  |
| Nvidia                                       | 491       | 23.57%  |
| Silicon Integrated Systems [SiS]             | 2         | 0.1%    |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.05%   |
| S3 Graphics                                  | 1         | 0.05%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.05%   |
| Matrox Electronics Systems                   | 1         | 0.05%   |
| ATI Technologies                             | 1         | 0.05%   |
| ASPEED Technology                            | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 110       | 5.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 75        | 3.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 62        | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 50        | 2.34%   |
| Intel HD Graphics 620                                                                    | 48        | 2.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 47        | 2.2%    |
| Intel HD Graphics 530                                                                    | 46        | 2.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 2.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 42        | 1.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 1.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 1.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 32        | 1.5%    |
| Intel UHD Graphics 620                                                                   | 32        | 1.5%    |
| Intel HD Graphics 5500                                                                   | 32        | 1.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 1.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 30        | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 1.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 26        | 1.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26        | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 22        | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 22        | 1.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 22        | 1.03%   |
| AMD Lucienne                                                                             | 21        | 0.98%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 19        | 0.89%   |
| Intel HD Graphics 630                                                                    | 19        | 0.89%   |
| AMD Renoir                                                                               | 18        | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 0.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 0.8%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 17        | 0.8%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 16        | 0.75%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 16        | 0.75%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 14        | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 13        | 0.61%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 0.61%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 13        | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.56%   |
| Intel HD Graphics 500                                                                    | 12        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 783       | 41.92%  |
| 1 x AMD                                  | 426       | 22.81%  |
| 1 x Nvidia                               | 314       | 16.81%  |
| Intel + Nvidia                           | 149       | 7.98%   |
| 2 x Intel                                | 101       | 5.41%   |
| Intel + AMD                              | 36        | 1.93%   |
| 2 x AMD                                  | 26        | 1.39%   |
| AMD + Nvidia                             | 23        | 1.23%   |
| 1 x SiS                                  | 2         | 0.11%   |
| Intel + AMD + 1 x Nvidia                 | 2         | 0.11%   |
| 2 x Nvidia                               | 1         | 0.05%   |
| 1 x S3 Graphics                          | 1         | 0.05%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.05%   |
| Nvidia + XGI                             | 1         | 0.05%   |
| 1 x ASPEED                               | 1         | 0.05%   |
| AMD + Matrox                             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1778      | 95.18%  |
| Proprietary | 53        | 2.84%   |
| Unknown     | 37        | 1.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 929       | 49.73%  |
| 1.01-2.0   | 265       | 14.19%  |
| 0.01-0.5   | 243       | 13.01%  |
| 0.51-1.0   | 153       | 8.19%   |
| 3.01-4.0   | 127       | 6.8%    |
| 7.01-8.0   | 71        | 3.8%    |
| 5.01-6.0   | 48        | 2.57%   |
| 8.01-16.0  | 21        | 1.12%   |
| 2.01-3.0   | 7         | 0.37%   |
| 16.01-24.0 | 3         | 0.16%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 238       | 12.7%   |
| AU Optronics            | 224       | 11.95%  |
| LG Display              | 162       | 8.64%   |
| BOE                     | 152       | 8.11%   |
| Chimei Innolux          | 143       | 7.63%   |
| Goldstar                | 102       | 5.44%   |
| Hewlett-Packard         | 86        | 4.59%   |
| Dell                    | 81        | 4.32%   |
| Acer                    | 68        | 3.63%   |
| AOC                     | 62        | 3.31%   |
| Philips                 | 48        | 2.56%   |
| BenQ                    | 47        | 2.51%   |
| Lenovo                  | 43        | 2.29%   |
| Ancor Communications    | 29        | 1.55%   |
| Sharp                   | 27        | 1.44%   |
| ViewSonic               | 25        | 1.33%   |
| Chi Mei Optoelectronics | 22        | 1.17%   |
| Apple                   | 22        | 1.17%   |
| LG Philips              | 21        | 1.12%   |
| ASUSTek Computer        | 21        | 1.12%   |
| Iiyama                  | 19        | 1.01%   |
| PANDA                   | 12        | 0.64%   |
| Unknown                 | 11        | 0.59%   |
| Sony                    | 10        | 0.53%   |
| Sceptre Tech            | 10        | 0.53%   |
| NEC Computers           | 8         | 0.43%   |
| HannStar                | 8         | 0.43%   |
| Unknown                 | 8         | 0.43%   |
| MSI                     | 7         | 0.37%   |
| Panasonic               | 6         | 0.32%   |
| InfoVision              | 6         | 0.32%   |
| HKC                     | 6         | 0.32%   |
| Fujitsu Siemens         | 5         | 0.27%   |
| Unknown (XXX)           | 4         | 0.21%   |
| Seiki                   | 4         | 0.21%   |
| LG Electronics          | 4         | 0.21%   |
| Insignia                | 4         | 0.21%   |
| Hitachi                 | 4         | 0.21%   |
| Eizo                    | 4         | 0.21%   |
| CSO                     | 4         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 10        | 0.53%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 10        | 0.53%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 0.42%   |
| Unknown                                                                  | 8         | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 7         | 0.37%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 6         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch    | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 6         | 0.32%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 6         | 0.32%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                         | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch            | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 6         | 0.32%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 6         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 5         | 0.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 5         | 0.26%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.26%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 5         | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 5         | 0.26%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 5         | 0.26%   |
| Seiki SE20HY SEK0CA8 1360x768 440x250mm 19.9-inch                        | 4         | 0.21%   |
| Samsung Electronics SyncMaster SAM0527 1600x900 443x250mm 20.0-inch      | 4         | 0.21%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 4         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 4         | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 0.21%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 4         | 0.21%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.21%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 4         | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 826       | 44.77%  |
| 1366x768 (WXGA)    | 405       | 21.95%  |
| 3840x2160 (4K)     | 89        | 4.82%   |
| 1600x900 (HD+)     | 87        | 4.72%   |
| 2560x1440 (QHD)    | 65        | 3.52%   |
| 1680x1050 (WSXGA+) | 63        | 3.41%   |
| 1280x800 (WXGA)    | 50        | 2.71%   |
| 1280x1024 (SXGA)   | 49        | 2.66%   |
| 1440x900 (WXGA+)   | 43        | 2.33%   |
| 1920x1200 (WUXGA)  | 38        | 2.06%   |
| 1360x768           | 26        | 1.41%   |
| 2560x1600          | 16        | 0.87%   |
| 3440x1440          | 14        | 0.76%   |
| 2560x1080          | 8         | 0.43%   |
| 2288x1287          | 6         | 0.33%   |
| 1920x540           | 6         | 0.33%   |
| 1024x768 (XGA)     | 5         | 0.27%   |
| Unknown            | 5         | 0.27%   |
| 3840x2400          | 4         | 0.22%   |
| 2736x1824          | 4         | 0.22%   |
| 2160x1440          | 4         | 0.22%   |
| 1920x1280          | 4         | 0.22%   |
| 2880x1800          | 3         | 0.16%   |
| 1280x960           | 3         | 0.16%   |
| 3200x1800 (QHD+)   | 2         | 0.11%   |
| 1280x720 (HD)      | 2         | 0.11%   |
| 1024x600           | 2         | 0.11%   |
| 8320x1440          | 1         | 0.05%   |
| 800x1280           | 1         | 0.05%   |
| 6000x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 5120x1440          | 1         | 0.05%   |
| 4480x2023          | 1         | 0.05%   |
| 3840x1080          | 1         | 0.05%   |
| 3456x2160          | 1         | 0.05%   |
| 2880x1920          | 1         | 0.05%   |
| 2240x1400          | 1         | 0.05%   |
| 2160x1350          | 1         | 0.05%   |
| 1800x1200          | 1         | 0.05%   |
| 1600x2560          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 474       | 25.27%  |
| 27      | 138       | 7.36%   |
| 23      | 138       | 7.36%   |
| 13      | 138       | 7.36%   |
| 21      | 130       | 6.93%   |
| 14      | 126       | 6.72%   |
| 24      | 117       | 6.24%   |
| 17      | 111       | 5.92%   |
| 19      | 52        | 2.77%   |
| 18      | 52        | 2.77%   |
| 22      | 48        | 2.56%   |
| Unknown | 47        | 2.51%   |
| 31      | 46        | 2.45%   |
| 12      | 39        | 2.08%   |
| 20      | 33        | 1.76%   |
| 11      | 28        | 1.49%   |
| 34      | 21        | 1.12%   |
| 16      | 18        | 0.96%   |
| 54      | 16        | 0.85%   |
| 84      | 12        | 0.64%   |
| 32      | 8         | 0.43%   |
| 72      | 7         | 0.37%   |
| 40      | 7         | 0.37%   |
| 25      | 7         | 0.37%   |
| 142     | 6         | 0.32%   |
| 26      | 6         | 0.32%   |
| 10      | 6         | 0.32%   |
| 39      | 5         | 0.27%   |
| 52      | 4         | 0.21%   |
| 48      | 4         | 0.21%   |
| 46      | 4         | 0.21%   |
| 65      | 3         | 0.16%   |
| 37      | 3         | 0.16%   |
| 29      | 3         | 0.16%   |
| 60      | 2         | 0.11%   |
| 36      | 2         | 0.11%   |
| 35      | 2         | 0.11%   |
| 28      | 2         | 0.11%   |
| 74      | 1         | 0.05%   |
| 64      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 711       | 38.29%  |
| 501-600        | 365       | 19.66%  |
| 401-500        | 290       | 15.62%  |
| 351-400        | 136       | 7.32%   |
| 201-300        | 124       | 6.68%   |
| 601-700        | 66        | 3.55%   |
| Unknown        | 47        | 2.53%   |
| 1001-1500      | 38        | 2.05%   |
| 701-800        | 33        | 1.78%   |
| 1501-2000      | 20        | 1.08%   |
| 801-900        | 17        | 0.92%   |
| More than 2000 | 6         | 0.32%   |
| 901-1000       | 2         | 0.11%   |
| 101-200        | 1         | 0.05%   |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1411      | 79.05%  |
| 16/10   | 218       | 12.21%  |
| 5/4     | 50        | 2.8%    |
| Unknown | 31        | 1.74%   |
| 3/2     | 26        | 1.46%   |
| 21/9    | 22        | 1.23%   |
| 4/3     | 15        | 0.84%   |
| 1.00    | 6         | 0.34%   |
| 32/9    | 1         | 0.06%   |
| 2.12    | 1         | 0.06%   |
| 2.00    | 1         | 0.06%   |
| 1.96    | 1         | 0.06%   |
| 0.67    | 1         | 0.06%   |
| 0.63    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 477       | 25.54%  |
| 201-250        | 346       | 18.52%  |
| 81-90          | 219       | 11.72%  |
| 301-350        | 140       | 7.49%   |
| 151-200        | 133       | 7.12%   |
| 351-500        | 79        | 4.23%   |
| 141-150        | 68        | 3.64%   |
| 121-130        | 67        | 3.59%   |
| More than 1000 | 59        | 3.16%   |
| 71-80          | 51        | 2.73%   |
| 251-300        | 48        | 2.57%   |
| Unknown        | 47        | 2.52%   |
| 51-60          | 31        | 1.66%   |
| 61-70          | 30        | 1.61%   |
| 131-140        | 26        | 1.39%   |
| 501-1000       | 26        | 1.39%   |
| 111-120        | 12        | 0.64%   |
| 91-100         | 4         | 0.21%   |
| 41-50          | 3         | 0.16%   |
| 1-40           | 2         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 677       | 36.81%  |
| 101-120       | 550       | 29.91%  |
| 121-160       | 417       | 22.68%  |
| 161-240       | 71        | 3.86%   |
| 1-50          | 57        | 3.1%    |
| Unknown       | 47        | 2.56%   |
| More than 240 | 20        | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1695      | 90.74%  |
| 2     | 147       | 7.87%   |
| 0     | 16        | 0.86%   |
| 3     | 9         | 0.48%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1098      | 40.65%  |
| Intel                             | 804       | 29.77%  |
| Qualcomm Atheros                  | 332       | 12.29%  |
| Broadcom                          | 125       | 4.63%   |
| MediaTek                          | 38        | 1.41%   |
| Ralink Technology                 | 35        | 1.3%    |
| Broadcom Limited                  | 28        | 1.04%   |
| Ralink                            | 27        | 1%      |
| TP-Link                           | 25        | 0.93%   |
| Marvell Technology Group          | 24        | 0.89%   |
| Nvidia                            | 23        | 0.85%   |
| Qualcomm Atheros Communications   | 18        | 0.67%   |
| ASUSTek Computer                  | 10        | 0.37%   |
| NetGear                           | 8         | 0.3%    |
| ASIX Electronics                  | 8         | 0.3%    |
| Dell                              | 7         | 0.26%   |
| D-Link                            | 7         | 0.26%   |
| Microsoft                         | 6         | 0.22%   |
| JMicron Technology                | 6         | 0.22%   |
| Sierra Wireless                   | 5         | 0.19%   |
| Samsung Electronics               | 5         | 0.19%   |
| Huawei Technologies               | 4         | 0.15%   |
| Ericsson Business Mobile Networks | 4         | 0.15%   |
| Aquantia                          | 4         | 0.15%   |
| Xiaomi                            | 3         | 0.11%   |
| T & A Mobile Phones               | 3         | 0.11%   |
| Linksys                           | 3         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.07%   |
| Sigma Sport                       | 2         | 0.07%   |
| Qualcomm                          | 2         | 0.07%   |
| OPPO Electronics                  | 2         | 0.07%   |
| Lenovo                            | 2         | 0.07%   |
| IMC Networks                      | 2         | 0.07%   |
| ICS Advent                        | 2         | 0.07%   |
| Gemtek                            | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| Attansic Technology               | 2         | 0.07%   |
| Arduino SA                        | 2         | 0.07%   |
| ZyDAS                             | 1         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 771       | 24.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 131       | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 70        | 2.22%   |
| Intel Wireless 7265                                               | 57        | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 55        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 48        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 46        | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 41        | 1.3%    |
| Intel Wi-Fi 6 AX200                                               | 40        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 39        | 1.24%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 39        | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 35        | 1.11%   |
| Intel Wireless 3165                                               | 34        | 1.08%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 32        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 30        | 0.95%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 0.79%   |
| Intel I211 Gigabit Network Connection                             | 24        | 0.76%   |
| Intel Wireless 8260                                               | 22        | 0.7%    |
| Intel Wireless 7260                                               | 22        | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 22        | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 21        | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 20        | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 20        | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 18        | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 18        | 0.57%   |
| Intel Ethernet Controller I225-V                                  | 18        | 0.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 17        | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                   | 17        | 0.54%   |
| Intel Wireless 3160                                               | 17        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 0.54%   |
| Intel 82579V Gigabit Network Connection                           | 17        | 0.54%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 16        | 0.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 597       | 42.64%  |
| Realtek Semiconductor           | 286       | 20.43%  |
| Qualcomm Atheros                | 248       | 17.71%  |
| Broadcom                        | 72        | 5.14%   |
| Ralink Technology               | 35        | 2.5%    |
| MediaTek                        | 34        | 2.43%   |
| Ralink                          | 27        | 1.93%   |
| Qualcomm Atheros Communications | 18        | 1.29%   |
| TP-Link                         | 16        | 1.14%   |
| ASUSTek Computer                | 9         | 0.64%   |
| Broadcom Limited                | 8         | 0.57%   |
| NetGear                         | 7         | 0.5%    |
| D-Link                          | 7         | 0.5%    |
| Sierra Wireless                 | 5         | 0.36%   |
| Microsoft                       | 5         | 0.36%   |
| Dell                            | 4         | 0.29%   |
| Marvell Technology Group        | 3         | 0.21%   |
| Linksys                         | 3         | 0.21%   |
| IMC Networks                    | 2         | 0.14%   |
| Gemtek                          | 2         | 0.14%   |
| D-Link System                   | 2         | 0.14%   |
| ZyDAS                           | 1         | 0.07%   |
| Wilocity                        | 1         | 0.07%   |
| VIA Technologies                | 1         | 0.07%   |
| Qualcomm                        | 1         | 0.07%   |
| PLANEX                          | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| BUFFALO                         | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |
| AVM                             | 1         | 0.07%   |
| Arduino SA                      | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 57        | 4.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 55        | 3.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 48        | 3.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 46        | 3.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 41        | 2.92%   |
| Intel Wi-Fi 6 AX200                                                     | 40        | 2.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 39        | 2.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 39        | 2.77%   |
| Intel Wireless 3165                                                     | 34        | 2.42%   |
| Intel Wi-Fi 6 AX201                                                     | 33        | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 32        | 2.28%   |
| Intel Wireless 8265 / 8275                                              | 32        | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 30        | 2.13%   |
| Intel Wireless 8260                                                     | 22        | 1.56%   |
| Intel Wireless 7260                                                     | 22        | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 22        | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 21        | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 20        | 1.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 20        | 1.42%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 18        | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 1.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 17        | 1.21%   |
| Qualcomm Atheros AR9271 802.11n                                         | 17        | 1.21%   |
| Intel Wireless 3160                                                     | 17        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 1.21%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 16        | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 15        | 1.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.07%   |
| Intel WiFi Link 5100                                                    | 15        | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 15        | 1.07%   |
| Intel Centrino Ultimate-N 6300                                          | 14        | 1%      |
| Ralink MT7601U Wireless Adapter                                         | 13        | 0.92%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 12        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.85%   |
| Realtek 802.11ac NIC                                                    | 12        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 12        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 981       | 57.6%   |
| Intel                            | 402       | 23.61%  |
| Qualcomm Atheros                 | 116       | 6.81%   |
| Broadcom                         | 75        | 4.4%    |
| Nvidia                           | 23        | 1.35%   |
| Marvell Technology Group         | 21        | 1.23%   |
| Broadcom Limited                 | 21        | 1.23%   |
| TP-Link                          | 9         | 0.53%   |
| ASIX Electronics                 | 8         | 0.47%   |
| JMicron Technology               | 6         | 0.35%   |
| Samsung Electronics              | 5         | 0.29%   |
| MediaTek                         | 4         | 0.23%   |
| Aquantia                         | 4         | 0.23%   |
| Xiaomi                           | 3         | 0.18%   |
| Huawei Technologies              | 3         | 0.18%   |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| OPPO Electronics                 | 2         | 0.12%   |
| Lenovo                           | 2         | 0.12%   |
| ICS Advent                       | 2         | 0.12%   |
| Attansic Technology              | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| T & A Mobile Phones              | 1         | 0.06%   |
| Qualcomm                         | 1         | 0.06%   |
| NetGear                          | 1         | 0.06%   |
| Motorola PCS                     | 1         | 0.06%   |
| Microsoft                        | 1         | 0.06%   |
| LG Electronics                   | 1         | 0.06%   |
| Insyde Software                  | 1         | 0.06%   |
| DisplayLink                      | 1         | 0.06%   |
| ASUSTek Computer                 | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |
| 3Com                             | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 771       | 44.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 131       | 7.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 70        | 4.05%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 2.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 35        | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 1.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.45%   |
| Intel I211 Gigabit Network Connection                             | 24        | 1.39%   |
| Intel Ethernet Controller I225-V                                  | 18        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 17        | 0.98%   |
| Intel 82567LM Gigabit Network Connection                          | 15        | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14        | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12        | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 12        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.64%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 0.58%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 8         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.46%   |
| Nvidia MCP61 Ethernet                                             | 8         | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.4%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 7         | 0.4%    |
| Intel I210 Gigabit Network Connection                             | 7         | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 7         | 0.4%    |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.4%    |
| Intel 82566MM Gigabit Network Connection                          | 7         | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7         | 0.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.4%    |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 6         | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                            | 5         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1655      | 54.77%  |
| WiFi     | 1349      | 44.64%  |
| Modem    | 14        | 0.46%   |
| Unknown  | 4         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 945       | 51.33%  |
| WiFi     | 895       | 48.61%  |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 965       | 51.66%  |
| 1     | 845       | 45.24%  |
| 0     | 27        | 1.45%   |
| 3     | 26        | 1.39%   |
| 4     | 4         | 0.21%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1259      | 67.4%   |
| Yes  | 609       | 32.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 450       | 43.77%  |
| Realtek Semiconductor           | 125       | 12.16%  |
| Qualcomm Atheros Communications | 79        | 7.68%   |
| Cambridge Silicon Radio         | 67        | 6.52%   |
| IMC Networks                    | 54        | 5.25%   |
| Broadcom                        | 54        | 5.25%   |
| Lite-On Technology              | 42        | 4.09%   |
| Foxconn / Hon Hai               | 26        | 2.53%   |
| Apple                           | 23        | 2.24%   |
| ASUSTek Computer                | 20        | 1.95%   |
| Toshiba                         | 18        | 1.75%   |
| Hewlett-Packard                 | 17        | 1.65%   |
| MediaTek                        | 12        | 1.17%   |
| Dell                            | 12        | 1.17%   |
| Realtek                         | 6         | 0.58%   |
| Ralink                          | 5         | 0.49%   |
| TP-Link                         | 3         | 0.29%   |
| Marvell Semiconductor           | 3         | 0.29%   |
| Chicony Electronics             | 2         | 0.19%   |
| Belkin Components               | 2         | 0.19%   |
| Qcom                            | 1         | 0.1%    |
| ISSC                            | 1         | 0.1%    |
| Integrated System Solution      | 1         | 0.1%    |
| Fujitsu                         | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| Unknown                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 189       | 18.37%  |
| Realtek Bluetooth Radio                             | 89        | 8.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 67        | 6.51%   |
| Intel AX201 Bluetooth                               | 62        | 6.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 58        | 5.64%   |
| Intel Bluetooth Device                              | 54        | 5.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 40        | 3.89%   |
| Intel AX200 Bluetooth                               | 37        | 3.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 27        | 2.62%   |
| Intel AX210 Bluetooth                               | 22        | 2.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 1.85%   |
| IMC Networks Bluetooth Radio                        | 16        | 1.55%   |
| IMC Networks Bluetooth Device                       | 16        | 1.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 14        | 1.36%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 1.26%   |
| Apple Bluetooth Host Controller                     | 13        | 1.26%   |
| MediaTek Wireless_Device                            | 12        | 1.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.17%   |
| IMC Networks Wireless_Device                        | 11        | 1.07%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 0.87%   |
| ASUS ASUS USB-BT500                                 | 9         | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 0.78%   |
| Lite-On Bluetooth Device                            | 7         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.68%   |
| Toshiba Bluetooth Device                            | 5         | 0.49%   |
| Realtek 802.11ac WLAN Adapter                       | 5         | 0.49%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.39%   |
| Lite-On Wireless_Device                             | 4         | 0.39%   |
| IMC Networks Bluetooth                              | 4         | 0.39%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.39%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 4         | 0.39%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1364      | 55%     |
| AMD                                          | 549       | 22.14%  |
| Nvidia                                       | 378       | 15.24%  |
| C-Media Electronics                          | 33        | 1.33%   |
| Creative Labs                                | 24        | 0.97%   |
| Generalplus Technology                       | 17        | 0.69%   |
| Logitech                                     | 9         | 0.36%   |
| Texas Instruments                            | 8         | 0.32%   |
| Creative Technology                          | 7         | 0.28%   |
| Micro Star International                     | 5         | 0.2%    |
| JMTek                                        | 5         | 0.2%    |
| Tenx Technology                              | 4         | 0.16%   |
| VIA Technologies                             | 3         | 0.12%   |
| SteelSeries ApS                              | 3         | 0.12%   |
| KTMicro                                      | 3         | 0.12%   |
| Hewlett-Packard                              | 3         | 0.12%   |
| GN Netcom                                    | 3         | 0.12%   |
| FiiO Electronics Technology                  | 3         | 0.12%   |
| ASUSTek Computer                             | 3         | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.08%   |
| Schiit Audio                                 | 2         | 0.08%   |
| Samson Technologies                          | 2         | 0.08%   |
| ROCCAT                                       | 2         | 0.08%   |
| Razer USA                                    | 2         | 0.08%   |
| PreSonus Audio Electronics                   | 2         | 0.08%   |
| No brand                                     | 2         | 0.08%   |
| Native Instruments                           | 2         | 0.08%   |
| Kingston Technology                          | 2         | 0.08%   |
| Focusrite-Novation                           | 2         | 0.08%   |
| Dell                                         | 2         | 0.08%   |
| Corsair                                      | 2         | 0.08%   |
| Yamaha                                       | 1         | 0.04%   |
| XMOS                                         | 1         | 0.04%   |
| Xilinx                                       | 1         | 0.04%   |
| USB-Speaker                                  | 1         | 0.04%   |
| THX                                          | 1         | 0.04%   |
| Tdlasunnic                                   | 1         | 0.04%   |
| Sterling                                     | 1         | 0.04%   |
| Sennheiser Communications                    | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 184       | 6.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 144       | 4.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 141       | 4.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 128       | 4.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 101       | 3.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 92        | 3.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 77        | 2.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 76        | 2.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 72        | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 72        | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 71        | 2.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 66        | 2.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 60        | 2.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 60        | 2.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 57        | 1.92%   |
| Intel 200 Series PCH HD Audio                                                                     | 50        | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 46        | 1.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 45        | 1.51%   |
| Intel Cannon Lake PCH cAVS                                                                        | 43        | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 42        | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 41        | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 38        | 1.28%   |
| Intel Broadwell-U Audio Controller                                                                | 37        | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 32        | 1.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 32        | 1.08%   |
| Intel 8 Series HD Audio Controller                                                                | 32        | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 30        | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 28        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 27        | 0.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 27        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 26        | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 0.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 25        | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 24        | 0.81%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 22        | 0.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 22        | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 21        | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 21        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 432       | 19.3%   |
| SK hynix                                         | 357       | 15.95%  |
| Kingston                                         | 292       | 13.05%  |
| Unknown                                          | 236       | 10.55%  |
| Micron Technology                                | 204       | 9.12%   |
| Crucial                                          | 121       | 5.41%   |
| Corsair                                          | 89        | 3.98%   |
| G.Skill                                          | 58        | 2.59%   |
| Ramaxel Technology                               | 49        | 2.19%   |
| A-DATA Technology                                | 47        | 2.1%    |
| Nanya Technology                                 | 44        | 1.97%   |
| Elpida                                           | 37        | 1.65%   |
| Unknown (ABCD)                                   | 36        | 1.61%   |
| Unknown                                          | 32        | 1.43%   |
| Team                                             | 25        | 1.12%   |
| Patriot                                          | 13        | 0.58%   |
| Transcend                                        | 12        | 0.54%   |
| Smart                                            | 11        | 0.49%   |
| GOODRAM                                          | 9         | 0.4%    |
| Multilaser                                       | 8         | 0.36%   |
| Apacer                                           | 8         | 0.36%   |
| Qimonda                                          | 6         | 0.27%   |
| Avant                                            | 6         | 0.27%   |
| AMD                                              | 6         | 0.27%   |
| Unifosa                                          | 4         | 0.18%   |
| Teikon                                           | 4         | 0.18%   |
| Silicon Power                                    | 4         | 0.18%   |
| Innodisk                                         | 4         | 0.18%   |
| Hikvision                                        | 4         | 0.18%   |
| Wilk                                             | 3         | 0.13%   |
| Toshiba                                          | 3         | 0.13%   |
| Timetec                                          | 3         | 0.13%   |
| Kllisre                                          | 3         | 0.13%   |
| GeIL                                             | 3         | 0.13%   |
| ASint Technology                                 | 3         | 0.13%   |
| Walton Chaintech                                 | 2         | 0.09%   |
| Unknown (0x48594D503132355336344350382D53362020) | 2         | 0.09%   |
| Sesame                                           | 2         | 0.09%   |
| PUSKILL                                          | 2         | 0.09%   |
| Patriot Memory (PDP Systems)                     | 2         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 32        | 1.32%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 26        | 1.07%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 20        | 0.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 19        | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.7%    |
| Unknown RAM Module 2GB DIMM SDRAM                                | 16        | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 0.62%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 14        | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.49%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 12        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 11        | 0.45%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 11        | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 10        | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 10        | 0.41%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 10        | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 10        | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 9         | 0.37%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 9         | 0.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 9         | 0.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 9         | 0.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.37%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 9         | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 9         | 0.37%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 9         | 0.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 0.37%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 8         | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 8         | 0.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 0.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 748       | 39.37%  |
| DDR3    | 725       | 38.16%  |
| DDR2    | 142       | 7.47%   |
| SDRAM   | 104       | 5.47%   |
| LPDDR4  | 68        | 3.58%   |
| Unknown | 62        | 3.26%   |
| DDR5    | 12        | 0.63%   |
| LPDDR3  | 11        | 0.58%   |
| LPDDR5  | 10        | 0.53%   |
| DDR     | 10        | 0.53%   |
| DRAM    | 8         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 993       | 53.16%  |
| DIMM         | 783       | 41.92%  |
| Row Of Chips | 77        | 4.12%   |
| Unknown      | 8         | 0.43%   |
| RIMM         | 4         | 0.21%   |
| Chip         | 3         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 726       | 34.29%  |
| 4096  | 688       | 32.5%   |
| 2048  | 363       | 17.15%  |
| 16384 | 178       | 8.41%   |
| 1024  | 90        | 4.25%   |
| 32768 | 61        | 2.88%   |
| 512   | 9         | 0.43%   |
| 256   | 1         | 0.05%   |
| 64    | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 458       | 21.74%  |
| 3200    | 260       | 12.34%  |
| 2667    | 219       | 10.39%  |
| 1333    | 186       | 8.83%   |
| 2400    | 167       | 7.93%   |
| 1334    | 87        | 4.13%   |
| 667     | 83        | 3.94%   |
| 2133    | 81        | 3.84%   |
| 800     | 69        | 3.27%   |
| Unknown | 56        | 2.66%   |
| 3600    | 51        | 2.42%   |
| 1867    | 32        | 1.52%   |
| 1067    | 26        | 1.23%   |
| 4199    | 22        | 1.04%   |
| 3266    | 22        | 1.04%   |
| 2933    | 22        | 1.04%   |
| 2048    | 21        | 1%      |
| 1066    | 20        | 0.95%   |
| 1866    | 19        | 0.9%    |
| 3000    | 15        | 0.71%   |
| 4267    | 14        | 0.66%   |
| 1800    | 14        | 0.66%   |
| 533     | 13        | 0.62%   |
| 2666    | 12        | 0.57%   |
| 6400    | 10        | 0.47%   |
| 3733    | 9         | 0.43%   |
| 4800    | 7         | 0.33%   |
| 3800    | 7         | 0.33%   |
| 3666    | 6         | 0.28%   |
| 3400    | 6         | 0.28%   |
| 4266    | 5         | 0.24%   |
| 3533    | 5         | 0.24%   |
| 3466    | 5         | 0.24%   |
| 975     | 5         | 0.24%   |
| 2800    | 4         | 0.19%   |
| 400     | 4         | 0.19%   |
| 49926   | 3         | 0.14%   |
| 6000    | 3         | 0.14%   |
| 3866    | 3         | 0.14%   |
| 3534    | 3         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 33.85%  |
| Brother Industries  | 15        | 23.08%  |
| Canon               | 13        | 20%     |
| Seiko Epson         | 7         | 10.77%  |
| Samsung Electronics | 5         | 7.69%   |
| Xerox               | 1         | 1.54%   |
| Prolific Technology | 1         | 1.54%   |
| Philips (or NXP)    | 1         | 1.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| HP DeskJet 2600 series              | 3         | 4.55%   |
| Brother HL-L2390DW                  | 3         | 4.55%   |
| HP OfficeJet 3830 series            | 2         | 3.03%   |
| HP Laser 107w                       | 2         | 3.03%   |
| Canon TS5300 series                 | 2         | 3.03%   |
| Canon CanoScan LiDE 300             | 2         | 3.03%   |
| Xerox WorkCentre 6025               | 1         | 1.52%   |
| Seiko Epson XP-7100 Series          | 1         | 1.52%   |
| Seiko Epson Printer                 | 1         | 1.52%   |
| Seiko Epson L6160 Series            | 1         | 1.52%   |
| Seiko Epson L365 Series             | 1         | 1.52%   |
| Seiko Epson L3110 Series            | 1         | 1.52%   |
| Seiko Epson L120 Series             | 1         | 1.52%   |
| Seiko Epson ET-2710 Series          | 1         | 1.52%   |
| Samsung SCX-3200 Series             | 1         | 1.52%   |
| Samsung ML-2010P Mono Laser Printer | 1         | 1.52%   |
| Samsung ML-1710 Printer             | 1         | 1.52%   |
| Samsung M267x 287x Series           | 1         | 1.52%   |
| Samsung M2070 Series                | 1         | 1.52%   |
| Prolific PL2305 Parallel Port       | 1         | 1.52%   |
| Philips (or NXP) USB Printer        | 1         | 1.52%   |
| HP OfficeJet 6950                   | 1         | 1.52%   |
| HP Officejet 4500 G510g-m           | 1         | 1.52%   |
| HP LaserJet P1005                   | 1         | 1.52%   |
| HP LaserJet M101-M106               | 1         | 1.52%   |
| HP ENVY 5000 series                 | 1         | 1.52%   |
| HP Deskjet F4500 series             | 1         | 1.52%   |
| HP DeskJet F4200 series             | 1         | 1.52%   |
| HP DeskJet 959c                     | 1         | 1.52%   |
| HP DeskJet 6122                     | 1         | 1.52%   |
| HP DeskJet 5650c                    | 1         | 1.52%   |
| HP DeskJet 3700 series              | 1         | 1.52%   |
| HP Deskjet 3540 series              | 1         | 1.52%   |
| HP Deskjet 2050 J510                | 1         | 1.52%   |
| HP DeskJet 1110 series              | 1         | 1.52%   |
| HP coredump                         | 1         | 1.52%   |
| Canon TS700 series                  | 1         | 1.52%   |
| Canon TS5100 series                 | 1         | 1.52%   |
| Canon TR7500 series                 | 1         | 1.52%   |
| Canon PIXMA MG3600 Series           | 1         | 1.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 5         | 62.5%   |
| KYE Systems (Mouse Systems) | 1         | 12.5%   |
| Hewlett-Packard             | 1         | 12.5%   |
| Acer Peripherals (now BenQ) | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE | 1         | 12.5%   |
| HP ScanJet 3670                                     | 1         | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20                  | 1         | 12.5%   |
| Canon CanoScan LiDE 90                              | 1         | 12.5%   |
| Canon CanoScan LIDE 25                              | 1         | 12.5%   |
| Canon CanoScan LiDE 210                             | 1         | 12.5%   |
| Canon CanoScan 1220U                                | 1         | 12.5%   |
| Acer Peripherals (now BenQ) Prisa 1240UT            | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 244       | 25.77%  |
| Realtek Semiconductor                  | 81        | 8.55%   |
| IMC Networks                           | 78        | 8.24%   |
| Microdia                               | 67        | 7.07%   |
| Sunplus Innovation Technology          | 52        | 5.49%   |
| Bison Electronics                      | 48        | 5.07%   |
| Suyin                                  | 40        | 4.22%   |
| Quanta                                 | 37        | 3.91%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 3.8%    |
| Logitech                               | 35        | 3.7%    |
| Syntek                                 | 32        | 3.38%   |
| Apple                                  | 22        | 2.32%   |
| Lite-On Technology                     | 17        | 1.8%    |
| Silicon Motion                         | 16        | 1.69%   |
| Alcor Micro                            | 12        | 1.27%   |
| Luxvisions Innotech Limited            | 11        | 1.16%   |
| Ricoh                                  | 9         | 0.95%   |
| Acer                                   | 9         | 0.95%   |
| Sonix Technology                       | 6         | 0.63%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.63%   |
| Primax Electronics                     | 6         | 0.63%   |
| Lenovo                                 | 6         | 0.63%   |
| Importek                               | 6         | 0.63%   |
| Generalplus Technology                 | 6         | 0.63%   |
| ALi                                    | 5         | 0.53%   |
| Z-Star Microelectronics                | 4         | 0.42%   |
| Samsung Electronics                    | 4         | 0.42%   |
| OmniVision Technologies                | 4         | 0.42%   |
| Microsoft                              | 4         | 0.42%   |
| icSpring                               | 4         | 0.42%   |
| HRY                                    | 3         | 0.32%   |
| Hewlett-Packard                        | 3         | 0.32%   |
| ARC International                      | 3         | 0.32%   |
| Y Media                                | 2         | 0.21%   |
| WaveRider Communications               | 2         | 0.21%   |
| Unknown                                | 2         | 0.21%   |
| Sunplus Technology                     | 2         | 0.21%   |
| Intel                                  | 2         | 0.21%   |
| Genesys Logic                          | 2         | 0.21%   |
| Creative Technology                    | 2         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 34        | 3.57%   |
| Chicony HD WebCam                                | 23        | 2.42%   |
| Microdia Integrated_Webcam_HD                    | 21        | 2.21%   |
| IMC Networks Integrated Camera                   | 20        | 2.1%    |
| Syntek Integrated Camera                         | 19        | 2%      |
| Realtek Integrated_Webcam_HD                     | 16        | 1.68%   |
| IMC Networks USB2.0 HD UVC WebCam                | 16        | 1.68%   |
| Realtek USB Camera                               | 15        | 1.58%   |
| Bison Integrated Camera                          | 15        | 1.58%   |
| Sunplus Integrated_Webcam_HD                     | 13        | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 13        | 1.37%   |
| Logitech Webcam C270                             | 12        | 1.26%   |
| Chicony FJ Camera                                | 12        | 1.26%   |
| Microdia Integrated Webcam                       | 10        | 1.05%   |
| Chicony USB2.0 Camera                            | 10        | 1.05%   |
| Chicony Lenovo EasyCamera                        | 9         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 9         | 0.95%   |
| Chicony HP Truevision HD                         | 8         | 0.84%   |
| Apple FaceTime HD Camera (Built-in)              | 8         | 0.84%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 7         | 0.74%   |
| Microdia Webcam Vitade AF                        | 7         | 0.74%   |
| Chicony VGA Webcam                               | 7         | 0.74%   |
| Chicony HP TrueVision HD Camera                  | 7         | 0.74%   |
| Chicony HD User Facing                           | 7         | 0.74%   |
| Chicony EasyCamera                               | 7         | 0.74%   |
| Bison HD Webcam                                  | 7         | 0.74%   |
| Syntek EasyCamera                                | 6         | 0.63%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera  | 6         | 0.63%   |
| Quanta VGA WebCam                                | 6         | 0.63%   |
| Quanta HP TrueVision HD Camera                   | 6         | 0.63%   |
| Chicony TOSHIBA Web Camera - HD                  | 6         | 0.63%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 6         | 0.63%   |
| Chicony HP Wide Vision HD Camera                 | 6         | 0.63%   |
| Apple FaceTime HD Camera                         | 6         | 0.63%   |
| Syntek Lenovo EasyCamera                         | 5         | 0.53%   |
| Sunplus HD WebCam                                | 5         | 0.53%   |
| Sunplus 1080p FHD Camera                         | 5         | 0.53%   |
| Sonix USB2.0 HD UVC WebCam                       | 5         | 0.53%   |
| Realtek Integrated Webcam HD                     | 5         | 0.53%   |
| Realtek Integrated Webcam                        | 5         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 43        | 29.05%  |
| Synaptics                  | 24        | 16.22%  |
| AuthenTec                  | 23        | 15.54%  |
| Upek                       | 13        | 8.78%   |
| Shenzhen Goodix Technology | 12        | 8.11%   |
| Elan Microelectronics      | 12        | 8.11%   |
| LighTuning Technology      | 9         | 6.08%   |
| STMicroelectronics         | 4         | 2.7%    |
| Samsung Electronics        | 4         | 2.7%    |
| Focal-systems.Corp         | 4         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 8.11%   |
| AuthenTec AES2810                                                          | 10        | 6.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 6.08%   |
| Validity Sensors VFS491                                                    | 8         | 5.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 4.73%   |
| Shenzhen Goodix  Fingerprint Device                                        | 7         | 4.73%   |
| Elan ELAN:ARM-M4                                                           | 7         | 4.73%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 4.05%   |
| Elan ELAN:Fingerprint                                                      | 5         | 3.38%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 2.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 2.7%    |
| Synaptics UWP WBDI Device                                                  | 4         | 2.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.7%    |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.7%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 2.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 2.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 2.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.03%   |
| Synaptics  WBDI                                                            | 3         | 2.03%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.35%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.35%   |
| Synaptics WBDI                                                             | 2         | 1.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.35%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.35%   |
| LighTuning Fingerprint Sensor                                              | 2         | 1.35%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.35%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.35%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1.35%   |
| AuthenTec AES1600                                                          | 2         | 1.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.68%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.68%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.68%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.68%   |
| Synaptics UWP WBDI                                                         | 1         | 0.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 31        | 46.27%  |
| O2 Micro              | 13        | 19.4%   |
| Alcor Micro           | 10        | 14.93%  |
| Upek                  | 4         | 5.97%   |
| Lenovo                | 4         | 5.97%   |
| SCM Microsystems      | 1         | 1.49%   |
| Realtek Semiconductor | 1         | 1.49%   |
| Gemalto (was Gemplus) | 1         | 1.49%   |
| Castles Technology    | 1         | 1.49%   |
| Advanced Card Systems | 1         | 1.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 13        | 19.4%   |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 16.42%  |
| Broadcom 5880                                                                | 11        | 16.42%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 14.93%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 11.94%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.97%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5.97%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 1.49%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.49%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.49%   |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 1.49%   |
| Broadcom 58200                                                               | 1         | 1.49%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1504      | 80.51%  |
| 1     | 322       | 17.24%  |
| 2     | 38        | 2.03%   |
| 3     | 4         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 148       | 37.19%  |
| Graphics card            | 115       | 28.89%  |
| Chipcard                 | 66        | 16.58%  |
| Net/wireless             | 14        | 3.52%   |
| Unassigned class         | 13        | 3.27%   |
| Communication controller | 10        | 2.51%   |
| Storage                  | 9         | 2.26%   |
| Multimedia controller    | 8         | 2.01%   |
| Camera                   | 8         | 2.01%   |
| Bluetooth                | 5         | 1.26%   |
| Net/ethernet             | 1         | 0.25%   |
| Flash memory             | 1         | 0.25%   |

