Elementary 6.1 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6.1/Desktop/README.md) and [notebooks](/Dist/Elementary_6.1/Notebook/README.md).

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

Total: 742

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | HVY-WXX9                    | Notebook    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [d86c708401](https://linux-hardware.org/?probe=d86c708401) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Google        | Blooglet                    | Notebook    | [44a9c6559f](https://linux-hardware.org/?probe=44a9c6559f) | Sep 29, 2022 |
| Medion        | Akoya E6422 MD99680         | Notebook    | [52c1708200](https://linux-hardware.org/?probe=52c1708200) | Sep 28, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [18ee2cafd6](https://linux-hardware.org/?probe=18ee2cafd6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [ffc2811bfe](https://linux-hardware.org/?probe=ffc2811bfe) | Sep 27, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Dell          | Latitude E5450              | Notebook    | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [ff1dd51829](https://linux-hardware.org/?probe=ff1dd51829) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6a0c80f635](https://linux-hardware.org/?probe=6a0c80f635) | Sep 22, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [7cf2d6a810](https://linux-hardware.org/?probe=7cf2d6a810) | Sep 20, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [71339e0cfb](https://linux-hardware.org/?probe=71339e0cfb) | Sep 19, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [a0acb674df](https://linux-hardware.org/?probe=a0acb674df) | Sep 19, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [573e0dd8fd](https://linux-hardware.org/?probe=573e0dd8fd) | Sep 19, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [3f3cb3be79](https://linux-hardware.org/?probe=3f3cb3be79) | Sep 19, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [94baca564e](https://linux-hardware.org/?probe=94baca564e) | Sep 19, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [db48d27324](https://linux-hardware.org/?probe=db48d27324) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Clevo         | W54xEU                      | Notebook    | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7861fa17bf](https://linux-hardware.org/?probe=7861fa17bf) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c54a63e1a3](https://linux-hardware.org/?probe=c54a63e1a3) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [b5f851bd15](https://linux-hardware.org/?probe=b5f851bd15) | Sep 12, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [4673830cd8](https://linux-hardware.org/?probe=4673830cd8) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [6b1829aad1](https://linux-hardware.org/?probe=6b1829aad1) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [9ef29f2258](https://linux-hardware.org/?probe=9ef29f2258) | Sep 12, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [335a8a059b](https://linux-hardware.org/?probe=335a8a059b) | Sep 12, 2022 |
| HP            | ENVY m6                     | Notebook    | [b9de3b6e35](https://linux-hardware.org/?probe=b9de3b6e35) | Sep 11, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [3d269171e7](https://linux-hardware.org/?probe=3d269171e7) | Sep 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e2d13711aa](https://linux-hardware.org/?probe=e2d13711aa) | Sep 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | Notebook    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [1d9611ecf1](https://linux-hardware.org/?probe=1d9611ecf1) | Sep 09, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [d2ad94ce21](https://linux-hardware.org/?probe=d2ad94ce21) | Sep 09, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [47708e7772](https://linux-hardware.org/?probe=47708e7772) | Sep 09, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [c5d5b88740](https://linux-hardware.org/?probe=c5d5b88740) | Sep 09, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [5001a76a0e](https://linux-hardware.org/?probe=5001a76a0e) | Sep 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [3932661b8e](https://linux-hardware.org/?probe=3932661b8e) | Sep 07, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [ae533c2bdf](https://linux-hardware.org/?probe=ae533c2bdf) | Sep 07, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [29b2041a5b](https://linux-hardware.org/?probe=29b2041a5b) | Sep 05, 2022 |
| Acer          | Aspire V5-552               | Notebook    | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [b37d844ab3](https://linux-hardware.org/?probe=b37d844ab3) | Sep 04, 2022 |
| TUXEDO        | Book XP14 Gen12             | Notebook    | [cfb0fb9451](https://linux-hardware.org/?probe=cfb0fb9451) | Sep 04, 2022 |
| Acer          | Aspire X1420G               | Desktop     | [e48b081560](https://linux-hardware.org/?probe=e48b081560) | Sep 04, 2022 |
| Timi          | TM1701                      | Notebook    | [f23c551375](https://linux-hardware.org/?probe=f23c551375) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [3a8803f198](https://linux-hardware.org/?probe=3a8803f198) | Sep 01, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [b6cc2513ff](https://linux-hardware.org/?probe=b6cc2513ff) | Aug 31, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [e8b26fc530](https://linux-hardware.org/?probe=e8b26fc530) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [f262848655](https://linux-hardware.org/?probe=f262848655) | Aug 30, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [7f66ca2cc7](https://linux-hardware.org/?probe=7f66ca2cc7) | Aug 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0da338038e](https://linux-hardware.org/?probe=0da338038e) | Aug 29, 2022 |
| Standard      | Unknown                     | Notebook    | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [155267063a](https://linux-hardware.org/?probe=155267063a) | Aug 28, 2022 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [0f71a52e11](https://linux-hardware.org/?probe=0f71a52e11) | Aug 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [0bf776cdc1](https://linux-hardware.org/?probe=0bf776cdc1) | Aug 28, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [68248e8ec4](https://linux-hardware.org/?probe=68248e8ec4) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Dell          | Latitude E7250              | Notebook    | [98f4886ef7](https://linux-hardware.org/?probe=98f4886ef7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | Notebook    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [9ffe8ee96e](https://linux-hardware.org/?probe=9ffe8ee96e) | Aug 24, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [4709584652](https://linux-hardware.org/?probe=4709584652) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [079a951d65](https://linux-hardware.org/?probe=079a951d65) | Aug 23, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [364b450a4f](https://linux-hardware.org/?probe=364b450a4f) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| ASUSTek       | K52F                        | Notebook    | [cafd25a659](https://linux-hardware.org/?probe=cafd25a659) | Aug 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [08d6e2e6e8](https://linux-hardware.org/?probe=08d6e2e6e8) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| HP            | 805D                        | Desktop     | [6748d722e7](https://linux-hardware.org/?probe=6748d722e7) | Aug 19, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f8675baa98](https://linux-hardware.org/?probe=f8675baa98) | Aug 18, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | Notebook    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [59456f2a25](https://linux-hardware.org/?probe=59456f2a25) | Aug 16, 2022 |
| HP            | 2AF7                        | Desktop     | [ca8820daa4](https://linux-hardware.org/?probe=ca8820daa4) | Aug 16, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [fb8a250b12](https://linux-hardware.org/?probe=fb8a250b12) | Aug 15, 2022 |
| ASUSTek       | P5B                         | Desktop     | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| Acer          | Aspire V5-552G              | Notebook    | [f51f3093d9](https://linux-hardware.org/?probe=f51f3093d9) | Aug 12, 2022 |
| ASUSTek       | K43E                        | Notebook    | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Dell          | Latitude D630               | Notebook    | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [0f4b093f48](https://linux-hardware.org/?probe=0f4b093f48) | Aug 07, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f06bb8d9ab](https://linux-hardware.org/?probe=f06bb8d9ab) | Aug 07, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9c47c2e4f4](https://linux-hardware.org/?probe=9c47c2e4f4) | Aug 07, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [ba73d094e7](https://linux-hardware.org/?probe=ba73d094e7) | Aug 06, 2022 |
| Sony          | SVS15117FLB                 | Notebook    | [2729210175](https://linux-hardware.org/?probe=2729210175) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | Notebook    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| MSI           | Creator 15 A10SET           | Notebook    | [45d9d06fb8](https://linux-hardware.org/?probe=45d9d06fb8) | Aug 05, 2022 |
| Medion        | Akoya E6422 MD99680         | Notebook    | [86cd2f6a0a](https://linux-hardware.org/?probe=86cd2f6a0a) | Aug 05, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [fc8e3b6a3b](https://linux-hardware.org/?probe=fc8e3b6a3b) | Aug 05, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [73488d7a09](https://linux-hardware.org/?probe=73488d7a09) | Aug 05, 2022 |
| Sony          | SVS15117FLB                 | Notebook    | [1f64d30f2f](https://linux-hardware.org/?probe=1f64d30f2f) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [7a0956e5f8](https://linux-hardware.org/?probe=7a0956e5f8) | Aug 04, 2022 |
| ASUSTek       | K43E                        | Notebook    | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| Dell          | Latitude E6400              | Notebook    | [54db9ae43d](https://linux-hardware.org/?probe=54db9ae43d) | Aug 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [b921b586f6](https://linux-hardware.org/?probe=b921b586f6) | Aug 02, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [e430a435bf](https://linux-hardware.org/?probe=e430a435bf) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [4a6d0213a4](https://linux-hardware.org/?probe=4a6d0213a4) | Aug 02, 2022 |
| Acer          | Aspire X1420G               | Desktop     | [7be7ab2e7e](https://linux-hardware.org/?probe=7be7ab2e7e) | Jul 31, 2022 |
| Dell          | Latitude E6320              | Notebook    | [34270898c6](https://linux-hardware.org/?probe=34270898c6) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [04487d99ff](https://linux-hardware.org/?probe=04487d99ff) | Jul 30, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Dell          | Latitude D630               | Notebook    | [37250474ae](https://linux-hardware.org/?probe=37250474ae) | Jul 29, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [dca4c898f8](https://linux-hardware.org/?probe=dca4c898f8) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | Notebook    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e99805635f](https://linux-hardware.org/?probe=e99805635f) | Jul 29, 2022 |
| ASUSTek       | K43E                        | Notebook    | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| Dell          | Latitude D630               | Notebook    | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [ab8af10726](https://linux-hardware.org/?probe=ab8af10726) | Jul 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [a5b77aa0e9](https://linux-hardware.org/?probe=a5b77aa0e9) | Jul 28, 2022 |
| Dell          | Latitude 3190               | Notebook    | [36027c80d2](https://linux-hardware.org/?probe=36027c80d2) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [d9a5e0b7e6](https://linux-hardware.org/?probe=d9a5e0b7e6) | Jul 27, 2022 |
| HP            | Pavilion g4                 | Notebook    | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f4026901c2](https://linux-hardware.org/?probe=f4026901c2) | Jul 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d0a69fba02](https://linux-hardware.org/?probe=d0a69fba02) | Jul 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [ae809bb317](https://linux-hardware.org/?probe=ae809bb317) | Jul 19, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | Notebook    | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | Notebook    | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [4cc1f4384c](https://linux-hardware.org/?probe=4cc1f4384c) | Jul 12, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [b1c5cb2096](https://linux-hardware.org/?probe=b1c5cb2096) | Jul 12, 2022 |
| Acer          | Aspire X1420G               | Desktop     | [0b7a9cbc2a](https://linux-hardware.org/?probe=0b7a9cbc2a) | Jul 12, 2022 |
| HP            | Notebook                    | Notebook    | [afaaed48c7](https://linux-hardware.org/?probe=afaaed48c7) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [1a880a89af](https://linux-hardware.org/?probe=1a880a89af) | Jul 09, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [3db9c636d0](https://linux-hardware.org/?probe=3db9c636d0) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [e4b17550d0](https://linux-hardware.org/?probe=e4b17550d0) | Jul 06, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [d07e96a623](https://linux-hardware.org/?probe=d07e96a623) | Jul 06, 2022 |
| HP            | Notebook                    | Notebook    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2919feb689](https://linux-hardware.org/?probe=2919feb689) | Jul 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2933dddc75](https://linux-hardware.org/?probe=2933dddc75) | Jul 04, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [3fcdd6c039](https://linux-hardware.org/?probe=3fcdd6c039) | Jul 03, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [7df8533350](https://linux-hardware.org/?probe=7df8533350) | Jul 03, 2022 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [654459e245](https://linux-hardware.org/?probe=654459e245) | Jul 03, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [88d34c06f3](https://linux-hardware.org/?probe=88d34c06f3) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [80a981f992](https://linux-hardware.org/?probe=80a981f992) | Jul 01, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [90c166f77b](https://linux-hardware.org/?probe=90c166f77b) | Jun 25, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | B85I                        | Desktop     | [886f971d22](https://linux-hardware.org/?probe=886f971d22) | Jun 25, 2022 |
| HP            | 339A                        | Desktop     | [822467af7f](https://linux-hardware.org/?probe=822467af7f) | Jun 25, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [ae3becae01](https://linux-hardware.org/?probe=ae3becae01) | Jun 24, 2022 |
| HP            | Pavilion g4                 | Notebook    | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [50e049e6fb](https://linux-hardware.org/?probe=50e049e6fb) | Jun 23, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [07506542b5](https://linux-hardware.org/?probe=07506542b5) | Jun 21, 2022 |
| Alienware     | m17 R3                      | Notebook    | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| Dell          | Latitude E5510              | Notebook    | [1f6cc92f98](https://linux-hardware.org/?probe=1f6cc92f98) | Jun 18, 2022 |
| T-bao         | MINI PC                     | Desktop     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [31b94c71c7](https://linux-hardware.org/?probe=31b94c71c7) | Jun 16, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [39d04d1188](https://linux-hardware.org/?probe=39d04d1188) | Jun 16, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [8c8275099b](https://linux-hardware.org/?probe=8c8275099b) | Jun 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c1efcc5411](https://linux-hardware.org/?probe=c1efcc5411) | Jun 16, 2022 |
| Samsung       | Lumpy                       | Notebook    | [50dad22fb3](https://linux-hardware.org/?probe=50dad22fb3) | Jun 15, 2022 |
| ASUSTek       | GR8                         | Notebook    | [3cdc341eda](https://linux-hardware.org/?probe=3cdc341eda) | Jun 15, 2022 |
| Samsung       | Lumpy                       | Notebook    | [4137bf9757](https://linux-hardware.org/?probe=4137bf9757) | Jun 14, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [5b8ae292bf](https://linux-hardware.org/?probe=5b8ae292bf) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [83cac56441](https://linux-hardware.org/?probe=83cac56441) | Jun 13, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [4cc4a7c1b3](https://linux-hardware.org/?probe=4cc4a7c1b3) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [25a8936801](https://linux-hardware.org/?probe=25a8936801) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [0ec841e188](https://linux-hardware.org/?probe=0ec841e188) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [5768dfe23f](https://linux-hardware.org/?probe=5768dfe23f) | Jun 11, 2022 |
| HP            | 2B43                        | Desktop     | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c76f63fb68](https://linux-hardware.org/?probe=c76f63fb68) | Jun 10, 2022 |
| HP            | ProBook 4540s               | Notebook    | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| HP            | Notebook                    | Notebook    | [f07183fab5](https://linux-hardware.org/?probe=f07183fab5) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [9de74ba486](https://linux-hardware.org/?probe=9de74ba486) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb704f99ee](https://linux-hardware.org/?probe=eb704f99ee) | Jun 04, 2022 |
| MSI           | B85I                        | Desktop     | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| HP            | ProBook 4540s               | Notebook    | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [baa12d722c](https://linux-hardware.org/?probe=baa12d722c) | Jun 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| ASUSTek       | P5B                         | Desktop     | [845c2f114b](https://linux-hardware.org/?probe=845c2f114b) | May 31, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | Notebook    | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [fc581d0fb4](https://linux-hardware.org/?probe=fc581d0fb4) | May 26, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [94796b9e96](https://linux-hardware.org/?probe=94796b9e96) | May 26, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | Notebook    | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| MSI           | H97M-P35                    | Desktop     | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [8cd4fba0ca](https://linux-hardware.org/?probe=8cd4fba0ca) | May 22, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| AMI           | Intel                       | Notebook    | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | Notebook    | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| MSI           | B85I                        | Desktop     | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| Sony          | VPCEB23FM                   | Notebook    | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | Notebook    | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | Notebook    | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | Notebook    | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | K55A                        | Notebook    | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [4521ae6617](https://linux-hardware.org/?probe=4521ae6617) | May 14, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [513d1e2c73](https://linux-hardware.org/?probe=513d1e2c73) | May 14, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | Notebook    | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASRock        | X570 Extreme4               | Desktop     | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| eMachines     | E525                        | Notebook    | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [271a0aaed2](https://linux-hardware.org/?probe=271a0aaed2) | May 01, 2022 |
| ASUSTek       | X202E                       | Notebook    | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| HP            | 0B48h                       | Desktop     | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | Notebook    | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [317f2966c3](https://linux-hardware.org/?probe=317f2966c3) | Apr 25, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | Notebook    | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| AZW           | GTi                         | Desktop     | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | Desktop     | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | Notebook    | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [b720cd5fc5](https://linux-hardware.org/?probe=b720cd5fc5) | Apr 20, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | Notebook    | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | Desktop     | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | Notebook    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | Desktop     | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| Pegatron      | IPMH61P1                    | Desktop     | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| ASRock        | C226 WS                     | Desktop     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | Notebook    | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| HP            | Notebook                    | Notebook    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Dell          | Inspiron 5481               | Convertible | [e364cee660](https://linux-hardware.org/?probe=e364cee660) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | Notebook    | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | Notebook    | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | Notebook    | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [01f1ca7f9d](https://linux-hardware.org/?probe=01f1ca7f9d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d299b01a23](https://linux-hardware.org/?probe=d299b01a23) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1b9e12b8fb](https://linux-hardware.org/?probe=1b9e12b8fb) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | Notebook    | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | Notebook    | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | Notebook    | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| Sony          | SVP1321B4E                  | Notebook    | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b39b0fda2](https://linux-hardware.org/?probe=2b39b0fda2) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [78df63a35f](https://linux-hardware.org/?probe=78df63a35f) | Mar 20, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1268effe7d](https://linux-hardware.org/?probe=1268effe7d) | Mar 17, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [9eb7577acd](https://linux-hardware.org/?probe=9eb7577acd) | Mar 12, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| MSI           | B85I                        | Desktop     | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| Teclast       | F15S                        | Notebook    | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d55f23484e](https://linux-hardware.org/?probe=d55f23484e) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | Desktop     | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | Desktop     | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | Notebook    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| HP            | 1589                        | Desktop     | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| Acer          | Nitro AN517-52              | Notebook    | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [707b59278e](https://linux-hardware.org/?probe=707b59278e) | Mar 05, 2022 |
| HP            | 802E                        | Desktop     | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| HP            | 805D                        | Desktop     | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [1f32b0aa84](https://linux-hardware.org/?probe=1f32b0aa84) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [ef94f0dd4d](https://linux-hardware.org/?probe=ef94f0dd4d) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Intel         | DH61BE AAG14062-210         | Desktop     | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | Desktop     | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | Notebook    | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | Notebook    | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| MSI           | B85I                        | Desktop     | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Google        | Lulu                        | Notebook    | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| Sony          | SVE15115EN                  | Notebook    | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| BANGHO        | Suma 1025                   | Tablet      | [585ea8c657](https://linux-hardware.org/?probe=585ea8c657) | Feb 10, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| Timi          | TM1613                      | Notebook    | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| Dell          | Inspiron 5481               | Convertible | [1f266a5183](https://linux-hardware.org/?probe=1f266a5183) | Feb 08, 2022 |
| ECS           | H55H-M                      | Desktop     | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | Notebook    | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f7500c309c](https://linux-hardware.org/?probe=f7500c309c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HP            | 802E                        | Desktop     | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | Notebook    | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | 82A5                        | Mini pc     | [c47d9b3ae0](https://linux-hardware.org/?probe=c47d9b3ae0) | Feb 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| HP            | 339A                        | Desktop     | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | Notebook    | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| HP            | 805D                        | Desktop     | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Teclast       | X6 plus                     | Tablet      | [a84fba541b](https://linux-hardware.org/?probe=a84fba541b) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [124dcb4c34](https://linux-hardware.org/?probe=124dcb4c34) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [804f9dbb94](https://linux-hardware.org/?probe=804f9dbb94) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| FIRICH        | J1900                       | Desktop     | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| Dell          | Latitude E5400              | Notebook    | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | Notebook    | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | Desktop     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | Notebook    | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | Notebook    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [1172390e59](https://linux-hardware.org/?probe=1172390e59) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | Notebook    | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | Notebook    | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | Notebook    | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| HP            | 3397                        | Desktop     | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Wortmann      | 1220729_1470271             | Notebook    | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| HP            | 1589                        | Desktop     | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Dell          | Latitude 3580               | Notebook    | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [730558c6bd](https://linux-hardware.org/?probe=730558c6bd) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | Notebook    | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | Notebook    | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | Notebook    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [3371572aa9](https://linux-hardware.org/?probe=3371572aa9) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary_6.1/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.11.0-43-generic          | 112       | 18.86%  |
| 5.15.0-46-generic          | 55        | 9.26%   |
| 5.13.0-28-generic          | 54        | 9.09%   |
| 5.13.0-30-generic          | 40        | 6.73%   |
| 5.13.0-39-generic          | 35        | 5.89%   |
| 5.13.0-27-generic          | 35        | 5.89%   |
| 5.15.0-41-generic          | 26        | 4.38%   |
| 5.13.0-40-generic          | 25        | 4.21%   |
| 5.13.0-35-generic          | 23        | 3.87%   |
| 5.13.0-37-generic          | 19        | 3.2%    |
| 5.11.0-44-generic          | 18        | 3.03%   |
| 5.13.0-52-generic          | 16        | 2.69%   |
| 5.13.0-51-generic          | 16        | 2.69%   |
| 5.13.0-41-generic          | 14        | 2.36%   |
| 5.15.0-43-generic          | 13        | 2.19%   |
| 5.13.0-44-generic          | 13        | 2.19%   |
| 5.11.0-46-generic          | 12        | 2.02%   |
| 5.15.0-48-generic          | 10        | 1.68%   |
| 5.11.0-41-generic          | 10        | 1.68%   |
| 5.13.0-48-generic          | 9         | 1.52%   |
| 5.13.0-25-generic          | 4         | 0.67%   |
| 5.11.0-40-generic          | 3         | 0.51%   |
| 5.15.36-xanmod1            | 2         | 0.34%   |
| 6.0.0-060000rc7-generic    | 1         | 0.17%   |
| 5.8.0-50-generic           | 1         | 0.17%   |
| 5.4.0-122-generic          | 1         | 0.17%   |
| 5.4.0-1055-raspi           | 1         | 0.17%   |
| 5.19.4-surface             | 1         | 0.17%   |
| 5.19.3-051903-generic      | 1         | 0.17%   |
| 5.19.11-xanmod1            | 1         | 0.17%   |
| 5.19.0-8.2-liquorix-amd64  | 1         | 0.17%   |
| 5.18.3-051803-generic      | 1         | 0.17%   |
| 5.17.3-xanmod1             | 1         | 0.17%   |
| 5.16.16-051616-generic     | 1         | 0.17%   |
| 5.16.11-surface            | 1         | 0.17%   |
| 5.16.10-051610-generic     | 1         | 0.17%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.17%   |
| 5.15.6-surface             | 1         | 0.17%   |
| 5.15.5-051505-generic      | 1         | 0.17%   |
| 5.15.3-xanmod1             | 1         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 281       | 49.73%  |
| 5.11.0  | 155       | 27.43%  |
| 5.15.0  | 101       | 17.88%  |
| 5.14.0  | 3         | 0.53%   |
| 5.4.0   | 2         | 0.35%   |
| 5.15.36 | 2         | 0.35%   |
| 6.0.0   | 1         | 0.18%   |
| 5.8.0   | 1         | 0.18%   |
| 5.19.4  | 1         | 0.18%   |
| 5.19.3  | 1         | 0.18%   |
| 5.19.11 | 1         | 0.18%   |
| 5.19.0  | 1         | 0.18%   |
| 5.18.3  | 1         | 0.18%   |
| 5.17.3  | 1         | 0.18%   |
| 5.16.16 | 1         | 0.18%   |
| 5.16.11 | 1         | 0.18%   |
| 5.16.10 | 1         | 0.18%   |
| 5.16.0  | 1         | 0.18%   |
| 5.15.6  | 1         | 0.18%   |
| 5.15.5  | 1         | 0.18%   |
| 5.15.3  | 1         | 0.18%   |
| 5.15.21 | 1         | 0.18%   |
| 5.15.13 | 1         | 0.18%   |
| 5.15.12 | 1         | 0.18%   |
| 5.15.11 | 1         | 0.18%   |
| 5.15.10 | 1         | 0.18%   |
| 5.14.10 | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 281       | 49.82%  |
| 5.11    | 155       | 27.48%  |
| 5.15    | 111       | 19.68%  |
| 5.19    | 4         | 0.71%   |
| 5.14    | 4         | 0.71%   |
| 5.16    | 3         | 0.53%   |
| 5.4     | 2         | 0.35%   |
| 6.0     | 1         | 0.18%   |
| 5.8     | 1         | 0.18%   |
| 5.18    | 1         | 0.18%   |
| 5.17    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 548       | 99.82%  |
| aarch64 | 1         | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 546       | 99.45%  |
| KDE5     | 1         | 0.18%   |
| GNOME    | 1         | 0.18%   |
| Unknown  | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 549       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 444       | 80.43%  |
| LightDM | 105       | 19.02%  |
| GDM3    | 2         | 0.36%   |
| GDM     | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 243       | 44.1%   |
| de_DE   | 67        | 12.16%  |
| es_ES   | 45        | 8.17%   |
| ru_RU   | 27        | 4.9%    |
| fr_FR   | 27        | 4.9%    |
| en_GB   | 27        | 4.9%    |
| pt_BR   | 23        | 4.17%   |
| it_IT   | 21        | 3.81%   |
| pl_PL   | 11        | 2%      |
| nl_NL   | 9         | 1.63%   |
| tr_TR   | 6         | 1.09%   |
| en_CA   | 6         | 1.09%   |
| en_AU   | 6         | 1.09%   |
| pt_PT   | 5         | 0.91%   |
| zh_CN   | 3         | 0.54%   |
| de_CH   | 3         | 0.54%   |
| uk_UA   | 2         | 0.36%   |
| sv_SE   | 2         | 0.36%   |
| nb_NO   | 2         | 0.36%   |
| ja_JP   | 2         | 0.36%   |
| hu_HU   | 2         | 0.36%   |
| C       | 2         | 0.36%   |
| sr_RS   | 1         | 0.18%   |
| id_ID   | 1         | 0.18%   |
| hr_HR   | 1         | 0.18%   |
| fr_CA   | 1         | 0.18%   |
| fi_FI   | 1         | 0.18%   |
| et_EE   | 1         | 0.18%   |
| da_DK   | 1         | 0.18%   |
| cs_CZ   | 1         | 0.18%   |
| bg_BG   | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 372       | 67.15%  |
| BIOS | 182       | 32.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 531       | 96.72%  |
| Btrfs   | 11        | 2%      |
| Overlay | 5         | 0.91%   |
| Xfs     | 2         | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 470       | 85.3%   |
| GPT     | 71        | 12.89%  |
| MBR     | 10        | 1.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 529       | 96.01%  |
| Yes       | 22        | 3.99%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 513       | 93.27%  |
| Yes       | 37        | 6.73%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 87        | 15.85%  |
| Lenovo                  | 76        | 13.84%  |
| Hewlett-Packard         | 74        | 13.48%  |
| Apple                   | 64        | 11.66%  |
| Dell                    | 53        | 9.65%   |
| Acer                    | 30        | 5.46%   |
| MSI                     | 25        | 4.55%   |
| Gigabyte Technology     | 22        | 4.01%   |
| HUAWEI                  | 10        | 1.82%   |
| ASRock                  | 10        | 1.82%   |
| Sony                    | 9         | 1.64%   |
| Toshiba                 | 7         | 1.28%   |
| Samsung Electronics     | 7         | 1.28%   |
| Microsoft               | 7         | 1.28%   |
| Intel                   | 7         | 1.28%   |
| Biostar                 | 4         | 0.73%   |
| Teclast                 | 3         | 0.55%   |
| Notebook                | 3         | 0.55%   |
| Foxconn                 | 3         | 0.55%   |
| AMI                     | 3         | 0.55%   |
| Timi                    | 2         | 0.36%   |
| Star Labs               | 2         | 0.36%   |
| Pegatron                | 2         | 0.36%   |
| Packard Bell            | 2         | 0.36%   |
| Monster                 | 2         | 0.36%   |
| LG Electronics          | 2         | 0.36%   |
| Google                  | 2         | 0.36%   |
| Fujitsu                 | 2         | 0.36%   |
| ECS                     | 2         | 0.36%   |
| Unknown                 | 2         | 0.36%   |
| Wortmann AG             | 1         | 0.18%   |
| TUXEDO                  | 1         | 0.18%   |
| TrekStor                | 1         | 0.18%   |
| T-bao                   | 1         | 0.18%   |
| Standard                | 1         | 0.18%   |
| Razer                   | 1         | 0.18%   |
| Raspberry Pi Foundation | 1         | 0.18%   |
| PIPO                    | 1         | 0.18%   |
| Medion                  | 1         | 0.18%   |
| LORD ELECTRONICS        | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 4         | 0.73%   |
| Apple MacBookPro8,2                | 4         | 0.73%   |
| Apple MacBookAir6,2                | 4         | 0.73%   |
| Apple MacBook5,1                   | 4         | 0.73%   |
| HUAWEI MACHD-WXX9                  | 3         | 0.55%   |
| HP Notebook                        | 3         | 0.55%   |
| ASUS ZenBook UX425EA_UX425EA       | 3         | 0.55%   |
| ASUS X550CA                        | 3         | 0.55%   |
| Apple MacBookAir4,2                | 3         | 0.55%   |
| Apple MacBook4,1                   | 3         | 0.55%   |
| Apple iMac8,1                      | 3         | 0.55%   |
| Apple iMac7,1                      | 3         | 0.55%   |
| Unknown                            | 3         | 0.55%   |
| Timi TM1613                        | 2         | 0.36%   |
| MSI Prestige 15 A11UC              | 2         | 0.36%   |
| MSI MS-7C35                        | 2         | 0.36%   |
| Lenovo Legion Y540-15IRH 81SX      | 2         | 0.36%   |
| Lenovo IdeaPad 310-15IKB 80TV      | 2         | 0.36%   |
| HUAWEI NBLK-WAX9X                  | 2         | 0.36%   |
| HP ProBook 4540s                   | 2         | 0.36%   |
| HP Pavilion g6                     | 2         | 0.36%   |
| HP Pavilion g4                     | 2         | 0.36%   |
| HP Pavilion 17                     | 2         | 0.36%   |
| HP Laptop 15-db0xxx                | 2         | 0.36%   |
| HP ENVY x360 Convertible 13-ay0xxx | 2         | 0.36%   |
| HP EliteBook 8460p                 | 2         | 0.36%   |
| HP EliteBook 840 G1                | 2         | 0.36%   |
| HP Compaq Pro 6300 MT              | 2         | 0.36%   |
| Gigabyte Z390 UD                   | 2         | 0.36%   |
| Dell XPS 13 9343                   | 2         | 0.36%   |
| Dell Inspiron N5050                | 2         | 0.36%   |
| Dell Inspiron 5537                 | 2         | 0.36%   |
| Dell Inspiron 15-3567              | 2         | 0.36%   |
| ASUS TUF Gaming B550M-PLUS         | 2         | 0.36%   |
| Apple Macmini5,1                   | 2         | 0.36%   |
| Apple MacBookPro6,2                | 2         | 0.36%   |
| Apple MacBookPro5,5                | 2         | 0.36%   |
| Apple MacBookPro11,5               | 2         | 0.36%   |
| Apple MacBookAir7,2                | 2         | 0.36%   |
| Apple MacBookAir7,1                | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 34        | 6.19%   |
| Lenovo IdeaPad     | 21        | 3.83%   |
| Acer Aspire        | 20        | 3.64%   |
| Dell Inspiron      | 18        | 3.28%   |
| Dell Latitude      | 14        | 2.55%   |
| HP Pavilion        | 13        | 2.37%   |
| HP ProBook         | 10        | 1.82%   |
| HP EliteBook       | 10        | 1.82%   |
| ASUS VivoBook      | 9         | 1.64%   |
| Microsoft Surface  | 7         | 1.28%   |
| HP Laptop          | 7         | 1.28%   |
| ASUS ZenBook       | 7         | 1.28%   |
| ASUS PRIME         | 7         | 1.28%   |
| HP ENVY            | 6         | 1.09%   |
| Dell XPS           | 6         | 1.09%   |
| Dell OptiPlex      | 6         | 1.09%   |
| ASUS TUF           | 6         | 1.09%   |
| ASUS ROG           | 6         | 1.09%   |
| Apple MacBookPro8  | 6         | 1.09%   |
| Toshiba Satellite  | 5         | 0.91%   |
| Dell Precision     | 5         | 0.91%   |
| Apple MacBookAir6  | 5         | 0.91%   |
| Apple MacBook5     | 5         | 0.91%   |
| Acer Swift         | 5         | 0.91%   |
| Lenovo Legion      | 4         | 0.73%   |
| HP Compaq          | 4         | 0.73%   |
| Dell Vostro        | 4         | 0.73%   |
| ASUS All           | 4         | 0.73%   |
| Apple MacBookPro5  | 4         | 0.73%   |
| Apple MacBookPro11 | 4         | 0.73%   |
| Apple MacBookAir7  | 4         | 0.73%   |
| Lenovo ThinkCentre | 3         | 0.55%   |
| Lenovo ThinkBook   | 3         | 0.55%   |
| HUAWEI MACHD-WXX9  | 3         | 0.55%   |
| HP ProDesk         | 3         | 0.55%   |
| HP Notebook        | 3         | 0.55%   |
| ASUS X550CA        | 3         | 0.55%   |
| ASUS P8H61-M       | 3         | 0.55%   |
| Apple Macmini5     | 3         | 0.55%   |
| Apple MacBookAir4  | 3         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 63        | 11.48%  |
| 2018    | 50        | 9.11%   |
| 2019    | 49        | 8.93%   |
| 2012    | 49        | 8.93%   |
| 2021    | 43        | 7.83%   |
| 2015    | 41        | 7.47%   |
| 2013    | 41        | 7.47%   |
| 2011    | 38        | 6.92%   |
| 2016    | 33        | 6.01%   |
| 2010    | 33        | 6.01%   |
| 2014    | 30        | 5.46%   |
| 2017    | 28        | 5.1%    |
| 2009    | 21        | 3.83%   |
| 2008    | 16        | 2.91%   |
| 2022    | 6         | 1.09%   |
| 2007    | 5         | 0.91%   |
| 2006    | 2         | 0.36%   |
| Unknown | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 352       | 64.12%  |
| Desktop        | 143       | 26.05%  |
| All in one     | 17        | 3.1%    |
| Tablet         | 12        | 2.19%   |
| Mini pc        | 12        | 2.19%   |
| Convertible    | 11        | 2%      |
| System on chip | 1         | 0.18%   |
| Server         | 1         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 474       | 86.03%  |
| Enabled  | 77        | 13.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 544       | 99.09%  |
| Yes  | 5         | 0.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 161       | 29.11%  |
| 3.01-4.0    | 119       | 21.52%  |
| 16.01-24.0  | 100       | 18.08%  |
| 8.01-16.0   | 94        | 17%     |
| 32.01-64.0  | 47        | 8.5%    |
| 1.01-2.0    | 17        | 3.07%   |
| 64.01-256.0 | 7         | 1.27%   |
| 24.01-32.0  | 5         | 0.9%    |
| 2.01-3.0    | 3         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 220       | 37.54%  |
| 2.01-3.0   | 170       | 29.01%  |
| 3.01-4.0   | 92        | 15.7%   |
| 4.01-8.0   | 65        | 11.09%  |
| 0.51-1.0   | 20        | 3.41%   |
| 8.01-16.0  | 17        | 2.9%    |
| 24.01-32.0 | 1         | 0.17%   |
| 16.01-24.0 | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 352       | 63.54%  |
| 2      | 145       | 26.17%  |
| 3      | 29        | 5.23%   |
| 4      | 14        | 2.53%   |
| 5      | 6         | 1.08%   |
| 6      | 4         | 0.72%   |
| 7      | 2         | 0.36%   |
| 0      | 2         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 358       | 64.62%  |
| Yes       | 196       | 35.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 435       | 79.23%  |
| No        | 114       | 20.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 468       | 84.78%  |
| No        | 84        | 15.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 422       | 76.31%  |
| No        | 131       | 23.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 79        | 14.39%  |
| Germany         | 62        | 11.29%  |
| Brazil          | 32        | 5.83%   |
| UK              | 31        | 5.65%   |
| Russia          | 30        | 5.46%   |
| Italy           | 28        | 5.1%    |
| India           | 19        | 3.46%   |
| France          | 19        | 3.46%   |
| Spain           | 17        | 3.1%    |
| Indonesia       | 15        | 2.73%   |
| Canada          | 14        | 2.55%   |
| Australia       | 14        | 2.55%   |
| Turkey          | 13        | 2.37%   |
| Poland          | 13        | 2.37%   |
| Mexico          | 12        | 2.19%   |
| Switzerland     | 10        | 1.82%   |
| Netherlands     | 9         | 1.64%   |
| Belgium         | 9         | 1.64%   |
| Austria         | 9         | 1.64%   |
| Argentina       | 9         | 1.64%   |
| Chile           | 6         | 1.09%   |
| Portugal        | 5         | 0.91%   |
| New Zealand     | 5         | 0.91%   |
| Sweden          | 4         | 0.73%   |
| Romania         | 4         | 0.73%   |
| Norway          | 4         | 0.73%   |
| Japan           | 4         | 0.73%   |
| Czechia         | 4         | 0.73%   |
| Colombia        | 4         | 0.73%   |
| Ukraine         | 3         | 0.55%   |
| South Africa    | 3         | 0.55%   |
| Iran            | 3         | 0.55%   |
| Hungary         | 3         | 0.55%   |
| China           | 3         | 0.55%   |
| Belarus         | 3         | 0.55%   |
| Venezuela       | 2         | 0.36%   |
| Sri Lanka       | 2         | 0.36%   |
| Serbia          | 2         | 0.36%   |
| Pakistan        | 2         | 0.36%   |
| North Macedonia | 2         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Moscow                 | 11        | 1.93%   |
| Sydney                 | 9         | 1.58%   |
| Hamburg                | 7         | 1.23%   |
| Warsaw                 | 6         | 1.05%   |
| Munich                 | 6         | 1.05%   |
| Istanbul               | 5         | 0.88%   |
| Vienna                 | 4         | 0.7%    |
| The Hague              | 4         | 0.7%    |
| St Petersburg          | 4         | 0.7%    |
| Pozza di Fassa         | 4         | 0.7%    |
| Milan                  | 4         | 0.7%    |
| Caslano                | 4         | 0.7%    |
| Tangerang              | 3         | 0.53%   |
| Sao Paulo              | 3         | 0.53%   |
| Rome                   | 3         | 0.53%   |
| Paris                  | 3         | 0.53%   |
| Madrid                 | 3         | 0.53%   |
| Jakarta                | 3         | 0.53%   |
| Bogor                  | 3         | 0.53%   |
| Berlin                 | 3         | 0.53%   |
| Ankara                 | 3         | 0.53%   |
| Yuba City              | 2         | 0.35%   |
| Yaroslavl              | 2         | 0.35%   |
| Wroclaw                | 2         | 0.35%   |
| Wolgast                | 2         | 0.35%   |
| Tucson                 | 2         | 0.35%   |
| Toronto                | 2         | 0.35%   |
| Teresina               | 2         | 0.35%   |
| Tel Aviv               | 2         | 0.35%   |
| Tehran                 | 2         | 0.35%   |
| Santo André           | 2         | 0.35%   |
| San Antonio            | 2         | 0.35%   |
| Porto                  | 2         | 0.35%   |
| Nottingham             | 2         | 0.35%   |
| Nairobi                | 2         | 0.35%   |
| Muralto                | 2         | 0.35%   |
| Mumbai                 | 2         | 0.35%   |
| Monza                  | 2         | 0.35%   |
| Montornès del Vallès | 2         | 0.35%   |
| Minsk                  | 2         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 114       | 154    | 14.82%  |
| WDC                       | 91        | 124    | 11.83%  |
| Seagate                   | 90        | 109    | 11.7%   |
| Toshiba                   | 56        | 66     | 7.28%   |
| Kingston                  | 51        | 62     | 6.63%   |
| SanDisk                   | 41        | 45     | 5.33%   |
| Unknown                   | 31        | 42     | 4.03%   |
| Crucial                   | 31        | 37     | 4.03%   |
| Apple                     | 22        | 25     | 2.86%   |
| HGST                      | 20        | 21     | 2.6%    |
| SK hynix                  | 17        | 18     | 2.21%   |
| Intel                     | 16        | 18     | 2.08%   |
| Hitachi                   | 16        | 17     | 2.08%   |
| A-DATA Technology         | 15        | 15     | 1.95%   |
| Phison                    | 11        | 12     | 1.43%   |
| Micron Technology         | 9         | 11     | 1.17%   |
| PNY                       | 8         | 14     | 1.04%   |
| KIOXIA                    | 8         | 9      | 1.04%   |
| Micron/Crucial Technology | 6         | 9      | 0.78%   |
| China                     | 6         | 6      | 0.78%   |
| JMicron Technology        | 5         | 5      | 0.65%   |
| Unknown                   | 5         | 6      | 0.65%   |
| Silicon Motion            | 4         | 4      | 0.52%   |
| Fujitsu                   | 4         | 4      | 0.52%   |
| Transcend                 | 3         | 3      | 0.39%   |
| Team                      | 3         | 4      | 0.39%   |
| Realtek Semiconductor     | 3         | 3      | 0.39%   |
| OCZ                       | 3         | 5      | 0.39%   |
| Maxtor                    | 3         | 3      | 0.39%   |
| LITEON                    | 3         | 3      | 0.39%   |
| Leven                     | 3         | 3      | 0.39%   |
| Corsair                   | 3         | 3      | 0.39%   |
| ASMT                      | 3         | 3      | 0.39%   |
| XPG                       | 2         | 2      | 0.26%   |
| TO Exter                  | 2         | 2      | 0.26%   |
| Teclast                   | 2         | 2      | 0.26%   |
| SPCC                      | 2         | 2      | 0.26%   |
| Plextor                   | 2         | 3      | 0.26%   |
| Netac                     | 2         | 2      | 0.26%   |
| Lite-On                   | 2         | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB        | 11        | 1.34%   |
| Samsung NVMe SSD Drive 256GB        | 11        | 1.34%   |
| Kingston SA400S37240G 240GB SSD     | 11        | 1.34%   |
| Toshiba MQ01ABD100 1TB              | 10        | 1.22%   |
| Samsung NVMe SSD Drive 500GB        | 10        | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB      | 9         | 1.1%    |
| Unknown MMC Card  32GB              | 8         | 0.98%   |
| SK hynix NVMe SSD Drive 256GB       | 7         | 0.85%   |
| SanDisk NVMe SSD Drive 512GB        | 7         | 0.85%   |
| Samsung SSD 860 EVO 250GB           | 7         | 0.85%   |
| Kingston SA400S37120G 120GB SSD     | 7         | 0.85%   |
| Samsung SSD 850 EVO 250GB           | 6         | 0.73%   |
| Phison NVMe SSD Drive 1TB           | 6         | 0.73%   |
| Intel NVMe SSD Drive 512GB          | 6         | 0.73%   |
| Crucial CT240BX500SSD1 240GB        | 6         | 0.73%   |
| Toshiba MQ01ABF050 500GB            | 5         | 0.61%   |
| Toshiba DT01ACA050 500GB            | 5         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 0.61%   |
| Samsung NVMe SSD Drive 1TB          | 5         | 0.61%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 5         | 0.61%   |
| HGST HTS721010A9E630 1TB            | 5         | 0.61%   |
| HGST HTS545050A7E680 500GB          | 5         | 0.61%   |
| Unknown                             | 5         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 4         | 0.49%   |
| Unknown MMC Card  64GB              | 4         | 0.49%   |
| Toshiba NVMe SSD Drive 512GB        | 4         | 0.49%   |
| Toshiba MQ04ABF100 1TB              | 4         | 0.49%   |
| SK hynix NVMe SSD Drive 512GB       | 4         | 0.49%   |
| Seagate ST3500418AS 500GB           | 4         | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB      | 4         | 0.49%   |
| Samsung SSD 860 EVO 500GB           | 4         | 0.49%   |
| Samsung SSD 860 EVO 1TB             | 4         | 0.49%   |
| Samsung NVMe SSD Drive 1024GB       | 4         | 0.49%   |
| PNY CS900 480GB SSD                 | 4         | 0.49%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 4         | 0.49%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 0.49%   |
| Kingston NVMe SSD Drive 500GB       | 4         | 0.49%   |
| JMicron Tech 250GB                  | 4         | 0.49%   |
| HGST HTS541010B7E610 1TB            | 4         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 105    | 33.21%  |
| WDC                 | 72        | 94     | 27.48%  |
| Toshiba             | 43        | 52     | 16.41%  |
| HGST                | 20        | 21     | 7.63%   |
| Hitachi             | 16        | 17     | 6.11%   |
| Samsung Electronics | 8         | 9      | 3.05%   |
| Fujitsu             | 4         | 4      | 1.53%   |
| Apple               | 3         | 3      | 1.15%   |
| Unknown             | 2         | 2      | 0.76%   |
| Maxtor              | 2         | 2      | 0.76%   |
| ASMT                | 2         | 2      | 0.76%   |
| Hewlett-Packard     | 1         | 1      | 0.38%   |
| Generic-            | 1         | 1      | 0.38%   |
| Ext Hard            | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 80     | 21.33%  |
| Kingston            | 37        | 41     | 12.94%  |
| Crucial             | 30        | 35     | 10.49%  |
| SanDisk             | 24        | 27     | 8.39%   |
| Apple               | 18        | 19     | 6.29%   |
| WDC                 | 14        | 19     | 4.9%    |
| A-DATA Technology   | 12        | 12     | 4.2%    |
| PNY                 | 8         | 14     | 2.8%    |
| Micron Technology   | 6         | 7      | 2.1%    |
| Intel               | 6         | 6      | 2.1%    |
| China               | 6         | 6      | 2.1%    |
| Toshiba             | 5         | 5      | 1.75%   |
| Transcend           | 3         | 3      | 1.05%   |
| Team                | 3         | 4      | 1.05%   |
| OCZ                 | 3         | 5      | 1.05%   |
| LITEON              | 3         | 3      | 1.05%   |
| Corsair             | 3         | 3      | 1.05%   |
| TO Exter            | 2         | 2      | 0.7%    |
| Teclast             | 2         | 2      | 0.7%    |
| SPCC                | 2         | 2      | 0.7%    |
| Plextor             | 2         | 3      | 0.7%    |
| Leven               | 2         | 2      | 0.7%    |
| Intenso             | 2         | 2      | 0.7%    |
| GOODRAM             | 2         | 2      | 0.7%    |
| FORESEE             | 2         | 2      | 0.7%    |
| Dogfish             | 2         | 2      | 0.7%    |
| Apacer              | 2         | 2      | 0.7%    |
| tigo                | 1         | 1      | 0.35%   |
| Super Talent        | 1         | 1      | 0.35%   |
| Star                | 1         | 1      | 0.35%   |
| Smartbuy            | 1         | 1      | 0.35%   |
| SK hynix            | 1         | 1      | 0.35%   |
| Seagate             | 1         | 2      | 0.35%   |
| Pichau              | 1         | 1      | 0.35%   |
| Phison              | 1         | 2      | 0.35%   |
| Patriot             | 1         | 2      | 0.35%   |
| OCZ-VERTEX2         | 1         | 1      | 0.35%   |
| NGFF                | 1         | 1      | 0.35%   |
| Netac               | 1         | 1      | 0.35%   |
| MidasForce          | 1         | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 265       | 337    | 36.81%  |
| HDD     | 235       | 314    | 32.64%  |
| NVMe    | 165       | 210    | 22.92%  |
| MMC     | 30        | 34     | 4.17%   |
| Unknown | 25        | 36     | 3.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 419       | 646    | 64.86%  |
| NVMe | 164       | 208    | 25.39%  |
| SAS  | 33        | 43     | 5.11%   |
| MMC  | 30        | 34     | 4.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 326       | 437    | 67.63%  |
| 0.51-1.0   | 116       | 156    | 24.07%  |
| 1.01-2.0   | 22        | 31     | 4.56%   |
| 2.01-3.0   | 7         | 15     | 1.45%   |
| 4.01-10.0  | 6         | 7      | 1.24%   |
| 3.01-4.0   | 5         | 5      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 221       | 39.53%  |
| 251-500        | 137       | 24.51%  |
| 501-1000       | 88        | 15.74%  |
| 51-100         | 41        | 7.33%   |
| 1001-2000      | 32        | 5.72%   |
| 21-50          | 24        | 4.29%   |
| More than 3000 | 11        | 1.97%   |
| 2001-3000      | 3         | 0.54%   |
| 1-20           | 1         | 0.18%   |
| Unknown        | 1         | 0.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 264       | 45.6%   |
| 21-50          | 135       | 23.32%  |
| 51-100         | 63        | 10.88%  |
| 101-250        | 55        | 9.5%    |
| 251-500        | 29        | 5.01%   |
| 501-1000       | 19        | 3.28%   |
| 1001-2000      | 8         | 1.38%   |
| More than 3000 | 3         | 0.52%   |
| 2001-3000      | 2         | 0.35%   |
| Unknown        | 1         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB            | 1         | 1      | 7.69%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1      | 7.69%   |
| Toshiba KBG30ZPZ128G 128GB              | 1         | 1      | 7.69%   |
| Seagate ST500LM030-2E717D 500GB         | 1         | 1      | 7.69%   |
| Seagate ST3500312CS 500GB               | 1         | 1      | 7.69%   |
| SanDisk SSD PLUS 240GB                  | 1         | 1      | 7.69%   |
| Kingston SV300S37A240G 240GB SSD        | 1         | 1      | 7.69%   |
| Kingston SUV400S37480G 480GB SSD        | 1         | 1      | 7.69%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 7.69%   |
| HGST HTS721010A9E630 1TB                | 1         | 1      | 7.69%   |
| HGST HTS545050A7E680 500GB              | 1         | 1      | 7.69%   |
| Crucial CT512M550SSD3 512GB             | 1         | 1      | 7.69%   |
| Apple SSD SM256C 256GB                  | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 3         | 3      | 23.08%  |
| WDC      | 2         | 2      | 15.38%  |
| Seagate  | 2         | 2      | 15.38%  |
| HGST     | 2         | 2      | 15.38%  |
| Toshiba  | 1         | 1      | 7.69%   |
| SanDisk  | 1         | 1      | 7.69%   |
| Crucial  | 1         | 1      | 7.69%   |
| Apple    | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| HGST    | 2         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 6         | 6      | 46.15%  |
| HDD  | 6         | 6      | 46.15%  |
| NVMe | 1         | 1      | 7.69%   |

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
| Detected | 487       | 812    | 84.99%  |
| Works    | 73        | 106    | 12.74%  |
| Malfunc  | 13        | 13     | 2.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 369       | 55.66%  |
| AMD                            | 82        | 12.37%  |
| Samsung Electronics            | 61        | 9.2%    |
| SanDisk                        | 21        | 3.17%   |
| Nvidia                         | 21        | 3.17%   |
| Kingston Technology Company    | 17        | 2.56%   |
| SK hynix                       | 16        | 2.41%   |
| Phison Electronics             | 11        | 1.66%   |
| Marvell Technology Group       | 9         | 1.36%   |
| Toshiba America Info Systems   | 8         | 1.21%   |
| Micron/Crucial Technology      | 7         | 1.06%   |
| KIOXIA                         | 6         | 0.9%    |
| Realtek Semiconductor          | 5         | 0.75%   |
| ASMedia Technology             | 5         | 0.75%   |
| Silicon Motion                 | 4         | 0.6%    |
| Micron Technology              | 3         | 0.45%   |
| ADATA Technology               | 3         | 0.45%   |
| Seagate Technology             | 2         | 0.3%    |
| Lite-On Technology             | 2         | 0.3%    |
| JMicron Technology             | 2         | 0.3%    |
| Apple                          | 2         | 0.3%    |
| Yangtze Memory Technologies    | 1         | 0.15%   |
| Union Memory (Shenzhen)        | 1         | 0.15%   |
| Solid State Storage Technology | 1         | 0.15%   |
| Shenzhen Longsys Electronics   | 1         | 0.15%   |
| LSI Logic / Symbios Logic      | 1         | 0.15%   |
| Hewlett-Packard                | 1         | 0.15%   |
| Biwin Storage Technology       | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 66        | 8.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 33        | 4.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 31        | 4.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 30        | 4.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 22        | 3%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21        | 2.86%   |
| Samsung NVMe SSD Controller 980                                                         | 16        | 2.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 16        | 2.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 15        | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15        | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 14        | 1.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 1.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 11        | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 11        | 1.5%    |
| Nvidia MCP79 AHCI Controller                                                            | 10        | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 9         | 1.23%   |
| Intel SSD 660P Series                                                                   | 8         | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 1.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 8         | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7         | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 7         | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 0.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 0.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6         | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 0.82%   |
| Samsung Electronics SATA controller                                                     | 6         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 6         | 0.82%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 6         | 0.82%   |
| Kingston Company A2000 NVMe SSD                                                         | 6         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6         | 0.82%   |
| SK hynix Gold P31 SSD                                                                   | 5         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 418       | 62.3%   |
| NVMe | 162       | 24.14%  |
| IDE  | 57        | 8.49%   |
| RAID | 33        | 4.92%   |
| SAS  | 1         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 437       | 79.6%   |
| AMD    | 111       | 20.22%  |
| ARM    | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 2.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 0.91%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.91%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.91%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 0.91%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.73%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 0.73%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.73%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.73%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.73%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.73%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.73%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.55%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 3         | 0.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.55%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 3         | 0.55%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.55%   |
| Intel Core i5-4250U CPU @ 1.30GHz             | 3         | 0.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.55%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 3         | 0.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.55%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 3         | 0.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.55%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.55%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 123       | 22.4%   |
| Intel Core i7           | 115       | 20.95%  |
| Intel Core i3           | 55        | 10.02%  |
| Intel Celeron           | 35        | 6.38%   |
| Other                   | 33        | 6.01%   |
| AMD Ryzen 5             | 33        | 6.01%   |
| Intel Core 2 Duo        | 32        | 5.83%   |
| AMD Ryzen 7             | 21        | 3.83%   |
| Intel Xeon              | 12        | 2.19%   |
| Intel Pentium           | 12        | 2.19%   |
| AMD A10                 | 8         | 1.46%   |
| AMD Ryzen 9             | 6         | 1.09%   |
| AMD Ryzen 3             | 6         | 1.09%   |
| Intel Atom              | 5         | 0.91%   |
| AMD A8                  | 5         | 0.91%   |
| AMD Athlon II X2        | 4         | 0.73%   |
| AMD A6                  | 4         | 0.73%   |
| Intel Pentium Silver    | 3         | 0.55%   |
| Intel Pentium Dual-Core | 3         | 0.55%   |
| Intel Core 2 Quad       | 3         | 0.55%   |
| AMD Ryzen 7 PRO         | 3         | 0.55%   |
| AMD Phenom II X4        | 3         | 0.55%   |
| AMD FX                  | 3         | 0.55%   |
| AMD A12                 | 3         | 0.55%   |
| Intel Genuine           | 2         | 0.36%   |
| Intel Core i9           | 2         | 0.36%   |
| Intel Celeron Dual-Core | 2         | 0.36%   |
| AMD Athlon              | 2         | 0.36%   |
| AMD A4                  | 2         | 0.36%   |
| Intel Pentium Dual      | 1         | 0.18%   |
| Intel Core m5           | 1         | 0.18%   |
| Intel Core m3           | 1         | 0.18%   |
| Intel Core 2            | 1         | 0.18%   |
| AMD Ryzen 5 PRO         | 1         | 0.18%   |
| AMD E1                  | 1         | 0.18%   |
| AMD E                   | 1         | 0.18%   |
| AMD Athlon X4           | 1         | 0.18%   |
| AMD Athlon II X4        | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 259       | 47.01%  |
| 4      | 201       | 36.48%  |
| 8      | 39        | 7.08%   |
| 6      | 39        | 7.08%   |
| 12     | 6         | 1.09%   |
| 1      | 4         | 0.73%   |
| 16     | 2         | 0.36%   |
| 3      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 546       | 99.45%  |
| 2      | 3         | 0.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 385       | 70%     |
| 1      | 165       | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 548       | 99.82%  |
| 64-bit         | 1         | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 49        | 8.81%   |
| 0x306a9    | 41        | 7.37%   |
| Unknown    | 41        | 7.37%   |
| 0x306c3    | 24        | 4.32%   |
| 0x1067a    | 22        | 3.96%   |
| 0x806c1    | 20        | 3.6%    |
| 0x40651    | 19        | 3.42%   |
| 0x306d4    | 19        | 3.42%   |
| 0x806e9    | 15        | 2.7%    |
| 0x406e3    | 15        | 2.7%    |
| 0x20655    | 15        | 2.7%    |
| 0x806ec    | 13        | 2.34%   |
| 0x10676    | 12        | 2.16%   |
| 0x08108109 | 10        | 1.8%    |
| 0x906ea    | 9         | 1.62%   |
| 0x806ea    | 9         | 1.62%   |
| 0xa0652    | 8         | 1.44%   |
| 0x906e9    | 8         | 1.44%   |
| 0x706a8    | 8         | 1.44%   |
| 0x506e3    | 8         | 1.44%   |
| 0x08701021 | 8         | 1.44%   |
| 0x08600106 | 8         | 1.44%   |
| 0x706e5    | 7         | 1.26%   |
| 0x506c9    | 7         | 1.26%   |
| 0x20652    | 7         | 1.26%   |
| 0x806eb    | 6         | 1.08%   |
| 0x406c3    | 6         | 1.08%   |
| 0x30678    | 6         | 1.08%   |
| 0x06001119 | 6         | 1.08%   |
| 0x906ed    | 5         | 0.9%    |
| 0x706a1    | 5         | 0.9%    |
| 0x0a50000c | 5         | 0.9%    |
| 0x08608103 | 5         | 0.9%    |
| 0x08108102 | 5         | 0.9%    |
| 0x0800820d | 5         | 0.9%    |
| 0x06006705 | 5         | 0.9%    |
| 0x6fd      | 4         | 0.72%   |
| 0x406c4    | 4         | 0.72%   |
| 0x40661    | 4         | 0.72%   |
| 0x206d7    | 4         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 79        | 14.39%  |
| SandyBridge      | 55        | 10.02%  |
| Haswell          | 51        | 9.29%   |
| IvyBridge        | 43        | 7.83%   |
| Penryn           | 34        | 6.19%   |
| Zen 2            | 25        | 4.55%   |
| TigerLake        | 25        | 4.55%   |
| Skylake          | 24        | 4.37%   |
| Westmere         | 23        | 4.19%   |
| Zen+             | 22        | 4.01%   |
| Broadwell        | 20        | 3.64%   |
| Silvermont       | 17        | 3.1%    |
| Goldmont plus    | 14        | 2.55%   |
| CometLake        | 13        | 2.37%   |
| Excavator        | 12        | 2.19%   |
| Core             | 12        | 2.19%   |
| Icelake          | 11        | 2%      |
| Zen 3            | 10        | 1.82%   |
| Zen              | 9         | 1.64%   |
| Piledriver       | 8         | 1.46%   |
| K10              | 8         | 1.46%   |
| Goldmont         | 7         | 1.28%   |
| Unknown          | 7         | 1.28%   |
| Nehalem          | 5         | 0.91%   |
| Steamroller      | 3         | 0.55%   |
| Tremont          | 2         | 0.36%   |
| Puma             | 2         | 0.36%   |
| K10 Llano        | 2         | 0.36%   |
| Jaguar           | 2         | 0.36%   |
| Bulldozer        | 1         | 0.18%   |
| Bonnell          | 1         | 0.18%   |
| Bobcat           | 1         | 0.18%   |
| Alderlake Hybrid | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 346       | 53.15%  |
| AMD                        | 166       | 25.5%   |
| Nvidia                     | 138       | 21.2%   |
| Matrox Electronics Systems | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 46        | 6.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 4.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 3.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 2.37%   |
| Intel HD Graphics 5500                                                                   | 15        | 2.23%   |
| AMD Renoir                                                                               | 15        | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 2.23%   |
| Intel HD Graphics 620                                                                    | 13        | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.78%   |
| Intel UHD Graphics 620                                                                   | 11        | 1.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.34%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.34%   |
| Nvidia C79 [GeForce 9400M]                                                               | 8         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.89%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.89%   |
| AMD Lucienne                                                                             | 6         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.74%   |
| Intel HD Graphics 630                                                                    | 5         | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.74%   |
| AMD Cezanne                                                                              | 5         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.59%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.59%   |
| Intel HD Graphics 530                                                                    | 4         | 0.59%   |
| Intel HD Graphics 500                                                                    | 4         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 248       | 45.01%  |
| 1 x AMD        | 123       | 22.32%  |
| 1 x Nvidia     | 66        | 11.98%  |
| Intel + Nvidia | 66        | 11.98%  |
| Intel + AMD    | 26        | 4.72%   |
| 2 x AMD        | 13        | 2.36%   |
| AMD + Nvidia   | 4         | 0.73%   |
| Other          | 2         | 0.36%   |
| 2 x Nvidia     | 2         | 0.36%   |
| 1 x Matrox     | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 481       | 87.14%  |
| Proprietary | 67        | 12.14%  |
| Unknown     | 4         | 0.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 289       | 51.98%  |
| 0.01-0.5   | 73        | 13.13%  |
| 1.01-2.0   | 72        | 12.95%  |
| 0.51-1.0   | 53        | 9.53%   |
| 3.01-4.0   | 35        | 6.29%   |
| 5.01-6.0   | 14        | 2.52%   |
| 7.01-8.0   | 13        | 2.34%   |
| 2.01-3.0   | 4         | 0.72%   |
| 8.01-16.0  | 3         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 72        | 11.69%  |
| LG Display              | 64        | 10.39%  |
| Samsung Electronics     | 62        | 10.06%  |
| Apple                   | 60        | 9.74%   |
| BOE                     | 53        | 8.6%    |
| Chimei Innolux          | 51        | 8.28%   |
| Dell                    | 25        | 4.06%   |
| Goldstar                | 23        | 3.73%   |
| Hewlett-Packard         | 22        | 3.57%   |
| Acer                    | 19        | 3.08%   |
| Lenovo                  | 16        | 2.6%    |
| Sharp                   | 15        | 2.44%   |
| AOC                     | 13        | 2.11%   |
| Philips                 | 12        | 1.95%   |
| Chi Mei Optoelectronics | 9         | 1.46%   |
| BenQ                    | 9         | 1.46%   |
| PANDA                   | 8         | 1.3%    |
| Ancor Communications    | 8         | 1.3%    |
| InfoVision              | 6         | 0.97%   |
| Sony                    | 5         | 0.81%   |
| CSO                     | 4         | 0.65%   |
| ViewSonic               | 3         | 0.49%   |
| Unknown                 | 3         | 0.49%   |
| NEC Computers           | 3         | 0.49%   |
| LG Electronics          | 3         | 0.49%   |
| Eizo                    | 3         | 0.49%   |
| AUS                     | 3         | 0.49%   |
| Vizio                   | 2         | 0.32%   |
| Panasonic               | 2         | 0.32%   |
| Onkyo                   | 2         | 0.32%   |
| Iiyama                  | 2         | 0.32%   |
| HPN                     | 2         | 0.32%   |
| Fujitsu Siemens         | 2         | 0.32%   |
| ___                     | 1         | 0.16%   |
| Vestel                  | 1         | 0.16%   |
| Toshiba                 | 1         | 0.16%   |
| TMX                     | 1         | 0.16%   |
| Tech Concepts           | 1         | 0.16%   |
| SPC                     | 1         | 0.16%   |
| SANYO                   | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.95%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.79%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 5         | 0.79%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 4         | 0.63%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.63%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.47%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.47%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.47%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.47%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.47%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 0.47%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.47%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 3         | 0.47%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 3         | 0.47%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                 | 3         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.32%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 2         | 0.32%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.32%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 2         | 0.32%   |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch             | 2         | 0.32%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.32%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.32%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2         | 0.32%   |
| Eizo EV2450 ENC2531 1920x1080 528x297mm 23.9-inch                     | 2         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 236       | 39.46%  |
| 1366x768 (WXGA)    | 136       | 22.74%  |
| 3840x2160 (4K)     | 33        | 5.52%   |
| 2560x1440 (QHD)    | 29        | 4.85%   |
| 1440x900 (WXGA+)   | 26        | 4.35%   |
| 1600x900 (HD+)     | 24        | 4.01%   |
| 1680x1050 (WSXGA+) | 23        | 3.85%   |
| 1280x800 (WXGA)    | 16        | 2.68%   |
| 1920x1200 (WUXGA)  | 12        | 2.01%   |
| 1280x1024 (SXGA)   | 9         | 1.51%   |
| 2880x1800          | 6         | 1%      |
| 1360x768           | 6         | 1%      |
| Unknown            | 5         | 0.84%   |
| 3840x1080          | 4         | 0.67%   |
| 3000x2000          | 4         | 0.67%   |
| 3440x1440          | 3         | 0.5%    |
| 2560x1080          | 3         | 0.5%    |
| 5120x1440          | 2         | 0.33%   |
| 3840x2400          | 2         | 0.33%   |
| 3200x1800 (QHD+)   | 2         | 0.33%   |
| 2736x1824          | 2         | 0.33%   |
| 2560x1600          | 2         | 0.33%   |
| 1920x540           | 2         | 0.33%   |
| 1920x1280          | 2         | 0.33%   |
| 7680x2160          | 1         | 0.17%   |
| 3840x1200          | 1         | 0.17%   |
| 3840x1100          | 1         | 0.17%   |
| 3072x1920          | 1         | 0.17%   |
| 2880x1920          | 1         | 0.17%   |
| 2496x1664          | 1         | 0.17%   |
| 1800x1200          | 1         | 0.17%   |
| 1400x1050          | 1         | 0.17%   |
| 1280x720 (HD)      | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 157       | 25.49%  |
| 13      | 87        | 14.12%  |
| 14      | 66        | 10.71%  |
| 24      | 36        | 5.84%   |
| 27      | 30        | 4.87%   |
| 23      | 30        | 4.87%   |
| 17      | 30        | 4.87%   |
| Unknown | 30        | 4.87%   |
| 21      | 22        | 3.57%   |
| 20      | 14        | 2.27%   |
| 11      | 14        | 2.27%   |
| 31      | 13        | 2.11%   |
| 22      | 13        | 2.11%   |
| 12      | 12        | 1.95%   |
| 18      | 10        | 1.62%   |
| 19      | 6         | 0.97%   |
| 34      | 5         | 0.81%   |
| 16      | 5         | 0.81%   |
| 72      | 4         | 0.65%   |
| 32      | 4         | 0.65%   |
| 84      | 3         | 0.49%   |
| 26      | 3         | 0.49%   |
| 25      | 3         | 0.49%   |
| 65      | 2         | 0.32%   |
| 52      | 2         | 0.32%   |
| 43      | 2         | 0.32%   |
| 33      | 2         | 0.32%   |
| 10      | 2         | 0.32%   |
| 60      | 1         | 0.16%   |
| 55      | 1         | 0.16%   |
| 49      | 1         | 0.16%   |
| 48      | 1         | 0.16%   |
| 47      | 1         | 0.16%   |
| 40      | 1         | 0.16%   |
| 37      | 1         | 0.16%   |
| 36      | 1         | 0.16%   |
| 28      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 257       | 42.55%  |
| 501-600     | 91        | 15.07%  |
| 201-300     | 81        | 13.41%  |
| 401-500     | 61        | 10.1%   |
| 351-400     | 34        | 5.63%   |
| Unknown     | 30        | 4.97%   |
| 601-700     | 18        | 2.98%   |
| 701-800     | 12        | 1.99%   |
| 1001-1500   | 9         | 1.49%   |
| 1501-2000   | 7         | 1.16%   |
| 801-900     | 2         | 0.33%   |
| 901-1000    | 2         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 418       | 74.38%  |
| 16/10   | 87        | 15.48%  |
| Unknown | 26        | 4.63%   |
| 3/2     | 14        | 2.49%   |
| 5/4     | 7         | 1.25%   |
| 21/9    | 6         | 1.07%   |
| 6/5     | 1         | 0.18%   |
| 4/3     | 1         | 0.18%   |
| 32/9    | 1         | 0.18%   |
| 3.40    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 156       | 25.66%  |
| 81-90          | 115       | 18.91%  |
| 201-250        | 74        | 12.17%  |
| 71-80          | 39        | 6.41%   |
| 301-350        | 31        | 5.1%    |
| Unknown        | 30        | 4.93%   |
| 151-200        | 26        | 4.28%   |
| 351-500        | 24        | 3.95%   |
| 251-300        | 21        | 3.45%   |
| 121-130        | 19        | 3.13%   |
| 51-60          | 15        | 2.47%   |
| More than 1000 | 14        | 2.3%    |
| 141-150        | 14        | 2.3%    |
| 61-70          | 10        | 1.64%   |
| 501-1000       | 7         | 1.15%   |
| 131-140        | 5         | 0.82%   |
| 111-120        | 4         | 0.66%   |
| 41-50          | 2         | 0.33%   |
| 91-100         | 2         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 180       | 29.95%  |
| 101-120       | 172       | 28.62%  |
| 51-100        | 151       | 25.12%  |
| 161-240       | 35        | 5.82%   |
| Unknown       | 30        | 4.99%   |
| More than 240 | 19        | 3.16%   |
| 1-50          | 14        | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 476       | 85.77%  |
| 2     | 66        | 11.89%  |
| 3     | 10        | 1.8%    |
| 0     | 2         | 0.36%   |
| 4     | 1         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 264       | 32.2%   |
| Intel                             | 242       | 29.51%  |
| Qualcomm Atheros                  | 96        | 11.71%  |
| Broadcom                          | 84        | 10.24%  |
| Nvidia                            | 18        | 2.2%    |
| Marvell Technology Group          | 18        | 2.2%    |
| Broadcom Limited                  | 18        | 2.2%    |
| Ralink Technology                 | 10        | 1.22%   |
| Ralink                            | 9         | 1.1%    |
| TP-Link                           | 8         | 0.98%   |
| Xiaomi                            | 5         | 0.61%   |
| Samsung Electronics               | 5         | 0.61%   |
| MediaTek                          | 4         | 0.49%   |
| OPPO Electronics                  | 3         | 0.37%   |
| Huawei Technologies               | 3         | 0.37%   |
| ASIX Electronics                  | 3         | 0.37%   |
| TRENDnet                          | 2         | 0.24%   |
| Sierra Wireless                   | 2         | 0.24%   |
| Linksys                           | 2         | 0.24%   |
| Lenovo                            | 2         | 0.24%   |
| Google                            | 2         | 0.24%   |
| Apple                             | 2         | 0.24%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.12%   |
| vivo                              | 1         | 0.12%   |
| Sitecom Europe                    | 1         | 0.12%   |
| Qualcomm Atheros Communications   | 1         | 0.12%   |
| Qualcomm                          | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.12%   |
| Motorola PCS                      | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| LG Electronics                    | 1         | 0.12%   |
| JMicron Technology                | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Fibocom                           | 1         | 0.12%   |
| Ericsson Business Mobile Networks | 1         | 0.12%   |
| D-Link System                     | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |
| AVM                               | 1         | 0.12%   |
| Aquantia                          | 1         | 0.12%   |
| AboCom Systems                    | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 166       | 17.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44        | 4.57%   |
| Intel Wi-Fi 6 AX200                                               | 23        | 2.39%   |
| Intel Wi-Fi 6 AX201                                               | 20        | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 1.97%   |
| Intel Wireless 8260                                               | 17        | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.35%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 12        | 1.25%   |
| Intel Wireless 7265                                               | 12        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.25%   |
| Nvidia MCP79 Ethernet                                             | 11        | 1.14%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 11        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 1.04%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 10        | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 10        | 1.04%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 10        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 0.93%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 9         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.93%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 9         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.83%   |
| Intel Wireless 7260                                               | 8         | 0.83%   |
| Intel I211 Gigabit Network Connection                             | 8         | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.73%   |
| Realtek 802.11ac NIC                                              | 7         | 0.73%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 0.73%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 7         | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 6         | 0.62%   |
| Intel Wireless 3165                                               | 6         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 198       | 40.08%  |
| Qualcomm Atheros                | 80        | 16.19%  |
| Realtek Semiconductor           | 76        | 15.38%  |
| Broadcom                        | 74        | 14.98%  |
| Broadcom Limited                | 17        | 3.44%   |
| Ralink Technology               | 10        | 2.02%   |
| Ralink                          | 9         | 1.82%   |
| TP-Link                         | 8         | 1.62%   |
| Marvell Technology Group        | 4         | 0.81%   |
| TRENDnet                        | 2         | 0.4%    |
| Sierra Wireless                 | 2         | 0.4%    |
| MediaTek                        | 2         | 0.4%    |
| Linksys                         | 2         | 0.4%    |
| Sitecom Europe                  | 1         | 0.2%    |
| Qualcomm Atheros Communications | 1         | 0.2%    |
| Qualcomm                        | 1         | 0.2%    |
| Microsoft                       | 1         | 0.2%    |
| LG Electronics                  | 1         | 0.2%    |
| Fibocom                         | 1         | 0.2%    |
| D-Link System                   | 1         | 0.2%    |
| D-Link                          | 1         | 0.2%    |
| AVM                             | 1         | 0.2%    |
| AboCom Systems                  | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 23        | 4.63%   |
| Intel Wi-Fi 6 AX201                                            | 20        | 4.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19        | 3.82%   |
| Intel Wireless 8260                                            | 17        | 3.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 3.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 2.62%   |
| Intel Wireless 8265 / 8275                                     | 13        | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 12        | 2.41%   |
| Intel Wireless 7265                                            | 12        | 2.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 2.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 11        | 2.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 2.01%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 10        | 2.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 2.01%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 10        | 2.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.81%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 9         | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.61%   |
| Intel Wireless 7260                                            | 8         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.41%   |
| Realtek 802.11ac NIC                                           | 7         | 1.41%   |
| Ralink MT7601U Wireless Adapter                                | 7         | 1.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 1.41%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 1.21%   |
| Intel Wireless 3165                                            | 6         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1.01%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.01%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.01%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 5         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 233       | 50.65%  |
| Intel                      | 106       | 23.04%  |
| Broadcom                   | 28        | 6.09%   |
| Qualcomm Atheros           | 27        | 5.87%   |
| Nvidia                     | 18        | 3.91%   |
| Marvell Technology Group   | 14        | 3.04%   |
| Xiaomi                     | 5         | 1.09%   |
| Samsung Electronics        | 5         | 1.09%   |
| OPPO Electronics           | 3         | 0.65%   |
| ASIX Electronics           | 3         | 0.65%   |
| MediaTek                   | 2         | 0.43%   |
| Lenovo                     | 2         | 0.43%   |
| Huawei Technologies        | 2         | 0.43%   |
| Google                     | 2         | 0.43%   |
| Broadcom Limited           | 2         | 0.43%   |
| Apple                      | 2         | 0.43%   |
| ZTE WCDMA Technologies MSM | 1         | 0.22%   |
| vivo                       | 1         | 0.22%   |
| Motorola PCS               | 1         | 0.22%   |
| JMicron Technology         | 1         | 0.22%   |
| Hewlett-Packard            | 1         | 0.22%   |
| Aquantia                   | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 166       | 35.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 44        | 9.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 4.1%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 13        | 2.81%   |
| Nvidia MCP79 Ethernet                                                          | 11        | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                              | 10        | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 1.94%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 9         | 1.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.73%   |
| Intel I211 Gigabit Network Connection                                          | 8         | 1.73%   |
| Intel Ethernet Controller I225-V                                               | 6         | 1.3%    |
| Intel Ethernet Connection I217-LM                                              | 6         | 1.3%    |
| Intel Ethernet Connection (2) I219-V                                           | 6         | 1.3%    |
| Nvidia MCP61 Ethernet                                                          | 5         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.08%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.86%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.86%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 0.86%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.65%   |
| OPPO RMX2117                                                                   | 3         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.65%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 3         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.43%   |
| MediaTek Nokia 5.1 Plus                                                        | 2         | 0.43%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.43%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.43%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 470       | 51.88%  |
| Ethernet | 433       | 47.79%  |
| Modem    | 2         | 0.22%   |
| Unknown  | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 366       | 66.79%  |
| Ethernet | 182       | 33.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 309       | 56.08%  |
| 1     | 222       | 40.29%  |
| 3     | 10        | 1.81%   |
| 0     | 9         | 1.63%   |
| 4     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 387       | 69.86%  |
| Yes  | 167       | 30.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 174       | 40.65%  |
| Apple                           | 65        | 15.19%  |
| Realtek Semiconductor           | 44        | 10.28%  |
| Qualcomm Atheros Communications | 26        | 6.07%   |
| Broadcom                        | 22        | 5.14%   |
| Cambridge Silicon Radio         | 19        | 4.44%   |
| Lite-On Technology              | 17        | 3.97%   |
| IMC Networks                    | 16        | 3.74%   |
| Foxconn / Hon Hai               | 12        | 2.8%    |
| Ralink                          | 6         | 1.4%    |
| Hewlett-Packard                 | 6         | 1.4%    |
| Marvell Semiconductor           | 5         | 1.17%   |
| Toshiba                         | 4         | 0.93%   |
| ASUSTek Computer                | 4         | 0.93%   |
| Realtek                         | 3         | 0.7%    |
| Dell                            | 3         | 0.7%    |
| Qcom                            | 1         | 0.23%   |
| Edimax Technology               | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 64        | 14.95%  |
| Intel AX201 Bluetooth                               | 38        | 8.88%   |
| Realtek Bluetooth Radio                             | 29        | 6.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 29        | 6.78%   |
| Apple Bluetooth Host Controller                     | 26        | 6.07%   |
| Intel AX200 Bluetooth                               | 22        | 5.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19        | 4.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 3.97%   |
| Apple Bluetooth USB Host Controller                 | 17        | 3.97%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 2.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 11        | 2.57%   |
| Apple Bluetooth HCI                                 | 11        | 2.57%   |
| Ralink RT3290 Bluetooth                             | 6         | 1.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.4%    |
| Intel AX210 Bluetooth                               | 6         | 1.4%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.17%   |
| IMC Networks Bluetooth Device                       | 5         | 1.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 1.17%   |
| Lite-On Bluetooth Device                            | 4         | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.93%   |
| IMC Networks Bluetooth Radio                        | 4         | 0.93%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.93%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.93%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.7%    |
| Realtek Bluetooth Radio                             | 3         | 0.7%    |
| Marvell Bluetooth and Wireless LAN Composite        | 3         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.47%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 0.47%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.47%   |
| IMC Networks Wireless_Device                        | 2         | 0.47%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 412       | 57.3%   |
| AMD                       | 150       | 20.86%  |
| Nvidia                    | 99        | 13.77%  |
| C-Media Electronics       | 14        | 1.95%   |
| Creative Labs             | 8         | 1.11%   |
| Logitech                  | 7         | 0.97%   |
| Texas Instruments         | 2         | 0.28%   |
| Realtek Semiconductor     | 2         | 0.28%   |
| Generalplus Technology    | 2         | 0.28%   |
| Focusrite-Novation        | 2         | 0.28%   |
| ESS Technology            | 2         | 0.28%   |
| Corsair                   | 2         | 0.28%   |
| Unknown                   | 1         | 0.14%   |
| SteelSeries ApS           | 1         | 0.14%   |
| Sennheiser Communications | 1         | 0.14%   |
| Razer USA                 | 1         | 0.14%   |
| No brand                  | 1         | 0.14%   |
| Native Instruments        | 1         | 0.14%   |
| Microsoft                 | 1         | 0.14%   |
| Micro Star International  | 1         | 0.14%   |
| GN Netcom                 | 1         | 0.14%   |
| Fry's Electronics         | 1         | 0.14%   |
| Edifier Technology        | 1         | 0.14%   |
| Dell                      | 1         | 0.14%   |
| Creative Technology       | 1         | 0.14%   |
| BEHRINGER International   | 1         | 0.14%   |
| ASUSTek Computer          | 1         | 0.14%   |
| Apple                     | 1         | 0.14%   |
| Anlya.cn                  | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 52        | 5.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 47        | 5.39%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 44        | 5.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 41        | 4.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 2.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 25        | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25        | 2.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 2.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 2.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 2.29%   |
| Intel Broadwell-U Audio Controller                                                                | 20        | 2.29%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 1.72%   |
| AMD FCH Azalia Controller                                                                         | 15        | 1.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 1.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 13        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 1.49%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 1.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 1.38%   |
| Nvidia MCP79 High Definition Audio                                                                | 11        | 1.26%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.15%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 10        | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 10        | 1.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 1.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 9         | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 7         | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 31.53%  |
| SK hynix            | 22        | 19.82%  |
| Micron Technology   | 14        | 12.61%  |
| Unknown             | 7         | 6.31%   |
| Kingston            | 7         | 6.31%   |
| A-DATA Technology   | 4         | 3.6%    |
| Unknown (ABCD)      | 3         | 2.7%    |
| G.Skill             | 3         | 2.7%    |
| Crucial             | 3         | 2.7%    |
| Corsair             | 3         | 2.7%    |
| Ramaxel Technology  | 2         | 1.8%    |
| Unknown (0x038A)    | 1         | 0.9%    |
| Transcend           | 1         | 0.9%    |
| SHARETRONIC         | 1         | 0.9%    |
| PNY                 | 1         | 0.9%    |
| Patriot             | 1         | 0.9%    |
| Hewlett-Packard     | 1         | 0.9%    |
| GSkill              | 1         | 0.9%    |
| Elpida              | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s     | 3         | 2.5%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 3         | 2.5%    |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s            | 3         | 2.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                | 3         | 2.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                | 2         | 1.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                | 2         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                | 2         | 1.67%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s             | 2         | 1.67%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s                | 2         | 1.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                            | 1         | 0.83%   |
| Unknown RAM Module 8192MB SODIMM DDR3                                | 1         | 0.83%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                         | 1         | 0.83%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                              | 1         | 0.83%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                            | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                       | 1         | 0.83%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s                   | 1         | 0.83%   |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s             | 1         | 0.83%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.83%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                    | 1         | 0.83%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.83%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.83%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB Chip DDR3 1600MT/s              | 1         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s                | 1         | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                 | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 0.83%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 0.83%   |
| SK hynix RAM HMP351S6AFR8C-S6 4096MB SODIMM DDR2 800MT/s             | 1         | 0.83%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s              | 1         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 0.83%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 0.83%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s               | 1         | 0.83%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s               | 1         | 0.83%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s               | 1         | 0.83%   |
| SK hynix RAM H9HCNNNFAMALTR-NEE 16384MB Row Of Chips LPDDR4 3733MT/s | 1         | 0.83%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s           | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 46        | 47.42%  |
| DDR3    | 34        | 35.05%  |
| LPDDR4  | 10        | 10.31%  |
| LPDDR3  | 3         | 3.09%   |
| DDR2    | 2         | 2.06%   |
| Unknown | 2         | 2.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 70.1%   |
| DIMM         | 19        | 19.59%  |
| Row Of Chips | 9         | 9.28%   |
| Chip         | 1         | 1.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 46        | 42.2%   |
| 4096  | 35        | 32.11%  |
| 16384 | 15        | 13.76%  |
| 2048  | 12        | 11.01%  |
| 32768 | 1         | 0.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 21        | 19.81%  |
| 2667    | 19        | 17.92%  |
| 3200    | 16        | 15.09%  |
| 2400    | 9         | 8.49%   |
| 1333    | 7         | 6.6%    |
| 2133    | 5         | 4.72%   |
| 4267    | 4         | 3.77%   |
| 1066    | 4         | 3.77%   |
| 8400    | 3         | 2.83%   |
| 3266    | 2         | 1.89%   |
| 1867    | 2         | 1.89%   |
| 1334    | 2         | 1.89%   |
| 4800    | 1         | 0.94%   |
| 4266    | 1         | 0.94%   |
| 3733    | 1         | 0.94%   |
| 3600    | 1         | 0.94%   |
| 2933    | 1         | 0.94%   |
| 2800    | 1         | 0.94%   |
| 2666    | 1         | 0.94%   |
| 2200    | 1         | 0.94%   |
| 1800    | 1         | 0.94%   |
| 800     | 1         | 0.94%   |
| 667     | 1         | 0.94%   |
| Unknown | 1         | 0.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 3         | 25%     |
| Samsung Electronics             | 2         | 16.67%  |
| Hewlett-Packard                 | 2         | 16.67%  |
| Brother Industries              | 2         | 16.67%  |
| Prolific Technology             | 1         | 8.33%   |
| Dymo-CoStar                     | 1         | 8.33%   |
| cab Produkttechnik GmbH & Co KG | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 2         | 16.67%  |
| Prolific PL2305 Parallel Port            | 1         | 8.33%   |
| HP OfficeJet 5200 series                 | 1         | 8.33%   |
| HP Ink Tank 110 series                   | 1         | 8.33%   |
| Dymo-CoStar LabelWriter 450              | 1         | 8.33%   |
| Canon PIXMA MG3600 Series                | 1         | 8.33%   |
| Canon PIXMA MG2500 Series                | 1         | 8.33%   |
| Canon G3000 series                       | 1         | 8.33%   |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 8.33%   |
| Brother MFC-L2750DW series               | 1         | 8.33%   |
| Brother MFC-J5335DW                      | 1         | 8.33%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 76        | 19.64%  |
| Apple                                  | 48        | 12.4%   |
| IMC Networks                           | 41        | 10.59%  |
| Realtek Semiconductor                  | 32        | 8.27%   |
| Quanta                                 | 25        | 6.46%   |
| Acer                                   | 25        | 6.46%   |
| Microdia                               | 24        | 6.2%    |
| Sunplus Innovation Technology          | 15        | 3.88%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.88%   |
| Suyin                                  | 13        | 3.36%   |
| Logitech                               | 12        | 3.1%    |
| Syntek                                 | 9         | 2.33%   |
| Alcor Micro                            | 9         | 2.33%   |
| Silicon Motion                         | 6         | 1.55%   |
| Microsoft                              | 5         | 1.29%   |
| Luxvisions Innotech Limited            | 4         | 1.03%   |
| Lenovo                                 | 4         | 1.03%   |
| Ricoh                                  | 2         | 0.52%   |
| Primax Electronics                     | 2         | 0.52%   |
| KYE Systems (Mouse Systems)            | 2         | 0.52%   |
| Foxconn / Hon Hai                      | 2         | 0.52%   |
| Z-Star Microelectronics                | 1         | 0.26%   |
| Y Media                                | 1         | 0.26%   |
| Unknown                                | 1         | 0.26%   |
| SunplusIT                              | 1         | 0.26%   |
| Sony                                   | 1         | 0.26%   |
| Samsung Electronics                    | 1         | 0.26%   |
| Razer USA                              | 1         | 0.26%   |
| Lite-On Technology                     | 1         | 0.26%   |
| kingcome                               | 1         | 0.26%   |
| Jieli Technology                       | 1         | 0.26%   |
| Importek                               | 1         | 0.26%   |
| Google                                 | 1         | 0.26%   |
| Generalplus Technology                 | 1         | 0.26%   |
| Cubeternet                             | 1         | 0.26%   |
| ANYKA                                  | 1         | 0.26%   |
| ALi                                    | 1         | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Apple Built-in iSight                | 22        | 5.61%   |
| Chicony Integrated Camera            | 18        | 4.59%   |
| IMC Networks Integrated Camera       | 13        | 3.32%   |
| IMC Networks USB2.0 HD UVC WebCam    | 11        | 2.81%   |
| Realtek Integrated_Webcam_HD         | 9         | 2.3%    |
| Chicony HD Webcam                    | 9         | 2.3%    |
| Syntek Integrated Camera             | 8         | 2.04%   |
| Microdia Integrated_Webcam_HD        | 8         | 2.04%   |
| Apple FaceTime HD Camera             | 8         | 2.04%   |
| Apple iPhone5/5C/5S/6                | 7         | 1.79%   |
| IMC Networks USB2.0 VGA UVC WebCam   | 6         | 1.53%   |
| Sunplus Integrated_Webcam_HD         | 5         | 1.28%   |
| Quanta HP TrueVision HD Camera       | 5         | 1.28%   |
| Chicony USB 2.0 Camera               | 5         | 1.28%   |
| Apple FaceTime HD Camera (Built-in)  | 5         | 1.28%   |
| Realtek USB2.0 HD UVC WebCam         | 4         | 1.02%   |
| Realtek USB Camera                   | 4         | 1.02%   |
| Quanta VGA WebCam                    | 4         | 1.02%   |
| Quanta HD User Facing                | 4         | 1.02%   |
| Apple FaceTime Camera                | 4         | 1.02%   |
| Acer Lenovo EasyCamera               | 4         | 1.02%   |
| Realtek USB2.0 VGA UVC WebCam        | 3         | 0.77%   |
| Realtek Integrated Webcam            | 3         | 0.77%   |
| Quanta HP Webcam                     | 3         | 0.77%   |
| IMC Networks USB2.0 UVC HD Webcam    | 3         | 0.77%   |
| Chicony HP Truevision HD             | 3         | 0.77%   |
| Chicony HP HD Webcam [Fixed]         | 3         | 0.77%   |
| Alcor Micro SHUNCCM2MP               | 3         | 0.77%   |
| Acer Integrated Camera               | 3         | 0.77%   |
| Acer HD Webcam                       | 3         | 0.77%   |
| Acer HD Camera                       | 3         | 0.77%   |
| Acer EasyCamera                      | 3         | 0.77%   |
| Suyin Integrated_Webcam_HD           | 2         | 0.51%   |
| Sunplus Laptop_Integrated_Webcam_HD  | 2         | 0.51%   |
| Sunplus ASUS USB2.0 Webcam           | 2         | 0.51%   |
| Realtek Built-In Video Camera        | 2         | 0.51%   |
| Realtek Acer 640 x 480 laptop camera | 2         | 0.51%   |
| Quanta HP Wide Vision HD Camera      | 2         | 0.51%   |
| Microsoft Rear LifeCam               | 2         | 0.51%   |
| Microsoft Front LifeCam              | 2         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 22        | 36.67%  |
| Validity Sensors           | 16        | 26.67%  |
| Shenzhen Goodix Technology | 8         | 13.33%  |
| LighTuning Technology      | 7         | 11.67%  |
| Upek                       | 5         | 8.33%   |
| Elan Microelectronics      | 2         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 9         | 15%     |
| Shenzhen Goodix  Fingerprint Device                        | 7         | 11.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 5%      |
| Validity Sensors VFS491                                    | 3         | 5%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 3.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 3.33%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.67%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 1.67%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.67%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.67%   |
| Synaptics  WBDI                                            | 1         | 1.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.67%   |
| Shenzhen Goodix FingerPrint                                | 1         | 1.67%   |
| LighTuning Fingerprint Sensor                              | 1         | 1.67%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.67%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 9         | 45%     |
| Alcor Micro           | 5         | 25%     |
| O2 Micro              | 2         | 10%     |
| Lenovo                | 2         | 10%     |
| Gemalto (was Gemplus) | 1         | 5%      |
| Chicony Electronics   | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 10%     |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10%     |
| Broadcom 58200                                                               | 2         | 10%     |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 5%      |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |
| Broadcom 5880                                                                | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 413       | 74.55%  |
| 1     | 111       | 20.04%  |
| 2     | 28        | 5.05%   |
| 4     | 1         | 0.18%   |
| 3     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 60        | 35.29%  |
| Net/wireless             | 30        | 17.65%  |
| Multimedia controller    | 22        | 12.94%  |
| Chipcard                 | 19        | 11.18%  |
| Graphics card            | 15        | 8.82%   |
| Bluetooth                | 8         | 4.71%   |
| Camera                   | 4         | 2.35%   |
| Card reader              | 3         | 1.76%   |
| Unassigned class         | 2         | 1.18%   |
| Sound                    | 2         | 1.18%   |
| Net/ethernet             | 2         | 1.18%   |
| Storage/ide              | 1         | 0.59%   |
| Storage                  | 1         | 0.59%   |
| Communication controller | 1         | 0.59%   |

