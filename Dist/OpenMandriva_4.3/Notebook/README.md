OpenMandriva 4.3 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

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

Total: 921

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3793               | [9d2383d1f8](https://linux-hardware.org/?probe=9d2383d1f8) | Apr 30, 2022 |
| HP            | 650                         | [1332a3196c](https://linux-hardware.org/?probe=1332a3196c) | Apr 30, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | Z50-70 20354                | [f253fe8221](https://linux-hardware.org/?probe=f253fe8221) | Apr 30, 2022 |
| Apple         | MacBookAir5,1               | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Philco        | 14I                         | [03bb0fdeef](https://linux-hardware.org/?probe=03bb0fdeef) | Apr 30, 2022 |
| HP            | Laptop 17-by4xxx            | [767590ac38](https://linux-hardware.org/?probe=767590ac38) | Apr 29, 2022 |
| ASUSTek       | S551LN                      | [a5f0e1cee7](https://linux-hardware.org/?probe=a5f0e1cee7) | Apr 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [2c8a1c2444](https://linux-hardware.org/?probe=2c8a1c2444) | Apr 29, 2022 |
| TUXEDO        | Book BM15 Gen10             | [45b5b1bba9](https://linux-hardware.org/?probe=45b5b1bba9) | Apr 29, 2022 |
| Dell          | Inspiron 3593               | [54087491d8](https://linux-hardware.org/?probe=54087491d8) | Apr 28, 2022 |
| Acer          | Extensa 5635G               | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| HUAWEI        | NBM-WXX9                    | [4f15ab06cc](https://linux-hardware.org/?probe=4f15ab06cc) | Apr 28, 2022 |
| Dell          | Latitude E4310              | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | X505BA                      | [30972759d1](https://linux-hardware.org/?probe=30972759d1) | Apr 27, 2022 |
| Notebook      | W130SV                      | [a88535a3a5](https://linux-hardware.org/?probe=a88535a3a5) | Apr 27, 2022 |
| Positivo      | S14SL01                     | [f8bdbe707d](https://linux-hardware.org/?probe=f8bdbe707d) | Apr 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [14f1d071ae](https://linux-hardware.org/?probe=14f1d071ae) | Apr 26, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Intel         | Unknown                     | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [64cd863479](https://linux-hardware.org/?probe=64cd863479) | Apr 26, 2022 |
| Medion        | S17402 MD63000              | [fe73d0023a](https://linux-hardware.org/?probe=fe73d0023a) | Apr 25, 2022 |
| Dell          | Latitude E6410              | [bc9515e4a7](https://linux-hardware.org/?probe=bc9515e4a7) | Apr 25, 2022 |
| Dell          | Inspiron 3537               | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| Dell          | Latitude E7270              | [d8dedbd4f6](https://linux-hardware.org/?probe=d8dedbd4f6) | Apr 25, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [7423afe5a1](https://linux-hardware.org/?probe=7423afe5a1) | Apr 25, 2022 |
| Dell          | Inspiron 7460               | [6a67f6de58](https://linux-hardware.org/?probe=6a67f6de58) | Apr 25, 2022 |
| Fujitsu       | FMVA06004                   | [4c63e1bcc2](https://linux-hardware.org/?probe=4c63e1bcc2) | Apr 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [2fcb2f9b19](https://linux-hardware.org/?probe=2fcb2f9b19) | Apr 24, 2022 |
| Lenovo        | ThinkPad W520 4284BL9       | [a7dd5a566e](https://linux-hardware.org/?probe=a7dd5a566e) | Apr 24, 2022 |
| Lenovo        | ThinkPad X220 42875TU       | [6748d74892](https://linux-hardware.org/?probe=6748d74892) | Apr 24, 2022 |
| Lenovo        | ThinkPad E460 20ET000YLM    | [c82beac367](https://linux-hardware.org/?probe=c82beac367) | Apr 23, 2022 |
| ASUSTek       | X705UQR                     | [e4a27bf740](https://linux-hardware.org/?probe=e4a27bf740) | Apr 23, 2022 |
| Chuwi         | AeroBook Pro                | [a123315898](https://linux-hardware.org/?probe=a123315898) | Apr 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3e3f727deb](https://linux-hardware.org/?probe=3e3f727deb) | Apr 23, 2022 |
| Acer          | Aspire V5-571G              | [e76a1e5467](https://linux-hardware.org/?probe=e76a1e5467) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad X220 42875TU       | [2dd8baa591](https://linux-hardware.org/?probe=2dd8baa591) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| HP            | Pavilion 15                 | [a1b094c360](https://linux-hardware.org/?probe=a1b094c360) | Apr 22, 2022 |
| Acer          | Aspire A515-54G             | [9eeb0ced39](https://linux-hardware.org/?probe=9eeb0ced39) | Apr 22, 2022 |
| Dell          | Precision 3560              | [cc7a9c5fe2](https://linux-hardware.org/?probe=cc7a9c5fe2) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| Dell          | Inspiron 1545               | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| Toshiba       | Satellite C850-A786         | [e57aca482e](https://linux-hardware.org/?probe=e57aca482e) | Apr 22, 2022 |
| HP            | ProBook 4540s               | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |
| MSI           | GE62 6QD                    | [d66e41c50e](https://linux-hardware.org/?probe=d66e41c50e) | Apr 22, 2022 |
| Apple         | MacBookAir4,2               | [1535fd1e85](https://linux-hardware.org/?probe=1535fd1e85) | Apr 21, 2022 |
| Dell          | Latitude 3310               | [3130a4d7c3](https://linux-hardware.org/?probe=3130a4d7c3) | Apr 21, 2022 |
| Acer          | Aspire E5-551G              | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| Philco        | Unknown                     | [16719246ff](https://linux-hardware.org/?probe=16719246ff) | Apr 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [9adfada605](https://linux-hardware.org/?probe=9adfada605) | Apr 20, 2022 |
| Dell          | G3 3579                     | [a85e01d9d0](https://linux-hardware.org/?probe=a85e01d9d0) | Apr 20, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b1eb98dd6a](https://linux-hardware.org/?probe=b1eb98dd6a) | Apr 19, 2022 |
| Toshiba       | dynabook Satellite B552/... | [60e6d780aa](https://linux-hardware.org/?probe=60e6d780aa) | Apr 19, 2022 |
| Dell          | Latitude E5470              | [da9241c331](https://linux-hardware.org/?probe=da9241c331) | Apr 19, 2022 |
| HP            | Compaq 6720s                | [23c39d626c](https://linux-hardware.org/?probe=23c39d626c) | Apr 19, 2022 |
| Toshiba       | Satellite Pro C660          | [678e3209cb](https://linux-hardware.org/?probe=678e3209cb) | Apr 18, 2022 |
| Acer          | Aspire E5-571G              | [f37cea6c6f](https://linux-hardware.org/?probe=f37cea6c6f) | Apr 18, 2022 |
| Toshiba       | Satellite P200              | [f7726b9903](https://linux-hardware.org/?probe=f7726b9903) | Apr 17, 2022 |
| HP            | Unknown                     | [7732ecb02d](https://linux-hardware.org/?probe=7732ecb02d) | Apr 17, 2022 |
| Apple         | MacBookPro5,4               | [918fef81c3](https://linux-hardware.org/?probe=918fef81c3) | Apr 17, 2022 |
| Dell          | Precision M6800             | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| Dell          | Latitude E6320              | [84523d9bd9](https://linux-hardware.org/?probe=84523d9bd9) | Apr 16, 2022 |
| Acer          | Nitro AN517-41              | [e955d40057](https://linux-hardware.org/?probe=e955d40057) | Apr 16, 2022 |
| ASUSTek       | P52F                        | [0cb00534d0](https://linux-hardware.org/?probe=0cb00534d0) | Apr 16, 2022 |
| Acer          | Aspire R3-131T              | [776575ecdb](https://linux-hardware.org/?probe=776575ecdb) | Apr 16, 2022 |
| Gigabyte      | G5 GD                       | [2b2833576e](https://linux-hardware.org/?probe=2b2833576e) | Apr 16, 2022 |
| Acer          | Aspire 5750G                | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Acer          | Aspire 5735                 | [e43434e15c](https://linux-hardware.org/?probe=e43434e15c) | Apr 15, 2022 |
| Samsung       | 700T                        | [ff97fa9856](https://linux-hardware.org/?probe=ff97fa9856) | Apr 15, 2022 |
| Dell          | Latitude E6530              | [d6f985e2ca](https://linux-hardware.org/?probe=d6f985e2ca) | Apr 15, 2022 |
| Sony          | VPCEE23FX                   | [4c7634a096](https://linux-hardware.org/?probe=4c7634a096) | Apr 15, 2022 |
| Fujitsu       | LIFEBOOK E743               | [43ee1b9237](https://linux-hardware.org/?probe=43ee1b9237) | Apr 14, 2022 |
| Sony          | VGN-FZ11M                   | [23731be3a1](https://linux-hardware.org/?probe=23731be3a1) | Apr 14, 2022 |
| HP            | ProBook 650 G5              | [db89b961c4](https://linux-hardware.org/?probe=db89b961c4) | Apr 14, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3e5c6ada15](https://linux-hardware.org/?probe=3e5c6ada15) | Apr 14, 2022 |
| Acer          | Aspire A717-71G             | [7bf2eeb5cc](https://linux-hardware.org/?probe=7bf2eeb5cc) | Apr 14, 2022 |
| Dell          | Latitude E6500              | [d88c77328a](https://linux-hardware.org/?probe=d88c77328a) | Apr 13, 2022 |
| Sony          | SVE1713A1EW                 | [fda4c51d3c](https://linux-hardware.org/?probe=fda4c51d3c) | Apr 13, 2022 |
| HP            | Pavilion dv6500             | [31d34f3d2d](https://linux-hardware.org/?probe=31d34f3d2d) | Apr 13, 2022 |
| Acer          | Aspire R3-131T              | [44a4c66cfe](https://linux-hardware.org/?probe=44a4c66cfe) | Apr 13, 2022 |
| Lenovo        | G405 20239                  | [ab55cb1e13](https://linux-hardware.org/?probe=ab55cb1e13) | Apr 13, 2022 |
| Acer          | Nitro AN515-41              | [b938e715f4](https://linux-hardware.org/?probe=b938e715f4) | Apr 13, 2022 |
| HP            | Laptop 15-db0xxx            | [5adcbc1b64](https://linux-hardware.org/?probe=5adcbc1b64) | Apr 13, 2022 |
| Samsung       | 750XDA                      | [e2c10772c0](https://linux-hardware.org/?probe=e2c10772c0) | Apr 13, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [28897f0c7b](https://linux-hardware.org/?probe=28897f0c7b) | Apr 13, 2022 |
| Acer          | Extensa 5635Z               | [641be7bf1b](https://linux-hardware.org/?probe=641be7bf1b) | Apr 12, 2022 |
| HP            | Presario CQ57               | [ece28d4d57](https://linux-hardware.org/?probe=ece28d4d57) | Apr 12, 2022 |
| Positivo      | Mobile                      | [1bd294322c](https://linux-hardware.org/?probe=1bd294322c) | Apr 12, 2022 |
| Lenovo        | 3000 V200 076472G           | [11a06d9b03](https://linux-hardware.org/?probe=11a06d9b03) | Apr 10, 2022 |
| ASUSTek       | GL702VM                     | [70ff5129b4](https://linux-hardware.org/?probe=70ff5129b4) | Apr 10, 2022 |
| Apple         | MacBookPro9,2               | [9ec146cb7c](https://linux-hardware.org/?probe=9ec146cb7c) | Apr 10, 2022 |
| HP            | 15                          | [43254accc2](https://linux-hardware.org/?probe=43254accc2) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [34b32b5b14](https://linux-hardware.org/?probe=34b32b5b14) | Apr 10, 2022 |
| Acer          | Aspire E5-575G              | [de3e230ca3](https://linux-hardware.org/?probe=de3e230ca3) | Apr 10, 2022 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [eb69184ad7](https://linux-hardware.org/?probe=eb69184ad7) | Apr 10, 2022 |
| HP            | Notebook                    | [4ffd4d11a5](https://linux-hardware.org/?probe=4ffd4d11a5) | Apr 09, 2022 |
| ASUSTek       | X555LJ                      | [e7e9bc2b60](https://linux-hardware.org/?probe=e7e9bc2b60) | Apr 09, 2022 |
| Apple         | MacBook5,1                  | [dc76bbdce6](https://linux-hardware.org/?probe=dc76bbdce6) | Apr 09, 2022 |
| Acer          | Aspire R3-131T              | [15f16fd968](https://linux-hardware.org/?probe=15f16fd968) | Apr 08, 2022 |
| HP            | ProBook 650 G1              | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| Apple         | MacBookPro9,2               | [8ae799c372](https://linux-hardware.org/?probe=8ae799c372) | Apr 08, 2022 |
| Dell          | Latitude E5500              | [485521f38b](https://linux-hardware.org/?probe=485521f38b) | Apr 08, 2022 |
| ASUSTek       | X541SA                      | [1d7a301fe2](https://linux-hardware.org/?probe=1d7a301fe2) | Apr 08, 2022 |
| Acer          | Aspire A315-54              | [596a2a878c](https://linux-hardware.org/?probe=596a2a878c) | Apr 08, 2022 |
| Positivo      | NB50TH                      | [8b6dbaa2a6](https://linux-hardware.org/?probe=8b6dbaa2a6) | Apr 08, 2022 |
| Toshiba       | TECRA A10                   | [b062d23fb7](https://linux-hardware.org/?probe=b062d23fb7) | Apr 07, 2022 |
| Dell          | Latitude E4310              | [e89d84e0dd](https://linux-hardware.org/?probe=e89d84e0dd) | Apr 07, 2022 |
| HP            | Laptop 17-by0xxx            | [40d9656aec](https://linux-hardware.org/?probe=40d9656aec) | Apr 07, 2022 |
| ASUSTek       | X556UQ                      | [ee38be8ddd](https://linux-hardware.org/?probe=ee38be8ddd) | Apr 07, 2022 |
| HP            | Laptop 14q-cy0xxx           | [625bad986e](https://linux-hardware.org/?probe=625bad986e) | Apr 07, 2022 |
| Positivo      | S14SL01                     | [092f7c7d2b](https://linux-hardware.org/?probe=092f7c7d2b) | Apr 07, 2022 |
| HP            | 2000                        | [e4610bcc0e](https://linux-hardware.org/?probe=e4610bcc0e) | Apr 07, 2022 |
| ARKA          | BOOK                        | [44809cec7b](https://linux-hardware.org/?probe=44809cec7b) | Apr 06, 2022 |
| Toshiba       | Satellite A350D             | [ea021d7947](https://linux-hardware.org/?probe=ea021d7947) | Apr 06, 2022 |
| ASUSTek       | K52Jc                       | [645adad8a7](https://linux-hardware.org/?probe=645adad8a7) | Apr 06, 2022 |
| Acer          | Aspire xxxx                 | [c389f4acb2](https://linux-hardware.org/?probe=c389f4acb2) | Apr 06, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [7ba2d85c09](https://linux-hardware.org/?probe=7ba2d85c09) | Apr 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3719a80289](https://linux-hardware.org/?probe=3719a80289) | Apr 06, 2022 |
| Toshiba       | dynabook R73/BN             | [af1ad57286](https://linux-hardware.org/?probe=af1ad57286) | Apr 06, 2022 |
| Apple         | MacBookAir4,2               | [0c1f8b4efe](https://linux-hardware.org/?probe=0c1f8b4efe) | Apr 05, 2022 |
| Lenovo        | V145-15AST 81MT             | [ee0a7bc711](https://linux-hardware.org/?probe=ee0a7bc711) | Apr 05, 2022 |
| Dell          | Latitude 3189               | [326c734059](https://linux-hardware.org/?probe=326c734059) | Apr 05, 2022 |
| Dell          | Latitude 3310               | [69ee7c1eaf](https://linux-hardware.org/?probe=69ee7c1eaf) | Apr 05, 2022 |
| Philco        | 14H                         | [4408057803](https://linux-hardware.org/?probe=4408057803) | Apr 04, 2022 |
| Fujitsu       | LIFEBOOK S752               | [307e875610](https://linux-hardware.org/?probe=307e875610) | Apr 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [952a71b37e](https://linux-hardware.org/?probe=952a71b37e) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [4fdc33f1a2](https://linux-hardware.org/?probe=4fdc33f1a2) | Apr 04, 2022 |
| HP            | Pavilion 14                 | [136105017c](https://linux-hardware.org/?probe=136105017c) | Apr 04, 2022 |
| AWOW          | AK41                        | [f491f6f0fa](https://linux-hardware.org/?probe=f491f6f0fa) | Apr 04, 2022 |
| HP            | ProBook 450 G5              | [3aa8c7cbc6](https://linux-hardware.org/?probe=3aa8c7cbc6) | Apr 04, 2022 |
| ASUSTek       | X455YA                      | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Dell          | Inspiron N5110              | [cd682e107d](https://linux-hardware.org/?probe=cd682e107d) | Apr 03, 2022 |
| Lenovo        | ThinkPad X100e 0022CTO      | [ad4b7e6509](https://linux-hardware.org/?probe=ad4b7e6509) | Apr 03, 2022 |
| Toshiba       | Satellite S855D             | [45b97d03ed](https://linux-hardware.org/?probe=45b97d03ed) | Apr 03, 2022 |
| Dell          | XPS 15 9510                 | [ca9b5c03cb](https://linux-hardware.org/?probe=ca9b5c03cb) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Dell          | Latitude E6420              | [41c4a5b886](https://linux-hardware.org/?probe=41c4a5b886) | Apr 02, 2022 |
| Fujitsu       | LIFEBOOK P701               | [5789c0842c](https://linux-hardware.org/?probe=5789c0842c) | Apr 02, 2022 |
| HP            | 255 G7 Notebook PC          | [a7d794c2d8](https://linux-hardware.org/?probe=a7d794c2d8) | Apr 02, 2022 |
| HP            | Elite x2 1012 G1            | [6c5dee9e74](https://linux-hardware.org/?probe=6c5dee9e74) | Apr 02, 2022 |
| Lenovo        | ThinkPad X61 7675LG2        | [bcbd5eb3f6](https://linux-hardware.org/?probe=bcbd5eb3f6) | Apr 01, 2022 |
| HP            | 255 G7 Notebook PC          | [290217f248](https://linux-hardware.org/?probe=290217f248) | Apr 01, 2022 |
| HP            | Laptop 15-da0xxx            | [b73099e091](https://linux-hardware.org/?probe=b73099e091) | Apr 01, 2022 |
| Acer          | Aspire E5-773G              | [b43b436e59](https://linux-hardware.org/?probe=b43b436e59) | Mar 31, 2022 |
| Dell          | Latitude 3189               | [36115f4eb5](https://linux-hardware.org/?probe=36115f4eb5) | Mar 31, 2022 |
| Dell          | Latitude E6230              | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [f236b5007a](https://linux-hardware.org/?probe=f236b5007a) | Mar 31, 2022 |
| Lenovo        | V15-IIL 82C5                | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| HP            | Pavilion g7                 | [a162ae9ffa](https://linux-hardware.org/?probe=a162ae9ffa) | Mar 30, 2022 |
| HP            | Pavilion dv5                | [29096b57ad](https://linux-hardware.org/?probe=29096b57ad) | Mar 30, 2022 |
| Fujitsu Si... | LIFEBOOK E8420              | [1f81c3ef0a](https://linux-hardware.org/?probe=1f81c3ef0a) | Mar 30, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [7abb97f630](https://linux-hardware.org/?probe=7abb97f630) | Mar 30, 2022 |
| Philco        | 14I                         | [f49a55854c](https://linux-hardware.org/?probe=f49a55854c) | Mar 30, 2022 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [0befbade0d](https://linux-hardware.org/?probe=0befbade0d) | Mar 29, 2022 |
| HP            | Pavilion 17                 | [da4b84712e](https://linux-hardware.org/?probe=da4b84712e) | Mar 29, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [fc7ebbef4e](https://linux-hardware.org/?probe=fc7ebbef4e) | Mar 29, 2022 |
| Dell          | Inspiron N5110              | [ce630f6abb](https://linux-hardware.org/?probe=ce630f6abb) | Mar 29, 2022 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [60aa56878d](https://linux-hardware.org/?probe=60aa56878d) | Mar 28, 2022 |
| Dell          | Latitude E5550              | [f01dc93afc](https://linux-hardware.org/?probe=f01dc93afc) | Mar 28, 2022 |
| Toshiba       | PORTEGE R935                | [b209a8e000](https://linux-hardware.org/?probe=b209a8e000) | Mar 28, 2022 |
| Coradir       | Coradir/ES10IS5             | [dfc5a02c31](https://linux-hardware.org/?probe=dfc5a02c31) | Mar 28, 2022 |
| Infinix       | INBook X1                   | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| Lenovo        | ThinkPad T61 6464W4J        | [5f73680acf](https://linux-hardware.org/?probe=5f73680acf) | Mar 28, 2022 |
| HP            | 250 G5 Notebook PC          | [a9ce7cfa0b](https://linux-hardware.org/?probe=a9ce7cfa0b) | Mar 27, 2022 |
| MSI           | GF63 Thin 9SCXR             | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Positivo      | Z100                        | [5577927db3](https://linux-hardware.org/?probe=5577927db3) | Mar 27, 2022 |
| ASUSTek       | N76VJ                       | [53ec863214](https://linux-hardware.org/?probe=53ec863214) | Mar 26, 2022 |
| Lenovo        | ThinkPad A485 20MU0007CD    | [1e231d6b08](https://linux-hardware.org/?probe=1e231d6b08) | Mar 26, 2022 |
| Toshiba       | Satellite C855-2G8          | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Apple         | MacBookPro7,1               | [ca93a32a4b](https://linux-hardware.org/?probe=ca93a32a4b) | Mar 25, 2022 |
| Dell          | Latitude E7450              | [db931ebb1f](https://linux-hardware.org/?probe=db931ebb1f) | Mar 25, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f92c8b77dc](https://linux-hardware.org/?probe=f92c8b77dc) | Mar 25, 2022 |
| HP            | Pavilion dv6                | [c7dff2cc50](https://linux-hardware.org/?probe=c7dff2cc50) | Mar 25, 2022 |
| Dell          | Latitude 3300               | [0dbed1a827](https://linux-hardware.org/?probe=0dbed1a827) | Mar 25, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1cf6ad2e8e](https://linux-hardware.org/?probe=1cf6ad2e8e) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [57c51a1a1c](https://linux-hardware.org/?probe=57c51a1a1c) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| HP            | Pavilion TS Sleekbook 14    | [73c4a3b7b4](https://linux-hardware.org/?probe=73c4a3b7b4) | Mar 24, 2022 |
| HP            | Pavilion 11 x360 PC         | [7c506671a1](https://linux-hardware.org/?probe=7c506671a1) | Mar 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5170bfb594](https://linux-hardware.org/?probe=5170bfb594) | Mar 24, 2022 |
| HP            | Pavilion g6                 | [984b59ccb9](https://linux-hardware.org/?probe=984b59ccb9) | Mar 24, 2022 |
| ASUSTek       | N56JN                       | [8302116452](https://linux-hardware.org/?probe=8302116452) | Mar 24, 2022 |
| Dell          | Inspiron 3543               | [e2163528af](https://linux-hardware.org/?probe=e2163528af) | Mar 24, 2022 |
| Lenovo        | ThinkPad X260 20F5S2C600    | [12df54f389](https://linux-hardware.org/?probe=12df54f389) | Mar 24, 2022 |
| MSI           | Alpha 15 A3DDK              | [ba7e272251](https://linux-hardware.org/?probe=ba7e272251) | Mar 23, 2022 |
| Dell          | XPS 13 9360                 | [30003161fe](https://linux-hardware.org/?probe=30003161fe) | Mar 23, 2022 |
| MSI           | GE72VR 6RF                  | [b957669e37](https://linux-hardware.org/?probe=b957669e37) | Mar 23, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [c923ffc942](https://linux-hardware.org/?probe=c923ffc942) | Mar 23, 2022 |
| Sony          | SVE1711G1RB                 | [f6c732711b](https://linux-hardware.org/?probe=f6c732711b) | Mar 23, 2022 |
| Dell          | Latitude E6220              | [b006a7da3b](https://linux-hardware.org/?probe=b006a7da3b) | Mar 23, 2022 |
| Unknown       | Unknown                     | [e0dc423b2a](https://linux-hardware.org/?probe=e0dc423b2a) | Mar 23, 2022 |
| HP            | Elite x2 1012 G1            | [d8c3d46ad9](https://linux-hardware.org/?probe=d8c3d46ad9) | Mar 23, 2022 |
| Dell          | Latitude 7490               | [46726fbceb](https://linux-hardware.org/?probe=46726fbceb) | Mar 23, 2022 |
| Dell          | Latitude 3189               | [1ba82561d5](https://linux-hardware.org/?probe=1ba82561d5) | Mar 22, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [35488c8cce](https://linux-hardware.org/?probe=35488c8cce) | Mar 22, 2022 |
| MSI           | GE72VR 6RF                  | [73be3ca633](https://linux-hardware.org/?probe=73be3ca633) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| Packard Be... | DOT S                       | [591be1d465](https://linux-hardware.org/?probe=591be1d465) | Mar 22, 2022 |
| Dell          | Inspiron 5423               | [ea335b5e3b](https://linux-hardware.org/?probe=ea335b5e3b) | Mar 21, 2022 |
| ASUSTek       | N752VX                      | [9eb7fe04cf](https://linux-hardware.org/?probe=9eb7fe04cf) | Mar 21, 2022 |
| ASUSTek       | K40IJ                       | [dbc0e61f47](https://linux-hardware.org/?probe=dbc0e61f47) | Mar 21, 2022 |
| Dell          | Inspiron 13-5368            | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| HP            | 255 G8 Notebook PC          | [5adc6f4d6b](https://linux-hardware.org/?probe=5adc6f4d6b) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| Dell          | System XPS L322X            | [ee172af23a](https://linux-hardware.org/?probe=ee172af23a) | Mar 21, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [c845b9c738](https://linux-hardware.org/?probe=c845b9c738) | Mar 21, 2022 |
| VIT           | P2402                       | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| eMachines     | E525                        | [269a5e5794](https://linux-hardware.org/?probe=269a5e5794) | Mar 20, 2022 |
| Apple         | MacBook5,2                  | [26c6fa4da4](https://linux-hardware.org/?probe=26c6fa4da4) | Mar 20, 2022 |
| Lenovo        | B560 43308VG                | [f1e07e69d0](https://linux-hardware.org/?probe=f1e07e69d0) | Mar 20, 2022 |
| Lenovo        | ThinkPad T520 4243M75       | [d7a393fd7b](https://linux-hardware.org/?probe=d7a393fd7b) | Mar 20, 2022 |
| Lenovo        | G50-45 80E3                 | [9ffca5e95b](https://linux-hardware.org/?probe=9ffca5e95b) | Mar 20, 2022 |
| Dell          | Precision M4800             | [71dd646f94](https://linux-hardware.org/?probe=71dd646f94) | Mar 20, 2022 |
| Lenovo        | ThinkPad X230 2325BA3       | [d4170940f0](https://linux-hardware.org/?probe=d4170940f0) | Mar 20, 2022 |
| Acer          | Acadia V1.21                | [e6541adef3](https://linux-hardware.org/?probe=e6541adef3) | Mar 20, 2022 |
| Dell          | XPS 13 9360                 | [f350633b4c](https://linux-hardware.org/?probe=f350633b4c) | Mar 20, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [93eefcdc91](https://linux-hardware.org/?probe=93eefcdc91) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | [66de21a937](https://linux-hardware.org/?probe=66de21a937) | Mar 19, 2022 |
| ASUSTek       | X555LJ                      | [9e38b0860e](https://linux-hardware.org/?probe=9e38b0860e) | Mar 19, 2022 |
| Fujitsu       | FMVA05003                   | [d61a791168](https://linux-hardware.org/?probe=d61a791168) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | [0207f22677](https://linux-hardware.org/?probe=0207f22677) | Mar 19, 2022 |
| Positivo      | Mobile                      | [a1eb18d712](https://linux-hardware.org/?probe=a1eb18d712) | Mar 18, 2022 |
| Dell          | Latitude 3189               | [89ec672f05](https://linux-hardware.org/?probe=89ec672f05) | Mar 18, 2022 |
| Sony          | VPCEB4E1E                   | [51c7b5aa1a](https://linux-hardware.org/?probe=51c7b5aa1a) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [2072cd9c30](https://linux-hardware.org/?probe=2072cd9c30) | Mar 18, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [0833c34819](https://linux-hardware.org/?probe=0833c34819) | Mar 18, 2022 |
| HP            | Pavilion dv6                | [e039f6eb58](https://linux-hardware.org/?probe=e039f6eb58) | Mar 17, 2022 |
| Acer          | Aspire 5820                 | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| Dell          | Precision M4600             | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Lenovo        | ThinkPad X230 23331D9       | [6edcc3117e](https://linux-hardware.org/?probe=6edcc3117e) | Mar 16, 2022 |
| Toshiba       | Satellite C55D-A            | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| Acer          | Aspire 7741                 | [abbf6e7e7b](https://linux-hardware.org/?probe=abbf6e7e7b) | Mar 16, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2bb6b8bfd0](https://linux-hardware.org/?probe=2bb6b8bfd0) | Mar 16, 2022 |
| Acer          | Predator G9-793             | [c8068717f8](https://linux-hardware.org/?probe=c8068717f8) | Mar 16, 2022 |
| Acer          | Swift SF314-52              | [24c4fad70d](https://linux-hardware.org/?probe=24c4fad70d) | Mar 16, 2022 |
| Lenovo        | N22 80S6                    | [279ca719c8](https://linux-hardware.org/?probe=279ca719c8) | Mar 16, 2022 |
| MSI           | GE72VR 6RF                  | [b64205ca2e](https://linux-hardware.org/?probe=b64205ca2e) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1b91ffaa87](https://linux-hardware.org/?probe=1b91ffaa87) | Mar 15, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [1829c59f64](https://linux-hardware.org/?probe=1829c59f64) | Mar 14, 2022 |
| Lenovo        | ThinkPad R61 7733B46        | [d2220c6c2e](https://linux-hardware.org/?probe=d2220c6c2e) | Mar 14, 2022 |
| ASUSTek       | G75VX                       | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Dell          | Latitude E5440              | [cc385d8327](https://linux-hardware.org/?probe=cc385d8327) | Mar 14, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [bf87e829d7](https://linux-hardware.org/?probe=bf87e829d7) | Mar 14, 2022 |
| HP            | Laptop 15s-eq2xxx           | [189e272099](https://linux-hardware.org/?probe=189e272099) | Mar 13, 2022 |
| Acer          | Aspire E5-571               | [824c5eb97d](https://linux-hardware.org/?probe=824c5eb97d) | Mar 13, 2022 |
| Lenovo        | G40-30 80FY                 | [7b54425ba2](https://linux-hardware.org/?probe=7b54425ba2) | Mar 13, 2022 |
| Toshiba       | Satellite Pro S500          | [9976a7321c](https://linux-hardware.org/?probe=9976a7321c) | Mar 13, 2022 |
| Lenovo        | ThinkPad X230 2325DV5       | [c622952988](https://linux-hardware.org/?probe=c622952988) | Mar 13, 2022 |
| Toshiba       | Satellite Pro C660          | [2a2400c148](https://linux-hardware.org/?probe=2a2400c148) | Mar 13, 2022 |
| HP            | Laptop 15-bs0xx             | [2dd60fe836](https://linux-hardware.org/?probe=2dd60fe836) | Mar 13, 2022 |
| HP            | Presario CQ62               | [143eade9bc](https://linux-hardware.org/?probe=143eade9bc) | Mar 13, 2022 |
| HP            | Pavilion Notebook           | [1de76aac69](https://linux-hardware.org/?probe=1de76aac69) | Mar 12, 2022 |
| Philco        | 10D                         | [c983be3bb0](https://linux-hardware.org/?probe=c983be3bb0) | Mar 11, 2022 |
| ASUSTek       | K53U                        | [7f78b941ce](https://linux-hardware.org/?probe=7f78b941ce) | Mar 11, 2022 |
| ASUSTek       | UX303LAB                    | [f3d0e8fbea](https://linux-hardware.org/?probe=f3d0e8fbea) | Mar 11, 2022 |
| Dell          | Latitude 3310               | [d0f00ace6c](https://linux-hardware.org/?probe=d0f00ace6c) | Mar 11, 2022 |
| Dell          | Latitude 3390 2-in-1        | [b482b781bd](https://linux-hardware.org/?probe=b482b781bd) | Mar 11, 2022 |
| Medion        | E6228                       | [47099a8c6c](https://linux-hardware.org/?probe=47099a8c6c) | Mar 11, 2022 |
| Dell          | Latitude E5470              | [7fcd9d2c98](https://linux-hardware.org/?probe=7fcd9d2c98) | Mar 11, 2022 |
| Toshiba       | QOSMIO X770                 | [86f68b585b](https://linux-hardware.org/?probe=86f68b585b) | Mar 10, 2022 |
| Sony          | VGN-FZ31Z                   | [17e3cb9771](https://linux-hardware.org/?probe=17e3cb9771) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [05b4cceab2](https://linux-hardware.org/?probe=05b4cceab2) | Mar 10, 2022 |
| Dell          | Latitude 5411               | [b56bb115a0](https://linux-hardware.org/?probe=b56bb115a0) | Mar 10, 2022 |
| Acer          | Aspire A317-33              | [a4c0271977](https://linux-hardware.org/?probe=a4c0271977) | Mar 10, 2022 |
| Acer          | Aspire S3                   | [6ae9c3b307](https://linux-hardware.org/?probe=6ae9c3b307) | Mar 10, 2022 |
| Lenovo        | B590 20208                  | [46d63f7527](https://linux-hardware.org/?probe=46d63f7527) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | [0f20b300ec](https://linux-hardware.org/?probe=0f20b300ec) | Mar 09, 2022 |
| Fujitsu       | LIFEBOOK S792               | [55da3ab4e0](https://linux-hardware.org/?probe=55da3ab4e0) | Mar 09, 2022 |
| ASUSTek       | UX305FA                     | [f1641a436c](https://linux-hardware.org/?probe=f1641a436c) | Mar 09, 2022 |
| Acer          | Extensa 5220                | [fa85be94b2](https://linux-hardware.org/?probe=fa85be94b2) | Mar 09, 2022 |
| ASUSTek       | X450EA                      | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| Acer          | AO722                       | [fc0bccc42d](https://linux-hardware.org/?probe=fc0bccc42d) | Mar 09, 2022 |
| Toshiba       | Satellite L450D             | [343578bf21](https://linux-hardware.org/?probe=343578bf21) | Mar 09, 2022 |
| Toshiba       | Satellite L350D             | [8023f07e6c](https://linux-hardware.org/?probe=8023f07e6c) | Mar 09, 2022 |
| Apple         | MacBookPro9,2               | [ef06c07ea8](https://linux-hardware.org/?probe=ef06c07ea8) | Mar 08, 2022 |
| ASUSTek       | F3Sr                        | [ab9d32a3ff](https://linux-hardware.org/?probe=ab9d32a3ff) | Mar 08, 2022 |
| HP            | EliteBook 840 G3            | [ce025d2364](https://linux-hardware.org/?probe=ce025d2364) | Mar 08, 2022 |
| Intel         | Unknown                     | [9390bef13c](https://linux-hardware.org/?probe=9390bef13c) | Mar 08, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [bd22f532ef](https://linux-hardware.org/?probe=bd22f532ef) | Mar 08, 2022 |
| Dell          | Inspiron 3493               | [dcefffbbbf](https://linux-hardware.org/?probe=dcefffbbbf) | Mar 08, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a9118e8bc](https://linux-hardware.org/?probe=3a9118e8bc) | Mar 07, 2022 |
| Lenovo        | Unknown                     | [4308edfd8d](https://linux-hardware.org/?probe=4308edfd8d) | Mar 07, 2022 |
| Toshiba       | Satellite U400              | [e21b12ca9f](https://linux-hardware.org/?probe=e21b12ca9f) | Mar 07, 2022 |
| Lenovo        | Flex 2-15 20405             | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| Dell          | Latitude 3310               | [0268bb19d1](https://linux-hardware.org/?probe=0268bb19d1) | Mar 07, 2022 |
| Toshiba       | Satellite C70               | [d8f6f051b3](https://linux-hardware.org/?probe=d8f6f051b3) | Mar 07, 2022 |
| HP            | Pavilion dv7                | [eda63a0bb2](https://linux-hardware.org/?probe=eda63a0bb2) | Mar 07, 2022 |
| Dell          | Latitude D830               | [a1fd190f57](https://linux-hardware.org/?probe=a1fd190f57) | Mar 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [71ec492183](https://linux-hardware.org/?probe=71ec492183) | Mar 06, 2022 |
| Toshiba       | PORTEGE R835                | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| Packard Be... | EasyNote TK11BZ             | [d52d456239](https://linux-hardware.org/?probe=d52d456239) | Mar 06, 2022 |
| HP            | EliteBook 820 G2            | [ecb1064b14](https://linux-hardware.org/?probe=ecb1064b14) | Mar 06, 2022 |
| Toshiba       | Satellite Pro P200          | [6a8be21d50](https://linux-hardware.org/?probe=6a8be21d50) | Mar 06, 2022 |
| Acer          | Extensa 5620                | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4177R3U       | [2d58d0613a](https://linux-hardware.org/?probe=2d58d0613a) | Mar 05, 2022 |
| Dell          | XPS 13 9350                 | [ce5fd5227f](https://linux-hardware.org/?probe=ce5fd5227f) | Mar 05, 2022 |
| Acer          | Aspire 5733                 | [79a1d21f1e](https://linux-hardware.org/?probe=79a1d21f1e) | Mar 05, 2022 |
| Dell          | Latitude D630               | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [85f724141f](https://linux-hardware.org/?probe=85f724141f) | Mar 05, 2022 |
| ASUSTek       | E205SA                      | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| Lenovo        | ThinkPad W541 20EGS03100    | [f7b51cf262](https://linux-hardware.org/?probe=f7b51cf262) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| Panasonic     | CF-30KTPA9NP                | [fffe3abd97](https://linux-hardware.org/?probe=fffe3abd97) | Mar 05, 2022 |
| Acer          | Aspire ES1-331              | [cbba045d50](https://linux-hardware.org/?probe=cbba045d50) | Mar 05, 2022 |
| Toshiba       | TECRA M11                   | [ff568f1c19](https://linux-hardware.org/?probe=ff568f1c19) | Mar 05, 2022 |
| Apple         | MacBookPro5,2               | [a1728941bf](https://linux-hardware.org/?probe=a1728941bf) | Mar 04, 2022 |
| Dell          | Inspiron 5593               | [eca1413f3f](https://linux-hardware.org/?probe=eca1413f3f) | Mar 04, 2022 |
| HP            | 340 G2                      | [c4f663b37b](https://linux-hardware.org/?probe=c4f663b37b) | Mar 04, 2022 |
| Positivo B... | VJFE52F11X-XXXXXX           | [d40ec33f5e](https://linux-hardware.org/?probe=d40ec33f5e) | Mar 04, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | [9f925455e8](https://linux-hardware.org/?probe=9f925455e8) | Mar 04, 2022 |
| Acer          | Aspire A315-57G             | [83f0bbb366](https://linux-hardware.org/?probe=83f0bbb366) | Mar 04, 2022 |
| Lenovo        | G40-45 80E1                 | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| Lenovo        | G570 20079                  | [55a854b0c1](https://linux-hardware.org/?probe=55a854b0c1) | Mar 04, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e8dd84a845](https://linux-hardware.org/?probe=e8dd84a845) | Mar 03, 2022 |
| Lenovo        | ThinkPad T430 2349T7Z       | [b567c4922e](https://linux-hardware.org/?probe=b567c4922e) | Mar 03, 2022 |
| Dell          | Studio 1737                 | [874afb5afd](https://linux-hardware.org/?probe=874afb5afd) | Mar 03, 2022 |
| Lenovo        | G505s 20255                 | [36cd8309bc](https://linux-hardware.org/?probe=36cd8309bc) | Mar 03, 2022 |
| Dell          | Latitude E7240              | [7004ac549b](https://linux-hardware.org/?probe=7004ac549b) | Mar 03, 2022 |
| Dell          | Latitude E6500              | [e801665544](https://linux-hardware.org/?probe=e801665544) | Mar 03, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [12ab030882](https://linux-hardware.org/?probe=12ab030882) | Mar 02, 2022 |
| Acer          | Aspire V3-371               | [038cc99ead](https://linux-hardware.org/?probe=038cc99ead) | Mar 02, 2022 |
| ASUSTek       | UL20A                       | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| HP            | 245 G3                      | [879094e00f](https://linux-hardware.org/?probe=879094e00f) | Mar 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [8c1bcab1d9](https://linux-hardware.org/?probe=8c1bcab1d9) | Mar 01, 2022 |
| HP            | ProBook 4340s               | [2b4257b1c2](https://linux-hardware.org/?probe=2b4257b1c2) | Mar 01, 2022 |
| Fujitsu       | AMILO Pi 3560               | [ea68b8ed21](https://linux-hardware.org/?probe=ea68b8ed21) | Mar 01, 2022 |
| Acer          | Aspire V3-771               | [6d5acc6be7](https://linux-hardware.org/?probe=6d5acc6be7) | Mar 01, 2022 |
| Sony          | VGN-Z690N                   | [d3465abe44](https://linux-hardware.org/?probe=d3465abe44) | Mar 01, 2022 |
| HP            | Laptop 14-fq0xxx            | [b610aeabed](https://linux-hardware.org/?probe=b610aeabed) | Mar 01, 2022 |
| Medion        | Akoya E7221                 | [a66540bc44](https://linux-hardware.org/?probe=a66540bc44) | Mar 01, 2022 |
| HP            | Notebook                    | [f820b3f676](https://linux-hardware.org/?probe=f820b3f676) | Feb 28, 2022 |
| Toshiba       | Satellite C50-A-19T         | [daa7733b2d](https://linux-hardware.org/?probe=daa7733b2d) | Feb 28, 2022 |
| ASUSTek       | X202E                       | [a8ceeefa2d](https://linux-hardware.org/?probe=a8ceeefa2d) | Feb 28, 2022 |
| Toshiba       | Satellite C50D-A-138        | [06b11bf254](https://linux-hardware.org/?probe=06b11bf254) | Feb 28, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [03a49e64cf](https://linux-hardware.org/?probe=03a49e64cf) | Feb 28, 2022 |
| Dell          | Latitude E7240              | [4cf8d57b13](https://linux-hardware.org/?probe=4cf8d57b13) | Feb 28, 2022 |
| Medion        | P6624                       | [0a502fd230](https://linux-hardware.org/?probe=0a502fd230) | Feb 28, 2022 |
| eMachines     | E525                        | [3dcd8ced36](https://linux-hardware.org/?probe=3dcd8ced36) | Feb 27, 2022 |
| ASUSTek       | N551VW                      | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [5f6664d102](https://linux-hardware.org/?probe=5f6664d102) | Feb 27, 2022 |
| HP            | Pavilion dv6                | [d04802b99e](https://linux-hardware.org/?probe=d04802b99e) | Feb 27, 2022 |
| ASUSTek       | X540SA                      | [b73a01ebca](https://linux-hardware.org/?probe=b73a01ebca) | Feb 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [3b6604efc1](https://linux-hardware.org/?probe=3b6604efc1) | Feb 27, 2022 |
| ASUSTek       | K73BY                       | [ea3bb81aaf](https://linux-hardware.org/?probe=ea3bb81aaf) | Feb 27, 2022 |
| Positivo      | C14CU41TV                   | [7cabe0e07c](https://linux-hardware.org/?probe=7cabe0e07c) | Feb 27, 2022 |
| Lenovo        | G560 0679                   | [7109402c58](https://linux-hardware.org/?probe=7109402c58) | Feb 27, 2022 |
| HP            | Pavilion 15                 | [c68dd3c495](https://linux-hardware.org/?probe=c68dd3c495) | Feb 27, 2022 |
| ASUSTek       | UL30A                       | [1fd1b8def7](https://linux-hardware.org/?probe=1fd1b8def7) | Feb 27, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [21e2170d4a](https://linux-hardware.org/?probe=21e2170d4a) | Feb 26, 2022 |
| Sony          | VGN-FZ31Z                   | [b223305dc1](https://linux-hardware.org/?probe=b223305dc1) | Feb 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ac4073b44](https://linux-hardware.org/?probe=0ac4073b44) | Feb 26, 2022 |
| HP            | Pavilion dv6                | [073fabe370](https://linux-hardware.org/?probe=073fabe370) | Feb 26, 2022 |
| Toshiba       | Satellite L775-166          | [f0ad0a4da5](https://linux-hardware.org/?probe=f0ad0a4da5) | Feb 26, 2022 |
| HP            | 2000                        | [53d7131a3d](https://linux-hardware.org/?probe=53d7131a3d) | Feb 26, 2022 |
| Fujitsu       | FMVA33LB2                   | [2dc30249b7](https://linux-hardware.org/?probe=2dc30249b7) | Feb 26, 2022 |
| Lenovo        | ThinkPad X220 4290LG4       | [bfb13999b0](https://linux-hardware.org/?probe=bfb13999b0) | Feb 26, 2022 |
| HP            | Compaq 6910p                | [1ba50507cc](https://linux-hardware.org/?probe=1ba50507cc) | Feb 26, 2022 |
| HP            | G60                         | [00a44feca2](https://linux-hardware.org/?probe=00a44feca2) | Feb 25, 2022 |
| Acer          | Aspire A515-51G             | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | G70-80 80FF                 | [0a349a2a70](https://linux-hardware.org/?probe=0a349a2a70) | Feb 25, 2022 |
| Toshiba       | Satellite Pro C650          | [15fb8724cf](https://linux-hardware.org/?probe=15fb8724cf) | Feb 25, 2022 |
| Toshiba       | Satellite P500              | [980cb1d4af](https://linux-hardware.org/?probe=980cb1d4af) | Feb 25, 2022 |
| HP            | Compaq Presario CQ61        | [96b71ee82f](https://linux-hardware.org/?probe=96b71ee82f) | Feb 25, 2022 |
| HP            | ZBook 15 G3                 | [7b9e3082bf](https://linux-hardware.org/?probe=7b9e3082bf) | Feb 25, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [76f891b923](https://linux-hardware.org/?probe=76f891b923) | Feb 25, 2022 |
| ASUSTek       | K53Z                        | [0bd403b2c1](https://linux-hardware.org/?probe=0bd403b2c1) | Feb 25, 2022 |
| ASUSTek       | X555LA                      | [35acd46342](https://linux-hardware.org/?probe=35acd46342) | Feb 25, 2022 |
| Lenovo        | ThinkPad T61 64659TU        | [b00d789d5d](https://linux-hardware.org/?probe=b00d789d5d) | Feb 24, 2022 |
| Dell          | Inspiron 15-3552            | [969cea89d7](https://linux-hardware.org/?probe=969cea89d7) | Feb 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [7803f9b898](https://linux-hardware.org/?probe=7803f9b898) | Feb 24, 2022 |
| Dell          | Inspiron 3531               | [d2d231ddeb](https://linux-hardware.org/?probe=d2d231ddeb) | Feb 24, 2022 |
| Lenovo        | IdeaPad S206 20154          | [8c712aa419](https://linux-hardware.org/?probe=8c712aa419) | Feb 24, 2022 |
| Toshiba       | Satellite C850-1GF          | [9ace91eeb9](https://linux-hardware.org/?probe=9ace91eeb9) | Feb 24, 2022 |
| ASUSTek       | X55U                        | [c7c38f077d](https://linux-hardware.org/?probe=c7c38f077d) | Feb 24, 2022 |
| HP            | EliteBook 820 G1            | [916b00f114](https://linux-hardware.org/?probe=916b00f114) | Feb 24, 2022 |
| Dell          | Latitude E6510              | [b2b28d822c](https://linux-hardware.org/?probe=b2b28d822c) | Feb 24, 2022 |
| Lenovo        | Z70-80 80FG                 | [6b2428cbfd](https://linux-hardware.org/?probe=6b2428cbfd) | Feb 24, 2022 |
| Dell          | Latitude E5500              | [1b8d8ffa33](https://linux-hardware.org/?probe=1b8d8ffa33) | Feb 24, 2022 |
| Packard Be... | EasyNote_MX67               | [0687a8a072](https://linux-hardware.org/?probe=0687a8a072) | Feb 23, 2022 |
| Sony          | SVD13215PLB                 | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| ASUSTek       | U32U                        | [b7944a1493](https://linux-hardware.org/?probe=b7944a1493) | Feb 23, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [b27662968a](https://linux-hardware.org/?probe=b27662968a) | Feb 23, 2022 |
| Lenovo        | ThinkPad T61 6464WBN        | [dde4e34ede](https://linux-hardware.org/?probe=dde4e34ede) | Feb 23, 2022 |
| Toshiba       | Satellite Pro R50-C         | [37ebd6d5b2](https://linux-hardware.org/?probe=37ebd6d5b2) | Feb 23, 2022 |
| HP            | 245 G6 Notebook PC          | [4cf4344d75](https://linux-hardware.org/?probe=4cf4344d75) | Feb 23, 2022 |
| Acer          | AO725                       | [65d4162ffe](https://linux-hardware.org/?probe=65d4162ffe) | Feb 23, 2022 |
| Lenovo        | IdeaPad S206 2638           | [84772cc34d](https://linux-hardware.org/?probe=84772cc34d) | Feb 23, 2022 |
| Lenovo        | IdeaPad Z580                | [c6aaa68e9c](https://linux-hardware.org/?probe=c6aaa68e9c) | Feb 23, 2022 |
| Dell          | Latitude 5511               | [4a0ed580d9](https://linux-hardware.org/?probe=4a0ed580d9) | Feb 23, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [fe042017e6](https://linux-hardware.org/?probe=fe042017e6) | Feb 23, 2022 |
| Lenovo        | B71-80 80RJ                 | [a5b06f50bd](https://linux-hardware.org/?probe=a5b06f50bd) | Feb 22, 2022 |
| Dell          | Latitude D630               | [df4da93a6c](https://linux-hardware.org/?probe=df4da93a6c) | Feb 22, 2022 |
| Alienware     | Area-51m R2                 | [65a1979bb3](https://linux-hardware.org/?probe=65a1979bb3) | Feb 22, 2022 |
| HP            | Laptop 15-db0xxx            | [cfdb3aa79b](https://linux-hardware.org/?probe=cfdb3aa79b) | Feb 22, 2022 |
| Acer          | Aspire ES1-512              | [924c20d0e4](https://linux-hardware.org/?probe=924c20d0e4) | Feb 22, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [1085285f79](https://linux-hardware.org/?probe=1085285f79) | Feb 22, 2022 |
| Dell          | G15 5515                    | [820ff78ebe](https://linux-hardware.org/?probe=820ff78ebe) | Feb 22, 2022 |
| Acer          | Aspire A115-31              | [b4e968ba72](https://linux-hardware.org/?probe=b4e968ba72) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [8b7ccdff57](https://linux-hardware.org/?probe=8b7ccdff57) | Feb 22, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [3285a9a5f6](https://linux-hardware.org/?probe=3285a9a5f6) | Feb 22, 2022 |
| HP            | EliteBook 6930p             | [82000c3346](https://linux-hardware.org/?probe=82000c3346) | Feb 22, 2022 |
| Acer          | Swift SF314-52              | [d5d23d1841](https://linux-hardware.org/?probe=d5d23d1841) | Feb 22, 2022 |
| HP            | EliteBook 820 G1            | [f7beb95ac9](https://linux-hardware.org/?probe=f7beb95ac9) | Feb 22, 2022 |
| HP            | Pavilion dv5                | [38d3a28768](https://linux-hardware.org/?probe=38d3a28768) | Feb 22, 2022 |
| HP            | ProBook 450 G1              | [1f26dfd88f](https://linux-hardware.org/?probe=1f26dfd88f) | Feb 22, 2022 |
| Dell          | Latitude E5270              | [5d2d5947f3](https://linux-hardware.org/?probe=5d2d5947f3) | Feb 22, 2022 |
| HP            | Pavilion g4                 | [ec1f96551c](https://linux-hardware.org/?probe=ec1f96551c) | Feb 22, 2022 |
| Positivo      | Mobile                      | [5192d94c20](https://linux-hardware.org/?probe=5192d94c20) | Feb 22, 2022 |
| ASUSTek       | X551MA                      | [4f5ec67daf](https://linux-hardware.org/?probe=4f5ec67daf) | Feb 22, 2022 |
| Samsung       | R530/R730                   | [18c21aabf3](https://linux-hardware.org/?probe=18c21aabf3) | Feb 22, 2022 |
| Toshiba       | Satellite L300D             | [b930bd727d](https://linux-hardware.org/?probe=b930bd727d) | Feb 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c4ba00804b](https://linux-hardware.org/?probe=c4ba00804b) | Feb 22, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [a9a21f6964](https://linux-hardware.org/?probe=a9a21f6964) | Feb 21, 2022 |
| HP            | Laptop 15-db0xxx            | [32942f112f](https://linux-hardware.org/?probe=32942f112f) | Feb 21, 2022 |
| HP            | ProBook 4720s               | [532e0a288f](https://linux-hardware.org/?probe=532e0a288f) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Apple         | MacBook4,1                  | [094a087c1a](https://linux-hardware.org/?probe=094a087c1a) | Feb 21, 2022 |
| HP            | ENVY TS 15                  | [af3e40938c](https://linux-hardware.org/?probe=af3e40938c) | Feb 21, 2022 |
| Dell          | Latitude E6440              | [2585c1cfb6](https://linux-hardware.org/?probe=2585c1cfb6) | Feb 21, 2022 |
| Dell          | Latitude E5420              | [6a57df1a59](https://linux-hardware.org/?probe=6a57df1a59) | Feb 21, 2022 |
| ASUSTek       | X200CA                      | [eea123637a](https://linux-hardware.org/?probe=eea123637a) | Feb 20, 2022 |
| Sony          | VPCEB1J8E                   | [b00a6a15b2](https://linux-hardware.org/?probe=b00a6a15b2) | Feb 20, 2022 |
| HP            | Compaq Presario CQ61        | [a9e075e530](https://linux-hardware.org/?probe=a9e075e530) | Feb 20, 2022 |
| Lenovo        | ThinkPad E495 20NE0002US    | [235260070b](https://linux-hardware.org/?probe=235260070b) | Feb 20, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [af3bef5727](https://linux-hardware.org/?probe=af3bef5727) | Feb 20, 2022 |
| Teclast       | F7                          | [fccda8fbdc](https://linux-hardware.org/?probe=fccda8fbdc) | Feb 20, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [0f818bf6e7](https://linux-hardware.org/?probe=0f818bf6e7) | Feb 20, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [2e2c2de75c](https://linux-hardware.org/?probe=2e2c2de75c) | Feb 20, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [cd97a5dfb4](https://linux-hardware.org/?probe=cd97a5dfb4) | Feb 20, 2022 |
| HP            | ENVY 15                     | [9758bb9b66](https://linux-hardware.org/?probe=9758bb9b66) | Feb 20, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [e844adcca1](https://linux-hardware.org/?probe=e844adcca1) | Feb 20, 2022 |
| Dell          | Vostro 3405                 | [f869338cb0](https://linux-hardware.org/?probe=f869338cb0) | Feb 20, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [571c932872](https://linux-hardware.org/?probe=571c932872) | Feb 20, 2022 |
| Acer          | Aspire V5-573G              | [62bd52b74c](https://linux-hardware.org/?probe=62bd52b74c) | Feb 20, 2022 |
| Acer          | Aspire A517-51              | [997108b078](https://linux-hardware.org/?probe=997108b078) | Feb 19, 2022 |
| Toshiba       | Satellite L355              | [d66c60d09a](https://linux-hardware.org/?probe=d66c60d09a) | Feb 19, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [013349e12a](https://linux-hardware.org/?probe=013349e12a) | Feb 19, 2022 |
| Dell          | System XPS L502X            | [110f0aa3e3](https://linux-hardware.org/?probe=110f0aa3e3) | Feb 19, 2022 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [7ad48c7fcf](https://linux-hardware.org/?probe=7ad48c7fcf) | Feb 19, 2022 |
| Lenovo        | ThinkPad T430 2349G2G       | [14f905c347](https://linux-hardware.org/?probe=14f905c347) | Feb 19, 2022 |
| Acer          | Aspire V3-771               | [962c444158](https://linux-hardware.org/?probe=962c444158) | Feb 19, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [8aaf1cdcde](https://linux-hardware.org/?probe=8aaf1cdcde) | Feb 19, 2022 |
| HP            | Pavilion g6                 | [792465ee85](https://linux-hardware.org/?probe=792465ee85) | Feb 19, 2022 |
| Acer          | Aspire E5-511               | [6b5a96e6cf](https://linux-hardware.org/?probe=6b5a96e6cf) | Feb 19, 2022 |
| Toshiba       | dynabook Satellite B552/... | [b86bbc9d7c](https://linux-hardware.org/?probe=b86bbc9d7c) | Feb 19, 2022 |
| Acer          | Aspire 4738                 | [f4b2c409f4](https://linux-hardware.org/?probe=f4b2c409f4) | Feb 19, 2022 |
| HP            | Compaq CQ58                 | [6f67712b57](https://linux-hardware.org/?probe=6f67712b57) | Feb 19, 2022 |
| Acer          | Aspire E5-571G              | [276c87bdc5](https://linux-hardware.org/?probe=276c87bdc5) | Feb 19, 2022 |
| Acer          | Aspire A515-51G             | [c11057eac9](https://linux-hardware.org/?probe=c11057eac9) | Feb 19, 2022 |
| Acer          | Aspire E5-575G              | [52f178c230](https://linux-hardware.org/?probe=52f178c230) | Feb 19, 2022 |
| HP            | Laptop 15-bw0xx             | [fa638b506a](https://linux-hardware.org/?probe=fa638b506a) | Feb 19, 2022 |
| ASUSTek       | K56CM                       | [c6e3cad977](https://linux-hardware.org/?probe=c6e3cad977) | Feb 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [f41ff1607c](https://linux-hardware.org/?probe=f41ff1607c) | Feb 19, 2022 |
| Dell          | System XPS L702X            | [e1d4821ec2](https://linux-hardware.org/?probe=e1d4821ec2) | Feb 19, 2022 |
| Toshiba       | Satellite L775-11N          | [497c03b2e2](https://linux-hardware.org/?probe=497c03b2e2) | Feb 19, 2022 |
| HP            | Pavilion g6                 | [77bcf6cc10](https://linux-hardware.org/?probe=77bcf6cc10) | Feb 19, 2022 |
| HP            | Notebook                    | [a1f9f76ed0](https://linux-hardware.org/?probe=a1f9f76ed0) | Feb 19, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| Acer          | Aspire V5-471               | [700b7ea8e8](https://linux-hardware.org/?probe=700b7ea8e8) | Feb 18, 2022 |
| Acer          | Swift SF114-34              | [5ed3b0b48e](https://linux-hardware.org/?probe=5ed3b0b48e) | Feb 18, 2022 |
| HP            | Pavilion g6                 | [298655060c](https://linux-hardware.org/?probe=298655060c) | Feb 18, 2022 |
| HP            | 620                         | [9824e767d3](https://linux-hardware.org/?probe=9824e767d3) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [f358f74d41](https://linux-hardware.org/?probe=f358f74d41) | Feb 18, 2022 |
| ASUSTek       | X705UDR                     | [6788479ad3](https://linux-hardware.org/?probe=6788479ad3) | Feb 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| Lenovo        | ThinkPad P50 20EN0005GE     | [1f8abac9d7](https://linux-hardware.org/?probe=1f8abac9d7) | Feb 18, 2022 |
| Lenovo        | Yoga 2 11 20332             | [8544ed95e5](https://linux-hardware.org/?probe=8544ed95e5) | Feb 18, 2022 |
| Lenovo        | ThinkPad X230 2325FG0       | [d8480748c7](https://linux-hardware.org/?probe=d8480748c7) | Feb 18, 2022 |
| AZW           | SEi                         | [e6305c0c34](https://linux-hardware.org/?probe=e6305c0c34) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [482b871e32](https://linux-hardware.org/?probe=482b871e32) | Feb 18, 2022 |
| Acer          | Nitro AN517-41              | [14f6daa0b9](https://linux-hardware.org/?probe=14f6daa0b9) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3HP0... | [3a79f95039](https://linux-hardware.org/?probe=3a79f95039) | Feb 18, 2022 |
| Dell          | Latitude E6440              | [1d4bac917c](https://linux-hardware.org/?probe=1d4bac917c) | Feb 18, 2022 |
| ASUSTek       | X555YI                      | [8bc0136607](https://linux-hardware.org/?probe=8bc0136607) | Feb 18, 2022 |
| HP            | Notebook                    | [ab39875441](https://linux-hardware.org/?probe=ab39875441) | Feb 18, 2022 |
| ASUSTek       | Q504UA                      | [515d64e480](https://linux-hardware.org/?probe=515d64e480) | Feb 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [97a3db4f2f](https://linux-hardware.org/?probe=97a3db4f2f) | Feb 18, 2022 |
| Compaq        | Presario CQ-17              | [02d0a5926f](https://linux-hardware.org/?probe=02d0a5926f) | Feb 18, 2022 |
| Gateway       | EC14D                       | [8a943f6b57](https://linux-hardware.org/?probe=8a943f6b57) | Feb 18, 2022 |
| LincPlus      | P1                          | [24e3b52251](https://linux-hardware.org/?probe=24e3b52251) | Feb 18, 2022 |
| Lenovo        | ThinkPad T480 20L50067US    | [db1d64253e](https://linux-hardware.org/?probe=db1d64253e) | Feb 17, 2022 |
| Lenovo        | ThinkPad X240 20AMA4V500    | [e6a94741de](https://linux-hardware.org/?probe=e6a94741de) | Feb 17, 2022 |
| Dell          | Latitude E5410              | [c60f9e4a42](https://linux-hardware.org/?probe=c60f9e4a42) | Feb 17, 2022 |
| Lenovo        | ThinkPad T430 2349H2G       | [f873bcc6c8](https://linux-hardware.org/?probe=f873bcc6c8) | Feb 17, 2022 |
| Acer          | Extensa 5230                | [3c58103e6a](https://linux-hardware.org/?probe=3c58103e6a) | Feb 17, 2022 |
| Acer          | Aspire 5749                 | [c2beca7751](https://linux-hardware.org/?probe=c2beca7751) | Feb 17, 2022 |
| Chuwi         | GemiBook                    | [596102e73f](https://linux-hardware.org/?probe=596102e73f) | Feb 17, 2022 |
| Lenovo        | Flex 2-14 20404             | [41713d7553](https://linux-hardware.org/?probe=41713d7553) | Feb 17, 2022 |
| Lenovo        | G710 20252                  | [528af81a3a](https://linux-hardware.org/?probe=528af81a3a) | Feb 17, 2022 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | [e418af16aa](https://linux-hardware.org/?probe=e418af16aa) | Feb 17, 2022 |
| Lenovo        | G505s 20255                 | [2be9f6bed4](https://linux-hardware.org/?probe=2be9f6bed4) | Feb 17, 2022 |
| Lenovo        | ThinkPad X395 20NLS0J400    | [a122ee336d](https://linux-hardware.org/?probe=a122ee336d) | Feb 17, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [dc90cd578a](https://linux-hardware.org/?probe=dc90cd578a) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Dell          | Vostro 3500                 | [e3f3a2ed38](https://linux-hardware.org/?probe=e3f3a2ed38) | Feb 17, 2022 |
| HP            | Compaq 6730b                | [bd5616251e](https://linux-hardware.org/?probe=bd5616251e) | Feb 17, 2022 |
| ASUSTek       | GL702ZC                     | [4a213a20c0](https://linux-hardware.org/?probe=4a213a20c0) | Feb 17, 2022 |
| ASUSTek       | K53SD                       | [d0ecebab71](https://linux-hardware.org/?probe=d0ecebab71) | Feb 16, 2022 |
| ASUSTek       | X556UB                      | [33eaab7189](https://linux-hardware.org/?probe=33eaab7189) | Feb 16, 2022 |
| Lenovo        | IdeaPad Z580                | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Dell          | Latitude E6520              | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [dae3397144](https://linux-hardware.org/?probe=dae3397144) | Feb 16, 2022 |
| Talal Abu-... | TAGITOP-Pro                 | [59879a1182](https://linux-hardware.org/?probe=59879a1182) | Feb 16, 2022 |
| Fujitsu       | LIFEBOOK E736               | [b5da44235a](https://linux-hardware.org/?probe=b5da44235a) | Feb 16, 2022 |
| Radio Vict... | B34 SLIM                    | [8a100feae7](https://linux-hardware.org/?probe=8a100feae7) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0A50... | [964c1a1526](https://linux-hardware.org/?probe=964c1a1526) | Feb 16, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [d0e44d293a](https://linux-hardware.org/?probe=d0e44d293a) | Feb 16, 2022 |
| Lenovo        | G580 20157                  | [0938ea75fa](https://linux-hardware.org/?probe=0938ea75fa) | Feb 16, 2022 |
| HP            | Pavilion g7                 | [d550adc412](https://linux-hardware.org/?probe=d550adc412) | Feb 16, 2022 |
| Lenovo        | ThinkPad T530 2394A11       | [c926008d79](https://linux-hardware.org/?probe=c926008d79) | Feb 16, 2022 |
| MSI           | Bravo 17 A4DDR              | [3dcfa13df7](https://linux-hardware.org/?probe=3dcfa13df7) | Feb 16, 2022 |
| Toshiba       | Satellite S55-B             | [3379e836d1](https://linux-hardware.org/?probe=3379e836d1) | Feb 16, 2022 |
| Acer          | Aspire A315-34              | [f6383e06d7](https://linux-hardware.org/?probe=f6383e06d7) | Feb 16, 2022 |
| Samsung       | 535U4C                      | [f5f9256781](https://linux-hardware.org/?probe=f5f9256781) | Feb 16, 2022 |
| Dell          | Latitude E7440              | [1efc982c71](https://linux-hardware.org/?probe=1efc982c71) | Feb 16, 2022 |
| Lenovo        | ThinkPad L460 20FVS07C00    | [e062302c48](https://linux-hardware.org/?probe=e062302c48) | Feb 16, 2022 |
| ASUSTek       | G751JY                      | [f4ccf15bdc](https://linux-hardware.org/?probe=f4ccf15bdc) | Feb 16, 2022 |
| Toshiba       | Satellite Pro R50-C         | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | [0ecb6e8bdf](https://linux-hardware.org/?probe=0ecb6e8bdf) | Feb 16, 2022 |
| Lenovo        | ThinkPad X230 2330A17       | [882f7d3c8b](https://linux-hardware.org/?probe=882f7d3c8b) | Feb 16, 2022 |
| Acer          | Aspire 7745                 | [59246d05e2](https://linux-hardware.org/?probe=59246d05e2) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| eMachines     | E625                        | [a8d173c56b](https://linux-hardware.org/?probe=a8d173c56b) | Feb 15, 2022 |
| Lenovo        | ThinkPad T420 4180F64       | [e9c9ca949c](https://linux-hardware.org/?probe=e9c9ca949c) | Feb 15, 2022 |
| Acer          | Aspire ES1-512              | [deb108070d](https://linux-hardware.org/?probe=deb108070d) | Feb 15, 2022 |
| Acer          | Aspire 4349                 | [31ff379e39](https://linux-hardware.org/?probe=31ff379e39) | Feb 15, 2022 |
| Toshiba       | Satellite Pro NB10-A-109    | [c3049f32df](https://linux-hardware.org/?probe=c3049f32df) | Feb 15, 2022 |
| HP            | Notebook                    | [7e7b9be307](https://linux-hardware.org/?probe=7e7b9be307) | Feb 15, 2022 |
| Dell          | Studio 1737                 | [498b2b8c3a](https://linux-hardware.org/?probe=498b2b8c3a) | Feb 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [adc2a96901](https://linux-hardware.org/?probe=adc2a96901) | Feb 15, 2022 |
| Toshiba       | Satellite C50-A             | [e88fd90806](https://linux-hardware.org/?probe=e88fd90806) | Feb 15, 2022 |
| HP            | Presario CQ57               | [14148f0279](https://linux-hardware.org/?probe=14148f0279) | Feb 15, 2022 |
| Toshiba       | Satellite S855D             | [47a0325074](https://linux-hardware.org/?probe=47a0325074) | Feb 15, 2022 |
| Lenovo        | ThinkPad X230 23252SG       | [a5179b9681](https://linux-hardware.org/?probe=a5179b9681) | Feb 15, 2022 |
| HP            | Pavilion 15                 | [3bd713bd35](https://linux-hardware.org/?probe=3bd713bd35) | Feb 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [507f27294e](https://linux-hardware.org/?probe=507f27294e) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [b4d07e8ab1](https://linux-hardware.org/?probe=b4d07e8ab1) | Feb 15, 2022 |
| Lenovo        | G560 20042                  | [5c4a8043b1](https://linux-hardware.org/?probe=5c4a8043b1) | Feb 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [85d4a8278e](https://linux-hardware.org/?probe=85d4a8278e) | Feb 15, 2022 |
| Toshiba       | Satellite C55-A             | [19133950aa](https://linux-hardware.org/?probe=19133950aa) | Feb 15, 2022 |
| Lenovo        | G70-35 80Q5                 | [bdf84bbcc1](https://linux-hardware.org/?probe=bdf84bbcc1) | Feb 14, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [25518083e9](https://linux-hardware.org/?probe=25518083e9) | Feb 14, 2022 |
| Dell          | Latitude E6540              | [a06de7f66f](https://linux-hardware.org/?probe=a06de7f66f) | Feb 14, 2022 |
| Computer D... | W240EU/W250EUQ/W270EUQ      | [730b3737e2](https://linux-hardware.org/?probe=730b3737e2) | Feb 14, 2022 |
| ASUSTek       | K53U                        | [06e94593cc](https://linux-hardware.org/?probe=06e94593cc) | Feb 14, 2022 |
| Acer          | Aspire 3820                 | [7364dc5d5e](https://linux-hardware.org/?probe=7364dc5d5e) | Feb 14, 2022 |
| Schenker      | XMG CORE (TGL/M21)          | [56e3cdba6d](https://linux-hardware.org/?probe=56e3cdba6d) | Feb 14, 2022 |
| Lenovo        | ThinkPad T410 2537AT1       | [7ecf503a63](https://linux-hardware.org/?probe=7ecf503a63) | Feb 14, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b64b02ec69](https://linux-hardware.org/?probe=b64b02ec69) | Feb 14, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [621c548147](https://linux-hardware.org/?probe=621c548147) | Feb 14, 2022 |
| Samsung       | 700T                        | [a8a433333d](https://linux-hardware.org/?probe=a8a433333d) | Feb 14, 2022 |
| Toshiba       | Satellite Pro L650          | [8cc610d205](https://linux-hardware.org/?probe=8cc610d205) | Feb 14, 2022 |
| Dell          | System Inspiron N4110       | [695b7bb3dd](https://linux-hardware.org/?probe=695b7bb3dd) | Feb 14, 2022 |
| Acer          | Aspire A514-53              | [5765e1b103](https://linux-hardware.org/?probe=5765e1b103) | Feb 14, 2022 |
| HP            | ProBook 4330s               | [3781146b1f](https://linux-hardware.org/?probe=3781146b1f) | Feb 14, 2022 |
| Packard Be... | EasyNote TJ65               | [8a31f29547](https://linux-hardware.org/?probe=8a31f29547) | Feb 14, 2022 |
| ASUSTek       | K52Je                       | [45a1a6ff08](https://linux-hardware.org/?probe=45a1a6ff08) | Feb 14, 2022 |
| HP            | 655                         | [b0189b16b1](https://linux-hardware.org/?probe=b0189b16b1) | Feb 14, 2022 |
| Fujitsu       | FMVNA1SE                    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Lenovo        | ThinkPad T430 23476P9       | [e55e8897a7](https://linux-hardware.org/?probe=e55e8897a7) | Feb 14, 2022 |
| Samsung       | 550XBE/350XBE               | [6846e14550](https://linux-hardware.org/?probe=6846e14550) | Feb 14, 2022 |
| Dell          | Latitude E6330              | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| Dell          | System Vostro 3750          | [4a5289bfbe](https://linux-hardware.org/?probe=4a5289bfbe) | Feb 14, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [b032bf234f](https://linux-hardware.org/?probe=b032bf234f) | Feb 14, 2022 |
| Dell          | Latitude 7490               | [0aac64c377](https://linux-hardware.org/?probe=0aac64c377) | Feb 14, 2022 |
| Acer          | V5-171                      | [0200220f80](https://linux-hardware.org/?probe=0200220f80) | Feb 14, 2022 |
| Chuwi         | AeroBook                    | [82d37bd4b8](https://linux-hardware.org/?probe=82d37bd4b8) | Feb 14, 2022 |
| ASUSTek       | X55A                        | [c6b17158ac](https://linux-hardware.org/?probe=c6b17158ac) | Feb 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e783775e08](https://linux-hardware.org/?probe=e783775e08) | Feb 14, 2022 |
| ASUSTek       | X555LJ                      | [c2f63ae6d7](https://linux-hardware.org/?probe=c2f63ae6d7) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [d9b970a3f2](https://linux-hardware.org/?probe=d9b970a3f2) | Feb 14, 2022 |
| Lenovo        | V15-IGL 82C3                | [35d928e17b](https://linux-hardware.org/?probe=35d928e17b) | Feb 14, 2022 |
| MSI           | MS-16F1                     | [cd35935349](https://linux-hardware.org/?probe=cd35935349) | Feb 13, 2022 |
| HP            | EliteBook 8440p             | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| Dell          | Inspiron 5558               | [999c4f7ab1](https://linux-hardware.org/?probe=999c4f7ab1) | Feb 13, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [429d06ed33](https://linux-hardware.org/?probe=429d06ed33) | Feb 13, 2022 |
| Acer          | Swift SF114-34              | [31d020671e](https://linux-hardware.org/?probe=31d020671e) | Feb 13, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a5407aa128](https://linux-hardware.org/?probe=a5407aa128) | Feb 13, 2022 |
| Acer          | Extensa 5620                | [d56ce9d11a](https://linux-hardware.org/?probe=d56ce9d11a) | Feb 13, 2022 |
| MSI           | GV72 7RE                    | [d199f3e50a](https://linux-hardware.org/?probe=d199f3e50a) | Feb 13, 2022 |
| Acer          | Aspire A114-32              | [ac87b42a18](https://linux-hardware.org/?probe=ac87b42a18) | Feb 13, 2022 |
| ASUSTek       | UX330UAK                    | [8731a73bfa](https://linux-hardware.org/?probe=8731a73bfa) | Feb 13, 2022 |
| HP            | 250 G7 Notebook PC          | [f2968206ac](https://linux-hardware.org/?probe=f2968206ac) | Feb 13, 2022 |
| Toshiba       | Satellite L755              | [0c388987dc](https://linux-hardware.org/?probe=0c388987dc) | Feb 13, 2022 |
| ASUSTek       | ZenBook UX334FLC_UX334FL    | [d74ad9fc94](https://linux-hardware.org/?probe=d74ad9fc94) | Feb 13, 2022 |
| Acer          | Aspire ES1-523              | [594cf4fa2f](https://linux-hardware.org/?probe=594cf4fa2f) | Feb 13, 2022 |
| HP            | Pavilion dm1                | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| Medion        | Akoya THE TOUCH 10          | [220896c95e](https://linux-hardware.org/?probe=220896c95e) | Feb 13, 2022 |
| Dell          | Inspiron 5579               | [8ae7432b94](https://linux-hardware.org/?probe=8ae7432b94) | Feb 13, 2022 |
| Acer          | Aspire 5715Z                | [cdd4414bbd](https://linux-hardware.org/?probe=cdd4414bbd) | Feb 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [30c1919c89](https://linux-hardware.org/?probe=30c1919c89) | Feb 13, 2022 |
| Fujitsu       | LIFEBOOK E780               | [0ba38c6605](https://linux-hardware.org/?probe=0ba38c6605) | Feb 13, 2022 |
| HP            | 245 G1                      | [30c3eb937a](https://linux-hardware.org/?probe=30c3eb937a) | Feb 13, 2022 |
| HP            | EliteBook 8530p             | [6b45115b9e](https://linux-hardware.org/?probe=6b45115b9e) | Feb 13, 2022 |
| HP            | ProBook 650 G1              | [789c553d62](https://linux-hardware.org/?probe=789c553d62) | Feb 13, 2022 |
| Lenovo        | ThinkPad X230T 34382AG      | [bec561800f](https://linux-hardware.org/?probe=bec561800f) | Feb 13, 2022 |
| Dell          | Precision 7520              | [8f91185b52](https://linux-hardware.org/?probe=8f91185b52) | Feb 13, 2022 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [0c52b3ab5c](https://linux-hardware.org/?probe=0c52b3ab5c) | Feb 13, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | [e64257c29a](https://linux-hardware.org/?probe=e64257c29a) | Feb 13, 2022 |
| Acer          | Aspire E5-571P              | [9e290336c1](https://linux-hardware.org/?probe=9e290336c1) | Feb 13, 2022 |
| Dell          | Latitude E5450              | [09fa63b2aa](https://linux-hardware.org/?probe=09fa63b2aa) | Feb 13, 2022 |
| Unknown       | Unknown                     | [fa14786b94](https://linux-hardware.org/?probe=fa14786b94) | Feb 13, 2022 |
| HP            | Laptop 17-ak0xx             | [874b22af5d](https://linux-hardware.org/?probe=874b22af5d) | Feb 13, 2022 |
| Toshiba       | Satellite C840              | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| ASUSTek       | X541UV                      | [fb81da9fa5](https://linux-hardware.org/?probe=fb81da9fa5) | Feb 13, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| Dell          | Inspiron 3421               | [dd5c587aaa](https://linux-hardware.org/?probe=dd5c587aaa) | Feb 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S3FY00    | [08006b1c3a](https://linux-hardware.org/?probe=08006b1c3a) | Feb 13, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80W2      | [045c989217](https://linux-hardware.org/?probe=045c989217) | Feb 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [574d71e586](https://linux-hardware.org/?probe=574d71e586) | Feb 13, 2022 |
| HP            | Pavilion dv7                | [937e0f27c0](https://linux-hardware.org/?probe=937e0f27c0) | Feb 13, 2022 |
| MSI           | GS73VR 7RF                  | [132f615f1d](https://linux-hardware.org/?probe=132f615f1d) | Feb 13, 2022 |
| HP            | Compaq 15                   | [fa22db8854](https://linux-hardware.org/?probe=fa22db8854) | Feb 12, 2022 |
| Packard Be... | EasyNote TE11HC             | [9bf695f39f](https://linux-hardware.org/?probe=9bf695f39f) | Feb 12, 2022 |
| HP            | G72                         | [b27d05f546](https://linux-hardware.org/?probe=b27d05f546) | Feb 12, 2022 |
| ASUSTek       | X550EP                      | [4a316b0aef](https://linux-hardware.org/?probe=4a316b0aef) | Feb 12, 2022 |
| Lenovo        | ThinkPad W510 4876A46       | [d4b8bb3ed1](https://linux-hardware.org/?probe=d4b8bb3ed1) | Feb 12, 2022 |
| HP            | ENVY 14                     | [8f15540064](https://linux-hardware.org/?probe=8f15540064) | Feb 12, 2022 |
| Dell          | Latitude 3390 2-in-1        | [c6fa52f6e0](https://linux-hardware.org/?probe=c6fa52f6e0) | Feb 12, 2022 |
| Dell          | Inspiron N5110              | [a87e7380d9](https://linux-hardware.org/?probe=a87e7380d9) | Feb 12, 2022 |
| ASUSTek       | Vivobook_ASUSLaptop M350... | [5d3d7c5340](https://linux-hardware.org/?probe=5d3d7c5340) | Feb 12, 2022 |
| ASUSTek       | X541UAK                     | [402470c7c4](https://linux-hardware.org/?probe=402470c7c4) | Feb 12, 2022 |
| HP            | Notebook                    | [7d0124e894](https://linux-hardware.org/?probe=7d0124e894) | Feb 12, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [9d3a4e4a04](https://linux-hardware.org/?probe=9d3a4e4a04) | Feb 12, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [889a7efca0](https://linux-hardware.org/?probe=889a7efca0) | Feb 12, 2022 |
| ASUSTek       | A8JR                        | [3fbe9d478e](https://linux-hardware.org/?probe=3fbe9d478e) | Feb 12, 2022 |
| ASUSTek       | X202E                       | [74bdbf8e59](https://linux-hardware.org/?probe=74bdbf8e59) | Feb 12, 2022 |
| HP            | ProBook 4730s               | [2a3ff15659](https://linux-hardware.org/?probe=2a3ff15659) | Feb 12, 2022 |
| Dell          | Vostro 3559                 | [02bc6c4a34](https://linux-hardware.org/?probe=02bc6c4a34) | Feb 12, 2022 |
| HP            | Compaq CQ58                 | [a7eac41f26](https://linux-hardware.org/?probe=a7eac41f26) | Feb 12, 2022 |
| MSI           | GF65 Thin 10SDR             | [bd57e9ab22](https://linux-hardware.org/?probe=bd57e9ab22) | Feb 12, 2022 |
| Dell          | Inspiron 1525               | [673daa75d1](https://linux-hardware.org/?probe=673daa75d1) | Feb 12, 2022 |
| HP            | 255 G4                      | [9ee2c88cb4](https://linux-hardware.org/?probe=9ee2c88cb4) | Feb 12, 2022 |
| ASUSTek       | K55A                        | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| Toshiba       | Satellite C70-C-18E         | [c9ca181b40](https://linux-hardware.org/?probe=c9ca181b40) | Feb 12, 2022 |
| HP            | Laptop 17-ak0xx             | [5ac054b0e2](https://linux-hardware.org/?probe=5ac054b0e2) | Feb 12, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| EVOO          | EG-LP4                      | [2d358de8cb](https://linux-hardware.org/?probe=2d358de8cb) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Samsung       | 770Z5E/780Z5E               | [a19da5635c](https://linux-hardware.org/?probe=a19da5635c) | Feb 12, 2022 |
| Acer          | Aspire ES1-411              | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo        | ThinkPad T500 2241CT7       | [e8559e7aba](https://linux-hardware.org/?probe=e8559e7aba) | Feb 12, 2022 |
| ASUSTek       | X756UXM                     | [d4ecf98490](https://linux-hardware.org/?probe=d4ecf98490) | Feb 12, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | [9ce361abd3](https://linux-hardware.org/?probe=9ce361abd3) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge E325 1297A... | [81d584f653](https://linux-hardware.org/?probe=81d584f653) | Feb 12, 2022 |
| HP            | Spectre 13 Ultrabook        | [6a23f734fb](https://linux-hardware.org/?probe=6a23f734fb) | Feb 12, 2022 |
| HP            | Pavilion dv6500             | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [08833de386](https://linux-hardware.org/?probe=08833de386) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [331b62c0e9](https://linux-hardware.org/?probe=331b62c0e9) | Feb 11, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | [59d473ded9](https://linux-hardware.org/?probe=59d473ded9) | Feb 11, 2022 |
| Dell          | Latitude D630               | [b73fc865fd](https://linux-hardware.org/?probe=b73fc865fd) | Feb 11, 2022 |
| Lenovo        | ThinkPad X240 20AM007QMS    | [d1a972806c](https://linux-hardware.org/?probe=d1a972806c) | Feb 11, 2022 |
| Dell          | Latitude E7450              | [d3eeb3ec1b](https://linux-hardware.org/?probe=d3eeb3ec1b) | Feb 11, 2022 |
| HP            | Notebook                    | [1b41ca9725](https://linux-hardware.org/?probe=1b41ca9725) | Feb 11, 2022 |
| HP            | ProBook 455 G3              | [7d8d1c9adb](https://linux-hardware.org/?probe=7d8d1c9adb) | Feb 11, 2022 |
| Sony          | VPCEB2E1E                   | [e3df114520](https://linux-hardware.org/?probe=e3df114520) | Feb 11, 2022 |
| Dell          | Inspiron N4010              | [b04de36c04](https://linux-hardware.org/?probe=b04de36c04) | Feb 11, 2022 |
| Lenovo        | G510 20238                  | [0ab9f95484](https://linux-hardware.org/?probe=0ab9f95484) | Feb 11, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [9b7b4aa697](https://linux-hardware.org/?probe=9b7b4aa697) | Feb 11, 2022 |
| Philco        | 10D                         | [562bb178d4](https://linux-hardware.org/?probe=562bb178d4) | Feb 11, 2022 |
| TUXEDO        | Aura 15 Gen1                | [832b48c46d](https://linux-hardware.org/?probe=832b48c46d) | Feb 11, 2022 |
| Sony          | VPCZ11X9E                   | [41f76e701c](https://linux-hardware.org/?probe=41f76e701c) | Feb 11, 2022 |
| ASUSTek       | K50IJ                       | [0dd30d1e7e](https://linux-hardware.org/?probe=0dd30d1e7e) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [39dbce5e49](https://linux-hardware.org/?probe=39dbce5e49) | Feb 11, 2022 |
| Dell          | Inspiron 5537               | [e9448e54b5](https://linux-hardware.org/?probe=e9448e54b5) | Feb 11, 2022 |
| ASUSTek       | X751SA                      | [007765d1b3](https://linux-hardware.org/?probe=007765d1b3) | Feb 11, 2022 |
| Dell          | Inspiron 7472               | [62bdd11635](https://linux-hardware.org/?probe=62bdd11635) | Feb 11, 2022 |
| Beelink       | Gemini N                    | [fa50b7bb95](https://linux-hardware.org/?probe=fa50b7bb95) | Feb 11, 2022 |
| Toshiba       | Satellite C660              | [9e9b592889](https://linux-hardware.org/?probe=9e9b592889) | Feb 11, 2022 |
| Dell          | Latitude E5450              | [b426feb1d9](https://linux-hardware.org/?probe=b426feb1d9) | Feb 11, 2022 |
| Dell          | Latitude 7420               | [2547d7836e](https://linux-hardware.org/?probe=2547d7836e) | Feb 11, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [c1ba1e4fe7](https://linux-hardware.org/?probe=c1ba1e4fe7) | Feb 11, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [ba593a6cdd](https://linux-hardware.org/?probe=ba593a6cdd) | Feb 11, 2022 |
| Dell          | Latitude E7240              | [3893c38bf7](https://linux-hardware.org/?probe=3893c38bf7) | Feb 11, 2022 |
| ASUSTek       | X102BA                      | [401e015fff](https://linux-hardware.org/?probe=401e015fff) | Feb 11, 2022 |
| Lenovo        | ThinkPad E15 20RD005HUS     | [bc65ffe3b4](https://linux-hardware.org/?probe=bc65ffe3b4) | Feb 11, 2022 |
| HP            | 650                         | [7369d6635b](https://linux-hardware.org/?probe=7369d6635b) | Feb 11, 2022 |
| Dell          | Latitude E5570              | [35cd880438](https://linux-hardware.org/?probe=35cd880438) | Feb 11, 2022 |
| Digibras      | CL341                       | [f3b678924d](https://linux-hardware.org/?probe=f3b678924d) | Feb 11, 2022 |
| HP            | Laptop 15-da0xxx            | [18fa19a4f0](https://linux-hardware.org/?probe=18fa19a4f0) | Feb 10, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [68d863ab48](https://linux-hardware.org/?probe=68d863ab48) | Feb 10, 2022 |
| Acer          | TravelMate B117-M           | [148a39d164](https://linux-hardware.org/?probe=148a39d164) | Feb 10, 2022 |
| Lenovo        | IdeaPad Y580                | [37a6572cb9](https://linux-hardware.org/?probe=37a6572cb9) | Feb 10, 2022 |
| HP            | ProBook 4510s               | [1ec304f4f6](https://linux-hardware.org/?probe=1ec304f4f6) | Feb 10, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [a0ba6bf4e9](https://linux-hardware.org/?probe=a0ba6bf4e9) | Feb 10, 2022 |
| Acer          | Aspire ES1-520              | [dadc839fc9](https://linux-hardware.org/?probe=dadc839fc9) | Feb 10, 2022 |
| Toshiba       | Satellite S50t-B            | [5aa437b5e0](https://linux-hardware.org/?probe=5aa437b5e0) | Feb 10, 2022 |
| Acer          | Aspire 7739G                | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| Dell          | Latitude E6420              | [b13a898011](https://linux-hardware.org/?probe=b13a898011) | Feb 10, 2022 |
| Lenovo        | G50-70 20351                | [0d63a077fb](https://linux-hardware.org/?probe=0d63a077fb) | Feb 10, 2022 |
| HP            | Laptop 17-ca0xxx            | [9be0b91a9a](https://linux-hardware.org/?probe=9be0b91a9a) | Feb 10, 2022 |
| Toshiba       | Satellite P200              | [31e65951de](https://linux-hardware.org/?probe=31e65951de) | Feb 10, 2022 |
| HP            | ProBook 640 G4              | [c155b2bd06](https://linux-hardware.org/?probe=c155b2bd06) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c4ac76b8e8](https://linux-hardware.org/?probe=c4ac76b8e8) | Feb 10, 2022 |
| Toshiba       | TECRA R950                  | [cb85483d3d](https://linux-hardware.org/?probe=cb85483d3d) | Feb 10, 2022 |
| Dell          | G3 3500                     | [0010596573](https://linux-hardware.org/?probe=0010596573) | Feb 10, 2022 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [30b9a925de](https://linux-hardware.org/?probe=30b9a925de) | Feb 10, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | [33a40b952e](https://linux-hardware.org/?probe=33a40b952e) | Feb 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6a4a06344a](https://linux-hardware.org/?probe=6a4a06344a) | Feb 10, 2022 |
| Sony          | VPCEL2S1E                   | [5bc3063386](https://linux-hardware.org/?probe=5bc3063386) | Feb 10, 2022 |
| Acer          | Aspire E5-571               | [c9317e5bc5](https://linux-hardware.org/?probe=c9317e5bc5) | Feb 10, 2022 |
| ASUSTek       | X555LAB                     | [4c0c519cde](https://linux-hardware.org/?probe=4c0c519cde) | Feb 10, 2022 |
| HP            | Compaq Presario CQ71        | [497c6a5a22](https://linux-hardware.org/?probe=497c6a5a22) | Feb 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [9a91ce673b](https://linux-hardware.org/?probe=9a91ce673b) | Feb 10, 2022 |
| Dell          | Latitude E6230              | [a8aeb155b0](https://linux-hardware.org/?probe=a8aeb155b0) | Feb 10, 2022 |
| Dell          | Latitude E6230              | [9a78278ecc](https://linux-hardware.org/?probe=9a78278ecc) | Feb 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | [80b214a273](https://linux-hardware.org/?probe=80b214a273) | Feb 10, 2022 |
| Clevo         | W240BU                      | [dd745527d7](https://linux-hardware.org/?probe=dd745527d7) | Feb 10, 2022 |
| Dell          | Latitude E5570              | [bc4b4080fd](https://linux-hardware.org/?probe=bc4b4080fd) | Feb 10, 2022 |
| Acer          | Aspire VN7-592G             | [fe5dd7a63b](https://linux-hardware.org/?probe=fe5dd7a63b) | Feb 10, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [869a837ab1](https://linux-hardware.org/?probe=869a837ab1) | Feb 10, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [82a3c63b3f](https://linux-hardware.org/?probe=82a3c63b3f) | Feb 10, 2022 |
| Acer          | Aspire A315-54              | [d4e5b617c7](https://linux-hardware.org/?probe=d4e5b617c7) | Feb 10, 2022 |
| Dell          | Latitude D620               | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| Lenovo        | ThinkPad X230 2325CZ1       | [77b71981b3](https://linux-hardware.org/?probe=77b71981b3) | Feb 10, 2022 |
| Lenovo        | ThinkPad X240 20AMS36W0X    | [2bf21d3499](https://linux-hardware.org/?probe=2bf21d3499) | Feb 10, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [23251c9e05](https://linux-hardware.org/?probe=23251c9e05) | Feb 10, 2022 |
| Lenovo        | Unknown                     | [a3a3ea2bd9](https://linux-hardware.org/?probe=a3a3ea2bd9) | Feb 10, 2022 |
| ASUSTek       | F3E                         | [1715199afd](https://linux-hardware.org/?probe=1715199afd) | Feb 09, 2022 |
| HP            | Pavilion dv6500             | [c1302b751d](https://linux-hardware.org/?probe=c1302b751d) | Feb 09, 2022 |
| Lenovo        | G510 20238                  | [a45f27f8f3](https://linux-hardware.org/?probe=a45f27f8f3) | Feb 09, 2022 |
| Notebook      | W65_67SZ                    | [747ffa0acc](https://linux-hardware.org/?probe=747ffa0acc) | Feb 09, 2022 |
| Apple         | MacBookPro6,2               | [7208fba41e](https://linux-hardware.org/?probe=7208fba41e) | Feb 09, 2022 |
| Lenovo        | ThinkPad T430 23501B3       | [565edc6010](https://linux-hardware.org/?probe=565edc6010) | Feb 09, 2022 |
| Dell          | Latitude 5580               | [d648fbb34d](https://linux-hardware.org/?probe=d648fbb34d) | Feb 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [b3067b4ba2](https://linux-hardware.org/?probe=b3067b4ba2) | Feb 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FG0... | [3a6e35daab](https://linux-hardware.org/?probe=3a6e35daab) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK NH532              | [b161688ec9](https://linux-hardware.org/?probe=b161688ec9) | Feb 09, 2022 |
| Dell          | Latitude E5530 non-vPro     | [953a03517c](https://linux-hardware.org/?probe=953a03517c) | Feb 09, 2022 |
| Dell          | XPS 15 9570                 | [38bb8e64f6](https://linux-hardware.org/?probe=38bb8e64f6) | Feb 09, 2022 |
| ASUSTek       | X751LAB                     | [53d804a7ed](https://linux-hardware.org/?probe=53d804a7ed) | Feb 09, 2022 |
| HP            | 240 G7 Notebook PC          | [03f63a3789](https://linux-hardware.org/?probe=03f63a3789) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK E559               | [66696218c1](https://linux-hardware.org/?probe=66696218c1) | Feb 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8bcb36b8c7](https://linux-hardware.org/?probe=8bcb36b8c7) | Feb 09, 2022 |
| PC Special... | PA70Hx                      | [c42b9bab78](https://linux-hardware.org/?probe=c42b9bab78) | Feb 09, 2022 |
| Lenovo        | V320-17IKB 81CN             | [07f4b5fa29](https://linux-hardware.org/?probe=07f4b5fa29) | Feb 09, 2022 |
| Acer          | VAG70_HC                    | [89df31dc20](https://linux-hardware.org/?probe=89df31dc20) | Feb 09, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [545af13c86](https://linux-hardware.org/?probe=545af13c86) | Feb 09, 2022 |
| Toshiba       | Satellite P200              | [f5c17b2b2a](https://linux-hardware.org/?probe=f5c17b2b2a) | Feb 09, 2022 |
| Acer          | Extensa 2540                | [f4d594d720](https://linux-hardware.org/?probe=f4d594d720) | Feb 09, 2022 |
| HP            | 2000                        | [a090a60014](https://linux-hardware.org/?probe=a090a60014) | Feb 09, 2022 |
| ASUSTek       | E202SA                      | [ced358c593](https://linux-hardware.org/?probe=ced358c593) | Feb 09, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | [a5201c533e](https://linux-hardware.org/?probe=a5201c533e) | Feb 09, 2022 |
| Acer          | TravelMate 5720             | [d0756aac7e](https://linux-hardware.org/?probe=d0756aac7e) | Feb 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d31f5e23d5](https://linux-hardware.org/?probe=d31f5e23d5) | Feb 09, 2022 |
| Sony          | VPCEB4M1E                   | [373127eb11](https://linux-hardware.org/?probe=373127eb11) | Feb 09, 2022 |
| Lenovo        | ThinkPad X230 2324A14       | [502457cef5](https://linux-hardware.org/?probe=502457cef5) | Feb 09, 2022 |
| Dell          | XPS L401X                   | [1db7a71e79](https://linux-hardware.org/?probe=1db7a71e79) | Feb 09, 2022 |
| Acer          | Aspire A515-43              | [be2c091c74](https://linux-hardware.org/?probe=be2c091c74) | Feb 09, 2022 |
| HP            | EliteBook 2170p             | [8abee6201f](https://linux-hardware.org/?probe=8abee6201f) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [76a7934681](https://linux-hardware.org/?probe=76a7934681) | Feb 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| Lenovo        | ThinkPad X240 20AMA18CIX    | [d1a32f6e9e](https://linux-hardware.org/?probe=d1a32f6e9e) | Feb 09, 2022 |
| Wortmann      | TERRA_MOBILE_1512/1712      | [6715b531e2](https://linux-hardware.org/?probe=6715b531e2) | Feb 09, 2022 |
| Acer          | Swift SF314-59              | [67a0a393d1](https://linux-hardware.org/?probe=67a0a393d1) | Feb 09, 2022 |
| Unknown       | Unknown                     | [736a64df69](https://linux-hardware.org/?probe=736a64df69) | Feb 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c08078130a](https://linux-hardware.org/?probe=c08078130a) | Feb 09, 2022 |
| Sony          | VGN-FW51JF_H                | [922a10f2f4](https://linux-hardware.org/?probe=922a10f2f4) | Feb 09, 2022 |
| Lenovo        | G505 20240                  | [ed806edbbb](https://linux-hardware.org/?probe=ed806edbbb) | Feb 09, 2022 |
| HP            | Compaq CQ45                 | [3c75fd14fb](https://linux-hardware.org/?probe=3c75fd14fb) | Feb 09, 2022 |
| Dell          | Latitude 5480               | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Dell          | Latitude E6520              | [6a40ef6090](https://linux-hardware.org/?probe=6a40ef6090) | Feb 09, 2022 |
| Lenovo        | ThinkPad T500 20828VG       | [f79076499b](https://linux-hardware.org/?probe=f79076499b) | Feb 09, 2022 |
| HP            | Pavilion dv6                | [efb945cc4f](https://linux-hardware.org/?probe=efb945cc4f) | Feb 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [6e83303f73](https://linux-hardware.org/?probe=6e83303f73) | Feb 09, 2022 |
| Dell          | Inspiron 5567               | [eec17e2cdc](https://linux-hardware.org/?probe=eec17e2cdc) | Feb 09, 2022 |
| HP            | HDX18                       | [9ac5cd7c4b](https://linux-hardware.org/?probe=9ac5cd7c4b) | Feb 09, 2022 |
| Sony          | VJFE52A0711H                | [0a29c49c46](https://linux-hardware.org/?probe=0a29c49c46) | Feb 09, 2022 |
| MSI           | MS-168A                     | [12e8387951](https://linux-hardware.org/?probe=12e8387951) | Feb 09, 2022 |
| Acer          | Aspire 5735                 | [13c6c15c9e](https://linux-hardware.org/?probe=13c6c15c9e) | Feb 09, 2022 |
| HP            | 15                          | [e2d83073ec](https://linux-hardware.org/?probe=e2d83073ec) | Feb 09, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0d09c987ef](https://linux-hardware.org/?probe=0d09c987ef) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| MSI           | GE62 7RE                    | [dba21298d0](https://linux-hardware.org/?probe=dba21298d0) | Feb 09, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [d596970450](https://linux-hardware.org/?probe=d596970450) | Feb 09, 2022 |
| HP            | Compaq Presario CQ60        | [f5d9f92aad](https://linux-hardware.org/?probe=f5d9f92aad) | Feb 09, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0MF0... | [4071e2b845](https://linux-hardware.org/?probe=4071e2b845) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK S751               | [42d5c28f38](https://linux-hardware.org/?probe=42d5c28f38) | Feb 09, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | [d13b0ff958](https://linux-hardware.org/?probe=d13b0ff958) | Feb 08, 2022 |
| Acer          | Aspire A515-43              | [2b3ad05e55](https://linux-hardware.org/?probe=2b3ad05e55) | Feb 08, 2022 |
| HP            | ENVY 15                     | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Samsung       | X420/X520                   | [cd4b91a032](https://linux-hardware.org/?probe=cd4b91a032) | Feb 08, 2022 |
| Packard Be... | EasyNote TE69CX             | [fb1073cdd0](https://linux-hardware.org/?probe=fb1073cdd0) | Feb 08, 2022 |
| Medion        | P6402 MD60800               | [a749ba246d](https://linux-hardware.org/?probe=a749ba246d) | Feb 08, 2022 |
| Lenovo        | V15-ADA 82C7                | [85f930f1fc](https://linux-hardware.org/?probe=85f930f1fc) | Feb 08, 2022 |
| HP            | Pavilion g6                 | [5d20c75fe1](https://linux-hardware.org/?probe=5d20c75fe1) | Feb 08, 2022 |
| Lenovo        | ThinkPad SL510 28477MG      | [8c6f03c8f7](https://linux-hardware.org/?probe=8c6f03c8f7) | Feb 08, 2022 |
| Acer          | Aspire 7740                 | [3963a3b387](https://linux-hardware.org/?probe=3963a3b387) | Feb 08, 2022 |
| Toshiba       | Satellite L40               | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [bbedc56833](https://linux-hardware.org/?probe=bbedc56833) | Feb 08, 2022 |
| Lenovo        | G50-30 80G0                 | [18bd9bbbe0](https://linux-hardware.org/?probe=18bd9bbbe0) | Feb 08, 2022 |
| HP            | Pavilion 11 x360 PC         | [f252168753](https://linux-hardware.org/?probe=f252168753) | Feb 08, 2022 |
| Lenovo        | ThinkPad T420 4180AT9       | [d83b7599cb](https://linux-hardware.org/?probe=d83b7599cb) | Feb 08, 2022 |
| Dell          | Latitude E6420              | [68c5bccf12](https://linux-hardware.org/?probe=68c5bccf12) | Feb 08, 2022 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [df89a1b937](https://linux-hardware.org/?probe=df89a1b937) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [fc5afec8d7](https://linux-hardware.org/?probe=fc5afec8d7) | Feb 08, 2022 |
| Medion        | Akoya P2214T                | [55708cb128](https://linux-hardware.org/?probe=55708cb128) | Feb 08, 2022 |
| Packard Be... | EasyNote LM98               | [21d535f4e4](https://linux-hardware.org/?probe=21d535f4e4) | Feb 08, 2022 |
| HP            | EliteBook 840 G3            | [383572d5be](https://linux-hardware.org/?probe=383572d5be) | Feb 08, 2022 |
| Dell          | Latitude 5520               | [4c6abde0d6](https://linux-hardware.org/?probe=4c6abde0d6) | Feb 08, 2022 |
| Radxa         | ROCK Pi X v1.4              | [6a3bd80ed5](https://linux-hardware.org/?probe=6a3bd80ed5) | Feb 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [73738d3f0c](https://linux-hardware.org/?probe=73738d3f0c) | Feb 08, 2022 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [0ec0943d03](https://linux-hardware.org/?probe=0ec0943d03) | Feb 08, 2022 |
| Clevo         | W251ESQ/W270ESQ             | [ece30938ed](https://linux-hardware.org/?probe=ece30938ed) | Feb 08, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | [3d7b583aeb](https://linux-hardware.org/?probe=3d7b583aeb) | Feb 08, 2022 |
| Lenovo        | ThinkPad T420s 4174NEG      | [dbb4a7778e](https://linux-hardware.org/?probe=dbb4a7778e) | Feb 08, 2022 |
| HP            | G6000 (GH831EA#ABD)         | [26992ff697](https://linux-hardware.org/?probe=26992ff697) | Feb 08, 2022 |
| Acer          | Aspire A515-51G             | [539119f529](https://linux-hardware.org/?probe=539119f529) | Feb 08, 2022 |
| Acer          | TravelMate 5760G            | [3024952eba](https://linux-hardware.org/?probe=3024952eba) | Feb 08, 2022 |
| Dell          | Latitude E5410              | [b153d79a85](https://linux-hardware.org/?probe=b153d79a85) | Feb 08, 2022 |
| Samsung       | 550XDA                      | [ec92003cdd](https://linux-hardware.org/?probe=ec92003cdd) | Feb 08, 2022 |
| Dell          | Latitude E4300              | [07ce1c5924](https://linux-hardware.org/?probe=07ce1c5924) | Feb 08, 2022 |
| Toshiba       | Satellite L755              | [11aa592c89](https://linux-hardware.org/?probe=11aa592c89) | Feb 08, 2022 |
| Acer          | Aspire E1-571G              | [6db3ca9f6d](https://linux-hardware.org/?probe=6db3ca9f6d) | Feb 08, 2022 |
| Acer          | Swift SF114-34              | [f0ffadac92](https://linux-hardware.org/?probe=f0ffadac92) | Feb 08, 2022 |
| HP            | ProBook 6475b               | [770340d4f9](https://linux-hardware.org/?probe=770340d4f9) | Feb 08, 2022 |
| Lenovo        | ThinkPad X240 20ALCTO1WW    | [1620a85467](https://linux-hardware.org/?probe=1620a85467) | Feb 08, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [a2e640db60](https://linux-hardware.org/?probe=a2e640db60) | Feb 08, 2022 |
| Lenovo        | Flex 2-15D 20377            | [6825bda258](https://linux-hardware.org/?probe=6825bda258) | Feb 08, 2022 |
| Lenovo        | ThinkPad X61 76733NJ        | [42dec79e1d](https://linux-hardware.org/?probe=42dec79e1d) | Feb 08, 2022 |
| PC Special... | GK5NPFO                     | [14695b59b4](https://linux-hardware.org/?probe=14695b59b4) | Feb 08, 2022 |
| Lenovo        | ThinkPad L380 20M5003FUK    | [fe486b4de6](https://linux-hardware.org/?probe=fe486b4de6) | Feb 08, 2022 |
| Acer          | Aspire E5-774G              | [791321d27d](https://linux-hardware.org/?probe=791321d27d) | Feb 08, 2022 |
| Quanta        | TW8/SW8/DW8                 | [a542c42556](https://linux-hardware.org/?probe=a542c42556) | Feb 08, 2022 |
| HP            | Laptop 15-bs0xx             | [422c043d76](https://linux-hardware.org/?probe=422c043d76) | Feb 08, 2022 |
| MSI           | GP60 2PE                    | [e597f61177](https://linux-hardware.org/?probe=e597f61177) | Feb 08, 2022 |
| Samsung       | Q310                        | [a558af5b07](https://linux-hardware.org/?probe=a558af5b07) | Feb 08, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [6fc44d8cf2](https://linux-hardware.org/?probe=6fc44d8cf2) | Feb 08, 2022 |
| HP            | 250 G6 Notebook PC          | [fe1ccafd2b](https://linux-hardware.org/?probe=fe1ccafd2b) | Feb 08, 2022 |
| Acer          | Aspire A515-52G             | [01b863976d](https://linux-hardware.org/?probe=01b863976d) | Feb 08, 2022 |
| ASUSTek       | X541SA                      | [afafec99f9](https://linux-hardware.org/?probe=afafec99f9) | Feb 08, 2022 |
| Acer          | Aspire F5-573G              | [e1f58e9713](https://linux-hardware.org/?probe=e1f58e9713) | Feb 08, 2022 |
| Lenovo        | G50-30 80G0                 | [6d631d4a4d](https://linux-hardware.org/?probe=6d631d4a4d) | Feb 08, 2022 |
| Lenovo        | G570 20079                  | [61d85f383b](https://linux-hardware.org/?probe=61d85f383b) | Feb 08, 2022 |
| Dell          | Latitude E6430              | [dbbb970199](https://linux-hardware.org/?probe=dbbb970199) | Feb 08, 2022 |
| Dell          | Latitude E6220              | [5c2160f294](https://linux-hardware.org/?probe=5c2160f294) | Feb 08, 2022 |
| HP            | Pavilion g7                 | [897512dac8](https://linux-hardware.org/?probe=897512dac8) | Feb 08, 2022 |
| ASUSTek       | G74Sx                       | [d0f48fef55](https://linux-hardware.org/?probe=d0f48fef55) | Feb 08, 2022 |
| Samsung       | 550XCJ/550XCR               | [36b7150c17](https://linux-hardware.org/?probe=36b7150c17) | Feb 08, 2022 |
| HP            | ProBook 645 G1              | [98bdb87a7c](https://linux-hardware.org/?probe=98bdb87a7c) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0cc7c7e225](https://linux-hardware.org/?probe=0cc7c7e225) | Feb 08, 2022 |
| Lenovo        | ThinkPad T470 20HES23B0U    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| Lanix         | A V16                       | [2cbb463004](https://linux-hardware.org/?probe=2cbb463004) | Feb 08, 2022 |
| Toshiba       | dynabook Satellite B453/... | [279ff9b0f0](https://linux-hardware.org/?probe=279ff9b0f0) | Feb 08, 2022 |
| ASUSTek       | P53E                        | [b05ea988a5](https://linux-hardware.org/?probe=b05ea988a5) | Feb 08, 2022 |
| Lenovo        | G580 2189                   | [12cb40d9b7](https://linux-hardware.org/?probe=12cb40d9b7) | Feb 08, 2022 |
| Acer          | Nitro AN517-51              | [250845433c](https://linux-hardware.org/?probe=250845433c) | Feb 08, 2022 |
| Dell          | Inspiron 5558               | [72501fb765](https://linux-hardware.org/?probe=72501fb765) | Feb 08, 2022 |
| MSI           | GS66 Stealth 10UH           | [a154ac8369](https://linux-hardware.org/?probe=a154ac8369) | Feb 08, 2022 |
| Dell          | Latitude E7440              | [e244c28777](https://linux-hardware.org/?probe=e244c28777) | Feb 08, 2022 |
| Lenovo        | B51-35 80LH                 | [4dc8595d0d](https://linux-hardware.org/?probe=4dc8595d0d) | Feb 08, 2022 |
| Apple         | MacBookPro8,1               | [e22836d761](https://linux-hardware.org/?probe=e22836d761) | Feb 08, 2022 |
| Samsung       | R580                        | [f822930ecf](https://linux-hardware.org/?probe=f822930ecf) | Feb 08, 2022 |
| Acer          | Aspire F5-573T              | [0f3251e85b](https://linux-hardware.org/?probe=0f3251e85b) | Feb 08, 2022 |
| Samsung       | RF510/RF410/RF710           | [8bb90d9533](https://linux-hardware.org/?probe=8bb90d9533) | Feb 08, 2022 |
| HP            | Laptop 17-ak0xx             | [fe99f0793f](https://linux-hardware.org/?probe=fe99f0793f) | Feb 08, 2022 |
| HP            | 250 G6 Notebook PC          | [40b0583970](https://linux-hardware.org/?probe=40b0583970) | Feb 08, 2022 |
| Lenovo        | Yoga 500-14IBD 80N4         | [277f7ae4fd](https://linux-hardware.org/?probe=277f7ae4fd) | Feb 08, 2022 |
| Sony          | VPCF236FM                   | [08bf40800a](https://linux-hardware.org/?probe=08bf40800a) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [09af3e68dd](https://linux-hardware.org/?probe=09af3e68dd) | Feb 07, 2022 |
| Dell          | Latitude E6540              | [aafec74a25](https://linux-hardware.org/?probe=aafec74a25) | Feb 07, 2022 |
| Dell          | Inspiron 3542               | [9d53729c91](https://linux-hardware.org/?probe=9d53729c91) | Feb 07, 2022 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | [78011da841](https://linux-hardware.org/?probe=78011da841) | Feb 07, 2022 |
| Dell          | Latitude E5410              | [68418aaa43](https://linux-hardware.org/?probe=68418aaa43) | Feb 07, 2022 |
| Toshiba       | Satellite U500              | [a5e6d93704](https://linux-hardware.org/?probe=a5e6d93704) | Feb 07, 2022 |
| Acer          | Swift SF113-31              | [04cad1ea2f](https://linux-hardware.org/?probe=04cad1ea2f) | Feb 07, 2022 |
| HP            | Laptop 15s-fq1xxx           | [d6f9a9112f](https://linux-hardware.org/?probe=d6f9a9112f) | Feb 07, 2022 |
| HP            | EliteBook 2540p             | [006afe98fe](https://linux-hardware.org/?probe=006afe98fe) | Feb 07, 2022 |
| Fujitsu       | LIFEBOOK E734               | [4605034148](https://linux-hardware.org/?probe=4605034148) | Feb 07, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5dbb969bd8](https://linux-hardware.org/?probe=5dbb969bd8) | Feb 07, 2022 |
| Dataton       | WATCHPAX 3362               | [a46a99f5f7](https://linux-hardware.org/?probe=a46a99f5f7) | Feb 07, 2022 |
| Toshiba       | Satellite C855-112          | [99cb514a47](https://linux-hardware.org/?probe=99cb514a47) | Feb 07, 2022 |
| HUAWEI        | KLVL-WXX9                   | [837b0e80ef](https://linux-hardware.org/?probe=837b0e80ef) | Feb 07, 2022 |
| Lenovo        | ThinkPad SL410 2842AKG      | [d5e2c893f5](https://linux-hardware.org/?probe=d5e2c893f5) | Feb 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Dell          | Inspiron 17-7778            | [5713c1770f](https://linux-hardware.org/?probe=5713c1770f) | Feb 07, 2022 |
| HP            | Pavilion 11 x360 PC         | [dcd0177f71](https://linux-hardware.org/?probe=dcd0177f71) | Feb 07, 2022 |
| Dell          | Latitude E5520m             | [0e5f84866b](https://linux-hardware.org/?probe=0e5f84866b) | Feb 07, 2022 |
| HP            | Laptop 14-fq0xxx            | [ae7230ad66](https://linux-hardware.org/?probe=ae7230ad66) | Feb 07, 2022 |
| Lenovo        | V130-15IGM 81HL             | [c2ea636dd2](https://linux-hardware.org/?probe=c2ea636dd2) | Feb 07, 2022 |
| HP            | ProBook 430 G2              | [789e7207f3](https://linux-hardware.org/?probe=789e7207f3) | Feb 07, 2022 |
| ASUSTek       | X200MA                      | [535688daec](https://linux-hardware.org/?probe=535688daec) | Feb 07, 2022 |
| ASUSTek       | X555UA                      | [04ae1e78b7](https://linux-hardware.org/?probe=04ae1e78b7) | Feb 07, 2022 |
| ASUSTek       | GL702VM                     | [015ed8325e](https://linux-hardware.org/?probe=015ed8325e) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| ASUSTek       | N56VZ                       | [b1702aa9ef](https://linux-hardware.org/?probe=b1702aa9ef) | Feb 07, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [33521d7a03](https://linux-hardware.org/?probe=33521d7a03) | Feb 07, 2022 |
| Dell          | Latitude E7250              | [a7ba3830f7](https://linux-hardware.org/?probe=a7ba3830f7) | Feb 07, 2022 |
| Gateway       | NV55C                       | [27fd1ff7f1](https://linux-hardware.org/?probe=27fd1ff7f1) | Feb 07, 2022 |
| HP            | Laptop 15s-fq1xxx           | [24186d3b9e](https://linux-hardware.org/?probe=24186d3b9e) | Feb 07, 2022 |
| HP            | Laptop 15q-ds0xxx           | [250ec15d99](https://linux-hardware.org/?probe=250ec15d99) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Dell          | Inspiron 1525               | [9291db4df4](https://linux-hardware.org/?probe=9291db4df4) | Feb 07, 2022 |
| HP            | Pavilion dm3                | [d8c2f04630](https://linux-hardware.org/?probe=d8c2f04630) | Feb 07, 2022 |
| Sony          | VGN-FW170J                  | [edead40b0d](https://linux-hardware.org/?probe=edead40b0d) | Feb 07, 2022 |
| Lenovo        | ThinkPad X201 3626AT7       | [92b79d9ade](https://linux-hardware.org/?probe=92b79d9ade) | Feb 07, 2022 |
| Acer          | Aspire V3-571G              | [9ab57d4641](https://linux-hardware.org/?probe=9ab57d4641) | Feb 07, 2022 |
| Acer          | Aspire 5732Z                | [bc1767bd42](https://linux-hardware.org/?probe=bc1767bd42) | Feb 07, 2022 |
| Acer          | Aspire A515-52G             | [cfc69482e3](https://linux-hardware.org/?probe=cfc69482e3) | Feb 07, 2022 |
| Toshiba       | Satellite L750              | [3e64e98234](https://linux-hardware.org/?probe=3e64e98234) | Feb 07, 2022 |
| ASUSTek       | K73SD                       | [ee4f8f2bfb](https://linux-hardware.org/?probe=ee4f8f2bfb) | Feb 07, 2022 |
| SLIMBOOK      | ESSENTIAL15-AMD             | [609b645899](https://linux-hardware.org/?probe=609b645899) | Feb 07, 2022 |
| Framework     | Laptop                      | [55d5b56564](https://linux-hardware.org/?probe=55d5b56564) | Feb 07, 2022 |
| Acer          | Aspire 7730G                | [2da9bdb8af](https://linux-hardware.org/?probe=2da9bdb8af) | Feb 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | [776a8f55b3](https://linux-hardware.org/?probe=776a8f55b3) | Feb 07, 2022 |
| HP            | Notebook                    | [be3e049297](https://linux-hardware.org/?probe=be3e049297) | Feb 07, 2022 |
| Apple         | MacBookPro11,4              | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| HP            | Pavilion dv7                | [e8cd45b30d](https://linux-hardware.org/?probe=e8cd45b30d) | Feb 07, 2022 |
| Toshiba       | Satellite C855-1TT          | [87eacffdb8](https://linux-hardware.org/?probe=87eacffdb8) | Feb 07, 2022 |
| Acer          | Nitro AN515-54              | [38aadf36ea](https://linux-hardware.org/?probe=38aadf36ea) | Feb 07, 2022 |
| Dell          | Latitude E7450              | [dd81e34279](https://linux-hardware.org/?probe=dd81e34279) | Feb 07, 2022 |
| Acer          | Aspire 4820TG               | [89b1f265e3](https://linux-hardware.org/?probe=89b1f265e3) | Feb 07, 2022 |
| Sony          | VPCF22C5E                   | [1887e093ef](https://linux-hardware.org/?probe=1887e093ef) | Feb 05, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 904       | 98.47%  |
| 5.16.13-desktop-1omv4003 | 10        | 1.09%   |
| 5.16.9-desktop-1omv4003  | 2         | 0.22%   |
| 5.16.9-desktop-1omv4050  | 1         | 0.11%   |
| 5.16.5-desktop-2omv4003  | 1         | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.7  | 904       | 98.47%  |
| 5.16.13 | 10        | 1.09%   |
| 5.16.9  | 3         | 0.33%   |
| 5.16.5  | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 918       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 918       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 917       | 99.89%  |
| Unknown | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 917       | 99.89%  |
| Wayland | 1         | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 918       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 496       | 54.03%  |
| de_DE | 107       | 11.66%  |
| fr_FR | 44        | 4.79%   |
| it_IT | 38        | 4.14%   |
| pt_BR | 37        | 4.03%   |
| pl_PL | 34        | 3.7%    |
| es_ES | 19        | 2.07%   |
| ru_RU | 18        | 1.96%   |
| en_GB | 16        | 1.74%   |
| de_AT | 13        | 1.42%   |
| es_MX | 12        | 1.31%   |
| es_AR | 8         | 0.87%   |
| nl_BE | 7         | 0.76%   |
| hu_HU | 7         | 0.76%   |
| cs_CZ | 7         | 0.76%   |
| tr_TR | 5         | 0.54%   |
| nl_NL | 4         | 0.44%   |
| es_CO | 4         | 0.44%   |
| de_CH | 4         | 0.44%   |
| pt_PT | 3         | 0.33%   |
| fr_CA | 3         | 0.33%   |
| es_CL | 3         | 0.33%   |
| en_IN | 3         | 0.33%   |
| en_CA | 3         | 0.33%   |
| fr_BE | 2         | 0.22%   |
| es_VE | 2         | 0.22%   |
| es_BO | 2         | 0.22%   |
| en_AU | 2         | 0.22%   |
| da_DK | 2         | 0.22%   |
| tr_CY | 1         | 0.11%   |
| ru_UA | 1         | 0.11%   |
| nb_NO | 1         | 0.11%   |
| fr_CH | 1         | 0.11%   |
| es_UY | 1         | 0.11%   |
| es_PY | 1         | 0.11%   |
| es_PR | 1         | 0.11%   |
| es_PE | 1         | 0.11%   |
| es_EC | 1         | 0.11%   |
| es_CR | 1         | 0.11%   |
| en_ZW | 1         | 0.11%   |
| en_ZA | 1         | 0.11%   |
| en_SG | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 496       | 54.03%  |
| BIOS | 422       | 45.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 739       | 80.5%   |
| Ext4    | 175       | 19.06%  |
| Xfs     | 2         | 0.22%   |
| Jfs     | 1         | 0.11%   |
| Btrfs   | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 631       | 68.74%  |
| MBR  | 287       | 31.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 464       | 50.54%  |
| No        | 454       | 49.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 541       | 58.93%  |
| Yes       | 377       | 41.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo                                    | 184       | 20.04%  |
| Hewlett-Packard                           | 167       | 18.19%  |
| Dell                                      | 128       | 13.94%  |
| ASUSTek Computer                          | 102       | 11.11%  |
| Acer                                      | 98        | 10.68%  |
| Toshiba                                   | 54        | 5.88%   |
| Samsung Electronics                       | 21        | 2.29%   |
| Fujitsu                                   | 20        | 2.18%   |
| Sony                                      | 19        | 2.07%   |
| MSI                                       | 15        | 1.63%   |
| Apple                                     | 15        | 1.63%   |
| Positivo                                  | 8         | 0.87%   |
| Packard Bell                              | 8         | 0.87%   |
| Medion                                    | 7         | 0.76%   |
| TUXEDO                                    | 6         | 0.65%   |
| Philco                                    | 6         | 0.65%   |
| HUAWEI                                    | 6         | 0.65%   |
| Positivo Bahia - VAIO                     | 3         | 0.33%   |
| Notebook                                  | 3         | 0.33%   |
| Fujitsu Siemens                           | 3         | 0.33%   |
| eMachines                                 | 3         | 0.33%   |
| Chuwi                                     | 3         | 0.33%   |
| Unknown                                   | 3         | 0.33%   |
| PC Specialist                             | 2         | 0.22%   |
| Intel                                     | 2         | 0.22%   |
| Gigabyte Technology                       | 2         | 0.22%   |
| Gateway                                   | 2         | 0.22%   |
| Clevo                                     | 2         | 0.22%   |
| Alienware                                 | 2         | 0.22%   |
| Wortmann AG                               | 1         | 0.11%   |
| VIT                                       | 1         | 0.11%   |
| UMAX                                      | 1         | 0.11%   |
| Teclast                                   | 1         | 0.11%   |
| Talal Abu-Ghazaleh for Technology TAGTECH | 1         | 0.11%   |
| SLIMBOOK                                  | 1         | 0.11%   |
| Schenker                                  | 1         | 0.11%   |
| Radio Victoria Fueguina                   | 1         | 0.11%   |
| Quanta                                    | 1         | 0.11%   |
| Panasonic                                 | 1         | 0.11%   |
| LincPlus                                  | 1         | 0.11%   |
| Lanix                                     | 1         | 0.11%   |
| Infinix                                   | 1         | 0.11%   |
| Framework                                 | 1         | 0.11%   |
| EVOO                                      | 1         | 0.11%   |
| Digibras                                  | 1         | 0.11%   |
| Dataton                                   | 1         | 0.11%   |
| Coradir                                   | 1         | 0.11%   |
| Computer Depot                            | 1         | 0.11%   |
| Compaq                                    | 1         | 0.11%   |
| Beelink                                   | 1         | 0.11%   |
| AZW                                       | 1         | 0.11%   |
| AWOW                                      | 1         | 0.11%   |
| ARKA                                      | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 10        | 1.09%   |
| HP Notebook                                | 8         | 0.87%   |
| Lenovo IdeaPad S340-14API 81NB             | 5         | 0.54%   |
| HP Pavilion g6                             | 5         | 0.54%   |
| HP Pavilion dv6                            | 5         | 0.54%   |
| Dell Latitude 3310                         | 4         | 0.44%   |
| Dell Latitude 3189                         | 4         | 0.44%   |
| Toshiba Satellite P200                     | 3         | 0.33%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 3         | 0.33%   |
| Positivo Mobile                            | 3         | 0.33%   |
| MSI GE72VR 6RF                             | 3         | 0.33%   |
| Lenovo IdeaPad Y700-17ISK 80Q0             | 3         | 0.33%   |
| HUAWEI NBLK-WAX9X                          | 3         | 0.33%   |
| HP Pavilion Laptop 15-eh0xxx               | 3         | 0.33%   |
| HP Pavilion g7                             | 3         | 0.33%   |
| HP Pavilion dv7                            | 3         | 0.33%   |
| HP Pavilion dv6500                         | 3         | 0.33%   |
| HP Pavilion 15                             | 3         | 0.33%   |
| HP Pavilion 11 x360 PC                     | 3         | 0.33%   |
| HP Laptop 17-ak0xx                         | 3         | 0.33%   |
| HP Laptop 15-db0xxx                        | 3         | 0.33%   |
| HP Laptop 15-da0xxx                        | 3         | 0.33%   |
| HP 2000                                    | 3         | 0.33%   |
| Dell Latitude E7450                        | 3         | 0.33%   |
| Dell Latitude E7240                        | 3         | 0.33%   |
| Dell Latitude E6420                        | 3         | 0.33%   |
| Dell Latitude E6230                        | 3         | 0.33%   |
| Dell Latitude E5410                        | 3         | 0.33%   |
| Dell Latitude D630                         | 3         | 0.33%   |
| Dell Inspiron N5110                        | 3         | 0.33%   |
| ASUS X555LJ                                | 3         | 0.33%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA     | 3         | 0.33%   |
| Apple MacBookPro9,2                        | 3         | 0.33%   |
| Acer Swift SF114-34                        | 3         | 0.33%   |
| Acer Aspire R3-131T                        | 3         | 0.33%   |
| Acer Aspire A515-51G                       | 3         | 0.33%   |
| TUXEDO Aura 15 Gen1                        | 2         | 0.22%   |
| Toshiba Satellite S855D                    | 2         | 0.22%   |
| Toshiba Satellite Pro R50-C                | 2         | 0.22%   |
| Toshiba Satellite Pro C660                 | 2         | 0.22%   |
| Toshiba Satellite L755                     | 2         | 0.22%   |
| Sony VGN-FZ31Z                             | 2         | 0.22%   |
| Samsung 700T                               | 2         | 0.22%   |
| Positivo S14SL01                           | 2         | 0.22%   |
| Philco 14I                                 | 2         | 0.22%   |
| Philco 10D                                 | 2         | 0.22%   |
| Lenovo ThinkPad X220 42875TU               | 2         | 0.22%   |
| Lenovo IdeaPad Z580                        | 2         | 0.22%   |
| Lenovo IdeaPad S145-15API 81UT             | 2         | 0.22%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7           | 2         | 0.22%   |
| Lenovo IdeaPad 5 15ALC05 82LN              | 2         | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81FE              | 2         | 0.22%   |
| Lenovo G570 20079                          | 2         | 0.22%   |
| Lenovo G510 20238                          | 2         | 0.22%   |
| Lenovo G505s 20255                         | 2         | 0.22%   |
| Lenovo G50-30 80G0                         | 2         | 0.22%   |
| HP ProBook 650 G1                          | 2         | 0.22%   |
| HP Presario CQ57                           | 2         | 0.22%   |
| HP Pavilion Laptop 15-cs3xxx               | 2         | 0.22%   |
| HP Pavilion dv5                            | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 81        | 8.82%   |
| Dell Latitude         | 77        | 8.39%   |
| Acer Aspire           | 69        | 7.52%   |
| Lenovo IdeaPad        | 52        | 5.66%   |
| Toshiba Satellite     | 44        | 4.79%   |
| HP Pavilion           | 44        | 4.79%   |
| HP Laptop             | 27        | 2.94%   |
| Dell Inspiron         | 27        | 2.94%   |
| ASUS VivoBook         | 22        | 2.4%    |
| HP ProBook            | 17        | 1.85%   |
| Fujitsu LIFEBOOK      | 14        | 1.53%   |
| HP EliteBook          | 12        | 1.31%   |
| HP Compaq             | 11        | 1.2%    |
| Unknown               | 10        | 1.09%   |
| Acer Swift            | 9         | 0.98%   |
| HP Notebook           | 8         | 0.87%   |
| Packard Bell EasyNote | 7         | 0.76%   |
| Acer Extensa          | 7         | 0.76%   |
| Dell XPS              | 6         | 0.65%   |
| HP OMEN               | 5         | 0.54%   |
| Dell System           | 5         | 0.54%   |
| Dell Precision        | 5         | 0.54%   |
| Acer Nitro            | 5         | 0.54%   |
| Toshiba dynabook      | 4         | 0.44%   |
| Lenovo Yoga           | 4         | 0.44%   |
| Lenovo Legion         | 4         | 0.44%   |
| HP ENVY               | 4         | 0.44%   |
| HP 255                | 4         | 0.44%   |
| HP 250                | 4         | 0.44%   |
| Toshiba TECRA         | 3         | 0.33%   |
| Samsung 300E4A        | 3         | 0.33%   |
| Positivo Mobile       | 3         | 0.33%   |
| MSI GE72VR            | 3         | 0.33%   |
| Medion Akoya          | 3         | 0.33%   |
| Lenovo Flex           | 3         | 0.33%   |
| HUAWEI NBLK-WAX9X     | 3         | 0.33%   |
| HP ZBook              | 3         | 0.33%   |
| HP Stream             | 3         | 0.33%   |
| HP Presario           | 3         | 0.33%   |
| HP 245                | 3         | 0.33%   |
| HP 2000               | 3         | 0.33%   |
| Dell Vostro           | 3         | 0.33%   |
| ASUS ZenBook          | 3         | 0.33%   |
| ASUS X555LJ           | 3         | 0.33%   |
| ASUS TUF              | 3         | 0.33%   |
| Apple MacBookPro9     | 3         | 0.33%   |
| Acer TravelMate       | 3         | 0.33%   |
| TUXEDO Pulse          | 2         | 0.22%   |
| TUXEDO Aura           | 2         | 0.22%   |
| Toshiba PORTEGE       | 2         | 0.22%   |
| Sony VGN-FZ31Z        | 2         | 0.22%   |
| Samsung 700T          | 2         | 0.22%   |
| Positivo S14SL01      | 2         | 0.22%   |
| Philco 14I            | 2         | 0.22%   |
| Philco 10D            | 2         | 0.22%   |
| MSI GE62              | 2         | 0.22%   |
| Lenovo G580           | 2         | 0.22%   |
| Lenovo G570           | 2         | 0.22%   |
| Lenovo G560           | 2         | 0.22%   |
| Lenovo G510           | 2         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 103       | 11.22%  |
| 2011    | 90        | 9.8%    |
| 2020    | 73        | 7.95%   |
| 2013    | 73        | 7.95%   |
| 2016    | 66        | 7.19%   |
| 2019    | 64        | 6.97%   |
| 2014    | 63        | 6.86%   |
| 2010    | 58        | 6.32%   |
| 2015    | 56        | 6.1%    |
| 2021    | 52        | 5.66%   |
| 2018    | 52        | 5.66%   |
| 2017    | 46        | 5.01%   |
| 2008    | 43        | 4.68%   |
| 2009    | 39        | 4.25%   |
| 2007    | 37        | 4.03%   |
| 2006    | 2         | 0.22%   |
| Unknown | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 918       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 918       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 918       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 313       | 34.1%   |
| 3.01-4.0    | 292       | 31.81%  |
| 8.01-16.0   | 135       | 14.71%  |
| 16.01-24.0  | 101       | 11%     |
| 1.01-2.0    | 33        | 3.59%   |
| 32.01-64.0  | 17        | 1.85%   |
| 2.01-3.0    | 15        | 1.63%   |
| 24.01-32.0  | 4         | 0.44%   |
| 64.01-256.0 | 4         | 0.44%   |
| 0.51-1.0    | 4         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 754       | 82.14%  |
| 0.51-1.0  | 95        | 10.35%  |
| 2.01-3.0  | 56        | 6.1%    |
| 3.01-4.0  | 4         | 0.44%   |
| 0.01-0.5  | 4         | 0.44%   |
| 4.01-8.0  | 3         | 0.33%   |
| 8.01-16.0 | 2         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 663       | 72.22%  |
| 2      | 212       | 23.09%  |
| 3      | 23        | 2.51%   |
| 0      | 15        | 1.63%   |
| 4      | 5         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 488       | 53.16%  |
| Yes       | 430       | 46.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 782       | 85.19%  |
| No        | 136       | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 909       | 99.02%  |
| No        | 9         | 0.98%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 689       | 75.05%  |
| No        | 229       | 24.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| Germany                | 147       | 16.01%  |
| USA                    | 101       | 11%     |
| France                 | 57        | 6.21%   |
| Brazil                 | 55        | 5.99%   |
| Poland                 | 53        | 5.77%   |
| Italy                  | 51        | 5.56%   |
| Russia                 | 30        | 3.27%   |
| Spain                  | 28        | 3.05%   |
| Netherlands            | 27        | 2.94%   |
| Canada                 | 24        | 2.61%   |
| UK                     | 23        | 2.51%   |
| Mexico                 | 19        | 2.07%   |
| Indonesia              | 19        | 2.07%   |
| Austria                | 16        | 1.74%   |
| Australia              | 14        | 1.53%   |
| Japan                  | 12        | 1.31%   |
| Turkey                 | 11        | 1.2%    |
| Bulgaria               | 11        | 1.2%    |
| Argentina              | 11        | 1.2%    |
| Switzerland            | 10        | 1.09%   |
| Portugal               | 10        | 1.09%   |
| Hungary                | 10        | 1.09%   |
| Czechia                | 10        | 1.09%   |
| Belgium                | 10        | 1.09%   |
| India                  | 9         | 0.98%   |
| Colombia               | 9         | 0.98%   |
| Ukraine                | 8         | 0.87%   |
| Sweden                 | 8         | 0.87%   |
| Slovakia               | 8         | 0.87%   |
| China                  | 8         | 0.87%   |
| Romania                | 7         | 0.76%   |
| Serbia                 | 6         | 0.65%   |
| Greece                 | 6         | 0.65%   |
| Finland                | 6         | 0.65%   |
| New Zealand            | 5         | 0.54%   |
| Chile                  | 5         | 0.54%   |
| Venezuela              | 4         | 0.44%   |
| Croatia                | 4         | 0.44%   |
| South Africa           | 3         | 0.33%   |
| Norway                 | 3         | 0.33%   |
| Egypt                  | 3         | 0.33%   |
| Costa Rica             | 3         | 0.33%   |
| Vietnam                | 2         | 0.22%   |
| Trinidad and Tobago    | 2         | 0.22%   |
| Singapore              | 2         | 0.22%   |
| Philippines            | 2         | 0.22%   |
| Peru                   | 2         | 0.22%   |
| Morocco                | 2         | 0.22%   |
| Israel                 | 2         | 0.22%   |
| Ecuador                | 2         | 0.22%   |
| Denmark                | 2         | 0.22%   |
| Bosnia and Herzegovina | 2         | 0.22%   |
| Bolivia                | 2         | 0.22%   |
| Zimbabwe               | 1         | 0.11%   |
| Uzbekistan             | 1         | 0.11%   |
| Uruguay                | 1         | 0.11%   |
| UAE                    | 1         | 0.11%   |
| Tunisia                | 1         | 0.11%   |
| Thailand               | 1         | 0.11%   |
| Taiwan                 | 1         | 0.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Berlin                 | 14        | 1.53%   |
| Schagen                | 11        | 1.2%    |
| Sao Paulo              | 11        | 1.2%    |
| Warsaw                 | 9         | 0.98%   |
| Paris                  | 9         | 0.98%   |
| Vienna                 | 8         | 0.87%   |
| Milan                  | 8         | 0.87%   |
| Krakow                 | 8         | 0.87%   |
| Sydney                 | 6         | 0.65%   |
| Salach                 | 6         | 0.65%   |
| Wroclaw                | 5         | 0.54%   |
| Prague                 | 5         | 0.54%   |
| Moscow                 | 5         | 0.54%   |
| Mexico City            | 5         | 0.54%   |
| Istanbul               | 5         | 0.54%   |
| Hamburg                | 5         | 0.54%   |
| Cologne                | 5         | 0.54%   |
| Belgrade               | 5         | 0.54%   |
| Sofia                  | 4         | 0.44%   |
| Padova                 | 4         | 0.44%   |
| Montreal               | 4         | 0.44%   |
| Jakarta                | 4         | 0.44%   |
| Bologna                | 4         | 0.44%   |
| Auckland               | 4         | 0.44%   |
| Werdau                 | 3         | 0.33%   |
| Villeurbanne           | 3         | 0.33%   |
| Surabaya               | 3         | 0.33%   |
| Sangerhausen           | 3         | 0.33%   |
| Rio de Janeiro         | 3         | 0.33%   |
| Richmond Hill          | 3         | 0.33%   |
| Regina                 | 3         | 0.33%   |
| MedellÃ­n            | 3         | 0.33%   |
| MÃ©rida              | 3         | 0.33%   |
| Madrid                 | 3         | 0.33%   |
| Inman                  | 3         | 0.33%   |
| GorzÃ³w Wielkopolski | 3         | 0.33%   |
| Duisburg               | 3         | 0.33%   |
| Champaign              | 3         | 0.33%   |
| Braunschweig           | 3         | 0.33%   |
| Bratislava             | 3         | 0.33%   |
| Bonn                   | 3         | 0.33%   |
| Barcelona              | 3         | 0.33%   |
| Athens                 | 3         | 0.33%   |
| Zagreb                 | 2         | 0.22%   |
| Yaroslavl              | 2         | 0.22%   |
| Yambol                 | 2         | 0.22%   |
| Wesel                  | 2         | 0.22%   |
| Umhausen               | 2         | 0.22%   |
| Turnhout               | 2         | 0.22%   |
| The Hague              | 2         | 0.22%   |
| Stuttgart              | 2         | 0.22%   |
| Singapore              | 2         | 0.22%   |
| Senigallia             | 2         | 0.22%   |
| Seattle                | 2         | 0.22%   |
| Schijndel              | 2         | 0.22%   |
| Scarborough            | 2         | 0.22%   |
| Sault Ste. Marie       | 2         | 0.22%   |
| Sarajevo               | 2         | 0.22%   |
| Sapporo                | 2         | 0.22%   |
| Santa Cruz de Tenerife | 2         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 143       | 151    | 13.07%  |
| WDC                 | 134       | 136    | 12.25%  |
| Seagate             | 124       | 128    | 11.33%  |
| Toshiba             | 113       | 115    | 10.33%  |
| Kingston            | 72        | 73     | 6.58%   |
| Hitachi             | 45        | 45     | 4.11%   |
| Crucial             | 45        | 47     | 4.11%   |
| HGST                | 41        | 41     | 3.75%   |
| Unknown             | 40        | 41     | 3.66%   |
| SanDisk             | 34        | 34     | 3.11%   |
| SK Hynix            | 31        | 35     | 2.83%   |
| Micron Technology   | 25        | 25     | 2.29%   |
| A-DATA Technology   | 23        | 23     | 2.1%    |
| Intel               | 22        | 23     | 2.01%   |
| Fujitsu             | 13        | 13     | 1.19%   |
| Unknown             | 13        | 13     | 1.19%   |
| LITEON              | 12        | 12     | 1.1%    |
| Intenso             | 10        | 10     | 0.91%   |
| ASMT                | 8         | 8      | 0.73%   |
| GOODRAM             | 7         | 7      | 0.64%   |
| Patriot             | 6         | 6      | 0.55%   |
| KIOXIA              | 6         | 6      | 0.55%   |
| JMicron             | 6         | 6      | 0.55%   |
| Corsair             | 6         | 6      | 0.55%   |
| Apple               | 6         | 6      | 0.55%   |
| Transcend           | 5         | 5      | 0.46%   |
| SSSTC               | 5         | 5      | 0.46%   |
| SPCC                | 5         | 5      | 0.46%   |
| SABRENT             | 5         | 5      | 0.46%   |
| Phison              | 5         | 5      | 0.46%   |
| KingSpec            | 5         | 5      | 0.46%   |
| China               | 5         | 5      | 0.46%   |
| LITEONIT            | 4         | 4      | 0.37%   |
| UMIS                | 3         | 3      | 0.27%   |
| Silicon Motion      | 3         | 4      | 0.27%   |
| PNY                 | 3         | 3      | 0.27%   |
| PLEXTOR             | 3         | 3      | 0.27%   |
| OCZ                 | 3         | 3      | 0.27%   |
| Lexar               | 3         | 3      | 0.27%   |
| KingDian            | 3         | 3      | 0.27%   |
| TCSUNBOW            | 2         | 2      | 0.18%   |
| INNOVATION IT       | 2         | 2      | 0.18%   |
| INDMEM              | 2         | 2      | 0.18%   |
| Hewlett-Packard     | 2         | 2      | 0.18%   |
| Gigabyte Technology | 2         | 2      | 0.18%   |
| DREVO               | 2         | 2      | 0.18%   |
| DOGFISH             | 2         | 2      | 0.18%   |
| ASMedia             | 2         | 2      | 0.18%   |
| Apacer              | 2         | 2      | 0.18%   |
| XrayDisk            | 1         | 1      | 0.09%   |
| Wdxsky              | 1         | 1      | 0.09%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| Verbatim            | 1         | 1      | 0.09%   |
| Vaseky              | 1         | 1      | 0.09%   |
| T-FORCE             | 1         | 1      | 0.09%   |
| SUNTRSI             | 1         | 1      | 0.09%   |
| SSK                 | 1         | 1      | 0.09%   |
| SPCC M.2            | 1         | 1      | 0.09%   |
| ROG                 | 1         | 1      | 0.09%   |
| Phison Electronics  | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 23        | 2.07%   |
| Toshiba MQ01ABF050 500GB                | 19        | 1.71%   |
| Kingston SA400S37240G 240GB SSD         | 18        | 1.62%   |
| Toshiba MQ04ABF100 1TB                  | 16        | 1.44%   |
| Seagate ST500LT012-1DG142 500GB         | 13        | 1.17%   |
| Unknown                                 | 13        | 1.17%   |
| HGST HTS721010A9E630 1TB                | 12        | 1.08%   |
| Samsung SSD 860 EVO 500GB               | 11        | 0.99%   |
| Toshiba MQ01ABD100 1TB                  | 10        | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB          | 10        | 0.9%    |
| Samsung SSD 850 EVO 250GB               | 10        | 0.9%    |
| Hitachi HTS543232A7A384 320GB           | 10        | 0.9%    |
| Kingston SA400S37480G 480GB SSD         | 9         | 0.81%   |
| Seagate ST9500325AS 500GB               | 8         | 0.72%   |
| HGST HTS541010A9E680 1TB                | 8         | 0.72%   |
| Crucial CT240BX500SSD1 240GB            | 8         | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 7         | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 7         | 0.63%   |
| Samsung SSD 860 QVO 1TB                 | 7         | 0.63%   |
| Seagate ST9320325AS 320GB               | 6         | 0.54%   |
| SanDisk SSD PLUS 480GB                  | 6         | 0.54%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 6         | 0.54%   |
| Kingston SA400S37120G 120GB SSD         | 6         | 0.54%   |
| JMicron Generic 240GB                   | 6         | 0.54%   |
| Crucial CT1000BX500SSD1 1TB             | 6         | 0.54%   |
| A-DATA SX8200PNP 512GB                  | 6         | 0.54%   |
| Toshiba MK1246GSX 120GB                 | 5         | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB         | 5         | 0.45%   |
| Samsung SSD 860 EVO 250GB               | 5         | 0.45%   |
| Crucial CT500MX500SSD1 500GB            | 5         | 0.45%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 4         | 0.36%   |
| WDC WD10SPZX-24Z10 1TB                  | 4         | 0.36%   |
| Unknown SD64G  64GB                     | 4         | 0.36%   |
| Unknown SD/MMC/MS PRO 16GB              | 4         | 0.36%   |
| Toshiba TR200 240GB SSD                 | 4         | 0.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 4         | 0.36%   |
| Seagate ST500LM000-1EJ162 500GB         | 4         | 0.36%   |
| Samsung SSD 840 EVO 500GB               | 4         | 0.36%   |
| Samsung MZVLB1T0HBLR-000L2 1TB          | 4         | 0.36%   |
| Intenso SSD Sata III 256GB              | 4         | 0.36%   |
| Hitachi HTS547575A9E384 752GB           | 4         | 0.36%   |
| Hitachi HTS545025B9SA02 250GB           | 4         | 0.36%   |
| HGST HTS725050A7E630 500GB              | 4         | 0.36%   |
| HGST HTS545050A7E680 500GB              | 4         | 0.36%   |
| HGST HTS545050A7E380 500GB              | 4         | 0.36%   |
| Crucial CT1000MX500SSD1 1TB             | 4         | 0.36%   |
| WDC WD5000BEKT-75KA9T0 500GB            | 3         | 0.27%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 3         | 0.27%   |
| WDC WD10JPVX-60JC3T0 1TB                | 3         | 0.27%   |
| WDC WD10JPCX-24UE4T0 1TB                | 3         | 0.27%   |
| Unknown ISOCOM  64GB                    | 3         | 0.27%   |
| Unknown DA4064  64GB                    | 3         | 0.27%   |
| Toshiba MQ01ACF050 500GB                | 3         | 0.27%   |
| Toshiba MQ01ABF032 320GB                | 3         | 0.27%   |
| Toshiba MK2035GSS 200GB                 | 3         | 0.27%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 3         | 0.27%   |
| SK Hynix HFS256G39MND-3510A 256GB SSD   | 3         | 0.27%   |
| SK Hynix HFM128GDJTNG-8310A 128GB       | 3         | 0.27%   |
| Seagate ST9320423AS 320GB               | 3         | 0.27%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 3         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 126    | 27.85%  |
| WDC                 | 98        | 98     | 22.37%  |
| Toshiba             | 96        | 98     | 21.92%  |
| Hitachi             | 45        | 45     | 10.27%  |
| HGST                | 41        | 41     | 9.36%   |
| Fujitsu             | 13        | 13     | 2.97%   |
| Samsung Electronics | 7         | 7      | 1.6%    |
| Unknown             | 4         | 4      | 0.91%   |
| SABRENT             | 3         | 3      | 0.68%   |
| ASMT                | 3         | 3      | 0.68%   |
| Apple               | 2         | 2      | 0.46%   |
| WD MediaMax         | 1         | 1      | 0.23%   |
| HGST HTS            | 1         | 1      | 0.23%   |
| Hewlett-Packard     | 1         | 1      | 0.23%   |
| ASMedia             | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 99        | 104    | 22.55%  |
| Kingston            | 56        | 57     | 12.76%  |
| Crucial             | 41        | 43     | 9.34%   |
| SanDisk             | 30        | 30     | 6.83%   |
| Micron Technology   | 21        | 21     | 4.78%   |
| WDC                 | 19        | 19     | 4.33%   |
| A-DATA Technology   | 14        | 14     | 3.19%   |
| SK Hynix            | 13        | 14     | 2.96%   |
| Toshiba             | 12        | 12     | 2.73%   |
| LITEON              | 10        | 10     | 2.28%   |
| Intenso             | 10        | 10     | 2.28%   |
| GOODRAM             | 7         | 7      | 1.59%   |
| Unknown             | 7         | 7      | 1.59%   |
| Patriot             | 6         | 6      | 1.37%   |
| JMicron             | 6         | 6      | 1.37%   |
| Intel               | 6         | 6      | 1.37%   |
| Transcend           | 5         | 5      | 1.14%   |
| KingSpec            | 5         | 5      | 1.14%   |
| China               | 5         | 5      | 1.14%   |
| LITEONIT            | 4         | 4      | 0.91%   |
| Corsair             | 4         | 4      | 0.91%   |
| Apple               | 4         | 4      | 0.91%   |
| SPCC                | 3         | 3      | 0.68%   |
| PNY                 | 3         | 3      | 0.68%   |
| PLEXTOR             | 3         | 3      | 0.68%   |
| OCZ                 | 3         | 3      | 0.68%   |
| Lexar               | 3         | 3      | 0.68%   |
| KingDian            | 3         | 3      | 0.68%   |
| TCSUNBOW            | 2         | 2      | 0.46%   |
| INNOVATION IT       | 2         | 2      | 0.46%   |
| Drevo               | 2         | 2      | 0.46%   |
| DOGFISH             | 2         | 2      | 0.46%   |
| ASMT                | 2         | 2      | 0.46%   |
| Apacer              | 2         | 2      | 0.46%   |
| XrayDisk            | 1         | 1      | 0.23%   |
| Wdxsky              | 1         | 1      | 0.23%   |
| Vaseky              | 1         | 1      | 0.23%   |
| T-FORCE             | 1         | 1      | 0.23%   |
| SUNTRSI             | 1         | 1      | 0.23%   |
| SPCC M.2            | 1         | 1      | 0.23%   |
| Seagate             | 1         | 1      | 0.23%   |
| MidasForce          | 1         | 1      | 0.23%   |
| LS600               | 1         | 1      | 0.23%   |
| Leven               | 1         | 1      | 0.23%   |
| KLEVV               | 1         | 1      | 0.23%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.23%   |
| KingFast            | 1         | 1      | 0.23%   |
| Kingchuxing         | 1         | 1      | 0.23%   |
| InnoDisk            | 1         | 1      | 0.23%   |
| imation             | 1         | 1      | 0.23%   |
| HS-SSD-E100N        | 1         | 1      | 0.23%   |
| Hewlett-Packard     | 1         | 1      | 0.23%   |
| GOLDEN              | 1         | 1      | 0.23%   |
| Gigabyte Technology | 1         | 1      | 0.23%   |
| FORESEE             | 1         | 1      | 0.23%   |
| External            | 1         | 1      | 0.23%   |
| BHT                 | 1         | 1      | 0.23%   |
| ASMedia             | 1         | 1      | 0.23%   |
| 2.5"                | 1         | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 427       | 444    | 40.59%  |
| SSD     | 415       | 448    | 39.45%  |
| NVMe    | 153       | 167    | 14.54%  |
| MMC     | 46        | 49     | 4.37%   |
| Unknown | 11        | 12     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 765       | 854    | 75.59%  |
| NVMe | 153       | 166    | 15.12%  |
| SAS  | 48        | 51     | 4.74%   |
| MMC  | 46        | 49     | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 598       | 651    | 71.88%  |
| 0.51-1.0   | 209       | 215    | 25.12%  |
| 1.01-2.0   | 22        | 23     | 2.64%   |
| 4.01-10.0  | 2         | 2      | 0.24%   |
| 3.01-4.0   | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 541       | 58.93%  |
| 101-250    | 143       | 15.58%  |
| 251-500    | 88        | 9.59%   |
| 51-100     | 43        | 4.68%   |
| 501-1000   | 40        | 4.36%   |
| 21-50      | 30        | 3.27%   |
| Unknown    | 23        | 2.51%   |
| 1001-2000  | 10        | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 830       | 90.41%  |
| Unknown   | 23        | 2.51%   |
| 51-100    | 22        | 2.4%    |
| 101-250   | 17        | 1.85%   |
| 21-50     | 16        | 1.74%   |
| 251-500   | 7         | 0.76%   |
| 1001-2000 | 2         | 0.22%   |
| 501-1000  | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 11        | 11     | 5.31%   |
| Toshiba MQ01ABF050 500GB                            | 9         | 9      | 4.35%   |
| Hitachi HTS543232A7A384 320GB                       | 8         | 8      | 3.86%   |
| Seagate ST9320325AS 320GB                           | 6         | 6      | 2.9%    |
| HGST HTS721010A9E630 1TB                            | 5         | 5      | 2.42%   |
| HGST HTS541010A9E680 1TB                            | 5         | 5      | 2.42%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 4      | 1.93%   |
| Toshiba MK1246GSX 120GB                             | 4         | 4      | 1.93%   |
| Seagate ST9500325AS 500GB                           | 4         | 4      | 1.93%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 4      | 1.93%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 4      | 1.93%   |
| HGST HTS545050A7E380 500GB                          | 4         | 4      | 1.93%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 3      | 1.45%   |
| Hitachi HTS547575A9E384 752GB                       | 3         | 3      | 1.45%   |
| HGST HTS725050A7E630 500GB                          | 3         | 3      | 1.45%   |
| HGST HTS541075A9E680 752GB                          | 3         | 3      | 1.45%   |
| WDC WD5000BEKT-75KA9T0 500GB                        | 2         | 2      | 0.97%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 2         | 2      | 0.97%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 2      | 0.97%   |
| Toshiba MQ01ABD050 500GB                            | 2         | 2      | 0.97%   |
| Toshiba MK2555GSX 250GB                             | 2         | 2      | 0.97%   |
| Toshiba MK2035GSS 200GB                             | 2         | 2      | 0.97%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 2         | 2      | 0.97%   |
| Seagate ST9320423AS 320GB                           | 2         | 2      | 0.97%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 2      | 0.97%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 2      | 0.97%   |
| Seagate ST500LM000-1EJ162 500GB                     | 2         | 2      | 0.97%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.97%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 2      | 0.97%   |
| Hitachi HTS542516K9SA00 160GB                       | 2         | 2      | 0.97%   |
| Hitachi HTS541612J9SA00 120GB                       | 2         | 2      | 0.97%   |
| HGST HTS545050A7E680 500GB                          | 2         | 2      | 0.97%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 1      | 0.48%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 1      | 0.48%   |
| WDC WD3200BUDT-63DPZY0 320GB                        | 1         | 1      | 0.48%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 0.48%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 1         | 1      | 0.48%   |
| WDC WD3200BEVT-22A23T0 320GB                        | 1         | 1      | 0.48%   |
| WDC WD32 00BEVT-24A23 320GB                         | 1         | 1      | 0.48%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 0.48%   |
| WDC WD1600BEVT-22ZCT0 160GB                         | 1         | 1      | 0.48%   |
| WDC WD1600BEVS-60RST0 160GB                         | 1         | 1      | 0.48%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 1      | 0.48%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1      | 0.48%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 0.48%   |
| Vaseky V800/60G 64GB SSD                            | 1         | 1      | 0.48%   |
| Transcend TS128XBTMT3D58G 128GB SSD                 | 1         | 1      | 0.48%   |
| Toshiba MQ01ABF032 320GB                            | 1         | 1      | 0.48%   |
| Toshiba MQ01ABD100M 1TB                             | 1         | 1      | 0.48%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 0.48%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 0.48%   |
| Toshiba MK6459GSXP 640GB                            | 1         | 1      | 0.48%   |
| Toshiba MK5065GSXN 500GB                            | 1         | 1      | 0.48%   |
| Toshiba MK5055GSX 500GB                             | 1         | 1      | 0.48%   |
| Toshiba MK3265GSX 320GB                             | 1         | 1      | 0.48%   |
| Toshiba MK3263GSX 320GB                             | 1         | 1      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 52     | 25.12%  |
| Toshiba             | 43        | 43     | 20.77%  |
| Hitachi             | 27        | 27     | 13.04%  |
| HGST                | 22        | 22     | 10.63%  |
| WDC                 | 21        | 21     | 10.14%  |
| Fujitsu             | 8         | 8      | 3.86%   |
| Samsung Electronics | 6         | 6      | 2.9%    |
| Micron Technology   | 4         | 4      | 1.93%   |
| Kingston            | 4         | 4      | 1.93%   |
| A-DATA Technology   | 4         | 4      | 1.93%   |
| Crucial             | 3         | 3      | 1.45%   |
| SK Hynix            | 2         | 3      | 0.97%   |
| Intel               | 2         | 2      | 0.97%   |
| Vaseky              | 1         | 1      | 0.48%   |
| Transcend           | 1         | 1      | 0.48%   |
| SanDisk             | 1         | 1      | 0.48%   |
| LITEON              | 1         | 1      | 0.48%   |
| DREVO               | 1         | 1      | 0.48%   |
| DOGFISH             | 1         | 1      | 0.48%   |
| Corsair             | 1         | 1      | 0.48%   |
| ASMedia             | 1         | 1      | 0.48%   |
| Apple               | 1         | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 52     | 29.71%  |
| Toshiba             | 41        | 41     | 23.43%  |
| Hitachi             | 27        | 27     | 15.43%  |
| HGST                | 22        | 22     | 12.57%  |
| WDC                 | 21        | 21     | 12%     |
| Fujitsu             | 8         | 8      | 4.57%   |
| Samsung Electronics | 3         | 3      | 1.71%   |
| ASMedia             | 1         | 1      | 0.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 174       | 175    | 84.47%  |
| SSD  | 31        | 32     | 15.05%  |
| NVMe | 1         | 1      | 0.49%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 1      | 14.29%  |
| WDC WD3200BEVT-11ZCT0 320GB         | 1         | 1      | 14.29%  |
| WDC WD2500BEVT-60ZCT1 250GB         | 1         | 1      | 14.29%  |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 14.29%  |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 14.29%  |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 14.29%  |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 57.14%  |
| Toshiba | 1         | 1      | 14.29%  |
| Seagate | 1         | 1      | 14.29%  |
| Apple   | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 703       | 815    | 70.72%  |
| Malfunc  | 204       | 208    | 20.52%  |
| Detected | 80        | 90     | 8.05%   |
| Failed   | 7         | 7      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 706       | 70.39%  |
| AMD                              | 142       | 14.16%  |
| Samsung Electronics              | 41        | 4.09%   |
| Sandisk                          | 19        | 1.89%   |
| Kingston Technology Company      | 16        | 1.6%    |
| SK Hynix                         | 15        | 1.5%    |
| Phison Electronics               | 11        | 1.1%    |
| ADATA Technology                 | 7         | 0.7%    |
| Toshiba America Info Systems     | 6         | 0.6%    |
| Nvidia                           | 6         | 0.6%    |
| Solid State Storage Technology   | 5         | 0.5%    |
| Micron Technology                | 5         | 0.5%    |
| KIOXIA                           | 5         | 0.5%    |
| Silicon Motion                   | 4         | 0.4%    |
| Union Memory (Shenzhen)          | 3         | 0.3%    |
| Micron/Crucial Technology        | 3         | 0.3%    |
| Silicon Integrated Systems [SiS] | 2         | 0.2%    |
| Realtek Semiconductor            | 2         | 0.2%    |
| Lite-On Technology               | 2         | 0.2%    |
| Seagate Technology               | 1         | 0.1%    |
| JMicron Technology               | 1         | 0.1%    |
| ASMedia Technology               | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 108       | 9.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 101       | 9.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 75        | 6.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 59        | 5.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 58        | 5.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 56        | 5.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 41        | 3.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 37        | 3.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 33        | 3.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 29        | 2.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 27        | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 25        | 2.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 2.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 22        | 2.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 20        | 1.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 18        | 1.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 17        | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 1.19%   |
| Samsung NVMe SSD Controller 980                                                  | 12        | 1.1%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 11        | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 10        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 10        | 0.91%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 9         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 0.82%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 8         | 0.73%   |
| Intel SSD 660P Series                                                            | 8         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 0.73%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 0.64%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 6         | 0.55%   |
| Phison E12 NVMe Controller                                                       | 6         | 0.55%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 6         | 0.55%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 6         | 0.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 6         | 0.55%   |
| Solid State Storage Non-Volatile memory controller                               | 5         | 0.46%   |
| SK Hynix Gold P31 SSD                                                            | 5         | 0.46%   |
| Micron Non-Volatile memory controller                                            | 5         | 0.46%   |
| KIOXIA Non-Volatile memory controller                                            | 5         | 0.46%   |
| Intel Non-Volatile memory controller                                             | 5         | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 0.37%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 0.37%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 4         | 0.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.37%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 4         | 0.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 4         | 0.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 0.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 0.37%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4         | 0.37%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.27%   |
| Phison PS5013 E13 NVMe Controller                                                | 3         | 0.27%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 0.27%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.27%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.27%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                               | 3         | 0.27%   |
| Intel SSD 600P Series                                                            | 3         | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 750       | 71.02%  |
| NVMe | 153       | 14.49%  |
| IDE  | 84        | 7.95%   |
| RAID | 69        | 6.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 744       | 81.05%  |
| AMD    | 174       | 18.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 20        | 2.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 1.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 15        | 1.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 1.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 1.31%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 1.31%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 12        | 1.31%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 12        | 1.31%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 0.98%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.87%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.87%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 8         | 0.87%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 7         | 0.76%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 7         | 0.76%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.76%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 7         | 0.76%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 7         | 0.76%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 7         | 0.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 0.76%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.76%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 7         | 0.76%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 6         | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.65%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 6         | 0.65%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 6         | 0.65%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.65%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 6         | 0.65%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 6         | 0.65%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 0.54%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 5         | 0.54%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.54%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 5         | 0.54%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 5         | 0.54%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 5         | 0.54%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 0.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.54%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 5         | 0.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.54%   |
| AMD E-450 APU with Radeon HD Graphics         | 5         | 0.54%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 5         | 0.54%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 4         | 0.44%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 4         | 0.44%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 4         | 0.44%   |
| Intel Pentium CPU B970 @ 2.30GHz              | 4         | 0.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.44%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 0.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.44%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 247       | 26.91%  |
| Intel Core i7                        | 123       | 13.4%   |
| Intel Core i3                        | 102       | 11.11%  |
| Intel Celeron                        | 92        | 10.02%  |
| Intel Core 2 Duo                     | 71        | 7.73%   |
| Intel Pentium                        | 40        | 4.36%   |
| AMD Ryzen 5                          | 31        | 3.38%   |
| AMD Ryzen 7                          | 26        | 2.83%   |
| Other                                | 22        | 2.4%    |
| AMD A6                               | 16        | 1.74%   |
| AMD E1                               | 13        | 1.42%   |
| AMD A8                               | 12        | 1.31%   |
| AMD E                                | 11        | 1.2%    |
| Intel Pentium Dual-Core              | 10        | 1.09%   |
| AMD A4                               | 10        | 1.09%   |
| AMD Ryzen 3                          | 8         | 0.87%   |
| Intel Pentium Dual                   | 7         | 0.76%   |
| Intel Genuine                        | 7         | 0.76%   |
| Intel Atom                           | 7         | 0.76%   |
| AMD A10                              | 7         | 0.76%   |
| Intel Pentium Silver                 | 6         | 0.65%   |
| AMD E2                               | 6         | 0.65%   |
| Intel Core 2                         | 4         | 0.44%   |
| AMD C-60                             | 4         | 0.44%   |
| AMD Athlon II                        | 3         | 0.33%   |
| AMD Athlon                           | 3         | 0.33%   |
| Intel Core m5                        | 2         | 0.22%   |
| Intel Core m3                        | 2         | 0.22%   |
| Intel Core M                         | 2         | 0.22%   |
| Intel Core i9                        | 2         | 0.22%   |
| Intel Core 2 Quad                    | 2         | 0.22%   |
| AMD Ryzen 7 PRO                      | 2         | 0.22%   |
| AMD Phenom II                        | 2         | 0.22%   |
| AMD FX                               | 2         | 0.22%   |
| AMD Athlon 64 X2                     | 2         | 0.22%   |
| Intel Celeron Dual-Core              | 1         | 0.11%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.11%   |
| AMD Turion 64 Mobile                 | 1         | 0.11%   |
| AMD Sempron                          | 1         | 0.11%   |
| AMD Ryzen 9                          | 1         | 0.11%   |
| AMD Ryzen 5 PRO                      | 1         | 0.11%   |
| AMD GX                               | 1         | 0.11%   |
| AMD C-70                             | 1         | 0.11%   |
| AMD C-50                             | 1         | 0.11%   |
| AMD Athlon X2                        | 1         | 0.11%   |
| AMD Athlon Neo X2                    | 1         | 0.11%   |
| AMD Athlon Neo                       | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 626       | 68.19%  |
| 4      | 211       | 22.98%  |
| 6      | 31        | 3.38%   |
| 8      | 28        | 3.05%   |
| 1      | 20        | 2.18%   |
| 10     | 1         | 0.11%   |
| 3      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 918       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 572       | 62.31%  |
| 1      | 342       | 37.25%  |
| 8      | 4         | 0.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 917       | 99.89%  |
| Unknown        | 1         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 90        | 9.8%    |
| 0x206a7    | 89        | 9.69%   |
| 0x1067a    | 50        | 5.45%   |
| 0x20655    | 45        | 4.9%    |
| 0x406e3    | 41        | 4.47%   |
| 0x306d4    | 37        | 4.03%   |
| 0x40651    | 31        | 3.38%   |
| 0x6fd      | 30        | 3.27%   |
| 0x806ea    | 29        | 3.16%   |
| Unknown    | 24        | 2.61%   |
| 0x806e9    | 23        | 2.51%   |
| 0x306c3    | 23        | 2.51%   |
| 0x806ec    | 22        | 2.4%    |
| 0x706e5    | 19        | 2.07%   |
| 0x506e3    | 19        | 2.07%   |
| 0x30678    | 19        | 2.07%   |
| 0x406c4    | 17        | 1.85%   |
| 0x06006705 | 17        | 1.85%   |
| 0x10676    | 14        | 1.53%   |
| 0x08108109 | 14        | 1.53%   |
| 0x906ea    | 13        | 1.42%   |
| 0x20652    | 13        | 1.42%   |
| 0x806c1    | 12        | 1.31%   |
| 0x506c9    | 11        | 1.2%    |
| 0x08108102 | 11        | 1.2%    |
| 0x0500010d | 11        | 1.2%    |
| 0x706a8    | 10        | 1.09%   |
| 0x706a1    | 9         | 0.98%   |
| 0x08608103 | 9         | 0.98%   |
| 0x08600106 | 9         | 0.98%   |
| 0x07030105 | 9         | 0.98%   |
| 0x906e9    | 8         | 0.87%   |
| 0x0a50000c | 8         | 0.87%   |
| 0xa0652    | 7         | 0.76%   |
| 0x406c3    | 7         | 0.76%   |
| 0x0700010b | 7         | 0.76%   |
| 0x05000101 | 6         | 0.65%   |
| 0x806eb    | 5         | 0.54%   |
| 0x6fb      | 5         | 0.54%   |
| 0x30673    | 5         | 0.54%   |
| 0x30661    | 5         | 0.54%   |
| 0x906c0    | 4         | 0.44%   |
| 0x6f6      | 4         | 0.44%   |
| 0x10661    | 4         | 0.44%   |
| 0x08608102 | 4         | 0.44%   |
| 0x07030104 | 4         | 0.44%   |
| 0x06001119 | 4         | 0.44%   |
| 0x03000027 | 4         | 0.44%   |
| 0x6fa      | 3         | 0.33%   |
| 0x08600104 | 3         | 0.33%   |
| 0x08600103 | 3         | 0.33%   |
| 0x0600111f | 3         | 0.33%   |
| 0x05000028 | 3         | 0.33%   |
| 0x010000c8 | 3         | 0.33%   |
| 0x806d1    | 2         | 0.22%   |
| 0x106e5    | 2         | 0.22%   |
| 0x08200103 | 2         | 0.22%   |
| 0x0700010f | 2         | 0.22%   |
| 0x07000106 | 2         | 0.22%   |
| 0x06006704 | 2         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 104       | 11.33%  |
| IvyBridge       | 91        | 9.91%   |
| SandyBridge     | 89        | 9.69%   |
| Penryn          | 64        | 6.97%   |
| Skylake         | 63        | 6.86%   |
| Westmere        | 59        | 6.43%   |
| Haswell         | 55        | 5.99%   |
| Silvermont      | 48        | 5.23%   |
| Core            | 46        | 5.01%   |
| Broadwell       | 38        | 4.14%   |
| Zen+            | 25        | 2.72%   |
| Excavator       | 23        | 2.51%   |
| Bobcat          | 22        | 2.4%    |
| IceLake         | 19        | 2.07%   |
| Goldmont plus   | 19        | 2.07%   |
| Zen 2           | 18        | 1.96%   |
| Unknown         | 16        | 1.74%   |
| TigerLake       | 14        | 1.53%   |
| Puma            | 14        | 1.53%   |
| Zen 3           | 12        | 1.31%   |
| Jaguar          | 12        | 1.31%   |
| Piledriver      | 11        | 1.2%    |
| Goldmont        | 11        | 1.2%    |
| CometLake       | 9         | 0.98%   |
| K8 Hammer       | 6         | 0.65%   |
| Bonnell         | 6         | 0.65%   |
| Zen             | 5         | 0.54%   |
| K10             | 5         | 0.54%   |
| Tremont         | 4         | 0.44%   |
| K10 Llano       | 4         | 0.44%   |
| K8 & K10 hybrid | 3         | 0.33%   |
| Nehalem         | 2         | 0.22%   |
| Steamroller     | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 666       | 60.77%  |
| AMD                              | 222       | 20.26%  |
| Nvidia                           | 206       | 18.8%   |
| Silicon Integrated Systems [SiS] | 2         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 87        | 7.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 80        | 7.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 44        | 3.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 44        | 3.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 40        | 3.52%   |
| Intel HD Graphics 5500                                                                   | 33        | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 31        | 2.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 2.38%   |
| Intel UHD Graphics 620                                                                   | 26        | 2.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 24        | 2.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 24        | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 2.11%   |
| Intel HD Graphics 620                                                                    | 22        | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 19        | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.41%   |
| AMD Renoir                                                                               | 16        | 1.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 15        | 1.32%   |
| Intel HD Graphics 530                                                                    | 15        | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 1.14%   |
| AMD Lucienne                                                                             | 13        | 1.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 1.06%   |
| AMD Cezanne                                                                              | 12        | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 0.97%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.88%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 10        | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 0.7%    |
| Nvidia GF108M [GeForce GT 525M]                                                          | 8         | 0.7%    |
| Intel HD Graphics 630                                                                    | 8         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.62%   |
| Intel HD Graphics 500                                                                    | 7         | 0.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 0.62%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 6         | 0.53%   |
| Nvidia GM108M [GeForce 840M]                                                             | 6         | 0.53%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 6         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.44%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.44%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 5         | 0.44%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 5         | 0.44%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 5         | 0.44%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 0.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.35%   |
| Nvidia TU117M                                                                            | 4         | 0.35%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 0.35%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 4         | 0.35%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.35%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 0.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 4         | 0.35%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 4         | 0.35%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 4         | 0.35%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.35%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.35%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.35%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 4         | 0.35%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                                  | 4         | 0.35%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 4         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 497       | 54.14%  |
| 1 x AMD        | 173       | 18.85%  |
| Intel + Nvidia | 142       | 15.47%  |
| 1 x Nvidia     | 54        | 5.88%   |
| Intel + AMD    | 26        | 2.83%   |
| 2 x AMD        | 14        | 1.53%   |
| AMD + Nvidia   | 9         | 0.98%   |
| 1 x SiS        | 2         | 0.22%   |
| 2 x Nvidia     | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 908       | 98.91%  |
| Unknown     | 9         | 0.98%   |
| Proprietary | 1         | 0.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 527       | 57.41%  |
| 0.01-0.5   | 160       | 17.43%  |
| 1.01-2.0   | 91        | 9.91%   |
| 0.51-1.0   | 78        | 8.5%    |
| 3.01-4.0   | 41        | 4.47%   |
| 5.01-6.0   | 12        | 1.31%   |
| 7.01-8.0   | 4         | 0.44%   |
| 2.01-3.0   | 4         | 0.44%   |
| 8.01-16.0  | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 197       | 20.85%  |
| AU Optronics            | 192       | 20.32%  |
| Chimei Innolux          | 137       | 14.5%   |
| BOE                     | 113       | 11.96%  |
| Samsung Electronics     | 103       | 10.9%   |
| Chi Mei Optoelectronics | 37        | 3.92%   |
| Lenovo                  | 20        | 2.12%   |
| Apple                   | 14        | 1.48%   |
| LG Philips              | 12        | 1.27%   |
| InfoVision              | 12        | 1.27%   |
| Sharp                   | 9         | 0.95%   |
| Hewlett-Packard         | 9         | 0.95%   |
| Goldstar                | 9         | 0.95%   |
| PANDA                   | 8         | 0.85%   |
| Dell                    | 7         | 0.74%   |
| Toshiba                 | 5         | 0.53%   |
| Philips                 | 5         | 0.53%   |
| CSO                     | 5         | 0.53%   |
| AOC                     | 5         | 0.53%   |
| Sony                    | 4         | 0.42%   |
| Iiyama                  | 4         | 0.42%   |
| Acer                    | 4         | 0.42%   |
| Unknown                 | 3         | 0.32%   |
| CPT                     | 3         | 0.32%   |
| BenQ                    | 3         | 0.32%   |
| ___                     | 2         | 0.21%   |
| Vizio                   | 2         | 0.21%   |
| KDC                     | 2         | 0.21%   |
| Eizo                    | 2         | 0.21%   |
| ASUSTek Computer        | 2         | 0.21%   |
| Ancor Communications    | 2         | 0.21%   |
| Xiaomi                  | 1         | 0.11%   |
| Vestel Elektronik       | 1         | 0.11%   |
| Q@L                     | 1         | 0.11%   |
| Panasonic               | 1         | 0.11%   |
| NEC Computers           | 1         | 0.11%   |
| LP133WP1-TJAA           | 1         | 0.11%   |
| L                       | 1         | 0.11%   |
| KTC                     | 1         | 0.11%   |
| InnoLux Display         | 1         | 0.11%   |
| Hitachi                 | 1         | 0.11%   |
| HannStar                | 1         | 0.11%   |
| Grundig                 | 1         | 0.11%   |
| Gigabyte Technology     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 1.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 13        | 1.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.95%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 8         | 0.84%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 7         | 0.74%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.74%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 7         | 0.74%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 6         | 0.63%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 6         | 0.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 6         | 0.63%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 5         | 0.53%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch             | 5         | 0.53%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 5         | 0.53%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 5         | 0.53%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 5         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 5         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.53%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.53%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 5         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.53%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 5         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 4         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 4         | 0.42%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 4         | 0.42%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch              | 4         | 0.42%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 4         | 0.42%   |
| BOE LCD Monitor BOE06E4 1366x768 256x144mm 11.6-inch                     | 4         | 0.42%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.42%   |
| BOE LCD Monitor BOE05F3 1366x768 309x173mm 13.9-inch                     | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 4         | 0.42%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 3         | 0.32%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.32%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch             | 3         | 0.32%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch              | 3         | 0.32%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 3         | 0.32%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 3         | 0.32%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x185mm 12.1-inch                  | 3         | 0.32%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch              | 3         | 0.32%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 3         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 421       | 45.51%  |
| 1920x1080 (FHD)    | 297       | 32.11%  |
| 1600x900 (HD+)     | 68        | 7.35%   |
| 1280x800 (WXGA)    | 50        | 5.41%   |
| 1440x900 (WXGA+)   | 20        | 2.16%   |
| 3840x2160 (4K)     | 16        | 1.73%   |
| 2560x1440 (QHD)    | 10        | 1.08%   |
| 1920x1200 (WUXGA)  | 8         | 0.86%   |
| 1680x1050 (WSXGA+) | 6         | 0.65%   |
| 1280x1024 (SXGA)   | 5         | 0.54%   |
| 2560x1600          | 4         | 0.43%   |
| 3200x1800 (QHD+)   | 3         | 0.32%   |
| 2880x1800          | 3         | 0.32%   |
| 2160x1440          | 2         | 0.22%   |
| 1920x1280          | 2         | 0.22%   |
| 1360x768           | 2         | 0.22%   |
| 1024x768 (XGA)     | 2         | 0.22%   |
| 3456x2160          | 1         | 0.11%   |
| 2560x1080          | 1         | 0.11%   |
| 2288x1287          | 1         | 0.11%   |
| 2256x1504          | 1         | 0.11%   |
| 1680x945           | 1         | 0.11%   |
| 1024x600           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 439       | 46.41%  |
| 13      | 130       | 13.74%  |
| 17      | 108       | 11.42%  |
| 14      | 91        | 9.62%   |
| 12      | 46        | 4.86%   |
| 11      | 33        | 3.49%   |
| 27      | 15        | 1.59%   |
| 24      | 14        | 1.48%   |
| 23      | 13        | 1.37%   |
| 18      | 8         | 0.85%   |
| 21      | 7         | 0.74%   |
| 19      | 5         | 0.53%   |
| 16      | 5         | 0.53%   |
| 31      | 4         | 0.42%   |
| 10      | 4         | 0.42%   |
| 65      | 3         | 0.32%   |
| 32      | 3         | 0.32%   |
| 84      | 2         | 0.21%   |
| 72      | 2         | 0.21%   |
| 22      | 2         | 0.21%   |
| 142     | 1         | 0.11%   |
| 74      | 1         | 0.11%   |
| 54      | 1         | 0.11%   |
| 47      | 1         | 0.11%   |
| 40      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 36      | 1         | 0.11%   |
| 34      | 1         | 0.11%   |
| 28      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 20      | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 594       | 62.86%  |
| 201-300        | 142       | 15.03%  |
| 351-400        | 122       | 12.91%  |
| 501-600        | 39        | 4.13%   |
| 401-500        | 20        | 2.12%   |
| 601-700        | 9         | 0.95%   |
| 701-800        | 5         | 0.53%   |
| 1501-2000      | 5         | 0.53%   |
| 1001-1500      | 5         | 0.53%   |
| 801-900        | 2         | 0.21%   |
| More than 2000 | 1         | 0.11%   |
| Unknown        | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 787       | 87.74%  |
| 16/10 | 93        | 10.37%  |
| 3/2   | 7         | 0.78%   |
| 5/4   | 4         | 0.45%   |
| 4/3   | 4         | 0.45%   |
| 21/9  | 1         | 0.11%   |
| 1.00  | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 437       | 46.15%  |
| 81-90          | 169       | 17.85%  |
| 121-130        | 92        | 9.71%   |
| 71-80          | 53        | 5.6%    |
| 61-70          | 45        | 4.75%   |
| 51-60          | 33        | 3.48%   |
| 201-250        | 29        | 3.06%   |
| 301-350        | 16        | 1.69%   |
| 131-140        | 16        | 1.69%   |
| More than 1000 | 10        | 1.06%   |
| 351-500        | 9         | 0.95%   |
| 141-150        | 8         | 0.84%   |
| 251-300        | 7         | 0.74%   |
| 151-200        | 7         | 0.74%   |
| 111-120        | 5         | 0.53%   |
| 41-50          | 4         | 0.42%   |
| 501-1000       | 4         | 0.42%   |
| 91-100         | 2         | 0.21%   |
| Unknown        | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 403       | 42.92%  |
| 121-160       | 341       | 36.32%  |
| 51-100        | 138       | 14.7%   |
| 161-240       | 37        | 3.94%   |
| More than 240 | 11        | 1.17%   |
| 1-50          | 8         | 0.85%   |
| Unknown       | 1         | 0.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 841       | 91.61%  |
| 2     | 70        | 7.63%   |
| 3     | 4         | 0.44%   |
| 0     | 3         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 512       | 35.24%  |
| Intel                                 | 431       | 29.66%  |
| Qualcomm Atheros                      | 267       | 18.38%  |
| Broadcom                              | 90        | 6.19%   |
| Ralink                                | 25        | 1.72%   |
| Marvell Technology Group              | 21        | 1.45%   |
| Broadcom Limited                      | 14        | 0.96%   |
| MEDIATEK                              | 11        | 0.76%   |
| JMicron Technology                    | 11        | 0.76%   |
| Ericsson Business Mobile Networks     | 11        | 0.76%   |
| Huawei Technologies                   | 8         | 0.55%   |
| Sierra Wireless                       | 6         | 0.41%   |
| Hewlett-Packard                       | 6         | 0.41%   |
| Nvidia                                | 5         | 0.34%   |
| Dell                                  | 5         | 0.34%   |
| Ralink Technology                     | 4         | 0.28%   |
| Samsung Electronics                   | 3         | 0.21%   |
| ASIX Electronics                      | 3         | 0.21%   |
| TP-Link                               | 2         | 0.14%   |
| Silicon Integrated Systems [SiS]      | 2         | 0.14%   |
| Qualcomm Atheros Communications       | 2         | 0.14%   |
| Motorola PCS                          | 2         | 0.14%   |
| AVM                                   | 2         | 0.14%   |
| Xiaomi                                | 1         | 0.07%   |
| U-Blox                                | 1         | 0.07%   |
| Shenzhen Goodix Technology            | 1         | 0.07%   |
| OPPO Electronics                      | 1         | 0.07%   |
| NetGear                               | 1         | 0.07%   |
| Linksys                               | 1         | 0.07%   |
| Lenovo                                | 1         | 0.07%   |
| ASUSTek Computer                      | 1         | 0.07%   |
| AMD                                   | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 300       | 16.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 118       | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 48        | 2.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 44        | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 2.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 42        | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 36        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 35        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 1.81%   |
| Intel Wireless 7265                                                     | 29        | 1.64%   |
| Intel Wireless 8260                                                     | 26        | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 26        | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 25        | 1.41%   |
| Intel Wireless 7260                                                     | 23        | 1.3%    |
| Intel Wi-Fi 6 AX200                                                     | 23        | 1.3%    |
| Intel Wireless 3160                                                     | 22        | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 1.19%   |
| Intel Wireless 3165                                                     | 21        | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 20        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.02%   |
| Intel Wireless 8265 / 8275                                              | 17        | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 16        | 0.9%    |
| Intel Centrino Wireless-N 2230                                          | 16        | 0.9%    |
| Intel WiFi Link 5100                                                    | 14        | 0.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 0.73%   |
| Intel Ethernet Connection I219-LM                                       | 13        | 0.73%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 0.73%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 12        | 0.68%   |
| Intel Ethernet Connection I218-LM                                       | 12        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.68%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 0.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                | 10        | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 9         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 9         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 9         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 9         | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 9         | 0.51%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.51%   |
| Intel Ethernet Connection I217-LM                                       | 9         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                                   | 9         | 0.51%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.51%   |
| Intel 82579V Gigabit Network Connection                                 | 9         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                                | 9         | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 0.45%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 0.45%   |
| Intel 82566MM Gigabit Network Connection                                | 8         | 0.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 7         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 0.4%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 7         | 0.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 410       | 43.57%  |
| Qualcomm Atheros                      | 223       | 23.7%   |
| Realtek Semiconductor                 | 174       | 18.49%  |
| Broadcom                              | 66        | 7.01%   |
| Ralink                                | 25        | 2.66%   |
| MEDIATEK                              | 11        | 1.17%   |
| Broadcom Limited                      | 8         | 0.85%   |
| Sierra Wireless                       | 6         | 0.64%   |
| Ralink Technology                     | 4         | 0.43%   |
| Hewlett-Packard                       | 3         | 0.32%   |
| Dell                                  | 3         | 0.32%   |
| Qualcomm Atheros Communications       | 2         | 0.21%   |
| AVM                                   | 2         | 0.21%   |
| TP-Link                               | 1         | 0.11%   |
| Linksys                               | 1         | 0.11%   |
| ASUSTek Computer                      | 1         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 44        | 4.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 4.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 42        | 4.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 36        | 3.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 35        | 3.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 3.39%   |
| Intel Wireless 7265                                                     | 29        | 3.07%   |
| Intel Wireless 8260                                                     | 26        | 2.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 26        | 2.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 25        | 2.65%   |
| Intel Wireless 7260                                                     | 23        | 2.44%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 2.44%   |
| Intel Wireless 3160                                                     | 22        | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 2.22%   |
| Intel Wireless 3165                                                     | 21        | 2.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.91%   |
| Intel Wireless 8265 / 8275                                              | 17        | 1.8%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 16        | 1.69%   |
| Intel Centrino Wireless-N 2230                                          | 16        | 1.69%   |
| Intel WiFi Link 5100                                                    | 14        | 1.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 1.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 1.38%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 12        | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.27%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 9         | 0.95%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.95%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.95%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 8         | 0.85%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 0.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 7         | 0.74%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 7         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 0.74%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 6         | 0.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.53%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.53%   |
| Intel Ultimate N WiFi Link 5300                                         | 5         | 0.53%   |
| Broadcom BCM43225 802.11b/g/n                                           | 5         | 0.53%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 5         | 0.53%   |
| Intel Wireless-AC 9260                                                  | 4         | 0.42%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 4         | 0.42%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 0.42%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.42%   |
| Sierra Wireless MC8305 Modem                                            | 3         | 0.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 446       | 55.82%  |
| Intel                            | 170       | 21.28%  |
| Qualcomm Atheros                 | 80        | 10.01%  |
| Broadcom                         | 38        | 4.76%   |
| Marvell Technology Group         | 21        | 2.63%   |
| JMicron Technology               | 11        | 1.38%   |
| Broadcom Limited                 | 6         | 0.75%   |
| Nvidia                           | 5         | 0.63%   |
| Huawei Technologies              | 5         | 0.63%   |
| Samsung Electronics              | 3         | 0.38%   |
| Hewlett-Packard                  | 3         | 0.38%   |
| ASIX Electronics                 | 3         | 0.38%   |
| Silicon Integrated Systems [SiS] | 2         | 0.25%   |
| Xiaomi                           | 1         | 0.13%   |
| TP-Link                          | 1         | 0.13%   |
| OPPO Electronics                 | 1         | 0.13%   |
| NetGear                          | 1         | 0.13%   |
| Motorola PCS                     | 1         | 0.13%   |
| Lenovo                           | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 300       | 37.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 118       | 14.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 48        | 5.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 20        | 2.48%   |
| Intel Ethernet Connection I219-LM                                              | 13        | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 12        | 1.49%   |
| Intel Ethernet Connection I218-LM                                              | 12        | 1.49%   |
| Intel 82577LM Gigabit Network Connection                                       | 10        | 1.24%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 9         | 1.12%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 9         | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 9         | 1.12%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 9         | 1.12%   |
| Intel Ethernet Connection I217-LM                                              | 9         | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                                          | 9         | 1.12%   |
| Intel 82579V Gigabit Network Connection                                        | 9         | 1.12%   |
| Intel 82567LM Gigabit Network Connection                                       | 9         | 1.12%   |
| Intel 82566MM Gigabit Network Connection                                       | 8         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 6         | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 0.75%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 6         | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.62%   |
| Intel Ethernet Connection I219-V                                               | 5         | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 4         | 0.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 4         | 0.5%    |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.5%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 4         | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 4         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.37%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 3         | 0.37%   |
| Intel WiMAX Connection 2400m                                                   | 3         | 0.37%   |
| Intel 82577LC Gigabit Network Connection                                       | 3         | 0.37%   |
| HP HP lt4120 Snapdragon X5 LTE                                                 | 3         | 0.37%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.37%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 2         | 0.25%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.25%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 2         | 0.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.25%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 2         | 0.25%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 2         | 0.25%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.25%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.25%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.25%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.25%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.25%   |
| Huawei JNY-LX1                                                                 | 2         | 0.25%   |
| Huawei E353/E3131                                                              | 2         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 909       | 53.13%  |
| Ethernet | 782       | 45.7%   |
| Modem    | 18        | 1.05%   |
| Unknown  | 2         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 655       | 71.35%  |
| Ethernet | 263       | 28.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 744       | 81.05%  |
| 1     | 167       | 18.19%  |
| 0     | 5         | 0.54%   |
| 3     | 2         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 651       | 70.92%  |
| Yes  | 267       | 29.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 273       | 39.51%  |
| Realtek Semiconductor           | 76        | 11%     |
| Qualcomm Atheros Communications | 68        | 9.84%   |
| Broadcom                        | 53        | 7.67%   |
| Lite-On Technology              | 41        | 5.93%   |
| IMC Networks                    | 35        | 5.07%   |
| Foxconn / Hon Hai               | 31        | 4.49%   |
| Dell                            | 20        | 2.89%   |
| Toshiba                         | 19        | 2.75%   |
| Apple                           | 15        | 2.17%   |
| Ralink                          | 12        | 1.74%   |
| Cambridge Silicon Radio         | 11        | 1.59%   |
| Hewlett-Packard                 | 9         | 1.3%    |
| Realtek                         | 5         | 0.72%   |
| Alps Electric                   | 5         | 0.72%   |
| ASUSTek Computer                | 4         | 0.58%   |
| Ralink Technology               | 3         | 0.43%   |
| Fujitsu                         | 2         | 0.29%   |
| Foxconn International           | 2         | 0.29%   |
| Chicony Electronics             | 2         | 0.29%   |
| Unknown                         | 1         | 0.14%   |
| Taiyo Yuden                     | 1         | 0.14%   |
| Edimax Technology               | 1         | 0.14%   |
| D-Link System                   | 1         | 0.14%   |
| Askey Computer                  | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 142       | 20.55%  |
| Realtek Bluetooth Radio                                                             | 40        | 5.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 32        | 4.63%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 29        | 4.2%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 28        | 4.05%   |
| Intel Bluetooth Device                                                              | 26        | 3.76%   |
| Lite-On Bluetooth Device                                                            | 25        | 3.62%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 25        | 3.62%   |
| Intel AX200 Bluetooth                                                               | 23        | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 15        | 2.17%   |
| IMC Networks Bluetooth Radio                                                        | 15        | 2.17%   |
| IMC Networks Bluetooth Device                                                       | 15        | 2.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 15        | 2.17%   |
| Ralink RT3290 Bluetooth                                                             | 12        | 1.74%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 12        | 1.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 11        | 1.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 1.59%   |
| Dell DW375 Bluetooth Module                                                         | 10        | 1.45%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 9         | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 1.01%   |
| Toshiba RT Bluetooth Radio                                                          | 6         | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.87%   |
| Realtek Bluetooth Radio                                                             | 5         | 0.72%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.72%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 5         | 0.72%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 5         | 0.72%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.72%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 0.72%   |
| Apple Bluetooth Host Controller                                                     | 5         | 0.72%   |
| Lite-On Wireless_Device                                                             | 4         | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.58%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 4         | 0.58%   |
| Broadcom BCM2045 Bluetooth                                                          | 4         | 0.58%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 0.58%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.43%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.43%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.43%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 0.43%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 3         | 0.43%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.29%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.29%   |
| Toshiba Bluetooth Radio                                                             | 2         | 0.29%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 2         | 0.29%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.29%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.29%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.29%   |
| Fujitsu Bluetooth Device                                                            | 2         | 0.29%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.29%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.29%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.29%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.29%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.29%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.29%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 736       | 68.91%  |
| AMD                              | 198       | 18.54%  |
| Nvidia                           | 114       | 10.67%  |
| Logitech                         | 4         | 0.37%   |
| Realtek Semiconductor            | 3         | 0.28%   |
| Silicon Integrated Systems [SiS] | 2         | 0.19%   |
| Lenovo                           | 2         | 0.19%   |
| Conexant Systems                 | 2         | 0.19%   |
| XMOS                             | 1         | 0.09%   |
| Samson Technologies              | 1         | 0.09%   |
| Native Instruments               | 1         | 0.09%   |
| M-Audio                          | 1         | 0.09%   |
| JMTek                            | 1         | 0.09%   |
| Generalplus Technology           | 1         | 0.09%   |
| Focusrite-Novation               | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 113       | 8.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 95        | 7.22%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 72        | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 67        | 5.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 62        | 4.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 61        | 4.64%   |
| AMD FCH Azalia Controller                                                                         | 47        | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 38        | 2.89%   |
| Intel Broadwell-U Audio Controller                                                                | 38        | 2.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 37        | 2.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 33        | 2.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 2.36%   |
| Intel 8 Series HD Audio Controller                                                                | 31        | 2.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 30        | 2.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 29        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 2.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 1.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24        | 1.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 23        | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 23        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 20        | 1.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 19        | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 1.44%   |
| AMD Wrestler HDMI Audio                                                                           | 19        | 1.44%   |
| AMD High Definition Audio Controller                                                              | 19        | 1.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 1.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 0.84%   |
| AMD Trinity HDMI Audio Controller                                                                 | 11        | 0.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.68%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 0.68%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 9         | 0.68%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 8         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 8         | 0.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.53%   |
| Nvidia Audio device                                                                               | 6         | 0.46%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.38%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.38%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.38%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.38%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.3%    |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.3%    |
| Intel Jasper Lake HD Audio                                                                        | 4         | 0.3%    |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 4         | 0.3%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 4         | 0.3%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 4         | 0.3%    |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.23%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.23%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.23%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 3         | 0.23%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.23%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 300       | 27.1%   |
| SK Hynix                                         | 238       | 21.5%   |
| Micron Technology                                | 121       | 10.93%  |
| Kingston                                         | 95        | 8.58%   |
| Unknown                                          | 91        | 8.22%   |
| Crucial                                          | 43        | 3.88%   |
| Ramaxel Technology                               | 32        | 2.89%   |
| A-DATA Technology                                | 27        | 2.44%   |
| Elpida                                           | 26        | 2.35%   |
| Nanya Technology                                 | 16        | 1.45%   |
| Corsair                                          | 16        | 1.45%   |
| Smart                                            | 11        | 0.99%   |
| Unknown (ABCD)                                   | 10        | 0.9%    |
| SMART Brazil                                     | 6         | 0.54%   |
| Unknown                                          | 6         | 0.54%   |
| G.Skill                                          | 5         | 0.45%   |
| Teikon                                           | 4         | 0.36%   |
| Team                                             | 4         | 0.36%   |
| Qimonda                                          | 4         | 0.36%   |
| Patriot                                          | 4         | 0.36%   |
| ASint Technology                                 | 4         | 0.36%   |
| Toshiba                                          | 3         | 0.27%   |
| GOODRAM                                          | 3         | 0.27%   |
| Netlist                                          | 2         | 0.18%   |
| Multilaser                                       | 2         | 0.18%   |
| High Bridge                                      | 2         | 0.18%   |
| Goldkey                                          | 2         | 0.18%   |
| CSX                                              | 2         | 0.18%   |
| Avant                                            | 2         | 0.18%   |
| Apacer                                           | 2         | 0.18%   |
| AMD                                              | 2         | 0.18%   |
| Unknown (0x89AD)                                 | 1         | 0.09%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.09%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.09%   |
| Unknown (0B45)                                   | 1         | 0.09%   |
| Unknown (09C7)                                   | 1         | 0.09%   |
| Unknown (08AE)                                   | 1         | 0.09%   |
| Unknown (081A)                                   | 1         | 0.09%   |
| Unigen                                           | 1         | 0.09%   |
| Unifosa                                          | 1         | 0.09%   |
| TIMETEC                                          | 1         | 0.09%   |
| Silicon Power                                    | 1         | 0.09%   |
| Sesame                                           | 1         | 0.09%   |
| PNY                                              | 1         | 0.09%   |
| OCZ                                              | 1         | 0.09%   |
| Novatech                                         | 1         | 0.09%   |
| Lexar                                            | 1         | 0.09%   |
| Kllisre                                          | 1         | 0.09%   |
| Kembona                                          | 1         | 0.09%   |
| HT Micron                                        | 1         | 0.09%   |
| Carry                                            | 1         | 0.09%   |
| AXIOM                                            | 1         | 0.09%   |
| 48spaces                                         | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 25        | 2.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 1.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 19        | 1.6%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 1.6%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 19        | 1.6%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 17        | 1.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 1.43%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 16        | 1.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 1.26%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 13        | 1.1%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 10        | 0.84%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 10        | 0.84%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 9         | 0.76%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.76%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 8         | 0.67%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.67%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 8         | 0.67%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 7         | 0.59%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 7         | 0.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 7         | 0.59%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 7         | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 7         | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 7         | 0.59%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 7         | 0.59%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 7         | 0.59%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 6         | 0.51%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.51%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 0.51%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 6         | 0.51%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.51%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 6         | 0.51%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 6         | 0.51%   |
| Unknown                                                          | 6         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 5         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 5         | 0.42%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 5         | 0.42%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 5         | 0.42%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.42%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.42%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 5         | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 5         | 0.42%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 5         | 0.42%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s       | 5         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.42%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.42%   |
| Kingston RAM HP16D3LS1KBGH/4G 4GB SODIMM DDR3 1600MT/s           | 5         | 0.42%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 5         | 0.42%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 0.34%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 0.34%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 4         | 0.34%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 465       | 50.82%  |
| DDR4    | 286       | 31.26%  |
| DDR2    | 80        | 8.74%   |
| SDRAM   | 29        | 3.17%   |
| LPDDR4  | 27        | 2.95%   |
| LPDDR3  | 13        | 1.42%   |
| Unknown | 9         | 0.98%   |
| DRAM    | 3         | 0.33%   |
| DDR     | 3         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 867       | 94.96%  |
| Row Of Chips | 37        | 4.05%   |
| Chip         | 5         | 0.55%   |
| DIMM         | 2         | 0.22%   |
| Unknown      | 2         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 449       | 44.41%  |
| 8192  | 274       | 27.1%   |
| 2048  | 198       | 19.58%  |
| 1024  | 42        | 4.15%   |
| 16384 | 40        | 3.96%   |
| 32768 | 8         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 319       | 31.65%  |
| 2667    | 148       | 14.68%  |
| 1334    | 84        | 8.33%   |
| 2400    | 76        | 7.54%   |
| 3200    | 71        | 7.04%   |
| 1333    | 60        | 5.95%   |
| 667     | 40        | 3.97%   |
| 1067    | 30        | 2.98%   |
| 800     | 28        | 2.78%   |
| 2133    | 27        | 2.68%   |
| Unknown | 25        | 2.48%   |
| 2048    | 15        | 1.49%   |
| 3266    | 13        | 1.29%   |
| 4199    | 11        | 1.09%   |
| 1867    | 9         | 0.89%   |
| 1066    | 9         | 0.89%   |
| 1866    | 8         | 0.79%   |
| 975     | 8         | 0.79%   |
| 4267    | 7         | 0.69%   |
| 533     | 6         | 0.6%    |
| 4266    | 5         | 0.5%    |
| 2933    | 3         | 0.3%    |
| 1639    | 2         | 0.2%    |
| 8400    | 1         | 0.1%    |
| 2666    | 1         | 0.1%    |
| 2267    | 1         | 0.1%    |
| 666     | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 3         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| HP OfficeJet 4300  | 1         | 16.67%  |
| HP LaserJet 1018   | 1         | 16.67%  |
| HP DeskJet D1360   | 1         | 16.67%  |
| Canon PIXMA MP280  | 1         | 16.67%  |
| Canon MP160        | 1         | 16.67%  |
| Canon G3000 series | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 231       | 29.06%  |
| Realtek Semiconductor                  | 72        | 9.06%   |
| Microdia                               | 71        | 8.93%   |
| IMC Networks                           | 61        | 7.67%   |
| Acer                                   | 60        | 7.55%   |
| Suyin                                  | 37        | 4.65%   |
| Sunplus Innovation Technology          | 37        | 4.65%   |
| Quanta                                 | 36        | 4.53%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 4.03%   |
| Syntek                                 | 26        | 3.27%   |
| Lite-On Technology                     | 22        | 2.77%   |
| Silicon Motion                         | 18        | 2.26%   |
| Ricoh                                  | 14        | 1.76%   |
| Apple                                  | 12        | 1.51%   |
| Importek                               | 10        | 1.26%   |
| Alcor Micro                            | 10        | 1.26%   |
| ALi                                    | 7         | 0.88%   |
| Luxvisions Innotech Limited            | 6         | 0.75%   |
| Z-Star Microelectronics                | 5         | 0.63%   |
| Lenovo                                 | 5         | 0.63%   |
| Sonix Technology                       | 3         | 0.38%   |
| Primax Electronics                     | 3         | 0.38%   |
| DigiTech                               | 3         | 0.38%   |
| Nebraska Furniture Mart                | 2         | 0.25%   |
| Logitech                               | 2         | 0.25%   |
| WaveRider Communications               | 1         | 0.13%   |
| Unknown                                | 1         | 0.13%   |
| Tobii Technology AB                    | 1         | 0.13%   |
| SunplusIT                              | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |
| OmniVision Technologies                | 1         | 0.13%   |
| Novatek Microelectronics               | 1         | 0.13%   |
| LG Electronics                         | 1         | 0.13%   |
| GEMBIRD                                | 1         | 0.13%   |
| Cubeternet                             | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                               | 32        | 4.02%   |
| Chicony Integrated Camera                                       | 27        | 3.39%   |
| Microdia Integrated_Webcam_HD                                   | 18        | 2.26%   |
| Microdia Integrated Webcam                                      | 13        | 1.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 13        | 1.63%   |
| IMC Networks Integrated Camera                                  | 13        | 1.63%   |
| Acer Integrated Camera                                          | 13        | 1.63%   |
| Realtek USB Camera                                              | 12        | 1.51%   |
| Realtek Integrated_Webcam_HD                                    | 12        | 1.51%   |
| Chicony FJ Camera                                               | 12        | 1.51%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 11        | 1.38%   |
| Chicony TOSHIBA Web Camera - HD                                 | 11        | 1.38%   |
| Syntek Integrated Camera                                        | 10        | 1.25%   |
| Sunplus Integrated_Webcam_HD                                    | 10        | 1.25%   |
| Realtek USB2.0 HD UVC WebCam                                    | 10        | 1.25%   |
| Chicony VGA WebCam                                              | 10        | 1.25%   |
| Chicony USB 2.0 Camera                                          | 10        | 1.25%   |
| Acer Lenovo EasyCamera                                          | 10        | 1.25%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 9         | 1.13%   |
| Lite-On Integrated Camera                                       | 9         | 1.13%   |
| Chicony Lenovo EasyCamera                                       | 9         | 1.13%   |
| Realtek Lenovo EasyCamera                                       | 8         | 1%      |
| Quanta HD User Facing                                           | 8         | 1%      |
| Chicony USB2.0 VGA UVC WebCam                                   | 8         | 1%      |
| Chicony HP Truevision HD camera                                 | 8         | 1%      |
| Quanta HD WebCam                                                | 7         | 0.88%   |
| Microdia USB 2.0 Camera                                         | 7         | 0.88%   |
| Chicony HD User Facing                                          | 7         | 0.88%   |
| Chicony EasyCamera                                              | 7         | 0.88%   |
| Syntek Lenovo EasyCamera                                        | 6         | 0.75%   |
| Suyin HP Truevision HD                                          | 6         | 0.75%   |
| Sunplus HD WebCam                                               | 6         | 0.75%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 6         | 0.75%   |
| Quanta HP TrueVision HD Camera                                  | 6         | 0.75%   |
| Microdia HP Webcam                                              | 6         | 0.75%   |
| Lite-On HP HD Webcam                                            | 6         | 0.75%   |
| Chicony USB2.0 HD UVC WebCam                                    | 6         | 0.75%   |
| Chicony HP Truevision HD                                        | 6         | 0.75%   |
| Acer Lenovo Integrated Webcam                                   | 6         | 0.75%   |
| Syntek EasyCamera                                               | 5         | 0.63%   |
| Realtek HP Webcam                                               | 5         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 5         | 0.63%   |
| Microdia Dell Integrated HD Webcam                              | 5         | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 5         | 0.63%   |
| Importek TOSHIBA Web Camera - HD                                | 5         | 0.63%   |
| Chicony CNF9055 Toshiba Webcam                                  | 5         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 5         | 0.63%   |
| Apple Built-in iSight                                           | 5         | 0.63%   |
| ALi Gateway Webcam                                              | 5         | 0.63%   |
| Acer BisonCam, NB Pro                                           | 5         | 0.63%   |
| Suyin 1.3M HD WebCam                                            | 4         | 0.5%    |
| Sunplus Laptop_Integrated_Webcam_HD                             | 4         | 0.5%    |
| Sunplus Asus Webcam                                             | 4         | 0.5%    |
| Quanta VGA WebCam                                               | 4         | 0.5%    |
| Quanta HP Webcam                                                | 4         | 0.5%    |
| Lite-On HP Wide Vision HD Camera                                | 4         | 0.5%    |
| IMC Networks ov9734_azurewave_camera                            | 4         | 0.5%    |
| Chicony USB2.0 UVC WebCam                                       | 4         | 0.5%    |
| Chicony HP Webcam                                               | 4         | 0.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 31.71%  |
| AuthenTec                  | 13        | 15.85%  |
| Elan Microelectronics      | 10        | 12.2%   |
| Synaptics                  | 8         | 9.76%   |
| Shenzhen Goodix Technology | 8         | 9.76%   |
| LighTuning Technology      | 6         | 7.32%   |
| Upek                       | 5         | 6.1%    |
| STMicroelectronics         | 4         | 4.88%   |
| Samsung Electronics        | 1         | 1.22%   |
| HOLTEK                     | 1         | 1.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 8         | 9.76%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 7.32%   |
| Elan ELAN:Fingerprint                                      | 6         | 7.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 6.1%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 4         | 4.88%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 4         | 4.88%   |
| STMicroelectronics Fingerprint Reader                      | 4         | 4.88%   |
| Elan ELAN:ARM-M4                                           | 4         | 4.88%   |
| AuthenTec AES1600                                          | 4         | 4.88%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 3         | 3.66%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 3         | 3.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 3         | 3.66%   |
| AuthenTec AES2810                                          | 3         | 3.66%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 3         | 3.66%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 2.44%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 2.44%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 2.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 2.44%   |
| AuthenTec Fingerprint Sensor                               | 2         | 2.44%   |
| Validity Sensors VFS491                                    | 1         | 1.22%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 1.22%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.22%   |
| Synaptics WBDI Device                                      | 1         | 1.22%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 1.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 1.22%   |
| Samsung Fingerprint Sensor Device - 730B                   | 1         | 1.22%   |
| LighTuning Fingerprint Reader                              | 1         | 1.22%   |
| HOLTEK FocalTech Fingerprint Device                        | 1         | 1.22%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 1.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 35        | 53.03%  |
| O2 Micro         | 10        | 15.15%  |
| Alcor Micro      | 9         | 13.64%  |
| Upek             | 6         | 9.09%   |
| Lenovo           | 4         | 6.06%   |
| SCM Microsystems | 2         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 22.73%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 15.15%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 13.64%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 13.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 9.09%   |
| Broadcom 5880                                                                | 6         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.06%   |
| Broadcom 58200                                                               | 4         | 6.06%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 3.03%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 711       | 77.45%  |
| 1     | 174       | 18.95%  |
| 2     | 28        | 3.05%   |
| 3     | 5         | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 82        | 33.88%  |
| Chipcard                 | 65        | 26.86%  |
| Graphics card            | 24        | 9.92%   |
| Bluetooth                | 24        | 9.92%   |
| Net/wireless             | 16        | 6.61%   |
| Storage                  | 13        | 5.37%   |
| Multimedia controller    | 7         | 2.89%   |
| Camera                   | 7         | 2.89%   |
| Network                  | 2         | 0.83%   |
| Sound                    | 1         | 0.41%   |
| Communication controller | 1         | 0.41%   |

