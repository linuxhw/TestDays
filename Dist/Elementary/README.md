Elementary - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Elementary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

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

Total: 1686

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
| Apple         | MacBookPro8,1               | Notebook    | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [f262848655](https://linux-hardware.org/?probe=f262848655) | Aug 30, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [7f66ca2cc7](https://linux-hardware.org/?probe=7f66ca2cc7) | Aug 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0da338038e](https://linux-hardware.org/?probe=0da338038e) | Aug 29, 2022 |
| Standard      | Unknown                     | Notebook    | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
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
| Gigabyte      | H81M-DS2                    | Desktop     | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [59456f2a25](https://linux-hardware.org/?probe=59456f2a25) | Aug 16, 2022 |
| HP            | 2AF7                        | Desktop     | [ca8820daa4](https://linux-hardware.org/?probe=ca8820daa4) | Aug 16, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [fb8a250b12](https://linux-hardware.org/?probe=fb8a250b12) | Aug 15, 2022 |
| ASUSTek       | P5B                         | Desktop     | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
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
| Sony          | VPCEB16FG                   | Notebook    | [6baf989163](https://linux-hardware.org/?probe=6baf989163) | Aug 06, 2022 |
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
| Dell          | 0GM819                      | Desktop     | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [ae809bb317](https://linux-hardware.org/?probe=ae809bb317) | Jul 19, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | Notebook    | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | Notebook    | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
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
| Lenovo        | V15-IIL 82C5                | Notebook    | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | Notebook    | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4d0e23962a](https://linux-hardware.org/?probe=4d0e23962a) | Jun 27, 2022 |
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
| Lenovo        | V15-IIL 82C5                | Notebook    | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
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
| ASUSTek       | P5KPL-VM/S                  | Desktop     | [66223d6ef0](https://linux-hardware.org/?probe=66223d6ef0) | May 25, 2022 |
| ASUSTek       | P5KPL-VM/S                  | Desktop     | [d44e9d6290](https://linux-hardware.org/?probe=d44e9d6290) | May 25, 2022 |
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
| HP            | ZBook 15                    | Notebook    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d7223d4b03](https://linux-hardware.org/?probe=d7223d4b03) | May 05, 2022 |
| ASRock        | X570 Extreme4               | Desktop     | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| eMachines     | E525                        | Notebook    | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
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
| Inventec      | D CLASS A02                 | Desktop     | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
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
| Dell          | Latitude 3550               | Notebook    | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Panasonic     | CF-31SBLJGDM                | Notebook    | [60a1068658](https://linux-hardware.org/?probe=60a1068658) | Apr 13, 2022 |
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
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| ASRock        | C226 WS                     | Desktop     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
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
| HP            | 18E7                        | Desktop     | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | Notebook    | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | Notebook    | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| LG Electro... | P1-JSUVT                    | Notebook    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | Notebook    | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
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
| Acer          | Swift SF314-52              | Notebook    | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
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
| Dell          | Latitude 3550               | Notebook    | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | Notebook    | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
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
| Dell          | 0HMX8D A01                  | Desktop     | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
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
| ASUSTek       | H81-PLUS                    | Desktop     | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
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
| ASUSTek       | K75VJ                       | Notebook    | [e0c07cf9d2](https://linux-hardware.org/?probe=e0c07cf9d2) | Feb 20, 2022 |
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
| ASUSTek       | PRIME B250-PRO              | Desktop     | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
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
| Intel         | NUC8BEB J72692-309          | Mini pc     | [85d07f0cc8](https://linux-hardware.org/?probe=85d07f0cc8) | Feb 03, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [f3e2292b52](https://linux-hardware.org/?probe=f3e2292b52) | Feb 03, 2022 |
| Panasonic     | CF-31SBLJGDM                | Notebook    | [488b80a942](https://linux-hardware.org/?probe=488b80a942) | Feb 03, 2022 |
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
| Dell          | XPS 15 9500                 | Notebook    | [ac78806c22](https://linux-hardware.org/?probe=ac78806c22) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [657fbc0f6d](https://linux-hardware.org/?probe=657fbc0f6d) | Jan 30, 2022 |
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
| HP            | Pavilion dv5                | Notebook    | [62a18fa26b](https://linux-hardware.org/?probe=62a18fa26b) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [804f9dbb94](https://linux-hardware.org/?probe=804f9dbb94) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [3aad8f46c6](https://linux-hardware.org/?probe=3aad8f46c6) | Jan 24, 2022 |
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
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| HP            | ProBook 4430s               | Notebook    | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | Desktop     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [d74dcddae6](https://linux-hardware.org/?probe=d74dcddae6) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| ASUSTek       | GL502VS                     | Notebook    | [feb64c0933](https://linux-hardware.org/?probe=feb64c0933) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [afe25bb395](https://linux-hardware.org/?probe=afe25bb395) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | Notebook    | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [172b005a76](https://linux-hardware.org/?probe=172b005a76) | Jan 07, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ab3973e74b](https://linux-hardware.org/?probe=ab3973e74b) | Jan 07, 2022 |
| Dell          | Latitude 5420               | Notebook    | [517adf10a8](https://linux-hardware.org/?probe=517adf10a8) | Jan 06, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | Notebook    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [a0a13869ab](https://linux-hardware.org/?probe=a0a13869ab) | Jan 05, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | Notebook    | [d52d9dc2bd](https://linux-hardware.org/?probe=d52d9dc2bd) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [1172390e59](https://linux-hardware.org/?probe=1172390e59) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | Notebook    | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | Notebook    | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | Notebook    | [b5d8962bbc](https://linux-hardware.org/?probe=b5d8962bbc) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
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
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fa46d4f41a](https://linux-hardware.org/?probe=fa46d4f41a) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [22fb358e03](https://linux-hardware.org/?probe=22fb358e03) | Dec 28, 2021 |
| Dell          | Latitude 3580               | Notebook    | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| ASRock        | Z590 Phantom Gaming 4/ac    | Desktop     | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [730558c6bd](https://linux-hardware.org/?probe=730558c6bd) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | Notebook    | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [82483b42e2](https://linux-hardware.org/?probe=82483b42e2) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [197a4e0280](https://linux-hardware.org/?probe=197a4e0280) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | Notebook    | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5627f53d66](https://linux-hardware.org/?probe=5627f53d66) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | Notebook    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [3371572aa9](https://linux-hardware.org/?probe=3371572aa9) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7b3efc8cd8](https://linux-hardware.org/?probe=7b3efc8cd8) | Dec 14, 2021 |
| Pegatron      | IPMH61P1                    | Desktop     | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a8abf45979](https://linux-hardware.org/?probe=a8abf45979) | Dec 13, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [40b1d83a44](https://linux-hardware.org/?probe=40b1d83a44) | Dec 11, 2021 |
| Star Labs     | StarBook                    | Notebook    | [e9414e6bc4](https://linux-hardware.org/?probe=e9414e6bc4) | Dec 09, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [31e281d91b](https://linux-hardware.org/?probe=31e281d91b) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [d32c954439](https://linux-hardware.org/?probe=d32c954439) | Dec 09, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| Dell          | 0MGK50 A02                  | Desktop     | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd20a94e3e](https://linux-hardware.org/?probe=cd20a94e3e) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fa1e8b87a6](https://linux-hardware.org/?probe=fa1e8b87a6) | Dec 08, 2021 |
| Google        | Cyan                        | Notebook    | [f49c895086](https://linux-hardware.org/?probe=f49c895086) | Dec 08, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Dell          | Latitude E5420              | Notebook    | [e9fdf365b6](https://linux-hardware.org/?probe=e9fdf365b6) | Dec 07, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [7cb1ebd6c9](https://linux-hardware.org/?probe=7cb1ebd6c9) | Dec 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [73f375d3ac](https://linux-hardware.org/?probe=73f375d3ac) | Dec 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ed493cd76f](https://linux-hardware.org/?probe=ed493cd76f) | Dec 05, 2021 |
| Acer          | Aspire X3990                | Desktop     | [e291d06394](https://linux-hardware.org/?probe=e291d06394) | Dec 05, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [970669192e](https://linux-hardware.org/?probe=970669192e) | Dec 05, 2021 |
| HP            | G62                         | Notebook    | [6e055d5b6b](https://linux-hardware.org/?probe=6e055d5b6b) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9143857ca7](https://linux-hardware.org/?probe=9143857ca7) | Dec 05, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [6b5bd7a6d3](https://linux-hardware.org/?probe=6b5bd7a6d3) | Dec 05, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [bc5923cefe](https://linux-hardware.org/?probe=bc5923cefe) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [f8ed9dbcf4](https://linux-hardware.org/?probe=f8ed9dbcf4) | Dec 04, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [3fd499b264](https://linux-hardware.org/?probe=3fd499b264) | Dec 04, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d58c199fda](https://linux-hardware.org/?probe=d58c199fda) | Dec 04, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [c9fe8f5431](https://linux-hardware.org/?probe=c9fe8f5431) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| HP            | 2B07                        | All in one  | [b6cf0a1651](https://linux-hardware.org/?probe=b6cf0a1651) | Dec 03, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Pegatron      | Benicia                     | Desktop     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [313d4d0bd8](https://linux-hardware.org/?probe=313d4d0bd8) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| HP            | 8653 A                      | Desktop     | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [0131556200](https://linux-hardware.org/?probe=0131556200) | Dec 01, 2021 |
| Samsung       | 550XDA                      | Notebook    | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [d13f27ae75](https://linux-hardware.org/?probe=d13f27ae75) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5052f33272](https://linux-hardware.org/?probe=5052f33272) | Nov 30, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| Google        | Kip                         | Notebook    | [958c198a17](https://linux-hardware.org/?probe=958c198a17) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4af62a6057](https://linux-hardware.org/?probe=4af62a6057) | Nov 29, 2021 |
| Biostar       | TH55XE                      | Desktop     | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [8b1d090289](https://linux-hardware.org/?probe=8b1d090289) | Nov 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP            | 1497                        | Desktop     | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| HP            | Pavilion dm4                | Notebook    | [e2c582f687](https://linux-hardware.org/?probe=e2c582f687) | Nov 28, 2021 |
| HP            | ProBook 4540s               | Notebook    | [b6762448da](https://linux-hardware.org/?probe=b6762448da) | Nov 28, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Acer          | Aspire X3990                | Desktop     | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| Notebook      | L140CU                      | Notebook    | [59021b2a31](https://linux-hardware.org/?probe=59021b2a31) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| Acer          | Iconia Tab W500             | Tablet      | [5984a91751](https://linux-hardware.org/?probe=5984a91751) | Nov 27, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [09a8a91f9e](https://linux-hardware.org/?probe=09a8a91f9e) | Nov 26, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [c8a72fc7e2](https://linux-hardware.org/?probe=c8a72fc7e2) | Nov 26, 2021 |
| HP            | 1825                        | Desktop     | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [0004bab911](https://linux-hardware.org/?probe=0004bab911) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [2ef4f4f273](https://linux-hardware.org/?probe=2ef4f4f273) | Nov 26, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [04dc1956ff](https://linux-hardware.org/?probe=04dc1956ff) | Nov 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| HP            | Pavilion dv7                | Notebook    | [073367afb1](https://linux-hardware.org/?probe=073367afb1) | Nov 25, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [94b3c73b50](https://linux-hardware.org/?probe=94b3c73b50) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [fe6a145b19](https://linux-hardware.org/?probe=fe6a145b19) | Nov 24, 2021 |
| Medion        | E7218                       | Notebook    | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [1bfd5fb612](https://linux-hardware.org/?probe=1bfd5fb612) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [4f694a8ba3](https://linux-hardware.org/?probe=4f694a8ba3) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar       | TA790GXE 128M               | Desktop     | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| MSI           | GF72 7RE                    | Notebook    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [e7e27b16de](https://linux-hardware.org/?probe=e7e27b16de) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | Notebook    | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP            | ProBook 4730s               | Notebook    | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| HP            | 0AECh D                     | Desktop     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Schenker      | X170KM-G                    | Notebook    | [79bb8af2a1](https://linux-hardware.org/?probe=79bb8af2a1) | Nov 19, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e49d63158f](https://linux-hardware.org/?probe=e49d63158f) | Nov 19, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [f965bf0bd8](https://linux-hardware.org/?probe=f965bf0bd8) | Nov 18, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [d998144d2e](https://linux-hardware.org/?probe=d998144d2e) | Nov 18, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [38d8d7827f](https://linux-hardware.org/?probe=38d8d7827f) | Nov 18, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [3369764322](https://linux-hardware.org/?probe=3369764322) | Nov 17, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [078e3be7c3](https://linux-hardware.org/?probe=078e3be7c3) | Nov 17, 2021 |
| HP            | Compaq 6710b (GB893EA#AB... | Notebook    | [47a6a7a44f](https://linux-hardware.org/?probe=47a6a7a44f) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [60fef7922d](https://linux-hardware.org/?probe=60fef7922d) | Nov 16, 2021 |
| Dell          | 0F2A20 A00                  | All in one  | [e98616633d](https://linux-hardware.org/?probe=e98616633d) | Nov 16, 2021 |
| Gigabyte      | EP43T-USB3                  | Desktop     | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [74e99a032e](https://linux-hardware.org/?probe=74e99a032e) | Nov 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [58edd5c8e6](https://linux-hardware.org/?probe=58edd5c8e6) | Nov 14, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock        | X570 Extreme4               | Desktop     | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | Notebook    | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [197f5e1565](https://linux-hardware.org/?probe=197f5e1565) | Nov 12, 2021 |
| Sony          | SVE15115EN                  | Notebook    | [03cbf5ac5a](https://linux-hardware.org/?probe=03cbf5ac5a) | Nov 11, 2021 |
| HP            | Laptop 17-by3xxx            | Notebook    | [beba4da01c](https://linux-hardware.org/?probe=beba4da01c) | Nov 09, 2021 |
| MSI           | 970A-G43                    | Desktop     | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| Dell          | 05R2TK A01                  | All in one  | [0b728f2263](https://linux-hardware.org/?probe=0b728f2263) | Nov 07, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [e43a236a2c](https://linux-hardware.org/?probe=e43a236a2c) | Nov 06, 2021 |
| Quanta        | TW9/SW9                     | Notebook    | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [66109af766](https://linux-hardware.org/?probe=66109af766) | Nov 05, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [28d4f5e427](https://linux-hardware.org/?probe=28d4f5e427) | Nov 04, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| ASUSTek       | K75VJ                       | Notebook    | [9c0bccf601](https://linux-hardware.org/?probe=9c0bccf601) | Nov 01, 2021 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [0db069b4f1](https://linux-hardware.org/?probe=0db069b4f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [2b68c16c68](https://linux-hardware.org/?probe=2b68c16c68) | Nov 01, 2021 |
| Dell          | Latitude E6410              | Notebook    | [ba51fc9216](https://linux-hardware.org/?probe=ba51fc9216) | Oct 30, 2021 |
| Dell          | 0KFKMF A00                  | All in one  | [81af87f00c](https://linux-hardware.org/?probe=81af87f00c) | Oct 29, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI           | 2A9Ch                       | Desktop     | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Lenovo        | ThinkPad X230 23259L3       | Notebook    | [801c1d8af3](https://linux-hardware.org/?probe=801c1d8af3) | Oct 27, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6461bfc243](https://linux-hardware.org/?probe=6461bfc243) | Oct 26, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a904daf48d](https://linux-hardware.org/?probe=a904daf48d) | Oct 26, 2021 |
| HP            | 84EE 1100                   | All in one  | [225f3ee57b](https://linux-hardware.org/?probe=225f3ee57b) | Oct 26, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [49aef5b72e](https://linux-hardware.org/?probe=49aef5b72e) | Oct 26, 2021 |
| HP            | ProBook 6460b               | Notebook    | [18f27d1f5c](https://linux-hardware.org/?probe=18f27d1f5c) | Oct 25, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| HP            | 158B                        | Desktop     | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [4ce4f8ba78](https://linux-hardware.org/?probe=4ce4f8ba78) | Oct 20, 2021 |
| Google        | Setzer                      | Notebook    | [e9536ccbfb](https://linux-hardware.org/?probe=e9536ccbfb) | Oct 19, 2021 |
| Google        | Setzer                      | Notebook    | [3ba49636ef](https://linux-hardware.org/?probe=3ba49636ef) | Oct 19, 2021 |
| HP            | 339A                        | Desktop     | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Lenovo        | ThinkPad E470 20H10052IG    | Notebook    | [1342d4ce00](https://linux-hardware.org/?probe=1342d4ce00) | Oct 15, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [dd3c7ef3e7](https://linux-hardware.org/?probe=dd3c7ef3e7) | Oct 14, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [c1c77cf91a](https://linux-hardware.org/?probe=c1c77cf91a) | Oct 14, 2021 |
| HP            | 2B42                        | All in one  | [42d66aed80](https://linux-hardware.org/?probe=42d66aed80) | Oct 14, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [c1224ad1ab](https://linux-hardware.org/?probe=c1224ad1ab) | Oct 11, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| HP            | ProBook 4530s               | Notebook    | [0a725a0b81](https://linux-hardware.org/?probe=0a725a0b81) | Oct 07, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [644b3b5b60](https://linux-hardware.org/?probe=644b3b5b60) | Oct 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle       | FS61                        | Desktop     | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Panasonic     | FZ-G1ASH39E3                | Tablet      | [06f11c0449](https://linux-hardware.org/?probe=06f11c0449) | Sep 30, 2021 |
| Panasonic     | FZ-G1ASH39E3                | Tablet      | [961d53afb6](https://linux-hardware.org/?probe=961d53afb6) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c28700cfda](https://linux-hardware.org/?probe=c28700cfda) | Sep 26, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [fbcf277174](https://linux-hardware.org/?probe=fbcf277174) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [59224ec754](https://linux-hardware.org/?probe=59224ec754) | Sep 26, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [25c8a26c00](https://linux-hardware.org/?probe=25c8a26c00) | Sep 24, 2021 |
| ASRock        | M3A790GXH/128M              | Desktop     | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Toshiba       | Satellite C870-1H2          | Notebook    | [73615204f8](https://linux-hardware.org/?probe=73615204f8) | Sep 23, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c1b8f22fa6](https://linux-hardware.org/?probe=c1b8f22fa6) | Sep 22, 2021 |
| Intel         | X79 V1.x                    | Desktop     | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Dell          | Precision M4800             | Notebook    | [736b482dc3](https://linux-hardware.org/?probe=736b482dc3) | Sep 22, 2021 |
| Gigabyte      | H67A-USB3-B3                | Desktop     | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| eMachines     | G525                        | Notebook    | [8e8d037369](https://linux-hardware.org/?probe=8e8d037369) | Sep 21, 2021 |
| ASUSTek       | M4N78-AM                    | Desktop     | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Lenovo        | ThinkPad W700 2758MVG       | Notebook    | [66c8ecbaa1](https://linux-hardware.org/?probe=66c8ecbaa1) | Sep 20, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [0e44f5011a](https://linux-hardware.org/?probe=0e44f5011a) | Sep 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | Notebook    | [2bec640695](https://linux-hardware.org/?probe=2bec640695) | Sep 20, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d2511347b4](https://linux-hardware.org/?probe=d2511347b4) | Sep 19, 2021 |
| HP            | ENVY 15                     | Notebook    | [ba9a8e1d7a](https://linux-hardware.org/?probe=ba9a8e1d7a) | Sep 19, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 549       | 43.43%  |
| Elementary 6     | 233       | 18.43%  |
| Elementary 5.1.7 | 227       | 17.96%  |
| Elementary 5.0   | 55        | 4.35%   |
| Elementary 5.1   | 46        | 3.64%   |
| Elementary 5.1.6 | 35        | 2.77%   |
| Elementary 5.1.4 | 33        | 2.61%   |
| Elementary 5.1.2 | 29        | 2.29%   |
| Elementary 5.1.3 | 23        | 1.82%   |
| Elementary 0.4.1 | 16        | 1.27%   |
| Elementary 5.1.5 | 11        | 0.87%   |
| Elementary 6.0   | 7         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 1214      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-43-generic | 112       | 8.31%   |
| 5.11.0-40-generic | 56        | 4.15%   |
| 5.15.0-46-generic | 55        | 4.08%   |
| 5.13.0-28-generic | 54        | 4.01%   |
| 5.11.0-41-generic | 52        | 3.86%   |
| 5.13.0-30-generic | 40        | 2.97%   |
| 5.11.0-27-generic | 40        | 2.97%   |
| 5.13.0-39-generic | 35        | 2.6%    |
| 5.13.0-27-generic | 35        | 2.6%    |
| 5.4.0-42-generic  | 32        | 2.37%   |
| 5.11.0-38-generic | 27        | 2%      |
| 5.15.0-41-generic | 26        | 1.93%   |
| 5.13.0-40-generic | 25        | 1.85%   |
| 5.11.0-37-generic | 25        | 1.85%   |
| 5.0.0-37-generic  | 25        | 1.85%   |
| 5.13.0-35-generic | 23        | 1.71%   |
| 5.3.0-62-generic  | 21        | 1.56%   |
| 5.13.0-37-generic | 19        | 1.41%   |
| 5.11.0-44-generic | 18        | 1.34%   |
| 5.11.0-25-generic | 18        | 1.34%   |
| 5.4.0-65-generic  | 17        | 1.26%   |
| 5.3.0-53-generic  | 16        | 1.19%   |
| 5.13.0-52-generic | 16        | 1.19%   |
| 5.13.0-51-generic | 16        | 1.19%   |
| 5.4.0-58-generic  | 15        | 1.11%   |
| 5.3.0-51-generic  | 14        | 1.04%   |
| 5.13.0-41-generic | 14        | 1.04%   |
| 5.11.0-34-generic | 14        | 1.04%   |
| 5.4.0-52-generic  | 13        | 0.96%   |
| 5.4.0-48-generic  | 13        | 0.96%   |
| 5.15.0-43-generic | 13        | 0.96%   |
| 5.13.0-44-generic | 13        | 0.96%   |
| 5.3.0-46-generic  | 12        | 0.89%   |
| 5.3.0-40-generic  | 12        | 0.89%   |
| 5.11.0-46-generic | 12        | 0.89%   |
| 5.4.0-56-generic  | 10        | 0.74%   |
| 5.15.0-48-generic | 10        | 0.74%   |
| 5.4.0-80-generic  | 9         | 0.67%   |
| 5.4.0-54-generic  | 9         | 0.67%   |
| 5.3.0-45-generic  | 9         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 364       | 28.84%  |
| 5.13.0  | 281       | 22.27%  |
| 5.4.0   | 210       | 16.64%  |
| 5.3.0   | 111       | 8.8%    |
| 5.15.0  | 101       | 8%      |
| 4.15.0  | 84        | 6.66%   |
| 5.0.0   | 32        | 2.54%   |
| 5.8.0   | 14        | 1.11%   |
| 5.14.0  | 4         | 0.32%   |
| 4.18.0  | 4         | 0.32%   |
| 4.13.0  | 4         | 0.32%   |
| 5.10.0  | 3         | 0.24%   |
| 4.4.0   | 3         | 0.24%   |
| 5.15.5  | 2         | 0.16%   |
| 5.15.36 | 2         | 0.16%   |
| 5.15.12 | 2         | 0.16%   |
| 4.10.0  | 2         | 0.16%   |
| 6.0.0   | 1         | 0.08%   |
| 5.9.1   | 1         | 0.08%   |
| 5.8.5   | 1         | 0.08%   |
| 5.8.13  | 1         | 0.08%   |
| 5.7.0   | 1         | 0.08%   |
| 5.6.2   | 1         | 0.08%   |
| 5.6.19  | 1         | 0.08%   |
| 5.6.14  | 1         | 0.08%   |
| 5.5.8   | 1         | 0.08%   |
| 5.5.6   | 1         | 0.08%   |
| 5.4.78  | 1         | 0.08%   |
| 5.4.1   | 1         | 0.08%   |
| 5.3.6   | 1         | 0.08%   |
| 5.3.11  | 1         | 0.08%   |
| 5.2.11  | 1         | 0.08%   |
| 5.19.4  | 1         | 0.08%   |
| 5.19.3  | 1         | 0.08%   |
| 5.19.11 | 1         | 0.08%   |
| 5.19.0  | 1         | 0.08%   |
| 5.18.3  | 1         | 0.08%   |
| 5.17.3  | 1         | 0.08%   |
| 5.17.0  | 1         | 0.08%   |
| 5.16.16 | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 364       | 28.91%  |
| 5.13    | 281       | 22.32%  |
| 5.4     | 212       | 16.84%  |
| 5.15    | 114       | 9.05%   |
| 5.3     | 113       | 8.98%   |
| 4.15    | 84        | 6.67%   |
| 5.0     | 33        | 2.62%   |
| 5.8     | 16        | 1.27%   |
| 5.14    | 8         | 0.64%   |
| 5.19    | 4         | 0.32%   |
| 5.10    | 4         | 0.32%   |
| 4.18    | 4         | 0.32%   |
| 4.13    | 4         | 0.32%   |
| 5.16    | 3         | 0.24%   |
| 4.4     | 3         | 0.24%   |
| 5.5     | 2         | 0.16%   |
| 5.17    | 2         | 0.16%   |
| 4.10    | 2         | 0.16%   |
| 6.0     | 1         | 0.08%   |
| 5.9     | 1         | 0.08%   |
| 5.7     | 1         | 0.08%   |
| 5.6     | 1         | 0.08%   |
| 5.2     | 1         | 0.08%   |
| 5.18    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1213      | 99.92%  |
| aarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pantheon      | 1108      | 90.23%  |
| Unknown       | 98        | 7.98%   |
| GNOME         | 12        | 0.98%   |
| X-Cinnamon    | 4         | 0.33%   |
| XFCE          | 1         | 0.08%   |
| Unity         | 1         | 0.08%   |
| MATE          | 1         | 0.08%   |
| KDE5          | 1         | 0.08%   |
| GNOME Classic | 1         | 0.08%   |
| Budgie        | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1212      | 99.84%  |
| Unknown | 2         | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 977       | 79.56%  |
| LightDM | 174       | 14.17%  |
| TDM     | 69        | 5.62%   |
| GDM     | 5         | 0.41%   |
| GDM3    | 2         | 0.16%   |
| SDDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 506       | 41.17%  |
| de_DE   | 114       | 9.28%   |
| es_ES   | 81        | 6.59%   |
| Unknown | 64        | 5.21%   |
| en_GB   | 62        | 5.04%   |
| pt_BR   | 56        | 4.56%   |
| ru_RU   | 53        | 4.31%   |
| fr_FR   | 43        | 3.5%    |
| it_IT   | 33        | 2.69%   |
| pl_PL   | 23        | 1.87%   |
| en_CA   | 22        | 1.79%   |
| en_AU   | 20        | 1.63%   |
| tr_TR   | 12        | 0.98%   |
| nl_NL   | 12        | 0.98%   |
| pt_PT   | 11        | 0.9%    |
| en_IN   | 11        | 0.9%    |
| es_MX   | 8         | 0.65%   |
| hu_HU   | 7         | 0.57%   |
| de_CH   | 7         | 0.57%   |
| zh_CN   | 6         | 0.49%   |
| cs_CZ   | 6         | 0.49%   |
| es_EC   | 4         | 0.33%   |
| en_ZA   | 4         | 0.33%   |
| uk_UA   | 3         | 0.24%   |
| sv_SE   | 3         | 0.24%   |
| nb_NO   | 3         | 0.24%   |
| id_ID   | 3         | 0.24%   |
| hr_HR   | 3         | 0.24%   |
| fi_FI   | 3         | 0.24%   |
| ca_ES   | 3         | 0.24%   |
| zh_TW   | 2         | 0.16%   |
| ja_JP   | 2         | 0.16%   |
| gl_ES   | 2         | 0.16%   |
| fr_CA   | 2         | 0.16%   |
| fr_BE   | 2         | 0.16%   |
| es_CL   | 2         | 0.16%   |
| es_AR   | 2         | 0.16%   |
| en_PH   | 2         | 0.16%   |
| el_GR   | 2         | 0.16%   |
| de_AT   | 2         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 755       | 61.43%  |
| BIOS | 474       | 38.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1150      | 94.34%  |
| Btrfs   | 25        | 2.05%   |
| Unknown | 21        | 1.72%   |
| Overlay | 18        | 1.48%   |
| Xfs     | 4         | 0.33%   |
| Ext3    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1025      | 83.95%  |
| GPT     | 152       | 12.45%  |
| MBR     | 44        | 3.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1152      | 94.74%  |
| Yes       | 64        | 5.26%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1055      | 86.48%  |
| Yes       | 165       | 13.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 192       | 15.82%  |
| ASUSTek Computer    | 173       | 14.25%  |
| Lenovo              | 170       | 14%     |
| Dell                | 132       | 10.87%  |
| Apple               | 102       | 8.4%    |
| Acer                | 77        | 6.34%   |
| Gigabyte Technology | 61        | 5.02%   |
| MSI                 | 50        | 4.12%   |
| ASRock              | 27        | 2.22%   |
| Toshiba             | 26        | 2.14%   |
| Samsung Electronics | 17        | 1.4%    |
| Intel               | 16        | 1.32%   |
| HUAWEI              | 14        | 1.15%   |
| Sony                | 13        | 1.07%   |
| Microsoft           | 10        | 0.82%   |
| Biostar             | 9         | 0.74%   |
| Google              | 6         | 0.49%   |
| Fujitsu             | 6         | 0.49%   |
| Pegatron            | 5         | 0.41%   |
| Packard Bell        | 5         | 0.41%   |
| Notebook            | 5         | 0.41%   |
| LG Electronics      | 5         | 0.41%   |
| Unknown             | 5         | 0.41%   |
| Star Labs           | 4         | 0.33%   |
| Foxconn             | 4         | 0.33%   |
| TUXEDO              | 3         | 0.25%   |
| Timi                | 3         | 0.25%   |
| Teclast             | 3         | 0.25%   |
| Medion              | 3         | 0.25%   |
| eMachines           | 3         | 0.25%   |
| ECS                 | 3         | 0.25%   |
| Compaq              | 3         | 0.25%   |
| AMI                 | 3         | 0.25%   |
| Wibtek              | 2         | 0.16%   |
| TrekStor            | 2         | 0.16%   |
| Razer               | 2         | 0.16%   |
| Positivo            | 2         | 0.16%   |
| Panasonic           | 2         | 0.16%   |
| Monster             | 2         | 0.16%   |
| Clevo               | 2         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 8         | 0.66%   |
| Unknown                            | 7         | 0.58%   |
| HP Notebook                        | 6         | 0.49%   |
| Apple MacBookPro8,2                | 5         | 0.41%   |
| Apple MacBookAir7,2                | 5         | 0.41%   |
| Lenovo G50-45 80E3                 | 4         | 0.33%   |
| HP Laptop 15-bs0xx                 | 4         | 0.33%   |
| ASUS ZenBook UX425EA_UX425EA       | 4         | 0.33%   |
| ASUS P8H61-M LX3 R2.0              | 4         | 0.33%   |
| Apple MacBookPro8,1                | 4         | 0.33%   |
| Apple MacBookAir6,2                | 4         | 0.33%   |
| Apple MacBookAir4,2                | 4         | 0.33%   |
| Apple MacBook5,1                   | 4         | 0.33%   |
| Apple iMac8,1                      | 4         | 0.33%   |
| MSI MS-7C02                        | 3         | 0.25%   |
| HUAWEI MACHD-WXX9                  | 3         | 0.25%   |
| HP ProBook 4540s                   | 3         | 0.25%   |
| HP Pavilion Notebook               | 3         | 0.25%   |
| HP Pavilion g6                     | 3         | 0.25%   |
| HP Laptop 15-db0xxx                | 3         | 0.25%   |
| HP ENVY x360 Convertible 13-ay0xxx | 3         | 0.25%   |
| HP EliteBook 840 G3                | 3         | 0.25%   |
| HP 15                              | 3         | 0.25%   |
| Dell Latitude E6400                | 3         | 0.25%   |
| Dell Inspiron N5110                | 3         | 0.25%   |
| Dell Inspiron 1545                 | 3         | 0.25%   |
| Dell Inspiron 15-3567              | 3         | 0.25%   |
| ASUS X550CA                        | 3         | 0.25%   |
| ASUS PRIME A320M-K                 | 3         | 0.25%   |
| Apple Macmini5,1                   | 3         | 0.25%   |
| Apple MacBookPro9,2                | 3         | 0.25%   |
| Apple MacBookPro9,1                | 3         | 0.25%   |
| Apple MacBookPro5,5                | 3         | 0.25%   |
| Apple MacBookPro11,2               | 3         | 0.25%   |
| Apple MacBook4,1                   | 3         | 0.25%   |
| Apple MacBook2,1                   | 3         | 0.25%   |
| Apple iMac9,1                      | 3         | 0.25%   |
| Apple iMac7,1                      | 3         | 0.25%   |
| Apple iMac11,3                     | 3         | 0.25%   |
| Wibtek H61-M HDMI2                 | 2         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 77        | 6.34%   |
| Acer Aspire        | 53        | 4.37%   |
| Lenovo IdeaPad     | 48        | 3.95%   |
| Dell Inspiron      | 40        | 3.29%   |
| HP Pavilion        | 38        | 3.13%   |
| Dell Latitude      | 34        | 2.8%    |
| HP ProBook         | 27        | 2.22%   |
| HP Laptop          | 24        | 1.98%   |
| HP EliteBook       | 23        | 1.89%   |
| Toshiba Satellite  | 21        | 1.73%   |
| Dell XPS           | 17        | 1.4%    |
| ASUS PRIME         | 16        | 1.32%   |
| Dell OptiPlex      | 14        | 1.15%   |
| ASUS ROG           | 14        | 1.15%   |
| HP ENVY            | 13        | 1.07%   |
| ASUS VivoBook      | 13        | 1.07%   |
| ASUS ZenBook       | 12        | 0.99%   |
| Dell Precision     | 11        | 0.91%   |
| Acer Swift         | 11        | 0.91%   |
| Microsoft Surface  | 10        | 0.82%   |
| Dell Vostro        | 10        | 0.82%   |
| ASUS TUF           | 10        | 0.82%   |
| Apple MacBookPro8  | 10        | 0.82%   |
| HP Compaq          | 8         | 0.66%   |
| ASUS All           | 8         | 0.66%   |
| Apple MacBookAir7  | 7         | 0.58%   |
| Unknown            | 7         | 0.58%   |
| Lenovo Yoga        | 6         | 0.49%   |
| Lenovo ThinkCentre | 6         | 0.49%   |
| HP Notebook        | 6         | 0.49%   |
| ASUS P8H61-M       | 6         | 0.49%   |
| Apple MacBookPro9  | 6         | 0.49%   |
| Apple MacBookPro11 | 6         | 0.49%   |
| Apple MacBookAir6  | 6         | 0.49%   |
| Apple MacBook5     | 6         | 0.49%   |
| Gigabyte Z390      | 5         | 0.41%   |
| Apple MacBookPro5  | 5         | 0.41%   |
| Apple iMac11       | 5         | 0.41%   |
| Lenovo Legion      | 4         | 0.33%   |
| Lenovo G50-45      | 4         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 126       | 10.38%  |
| 2012    | 111       | 9.14%   |
| 2020    | 107       | 8.81%   |
| 2019    | 106       | 8.73%   |
| 2013    | 105       | 8.65%   |
| 2011    | 90        | 7.41%   |
| 2015    | 86        | 7.08%   |
| 2017    | 82        | 6.75%   |
| 2016    | 78        | 6.43%   |
| 2010    | 75        | 6.18%   |
| 2014    | 70        | 5.77%   |
| 2021    | 59        | 4.86%   |
| 2009    | 47        | 3.87%   |
| 2008    | 42        | 3.46%   |
| 2007    | 16        | 1.32%   |
| 2022    | 6         | 0.49%   |
| 2006    | 5         | 0.41%   |
| Unknown | 2         | 0.16%   |
| 2005    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 776       | 63.92%  |
| Desktop        | 329       | 27.1%   |
| All in one     | 37        | 3.05%   |
| Convertible    | 30        | 2.47%   |
| Tablet         | 20        | 1.65%   |
| Mini pc        | 18        | 1.48%   |
| Server         | 3         | 0.25%   |
| System on chip | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1079      | 88.59%  |
| Enabled  | 139       | 11.41%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1203      | 99.09%  |
| Yes  | 11        | 0.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 344       | 28.15%  |
| 3.01-4.0    | 257       | 21.03%  |
| 8.01-16.0   | 224       | 18.33%  |
| 16.01-24.0  | 221       | 18.09%  |
| 32.01-64.0  | 90        | 7.36%   |
| 1.01-2.0    | 47        | 3.85%   |
| 2.01-3.0    | 13        | 1.06%   |
| 24.01-32.0  | 12        | 0.98%   |
| 64.01-256.0 | 12        | 0.98%   |
| 0.51-1.0    | 2         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 513       | 39.1%   |
| 2.01-3.0   | 366       | 27.9%   |
| 3.01-4.0   | 204       | 15.55%  |
| 4.01-8.0   | 156       | 11.89%  |
| 0.51-1.0   | 40        | 3.05%   |
| 8.01-16.0  | 30        | 2.29%   |
| 32.01-64.0 | 1         | 0.08%   |
| 24.01-32.0 | 1         | 0.08%   |
| 16.01-24.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 779       | 63.28%  |
| 2       | 330       | 26.81%  |
| 3       | 57        | 4.63%   |
| 4       | 28        | 2.27%   |
| 5       | 17        | 1.38%   |
| 6       | 7         | 0.57%   |
| 0       | 7         | 0.57%   |
| 7       | 4         | 0.32%   |
| 8       | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 777       | 63.43%  |
| Yes       | 448       | 36.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 993       | 81.8%   |
| No        | 221       | 18.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1026      | 84.1%   |
| No        | 194       | 15.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 869       | 71%     |
| No        | 355       | 29%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 161       | 13.24%  |
| Germany      | 117       | 9.62%   |
| Brazil       | 83        | 6.83%   |
| UK           | 66        | 5.43%   |
| Russia       | 62        | 5.1%    |
| India        | 49        | 4.03%   |
| Italy        | 46        | 3.78%   |
| Spain        | 44        | 3.62%   |
| Canada       | 39        | 3.21%   |
| France       | 36        | 2.96%   |
| Indonesia    | 33        | 2.71%   |
| Mexico       | 32        | 2.63%   |
| Australia    | 29        | 2.38%   |
| Poland       | 27        | 2.22%   |
| Turkey       | 24        | 1.97%   |
| Netherlands  | 21        | 1.73%   |
| Argentina    | 21        | 1.73%   |
| Austria      | 17        | 1.4%    |
| Belgium      | 15        | 1.23%   |
| Ukraine      | 14        | 1.15%   |
| Switzerland  | 14        | 1.15%   |
| Portugal     | 13        | 1.07%   |
| Czechia      | 11        | 0.9%    |
| Sweden       | 10        | 0.82%   |
| Chile        | 10        | 0.82%   |
| Malaysia     | 9         | 0.74%   |
| Romania      | 8         | 0.66%   |
| Norway       | 8         | 0.66%   |
| New Zealand  | 8         | 0.66%   |
| Hungary      | 8         | 0.66%   |
| Colombia     | 8         | 0.66%   |
| South Africa | 7         | 0.58%   |
| Ireland      | 7         | 0.58%   |
| Finland      | 7         | 0.58%   |
| China        | 7         | 0.58%   |
| Greece       | 6         | 0.49%   |
| Denmark      | 6         | 0.49%   |
| Philippines  | 5         | 0.41%   |
| Kenya        | 5         | 0.41%   |
| Japan        | 5         | 0.41%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 16        | 1.27%   |
| Warsaw         | 11        | 0.87%   |
| Sydney         | 11        | 0.87%   |
| Hamburg        | 10        | 0.79%   |
| Berlin         | 10        | 0.79%   |
| Vienna         | 9         | 0.71%   |
| Milan          | 9         | 0.71%   |
| Sao Paulo      | 8         | 0.63%   |
| Rio de Janeiro | 8         | 0.63%   |
| Paris          | 8         | 0.63%   |
| Istanbul       | 8         | 0.63%   |
| Munich         | 7         | 0.55%   |
| Mexico City    | 7         | 0.55%   |
| Madrid         | 7         | 0.55%   |
| Fortaleza      | 7         | 0.55%   |
| Montreal       | 6         | 0.48%   |
| Jakarta        | 6         | 0.48%   |
| Dublin         | 6         | 0.48%   |
| The Hague      | 5         | 0.4%    |
| St Petersburg  | 5         | 0.4%    |
| Perth          | 5         | 0.4%    |
| Nairobi        | 5         | 0.4%    |
| Brisbane       | 5         | 0.4%    |
| Zagreb         | 4         | 0.32%   |
| Valencia       | 4         | 0.32%   |
| Surabaya       | 4         | 0.32%   |
| Sofia          | 4         | 0.32%   |
| Santo André   | 4         | 0.32%   |
| Rome           | 4         | 0.32%   |
| Pozza di Fassa | 4         | 0.32%   |
| Novosibirsk    | 4         | 0.32%   |
| Mumbai         | 4         | 0.32%   |
| Kolkata        | 4         | 0.32%   |
| Dresden        | 4         | 0.32%   |
| Delhi          | 4         | 0.32%   |
| Córdoba       | 4         | 0.32%   |
| Caslano        | 4         | 0.32%   |
| Cairo          | 4         | 0.32%   |
| Bogor          | 4         | 0.32%   |
| Vernon         | 3         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 233       | 326    | 13.92%  |
| WDC                       | 220       | 299    | 13.14%  |
| Seagate                   | 213       | 273    | 12.72%  |
| Toshiba                   | 133       | 166    | 7.95%   |
| SanDisk                   | 108       | 118    | 6.45%   |
| Kingston                  | 108       | 140    | 6.45%   |
| Unknown                   | 84        | 106    | 5.02%   |
| Crucial                   | 68        | 84     | 4.06%   |
| Hitachi                   | 52        | 55     | 3.11%   |
| HGST                      | 46        | 57     | 2.75%   |
| Apple                     | 38        | 41     | 2.27%   |
| Intel                     | 37        | 44     | 2.21%   |
| SK hynix                  | 32        | 34     | 1.91%   |
| A-DATA Technology         | 29        | 32     | 1.73%   |
| Micron Technology         | 21        | 24     | 1.25%   |
| Phison                    | 15        | 17     | 0.9%    |
| KIOXIA                    | 14        | 20     | 0.84%   |
| China                     | 13        | 13     | 0.78%   |
| PNY                       | 10        | 17     | 0.6%    |
| Fujitsu                   | 10        | 11     | 0.6%    |
| Transcend                 | 8         | 9      | 0.48%   |
| OCZ                       | 8         | 12     | 0.48%   |
| Micron/Crucial Technology | 7         | 12     | 0.42%   |
| LITEON                    | 7         | 7      | 0.42%   |
| Silicon Motion            | 6         | 7      | 0.36%   |
| Patriot                   | 6         | 8      | 0.36%   |
| JMicron Technology        | 6         | 6      | 0.36%   |
| Corsair                   | 6         | 6      | 0.36%   |
| Gigabyte Technology       | 5         | 5      | 0.3%    |
| Unknown                   | 5         | 6      | 0.3%    |
| Team                      | 4         | 5      | 0.24%   |
| SPCC                      | 4         | 4      | 0.24%   |
| Plextor                   | 4         | 5      | 0.24%   |
| Lite-On                   | 4         | 4      | 0.24%   |
| Intenso                   | 4         | 4      | 0.24%   |
| Hewlett-Packard           | 4         | 4      | 0.24%   |
| TO Exter                  | 3         | 3      | 0.18%   |
| Realtek Semiconductor     | 3         | 3      | 0.18%   |
| Netac                     | 3         | 3      | 0.18%   |
| Maxtor                    | 3         | 3      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 31        | 1.73%   |
| Toshiba MQ01ABD100 1TB             | 24        | 1.34%   |
| Samsung NVMe SSD Drive 512GB       | 22        | 1.23%   |
| Unknown MMC Card  32GB             | 21        | 1.17%   |
| Samsung NVMe SSD Drive 256GB       | 21        | 1.17%   |
| Unknown MMC Card  64GB             | 16        | 0.89%   |
| SanDisk NVMe SSD Drive 512GB       | 16        | 0.89%   |
| Samsung NVMe SSD Drive 500GB       | 16        | 0.89%   |
| Kingston SA400S37120G 120GB SSD    | 16        | 0.89%   |
| Samsung SSD 850 EVO 250GB          | 15        | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB     | 14        | 0.78%   |
| Toshiba MQ04ABF100 1TB             | 13        | 0.73%   |
| Seagate ST500LT012-1DG142 500GB    | 13        | 0.73%   |
| HGST HTS721010A9E630 1TB           | 13        | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 12        | 0.67%   |
| Samsung SSD 860 EVO 250GB          | 12        | 0.67%   |
| Intel NVMe SSD Drive 512GB         | 12        | 0.67%   |
| Unknown MMC Card  128GB            | 11        | 0.61%   |
| Samsung NVMe SSD Drive 1TB         | 11        | 0.61%   |
| Kingston SV300S37A120G 120GB SSD   | 11        | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 10        | 0.56%   |
| Toshiba MQ01ABF050 500GB           | 10        | 0.56%   |
| SK hynix NVMe SSD Drive 512GB      | 10        | 0.56%   |
| Samsung SSD 860 EVO 500GB          | 10        | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB           | 9         | 0.5%    |
| Toshiba NVMe SSD Drive 256GB       | 9         | 0.5%    |
| Samsung SSD 860 EVO 1TB            | 9         | 0.5%    |
| HGST HTS545050A7E680 500GB         | 9         | 0.5%    |
| Crucial CT240BX500SSD1 240GB       | 9         | 0.5%    |
| SK hynix NVMe SSD Drive 256GB      | 8         | 0.45%   |
| Seagate ST500DM002-1BD142 500GB    | 8         | 0.45%   |
| SanDisk NVMe SSD Drive 256GB       | 8         | 0.45%   |
| Samsung SSD 850 EVO 500GB          | 8         | 0.45%   |
| Toshiba DT01ACA100 1TB             | 7         | 0.39%   |
| Toshiba DT01ACA050 500GB           | 7         | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB     | 7         | 0.39%   |
| Samsung SSD 840 EVO 250GB          | 7         | 0.39%   |
| Phison NVMe SSD Drive 1TB          | 7         | 0.39%   |
| HGST HTS541010A9E680 1TB           | 7         | 0.39%   |
| Crucial CT1000MX500SSD1 1TB        | 7         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 209       | 265    | 32.76%  |
| WDC                 | 174       | 232    | 27.27%  |
| Toshiba             | 105       | 135    | 16.46%  |
| Hitachi             | 52        | 55     | 8.15%   |
| HGST                | 46        | 57     | 7.21%   |
| Samsung Electronics | 23        | 26     | 3.61%   |
| Fujitsu             | 10        | 11     | 1.57%   |
| Apple               | 9         | 9      | 1.41%   |
| Unknown             | 3         | 4      | 0.47%   |
| Maxtor              | 2         | 2      | 0.31%   |
| ASMT                | 2         | 2      | 0.31%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |
| Generic-            | 1         | 1      | 0.16%   |
| Ext Hard            | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 132       | 173    | 20.63%  |
| Kingston            | 91        | 105    | 14.22%  |
| SanDisk             | 68        | 75     | 10.63%  |
| Crucial             | 67        | 82     | 10.47%  |
| WDC                 | 37        | 47     | 5.78%   |
| Apple               | 28        | 29     | 4.38%   |
| A-DATA Technology   | 26        | 29     | 4.06%   |
| Intel               | 16        | 16     | 2.5%    |
| Micron Technology   | 13        | 15     | 2.03%   |
| China               | 13        | 13     | 2.03%   |
| Toshiba             | 12        | 12     | 1.88%   |
| PNY                 | 10        | 17     | 1.56%   |
| Transcend           | 8         | 9      | 1.25%   |
| OCZ                 | 8         | 12     | 1.25%   |
| LITEON              | 7         | 7      | 1.09%   |
| SK hynix            | 6         | 6      | 0.94%   |
| Patriot             | 6         | 8      | 0.94%   |
| Corsair             | 6         | 6      | 0.94%   |
| Team                | 4         | 5      | 0.63%   |
| SPCC                | 4         | 4      | 0.63%   |
| Plextor             | 4         | 5      | 0.63%   |
| Intenso             | 4         | 4      | 0.63%   |
| TO Exter            | 3         | 3      | 0.47%   |
| Hewlett-Packard     | 3         | 3      | 0.47%   |
| GOODRAM             | 3         | 6      | 0.47%   |
| Gigabyte Technology | 3         | 3      | 0.47%   |
| FORESEE             | 3         | 3      | 0.47%   |
| Apacer              | 3         | 3      | 0.47%   |
| Teclast             | 2         | 2      | 0.31%   |
| Star                | 2         | 2      | 0.31%   |
| NGFF                | 2         | 2      | 0.31%   |
| Netac               | 2         | 2      | 0.31%   |
| LITEONIT            | 2         | 2      | 0.31%   |
| Leven               | 2         | 2      | 0.31%   |
| KingSpec            | 2         | 2      | 0.31%   |
| KingDian            | 2         | 3      | 0.31%   |
| Dogfish             | 2         | 3      | 0.31%   |
| WDC WDS             | 1         | 1      | 0.16%   |
| VT                  | 1         | 1      | 0.16%   |
| V-GeN               | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 575       | 801    | 36.98%  |
| SSD     | 572       | 757    | 36.78%  |
| NVMe    | 298       | 398    | 19.16%  |
| MMC     | 75        | 87     | 4.82%   |
| Unknown | 35        | 47     | 2.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 969       | 1538   | 69.56%  |
| NVMe | 296       | 395    | 21.25%  |
| MMC  | 75        | 87     | 5.38%   |
| SAS  | 53        | 70     | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 745       | 1035   | 65.58%  |
| 0.51-1.0   | 310       | 402    | 27.29%  |
| 1.01-2.0   | 46        | 65     | 4.05%   |
| 2.01-3.0   | 16        | 34     | 1.41%   |
| 4.01-10.0  | 10        | 12     | 0.88%   |
| 3.01-4.0   | 9         | 10     | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 456       | 36.48%  |
| 251-500        | 320       | 25.6%   |
| 501-1000       | 180       | 14.4%   |
| 51-100         | 95        | 7.6%    |
| 1001-2000      | 72        | 5.76%   |
| 21-50          | 65        | 5.2%    |
| More than 3000 | 24        | 1.92%   |
| 1-20           | 17        | 1.36%   |
| 2001-3000      | 16        | 1.28%   |
| Unknown        | 5         | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 553       | 42.54%  |
| 21-50          | 296       | 22.77%  |
| 51-100         | 156       | 12%     |
| 101-250        | 137       | 10.54%  |
| 251-500        | 68        | 5.23%   |
| 501-1000       | 50        | 3.85%   |
| 1001-2000      | 21        | 1.62%   |
| More than 3000 | 7         | 0.54%   |
| 2001-3000      | 7         | 0.54%   |
| Unknown        | 5         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 1      | 2.08%   |
| WDC WD5000BPKT-75PK4T0 500GB            | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-221CA1 500GB             | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 1         | 1      | 2.08%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 1         | 1      | 2.08%   |
| WDC WD3200AAJS-56B4A0 320GB             | 1         | 1      | 2.08%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1      | 2.08%   |
| WDC WD10EZEX-00KUWA0 1TB                | 1         | 1      | 2.08%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1         | 1      | 2.08%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 2.08%   |
| Toshiba MK3259GSXP 320GB                | 1         | 1      | 2.08%   |
| Toshiba KBG30ZPZ128G 128GB              | 1         | 1      | 2.08%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 2.08%   |
| Seagate ST500LM030-2E717D 500GB         | 1         | 1      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1      | 2.08%   |
| Seagate ST3500414CS 500GB               | 1         | 2      | 2.08%   |
| Seagate ST3500312CS 500GB               | 1         | 1      | 2.08%   |
| Seagate ST3320613AS 320GB               | 1         | 1      | 2.08%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 1      | 2.08%   |
| Seagate ST3160813AS 160GB               | 1         | 1      | 2.08%   |
| Seagate ST2000DM006-2DM164 2TB          | 1         | 1      | 2.08%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB     | 1         | 1      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1      | 2.08%   |
| SanDisk SSD PLUS 240GB                  | 1         | 1      | 2.08%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD     | 1         | 1      | 2.08%   |
| SanDisk SD7SB3Q256G1002 256GB SSD       | 1         | 1      | 2.08%   |
| Samsung Electronics HD322GJ 320GB       | 1         | 1      | 2.08%   |
| Samsung Electronics HD204UI 2TB         | 1         | 1      | 2.08%   |
| Samsung Electronics HD160JJ 160GB       | 1         | 1      | 2.08%   |
| Kingston SV300S37A240G 240GB SSD        | 1         | 1      | 2.08%   |
| Kingston SUV400S37480G 480GB SSD        | 1         | 1      | 2.08%   |
| Kingston SA400S37120G 120GB SSD         | 1         | 1      | 2.08%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 2.08%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 1      | 2.08%   |
| Hitachi HDT721064SLA360 640GB           | 1         | 1      | 2.08%   |
| Hitachi HDS721010CLA332 1TB             | 1         | 1      | 2.08%   |
| HGST HUS724030ALA640 3TB                | 1         | 1      | 2.08%   |
| HGST HTS725050A7E630 500GB              | 1         | 1      | 2.08%   |
| HGST HTS721010A9E630 1TB                | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 22.92%  |
| WDC                 | 10        | 10     | 20.83%  |
| HGST                | 5         | 5      | 10.42%  |
| Kingston            | 4         | 4      | 8.33%   |
| Toshiba             | 3         | 3      | 6.25%   |
| SanDisk             | 3         | 3      | 6.25%   |
| Samsung Electronics | 3         | 3      | 6.25%   |
| Hitachi             | 3         | 3      | 6.25%   |
| Crucial             | 2         | 2      | 4.17%   |
| Apple               | 2         | 2      | 4.17%   |
| Fujitsu             | 1         | 2      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 31.43%  |
| WDC                 | 9         | 9      | 25.71%  |
| HGST                | 5         | 5      | 14.29%  |
| Samsung Electronics | 3         | 3      | 8.57%   |
| Hitachi             | 3         | 3      | 8.57%   |
| Toshiba             | 2         | 2      | 5.71%   |
| Fujitsu             | 1         | 2      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 37     | 71.11%  |
| SSD  | 12        | 12     | 26.67%  |
| NVMe | 1         | 1      | 2.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-75Z10T1 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1040      | 1772   | 82.34%  |
| Works    | 178       | 267    | 14.09%  |
| Malfunc  | 44        | 50     | 3.48%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 863       | 59.93%  |
| AMD                            | 181       | 12.57%  |
| Samsung Electronics            | 116       | 8.06%   |
| SanDisk                        | 53        | 3.68%   |
| Nvidia                         | 36        | 2.5%    |
| SK hynix                       | 26        | 1.81%   |
| Kingston Technology Company    | 21        | 1.46%   |
| Toshiba America Info Systems   | 18        | 1.25%   |
| Phison Electronics             | 17        | 1.18%   |
| Marvell Technology Group       | 16        | 1.11%   |
| ASMedia Technology             | 15        | 1.04%   |
| KIOXIA                         | 13        | 0.9%    |
| JMicron Technology             | 9         | 0.63%   |
| Micron/Crucial Technology      | 8         | 0.56%   |
| Micron Technology              | 8         | 0.56%   |
| ADATA Technology               | 7         | 0.49%   |
| Silicon Motion                 | 6         | 0.42%   |
| Realtek Semiconductor          | 5         | 0.35%   |
| Lite-On Technology             | 4         | 0.28%   |
| Seagate Technology             | 3         | 0.21%   |
| Union Memory (Shenzhen)        | 2         | 0.14%   |
| LSI Logic / Symbios Logic      | 2         | 0.14%   |
| Broadcom / LSI                 | 2         | 0.14%   |
| Apple                          | 2         | 0.14%   |
| Yangtze Memory Technologies    | 1         | 0.07%   |
| VIA Technologies               | 1         | 0.07%   |
| Solid State Storage Technology | 1         | 0.07%   |
| Silicon Image                  | 1         | 0.07%   |
| Shenzhen Longsys Electronics   | 1         | 0.07%   |
| Hewlett-Packard                | 1         | 0.07%   |
| Biwin Storage Technology       | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 141       | 8.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 91        | 5.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 79        | 4.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 62        | 3.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 54        | 3.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 48        | 2.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 46        | 2.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 42        | 2.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 29        | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 27        | 1.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 26        | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 24        | 1.49%   |
| Samsung NVMe SSD Controller 980                                                         | 23        | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 23        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 22        | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 21        | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18        | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18        | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 18        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 18        | 1.12%   |
| Intel SATA Controller [RAID mode]                                                       | 17        | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17        | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 17        | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 16        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 16        | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16        | 0.99%   |
| Nvidia MCP79 AHCI Controller                                                            | 14        | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 14        | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 14        | 0.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 13        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12        | 0.74%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 12        | 0.74%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 12        | 0.74%   |
| Intel SSD 660P Series                                                                   | 12        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12        | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 11        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 11        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 921       | 63.43%  |
| NVMe | 298       | 20.52%  |
| IDE  | 136       | 9.37%   |
| RAID | 93        | 6.4%    |
| SAS  | 3         | 0.21%   |
| SCSI | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 987       | 81.3%   |
| AMD    | 226       | 18.62%  |
| ARM    | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 20        | 1.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 17        | 1.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 14        | 1.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 1.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 1.07%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.99%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 12        | 0.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.99%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 10        | 0.82%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 10        | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 0.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 9         | 0.74%   |
| AMD Ryzen 5 3600 6-Core Processor             | 9         | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.66%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.66%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 8         | 0.66%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 8         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.58%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 7         | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.58%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.58%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 7         | 0.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.58%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 0.49%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.49%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.49%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 6         | 0.49%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 0.49%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 6         | 0.49%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6         | 0.49%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 5         | 0.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.41%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 5         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 309       | 25.45%  |
| Intel Core i7           | 252       | 20.76%  |
| Intel Core i3           | 116       | 9.56%   |
| Intel Celeron           | 74        | 6.1%    |
| Intel Core 2 Duo        | 62        | 5.11%   |
| AMD Ryzen 5             | 59        | 4.86%   |
| Other                   | 51        | 4.2%    |
| AMD Ryzen 7             | 35        | 2.88%   |
| Intel Pentium           | 28        | 2.31%   |
| Intel Xeon              | 24        | 1.98%   |
| Intel Atom              | 18        | 1.48%   |
| Intel Pentium Dual-Core | 14        | 1.15%   |
| AMD Ryzen 3             | 14        | 1.15%   |
| AMD A8                  | 13        | 1.07%   |
| AMD FX                  | 11        | 0.91%   |
| AMD A6                  | 11        | 0.91%   |
| AMD A10                 | 11        | 0.91%   |
| Intel Core 2 Quad       | 10        | 0.82%   |
| AMD Ryzen 9             | 8         | 0.66%   |
| AMD Phenom II X4        | 8         | 0.66%   |
| AMD A4                  | 8         | 0.66%   |
| Intel Pentium Silver    | 7         | 0.58%   |
| Intel Core 2            | 7         | 0.58%   |
| Intel Core i9           | 5         | 0.41%   |
| AMD Ryzen 7 PRO         | 4         | 0.33%   |
| AMD E1                  | 4         | 0.33%   |
| AMD Athlon II X4        | 4         | 0.33%   |
| AMD Athlon II X2        | 4         | 0.33%   |
| AMD A12                 | 4         | 0.33%   |
| Intel Genuine           | 3         | 0.25%   |
| Intel Core m3           | 3         | 0.25%   |
| Intel Celeron Dual-Core | 3         | 0.25%   |
| AMD Ryzen 5 PRO         | 3         | 0.25%   |
| AMD Athlon              | 3         | 0.25%   |
| Intel Pentium Dual      | 2         | 0.16%   |
| Intel Core m5           | 2         | 0.16%   |
| AMD Phenom              | 2         | 0.16%   |
| AMD E                   | 2         | 0.16%   |
| AMD C-60                | 2         | 0.16%   |
| Intel Xeon Silver       | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 590       | 48.52%  |
| 4      | 443       | 36.43%  |
| 6      | 85        | 6.99%   |
| 8      | 61        | 5.02%   |
| 1      | 14        | 1.15%   |
| 12     | 10        | 0.82%   |
| 3      | 8         | 0.66%   |
| 16     | 3         | 0.25%   |
| 10     | 2         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1206      | 99.34%  |
| 2      | 8         | 0.66%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 817       | 67.24%  |
| 1      | 398       | 32.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1203      | 99.01%  |
| Unknown        | 11        | 0.91%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 112       | 9.07%   |
| Unknown    | 108       | 8.74%   |
| 0x306a9    | 94        | 7.61%   |
| 0x306c3    | 60        | 4.86%   |
| 0x1067a    | 54        | 4.37%   |
| 0x40651    | 48        | 3.89%   |
| 0x406e3    | 39        | 3.16%   |
| 0x806e9    | 37        | 3%      |
| 0x306d4    | 33        | 2.67%   |
| 0x806c1    | 32        | 2.59%   |
| 0x806ec    | 30        | 2.43%   |
| 0x806ea    | 30        | 2.43%   |
| 0x906ea    | 26        | 2.11%   |
| 0x20655    | 26        | 2.11%   |
| 0x906e9    | 21        | 1.7%    |
| 0x20652    | 20        | 1.62%   |
| 0x30678    | 19        | 1.54%   |
| 0x506e3    | 17        | 1.38%   |
| 0x10676    | 17        | 1.38%   |
| 0x08108109 | 17        | 1.38%   |
| 0x08701021 | 16        | 1.3%    |
| 0x706e5    | 14        | 1.13%   |
| 0x706a1    | 14        | 1.13%   |
| 0x806eb    | 13        | 1.05%   |
| 0x406c3    | 13        | 1.05%   |
| 0x706a8    | 11        | 0.89%   |
| 0x506c9    | 11        | 0.89%   |
| 0x06006705 | 11        | 0.89%   |
| 0xa0652    | 10        | 0.81%   |
| 0x08600106 | 10        | 0.81%   |
| 0x0800820d | 10        | 0.81%   |
| 0x06001119 | 10        | 0.81%   |
| 0x906ed    | 9         | 0.73%   |
| 0x106e5    | 9         | 0.73%   |
| 0x08108102 | 9         | 0.73%   |
| 0x010000c8 | 9         | 0.73%   |
| 0x6fd      | 8         | 0.65%   |
| 0x6fb      | 8         | 0.65%   |
| 0x406c4    | 8         | 0.65%   |
| 0x906eb    | 7         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 200       | 16.47%  |
| SandyBridge      | 124       | 10.21%  |
| Haswell          | 124       | 10.21%  |
| IvyBridge        | 101       | 8.32%   |
| Penryn           | 74        | 6.1%    |
| Skylake          | 63        | 5.19%   |
| Westmere         | 48        | 3.95%   |
| Silvermont       | 48        | 3.95%   |
| Zen 2            | 43        | 3.54%   |
| Zen+             | 41        | 3.38%   |
| TigerLake        | 37        | 3.05%   |
| Broadwell        | 35        | 2.88%   |
| Core             | 31        | 2.55%   |
| Goldmont plus    | 27        | 2.22%   |
| Excavator        | 26        | 2.14%   |
| Zen              | 24        | 1.98%   |
| IceLake          | 22        | 1.81%   |
| K10              | 21        | 1.73%   |
| CometLake        | 19        | 1.57%   |
| Piledriver       | 18        | 1.48%   |
| Nehalem          | 14        | 1.15%   |
| Zen 3            | 12        | 0.99%   |
| Goldmont         | 11        | 0.91%   |
| Puma             | 9         | 0.74%   |
| Unknown          | 9         | 0.74%   |
| Bobcat           | 7         | 0.58%   |
| Jaguar           | 6         | 0.49%   |
| Steamroller      | 4         | 0.33%   |
| Bulldozer        | 4         | 0.33%   |
| Bonnell          | 3         | 0.25%   |
| Tremont          | 2         | 0.16%   |
| NetBurst         | 2         | 0.16%   |
| K10 Llano        | 2         | 0.16%   |
| K8 Hammer        | 1         | 0.08%   |
| K8 & K10 hybrid  | 1         | 0.08%   |
| Alderlake Hybrid | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 784       | 55.02%  |
| Nvidia                     | 321       | 22.53%  |
| AMD                        | 316       | 22.18%  |
| ATI Technologies           | 2         | 0.14%   |
| Matrox Electronics Systems | 1         | 0.07%   |
| Conexant Systems           | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 92        | 6.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 4.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 50        | 3.41%   |
| Intel HD Graphics 620                                                                    | 40        | 2.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 38        | 2.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 36        | 2.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 2.39%   |
| Intel UHD Graphics 620                                                                   | 34        | 2.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 31        | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 1.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26        | 1.77%   |
| Intel HD Graphics 5500                                                                   | 25        | 1.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 1.57%   |
| AMD Renoir                                                                               | 22        | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 21        | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 1.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 20        | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 16        | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 1.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 15        | 1.02%   |
| Intel HD Graphics 630                                                                    | 14        | 0.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.82%   |
| Nvidia C79 [GeForce 9400M]                                                               | 10        | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 0.68%   |
| Intel HD Graphics 530                                                                    | 10        | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.68%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 10        | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.61%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.55%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.55%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 583       | 47.9%   |
| 1 x AMD                        | 245       | 20.13%  |
| 1 x Nvidia                     | 167       | 13.72%  |
| Intel + Nvidia                 | 143       | 11.75%  |
| Intel + AMD                    | 43        | 3.53%   |
| 2 x AMD                        | 22        | 1.81%   |
| AMD + Nvidia                   | 6         | 0.49%   |
| 2 x Nvidia                     | 3         | 0.25%   |
| Other                          | 2         | 0.16%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.08%   |
| 1 x Matrox                     | 1         | 0.08%   |
| Intel + 2 x AMD                | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1027      | 84.04%  |
| Proprietary | 175       | 14.32%  |
| Unknown     | 20        | 1.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 631       | 51.26%  |
| 1.01-2.0   | 191       | 15.52%  |
| 0.01-0.5   | 140       | 11.37%  |
| 0.51-1.0   | 107       | 8.69%   |
| 3.01-4.0   | 84        | 6.82%   |
| 7.01-8.0   | 40        | 3.25%   |
| 5.01-6.0   | 25        | 2.03%   |
| 2.01-3.0   | 7         | 0.57%   |
| 8.01-16.0  | 6         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 166       | 12.49%  |
| Samsung Electronics     | 149       | 11.21%  |
| LG Display              | 134       | 10.08%  |
| Chimei Innolux          | 123       | 9.26%   |
| BOE                     | 119       | 8.95%   |
| Apple                   | 95        | 7.15%   |
| Dell                    | 60        | 4.51%   |
| Goldstar                | 49        | 3.69%   |
| Hewlett-Packard         | 48        | 3.61%   |
| Acer                    | 37        | 2.78%   |
| AOC                     | 32        | 2.41%   |
| Sharp                   | 31        | 2.33%   |
| Lenovo                  | 29        | 2.18%   |
| BenQ                    | 22        | 1.66%   |
| Ancor Communications    | 22        | 1.66%   |
| Chi Mei Optoelectronics | 20        | 1.5%    |
| Philips                 | 19        | 1.43%   |
| LG Electronics          | 15        | 1.13%   |
| PANDA                   | 13        | 0.98%   |
| ViewSonic               | 9         | 0.68%   |
| Unknown                 | 9         | 0.68%   |
| InfoVision              | 8         | 0.6%    |
| Sony                    | 7         | 0.53%   |
| Vizio                   | 6         | 0.45%   |
| Panasonic               | 6         | 0.45%   |
| Fujitsu Siemens         | 5         | 0.38%   |
| CSO                     | 5         | 0.38%   |
| Toshiba                 | 4         | 0.3%    |
| NEC Computers           | 4         | 0.3%    |
| CPT                     | 4         | 0.3%    |
| ___                     | 3         | 0.23%   |
| LG Philips              | 3         | 0.23%   |
| Iiyama                  | 3         | 0.23%   |
| HPN                     | 3         | 0.23%   |
| Eizo                    | 3         | 0.23%   |
| AUS                     | 3         | 0.23%   |
| Unknown                 | 3         | 0.23%   |
| Onkyo                   | 2         | 0.15%   |
| MSI                     | 2         | 0.15%   |
| LGD                     | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 10        | 0.73%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.59%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 8         | 0.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 6         | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.44%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.37%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 5         | 0.37%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 5         | 0.37%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 5         | 0.37%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 5         | 0.37%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch        | 4         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 0.29%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 4         | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 4         | 0.29%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.29%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 4         | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 0.29%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                     | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 4         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 0.29%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 4         | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.29%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.29%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.29%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 4         | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 3         | 0.22%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch     | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 502       | 39.13%  |
| 1366x768 (WXGA)    | 314       | 24.47%  |
| 3840x2160 (4K)     | 68        | 5.3%    |
| 1600x900 (HD+)     | 64        | 4.99%   |
| 2560x1440 (QHD)    | 51        | 3.98%   |
| 1280x800 (WXGA)    | 47        | 3.66%   |
| 1440x900 (WXGA+)   | 42        | 3.27%   |
| 1680x1050 (WSXGA+) | 40        | 3.12%   |
| 1280x1024 (SXGA)   | 21        | 1.64%   |
| 1920x1200 (WUXGA)  | 20        | 1.56%   |
| Unknown            | 16        | 1.25%   |
| 3840x1080          | 9         | 0.7%    |
| 2560x1600          | 9         | 0.7%    |
| 2880x1800          | 8         | 0.62%   |
| 1360x768           | 8         | 0.62%   |
| 2560x1080          | 7         | 0.55%   |
| 3440x1440          | 5         | 0.39%   |
| 3000x2000          | 5         | 0.39%   |
| 1600x1200          | 4         | 0.31%   |
| 5120x1440          | 3         | 0.23%   |
| 3840x2400          | 3         | 0.23%   |
| 2736x1824          | 3         | 0.23%   |
| 1920x540           | 3         | 0.23%   |
| 1920x1280          | 3         | 0.23%   |
| 1024x600           | 3         | 0.23%   |
| 3200x1800 (QHD+)   | 2         | 0.16%   |
| 7680x2160          | 1         | 0.08%   |
| 7680x1600          | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 5760x1080          | 1         | 0.08%   |
| 4480x1440          | 1         | 0.08%   |
| 3968x1280          | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3840x1200          | 1         | 0.08%   |
| 3840x1100          | 1         | 0.08%   |
| 3600x1080          | 1         | 0.08%   |
| 3072x1920          | 1         | 0.08%   |
| 2880x1920          | 1         | 0.08%   |
| 2496x1664          | 1         | 0.08%   |
| 2288x1287          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 336       | 25.36%  |
| 13      | 192       | 14.49%  |
| 14      | 125       | 9.43%   |
| Unknown | 94        | 7.09%   |
| 24      | 68        | 5.13%   |
| 27      | 67        | 5.06%   |
| 17      | 61        | 4.6%    |
| 23      | 59        | 4.45%   |
| 21      | 55        | 4.15%   |
| 11      | 31        | 2.34%   |
| 20      | 28        | 2.11%   |
| 19      | 25        | 1.89%   |
| 12      | 25        | 1.89%   |
| 31      | 21        | 1.58%   |
| 22      | 21        | 1.58%   |
| 18      | 20        | 1.51%   |
| 84      | 9         | 0.68%   |
| 72      | 9         | 0.68%   |
| 32      | 9         | 0.68%   |
| 10      | 9         | 0.68%   |
| 34      | 8         | 0.6%    |
| 25      | 7         | 0.53%   |
| 16      | 7         | 0.53%   |
| 54      | 4         | 0.3%    |
| 33      | 4         | 0.3%    |
| 29      | 3         | 0.23%   |
| 26      | 3         | 0.23%   |
| 65      | 2         | 0.15%   |
| 52      | 2         | 0.15%   |
| 49      | 2         | 0.15%   |
| 48      | 2         | 0.15%   |
| 43      | 2         | 0.15%   |
| 40      | 2         | 0.15%   |
| 37      | 2         | 0.15%   |
| 28      | 2         | 0.15%   |
| 74      | 1         | 0.08%   |
| 69      | 1         | 0.08%   |
| 60      | 1         | 0.08%   |
| 57      | 1         | 0.08%   |
| 55      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 548       | 42.19%  |
| 501-600     | 178       | 13.7%   |
| 201-300     | 172       | 13.24%  |
| 401-500     | 134       | 10.32%  |
| Unknown     | 94        | 7.24%   |
| 351-400     | 70        | 5.39%   |
| 601-700     | 37        | 2.85%   |
| 701-800     | 22        | 1.69%   |
| 1501-2000   | 20        | 1.54%   |
| 1001-1500   | 16        | 1.23%   |
| 801-900     | 6         | 0.46%   |
| 901-1000    | 2         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 888       | 73.88%  |
| 16/10   | 165       | 13.73%  |
| Unknown | 87        | 7.24%   |
| 3/2     | 22        | 1.83%   |
| 5/4     | 18        | 1.5%    |
| 21/9    | 11        | 0.92%   |
| 4/3     | 5         | 0.42%   |
| 32/9    | 2         | 0.17%   |
| 6/5     | 1         | 0.08%   |
| 3.73    | 1         | 0.08%   |
| 3.40    | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 336       | 25.63%  |
| 81-90          | 240       | 18.31%  |
| 201-250        | 155       | 11.82%  |
| Unknown        | 94        | 7.17%   |
| 71-80          | 78        | 5.95%   |
| 301-350        | 69        | 5.26%   |
| 151-200        | 66        | 5.03%   |
| 351-500        | 44        | 3.36%   |
| 121-130        | 40        | 3.05%   |
| 251-300        | 34        | 2.59%   |
| More than 1000 | 32        | 2.44%   |
| 51-60          | 32        | 2.44%   |
| 141-150        | 29        | 2.21%   |
| 61-70          | 23        | 1.75%   |
| 501-1000       | 13        | 0.99%   |
| 131-140        | 10        | 0.76%   |
| 41-50          | 9         | 0.69%   |
| 111-120        | 5         | 0.38%   |
| 91-100         | 2         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 399       | 31.22%  |
| 121-160       | 351       | 27.46%  |
| 51-100        | 305       | 23.87%  |
| Unknown       | 94        | 7.36%   |
| 161-240       | 71        | 5.56%   |
| More than 240 | 30        | 2.35%   |
| 1-50          | 28        | 2.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1038      | 84.05%  |
| 2     | 155       | 12.55%  |
| 3     | 22        | 1.78%   |
| 0     | 19        | 1.54%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 622       | 33.68%  |
| Intel                             | 524       | 28.37%  |
| Qualcomm Atheros                  | 232       | 12.56%  |
| Broadcom                          | 175       | 9.47%   |
| Broadcom Limited                  | 34        | 1.84%   |
| Marvell Technology Group          | 31        | 1.68%   |
| Nvidia                            | 30        | 1.62%   |
| TP-Link                           | 28        | 1.52%   |
| Ralink Technology                 | 22        | 1.19%   |
| Ralink                            | 18        | 0.97%   |
| Xiaomi                            | 10        | 0.54%   |
| Samsung Electronics               | 10        | 0.54%   |
| Huawei Technologies               | 9         | 0.49%   |
| MediaTek                          | 8         | 0.43%   |
| D-Link                            | 8         | 0.43%   |
| Sierra Wireless                   | 7         | 0.38%   |
| ASIX Electronics                  | 7         | 0.38%   |
| OPPO Electronics                  | 5         | 0.27%   |
| Qualcomm Atheros Communications   | 4         | 0.22%   |
| Qualcomm                          | 4         | 0.22%   |
| Linksys                           | 4         | 0.22%   |
| Hewlett-Packard                   | 4         | 0.22%   |
| Google                            | 4         | 0.22%   |
| Ericsson Business Mobile Networks | 4         | 0.22%   |
| D-Link System                     | 4         | 0.22%   |
| Microsoft                         | 3         | 0.16%   |
| TRENDnet                          | 2         | 0.11%   |
| LG Electronics                    | 2         | 0.11%   |
| Lenovo                            | 2         | 0.11%   |
| JMicron Technology                | 2         | 0.11%   |
| Fibocom                           | 2         | 0.11%   |
| ASUSTek Computer                  | 2         | 0.11%   |
| Apple                             | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |
| vivo                              | 1         | 0.05%   |
| VIA Technologies                  | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| Sitecom Europe                    | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.05%   |
| NetGear                           | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 412       | 18.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 98        | 4.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 42        | 1.93%   |
| Intel Wi-Fi 6 AX200                                               | 42        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 39        | 1.8%    |
| Intel Wireless 8260                                               | 38        | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 37        | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29        | 1.34%   |
| Intel Wireless 8265 / 8275                                        | 28        | 1.29%   |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 27        | 1.24%   |
| Intel Wireless 7265                                               | 26        | 1.2%    |
| Intel Wireless 7260                                               | 25        | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 1.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 21        | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 21        | 0.97%   |
| Intel I211 Gigabit Network Connection                             | 20        | 0.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 20        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.87%   |
| Intel Wireless 3165                                               | 18        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 0.78%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 17        | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 16        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 15        | 0.69%   |
| Nvidia MCP79 Ethernet                                             | 15        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 15        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 0.64%   |
| Realtek 802.11ac NIC                                              | 14        | 0.64%   |
| Ralink MT7601U Wireless Adapter                                   | 14        | 0.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 14        | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                     | 14        | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 13        | 0.6%    |
| Intel Ethernet Connection (2) I219-V                              | 12        | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 421       | 38.55%  |
| Qualcomm Atheros                  | 196       | 17.95%  |
| Realtek Semiconductor             | 181       | 16.58%  |
| Broadcom                          | 142       | 13%     |
| Broadcom Limited                  | 30        | 2.75%   |
| TP-Link                           | 28        | 2.56%   |
| Ralink Technology                 | 22        | 2.01%   |
| Ralink                            | 18        | 1.65%   |
| Sierra Wireless                   | 7         | 0.64%   |
| Marvell Technology Group          | 7         | 0.64%   |
| D-Link                            | 6         | 0.55%   |
| Qualcomm Atheros Communications   | 4         | 0.37%   |
| Microsoft                         | 3         | 0.27%   |
| MediaTek                          | 3         | 0.27%   |
| Linksys                           | 3         | 0.27%   |
| Ericsson Business Mobile Networks | 3         | 0.27%   |
| D-Link System                     | 3         | 0.27%   |
| TRENDnet                          | 2         | 0.18%   |
| FIBOCOM                           | 2         | 0.18%   |
| ASUSTek Computer                  | 2         | 0.18%   |
| Sitecom Europe                    | 1         | 0.09%   |
| Qualcomm                          | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| Mercucys                          | 1         | 0.09%   |
| LG Electronics                    | 1         | 0.09%   |
| Edimax Technology                 | 1         | 0.09%   |
| BUFFALO                           | 1         | 0.09%   |
| AVM                               | 1         | 0.09%   |
| AboCom Systems                    | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 42        | 3.82%   |
| Intel Wi-Fi 6 AX200                                            | 42        | 3.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 39        | 3.55%   |
| Intel Wireless 8260                                            | 38        | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 37        | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 29        | 2.64%   |
| Intel Wireless 8265 / 8275                                     | 28        | 2.55%   |
| Intel Wi-Fi 6 AX201                                            | 28        | 2.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 27        | 2.46%   |
| Intel Wireless 7265                                            | 26        | 2.37%   |
| Intel Wireless 7260                                            | 25        | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 21        | 1.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 1.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 20        | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.73%   |
| Intel Wireless 3165                                            | 18        | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 17        | 1.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 17        | 1.55%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 16        | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15        | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 1.36%   |
| Realtek 802.11ac NIC                                           | 14        | 1.27%   |
| Ralink MT7601U Wireless Adapter                                | 14        | 1.27%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 14        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 13        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 1.09%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 1.09%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 12        | 1.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 11        | 1%      |
| Intel Wireless 3160                                            | 11        | 1%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 11        | 1%      |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 11        | 1%      |
| Realtek RTL8723DE Wireless Network Adapter                     | 10        | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 548       | 52.29%  |
| Intel                      | 240       | 22.9%   |
| Broadcom                   | 69        | 6.58%   |
| Qualcomm Atheros           | 59        | 5.63%   |
| Nvidia                     | 30        | 2.86%   |
| Marvell Technology Group   | 24        | 2.29%   |
| Xiaomi                     | 10        | 0.95%   |
| Samsung Electronics        | 10        | 0.95%   |
| ASIX Electronics           | 7         | 0.67%   |
| Huawei Technologies        | 6         | 0.57%   |
| OPPO Electronics           | 5         | 0.48%   |
| MediaTek                   | 5         | 0.48%   |
| Broadcom Limited           | 5         | 0.48%   |
| Google                     | 4         | 0.38%   |
| Qualcomm                   | 3         | 0.29%   |
| Lenovo                     | 2         | 0.19%   |
| JMicron Technology         | 2         | 0.19%   |
| Hewlett-Packard            | 2         | 0.19%   |
| D-Link                     | 2         | 0.19%   |
| Apple                      | 2         | 0.19%   |
| ZTE WCDMA Technologies MSM | 1         | 0.1%    |
| vivo                       | 1         | 0.1%    |
| VIA Technologies           | 1         | 0.1%    |
| Motorola PCS               | 1         | 0.1%    |
| LSI                        | 1         | 0.1%    |
| Linksys                    | 1         | 0.1%    |
| LG Electronics             | 1         | 0.1%    |
| ICS Advent                 | 1         | 0.1%    |
| HMD Global                 | 1         | 0.1%    |
| DisplayLink                | 1         | 0.1%    |
| D-Link System              | 1         | 0.1%    |
| Attansic Technology        | 1         | 0.1%    |
| Aquantia                   | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 412       | 38.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 98        | 9.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 4.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 2.07%   |
| Intel I211 Gigabit Network Connection                             | 20        | 1.88%   |
| Nvidia MCP79 Ethernet                                             | 15        | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 1.22%   |
| Intel Ethernet Connection (2) I219-V                              | 12        | 1.13%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.13%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 1.04%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 1.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 10        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.94%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 9         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.66%   |
| Nvidia MCP61 Ethernet                                             | 7         | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.66%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 7         | 0.66%   |
| Intel Ethernet Controller I225-V                                  | 6         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.47%   |
| OPPO RMX2117                                                      | 5         | 0.47%   |
| MediaTek Nokia 5.1 Plus                                           | 5         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.47%   |
| Huawei YAL-L21                                                    | 5         | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1029      | 50.64%  |
| Ethernet | 992       | 48.82%  |
| Modem    | 9         | 0.44%   |
| Unknown  | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 827       | 67.68%  |
| Ethernet | 395       | 32.32%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 709       | 58.21%  |
| 1     | 462       | 37.93%  |
| 0     | 25        | 2.05%   |
| 3     | 19        | 1.56%   |
| 4     | 2         | 0.16%   |
| 5     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 969       | 79.17%  |
| Yes     | 254       | 20.75%  |
| Unknown | 1         | 0.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 351       | 39.84%  |
| Apple                           | 103       | 11.69%  |
| Realtek Semiconductor           | 94        | 10.67%  |
| Qualcomm Atheros Communications | 73        | 8.29%   |
| Cambridge Silicon Radio         | 51        | 5.79%   |
| Broadcom                        | 49        | 5.56%   |
| Lite-On Technology              | 37        | 4.2%    |
| Foxconn / Hon Hai               | 27        | 3.06%   |
| IMC Networks                    | 22        | 2.5%    |
| Toshiba                         | 11        | 1.25%   |
| Ralink                          | 11        | 1.25%   |
| Hewlett-Packard                 | 10        | 1.14%   |
| Dell                            | 9         | 1.02%   |
| ASUSTek Computer                | 9         | 1.02%   |
| Marvell Semiconductor           | 8         | 0.91%   |
| Realtek                         | 5         | 0.57%   |
| Qcom                            | 3         | 0.34%   |
| Belkin Components               | 2         | 0.23%   |
| Unknown                         | 1         | 0.11%   |
| Taiyo Yuden                     | 1         | 0.11%   |
| Logitech                        | 1         | 0.11%   |
| Fujitsu                         | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 149       | 16.91%  |
| Intel AX201 Bluetooth                               | 59        | 6.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 57        | 6.47%   |
| Realtek Bluetooth Radio                             | 53        | 6.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 51        | 5.79%   |
| Apple Bluetooth Host Controller                     | 42        | 4.77%   |
| Intel AX200 Bluetooth                               | 41        | 4.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 40        | 4.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 31        | 3.52%   |
| Apple Bluetooth USB Host Controller                 | 30        | 3.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 1.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 1.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 16        | 1.82%   |
| Apple Bluetooth HCI                                 | 15        | 1.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.36%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 1.36%   |
| Ralink RT3290 Bluetooth                             | 11        | 1.25%   |
| Lite-On Bluetooth Device                            | 9         | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 1.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 1.02%   |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 8         | 0.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.68%   |
| Intel AX210 Bluetooth                               | 6         | 0.68%   |
| IMC Networks Bluetooth Radio                        | 6         | 0.68%   |
| IMC Networks Bluetooth Device                       | 6         | 0.68%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.57%   |
| Realtek Bluetooth Radio                             | 5         | 0.57%   |
| Marvell Bluetooth and Wireless LAN Composite        | 5         | 0.57%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.57%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.45%   |
| Lite-On Atheros Bluetooth                           | 4         | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 937       | 58.97%  |
| AMD                                  | 303       | 19.07%  |
| Nvidia                               | 225       | 14.16%  |
| C-Media Electronics                  | 32        | 2.01%   |
| Logitech                             | 13        | 0.82%   |
| Creative Labs                        | 12        | 0.76%   |
| Generalplus Technology               | 8         | 0.5%    |
| JMTek                                | 5         | 0.31%   |
| GN Netcom                            | 4         | 0.25%   |
| Creative Technology                  | 4         | 0.25%   |
| BEHRINGER International              | 4         | 0.25%   |
| Texas Instruments                    | 3         | 0.19%   |
| Realtek Semiconductor                | 3         | 0.19%   |
| Razer USA                            | 3         | 0.19%   |
| Corsair                              | 3         | 0.19%   |
| Plantronics                          | 2         | 0.13%   |
| Native Instruments                   | 2         | 0.13%   |
| Focusrite-Novation                   | 2         | 0.13%   |
| ESS Technology                       | 2         | 0.13%   |
| Dell                                 | 2         | 0.13%   |
| YUAN High-Tech Development           | 1         | 0.06%   |
| Unknown                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| TEAC                                 | 1         | 0.06%   |
| SteelSeries ApS                      | 1         | 0.06%   |
| Sennheiser Communications            | 1         | 0.06%   |
| PreSonus Audio Electronics           | 1         | 0.06%   |
| No brand                             | 1         | 0.06%   |
| Microsoft                            | 1         | 0.06%   |
| Micro Star International             | 1         | 0.06%   |
| Hewlett-Packard                      | 1         | 0.06%   |
| Fry's Electronics                    | 1         | 0.06%   |
| Fortemedia                           | 1         | 0.06%   |
| Edifier Technology                   | 1         | 0.06%   |
| BY EDIFIER                           | 1         | 0.06%   |
| ATI Technologies                     | 1         | 0.06%   |
| ASUSTek Computer                     | 1         | 0.06%   |
| Astro Gaming                         | 1         | 0.06%   |
| Apple                                | 1         | 0.06%   |
| Anlya.cn                             | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 123       | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 115       | 6.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 100       | 5.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 78        | 4.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 62        | 3.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 55        | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 51        | 2.67%   |
| Intel 8 Series HD Audio Controller                                                                | 51        | 2.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 41        | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 41        | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 40        | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 39        | 2.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 37        | 1.94%   |
| Intel Broadwell-U Audio Controller                                                                | 35        | 1.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 35        | 1.84%   |
| AMD FCH Azalia Controller                                                                         | 35        | 1.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 33        | 1.73%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 27        | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 27        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 27        | 1.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 25        | 1.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 25        | 1.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 24        | 1.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 24        | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 21        | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 20        | 1.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 20        | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 19        | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 1%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 19        | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 16        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.84%   |
| Intel 200 Series PCH HD Audio                                                                     | 16        | 0.84%   |
| Nvidia MCP79 High Definition Audio                                                                | 15        | 0.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 0.79%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 15        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 15        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 105       | 24.65%  |
| SK hynix            | 79        | 18.54%  |
| Kingston            | 51        | 11.97%  |
| Micron Technology   | 43        | 10.09%  |
| Unknown             | 36        | 8.45%   |
| Crucial             | 19        | 4.46%   |
| Corsair             | 12        | 2.82%   |
| Elpida              | 11        | 2.58%   |
| G.Skill             | 10        | 2.35%   |
| A-DATA Technology   | 9         | 2.11%   |
| Unknown (ABCD)      | 7         | 1.64%   |
| Ramaxel Technology  | 6         | 1.41%   |
| Patriot             | 4         | 0.94%   |
| Nanya Technology    | 4         | 0.94%   |
| Smart               | 3         | 0.7%    |
| Transcend           | 2         | 0.47%   |
| PNY                 | 2         | 0.47%   |
| GSkill              | 2         | 0.47%   |
| Apacer              | 2         | 0.47%   |
| Unknown (82B5)      | 1         | 0.23%   |
| Unknown (0x198)     | 1         | 0.23%   |
| Unknown (0x038A)    | 1         | 0.23%   |
| Toshiba             | 1         | 0.23%   |
| Timetec             | 1         | 0.23%   |
| Team                | 1         | 0.23%   |
| Smart Brazil        | 1         | 0.23%   |
| SHARETRONIC         | 1         | 0.23%   |
| Qimonda             | 1         | 0.23%   |
| Neo Forza           | 1         | 0.23%   |
| Multilaser          | 1         | 0.23%   |
| Magnum Tech         | 1         | 0.23%   |
| Kllisre             | 1         | 0.23%   |
| Hewlett-Packard     | 1         | 0.23%   |
| Avant               | 1         | 0.23%   |
| AMD                 | 1         | 0.23%   |
| Aeneon              | 1         | 0.23%   |
| A Force             | 1         | 0.23%   |
| Unknown             | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.98%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 6         | 1.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 1.32%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.1%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.88%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 4         | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.88%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 0.66%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 3         | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.66%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 3         | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 3         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.66%   |
| Micron RAM MT52L1G32D4PG-093 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.66%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 3         | 0.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 2         | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 2         | 0.44%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 2         | 0.44%   |
| Smart RAM SG564283FG8NWKF-Z1 1024MB SODIMM DDR2 800MT/s          | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s             | 2         | 0.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.44%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 2         | 0.44%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 154       | 43.75%  |
| DDR4    | 133       | 37.78%  |
| DDR2    | 21        | 5.97%   |
| LPDDR4  | 19        | 5.4%    |
| LPDDR3  | 11        | 3.13%   |
| SDRAM   | 7         | 1.99%   |
| Unknown | 6         | 1.7%    |
| DDR     | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 251       | 70.9%   |
| DIMM         | 77        | 21.75%  |
| Row Of Chips | 20        | 5.65%   |
| Chip         | 4         | 1.13%   |
| FB-DIMM      | 1         | 0.28%   |
| Unknown      | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 148       | 36.45%  |
| 4096  | 134       | 33%     |
| 2048  | 65        | 16.01%  |
| 16384 | 41        | 10.1%   |
| 1024  | 14        | 3.45%   |
| 32768 | 3         | 0.74%   |
| 512   | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 95        | 24.23%  |
| 2667    | 60        | 15.31%  |
| 1333    | 37        | 9.44%   |
| 3200    | 33        | 8.42%   |
| 2400    | 29        | 7.4%    |
| 2133    | 28        | 7.14%   |
| 1334    | 16        | 4.08%   |
| 667     | 12        | 3.06%   |
| 800     | 10        | 2.55%   |
| 1867    | 9         | 2.3%    |
| 1067    | 8         | 2.04%   |
| 1066    | 8         | 2.04%   |
| 4267    | 5         | 1.28%   |
| 3600    | 4         | 1.02%   |
| 3266    | 4         | 1.02%   |
| 8400    | 3         | 0.77%   |
| 3466    | 3         | 0.77%   |
| 1800    | 3         | 0.77%   |
| 4266    | 2         | 0.51%   |
| 4199    | 2         | 0.51%   |
| 3733    | 2         | 0.51%   |
| 3000    | 2         | 0.51%   |
| 2933    | 2         | 0.51%   |
| 1866    | 2         | 0.51%   |
| Unknown | 2         | 0.51%   |
| 4800    | 1         | 0.26%   |
| 3334    | 1         | 0.26%   |
| 3007    | 1         | 0.26%   |
| 2934    | 1         | 0.26%   |
| 2800    | 1         | 0.26%   |
| 2666    | 1         | 0.26%   |
| 2200    | 1         | 0.26%   |
| 2048    | 1         | 0.26%   |
| 1639    | 1         | 0.26%   |
| 975     | 1         | 0.26%   |
| 133     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 9         | 33.33%  |
| Brother Industries              | 6         | 22.22%  |
| Canon                           | 4         | 14.81%  |
| Seiko Epson                     | 2         | 7.41%   |
| Samsung Electronics             | 2         | 7.41%   |
| Xerox                           | 1         | 3.7%    |
| Prolific Technology             | 1         | 3.7%    |
| Dymo-CoStar                     | 1         | 3.7%    |
| cab Produkttechnik GmbH & Co KG | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 2         | 7.41%   |
| Xerox Phaser 3040                        | 1         | 3.7%    |
| Seiko Epson XP-202 203 206 Series        | 1         | 3.7%    |
| Seiko Epson L395 Series                  | 1         | 3.7%    |
| Prolific PL2305 Parallel Port            | 1         | 3.7%    |
| HP Printing Support                      | 1         | 3.7%    |
| HP OfficeJet 5200 series                 | 1         | 3.7%    |
| HP LaserJet Pro M202dw                   | 1         | 3.7%    |
| HP LaserJet M101-M106                    | 1         | 3.7%    |
| HP LaserJet 1320                         | 1         | 3.7%    |
| HP Ink Tank 110 series                   | 1         | 3.7%    |
| HP Deskjet F4500 series                  | 1         | 3.7%    |
| HP Deskjet 2050 J510                     | 1         | 3.7%    |
| HP Deskjet 1000 J110 series              | 1         | 3.7%    |
| Dymo-CoStar LabelWriter 450              | 1         | 3.7%    |
| Canon TR8500 series                      | 1         | 3.7%    |
| Canon PIXMA MG3600 Series                | 1         | 3.7%    |
| Canon PIXMA MG2500 Series                | 1         | 3.7%    |
| Canon G3000 series                       | 1         | 3.7%    |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 3.7%    |
| Brother MFC-T910DW                       | 1         | 3.7%    |
| Brother MFC-T800W                        | 1         | 3.7%    |
| Brother MFC-L2750DW series               | 1         | 3.7%    |
| Brother MFC-J5335DW                      | 1         | 3.7%    |
| Brother HL-4140CN series                 | 1         | 3.7%    |
| Brother DCP-L2550DN series               | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 50%     |
| Canon CanoScan LiDE 110                                 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 187       | 21.95%  |
| Realtek Semiconductor                  | 82        | 9.62%   |
| Apple                                  | 78        | 9.15%   |
| IMC Networks                           | 68        | 7.98%   |
| Microdia                               | 54        | 6.34%   |
| Acer                                   | 48        | 5.63%   |
| Sunplus Innovation Technology          | 47        | 5.52%   |
| Quanta                                 | 41        | 4.81%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 3.87%   |
| Logitech                               | 29        | 3.4%    |
| Suyin                                  | 27        | 3.17%   |
| Syntek                                 | 24        | 2.82%   |
| Alcor Micro                            | 19        | 2.23%   |
| Silicon Motion                         | 17        | 2%      |
| Lite-On Technology                     | 15        | 1.76%   |
| Microsoft                              | 11        | 1.29%   |
| Lenovo                                 | 10        | 1.17%   |
| Luxvisions Innotech Limited            | 7         | 0.82%   |
| Ricoh                                  | 6         | 0.7%    |
| Importek                               | 5         | 0.59%   |
| Z-Star Microelectronics                | 4         | 0.47%   |
| LG Electronics                         | 4         | 0.47%   |
| Samsung Electronics                    | 3         | 0.35%   |
| Primax Electronics                     | 3         | 0.35%   |
| KYE Systems (Mouse Systems)            | 3         | 0.35%   |
| Generalplus Technology                 | 3         | 0.35%   |
| Cubeternet                             | 3         | 0.35%   |
| ALi                                    | 3         | 0.35%   |
| Jieli Technology                       | 2         | 0.23%   |
| Foxconn / Hon Hai                      | 2         | 0.23%   |
| Y Media                                | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Teslong Camera                         | 1         | 0.12%   |
| SunplusIT                              | 1         | 0.12%   |
| Sony                                   | 1         | 0.12%   |
| Razer USA                              | 1         | 0.12%   |
| kingcome                               | 1         | 0.12%   |
| icSpring                               | 1         | 0.12%   |
| Hewlett-Packard                        | 1         | 0.12%   |
| Guillemot                              | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Chicony Integrated Camera             | 34        | 3.96%   |
| Apple Built-in iSight                 | 31        | 3.61%   |
| Realtek Integrated_Webcam_HD          | 26        | 3.03%   |
| Chicony HD Webcam                     | 24        | 2.79%   |
| IMC Networks Integrated Camera        | 19        | 2.21%   |
| IMC Networks USB2.0 HD UVC WebCam     | 18        | 2.1%    |
| Apple FaceTime HD Camera              | 16        | 1.86%   |
| Syntek Integrated Camera              | 13        | 1.51%   |
| Microdia Integrated_Webcam_HD         | 13        | 1.51%   |
| Apple iPhone5/5C/5S/6                 | 13        | 1.51%   |
| Sunplus Integrated_Webcam_HD          | 12        | 1.4%    |
| Realtek USB Camera                    | 10        | 1.16%   |
| Apple FaceTime HD Camera (Built-in)   | 10        | 1.16%   |
| Realtek USB2.0 HD UVC WebCam          | 9         | 1.05%   |
| Chicony HP HD Webcam [Fixed]          | 9         | 1.05%   |
| Quanta HP TrueVision HD Camera        | 8         | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam    | 8         | 0.93%   |
| Chicony USB 2.0 Camera                | 8         | 0.93%   |
| Acer Lenovo EasyCamera                | 8         | 0.93%   |
| Sunplus HD WebCam                     | 7         | 0.81%   |
| Realtek Integrated Webcam             | 7         | 0.81%   |
| Quanta HP Webcam                      | 7         | 0.81%   |
| Logitech HD Pro Webcam C920           | 7         | 0.81%   |
| Lite-On Integrated Camera             | 7         | 0.81%   |
| Chicony HP HD Camera                  | 7         | 0.81%   |
| Sunplus Laptop_Integrated_Webcam_HD   | 6         | 0.7%    |
| Realtek HD WebCam                     | 6         | 0.7%    |
| Chicony VGA WebCam                    | 6         | 0.7%    |
| Chicony HP Wide Vision HD Camera      | 6         | 0.7%    |
| Chicony HP Truevision HD              | 6         | 0.7%    |
| Chicony HP High Definition 1MP Webcam | 6         | 0.7%    |
| Chicony EasyCamera                    | 6         | 0.7%    |
| Acer EasyCamera                       | 6         | 0.7%    |
| Syntek Lenovo EasyCamera              | 5         | 0.58%   |
| Syntek EasyCamera                     | 5         | 0.58%   |
| Silicon Motion Web Camera             | 5         | 0.58%   |
| Quanta VGA WebCam                     | 5         | 0.58%   |
| Quanta HD User Facing                 | 5         | 0.58%   |
| Microdia Integrated Webcam            | 5         | 0.58%   |
| Lenovo Integrated Webcam [R5U877]     | 5         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 36.11%  |
| Synaptics                  | 39        | 27.08%  |
| Shenzhen Goodix Technology | 15        | 10.42%  |
| LighTuning Technology      | 14        | 9.72%   |
| Upek                       | 9         | 6.25%   |
| Elan Microelectronics      | 7         | 4.86%   |
| AuthenTec                  | 5         | 3.47%   |
| STMicroelectronics         | 2         | 1.39%   |
| Focal-systems.Corp         | 1         | 0.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 13        | 9.03%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 8.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 7.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 4.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 4.86%   |
| Validity Sensors VFS491                                                    | 6         | 4.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 3.47%   |
| Elan ELAN:Fingerprint                                                      | 5         | 3.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.78%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.08%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.08%   |
| Synaptics  WBDI                                                            | 3         | 2.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.08%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.08%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.39%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.39%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.39%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.39%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.39%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.39%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.39%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.69%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.69%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.69%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.69%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.69%   |
| AuthenTec AES2810                                                          | 1         | 0.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.69%   |
| AuthenTec AES1600                                                          | 1         | 0.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 22        | 44.9%   |
| Alcor Micro                       | 14        | 28.57%  |
| O2 Micro                          | 5         | 10.2%   |
| Lenovo                            | 3         | 6.12%   |
| Upek                              | 2         | 4.08%   |
| VASCO Data Security International | 1         | 2.04%   |
| Gemalto (was Gemplus)             | 1         | 2.04%   |
| Chicony Electronics               | 1         | 2.04%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 22.45%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 10.2%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 8.16%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.12%   |
| Broadcom 5880                                                                | 3         | 6.12%   |
| Broadcom 58200                                                               | 3         | 6.12%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.08%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 2.04%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.04%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.04%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 2.04%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 900       | 73.17%  |
| 1     | 264       | 21.46%  |
| 2     | 56        | 4.55%   |
| 3     | 7         | 0.57%   |
| 4     | 2         | 0.16%   |
| 7     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 143       | 35.48%  |
| Net/wireless             | 70        | 17.37%  |
| Graphics card            | 54        | 13.4%   |
| Chipcard                 | 46        | 11.41%  |
| Multimedia controller    | 32        | 7.94%   |
| Bluetooth                | 13        | 3.23%   |
| Camera                   | 11        | 2.73%   |
| Sound                    | 7         | 1.74%   |
| Storage                  | 5         | 1.24%   |
| Net/ethernet             | 5         | 1.24%   |
| Card reader              | 5         | 1.24%   |
| Communication controller | 4         | 0.99%   |
| Unassigned class         | 3         | 0.74%   |
| Storage/raid             | 2         | 0.5%    |
| Network                  | 2         | 0.5%    |
| Storage/ide              | 1         | 0.25%   |

