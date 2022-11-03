Elementary 6.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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

Total: 500

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T495 20NKS01W02    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Laptop 17-ca3xxx            | [2c42913712](https://linux-hardware.org/?probe=2c42913712) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| Toshiba       | TECRA A11                   | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [9b90ea1d4d](https://linux-hardware.org/?probe=9b90ea1d4d) | Oct 27, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| HP            | Laptop 15-bw0xx             | [cdd4d21000](https://linux-hardware.org/?probe=cdd4d21000) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| Apple         | MacBookPro10,1              | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [484cb84d6b](https://linux-hardware.org/?probe=484cb84d6b) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2dd84a41e8](https://linux-hardware.org/?probe=2dd84a41e8) | Oct 17, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [c5b6ba786e](https://linux-hardware.org/?probe=c5b6ba786e) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Dell          | Inspiron 15-3567            | [2b00bd7a92](https://linux-hardware.org/?probe=2b00bd7a92) | Oct 15, 2022 |
| HP            | Pavilion dv7                | [44ae8ac465](https://linux-hardware.org/?probe=44ae8ac465) | Oct 14, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [8926251d64](https://linux-hardware.org/?probe=8926251d64) | Oct 11, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [db3419c5de](https://linux-hardware.org/?probe=db3419c5de) | Oct 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f06f54475b](https://linux-hardware.org/?probe=f06f54475b) | Oct 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [20ea012e04](https://linux-hardware.org/?probe=20ea012e04) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| Lenovo        | V130-15IKB 81HN             | [823a068620](https://linux-hardware.org/?probe=823a068620) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c086a688f1](https://linux-hardware.org/?probe=c086a688f1) | Oct 02, 2022 |
| HUAWEI        | HVY-WXX9                    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Google        | Blooglet                    | [44a9c6559f](https://linux-hardware.org/?probe=44a9c6559f) | Sep 29, 2022 |
| Medion        | Akoya E6422 MD99680         | [52c1708200](https://linux-hardware.org/?probe=52c1708200) | Sep 28, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [18ee2cafd6](https://linux-hardware.org/?probe=18ee2cafd6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [ffc2811bfe](https://linux-hardware.org/?probe=ffc2811bfe) | Sep 27, 2022 |
| Dell          | Latitude E6540              | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Dell          | Latitude E5450              | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| Apple         | MacBookAir6,2               | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Dell          | Inspiron 3493               | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6a0c80f635](https://linux-hardware.org/?probe=6a0c80f635) | Sep 22, 2022 |
| Acer          | Nitro AN515-54              | [7cf2d6a810](https://linux-hardware.org/?probe=7cf2d6a810) | Sep 20, 2022 |
| ASUSTek       | X555LAB                     | [71339e0cfb](https://linux-hardware.org/?probe=71339e0cfb) | Sep 19, 2022 |
| ASUSTek       | X555LAB                     | [a0acb674df](https://linux-hardware.org/?probe=a0acb674df) | Sep 19, 2022 |
| HP            | Laptop 15-bw0xx             | [94baca564e](https://linux-hardware.org/?probe=94baca564e) | Sep 19, 2022 |
| ASUSTek       | X555DG                      | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Clevo         | W54xEU                      | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7861fa17bf](https://linux-hardware.org/?probe=7861fa17bf) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| Dell          | Inspiron 5458               | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | [6b1829aad1](https://linux-hardware.org/?probe=6b1829aad1) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | [9ef29f2258](https://linux-hardware.org/?probe=9ef29f2258) | Sep 12, 2022 |
| HP            | ENVY m6                     | [b9de3b6e35](https://linux-hardware.org/?probe=b9de3b6e35) | Sep 11, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Apple         | MacBookPro11,2              | [47708e7772](https://linux-hardware.org/?probe=47708e7772) | Sep 09, 2022 |
| Apple         | MacBookPro11,4              | [c5d5b88740](https://linux-hardware.org/?probe=c5d5b88740) | Sep 09, 2022 |
| ASUSTek       | GL702VSK                    | [5001a76a0e](https://linux-hardware.org/?probe=5001a76a0e) | Sep 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [3932661b8e](https://linux-hardware.org/?probe=3932661b8e) | Sep 07, 2022 |
| Acer          | Aspire V5-552               | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| Apple         | MacBookPro8,2               | [b37d844ab3](https://linux-hardware.org/?probe=b37d844ab3) | Sep 04, 2022 |
| TUXEDO        | Book XP14 Gen12             | [cfb0fb9451](https://linux-hardware.org/?probe=cfb0fb9451) | Sep 04, 2022 |
| Timi          | TM1701                      | [f23c551375](https://linux-hardware.org/?probe=f23c551375) | Sep 03, 2022 |
| Notebook      | NLx0MU                      | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| Apple         | MacBookPro5,2               | [7f66ca2cc7](https://linux-hardware.org/?probe=7f66ca2cc7) | Aug 29, 2022 |
| Standard      | Unknown                     | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| HP            | Laptop 15-db0xxx            | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| ASUSTek       | X542UA                      | [0bf776cdc1](https://linux-hardware.org/?probe=0bf776cdc1) | Aug 28, 2022 |
| HP            | 240 G7 Notebook PC          | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Complet       | MY8312                      | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Dell          | Inspiron 5537               | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Dell          | Latitude E7250              | [98f4886ef7](https://linux-hardware.org/?probe=98f4886ef7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Apple         | MacBookAir7,1               | [079a951d65](https://linux-hardware.org/?probe=079a951d65) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| ASUSTek       | K52F                        | [cafd25a659](https://linux-hardware.org/?probe=cafd25a659) | Aug 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [08d6e2e6e8](https://linux-hardware.org/?probe=08d6e2e6e8) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| HP            | 240 G7 Notebook PC          | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| Acer          | Aspire V5-552G              | [f51f3093d9](https://linux-hardware.org/?probe=f51f3093d9) | Aug 12, 2022 |
| ASUSTek       | K43E                        | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Dell          | Latitude D630               | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| HP            | Pavilion 17                 | [f06bb8d9ab](https://linux-hardware.org/?probe=f06bb8d9ab) | Aug 07, 2022 |
| HP            | Pavilion 17                 | [9c47c2e4f4](https://linux-hardware.org/?probe=9c47c2e4f4) | Aug 07, 2022 |
| TrekStor      | Notebook Slim S130          | [ba73d094e7](https://linux-hardware.org/?probe=ba73d094e7) | Aug 06, 2022 |
| Sony          | SVS15117FLB                 | [2729210175](https://linux-hardware.org/?probe=2729210175) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| MSI           | Creator 15 A10SET           | [45d9d06fb8](https://linux-hardware.org/?probe=45d9d06fb8) | Aug 05, 2022 |
| Medion        | Akoya E6422 MD99680         | [86cd2f6a0a](https://linux-hardware.org/?probe=86cd2f6a0a) | Aug 05, 2022 |
| Sony          | SVS15117FLB                 | [1f64d30f2f](https://linux-hardware.org/?probe=1f64d30f2f) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [7a0956e5f8](https://linux-hardware.org/?probe=7a0956e5f8) | Aug 04, 2022 |
| ASUSTek       | K43E                        | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| Dell          | Latitude E6400              | [54db9ae43d](https://linux-hardware.org/?probe=54db9ae43d) | Aug 04, 2022 |
| HP            | Pavilion dv6                | [b921b586f6](https://linux-hardware.org/?probe=b921b586f6) | Aug 02, 2022 |
| HP            | 431                         | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Dell          | Latitude E6320              | [34270898c6](https://linux-hardware.org/?probe=34270898c6) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [04487d99ff](https://linux-hardware.org/?probe=04487d99ff) | Jul 30, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| Dell          | Latitude D630               | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | Latitude E6320              | [a5b77aa0e9](https://linux-hardware.org/?probe=a5b77aa0e9) | Jul 28, 2022 |
| Dell          | Latitude 3190               | [36027c80d2](https://linux-hardware.org/?probe=36027c80d2) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [d9a5e0b7e6](https://linux-hardware.org/?probe=d9a5e0b7e6) | Jul 27, 2022 |
| HP            | Pavilion g4                 | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| HP            | 255 G7 Notebook PC          | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f4026901c2](https://linux-hardware.org/?probe=f4026901c2) | Jul 25, 2022 |
| HP            | Pavilion g6                 | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| HP            | EliteBook 8460p             | [b1c5cb2096](https://linux-hardware.org/?probe=b1c5cb2096) | Jul 12, 2022 |
| HP            | Notebook                    | [afaaed48c7](https://linux-hardware.org/?probe=afaaed48c7) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Acer          | Aspire AV15-51              | [1a880a89af](https://linux-hardware.org/?probe=1a880a89af) | Jul 09, 2022 |
| Acer          | Aspire V3-771               | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| HP            | Notebook                    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| HP            | Laptop 15-dy1xxx            | [3fcdd6c039](https://linux-hardware.org/?probe=3fcdd6c039) | Jul 03, 2022 |
| Dell          | XPS 15 9500                 | [7df8533350](https://linux-hardware.org/?probe=7df8533350) | Jul 03, 2022 |
| ASUSTek       | N56VB                       | [88d34c06f3](https://linux-hardware.org/?probe=88d34c06f3) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| ASUSTek       | X553MA                      | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| Apple         | MacBookPro14,2              | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| ASUSTek       | UX303LAB                    | [ae3becae01](https://linux-hardware.org/?probe=ae3becae01) | Jun 24, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Alienware     | m17 R3                      | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| Dell          | Latitude E5510              | [1f6cc92f98](https://linux-hardware.org/?probe=1f6cc92f98) | Jun 18, 2022 |
| HP            | EliteBook 2170p             | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| HP            | ProBook 455R G6             | [31b94c71c7](https://linux-hardware.org/?probe=31b94c71c7) | Jun 16, 2022 |
| HP            | ProBook 455R G6             | [39d04d1188](https://linux-hardware.org/?probe=39d04d1188) | Jun 16, 2022 |
| Samsung       | Lumpy                       | [50dad22fb3](https://linux-hardware.org/?probe=50dad22fb3) | Jun 15, 2022 |
| ASUSTek       | GR8                         | [3cdc341eda](https://linux-hardware.org/?probe=3cdc341eda) | Jun 15, 2022 |
| Samsung       | Lumpy                       | [4137bf9757](https://linux-hardware.org/?probe=4137bf9757) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Apple         | MacBook4,1                  | [83cac56441](https://linux-hardware.org/?probe=83cac56441) | Jun 13, 2022 |
| HP            | ProBook 4540s               | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| Acer          | Aspire A315-21              | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [0ec841e188](https://linux-hardware.org/?probe=0ec841e188) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5768dfe23f](https://linux-hardware.org/?probe=5768dfe23f) | Jun 11, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c76f63fb68](https://linux-hardware.org/?probe=c76f63fb68) | Jun 10, 2022 |
| HP            | ProBook 4540s               | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| HP            | Notebook                    | [f07183fab5](https://linux-hardware.org/?probe=f07183fab5) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| HP            | ProBook 4540s               | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| Apple         | MacBookAir7,2               | [9de74ba486](https://linux-hardware.org/?probe=9de74ba486) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | [eb704f99ee](https://linux-hardware.org/?probe=eb704f99ee) | Jun 04, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| HP            | ProBook 4540s               | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| Samsung       | 300E5M/300E5L               | [baa12d722c](https://linux-hardware.org/?probe=baa12d722c) | Jun 01, 2022 |
| Dell          | XPS 13 9343                 | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| ASUSTek       | X550CA                      | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| Acer          | Swift SF114-32              | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| Apple         | MacBook4,1                  | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| AMI           | Intel                       | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| Sony          | VPCEB23FM                   | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| ASUSTek       | K55A                        | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| Apple         | MacBookPro8,2               | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| eMachines     | E525                        | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| HP            | EliteBook 840 G1            | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| HP            | ProBook 440 G7              | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Acer          | Aspire E5-575G              | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| HP            | Notebook                    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Dell          | Inspiron MM061              | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| Sony          | SVP1321B4E                  | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | MacBookAir7,1               | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| Acer          | Nitro AN517-52              | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| Packard Be... | EasyNote LS11HR             | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | X540SA                      | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| Dell          | Precision 7720              | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Google        | Lulu                        | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Sony          | SVE15115EN                  | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| Apple         | MacBookAir4,2               | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| Timi          | TM1613                      | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Apple         | MacBookPro6,2               | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Dell          | Inspiron 15-3567            | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| ASUSTek       | X555LN                      | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| Lenovo        | G550 20023                  | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| HP            | ProBook 4540s               | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Apple         | MacBookPro8,2               | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| Dell          | Latitude E5400              | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Star Labs     | StarBook                    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| MSI           | GF63 Thin 9SCSR             | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| Wortmann      | 1220729_1470271             | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Latitude 3580               | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.11.0-43-generic          | 78        | 19.55%  |
| 5.13.0-28-generic          | 32        | 8.02%   |
| 5.15.0-46-generic          | 29        | 7.27%   |
| 5.13.0-30-generic          | 27        | 6.77%   |
| 5.13.0-27-generic          | 24        | 6.02%   |
| 5.15.0-41-generic          | 20        | 5.01%   |
| 5.15.0-48-generic          | 18        | 4.51%   |
| 5.13.0-40-generic          | 16        | 4.01%   |
| 5.13.0-39-generic          | 16        | 4.01%   |
| 5.11.0-44-generic          | 14        | 3.51%   |
| 5.13.0-35-generic          | 13        | 3.26%   |
| 5.15.0-43-generic          | 12        | 3.01%   |
| 5.13.0-37-generic          | 12        | 3.01%   |
| 5.13.0-52-generic          | 10        | 2.51%   |
| 5.13.0-41-generic          | 10        | 2.51%   |
| 5.11.0-46-generic          | 10        | 2.51%   |
| 5.13.0-51-generic          | 8         | 2.01%   |
| 5.13.0-44-generic          | 7         | 1.75%   |
| 5.15.0-50-generic          | 6         | 1.5%    |
| 5.13.0-48-generic          | 6         | 1.5%    |
| 5.11.0-41-generic          | 4         | 1%      |
| 5.15.0-52-generic          | 3         | 0.75%   |
| 5.13.0-25-generic          | 2         | 0.5%    |
| 5.11.0-40-generic          | 2         | 0.5%    |
| 6.0.0-060000rc7-generic    | 1         | 0.25%   |
| 5.8.0-50-generic           | 1         | 0.25%   |
| 5.4.0-122-generic          | 1         | 0.25%   |
| 5.19.3-051903-generic      | 1         | 0.25%   |
| 5.19.12-051912-generic     | 1         | 0.25%   |
| 5.19.11-xanmod1            | 1         | 0.25%   |
| 5.19.0-8.2-liquorix-amd64  | 1         | 0.25%   |
| 5.18.3-051803-generic      | 1         | 0.25%   |
| 5.16.16-051616-generic     | 1         | 0.25%   |
| 5.16.10-051610-generic     | 1         | 0.25%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.25%   |
| 5.15.36-xanmod1            | 1         | 0.25%   |
| 5.15.3-xanmod1             | 1         | 0.25%   |
| 5.15.21-051521-generic     | 1         | 0.25%   |
| 5.15.13-xanmod1            | 1         | 0.25%   |
| 5.15.12-xanmod1-tt         | 1         | 0.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 173       | 44.94%  |
| 5.11.0  | 108       | 28.05%  |
| 5.15.0  | 84        | 21.82%  |
| 5.14.0  | 2         | 0.52%   |
| 6.0.0   | 1         | 0.26%   |
| 5.8.0   | 1         | 0.26%   |
| 5.4.0   | 1         | 0.26%   |
| 5.19.3  | 1         | 0.26%   |
| 5.19.12 | 1         | 0.26%   |
| 5.19.11 | 1         | 0.26%   |
| 5.19.0  | 1         | 0.26%   |
| 5.18.3  | 1         | 0.26%   |
| 5.16.16 | 1         | 0.26%   |
| 5.16.10 | 1         | 0.26%   |
| 5.16.0  | 1         | 0.26%   |
| 5.15.36 | 1         | 0.26%   |
| 5.15.3  | 1         | 0.26%   |
| 5.15.21 | 1         | 0.26%   |
| 5.15.13 | 1         | 0.26%   |
| 5.15.12 | 1         | 0.26%   |
| 5.15.11 | 1         | 0.26%   |
| 5.14.10 | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 173       | 45.05%  |
| 5.11    | 108       | 28.13%  |
| 5.15    | 90        | 23.44%  |
| 5.19    | 4         | 1.04%   |
| 5.14    | 3         | 0.78%   |
| 5.16    | 2         | 0.52%   |
| 6.0     | 1         | 0.26%   |
| 5.8     | 1         | 0.26%   |
| 5.4     | 1         | 0.26%   |
| 5.18    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 374       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 373       | 99.73%  |
| Unknown  | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 374       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 301       | 80.27%  |
| LightDM | 73        | 19.47%  |
| GDM     | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 173       | 46.13%  |
| de_DE   | 44        | 11.73%  |
| es_ES   | 28        | 7.47%   |
| ru_RU   | 20        | 5.33%   |
| pt_BR   | 17        | 4.53%   |
| en_GB   | 17        | 4.53%   |
| it_IT   | 15        | 4%      |
| fr_FR   | 14        | 3.73%   |
| nl_NL   | 9         | 2.4%    |
| pl_PL   | 6         | 1.6%    |
| tr_TR   | 5         | 1.33%   |
| pt_PT   | 5         | 1.33%   |
| en_AU   | 4         | 1.07%   |
| en_CA   | 3         | 0.8%    |
| nb_NO   | 2         | 0.53%   |
| hu_HU   | 2         | 0.53%   |
| de_CH   | 2         | 0.53%   |
| zh_CN   | 1         | 0.27%   |
| uk_UA   | 1         | 0.27%   |
| sv_SE   | 1         | 0.27%   |
| et_EE   | 1         | 0.27%   |
| es_MX   | 1         | 0.27%   |
| cs_CZ   | 1         | 0.27%   |
| C       | 1         | 0.27%   |
| bg_BG   | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 263       | 69.95%  |
| BIOS | 113       | 30.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 363       | 97.06%  |
| Btrfs   | 6         | 1.6%    |
| Overlay | 4         | 1.07%   |
| Xfs     | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 318       | 84.8%   |
| GPT     | 51        | 13.6%   |
| MBR     | 6         | 1.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 364       | 97.33%  |
| Yes       | 10        | 2.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 350       | 93.58%  |
| Yes       | 24        | 6.42%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 76        | 20.32%  |
| Hewlett-Packard        | 57        | 15.24%  |
| ASUSTek Computer       | 49        | 13.1%   |
| Apple                  | 44        | 11.76%  |
| Dell                   | 42        | 11.23%  |
| Acer                   | 28        | 7.49%   |
| HUAWEI                 | 11        | 2.94%   |
| Toshiba                | 9         | 2.41%   |
| Sony                   | 9         | 2.41%   |
| MSI                    | 9         | 2.41%   |
| Samsung Electronics    | 7         | 1.87%   |
| Notebook               | 3         | 0.8%    |
| Timi                   | 2         | 0.53%   |
| Teclast                | 2         | 0.53%   |
| Star Labs              | 2         | 0.53%   |
| Monster                | 2         | 0.53%   |
| LG Electronics         | 2         | 0.53%   |
| Google                 | 2         | 0.53%   |
| Wortmann AG            | 1         | 0.27%   |
| TUXEDO                 | 1         | 0.27%   |
| TrekStor               | 1         | 0.27%   |
| Standard               | 1         | 0.27%   |
| Razer                  | 1         | 0.27%   |
| PIPO                   | 1         | 0.27%   |
| Packard Bell           | 1         | 0.27%   |
| Medion                 | 1         | 0.27%   |
| iOTA                   | 1         | 0.27%   |
| Fujitsu                | 1         | 0.27%   |
| eMachines              | 1         | 0.27%   |
| Complet                | 1         | 0.27%   |
| Compaq                 | 1         | 0.27%   |
| Clevo                  | 1         | 0.27%   |
| Casper                 | 1         | 0.27%   |
| Avell High Performance | 1         | 0.27%   |
| AMI                    | 1         | 0.27%   |
| Alienware              | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Apple MacBookPro8,2           | 4         | 1.07%   |
| Apple MacBookAir6,2           | 4         | 1.07%   |
| Apple MacBook5,1              | 4         | 1.07%   |
| HUAWEI NBLK-WAX9X             | 3         | 0.8%    |
| HUAWEI MACHD-WXX9             | 3         | 0.8%    |
| HP Notebook                   | 3         | 0.8%    |
| Dell Inspiron 15-3567         | 3         | 0.8%    |
| ASUS ZenBook UX425EA_UX425EA  | 3         | 0.8%    |
| ASUS X550CA                   | 3         | 0.8%    |
| Apple MacBookAir4,2           | 3         | 0.8%    |
| Apple MacBook4,1              | 3         | 0.8%    |
| Timi TM1613                   | 2         | 0.53%   |
| MSI Prestige 15 A11UC         | 2         | 0.53%   |
| MSI Modern 14 B10MW           | 2         | 0.53%   |
| Lenovo Legion Y540-15IRH 81SX | 2         | 0.53%   |
| Lenovo IdeaPad 510-15IKB 80SV | 2         | 0.53%   |
| Lenovo IdeaPad 310-15IKB 80TV | 2         | 0.53%   |
| HP ProBook 4540s              | 2         | 0.53%   |
| HP Pavilion g6                | 2         | 0.53%   |
| HP Pavilion g4                | 2         | 0.53%   |
| HP Pavilion 17                | 2         | 0.53%   |
| HP Laptop 15-db0xxx           | 2         | 0.53%   |
| HP Laptop 15-bw0xx            | 2         | 0.53%   |
| HP EliteBook 8460p            | 2         | 0.53%   |
| HP EliteBook 840 G1           | 2         | 0.53%   |
| Dell XPS 13 9343              | 2         | 0.53%   |
| Dell Inspiron N5050           | 2         | 0.53%   |
| Dell Inspiron 5537            | 2         | 0.53%   |
| Apple MacBookPro6,2           | 2         | 0.53%   |
| Apple MacBookPro5,5           | 2         | 0.53%   |
| Apple MacBookPro11,5          | 2         | 0.53%   |
| Apple MacBookPro10,1          | 2         | 0.53%   |
| Apple MacBookAir7,2           | 2         | 0.53%   |
| Apple MacBookAir7,1           | 2         | 0.53%   |
| Acer Swift SF114-32           | 2         | 0.53%   |
| Wortmann AG 1220729_1470271   | 1         | 0.27%   |
| TUXEDO Book XP14 Gen12        | 1         | 0.27%   |
| TrekStor Notebook Slim S130   | 1         | 0.27%   |
| Toshiba TECRA A11             | 1         | 0.27%   |
| Toshiba Satellite T130        | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 37        | 9.89%   |
| Lenovo IdeaPad     | 25        | 6.68%   |
| Acer Aspire        | 19        | 5.08%   |
| Dell Inspiron      | 17        | 4.55%   |
| HP Pavilion        | 14        | 3.74%   |
| Dell Latitude      | 13        | 3.48%   |
| HP ProBook         | 10        | 2.67%   |
| HP EliteBook       | 10        | 2.67%   |
| HP Laptop          | 9         | 2.41%   |
| ASUS VivoBook      | 9         | 2.41%   |
| ASUS ZenBook       | 8         | 2.14%   |
| Toshiba Satellite  | 6         | 1.6%    |
| Apple MacBookPro8  | 6         | 1.6%    |
| Lenovo Legion      | 5         | 1.34%   |
| Apple MacBookAir6  | 5         | 1.34%   |
| Apple MacBook5     | 5         | 1.34%   |
| Acer Swift         | 5         | 1.34%   |
| Dell XPS           | 4         | 1.07%   |
| Dell Vostro        | 4         | 1.07%   |
| Dell Precision     | 4         | 1.07%   |
| Apple MacBookPro5  | 4         | 1.07%   |
| Apple MacBookPro11 | 4         | 1.07%   |
| Apple MacBookAir7  | 4         | 1.07%   |
| MSI Modern         | 3         | 0.8%    |
| HUAWEI NBLK-WAX9X  | 3         | 0.8%    |
| HUAWEI MACHD-WXX9  | 3         | 0.8%    |
| HP Notebook        | 3         | 0.8%    |
| ASUS X550CA        | 3         | 0.8%    |
| Apple MacBookAir4  | 3         | 0.8%    |
| Apple MacBook4     | 3         | 0.8%    |
| Acer Nitro         | 3         | 0.8%    |
| Toshiba PORTEGE    | 2         | 0.53%   |
| Timi TM1613        | 2         | 0.53%   |
| MSI Prestige       | 2         | 0.53%   |
| Lenovo ThinkBook   | 2         | 0.53%   |
| Lenovo G550        | 2         | 0.53%   |
| HP Stream          | 2         | 0.53%   |
| HP ENVY            | 2         | 0.53%   |
| HP 255             | 2         | 0.53%   |
| HP 240             | 2         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 46        | 12.3%   |
| 2019 | 34        | 9.09%   |
| 2021 | 33        | 8.82%   |
| 2018 | 32        | 8.56%   |
| 2013 | 32        | 8.56%   |
| 2012 | 29        | 7.75%   |
| 2016 | 28        | 7.49%   |
| 2015 | 28        | 7.49%   |
| 2011 | 23        | 6.15%   |
| 2017 | 20        | 5.35%   |
| 2014 | 18        | 4.81%   |
| 2010 | 17        | 4.55%   |
| 2009 | 17        | 4.55%   |
| 2008 | 12        | 3.21%   |
| 2022 | 3         | 0.8%    |
| 2007 | 1         | 0.27%   |
| 2006 | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 374       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 307       | 81.87%  |
| Enabled  | 68        | 18.13%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 369       | 98.66%  |
| Yes  | 5         | 1.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 135       | 35.81%  |
| 3.01-4.0    | 88        | 23.34%  |
| 16.01-24.0  | 64        | 16.98%  |
| 8.01-16.0   | 57        | 15.12%  |
| 32.01-64.0  | 17        | 4.51%   |
| 1.01-2.0    | 10        | 2.65%   |
| 24.01-32.0  | 2         | 0.53%   |
| 2.01-3.0    | 2         | 0.53%   |
| 64.01-256.0 | 2         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 147       | 37.31%  |
| 2.01-3.0   | 124       | 31.47%  |
| 3.01-4.0   | 61        | 15.48%  |
| 4.01-8.0   | 36        | 9.14%   |
| 0.51-1.0   | 14        | 3.55%   |
| 8.01-16.0  | 10        | 2.54%   |
| 24.01-32.0 | 1         | 0.25%   |
| 16.01-24.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 282       | 75%     |
| 2      | 87        | 23.14%  |
| 3      | 5         | 1.33%   |
| 5      | 1         | 0.27%   |
| 4      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 259       | 68.7%   |
| Yes       | 118       | 31.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 73.8%   |
| No        | 98        | 26.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 370       | 98.67%  |
| No        | 5         | 1.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 336       | 89.12%  |
| No        | 41        | 10.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 52        | 13.9%   |
| Germany         | 39        | 10.43%  |
| Russia          | 26        | 6.95%   |
| Brazil          | 24        | 6.42%   |
| Italy           | 20        | 5.35%   |
| India           | 18        | 4.81%   |
| UK              | 17        | 4.55%   |
| Turkey          | 11        | 2.94%   |
| Mexico          | 11        | 2.94%   |
| France          | 11        | 2.94%   |
| Indonesia       | 9         | 2.41%   |
| Poland          | 8         | 2.14%   |
| Netherlands     | 8         | 2.14%   |
| Canada          | 8         | 2.14%   |
| Belgium         | 8         | 2.14%   |
| Australia       | 8         | 2.14%   |
| Spain           | 7         | 1.87%   |
| Portugal        | 6         | 1.6%    |
| Chile           | 6         | 1.6%    |
| Argentina       | 5         | 1.34%   |
| Switzerland     | 4         | 1.07%   |
| Romania         | 4         | 1.07%   |
| Austria         | 4         | 1.07%   |
| Ukraine         | 3         | 0.8%    |
| Norway          | 3         | 0.8%    |
| New Zealand     | 3         | 0.8%    |
| Hungary         | 3         | 0.8%    |
| Czechia         | 3         | 0.8%    |
| South Africa    | 2         | 0.53%   |
| Pakistan        | 2         | 0.53%   |
| North Macedonia | 2         | 0.53%   |
| Iceland         | 2         | 0.53%   |
| Estonia         | 2         | 0.53%   |
| Colombia        | 2         | 0.53%   |
| Bulgaria        | 2         | 0.53%   |
| Belarus         | 2         | 0.53%   |
| Zambia          | 1         | 0.27%   |
| Venezuela       | 1         | 0.27%   |
| Thailand        | 1         | 0.27%   |
| Taiwan          | 1         | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 9         | 2.34%   |
| Sydney                 | 7         | 1.82%   |
| St Petersburg          | 5         | 1.3%    |
| The Hague              | 4         | 1.04%   |
| Munich                 | 4         | 1.04%   |
| Istanbul               | 4         | 1.04%   |
| Rome                   | 3         | 0.78%   |
| Milan                  | 3         | 0.78%   |
| Madrid                 | 3         | 0.78%   |
| Hamburg                | 3         | 0.78%   |
| Yuba City              | 2         | 0.52%   |
| Yaroslavl              | 2         | 0.52%   |
| Warsaw                 | 2         | 0.52%   |
| Vienna                 | 2         | 0.52%   |
| Tucson                 | 2         | 0.52%   |
| Toronto                | 2         | 0.52%   |
| Sao Paulo              | 2         | 0.52%   |
| Santo André           | 2         | 0.52%   |
| Pozza di Fassa         | 2         | 0.52%   |
| Porto                  | 2         | 0.52%   |
| Paris                  | 2         | 0.52%   |
| Mumbai                 | 2         | 0.52%   |
| Monza                  | 2         | 0.52%   |
| Montornès del Vallès | 2         | 0.52%   |
| Minsk                  | 2         | 0.52%   |
| Khimki                 | 2         | 0.52%   |
| Jakarta                | 2         | 0.52%   |
| Islamabad              | 2         | 0.52%   |
| Harelbeke              | 2         | 0.52%   |
| Fortaleza              | 2         | 0.52%   |
| Cologne                | 2         | 0.52%   |
| Chelyabinsk            | 2         | 0.52%   |
| Cankaya                | 2         | 0.52%   |
| Bogor                  | 2         | 0.52%   |
| Bern                   | 2         | 0.52%   |
| Berlin                 | 2         | 0.52%   |
| Belo Horizonte         | 2         | 0.52%   |
| Austin                 | 2         | 0.52%   |
| Antalya                | 2         | 0.52%   |
| Ankara                 | 2         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 69        | 82     | 14.81%  |
| Seagate                     | 44        | 47     | 9.44%   |
| WDC                         | 42        | 49     | 9.01%   |
| Toshiba                     | 37        | 38     | 7.94%   |
| SanDisk                     | 31        | 33     | 6.65%   |
| Kingston                    | 26        | 29     | 5.58%   |
| Unknown                     | 22        | 25     | 4.72%   |
| Apple                       | 21        | 23     | 4.51%   |
| Crucial                     | 19        | 21     | 4.08%   |
| HGST                        | 17        | 18     | 3.65%   |
| SK hynix                    | 15        | 16     | 3.22%   |
| Intel                       | 11        | 14     | 2.36%   |
| A-DATA Technology           | 10        | 10     | 2.15%   |
| Hitachi                     | 8         | 8      | 1.72%   |
| Phison                      | 6         | 7      | 1.29%   |
| Micron Technology           | 6         | 7      | 1.29%   |
| KIOXIA                      | 6         | 7      | 1.29%   |
| China                       | 4         | 4      | 0.86%   |
| Silicon Motion              | 3         | 3      | 0.64%   |
| JMicron Technology          | 3         | 3      | 0.64%   |
| Fujitsu                     | 3         | 3      | 0.64%   |
| Unknown                     | 3         | 3      | 0.64%   |
| Transcend                   | 2         | 2      | 0.43%   |
| TO Exter                    | 2         | 2      | 0.43%   |
| PNY                         | 2         | 3      | 0.43%   |
| OCZ                         | 2         | 3      | 0.43%   |
| Micron/Crucial Technology   | 2         | 2      | 0.43%   |
| LITEON                      | 2         | 2      | 0.43%   |
| KingDian                    | 2         | 2      | 0.43%   |
| FORESEE                     | 2         | 2      | 0.43%   |
| EYOTA                       | 2         | 2      | 0.43%   |
| ZTE                         | 1         | 1      | 0.21%   |
| Yangtze Memory Technologies | 1         | 1      | 0.21%   |
| XPG                         | 1         | 1      | 0.21%   |
| V-GeN                       | 1         | 1      | 0.21%   |
| Union Memory                | 1         | 1      | 0.21%   |
| UMIS                        | 1         | 1      | 0.21%   |
| Timetec                     | 1         | 1      | 0.21%   |
| Teclast                     | 1         | 1      | 0.21%   |
| Team                        | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                 | 10        | 2.1%    |
| Seagate ST1000LM035-1RK172 1TB         | 9         | 1.89%   |
| Samsung NVMe SSD Drive 512GB           | 9         | 1.89%   |
| Kingston SA400S37240G 240GB SSD        | 8         | 1.68%   |
| SanDisk NVMe SSD Drive 512GB           | 7         | 1.47%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 6         | 1.26%   |
| Unknown MMC Card  32GB                 | 5         | 1.05%   |
| Toshiba MQ01ABF050 500GB               | 5         | 1.05%   |
| Seagate ST500LT012-1DG142 500GB        | 5         | 1.05%   |
| Samsung SSD 850 EVO 250GB              | 5         | 1.05%   |
| HGST HTS545050A7E680 500GB             | 5         | 1.05%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 4         | 0.84%   |
| Unknown MMC Card  64GB                 | 4         | 0.84%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 0.84%   |
| SK hynix NVMe SSD Drive 256GB          | 4         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 4         | 0.84%   |
| Samsung NVMe SSD Drive 1024GB          | 4         | 0.84%   |
| Intel NVMe SSD Drive 512GB             | 4         | 0.84%   |
| HGST HTS541010B7E610 1TB               | 4         | 0.84%   |
| Unknown MMC Card  128GB                | 3         | 0.63%   |
| Toshiba NVMe SSD Drive 512GB           | 3         | 0.63%   |
| Toshiba NVMe SSD Drive 256GB           | 3         | 0.63%   |
| SK hynix NVMe SSD Drive 512GB          | 3         | 0.63%   |
| SanDisk NVMe SSD Drive 1024GB          | 3         | 0.63%   |
| Samsung SSD 860 EVO 500GB              | 3         | 0.63%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.63%   |
| Samsung SSD 850 EVO 500GB              | 3         | 0.63%   |
| Samsung NVMe SSD Drive 1TB             | 3         | 0.63%   |
| Phison NVMe SSD Drive 1TB              | 3         | 0.63%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 3         | 0.63%   |
| Kingston SA400S37120G 120GB SSD        | 3         | 0.63%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.63%   |
| Apple SSD SM0512G 500GB                | 3         | 0.63%   |
| Apple SSD SD0256F 256GB                | 3         | 0.63%   |
| A-DATA SU650 120GB SSD                 | 3         | 0.63%   |
| Unknown                                | 3         | 0.63%   |
| WDC WD5000LPVX-75V0TT0 500GB           | 2         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.42%   |
| TO Exter nal USB 3.0 1TB               | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 47     | 33.85%  |
| WDC                 | 28        | 33     | 21.54%  |
| Toshiba             | 25        | 26     | 19.23%  |
| HGST                | 17        | 18     | 13.08%  |
| Hitachi             | 8         | 8      | 6.15%   |
| Fujitsu             | 3         | 3      | 2.31%   |
| Unknown             | 1         | 1      | 0.77%   |
| Samsung Electronics | 1         | 1      | 0.77%   |
| SABRENT             | 1         | 1      | 0.77%   |
| Generic-            | 1         | 1      | 0.77%   |
| Apple               | 1         | 1      | 0.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 44     | 21.59%  |
| Crucial             | 19        | 21     | 10.8%   |
| Kingston            | 18        | 18     | 10.23%  |
| Apple               | 18        | 19     | 10.23%  |
| SanDisk             | 14        | 16     | 7.95%   |
| WDC                 | 8         | 8      | 4.55%   |
| A-DATA Technology   | 8         | 8      | 4.55%   |
| Toshiba             | 4         | 4      | 2.27%   |
| Micron Technology   | 4         | 5      | 2.27%   |
| China               | 4         | 4      | 2.27%   |
| Intel               | 3         | 3      | 1.7%    |
| Transcend           | 2         | 2      | 1.14%   |
| TO Exter            | 2         | 2      | 1.14%   |
| SK hynix            | 2         | 2      | 1.14%   |
| PNY                 | 2         | 3      | 1.14%   |
| OCZ                 | 2         | 3      | 1.14%   |
| LITEON              | 2         | 2      | 1.14%   |
| FORESEE             | 2         | 2      | 1.14%   |
| Teclast             | 1         | 1      | 0.57%   |
| Team                | 1         | 1      | 0.57%   |
| Super Talent        | 1         | 1      | 0.57%   |
| Star                | 1         | 1      | 0.57%   |
| SPCC                | 1         | 1      | 0.57%   |
| Smartbuy            | 1         | 1      | 0.57%   |
| Pioneer             | 1         | 1      | 0.57%   |
| Pichau              | 1         | 1      | 0.57%   |
| Phison              | 1         | 2      | 0.57%   |
| Patriot             | 1         | 2      | 0.57%   |
| NGFF                | 1         | 1      | 0.57%   |
| Netac               | 1         | 1      | 0.57%   |
| MENGMI              | 1         | 1      | 0.57%   |
| Lexar               | 1         | 1      | 0.57%   |
| KingSpec            | 1         | 1      | 0.57%   |
| KingDian            | 1         | 1      | 0.57%   |
| GOODRAM             | 1         | 1      | 0.57%   |
| EYOTA               | 1         | 1      | 0.57%   |
| EVM                 | 1         | 1      | 0.57%   |
| Dogfish             | 1         | 1      | 0.57%   |
| Corsair             | 1         | 1      | 0.57%   |
| Colorful            | 1         | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 169       | 192    | 37.47%  |
| HDD     | 128       | 140    | 28.38%  |
| NVMe    | 115       | 141    | 25.5%   |
| MMC     | 23        | 25     | 5.1%    |
| Unknown | 16        | 17     | 3.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 270       | 330    | 63.38%  |
| NVMe | 115       | 140    | 27%     |
| MMC  | 23        | 25     | 5.4%    |
| SAS  | 18        | 20     | 4.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 207       | 244    | 72.13%  |
| 0.51-1.0   | 70        | 74     | 24.39%  |
| 1.01-2.0   | 8         | 12     | 2.79%   |
| 4.01-10.0  | 2         | 2      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 158       | 42.02%  |
| 251-500        | 96        | 25.53%  |
| 501-1000       | 57        | 15.16%  |
| 51-100         | 28        | 7.45%   |
| 21-50          | 17        | 4.52%   |
| 1001-2000      | 15        | 3.99%   |
| 2001-3000      | 2         | 0.53%   |
| More than 3000 | 1         | 0.27%   |
| 1-20           | 1         | 0.27%   |
| Unknown        | 1         | 0.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 176       | 45.24%  |
| 21-50     | 107       | 27.51%  |
| 51-100    | 44        | 11.31%  |
| 101-250   | 31        | 7.97%   |
| 251-500   | 17        | 4.37%   |
| 501-1000  | 9         | 2.31%   |
| 1001-2000 | 3         | 0.77%   |
| 2001-3000 | 1         | 0.26%   |
| Unknown   | 1         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 14.29%  |
| Seagate ST500LM030-2E717D 500GB  | 1         | 1      | 14.29%  |
| Kingston SV300S37A240G 240GB SSD | 1         | 1      | 14.29%  |
| Kingston SUV400S37480G 480GB SSD | 1         | 1      | 14.29%  |
| HGST HTS545050A7E680 500GB       | 1         | 1      | 14.29%  |
| Crucial CT512M550SSD3 512GB      | 1         | 1      | 14.29%  |
| Apple SSD SM256C 256GB           | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 2         | 2      | 28.57%  |
| WDC      | 1         | 1      | 14.29%  |
| Seagate  | 1         | 1      | 14.29%  |
| HGST     | 1         | 1      | 14.29%  |
| Crucial  | 1         | 1      | 14.29%  |
| Apple    | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 4      | 57.14%  |
| HDD  | 3         | 3      | 42.86%  |

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
| Detected | 335       | 444    | 85.03%  |
| Works    | 52        | 64     | 13.2%   |
| Malfunc  | 7         | 7      | 1.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 253       | 58.97%  |
| AMD                            | 43        | 10.02%  |
| Samsung Electronics            | 38        | 8.86%   |
| SanDisk                        | 21        | 4.9%    |
| SK hynix                       | 13        | 3.03%   |
| Nvidia                         | 10        | 2.33%   |
| Kingston Technology Company    | 10        | 2.33%   |
| Toshiba America Info Systems   | 8         | 1.86%   |
| Phison Electronics             | 6         | 1.4%    |
| Marvell Technology Group       | 4         | 0.93%   |
| KIOXIA                         | 4         | 0.93%   |
| Silicon Motion                 | 3         | 0.7%    |
| Union Memory (Shenzhen)        | 2         | 0.47%   |
| Realtek Semiconductor          | 2         | 0.47%   |
| Micron/Crucial Technology      | 2         | 0.47%   |
| Micron Technology              | 2         | 0.47%   |
| Apple                          | 2         | 0.47%   |
| ADATA Technology               | 2         | 0.47%   |
| Yangtze Memory Technologies    | 1         | 0.23%   |
| Solid State Storage Technology | 1         | 0.23%   |
| Lite-On Technology             | 1         | 0.23%   |
| Biwin Storage Technology       | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 41        | 9.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 34        | 7.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 7.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 26        | 5.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 15        | 3.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 3.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 3.1%    |
| Samsung NVMe SSD Controller 980                                                  | 13        | 2.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 2.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 2.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 2.22%   |
| Intel Comet Lake SATA AHCI Controller                                            | 9         | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 2%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 2%      |
| Nvidia MCP79 AHCI Controller                                                     | 8         | 1.77%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 1.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 1.77%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 7         | 1.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 1.55%   |
| Intel SSD 660P Series                                                            | 7         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.55%   |
| Samsung Electronics SATA controller                                              | 6         | 1.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.11%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 1.11%   |
| SK hynix Gold P31 SSD                                                            | 4         | 0.89%   |
| SK hynix BC511                                                                   | 4         | 0.89%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 4         | 0.89%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 0.89%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 4         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.67%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 0.67%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 3         | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.67%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 284       | 65.14%  |
| NVMe | 113       | 25.92%  |
| RAID | 24        | 5.5%    |
| IDE  | 15        | 3.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 309       | 82.62%  |
| AMD    | 65        | 17.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 3.21%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 2.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 2.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 1.34%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.34%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 1.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.34%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 1.34%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.07%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 1.07%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 1.07%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.07%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.07%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.07%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 1.07%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 1.07%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.8%    |
| Intel Core i7-10875H CPU @ 2.30GHz            | 3         | 0.8%    |
| Intel Core i5-4250U CPU @ 1.30GHz             | 3         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.8%    |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 0.8%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.8%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.8%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.8%    |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 0.8%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.8%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.8%    |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 0.8%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.8%    |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz       | 3         | 0.8%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.8%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.8%    |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 0.8%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 91        | 24.33%  |
| Intel Core i7           | 86        | 22.99%  |
| Intel Core i3           | 39        | 10.43%  |
| Other                   | 28        | 7.49%   |
| Intel Celeron           | 26        | 6.95%   |
| AMD Ryzen 5             | 23        | 6.15%   |
| Intel Core 2 Duo        | 20        | 5.35%   |
| Intel Pentium           | 8         | 2.14%   |
| AMD Ryzen 7             | 7         | 1.87%   |
| AMD A10                 | 6         | 1.6%    |
| AMD Ryzen 3             | 4         | 1.07%   |
| AMD A6                  | 4         | 1.07%   |
| Intel Pentium Silver    | 3         | 0.8%    |
| AMD Ryzen 7 PRO         | 3         | 0.8%    |
| AMD A8                  | 3         | 0.8%    |
| AMD A12                 | 3         | 0.8%    |
| Intel Pentium Dual-Core | 2         | 0.53%   |
| Intel Genuine           | 2         | 0.53%   |
| Intel Celeron Dual-Core | 2         | 0.53%   |
| AMD Ryzen 5 PRO         | 2         | 0.53%   |
| AMD A4                  | 2         | 0.53%   |
| Intel Pentium Dual      | 1         | 0.27%   |
| Intel Core m5           | 1         | 0.27%   |
| Intel Core i9           | 1         | 0.27%   |
| Intel Core 2 Quad       | 1         | 0.27%   |
| Intel Core 2            | 1         | 0.27%   |
| Intel Atom              | 1         | 0.27%   |
| AMD Ryzen 9             | 1         | 0.27%   |
| AMD Phenom II           | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD E                   | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 211       | 56.42%  |
| 4      | 123       | 32.89%  |
| 6      | 23        | 6.15%   |
| 8      | 15        | 4.01%   |
| 1      | 2         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 374       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 285       | 76.2%   |
| 1      | 89        | 23.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 374       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 31        | 8.18%   |
| 0x306a9    | 30        | 7.92%   |
| Unknown    | 26        | 6.86%   |
| 0x806c1    | 19        | 5.01%   |
| 0x306d4    | 19        | 5.01%   |
| 0x40651    | 18        | 4.75%   |
| 0x806e9    | 16        | 4.22%   |
| 0x1067a    | 16        | 4.22%   |
| 0x806ec    | 13        | 3.43%   |
| 0x406e3    | 13        | 3.43%   |
| 0x20655    | 13        | 3.43%   |
| 0xa0652    | 9         | 2.37%   |
| 0x806ea    | 9         | 2.37%   |
| 0x306c3    | 8         | 2.11%   |
| 0x10676    | 8         | 2.11%   |
| 0x08600106 | 8         | 2.11%   |
| 0x08108109 | 8         | 2.11%   |
| 0x706a8    | 7         | 1.85%   |
| 0x706e5    | 6         | 1.58%   |
| 0x506c9    | 6         | 1.58%   |
| 0x406c3    | 6         | 1.58%   |
| 0x08608103 | 6         | 1.58%   |
| 0x906ea    | 5         | 1.32%   |
| 0x806eb    | 5         | 1.32%   |
| 0x20652    | 5         | 1.32%   |
| 0x06006705 | 5         | 1.32%   |
| 0x06001119 | 5         | 1.32%   |
| 0x706a1    | 4         | 1.06%   |
| 0x6fd      | 4         | 1.06%   |
| 0x40661    | 4         | 1.06%   |
| 0x0a50000c | 4         | 1.06%   |
| 0x08108102 | 4         | 1.06%   |
| 0x906e9    | 3         | 0.79%   |
| 0x806c2    | 3         | 0.79%   |
| 0x30678    | 3         | 0.79%   |
| 0x08101007 | 3         | 0.79%   |
| 0x0600611a | 3         | 0.79%   |
| 0x906ed    | 2         | 0.53%   |
| 0x506e3    | 2         | 0.53%   |
| 0x0810100b | 2         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 59        | 15.78%  |
| SandyBridge   | 32        | 8.56%   |
| Haswell       | 32        | 8.56%   |
| IvyBridge     | 31        | 8.29%   |
| Penryn        | 24        | 6.42%   |
| TigerLake     | 23        | 6.15%   |
| Broadwell     | 19        | 5.08%   |
| Westmere      | 18        | 4.81%   |
| Skylake       | 16        | 4.28%   |
| Excavator     | 13        | 3.48%   |
| Zen+          | 12        | 3.21%   |
| Zen 2         | 12        | 3.21%   |
| Goldmont plus | 12        | 3.21%   |
| Silvermont    | 11        | 2.94%   |
| CometLake     | 10        | 2.67%   |
| Unknown       | 8         | 2.14%   |
| IceLake       | 7         | 1.87%   |
| Goldmont      | 6         | 1.6%    |
| Core          | 6         | 1.6%    |
| Zen           | 5         | 1.34%   |
| Piledriver    | 5         | 1.34%   |
| Zen 3         | 4         | 1.07%   |
| Puma          | 2         | 0.53%   |
| Jaguar        | 2         | 0.53%   |
| Tremont       | 1         | 0.27%   |
| Nehalem       | 1         | 0.27%   |
| K10 Llano     | 1         | 0.27%   |
| K10           | 1         | 0.27%   |
| Bobcat        | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 283       | 60.34%  |
| AMD    | 97        | 20.68%  |
| Nvidia | 89        | 18.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 6.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 6.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 4.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 3.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 3.27%   |
| Intel HD Graphics 620                                                                    | 15        | 3.07%   |
| Intel HD Graphics 5500                                                                   | 15        | 3.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 2.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 2.45%   |
| AMD Renoir                                                                               | 12        | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.45%   |
| Intel UHD Graphics 620                                                                   | 10        | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.84%   |
| Nvidia C79 [GeForce 9400M]                                                               | 8         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.43%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.43%   |
| AMD Lucienne                                                                             | 7         | 1.43%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.23%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 1.23%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 1.23%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 1.02%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 1.02%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.02%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.82%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.82%   |
| AMD Cezanne                                                                              | 4         | 0.82%   |
| Nvidia TU117M                                                                            | 3         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.61%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 3         | 0.61%   |
| Intel HD Graphics 500                                                                    | 3         | 0.61%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 190       | 50.8%   |
| Intel + Nvidia | 67        | 17.91%  |
| 1 x AMD        | 57        | 15.24%  |
| Intel + AMD    | 25        | 6.68%   |
| 1 x Nvidia     | 17        | 4.55%   |
| 2 x AMD        | 12        | 3.21%   |
| AMD + Nvidia   | 3         | 0.8%    |
| 2 x Nvidia     | 2         | 0.53%   |
| Other          | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 332       | 88.53%  |
| Proprietary | 41        | 10.93%  |
| Unknown     | 2         | 0.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 223       | 59.47%  |
| 0.01-0.5   | 51        | 13.6%   |
| 1.01-2.0   | 50        | 13.33%  |
| 0.51-1.0   | 30        | 8%      |
| 3.01-4.0   | 12        | 3.2%    |
| 5.01-6.0   | 7         | 1.87%   |
| 7.01-8.0   | 2         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 75        | 17.61%  |
| LG Display              | 64        | 15.02%  |
| BOE                     | 57        | 13.38%  |
| Chimei Innolux          | 52        | 12.21%  |
| Apple                   | 44        | 10.33%  |
| Samsung Electronics     | 35        | 8.22%   |
| Dell                    | 10        | 2.35%   |
| Sharp                   | 9         | 2.11%   |
| Chi Mei Optoelectronics | 9         | 2.11%   |
| PANDA                   | 8         | 1.88%   |
| Lenovo                  | 8         | 1.88%   |
| Hewlett-Packard         | 6         | 1.41%   |
| Goldstar                | 6         | 1.41%   |
| CSO                     | 5         | 1.17%   |
| ViewSonic               | 4         | 0.94%   |
| Sony                    | 3         | 0.7%    |
| InfoVision              | 3         | 0.7%    |
| BenQ                    | 3         | 0.7%    |
| AOC                     | 3         | 0.7%    |
| Acer                    | 2         | 0.47%   |
| Toshiba                 | 1         | 0.23%   |
| TopView                 | 1         | 0.23%   |
| TMX                     | 1         | 0.23%   |
| Tech Concepts           | 1         | 0.23%   |
| SANYO                   | 1         | 0.23%   |
| Plain Tree Systems      | 1         | 0.23%   |
| Philips                 | 1         | 0.23%   |
| Panasonic               | 1         | 0.23%   |
| Packard Bell            | 1         | 0.23%   |
| LG Philips              | 1         | 0.23%   |
| Konka                   | 1         | 0.23%   |
| JDI                     | 1         | 0.23%   |
| HUAWEI                  | 1         | 0.23%   |
| HJC                     | 1         | 0.23%   |
| EXP                     | 1         | 0.23%   |
| DPL                     | 1         | 0.23%   |
| CPT                     | 1         | 0.23%   |
| BOE Technology Group    | 1         | 0.23%   |
| ASUSTek Computer        | 1         | 0.23%   |
| Ancor Communications    | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 1.15%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 1.15%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 5         | 1.15%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.92%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.92%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 4         | 0.92%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 0.92%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.69%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.69%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.69%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 0.69%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.69%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 3         | 0.69%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 3         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.46%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.46%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.46%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 2         | 0.46%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.46%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.46%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.46%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.46%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.46%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 2         | 0.46%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.46%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 344x193mm 15.5-inch      | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.46%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.46%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 2         | 0.46%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 164       | 40.59%  |
| 1366x768 (WXGA)    | 127       | 31.44%  |
| 1440x900 (WXGA+)   | 20        | 4.95%   |
| 1600x900 (HD+)     | 18        | 4.46%   |
| 1280x800 (WXGA)    | 16        | 3.96%   |
| 3840x2160 (4K)     | 13        | 3.22%   |
| 2560x1440 (QHD)    | 12        | 2.97%   |
| 2880x1800          | 8         | 1.98%   |
| 3000x2000          | 4         | 0.99%   |
| 1920x1200 (WUXGA)  | 4         | 0.99%   |
| 2560x1600          | 3         | 0.74%   |
| 3200x1800 (QHD+)   | 2         | 0.5%    |
| 2560x1080          | 2         | 0.5%    |
| 1680x1050 (WSXGA+) | 2         | 0.5%    |
| 1280x1024 (SXGA)   | 2         | 0.5%    |
| 3840x2400          | 1         | 0.25%   |
| 3840x1100          | 1         | 0.25%   |
| 3072x1920          | 1         | 0.25%   |
| 1920x540           | 1         | 0.25%   |
| 1920x1280          | 1         | 0.25%   |
| 1400x1050          | 1         | 0.25%   |
| 1360x768           | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 163       | 38.08%  |
| 13      | 83        | 19.39%  |
| 14      | 66        | 15.42%  |
| 17      | 27        | 6.31%   |
| 11      | 13        | 3.04%   |
| 27      | 11        | 2.57%   |
| 23      | 11        | 2.57%   |
| 24      | 10        | 2.34%   |
| 12      | 8         | 1.87%   |
| 31      | 5         | 1.17%   |
| 16      | 5         | 1.17%   |
| Unknown | 4         | 0.93%   |
| 21      | 3         | 0.7%    |
| 84      | 2         | 0.47%   |
| 72      | 2         | 0.47%   |
| 52      | 2         | 0.47%   |
| 34      | 2         | 0.47%   |
| 25      | 2         | 0.47%   |
| 18      | 2         | 0.47%   |
| 47      | 1         | 0.23%   |
| 43      | 1         | 0.23%   |
| 33      | 1         | 0.23%   |
| 26      | 1         | 0.23%   |
| 22      | 1         | 0.23%   |
| 20      | 1         | 0.23%   |
| 19      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 261       | 61.85%  |
| 201-300     | 69        | 16.35%  |
| 501-600     | 32        | 7.58%   |
| 351-400     | 32        | 7.58%   |
| 401-500     | 8         | 1.9%    |
| 601-700     | 5         | 1.18%   |
| 1501-2000   | 4         | 0.95%   |
| Unknown     | 4         | 0.95%   |
| 701-800     | 3         | 0.71%   |
| 1001-1500   | 3         | 0.71%   |
| 901-1000    | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 312       | 81.68%  |
| 16/10   | 54        | 14.14%  |
| 3/2     | 7         | 1.83%   |
| Unknown | 3         | 0.79%   |
| 5/4     | 2         | 0.52%   |
| 21/9    | 2         | 0.52%   |
| 4/3     | 1         | 0.26%   |
| 3.40    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 163       | 38.35%  |
| 81-90          | 116       | 27.29%  |
| 71-80          | 32        | 7.53%   |
| 121-130        | 21        | 4.94%   |
| 201-250        | 20        | 4.71%   |
| 51-60          | 14        | 3.29%   |
| 301-350        | 11        | 2.59%   |
| 61-70          | 8         | 1.88%   |
| 351-500        | 8         | 1.88%   |
| More than 1000 | 6         | 1.41%   |
| 251-300        | 5         | 1.18%   |
| 141-150        | 4         | 0.94%   |
| 131-140        | 4         | 0.94%   |
| 111-120        | 4         | 0.94%   |
| Unknown        | 4         | 0.94%   |
| 151-200        | 2         | 0.47%   |
| 501-1000       | 2         | 0.47%   |
| 91-100         | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 179       | 42.72%  |
| 101-120       | 139       | 33.17%  |
| 51-100        | 50        | 11.93%  |
| 161-240       | 28        | 6.68%   |
| More than 240 | 15        | 3.58%   |
| 1-50          | 4         | 0.95%   |
| Unknown       | 4         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 322       | 85.19%  |
| 2     | 47        | 12.43%  |
| 3     | 7         | 1.85%   |
| 4     | 1         | 0.26%   |
| 0     | 1         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 179       | 31.35%  |
| Intel                             | 173       | 30.3%   |
| Qualcomm Atheros                  | 82        | 14.36%  |
| Broadcom                          | 58        | 10.16%  |
| Broadcom Limited                  | 15        | 2.63%   |
| Nvidia                            | 9         | 1.58%   |
| Marvell Technology Group          | 8         | 1.4%    |
| Ralink                            | 6         | 1.05%   |
| MediaTek                          | 6         | 1.05%   |
| TP-Link                           | 5         | 0.88%   |
| Sierra Wireless                   | 3         | 0.53%   |
| Ralink Technology                 | 3         | 0.53%   |
| Xiaomi                            | 2         | 0.35%   |
| Lenovo                            | 2         | 0.35%   |
| Huawei Technologies               | 2         | 0.35%   |
| Google                            | 2         | 0.35%   |
| D-Link                            | 2         | 0.35%   |
| ASIX Electronics                  | 2         | 0.35%   |
| Apple                             | 2         | 0.35%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.18%   |
| TRENDnet                          | 1         | 0.18%   |
| Sitecom Europe                    | 1         | 0.18%   |
| Samsung Electronics               | 1         | 0.18%   |
| Qualcomm                          | 1         | 0.18%   |
| OPPO Electronics                  | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.18%   |
| JMicron Technology                | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| Ericsson Business Mobile Networks | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 106       | 15.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 5.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 2.79%   |
| Intel Wi-Fi 6 AX201                                               | 18        | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 2.2%    |
| Intel Wireless 8260                                               | 15        | 2.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 1.91%   |
| Intel Wireless 8265 / 8275                                        | 12        | 1.76%   |
| Intel Wireless 7265                                               | 11        | 1.61%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.47%   |
| Nvidia MCP79 Ethernet                                             | 9         | 1.32%   |
| Intel Wireless 7260                                               | 9         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.32%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 9         | 1.32%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 9         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 1.17%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 1.17%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 8         | 1.17%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 8         | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 0.73%   |
| Intel Wireless 3165                                               | 5         | 0.73%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.73%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.73%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 5         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 166       | 42.56%  |
| Qualcomm Atheros      | 72        | 18.46%  |
| Realtek Semiconductor | 57        | 14.62%  |
| Broadcom              | 55        | 14.1%   |
| Broadcom Limited      | 14        | 3.59%   |
| Ralink                | 6         | 1.54%   |
| TP-Link               | 5         | 1.28%   |
| MediaTek              | 4         | 1.03%   |
| Sierra Wireless       | 3         | 0.77%   |
| Ralink Technology     | 3         | 0.77%   |
| D-Link                | 2         | 0.51%   |
| TRENDnet              | 1         | 0.26%   |
| Sitecom Europe        | 1         | 0.26%   |
| Qualcomm              | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19        | 4.85%   |
| Intel Wi-Fi 6 AX201                                            | 18        | 4.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 3.83%   |
| Intel Wireless 8260                                            | 15        | 3.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 3.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 3.32%   |
| Intel Wireless 8265 / 8275                                     | 12        | 3.06%   |
| Intel Wireless 7265                                            | 11        | 2.81%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 2.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 2.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 2.55%   |
| Intel Wireless 7260                                            | 9         | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.3%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 9         | 2.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 2.3%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 2.04%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 8         | 2.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 8         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 1.28%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.28%   |
| Intel Wireless 3165                                            | 5         | 1.28%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.28%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.28%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 5         | 1.28%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.02%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.02%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 1.02%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 4         | 1.02%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 3         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 157       | 55.28%  |
| Intel                      | 52        | 18.31%  |
| Qualcomm Atheros           | 21        | 7.39%   |
| Broadcom                   | 17        | 5.99%   |
| Nvidia                     | 9         | 3.17%   |
| Marvell Technology Group   | 8         | 2.82%   |
| Xiaomi                     | 2         | 0.7%    |
| MediaTek                   | 2         | 0.7%    |
| Lenovo                     | 2         | 0.7%    |
| Google                     | 2         | 0.7%    |
| Broadcom Limited           | 2         | 0.7%    |
| ASIX Electronics           | 2         | 0.7%    |
| Apple                      | 2         | 0.7%    |
| ZTE WCDMA Technologies MSM | 1         | 0.35%   |
| Samsung Electronics        | 1         | 0.35%   |
| OPPO Electronics           | 1         | 0.35%   |
| JMicron Technology         | 1         | 0.35%   |
| Huawei Technologies        | 1         | 0.35%   |
| Hewlett-Packard            | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 106       | 36.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 38        | 13.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 3.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 3.48%   |
| Nvidia MCP79 Ethernet                                                          | 9         | 3.14%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 8         | 2.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.74%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.39%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.39%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.7%    |
| MediaTek TECNO Pouvoir 3 Air                                                   | 2         | 0.7%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.7%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.7%    |
| Lenovo ThinkPad Lan                                                            | 2         | 0.7%    |
| Intel Ethernet Connection I218-V                                               | 2         | 0.7%    |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.7%    |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.7%    |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.7%    |
| Google Nexus/Pixel Device (tether)                                             | 2         | 0.7%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.7%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.7%    |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.7%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.7%    |
| ZTE WCDMA MSM ZTE MSM                                                          | 1         | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.35%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 371       | 57.25%  |
| Ethernet | 274       | 42.28%  |
| Modem    | 2         | 0.31%   |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 313       | 82.59%  |
| Ethernet | 66        | 17.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 251       | 66.93%  |
| 1     | 117       | 31.2%   |
| 0     | 4         | 1.07%   |
| 3     | 3         | 0.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 259       | 68.7%   |
| Yes  | 118       | 31.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 142       | 41.76%  |
| Apple                           | 43        | 12.65%  |
| Realtek Semiconductor           | 36        | 10.59%  |
| Qualcomm Atheros Communications | 25        | 7.35%   |
| Broadcom                        | 18        | 5.29%   |
| Lite-On Technology              | 17        | 5%      |
| IMC Networks                    | 15        | 4.41%   |
| Foxconn / Hon Hai               | 13        | 3.82%   |
| Toshiba                         | 6         | 1.76%   |
| Hewlett-Packard                 | 6         | 1.76%   |
| Ralink                          | 5         | 1.47%   |
| Cambridge Silicon Radio         | 5         | 1.47%   |
| Realtek                         | 4         | 1.18%   |
| Dell                            | 3         | 0.88%   |
| ASUSTek Computer                | 2         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 59        | 17.35%  |
| Intel AX201 Bluetooth                               | 30        | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 8.24%   |
| Apple Bluetooth Host Controller                     | 21        | 6.18%   |
| Realtek Bluetooth Radio                             | 20        | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 4.71%   |
| Apple Bluetooth USB Host Controller                 | 14        | 4.12%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 3.24%   |
| Intel AX200 Bluetooth                               | 11        | 3.24%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.76%   |
| Ralink RT3290 Bluetooth                             | 5         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 1.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 1.47%   |
| Realtek Bluetooth Radio                             | 4         | 1.18%   |
| Lite-On Bluetooth Device                            | 4         | 1.18%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 1.18%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.18%   |
| IMC Networks Bluetooth Device                       | 4         | 1.18%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 1.18%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.18%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 1.18%   |
| Apple Bluetooth HCI                                 | 4         | 1.18%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.88%   |
| Intel AX210 Bluetooth                               | 3         | 0.88%   |
| IMC Networks Wireless_Device                        | 3         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.88%   |
| Toshiba RT Bluetooth Radio                          | 2         | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.59%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.59%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.59%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.59%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 297       | 67.96%  |
| AMD                     | 78        | 17.85%  |
| Nvidia                  | 46        | 10.53%  |
| Logitech                | 2         | 0.46%   |
| ESS Technology          | 2         | 0.46%   |
| C-Media Electronics     | 2         | 0.46%   |
| Texas Instruments       | 1         | 0.23%   |
| SteelSeries ApS         | 1         | 0.23%   |
| Realtek Semiconductor   | 1         | 0.23%   |
| No brand                | 1         | 0.23%   |
| Huawei Technologies     | 1         | 0.23%   |
| Goldvish                | 1         | 0.23%   |
| Generalplus Technology  | 1         | 0.23%   |
| Dell                    | 1         | 0.23%   |
| BEHRINGER International | 1         | 0.23%   |
| Apple                   | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 41        | 7.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 38        | 6.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 35        | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 5.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 4.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 4.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 3.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 3.46%   |
| Intel Broadwell-U Audio Controller                                                                | 19        | 3.46%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 3.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 3.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 3.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 2.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 2.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 2.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 2.19%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.82%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.82%   |
| Nvidia MCP79 High Definition Audio                                                                | 9         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.46%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.28%   |
| AMD High Definition Audio Controller                                                              | 7         | 1.28%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.91%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.73%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.55%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.55%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 36%     |
| SK hynix            | 17        | 22.67%  |
| Micron Technology   | 13        | 17.33%  |
| Crucial             | 3         | 4%      |
| Unknown (ABCD)      | 2         | 2.67%   |
| Unknown             | 2         | 2.67%   |
| Kingston            | 2         | 2.67%   |
| G.Skill             | 2         | 2.67%   |
| A-DATA Technology   | 2         | 2.67%   |
| Transcend           | 1         | 1.33%   |
| SHARETRONIC         | 1         | 1.33%   |
| Ramaxel Technology  | 1         | 1.33%   |
| GSkill              | 1         | 1.33%   |
| Elpida              | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 3.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 3.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.41%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 2         | 2.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 2.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.41%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 2         | 2.41%   |
| Unknown RAM Module 8192MB SODIMM DDR3                            | 1         | 1.2%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.2%    |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s         | 1         | 1.2%    |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 1.2%    |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.2%    |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 1         | 1.2%    |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 1.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.2%    |
| SK hynix RAM HMP351S6AFR8C-S6 4096MB SODIMM DDR2 800MT/s         | 1         | 1.2%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.2%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s           | 1         | 1.2%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.2%    |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 1.2%    |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.2%    |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 1.2%    |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.2%    |
| Samsung RAM M471B5674EB0-YK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.2%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.2%    |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 35        | 51.47%  |
| DDR3   | 21        | 30.88%  |
| LPDDR4 | 8         | 11.76%  |
| LPDDR3 | 2         | 2.94%   |
| DDR2   | 2         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 88.24%  |
| Row Of Chips | 7         | 10.29%  |
| Chip         | 1         | 1.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 36        | 46.75%  |
| 4096  | 24        | 31.17%  |
| 2048  | 9         | 11.69%  |
| 16384 | 8         | 10.39%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 21.62%  |
| 2667    | 15        | 20.27%  |
| 3200    | 14        | 18.92%  |
| 2400    | 7         | 9.46%   |
| 4267    | 4         | 5.41%   |
| 2133    | 4         | 5.41%   |
| 8400    | 3         | 4.05%   |
| 3266    | 2         | 2.7%    |
| 1334    | 2         | 2.7%    |
| 1333    | 2         | 2.7%    |
| 4266    | 1         | 1.35%   |
| 1867    | 1         | 1.35%   |
| 800     | 1         | 1.35%   |
| 667     | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 2         | 40%     |
| Samsung Electronics             | 1         | 20%     |
| Prolific Technology             | 1         | 20%     |
| cab Produkttechnik GmbH & Co KG | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 1         | 20%     |
| Prolific PL2305 Parallel Port            | 1         | 20%     |
| Canon PIXMA MG2500 Series                | 1         | 20%     |
| Canon G3000 series                       | 1         | 20%     |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 76        | 21.71%  |
| IMC Networks                           | 43        | 12.29%  |
| Apple                                  | 33        | 9.43%   |
| Realtek Semiconductor                  | 30        | 8.57%   |
| Acer                                   | 29        | 8.29%   |
| Quanta                                 | 24        | 6.86%   |
| Microdia                               | 19        | 5.43%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 4.57%   |
| Suyin                                  | 14        | 4%      |
| Sunplus Innovation Technology          | 14        | 4%      |
| Syntek                                 | 9         | 2.57%   |
| Alcor Micro                            | 8         | 2.29%   |
| Silicon Motion                         | 6         | 1.71%   |
| Luxvisions Innotech Limited            | 4         | 1.14%   |
| Lenovo                                 | 4         | 1.14%   |
| Logitech                               | 3         | 0.86%   |
| Ricoh                                  | 2         | 0.57%   |
| Primax Electronics                     | 2         | 0.57%   |
| Lite-On Technology                     | 2         | 0.57%   |
| KYE Systems (Mouse Systems)            | 2         | 0.57%   |
| Foxconn / Hon Hai                      | 2         | 0.57%   |
| Y Media                                | 1         | 0.29%   |
| Unknown                                | 1         | 0.29%   |
| Sony                                   | 1         | 0.29%   |
| Samsung Electronics                    | 1         | 0.29%   |
| kingcome                               | 1         | 0.29%   |
| Importek                               | 1         | 0.29%   |
| Google                                 | 1         | 0.29%   |
| ALi                                    | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 22        | 6.25%   |
| IMC Networks USB2.0 HD UVC WebCam                | 13        | 3.69%   |
| IMC Networks Integrated Camera                   | 12        | 3.41%   |
| Apple Built-in iSight                            | 11        | 3.13%   |
| Chicony HD Webcam                                | 9         | 2.56%   |
| Microdia Integrated_Webcam_HD                    | 8         | 2.27%   |
| Apple FaceTime HD Camera                         | 8         | 2.27%   |
| Syntek Integrated Camera                         | 7         | 1.99%   |
| Realtek Integrated_Webcam_HD                     | 7         | 1.99%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 6         | 1.7%    |
| Sunplus Integrated_Webcam_HD                     | 5         | 1.42%   |
| Quanta HP TrueVision HD Camera                   | 5         | 1.42%   |
| Apple iPhone 5/5C/5S/6/SE                        | 5         | 1.42%   |
| Acer Integrated Camera                           | 5         | 1.42%   |
| Realtek USB2.0 HD UVC WebCam                     | 4         | 1.14%   |
| Realtek USB Camera                               | 4         | 1.14%   |
| Quanta VGA WebCam                                | 4         | 1.14%   |
| Quanta HP Webcam                                 | 4         | 1.14%   |
| Quanta HD User Facing                            | 4         | 1.14%   |
| Chicony USB 2.0 Camera                           | 4         | 1.14%   |
| Apple FaceTime Camera                            | 4         | 1.14%   |
| Acer Lenovo EasyCamera                           | 4         | 1.14%   |
| Acer HD Webcam                                   | 4         | 1.14%   |
| Realtek USB2.0 VGA UVC WebCam                    | 3         | 0.85%   |
| Realtek Integrated Webcam                        | 3         | 0.85%   |
| IMC Networks USB2.0 UVC HD Webcam                | 3         | 0.85%   |
| IMC Networks ov9734_azurewave_camera             | 3         | 0.85%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 0.85%   |
| Chicony HP Truevision HD                         | 3         | 0.85%   |
| Chicony HP HD Webcam [Fixed]                     | 3         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 3         | 0.85%   |
| Apple FaceTime HD Camera (Built-in)              | 3         | 0.85%   |
| Alcor Micro USB 2.0 WebCamera                    | 3         | 0.85%   |
| Acer HD Camera                                   | 3         | 0.85%   |
| Acer EasyCamera                                  | 3         | 0.85%   |
| Syntek EasyCamera                                | 2         | 0.57%   |
| Suyin Integrated_Webcam_HD                       | 2         | 0.57%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 2         | 0.57%   |
| Sunplus Asus Webcam                              | 2         | 0.57%   |
| Realtek Built-In Video Camera                    | 2         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 30%     |
| Synaptics                  | 17        | 28.33%  |
| Shenzhen Goodix Technology | 11        | 18.33%  |
| LighTuning Technology      | 6         | 10%     |
| Upek                       | 5         | 8.33%   |
| Elan Microelectronics      | 2         | 3.33%   |
| AuthenTec                  | 1         | 1.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 9         | 15%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 5         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 8.33%   |
| Unknown                                                    | 5         | 8.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 5%      |
| Validity Sensors VFS491                                    | 3         | 5%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 3.33%   |
| LighTuning EgisTec_ES603                                   | 2         | 3.33%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.67%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 1.67%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.67%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.67%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.67%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.67%   |
| Shenzhen Goodix FingerPrint                                | 1         | 1.67%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.67%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.67%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 9         | 47.37%  |
| Alcor Micro           | 5         | 26.32%  |
| O2 Micro              | 2         | 10.53%  |
| Lenovo                | 2         | 10.53%  |
| Gemalto (was Gemplus) | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 26.32%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 26.32%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 10.53%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10.53%  |
| Broadcom 58200                                                               | 2         | 10.53%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.26%   |
| Broadcom 5880                                                                | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 253       | 67.29%  |
| 1     | 98        | 26.06%  |
| 2     | 24        | 6.38%   |
| 3     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 59        | 40.14%  |
| Multimedia controller | 21        | 14.29%  |
| Net/wireless          | 19        | 12.93%  |
| Chipcard              | 19        | 12.93%  |
| Graphics card         | 13        | 8.84%   |
| Bluetooth             | 5         | 3.4%    |
| Camera                | 4         | 2.72%   |
| Net/ethernet          | 3         | 2.04%   |
| Card reader           | 3         | 2.04%   |
| Storage               | 1         | 0.68%   |

