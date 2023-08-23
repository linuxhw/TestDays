OpenMandriva 4.3 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_4.3/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_4.3/Notebook/README.md).

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

Total: 4685

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | Rampage IV GENE             | Desktop     | [2a494a04b5](https://linux-hardware.org/?probe=2a494a04b5) | Aug 12, 2023 |
| Acer          | Aspire ES1-431              | Notebook    | [171fd219cc](https://linux-hardware.org/?probe=171fd219cc) | Aug 10, 2023 |
| HP            | 18E7                        | Desktop     | [ff27f888f0](https://linux-hardware.org/?probe=ff27f888f0) | Aug 10, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [13d99d66da](https://linux-hardware.org/?probe=13d99d66da) | Aug 09, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [b280ab65dd](https://linux-hardware.org/?probe=b280ab65dd) | Aug 09, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [e5091194fb](https://linux-hardware.org/?probe=e5091194fb) | Aug 08, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [f5df04e0e6](https://linux-hardware.org/?probe=f5df04e0e6) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c94a18b924](https://linux-hardware.org/?probe=c94a18b924) | Aug 02, 2023 |
| Toshiba       | Satellite C850-B239         | Notebook    | [a075f60c70](https://linux-hardware.org/?probe=a075f60c70) | Aug 02, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| HP            | 18E7                        | Desktop     | [339050cd65](https://linux-hardware.org/?probe=339050cd65) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3a500cdb55](https://linux-hardware.org/?probe=3a500cdb55) | Aug 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b57f8ee5f8](https://linux-hardware.org/?probe=b57f8ee5f8) | Aug 01, 2023 |
| Dell          | 0C27VV A03                  | Desktop     | [75ff82774b](https://linux-hardware.org/?probe=75ff82774b) | Jul 31, 2023 |
| HP            | 84EE 1100                   | All in one  | [52d1413f34](https://linux-hardware.org/?probe=52d1413f34) | Jul 29, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [ee17cd82e7](https://linux-hardware.org/?probe=ee17cd82e7) | Jul 27, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| Toshiba       | Satellite C50D-A-11G        | Notebook    | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [1d4e6c23cf](https://linux-hardware.org/?probe=1d4e6c23cf) | Jul 27, 2023 |
| HP            | 212B                        | Desktop     | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| Intel         | powered classmate PC        | Notebook    | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| Dell          | 0VD92X A00                  | Desktop     | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| Intel         | JSL MRD                     | Desktop     | [4c9c765884](https://linux-hardware.org/?probe=4c9c765884) | Jul 21, 2023 |
| Dell          | 0M863N A01                  | Desktop     | [682fc212b6](https://linux-hardware.org/?probe=682fc212b6) | Jul 20, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [61fa9a2c91](https://linux-hardware.org/?probe=61fa9a2c91) | Jul 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [140474e198](https://linux-hardware.org/?probe=140474e198) | Jul 19, 2023 |
| Intel X79     | Unknown                     | Desktop     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [9853a8cf46](https://linux-hardware.org/?probe=9853a8cf46) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [afb16ac821](https://linux-hardware.org/?probe=afb16ac821) | Jul 17, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [3cc36162b8](https://linux-hardware.org/?probe=3cc36162b8) | Jul 16, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [87763ca861](https://linux-hardware.org/?probe=87763ca861) | Jul 16, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [46cfd28279](https://linux-hardware.org/?probe=46cfd28279) | Jul 16, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [e302c823fc](https://linux-hardware.org/?probe=e302c823fc) | Jul 13, 2023 |
| HP            | 18E8                        | Desktop     | [b892f0dd28](https://linux-hardware.org/?probe=b892f0dd28) | Jul 12, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7a8f3c985f](https://linux-hardware.org/?probe=7a8f3c985f) | Jul 11, 2023 |
| ASUSTek       | X756UXK                     | Notebook    | [746e141543](https://linux-hardware.org/?probe=746e141543) | Jul 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [144cb029ba](https://linux-hardware.org/?probe=144cb029ba) | Jul 08, 2023 |
| Dell          | 01TKCC A01                  | Desktop     | [b3ab41fd8f](https://linux-hardware.org/?probe=b3ab41fd8f) | Jul 08, 2023 |
| Dell          | 04P1GP A01                  | All in one  | [3a9a768d92](https://linux-hardware.org/?probe=3a9a768d92) | Jul 08, 2023 |
| Lenovo        | G485 20136                  | Notebook    | [9ce1d97d02](https://linux-hardware.org/?probe=9ce1d97d02) | Jul 07, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [c9ccceb765](https://linux-hardware.org/?probe=c9ccceb765) | Jul 07, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [2cb98a7961](https://linux-hardware.org/?probe=2cb98a7961) | Jul 06, 2023 |
| ASUSTek       | TP501UA                     | Notebook    | [ee28aacdd1](https://linux-hardware.org/?probe=ee28aacdd1) | Jul 05, 2023 |
| ASUSTek       | 1015PN                      | Notebook    | [7482ea5fc2](https://linux-hardware.org/?probe=7482ea5fc2) | Jul 03, 2023 |
| ECS           | H55H-M2                     | Desktop     | [344ce5bb17](https://linux-hardware.org/?probe=344ce5bb17) | Jul 03, 2023 |
| ASUSTek       | UN45                        | Desktop     | [487845dd55](https://linux-hardware.org/?probe=487845dd55) | Jul 03, 2023 |
| Gigabyte      | 965P-S3                     | Desktop     | [7aa7550205](https://linux-hardware.org/?probe=7aa7550205) | Jul 02, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [7beeaf657d](https://linux-hardware.org/?probe=7beeaf657d) | Jul 02, 2023 |
| Acer          | Aspire E5-772               | Notebook    | [b33f11c7c9](https://linux-hardware.org/?probe=b33f11c7c9) | Jul 01, 2023 |
| ASUSTek       | N752VX                      | Notebook    | [d4fd40a9f3](https://linux-hardware.org/?probe=d4fd40a9f3) | Jul 01, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [b6be2d7f9f](https://linux-hardware.org/?probe=b6be2d7f9f) | Jun 30, 2023 |
| HP            | Notebook                    | Notebook    | [a178cbf707](https://linux-hardware.org/?probe=a178cbf707) | Jun 29, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [326f873ac3](https://linux-hardware.org/?probe=326f873ac3) | Jun 29, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d2a1351f86](https://linux-hardware.org/?probe=d2a1351f86) | Jun 28, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [2faeb24e37](https://linux-hardware.org/?probe=2faeb24e37) | Jun 27, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [90067b8232](https://linux-hardware.org/?probe=90067b8232) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [a31908b24b](https://linux-hardware.org/?probe=a31908b24b) | Jun 25, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [4269ca2c0b](https://linux-hardware.org/?probe=4269ca2c0b) | Jun 25, 2023 |
| HP            | 8055                        | Desktop     | [7fac5a1354](https://linux-hardware.org/?probe=7fac5a1354) | Jun 24, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [cdc135487b](https://linux-hardware.org/?probe=cdc135487b) | Jun 24, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9408842ffc](https://linux-hardware.org/?probe=9408842ffc) | Jun 24, 2023 |
| MSI           | MS-7360                     | Desktop     | [9a0d46b069](https://linux-hardware.org/?probe=9a0d46b069) | Jun 23, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [9d234065ed](https://linux-hardware.org/?probe=9d234065ed) | Jun 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [4e877b9c8d](https://linux-hardware.org/?probe=4e877b9c8d) | Jun 22, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [fc54744449](https://linux-hardware.org/?probe=fc54744449) | Jun 22, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [09f4615df6](https://linux-hardware.org/?probe=09f4615df6) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4560c6d34d](https://linux-hardware.org/?probe=4560c6d34d) | Jun 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [35de204113](https://linux-hardware.org/?probe=35de204113) | Jun 19, 2023 |
| MSI           | 2AE0                        | Desktop     | [fdfc88e5da](https://linux-hardware.org/?probe=fdfc88e5da) | Jun 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [651988e989](https://linux-hardware.org/?probe=651988e989) | Jun 18, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3c45e54fd2](https://linux-hardware.org/?probe=3c45e54fd2) | Jun 17, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [adc38f998a](https://linux-hardware.org/?probe=adc38f998a) | Jun 17, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [a587493314](https://linux-hardware.org/?probe=a587493314) | Jun 16, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [8571bdf994](https://linux-hardware.org/?probe=8571bdf994) | Jun 15, 2023 |
| Acer          | Veriton M6630G V:1.0        | Desktop     | [d58cd3aa7d](https://linux-hardware.org/?probe=d58cd3aa7d) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [922c598503](https://linux-hardware.org/?probe=922c598503) | Jun 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | Desktop     | [26e6a1f816](https://linux-hardware.org/?probe=26e6a1f816) | Jun 13, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | Desktop     | [5c2eef3678](https://linux-hardware.org/?probe=5c2eef3678) | Jun 12, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b5b264d1e8](https://linux-hardware.org/?probe=b5b264d1e8) | Jun 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d592b19e9b](https://linux-hardware.org/?probe=d592b19e9b) | Jun 10, 2023 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [eea1c44d94](https://linux-hardware.org/?probe=eea1c44d94) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| Toshiba       | Satellite L635              | Notebook    | [4f124d1525](https://linux-hardware.org/?probe=4f124d1525) | Jun 09, 2023 |
| Biostar       | H610MH                      | Desktop     | [2cd4e157d4](https://linux-hardware.org/?probe=2cd4e157d4) | Jun 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [44cf28ec0e](https://linux-hardware.org/?probe=44cf28ec0e) | Jun 05, 2023 |
| HP            | Pavilion g4                 | Notebook    | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Dell          | Latitude E4300              | Notebook    | [cfd95b7e5e](https://linux-hardware.org/?probe=cfd95b7e5e) | Jun 05, 2023 |
| HP            | 1850                        | Desktop     | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [0564fd483d](https://linux-hardware.org/?probe=0564fd483d) | Jun 04, 2023 |
| HP            | 1495                        | Desktop     | [0cbf6bee1f](https://linux-hardware.org/?probe=0cbf6bee1f) | Jun 04, 2023 |
| MSI           | Boston                      | Desktop     | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1b82c0c3c8](https://linux-hardware.org/?probe=1b82c0c3c8) | Jun 02, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [7b5291c6f8](https://linux-hardware.org/?probe=7b5291c6f8) | Jun 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [e58b7bfc92](https://linux-hardware.org/?probe=e58b7bfc92) | May 29, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [bf3b702d7a](https://linux-hardware.org/?probe=bf3b702d7a) | May 28, 2023 |
| HP            | Pavilion dm4                | Notebook    | [51b921c72d](https://linux-hardware.org/?probe=51b921c72d) | May 28, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [31c6913c14](https://linux-hardware.org/?probe=31c6913c14) | May 26, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6f1a19d503](https://linux-hardware.org/?probe=6f1a19d503) | May 25, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [149a19eeeb](https://linux-hardware.org/?probe=149a19eeeb) | May 24, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f0b7bf3520](https://linux-hardware.org/?probe=f0b7bf3520) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | Notebook    | [5c190a4d57](https://linux-hardware.org/?probe=5c190a4d57) | May 22, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [c1df991f26](https://linux-hardware.org/?probe=c1df991f26) | May 19, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| HP            | 0A54h                       | Desktop     | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| UMAX          | VisionBook 13Wg Flex        | Convertible | [170db25383](https://linux-hardware.org/?probe=170db25383) | May 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [f50517b1c5](https://linux-hardware.org/?probe=f50517b1c5) | May 17, 2023 |
| HP            | 18E5                        | Desktop     | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | Notebook    | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [8859685e86](https://linux-hardware.org/?probe=8859685e86) | May 13, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [60defd2bfe](https://linux-hardware.org/?probe=60defd2bfe) | May 12, 2023 |
| Acer          | RS880M05                    | Desktop     | [5952c105f6](https://linux-hardware.org/?probe=5952c105f6) | May 12, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [68afb54270](https://linux-hardware.org/?probe=68afb54270) | May 10, 2023 |
| HP            | 83EB                        | All in one  | [0abdbdd77b](https://linux-hardware.org/?probe=0abdbdd77b) | May 10, 2023 |
| ASUSTek       | M4A78L-M                    | Desktop     | [1a843c3a7f](https://linux-hardware.org/?probe=1a843c3a7f) | May 10, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [6fe358200a](https://linux-hardware.org/?probe=6fe358200a) | May 09, 2023 |
| HP            | ProBook 440 G1              | Notebook    | [aea73943e8](https://linux-hardware.org/?probe=aea73943e8) | May 09, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [a0073c6ff3](https://linux-hardware.org/?probe=a0073c6ff3) | May 08, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [eeb083abcd](https://linux-hardware.org/?probe=eeb083abcd) | May 07, 2023 |
| Shuttle       | FZ77                        | Desktop     | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [6c404ee491](https://linux-hardware.org/?probe=6c404ee491) | May 06, 2023 |
| Quanta        | JW2                         | Notebook    | [eb9ff2a263](https://linux-hardware.org/?probe=eb9ff2a263) | May 06, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d8f78a98f2](https://linux-hardware.org/?probe=d8f78a98f2) | May 05, 2023 |
| eMachines     | eMG620                      | Notebook    | [224dc7209e](https://linux-hardware.org/?probe=224dc7209e) | May 04, 2023 |
| MSI           | 760GM-P34                   | Desktop     | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [20d436bfa7](https://linux-hardware.org/?probe=20d436bfa7) | May 02, 2023 |
| MSI           | MS-7025                     | Desktop     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| MAXSUN        | MS-A86FX FS M.3             | Desktop     | [3ce20d3b05](https://linux-hardware.org/?probe=3ce20d3b05) | May 01, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| Sony          | VGN-AW11M_H                 | Notebook    | [2c9f98ca31](https://linux-hardware.org/?probe=2c9f98ca31) | May 01, 2023 |
| DIEBOLD       | NM70-I                      | Desktop     | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [33a55a2347](https://linux-hardware.org/?probe=33a55a2347) | Apr 29, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| AZW           | MINI S 10                   | Desktop     | [12ba32f977](https://linux-hardware.org/?probe=12ba32f977) | Apr 28, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [a84de33c38](https://linux-hardware.org/?probe=a84de33c38) | Apr 28, 2023 |
| Dell          | Latitude D830               | Notebook    | [2ab0772efb](https://linux-hardware.org/?probe=2ab0772efb) | Apr 28, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [a63003783d](https://linux-hardware.org/?probe=a63003783d) | Apr 27, 2023 |
| Dell          | 0XKD8M A00                  | All in one  | [1629350aa9](https://linux-hardware.org/?probe=1629350aa9) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [f549cb502c](https://linux-hardware.org/?probe=f549cb502c) | Apr 27, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | Notebook    | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| Fujitsu       | FMVA05004                   | Notebook    | [c494a8453d](https://linux-hardware.org/?probe=c494a8453d) | Apr 26, 2023 |
| Toshiba       | dynabook TV/68KBL           | Notebook    | [19c59e3701](https://linux-hardware.org/?probe=19c59e3701) | Apr 26, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5c79032176](https://linux-hardware.org/?probe=5c79032176) | Apr 25, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| HP            | Pavilion g4                 | Notebook    | [5e2040a91f](https://linux-hardware.org/?probe=5e2040a91f) | Apr 25, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [ae90303c3a](https://linux-hardware.org/?probe=ae90303c3a) | Apr 25, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | Desktop     | [b1b8bf3df6](https://linux-hardware.org/?probe=b1b8bf3df6) | Apr 25, 2023 |
| HP            | ProBook 5320m               | Notebook    | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b72361ca9e](https://linux-hardware.org/?probe=b72361ca9e) | Apr 24, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [961a066e6b](https://linux-hardware.org/?probe=961a066e6b) | Apr 24, 2023 |
| Toshiba       | Satellite C855              | Notebook    | [b383279bda](https://linux-hardware.org/?probe=b383279bda) | Apr 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e72f221b5b](https://linux-hardware.org/?probe=e72f221b5b) | Apr 23, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | Desktop     | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Biostar       | A75MG                       | Desktop     | [50cb5c256e](https://linux-hardware.org/?probe=50cb5c256e) | Apr 22, 2023 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Notebook    | [503c99202e](https://linux-hardware.org/?probe=503c99202e) | Apr 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b3613186fa](https://linux-hardware.org/?probe=b3613186fa) | Apr 21, 2023 |
| Intel         | DB65AL AAG12530-310         | Desktop     | [c625f3747a](https://linux-hardware.org/?probe=c625f3747a) | Apr 21, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [78adec215e](https://linux-hardware.org/?probe=78adec215e) | Apr 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [68a7470480](https://linux-hardware.org/?probe=68a7470480) | Apr 19, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [53d3a8d066](https://linux-hardware.org/?probe=53d3a8d066) | Apr 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0W    | Notebook    | [97447a0777](https://linux-hardware.org/?probe=97447a0777) | Apr 19, 2023 |
| Lenovo        | ThinkPad T540p 20BECTO1W... | Notebook    | [ccb7f92798](https://linux-hardware.org/?probe=ccb7f92798) | Apr 19, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [b825c609a9](https://linux-hardware.org/?probe=b825c609a9) | Apr 15, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [7ac461b735](https://linux-hardware.org/?probe=7ac461b735) | Apr 15, 2023 |
| Gigabyte      | P55-UD3R                    | Desktop     | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Acer          | AO756                       | Notebook    | [c17d5276ec](https://linux-hardware.org/?probe=c17d5276ec) | Apr 14, 2023 |
| ASUSTek       | K73TA                       | Notebook    | [34319e673a](https://linux-hardware.org/?probe=34319e673a) | Apr 13, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| ASRock        | M3N78D FX                   | Desktop     | [618073d9e9](https://linux-hardware.org/?probe=618073d9e9) | Apr 12, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [6a6e2f88f4](https://linux-hardware.org/?probe=6a6e2f88f4) | Apr 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [2cec768fe1](https://linux-hardware.org/?probe=2cec768fe1) | Apr 11, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [54fabc7712](https://linux-hardware.org/?probe=54fabc7712) | Apr 09, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [f2040ffb31](https://linux-hardware.org/?probe=f2040ffb31) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [52b4a5a0f0](https://linux-hardware.org/?probe=52b4a5a0f0) | Apr 08, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [1502ff1933](https://linux-hardware.org/?probe=1502ff1933) | Apr 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2d355e87d7](https://linux-hardware.org/?probe=2d355e87d7) | Apr 07, 2023 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [ea2ee391a5](https://linux-hardware.org/?probe=ea2ee391a5) | Apr 07, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [10c9b38ed6](https://linux-hardware.org/?probe=10c9b38ed6) | Apr 07, 2023 |
| HP            | ProBook 4530s               | Notebook    | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [78e2e080ea](https://linux-hardware.org/?probe=78e2e080ea) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [fea5792a8b](https://linux-hardware.org/?probe=fea5792a8b) | Apr 06, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [8756f8891c](https://linux-hardware.org/?probe=8756f8891c) | Apr 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9e99b4150b](https://linux-hardware.org/?probe=9e99b4150b) | Apr 06, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [6da0293a4b](https://linux-hardware.org/?probe=6da0293a4b) | Apr 05, 2023 |
| Acer          | Aspire 3680                 | Notebook    | [b5511d9060](https://linux-hardware.org/?probe=b5511d9060) | Apr 05, 2023 |
| HP            | 245 G6                      | Notebook    | [c6a1e2951c](https://linux-hardware.org/?probe=c6a1e2951c) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [d8dc8a37b1](https://linux-hardware.org/?probe=d8dc8a37b1) | Apr 04, 2023 |
| Lenovo        | ThinkPad T410 2537WB7       | Notebook    | [d68ffd9d0f](https://linux-hardware.org/?probe=d68ffd9d0f) | Apr 04, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8293b6000a](https://linux-hardware.org/?probe=8293b6000a) | Apr 04, 2023 |
| Lenovo        | ThinkPad X220 4290CTO       | Notebook    | [5dd9277838](https://linux-hardware.org/?probe=5dd9277838) | Apr 04, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [de861c6d3f](https://linux-hardware.org/?probe=de861c6d3f) | Apr 03, 2023 |
| Acer          | Veriton X2632G V:1.0        | Desktop     | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| ASUSTek       | G752VM                      | Notebook    | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [5f703bfc7d](https://linux-hardware.org/?probe=5f703bfc7d) | Apr 01, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [96fcc41161](https://linux-hardware.org/?probe=96fcc41161) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| HP            | 2AFA                        | Desktop     | [d177838277](https://linux-hardware.org/?probe=d177838277) | Mar 31, 2023 |
| Dell          | XPS M1330                   | Notebook    | [46b9a5cfde](https://linux-hardware.org/?probe=46b9a5cfde) | Mar 31, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c51f53a733](https://linux-hardware.org/?probe=c51f53a733) | Mar 31, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [fc9a42e387](https://linux-hardware.org/?probe=fc9a42e387) | Mar 31, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [36c0a38885](https://linux-hardware.org/?probe=36c0a38885) | Mar 31, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c91e4d9c5a](https://linux-hardware.org/?probe=c91e4d9c5a) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| Lenovo        | ThinkPad Edge E530 3259M... | Notebook    | [9aaa97a931](https://linux-hardware.org/?probe=9aaa97a931) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [a316144991](https://linux-hardware.org/?probe=a316144991) | Mar 29, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [0bc21ff162](https://linux-hardware.org/?probe=0bc21ff162) | Mar 28, 2023 |
| HP            | 3047h                       | Desktop     | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [4f523c6409](https://linux-hardware.org/?probe=4f523c6409) | Mar 28, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [220c640743](https://linux-hardware.org/?probe=220c640743) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | All in one  | [fcd01e22d7](https://linux-hardware.org/?probe=fcd01e22d7) | Mar 28, 2023 |
| Dell          | Studio 1558                 | Notebook    | [955946c74d](https://linux-hardware.org/?probe=955946c74d) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [0901eb1e27](https://linux-hardware.org/?probe=0901eb1e27) | Mar 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6ddfac9d0](https://linux-hardware.org/?probe=d6ddfac9d0) | Mar 27, 2023 |
| HP            | 250 G1                      | Notebook    | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| HP            | 8158 A01                    | Mini pc     | [8d1c60fe86](https://linux-hardware.org/?probe=8d1c60fe86) | Mar 26, 2023 |
| Medion        | Akoya E6416                 | Notebook    | [bb2e759014](https://linux-hardware.org/?probe=bb2e759014) | Mar 26, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [6fc56d2339](https://linux-hardware.org/?probe=6fc56d2339) | Mar 25, 2023 |
| MSI           | A520M PRO                   | Desktop     | [c27ea21be5](https://linux-hardware.org/?probe=c27ea21be5) | Mar 25, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [1a4caa9a83](https://linux-hardware.org/?probe=1a4caa9a83) | Mar 24, 2023 |
| HP            | 86F3 00100                  | All in one  | [4cf13e2cd3](https://linux-hardware.org/?probe=4cf13e2cd3) | Mar 24, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [178936b7f4](https://linux-hardware.org/?probe=178936b7f4) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | Desktop     | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| MSI           | MS-7255                     | Desktop     | [7322068101](https://linux-hardware.org/?probe=7322068101) | Mar 23, 2023 |
| Toshiba       | T20                         | Notebook    | [a0757b47d7](https://linux-hardware.org/?probe=a0757b47d7) | Mar 22, 2023 |
| Acer          | TravelMate 5744             | Notebook    | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [db3e17d5f1](https://linux-hardware.org/?probe=db3e17d5f1) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [52b0aa69ba](https://linux-hardware.org/?probe=52b0aa69ba) | Mar 20, 2023 |
| HP            | 18E7                        | Desktop     | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [0daa99f732](https://linux-hardware.org/?probe=0daa99f732) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | Notebook    | [beeb327f26](https://linux-hardware.org/?probe=beeb327f26) | Mar 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [a3ffd8113f](https://linux-hardware.org/?probe=a3ffd8113f) | Mar 18, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [19fd2af680](https://linux-hardware.org/?probe=19fd2af680) | Mar 18, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [39d6b256fa](https://linux-hardware.org/?probe=39d6b256fa) | Mar 18, 2023 |
| MSI           | H55M-P31                    | Desktop     | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| Notebook      | N8xxEP6                     | Notebook    | [a4bd2c22eb](https://linux-hardware.org/?probe=a4bd2c22eb) | Mar 18, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9c24401930](https://linux-hardware.org/?probe=9c24401930) | Mar 18, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [2d7a146140](https://linux-hardware.org/?probe=2d7a146140) | Mar 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [fce879befb](https://linux-hardware.org/?probe=fce879befb) | Mar 18, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.217     | Desktop     | [1e1a430355](https://linux-hardware.org/?probe=1e1a430355) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [8a6e751b61](https://linux-hardware.org/?probe=8a6e751b61) | Mar 16, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| ASUSTek       | CG5290                      | Desktop     | [e0ab58dbfe](https://linux-hardware.org/?probe=e0ab58dbfe) | Mar 16, 2023 |
| ASUSTek       | VC62B                       | Desktop     | [9bf2d226a8](https://linux-hardware.org/?probe=9bf2d226a8) | Mar 15, 2023 |
| MSI           | H61M-P20                    | Desktop     | [8129a4f5a4](https://linux-hardware.org/?probe=8129a4f5a4) | Mar 15, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7fbe857344](https://linux-hardware.org/?probe=7fbe857344) | Mar 14, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [8ff2a816b5](https://linux-hardware.org/?probe=8ff2a816b5) | Mar 13, 2023 |
| ASRock        | G31M-S                      | Desktop     | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [9509c77e2b](https://linux-hardware.org/?probe=9509c77e2b) | Mar 13, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [4247bd6835](https://linux-hardware.org/?probe=4247bd6835) | Mar 12, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [a45ebd1b85](https://linux-hardware.org/?probe=a45ebd1b85) | Mar 12, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [757a62eff0](https://linux-hardware.org/?probe=757a62eff0) | Mar 11, 2023 |
| Pegatron      | 2AC2                        | Desktop     | [a6084e8904](https://linux-hardware.org/?probe=a6084e8904) | Mar 11, 2023 |
| Toshiba       | All In One PC MP            | All in one  | [2a3a0b15f8](https://linux-hardware.org/?probe=2a3a0b15f8) | Mar 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [d2b402f3c0](https://linux-hardware.org/?probe=d2b402f3c0) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [1d2e721898](https://linux-hardware.org/?probe=1d2e721898) | Mar 10, 2023 |
| HP            | 0AA0h                       | Desktop     | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [b8dffd9bd3](https://linux-hardware.org/?probe=b8dffd9bd3) | Mar 10, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [a5677d37dc](https://linux-hardware.org/?probe=a5677d37dc) | Mar 09, 2023 |
| ASRock        | H61M-ITX                    | Desktop     | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| HP            | ENVY 6                      | Notebook    | [4873f7b85f](https://linux-hardware.org/?probe=4873f7b85f) | Mar 08, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| ECS           | MCP61PM-GM                  | Desktop     | [ac561937e3](https://linux-hardware.org/?probe=ac561937e3) | Mar 08, 2023 |
| AZW           | GT-R                        | Notebook    | [cce9cccb8f](https://linux-hardware.org/?probe=cce9cccb8f) | Mar 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0cd8da5364](https://linux-hardware.org/?probe=0cd8da5364) | Mar 06, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9b72e94139](https://linux-hardware.org/?probe=9b72e94139) | Mar 06, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [c420621505](https://linux-hardware.org/?probe=c420621505) | Mar 05, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [d000dc6718](https://linux-hardware.org/?probe=d000dc6718) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [9c91f76369](https://linux-hardware.org/?probe=9c91f76369) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [9b0664e4d7](https://linux-hardware.org/?probe=9b0664e4d7) | Mar 04, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [82ecc9ac72](https://linux-hardware.org/?probe=82ecc9ac72) | Mar 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [84e37e870d](https://linux-hardware.org/?probe=84e37e870d) | Mar 03, 2023 |
| Toshiba       | dynabook R73/BN             | Notebook    | [1d81bb5f08](https://linux-hardware.org/?probe=1d81bb5f08) | Mar 03, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [1da5b61697](https://linux-hardware.org/?probe=1da5b61697) | Mar 02, 2023 |
| Acer          | Aspire E1-532P              | Notebook    | [8a23f06db4](https://linux-hardware.org/?probe=8a23f06db4) | Mar 01, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [5a0c297e10](https://linux-hardware.org/?probe=5a0c297e10) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a6af4042ea](https://linux-hardware.org/?probe=a6af4042ea) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0335729036](https://linux-hardware.org/?probe=0335729036) | Feb 27, 2023 |
| Intel         | H61                         | Desktop     | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| MSI           | NF750-G55                   | Desktop     | [f279251ffa](https://linux-hardware.org/?probe=f279251ffa) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| Acer          | EG43M                       | Desktop     | [d533c457eb](https://linux-hardware.org/?probe=d533c457eb) | Feb 26, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| eMachines     | eME728                      | Notebook    | [2331984fc8](https://linux-hardware.org/?probe=2331984fc8) | Feb 26, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| HP            | 650                         | Notebook    | [ab0b350259](https://linux-hardware.org/?probe=ab0b350259) | Feb 24, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9171567db4](https://linux-hardware.org/?probe=9171567db4) | Feb 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [b410c9f493](https://linux-hardware.org/?probe=b410c9f493) | Feb 24, 2023 |
| HP            | 1998                        | Desktop     | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [21aa20cd64](https://linux-hardware.org/?probe=21aa20cd64) | Feb 24, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [12040fcd10](https://linux-hardware.org/?probe=12040fcd10) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | Notebook    | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [cfe5ecec44](https://linux-hardware.org/?probe=cfe5ecec44) | Feb 23, 2023 |
| Biostar       | N68S3B                      | Desktop     | [4572b3d965](https://linux-hardware.org/?probe=4572b3d965) | Feb 23, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [75b2eb9c1f](https://linux-hardware.org/?probe=75b2eb9c1f) | Feb 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| Positivo      | S14SL01                     | Notebook    | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | Notebook    | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4803e8ee01](https://linux-hardware.org/?probe=4803e8ee01) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9523a0ccc2](https://linux-hardware.org/?probe=9523a0ccc2) | Feb 22, 2023 |
| Gateway       | NV53A                       | Notebook    | [1e2b4ec4d3](https://linux-hardware.org/?probe=1e2b4ec4d3) | Feb 22, 2023 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [28890c5346](https://linux-hardware.org/?probe=28890c5346) | Feb 21, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b4288b76ee](https://linux-hardware.org/?probe=b4288b76ee) | Feb 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| MSI           | G41M-P23                    | Desktop     | [04211b9202](https://linux-hardware.org/?probe=04211b9202) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASRock        | 880GM-LE FX                 | Desktop     | [db290cd703](https://linux-hardware.org/?probe=db290cd703) | Feb 19, 2023 |
| Lenovo        | B560 43308VG                | Notebook    | [c30b594458](https://linux-hardware.org/?probe=c30b594458) | Feb 19, 2023 |
| HP            | ProBook 4520s               | Notebook    | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | Desktop     | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | 15                          | Notebook    | [4db2520843](https://linux-hardware.org/?probe=4db2520843) | Feb 18, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [ff9cd473da](https://linux-hardware.org/?probe=ff9cd473da) | Feb 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| ASRock        | 880GM-LE FX                 | Desktop     | [1d45a444a3](https://linux-hardware.org/?probe=1d45a444a3) | Feb 18, 2023 |
| PC Special... | NJ50_70CU                   | Notebook    | [68dd853397](https://linux-hardware.org/?probe=68dd853397) | Feb 17, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [3ed988e135](https://linux-hardware.org/?probe=3ed988e135) | Feb 17, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [a524479b7a](https://linux-hardware.org/?probe=a524479b7a) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | Notebook    | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| EVGA          | 151-IB-E699                 | Desktop     | [9e975c7966](https://linux-hardware.org/?probe=9e975c7966) | Feb 17, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ac458108b4](https://linux-hardware.org/?probe=ac458108b4) | Feb 17, 2023 |
| Pegatron      | IPM31G                      | Desktop     | [42d112d7e0](https://linux-hardware.org/?probe=42d112d7e0) | Feb 17, 2023 |
| ASUSTek       | K54C                        | Notebook    | [ea944628df](https://linux-hardware.org/?probe=ea944628df) | Feb 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [66c33604c4](https://linux-hardware.org/?probe=66c33604c4) | Feb 17, 2023 |
| Samsung       | R519/R719                   | Notebook    | [1dc4bc1b72](https://linux-hardware.org/?probe=1dc4bc1b72) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| HP            | 2820h                       | Desktop     | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| eMachines     | eMachiens G443              | Notebook    | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| MSI           | H61M-E33                    | Desktop     | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M91 4518E4S     | Desktop     | [91b1fb7e03](https://linux-hardware.org/?probe=91b1fb7e03) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| ASUSTek       | H81T                        | Desktop     | [51aa090e9a](https://linux-hardware.org/?probe=51aa090e9a) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| Dell          | Latitude E7440              | Notebook    | [86f8d34ba7](https://linux-hardware.org/?probe=86f8d34ba7) | Feb 16, 2023 |
| HP            | 3031h                       | Desktop     | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| Toshiba       | dynabook R73/BN             | Notebook    | [df7e69c5c4](https://linux-hardware.org/?probe=df7e69c5c4) | Feb 16, 2023 |
| HP            | ProBook 470 G4              | Notebook    | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| MSI           | MS-7235                     | Desktop     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [f87ece85e9](https://linux-hardware.org/?probe=f87ece85e9) | Feb 15, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| HP            | 1000                        | Notebook    | [57de0f3103](https://linux-hardware.org/?probe=57de0f3103) | Feb 15, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [20b88dda19](https://linux-hardware.org/?probe=20b88dda19) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [f9318d4390](https://linux-hardware.org/?probe=f9318d4390) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| ASRock        | E350M1                      | Desktop     | [ac69adceb6](https://linux-hardware.org/?probe=ac69adceb6) | Feb 13, 2023 |
| ASUSTek       | P7P55D-E EVO                | Desktop     | [f1ec250753](https://linux-hardware.org/?probe=f1ec250753) | Feb 13, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [cdc2dedbcd](https://linux-hardware.org/?probe=cdc2dedbcd) | Feb 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7623da10b8](https://linux-hardware.org/?probe=7623da10b8) | Feb 13, 2023 |
| HP            | 3031h                       | Desktop     | [f9a0848388](https://linux-hardware.org/?probe=f9a0848388) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f0f4d31de2](https://linux-hardware.org/?probe=f0f4d31de2) | Feb 10, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| Medion        | TJ4105                      | Desktop     | [cd654518c0](https://linux-hardware.org/?probe=cd654518c0) | Feb 09, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [8532f05156](https://linux-hardware.org/?probe=8532f05156) | Feb 09, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [df4d59acd5](https://linux-hardware.org/?probe=df4d59acd5) | Feb 07, 2023 |
| HP            | 1905                        | Desktop     | [a442e1de06](https://linux-hardware.org/?probe=a442e1de06) | Feb 07, 2023 |
| Lenovo        | ThinkPad X240 20AL00FMGE    | Notebook    | [0ac2678512](https://linux-hardware.org/?probe=0ac2678512) | Feb 06, 2023 |
| Acer          | Extensa 5635                | Notebook    | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [7fe633b52f](https://linux-hardware.org/?probe=7fe633b52f) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| HP            | ProBook 6465b               | Notebook    | [00b2021fae](https://linux-hardware.org/?probe=00b2021fae) | Feb 04, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [87fe173b18](https://linux-hardware.org/?probe=87fe173b18) | Feb 02, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a440e41d7](https://linux-hardware.org/?probe=6a440e41d7) | Feb 02, 2023 |
| Dell          | Latitude E5420              | Notebook    | [ccc3ca9853](https://linux-hardware.org/?probe=ccc3ca9853) | Jan 31, 2023 |
| HP            | 3115-AEC13432GR1            | Notebook    | [98eb70341a](https://linux-hardware.org/?probe=98eb70341a) | Jan 30, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| HP            | Notebook                    | Notebook    | [d38e078368](https://linux-hardware.org/?probe=d38e078368) | Jan 28, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| HP            | 14                          | Notebook    | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | Notebook    | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [873ee647b0](https://linux-hardware.org/?probe=873ee647b0) | Jan 26, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| HP            | 3048h                       | Desktop     | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | Notebook    | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| AZW           | U59                         | Desktop     | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | Desktop     | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | Notebook    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [95898eae6d](https://linux-hardware.org/?probe=95898eae6d) | Jan 23, 2023 |
| Packard Be... | PB56                        | Notebook    | [f26fcb7ee5](https://linux-hardware.org/?probe=f26fcb7ee5) | Jan 23, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [5b29ed7213](https://linux-hardware.org/?probe=5b29ed7213) | Jan 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| Gigabyte      | N3050ND3H                   | Desktop     | [1663928526](https://linux-hardware.org/?probe=1663928526) | Jan 21, 2023 |
| HP            | Pavilion dv5                | Notebook    | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| GEEKOM        | MiniAir 11                  | Server      | [0d27879bb6](https://linux-hardware.org/?probe=0d27879bb6) | Jan 19, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [c3d132fb91](https://linux-hardware.org/?probe=c3d132fb91) | Jan 18, 2023 |
| ASUSTek       | C60M1-I                     | Desktop     | [defd3912ae](https://linux-hardware.org/?probe=defd3912ae) | Jan 18, 2023 |
| Panasonic     | CF-53JULCV1M                | Notebook    | [89c1166efc](https://linux-hardware.org/?probe=89c1166efc) | Jan 18, 2023 |
| Unknown       | HX90                        | Desktop     | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| HP            | ProBook 440 G1              | Notebook    | [035c7a4e2d](https://linux-hardware.org/?probe=035c7a4e2d) | Jan 18, 2023 |
| Medion        | MS-7621                     | Desktop     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b611fc6b64](https://linux-hardware.org/?probe=b611fc6b64) | Jan 18, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [74a62575d2](https://linux-hardware.org/?probe=74a62575d2) | Jan 17, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [276102bb1a](https://linux-hardware.org/?probe=276102bb1a) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [9941154ca3](https://linux-hardware.org/?probe=9941154ca3) | Jan 15, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [c20a339ddb](https://linux-hardware.org/?probe=c20a339ddb) | Jan 15, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| Acer          | Aspire 7551                 | Notebook    | [b3e5df94f4](https://linux-hardware.org/?probe=b3e5df94f4) | Jan 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [b70eca9c43](https://linux-hardware.org/?probe=b70eca9c43) | Jan 14, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9c4aac8b46](https://linux-hardware.org/?probe=9c4aac8b46) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| HP            | 8054                        | Desktop     | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| Supermicro    | A1SA2-2750F                 | Server      | [e134d7a317](https://linux-hardware.org/?probe=e134d7a317) | Jan 14, 2023 |
| HP            | 18E5                        | Desktop     | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | 84EE 1100                   | All in one  | [708c21d16b](https://linux-hardware.org/?probe=708c21d16b) | Jan 13, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [12f29d53ba](https://linux-hardware.org/?probe=12f29d53ba) | Jan 13, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [72e7e2e1cf](https://linux-hardware.org/?probe=72e7e2e1cf) | Jan 11, 2023 |
| Toshiba       | Satellite C850-B561         | Notebook    | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Lenovo        | ThinkPad X240 20AM001RGE    | Notebook    | [f4aafcf7a9](https://linux-hardware.org/?probe=f4aafcf7a9) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [ce911686b3](https://linux-hardware.org/?probe=ce911686b3) | Jan 10, 2023 |
| Dell          | XPS M1330                   | Notebook    | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [ec34a44908](https://linux-hardware.org/?probe=ec34a44908) | Jan 10, 2023 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [f540a5f964](https://linux-hardware.org/?probe=f540a5f964) | Jan 09, 2023 |
| Star Labs     | Lite                        | Notebook    | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| HP            | 802F                        | Desktop     | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [a2bce032b4](https://linux-hardware.org/?probe=a2bce032b4) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | Desktop     | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| HP            | 8265                        | Desktop     | [83897e98cf](https://linux-hardware.org/?probe=83897e98cf) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | Desktop     | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [d94d0c7025](https://linux-hardware.org/?probe=d94d0c7025) | Jan 08, 2023 |
| Dell          | Latitude E6400              | Notebook    | [70bce3a55c](https://linux-hardware.org/?probe=70bce3a55c) | Jan 08, 2023 |
| HP            | 1489                        | All in one  | [2660a9d31d](https://linux-hardware.org/?probe=2660a9d31d) | Jan 08, 2023 |
| Dell          | Latitude E5440              | Notebook    | [91bedeb5e1](https://linux-hardware.org/?probe=91bedeb5e1) | Jan 07, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [d0e4567b4a](https://linux-hardware.org/?probe=d0e4567b4a) | Jan 07, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [3bc9e3b318](https://linux-hardware.org/?probe=3bc9e3b318) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| Alienware     | 04VWF2 A02                  | Desktop     | [15f4ed4e31](https://linux-hardware.org/?probe=15f4ed4e31) | Jan 07, 2023 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [e6190d3469](https://linux-hardware.org/?probe=e6190d3469) | Jan 07, 2023 |
| HP            | 250 G3                      | Notebook    | [227b44bf7c](https://linux-hardware.org/?probe=227b44bf7c) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| eMachines     | E725                        | Notebook    | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| Acer          | Spin SP513-51               | Convertible | [1fe9e7fa54](https://linux-hardware.org/?probe=1fe9e7fa54) | Jan 06, 2023 |
| Acer          | Veriton M2631G V:1.0        | Desktop     | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | Notebook    | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| HP            | ProBook 470 G2              | Notebook    | [1f62ff6417](https://linux-hardware.org/?probe=1f62ff6417) | Jan 04, 2023 |
| HP            | Compaq 15                   | Notebook    | [c282ede7c5](https://linux-hardware.org/?probe=c282ede7c5) | Jan 04, 2023 |
| HP            | EliteBook 725 G3            | Notebook    | [174e0c5f05](https://linux-hardware.org/?probe=174e0c5f05) | Jan 04, 2023 |
| Dell          | Latitude D520               | Notebook    | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7e445638b6](https://linux-hardware.org/?probe=7e445638b6) | Jan 04, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [1caf5c85d9](https://linux-hardware.org/?probe=1caf5c85d9) | Jan 04, 2023 |
| Sony          | VJF153                      | Notebook    | [f3643923cc](https://linux-hardware.org/?probe=f3643923cc) | Jan 04, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c0e5361a69](https://linux-hardware.org/?probe=c0e5361a69) | Jan 03, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [55627fc077](https://linux-hardware.org/?probe=55627fc077) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [faccba61cf](https://linux-hardware.org/?probe=faccba61cf) | Jan 03, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [afe5105302](https://linux-hardware.org/?probe=afe5105302) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Dell          | 0MM599                      | Desktop     | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [e93bf27a59](https://linux-hardware.org/?probe=e93bf27a59) | Jan 02, 2023 |
| Positivo      | Z100                        | Notebook    | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [287840d797](https://linux-hardware.org/?probe=287840d797) | Jan 02, 2023 |
| AZW           | MINI S                      | Desktop     | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [86b79bce9e](https://linux-hardware.org/?probe=86b79bce9e) | Jan 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| OEM           | Intel H81                   | Desktop     | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| Dell          | System Inspiron N411Z       | Notebook    | [21f279751c](https://linux-hardware.org/?probe=21f279751c) | Jan 01, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [e2215a9d80](https://linux-hardware.org/?probe=e2215a9d80) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | Notebook    | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| HP            | 1000                        | Notebook    | [5634ff72b1](https://linux-hardware.org/?probe=5634ff72b1) | Jan 01, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [bba53b0159](https://linux-hardware.org/?probe=bba53b0159) | Jan 01, 2023 |
| Toshiba       | Satellite A305D             | Notebook    | [b85a377462](https://linux-hardware.org/?probe=b85a377462) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | UN45                        | Desktop     | [bde2e2efb1](https://linux-hardware.org/?probe=bde2e2efb1) | Dec 31, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [9126e1035f](https://linux-hardware.org/?probe=9126e1035f) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | Notebook    | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| ASUSTek       | TP501UA                     | Notebook    | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | Notebook    | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | STRIKER II EXTREME          | Desktop     | [3258ffa0c1](https://linux-hardware.org/?probe=3258ffa0c1) | Dec 29, 2022 |
| ASUSTek       | G1                          | Notebook    | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| HP            | Notebook                    | Notebook    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | Notebook    | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [3f0c89985c](https://linux-hardware.org/?probe=3f0c89985c) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4734f4370b](https://linux-hardware.org/?probe=4734f4370b) | Dec 28, 2022 |
| Lenovo        | V560                        | Notebook    | [f937de4c61](https://linux-hardware.org/?probe=f937de4c61) | Dec 28, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [92ece593f5](https://linux-hardware.org/?probe=92ece593f5) | Dec 28, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [bd56ec4f01](https://linux-hardware.org/?probe=bd56ec4f01) | Dec 28, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Positivo      | Hendrix                     | Notebook    | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| Pegatron      | APX85-GS                    | Desktop     | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Acer          | Aspire TC-865 V:1.1         | Desktop     | [0c8add55fe](https://linux-hardware.org/?probe=0c8add55fe) | Dec 27, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | Notebook    | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | 2AF7                        | Desktop     | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [e012bb5bc1](https://linux-hardware.org/?probe=e012bb5bc1) | Dec 25, 2022 |
| ASUSTek       | M51Tr                       | Notebook    | [dffa412a98](https://linux-hardware.org/?probe=dffa412a98) | Dec 25, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | Desktop     | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| Dell          | G7 7790                     | Notebook    | [da767d5fd4](https://linux-hardware.org/?probe=da767d5fd4) | Dec 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [8c835888d6](https://linux-hardware.org/?probe=8c835888d6) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [435933801a](https://linux-hardware.org/?probe=435933801a) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [f2e0369ba1](https://linux-hardware.org/?probe=f2e0369ba1) | Dec 24, 2022 |
| Positivo      | Mobile                      | Notebook    | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Positivo      | H14BT58                     | Notebook    | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| MSI           | 880GM-E41                   | Desktop     | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | Desktop     | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | Desktop     | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| Dell          | Latitude 5280               | Notebook    | [59002e923b](https://linux-hardware.org/?probe=59002e923b) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | Notebook    | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | Notebook    | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [003ac98d7f](https://linux-hardware.org/?probe=003ac98d7f) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | Desktop     | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ec2528ae6f](https://linux-hardware.org/?probe=ec2528ae6f) | Dec 20, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [9724b5d705](https://linux-hardware.org/?probe=9724b5d705) | Dec 20, 2022 |
| RM Educati... | RM                          | Notebook    | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Langchao      | NF5110                      | Server      | [3578ca8ceb](https://linux-hardware.org/?probe=3578ca8ceb) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| ECS           | G31T-M7                     | Desktop     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | Notebook    | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| MSI           | H81M-E34                    | Desktop     | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | Notebook    | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [d1d5c6a19e](https://linux-hardware.org/?probe=d1d5c6a19e) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [ff287eecab](https://linux-hardware.org/?probe=ff287eecab) | Dec 18, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [71ebf721cc](https://linux-hardware.org/?probe=71ebf721cc) | Dec 17, 2022 |
| HP            | 8055                        | Desktop     | [6c7fa83dc9](https://linux-hardware.org/?probe=6c7fa83dc9) | Dec 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Lenovo        | Yoga 2-11 20332             | Notebook    | [92a038a164](https://linux-hardware.org/?probe=92a038a164) | Dec 16, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [b2b98c19da](https://linux-hardware.org/?probe=b2b98c19da) | Dec 15, 2022 |
| Acer          | Veriton N2620G              | Desktop     | [a626bf668e](https://linux-hardware.org/?probe=a626bf668e) | Dec 15, 2022 |
| Dell          | 050Nt9 A00                  | All in one  | [075f206957](https://linux-hardware.org/?probe=075f206957) | Dec 15, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| ASUSTek       | K40IJ                       | Notebook    | [191b6ded65](https://linux-hardware.org/?probe=191b6ded65) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | Desktop     | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| HP            | 2AFB                        | Desktop     | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Lenovo        | ThinkPad X230 23245QP       | Notebook    | [e525a77c95](https://linux-hardware.org/?probe=e525a77c95) | Dec 15, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [b76fa704f7](https://linux-hardware.org/?probe=b76fa704f7) | Dec 15, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [a9d66f9686](https://linux-hardware.org/?probe=a9d66f9686) | Dec 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [d5aa2c3900](https://linux-hardware.org/?probe=d5aa2c3900) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | Desktop     | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Datto         | SSD                         | Desktop     | [a9bff0a51c](https://linux-hardware.org/?probe=a9bff0a51c) | Dec 14, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [373f71370e](https://linux-hardware.org/?probe=373f71370e) | Dec 14, 2022 |
| HP            | 304Ah                       | Desktop     | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| HP            | Notebook                    | Notebook    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [6895902fe7](https://linux-hardware.org/?probe=6895902fe7) | Dec 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c832b9b688](https://linux-hardware.org/?probe=c832b9b688) | Dec 12, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [ec5acc536f](https://linux-hardware.org/?probe=ec5acc536f) | Dec 12, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4784b53f14](https://linux-hardware.org/?probe=4784b53f14) | Dec 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [62f6fd5f8d](https://linux-hardware.org/?probe=62f6fd5f8d) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Dell          | 0KG317                      | Desktop     | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| HP            | 650                         | Notebook    | [9bb3729969](https://linux-hardware.org/?probe=9bb3729969) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [d7ea1184a2](https://linux-hardware.org/?probe=d7ea1184a2) | Dec 10, 2022 |
| Acer          | Aspire V5-573               | Notebook    | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [344383d85d](https://linux-hardware.org/?probe=344383d85d) | Dec 10, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | Desktop     | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| HP            | 18E7                        | Desktop     | [9759493e06](https://linux-hardware.org/?probe=9759493e06) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | Desktop     | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| Positivo      | Mobile                      | Notebook    | [bc5f4e6c85](https://linux-hardware.org/?probe=bc5f4e6c85) | Dec 09, 2022 |
| Acer          | TravelMate 5720             | Notebook    | [d0a54f621e](https://linux-hardware.org/?probe=d0a54f621e) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [8ab7a916f1](https://linux-hardware.org/?probe=8ab7a916f1) | Dec 08, 2022 |
| HP            | 15                          | Notebook    | [20dfd7b8f5](https://linux-hardware.org/?probe=20dfd7b8f5) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [0203e79add](https://linux-hardware.org/?probe=0203e79add) | Dec 08, 2022 |
| Packard Be... | DOT S                       | Notebook    | [753f17a658](https://linux-hardware.org/?probe=753f17a658) | Dec 08, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [469f0a1d1f](https://linux-hardware.org/?probe=469f0a1d1f) | Dec 07, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [3ab56a93d6](https://linux-hardware.org/?probe=3ab56a93d6) | Dec 07, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [1a35ba24c1](https://linux-hardware.org/?probe=1a35ba24c1) | Dec 07, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [a745b1ead9](https://linux-hardware.org/?probe=a745b1ead9) | Dec 07, 2022 |
| Positivo      | H14BT58                     | Notebook    | [c038df5c8c](https://linux-hardware.org/?probe=c038df5c8c) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bc15145c](https://linux-hardware.org/?probe=b0bc15145c) | Dec 06, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [13ca001c57](https://linux-hardware.org/?probe=13ca001c57) | Dec 06, 2022 |
| HP            | 15                          | Notebook    | [e5a0cdc9de](https://linux-hardware.org/?probe=e5a0cdc9de) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | Desktop     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [20786b000c](https://linux-hardware.org/?probe=20786b000c) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | Desktop     | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| HP            | Pavilion dv6000 (RV009UA... | Notebook    | [6dcd661136](https://linux-hardware.org/?probe=6dcd661136) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| Sony          | VPCEL2S1E                   | Notebook    | [0c98b9d570](https://linux-hardware.org/?probe=0c98b9d570) | Dec 04, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [af63449087](https://linux-hardware.org/?probe=af63449087) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | Notebook    | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | Desktop     | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Sony          | VGN-NW31JF_S                | Notebook    | [ebfbfb034a](https://linux-hardware.org/?probe=ebfbfb034a) | Dec 04, 2022 |
| ASUSTek       | K42F                        | Notebook    | [05ddce411d](https://linux-hardware.org/?probe=05ddce411d) | Dec 04, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [bfe28498bd](https://linux-hardware.org/?probe=bfe28498bd) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| Dell          | Latitude E5510              | Notebook    | [6027856ab6](https://linux-hardware.org/?probe=6027856ab6) | Dec 03, 2022 |
| Acer          | Aspire X3950                | Desktop     | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f8f94617e8](https://linux-hardware.org/?probe=f8f94617e8) | Dec 03, 2022 |
| HP            | 8648                        | Desktop     | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [d9bba42204](https://linux-hardware.org/?probe=d9bba42204) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [78f2f440eb](https://linux-hardware.org/?probe=78f2f440eb) | Dec 02, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [8a2aad437e](https://linux-hardware.org/?probe=8a2aad437e) | Dec 02, 2022 |
| Langchao      | NF5110                      | Server      | [ae8b7868da](https://linux-hardware.org/?probe=ae8b7868da) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| Dell          | Latitude E6420              | Notebook    | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | Desktop     | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | Desktop     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Samsung       | 550XDA                      | Notebook    | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Medion        | MS-7800                     | Desktop     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| Dell          | 0YHMCJ A01                  | Server      | [77f946c99b](https://linux-hardware.org/?probe=77f946c99b) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9505f905e8](https://linux-hardware.org/?probe=9505f905e8) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1a742c23df](https://linux-hardware.org/?probe=1a742c23df) | Nov 29, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [f03f3a9325](https://linux-hardware.org/?probe=f03f3a9325) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| ECS           | 945P/PL-A                   | Desktop     | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Toshiba       | Satellite L875              | Notebook    | [2d5e211d72](https://linux-hardware.org/?probe=2d5e211d72) | Nov 28, 2022 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [8af94993bd](https://linux-hardware.org/?probe=8af94993bd) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Medion        | E11201                      | Notebook    | [0838f9db75](https://linux-hardware.org/?probe=0838f9db75) | Nov 27, 2022 |
| Gateway       | M-1631U                     | Notebook    | [f0f0517dab](https://linux-hardware.org/?probe=f0f0517dab) | Nov 27, 2022 |
| Medion        | E2292                       | Convertible | [98818a6a22](https://linux-hardware.org/?probe=98818a6a22) | Nov 27, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | Desktop     | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| Lenovo        | 3000 N500 42336DS           | Notebook    | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| MSI           | P55-CD53                    | Desktop     | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Dell          | Latitude E6220              | Notebook    | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | Desktop     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| HP            | 1589                        | Desktop     | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| HP            | 2215                        | Desktop     | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [9f49ff06cf](https://linux-hardware.org/?probe=9f49ff06cf) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| HP            | 650                         | Notebook    | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [600e3f0f09](https://linux-hardware.org/?probe=600e3f0f09) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [9b50d75b30](https://linux-hardware.org/?probe=9b50d75b30) | Nov 24, 2022 |
| Foxconn       | 2A92                        | Desktop     | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | Desktop     | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | Desktop     | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | Notebook    | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | 8582 01100                  | All in one  | [4977f9d91d](https://linux-hardware.org/?probe=4977f9d91d) | Nov 23, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| HP            | Notebook                    | Notebook    | [616c071073](https://linux-hardware.org/?probe=616c071073) | Nov 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [063ffbb0e8](https://linux-hardware.org/?probe=063ffbb0e8) | Nov 23, 2022 |
| Lenovo        | IdeaPad U310 Touch          | Notebook    | [09beadc5ae](https://linux-hardware.org/?probe=09beadc5ae) | Nov 22, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| Intel         | powered classmate PC        | Notebook    | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | Notebook    | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| HP            | 3399                        | Desktop     | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | Desktop     | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | Desktop     | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | Desktop     | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | Desktop     | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| Alienware     | M17xR3                      | Notebook    | [d472e55685](https://linux-hardware.org/?probe=d472e55685) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7d3f0e5604](https://linux-hardware.org/?probe=7d3f0e5604) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Chuwi         | LapBook SE                  | Notebook    | [ecc56a3703](https://linux-hardware.org/?probe=ecc56a3703) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Shuttle       | FS61                        | Desktop     | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | Notebook    | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| HP            | Pavilion dm4                | Notebook    | [d90ac7b5c2](https://linux-hardware.org/?probe=d90ac7b5c2) | Nov 19, 2022 |
| ECS           | G41T-M7                     | Desktop     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | Desktop     | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| HP            | Notebook                    | Notebook    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| HP            | Presario CQ43               | Notebook    | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [c27978fdc4](https://linux-hardware.org/?probe=c27978fdc4) | Nov 18, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [05ad62f97d](https://linux-hardware.org/?probe=05ad62f97d) | Nov 17, 2022 |
| Packard Be... | EasyNote TK81               | Notebook    | [c396423368](https://linux-hardware.org/?probe=c396423368) | Nov 17, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [ba95174feb](https://linux-hardware.org/?probe=ba95174feb) | Nov 17, 2022 |
| Compaq        | 420                         | Notebook    | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| Dell          | 0FDT3J A03                  | Server      | [438f28559c](https://linux-hardware.org/?probe=438f28559c) | Nov 16, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | Desktop     | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | Desktop     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| MSI           | CR620                       | Notebook    | [4d90de18ca](https://linux-hardware.org/?probe=4d90de18ca) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | Desktop     | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Toshiba       | Satellite Pro U500          | Notebook    | [064a36a5bb](https://linux-hardware.org/?probe=064a36a5bb) | Nov 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [6f3ecf327d](https://linux-hardware.org/?probe=6f3ecf327d) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| AZW           | Gemini M                    | Desktop     | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| LDLC          | SPC-N                       | Notebook    | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| Dell          | 0UR033 A00                  | Server      | [2ff8924b15](https://linux-hardware.org/?probe=2ff8924b15) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | N751JX                      | Notebook    | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| HP            | 22F8                        | Desktop     | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [80be7e8e25](https://linux-hardware.org/?probe=80be7e8e25) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | Notebook    | [4121297e16](https://linux-hardware.org/?probe=4121297e16) | Nov 14, 2022 |
| Sony          | SVE1411EGXB                 | Notebook    | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| Lenovo        | 0x36C4 SDK0K17763 WIN 18... | All in one  | [7a3f735fc0](https://linux-hardware.org/?probe=7a3f735fc0) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| HP            | 84FD                        | Desktop     | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | Desktop     | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [f6b2530682](https://linux-hardware.org/?probe=f6b2530682) | Nov 12, 2022 |
| HP            | ProBook 455 G2              | Notebook    | [1a5d0a1618](https://linux-hardware.org/?probe=1a5d0a1618) | Nov 12, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [be3a3b081d](https://linux-hardware.org/?probe=be3a3b081d) | Nov 12, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [d5166a002a](https://linux-hardware.org/?probe=d5166a002a) | Nov 11, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| MSI           | U270DX                      | Notebook    | [2a68a6ba02](https://linux-hardware.org/?probe=2a68a6ba02) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5a5633f611](https://linux-hardware.org/?probe=5a5633f611) | Nov 09, 2022 |
| Acer          | RS880M05                    | Desktop     | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| Fujitsu       | FMVXN4MN2Z                  | Notebook    | [7a08a94b1e](https://linux-hardware.org/?probe=7a08a94b1e) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Dell          | 0V52N7 A02                  | Server      | [3151a21ebf](https://linux-hardware.org/?probe=3151a21ebf) | Nov 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [c46b9195f3](https://linux-hardware.org/?probe=c46b9195f3) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| Acer          | Aspire X1700                | Desktop     | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| Dell          | Latitude E6400              | Notebook    | [22ccbac81a](https://linux-hardware.org/?probe=22ccbac81a) | Nov 07, 2022 |
| HP            | Notebook                    | Notebook    | [0164126ac9](https://linux-hardware.org/?probe=0164126ac9) | Nov 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| ASUSTek       | K53E                        | Notebook    | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| HP            | Notebook                    | Notebook    | [59b70f4c7c](https://linux-hardware.org/?probe=59b70f4c7c) | Nov 06, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | Desktop     | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| Lenovo        | G485 20136                  | Notebook    | [f8ee5082f8](https://linux-hardware.org/?probe=f8ee5082f8) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| Acer          | TravelMate P259-G2-M        | Notebook    | [4a85f586b3](https://linux-hardware.org/?probe=4a85f586b3) | Nov 05, 2022 |
| Acer          | Aspire A717-71G             | Notebook    | [a6fa794196](https://linux-hardware.org/?probe=a6fa794196) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e2cadc512e](https://linux-hardware.org/?probe=e2cadc512e) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| HP            | 2820h                       | Desktop     | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [c125fc089c](https://linux-hardware.org/?probe=c125fc089c) | Nov 05, 2022 |
| VS Company    | MCP61M                      | Desktop     | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| Lenovo        | ThinkPad L520 78596CG       | Notebook    | [094f09bcf8](https://linux-hardware.org/?probe=094f09bcf8) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | Notebook    | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Lenovo        | B50-45 80F0                 | Notebook    | [2d36803ec6](https://linux-hardware.org/?probe=2d36803ec6) | Nov 04, 2022 |
| ASUSTek       | H170I-PLUS D3               | Desktop     | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | Notebook    | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Samsung       | 400B2B/400B2B               | Notebook    | [a909b4b203](https://linux-hardware.org/?probe=a909b4b203) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [f9f727f7e5](https://linux-hardware.org/?probe=f9f727f7e5) | Nov 02, 2022 |
| HP            | ENVY m6                     | Notebook    | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [83a1fc191a](https://linux-hardware.org/?probe=83a1fc191a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Panasonic     | CF-C1BWFBZ1M                | Notebook    | [18a81d5db2](https://linux-hardware.org/?probe=18a81d5db2) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | Desktop     | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003       | 4251      | 92.49%  |
| 5.16.13-desktop-1omv4003      | 302       | 6.57%   |
| 5.17.1-desktop-2omv4050       | 17        | 0.37%   |
| 5.14.14-desktop-1omv4050      | 7         | 0.15%   |
| 5.16.5-desktop-2omv4003       | 4         | 0.09%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.04%   |
| 5.16.9-desktop-1omv4003       | 2         | 0.04%   |
| 5.16.3-desktop-2omv4050       | 2         | 0.04%   |
| 5.10.14-desktop-1omv4002      | 2         | 0.04%   |
| 6.1.10                        | 1         | 0.02%   |
| 5.17.7-desktop-1omv4090       | 1         | 0.02%   |
| 5.16.9-desktop-1omv4050       | 1         | 0.02%   |
| 5.16.7-desktop-clang-1omv4003 | 1         | 0.02%   |
| 5.16.13-desktop-1omv4050      | 1         | 0.02%   |
| 5.15.14-1-lts                 | 1         | 0.02%   |
| 5.11.12-desktop-1omv4002      | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.7  | 4252      | 92.52%  |
| 5.16.13 | 303       | 6.59%   |
| 5.17.1  | 19        | 0.41%   |
| 5.14.14 | 7         | 0.15%   |
| 5.16.5  | 4         | 0.09%   |
| 5.16.9  | 3         | 0.07%   |
| 5.16.3  | 2         | 0.04%   |
| 5.10.14 | 2         | 0.04%   |
| 6.1.10  | 1         | 0.02%   |
| 5.17.7  | 1         | 0.02%   |
| 5.15.14 | 1         | 0.02%   |
| 5.11.12 | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 4498      | 99.29%  |
| 5.17    | 20        | 0.44%   |
| 5.14    | 7         | 0.15%   |
| 5.10    | 2         | 0.04%   |
| 6.1     | 1         | 0.02%   |
| 5.15    | 1         | 0.02%   |
| 5.11    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4529      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 4512      | 99.54%  |
| LXQt     | 9         | 0.2%    |
| Unknown  | 7         | 0.15%   |
| Budgie   | 3         | 0.07%   |
| Cinnamon | 2         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4500      | 99.36%  |
| Wayland | 29        | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 4526      | 99.91%  |
| LightDM | 4         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 2537      | 55.64%  |
| de_DE | 396       | 8.68%   |
| fr_FR | 238       | 5.22%   |
| ru_RU | 232       | 5.09%   |
| pt_BR | 184       | 4.04%   |
| pl_PL | 139       | 3.05%   |
| it_IT | 123       | 2.7%    |
| en_GB | 97        | 2.13%   |
| es_ES | 88        | 1.93%   |
| cs_CZ | 52        | 1.14%   |
| es_AR | 45        | 0.99%   |
| es_MX | 44        | 0.96%   |
| de_AT | 41        | 0.9%    |
| en_IN | 26        | 0.57%   |
| hu_HU | 25        | 0.55%   |
| en_CA | 22        | 0.48%   |
| tr_TR | 21        | 0.46%   |
| pt_PT | 19        | 0.42%   |
| es_CO | 19        | 0.42%   |
| fr_CA | 18        | 0.39%   |
| en_AU | 16        | 0.35%   |
| nl_NL | 15        | 0.33%   |
| es_CL | 15        | 0.33%   |
| de_CH | 15        | 0.33%   |
| fr_BE | 13        | 0.29%   |
| es_VE | 11        | 0.24%   |
| ru_UA | 10        | 0.22%   |
| nl_BE | 9         | 0.2%    |
| da_DK | 9         | 0.2%    |
| es_PE | 8         | 0.18%   |
| nb_NO | 6         | 0.13%   |
| fr_CH | 6         | 0.13%   |
| es_CR | 5         | 0.11%   |
| ro_RO | 4         | 0.09%   |
| es_UY | 4         | 0.09%   |
| es_EC | 4         | 0.09%   |
| es_BO | 4         | 0.09%   |
| uk_UA | 3         | 0.07%   |
| es_SV | 3         | 0.07%   |
| en_ZA | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2348      | 51.79%  |
| BIOS | 2186      | 48.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 3655      | 79.44%  |
| Ext4     | 924       | 20.08%  |
| Btrfs    | 7         | 0.15%   |
| Xfs      | 6         | 0.13%   |
| F2fs     | 5         | 0.11%   |
| Jfs      | 2         | 0.04%   |
| Reiserfs | 1         | 0.02%   |
| Ext3     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3033      | 66.72%  |
| MBR     | 1493      | 32.84%  |
| Unknown | 20        | 0.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2497      | 54.67%  |
| No        | 2070      | 45.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2309      | 50.88%  |
| Yes       | 2229      | 49.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUSTek Computer      | 718       | 15.85%  |
| Dell                  | 604       | 13.34%  |
| Hewlett-Packard       | 593       | 13.09%  |
| Lenovo                | 532       | 11.75%  |
| Gigabyte Technology   | 396       | 8.74%   |
| Acer                  | 301       | 6.65%   |
| MSI                   | 262       | 5.78%   |
| ASRock                | 184       | 4.06%   |
| Toshiba               | 107       | 2.36%   |
| Intel                 | 97        | 2.14%   |
| Apple                 | 79        | 1.74%   |
| Fujitsu               | 70        | 1.55%   |
| Samsung Electronics   | 50        | 1.1%    |
| Sony                  | 48        | 1.06%   |
| Positivo              | 32        | 0.71%   |
| Medion                | 29        | 0.64%   |
| Foxconn               | 27        | 0.6%    |
| Pegatron              | 25        | 0.55%   |
| Packard Bell          | 25        | 0.55%   |
| Biostar               | 25        | 0.55%   |
| Unknown               | 20        | 0.44%   |
| ECS                   | 17        | 0.38%   |
| AZW                   | 14        | 0.31%   |
| Fujitsu Siemens       | 13        | 0.29%   |
| HUAWEI                | 11        | 0.24%   |
| Alienware             | 11        | 0.24%   |
| TUXEDO                | 10        | 0.22%   |
| eMachines             | 10        | 0.22%   |
| BESSTAR Tech          | 10        | 0.22%   |
| Philco                | 9         | 0.2%    |
| Shuttle               | 8         | 0.18%   |
| LG Electronics        | 8         | 0.18%   |
| Chuwi                 | 8         | 0.18%   |
| Supermicro            | 7         | 0.15%   |
| Notebook              | 7         | 0.15%   |
| Compaq                | 7         | 0.15%   |
| Microsoft             | 6         | 0.13%   |
| Gateway               | 6         | 0.13%   |
| Positivo Bahia - VAIO | 4         | 0.09%   |
| PCWare                | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Latitude 3120             | 48        | 1.06%   |
| ASUS All Series                | 44        | 0.97%   |
| Unknown                        | 35        | 0.77%   |
| Dell Latitude 3190 2-in-1      | 34        | 0.75%   |
| Dell Latitude 3310             | 29        | 0.64%   |
| Gigabyte H410M H V3            | 27        | 0.6%    |
| HP Notebook                    | 23        | 0.51%   |
| ASUS SABERTOOTH Z77            | 19        | 0.42%   |
| Dell OptiPlex 7010             | 18        | 0.4%    |
| ASUS UX31E                     | 18        | 0.4%    |
| Lenovo IdeaPad 1 14ADA05 82GW  | 11        | 0.24%   |
| Intel H61                      | 10        | 0.22%   |
| HP Pavilion g6                 | 10        | 0.22%   |
| HP Pavilion dv6                | 10        | 0.22%   |
| Dell OptiPlex 780              | 10        | 0.22%   |
| Sony VGN-FZ31Z                 | 9         | 0.2%    |
| MSI MS-7C91                    | 9         | 0.2%    |
| Gigabyte B450M DS3H            | 9         | 0.2%    |
| ASUS PRIME B450M-A II          | 9         | 0.2%    |
| Lenovo IdeaPad S145-15AST 81N3 | 8         | 0.18%   |
| HP ProDesk 600 G1 SFF          | 8         | 0.18%   |
| Dell OptiPlex 9020             | 8         | 0.18%   |
| Dell OptiPlex 790              | 8         | 0.18%   |
| Dell OptiPlex 380              | 8         | 0.18%   |
| Dell OptiPlex 3020             | 8         | 0.18%   |
| Dell Latitude 3300             | 8         | 0.18%   |
| Positivo Mobile                | 7         | 0.15%   |
| HP 15                          | 7         | 0.15%   |
| Dell XPS 15 9530               | 7         | 0.15%   |
| Dell Latitude E7450            | 7         | 0.15%   |
| Dell Latitude E7240            | 7         | 0.15%   |
| Dell Latitude E6420            | 7         | 0.15%   |
| Acer Aspire A515-51G           | 7         | 0.15%   |
| MSI MS-7C37                    | 6         | 0.13%   |
| MSI MS-7C02                    | 6         | 0.13%   |
| MSI MS-7B79                    | 6         | 0.13%   |
| MSI MS-7A38                    | 6         | 0.13%   |
| MSI MS-7721                    | 6         | 0.13%   |
| HP Pavilion 15                 | 6         | 0.13%   |
| HP Laptop 15-da0xxx            | 6         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 282       | 6.23%   |
| Acer Aspire           | 201       | 4.44%   |
| Lenovo ThinkPad       | 172       | 3.8%    |
| Lenovo IdeaPad        | 137       | 3.02%   |
| Dell OptiPlex         | 116       | 2.56%   |
| HP Pavilion           | 105       | 2.32%   |
| HP Compaq             | 89        | 1.97%   |
| Toshiba Satellite     | 87        | 1.92%   |
| ASUS PRIME            | 86        | 1.9%    |
| Dell Inspiron         | 84        | 1.85%   |
| Lenovo ThinkCentre    | 62        | 1.37%   |
| HP Laptop             | 62        | 1.37%   |
| HP ProBook            | 54        | 1.19%   |
| ASUS All              | 44        | 0.97%   |
| ASUS VivoBook         | 43        | 0.95%   |
| ASUS TUF              | 41        | 0.91%   |
| ASUS ROG              | 37        | 0.82%   |
| Unknown               | 35        | 0.77%   |
| HP EliteDesk          | 33        | 0.73%   |
| Dell Precision        | 33        | 0.73%   |
| HP EliteBook          | 32        | 0.71%   |
| Gigabyte H410M        | 31        | 0.68%   |
| Dell XPS              | 29        | 0.64%   |
| Dell Vostro           | 29        | 0.64%   |
| Fujitsu LIFEBOOK      | 28        | 0.62%   |
| HP ProDesk            | 27        | 0.6%    |
| Fujitsu ESPRIMO       | 27        | 0.6%    |
| ASUS SABERTOOTH       | 25        | 0.55%   |
| HP Notebook           | 23        | 0.51%   |
| Lenovo IdeaCentre     | 21        | 0.46%   |
| Acer Nitro            | 20        | 0.44%   |
| ASUS M5A78L-M         | 19        | 0.42%   |
| Gigabyte B450M        | 18        | 0.4%    |
| ASUS UX31E            | 18        | 0.4%    |
| Packard Bell EasyNote | 17        | 0.38%   |
| Lenovo Yoga           | 14        | 0.31%   |
| Acer Veriton          | 14        | 0.31%   |
| Acer Swift            | 13        | 0.29%   |
| HP 250                | 12        | 0.26%   |
| Acer TravelMate       | 12        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 462       | 10.2%   |
| 2011    | 423       | 9.34%   |
| 2013    | 369       | 8.15%   |
| 2019    | 342       | 7.55%   |
| 2021    | 341       | 7.53%   |
| 2020    | 327       | 7.22%   |
| 2018    | 322       | 7.11%   |
| 2014    | 312       | 6.89%   |
| 2010    | 290       | 6.4%    |
| 2016    | 231       | 5.1%    |
| 2015    | 230       | 5.08%   |
| 2017    | 218       | 4.81%   |
| 2009    | 210       | 4.64%   |
| 2008    | 207       | 4.57%   |
| 2007    | 133       | 2.94%   |
| 2006    | 62        | 1.37%   |
| 2022    | 38        | 0.84%   |
| 2005    | 6         | 0.13%   |
| Unknown | 4         | 0.09%   |
| 2023    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2126      | 46.94%  |
| Desktop     | 2093      | 46.21%  |
| Convertible | 125       | 2.76%   |
| All in one  | 76        | 1.68%   |
| Mini pc     | 72        | 1.59%   |
| Server      | 20        | 0.44%   |
| Tablet      | 17        | 0.38%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4529      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4523      | 99.87%  |
| Yes  | 6         | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1288      | 28.37%  |
| 3.01-4.0        | 1170      | 25.77%  |
| 8.01-16.0       | 801       | 17.64%  |
| 16.01-24.0      | 674       | 14.85%  |
| 32.01-64.0      | 264       | 5.81%   |
| 1.01-2.0        | 153       | 3.37%   |
| 2.01-3.0        | 60        | 1.32%   |
| 64.01-256.0     | 59        | 1.3%    |
| 24.01-32.0      | 58        | 1.28%   |
| 0.51-1.0        | 10        | 0.22%   |
| More than 256.0 | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 3347      | 73.13%  |
| 0.51-1.0  | 757       | 16.54%  |
| 2.01-3.0  | 340       | 7.43%   |
| 0.01-0.5  | 72        | 1.57%   |
| 3.01-4.0  | 34        | 0.74%   |
| 4.01-8.0  | 16        | 0.35%   |
| 8.01-16.0 | 11        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2679      | 58.87%  |
| 2      | 1106      | 24.3%   |
| 3      | 352       | 7.73%   |
| 4      | 196       | 4.31%   |
| 0      | 82        | 1.8%    |
| 5      | 74        | 1.63%   |
| 6      | 28        | 0.62%   |
| 7      | 13        | 0.29%   |
| 8      | 7         | 0.15%   |
| 9      | 4         | 0.09%   |
| 12     | 3         | 0.07%   |
| 11     | 3         | 0.07%   |
| 25     | 1         | 0.02%   |
| 15     | 1         | 0.02%   |
| 13     | 1         | 0.02%   |
| 10     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2274      | 50.13%  |
| No        | 2262      | 49.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4079      | 90.06%  |
| No        | 450       | 9.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3121      | 68.84%  |
| No        | 1413      | 31.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2283      | 50.35%  |
| No        | 2251      | 49.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 543       | 11.97%  |
| USA         | 520       | 11.46%  |
| France      | 308       | 6.79%   |
| Brazil      | 294       | 6.48%   |
| Russia      | 285       | 6.28%   |
| Poland      | 229       | 5.05%   |
| Netherlands | 196       | 4.32%   |
| Italy       | 192       | 4.23%   |
| UK          | 144       | 3.17%   |
| Spain       | 122       | 2.69%   |
| Canada      | 118       | 2.6%    |
| Mexico      | 85        | 1.87%   |
| India       | 77        | 1.7%    |
| Australia   | 74        | 1.63%   |
| Czechia     | 70        | 1.54%   |
| Japan       | 60        | 1.32%   |
| Indonesia   | 59        | 1.3%    |
| Argentina   | 56        | 1.23%   |
| Austria     | 54        | 1.19%   |
| Portugal    | 50        | 1.1%    |
| Ukraine     | 47        | 1.04%   |
| Romania     | 44        | 0.97%   |
| Turkey      | 43        | 0.95%   |
| Switzerland | 43        | 0.95%   |
| Sweden      | 40        | 0.88%   |
| Hungary     | 39        | 0.86%   |
| Belgium     | 38        | 0.84%   |
| Colombia    | 37        | 0.82%   |
| Slovakia    | 31        | 0.68%   |
| Serbia      | 28        | 0.62%   |
| Finland     | 25        | 0.55%   |
| China       | 23        | 0.51%   |
| Chile       | 23        | 0.51%   |
| Greece      | 22        | 0.49%   |
| Egypt       | 21        | 0.46%   |
| Bulgaria    | 21        | 0.46%   |
| Peru        | 19        | 0.42%   |
| Venezuela   | 18        | 0.4%    |
| Norway      | 18        | 0.4%    |
| Israel      | 17        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Schagen        | 137       | 2.98%   |
| Moscow         | 57        | 1.24%   |
| Warsaw         | 38        | 0.83%   |
| Berlin         | 38        | 0.83%   |
| Sao Paulo      | 35        | 0.76%   |
| Paris          | 35        | 0.76%   |
| Prague         | 29        | 0.63%   |
| Vienna         | 27        | 0.59%   |
| Milan          | 25        | 0.54%   |
| Munich         | 23        | 0.5%    |
| Gonikoppal     | 22        | 0.48%   |
| Mexico City    | 21        | 0.46%   |
| Sydney         | 20        | 0.44%   |
| St Petersburg  | 18        | 0.39%   |
| Istanbul       | 18        | 0.39%   |
| Strzyzow       | 17        | 0.37%   |
| Jakarta        | 17        | 0.37%   |
| Belgrade       | 17        | 0.37%   |
| Rio de Janeiro | 16        | 0.35%   |
| Madrid         | 16        | 0.35%   |
| Hamburg        | 16        | 0.35%   |
| Cairo          | 14        | 0.3%    |
| Rome           | 13        | 0.28%   |
| Lima           | 13        | 0.28%   |
| Krakow         | 13        | 0.28%   |
| Bengaluru      | 13        | 0.28%   |
| Poznan         | 12        | 0.26%   |
| Brisbane       | 12        | 0.26%   |
| Bratislava     | 12        | 0.26%   |
| Helsinki       | 11        | 0.24%   |
| Cascais        | 11        | 0.24%   |
| Barcelona      | 11        | 0.24%   |
| Zagreb         | 10        | 0.22%   |
| Wroclaw        | 10        | 0.22%   |
| Montreal       | 10        | 0.22%   |
| Montevideo     | 10        | 0.22%   |
| Kyiv           | 10        | 0.22%   |
| Jeddah         | 10        | 0.22%   |
| Gdansk         | 10        | 0.22%   |
| Curitiba       | 10        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1113      | 1372   | 17.01%  |
| Seagate             | 970       | 1216   | 14.82%  |
| Samsung Electronics | 841       | 1034   | 12.85%  |
| Toshiba             | 453       | 492    | 6.92%   |
| Kingston            | 380       | 413    | 5.81%   |
| Crucial             | 288       | 332    | 4.4%    |
| SanDisk             | 282       | 316    | 4.31%   |
| Hitachi             | 265       | 284    | 4.05%   |
| Unknown             | 174       | 189    | 2.66%   |
| A-DATA Technology   | 156       | 166    | 2.38%   |
| SK hynix            | 141       | 146    | 2.15%   |
| HGST                | 123       | 139    | 1.88%   |
| China               | 75        | 82     | 1.15%   |
| Intel               | 72        | 78     | 1.1%    |
| Micron Technology   | 64        | 66     | 0.98%   |
| GOODRAM             | 50        | 52     | 0.76%   |
| PNY                 | 44        | 53     | 0.67%   |
| SPCC                | 43        | 47     | 0.66%   |
| Intenso             | 42        | 43     | 0.64%   |
| Unknown             | 41        | 43     | 0.63%   |
| Patriot             | 38        | 40     | 0.58%   |
| Maxtor              | 36        | 41     | 0.55%   |
| LITEON              | 36        | 36     | 0.55%   |
| Apple               | 36        | 38     | 0.55%   |
| KIOXIA              | 35        | 35     | 0.53%   |
| Apacer              | 34        | 35     | 0.52%   |
| ASMT                | 33        | 40     | 0.5%    |
| JMicron Technology  | 32        | 33     | 0.49%   |
| Gigabyte Technology | 31        | 31     | 0.47%   |
| Fujitsu             | 29        | 30     | 0.44%   |
| Netac               | 26        | 30     | 0.4%    |
| Corsair             | 25        | 27     | 0.38%   |
| SSSTC               | 24        | 24     | 0.37%   |
| Phison              | 24        | 27     | 0.37%   |
| OCZ                 | 24        | 24     | 0.37%   |
| Transcend           | 23        | 25     | 0.35%   |
| Hewlett-Packard     | 23        | 31     | 0.35%   |
| Team                | 22        | 22     | 0.34%   |
| Silicon Motion      | 18        | 21     | 0.28%   |
| KingSpec            | 18        | 18     | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 92        | 1.29%   |
| Seagate ST500DM002-1BD142 500GB     | 74        | 1.03%   |
| Seagate ST1000DM010-2EP102 1TB      | 61        | 0.85%   |
| Kingston SA400S37480G 480GB SSD     | 48        | 0.67%   |
| Samsung SSD 860 EVO 500GB           | 47        | 0.66%   |
| Toshiba MQ01ABF050 500GB            | 44        | 0.62%   |
| Kingston SA400S37120G 120GB SSD     | 44        | 0.62%   |
| Toshiba MQ01ABD100 1TB              | 43        | 0.6%    |
| Samsung SSD 860 EVO 250GB           | 43        | 0.6%    |
| Samsung SSD 850 EVO 250GB           | 43        | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB            | 42        | 0.59%   |
| Unknown SD/MMC/MS PRO 128GB         | 41        | 0.57%   |
| Crucial CT500MX500SSD1 500GB        | 41        | 0.57%   |
| Unknown                             | 41        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 40        | 0.56%   |
| Crucial CT240BX500SSD1 240GB        | 39        | 0.55%   |
| Toshiba DT01ACA100 1TB              | 37        | 0.52%   |
| Seagate ST2000DM008-2FR102 2TB      | 34        | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 33        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB     | 33        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB      | 32        | 0.45%   |
| Toshiba MQ04ABF100 1TB              | 31        | 0.43%   |
| Kingston SV300S37A120G 120GB SSD    | 31        | 0.43%   |
| Samsung SSD 850 EVO 500GB           | 29        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB         | 29        | 0.41%   |
| Toshiba DT01ACA050 500GB            | 28        | 0.39%   |
| Crucial CT480BX500SSD1 480GB        | 28        | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB      | 26        | 0.36%   |
| Seagate ST9500325AS 500GB           | 25        | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB      | 25        | 0.35%   |
| HGST HTS545050A7E680 500GB          | 25        | 0.35%   |
| SanDisk SSD PLUS 240GB              | 24        | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB        | 23        | 0.32%   |
| SK hynix BC711 NVMe 128GB           | 22        | 0.31%   |
| Seagate ST3500418AS 500GB           | 22        | 0.31%   |
| Samsung HD502HJ 500GB               | 22        | 0.31%   |
| HGST HTS721010A9E630 1TB            | 22        | 0.31%   |
| A-DATA SU750 256GB SSD              | 22        | 0.31%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 21        | 0.29%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 20        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 956       | 1192   | 31.57%  |
| WDC                 | 901       | 1083   | 29.76%  |
| Toshiba             | 401       | 435    | 13.24%  |
| Hitachi             | 265       | 284    | 8.75%   |
| Samsung Electronics | 176       | 205    | 5.81%   |
| HGST                | 123       | 139    | 4.06%   |
| Unknown             | 42        | 42     | 1.39%   |
| Maxtor              | 34        | 39     | 1.12%   |
| Fujitsu             | 29        | 30     | 0.96%   |
| JMicron Technology  | 21        | 22     | 0.69%   |
| Apple               | 17        | 18     | 0.56%   |
| ASMT                | 15        | 21     | 0.5%    |
| USB3.0              | 6         | 6      | 0.2%    |
| Hewlett-Packard     | 5         | 10     | 0.17%   |
| WD MediaMax         | 4         | 5      | 0.13%   |
| Intenso             | 4         | 4      | 0.13%   |
| ASMedia             | 4         | 4      | 0.13%   |
| Magnetic Data       | 3         | 3      | 0.1%    |
| IBM/Hitachi         | 3         | 4      | 0.1%    |
| Initio              | 2         | 2      | 0.07%   |
| HPE                 | 2         | 3      | 0.07%   |
| External            | 2         | 2      | 0.07%   |
| Unknown             | 2         | 2      | 0.07%   |
| SSK                 | 1         | 1      | 0.03%   |
| RSH-339             | 1         | 1      | 0.03%   |
| QUANTUM             | 1         | 1      | 0.03%   |
| QC-FT-D             | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 461       | 533    | 18.74%  |
| Kingston            | 315       | 339    | 12.8%   |
| SanDisk             | 248       | 276    | 10.08%  |
| Crucial             | 246       | 281    | 10%     |
| WDC                 | 139       | 156    | 5.65%   |
| A-DATA Technology   | 124       | 126    | 5.04%   |
| China               | 74        | 81     | 3.01%   |
| GOODRAM             | 48        | 48     | 1.95%   |
| Micron Technology   | 46        | 46     | 1.87%   |
| SK hynix            | 39        | 40     | 1.59%   |
| PNY                 | 38        | 44     | 1.54%   |
| Toshiba             | 37        | 39     | 1.5%    |
| Patriot             | 33        | 35     | 1.34%   |
| LITEON              | 33        | 33     | 1.34%   |
| SPCC                | 32        | 35     | 1.3%    |
| Intel               | 32        | 34     | 1.3%    |
| Intenso             | 31        | 32     | 1.26%   |
| Apacer              | 31        | 31     | 1.26%   |
| OCZ                 | 24        | 24     | 0.98%   |
| Unknown             | 23        | 24     | 0.93%   |
| Netac               | 22        | 26     | 0.89%   |
| Transcend           | 21        | 22     | 0.85%   |
| Team                | 21        | 21     | 0.85%   |
| Gigabyte Technology | 19        | 19     | 0.77%   |
| KingSpec            | 18        | 18     | 0.73%   |
| Apple               | 17        | 17     | 0.69%   |
| LITEONIT            | 14        | 15     | 0.57%   |
| ASMT                | 14        | 15     | 0.57%   |
| Hewlett-Packard     | 13        | 15     | 0.53%   |
| Corsair             | 12        | 13     | 0.49%   |
| Lexar               | 11        | 11     | 0.45%   |
| KIOXIA-EXCERIA      | 9         | 9      | 0.37%   |
| Leven               | 8         | 9      | 0.33%   |
| KingFast            | 8         | 8      | 0.33%   |
| Seagate             | 7         | 7      | 0.28%   |
| KingDian            | 7         | 7      | 0.28%   |
| TO Exter            | 6         | 6      | 0.24%   |
| TCSUNBOW            | 5         | 5      | 0.2%    |
| Emtec               | 5         | 5      | 0.2%    |
| Colorful            | 5         | 6      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2558      | 3566   | 44.2%   |
| SSD     | 2110      | 2678   | 36.46%  |
| NVMe    | 895       | 1057   | 15.47%  |
| MMC     | 154       | 164    | 2.66%   |
| Unknown | 70        | 84     | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3873      | 5974   | 74.17%  |
| NVMe | 888       | 1039   | 17%     |
| SAS  | 307       | 372    | 5.88%   |
| MMC  | 154       | 164    | 2.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3078      | 4016   | 63.74%  |
| 0.51-1.0   | 1251      | 1572   | 25.91%  |
| 1.01-2.0   | 305       | 389    | 6.32%   |
| 2.01-3.0   | 62        | 79     | 1.28%   |
| 3.01-4.0   | 60        | 89     | 1.24%   |
| 4.01-10.0  | 56        | 82     | 1.16%   |
| 10.01-20.0 | 17        | 17     | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2521      | 54.79%  |
| 101-250        | 651       | 14.15%  |
| 251-500        | 386       | 8.39%   |
| Unknown        | 361       | 7.85%   |
| 501-1000       | 207       | 4.5%    |
| 51-100         | 192       | 4.17%   |
| 21-50          | 174       | 3.78%   |
| 1001-2000      | 70        | 1.52%   |
| More than 3000 | 20        | 0.43%   |
| 2001-3000      | 19        | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3803      | 83%     |
| Unknown        | 361       | 7.88%   |
| 101-250        | 108       | 2.36%   |
| 21-50          | 100       | 2.18%   |
| 51-100         | 90        | 1.96%   |
| 251-500        | 55        | 1.2%    |
| 501-1000       | 36        | 0.79%   |
| 1001-2000      | 19        | 0.41%   |
| More than 3000 | 7         | 0.15%   |
| 2001-3000      | 3         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 33        | 34     | 2.4%    |
| HGST HTS545050A7E680 500GB          | 20        | 20     | 1.45%   |
| Seagate ST9500325AS 500GB           | 18        | 18     | 1.31%   |
| SanDisk SSD U100 256GB              | 18        | 18     | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 17        | 17     | 1.24%   |
| HGST HTS541010A9E680 1TB            | 13        | 14     | 0.95%   |
| Toshiba MQ01ABF050 500GB            | 12        | 12     | 0.87%   |
| Seagate ST9320325AS 320GB           | 11        | 11     | 0.8%    |
| Kingston SV300S37A120G 120GB SSD    | 11        | 11     | 0.8%    |
| Samsung Electronics HD322HJ 320GB   | 10        | 11     | 0.73%   |
| Hitachi HTS543232A7A384 320GB       | 10        | 11     | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB      | 9         | 10     | 0.65%   |
| Seagate ST1000DM003-9YN162 1TB      | 9         | 9      | 0.65%   |
| HGST HTS721010A9E630 1TB            | 9         | 11     | 0.65%   |
| Crucial CT240M500SSD1 240GB         | 9         | 9      | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 9      | 0.58%   |
| Toshiba MQ01ABD100 1TB              | 8         | 8      | 0.58%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 8      | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 8      | 0.58%   |
| Seagate ST3500418AS 500GB           | 8         | 8      | 0.58%   |
| Seagate ST3500413AS 500GB           | 8         | 8      | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 8      | 0.58%   |
| Toshiba MQ01ABD050 500GB            | 7         | 7      | 0.51%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 7      | 0.51%   |
| Seagate ST31000524AS 1TB            | 7         | 7      | 0.51%   |
| SanDisk SSD PLUS 240GB              | 7         | 7      | 0.51%   |
| Samsung Electronics HD502HJ 500GB   | 7         | 7      | 0.51%   |
| Hitachi HTS725032A7E630 320GB       | 7         | 7      | 0.51%   |
| HGST HTS545050A7E380 500GB          | 7         | 7      | 0.51%   |
| WDC WD10EALX-009BA0 1TB             | 6         | 6      | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB      | 6         | 6      | 0.44%   |
| SanDisk SSD PLUS 480GB              | 6         | 6      | 0.44%   |
| Hitachi HTS545050B9A300 500GB       | 6         | 6      | 0.44%   |
| Hitachi HTS545050A7E380 500GB       | 6         | 6      | 0.44%   |
| HGST HTS725050A7E630 500GB          | 6         | 6      | 0.44%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5         | 5      | 0.36%   |
| WDC WD5000AAKS-00V1A0 500GB         | 5         | 5      | 0.36%   |
| WDC WD5000AADS-00S9B0 500GB         | 5         | 5      | 0.36%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 5         | 5      | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5         | 5      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 358       | 391    | 26.78%  |
| WDC                 | 280       | 308    | 20.94%  |
| Hitachi             | 141       | 148    | 10.55%  |
| Toshiba             | 116       | 118    | 8.68%   |
| Samsung Electronics | 105       | 116    | 7.85%   |
| HGST                | 68        | 72     | 5.09%   |
| SanDisk             | 47        | 47     | 3.52%   |
| Kingston            | 29        | 30     | 2.17%   |
| Crucial             | 25        | 26     | 1.87%   |
| Maxtor              | 23        | 24     | 1.72%   |
| A-DATA Technology   | 17        | 18     | 1.27%   |
| Micron Technology   | 12        | 12     | 0.9%    |
| Intel               | 12        | 12     | 0.9%    |
| Fujitsu             | 12        | 12     | 0.9%    |
| SK hynix            | 9         | 10     | 0.67%   |
| China               | 9         | 9      | 0.67%   |
| Apple               | 7         | 7      | 0.52%   |
| GOODRAM             | 5         | 5      | 0.37%   |
| ASMT                | 5         | 6      | 0.37%   |
| OCZ                 | 4         | 4      | 0.3%    |
| LITEON              | 4         | 4      | 0.3%    |
| IBM/Hitachi         | 3         | 4      | 0.22%   |
| Hewlett-Packard     | 3         | 3      | 0.22%   |
| Corsair             | 3         | 4      | 0.22%   |
| Transcend           | 2         | 2      | 0.15%   |
| SPCC                | 2         | 2      | 0.15%   |
| PNY                 | 2         | 3      | 0.15%   |
| Patriot             | 2         | 2      | 0.15%   |
| KingSpec            | 2         | 2      | 0.15%   |
| HP Phison           | 2         | 2      | 0.15%   |
| ASMedia             | 2         | 2      | 0.15%   |
| Unknown             | 2         | 2      | 0.15%   |
| WDC WDS2            | 1         | 1      | 0.07%   |
| WD MediaMax         | 1         | 1      | 0.07%   |
| Vaseky              | 1         | 1      | 0.07%   |
| USB3.0              | 1         | 1      | 0.07%   |
| TO Exter            | 1         | 1      | 0.07%   |
| TEXTORM             | 1         | 1      | 0.07%   |
| TCSUNBOW            | 1         | 1      | 0.07%   |
| RSH-339             | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 358       | 391    | 33%     |
| WDC                 | 267       | 292    | 24.61%  |
| Hitachi             | 141       | 148    | 13%     |
| Toshiba             | 113       | 115    | 10.41%  |
| Samsung Electronics | 85        | 94     | 7.83%   |
| HGST                | 68        | 72     | 6.27%   |
| Maxtor              | 23        | 24     | 2.12%   |
| Fujitsu             | 12        | 12     | 1.11%   |
| IBM/Hitachi         | 3         | 4      | 0.28%   |
| Apple               | 3         | 3      | 0.28%   |
| ASMedia             | 2         | 2      | 0.18%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| USB3.0              | 1         | 1      | 0.09%   |
| RSH-339             | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 1      | 0.09%   |
| Initio              | 1         | 1      | 0.09%   |
| HPE                 | 1         | 1      | 0.09%   |
| Hewlett-Packard     | 1         | 1      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| ASMT                | 1         | 2      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1000      | 1168   | 79.94%  |
| SSD     | 236       | 247    | 18.86%  |
| NVMe    | 14        | 16     | 1.12%   |
| Unknown | 1         | 1      | 0.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3         | 3      | 7.14%   |
| Apple HDD HTS541010A9E662 1TB                    | 3         | 3      | 7.14%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 4.76%   |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 4.76%   |
| WDC WD5000BEVT-22ZAT0 500GB                      | 1         | 1      | 2.38%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 2.38%   |
| WDC WD3200BUCT-63TWBY0 320GB                     | 1         | 1      | 2.38%   |
| WDC WD3200BEKT-60KA9T0 320GB                     | 1         | 1      | 2.38%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1         | 1      | 2.38%   |
| WDC WD2500BEVT-60ZCT1 250GB                      | 1         | 1      | 2.38%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 2.38%   |
| WDC WD1600YS-23SHB0 160GB                        | 1         | 1      | 2.38%   |
| WDC WD1600BEVT-75A23T0 160GB                     | 1         | 1      | 2.38%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 2.38%   |
| Toshiba MK3265GSXN 320GB                         | 1         | 1      | 2.38%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 1      | 2.38%   |
| Toshiba MK3256GSY 320GB                          | 1         | 1      | 2.38%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.38%   |
| Seagate STM31000528AS 1TB                        | 1         | 1      | 2.38%   |
| Seagate ST980811AS 80GB                          | 1         | 1      | 2.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.38%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.38%   |
| Seagate ST3160215A 160GB                         | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 2.38%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 2.38%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.38%   |
| Samsung Electronics HD502IJ 500GB                | 1         | 1      | 2.38%   |
| Samsung Electronics HD103UJ 1TB                  | 1         | 1      | 2.38%   |
| Intel SSDSA2BW160G3 160GB                        | 1         | 1      | 2.38%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 2.38%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 2.38%   |
| Hitachi HDS721010DLE630 1TB                      | 1         | 1      | 2.38%   |
| Hitachi HDP725050GLA360 500GB                    | 1         | 1      | 2.38%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1         | 1      | 2.38%   |
| Apple HDD HTS545050A7E362 500GB                  | 1         | 1      | 2.38%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 28.57%  |
| Samsung Electronics | 8         | 8      | 19.05%  |
| Toshiba             | 7         | 7      | 16.67%  |
| Seagate             | 5         | 5      | 11.9%   |
| Hitachi             | 4         | 4      | 9.52%   |
| Apple               | 4         | 4      | 9.52%   |
| Intel               | 1         | 1      | 2.38%   |
| GOODRAM             | 1         | 1      | 2.38%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3554      | 5582   | 67.84%  |
| Malfunc  | 1223      | 1432   | 23.34%  |
| Detected | 421       | 493    | 8.04%   |
| Failed   | 41        | 42     | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3184      | 58.21%  |
| AMD                              | 964       | 17.62%  |
| Samsung Electronics              | 270       | 4.94%   |
| SanDisk                          | 140       | 2.56%   |
| Nvidia                           | 97        | 1.77%   |
| SK hynix                         | 94        | 1.72%   |
| JMicron Technology               | 90        | 1.65%   |
| ASMedia Technology               | 82        | 1.5%    |
| Marvell Technology Group         | 71        | 1.3%    |
| Kingston Technology Company      | 71        | 1.3%    |
| Phison Electronics               | 66        | 1.21%   |
| Silicon Motion                   | 46        | 0.84%   |
| Micron/Crucial Technology        | 45        | 0.82%   |
| KIOXIA                           | 34        | 0.62%   |
| ADATA Technology                 | 30        | 0.55%   |
| Solid State Storage Technology   | 24        | 0.44%   |
| VIA Technologies                 | 22        | 0.4%    |
| Micron Technology                | 22        | 0.4%    |
| Toshiba America Info Systems     | 20        | 0.37%   |
| Realtek Semiconductor            | 19        | 0.35%   |
| Broadcom / LSI                   | 11        | 0.2%    |
| Union Memory (Shenzhen)          | 9         | 0.16%   |
| Seagate Technology               | 8         | 0.15%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.11%   |
| Lite-On Technology               | 6         | 0.11%   |
| Integrated Technology Express    | 6         | 0.11%   |
| Silicon Integrated Systems [SiS] | 5         | 0.09%   |
| LSI Logic / Symbios Logic        | 4         | 0.07%   |
| Adaptec                          | 4         | 0.07%   |
| Silicon Image                    | 3         | 0.05%   |
| Shenzhen Longsys Electronics     | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Promise Technology               | 2         | 0.04%   |
| Hewlett-Packard                  | 2         | 0.04%   |
| Apple                            | 2         | 0.04%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 564       | 8.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 250       | 3.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 243       | 3.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 192       | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 166       | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 154       | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 146       | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 136       | 2.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 132       | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 132       | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 129       | 1.99%   |
| AMD 400 Series Chipset SATA Controller                                                  | 117       | 1.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 116       | 1.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 111       | 1.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 105       | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 102       | 1.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 91        | 1.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 83        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 83        | 1.28%   |
| Samsung NVMe SSD Controller 980                                                         | 81        | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 81        | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 78        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 78        | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                                  | 77        | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 76        | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 75        | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 71        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 71        | 1.1%    |
| Intel SATA Controller [RAID mode]                                                       | 70        | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 70        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 69        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 69        | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 66        | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 66        | 1.02%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 60        | 0.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 43        | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 41        | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 41        | 0.63%   |
| Nvidia MCP61 SATA Controller                                                            | 40        | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 40        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3520      | 63.05%  |
| NVMe | 884       | 15.83%  |
| IDE  | 884       | 15.83%  |
| RAID | 279       | 5%      |
| SCSI | 9         | 0.16%   |
| SAS  | 7         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3400      | 75.07%  |
| AMD    | 1129      | 24.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 54        | 1.19%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 41        | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 0.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 32        | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 31        | 0.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 31        | 0.68%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 30        | 0.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 28        | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 27        | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.6%    |
| AMD Ryzen 5 3600 6-Core Processor             | 27        | 0.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 25        | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 24        | 0.53%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 24        | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 23        | 0.51%   |
| AMD FX-8350 Eight-Core Processor              | 23        | 0.51%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 22        | 0.49%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 22        | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.46%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 21        | 0.46%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 21        | 0.46%   |
| AMD 3020e with Radeon Graphics                | 21        | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 20        | 0.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 20        | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 20        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 19        | 0.42%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 19        | 0.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 19        | 0.42%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 19        | 0.42%   |
| AMD FX-6300 Six-Core Processor                | 19        | 0.42%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 18        | 0.4%    |
| Intel Core i5-4590 CPU @ 3.30GHz              | 18        | 0.4%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 18        | 0.4%    |
| Intel Core i3-2100 CPU @ 3.10GHz              | 18        | 0.4%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 18        | 0.4%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 17        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1064      | 23.48%  |
| Intel Core i3           | 497       | 10.97%  |
| Intel Core i7           | 470       | 10.37%  |
| Intel Celeron           | 328       | 7.24%   |
| Intel Core 2 Duo        | 256       | 5.65%   |
| AMD Ryzen 5             | 203       | 4.48%   |
| Intel Pentium           | 177       | 3.91%   |
| AMD Ryzen 7             | 143       | 3.16%   |
| Other                   | 129       | 2.85%   |
| Intel Pentium Silver    | 102       | 2.25%   |
| AMD FX                  | 97        | 2.14%   |
| Intel Xeon              | 84        | 1.85%   |
| Intel Pentium Dual-Core | 84        | 1.85%   |
| AMD Ryzen 3             | 66        | 1.46%   |
| Intel Core 2 Quad       | 65        | 1.43%   |
| AMD A8                  | 52        | 1.15%   |
| AMD A6                  | 51        | 1.13%   |
| AMD A4                  | 44        | 0.97%   |
| AMD A10                 | 40        | 0.88%   |
| Intel Core 2            | 35        | 0.77%   |
| Intel Atom              | 33        | 0.73%   |
| AMD Athlon              | 33        | 0.73%   |
| Intel Pentium Dual      | 32        | 0.71%   |
| AMD E1                  | 32        | 0.71%   |
| AMD Phenom II X4        | 31        | 0.68%   |
| AMD Ryzen 9             | 29        | 0.64%   |
| AMD Athlon II X2        | 29        | 0.64%   |
| AMD E                   | 28        | 0.62%   |
| AMD Athlon 64 X2        | 24        | 0.53%   |
| Intel Core i9           | 18        | 0.4%    |
| AMD E2                  | 16        | 0.35%   |
| Intel Genuine           | 15        | 0.33%   |
| AMD Ryzen 5 PRO         | 13        | 0.29%   |
| Intel Pentium Gold      | 12        | 0.26%   |
| AMD Athlon II X4        | 12        | 0.26%   |
| AMD Sempron             | 11        | 0.24%   |
| AMD C-60                | 11        | 0.24%   |
| AMD Athlon X4           | 11        | 0.24%   |
| AMD Phenom              | 10        | 0.22%   |
| AMD Athlon II X3        | 10        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2340      | 51.63%  |
| 4      | 1416      | 31.24%  |
| 6      | 369       | 8.14%   |
| 8      | 202       | 4.46%   |
| 1      | 102       | 2.25%   |
| 3      | 42        | 0.93%   |
| 12     | 25        | 0.55%   |
| 16     | 19        | 0.42%   |
| 10     | 10        | 0.22%   |
| 14     | 3         | 0.07%   |
| 128    | 1         | 0.02%   |
| 44     | 1         | 0.02%   |
| 28     | 1         | 0.02%   |
| 20     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4507      | 99.51%  |
| 2      | 22        | 0.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2461      | 54.31%  |
| 1      | 2058      | 45.42%  |
| 8      | 9         | 0.2%    |
| 4      | 3         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4528      | 99.96%  |
| Unknown        | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 394       | 8.67%   |
| 0x306a9    | 376       | 8.28%   |
| 0x306c3    | 307       | 6.76%   |
| 0x1067a    | 283       | 6.23%   |
| Unknown    | 120       | 2.64%   |
| 0x20655    | 116       | 2.55%   |
| 0x906ea    | 108       | 2.38%   |
| 0x506e3    | 105       | 2.31%   |
| 0x406e3    | 92        | 2.03%   |
| 0x306d4    | 92        | 2.03%   |
| 0x40651    | 89        | 1.96%   |
| 0x806e9    | 85        | 1.87%   |
| 0x08108109 | 79        | 1.74%   |
| 0x6fd      | 76        | 1.67%   |
| 0x906c0    | 73        | 1.61%   |
| 0x906e9    | 72        | 1.59%   |
| 0x806ea    | 72        | 1.59%   |
| 0x706a8    | 70        | 1.54%   |
| 0x08701021 | 70        | 1.54%   |
| 0x30678    | 63        | 1.39%   |
| 0x806ec    | 61        | 1.34%   |
| 0x10676    | 58        | 1.28%   |
| 0xa0655    | 50        | 1.1%    |
| 0x6fb      | 49        | 1.08%   |
| 0x706a1    | 47        | 1.03%   |
| 0x0a50000c | 47        | 1.03%   |
| 0x06001119 | 46        | 1.01%   |
| 0x010000c8 | 46        | 1.01%   |
| 0x20652    | 42        | 0.92%   |
| 0xa0653    | 41        | 0.9%    |
| 0x506c9    | 39        | 0.86%   |
| 0x0800820d | 39        | 0.86%   |
| 0x406c4    | 35        | 0.77%   |
| 0x06006705 | 35        | 0.77%   |
| 0x806c1    | 34        | 0.75%   |
| 0x706e5    | 34        | 0.75%   |
| 0x106e5    | 34        | 0.75%   |
| 0x08600106 | 33        | 0.73%   |
| 0x06003106 | 33        | 0.73%   |
| 0x07030105 | 30        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 474       | 10.46%  |
| SandyBridge      | 412       | 9.09%   |
| Haswell          | 412       | 9.09%   |
| IvyBridge        | 390       | 8.61%   |
| Penryn           | 351       | 7.74%   |
| Skylake          | 206       | 4.55%   |
| Core             | 184       | 4.06%   |
| Westmere         | 171       | 3.77%   |
| Zen+             | 147       | 3.24%   |
| Zen 2            | 136       | 3%      |
| Silvermont       | 135       | 2.98%   |
| Piledriver       | 134       | 2.96%   |
| K10              | 127       | 2.8%    |
| Goldmont plus    | 117       | 2.58%   |
| CometLake        | 110       | 2.43%   |
| Zen 3            | 106       | 2.34%   |
| Broadwell        | 103       | 2.27%   |
| Zen              | 91        | 2.01%   |
| Tremont          | 73        | 1.61%   |
| Excavator        | 69        | 1.52%   |
| Bobcat           | 60        | 1.32%   |
| IceLake          | 59        | 1.3%    |
| Nehalem          | 50        | 1.1%    |
| K8 Hammer        | 50        | 1.1%    |
| Unknown          | 48        | 1.06%   |
| Puma             | 44        | 0.97%   |
| Steamroller      | 40        | 0.88%   |
| Goldmont         | 40        | 0.88%   |
| TigerLake        | 36        | 0.79%   |
| K10 Llano        | 31        | 0.68%   |
| Jaguar           | 31        | 0.68%   |
| Bonnell          | 28        | 0.62%   |
| Alderlake Hybrid | 19        | 0.42%   |
| NetBurst         | 18        | 0.4%    |
| Bulldozer        | 18        | 0.4%    |
| K8 & K10 hybrid  | 12        | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2538      | 50.68%  |
| Nvidia                           | 1232      | 24.6%   |
| AMD                              | 1215      | 24.26%  |
| Matrox Electronics Systems       | 8         | 0.16%   |
| ASPEED Technology                | 6         | 0.12%   |
| Silicon Integrated Systems [SiS] | 4         | 0.08%   |
| VIA Technologies                 | 3         | 0.06%   |
| Conexant Systems                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 323       | 6.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 206       | 4.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 134       | 2.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 120       | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 109       | 2.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 95        | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 89        | 1.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 87        | 1.69%   |
| Intel HD Graphics 620                                                                    | 81        | 1.58%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 80        | 1.56%   |
| Intel HD Graphics 5500                                                                   | 75        | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 74        | 1.44%   |
| Intel JasperLake [UHD Graphics]                                                          | 73        | 1.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 72        | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 71        | 1.38%   |
| Intel HD Graphics 530                                                                    | 70        | 1.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 62        | 1.21%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 59        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 59        | 1.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 58        | 1.13%   |
| Intel UHD Graphics 620                                                                   | 58        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 57        | 1.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 57        | 1.11%   |
| AMD Renoir                                                                               | 51        | 0.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 50        | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 49        | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 0.92%   |
| Intel HD Graphics 630                                                                    | 46        | 0.9%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 46        | 0.9%    |
| Nvidia GT218 [GeForce 210]                                                               | 44        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 43        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 42        | 0.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 38        | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 36        | 0.7%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 32        | 0.62%   |
| Intel HD Graphics 500                                                                    | 31        | 0.6%    |
| AMD Lucienne                                                                             | 31        | 0.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 30        | 0.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 28        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2086      | 46.01%  |
| 1 x AMD                  | 1056      | 23.29%  |
| 1 x Nvidia               | 871       | 19.21%  |
| Intel + Nvidia           | 331       | 7.3%    |
| Intel + AMD              | 77        | 1.7%    |
| 2 x AMD                  | 63        | 1.39%   |
| AMD + Nvidia             | 20        | 0.44%   |
| 2 x Nvidia               | 7         | 0.15%   |
| 1 x Matrox               | 6         | 0.13%   |
| 1 x ASPEED               | 5         | 0.11%   |
| 1 x SiS                  | 4         | 0.09%   |
| 1 x VIA                  | 3         | 0.07%   |
| 3 x AMD                  | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.02%   |
| Nvidia + Matrox          | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| Intel + Conexant Systems | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4415      | 97.44%  |
| Unknown     | 110       | 2.43%   |
| Proprietary | 6         | 0.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2241      | 49.44%  |
| 0.01-0.5   | 693       | 15.29%  |
| 1.01-2.0   | 589       | 12.99%  |
| 0.51-1.0   | 499       | 11.01%  |
| 3.01-4.0   | 225       | 4.96%   |
| 7.01-8.0   | 148       | 3.26%   |
| 5.01-6.0   | 77        | 1.7%    |
| 2.01-3.0   | 33        | 0.73%   |
| 8.01-16.0  | 23        | 0.51%   |
| 16.01-24.0 | 4         | 0.09%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 616       | 13.62%  |
| AU Optronics            | 485       | 10.73%  |
| LG Display              | 412       | 9.11%   |
| Chimei Innolux          | 330       | 7.3%    |
| BOE                     | 326       | 7.21%   |
| Goldstar                | 265       | 5.86%   |
| Dell                    | 233       | 5.15%   |
| Hewlett-Packard         | 232       | 5.13%   |
| Acer                    | 171       | 3.78%   |
| AOC                     | 151       | 3.34%   |
| Philips                 | 143       | 3.16%   |
| BenQ                    | 98        | 2.17%   |
| Lenovo                  | 91        | 2.01%   |
| Chi Mei Optoelectronics | 81        | 1.79%   |
| Ancor Communications    | 75        | 1.66%   |
| ViewSonic               | 65        | 1.44%   |
| Apple                   | 64        | 1.42%   |
| Iiyama                  | 44        | 0.97%   |
| Eizo                    | 37        | 0.82%   |
| Sharp                   | 35        | 0.77%   |
| Sony                    | 34        | 0.75%   |
| InfoVision              | 29        | 0.64%   |
| LG Philips              | 28        | 0.62%   |
| ASUSTek Computer        | 28        | 0.62%   |
| CPT                     | 24        | 0.53%   |
| Toshiba                 | 23        | 0.51%   |
| NEC Computers           | 20        | 0.44%   |
| HannStar                | 19        | 0.42%   |
| Fujitsu Siemens         | 18        | 0.4%    |
| PANDA                   | 17        | 0.38%   |
| Panasonic               | 14        | 0.31%   |
| Hitachi                 | 11        | 0.24%   |
| Unknown                 | 10        | 0.22%   |
| Sceptre Tech            | 10        | 0.22%   |
| ___                     | 9         | 0.2%    |
| Vestel Elektronik       | 9         | 0.2%    |
| TCL                     | 9         | 0.2%    |
| MSI                     | 9         | 0.2%    |
| Medion                  | 9         | 0.2%    |
| Vizio                   | 8         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 25        | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 24        | 0.53%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 22        | 0.48%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 18        | 0.39%   |
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 18        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.35%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 15        | 0.33%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 15        | 0.33%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch            | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 12        | 0.26%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 11        | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 11        | 0.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.24%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                         | 11        | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 10        | 0.22%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                     | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 10        | 0.22%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 9         | 0.2%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 9         | 0.2%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1696      | 38.18%  |
| 1366x768 (WXGA)    | 1228      | 27.65%  |
| 3840x2160 (4K)     | 238       | 5.36%   |
| 1600x900 (HD+)     | 236       | 5.31%   |
| 1280x1024 (SXGA)   | 196       | 4.41%   |
| 2560x1440 (QHD)    | 148       | 3.33%   |
| 1440x900 (WXGA+)   | 144       | 3.24%   |
| 1680x1050 (WSXGA+) | 136       | 3.06%   |
| 1280x800 (WXGA)    | 114       | 2.57%   |
| 1920x1200 (WUXGA)  | 85        | 1.91%   |
| 1360x768           | 45        | 1.01%   |
| 3440x1440          | 28        | 0.63%   |
| 2560x1080          | 24        | 0.54%   |
| 1920x540           | 16        | 0.36%   |
| 1024x768 (XGA)     | 16        | 0.36%   |
| 2560x1600          | 14        | 0.32%   |
| 3200x1800 (QHD+)   | 12        | 0.27%   |
| 1600x1200          | 8         | 0.18%   |
| 2288x1287          | 6         | 0.14%   |
| 2160x1440          | 6         | 0.14%   |
| 1280x720 (HD)      | 6         | 0.14%   |
| 1024x600           | 5         | 0.11%   |
| 2880x1800          | 4         | 0.09%   |
| 2736x1824          | 4         | 0.09%   |
| 2048x1152          | 4         | 0.09%   |
| 1920x1280          | 4         | 0.09%   |
| 1280x960           | 4         | 0.09%   |
| 3840x1080          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1280x768           | 2         | 0.05%   |
| 3840x2400          | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |
| 3840x1200          | 1         | 0.02%   |
| 3456x2160          | 1         | 0.02%   |
| 3200x2000          | 1         | 0.02%   |
| 1400x1050          | 1         | 0.02%   |
| Unknown            | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1028      | 22.7%   |
| 13      | 384       | 8.48%   |
| 23      | 349       | 7.71%   |
| 21      | 336       | 7.42%   |
| 27      | 320       | 7.07%   |
| 17      | 304       | 6.71%   |
| 24      | 292       | 6.45%   |
| 14      | 248       | 5.48%   |
| 19      | 195       | 4.31%   |
| 11      | 144       | 3.18%   |
| 18      | 138       | 3.05%   |
| 31      | 118       | 2.61%   |
| 22      | 102       | 2.25%   |
| 12      | 99        | 2.19%   |
| 20      | 82        | 1.81%   |
| 84      | 46        | 1.02%   |
| 34      | 45        | 0.99%   |
| 32      | 31        | 0.68%   |
| Unknown | 26        | 0.57%   |
| 40      | 24        | 0.53%   |
| 26      | 22        | 0.49%   |
| 72      | 21        | 0.46%   |
| 54      | 18        | 0.4%    |
| 25      | 18        | 0.4%    |
| 16      | 16        | 0.35%   |
| 10      | 14        | 0.31%   |
| 65      | 13        | 0.29%   |
| 52      | 12        | 0.27%   |
| 48      | 8         | 0.18%   |
| 39      | 7         | 0.15%   |
| 33      | 7         | 0.15%   |
| 46      | 6         | 0.13%   |
| 28      | 6         | 0.13%   |
| 74      | 5         | 0.11%   |
| 47      | 5         | 0.11%   |
| 142     | 4         | 0.09%   |
| 42      | 4         | 0.09%   |
| 37      | 4         | 0.09%   |
| 35      | 4         | 0.09%   |
| 29      | 4         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1538      | 34.36%  |
| 501-600        | 928       | 20.73%  |
| 401-500        | 746       | 16.67%  |
| 201-300        | 450       | 10.05%  |
| 351-400        | 354       | 7.91%   |
| 601-700        | 154       | 3.44%   |
| 701-800        | 83        | 1.85%   |
| 1501-2000      | 74        | 1.65%   |
| 1001-1500      | 74        | 1.65%   |
| 801-900        | 40        | 0.89%   |
| Unknown        | 26        | 0.58%   |
| 901-1000       | 5         | 0.11%   |
| More than 2000 | 4         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3465      | 80.17%  |
| 16/10   | 529       | 12.24%  |
| 5/4     | 191       | 4.42%   |
| 21/9    | 49        | 1.13%   |
| 4/3     | 41        | 0.95%   |
| 3/2     | 27        | 0.62%   |
| 6/5     | 6         | 0.14%   |
| 1.00    | 4         | 0.09%   |
| 32/9    | 3         | 0.07%   |
| Unknown | 3         | 0.07%   |
| 1.96    | 2         | 0.05%   |
| 3.20    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1020      | 22.67%  |
| 201-250        | 863       | 19.18%  |
| 81-90          | 467       | 10.38%  |
| 151-200        | 384       | 8.53%   |
| 301-350        | 338       | 7.51%   |
| 141-150        | 208       | 4.62%   |
| 351-500        | 207       | 4.6%    |
| 71-80          | 175       | 3.89%   |
| 121-130        | 172       | 3.82%   |
| 51-60          | 144       | 3.2%    |
| More than 1000 | 136       | 3.02%   |
| 251-300        | 133       | 2.96%   |
| 61-70          | 88        | 1.96%   |
| 501-1000       | 61        | 1.36%   |
| 131-140        | 38        | 0.84%   |
| Unknown        | 26        | 0.58%   |
| 111-120        | 19        | 0.42%   |
| 41-50          | 15        | 0.33%   |
| 91-100         | 6         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1812      | 41%     |
| 101-120       | 1418      | 32.09%  |
| 121-160       | 869       | 19.67%  |
| 161-240       | 154       | 3.48%   |
| 1-50          | 117       | 2.65%   |
| Unknown       | 26        | 0.59%   |
| More than 240 | 23        | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4114      | 90.78%  |
| 2     | 339       | 7.48%   |
| 0     | 56        | 1.24%   |
| 3     | 20        | 0.44%   |
| 4     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2657      | 40.19%  |
| Intel                             | 1838      | 27.8%   |
| Qualcomm Atheros                  | 868       | 13.13%  |
| Broadcom                          | 343       | 5.19%   |
| Ralink                            | 99        | 1.5%    |
| Ralink Technology                 | 98        | 1.48%   |
| Marvell Technology Group          | 89        | 1.35%   |
| Broadcom Limited                  | 78        | 1.18%   |
| Nvidia                            | 74        | 1.12%   |
| TP-Link                           | 56        | 0.85%   |
| Samsung Electronics               | 38        | 0.57%   |
| MediaTek                          | 35        | 0.53%   |
| Qualcomm Atheros Communications   | 22        | 0.33%   |
| JMicron Technology                | 22        | 0.33%   |
| Huawei Technologies               | 22        | 0.33%   |
| Dell                              | 19        | 0.29%   |
| Ericsson Business Mobile Networks | 18        | 0.27%   |
| D-Link System                     | 17        | 0.26%   |
| ASIX Electronics                  | 17        | 0.26%   |
| NetGear                           | 15        | 0.23%   |
| D-Link                            | 14        | 0.21%   |
| Motorola PCS                      | 13        | 0.2%    |
| Sierra Wireless                   | 11        | 0.17%   |
| VIA Technologies                  | 10        | 0.15%   |
| Aquantia                          | 9         | 0.14%   |
| Hewlett-Packard                   | 8         | 0.12%   |
| Microsoft                         | 7         | 0.11%   |
| Edimax Technology                 | 7         | 0.11%   |
| Belkin Components                 | 7         | 0.11%   |
| ASUSTek Computer                  | 7         | 0.11%   |
| Xiaomi                            | 6         | 0.09%   |
| DisplayLink                       | 6         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.08%   |
| IMC Networks                      | 5         | 0.08%   |
| AVM                               | 5         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.05%   |
| vivo                              | 3         | 0.05%   |
| Spreadtrum Communications         | 3         | 0.05%   |
| Mellanox Technologies             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1881      | 24.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 352       | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 184       | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 122       | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 122       | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 114       | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 113       | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 104       | 1.36%   |
| Intel Wi-Fi 6 AX200                                               | 104       | 1.36%   |
| Intel Wireless 8265 / 8275                                        | 96        | 1.26%   |
| Intel Wireless 7265                                               | 94        | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 90        | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 82        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 75        | 0.98%   |
| Intel Wireless 7260                                               | 73        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 69        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 69        | 0.9%    |
| Intel Wireless 3165                                               | 69        | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 64        | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 63        | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 0.81%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 61        | 0.8%    |
| Intel 82579V Gigabit Network Connection                           | 60        | 0.79%   |
| Intel Wireless 8260                                               | 57        | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 56        | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 55        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 50        | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 48        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 48        | 0.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 44        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 43        | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 40        | 0.52%   |
| Intel Wireless 3160                                               | 40        | 0.52%   |
| Ralink MT7601U Wireless Adapter                                   | 39        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 37        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 36        | 0.47%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 0.47%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 35        | 0.46%   |
| Nvidia MCP61 Ethernet                                             | 34        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1267      | 39.08%  |
| Qualcomm Atheros                      | 696       | 21.47%  |
| Realtek Semiconductor                 | 621       | 19.15%  |
| Broadcom                              | 206       | 6.35%   |
| Ralink                                | 99        | 3.05%   |
| Ralink Technology                     | 98        | 3.02%   |
| TP-Link                               | 41        | 1.26%   |
| Broadcom Limited                      | 35        | 1.08%   |
| MediaTek                              | 32        | 0.99%   |
| Qualcomm Atheros Communications       | 22        | 0.68%   |
| D-Link                                | 14        | 0.43%   |
| NetGear                               | 13        | 0.4%    |
| Sierra Wireless                       | 11        | 0.34%   |
| Dell                                  | 11        | 0.34%   |
| D-Link System                         | 8         | 0.25%   |
| Microsoft                             | 7         | 0.22%   |
| Edimax Technology                     | 7         | 0.22%   |
| ASUSTek Computer                      | 7         | 0.22%   |
| Belkin Components                     | 6         | 0.19%   |
| Marvell Technology Group              | 5         | 0.15%   |
| IMC Networks                          | 5         | 0.15%   |
| AVM                                   | 5         | 0.15%   |
| Hewlett-Packard                       | 4         | 0.12%   |
| Ericsson Business Mobile Networks     | 3         | 0.09%   |
| Qcom                                  | 2         | 0.06%   |
| Mercucys                              | 2         | 0.06%   |
| Linksys                               | 2         | 0.06%   |
| Gemtek                                | 2         | 0.06%   |
| Chu Yuen Enterprise                   | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| ZyDAS                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Logitec                               | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 122       | 3.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 122       | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 114       | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 113       | 3.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 104       | 3.2%    |
| Intel Wi-Fi 6 AX200                                            | 104       | 3.2%    |
| Intel Wireless 8265 / 8275                                     | 96        | 2.95%   |
| Intel Wireless 7265                                            | 94        | 2.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 75        | 2.31%   |
| Intel Wireless 7260                                            | 73        | 2.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 69        | 2.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 69        | 2.12%   |
| Intel Wireless 3165                                            | 69        | 2.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 64        | 1.97%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 61        | 1.88%   |
| Intel Wireless 8260                                            | 57        | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 55        | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 48        | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 48        | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 44        | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 43        | 1.32%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 40        | 1.23%   |
| Intel Wireless 3160                                            | 40        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                | 39        | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 35        | 1.08%   |
| Intel WiFi Link 5100                                           | 31        | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 31        | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 30        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 30        | 0.92%   |
| Intel Centrino Wireless-N 2230                                 | 30        | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 28        | 0.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 28        | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 28        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 28        | 0.86%   |
| Intel Wireless-AC 9260                                         | 27        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                 | 27        | 0.83%   |
| Intel Wi-Fi 6 AX201                                            | 25        | 0.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 25        | 0.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 24        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 22        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2418      | 56.77%  |
| Intel                             | 987       | 23.17%  |
| Qualcomm Atheros                  | 257       | 6.03%   |
| Broadcom                          | 187       | 4.39%   |
| Marvell Technology Group          | 84        | 1.97%   |
| Nvidia                            | 74        | 1.74%   |
| Broadcom Limited                  | 43        | 1.01%   |
| Samsung Electronics               | 36        | 0.85%   |
| JMicron Technology                | 22        | 0.52%   |
| ASIX Electronics                  | 17        | 0.4%    |
| Huawei Technologies               | 16        | 0.38%   |
| TP-Link                           | 15        | 0.35%   |
| VIA Technologies                  | 10        | 0.23%   |
| D-Link System                     | 9         | 0.21%   |
| Aquantia                          | 9         | 0.21%   |
| Motorola PCS                      | 8         | 0.19%   |
| Xiaomi                            | 6         | 0.14%   |
| DisplayLink                       | 6         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.07%   |
| vivo                              | 3         | 0.07%   |
| Spreadtrum Communications         | 3         | 0.07%   |
| MediaTek                          | 3         | 0.07%   |
| HTC (High Tech Computer)          | 3         | 0.07%   |
| Hewlett-Packard                   | 3         | 0.07%   |
| Google                            | 3         | 0.07%   |
| 3Com                              | 3         | 0.07%   |
| T & A Mobile Phones               | 2         | 0.05%   |
| Qualcomm                          | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| NetGear                           | 2         | 0.05%   |
| Mellanox Technologies             | 2         | 0.05%   |
| ICS Advent                        | 2         | 0.05%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Netchip Technology                | 1         | 0.02%   |
| Lenovo                            | 1         | 0.02%   |
| Emulex                            | 1         | 0.02%   |
| Dell                              | 1         | 0.02%   |
| Davicom Semiconductor             | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1881      | 43.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 352       | 8.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 184       | 4.23%   |
| Intel Ethernet Connection I217-LM                                 | 90        | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 82        | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 63        | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 60        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 56        | 1.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 50        | 1.15%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39        | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 37        | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 36        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 36        | 0.83%   |
| Nvidia MCP61 Ethernet                                             | 34        | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 33        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 32        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 30        | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 27        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 26        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 26        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 25        | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 25        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 23        | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 22        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 18        | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 18        | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 18        | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.37%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 14        | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 14        | 0.32%   |
| Nvidia MCP79 Ethernet                                             | 14        | 0.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 14        | 0.32%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 13        | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4077      | 56.29%  |
| WiFi     | 3122      | 43.1%   |
| Modem    | 35        | 0.48%   |
| Unknown  | 9         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2483      | 55.84%  |
| WiFi     | 1964      | 44.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2371      | 52.34%  |
| 1     | 2043      | 45.1%   |
| 3     | 66        | 1.46%   |
| 0     | 38        | 0.84%   |
| 4     | 9         | 0.2%    |
| 5     | 2         | 0.04%   |
| 10    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3215      | 70.71%  |
| Yes  | 1332      | 29.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 946       | 41.08%  |
| Realtek Semiconductor           | 243       | 10.55%  |
| Qualcomm Atheros Communications | 210       | 9.12%   |
| Cambridge Silicon Radio         | 152       | 6.6%    |
| Broadcom                        | 147       | 6.38%   |
| Lite-On Technology              | 104       | 4.52%   |
| IMC Networks                    | 99        | 4.3%    |
| Apple                           | 76        | 3.3%    |
| Foxconn / Hon Hai               | 71        | 3.08%   |
| Dell                            | 45        | 1.95%   |
| Toshiba                         | 37        | 1.61%   |
| ASUSTek Computer                | 34        | 1.48%   |
| Ralink                          | 30        | 1.3%    |
| Hewlett-Packard                 | 30        | 1.3%    |
| Realtek                         | 9         | 0.39%   |
| Alps Electric                   | 9         | 0.39%   |
| MediaTek                        | 8         | 0.35%   |
| Ralink Technology               | 7         | 0.3%    |
| Marvell Semiconductor           | 5         | 0.22%   |
| Fujitsu                         | 5         | 0.22%   |
| Edimax Technology               | 4         | 0.17%   |
| Askey Computer                  | 4         | 0.17%   |
| TP-Link                         | 3         | 0.13%   |
| Foxconn International           | 3         | 0.13%   |
| Dynex                           | 3         | 0.13%   |
| Unknown                         | 3         | 0.13%   |
| Integrated System Solution      | 2         | 0.09%   |
| Chicony Electronics             | 2         | 0.09%   |
| Belkin Components               | 2         | 0.09%   |
| Accel Semiconductor             | 2         | 0.09%   |
| USI                             | 1         | 0.04%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Smart Modular Technologies      | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Primax Electronics              | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| ISSC                            | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 431       | 18.71%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 152       | 6.6%    |
| Realtek Bluetooth Radio                                                             | 145       | 6.3%    |
| Intel AX201 Bluetooth                                                               | 130       | 5.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 125       | 5.43%   |
| Intel AX200 Bluetooth                                                               | 100       | 4.34%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 82        | 3.56%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 73        | 3.17%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 52        | 2.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 41        | 1.78%   |
| IMC Networks Bluetooth Radio                                                        | 41        | 1.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 40        | 1.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 36        | 1.56%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 36        | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 34        | 1.48%   |
| Ralink RT3290 Bluetooth                                                             | 30        | 1.3%    |
| IMC Networks Bluetooth Device                                                       | 30        | 1.3%    |
| Lite-On Bluetooth Device                                                            | 29        | 1.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 29        | 1.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 26        | 1.13%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 26        | 1.13%   |
| Apple Bluetooth Host Controller                                                     | 25        | 1.09%   |
| Dell DW375 Bluetooth Module                                                         | 24        | 1.04%   |
| Apple Bluetooth USB Host Controller                                                 | 23        | 1%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 21        | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 21        | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 20        | 0.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 20        | 0.87%   |
| Intel AX210 Bluetooth                                                               | 18        | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 18        | 0.78%   |
| Realtek RTL8723B Bluetooth                                                          | 12        | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 12        | 0.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 12        | 0.52%   |
| Toshiba RT Bluetooth Radio                                                          | 11        | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 11        | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 11        | 0.48%   |
| Broadcom BCM2045 Bluetooth                                                          | 10        | 0.43%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 10        | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 9         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3303      | 54.89%  |
| AMD                                          | 1344      | 22.34%  |
| Nvidia                                       | 968       | 16.09%  |
| C-Media Electronics                          | 87        | 1.45%   |
| Creative Labs                                | 51        | 0.85%   |
| Logitech                                     | 36        | 0.6%    |
| Texas Instruments                            | 20        | 0.33%   |
| Creative Technology                          | 16        | 0.27%   |
| JMTek                                        | 15        | 0.25%   |
| Generalplus Technology                       | 13        | 0.22%   |
| ASUSTek Computer                             | 11        | 0.18%   |
| VIA Technologies                             | 7         | 0.12%   |
| Plantronics                                  | 7         | 0.12%   |
| GN Netcom                                    | 7         | 0.12%   |
| XMOS                                         | 5         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.08%   |
| Realtek Semiconductor                        | 5         | 0.08%   |
| Tenx Technology                              | 4         | 0.07%   |
| Samson Technologies                          | 4         | 0.07%   |
| Kingston Technology                          | 4         | 0.07%   |
| Focusrite-Novation                           | 4         | 0.07%   |
| Blue Microphones                             | 4         | 0.07%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.05%   |
| SteelSeries ApS                              | 3         | 0.05%   |
| Sony                                         | 3         | 0.05%   |
| Razer USA                                    | 3         | 0.05%   |
| Lenovo                                       | 3         | 0.05%   |
| KTMicro                                      | 3         | 0.05%   |
| Hewlett-Packard                              | 3         | 0.05%   |
| Corsair                                      | 3         | 0.05%   |
| BEHRINGER International                      | 3         | 0.05%   |
| Apple                                        | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| Trust                                        | 2         | 0.03%   |
| ROCCAT                                       | 2         | 0.03%   |
| QinHeng Electronics                          | 2         | 0.03%   |
| PreSonus Audio Electronics                   | 2         | 0.03%   |
| No brand                                     | 2         | 0.03%   |
| Micro Star International                     | 2         | 0.03%   |
| Medeli Electronics                           | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 396       | 5.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 381       | 5.28%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 314       | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 273       | 3.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 251       | 3.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 245       | 3.39%   |
| AMD FCH Azalia Controller                                                                         | 224       | 3.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 217       | 3.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 190       | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 179       | 2.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 154       | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 152       | 2.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 138       | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 125       | 1.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 116       | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 114       | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 112       | 1.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 111       | 1.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 103       | 1.43%   |
| Intel Broadwell-U Audio Controller                                                                | 96        | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 95        | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 92        | 1.27%   |
| Intel 8 Series HD Audio Controller                                                                | 91        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 90        | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 87        | 1.21%   |
| Intel 200 Series PCH HD Audio                                                                     | 86        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 84        | 1.16%   |
| Nvidia High Definition Audio Controller                                                           | 83        | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 76        | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 75        | 1.04%   |
| Intel Jasper Lake HD Audio                                                                        | 73        | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 67        | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 65        | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 63        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 63        | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 62        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 55        | 0.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 52        | 0.72%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 50        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 48        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 995       | 18.39%  |
| SK hynix            | 845       | 15.62%  |
| Unknown             | 694       | 12.83%  |
| Kingston            | 684       | 12.64%  |
| Micron Technology   | 446       | 8.24%   |
| Crucial             | 286       | 5.29%   |
| Corsair             | 220       | 4.07%   |
| G.Skill             | 174       | 3.22%   |
| A-DATA Technology   | 132       | 2.44%   |
| Ramaxel Technology  | 105       | 1.94%   |
| Elpida              | 105       | 1.94%   |
| Nanya Technology    | 81        | 1.5%    |
| Unknown             | 70        | 1.29%   |
| Smart               | 69        | 1.28%   |
| Unknown (ABCD)      | 46        | 0.85%   |
| Patriot             | 46        | 0.85%   |
| Team                | 40        | 0.74%   |
| GOODRAM             | 26        | 0.48%   |
| Transcend           | 23        | 0.43%   |
| AMD                 | 21        | 0.39%   |
| Teikon              | 18        | 0.33%   |
| Silicon Power       | 13        | 0.24%   |
| Apacer              | 13        | 0.24%   |
| ASint Technology    | 12        | 0.22%   |
| Qimonda             | 11        | 0.2%    |
| CSX                 | 11        | 0.2%    |
| Kingmax             | 9         | 0.17%   |
| GeIL                | 9         | 0.17%   |
| Unifosa             | 8         | 0.15%   |
| PNY                 | 8         | 0.15%   |
| Avant               | 8         | 0.15%   |
| Smart Brazil        | 7         | 0.13%   |
| High Bridge         | 7         | 0.13%   |
| Toshiba             | 6         | 0.11%   |
| Goldkey             | 6         | 0.11%   |
| Super Talent        | 5         | 0.09%   |
| Sesame              | 5         | 0.09%   |
| Multilaser          | 5         | 0.09%   |
| 48spaces            | 5         | 0.09%   |
| Timetec             | 4         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 70        | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 62        | 1.05%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 53        | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 51        | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 51        | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 49        | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 47        | 0.8%    |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 44        | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 40        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 37        | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 36        | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 36        | 0.61%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 35        | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 34        | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 34        | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 34        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 32        | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 26        | 0.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 26        | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 23        | 0.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 22        | 0.37%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 22        | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 21        | 0.36%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 20        | 0.34%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 20        | 0.34%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                 | 20        | 0.34%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 20        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 0.34%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 19        | 0.32%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 19        | 0.32%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 18        | 0.31%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 18        | 0.31%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 18        | 0.31%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                         | 18        | 0.31%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s             | 18        | 0.31%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s            | 18        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 2070      | 45.17%  |
| DDR4    | 1502      | 32.77%  |
| DDR2    | 355       | 7.75%   |
| SDRAM   | 221       | 4.82%   |
| Unknown | 200       | 4.36%   |
| LPDDR4  | 142       | 3.1%    |
| DDR     | 38        | 0.83%   |
| LPDDR3  | 34        | 0.74%   |
| DRAM    | 13        | 0.28%   |
| DDR5    | 7         | 0.15%   |
| LPDDR5  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2357      | 52.27%  |
| DIMM         | 1980      | 43.91%  |
| Row Of Chips | 145       | 3.22%   |
| Chip         | 14        | 0.31%   |
| Unknown      | 6         | 0.13%   |
| FB-DIMM      | 4         | 0.09%   |
| RIMM         | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1825      | 35.68%  |
| 8192  | 1619      | 31.65%  |
| 2048  | 1023      | 20%     |
| 16384 | 335       | 6.55%   |
| 1024  | 224       | 4.38%   |
| 32768 | 63        | 1.23%   |
| 512   | 25        | 0.49%   |
| 65536 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1317      | 25.88%  |
| 1333    | 528       | 10.38%  |
| 2667    | 465       | 9.14%   |
| 3200    | 371       | 7.29%   |
| 2400    | 360       | 7.08%   |
| 1334    | 234       | 4.6%    |
| 800     | 190       | 3.73%   |
| 667     | 180       | 3.54%   |
| 2133    | 170       | 3.34%   |
| Unknown | 148       | 2.91%   |
| 3600    | 112       | 2.2%    |
| 1067    | 103       | 2.02%   |
| 1867    | 95        | 1.87%   |
| 4267    | 60        | 1.18%   |
| 2666    | 59        | 1.16%   |
| 1866    | 59        | 1.16%   |
| 1066    | 52        | 1.02%   |
| 3266    | 45        | 0.88%   |
| 2048    | 43        | 0.85%   |
| 4199    | 41        | 0.81%   |
| 533     | 36        | 0.71%   |
| 3400    | 35        | 0.69%   |
| 1800    | 35        | 0.69%   |
| 3000    | 30        | 0.59%   |
| 975     | 27        | 0.53%   |
| 2933    | 23        | 0.45%   |
| 400     | 22        | 0.43%   |
| 3866    | 17        | 0.33%   |
| 3733    | 15        | 0.29%   |
| 3466    | 13        | 0.26%   |
| 333     | 13        | 0.26%   |
| 8400    | 11        | 0.22%   |
| 3666    | 11        | 0.22%   |
| 2800    | 10        | 0.2%    |
| 1639    | 10        | 0.2%    |
| 4266    | 9         | 0.18%   |
| 3800    | 9         | 0.18%   |
| 49926   | 8         | 0.16%   |
| 2000    | 8         | 0.16%   |
| 3333    | 7         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 65        | 38.69%  |
| Brother Industries    | 36        | 21.43%  |
| Canon                 | 26        | 15.48%  |
| Samsung Electronics   | 13        | 7.74%   |
| Seiko Epson           | 11        | 6.55%   |
| Lexmark International | 6         | 3.57%   |
| Xerox                 | 2         | 1.19%   |
| Kyocera               | 2         | 1.19%   |
| Zebra                 | 1         | 0.6%    |
| Ricoh                 | 1         | 0.6%    |
| QinHeng Electronics   | 1         | 0.6%    |
| Prolific Technology   | 1         | 0.6%    |
| NXP Semiconductors    | 1         | 0.6%    |
| Dymo-CoStar           | 1         | 0.6%    |
| Citizen               | 1         | 0.6%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Brother DCP-7055W                            | 4         | 2.38%   |
| Samsung M2070 Series                         | 3         | 1.79%   |
| HP LaserJet 1200                             | 3         | 1.79%   |
| HP LaserJet 1018                             | 3         | 1.79%   |
| HP LaserJet 1010                             | 3         | 1.79%   |
| HP ENVY 4520 series                          | 3         | 1.79%   |
| HP DeskJet 2700 series                       | 3         | 1.79%   |
| Seiko Epson ET-4760 Series                   | 2         | 1.19%   |
| Samsung SCX-3400 Series                      | 2         | 1.19%   |
| Samsung M2020 Series                         | 2         | 1.19%   |
| Samsung CLP-310 Color Laser Printer          | 2         | 1.19%   |
| HP OfficeJet Pro 7740 series                 | 2         | 1.19%   |
| HP LaserJet P1005                            | 2         | 1.19%   |
| HP LaserJet 1020                             | 2         | 1.19%   |
| HP Ink Tank Wireless 410 series              | 2         | 1.19%   |
| HP ENVY 4500 series                          | 2         | 1.19%   |
| HP DeskJet 5550                              | 2         | 1.19%   |
| HP DeskJet 2620 All-in-One Printer           | 2         | 1.19%   |
| HP Deskjet 1050 J410                         | 2         | 1.19%   |
| Canon TS5100 series                          | 2         | 1.19%   |
| Canon PIXMA MG3600 Series                    | 2         | 1.19%   |
| Canon iP7200 series                          | 2         | 1.19%   |
| Brother MFC-L2710DW series                   | 2         | 1.19%   |
| Brother MFC-J470DW                           | 2         | 1.19%   |
| Brother DCP-T310                             | 2         | 1.19%   |
| Zebra LP2824                                 | 1         | 0.6%    |
| Xerox Phaser 6510                            | 1         | 0.6%    |
| Xerox Phaser 6010N                           | 1         | 0.6%    |
| Seiko Epson XP-2100 Series                   | 1         | 0.6%    |
| Seiko Epson WF-2510 Series                   | 1         | 0.6%    |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.6%    |
| Seiko Epson L6160 Series                     | 1         | 0.6%    |
| Seiko Epson L365 Series                      | 1         | 0.6%    |
| Seiko Epson L355 Series                      | 1         | 0.6%    |
| Seiko Epson L3210 Series                     | 1         | 0.6%    |
| Seiko Epson L120 Series                      | 1         | 0.6%    |
| Seiko Epson ET-2710 Series                   | 1         | 0.6%    |
| Samsung ML-2850 Series                       | 1         | 0.6%    |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.6%    |
| Samsung M267x 287x Series                    | 1         | 0.6%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 15        | 71.43%  |
| Seiko Epson     | 3         | 14.29%  |
| Mustek Systems  | 2         | 9.52%   |
| Hewlett-Packard | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 3         | 14.29%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 9.52%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 9.52%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 9.52%   |
| Canon CanoScan LiDE 120                                  | 2         | 9.52%   |
| Canon CanoScan LiDE 100                                  | 2         | 9.52%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 4.76%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 4.76%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 4.76%   |
| HP ScanJet 2400c                                         | 1         | 4.76%   |
| Canon CanoScan LiDE 600F                                 | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                   | 1         | 4.76%   |
| Canon CanoScan LiDE 210                                  | 1         | 4.76%   |
| Canon CanoScan 5200F                                     | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 508       | 21.49%  |
| Realtek Semiconductor                  | 264       | 11.17%  |
| Microdia                               | 251       | 10.62%  |
| IMC Networks                           | 135       | 5.71%   |
| Sunplus Innovation Technology          | 134       | 5.67%   |
| Logitech                               | 119       | 5.03%   |
| Suyin                                  | 99        | 4.19%   |
| Quanta                                 | 91        | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 88        | 3.72%   |
| Bison Electronics                      | 85        | 3.6%    |
| Syntek                                 | 64        | 2.71%   |
| Apple                                  | 60        | 2.54%   |
| Lite-On Technology                     | 47        | 1.99%   |
| Silicon Motion                         | 45        | 1.9%    |
| Acer                                   | 42        | 1.78%   |
| Alcor Micro                            | 38        | 1.61%   |
| Ricoh                                  | 36        | 1.52%   |
| Microsoft                              | 22        | 0.93%   |
| ALi                                    | 20        | 0.85%   |
| Importek                               | 19        | 0.8%    |
| Lenovo                                 | 17        | 0.72%   |
| Z-Star Microelectronics                | 16        | 0.68%   |
| Luxvisions Innotech Limited            | 13        | 0.55%   |
| Generalplus Technology                 | 13        | 0.55%   |
| Primax Electronics                     | 11        | 0.47%   |
| Sonix Technology                       | 9         | 0.38%   |
| Samsung Electronics                    | 9         | 0.38%   |
| KYE Systems (Mouse Systems)            | 9         | 0.38%   |
| Cubeternet                             | 7         | 0.3%    |
| Aveo Technology                        | 7         | 0.3%    |
| Sunplus Technology                     | 5         | 0.21%   |
| Hewlett-Packard                        | 5         | 0.21%   |
| DigiTech                               | 5         | 0.21%   |
| Trust                                  | 4         | 0.17%   |
| OmniVision Technologies                | 4         | 0.17%   |
| GEMBIRD                                | 4         | 0.17%   |
| ARC International                      | 4         | 0.17%   |
| Unknown                                | 3         | 0.13%   |
| Jieli Technology                       | 3         | 0.13%   |
| Creative Technology                    | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 101       | 4.2%    |
| Chicony Integrated Camera                               | 71        | 2.95%   |
| Realtek Integrated_Webcam_5M                            | 59        | 2.46%   |
| Realtek Integrated_Webcam_HD                            | 55        | 2.29%   |
| Chicony HD WebCam                                       | 53        | 2.21%   |
| Sunplus Integrated_Webcam_HD                            | 52        | 2.16%   |
| Syntek Integrated Camera                                | 32        | 1.33%   |
| Microdia Integrated Webcam                              | 32        | 1.33%   |
| Logitech Webcam C270                                    | 29        | 1.21%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 27        | 1.12%   |
| IMC Networks Integrated Camera                          | 25        | 1.04%   |
| Realtek USB Camera                                      | 24        | 1%      |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 22        | 0.92%   |
| Chicony USB 2.0 Camera                                  | 22        | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 21        | 0.87%   |
| Chicony TOSHIBA Web Camera - HD                         | 21        | 0.87%   |
| Chicony Lenovo EasyCamera                               | 21        | 0.87%   |
| Microdia USB 2.0 Camera                                 | 20        | 0.83%   |
| Chicony VGA Webcam                                      | 20        | 0.83%   |
| Chicony USB2.0 VGA UVC WebCam                           | 19        | 0.79%   |
| Apple FaceTime HD Camera (Built-in)                     | 19        | 0.79%   |
| Apple Built-in iSight                                   | 19        | 0.79%   |
| Quanta HD User Facing                                   | 18        | 0.75%   |
| Sunplus HD WebCam                                       | 17        | 0.71%   |
| Microdia Integrated_Webcam_5M                           | 17        | 0.71%   |
| Chicony FJ Camera                                       | 17        | 0.71%   |
| Chicony HP Truevision HD                                | 16        | 0.67%   |
| Chicony HD User Facing                                  | 16        | 0.67%   |
| Realtek EasyCamera                                      | 15        | 0.62%   |
| Quanta HP TrueVision HD Camera                          | 15        | 0.62%   |
| Logitech HD Webcam C525                                 | 15        | 0.62%   |
| Chicony USB2.0 HD UVC WebCam                            | 15        | 0.62%   |
| Chicony HP TrueVision HD Camera                         | 15        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.62%   |
| Quanta HD Webcam                                        | 14        | 0.58%   |
| Lite-On Integrated Camera                               | 14        | 0.58%   |
| Syntek Lenovo EasyCamera                                | 13        | 0.54%   |
| Realtek Lenovo EasyCamera                               | 13        | 0.54%   |
| Logitech HD Pro Webcam C920                             | 13        | 0.54%   |
| Chicony HP Webcam                                       | 13        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 86        | 38.57%  |
| AuthenTec                  | 32        | 14.35%  |
| Upek                       | 25        | 11.21%  |
| Synaptics                  | 20        | 8.97%   |
| Shenzhen Goodix Technology | 18        | 8.07%   |
| Elan Microelectronics      | 18        | 8.07%   |
| LighTuning Technology      | 11        | 4.93%   |
| STMicroelectronics         | 10        | 4.48%   |
| Samsung Electronics        | 1         | 0.45%   |
| HOLTEK                     | 1         | 0.45%   |
| Focal-systems.Corp         | 1         | 0.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 24        | 10.76%  |
| Validity Sensors VFS495 Fingerprint Reader                  | 21        | 9.42%   |
| Shenzhen Goodix  Fingerprint Device                         | 11        | 4.93%   |
| STMicroelectronics Fingerprint Reader                       | 10        | 4.48%   |
| Elan ELAN:Fingerprint                                       | 10        | 4.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 9         | 4.04%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 9         | 4.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 8         | 3.59%   |
| Elan ELAN:ARM-M4                                            | 8         | 3.59%   |
| Validity Sensors VFS491                                     | 7         | 3.14%   |
| AuthenTec AES2810                                           | 7         | 3.14%   |
| AuthenTec AES1600                                           | 7         | 3.14%   |
| Validity Sensors Synaptics WBDI                             | 6         | 2.69%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 6         | 2.69%   |
| Shenzhen Goodix Fingerprint Reader                          | 6         | 2.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 5         | 2.24%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 5         | 2.24%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 5         | 2.24%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 5         | 2.24%   |
| AuthenTec Fingerprint Sensor                                | 5         | 2.24%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 4         | 1.79%   |
| Validity Sensors Fingerprint scanner                        | 4         | 1.79%   |
| Synaptics UWP WBDI                                          | 4         | 1.79%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 1.35%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 3         | 1.35%   |
| Synaptics Fingerprint reader [HP G6]                        | 3         | 1.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 3         | 1.35%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 3         | 1.35%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 2         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 2         | 0.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 2         | 0.9%    |
| LighTuning Fingerprint Reader                               | 2         | 0.9%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 0.45%   |
| Upek TCS5B Fingerprint sensor                               | 1         | 0.45%   |
| Synaptics WBDI Fingerprint Reader USB 102                   | 1         | 0.45%   |
| Synaptics WBDI Device                                       | 1         | 0.45%   |
| Synaptics  WBDI                                             | 1         | 0.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 0.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 0.45%   |
| Synaptics Fingerprint scanner                               | 1         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 85        | 52.8%   |
| O2 Micro              | 19        | 11.8%   |
| Alcor Micro           | 19        | 11.8%   |
| Upek                  | 14        | 8.7%    |
| Lenovo                | 12        | 7.45%   |
| SCM Microsystems      | 3         | 1.86%   |
| Realtek Semiconductor | 3         | 1.86%   |
| Gemalto (was Gemplus) | 3         | 1.86%   |
| BIT4ID                | 2         | 1.24%   |
| Cherry                | 1         | 0.62%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 40        | 24.84%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 14.91%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 11.18%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 11.18%  |
| Broadcom 5880                                                                | 15        | 9.32%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 8.7%    |
| Lenovo Integrated Smart Card Reader                                          | 12        | 7.45%   |
| Broadcom 58200                                                               | 5         | 3.11%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.86%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.24%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.24%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.62%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.62%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.62%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.62%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.62%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.62%   |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.62%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.62%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3724      | 82.12%  |
| 1     | 702       | 15.48%  |
| 2     | 95        | 2.09%   |
| 3     | 11        | 0.24%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 223       | 24.48%  |
| Graphics card            | 189       | 20.75%  |
| Chipcard                 | 156       | 17.12%  |
| Net/wireless             | 87        | 9.55%   |
| Multimedia controller    | 77        | 8.45%   |
| Bluetooth                | 62        | 6.81%   |
| Storage                  | 28        | 3.07%   |
| Communication controller | 24        | 2.63%   |
| Camera                   | 24        | 2.63%   |
| Unassigned class         | 17        | 1.87%   |
| Network                  | 7         | 0.77%   |
| Sound                    | 4         | 0.44%   |
| Wireless                 | 3         | 0.33%   |
| Flash memory             | 3         | 0.33%   |
| Storage/raid             | 2         | 0.22%   |
| Net/ethernet             | 2         | 0.22%   |
| Card reader              | 2         | 0.22%   |
| Dvb card                 | 1         | 0.11%   |

