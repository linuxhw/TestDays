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

Total: 778

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4354f496c](https://linux-hardware.org/?probe=a4354f496c) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5cf615d5b2](https://linux-hardware.org/?probe=5cf615d5b2) | Nov 02, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [2c42913712](https://linux-hardware.org/?probe=2c42913712) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [9b90ea1d4d](https://linux-hardware.org/?probe=9b90ea1d4d) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [cdd4d21000](https://linux-hardware.org/?probe=cdd4d21000) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| HP            | 805D                        | Desktop     | [916b6f09ac](https://linux-hardware.org/?probe=916b6f09ac) | Oct 23, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [484cb84d6b](https://linux-hardware.org/?probe=484cb84d6b) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [2dd84a41e8](https://linux-hardware.org/?probe=2dd84a41e8) | Oct 17, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [c5b6ba786e](https://linux-hardware.org/?probe=c5b6ba786e) | Oct 16, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [ce623178a2](https://linux-hardware.org/?probe=ce623178a2) | Oct 16, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [435831fd5b](https://linux-hardware.org/?probe=435831fd5b) | Oct 15, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2b00bd7a92](https://linux-hardware.org/?probe=2b00bd7a92) | Oct 15, 2022 |
| HP            | Pavilion dv7                | Notebook    | [44ae8ac465](https://linux-hardware.org/?probe=44ae8ac465) | Oct 14, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| Kraftway      | KWQ67                       | Desktop     | [8346fc15e3](https://linux-hardware.org/?probe=8346fc15e3) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | Notebook    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Kraftway      | KWQ67                       | Desktop     | [d57d34be64](https://linux-hardware.org/?probe=d57d34be64) | Oct 13, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [88772ad191](https://linux-hardware.org/?probe=88772ad191) | Oct 11, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [8926251d64](https://linux-hardware.org/?probe=8926251d64) | Oct 11, 2022 |
| ASUSTek       | Vivobook Slate T3300KA_T... | Tablet      | [cf1735bf9e](https://linux-hardware.org/?probe=cf1735bf9e) | Oct 11, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [db3419c5de](https://linux-hardware.org/?probe=db3419c5de) | Oct 09, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [d19b3b23b5](https://linux-hardware.org/?probe=d19b3b23b5) | Oct 08, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [7f59512d7b](https://linux-hardware.org/?probe=7f59512d7b) | Oct 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f06f54475b](https://linux-hardware.org/?probe=f06f54475b) | Oct 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [20ea012e04](https://linux-hardware.org/?probe=20ea012e04) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | Notebook    | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [823a068620](https://linux-hardware.org/?probe=823a068620) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [c086a688f1](https://linux-hardware.org/?probe=c086a688f1) | Oct 02, 2022 |
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
| HP            | 802E                        | Desktop     | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
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
| 5.11.0-43-generic          | 117       | 18.75%  |
| 5.15.0-46-generic          | 53        | 8.49%   |
| 5.13.0-28-generic          | 53        | 8.49%   |
| 5.13.0-30-generic          | 38        | 6.09%   |
| 5.13.0-27-generic          | 36        | 5.77%   |
| 5.13.0-39-generic          | 35        | 5.61%   |
| 5.15.0-41-generic          | 26        | 4.17%   |
| 5.13.0-40-generic          | 26        | 4.17%   |
| 5.13.0-35-generic          | 23        | 3.69%   |
| 5.15.0-48-generic          | 21        | 3.37%   |
| 5.13.0-37-generic          | 19        | 3.04%   |
| 5.11.0-44-generic          | 18        | 2.88%   |
| 5.13.0-52-generic          | 16        | 2.56%   |
| 5.13.0-51-generic          | 16        | 2.56%   |
| 5.15.0-43-generic          | 14        | 2.24%   |
| 5.13.0-41-generic          | 14        | 2.24%   |
| 5.13.0-44-generic          | 13        | 2.08%   |
| 5.11.0-46-generic          | 12        | 1.92%   |
| 5.15.0-50-generic          | 10        | 1.6%    |
| 5.11.0-41-generic          | 10        | 1.6%    |
| 5.13.0-48-generic          | 9         | 1.44%   |
| 5.15.0-52-generic          | 5         | 0.8%    |
| 5.13.0-25-generic          | 4         | 0.64%   |
| 5.11.0-40-generic          | 3         | 0.48%   |
| 5.15.36-xanmod1            | 2         | 0.32%   |
| 6.0.0-060000rc7-generic    | 1         | 0.16%   |
| 5.8.0-50-generic           | 1         | 0.16%   |
| 5.4.0-122-generic          | 1         | 0.16%   |
| 5.4.0-1055-raspi           | 1         | 0.16%   |
| 5.19.4-surface             | 1         | 0.16%   |
| 5.19.3-051903-generic      | 1         | 0.16%   |
| 5.19.12-051912-generic     | 1         | 0.16%   |
| 5.19.11-xanmod1            | 1         | 0.16%   |
| 5.19.0-8.2-liquorix-amd64  | 1         | 0.16%   |
| 5.18.3-051803-generic      | 1         | 0.16%   |
| 5.17.3-xanmod1             | 1         | 0.16%   |
| 5.16.16-051616-generic     | 1         | 0.16%   |
| 5.16.11-surface            | 1         | 0.16%   |
| 5.16.10-051610-generic     | 1         | 0.16%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 283       | 47.56%  |
| 5.11.0  | 160       | 26.89%  |
| 5.15.0  | 123       | 20.67%  |
| 5.14.0  | 3         | 0.5%    |
| 5.4.0   | 2         | 0.34%   |
| 5.15.36 | 2         | 0.34%   |
| 6.0.0   | 1         | 0.17%   |
| 5.8.0   | 1         | 0.17%   |
| 5.19.4  | 1         | 0.17%   |
| 5.19.3  | 1         | 0.17%   |
| 5.19.12 | 1         | 0.17%   |
| 5.19.11 | 1         | 0.17%   |
| 5.19.0  | 1         | 0.17%   |
| 5.18.3  | 1         | 0.17%   |
| 5.17.3  | 1         | 0.17%   |
| 5.16.16 | 1         | 0.17%   |
| 5.16.11 | 1         | 0.17%   |
| 5.16.10 | 1         | 0.17%   |
| 5.16.0  | 1         | 0.17%   |
| 5.15.6  | 1         | 0.17%   |
| 5.15.5  | 1         | 0.17%   |
| 5.15.3  | 1         | 0.17%   |
| 5.15.21 | 1         | 0.17%   |
| 5.15.13 | 1         | 0.17%   |
| 5.15.12 | 1         | 0.17%   |
| 5.15.11 | 1         | 0.17%   |
| 5.15.10 | 1         | 0.17%   |
| 5.14.10 | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 283       | 47.64%  |
| 5.11    | 160       | 26.94%  |
| 5.15    | 133       | 22.39%  |
| 5.19    | 5         | 0.84%   |
| 5.14    | 4         | 0.67%   |
| 5.16    | 3         | 0.51%   |
| 5.4     | 2         | 0.34%   |
| 6.0     | 1         | 0.17%   |
| 5.8     | 1         | 0.17%   |
| 5.18    | 1         | 0.17%   |
| 5.17    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 577       | 99.83%  |
| aarch64 | 1         | 0.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 575       | 99.48%  |
| KDE5     | 1         | 0.17%   |
| GNOME    | 1         | 0.17%   |
| Unknown  | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 578       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 468       | 80.55%  |
| LightDM | 110       | 18.93%  |
| GDM3    | 2         | 0.34%   |
| GDM     | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 262       | 45.09%  |
| de_DE   | 70        | 12.05%  |
| es_ES   | 46        | 7.92%   |
| en_GB   | 29        | 4.99%   |
| ru_RU   | 28        | 4.82%   |
| fr_FR   | 28        | 4.82%   |
| pt_BR   | 23        | 3.96%   |
| it_IT   | 21        | 3.61%   |
| pl_PL   | 11        | 1.89%   |
| nl_NL   | 9         | 1.55%   |
| tr_TR   | 7         | 1.2%    |
| pt_PT   | 6         | 1.03%   |
| en_CA   | 6         | 1.03%   |
| en_AU   | 6         | 1.03%   |
| zh_CN   | 3         | 0.52%   |
| de_CH   | 3         | 0.52%   |
| uk_UA   | 2         | 0.34%   |
| sv_SE   | 2         | 0.34%   |
| nb_NO   | 2         | 0.34%   |
| ja_JP   | 2         | 0.34%   |
| hu_HU   | 2         | 0.34%   |
| C       | 2         | 0.34%   |
| sr_RS   | 1         | 0.17%   |
| id_ID   | 1         | 0.17%   |
| hr_HR   | 1         | 0.17%   |
| fr_CA   | 1         | 0.17%   |
| fi_FI   | 1         | 0.17%   |
| et_EE   | 1         | 0.17%   |
| es_MX   | 1         | 0.17%   |
| da_DK   | 1         | 0.17%   |
| cs_CZ   | 1         | 0.17%   |
| bg_BG   | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 391       | 66.95%  |
| BIOS | 193       | 33.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 558       | 96.54%  |
| Btrfs   | 12        | 2.08%   |
| Overlay | 5         | 0.87%   |
| Xfs     | 3         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 494       | 85.17%  |
| GPT     | 76        | 13.1%   |
| MBR     | 10        | 1.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 558       | 96.21%  |
| Yes       | 22        | 3.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 541       | 93.44%  |
| Yes       | 38        | 6.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 92        | 15.92%  |
| Lenovo                  | 86        | 14.88%  |
| Hewlett-Packard         | 77        | 13.32%  |
| Apple                   | 66        | 11.42%  |
| Dell                    | 55        | 9.52%   |
| Acer                    | 30        | 5.19%   |
| MSI                     | 28        | 4.84%   |
| Gigabyte Technology     | 22        | 3.81%   |
| HUAWEI                  | 11        | 1.9%    |
| ASRock                  | 10        | 1.73%   |
| Toshiba                 | 9         | 1.56%   |
| Sony                    | 9         | 1.56%   |
| Samsung Electronics     | 7         | 1.21%   |
| Microsoft               | 7         | 1.21%   |
| Intel                   | 7         | 1.21%   |
| Biostar                 | 4         | 0.69%   |
| Teclast                 | 3         | 0.52%   |
| Notebook                | 3         | 0.52%   |
| Foxconn                 | 3         | 0.52%   |
| AMI                     | 3         | 0.52%   |
| Timi                    | 2         | 0.35%   |
| Star Labs               | 2         | 0.35%   |
| Pegatron                | 2         | 0.35%   |
| Packard Bell            | 2         | 0.35%   |
| Monster                 | 2         | 0.35%   |
| LG Electronics          | 2         | 0.35%   |
| Google                  | 2         | 0.35%   |
| Fujitsu                 | 2         | 0.35%   |
| ECS                     | 2         | 0.35%   |
| Unknown                 | 2         | 0.35%   |
| Wortmann AG             | 1         | 0.17%   |
| TUXEDO                  | 1         | 0.17%   |
| TrekStor                | 1         | 0.17%   |
| T-bao                   | 1         | 0.17%   |
| Standard                | 1         | 0.17%   |
| Razer                   | 1         | 0.17%   |
| Raspberry Pi Foundation | 1         | 0.17%   |
| PIPO                    | 1         | 0.17%   |
| Medion                  | 1         | 0.17%   |
| LORD ELECTRONICS        | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 4         | 0.69%   |
| Apple MacBookPro8,2                | 4         | 0.69%   |
| Apple MacBookAir6,2                | 4         | 0.69%   |
| Apple MacBook5,1                   | 4         | 0.69%   |
| Apple iMac8,1                      | 4         | 0.69%   |
| HUAWEI NBLK-WAX9X                  | 3         | 0.52%   |
| HUAWEI MACHD-WXX9                  | 3         | 0.52%   |
| HP Notebook                        | 3         | 0.52%   |
| Dell Inspiron 15-3567              | 3         | 0.52%   |
| ASUS ZenBook UX425EA_UX425EA       | 3         | 0.52%   |
| ASUS X550CA                        | 3         | 0.52%   |
| Apple MacBookAir4,2                | 3         | 0.52%   |
| Apple MacBook4,1                   | 3         | 0.52%   |
| Apple iMac7,1                      | 3         | 0.52%   |
| Unknown                            | 3         | 0.52%   |
| Timi TM1613                        | 2         | 0.35%   |
| MSI Prestige 15 A11UC              | 2         | 0.35%   |
| MSI MS-7C35                        | 2         | 0.35%   |
| MSI Modern 14 B10MW                | 2         | 0.35%   |
| Lenovo Legion Y540-15IRH 81SX      | 2         | 0.35%   |
| Lenovo IdeaPad 510-15IKB 80SV      | 2         | 0.35%   |
| Lenovo IdeaPad 310-15IKB 80TV      | 2         | 0.35%   |
| HP ProBook 4540s                   | 2         | 0.35%   |
| HP Pavilion g6                     | 2         | 0.35%   |
| HP Pavilion g4                     | 2         | 0.35%   |
| HP Pavilion 17                     | 2         | 0.35%   |
| HP Laptop 15-db0xxx                | 2         | 0.35%   |
| HP Laptop 15-bw0xx                 | 2         | 0.35%   |
| HP ENVY x360 Convertible 13-ay0xxx | 2         | 0.35%   |
| HP EliteBook 8460p                 | 2         | 0.35%   |
| HP EliteBook 840 G1                | 2         | 0.35%   |
| HP Compaq Pro 6300 MT              | 2         | 0.35%   |
| Gigabyte Z390 UD                   | 2         | 0.35%   |
| Dell XPS 13 9343                   | 2         | 0.35%   |
| Dell OptiPlex 790                  | 2         | 0.35%   |
| Dell Inspiron N5050                | 2         | 0.35%   |
| Dell Inspiron 5537                 | 2         | 0.35%   |
| ASUS TUF Gaming B550M-PLUS         | 2         | 0.35%   |
| Apple Macmini5,1                   | 2         | 0.35%   |
| Apple MacBookPro6,2                | 2         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 38        | 6.57%   |
| Lenovo IdeaPad     | 25        | 4.33%   |
| Acer Aspire        | 20        | 3.46%   |
| Dell Inspiron      | 19        | 3.29%   |
| HP Pavilion        | 14        | 2.42%   |
| Dell Latitude      | 14        | 2.42%   |
| HP ProBook         | 10        | 1.73%   |
| HP EliteBook       | 10        | 1.73%   |
| ASUS VivoBook      | 10        | 1.73%   |
| HP Laptop          | 9         | 1.56%   |
| ASUS ZenBook       | 8         | 1.38%   |
| ASUS PRIME         | 8         | 1.38%   |
| Microsoft Surface  | 7         | 1.21%   |
| Dell OptiPlex      | 7         | 1.21%   |
| ASUS TUF           | 7         | 1.21%   |
| ASUS ROG           | 7         | 1.21%   |
| Toshiba Satellite  | 6         | 1.04%   |
| HP ENVY            | 6         | 1.04%   |
| Dell XPS           | 6         | 1.04%   |
| Apple MacBookPro8  | 6         | 1.04%   |
| Lenovo Legion      | 5         | 0.87%   |
| Dell Precision     | 5         | 0.87%   |
| Apple MacBookAir6  | 5         | 0.87%   |
| Apple MacBook5     | 5         | 0.87%   |
| Acer Swift         | 5         | 0.87%   |
| HP Compaq          | 4         | 0.69%   |
| Dell Vostro        | 4         | 0.69%   |
| ASUS All           | 4         | 0.69%   |
| Apple MacBookPro5  | 4         | 0.69%   |
| Apple MacBookPro11 | 4         | 0.69%   |
| Apple MacBookAir7  | 4         | 0.69%   |
| Apple iMac8        | 4         | 0.69%   |
| MSI Modern         | 3         | 0.52%   |
| Lenovo ThinkCentre | 3         | 0.52%   |
| Lenovo ThinkBook   | 3         | 0.52%   |
| HUAWEI NBLK-WAX9X  | 3         | 0.52%   |
| HUAWEI MACHD-WXX9  | 3         | 0.52%   |
| HP ProDesk         | 3         | 0.52%   |
| HP Notebook        | 3         | 0.52%   |
| ASUS X550CA        | 3         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 66        | 11.42%  |
| 2019    | 54        | 9.34%   |
| 2018    | 52        | 9%      |
| 2012    | 51        | 8.82%   |
| 2021    | 47        | 8.13%   |
| 2015    | 42        | 7.27%   |
| 2013    | 41        | 7.09%   |
| 2011    | 39        | 6.75%   |
| 2016    | 35        | 6.06%   |
| 2010    | 34        | 5.88%   |
| 2014    | 32        | 5.54%   |
| 2017    | 30        | 5.19%   |
| 2009    | 21        | 3.63%   |
| 2008    | 18        | 3.11%   |
| 2022    | 8         | 1.38%   |
| 2007    | 5         | 0.87%   |
| 2006    | 2         | 0.35%   |
| Unknown | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 374       | 64.71%  |
| Desktop        | 148       | 25.61%  |
| All in one     | 18        | 3.11%   |
| Tablet         | 13        | 2.25%   |
| Mini pc        | 12        | 2.08%   |
| Convertible    | 11        | 1.9%    |
| System on chip | 1         | 0.17%   |
| Server         | 1         | 0.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 500       | 86.21%  |
| Enabled  | 80        | 13.79%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 573       | 99.13%  |
| Yes  | 5         | 0.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 172       | 29.55%  |
| 3.01-4.0    | 122       | 20.96%  |
| 16.01-24.0  | 105       | 18.04%  |
| 8.01-16.0   | 100       | 17.18%  |
| 32.01-64.0  | 50        | 8.59%   |
| 1.01-2.0    | 17        | 2.92%   |
| 64.01-256.0 | 8         | 1.37%   |
| 24.01-32.0  | 5         | 0.86%   |
| 2.01-3.0    | 3         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 230       | 37.28%  |
| 2.01-3.0   | 182       | 29.5%   |
| 3.01-4.0   | 93        | 15.07%  |
| 4.01-8.0   | 72        | 11.67%  |
| 0.51-1.0   | 20        | 3.24%   |
| 8.01-16.0  | 18        | 2.92%   |
| 24.01-32.0 | 1         | 0.16%   |
| 16.01-24.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 374       | 64.15%  |
| 2      | 149       | 25.56%  |
| 3      | 30        | 5.15%   |
| 4      | 16        | 2.74%   |
| 5      | 6         | 1.03%   |
| 6      | 4         | 0.69%   |
| 7      | 2         | 0.34%   |
| 0      | 2         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 380       | 65.18%  |
| Yes       | 203       | 34.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 458       | 79.24%  |
| No        | 120       | 20.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 496       | 85.37%  |
| No        | 85        | 14.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 447       | 76.8%   |
| No        | 135       | 23.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 84        | 14.53%  |
| Germany      | 64        | 11.07%  |
| Russia       | 33        | 5.71%   |
| Brazil       | 33        | 5.71%   |
| UK           | 32        | 5.54%   |
| Italy        | 28        | 4.84%   |
| India        | 21        | 3.63%   |
| France       | 20        | 3.46%   |
| Spain        | 18        | 3.11%   |
| Canada       | 16        | 2.77%   |
| Turkey       | 15        | 2.6%    |
| Indonesia    | 15        | 2.6%    |
| Australia    | 14        | 2.42%   |
| Poland       | 13        | 2.25%   |
| Mexico       | 13        | 2.25%   |
| Switzerland  | 10        | 1.73%   |
| Netherlands  | 9         | 1.56%   |
| Belgium      | 9         | 1.56%   |
| Austria      | 9         | 1.56%   |
| Argentina    | 9         | 1.56%   |
| Portugal     | 6         | 1.04%   |
| Chile        | 6         | 1.04%   |
| Romania      | 5         | 0.87%   |
| New Zealand  | 5         | 0.87%   |
| Sweden       | 4         | 0.69%   |
| Norway       | 4         | 0.69%   |
| Japan        | 4         | 0.69%   |
| Czechia      | 4         | 0.69%   |
| Colombia     | 4         | 0.69%   |
| Ukraine      | 3         | 0.52%   |
| South Africa | 3         | 0.52%   |
| Ireland      | 3         | 0.52%   |
| Iran         | 3         | 0.52%   |
| Hungary      | 3         | 0.52%   |
| China        | 3         | 0.52%   |
| Belarus      | 3         | 0.52%   |
| Venezuela    | 2         | 0.35%   |
| Thailand     | 2         | 0.35%   |
| Sri Lanka    | 2         | 0.35%   |
| Serbia       | 2         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Moscow                 | 12        | 2.01%   |
| Sydney                 | 9         | 1.51%   |
| Munich                 | 7         | 1.17%   |
| Istanbul               | 7         | 1.17%   |
| Hamburg                | 7         | 1.17%   |
| Warsaw                 | 6         | 1%      |
| St Petersburg          | 5         | 0.84%   |
| Vienna                 | 4         | 0.67%   |
| The Hague              | 4         | 0.67%   |
| Sao Paulo              | 4         | 0.67%   |
| Pozza di Fassa         | 4         | 0.67%   |
| Paris                  | 4         | 0.67%   |
| Milan                  | 4         | 0.67%   |
| Madrid                 | 4         | 0.67%   |
| Caslano                | 4         | 0.67%   |
| Toronto                | 3         | 0.5%    |
| Tangerang              | 3         | 0.5%    |
| Rome                   | 3         | 0.5%    |
| Jakarta                | 3         | 0.5%    |
| Bogor                  | 3         | 0.5%    |
| Berlin                 | 3         | 0.5%    |
| Ankara                 | 3         | 0.5%    |
| Yuba City              | 2         | 0.33%   |
| Yaroslavl              | 2         | 0.33%   |
| Wroclaw                | 2         | 0.33%   |
| Wolgast                | 2         | 0.33%   |
| Tucson                 | 2         | 0.33%   |
| Teresina               | 2         | 0.33%   |
| Tel Aviv               | 2         | 0.33%   |
| Tehran                 | 2         | 0.33%   |
| Santo André           | 2         | 0.33%   |
| San Antonio            | 2         | 0.33%   |
| Porto                  | 2         | 0.33%   |
| Novosibirsk            | 2         | 0.33%   |
| Nottingham             | 2         | 0.33%   |
| Nairobi                | 2         | 0.33%   |
| Muralto                | 2         | 0.33%   |
| Mumbai                 | 2         | 0.33%   |
| Monza                  | 2         | 0.33%   |
| Montornès del Vallès | 2         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 121       | 159    | 14.98%  |
| WDC                       | 96        | 130    | 11.88%  |
| Seagate                   | 95        | 114    | 11.76%  |
| Toshiba                   | 59        | 69     | 7.3%    |
| Kingston                  | 51        | 62     | 6.31%   |
| SanDisk                   | 45        | 50     | 5.57%   |
| Unknown                   | 32        | 43     | 3.96%   |
| Crucial                   | 32        | 38     | 3.96%   |
| Apple                     | 23        | 26     | 2.85%   |
| HGST                      | 20        | 21     | 2.48%   |
| SK hynix                  | 19        | 20     | 2.35%   |
| Intel                     | 17        | 20     | 2.1%    |
| Hitachi                   | 16        | 17     | 1.98%   |
| A-DATA Technology         | 15        | 15     | 1.86%   |
| Phison                    | 11        | 12     | 1.36%   |
| PNY                       | 10        | 15     | 1.24%   |
| Micron Technology         | 9         | 11     | 1.11%   |
| KIOXIA                    | 8         | 9      | 0.99%   |
| Micron/Crucial Technology | 7         | 10     | 0.87%   |
| China                     | 6         | 6      | 0.74%   |
| JMicron Technology        | 5         | 5      | 0.62%   |
| Unknown                   | 5         | 7      | 0.62%   |
| Silicon Motion            | 4         | 4      | 0.5%    |
| Fujitsu                   | 4         | 4      | 0.5%    |
| Transcend                 | 3         | 3      | 0.37%   |
| Team                      | 3         | 4      | 0.37%   |
| Realtek Semiconductor     | 3         | 4      | 0.37%   |
| OCZ                       | 3         | 6      | 0.37%   |
| Maxtor                    | 3         | 3      | 0.37%   |
| LITEON                    | 3         | 3      | 0.37%   |
| Leven                     | 3         | 3      | 0.37%   |
| KingDian                  | 3         | 3      | 0.37%   |
| Corsair                   | 3         | 3      | 0.37%   |
| ASMT                      | 3         | 3      | 0.37%   |
| XPG                       | 2         | 2      | 0.25%   |
| TO Exter                  | 2         | 2      | 0.25%   |
| Teclast                   | 2         | 2      | 0.25%   |
| SPCC                      | 2         | 2      | 0.25%   |
| Plextor                   | 2         | 3      | 0.25%   |
| Netac                     | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 11        | 1.28%   |
| Samsung NVMe SSD Drive 512GB                        | 11        | 1.28%   |
| Kingston SA400S37240G 240GB SSD                     | 11        | 1.28%   |
| Toshiba MQ01ABD100 1TB                              | 10        | 1.16%   |
| Samsung NVMe SSD Drive 500GB                        | 10        | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB                      | 9         | 1.05%   |
| Unknown MMC Card  32GB                              | 8         | 0.93%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 0.93%   |
| SK hynix NVMe SSD Drive 256GB                       | 7         | 0.81%   |
| SanDisk NVMe SSD Drive 512GB                        | 7         | 0.81%   |
| Samsung SSD 860 EVO 250GB                           | 7         | 0.81%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.81%   |
| Phison NVMe SSD Drive 1TB                           | 6         | 0.7%    |
| Intel NVMe SSD Drive 512GB                          | 6         | 0.7%    |
| Crucial CT240BX500SSD1 240GB                        | 6         | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 5         | 0.58%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.58%   |
| Toshiba DT01ACA050 500GB                            | 5         | 0.58%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 0.58%   |
| Samsung NVMe SSD Drive 1TB                          | 5         | 0.58%   |
| Micron/Crucial NVMe SSD Drive 1TB                   | 5         | 0.58%   |
| HGST HTS721010A9E630 1TB                            | 5         | 0.58%   |
| HGST HTS545050A7E680 500GB                          | 5         | 0.58%   |
| Unknown                                             | 5         | 0.58%   |
| Unknown MMC Card  64GB                              | 4         | 0.46%   |
| Toshiba NVMe SSD Drive 512GB                        | 4         | 0.46%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                       | 4         | 0.46%   |
| Seagate ST3500418AS 500GB                           | 4         | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                      | 4         | 0.46%   |
| Samsung SSD 860 EVO 500GB                           | 4         | 0.46%   |
| Samsung SSD 860 EVO 1TB                             | 4         | 0.46%   |
| Samsung NVMe SSD Drive 1024GB                       | 4         | 0.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4         | 0.46%   |
| PNY CS900 480GB SSD                                 | 4         | 0.46%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 4         | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                    | 4         | 0.46%   |
| Kingston NVMe SSD Drive 500GB                       | 4         | 0.46%   |
| JMicron Tech 250GB                                  | 4         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 92        | 110    | 34.33%  |
| WDC                 | 72        | 94     | 26.87%  |
| Toshiba             | 44        | 53     | 16.42%  |
| HGST                | 20        | 21     | 7.46%   |
| Hitachi             | 16        | 17     | 5.97%   |
| Samsung Electronics | 9         | 10     | 3.36%   |
| Fujitsu             | 4         | 4      | 1.49%   |
| Apple               | 3         | 3      | 1.12%   |
| Unknown             | 2         | 2      | 0.75%   |
| Maxtor              | 2         | 2      | 0.75%   |
| SABRENT             | 1         | 1      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.37%   |
| Generic-            | 1         | 1      | 0.37%   |
| Ext Hard            | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 64        | 82     | 21.26%  |
| Kingston            | 37        | 41     | 12.29%  |
| Crucial             | 31        | 36     | 10.3%   |
| SanDisk             | 25        | 28     | 8.31%   |
| Apple               | 19        | 20     | 6.31%   |
| WDC                 | 15        | 20     | 4.98%   |
| A-DATA Technology   | 12        | 12     | 3.99%   |
| PNY                 | 10        | 15     | 3.32%   |
| Micron Technology   | 6         | 7      | 1.99%   |
| Intel               | 6         | 6      | 1.99%   |
| China               | 6         | 6      | 1.99%   |
| Toshiba             | 5         | 5      | 1.66%   |
| Transcend           | 3         | 3      | 1%      |
| Team                | 3         | 4      | 1%      |
| OCZ                 | 3         | 6      | 1%      |
| LITEON              | 3         | 3      | 1%      |
| Corsair             | 3         | 3      | 1%      |
| ASMT                | 3         | 3      | 1%      |
| TO Exter            | 2         | 2      | 0.66%   |
| Teclast             | 2         | 2      | 0.66%   |
| SPCC                | 2         | 2      | 0.66%   |
| SK hynix            | 2         | 2      | 0.66%   |
| Plextor             | 2         | 3      | 0.66%   |
| Leven               | 2         | 2      | 0.66%   |
| KingDian            | 2         | 2      | 0.66%   |
| Intenso             | 2         | 2      | 0.66%   |
| GOODRAM             | 2         | 2      | 0.66%   |
| FORESEE             | 2         | 2      | 0.66%   |
| Dogfish             | 2         | 2      | 0.66%   |
| Apacer              | 2         | 2      | 0.66%   |
| tigo                | 1         | 1      | 0.33%   |
| Super Talent        | 1         | 1      | 0.33%   |
| Star                | 1         | 1      | 0.33%   |
| Smartbuy            | 1         | 1      | 0.33%   |
| Seagate             | 1         | 2      | 0.33%   |
| Pioneer             | 1         | 1      | 0.33%   |
| Pichau              | 1         | 1      | 0.33%   |
| Phison              | 1         | 2      | 0.33%   |
| Patriot             | 1         | 2      | 0.33%   |
| OCZ-VERTEX2         | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 277       | 351    | 36.74%  |
| HDD     | 242       | 320    | 32.1%   |
| NVMe    | 178       | 230    | 23.61%  |
| MMC     | 31        | 36     | 4.11%   |
| Unknown | 26        | 37     | 3.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 435       | 664    | 64.16%  |
| NVMe | 178       | 229    | 26.25%  |
| SAS  | 34        | 45     | 5.01%   |
| MMC  | 31        | 36     | 4.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 336       | 450    | 67.07%  |
| 0.51-1.0   | 122       | 161    | 24.35%  |
| 1.01-2.0   | 22        | 29     | 4.39%   |
| 4.01-10.0  | 8         | 10     | 1.6%    |
| 2.01-3.0   | 7         | 15     | 1.4%    |
| 3.01-4.0   | 6         | 6      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 233       | 39.63%  |
| 251-500        | 145       | 24.66%  |
| 501-1000       | 93        | 15.82%  |
| 51-100         | 42        | 7.14%   |
| 1001-2000      | 33        | 5.61%   |
| 21-50          | 25        | 4.25%   |
| More than 3000 | 11        | 1.87%   |
| 2001-3000      | 4         | 0.68%   |
| 1-20           | 1         | 0.17%   |
| Unknown        | 1         | 0.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 272       | 44.52%  |
| 21-50          | 147       | 24.06%  |
| 51-100         | 68        | 11.13%  |
| 101-250        | 59        | 9.66%   |
| 251-500        | 31        | 5.07%   |
| 501-1000       | 19        | 3.11%   |
| 1001-2000      | 9         | 1.47%   |
| More than 3000 | 3         | 0.49%   |
| 2001-3000      | 2         | 0.33%   |
| Unknown        | 1         | 0.16%   |

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
| Detected | 512       | 848    | 85.05%  |
| Works    | 77        | 113    | 12.79%  |
| Malfunc  | 13        | 13     | 2.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 387       | 55.29%  |
| AMD                            | 86        | 12.29%  |
| Samsung Electronics            | 64        | 9.14%   |
| SanDisk                        | 27        | 3.86%   |
| Nvidia                         | 21        | 3%      |
| SK hynix                       | 17        | 2.43%   |
| Kingston Technology Company    | 17        | 2.43%   |
| Phison Electronics             | 12        | 1.71%   |
| Toshiba America Info Systems   | 10        | 1.43%   |
| Marvell Technology Group       | 9         | 1.29%   |
| Micron/Crucial Technology      | 8         | 1.14%   |
| KIOXIA                         | 6         | 0.86%   |
| Realtek Semiconductor          | 5         | 0.71%   |
| ASMedia Technology             | 5         | 0.71%   |
| Silicon Motion                 | 4         | 0.57%   |
| Micron Technology              | 3         | 0.43%   |
| ADATA Technology               | 3         | 0.43%   |
| Union Memory (Shenzhen)        | 2         | 0.29%   |
| Seagate Technology             | 2         | 0.29%   |
| Lite-On Technology             | 2         | 0.29%   |
| JMicron Technology             | 2         | 0.29%   |
| Apple                          | 2         | 0.29%   |
| Yangtze Memory Technologies    | 1         | 0.14%   |
| Solid State Storage Technology | 1         | 0.14%   |
| Shenzhen Longsys Electronics   | 1         | 0.14%   |
| LSI Logic / Symbios Logic      | 1         | 0.14%   |
| Hewlett-Packard                | 1         | 0.14%   |
| Biwin Storage Technology       | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 69        | 8.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 35        | 4.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 34        | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 30        | 3.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25        | 3.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22        | 2.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 2.19%   |
| Samsung NVMe SSD Controller 980                                                         | 16        | 2.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 16        | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15        | 1.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 14        | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14        | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 12        | 1.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 12        | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 12        | 1.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.42%   |
| Nvidia MCP79 AHCI Controller                                                            | 10        | 1.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 10        | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 9         | 1.16%   |
| Intel SSD 660P Series                                                                   | 9         | 1.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 1.16%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 8         | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 8         | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8         | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 7         | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7         | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 7         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 7         | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 0.9%    |
| Samsung Electronics SATA controller                                                     | 6         | 0.77%   |
| Phison E12 NVMe Controller                                                              | 6         | 0.77%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 6         | 0.77%   |
| Kingston Company A2000 NVMe SSD                                                         | 6         | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 6         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 437       | 61.55%  |
| NVMe | 176       | 24.79%  |
| IDE  | 59        | 8.31%   |
| RAID | 37        | 5.21%   |
| SAS  | 1         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 458       | 79.24%  |
| AMD    | 119       | 20.59%  |
| ARM    | 1         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 2.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 1.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 1.21%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.21%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.04%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.87%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.87%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 0.87%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.87%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.69%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.69%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.69%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.69%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.69%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.69%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.69%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.69%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.52%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 3         | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.52%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 3         | 0.52%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 3         | 0.52%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.52%   |
| Intel Core i5-4250U CPU @ 1.30GHz             | 3         | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.52%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 3         | 0.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.52%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 0.52%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 3         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 128       | 22.15%  |
| Intel Core i7           | 122       | 21.11%  |
| Intel Core i3           | 58        | 10.03%  |
| AMD Ryzen 5             | 37        | 6.4%    |
| Other                   | 36        | 6.23%   |
| Intel Celeron           | 35        | 6.06%   |
| Intel Core 2 Duo        | 33        | 5.71%   |
| AMD Ryzen 7             | 21        | 3.63%   |
| Intel Pentium           | 13        | 2.25%   |
| Intel Xeon              | 12        | 2.08%   |
| AMD A10                 | 8         | 1.38%   |
| AMD Ryzen 9             | 7         | 1.21%   |
| AMD Ryzen 3             | 6         | 1.04%   |
| Intel Atom              | 5         | 0.87%   |
| AMD A8                  | 5         | 0.87%   |
| Intel Pentium Silver    | 4         | 0.69%   |
| AMD Athlon II X2        | 4         | 0.69%   |
| AMD A6                  | 4         | 0.69%   |
| Intel Pentium Dual-Core | 3         | 0.52%   |
| Intel Core i9           | 3         | 0.52%   |
| Intel Core 2 Quad       | 3         | 0.52%   |
| AMD Ryzen 7 PRO         | 3         | 0.52%   |
| AMD Phenom II X4        | 3         | 0.52%   |
| AMD FX                  | 3         | 0.52%   |
| AMD A12                 | 3         | 0.52%   |
| Intel Genuine           | 2         | 0.35%   |
| Intel Celeron Dual-Core | 2         | 0.35%   |
| AMD Ryzen 5 PRO         | 2         | 0.35%   |
| AMD Athlon              | 2         | 0.35%   |
| AMD A4                  | 2         | 0.35%   |
| Intel Pentium Dual      | 1         | 0.17%   |
| Intel Core m5           | 1         | 0.17%   |
| Intel Core m3           | 1         | 0.17%   |
| Intel Core 2            | 1         | 0.17%   |
| AMD Phenom II           | 1         | 0.17%   |
| AMD E1                  | 1         | 0.17%   |
| AMD E                   | 1         | 0.17%   |
| AMD Athlon X4           | 1         | 0.17%   |
| AMD Athlon II X4        | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 273       | 47.07%  |
| 4      | 208       | 35.86%  |
| 6      | 43        | 7.41%   |
| 8      | 42        | 7.24%   |
| 12     | 6         | 1.03%   |
| 1      | 4         | 0.69%   |
| 16     | 3         | 0.52%   |
| 3      | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 575       | 99.48%  |
| 2      | 3         | 0.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 407       | 70.29%  |
| 1      | 172       | 29.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 577       | 99.83%  |
| 64-bit         | 1         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 52        | 8.87%   |
| Unknown    | 43        | 7.34%   |
| 0x306a9    | 42        | 7.17%   |
| 0x306c3    | 25        | 4.27%   |
| 0x1067a    | 22        | 3.75%   |
| 0x806c1    | 21        | 3.58%   |
| 0x40651    | 20        | 3.41%   |
| 0x306d4    | 19        | 3.24%   |
| 0x806e9    | 18        | 3.07%   |
| 0x20655    | 16        | 2.73%   |
| 0x806ec    | 15        | 2.56%   |
| 0x406e3    | 15        | 2.56%   |
| 0x10676    | 13        | 2.22%   |
| 0x08108109 | 12        | 2.05%   |
| 0x806ea    | 10        | 1.71%   |
| 0xa0652    | 9         | 1.54%   |
| 0x906ea    | 9         | 1.54%   |
| 0x08600106 | 9         | 1.54%   |
| 0x906e9    | 8         | 1.37%   |
| 0x706e5    | 8         | 1.37%   |
| 0x706a8    | 8         | 1.37%   |
| 0x506e3    | 8         | 1.37%   |
| 0x08701021 | 8         | 1.37%   |
| 0x906ed    | 7         | 1.19%   |
| 0x506c9    | 7         | 1.19%   |
| 0x20652    | 7         | 1.19%   |
| 0x806eb    | 6         | 1.02%   |
| 0x406c3    | 6         | 1.02%   |
| 0x30678    | 6         | 1.02%   |
| 0x0a50000c | 6         | 1.02%   |
| 0x08608103 | 6         | 1.02%   |
| 0x06001119 | 6         | 1.02%   |
| 0x706a1    | 5         | 0.85%   |
| 0x08108102 | 5         | 0.85%   |
| 0x0800820d | 5         | 0.85%   |
| 0x06006705 | 5         | 0.85%   |
| 0x6fd      | 4         | 0.68%   |
| 0x406c4    | 4         | 0.68%   |
| 0x40661    | 4         | 0.68%   |
| 0x206d7    | 4         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 87        | 15.05%  |
| SandyBridge      | 58        | 10.03%  |
| Haswell          | 53        | 9.17%   |
| IvyBridge        | 44        | 7.61%   |
| Penryn           | 35        | 6.06%   |
| Zen 2            | 26        | 4.5%    |
| TigerLake        | 26        | 4.5%    |
| Zen+             | 24        | 4.15%   |
| Westmere         | 24        | 4.15%   |
| Skylake          | 24        | 4.15%   |
| Broadwell        | 20        | 3.46%   |
| Silvermont       | 17        | 2.94%   |
| Goldmont plus    | 14        | 2.42%   |
| CometLake        | 14        | 2.42%   |
| Excavator        | 13        | 2.25%   |
| Zen 3            | 12        | 2.08%   |
| IceLake          | 12        | 2.08%   |
| Core             | 12        | 2.08%   |
| Zen              | 9         | 1.56%   |
| K10              | 9         | 1.56%   |
| Unknown          | 9         | 1.56%   |
| Piledriver       | 8         | 1.38%   |
| Goldmont         | 7         | 1.21%   |
| Nehalem          | 5         | 0.87%   |
| Tremont          | 3         | 0.52%   |
| Steamroller      | 3         | 0.52%   |
| Puma             | 2         | 0.35%   |
| K10 Llano        | 2         | 0.35%   |
| Jaguar           | 2         | 0.35%   |
| Bulldozer        | 1         | 0.17%   |
| Bonnell          | 1         | 0.17%   |
| Bobcat           | 1         | 0.17%   |
| Alderlake Hybrid | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 363       | 52.84%  |
| AMD                        | 177       | 25.76%  |
| Nvidia                     | 146       | 21.25%  |
| Matrox Electronics Systems | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 6.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 4.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 3.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 21        | 2.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 2.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 2.39%   |
| Intel HD Graphics 620                                                                    | 16        | 2.25%   |
| AMD Renoir                                                                               | 16        | 2.25%   |
| Intel HD Graphics 5500                                                                   | 15        | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.97%   |
| Intel UHD Graphics 620                                                                   | 12        | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.26%   |
| Nvidia C79 [GeForce 9400M]                                                               | 8         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.98%   |
| AMD Lucienne                                                                             | 7         | 0.98%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.84%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.84%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.84%   |
| AMD Cezanne                                                                              | 6         | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.7%    |
| Intel HD Graphics 630                                                                    | 5         | 0.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.7%    |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 5         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 258       | 44.48%  |
| 1 x AMD        | 130       | 22.41%  |
| Intel + Nvidia | 71        | 12.24%  |
| 1 x Nvidia     | 69        | 11.9%   |
| Intel + AMD    | 28        | 4.83%   |
| 2 x AMD        | 15        | 2.59%   |
| AMD + Nvidia   | 4         | 0.69%   |
| Other          | 2         | 0.34%   |
| 2 x Nvidia     | 2         | 0.34%   |
| 1 x Matrox     | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 506       | 87.09%  |
| Proprietary | 71        | 12.22%  |
| Unknown     | 4         | 0.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 302       | 51.62%  |
| 1.01-2.0   | 78        | 13.33%  |
| 0.01-0.5   | 76        | 12.99%  |
| 0.51-1.0   | 56        | 9.57%   |
| 3.01-4.0   | 35        | 5.98%   |
| 7.01-8.0   | 15        | 2.56%   |
| 5.01-6.0   | 15        | 2.56%   |
| 2.01-3.0   | 4         | 0.68%   |
| 8.01-16.0  | 4         | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 78        | 11.96%  |
| LG Display              | 67        | 10.28%  |
| Samsung Electronics     | 65        | 9.97%   |
| Apple                   | 62        | 9.51%   |
| BOE                     | 60        | 9.2%    |
| Chimei Innolux          | 54        | 8.28%   |
| Dell                    | 29        | 4.45%   |
| Goldstar                | 24        | 3.68%   |
| Hewlett-Packard         | 22        | 3.37%   |
| Acer                    | 19        | 2.91%   |
| Lenovo                  | 16        | 2.45%   |
| Sharp                   | 15        | 2.3%    |
| AOC                     | 13        | 1.99%   |
| Philips                 | 12        | 1.84%   |
| BenQ                    | 10        | 1.53%   |
| Chi Mei Optoelectronics | 9         | 1.38%   |
| PANDA                   | 8         | 1.23%   |
| Ancor Communications    | 8         | 1.23%   |
| InfoVision              | 6         | 0.92%   |
| ViewSonic               | 5         | 0.77%   |
| Sony                    | 5         | 0.77%   |
| CSO                     | 5         | 0.77%   |
| Vizio                   | 3         | 0.46%   |
| Unknown                 | 3         | 0.46%   |
| NEC Computers           | 3         | 0.46%   |
| LG Electronics          | 3         | 0.46%   |
| Eizo                    | 3         | 0.46%   |
| AUS                     | 3         | 0.46%   |
| Panasonic               | 2         | 0.31%   |
| Onkyo                   | 2         | 0.31%   |
| Iiyama                  | 2         | 0.31%   |
| HPN                     | 2         | 0.31%   |
| Fujitsu Siemens         | 2         | 0.31%   |
| ___                     | 1         | 0.15%   |
| Vestel                  | 1         | 0.15%   |
| Toshiba                 | 1         | 0.15%   |
| TopView                 | 1         | 0.15%   |
| TMX                     | 1         | 0.15%   |
| Tech Concepts           | 1         | 0.15%   |
| SPC                     | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.89%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 0.89%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.75%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 5         | 0.75%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.6%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.6%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 4         | 0.6%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 0.6%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3         | 0.45%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.45%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.45%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 0.45%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.45%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 3         | 0.45%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 3         | 0.45%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                 | 3         | 0.45%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                 | 3         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.3%    |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 2         | 0.3%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.3%    |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.3%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 2         | 0.3%    |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch             | 2         | 0.3%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.3%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 251       | 39.84%  |
| 1366x768 (WXGA)    | 142       | 22.54%  |
| 3840x2160 (4K)     | 33        | 5.24%   |
| 2560x1440 (QHD)    | 31        | 4.92%   |
| 1440x900 (WXGA+)   | 27        | 4.29%   |
| 1600x900 (HD+)     | 26        | 4.13%   |
| 1680x1050 (WSXGA+) | 25        | 3.97%   |
| 1280x800 (WXGA)    | 16        | 2.54%   |
| 1920x1200 (WUXGA)  | 12        | 1.9%    |
| 1280x1024 (SXGA)   | 10        | 1.59%   |
| 2880x1800          | 8         | 1.27%   |
| 1360x768           | 6         | 0.95%   |
| Unknown            | 5         | 0.79%   |
| 3840x1080          | 4         | 0.63%   |
| 3000x2000          | 4         | 0.63%   |
| 2560x1080          | 4         | 0.63%   |
| 3440x1440          | 3         | 0.48%   |
| 2560x1600          | 3         | 0.48%   |
| 5120x1440          | 2         | 0.32%   |
| 3840x2400          | 2         | 0.32%   |
| 3200x1800 (QHD+)   | 2         | 0.32%   |
| 2736x1824          | 2         | 0.32%   |
| 1920x540           | 2         | 0.32%   |
| 1920x1280          | 2         | 0.32%   |
| 7680x2160          | 1         | 0.16%   |
| 3840x1200          | 1         | 0.16%   |
| 3840x1100          | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 2880x1920          | 1         | 0.16%   |
| 2496x1664          | 1         | 0.16%   |
| 1800x1200          | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 167       | 25.65%  |
| 13      | 91        | 13.98%  |
| 14      | 71        | 10.91%  |
| 24      | 37        | 5.68%   |
| 17      | 33        | 5.07%   |
| 23      | 32        | 4.92%   |
| 27      | 31        | 4.76%   |
| Unknown | 30        | 4.61%   |
| 21      | 23        | 3.53%   |
| 20      | 15        | 2.3%    |
| 31      | 14        | 2.15%   |
| 11      | 14        | 2.15%   |
| 22      | 13        | 2%      |
| 12      | 12        | 1.84%   |
| 18      | 10        | 1.54%   |
| 19      | 9         | 1.38%   |
| 34      | 6         | 0.92%   |
| 16      | 6         | 0.92%   |
| 72      | 4         | 0.61%   |
| 32      | 4         | 0.61%   |
| 84      | 3         | 0.46%   |
| 26      | 3         | 0.46%   |
| 25      | 3         | 0.46%   |
| 65      | 2         | 0.31%   |
| 52      | 2         | 0.31%   |
| 43      | 2         | 0.31%   |
| 33      | 2         | 0.31%   |
| 10      | 2         | 0.31%   |
| 60      | 1         | 0.15%   |
| 55      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 48      | 1         | 0.15%   |
| 47      | 1         | 0.15%   |
| 40      | 1         | 0.15%   |
| 38      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 36      | 1         | 0.15%   |
| 28      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 275       | 43.04%  |
| 501-600     | 95        | 14.87%  |
| 201-300     | 83        | 12.99%  |
| 401-500     | 65        | 10.17%  |
| 351-400     | 38        | 5.95%   |
| Unknown     | 30        | 4.69%   |
| 601-700     | 19        | 2.97%   |
| 701-800     | 13        | 2.03%   |
| 1001-1500   | 9         | 1.41%   |
| 1501-2000   | 7         | 1.1%    |
| 801-900     | 3         | 0.47%   |
| 901-1000    | 2         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 440       | 74.32%  |
| 16/10   | 93        | 15.71%  |
| Unknown | 26        | 4.39%   |
| 3/2     | 14        | 2.36%   |
| 5/4     | 8         | 1.35%   |
| 21/9    | 7         | 1.18%   |
| 6/5     | 1         | 0.17%   |
| 4/3     | 1         | 0.17%   |
| 32/9    | 1         | 0.17%   |
| 3.40    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 166       | 25.82%  |
| 81-90          | 122       | 18.97%  |
| 201-250        | 78        | 12.13%  |
| 71-80          | 41        | 6.38%   |
| 301-350        | 32        | 4.98%   |
| 151-200        | 30        | 4.67%   |
| Unknown        | 30        | 4.67%   |
| 351-500        | 26        | 4.04%   |
| 121-130        | 22        | 3.42%   |
| 251-300        | 21        | 3.27%   |
| 51-60          | 15        | 2.33%   |
| More than 1000 | 14        | 2.18%   |
| 141-150        | 14        | 2.18%   |
| 61-70          | 10        | 1.56%   |
| 501-1000       | 8         | 1.24%   |
| 131-140        | 5         | 0.78%   |
| 111-120        | 5         | 0.78%   |
| 41-50          | 2         | 0.31%   |
| 91-100         | 2         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 191       | 30.08%  |
| 101-120       | 179       | 28.19%  |
| 51-100        | 160       | 25.2%   |
| 161-240       | 40        | 6.3%    |
| Unknown       | 30        | 4.72%   |
| More than 240 | 20        | 3.15%   |
| 1-50          | 15        | 2.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 498       | 84.98%  |
| 2     | 74        | 12.63%  |
| 3     | 11        | 1.88%   |
| 0     | 2         | 0.34%   |
| 4     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 280       | 32.26%  |
| Intel                             | 259       | 29.84%  |
| Qualcomm Atheros                  | 100       | 11.52%  |
| Broadcom                          | 87        | 10.02%  |
| Marvell Technology Group          | 19        | 2.19%   |
| Broadcom Limited                  | 19        | 2.19%   |
| Nvidia                            | 18        | 2.07%   |
| Ralink Technology                 | 10        | 1.15%   |
| Ralink                            | 9         | 1.04%   |
| TP-Link                           | 8         | 0.92%   |
| Samsung Electronics               | 6         | 0.69%   |
| MediaTek                          | 6         | 0.69%   |
| Xiaomi                            | 5         | 0.58%   |
| Sierra Wireless                   | 3         | 0.35%   |
| OPPO Electronics                  | 3         | 0.35%   |
| Huawei Technologies               | 3         | 0.35%   |
| ASIX Electronics                  | 3         | 0.35%   |
| TRENDnet                          | 2         | 0.23%   |
| Linksys                           | 2         | 0.23%   |
| Lenovo                            | 2         | 0.23%   |
| Google                            | 2         | 0.23%   |
| D-Link                            | 2         | 0.23%   |
| Apple                             | 2         | 0.23%   |
| ZyXEL Communications              | 1         | 0.12%   |
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
| AVM                               | 1         | 0.12%   |
| Aquantia                          | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 176       | 17.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 46        | 4.51%   |
| Intel Wi-Fi 6 AX200                                               | 24        | 2.35%   |
| Intel Wi-Fi 6 AX201                                               | 21        | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 20        | 1.96%   |
| Intel Wireless 8260                                               | 17        | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 1.37%   |
| Intel Wireless 8265 / 8275                                        | 14        | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 1.27%   |
| Intel Wireless 7265                                               | 12        | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 1.08%   |
| Nvidia MCP79 Ethernet                                             | 11        | 1.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 11        | 1.08%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 11        | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.98%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 10        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 0.98%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 10        | 0.98%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 10        | 0.98%   |
| Intel Wireless 7260                                               | 9         | 0.88%   |
| Intel I211 Gigabit Network Connection                             | 9         | 0.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 9         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.69%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 7         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 6         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 211       | 40.27%  |
| Qualcomm Atheros                | 83        | 15.84%  |
| Realtek Semiconductor           | 82        | 15.65%  |
| Broadcom                        | 76        | 14.5%   |
| Broadcom Limited                | 18        | 3.44%   |
| Ralink Technology               | 10        | 1.91%   |
| Ralink                          | 9         | 1.72%   |
| TP-Link                         | 8         | 1.53%   |
| MediaTek                        | 4         | 0.76%   |
| Marvell Technology Group        | 4         | 0.76%   |
| Sierra Wireless                 | 3         | 0.57%   |
| TRENDnet                        | 2         | 0.38%   |
| Linksys                         | 2         | 0.38%   |
| D-Link                          | 2         | 0.38%   |
| ZyXEL Communications            | 1         | 0.19%   |
| Sitecom Europe                  | 1         | 0.19%   |
| Qualcomm Atheros Communications | 1         | 0.19%   |
| Qualcomm                        | 1         | 0.19%   |
| Microsoft                       | 1         | 0.19%   |
| LG Electronics                  | 1         | 0.19%   |
| Fibocom                         | 1         | 0.19%   |
| D-Link System                   | 1         | 0.19%   |
| AVM                             | 1         | 0.19%   |
| AboCom Systems                  | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 24        | 4.55%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 3.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 20        | 3.8%    |
| Intel Wireless 8260                                            | 17        | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 3.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 2.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 2.66%   |
| Intel Wireless 8265 / 8275                                     | 14        | 2.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 2.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 13        | 2.47%   |
| Intel Wireless 7265                                            | 12        | 2.28%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 11        | 2.09%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 11        | 2.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 1.9%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 10        | 1.9%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 1.9%    |
| Intel Wireless 7260                                            | 9         | 1.71%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 9         | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.33%   |
| Ralink MT7601U Wireless Adapter                                | 7         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 1.14%   |
| Intel Wireless 3165                                            | 6         | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 5         | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 0.95%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 0.95%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 0.95%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 5         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 247       | 50.93%  |
| Intel                      | 113       | 23.3%   |
| Broadcom                   | 29        | 5.98%   |
| Qualcomm Atheros           | 28        | 5.77%   |
| Nvidia                     | 18        | 3.71%   |
| Marvell Technology Group   | 15        | 3.09%   |
| Samsung Electronics        | 6         | 1.24%   |
| Xiaomi                     | 5         | 1.03%   |
| OPPO Electronics           | 3         | 0.62%   |
| ASIX Electronics           | 3         | 0.62%   |
| MediaTek                   | 2         | 0.41%   |
| Lenovo                     | 2         | 0.41%   |
| Huawei Technologies        | 2         | 0.41%   |
| Google                     | 2         | 0.41%   |
| Broadcom Limited           | 2         | 0.41%   |
| Apple                      | 2         | 0.41%   |
| ZTE WCDMA Technologies MSM | 1         | 0.21%   |
| vivo                       | 1         | 0.21%   |
| Motorola PCS               | 1         | 0.21%   |
| JMicron Technology         | 1         | 0.21%   |
| Hewlett-Packard            | 1         | 0.21%   |
| Aquantia                   | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 176       | 35.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 46        | 9.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 21        | 4.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 13        | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 2.24%   |
| Nvidia MCP79 Ethernet                                                          | 11        | 2.24%   |
| Realtek RTL8125 2.5GbE Controller                                              | 10        | 2.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 10        | 2.04%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 1.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.63%   |
| Intel Ethernet Connection (2) I219-V                                           | 7         | 1.43%   |
| Intel Ethernet Controller I225-V                                               | 6         | 1.22%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 1.22%   |
| Nvidia MCP61 Ethernet                                                          | 5         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.02%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 4         | 0.82%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.82%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.61%   |
| OPPO RMX2180                                                                   | 3         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.61%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 0.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 3         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.41%   |
| MediaTek TECNO Pouvoir 3 Air                                                   | 2         | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 498       | 52.04%  |
| Ethernet | 456       | 47.65%  |
| Modem    | 2         | 0.21%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 387       | 66.96%  |
| Ethernet | 191       | 33.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 329       | 56.72%  |
| 1     | 230       | 39.66%  |
| 3     | 11        | 1.9%    |
| 0     | 9         | 1.55%   |
| 4     | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 409       | 70.15%  |
| Yes  | 174       | 29.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 186       | 41.06%  |
| Apple                           | 67        | 14.79%  |
| Realtek Semiconductor           | 47        | 10.38%  |
| Qualcomm Atheros Communications | 28        | 6.18%   |
| Broadcom                        | 23        | 5.08%   |
| Cambridge Silicon Radio         | 19        | 4.19%   |
| Lite-On Technology              | 17        | 3.75%   |
| IMC Networks                    | 17        | 3.75%   |
| Foxconn / Hon Hai               | 13        | 2.87%   |
| Toshiba                         | 6         | 1.32%   |
| Ralink                          | 6         | 1.32%   |
| Hewlett-Packard                 | 6         | 1.32%   |
| Marvell Semiconductor           | 5         | 1.1%    |
| Realtek                         | 4         | 0.88%   |
| ASUSTek Computer                | 4         | 0.88%   |
| Dell                            | 3         | 0.66%   |
| Qcom                            | 1         | 0.22%   |
| Edimax Technology               | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 67        | 14.79%  |
| Intel AX201 Bluetooth                               | 41        | 9.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 33        | 7.28%   |
| Realtek Bluetooth Radio                             | 28        | 6.18%   |
| Apple Bluetooth Host Controller                     | 27        | 5.96%   |
| Intel AX200 Bluetooth                               | 23        | 5.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19        | 4.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 3.97%   |
| Apple Bluetooth USB Host Controller                 | 17        | 3.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 2.65%   |
| Apple Bluetooth HCI                                 | 12        | 2.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 11        | 2.43%   |
| Ralink RT3290 Bluetooth                             | 6         | 1.32%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.32%   |
| Intel AX210 Bluetooth                               | 6         | 1.32%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.1%    |
| IMC Networks Bluetooth Device                       | 5         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 1.1%    |
| Realtek Bluetooth Radio                             | 4         | 0.88%   |
| Lite-On Bluetooth Device                            | 4         | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.88%   |
| IMC Networks Bluetooth Radio                        | 4         | 0.88%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.88%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.88%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.88%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.66%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.66%   |
| Marvell Bluetooth and Wireless LAN Composite        | 3         | 0.66%   |
| IMC Networks Wireless_Device                        | 3         | 0.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3         | 0.66%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.66%   |
| Toshiba RT Bluetooth Radio                          | 2         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.44%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 433       | 57.05%  |
| AMD                      | 159       | 20.95%  |
| Nvidia                   | 105       | 13.83%  |
| C-Media Electronics      | 14        | 1.84%   |
| Creative Labs            | 8         | 1.05%   |
| Logitech                 | 7         | 0.92%   |
| Texas Instruments        | 2         | 0.26%   |
| Realtek Semiconductor    | 2         | 0.26%   |
| Generalplus Technology   | 2         | 0.26%   |
| Focusrite-Novation       | 2         | 0.26%   |
| ESS Technology           | 2         | 0.26%   |
| Corsair                  | 2         | 0.26%   |
| Unknown                  | 1         | 0.13%   |
| Tenx Technology          | 1         | 0.13%   |
| SteelSeries ApS          | 1         | 0.13%   |
| Sony                     | 1         | 0.13%   |
| Razer USA                | 1         | 0.13%   |
| No brand                 | 1         | 0.13%   |
| Native Instruments       | 1         | 0.13%   |
| Microsoft                | 1         | 0.13%   |
| Micro Star International | 1         | 0.13%   |
| Huawei Technologies      | 1         | 0.13%   |
| Goldvish                 | 1         | 0.13%   |
| GN Netcom                | 1         | 0.13%   |
| Fry's Electronics        | 1         | 0.13%   |
| Edifier Technology       | 1         | 0.13%   |
| DSEA A/S                 | 1         | 0.13%   |
| Dell                     | 1         | 0.13%   |
| Creative Technology      | 1         | 0.13%   |
| BEHRINGER International  | 1         | 0.13%   |
| ASUSTek Computer         | 1         | 0.13%   |
| Apple                    | 1         | 0.13%   |
| Anlya.cn                 | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 54        | 5.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 52        | 5.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 48        | 5.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 43        | 4.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 3.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 27        | 2.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 26        | 2.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26        | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 24        | 2.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 2.28%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 2.28%   |
| Intel Broadwell-U Audio Controller                                                                | 20        | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 16        | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 1.63%   |
| AMD FCH Azalia Controller                                                                         | 15        | 1.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 1.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.52%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 1.52%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 1.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 12        | 1.3%    |
| Nvidia MCP79 High Definition Audio                                                                | 11        | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.09%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 10        | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 10        | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.09%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 0.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 0.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 0.98%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 9         | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.76%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 0.76%   |
| AMD High Definition Audio Controller                                                              | 7         | 0.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 31.03%  |
| SK hynix            | 24        | 20.69%  |
| Micron Technology   | 14        | 12.07%  |
| Kingston            | 8         | 6.9%    |
| Unknown             | 7         | 6.03%   |
| Crucial             | 4         | 3.45%   |
| A-DATA Technology   | 4         | 3.45%   |
| Unknown (ABCD)      | 3         | 2.59%   |
| G.Skill             | 3         | 2.59%   |
| Corsair             | 3         | 2.59%   |
| Ramaxel Technology  | 2         | 1.72%   |
| Unknown (0x038A)    | 1         | 0.86%   |
| Transcend           | 1         | 0.86%   |
| SHARETRONIC         | 1         | 0.86%   |
| PNY                 | 1         | 0.86%   |
| Patriot             | 1         | 0.86%   |
| Hewlett-Packard     | 1         | 0.86%   |
| GSkill              | 1         | 0.86%   |
| Elpida              | 1         | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s     | 3         | 2.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 3         | 2.4%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s               | 3         | 2.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                | 3         | 2.4%    |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 2         | 1.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s            | 2         | 1.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                | 2         | 1.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                | 2         | 1.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                | 2         | 1.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                | 2         | 1.6%    |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s                | 2         | 1.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                            | 1         | 0.8%    |
| Unknown RAM Module 8192MB SODIMM DDR3                                | 1         | 0.8%    |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                         | 1         | 0.8%    |
| Unknown RAM Module 8192MB DIMM 1066MT/s                              | 1         | 0.8%    |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                            | 1         | 0.8%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 1         | 0.8%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                       | 1         | 0.8%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                       | 1         | 0.8%    |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s                   | 1         | 0.8%    |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s             | 1         | 0.8%    |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                    | 1         | 0.8%    |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.8%    |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.8%    |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                 | 1         | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 0.8%    |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s                | 1         | 0.8%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 0.8%    |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s              | 1         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 0.8%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 0.8%    |
| SK hynix RAM HMP351S6AFR8C-S6 4096MB SODIMM DDR2 800MT/s             | 1         | 0.8%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s              | 1         | 0.8%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 0.8%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 0.8%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s               | 1         | 0.8%    |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s               | 1         | 0.8%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.8%    |
| SK hynix RAM H9HCNNNFAMALTR-NEE 16384MB Row Of Chips LPDDR4 3733MT/s | 1         | 0.8%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s           | 1         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 48        | 47.52%  |
| DDR3    | 35        | 34.65%  |
| LPDDR4  | 11        | 10.89%  |
| LPDDR3  | 3         | 2.97%   |
| DDR2    | 2         | 1.98%   |
| Unknown | 2         | 1.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 70        | 69.31%  |
| DIMM         | 20        | 19.8%   |
| Row Of Chips | 10        | 9.9%    |
| Chip         | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 48        | 42.48%  |
| 4096  | 36        | 31.86%  |
| 16384 | 15        | 13.27%  |
| 2048  | 12        | 10.62%  |
| 32768 | 2         | 1.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 23        | 20.91%  |
| 2667    | 19        | 17.27%  |
| 3200    | 17        | 15.45%  |
| 2400    | 9         | 8.18%   |
| 1333    | 6         | 5.45%   |
| 4267    | 5         | 4.55%   |
| 2133    | 5         | 4.55%   |
| 1066    | 4         | 3.64%   |
| 8400    | 3         | 2.73%   |
| 3600    | 2         | 1.82%   |
| 3266    | 2         | 1.82%   |
| 1867    | 2         | 1.82%   |
| 1334    | 2         | 1.82%   |
| 4800    | 1         | 0.91%   |
| 4266    | 1         | 0.91%   |
| 3733    | 1         | 0.91%   |
| 3400    | 1         | 0.91%   |
| 2800    | 1         | 0.91%   |
| 2666    | 1         | 0.91%   |
| 2200    | 1         | 0.91%   |
| 1800    | 1         | 0.91%   |
| 800     | 1         | 0.91%   |
| 667     | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

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
| Chicony Electronics                    | 82        | 20.05%  |
| Apple                                  | 50        | 12.22%  |
| IMC Networks                           | 45        | 11%     |
| Realtek Semiconductor                  | 32        | 7.82%   |
| Acer                                   | 29        | 7.09%   |
| Quanta                                 | 26        | 6.36%   |
| Microdia                               | 25        | 6.11%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 3.91%   |
| Sunplus Innovation Technology          | 15        | 3.67%   |
| Suyin                                  | 14        | 3.42%   |
| Logitech                               | 12        | 2.93%   |
| Syntek                                 | 10        | 2.44%   |
| Alcor Micro                            | 9         | 2.2%    |
| Silicon Motion                         | 6         | 1.47%   |
| Microsoft                              | 5         | 1.22%   |
| Luxvisions Innotech Limited            | 4         | 0.98%   |
| Lenovo                                 | 4         | 0.98%   |
| Ricoh                                  | 2         | 0.49%   |
| Primax Electronics                     | 2         | 0.49%   |
| Lite-On Technology                     | 2         | 0.49%   |
| KYE Systems (Mouse Systems)            | 2         | 0.49%   |
| Foxconn / Hon Hai                      | 2         | 0.49%   |
| Z-Star Microelectronics                | 1         | 0.24%   |
| Y Media                                | 1         | 0.24%   |
| Unknown                                | 1         | 0.24%   |
| SunplusIT                              | 1         | 0.24%   |
| Sony                                   | 1         | 0.24%   |
| Samsung Electronics                    | 1         | 0.24%   |
| Razer USA                              | 1         | 0.24%   |
| kingcome                               | 1         | 0.24%   |
| Jieli Technology                       | 1         | 0.24%   |
| Importek                               | 1         | 0.24%   |
| Google                                 | 1         | 0.24%   |
| Generalplus Technology                 | 1         | 0.24%   |
| Cubeternet                             | 1         | 0.24%   |
| ANYKA                                  | 1         | 0.24%   |
| ALi                                    | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Apple Built-in iSight                            | 23        | 5.56%   |
| Chicony Integrated Camera                        | 22        | 5.31%   |
| IMC Networks Integrated Camera                   | 14        | 3.38%   |
| IMC Networks USB2.0 HD UVC WebCam                | 13        | 3.14%   |
| Realtek Integrated_Webcam_HD                     | 9         | 2.17%   |
| Microdia Integrated_Webcam_HD                    | 9         | 2.17%   |
| Chicony HD Webcam                                | 9         | 2.17%   |
| Syntek Integrated Camera                         | 8         | 1.93%   |
| Apple FaceTime HD Camera                         | 8         | 1.93%   |
| Apple iPhone 5/5C/5S/6/SE                        | 7         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 6         | 1.45%   |
| Apple FaceTime HD Camera (Built-in)              | 6         | 1.45%   |
| Sunplus Integrated_Webcam_HD                     | 5         | 1.21%   |
| Quanta HP TrueVision HD Camera                   | 5         | 1.21%   |
| Chicony USB 2.0 Camera                           | 5         | 1.21%   |
| Acer Integrated Camera                           | 5         | 1.21%   |
| Realtek USB2.0 HD UVC WebCam                     | 4         | 0.97%   |
| Realtek USB Camera                               | 4         | 0.97%   |
| Quanta VGA WebCam                                | 4         | 0.97%   |
| Quanta HP Webcam                                 | 4         | 0.97%   |
| Quanta HD User Facing                            | 4         | 0.97%   |
| Apple FaceTime Camera                            | 4         | 0.97%   |
| Acer Lenovo EasyCamera                           | 4         | 0.97%   |
| Acer HD Webcam                                   | 4         | 0.97%   |
| Realtek USB2.0 VGA UVC WebCam                    | 3         | 0.72%   |
| Realtek Integrated Webcam                        | 3         | 0.72%   |
| IMC Networks USB2.0 UVC HD Webcam                | 3         | 0.72%   |
| IMC Networks ov9734_azurewave_camera             | 3         | 0.72%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 0.72%   |
| Chicony HP Truevision HD                         | 3         | 0.72%   |
| Chicony HP HD Webcam [Fixed]                     | 3         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 3         | 0.72%   |
| Alcor Micro USB 2.0 WebCamera                    | 3         | 0.72%   |
| Acer HD Camera                                   | 3         | 0.72%   |
| Acer EasyCamera                                  | 3         | 0.72%   |
| Syntek EasyCamera                                | 2         | 0.48%   |
| Suyin Integrated_Webcam_HD                       | 2         | 0.48%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 2         | 0.48%   |
| Sunplus Asus Webcam                              | 2         | 0.48%   |
| Realtek Built-In Video Camera                    | 2         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 23        | 33.82%  |
| Validity Sensors           | 18        | 26.47%  |
| Shenzhen Goodix Technology | 12        | 17.65%  |
| LighTuning Technology      | 7         | 10.29%  |
| Upek                       | 5         | 7.35%   |
| Elan Microelectronics      | 2         | 2.94%   |
| AuthenTec                  | 1         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 10        | 14.71%  |
| Unknown                                                    | 9         | 13.24%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 5         | 7.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 7.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 7.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 5.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 4.41%   |
| Validity Sensors VFS491                                    | 3         | 4.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 4.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 4.41%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 2.94%   |
| LighTuning EgisTec_ES603                                   | 2         | 2.94%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 1.47%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.47%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.47%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.47%   |
| Synaptics  WBDI                                            | 1         | 1.47%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.47%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.47%   |
| Shenzhen Goodix FingerPrint                                | 1         | 1.47%   |
| LighTuning Fingerprint Sensor                              | 1         | 1.47%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.47%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.47%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.47%   |

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
| 0     | 431       | 73.93%  |
| 1     | 121       | 20.75%  |
| 2     | 29        | 4.97%   |
| 4     | 1         | 0.17%   |
| 3     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 67        | 37.02%  |
| Net/wireless             | 30        | 16.57%  |
| Multimedia controller    | 23        | 12.71%  |
| Chipcard                 | 19        | 10.5%   |
| Graphics card            | 16        | 8.84%   |
| Bluetooth                | 8         | 4.42%   |
| Camera                   | 4         | 2.21%   |
| Sound                    | 3         | 1.66%   |
| Net/ethernet             | 3         | 1.66%   |
| Card reader              | 3         | 1.66%   |
| Unassigned class         | 2         | 1.1%    |
| Storage/ide              | 1         | 0.55%   |
| Storage                  | 1         | 0.55%   |
| Communication controller | 1         | 0.55%   |

