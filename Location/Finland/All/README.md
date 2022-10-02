Linux in Finland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Finland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Finland/Desktop/README.md) and [notebooks](/Location/Finland/Notebook/README.md).

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

Total: 1573

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5480               | Notebook    | [ec9593f051](https://linux-hardware.org/?probe=ec9593f051) | Oct 01, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [a64f339e70](https://linux-hardware.org/?probe=a64f339e70) | Sep 28, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [03ac8c5daa](https://linux-hardware.org/?probe=03ac8c5daa) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0f4b7501b3](https://linux-hardware.org/?probe=0f4b7501b3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [d603e07087](https://linux-hardware.org/?probe=d603e07087) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a2ebf20cd0](https://linux-hardware.org/?probe=a2ebf20cd0) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| HP            | 0AA0h                       | Desktop     | [5757039d29](https://linux-hardware.org/?probe=5757039d29) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e46ce42e90](https://linux-hardware.org/?probe=e46ce42e90) | Sep 20, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| ZMY           | D1500 Ver.A                 | Server      | [a99d672930](https://linux-hardware.org/?probe=a99d672930) | Sep 15, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [e620df9580](https://linux-hardware.org/?probe=e620df9580) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6168b7089f](https://linux-hardware.org/?probe=6168b7089f) | Sep 11, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [4a00a1ca0b](https://linux-hardware.org/?probe=4a00a1ca0b) | Sep 10, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [bb1af3736f](https://linux-hardware.org/?probe=bb1af3736f) | Sep 10, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [40ad505314](https://linux-hardware.org/?probe=40ad505314) | Sep 10, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| Dell          | Latitude E6220              | Notebook    | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| HP            | 805A                        | Desktop     | [477936d851](https://linux-hardware.org/?probe=477936d851) | Aug 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2fd4ef02b3](https://linux-hardware.org/?probe=2fd4ef02b3) | Aug 30, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4b37519faf](https://linux-hardware.org/?probe=4b37519faf) | Aug 29, 2022 |
| HP            | 339A                        | Desktop     | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | Notebook    | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [a180ab604a](https://linux-hardware.org/?probe=a180ab604a) | Aug 26, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [6bcc6b550f](https://linux-hardware.org/?probe=6bcc6b550f) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| Acer          | Predator G3620              | Desktop     | [b79ed7b47b](https://linux-hardware.org/?probe=b79ed7b47b) | Aug 23, 2022 |
| HP            | Compaq 6735s                | Notebook    | [4e52bb6ecb](https://linux-hardware.org/?probe=4e52bb6ecb) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1d0c242f30](https://linux-hardware.org/?probe=1d0c242f30) | Aug 23, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| ASRock        | Z75 Pro3                    | Desktop     | [4fbe3d2710](https://linux-hardware.org/?probe=4fbe3d2710) | Aug 22, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Alienware     | 15 R3                       | Notebook    | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [7deff7707e](https://linux-hardware.org/?probe=7deff7707e) | Aug 21, 2022 |
| HP            | Compaq 6735s                | Notebook    | [5cfcfab468](https://linux-hardware.org/?probe=5cfcfab468) | Aug 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [8834646a81](https://linux-hardware.org/?probe=8834646a81) | Aug 19, 2022 |
| Acer          | Predator PO5-600s V:1.0     | Desktop     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [eaea01215e](https://linux-hardware.org/?probe=eaea01215e) | Aug 17, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9d82dca288](https://linux-hardware.org/?probe=9d82dca288) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X501A1                      | Notebook    | [d021969767](https://linux-hardware.org/?probe=d021969767) | Aug 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| Acer          | Aspire VN7-571G             | Notebook    | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a5ef05aaff](https://linux-hardware.org/?probe=a5ef05aaff) | Aug 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [bd608fb7bc](https://linux-hardware.org/?probe=bd608fb7bc) | Aug 13, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| HP            | 805A                        | Desktop     | [c7671a704a](https://linux-hardware.org/?probe=c7671a704a) | Aug 11, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [2539e9f908](https://linux-hardware.org/?probe=2539e9f908) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| HP            | 1497                        | Desktop     | [2fe6cb5b2c](https://linux-hardware.org/?probe=2fe6cb5b2c) | Aug 07, 2022 |
| HP            | 1497                        | Desktop     | [24959f2c80](https://linux-hardware.org/?probe=24959f2c80) | Aug 07, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [0f1a9e4af2](https://linux-hardware.org/?probe=0f1a9e4af2) | Aug 06, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fa0a089121](https://linux-hardware.org/?probe=fa0a089121) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a284074100](https://linux-hardware.org/?probe=a284074100) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [f14436327b](https://linux-hardware.org/?probe=f14436327b) | Aug 04, 2022 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [365fe3e266](https://linux-hardware.org/?probe=365fe3e266) | Aug 03, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [da1731c1d2](https://linux-hardware.org/?probe=da1731c1d2) | Aug 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [2cea7378e8](https://linux-hardware.org/?probe=2cea7378e8) | Aug 03, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [09cd376e43](https://linux-hardware.org/?probe=09cd376e43) | Aug 02, 2022 |
| HP            | Compaq 2510p                | Notebook    | [b61ccedd14](https://linux-hardware.org/?probe=b61ccedd14) | Jul 31, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [8693dca4f6](https://linux-hardware.org/?probe=8693dca4f6) | Jul 30, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [dca4c898f8](https://linux-hardware.org/?probe=dca4c898f8) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ca37936b6f](https://linux-hardware.org/?probe=ca37936b6f) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [fa46d23eda](https://linux-hardware.org/?probe=fa46d23eda) | Jul 27, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [70ddacf43f](https://linux-hardware.org/?probe=70ddacf43f) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1578510bc0](https://linux-hardware.org/?probe=1578510bc0) | Jul 25, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | Desktop     | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [9558ff01e9](https://linux-hardware.org/?probe=9558ff01e9) | Jul 20, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [bc85466c3f](https://linux-hardware.org/?probe=bc85466c3f) | Jul 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [96c65556bb](https://linux-hardware.org/?probe=96c65556bb) | Jul 18, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [e540c6e30d](https://linux-hardware.org/?probe=e540c6e30d) | Jul 18, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [34ff1068ca](https://linux-hardware.org/?probe=34ff1068ca) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [f4f2c80cdd](https://linux-hardware.org/?probe=f4f2c80cdd) | Jul 09, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [57517e2dc2](https://linux-hardware.org/?probe=57517e2dc2) | Jul 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3a5fc098c4](https://linux-hardware.org/?probe=3a5fc098c4) | Jul 08, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [a93792aef3](https://linux-hardware.org/?probe=a93792aef3) | Jul 07, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [9467db0d89](https://linux-hardware.org/?probe=9467db0d89) | Jul 06, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f525b5f3b0](https://linux-hardware.org/?probe=f525b5f3b0) | Jul 04, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | Notebook    | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| HP            | 829E                        | Mini pc     | [91fee1441e](https://linux-hardware.org/?probe=91fee1441e) | Jul 01, 2022 |
| HP            | 3647h                       | Desktop     | [f59774eab5](https://linux-hardware.org/?probe=f59774eab5) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [8ecea7fce7](https://linux-hardware.org/?probe=8ecea7fce7) | Jun 28, 2022 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| Medion        | AXA                         | All in one  | [0cbda6d693](https://linux-hardware.org/?probe=0cbda6d693) | Jun 23, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f0d321b741](https://linux-hardware.org/?probe=f0d321b741) | Jun 22, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a69564b477](https://linux-hardware.org/?probe=a69564b477) | Jun 17, 2022 |
| Dell          | Latitude E7440              | Notebook    | [41acc5e2ba](https://linux-hardware.org/?probe=41acc5e2ba) | Jun 17, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [139ffc0039](https://linux-hardware.org/?probe=139ffc0039) | Jun 16, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f339cce523](https://linux-hardware.org/?probe=f339cce523) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [36bf4dc378](https://linux-hardware.org/?probe=36bf4dc378) | Jun 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [d4bfcc2d6d](https://linux-hardware.org/?probe=d4bfcc2d6d) | Jun 12, 2022 |
| Dell          | 0RW203                      | Desktop     | [d53558bc85](https://linux-hardware.org/?probe=d53558bc85) | Jun 12, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d2861687ff](https://linux-hardware.org/?probe=d2861687ff) | Jun 12, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| HP            | G62                         | Notebook    | [de2464c378](https://linux-hardware.org/?probe=de2464c378) | Jun 08, 2022 |
| HP            | Elite Dragonfly Max Note... | Convertible | [3b16bdeb2c](https://linux-hardware.org/?probe=3b16bdeb2c) | Jun 06, 2022 |
| Supermicro    | X10SBA-LA                   | Desktop     | [4b46c69e08](https://linux-hardware.org/?probe=4b46c69e08) | Jun 03, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [dff99aa7e6](https://linux-hardware.org/?probe=dff99aa7e6) | May 30, 2022 |
| HP            | 1998                        | Desktop     | [48be2e4a99](https://linux-hardware.org/?probe=48be2e4a99) | May 30, 2022 |
| HP            | 1998                        | Desktop     | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [6e41ef26bf](https://linux-hardware.org/?probe=6e41ef26bf) | May 29, 2022 |
| Unknown       | Unknown                     | Phone       | [63d3c9a3b6](https://linux-hardware.org/?probe=63d3c9a3b6) | May 28, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [3a472b96d3](https://linux-hardware.org/?probe=3a472b96d3) | May 27, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [7f3e3aada0](https://linux-hardware.org/?probe=7f3e3aada0) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Dell          | Latitude 3520               | Notebook    | [6c5618416d](https://linux-hardware.org/?probe=6c5618416d) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | Notebook    | [018e2a8bff](https://linux-hardware.org/?probe=018e2a8bff) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | Notebook    | [6d4ab67cb8](https://linux-hardware.org/?probe=6d4ab67cb8) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 81X2          | Convertible | [df65cb7a9e](https://linux-hardware.org/?probe=df65cb7a9e) | May 26, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [1ca9184b98](https://linux-hardware.org/?probe=1ca9184b98) | May 22, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [d52e9e2938](https://linux-hardware.org/?probe=d52e9e2938) | May 17, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [f06eee580b](https://linux-hardware.org/?probe=f06eee580b) | May 16, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [d2e3603431](https://linux-hardware.org/?probe=d2e3603431) | May 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [244be4f232](https://linux-hardware.org/?probe=244be4f232) | May 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [587c1deb4c](https://linux-hardware.org/?probe=587c1deb4c) | May 15, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [7cbd29cc48](https://linux-hardware.org/?probe=7cbd29cc48) | May 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2f3b6548d0](https://linux-hardware.org/?probe=2f3b6548d0) | May 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [826dfbee64](https://linux-hardware.org/?probe=826dfbee64) | May 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [0065ab0681](https://linux-hardware.org/?probe=0065ab0681) | May 12, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [d94b81d9d3](https://linux-hardware.org/?probe=d94b81d9d3) | May 12, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| HP            | 805F                        | Desktop     | [466bb8cc36](https://linux-hardware.org/?probe=466bb8cc36) | May 10, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [65d7984ad4](https://linux-hardware.org/?probe=65d7984ad4) | May 09, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| Acer          | RS780HVF                    | Desktop     | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [df57c0ad60](https://linux-hardware.org/?probe=df57c0ad60) | May 09, 2022 |
| MSI           | Z87M GAMING                 | Desktop     | [7e95657ad7](https://linux-hardware.org/?probe=7e95657ad7) | May 08, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [537def711a](https://linux-hardware.org/?probe=537def711a) | May 08, 2022 |
| Acer          | RS780HVF                    | Desktop     | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Acer          | H57M01                      | Desktop     | [180132b3e1](https://linux-hardware.org/?probe=180132b3e1) | May 03, 2022 |
| Acer          | FX58M                       | Desktop     | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| HP            | 1589                        | Desktop     | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c78066bc19](https://linux-hardware.org/?probe=c78066bc19) | Apr 29, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [2e84d98937](https://linux-hardware.org/?probe=2e84d98937) | Apr 29, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [31bc958302](https://linux-hardware.org/?probe=31bc958302) | Apr 26, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [8446691cb3](https://linux-hardware.org/?probe=8446691cb3) | Apr 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| Lenovo        | ThinkPad X230 2324GA7       | Notebook    | [a5138b511d](https://linux-hardware.org/?probe=a5138b511d) | Apr 25, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [f656f0d16f](https://linux-hardware.org/?probe=f656f0d16f) | Apr 24, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1612f46137](https://linux-hardware.org/?probe=1612f46137) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e83ffcb04f](https://linux-hardware.org/?probe=e83ffcb04f) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [25e6181500](https://linux-hardware.org/?probe=25e6181500) | Apr 24, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [cd1bc2095f](https://linux-hardware.org/?probe=cd1bc2095f) | Apr 22, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [33afc70a54](https://linux-hardware.org/?probe=33afc70a54) | Apr 22, 2022 |
| Acer          | Aspire 7530G                | Notebook    | [710b429d94](https://linux-hardware.org/?probe=710b429d94) | Apr 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| ASRock        | Z87 Extreme6                | Desktop     | [d7e24821ee](https://linux-hardware.org/?probe=d7e24821ee) | Apr 18, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [5a93c8e68c](https://linux-hardware.org/?probe=5a93c8e68c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T480 20L6S93F00    | Notebook    | [b8c57e6b8a](https://linux-hardware.org/?probe=b8c57e6b8a) | Apr 14, 2022 |
| MSI           | Indio                       | Desktop     | [ca3a24d84d](https://linux-hardware.org/?probe=ca3a24d84d) | Apr 13, 2022 |
| HP            | Notebook                    | Notebook    | [24faf4835d](https://linux-hardware.org/?probe=24faf4835d) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| Acer          | Batman A01                  | Desktop     | [a102f85d9d](https://linux-hardware.org/?probe=a102f85d9d) | Apr 08, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [1a1c86083e](https://linux-hardware.org/?probe=1a1c86083e) | Apr 07, 2022 |
| HP            | 18E7                        | Desktop     | [35dbcc5737](https://linux-hardware.org/?probe=35dbcc5737) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | B150M-K                     | Desktop     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASRock        | B85M-ITX                    | Desktop     | [1a2849588f](https://linux-hardware.org/?probe=1a2849588f) | Apr 01, 2022 |
| HP            | 3047h                       | Desktop     | [356fac6a3a](https://linux-hardware.org/?probe=356fac6a3a) | Apr 01, 2022 |
| HP            | 3047h                       | Desktop     | [d4c9852b3c](https://linux-hardware.org/?probe=d4c9852b3c) | Apr 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [07efb6a561](https://linux-hardware.org/?probe=07efb6a561) | Apr 01, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Dell          | Latitude 5480               | Notebook    | [2d431aae25](https://linux-hardware.org/?probe=2d431aae25) | Mar 29, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [79c9d66395](https://linux-hardware.org/?probe=79c9d66395) | Mar 26, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| Lenovo        | ThinkPad X230 2325BN8       | Notebook    | [3ad2d0f3ee](https://linux-hardware.org/?probe=3ad2d0f3ee) | Mar 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | Notebook    | [d5b5eeffc8](https://linux-hardware.org/?probe=d5b5eeffc8) | Mar 25, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7b835e9a57](https://linux-hardware.org/?probe=7b835e9a57) | Mar 23, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [069ce018ad](https://linux-hardware.org/?probe=069ce018ad) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [bf87e829d7](https://linux-hardware.org/?probe=bf87e829d7) | Mar 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [78ae0419a3](https://linux-hardware.org/?probe=78ae0419a3) | Mar 14, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ba2686174e](https://linux-hardware.org/?probe=ba2686174e) | Mar 13, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| Acer          | AO725                       | Notebook    | [70febdd28f](https://linux-hardware.org/?probe=70febdd28f) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | Notebook    | [0f20b300ec](https://linux-hardware.org/?probe=0f20b300ec) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| HP            | G62                         | Notebook    | [67bc301ee6](https://linux-hardware.org/?probe=67bc301ee6) | Mar 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f351d9839b](https://linux-hardware.org/?probe=f351d9839b) | Mar 09, 2022 |
| Acer          | FX58M                       | Desktop     | [7404e9534e](https://linux-hardware.org/?probe=7404e9534e) | Mar 09, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [2142681934](https://linux-hardware.org/?probe=2142681934) | Mar 06, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2e19b36624](https://linux-hardware.org/?probe=2e19b36624) | Mar 03, 2022 |
| Lenovo        | ThinkPad 13 20GJ0048MS      | Notebook    | [6590a539cf](https://linux-hardware.org/?probe=6590a539cf) | Mar 02, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [ea68b8ed21](https://linux-hardware.org/?probe=ea68b8ed21) | Mar 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0278765ef8](https://linux-hardware.org/?probe=0278765ef8) | Feb 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c08be74242](https://linux-hardware.org/?probe=c08be74242) | Feb 27, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [0dd55e5b26](https://linux-hardware.org/?probe=0dd55e5b26) | Feb 26, 2022 |
| ABIT          | IP35                        | Desktop     | [278dd592cc](https://linux-hardware.org/?probe=278dd592cc) | Feb 26, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [f12d1e47df](https://linux-hardware.org/?probe=f12d1e47df) | Feb 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fa5d4846df](https://linux-hardware.org/?probe=fa5d4846df) | Feb 23, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [5fe85bba2e](https://linux-hardware.org/?probe=5fe85bba2e) | Feb 22, 2022 |
| HP            | G62                         | Notebook    | [337afde8c1](https://linux-hardware.org/?probe=337afde8c1) | Feb 21, 2022 |
| HP            | G62                         | Notebook    | [a175af3dd6](https://linux-hardware.org/?probe=a175af3dd6) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [811ec775f8](https://linux-hardware.org/?probe=811ec775f8) | Feb 19, 2022 |
| powerinter... | Cepter N510-03              | Notebook    | [cd6804144d](https://linux-hardware.org/?probe=cd6804144d) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | Notebook    | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Lenovo        | ThinkPad E14 20RA001LMX     | Notebook    | [19edff5659](https://linux-hardware.org/?probe=19edff5659) | Feb 17, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | Notebook    | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [deb108070d](https://linux-hardware.org/?probe=deb108070d) | Feb 15, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [8b588bf90b](https://linux-hardware.org/?probe=8b588bf90b) | Feb 15, 2022 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [a5179b9681](https://linux-hardware.org/?probe=a5179b9681) | Feb 15, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [7cdffcccb7](https://linux-hardware.org/?probe=7cdffcccb7) | Feb 13, 2022 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [0ba38c6605](https://linux-hardware.org/?probe=0ba38c6605) | Feb 13, 2022 |
| Dell          | Latitude E5420              | Notebook    | [f016e9f3ad](https://linux-hardware.org/?probe=f016e9f3ad) | Feb 12, 2022 |
| Dell          | Latitude E5420              | Notebook    | [8843a735a0](https://linux-hardware.org/?probe=8843a735a0) | Feb 12, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [61e1bce7ae](https://linux-hardware.org/?probe=61e1bce7ae) | Feb 12, 2022 |
| ASRock        | 890FX Deluxe4               | Desktop     | [33a47b3c4b](https://linux-hardware.org/?probe=33a47b3c4b) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [766e937263](https://linux-hardware.org/?probe=766e937263) | Feb 10, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [ba2262bba5](https://linux-hardware.org/?probe=ba2262bba5) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | Notebook    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [3d76f83751](https://linux-hardware.org/?probe=3d76f83751) | Feb 10, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [75b31509a3](https://linux-hardware.org/?probe=75b31509a3) | Feb 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [72b880911a](https://linux-hardware.org/?probe=72b880911a) | Feb 08, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [88fdd17fc6](https://linux-hardware.org/?probe=88fdd17fc6) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [22be2d64a2](https://linux-hardware.org/?probe=22be2d64a2) | Feb 06, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [e0765c9f5a](https://linux-hardware.org/?probe=e0765c9f5a) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [cba6a6b5a6](https://linux-hardware.org/?probe=cba6a6b5a6) | Feb 02, 2022 |
| Dell          | 051FJ8 A00                  | Desktop     | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [e83deb15fd](https://linux-hardware.org/?probe=e83deb15fd) | Jan 31, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [5f6a8cf57f](https://linux-hardware.org/?probe=5f6a8cf57f) | Jan 29, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [9ff78b6d13](https://linux-hardware.org/?probe=9ff78b6d13) | Jan 29, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f76e2b6c0f](https://linux-hardware.org/?probe=f76e2b6c0f) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| Lenovo        | ThinkPad X390 20Q00057MX    | Notebook    | [326cb714f0](https://linux-hardware.org/?probe=326cb714f0) | Jan 27, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [a31ae712c0](https://linux-hardware.org/?probe=a31ae712c0) | Jan 26, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [82a45a6067](https://linux-hardware.org/?probe=82a45a6067) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [cf5823e07b](https://linux-hardware.org/?probe=cf5823e07b) | Jan 26, 2022 |
| Packard Be... | IMEDIA S3840                | Desktop     | [eff4bf09ec](https://linux-hardware.org/?probe=eff4bf09ec) | Jan 26, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [63d4ce1086](https://linux-hardware.org/?probe=63d4ce1086) | Jan 23, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [b9d8fc0e46](https://linux-hardware.org/?probe=b9d8fc0e46) | Jan 23, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [88049a6cee](https://linux-hardware.org/?probe=88049a6cee) | Jan 22, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | Notebook    | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [8f7c57b03f](https://linux-hardware.org/?probe=8f7c57b03f) | Jan 18, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [06c4be96aa](https://linux-hardware.org/?probe=06c4be96aa) | Jan 17, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [39b90ab9c3](https://linux-hardware.org/?probe=39b90ab9c3) | Jan 17, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | Notebook    | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| HP            | 18E5                        | Desktop     | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [3417abe371](https://linux-hardware.org/?probe=3417abe371) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [3d2a67265f](https://linux-hardware.org/?probe=3d2a67265f) | Jan 15, 2022 |
| HP            | 1495                        | Desktop     | [ea7df45832](https://linux-hardware.org/?probe=ea7df45832) | Jan 14, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c2406eee73](https://linux-hardware.org/?probe=c2406eee73) | Jan 13, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [4bbc688f9d](https://linux-hardware.org/?probe=4bbc688f9d) | Jan 13, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [e82feb71d2](https://linux-hardware.org/?probe=e82feb71d2) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0529614510](https://linux-hardware.org/?probe=0529614510) | Jan 12, 2022 |
| Toshiba       | Satellite P870              | Notebook    | [e046040d73](https://linux-hardware.org/?probe=e046040d73) | Jan 11, 2022 |
| HP            | Notebook                    | Notebook    | [0667124a5f](https://linux-hardware.org/?probe=0667124a5f) | Jan 10, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [1da9aea182](https://linux-hardware.org/?probe=1da9aea182) | Jan 10, 2022 |
| Sony          | VGN-FZ21Z                   | Notebook    | [6291085e58](https://linux-hardware.org/?probe=6291085e58) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| HP            | 3646h                       | Desktop     | [85edd0c1bf](https://linux-hardware.org/?probe=85edd0c1bf) | Jan 08, 2022 |
| HP            | 3646h                       | Desktop     | [616a0acd31](https://linux-hardware.org/?probe=616a0acd31) | Jan 08, 2022 |
| Sony          | VGN-FZ21Z                   | Notebook    | [c4ac286105](https://linux-hardware.org/?probe=c4ac286105) | Jan 08, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [72fa18d5dd](https://linux-hardware.org/?probe=72fa18d5dd) | Jan 08, 2022 |
| MSI           | H110M ECO                   | Desktop     | [c056a2eafa](https://linux-hardware.org/?probe=c056a2eafa) | Jan 07, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [1644301279](https://linux-hardware.org/?probe=1644301279) | Jan 07, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [6f8a6d74e4](https://linux-hardware.org/?probe=6f8a6d74e4) | Jan 07, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [b2682cb5fe](https://linux-hardware.org/?probe=b2682cb5fe) | Jan 06, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Acer          | WMCP78M                     | Desktop     | [250fa57c5d](https://linux-hardware.org/?probe=250fa57c5d) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 20RA001BMX     | Notebook    | [b34ccf2c06](https://linux-hardware.org/?probe=b34ccf2c06) | Jan 05, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [c28c0f7f40](https://linux-hardware.org/?probe=c28c0f7f40) | Jan 04, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [0731f1a6d9](https://linux-hardware.org/?probe=0731f1a6d9) | Jan 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [5dd20e2872](https://linux-hardware.org/?probe=5dd20e2872) | Jan 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [4ed85a0f7a](https://linux-hardware.org/?probe=4ed85a0f7a) | Dec 30, 2021 |
| HP            | 3397                        | Desktop     | [188bb8c669](https://linux-hardware.org/?probe=188bb8c669) | Dec 28, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | Notebook    | [25a59e69c1](https://linux-hardware.org/?probe=25a59e69c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | Notebook    | [a5b0d0a06a](https://linux-hardware.org/?probe=a5b0d0a06a) | Dec 25, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [4384deed19](https://linux-hardware.org/?probe=4384deed19) | Dec 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Dell          | Latitude 5490               | Notebook    | [a9261b4529](https://linux-hardware.org/?probe=a9261b4529) | Dec 16, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [4365a457d8](https://linux-hardware.org/?probe=4365a457d8) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a1c07a7e6a](https://linux-hardware.org/?probe=a1c07a7e6a) | Dec 15, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0ca333f8b0](https://linux-hardware.org/?probe=0ca333f8b0) | Dec 15, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [002a05b1c7](https://linux-hardware.org/?probe=002a05b1c7) | Dec 14, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [81873c2912](https://linux-hardware.org/?probe=81873c2912) | Dec 14, 2021 |
| Dell          | Precision 7510              | Notebook    | [59a0d1a314](https://linux-hardware.org/?probe=59a0d1a314) | Dec 13, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [9b61f8e080](https://linux-hardware.org/?probe=9b61f8e080) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Samsung       | 750XDA                      | Notebook    | [30d61197a1](https://linux-hardware.org/?probe=30d61197a1) | Dec 09, 2021 |
| HP            | 340 G5                      | Notebook    | [8ed2eec9b4](https://linux-hardware.org/?probe=8ed2eec9b4) | Dec 07, 2021 |
| Dell          | Latitude E6400              | Notebook    | [b8e56749b8](https://linux-hardware.org/?probe=b8e56749b8) | Dec 03, 2021 |
| Lenovo        | ThinkPad W540 20BH002NMS    | Notebook    | [52d66e95f4](https://linux-hardware.org/?probe=52d66e95f4) | Dec 01, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [3284718afd](https://linux-hardware.org/?probe=3284718afd) | Dec 01, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [493153bf7c](https://linux-hardware.org/?probe=493153bf7c) | Nov 30, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [b98f644a91](https://linux-hardware.org/?probe=b98f644a91) | Nov 30, 2021 |
| HP            | 3646h                       | Desktop     | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | Desktop     | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [71d6a80bd1](https://linux-hardware.org/?probe=71d6a80bd1) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [65d49ae483](https://linux-hardware.org/?probe=65d49ae483) | Nov 26, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3355d6fd50](https://linux-hardware.org/?probe=3355d6fd50) | Nov 24, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9b0bfd9c19](https://linux-hardware.org/?probe=9b0bfd9c19) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f62619c698](https://linux-hardware.org/?probe=f62619c698) | Nov 24, 2021 |
| Acer          | WMCP78M                     | Desktop     | [5930f530bb](https://linux-hardware.org/?probe=5930f530bb) | Nov 24, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9476bb5e05](https://linux-hardware.org/?probe=9476bb5e05) | Nov 24, 2021 |
| HP            | 3647h                       | Desktop     | [e3d0601f0b](https://linux-hardware.org/?probe=e3d0601f0b) | Nov 23, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [613686da3f](https://linux-hardware.org/?probe=613686da3f) | Nov 22, 2021 |
| HP            | 8433 11                     | Desktop     | [e88c3d4a94](https://linux-hardware.org/?probe=e88c3d4a94) | Nov 22, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | Notebook    | [cdf3297bef](https://linux-hardware.org/?probe=cdf3297bef) | Nov 21, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| Google        | Relm                        | Notebook    | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [11710ca51d](https://linux-hardware.org/?probe=11710ca51d) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| Lenovo        | ThinkStation S20 4157FY2    | Desktop     | [b05be2384d](https://linux-hardware.org/?probe=b05be2384d) | Nov 20, 2021 |
| Dell          | Latitude E6420              | Notebook    | [2e2b68b190](https://linux-hardware.org/?probe=2e2b68b190) | Nov 20, 2021 |
| HP            | Pavilion 17                 | Notebook    | [a633bbd978](https://linux-hardware.org/?probe=a633bbd978) | Nov 20, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [646919d578](https://linux-hardware.org/?probe=646919d578) | Nov 20, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [972f96ba1d](https://linux-hardware.org/?probe=972f96ba1d) | Nov 17, 2021 |
| Lenovo        | ThinkPad T530 24341G0       | Notebook    | [0dcfa8bdc7](https://linux-hardware.org/?probe=0dcfa8bdc7) | Nov 17, 2021 |
| Dell          | Latitude 7420               | Notebook    | [52bd94ce90](https://linux-hardware.org/?probe=52bd94ce90) | Nov 17, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [5bed28d52e](https://linux-hardware.org/?probe=5bed28d52e) | Nov 15, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [da8846a5fd](https://linux-hardware.org/?probe=da8846a5fd) | Nov 14, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [d004277425](https://linux-hardware.org/?probe=d004277425) | Nov 14, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [1d72b572ac](https://linux-hardware.org/?probe=1d72b572ac) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | Notebook    | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [438a1236fb](https://linux-hardware.org/?probe=438a1236fb) | Nov 11, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [7a1824b26a](https://linux-hardware.org/?probe=7a1824b26a) | Nov 11, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| HP            | 1495                        | Desktop     | [d66a2a8cf5](https://linux-hardware.org/?probe=d66a2a8cf5) | Nov 10, 2021 |
| Lenovo        | Kabini CRB 31900003 STD     | Desktop     | [4d94fd8ba6](https://linux-hardware.org/?probe=4d94fd8ba6) | Nov 10, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [b98565dc8e](https://linux-hardware.org/?probe=b98565dc8e) | Nov 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [224597688f](https://linux-hardware.org/?probe=224597688f) | Nov 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [0aeea3a3c9](https://linux-hardware.org/?probe=0aeea3a3c9) | Nov 09, 2021 |
| HP            | 1495                        | Desktop     | [22bbd228cb](https://linux-hardware.org/?probe=22bbd228cb) | Nov 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [536b4200f8](https://linux-hardware.org/?probe=536b4200f8) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [33a5ffbf9a](https://linux-hardware.org/?probe=33a5ffbf9a) | Nov 07, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [748d879ed2](https://linux-hardware.org/?probe=748d879ed2) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [a40335233e](https://linux-hardware.org/?probe=a40335233e) | Nov 04, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [32b0b7b787](https://linux-hardware.org/?probe=32b0b7b787) | Nov 04, 2021 |
| ABIT          | AI7                         | Desktop     | [75f77dabe1](https://linux-hardware.org/?probe=75f77dabe1) | Nov 03, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [ae1af68eae](https://linux-hardware.org/?probe=ae1af68eae) | Nov 03, 2021 |
| Samsung       | R530/R730                   | Notebook    | [a62fb59972](https://linux-hardware.org/?probe=a62fb59972) | Nov 03, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [1217a94f61](https://linux-hardware.org/?probe=1217a94f61) | Oct 26, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [e10152abc8](https://linux-hardware.org/?probe=e10152abc8) | Oct 25, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [0f6daccd63](https://linux-hardware.org/?probe=0f6daccd63) | Oct 25, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [e74dc83f0a](https://linux-hardware.org/?probe=e74dc83f0a) | Oct 24, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [5b429fd560](https://linux-hardware.org/?probe=5b429fd560) | Oct 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [477512ba5c](https://linux-hardware.org/?probe=477512ba5c) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [c487ba6138](https://linux-hardware.org/?probe=c487ba6138) | Oct 22, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| HP            | Compaq 6735s                | Notebook    | [25c73d7c4d](https://linux-hardware.org/?probe=25c73d7c4d) | Oct 20, 2021 |
| HP            | 158B                        | Desktop     | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [d89008ef64](https://linux-hardware.org/?probe=d89008ef64) | Oct 16, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8961245abb](https://linux-hardware.org/?probe=8961245abb) | Oct 15, 2021 |
| Acer          | Aspire 7530G                | Notebook    | [09694e2816](https://linux-hardware.org/?probe=09694e2816) | Oct 15, 2021 |
| HP            | ProBook 655 G1              | Notebook    | [5a67ea75fe](https://linux-hardware.org/?probe=5a67ea75fe) | Oct 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [072dab3e8c](https://linux-hardware.org/?probe=072dab3e8c) | Oct 14, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [cf747bee4e](https://linux-hardware.org/?probe=cf747bee4e) | Oct 13, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [e8ad89cb87](https://linux-hardware.org/?probe=e8ad89cb87) | Oct 12, 2021 |
| HP            | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [818fe93a6d](https://linux-hardware.org/?probe=818fe93a6d) | Oct 10, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [319f2002de](https://linux-hardware.org/?probe=319f2002de) | Oct 09, 2021 |
| Dell          | 0YC523                      | Desktop     | [cf8d063deb](https://linux-hardware.org/?probe=cf8d063deb) | Oct 09, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [a9d87f6d4e](https://linux-hardware.org/?probe=a9d87f6d4e) | Oct 08, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | Notebook    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [2fe4152b53](https://linux-hardware.org/?probe=2fe4152b53) | Oct 07, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [26501031e8](https://linux-hardware.org/?probe=26501031e8) | Oct 07, 2021 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [28eb3733ca](https://linux-hardware.org/?probe=28eb3733ca) | Oct 06, 2021 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [8028a9757c](https://linux-hardware.org/?probe=8028a9757c) | Oct 06, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [0c5e4a2345](https://linux-hardware.org/?probe=0c5e4a2345) | Oct 02, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [31df81c76d](https://linux-hardware.org/?probe=31df81c76d) | Sep 30, 2021 |
| HP            | 0AACh                       | Desktop     | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [ba4f1bda7d](https://linux-hardware.org/?probe=ba4f1bda7d) | Sep 30, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [8fa77435f7](https://linux-hardware.org/?probe=8fa77435f7) | Sep 29, 2021 |
| Medion        | B460H6-EM                   | Desktop     | [b461764429](https://linux-hardware.org/?probe=b461764429) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [171fc1cb46](https://linux-hardware.org/?probe=171fc1cb46) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [f9373d8ba5](https://linux-hardware.org/?probe=f9373d8ba5) | Sep 27, 2021 |
| MSI           | MS-7211                     | Desktop     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [89783ad217](https://linux-hardware.org/?probe=89783ad217) | Sep 24, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [867138c338](https://linux-hardware.org/?probe=867138c338) | Sep 22, 2021 |
| Lenovo        | ThinkPad X230 204016Z1ZS    | Notebook    | [eb1d7abffc](https://linux-hardware.org/?probe=eb1d7abffc) | Sep 21, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | Desktop     | [7ded59f42f](https://linux-hardware.org/?probe=7ded59f42f) | Sep 21, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [a4488fd2fe](https://linux-hardware.org/?probe=a4488fd2fe) | Sep 19, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [f9509414bc](https://linux-hardware.org/?probe=f9509414bc) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [506a3682b9](https://linux-hardware.org/?probe=506a3682b9) | Sep 15, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [badf707f13](https://linux-hardware.org/?probe=badf707f13) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c8e465fcb0](https://linux-hardware.org/?probe=c8e465fcb0) | Sep 14, 2021 |
| Unknown       | Unknown                     | Notebook    | [6670bba1d8](https://linux-hardware.org/?probe=6670bba1d8) | Sep 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [94e64b5b30](https://linux-hardware.org/?probe=94e64b5b30) | Sep 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0a2430ae78](https://linux-hardware.org/?probe=0a2430ae78) | Sep 10, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7fdf917680](https://linux-hardware.org/?probe=7fdf917680) | Sep 09, 2021 |
| Dell          | Latitude 7420               | Notebook    | [225b6a0d52](https://linux-hardware.org/?probe=225b6a0d52) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [d05cb87743](https://linux-hardware.org/?probe=d05cb87743) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| Dell          | Latitude E6430              | Notebook    | [e02c871576](https://linux-hardware.org/?probe=e02c871576) | Sep 06, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d2627b08e](https://linux-hardware.org/?probe=5d2627b08e) | Sep 06, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [22390a295d](https://linux-hardware.org/?probe=22390a295d) | Sep 04, 2021 |
| Fujitsu       | LIFEBOOK U9310              | Notebook    | [48113d6636](https://linux-hardware.org/?probe=48113d6636) | Sep 02, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7467c9452c](https://linux-hardware.org/?probe=7467c9452c) | Sep 01, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [08ad3775b8](https://linux-hardware.org/?probe=08ad3775b8) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | Notebook    | [8e46956f05](https://linux-hardware.org/?probe=8e46956f05) | Aug 31, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | Notebook    | [8512904445](https://linux-hardware.org/?probe=8512904445) | Aug 29, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [93e2baa57a](https://linux-hardware.org/?probe=93e2baa57a) | Aug 29, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b8aadba448](https://linux-hardware.org/?probe=b8aadba448) | Aug 28, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [adfa074262](https://linux-hardware.org/?probe=adfa074262) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [f15a7392b9](https://linux-hardware.org/?probe=f15a7392b9) | Aug 27, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [fa40b359a1](https://linux-hardware.org/?probe=fa40b359a1) | Aug 27, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [4198aeb0a0](https://linux-hardware.org/?probe=4198aeb0a0) | Aug 26, 2021 |
| Dell          | Latitude 5480               | Notebook    | [3374e57369](https://linux-hardware.org/?probe=3374e57369) | Aug 25, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [fe8aa54fcd](https://linux-hardware.org/?probe=fe8aa54fcd) | Aug 25, 2021 |
| HP            | Compaq 8710w (GC124EA#AK... | Notebook    | [d7475c57ca](https://linux-hardware.org/?probe=d7475c57ca) | Aug 24, 2021 |
| HP            | ProBook 6360b               | Notebook    | [f8a9a512b2](https://linux-hardware.org/?probe=f8a9a512b2) | Aug 24, 2021 |
| HP            | ProBook 6360b               | Notebook    | [beb76e16b5](https://linux-hardware.org/?probe=beb76e16b5) | Aug 24, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bf921c6ff6](https://linux-hardware.org/?probe=bf921c6ff6) | Aug 23, 2021 |
| Dell          | Latitude 7490               | Notebook    | [b4759deb9a](https://linux-hardware.org/?probe=b4759deb9a) | Aug 21, 2021 |
| Acer          | RS780HVF                    | Desktop     | [f051228785](https://linux-hardware.org/?probe=f051228785) | Aug 21, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [97a8f28916](https://linux-hardware.org/?probe=97a8f28916) | Aug 21, 2021 |
| HP            | 255 G1                      | Notebook    | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [78377f3635](https://linux-hardware.org/?probe=78377f3635) | Aug 17, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [e91d03b0c4](https://linux-hardware.org/?probe=e91d03b0c4) | Aug 17, 2021 |
| Dell          | Latitude E6430              | Notebook    | [afe966ff62](https://linux-hardware.org/?probe=afe966ff62) | Aug 17, 2021 |
| Dell          | Latitude E6500              | Notebook    | [a707e64d52](https://linux-hardware.org/?probe=a707e64d52) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8bf626f6b3](https://linux-hardware.org/?probe=8bf626f6b3) | Aug 15, 2021 |
| Acer          | RS780HVF                    | Desktop     | [32c3b00b51](https://linux-hardware.org/?probe=32c3b00b51) | Aug 14, 2021 |
| Acer          | RS780HVF                    | Desktop     | [858844ae39](https://linux-hardware.org/?probe=858844ae39) | Aug 14, 2021 |
| Acer          | Predator G3-710             | Desktop     | [bc8ec0cacc](https://linux-hardware.org/?probe=bc8ec0cacc) | Aug 14, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b656e3aec4](https://linux-hardware.org/?probe=b656e3aec4) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [11f9ccb3ad](https://linux-hardware.org/?probe=11f9ccb3ad) | Aug 13, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | Notebook    | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [33a532dde2](https://linux-hardware.org/?probe=33a532dde2) | Aug 09, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [8d464633db](https://linux-hardware.org/?probe=8d464633db) | Aug 08, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [bd3d1ed844](https://linux-hardware.org/?probe=bd3d1ed844) | Aug 08, 2021 |
| Lenovo        | ThinkPad X270 20HMS70400    | Notebook    | [6b647baf7c](https://linux-hardware.org/?probe=6b647baf7c) | Aug 07, 2021 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [ab5514ae70](https://linux-hardware.org/?probe=ab5514ae70) | Aug 06, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [47fca1c82c](https://linux-hardware.org/?probe=47fca1c82c) | Aug 05, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [a5d694843c](https://linux-hardware.org/?probe=a5d694843c) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | Notebook    | [0297e70b90](https://linux-hardware.org/?probe=0297e70b90) | Aug 04, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [ec6b248ebe](https://linux-hardware.org/?probe=ec6b248ebe) | Aug 03, 2021 |
| ASRock        | 939A785GMH/128M             | Desktop     | [fe09c8fdc1](https://linux-hardware.org/?probe=fe09c8fdc1) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AN007FM... | Notebook    | [ba75506849](https://linux-hardware.org/?probe=ba75506849) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d6735c5f18](https://linux-hardware.org/?probe=d6735c5f18) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [734237b1dc](https://linux-hardware.org/?probe=734237b1dc) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9ce0842819](https://linux-hardware.org/?probe=9ce0842819) | Aug 02, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0451bc276f](https://linux-hardware.org/?probe=0451bc276f) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| ASUSTek       | P5K-VM                      | Desktop     | [1b2a02afbe](https://linux-hardware.org/?probe=1b2a02afbe) | Jul 31, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [abb1e8ea82](https://linux-hardware.org/?probe=abb1e8ea82) | Jul 31, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [6e097e987f](https://linux-hardware.org/?probe=6e097e987f) | Jul 29, 2021 |
| HP            | 8437                        | Desktop     | [06f61b9a3f](https://linux-hardware.org/?probe=06f61b9a3f) | Jul 27, 2021 |
| HP            | 8437                        | Desktop     | [3e06775292](https://linux-hardware.org/?probe=3e06775292) | Jul 27, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [643094a68a](https://linux-hardware.org/?probe=643094a68a) | Jul 26, 2021 |
| Acer          | AO725                       | Notebook    | [4e27f519f7](https://linux-hardware.org/?probe=4e27f519f7) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| Sony          | VPCEH3D0E                   | Notebook    | [2d04f2e0e8](https://linux-hardware.org/?probe=2d04f2e0e8) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| HP            | 8437                        | Desktop     | [0764df2f0a](https://linux-hardware.org/?probe=0764df2f0a) | Jul 24, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [2c81844355](https://linux-hardware.org/?probe=2c81844355) | Jul 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| ASRock        | 939A785GMH/128M             | Desktop     | [f363c1063a](https://linux-hardware.org/?probe=f363c1063a) | Jul 22, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [384c090a20](https://linux-hardware.org/?probe=384c090a20) | Jul 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTS0... | Notebook    | [550f9db7cd](https://linux-hardware.org/?probe=550f9db7cd) | Jul 22, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [99b906c497](https://linux-hardware.org/?probe=99b906c497) | Jul 21, 2021 |
| Dell          | 0GH911                      | Desktop     | [2aa93c89cd](https://linux-hardware.org/?probe=2aa93c89cd) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Dell          | 0VHWTR A01                  | Desktop     | [5116710fe0](https://linux-hardware.org/?probe=5116710fe0) | Jul 20, 2021 |
| HP            | 802F                        | Desktop     | [469561ff27](https://linux-hardware.org/?probe=469561ff27) | Jul 20, 2021 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [4f9f3cbb83](https://linux-hardware.org/?probe=4f9f3cbb83) | Jul 18, 2021 |
| ASUSTek       | NARRA2                      | Desktop     | [e7e7f905c7](https://linux-hardware.org/?probe=e7e7f905c7) | Jul 17, 2021 |
| ASUSTek       | NARRA2                      | Desktop     | [40f65831a3](https://linux-hardware.org/?probe=40f65831a3) | Jul 17, 2021 |
| MSI           | GS60 2PC Ghost              | Notebook    | [cf537038dd](https://linux-hardware.org/?probe=cf537038dd) | Jul 17, 2021 |
| Dell          | Latitude E7470              | Notebook    | [8c32d73d55](https://linux-hardware.org/?probe=8c32d73d55) | Jul 16, 2021 |
| Dell          | Latitude E7470              | Notebook    | [22583cadb6](https://linux-hardware.org/?probe=22583cadb6) | Jul 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [532e266dcb](https://linux-hardware.org/?probe=532e266dcb) | Jul 13, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [f5ec156890](https://linux-hardware.org/?probe=f5ec156890) | Jul 12, 2021 |
| Samsung       | R530/R730                   | Notebook    | [103edb36d2](https://linux-hardware.org/?probe=103edb36d2) | Jul 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d52de582e8](https://linux-hardware.org/?probe=d52de582e8) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [9f1b7a37f2](https://linux-hardware.org/?probe=9f1b7a37f2) | Jul 07, 2021 |
| Dell          | G7 7700                     | Notebook    | [6fc41408bf](https://linux-hardware.org/?probe=6fc41408bf) | Jul 07, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [d5eb8c32fb](https://linux-hardware.org/?probe=d5eb8c32fb) | Jul 06, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [557af42b3d](https://linux-hardware.org/?probe=557af42b3d) | Jul 03, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [def9f42f6c](https://linux-hardware.org/?probe=def9f42f6c) | Jul 02, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| Dell          | Precision 5540              | Notebook    | [a685a9c5bb](https://linux-hardware.org/?probe=a685a9c5bb) | Jun 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e2743844ad](https://linux-hardware.org/?probe=e2743844ad) | Jun 29, 2021 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [2043830384](https://linux-hardware.org/?probe=2043830384) | Jun 26, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [39f8c7f885](https://linux-hardware.org/?probe=39f8c7f885) | Jun 26, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [110b313bc0](https://linux-hardware.org/?probe=110b313bc0) | Jun 25, 2021 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [52199864f7](https://linux-hardware.org/?probe=52199864f7) | Jun 24, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e966d318da](https://linux-hardware.org/?probe=e966d318da) | Jun 23, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [7767a1cde7](https://linux-hardware.org/?probe=7767a1cde7) | Jun 23, 2021 |
| Dell          | Precision 5550              | Notebook    | [646d84cc95](https://linux-hardware.org/?probe=646d84cc95) | Jun 23, 2021 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [fa3749c0c0](https://linux-hardware.org/?probe=fa3749c0c0) | Jun 22, 2021 |
| IBM           | ThinkPad T43 2668F7G        | Notebook    | [93c8e53b04](https://linux-hardware.org/?probe=93c8e53b04) | Jun 15, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [8ec235f1f1](https://linux-hardware.org/?probe=8ec235f1f1) | Jun 13, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [ce648ba480](https://linux-hardware.org/?probe=ce648ba480) | Jun 12, 2021 |
| Dell          | 0GH911                      | Desktop     | [3d8aec55af](https://linux-hardware.org/?probe=3d8aec55af) | Jun 10, 2021 |
| HP            | Compaq 8510p                | Notebook    | [c371bbdff4](https://linux-hardware.org/?probe=c371bbdff4) | Jun 09, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [54b62ad499](https://linux-hardware.org/?probe=54b62ad499) | Jun 08, 2021 |
| ASUSTek       | K53U                        | Notebook    | [3acb45024a](https://linux-hardware.org/?probe=3acb45024a) | Jun 08, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [e0db4d0875](https://linux-hardware.org/?probe=e0db4d0875) | Jun 08, 2021 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [3764e87d16](https://linux-hardware.org/?probe=3764e87d16) | Jun 07, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [493278d567](https://linux-hardware.org/?probe=493278d567) | Jun 05, 2021 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [49a0eec9f5](https://linux-hardware.org/?probe=49a0eec9f5) | Jun 05, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a750453ba5](https://linux-hardware.org/?probe=a750453ba5) | Jun 04, 2021 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [421fa035ee](https://linux-hardware.org/?probe=421fa035ee) | Jun 03, 2021 |
| Dell          | Latitude E7470              | Notebook    | [6be76778ae](https://linux-hardware.org/?probe=6be76778ae) | Jun 03, 2021 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [a434845c16](https://linux-hardware.org/?probe=a434845c16) | Jun 03, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [baad40baaa](https://linux-hardware.org/?probe=baad40baaa) | Jun 01, 2021 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [ef97789a6a](https://linux-hardware.org/?probe=ef97789a6a) | May 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [a266b8dd81](https://linux-hardware.org/?probe=a266b8dd81) | May 27, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [30e8995988](https://linux-hardware.org/?probe=30e8995988) | May 27, 2021 |
| HP            | Compaq 8510p                | Notebook    | [7e17cf2706](https://linux-hardware.org/?probe=7e17cf2706) | May 26, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [541b3e9cba](https://linux-hardware.org/?probe=541b3e9cba) | May 25, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [ddfe32e6ab](https://linux-hardware.org/?probe=ddfe32e6ab) | May 25, 2021 |
| Acer          | Aspire 8950G                | Notebook    | [d65fb86955](https://linux-hardware.org/?probe=d65fb86955) | May 22, 2021 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [66c62dc8f8](https://linux-hardware.org/?probe=66c62dc8f8) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [1b1a173884](https://linux-hardware.org/?probe=1b1a173884) | May 22, 2021 |
| HP            | 8433 11                     | Desktop     | [8670420e76](https://linux-hardware.org/?probe=8670420e76) | May 21, 2021 |
| HP            | 350 G1                      | Notebook    | [949ae1ce88](https://linux-hardware.org/?probe=949ae1ce88) | May 20, 2021 |
| ASRock        | X99M Extreme4               | Desktop     | [fba004a752](https://linux-hardware.org/?probe=fba004a752) | May 20, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [60eb674c8f](https://linux-hardware.org/?probe=60eb674c8f) | May 19, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [fa879ee1d2](https://linux-hardware.org/?probe=fa879ee1d2) | May 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [249ab0aa24](https://linux-hardware.org/?probe=249ab0aa24) | May 19, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [09351c4654](https://linux-hardware.org/?probe=09351c4654) | May 18, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [8b2100d9ad](https://linux-hardware.org/?probe=8b2100d9ad) | May 14, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [d125abf69e](https://linux-hardware.org/?probe=d125abf69e) | May 12, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [a981f9a0c5](https://linux-hardware.org/?probe=a981f9a0c5) | May 12, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ab2366fd14](https://linux-hardware.org/?probe=ab2366fd14) | May 11, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [714a70d40a](https://linux-hardware.org/?probe=714a70d40a) | May 07, 2021 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [4482a1fb69](https://linux-hardware.org/?probe=4482a1fb69) | May 06, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [efc8ac4c79](https://linux-hardware.org/?probe=efc8ac4c79) | May 06, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [3ea8d93c76](https://linux-hardware.org/?probe=3ea8d93c76) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [a32714d409](https://linux-hardware.org/?probe=a32714d409) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [eb8ca2d9d2](https://linux-hardware.org/?probe=eb8ca2d9d2) | May 05, 2021 |
| Dell          | Latitude E7270              | Notebook    | [6708f53385](https://linux-hardware.org/?probe=6708f53385) | May 04, 2021 |
| HP            | 3647h                       | Desktop     | [bd39210291](https://linux-hardware.org/?probe=bd39210291) | May 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [9482db99b9](https://linux-hardware.org/?probe=9482db99b9) | May 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [ef52974aaf](https://linux-hardware.org/?probe=ef52974aaf) | May 03, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [1c94c5b005](https://linux-hardware.org/?probe=1c94c5b005) | May 03, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [9eb409c988](https://linux-hardware.org/?probe=9eb409c988) | May 02, 2021 |
| MSI           | 2A9C                        | Desktop     | [fbb37a1ceb](https://linux-hardware.org/?probe=fbb37a1ceb) | May 02, 2021 |
| MSI           | 2A9C                        | Desktop     | [1b4573b9c5](https://linux-hardware.org/?probe=1b4573b9c5) | May 02, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [4ab0e6b099](https://linux-hardware.org/?probe=4ab0e6b099) | May 01, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [40e07b4dad](https://linux-hardware.org/?probe=40e07b4dad) | Apr 26, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [93eb4a6a39](https://linux-hardware.org/?probe=93eb4a6a39) | Apr 24, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c586a3a771](https://linux-hardware.org/?probe=c586a3a771) | Apr 20, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [7e5ffea0b6](https://linux-hardware.org/?probe=7e5ffea0b6) | Apr 20, 2021 |
| Lenovo        | B70-80 80MR                 | Notebook    | [edef8dfd8b](https://linux-hardware.org/?probe=edef8dfd8b) | Apr 19, 2021 |
| HP            | 1998                        | Desktop     | [9bb6ae0565](https://linux-hardware.org/?probe=9bb6ae0565) | Apr 18, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [6a0c5e5bda](https://linux-hardware.org/?probe=6a0c5e5bda) | Apr 18, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [6ac1485bc6](https://linux-hardware.org/?probe=6ac1485bc6) | Apr 17, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [d01dac7a8f](https://linux-hardware.org/?probe=d01dac7a8f) | Apr 16, 2021 |
| Lenovo        | B50-45 80F0                 | Notebook    | [0558c9e99e](https://linux-hardware.org/?probe=0558c9e99e) | Apr 16, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [7ca0cd3696](https://linux-hardware.org/?probe=7ca0cd3696) | Apr 15, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [3274addf89](https://linux-hardware.org/?probe=3274addf89) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9776a806ac](https://linux-hardware.org/?probe=9776a806ac) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [597f1536e2](https://linux-hardware.org/?probe=597f1536e2) | Apr 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [8a8adf8790](https://linux-hardware.org/?probe=8a8adf8790) | Apr 12, 2021 |
| Pegatron      | APX85-GS                    | Desktop     | [3a6accac1f](https://linux-hardware.org/?probe=3a6accac1f) | Apr 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [12fb9fd662](https://linux-hardware.org/?probe=12fb9fd662) | Apr 12, 2021 |
| ASUSTek       | P5E                         | Desktop     | [8689ac73b3](https://linux-hardware.org/?probe=8689ac73b3) | Apr 11, 2021 |
| Pegatron      | 2A99                        | Desktop     | [07a84a3b4d](https://linux-hardware.org/?probe=07a84a3b4d) | Apr 11, 2021 |
| MSI           | GL62M 7REX                  | Notebook    | [8ee2678b38](https://linux-hardware.org/?probe=8ee2678b38) | Apr 10, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [258fbf86ed](https://linux-hardware.org/?probe=258fbf86ed) | Apr 09, 2021 |
| HP            | 0A00h                       | Desktop     | [144a5f7819](https://linux-hardware.org/?probe=144a5f7819) | Apr 09, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| Pegatron      | 2A72h                       | Desktop     | [e1fff3ade4](https://linux-hardware.org/?probe=e1fff3ade4) | Apr 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [c480530d42](https://linux-hardware.org/?probe=c480530d42) | Apr 07, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ecae2e7ad8](https://linux-hardware.org/?probe=ecae2e7ad8) | Apr 06, 2021 |
| Samsung       | R530/R730                   | Notebook    | [0085bebd03](https://linux-hardware.org/?probe=0085bebd03) | Apr 05, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [6534232c53](https://linux-hardware.org/?probe=6534232c53) | Apr 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [e88c887878](https://linux-hardware.org/?probe=e88c887878) | Apr 01, 2021 |
| HP            | EliteBook 755 G2            | Notebook    | [12cd60c247](https://linux-hardware.org/?probe=12cd60c247) | Mar 31, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [4ac35c901a](https://linux-hardware.org/?probe=4ac35c901a) | Mar 30, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [2838e1ca6c](https://linux-hardware.org/?probe=2838e1ca6c) | Mar 30, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [d8f1bccb78](https://linux-hardware.org/?probe=d8f1bccb78) | Mar 29, 2021 |
| ASRock        | ALiveNF6G-GLAN              | Desktop     | [1f409f9bf1](https://linux-hardware.org/?probe=1f409f9bf1) | Mar 28, 2021 |
| Lenovo        | ThinkPad T430 2349UWT       | Notebook    | [d6edf7c2df](https://linux-hardware.org/?probe=d6edf7c2df) | Mar 28, 2021 |
| HP            | 1589                        | Desktop     | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [54845ca16f](https://linux-hardware.org/?probe=54845ca16f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [04469024ca](https://linux-hardware.org/?probe=04469024ca) | Mar 27, 2021 |
| HP            | 8054                        | Desktop     | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | Desktop     | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [1f11381bfb](https://linux-hardware.org/?probe=1f11381bfb) | Mar 27, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [c412261d89](https://linux-hardware.org/?probe=c412261d89) | Mar 26, 2021 |
| HP            | ZBook 15 G4                 | Notebook    | [4d3778017f](https://linux-hardware.org/?probe=4d3778017f) | Mar 25, 2021 |
| Samsung       | SF311/SF411/SF511           | Notebook    | [fb1261d331](https://linux-hardware.org/?probe=fb1261d331) | Mar 25, 2021 |
| HP            | 802F                        | Desktop     | [ae40d5cbc9](https://linux-hardware.org/?probe=ae40d5cbc9) | Mar 24, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [ccb057337e](https://linux-hardware.org/?probe=ccb057337e) | Mar 23, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [91409f3c71](https://linux-hardware.org/?probe=91409f3c71) | Mar 23, 2021 |
| Shuttle       | FZ77                        | Desktop     | [ca3dfc266d](https://linux-hardware.org/?probe=ca3dfc266d) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0debcb68ae](https://linux-hardware.org/?probe=0debcb68ae) | Mar 18, 2021 |
| Lenovo        | B50-45 80F0                 | Notebook    | [9af2b46c0a](https://linux-hardware.org/?probe=9af2b46c0a) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [50b82af935](https://linux-hardware.org/?probe=50b82af935) | Mar 18, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [72fc5ffa15](https://linux-hardware.org/?probe=72fc5ffa15) | Mar 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [3c98763834](https://linux-hardware.org/?probe=3c98763834) | Mar 17, 2021 |
| HP            | 1495                        | Desktop     | [23947d4a1e](https://linux-hardware.org/?probe=23947d4a1e) | Mar 17, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [48f8273cdb](https://linux-hardware.org/?probe=48f8273cdb) | Mar 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [e9c99960d1](https://linux-hardware.org/?probe=e9c99960d1) | Mar 16, 2021 |
| ASUSTek       | P5N32-E SLI                 | Desktop     | [11caeb50ac](https://linux-hardware.org/?probe=11caeb50ac) | Mar 16, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| Acer          | Aspire C24-865              | All in one  | [6dc98b8074](https://linux-hardware.org/?probe=6dc98b8074) | Mar 16, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [2cbefa6c90](https://linux-hardware.org/?probe=2cbefa6c90) | Mar 15, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ad7470fc89](https://linux-hardware.org/?probe=ad7470fc89) | Mar 15, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [2417d2d1b5](https://linux-hardware.org/?probe=2417d2d1b5) | Mar 14, 2021 |
| MSI           | H81M-P33                    | Desktop     | [9487818af0](https://linux-hardware.org/?probe=9487818af0) | Mar 13, 2021 |
| HP            | 859C                        | Desktop     | [6434de9da7](https://linux-hardware.org/?probe=6434de9da7) | Mar 13, 2021 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [feedeb2b69](https://linux-hardware.org/?probe=feedeb2b69) | Mar 12, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [c6866f0d34](https://linux-hardware.org/?probe=c6866f0d34) | Mar 10, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [112bdb4e2a](https://linux-hardware.org/?probe=112bdb4e2a) | Mar 09, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [e83e8ffa64](https://linux-hardware.org/?probe=e83e8ffa64) | Mar 08, 2021 |
| Lenovo        | ThinkPad T450 20BV001YMS    | Notebook    | [57449243ca](https://linux-hardware.org/?probe=57449243ca) | Mar 07, 2021 |
| Gigabyte      | MZ31-AR0-00 01010101        | Server      | [6d486a7ee9](https://linux-hardware.org/?probe=6d486a7ee9) | Mar 05, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [ee5505ce8e](https://linux-hardware.org/?probe=ee5505ce8e) | Mar 05, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [c4548cb133](https://linux-hardware.org/?probe=c4548cb133) | Mar 04, 2021 |
| ASUSTek       | P5E                         | Desktop     | [adac4a8f70](https://linux-hardware.org/?probe=adac4a8f70) | Mar 04, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [857a1c6e52](https://linux-hardware.org/?probe=857a1c6e52) | Mar 04, 2021 |
| Intel         | DH77KC AAG39641-401         | Desktop     | [1af2ede26c](https://linux-hardware.org/?probe=1af2ede26c) | Mar 03, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [3e423c7d87](https://linux-hardware.org/?probe=3e423c7d87) | Mar 03, 2021 |
| ASUSTek       | UX32A                       | Notebook    | [7debc0a27d](https://linux-hardware.org/?probe=7debc0a27d) | Mar 02, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [8b50e7792e](https://linux-hardware.org/?probe=8b50e7792e) | Mar 02, 2021 |
| Gigabyte      | Z490 VISION D               | Desktop     | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| Lenovo        | ThinkPad E580 20KS001RMX    | Notebook    | [5bcb97d47f](https://linux-hardware.org/?probe=5bcb97d47f) | Feb 28, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [1f91d9a631](https://linux-hardware.org/?probe=1f91d9a631) | Feb 27, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [ad443f47c2](https://linux-hardware.org/?probe=ad443f47c2) | Feb 27, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [987d795cb7](https://linux-hardware.org/?probe=987d795cb7) | Feb 27, 2021 |
| ASUSTek       | K54C                        | Notebook    | [467c86ad9a](https://linux-hardware.org/?probe=467c86ad9a) | Feb 26, 2021 |
| Dell          | Latitude E7470              | Notebook    | [93cf5a0e8b](https://linux-hardware.org/?probe=93cf5a0e8b) | Feb 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [9a68092d87](https://linux-hardware.org/?probe=9a68092d87) | Feb 25, 2021 |
| ASUSTek       | K70IO                       | Notebook    | [49623c33e1](https://linux-hardware.org/?probe=49623c33e1) | Feb 25, 2021 |
| HP            | 805A                        | Desktop     | [26d9d2a996](https://linux-hardware.org/?probe=26d9d2a996) | Feb 25, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [cd111b2c04](https://linux-hardware.org/?probe=cd111b2c04) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | Desktop     | [762e158923](https://linux-hardware.org/?probe=762e158923) | Feb 25, 2021 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [bcbcbdf158](https://linux-hardware.org/?probe=bcbcbdf158) | Feb 25, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5af628a455](https://linux-hardware.org/?probe=5af628a455) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [90fa6e7434](https://linux-hardware.org/?probe=90fa6e7434) | Feb 24, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [601807d0e7](https://linux-hardware.org/?probe=601807d0e7) | Feb 24, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [84ddb6cbec](https://linux-hardware.org/?probe=84ddb6cbec) | Feb 24, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | Notebook    | [8a3e6146db](https://linux-hardware.org/?probe=8a3e6146db) | Feb 23, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [d47c258b89](https://linux-hardware.org/?probe=d47c258b89) | Feb 22, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ccd37902d0](https://linux-hardware.org/?probe=ccd37902d0) | Feb 22, 2021 |
| Dell          | 0YC523                      | Desktop     | [d805d39715](https://linux-hardware.org/?probe=d805d39715) | Feb 22, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [50065d2efb](https://linux-hardware.org/?probe=50065d2efb) | Feb 20, 2021 |
| HP            | Presario CQ56               | Notebook    | [54f5681a51](https://linux-hardware.org/?probe=54f5681a51) | Feb 20, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [c116602ad6](https://linux-hardware.org/?probe=c116602ad6) | Feb 18, 2021 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [b1e9a3d14d](https://linux-hardware.org/?probe=b1e9a3d14d) | Feb 18, 2021 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [d90fd08234](https://linux-hardware.org/?probe=d90fd08234) | Feb 17, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [544e6bde0b](https://linux-hardware.org/?probe=544e6bde0b) | Feb 17, 2021 |
| ECS           | Nettle3                     | Desktop     | [fb2a315c43](https://linux-hardware.org/?probe=fb2a315c43) | Feb 16, 2021 |
| Lenovo        | ThinkPad L490 20Q50020MX    | Notebook    | [24fb34852c](https://linux-hardware.org/?probe=24fb34852c) | Feb 16, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [d91ab98cb0](https://linux-hardware.org/?probe=d91ab98cb0) | Feb 16, 2021 |
| Dell          | 060K5C A04                  | Server      | [33fde2b5fb](https://linux-hardware.org/?probe=33fde2b5fb) | Feb 15, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [33e13fb990](https://linux-hardware.org/?probe=33e13fb990) | Feb 14, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [ce117380dd](https://linux-hardware.org/?probe=ce117380dd) | Feb 14, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [573a6ae3c7](https://linux-hardware.org/?probe=573a6ae3c7) | Feb 14, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [2941ebcde6](https://linux-hardware.org/?probe=2941ebcde6) | Feb 13, 2021 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [21e0385b49](https://linux-hardware.org/?probe=21e0385b49) | Feb 13, 2021 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [9862174836](https://linux-hardware.org/?probe=9862174836) | Feb 13, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d87dd2f698](https://linux-hardware.org/?probe=d87dd2f698) | Feb 12, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [99f3171b76](https://linux-hardware.org/?probe=99f3171b76) | Feb 10, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e052a51f58](https://linux-hardware.org/?probe=e052a51f58) | Feb 10, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [dee973015c](https://linux-hardware.org/?probe=dee973015c) | Feb 09, 2021 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [c0ada2d30c](https://linux-hardware.org/?probe=c0ada2d30c) | Feb 08, 2021 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [71a56734c1](https://linux-hardware.org/?probe=71a56734c1) | Feb 07, 2021 |
| Dell          | Latitude E5470              | Notebook    | [562dbbdcdd](https://linux-hardware.org/?probe=562dbbdcdd) | Feb 07, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [826729feac](https://linux-hardware.org/?probe=826729feac) | Feb 07, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [389456d6b7](https://linux-hardware.org/?probe=389456d6b7) | Feb 06, 2021 |
| Acer          | TravelMate 5744             | Notebook    | [78690829c5](https://linux-hardware.org/?probe=78690829c5) | Feb 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [8370d569ed](https://linux-hardware.org/?probe=8370d569ed) | Feb 06, 2021 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [3e78bc9f2c](https://linux-hardware.org/?probe=3e78bc9f2c) | Feb 06, 2021 |
| Dell          | Precision 3520              | Notebook    | [1e72fdbddc](https://linux-hardware.org/?probe=1e72fdbddc) | Feb 05, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [95af098c68](https://linux-hardware.org/?probe=95af098c68) | Feb 05, 2021 |
| HP            | 0A64h                       | Desktop     | [6b5e34333d](https://linux-hardware.org/?probe=6b5e34333d) | Feb 04, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [e5ac3cd7e2](https://linux-hardware.org/?probe=e5ac3cd7e2) | Feb 04, 2021 |
| Dell          | Precision 3520              | Notebook    | [fb3da7ea03](https://linux-hardware.org/?probe=fb3da7ea03) | Feb 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [47d61a08a0](https://linux-hardware.org/?probe=47d61a08a0) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | Desktop     | [e546964d97](https://linux-hardware.org/?probe=e546964d97) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | Desktop     | [80124b02cf](https://linux-hardware.org/?probe=80124b02cf) | Jan 31, 2021 |
| Samsung       | R530/R730                   | Notebook    | [9b9a4ce82c](https://linux-hardware.org/?probe=9b9a4ce82c) | Jan 31, 2021 |
| ASUSTek       | K73TA                       | Notebook    | [2b15e899ed](https://linux-hardware.org/?probe=2b15e899ed) | Jan 30, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [20789a4459](https://linux-hardware.org/?probe=20789a4459) | Jan 30, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [c0c66476fe](https://linux-hardware.org/?probe=c0c66476fe) | Jan 30, 2021 |
| ASUSTek       | K73TA                       | Notebook    | [0e4b16a1c5](https://linux-hardware.org/?probe=0e4b16a1c5) | Jan 30, 2021 |
| ASUSTek       | P5G41T-M LX PLUS            | Desktop     | [ef58793cd1](https://linux-hardware.org/?probe=ef58793cd1) | Jan 29, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3d1daadbf9](https://linux-hardware.org/?probe=3d1daadbf9) | Jan 28, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [897d7d00d7](https://linux-hardware.org/?probe=897d7d00d7) | Jan 27, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [591c655546](https://linux-hardware.org/?probe=591c655546) | Jan 27, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [10f4ad2179](https://linux-hardware.org/?probe=10f4ad2179) | Jan 27, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [bc43832b9f](https://linux-hardware.org/?probe=bc43832b9f) | Jan 27, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [2d3b61aa15](https://linux-hardware.org/?probe=2d3b61aa15) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [07c16b45cb](https://linux-hardware.org/?probe=07c16b45cb) | Jan 26, 2021 |
| Lenovo        | ThinkPad T430 2349W2P       | Notebook    | [58c2f66dd6](https://linux-hardware.org/?probe=58c2f66dd6) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [0903507e18](https://linux-hardware.org/?probe=0903507e18) | Jan 25, 2021 |
| Acer          | Extensa 5220                | Notebook    | [5d121bc112](https://linux-hardware.org/?probe=5d121bc112) | Jan 25, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [aaedd808e4](https://linux-hardware.org/?probe=aaedd808e4) | Jan 25, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [e6dcbd8319](https://linux-hardware.org/?probe=e6dcbd8319) | Jan 24, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [7718bb2939](https://linux-hardware.org/?probe=7718bb2939) | Jan 24, 2021 |
| Acer          | Extensa 5220                | Notebook    | [138ec8e43b](https://linux-hardware.org/?probe=138ec8e43b) | Jan 24, 2021 |
| AOpen         | D1007 0BB4                  | Desktop     | [8e09b52f79](https://linux-hardware.org/?probe=8e09b52f79) | Jan 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c50f23fd8b](https://linux-hardware.org/?probe=c50f23fd8b) | Jan 23, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [6a6277a771](https://linux-hardware.org/?probe=6a6277a771) | Jan 22, 2021 |
| Dell          | Latitude 7400               | Notebook    | [0ecb2cacfe](https://linux-hardware.org/?probe=0ecb2cacfe) | Jan 22, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [40e24ed53c](https://linux-hardware.org/?probe=40e24ed53c) | Jan 21, 2021 |
| AOpen         | D1007 0BB4                  | Desktop     | [73d0723981](https://linux-hardware.org/?probe=73d0723981) | Jan 21, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [40dbe0488c](https://linux-hardware.org/?probe=40dbe0488c) | Jan 21, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d4d4c84bc5](https://linux-hardware.org/?probe=d4d4c84bc5) | Jan 19, 2021 |
| Lenovo        | ThinkPad L490 20Q50020MX    | Notebook    | [d442be2460](https://linux-hardware.org/?probe=d442be2460) | Jan 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [3d3987411f](https://linux-hardware.org/?probe=3d3987411f) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| HP            | EliteBook 1040 G4           | Notebook    | [b7ba6238f6](https://linux-hardware.org/?probe=b7ba6238f6) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [5d2f2486eb](https://linux-hardware.org/?probe=5d2f2486eb) | Jan 17, 2021 |
| Lenovo        | ThinkPad T420 4236WUL       | Notebook    | [7fcf14c600](https://linux-hardware.org/?probe=7fcf14c600) | Jan 16, 2021 |
| HP            | 844C                        | Desktop     | [f9e65434d6](https://linux-hardware.org/?probe=f9e65434d6) | Jan 16, 2021 |
| Dell          | Latitude 5480               | Notebook    | [de414e3763](https://linux-hardware.org/?probe=de414e3763) | Jan 16, 2021 |
| Dell          | Vostro 5581                 | Notebook    | [b706435c71](https://linux-hardware.org/?probe=b706435c71) | Jan 15, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0e5edf7f67](https://linux-hardware.org/?probe=0e5edf7f67) | Jan 14, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4d2826d61b](https://linux-hardware.org/?probe=4d2826d61b) | Jan 13, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [47744c734e](https://linux-hardware.org/?probe=47744c734e) | Jan 13, 2021 |
| Dell          | 0Y958C A00                  | Desktop     | [6a52898067](https://linux-hardware.org/?probe=6a52898067) | Jan 12, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4b8c49c0dd](https://linux-hardware.org/?probe=4b8c49c0dd) | Jan 10, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [f234ba69b3](https://linux-hardware.org/?probe=f234ba69b3) | Jan 09, 2021 |
| Dell          | Latitude 5410               | Notebook    | [dcbd8fa748](https://linux-hardware.org/?probe=dcbd8fa748) | Jan 09, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [9dafe213ae](https://linux-hardware.org/?probe=9dafe213ae) | Jan 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b36e938e43](https://linux-hardware.org/?probe=b36e938e43) | Jan 05, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [750bd00cb1](https://linux-hardware.org/?probe=750bd00cb1) | Jan 05, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [ed6d998571](https://linux-hardware.org/?probe=ed6d998571) | Jan 04, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [48b31af6f7](https://linux-hardware.org/?probe=48b31af6f7) | Jan 04, 2021 |
| Dell          | 0YC523                      | Desktop     | [ef04db7b3d](https://linux-hardware.org/?probe=ef04db7b3d) | Jan 04, 2021 |
| MSI           | Z170A GAMING M5             | Desktop     | [fde14ce5dd](https://linux-hardware.org/?probe=fde14ce5dd) | Jan 04, 2021 |
| MSI           | Z170A GAMING M5             | Desktop     | [f120a3b7a1](https://linux-hardware.org/?probe=f120a3b7a1) | Jan 04, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [f254fc1794](https://linux-hardware.org/?probe=f254fc1794) | Dec 31, 2020 |
| ASUSTek       | Z87-K                       | Desktop     | [aa039f37b7](https://linux-hardware.org/?probe=aa039f37b7) | Dec 30, 2020 |
| Packard Be... | RS740                       | Desktop     | [5ce58f1cfb](https://linux-hardware.org/?probe=5ce58f1cfb) | Dec 30, 2020 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [f6f6ae0026](https://linux-hardware.org/?probe=f6f6ae0026) | Dec 29, 2020 |
| Lenovo        | ThinkPad W510 431924G       | Notebook    | [e5b63a5115](https://linux-hardware.org/?probe=e5b63a5115) | Dec 29, 2020 |
| MSI           | B360M MORTAR                | Desktop     | [96a4f4f86f](https://linux-hardware.org/?probe=96a4f4f86f) | Dec 29, 2020 |
| MSI           | B360M MORTAR                | Desktop     | [770704b41d](https://linux-hardware.org/?probe=770704b41d) | Dec 29, 2020 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a4ad398189](https://linux-hardware.org/?probe=a4ad398189) | Dec 28, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [38bf55661f](https://linux-hardware.org/?probe=38bf55661f) | Dec 28, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9c1f8e8a57](https://linux-hardware.org/?probe=9c1f8e8a57) | Dec 28, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [7308662eff](https://linux-hardware.org/?probe=7308662eff) | Dec 28, 2020 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Dell          | Latitude E6540              | Notebook    | [f5a9ac4cec](https://linux-hardware.org/?probe=f5a9ac4cec) | Dec 27, 2020 |
| Apple         | MacBookAir5,2               | Notebook    | [7db2c6e8e1](https://linux-hardware.org/?probe=7db2c6e8e1) | Dec 27, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [ad51692f6a](https://linux-hardware.org/?probe=ad51692f6a) | Dec 26, 2020 |
| Apple         | MacBook10,1                 | Notebook    | [ab77e34c6e](https://linux-hardware.org/?probe=ab77e34c6e) | Dec 26, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY007... | Notebook    | [92e373f93e](https://linux-hardware.org/?probe=92e373f93e) | Dec 25, 2020 |
| Intel         | D34010WYK H14771-303        | Desktop     | [3a3ce906e2](https://linux-hardware.org/?probe=3a3ce906e2) | Dec 25, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [d3a90166ed](https://linux-hardware.org/?probe=d3a90166ed) | Dec 23, 2020 |
| Dell          | Latitude E6500              | Notebook    | [2745d38e45](https://linux-hardware.org/?probe=2745d38e45) | Dec 22, 2020 |
| Lenovo        | G505s 20255                 | Notebook    | [88c214adee](https://linux-hardware.org/?probe=88c214adee) | Dec 22, 2020 |
| HP            | EliteBook 8760w             | Notebook    | [36d7439921](https://linux-hardware.org/?probe=36d7439921) | Dec 20, 2020 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [4b40fc00f6](https://linux-hardware.org/?probe=4b40fc00f6) | Dec 20, 2020 |
| HP            | 1850                        | Desktop     | [a92e22af3c](https://linux-hardware.org/?probe=a92e22af3c) | Dec 19, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [822e9847fc](https://linux-hardware.org/?probe=822e9847fc) | Dec 19, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [21eff471d2](https://linux-hardware.org/?probe=21eff471d2) | Dec 19, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [864204221a](https://linux-hardware.org/?probe=864204221a) | Dec 18, 2020 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [2eb3ffc86c](https://linux-hardware.org/?probe=2eb3ffc86c) | Dec 18, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [48b96a1eb2](https://linux-hardware.org/?probe=48b96a1eb2) | Dec 18, 2020 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [5a169ac50d](https://linux-hardware.org/?probe=5a169ac50d) | Dec 18, 2020 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [53bda46668](https://linux-hardware.org/?probe=53bda46668) | Dec 17, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [4e7ff831eb](https://linux-hardware.org/?probe=4e7ff831eb) | Dec 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| ASUSTek       | G751JT                      | Notebook    | [dc87c4f0ee](https://linux-hardware.org/?probe=dc87c4f0ee) | Dec 14, 2020 |
| Lenovo        | ThinkPad X301 4057W3A       | Notebook    | [ca140372c9](https://linux-hardware.org/?probe=ca140372c9) | Dec 13, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [7aea4d859f](https://linux-hardware.org/?probe=7aea4d859f) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [0b3c20a9d9](https://linux-hardware.org/?probe=0b3c20a9d9) | Dec 12, 2020 |
| ASUSTek       | H110M-C                     | Desktop     | [cde1c20a36](https://linux-hardware.org/?probe=cde1c20a36) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [1aedfd747c](https://linux-hardware.org/?probe=1aedfd747c) | Dec 12, 2020 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [16778aa65b](https://linux-hardware.org/?probe=16778aa65b) | Dec 11, 2020 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [79400c58bc](https://linux-hardware.org/?probe=79400c58bc) | Dec 11, 2020 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [3167aca45c](https://linux-hardware.org/?probe=3167aca45c) | Dec 10, 2020 |
| Apple         | MacBookAir3,2               | Notebook    | [da600a761d](https://linux-hardware.org/?probe=da600a761d) | Dec 10, 2020 |
| HP            | 2AF3                        | Desktop     | [66cb088231](https://linux-hardware.org/?probe=66cb088231) | Dec 10, 2020 |
| HP            | 2AF3                        | Desktop     | [839c9749a0](https://linux-hardware.org/?probe=839c9749a0) | Dec 10, 2020 |
| ASUSTek       | M4A785T-M                   | Desktop     | [44e7dff3d3](https://linux-hardware.org/?probe=44e7dff3d3) | Dec 10, 2020 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [b9e091029f](https://linux-hardware.org/?probe=b9e091029f) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [84feb3d2f6](https://linux-hardware.org/?probe=84feb3d2f6) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [92ad61acb2](https://linux-hardware.org/?probe=92ad61acb2) | Dec 10, 2020 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [37b50cd4d6](https://linux-hardware.org/?probe=37b50cd4d6) | Dec 09, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e4dc25a528](https://linux-hardware.org/?probe=e4dc25a528) | Dec 09, 2020 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [27f9412b8a](https://linux-hardware.org/?probe=27f9412b8a) | Dec 08, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [5a3c92338e](https://linux-hardware.org/?probe=5a3c92338e) | Dec 08, 2020 |
| HP            | Pavilion dv2000 (RN081EA... | Notebook    | [efffe561da](https://linux-hardware.org/?probe=efffe561da) | Dec 07, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [0347053bb5](https://linux-hardware.org/?probe=0347053bb5) | Dec 06, 2020 |
| Unknown       | Unknown                     | Notebook    | [32c7f47910](https://linux-hardware.org/?probe=32c7f47910) | Dec 06, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [8b9e3a522e](https://linux-hardware.org/?probe=8b9e3a522e) | Dec 05, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [19ad2b41f0](https://linux-hardware.org/?probe=19ad2b41f0) | Dec 02, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [5fcb11c8cc](https://linux-hardware.org/?probe=5fcb11c8cc) | Dec 02, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [17a41f14d5](https://linux-hardware.org/?probe=17a41f14d5) | Dec 02, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [c60a02a67d](https://linux-hardware.org/?probe=c60a02a67d) | Dec 01, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [48c0620183](https://linux-hardware.org/?probe=48c0620183) | Dec 01, 2020 |
| Unknown       | Unknown                     | Notebook    | [d3ce335695](https://linux-hardware.org/?probe=d3ce335695) | Dec 01, 2020 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [0d011c1658](https://linux-hardware.org/?probe=0d011c1658) | Nov 30, 2020 |
| Dell          | Vostro 5568                 | Notebook    | [fdfdbf71f3](https://linux-hardware.org/?probe=fdfdbf71f3) | Nov 29, 2020 |
| HP            | 350 G2                      | Notebook    | [c36419b264](https://linux-hardware.org/?probe=c36419b264) | Nov 28, 2020 |
| HP            | 350 G2                      | Notebook    | [e075d2aae9](https://linux-hardware.org/?probe=e075d2aae9) | Nov 28, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [45e6832bd6](https://linux-hardware.org/?probe=45e6832bd6) | Nov 26, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [cc791659ec](https://linux-hardware.org/?probe=cc791659ec) | Nov 25, 2020 |
| Acer          | Aspire TC-603               | Desktop     | [79605fa1a1](https://linux-hardware.org/?probe=79605fa1a1) | Nov 24, 2020 |
| Dell          | XPS 15 9500                 | Notebook    | [97c1978e12](https://linux-hardware.org/?probe=97c1978e12) | Nov 24, 2020 |
| Dell          | XPS 15 9500                 | Notebook    | [3b0c917efa](https://linux-hardware.org/?probe=3b0c917efa) | Nov 24, 2020 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [19c11c3ffd](https://linux-hardware.org/?probe=19c11c3ffd) | Nov 24, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [63ba982c79](https://linux-hardware.org/?probe=63ba982c79) | Nov 23, 2020 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [f4e6fa8cea](https://linux-hardware.org/?probe=f4e6fa8cea) | Nov 22, 2020 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [a26299780d](https://linux-hardware.org/?probe=a26299780d) | Nov 22, 2020 |
| Lenovo        | 371C SDK0J40700 WIN 3258... | All in one  | [b2ea83f411](https://linux-hardware.org/?probe=b2ea83f411) | Nov 21, 2020 |
| Acer          | NG-VX5-591G-52AT            | Notebook    | [304a828df3](https://linux-hardware.org/?probe=304a828df3) | Nov 20, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cd25862710](https://linux-hardware.org/?probe=cd25862710) | Nov 20, 2020 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [fcfb9d1f17](https://linux-hardware.org/?probe=fcfb9d1f17) | Nov 19, 2020 |
| HP            | 198E                        | Desktop     | [1c885683dc](https://linux-hardware.org/?probe=1c885683dc) | Nov 19, 2020 |
| Lenovo        | ThinkPad X250 20CM004VMS    | Notebook    | [c4b4e94df8](https://linux-hardware.org/?probe=c4b4e94df8) | Nov 18, 2020 |
| Lenovo        | ThinkPad X250 20CM004VMS    | Notebook    | [7b4d4bf272](https://linux-hardware.org/?probe=7b4d4bf272) | Nov 18, 2020 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [e7fe53d106](https://linux-hardware.org/?probe=e7fe53d106) | Nov 18, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2e4848ae3d](https://linux-hardware.org/?probe=2e4848ae3d) | Nov 15, 2020 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [5d53e48607](https://linux-hardware.org/?probe=5d53e48607) | Nov 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d4b56e4038](https://linux-hardware.org/?probe=d4b56e4038) | Nov 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [16a35d0af3](https://linux-hardware.org/?probe=16a35d0af3) | Nov 14, 2020 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [a3a3bd1c26](https://linux-hardware.org/?probe=a3a3bd1c26) | Nov 14, 2020 |
| Lenovo        | ThinkPad L490 20Q50020MX    | Notebook    | [4d72b1a3cc](https://linux-hardware.org/?probe=4d72b1a3cc) | Nov 13, 2020 |
| HP            | 1998                        | Desktop     | [1346951067](https://linux-hardware.org/?probe=1346951067) | Nov 12, 2020 |
| HP            | 1998                        | Desktop     | [dece9d28a6](https://linux-hardware.org/?probe=dece9d28a6) | Nov 12, 2020 |
| HP            | 1998                        | Desktop     | [00c2c438c0](https://linux-hardware.org/?probe=00c2c438c0) | Nov 11, 2020 |
| HP            | 1998                        | Desktop     | [3772df1169](https://linux-hardware.org/?probe=3772df1169) | Nov 11, 2020 |
| HP            | 1998                        | Desktop     | [7c1b7a3a8f](https://linux-hardware.org/?probe=7c1b7a3a8f) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1fe2eda7db](https://linux-hardware.org/?probe=1fe2eda7db) | Nov 11, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [cae149b8a1](https://linux-hardware.org/?probe=cae149b8a1) | Nov 11, 2020 |
| HP            | 1998                        | Desktop     | [e3874c5181](https://linux-hardware.org/?probe=e3874c5181) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [afee9b144d](https://linux-hardware.org/?probe=afee9b144d) | Nov 11, 2020 |
| ASUSTek       | P8H67                       | Desktop     | [58e6f9543d](https://linux-hardware.org/?probe=58e6f9543d) | Nov 10, 2020 |
| ASUSTek       | P8H67                       | Desktop     | [4ac5a781a1](https://linux-hardware.org/?probe=4ac5a781a1) | Nov 10, 2020 |
| Lenovo        | ThinkPad L450 20DSS0VJ00    | Notebook    | [680974d12f](https://linux-hardware.org/?probe=680974d12f) | Nov 09, 2020 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5234189221](https://linux-hardware.org/?probe=5234189221) | Nov 08, 2020 |
| ASUSTek       | E402NA                      | Notebook    | [22f631fe63](https://linux-hardware.org/?probe=22f631fe63) | Nov 08, 2020 |
| ASUSTek       | E402NA                      | Notebook    | [8f7f5ad515](https://linux-hardware.org/?probe=8f7f5ad515) | Nov 08, 2020 |
| HP            | 1495                        | Desktop     | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| Notebook      | P64_HJ,HK1                  | Notebook    | [9881503776](https://linux-hardware.org/?probe=9881503776) | Nov 07, 2020 |
| HP            | 1495                        | Desktop     | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| Lenovo        | ThinkPad X301 4057AL1       | Notebook    | [b52207277d](https://linux-hardware.org/?probe=b52207277d) | Nov 04, 2020 |
| Lenovo        | B50-30 80ES                 | Notebook    | [fd647f5ce9](https://linux-hardware.org/?probe=fd647f5ce9) | Nov 04, 2020 |
| MSI           | Z97M-G43                    | Desktop     | [58cf86104b](https://linux-hardware.org/?probe=58cf86104b) | Nov 03, 2020 |
| MSI           | B450-A PRO MAX              | Desktop     | [b348fef370](https://linux-hardware.org/?probe=b348fef370) | Nov 02, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [0352b345cb](https://linux-hardware.org/?probe=0352b345cb) | Nov 02, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [0745eca4eb](https://linux-hardware.org/?probe=0745eca4eb) | Oct 31, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | Notebook    | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [5e5eff0a90](https://linux-hardware.org/?probe=5e5eff0a90) | Oct 31, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [a4caa7de36](https://linux-hardware.org/?probe=a4caa7de36) | Oct 30, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Finland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 181       | 15.51%  |
| Ubuntu 18.04                 | 103       | 8.83%   |
| Ubuntu 22.04                 | 34        | 2.91%   |
| OpenMandriva 4.2             | 33        | 2.83%   |
| Arch Rolling                 | 27        | 2.31%   |
| Arch                         | 27        | 2.31%   |
| Linux Mint 20                | 24        | 2.06%   |
| Ubuntu 21.04                 | 23        | 1.97%   |
| Debian 11                    | 22        | 1.89%   |
| Linux Mint 20.1              | 21        | 1.8%    |
| Pop!_OS 21.04                | 20        | 1.71%   |
| OpenMandriva 4.3             | 20        | 1.71%   |
| Ubuntu 20.10                 | 19        | 1.63%   |
| Manjaro                      | 19        | 1.63%   |
| Xubuntu 20.04                | 18        | 1.54%   |
| Linux Mint 19.3              | 17        | 1.46%   |
| Fedora 33                    | 17        | 1.46%   |
| Ubuntu 21.10                 | 16        | 1.37%   |
| Pop!_OS 20.04                | 16        | 1.37%   |
| Gentoo 2.7                   | 15        | 1.29%   |
| Fedora 32                    | 15        | 1.29%   |
| Debian 10                    | 15        | 1.29%   |
| Linux Mint 20.2              | 14        | 1.2%    |
| Fedora 34                    | 14        | 1.2%    |
| Fedora 31                    | 14        | 1.2%    |
| Ubuntu 19.10                 | 13        | 1.11%   |
| Linux Mint 20.3              | 12        | 1.03%   |
| Fedora 36                    | 12        | 1.03%   |
| ArcoLinux Rolling            | 12        | 1.03%   |
| Xubuntu 18.04                | 11        | 0.94%   |
| Pop!_OS 21.10                | 11        | 0.94%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.86%   |
| KDE neon 20.04               | 10        | 0.86%   |
| EndeavourOS Rolling          | 10        | 0.86%   |
| Debian Testing               | 10        | 0.86%   |
| Zorin 16                     | 9         | 0.77%   |
| Ubuntu 19.04                 | 9         | 0.77%   |
| Pop!_OS 22.04                | 9         | 0.77%   |
| Gentoo 2.6                   | 9         | 0.77%   |
| Pop!_OS 20.10                | 8         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 390       | 35.23%  |
| Linux Mint    | 87        | 7.86%   |
| Fedora        | 75        | 6.78%   |
| Pop!_OS       | 61        | 5.51%   |
| OpenMandriva  | 58        | 5.24%   |
| Arch          | 54        | 4.88%   |
| Manjaro       | 52        | 4.7%    |
| Debian        | 50        | 4.52%   |
| Xubuntu       | 39        | 3.52%   |
| Gentoo        | 25        | 2.26%   |
| ROSA          | 24        | 2.17%   |
| Kubuntu       | 16        | 1.45%   |
| openSUSE      | 15        | 1.36%   |
| ArcoLinux     | 14        | 1.26%   |
| Zorin         | 13        | 1.17%   |
| Lubuntu       | 12        | 1.08%   |
| EndeavourOS   | 12        | 1.08%   |
| KDE neon      | 11        | 0.99%   |
| CentOS        | 11        | 0.99%   |
| Ubuntu MATE   | 10        | 0.9%    |
| MX            | 7         | 0.63%   |
| Elementary    | 7         | 0.63%   |
| BlackPanther  | 6         | 0.54%   |
| Ubuntu Unity  | 5         | 0.45%   |
| Peppermint    | 5         | 0.45%   |
| Kali          | 5         | 0.45%   |
| Ubuntu Budgie | 4         | 0.36%   |
| Endless       | 4         | 0.36%   |
| Clear Linux   | 4         | 0.36%   |
| LMDE          | 3         | 0.27%   |
| Garuda Linux  | 3         | 0.27%   |
| RHEL          | 2         | 0.18%   |
| Raspbian      | 2         | 0.18%   |
| Parrot        | 2         | 0.18%   |
| Devuan        | 2         | 0.18%   |
| Artix         | 2         | 0.18%   |
| antergos      | 2         | 0.18%   |
| UbuntuDDE     | 1         | 0.09%   |
| Ubuntu Studio | 1         | 0.09%   |
| SteamOS       | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 37        | 2.91%   |
| 5.10.14-desktop-1omv4002        | 32        | 2.52%   |
| 5.16.7-desktop-1omv4003         | 19        | 1.5%    |
| 5.4.0-58-generic                | 18        | 1.42%   |
| 5.4.0-48-generic                | 16        | 1.26%   |
| 5.4.0-47-generic                | 16        | 1.26%   |
| 5.4.0-52-generic                | 12        | 0.94%   |
| 5.3.0-40-generic                | 12        | 0.94%   |
| 5.11.0-7620-generic             | 12        | 0.94%   |
| 5.8.0-44-generic                | 10        | 0.79%   |
| 5.8.0-41-generic                | 9         | 0.71%   |
| 5.4.0-65-generic                | 9         | 0.71%   |
| 5.4.0-56-generic                | 9         | 0.71%   |
| 5.4.0-53-generic                | 9         | 0.71%   |
| 5.15.0-46-generic               | 9         | 0.71%   |
| 5.4.0-45-generic                | 8         | 0.63%   |
| 5.13.0-7620-generic             | 8         | 0.63%   |
| 5.8.0-43-generic                | 7         | 0.55%   |
| 5.4.0-92-generic                | 7         | 0.55%   |
| 5.4.0-66-generic                | 7         | 0.55%   |
| 5.4.0-54-generic                | 7         | 0.55%   |
| 5.3.0-46-generic                | 7         | 0.55%   |
| 5.3.0-42-generic                | 7         | 0.55%   |
| 5.15.0-27-generic               | 7         | 0.55%   |
| 5.11.0-25-generic               | 7         | 0.55%   |
| 5.8.0-7630-generic              | 6         | 0.47%   |
| 5.4.0-7634-generic              | 6         | 0.47%   |
| 5.4.0-51-generic                | 6         | 0.47%   |
| 5.15.0-47-generic               | 6         | 0.47%   |
| 5.15.0-41-generic               | 6         | 0.47%   |
| 5.13.0-30-generic               | 6         | 0.47%   |
| 5.13.0-22-generic               | 6         | 0.47%   |
| 5.11.0-41-generic               | 6         | 0.47%   |
| 5.11.0-34-generic               | 6         | 0.47%   |
| 5.11.0-27-generic               | 6         | 0.47%   |
| 5.10.0-8-amd64                  | 6         | 0.47%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 6         | 0.47%   |
| 4.18.16-desktop-1bP             | 6         | 0.47%   |
| 5.8.0-50-generic                | 5         | 0.39%   |
| 5.8.0-48-generic                | 5         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 252       | 20.83%  |
| 5.8.0   | 81        | 6.69%   |
| 4.15.0  | 78        | 6.45%   |
| 5.11.0  | 73        | 6.03%   |
| 5.15.0  | 51        | 4.21%   |
| 5.3.0   | 49        | 4.05%   |
| 5.13.0  | 48        | 3.97%   |
| 5.10.14 | 33        | 2.73%   |
| 5.0.0   | 26        | 2.15%   |
| 5.10.0  | 24        | 1.98%   |
| 4.18.0  | 22        | 1.82%   |
| 5.16.7  | 19        | 1.57%   |
| 4.19.0  | 19        | 1.57%   |
| 5.17.5  | 7         | 0.58%   |
| 5.14.0  | 7         | 0.58%   |
| 4.18.16 | 7         | 0.58%   |
| 4.9.60  | 6         | 0.5%    |
| 3.10.0  | 6         | 0.5%    |
| 5.15.15 | 5         | 0.41%   |
| 5.14.14 | 5         | 0.41%   |
| 5.12.4  | 5         | 0.41%   |
| 5.11.14 | 5         | 0.41%   |
| 5.10.74 | 5         | 0.41%   |
| 5.9.0   | 4         | 0.33%   |
| 5.8.11  | 4         | 0.33%   |
| 5.6.0   | 4         | 0.33%   |
| 5.3.18  | 4         | 0.33%   |
| 5.19.0  | 4         | 0.33%   |
| 5.16.13 | 4         | 0.33%   |
| 5.15.28 | 4         | 0.33%   |
| 5.13.9  | 4         | 0.33%   |
| 5.11.2  | 4         | 0.33%   |
| 5.9.16  | 3         | 0.25%   |
| 5.9.11  | 3         | 0.25%   |
| 5.8.6   | 3         | 0.25%   |
| 5.8.16  | 3         | 0.25%   |
| 5.8.14  | 3         | 0.25%   |
| 5.6.19  | 3         | 0.25%   |
| 5.5.10  | 3         | 0.25%   |
| 5.3.7   | 3         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 277       | 23.28%  |
| 5.8     | 106       | 8.91%   |
| 5.15    | 97        | 8.15%   |
| 5.11    | 95        | 7.98%   |
| 5.10    | 92        | 7.73%   |
| 4.15    | 79        | 6.64%   |
| 5.13    | 64        | 5.38%   |
| 5.3     | 62        | 5.21%   |
| 5.16    | 42        | 3.53%   |
| 4.18    | 30        | 2.52%   |
| 5.17    | 27        | 2.27%   |
| 5.0     | 27        | 2.27%   |
| 4.19    | 24        | 2.02%   |
| 5.14    | 19        | 1.6%    |
| 5.9     | 18        | 1.51%   |
| 5.7     | 17        | 1.43%   |
| 5.12    | 17        | 1.43%   |
| 5.18    | 16        | 1.34%   |
| 5.6     | 14        | 1.18%   |
| 5.19    | 14        | 1.18%   |
| 4.9     | 14        | 1.18%   |
| 5.5     | 13        | 1.09%   |
| 3.10    | 6         | 0.5%    |
| 4.1     | 4         | 0.34%   |
| 5.2     | 3         | 0.25%   |
| 4.4     | 3         | 0.25%   |
| 5.1     | 2         | 0.17%   |
| 4.13    | 2         | 0.17%   |
| 6.0     | 1         | 0.08%   |
| 4.20    | 1         | 0.08%   |
| 4.17    | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |
| 4.12    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1034      | 96.37%  |
| i686    | 30        | 2.8%    |
| aarch64 | 8         | 0.75%   |
| armv6l  | 1         | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 469       | 41.88%  |
| KDE5             | 176       | 15.71%  |
| Unknown          | 168       | 15%     |
| XFCE             | 93        | 8.3%    |
| X-Cinnamon       | 56        | 5%      |
| MATE             | 35        | 3.13%   |
| KDE              | 23        | 2.05%   |
| KDE4             | 13        | 1.16%   |
| Cinnamon         | 13        | 1.16%   |
| LXQt             | 12        | 1.07%   |
| GNOME Flashback  | 9         | 0.8%    |
| i3               | 8         | 0.71%   |
| LXDE             | 7         | 0.63%   |
| Budgie           | 7         | 0.63%   |
| Pantheon         | 6         | 0.54%   |
| lightdm-xsession | 6         | 0.54%   |
| Unity            | 5         | 0.45%   |
| Deepin           | 3         | 0.27%   |
| bspwm            | 3         | 0.27%   |
| LeftWM           | 2         | 0.18%   |
| DWM              | 2         | 0.18%   |
| xubuntu          | 1         | 0.09%   |
| xmonad           | 1         | 0.09%   |
| sway:Unity       | 1         | 0.09%   |
| GNOME Classic    | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 841       | 76.73%  |
| Wayland | 137       | 12.5%   |
| Unknown | 76        | 6.93%   |
| Tty     | 41        | 3.74%   |
| Web     | 1         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 567       | 50.63%  |
| SDDM    | 162       | 14.46%  |
| GDM     | 155       | 13.84%  |
| LightDM | 89        | 7.95%   |
| GDM3    | 68        | 6.07%   |
| TDM     | 61        | 5.45%   |
| KDM     | 14        | 1.25%   |
| XDM     | 1         | 0.09%   |
| SLiM    | 1         | 0.09%   |
| Ly      | 1         | 0.09%   |
| LXDM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 454       | 41.39%  |
| fi_FI       | 355       | 32.36%  |
| Unknown     | 138       | 12.58%  |
| en_GB       | 63        | 5.74%   |
| C           | 22        | 2.01%   |
| ru_RU       | 15        | 1.37%   |
| en_FI       | 6         | 0.55%   |
| sv_FI       | 5         | 0.46%   |
| sv_SE       | 4         | 0.36%   |
| C.UTF8      | 4         | 0.36%   |
| pl_PL       | 3         | 0.27%   |
| fr_FR       | 3         | 0.27%   |
| en_DK       | 3         | 0.27%   |
| it_IT       | 2         | 0.18%   |
| et_EE       | 2         | 0.18%   |
| en_SE       | 2         | 0.18%   |
| en_IE       | 2         | 0.18%   |
| en_AG       | 2         | 0.18%   |
| de_DE       | 2         | 0.18%   |
| zh_CN       | 1         | 0.09%   |
| UTF-8       | 1         | 0.09%   |
| is_IS       | 1         | 0.09%   |
| ia_FR       | 1         | 0.09%   |
| hu_HU       | 1         | 0.09%   |
| fr_CA       | 1         | 0.09%   |
| en_US.utf-8 | 1         | 0.09%   |
| en_NG       | 1         | 0.09%   |
| en_CA       | 1         | 0.09%   |
| af_ZA       | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 582       | 53.2%   |
| EFI  | 512       | 46.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 825       | 75.41%  |
| Btrfs   | 106       | 9.69%   |
| Overlay | 79        | 7.22%   |
| Unknown | 42        | 3.84%   |
| Xfs     | 22        | 2.01%   |
| Zfs     | 12        | 1.1%    |
| Ext3    | 3         | 0.27%   |
| Ext2    | 3         | 0.27%   |
| F2fs    | 2         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 565       | 51.69%  |
| GPT     | 378       | 34.58%  |
| MBR     | 150       | 13.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 929       | 85.31%  |
| Yes       | 160       | 14.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 797       | 73.19%  |
| Yes       | 292       | 26.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 232       | 21.64%  |
| Lenovo                  | 202       | 18.84%  |
| Hewlett-Packard         | 173       | 16.14%  |
| Dell                    | 85        | 7.93%   |
| MSI                     | 60        | 5.6%    |
| Acer                    | 60        | 5.6%    |
| Gigabyte Technology     | 52        | 4.85%   |
| ASRock                  | 44        | 4.1%    |
| Fujitsu                 | 27        | 2.52%   |
| Samsung Electronics     | 18        | 1.68%   |
| Apple                   | 18        | 1.68%   |
| Intel                   | 15        | 1.4%    |
| Fujitsu Siemens         | 10        | 0.93%   |
| Pegatron                | 8         | 0.75%   |
| Packard Bell            | 7         | 0.65%   |
| Foxconn                 | 7         | 0.65%   |
| Raspberry Pi Foundation | 6         | 0.56%   |
| Toshiba                 | 5         | 0.47%   |
| Supermicro              | 4         | 0.37%   |
| Sony                    | 4         | 0.37%   |
| Unknown                 | 4         | 0.37%   |
| HUAWEI                  | 3         | 0.28%   |
| Timi                    | 2         | 0.19%   |
| Medion                  | 2         | 0.19%   |
| ASRockRack              | 2         | 0.19%   |
| AOpen                   | 2         | 0.19%   |
| AMI                     | 2         | 0.19%   |
| ABIT                    | 2         | 0.19%   |
| ZOTAC                   | 1         | 0.09%   |
| ZMY                     | 1         | 0.09%   |
| WeiBu                   | 1         | 0.09%   |
| Valve                   | 1         | 0.09%   |
| Shuttle                 | 1         | 0.09%   |
| Seco                    | 1         | 0.09%   |
| powerinternational      | 1         | 0.09%   |
| Pine Microsystems       | 1         | 0.09%   |
| Notebook                | 1         | 0.09%   |
| Microsoft               | 1         | 0.09%   |
| IBM                     | 1         | 0.09%   |
| Google                  | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 22        | 2.05%   |
| HP EliteDesk 800 G1 SFF              | 8         | 0.75%   |
| MSI MS-7C37                          | 6         | 0.56%   |
| ASUS TUF Gaming X570-PLUS            | 6         | 0.56%   |
| Unknown                              | 5         | 0.47%   |
| MSI MS-7A38                          | 4         | 0.37%   |
| Gigabyte X570 AORUS ELITE            | 4         | 0.37%   |
| ASUS Pro WS 565-ACE                  | 4         | 0.37%   |
| ASUS M5A97 R2.0                      | 4         | 0.37%   |
| Samsung R530/R730                    | 3         | 0.28%   |
| MSI MS-7B89                          | 3         | 0.28%   |
| MSI MS-7B48                          | 3         | 0.28%   |
| Lenovo V145-15AST 81MT               | 3         | 0.28%   |
| Lenovo ThinkPad T420 4180PBG         | 3         | 0.28%   |
| Lenovo MIIX 310-10ICR 80SG           | 3         | 0.28%   |
| HP Pavilion dv6                      | 3         | 0.28%   |
| HP EliteBook 8460p                   | 3         | 0.28%   |
| HP EliteBook 840 G7 Notebook PC      | 3         | 0.28%   |
| HP EliteBook 820 G1                  | 3         | 0.28%   |
| HP EliteBook 2560p                   | 3         | 0.28%   |
| HP Compaq 8200 Elite SFF PC          | 3         | 0.28%   |
| Fujitsu Siemens ESPRIMO Mobile D9500 | 3         | 0.28%   |
| Fujitsu LIFEBOOK A530                | 3         | 0.28%   |
| Dell XPS 13 9380                     | 3         | 0.28%   |
| Dell OptiPlex 780                    | 3         | 0.28%   |
| Dell Latitude 7490                   | 3         | 0.28%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 3         | 0.28%   |
| ASUS TUF B450-PLUS GAMING            | 3         | 0.28%   |
| ASUS ROG STRIX Z370-F GAMING         | 3         | 0.28%   |
| ASUS ROG STRIX B550-I GAMING         | 3         | 0.28%   |
| ASUS PRIME B450-PLUS                 | 3         | 0.28%   |
| ASUS PRIME B350-PLUS                 | 3         | 0.28%   |
| ASUS E402NA                          | 3         | 0.28%   |
| ASRock B450M-HDV R4.0                | 3         | 0.28%   |
| Acer Aspire X3300                    | 3         | 0.28%   |
| Toshiba Satellite C660               | 2         | 0.19%   |
| Samsung R610                         | 2         | 0.19%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 2         | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.4   | 2         | 0.19%   |
| MSI MS-7C84                          | 2         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 121       | 11.29%  |
| HP EliteBook            | 40        | 3.73%   |
| Acer Aspire             | 40        | 3.73%   |
| Dell Latitude           | 34        | 3.17%   |
| HP Compaq               | 32        | 2.99%   |
| ASUS PRIME              | 30        | 2.8%    |
| HP Pavilion             | 26        | 2.43%   |
| ASUS All                | 22        | 2.05%   |
| ASUS ROG                | 20        | 1.87%   |
| Lenovo IdeaPad          | 18        | 1.68%   |
| Dell XPS                | 15        | 1.4%    |
| ASUS TUF                | 15        | 1.4%    |
| Dell OptiPlex           | 14        | 1.31%   |
| Lenovo Yoga             | 13        | 1.21%   |
| Fujitsu LIFEBOOK        | 12        | 1.12%   |
| Dell Precision          | 12        | 1.12%   |
| Lenovo ThinkCentre      | 11        | 1.03%   |
| HP ProBook              | 11        | 1.03%   |
| HP EliteDesk            | 11        | 1.03%   |
| Fujitsu ESPRIMO         | 8         | 0.75%   |
| HP ProDesk              | 7         | 0.65%   |
| Gigabyte X570           | 7         | 0.65%   |
| Fujitsu Siemens ESPRIMO | 7         | 0.65%   |
| ASUS VivoBook           | 7         | 0.65%   |
| ASUS M5A97              | 7         | 0.65%   |
| RPi Raspberry           | 6         | 0.56%   |
| MSI MS-7C37             | 6         | 0.56%   |
| HP Laptop               | 6         | 0.56%   |
| Toshiba Satellite       | 5         | 0.47%   |
| Lenovo Legion           | 5         | 0.47%   |
| Dell Inspiron           | 5         | 0.47%   |
| ASUS Pro                | 5         | 0.47%   |
| Acer Swift              | 5         | 0.47%   |
| Unknown                 | 5         | 0.47%   |
| Packard Bell EasyNote   | 4         | 0.37%   |
| MSI MS-7A38             | 4         | 0.37%   |
| HP ZBook                | 4         | 0.37%   |
| Gigabyte B550           | 4         | 0.37%   |
| ASRock B450M-HDV        | 4         | 0.37%   |
| Samsung R530            | 3         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 106       | 9.89%   |
| 2012    | 99        | 9.24%   |
| 2018    | 95        | 8.86%   |
| 2013    | 90        | 8.4%    |
| 2011    | 89        | 8.3%    |
| 2017    | 83        | 7.74%   |
| 2020    | 80        | 7.46%   |
| 2014    | 62        | 5.78%   |
| 2015    | 59        | 5.5%    |
| 2008    | 57        | 5.32%   |
| 2016    | 55        | 5.13%   |
| 2009    | 52        | 4.85%   |
| 2010    | 48        | 4.48%   |
| 2021    | 32        | 2.99%   |
| 2007    | 32        | 2.99%   |
| 2006    | 12        | 1.12%   |
| 2022    | 8         | 0.75%   |
| Unknown | 6         | 0.56%   |
| 2005    | 5         | 0.47%   |
| 2004    | 2         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 545       | 50.84%  |
| Desktop        | 463       | 43.19%  |
| Convertible    | 18        | 1.68%   |
| Mini pc        | 12        | 1.12%   |
| All in one     | 11        | 1.03%   |
| Server         | 9         | 0.84%   |
| System on chip | 6         | 0.56%   |
| Tablet         | 6         | 0.56%   |
| Phone          | 2         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 994       | 92.47%  |
| Enabled  | 81        | 7.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1071      | 99.91%  |
| Yes  | 1         | 0.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 234       | 21.61%  |
| 4.01-8.0        | 233       | 21.51%  |
| 3.01-4.0        | 226       | 20.87%  |
| 8.01-16.0       | 166       | 15.33%  |
| 32.01-64.0      | 106       | 9.79%   |
| 1.01-2.0        | 40        | 3.69%   |
| 64.01-256.0     | 34        | 3.14%   |
| 2.01-3.0        | 18        | 1.66%   |
| 24.01-32.0      | 16        | 1.48%   |
| 0.51-1.0        | 5         | 0.46%   |
| More than 256.0 | 4         | 0.37%   |
| 0.01-0.5        | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 428       | 36.39%  |
| 2.01-3.0    | 262       | 22.28%  |
| 4.01-8.0    | 152       | 12.93%  |
| 3.01-4.0    | 135       | 11.48%  |
| 0.51-1.0    | 99        | 8.42%   |
| 8.01-16.0   | 59        | 5.02%   |
| 0.01-0.5    | 19        | 1.62%   |
| 16.01-24.0  | 10        | 0.85%   |
| 32.01-64.0  | 5         | 0.43%   |
| 24.01-32.0  | 4         | 0.34%   |
| 64.01-256.0 | 2         | 0.17%   |
| 0           | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 639       | 58.2%   |
| 2      | 238       | 21.68%  |
| 3      | 98        | 8.93%   |
| 4      | 44        | 4.01%   |
| 5      | 27        | 2.46%   |
| 0      | 19        | 1.73%   |
| 6      | 12        | 1.09%   |
| 7      | 7         | 0.64%   |
| 9      | 5         | 0.46%   |
| 8      | 5         | 0.46%   |
| 10     | 2         | 0.18%   |
| 23     | 1         | 0.09%   |
| 11     | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 627       | 57.89%  |
| Yes       | 456       | 42.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 968       | 90.05%  |
| No        | 107       | 9.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 760       | 70.57%  |
| No        | 317       | 29.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 596       | 55.08%  |
| No        | 486       | 44.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Finland | 1072      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Helsinki     | 487       | 42.38%  |
| Tampere      | 107       | 9.31%   |
| Turku        | 86        | 7.48%   |
| Oulu         | 56        | 4.87%   |
| Espoo        | 52        | 4.53%   |
| Kuopio       | 34        | 2.96%   |
| Jyväskylä  | 28        | 2.44%   |
| Lahti        | 26        | 2.26%   |
| Vantaa       | 25        | 2.18%   |
| Vaasa        | 14        | 1.22%   |
| Tuusula      | 13        | 1.13%   |
| Raisio       | 13        | 1.13%   |
| Raahe        | 9         | 0.78%   |
| Lappeenranta | 9         | 0.78%   |
| Joensuu      | 9         | 0.78%   |
| Hyvinkaeae   | 9         | 0.78%   |
| Pori         | 8         | 0.7%    |
| Tenala       | 4         | 0.35%   |
| Solv         | 4         | 0.35%   |
| Seinäjoki   | 4         | 0.35%   |
| Salo         | 4         | 0.35%   |
| Kouvola      | 4         | 0.35%   |
| Kotka        | 4         | 0.35%   |
| Klaukkala    | 4         | 0.35%   |
| Järvenpää | 4         | 0.35%   |
| Rusko        | 3         | 0.26%   |
| Rauma        | 3         | 0.26%   |
| Porlammi     | 3         | 0.26%   |
| Mäntsälä  | 3         | 0.26%   |
| Lempäälä  | 3         | 0.26%   |
| Kokkola      | 3         | 0.26%   |
| Kerava       | 3         | 0.26%   |
| Heinola      | 3         | 0.26%   |
| Hanko        | 3         | 0.26%   |
| Hämeenlinna | 3         | 0.26%   |
| Urjala       | 2         | 0.17%   |
| Tarvasjoki   | 2         | 0.17%   |
| Sastamala    | 2         | 0.17%   |
| Rovaniemi    | 2         | 0.17%   |
| Riihimäki   | 2         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 315       | 495    | 20.11%  |
| WDC                 | 231       | 399    | 14.75%  |
| Seagate             | 201       | 319    | 12.84%  |
| Kingston            | 181       | 262    | 11.56%  |
| Toshiba             | 84        | 133    | 5.36%   |
| Intel               | 59        | 75     | 3.77%   |
| Hitachi             | 59        | 81     | 3.77%   |
| Unknown             | 55        | 76     | 3.51%   |
| SanDisk             | 48        | 57     | 3.07%   |
| SK hynix            | 47        | 60     | 3%      |
| Crucial             | 42        | 50     | 2.68%   |
| Micron Technology   | 25        | 53     | 1.6%    |
| HGST                | 25        | 46     | 1.6%    |
| A-DATA Technology   | 21        | 28     | 1.34%   |
| Corsair             | 13        | 15     | 0.83%   |
| Maxtor              | 12        | 19     | 0.77%   |
| Transcend           | 11        | 12     | 0.7%    |
| PNY                 | 11        | 11     | 0.7%    |
| OCZ                 | 11        | 16     | 0.7%    |
| Fujitsu             | 10        | 12     | 0.64%   |
| Phison              | 9         | 10     | 0.57%   |
| KIOXIA              | 9         | 9      | 0.57%   |
| Apple               | 7         | 9      | 0.45%   |
| Verbatim            | 6         | 8      | 0.38%   |
| LITEON              | 6         | 8      | 0.38%   |
| LITEONIT            | 5         | 6      | 0.32%   |
| Intenso             | 5         | 5      | 0.32%   |
| XPG                 | 4         | 5      | 0.26%   |
| Patriot             | 4         | 7      | 0.26%   |
| HUAWEI              | 3         | 3      | 0.19%   |
| Hewlett-Packard     | 3         | 4      | 0.19%   |
| China               | 3         | 3      | 0.19%   |
| ASMT                | 3         | 3      | 0.19%   |
| UMIS                | 2         | 2      | 0.13%   |
| Plextor             | 2         | 2      | 0.13%   |
| OCZ-VERTEX3         | 2         | 2      | 0.13%   |
| Lenovo              | 2         | 2      | 0.13%   |
| JMicron Technology  | 2         | 5      | 0.13%   |
| Gigabyte Technology | 2         | 2      | 0.13%   |
| BHT                 | 2         | 4      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 27        | 1.53%   |
| Samsung SSD 850 EVO 250GB          | 26        | 1.47%   |
| Kingston SA400S37120G 120GB SSD    | 20        | 1.13%   |
| Samsung SSD 850 EVO 500GB          | 19        | 1.08%   |
| Samsung NVMe SSD Drive 500GB       | 17        | 0.96%   |
| Kingston SA400S37480G 480GB SSD    | 17        | 0.96%   |
| Unknown MMC Card  64GB             | 14        | 0.79%   |
| Kingston SV300S37A120G 120GB SSD   | 14        | 0.79%   |
| Kingston SHFS37A120G 120GB SSD     | 13        | 0.74%   |
| Seagate ST9500325AS 500GB          | 12        | 0.68%   |
| Samsung SSD 860 EVO 500GB          | 12        | 0.68%   |
| Kingston SV300S37A240G 240GB SSD   | 12        | 0.68%   |
| Samsung NVMe SSD Drive 256GB       | 11        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB    | 10        | 0.57%   |
| Samsung NVMe SSD Drive 512GB       | 10        | 0.57%   |
| Samsung NVMe SSD Drive 1TB         | 10        | 0.57%   |
| Samsung HD103SJ 1TB                | 10        | 0.57%   |
| HGST HTS721010A9E630 1TB           | 10        | 0.57%   |
| Unknown MMC Card  32GB             | 9         | 0.51%   |
| Crucial CT1000MX500SSD1 1TB        | 9         | 0.51%   |
| WDC WD30EFRX-68EUZN0 3TB           | 8         | 0.45%   |
| Toshiba DT01ACA300 3TB             | 8         | 0.45%   |
| Samsung SSD 960 EVO 500GB          | 8         | 0.45%   |
| Samsung SSD 860 EVO 1TB            | 8         | 0.45%   |
| Samsung HD501LJ 500GB              | 8         | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 7         | 0.4%    |
| WDC WD40EFRX-68WT0N0 4TB           | 7         | 0.4%    |
| SK hynix NVMe SSD Drive 256GB      | 7         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB    | 7         | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB     | 7         | 0.4%    |
| Samsung SSD 840 EVO 120GB          | 7         | 0.4%    |
| PNY CS900 120GB SSD                | 7         | 0.4%    |
| Toshiba NVMe SSD Drive 256GB       | 6         | 0.34%   |
| Toshiba MQ01ABD100 1TB             | 6         | 0.34%   |
| SK hynix NVMe SSD Drive 512GB      | 6         | 0.34%   |
| Seagate ST4000DM004-2CV104 4TB     | 6         | 0.34%   |
| Seagate ST31000524AS 1TB           | 6         | 0.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.34%   |
| Seagate Expansion 1TB              | 6         | 0.34%   |
| SanDisk NVMe SSD Drive 512GB       | 6         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 194       | 308    | 32.61%  |
| WDC                 | 187       | 325    | 31.43%  |
| Hitachi             | 59        | 81     | 9.92%   |
| Toshiba             | 56        | 87     | 9.41%   |
| Samsung Electronics | 41        | 57     | 6.89%   |
| HGST                | 25        | 46     | 4.2%    |
| Maxtor              | 12        | 19     | 2.02%   |
| Fujitsu             | 10        | 12     | 1.68%   |
| Unknown             | 3         | 3      | 0.5%    |
| Intenso             | 2         | 2      | 0.34%   |
| Apple               | 2         | 2      | 0.34%   |
| RSH-339             | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 3      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |
| ASMT                | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 182       | 261    | 29.79%  |
| Kingston            | 158       | 232    | 25.86%  |
| Crucial             | 41        | 49     | 6.71%   |
| WDC                 | 35        | 49     | 5.73%   |
| Intel               | 27        | 39     | 4.42%   |
| SanDisk             | 25        | 31     | 4.09%   |
| Micron Technology   | 19        | 46     | 3.11%   |
| Transcend           | 11        | 12     | 1.8%    |
| OCZ                 | 11        | 16     | 1.8%    |
| A-DATA Technology   | 11        | 15     | 1.8%    |
| Toshiba             | 10        | 18     | 1.64%   |
| SK hynix            | 10        | 19     | 1.64%   |
| PNY                 | 10        | 10     | 1.64%   |
| Corsair             | 7         | 8      | 1.15%   |
| Verbatim            | 6         | 8      | 0.98%   |
| LITEON              | 6         | 8      | 0.98%   |
| LITEONIT            | 5         | 6      | 0.82%   |
| Patriot             | 4         | 7      | 0.65%   |
| Apple               | 4         | 5      | 0.65%   |
| Intenso             | 3         | 3      | 0.49%   |
| China               | 3         | 3      | 0.49%   |
| Plextor             | 2         | 2      | 0.33%   |
| OCZ-VERTEX3         | 2         | 2      | 0.33%   |
| Hewlett-Packard     | 2         | 3      | 0.33%   |
| BHT                 | 2         | 4      | 0.33%   |
| ASMT                | 2         | 2      | 0.33%   |
| Vaseky              | 1         | 1      | 0.16%   |
| Unknown             | 1         | 1      | 0.16%   |
| TSA                 | 1         | 1      | 0.16%   |
| TO Exter            | 1         | 1      | 0.16%   |
| SPCC                | 1         | 1      | 0.16%   |
| Seagate             | 1         | 1      | 0.16%   |
| Ramsta              | 1         | 1      | 0.16%   |
| OCZ-VERTEX          | 1         | 1      | 0.16%   |
| GOODRAM             | 1         | 1      | 0.16%   |
| FORESEE             | 1         | 1      | 0.16%   |
| CT240BX5            | 1         | 1      | 0.16%   |
| ATP                 | 1         | 1      | 0.16%   |
| Unknown             | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 527       | 871    | 37.59%  |
| HDD     | 496       | 948    | 35.38%  |
| NVMe    | 311       | 432    | 22.18%  |
| MMC     | 54        | 71     | 3.85%   |
| Unknown | 14        | 23     | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 834       | 1771   | 67.1%   |
| NVMe | 310       | 429    | 24.94%  |
| MMC  | 54        | 71     | 4.34%   |
| SAS  | 45        | 74     | 3.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 682       | 1131   | 62.8%   |
| 0.51-1.0   | 255       | 360    | 23.48%  |
| 1.01-2.0   | 66        | 129    | 6.08%   |
| 3.01-4.0   | 29        | 81     | 2.67%   |
| 2.01-3.0   | 29        | 60     | 2.67%   |
| 4.01-10.0  | 23        | 56     | 2.12%   |
| 10.01-20.0 | 2         | 2      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 329       | 29.4%   |
| 251-500        | 215       | 19.21%  |
| 501-1000       | 138       | 12.33%  |
| 51-100         | 86        | 7.69%   |
| More than 3000 | 74        | 6.61%   |
| 1001-2000      | 73        | 6.52%   |
| 1-20           | 73        | 6.52%   |
| Unknown        | 53        | 4.74%   |
| 21-50          | 42        | 3.75%   |
| 2001-3000      | 36        | 3.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 445       | 38.63%  |
| 21-50          | 192       | 16.67%  |
| 51-100         | 119       | 10.33%  |
| 101-250        | 116       | 10.07%  |
| 251-500        | 69        | 5.99%   |
| 501-1000       | 67        | 5.82%   |
| Unknown        | 53        | 4.6%    |
| 1001-2000      | 40        | 3.47%   |
| More than 3000 | 29        | 2.52%   |
| 2001-3000      | 22        | 1.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB                       | 3         | 5      | 2.83%   |
| Seagate ST9500325AS 500GB                      | 3         | 4      | 2.83%   |
| Samsung Electronics HD103SJ 1TB                | 3         | 4      | 2.83%   |
| Kingston SHFS37A120G 120GB SSD                 | 3         | 4      | 2.83%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 1.89%   |
| Samsung Electronics SSD 850 EVO 1TB            | 2         | 2      | 1.89%   |
| Micron Technology MTFDDAK512MAM-1K1 512GB SSD  | 2         | 2      | 1.89%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD | 2         | 4      | 1.89%   |
| Maxtor 7Y250M0 250GB                           | 2         | 2      | 1.89%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 1.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 0.94%   |
| WDC WD6400AAKS-07A7B0 640GB                    | 1         | 1      | 0.94%   |
| WDC WD50EZRZ-32RWYB1 5TB                       | 1         | 1      | 0.94%   |
| WDC WD5000AAKX-00ERMA0 500GB                   | 1         | 1      | 0.94%   |
| WDC WD5000AAKS-22A7B0 500GB                    | 1         | 1      | 0.94%   |
| WDC WD3200BEVT-22ZCT0 320GB                    | 1         | 1      | 0.94%   |
| WDC WD3200AAKS-00L9A0 320GB                    | 1         | 1      | 0.94%   |
| WDC WD3200AAJS-60Z0A0 320GB                    | 1         | 1      | 0.94%   |
| WDC WD30EFRX-68EUZN0 3TB                       | 1         | 1      | 0.94%   |
| WDC WD2500AAJS-00V4A0 250GB                    | 1         | 1      | 0.94%   |
| WDC WD2002FAEX-007BA0 2TB                      | 1         | 1      | 0.94%   |
| WDC WD1600BJKT-75F4T0 160GB                    | 1         | 1      | 0.94%   |
| WDC WD10JUCT-63CYNY0 1TB                       | 1         | 1      | 0.94%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1         | 1      | 0.94%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 1      | 0.94%   |
| WDC WD10EADX-22TDHB0 1TB                       | 1         | 1      | 0.94%   |
| WDC WD10EADS-22M2B0 1TB                        | 1         | 1      | 0.94%   |
| Vaseky V800/60G 64GB                           | 1         | 1      | 0.94%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 0.94%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 0.94%   |
| Toshiba MK8052GSX 80GB                         | 1         | 1      | 0.94%   |
| Toshiba MK7575GSX 752GB                        | 1         | 1      | 0.94%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 0.94%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD        | 1         | 1      | 0.94%   |
| Toshiba HDWA120 2TB                            | 1         | 1      | 0.94%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 0.94%   |
| Toshiba DT01ABA200 2TB                         | 1         | 1      | 0.94%   |
| SK hynix PC401 NVMe 512GB                      | 1         | 1      | 0.94%   |
| SK hynix BC711 HFM256GD3JX013N 256GB           | 1         | 1      | 0.94%   |
| Seagate ST9500620NS 500GB                      | 1         | 1      | 0.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 25     | 21.36%  |
| WDC                 | 19        | 22     | 18.45%  |
| Toshiba             | 9         | 9      | 8.74%   |
| Samsung Electronics | 9         | 11     | 8.74%   |
| Hitachi             | 9         | 17     | 8.74%   |
| Kingston            | 8         | 9      | 7.77%   |
| Micron Technology   | 5         | 7      | 4.85%   |
| HGST                | 5         | 5      | 4.85%   |
| Intel               | 4         | 4      | 3.88%   |
| Maxtor              | 3         | 3      | 2.91%   |
| SK hynix            | 2         | 2      | 1.94%   |
| Fujitsu             | 2         | 2      | 1.94%   |
| Vaseky              | 1         | 1      | 0.97%   |
| SanDisk             | 1         | 1      | 0.97%   |
| OCZ                 | 1         | 1      | 0.97%   |
| LITEONIT            | 1         | 1      | 0.97%   |
| Corsair             | 1         | 1      | 0.97%   |
| ATP                 | 1         | 1      | 0.97%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 25     | 30.99%  |
| WDC                 | 18        | 21     | 25.35%  |
| Hitachi             | 9         | 17     | 12.68%  |
| Toshiba             | 8         | 8      | 11.27%  |
| HGST                | 5         | 5      | 7.04%   |
| Samsung Electronics | 4         | 5      | 5.63%   |
| Maxtor              | 3         | 3      | 4.23%   |
| Fujitsu             | 2         | 2      | 2.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 70        | 86     | 67.96%  |
| SSD  | 28        | 31     | 27.18%  |
| NVMe | 5         | 5      | 4.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 611       | 1292   | 52.76%  |
| Works    | 446       | 930    | 38.51%  |
| Malfunc  | 100       | 122    | 8.64%   |
| Failed   | 1         | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 688       | 51.19%  |
| AMD                              | 234       | 17.41%  |
| Samsung Electronics              | 125       | 9.3%    |
| SanDisk                          | 38        | 2.83%   |
| SK hynix                         | 35        | 2.6%    |
| Nvidia                           | 32        | 2.38%   |
| ASMedia Technology               | 32        | 2.38%   |
| Kingston Technology Company      | 24        | 1.79%   |
| JMicron Technology               | 23        | 1.71%   |
| Toshiba America Info Systems     | 20        | 1.49%   |
| Phison Electronics               | 19        | 1.41%   |
| ADATA Technology                 | 14        | 1.04%   |
| Marvell Technology Group         | 11        | 0.82%   |
| KIOXIA                           | 9         | 0.67%   |
| VIA Technologies                 | 6         | 0.45%   |
| Micron Technology                | 6         | 0.45%   |
| Seagate Technology               | 4         | 0.3%    |
| Union Memory (Shenzhen)          | 3         | 0.22%   |
| Silicon Integrated Systems [SiS] | 3         | 0.22%   |
| Realtek Semiconductor            | 3         | 0.22%   |
| LSI Logic / Symbios Logic        | 3         | 0.22%   |
| Broadcom / LSI                   | 3         | 0.22%   |
| Solid State Storage Technology   | 2         | 0.15%   |
| Lenovo                           | 2         | 0.15%   |
| Silicon Motion                   | 1         | 0.07%   |
| Micron/Crucial Technology        | 1         | 0.07%   |
| Lite-On Technology               | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 153       | 9.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 76        | 4.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 57        | 3.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 45        | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 45        | 2.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 42        | 2.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 42        | 2.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 35        | 2.2%    |
| AMD 400 Series Chipset SATA Controller                                         | 35        | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 33        | 2.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 30        | 1.89%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 30        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 30        | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 1.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 24        | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 24        | 1.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 22        | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 22        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 22        | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 19        | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 18        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 18        | 1.13%   |
| AMD 500 Series Chipset SATA Controller                                         | 18        | 1.13%   |
| Intel SSD 660P Series                                                          | 17        | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 17        | 1.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 15        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 0.94%   |
| Intel SATA Controller [RAID mode]                                              | 15        | 0.94%   |
| Kingston Company A2000 NVMe SSD                                                | 14        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 14        | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                         | 14        | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 13        | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 0.82%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 13        | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 12        | 0.76%   |
| Phison E12 NVMe Controller                                                     | 12        | 0.76%   |
| Nvidia MCP61 SATA Controller                                                   | 12        | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 11        | 0.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 11        | 0.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 11        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 820       | 59.94%  |
| NVMe | 314       | 22.95%  |
| IDE  | 174       | 12.72%  |
| RAID | 54        | 3.95%   |
| SAS  | 4         | 0.29%   |
| SCSI | 2         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 776       | 72.39%  |
| AMD          | 286       | 26.68%  |
| ARM          | 8         | 0.75%   |
| QUALCOMM     | 1         | 0.09%   |
| CentaurHauls | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz     | 15        | 1.4%    |
| Intel Core i5-8265U CPU @ 1.60GHz     | 14        | 1.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz     | 13        | 1.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz     | 12        | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz     | 12        | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor    | 11        | 1.02%   |
| AMD Ryzen 5 3600 6-Core Processor     | 11        | 1.02%   |
| Intel Core i5-3320M CPU @ 2.60GHz     | 10        | 0.93%   |
| AMD Ryzen 9 5950X 16-Core Processor   | 10        | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz     | 9         | 0.84%   |
| Intel Core i7-4770 CPU @ 3.40GHz      | 8         | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz     | 8         | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz      | 8         | 0.74%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz  | 8         | 0.74%   |
| AMD Ryzen 7 1700 Eight-Core Processor | 8         | 0.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz     | 7         | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz     | 7         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz    | 7         | 0.65%   |
| Intel Core i5-6600K CPU @ 3.50GHz     | 7         | 0.65%   |
| AMD Ryzen 9 5900X 12-Core Processor   | 7         | 0.65%   |
| AMD Ryzen 5 2600 Six-Core Processor   | 7         | 0.65%   |
| AMD FX-8350 Eight-Core Processor      | 7         | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz    | 6         | 0.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz      | 6         | 0.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz     | 6         | 0.56%   |
| Intel Core i5-4570 CPU @ 3.20GHz      | 6         | 0.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz     | 6         | 0.56%   |
| Intel Core i5-4200U CPU @ 1.60GHz     | 6         | 0.56%   |
| Intel Core i5-2500K CPU @ 3.30GHz     | 6         | 0.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz      | 6         | 0.56%   |
| Intel Celeron CPU N2840 @ 2.16GHz     | 6         | 0.56%   |
| ARM Processor                         | 6         | 0.56%   |
| AMD Ryzen 5 5600X 6-Core Processor    | 6         | 0.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz     | 5         | 0.47%   |
| Intel Core i7-6700 CPU @ 3.40GHz      | 5         | 0.47%   |
| Intel Core i7-4790K CPU @ 4.00GHz     | 5         | 0.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz    | 5         | 0.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz     | 5         | 0.47%   |
| Intel Core i5-2410M CPU @ 2.30GHz     | 5         | 0.47%   |
| Intel Core i5 CPU M 520 @ 2.40GHz     | 5         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 272       | 25.37%  |
| Intel Core i7                  | 189       | 17.63%  |
| Intel Core i3                  | 64        | 5.97%   |
| Intel Core 2 Duo               | 56        | 5.22%   |
| AMD Ryzen 7                    | 53        | 4.94%   |
| AMD Ryzen 5                    | 52        | 4.85%   |
| Intel Celeron                  | 51        | 4.76%   |
| Other                          | 30        | 2.8%    |
| Intel Pentium                  | 30        | 2.8%    |
| AMD Ryzen 9                    | 25        | 2.33%   |
| Intel Xeon                     | 24        | 2.24%   |
| AMD FX                         | 19        | 1.77%   |
| Intel Atom                     | 18        | 1.68%   |
| Intel Pentium Dual-Core        | 14        | 1.31%   |
| AMD Athlon II X2               | 12        | 1.12%   |
| AMD Ryzen 3                    | 11        | 1.03%   |
| AMD Phenom II X4               | 10        | 0.93%   |
| AMD E1                         | 10        | 0.93%   |
| AMD Athlon 64 X2               | 9         | 0.84%   |
| AMD Ryzen 7 PRO                | 8         | 0.75%   |
| Intel Genuine                  | 7         | 0.65%   |
| AMD A8                         | 7         | 0.65%   |
| AMD A10                        | 7         | 0.65%   |
| Intel Core 2 Quad              | 6         | 0.56%   |
| Intel Core 2                   | 6         | 0.56%   |
| AMD A4                         | 6         | 0.56%   |
| Intel Core i9                  | 5         | 0.47%   |
| AMD Phenom                     | 5         | 0.47%   |
| Intel Pentium Dual             | 4         | 0.37%   |
| Intel Pentium 4                | 3         | 0.28%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.28%   |
| AMD EPYC                       | 3         | 0.28%   |
| AMD Athlon II X4               | 3         | 0.28%   |
| AMD Athlon                     | 3         | 0.28%   |
| AMD A6                         | 3         | 0.28%   |
| Intel Core Duo                 | 2         | 0.19%   |
| ARM BCM                        | 2         | 0.19%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.19%   |
| AMD Turion                     | 2         | 0.19%   |
| AMD Sempron                    | 2         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 449       | 41.85%  |
| 4      | 397       | 37%     |
| 6      | 83        | 7.74%   |
| 8      | 70        | 6.52%   |
| 1      | 24        | 2.24%   |
| 12     | 17        | 1.58%   |
| 16     | 13        | 1.21%   |
| 3      | 11        | 1.03%   |
| 10     | 3         | 0.28%   |
| 24     | 2         | 0.19%   |
| 80     | 1         | 0.09%   |
| 32     | 1         | 0.09%   |
| 14     | 1         | 0.09%   |
| 5      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1071      | 99.91%  |
| 2      | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 661       | 61.55%  |
| 1      | 413       | 38.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1046      | 97.21%  |
| Unknown        | 19        | 1.77%   |
| 32-bit         | 11        | 1.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 245       | 22.23%  |
| 0x206a7    | 71        | 6.44%   |
| 0x306a9    | 61        | 5.54%   |
| 0x306c3    | 53        | 4.81%   |
| 0x1067a    | 42        | 3.81%   |
| 0x506e3    | 36        | 3.27%   |
| 0x806ec    | 31        | 2.81%   |
| 0x40651    | 24        | 2.18%   |
| 0x806ea    | 23        | 2.09%   |
| 0x406e3    | 23        | 2.09%   |
| 0x906ea    | 19        | 1.72%   |
| 0x906e9    | 18        | 1.63%   |
| 0x08701021 | 18        | 1.63%   |
| 0x20655    | 16        | 1.45%   |
| 0x30678    | 15        | 1.36%   |
| 0x0a201016 | 15        | 1.36%   |
| 0x306d4    | 14        | 1.27%   |
| 0x20652    | 14        | 1.27%   |
| 0x10676    | 14        | 1.27%   |
| 0x806e9    | 13        | 1.18%   |
| 0x6fd      | 13        | 1.18%   |
| 0x406c4    | 13        | 1.18%   |
| 0x0800820d | 13        | 1.18%   |
| 0x08701013 | 12        | 1.09%   |
| 0x06000852 | 12        | 1.09%   |
| 0x010000c8 | 12        | 1.09%   |
| 0x806c1    | 10        | 0.91%   |
| 0x6fb      | 10        | 0.91%   |
| 0xa0652    | 9         | 0.82%   |
| 0x906eb    | 8         | 0.73%   |
| 0x506c9    | 8         | 0.73%   |
| 0x08600106 | 7         | 0.64%   |
| 0x08108102 | 7         | 0.64%   |
| 0x06001119 | 7         | 0.64%   |
| 0x906ed    | 6         | 0.54%   |
| 0x806eb    | 6         | 0.54%   |
| 0x706e5    | 6         | 0.54%   |
| 0x08001138 | 6         | 0.54%   |
| 0x05000119 | 6         | 0.54%   |
| 0x706a1    | 5         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 157       | 14.62%  |
| Haswell          | 107       | 9.96%   |
| SandyBridge      | 93        | 8.66%   |
| Skylake          | 74        | 6.89%   |
| IvyBridge        | 72        | 6.7%    |
| Penryn           | 59        | 5.49%   |
| Zen 2            | 55        | 5.12%   |
| Core             | 39        | 3.63%   |
| K10              | 37        | 3.45%   |
| Silvermont       | 36        | 3.35%   |
| Zen 3            | 34        | 3.17%   |
| Zen              | 34        | 3.17%   |
| Zen+             | 33        | 3.07%   |
| Westmere         | 33        | 3.07%   |
| Piledriver       | 25        | 2.33%   |
| K8 Hammer        | 19        | 1.77%   |
| Unknown          | 19        | 1.77%   |
| Broadwell        | 18        | 1.68%   |
| CometLake        | 17        | 1.58%   |
| TigerLake        | 13        | 1.21%   |
| IceLake          | 12        | 1.12%   |
| Nehalem          | 10        | 0.93%   |
| Goldmont         | 10        | 0.93%   |
| Excavator        | 10        | 0.93%   |
| Puma             | 7         | 0.65%   |
| Bobcat           | 7         | 0.65%   |
| P6               | 6         | 0.56%   |
| Jaguar           | 6         | 0.56%   |
| Goldmont plus    | 6         | 0.56%   |
| Bonnell          | 6         | 0.56%   |
| Steamroller      | 5         | 0.47%   |
| NetBurst         | 5         | 0.47%   |
| K8 & K10 hybrid  | 4         | 0.37%   |
| Bulldozer        | 4         | 0.37%   |
| K10 Llano        | 1         | 0.09%   |
| Alderlake Hybrid | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 565       | 46.43%  |
| Nvidia                                       | 353       | 29.01%  |
| AMD                                          | 274       | 22.51%  |
| ASPEED Technology                            | 13        | 1.07%   |
| Matrox Electronics Systems                   | 4         | 0.33%   |
| Silicon Motion                               | 3         | 0.25%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.25%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.08%   |
| VIA Technologies                             | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 68        | 5.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 40        | 3.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 2.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 27        | 2.14%   |
| Intel UHD Graphics 620                                                                   | 25        | 1.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 1.98%   |
| Intel HD Graphics 530                                                                    | 23        | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 1.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 1.5%    |
| Intel HD Graphics 620                                                                    | 17        | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 1.34%   |
| AMD Renoir                                                                               | 16        | 1.27%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 15        | 1.19%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 1.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 1.03%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 13        | 1.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 0.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                               | 10        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10        | 0.79%   |
| Intel HD Graphics 630                                                                    | 10        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 9         | 0.71%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 8         | 0.63%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8         | 0.63%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 7         | 0.55%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 0.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 435       | 40.2%   |
| 1 x Nvidia         | 243       | 22.46%  |
| 1 x AMD            | 224       | 20.7%   |
| Intel + Nvidia     | 93        | 8.6%    |
| Intel + AMD        | 19        | 1.76%   |
| 2 x AMD            | 18        | 1.66%   |
| 1 x ASPEED         | 13        | 1.2%    |
| AMD + Nvidia       | 12        | 1.11%   |
| Other              | 8         | 0.74%   |
| 2 x Nvidia         | 4         | 0.37%   |
| 1 x SiS            | 3         | 0.28%   |
| 1 x Silicon Motion | 3         | 0.28%   |
| 1 x Matrox         | 3         | 0.28%   |
| 2 x Intel          | 1         | 0.09%   |
| 1 x XGI            | 1         | 0.09%   |
| 1 x VIA            | 1         | 0.09%   |
| Nvidia + Matrox    | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 820       | 75.37%  |
| Proprietary | 209       | 19.21%  |
| Unknown     | 59        | 5.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 579       | 52.73%  |
| 0.01-0.5   | 129       | 11.75%  |
| 1.01-2.0   | 124       | 11.29%  |
| 0.51-1.0   | 81        | 7.38%   |
| 3.01-4.0   | 78        | 7.1%    |
| 7.01-8.0   | 64        | 5.83%   |
| 5.01-6.0   | 22        | 2%      |
| 2.01-3.0   | 10        | 0.91%   |
| 8.01-16.0  | 9         | 0.82%   |
| 16.01-24.0 | 2         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 177       | 14.95%  |
| AU Optronics            | 131       | 11.06%  |
| LG Display              | 106       | 8.95%   |
| Chimei Innolux          | 68        | 5.74%   |
| Dell                    | 64        | 5.41%   |
| BenQ                    | 62        | 5.24%   |
| Hewlett-Packard         | 57        | 4.81%   |
| BOE                     | 53        | 4.48%   |
| Lenovo                  | 50        | 4.22%   |
| Acer                    | 50        | 4.22%   |
| Ancor Communications    | 48        | 4.05%   |
| Goldstar                | 44        | 3.72%   |
| Philips                 | 20        | 1.69%   |
| Fujitsu Siemens         | 20        | 1.69%   |
| AOC                     | 19        | 1.6%    |
| Apple                   | 18        | 1.52%   |
| Sony                    | 17        | 1.44%   |
| Sharp                   | 16        | 1.35%   |
| ASUSTek Computer        | 16        | 1.35%   |
| InfoVision              | 14        | 1.18%   |
| ViewSonic               | 13        | 1.1%    |
| Eizo                    | 9         | 0.76%   |
| Chi Mei Optoelectronics | 9         | 0.76%   |
| LG Philips              | 8         | 0.68%   |
| Vestel Elektronik       | 6         | 0.51%   |
| Unknown                 | 6         | 0.51%   |
| Toshiba                 | 6         | 0.51%   |
| Panasonic               | 5         | 0.42%   |
| LG Electronics          | 5         | 0.42%   |
| CSO                     | 5         | 0.42%   |
| CPT                     | 4         | 0.34%   |
| PANDA                   | 3         | 0.25%   |
| Packard Bell            | 3         | 0.25%   |
| NEC Computers           | 3         | 0.25%   |
| Lenovo Group Limited    | 3         | 0.25%   |
| Iiyama                  | 3         | 0.25%   |
| IBM                     | 3         | 0.25%   |
| FUS                     | 3         | 0.25%   |
| Onkyo                   | 2         | 0.17%   |
| LGD                     | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.57%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 6         | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.49%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 5         | 0.41%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 5         | 0.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 0.33%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 4         | 0.33%   |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch           | 4         | 0.33%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 4         | 0.33%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 4         | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 4         | 0.33%   |
| BenQ ZOWIE XL LCD BNQ7F32 1920x1080 531x298mm 24.0-inch               | 4         | 0.33%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.33%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 4         | 0.33%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.24%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 3         | 0.24%   |
| Samsung Electronics T24D390 SAM0B6C 1920x1080 521x293mm 23.5-inch     | 3         | 0.24%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 3         | 0.24%   |
| Samsung Electronics CF791 SAM0DC4 3440x1440 797x333mm 34.0-inch       | 3         | 0.24%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 3         | 0.24%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 3         | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.24%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 3         | 0.24%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 3         | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.24%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch                  | 3         | 0.24%   |
| Lenovo LEN L27q-10 LEN65CE 2560x1440 597x336mm 27.0-inch              | 3         | 0.24%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.24%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 3         | 0.24%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 3         | 0.24%   |
| Lenovo LCD Monitor LEN4000 1024x768 246x184mm 12.1-inch               | 3         | 0.24%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                 | 3         | 0.24%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 3         | 0.24%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 3         | 0.24%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 3         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 466       | 40.7%   |
| 1366x768 (WXGA)    | 145       | 12.66%  |
| 3840x2160 (4K)     | 71        | 6.2%    |
| 2560x1440 (QHD)    | 71        | 6.2%    |
| 1920x1200 (WUXGA)  | 60        | 5.24%   |
| 1680x1050 (WSXGA+) | 52        | 4.54%   |
| 1600x900 (HD+)     | 52        | 4.54%   |
| 1280x1024 (SXGA)   | 44        | 3.84%   |
| 1440x900 (WXGA+)   | 29        | 2.53%   |
| 1280x800 (WXGA)    | 29        | 2.53%   |
| Unknown            | 25        | 2.18%   |
| 3440x1440          | 16        | 1.4%    |
| 1360x768           | 13        | 1.14%   |
| 3840x1080          | 9         | 0.79%   |
| 3840x2400          | 6         | 0.52%   |
| 2560x1600          | 5         | 0.44%   |
| 4480x1440          | 4         | 0.35%   |
| 1920x540           | 4         | 0.35%   |
| 1280x720 (HD)      | 4         | 0.35%   |
| 1024x600           | 4         | 0.35%   |
| 3200x1800 (QHD+)   | 3         | 0.26%   |
| 2560x1080          | 3         | 0.26%   |
| 1600x1200          | 3         | 0.26%   |
| 5760x2160          | 2         | 0.17%   |
| 5120x1440          | 2         | 0.17%   |
| 3840x1200          | 2         | 0.17%   |
| 3360x1050          | 2         | 0.17%   |
| 1400x1050          | 2         | 0.17%   |
| 800x1280           | 1         | 0.09%   |
| 5760x1440          | 1         | 0.09%   |
| 5280x1080          | 1         | 0.09%   |
| 3840x1600          | 1         | 0.09%   |
| 3520x1200          | 1         | 0.09%   |
| 3000x2000          | 1         | 0.09%   |
| 2880x1800          | 1         | 0.09%   |
| 2800x1752          | 1         | 0.09%   |
| 2736x1824          | 1         | 0.09%   |
| 2304x1440          | 1         | 0.09%   |
| 2160x1200          | 1         | 0.09%   |
| 1920x1280          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 220       | 18.8%   |
| 24      | 124       | 10.6%   |
| 13      | 105       | 8.97%   |
| 14      | 95        | 8.12%   |
| 27      | 92        | 7.86%   |
| 23      | 92        | 7.86%   |
| Unknown | 86        | 7.35%   |
| 17      | 57        | 4.87%   |
| 22      | 36        | 3.08%   |
| 19      | 36        | 3.08%   |
| 12      | 32        | 2.74%   |
| 21      | 27        | 2.31%   |
| 31      | 24        | 2.05%   |
| 84      | 19        | 1.62%   |
| 34      | 15        | 1.28%   |
| 18      | 14        | 1.2%    |
| 11      | 14        | 1.2%    |
| 20      | 11        | 0.94%   |
| 32      | 10        | 0.85%   |
| 25      | 10        | 0.85%   |
| 72      | 9         | 0.77%   |
| 40      | 5         | 0.43%   |
| 55      | 4         | 0.34%   |
| 54      | 4         | 0.34%   |
| 28      | 4         | 0.34%   |
| 26      | 4         | 0.34%   |
| 10      | 4         | 0.34%   |
| 65      | 3         | 0.26%   |
| 46      | 2         | 0.17%   |
| 29      | 2         | 0.17%   |
| 16      | 2         | 0.17%   |
| 75      | 1         | 0.09%   |
| 66      | 1         | 0.09%   |
| 48      | 1         | 0.09%   |
| 47      | 1         | 0.09%   |
| 39      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 36      | 1         | 0.09%   |
| 33      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 369       | 32.48%  |
| 501-600     | 279       | 24.56%  |
| 201-300     | 102       | 8.98%   |
| 351-400     | 91        | 8.01%   |
| 401-500     | 88        | 7.75%   |
| Unknown     | 86        | 7.57%   |
| 601-700     | 44        | 3.87%   |
| 1501-2000   | 29        | 2.55%   |
| 701-800     | 27        | 2.38%   |
| 1001-1500   | 14        | 1.23%   |
| 801-900     | 7         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 723       | 68.27%  |
| 16/10   | 183       | 17.28%  |
| Unknown | 71        | 6.7%    |
| 5/4     | 42        | 3.97%   |
| 21/9    | 18        | 1.7%    |
| 3/2     | 8         | 0.76%   |
| 4/3     | 7         | 0.66%   |
| 32/9    | 3         | 0.28%   |
| 6/5     | 2         | 0.19%   |
| 0.62    | 1         | 0.09%   |
| 0.45    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 220       | 19.13%  |
| 201-250        | 203       | 17.65%  |
| 81-90          | 157       | 13.65%  |
| 301-350        | 95        | 8.26%   |
| Unknown        | 86        | 7.48%   |
| 251-300        | 66        | 5.74%   |
| 151-200        | 58        | 5.04%   |
| 351-500        | 54        | 4.7%    |
| 71-80          | 42        | 3.65%   |
| More than 1000 | 40        | 3.48%   |
| 121-130        | 40        | 3.48%   |
| 61-70          | 32        | 2.78%   |
| 141-150        | 17        | 1.48%   |
| 51-60          | 14        | 1.22%   |
| 501-1000       | 12        | 1.04%   |
| 131-140        | 7         | 0.61%   |
| 41-50          | 4         | 0.35%   |
| 111-120        | 3         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 404       | 36.04%  |
| 121-160       | 301       | 26.85%  |
| 101-120       | 241       | 21.5%   |
| Unknown       | 86        | 7.67%   |
| 161-240       | 42        | 3.75%   |
| 1-50          | 27        | 2.41%   |
| More than 240 | 20        | 1.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 834       | 75.96%  |
| 2     | 179       | 16.3%   |
| 0     | 63        | 5.74%   |
| 3     | 20        | 1.82%   |
| 4     | 2         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 574       | 35.41%  |
| Realtek Semiconductor                  | 476       | 29.36%  |
| Qualcomm Atheros                       | 152       | 9.38%   |
| Broadcom                               | 86        | 5.31%   |
| Huawei Technologies                    | 25        | 1.54%   |
| Nvidia                                 | 24        | 1.48%   |
| Marvell Technology Group               | 23        | 1.42%   |
| Ralink                                 | 21        | 1.3%    |
| TP-Link                                | 19        | 1.17%   |
| Ericsson Business Mobile Networks      | 18        | 1.11%   |
| Hewlett-Packard                        | 16        | 0.99%   |
| Broadcom Limited                       | 15        | 0.93%   |
| ASUSTek Computer                       | 15        | 0.93%   |
| MediaTek                               | 14        | 0.86%   |
| Samsung Electronics                    | 13        | 0.8%    |
| Ralink Technology                      | 12        | 0.74%   |
| Dell                                   | 8         | 0.49%   |
| ZyXEL Communications                   | 7         | 0.43%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.37%   |
| Lenovo                                 | 6         | 0.37%   |
| Sierra Wireless                        | 5         | 0.31%   |
| Microsoft                              | 5         | 0.31%   |
| FIBOCOM                                | 5         | 0.31%   |
| D-Link System                          | 5         | 0.31%   |
| Motorola PCS                           | 4         | 0.25%   |
| Microchip Technology                   | 4         | 0.25%   |
| HMD Global                             | 4         | 0.25%   |
| ASIX Electronics                       | 4         | 0.25%   |
| Xiaomi                                 | 3         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.19%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.19%   |
| Gemtek                                 | 3         | 0.19%   |
| BUFFALO                                | 3         | 0.19%   |
| Aquantia                               | 3         | 0.19%   |
| 3Com                                   | 3         | 0.19%   |
| Qualcomm                               | 2         | 0.12%   |
| Linksys                                | 2         | 0.12%   |
| Edimax Technology                      | 2         | 0.12%   |
| DisplayLink                            | 2         | 0.12%   |
| D-Link                                 | 2         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 361       | 18.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 71        | 3.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 2.1%    |
| Intel Wi-Fi 6 AX200                                               | 38        | 1.94%   |
| Intel I211 Gigabit Network Connection                             | 37        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 36        | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 29        | 1.48%   |
| Intel Wireless 8265 / 8275                                        | 28        | 1.43%   |
| Intel Wireless 7260                                               | 28        | 1.43%   |
| Intel Wireless 8260                                               | 25        | 1.28%   |
| Intel Wireless 7265                                               | 23        | 1.18%   |
| Intel Ethernet Connection (2) I219-V                              | 23        | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 0.97%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 19        | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 0.92%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 15        | 0.77%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 15        | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 13        | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 0.66%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                    | 12        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11        | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 11        | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 11        | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 11        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 385       | 47.47%  |
| Qualcomm Atheros                  | 124       | 15.29%  |
| Realtek Semiconductor             | 106       | 13.07%  |
| Broadcom                          | 58        | 7.15%   |
| Ralink                            | 21        | 2.59%   |
| TP-Link                           | 18        | 2.22%   |
| ASUSTek Computer                  | 15        | 1.85%   |
| Ralink Technology                 | 12        | 1.48%   |
| MediaTek                          | 10        | 1.23%   |
| Broadcom Limited                  | 8         | 0.99%   |
| ZyXEL Communications              | 7         | 0.86%   |
| Sierra Wireless                   | 5         | 0.62%   |
| Microsoft                         | 5         | 0.62%   |
| Hewlett-Packard                   | 5         | 0.62%   |
| FIBOCOM                           | 5         | 0.62%   |
| Ericsson Business Mobile Networks | 5         | 0.62%   |
| Dell                              | 4         | 0.49%   |
| D-Link System                     | 4         | 0.49%   |
| Gemtek                            | 3         | 0.37%   |
| BUFFALO                           | 3         | 0.37%   |
| Edimax Technology                 | 2         | 0.25%   |
| ZyDAS                             | 1         | 0.12%   |
| Qualcomm Atheros Communications   | 1         | 0.12%   |
| NetGear                           | 1         | 0.12%   |
| Marvell Technology Group          | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 38        | 4.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 36        | 4.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 3.57%   |
| Intel Wireless 8265 / 8275                                              | 28        | 3.44%   |
| Intel Wireless 7260                                                     | 28        | 3.44%   |
| Intel Wireless 8260                                                     | 25        | 3.08%   |
| Intel Wireless 7265                                                     | 23        | 2.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 19        | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 2.21%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 15        | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 1.6%    |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.6%    |
| Intel Centrino Ultimate-N 6300                                          | 12        | 1.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 1.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.35%   |
| Intel Wireless-AC 9260                                                  | 10        | 1.23%   |
| Intel Wireless 3165                                                     | 10        | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 1.11%   |
| Intel Wireless 3160                                                     | 9         | 1.11%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.98%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 7         | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 0.86%   |
| Realtek 802.11ac NIC                                                    | 5         | 0.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 5         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 448       | 42.11%  |
| Intel                                  | 395       | 37.12%  |
| Qualcomm Atheros                       | 38        | 3.57%   |
| Broadcom                               | 38        | 3.57%   |
| Nvidia                                 | 24        | 2.26%   |
| Marvell Technology Group               | 22        | 2.07%   |
| Huawei Technologies                    | 18        | 1.69%   |
| Samsung Electronics                    | 13        | 1.22%   |
| Broadcom Limited                       | 7         | 0.66%   |
| Lenovo                                 | 6         | 0.56%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.47%   |
| MediaTek                               | 4         | 0.38%   |
| HMD Global                             | 4         | 0.38%   |
| ASIX Electronics                       | 4         | 0.38%   |
| Xiaomi                                 | 3         | 0.28%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.28%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.28%   |
| Aquantia                               | 3         | 0.28%   |
| 3Com                                   | 3         | 0.28%   |
| TP-Link                                | 2         | 0.19%   |
| Qualcomm                               | 2         | 0.19%   |
| Motorola PCS                           | 2         | 0.19%   |
| Hewlett-Packard                        | 2         | 0.19%   |
| DisplayLink                            | 2         | 0.19%   |
| VIA Technologies                       | 1         | 0.09%   |
| Standard Microsystems                  | 1         | 0.09%   |
| Microchip Technology                   | 1         | 0.09%   |
| Linksys                                | 1         | 0.09%   |
| ICS Advent                             | 1         | 0.09%   |
| Google                                 | 1         | 0.09%   |
| Foxconn / Hon Hai                      | 1         | 0.09%   |
| D-Link System                          | 1         | 0.09%   |
| D-Link                                 | 1         | 0.09%   |
| Attansic Technology                    | 1         | 0.09%   |
| American Megatrends                    | 1         | 0.09%   |
| AMD                                    | 1         | 0.09%   |
| ADMtek                                 | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 361       | 33.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 71        | 6.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 3.77%   |
| Intel I211 Gigabit Network Connection                             | 37        | 3.4%    |
| Intel Ethernet Connection (2) I219-V                              | 23        | 2.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 1.75%   |
| Intel I210 Gigabit Network Connection                             | 18        | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 1.47%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 1.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 1.38%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 1.29%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.1%    |
| Nvidia MCP61 Ethernet                                             | 11        | 1.01%   |
| Intel Ethernet Connection I219-V                                  | 11        | 1.01%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.01%   |
| Intel Ethernet Connection I217-V                                  | 11        | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10        | 0.92%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.92%   |
| Huawei YAL-L21                                                    | 10        | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.83%   |
| Intel Ethernet Controller I225-V                                  | 9         | 0.83%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.74%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.64%   |
| Intel I350 Gigabit Network Connection                             | 7         | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.64%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.55%   |
| Huawei E353/E3131                                                 | 6         | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.46%   |
| OnePlus (Shenzhen) OnePlus                                        | 5         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 967       | 54.45%  |
| WiFi     | 758       | 42.68%  |
| Modem    | 47        | 2.65%   |
| Unknown  | 4         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 548       | 50.65%  |
| Ethernet | 533       | 49.26%  |
| Unknown  | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 589       | 54.69%  |
| 1     | 433       | 40.2%   |
| 0     | 23        | 2.14%   |
| 3     | 21        | 1.95%   |
| 4     | 6         | 0.56%   |
| 5     | 5         | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 924       | 83.77%  |
| Yes  | 179       | 16.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 275       | 45.45%  |
| Broadcom                        | 55        | 9.09%   |
| Realtek Semiconductor           | 46        | 7.6%    |
| Cambridge Silicon Radio         | 39        | 6.45%   |
| Qualcomm Atheros Communications | 37        | 6.12%   |
| ASUSTek Computer                | 34        | 5.62%   |
| IMC Networks                    | 21        | 3.47%   |
| Apple                           | 20        | 3.31%   |
| Foxconn / Hon Hai               | 17        | 2.81%   |
| Hewlett-Packard                 | 13        | 2.15%   |
| Lite-On Technology              | 12        | 1.98%   |
| Dell                            | 9         | 1.49%   |
| Askey Computer                  | 6         | 0.99%   |
| Ralink                          | 4         | 0.66%   |
| Foxconn International           | 4         | 0.66%   |
| HTC (High Tech Computer)        | 3         | 0.5%    |
| Edimax Technology               | 2         | 0.33%   |
| Toshiba                         | 1         | 0.17%   |
| Taiyo Yuden                     | 1         | 0.17%   |
| Realtek                         | 1         | 0.17%   |
| MediaTek                        | 1         | 0.17%   |
| Marvell Semiconductor           | 1         | 0.17%   |
| Chicony Electronics             | 1         | 0.17%   |
| Belkin Components               | 1         | 0.17%   |
| Alps Electric                   | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 119       | 19.67%  |
| Intel AX201 Bluetooth                                                | 43        | 7.11%   |
| Intel AX200 Bluetooth                                                | 42        | 6.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 39        | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 32        | 5.29%   |
| Realtek Bluetooth Radio                                              | 26        | 4.3%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 20        | 3.31%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 14        | 2.31%   |
| Qualcomm Atheros  Bluetooth Device                                   | 14        | 2.31%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 14        | 2.31%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 12        | 1.98%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 10        | 1.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 10        | 1.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 9         | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 9         | 1.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 8         | 1.32%   |
| IMC Networks Bluetooth Device                                        | 7         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 7         | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 7         | 1.16%   |
| Apple Bluetooth USB Host Controller                                  | 7         | 1.16%   |
| IMC Networks Bluetooth Radio                                         | 6         | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 6         | 0.99%   |
| Broadcom HP Portable Bumble Bee                                      | 6         | 0.99%   |
| Askey Bluetooth Device                                               | 6         | 0.99%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 0.99%   |
| Realtek RTL8723B Bluetooth                                           | 5         | 0.83%   |
| Lite-On Bluetooth Device                                             | 5         | 0.83%   |
| Ralink RT3290 Bluetooth                                              | 4         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 4         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module                    | 4         | 0.66%   |
| Broadcom HP Portable SoftSailing                                     | 4         | 0.66%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 4         | 0.66%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 4         | 0.66%   |
| Broadcom BCM2045 Bluetooth                                           | 4         | 0.66%   |
| Apple Bluetooth Host Controller                                      | 4         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 3         | 0.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 0.5%    |
| Intel AX210 Bluetooth                                                | 3         | 0.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                    | 3         | 0.5%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 724       | 47.92%  |
| AMD                                  | 310       | 20.52%  |
| Nvidia                               | 291       | 19.26%  |
| C-Media Electronics                  | 23        | 1.52%   |
| Logitech                             | 14        | 0.93%   |
| Creative Labs                        | 12        | 0.79%   |
| Creative Technology                  | 8         | 0.53%   |
| ASUSTek Computer                     | 8         | 0.53%   |
| Realtek Semiconductor                | 7         | 0.46%   |
| GN Netcom                            | 7         | 0.46%   |
| SteelSeries ApS                      | 6         | 0.4%    |
| Kingston Technology                  | 6         | 0.4%    |
| VIA Technologies                     | 5         | 0.33%   |
| Texas Instruments                    | 5         | 0.33%   |
| RODE Microphones                     | 5         | 0.33%   |
| Plantronics                          | 5         | 0.33%   |
| Razer USA                            | 4         | 0.26%   |
| GYROCOM C&C                          | 4         | 0.26%   |
| Focusrite-Novation                   | 4         | 0.26%   |
| Blue Microphones                     | 4         | 0.26%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.2%    |
| Silicon Integrated Systems [SiS]     | 3         | 0.2%    |
| Sennheiser Communications            | 3         | 0.2%    |
| M-Audio                              | 3         | 0.2%    |
| Lenovo                               | 3         | 0.2%    |
| Corsair                              | 3         | 0.2%    |
| Microsoft                            | 2         | 0.13%   |
| Hewlett-Packard                      | 2         | 0.13%   |
| DigiTech                             | 2         | 0.13%   |
| Cambridge Audio                      | 2         | 0.13%   |
| AudioQuest                           | 2         | 0.13%   |
| ZOOM                                 | 1         | 0.07%   |
| Yamaha                               | 1         | 0.07%   |
| XMOS                                 | 1         | 0.07%   |
| Turtle Beach                         | 1         | 0.07%   |
| Trust                                | 1         | 0.07%   |
| Thomann                              | 1         | 0.07%   |
| Tenx Technology                      | 1         | 0.07%   |
| Syntek                               | 1         | 0.07%   |
| Superlux digit                       | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 88        | 4.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 72        | 4.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 68        | 3.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 57        | 3.21%   |
| AMD Family 17h/19h HD Audio Controller                                     | 56        | 3.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 54        | 3.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 54        | 3.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 40        | 2.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 37        | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 35        | 1.97%   |
| AMD FCH Azalia Controller                                                  | 33        | 1.86%   |
| Intel 8 Series HD Audio Controller                                         | 32        | 1.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 31        | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 31        | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 31        | 1.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 30        | 1.69%   |
| Nvidia GP104 High Definition Audio Controller                              | 27        | 1.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 26        | 1.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 25        | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 23        | 1.29%   |
| Intel 200 Series PCH HD Audio                                              | 23        | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 23        | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 20        | 1.12%   |
| Nvidia High Definition Audio Controller                                    | 16        | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 16        | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                               | 16        | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                   | 16        | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 15        | 0.84%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 14        | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 14        | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                         | 13        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 13        | 0.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 13        | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13        | 0.73%   |
| AMD Navi 10 HDMI Audio                                                     | 13        | 0.73%   |
| Nvidia MCP61 High Definition Audio                                         | 12        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 172       | 24.64%  |
| Kingston            | 132       | 18.91%  |
| SK hynix            | 115       | 16.48%  |
| Unknown             | 67        | 9.6%    |
| Micron Technology   | 61        | 8.74%   |
| Corsair             | 35        | 5.01%   |
| G.Skill             | 32        | 4.58%   |
| Crucial             | 28        | 4.01%   |
| Elpida              | 13        | 1.86%   |
| A-DATA Technology   | 11        | 1.58%   |
| Ramaxel Technology  | 10        | 1.43%   |
| Nanya Technology    | 7         | 1%      |
| Team                | 2         | 0.29%   |
| Qimonda             | 2         | 0.29%   |
| Unknown (ABCD)      | 1         | 0.14%   |
| PUSKILL             | 1         | 0.14%   |
| pqi                 | 1         | 0.14%   |
| Patriot             | 1         | 0.14%   |
| Hitachi             | 1         | 0.14%   |
| GOODRAM             | 1         | 0.14%   |
| GIGA-BYTE           | 1         | 0.14%   |
| ASint Technology    | 1         | 0.14%   |
| Apacer              | 1         | 0.14%   |
| 48spaces            | 1         | 0.14%   |
| Unknown             | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 10        | 1.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 8         | 1.06%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 8         | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 8         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 8         | 1.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 7         | 0.92%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 7         | 0.92%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 7         | 0.92%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 6         | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 6         | 0.79%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 6         | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s  | 5         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 5         | 0.66%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 5         | 0.66%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 4         | 0.53%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s  | 4         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 4         | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s  | 4         | 0.53%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s     | 4         | 0.53%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s       | 4         | 0.53%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 4         | 0.53%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s       | 4         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 3         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 3         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 3         | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 3         | 0.4%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 3         | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 0.4%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 3         | 0.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 3         | 0.4%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 3         | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 3         | 0.4%    |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s               | 3         | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 3         | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 3         | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 3         | 0.4%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 3         | 0.4%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s     | 3         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 273       | 43.82%  |
| DDR3    | 229       | 36.76%  |
| DDR2    | 51        | 8.19%   |
| SDRAM   | 20        | 3.21%   |
| LPDDR3  | 15        | 2.41%   |
| Unknown | 15        | 2.41%   |
| LPDDR4  | 12        | 1.93%   |
| DDR     | 6         | 0.96%   |
| DRAM    | 1         | 0.16%   |
| DDR5    | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 322       | 52.1%   |
| DIMM         | 262       | 42.39%  |
| Row Of Chips | 27        | 4.37%   |
| Chip         | 4         | 0.65%   |
| RIMM         | 2         | 0.32%   |
| Unknown      | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 227       | 33.88%  |
| 4096  | 188       | 28.06%  |
| 2048  | 105       | 15.67%  |
| 16384 | 83        | 12.39%  |
| 32768 | 31        | 4.63%   |
| 1024  | 31        | 4.63%   |
| 512   | 5         | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 133       | 19.82%  |
| 2667    | 79        | 11.77%  |
| 3200    | 73        | 10.88%  |
| 1333    | 49        | 7.3%    |
| 2400    | 43        | 6.41%   |
| 2133    | 39        | 5.81%   |
| 667     | 32        | 4.77%   |
| 1334    | 28        | 4.17%   |
| 3600    | 25        | 3.73%   |
| 800     | 20        | 2.98%   |
| 1867    | 19        | 2.83%   |
| 3466    | 15        | 2.24%   |
| Unknown | 13        | 1.94%   |
| 4267    | 8         | 1.19%   |
| 2933    | 8         | 1.19%   |
| 1067    | 8         | 1.19%   |
| 4199    | 7         | 1.04%   |
| 1066    | 7         | 1.04%   |
| 3800    | 6         | 0.89%   |
| 3000    | 5         | 0.75%   |
| 533     | 5         | 0.75%   |
| 3733    | 4         | 0.6%    |
| 3266    | 4         | 0.6%    |
| 2200    | 4         | 0.6%    |
| 2048    | 4         | 0.6%    |
| 1866    | 4         | 0.6%    |
| 2800    | 3         | 0.45%   |
| 975     | 3         | 0.45%   |
| 49926   | 2         | 0.3%    |
| 3400    | 2         | 0.3%    |
| 2666    | 2         | 0.3%    |
| 1800    | 2         | 0.3%    |
| 1639    | 2         | 0.3%    |
| 8192    | 1         | 0.15%   |
| 4800    | 1         | 0.15%   |
| 4266    | 1         | 0.15%   |
| 4000    | 1         | 0.15%   |
| 3533    | 1         | 0.15%   |
| 3334    | 1         | 0.15%   |
| 3333    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 33.33%  |
| Samsung Electronics   | 5         | 18.52%  |
| Canon                 | 4         | 14.81%  |
| Seiko Epson           | 3         | 11.11%  |
| Xerox                 | 1         | 3.7%    |
| Prolific Technology   | 1         | 3.7%    |
| Pantum                | 1         | 3.7%    |
| Lexmark International | 1         | 3.7%    |
| Dell                  | 1         | 3.7%    |
| Brother Industries    | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-1660 Series              | 2         | 7.41%   |
| Xerox Phaser 6500DN                 | 1         | 3.7%    |
| Seiko Epson XP-510 Series           | 1         | 3.7%    |
| Seiko Epson Printer                 | 1         | 3.7%    |
| Seiko Epson L555 Series             | 1         | 3.7%    |
| Samsung M2020 Series                | 1         | 3.7%    |
| Samsung CLP-325 Color Laser Printer | 1         | 3.7%    |
| Samsung C43x Series                 | 1         | 3.7%    |
| Prolific PL2305 Parallel Port       | 1         | 3.7%    |
| Pantum P2500W series                | 1         | 3.7%    |
| Lexmark International 2400 series   | 1         | 3.7%    |
| HP PSC 1100 series                  | 1         | 3.7%    |
| HP OfficeJet Pro 69                 | 1         | 3.7%    |
| HP OfficeJet 5200 series            | 1         | 3.7%    |
| HP LaserJet Professional P 1102w    | 1         | 3.7%    |
| HP LaserJet P2055 series            | 1         | 3.7%    |
| HP LaserJet P2015 series            | 1         | 3.7%    |
| HP DeskJet F300 series              | 1         | 3.7%    |
| HP DeskJet 960c                     | 1         | 3.7%    |
| HP DeskJet 2130 series              | 1         | 3.7%    |
| Dell Laser Printer 1720             | 1         | 3.7%    |
| Canon TS3300 series                 | 1         | 3.7%    |
| Canon TS3100 series                 | 1         | 3.7%    |
| Canon PIXMA MG3100 Series           | 1         | 3.7%    |
| Canon LBP6000                       | 1         | 3.7%    |
| Brother DCP-7055 scanner/printer    | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 83.33%  |
| Seiko Epson | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan N650U/N656U            | 2         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 16.67%  |
| Canon CanoScan LiDE 200               | 1         | 16.67%  |
| Canon CanoScan LiDE 110               | 1         | 16.67%  |
| Canon CanoScan LiDE 100               | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 170       | 30.52%  |
| IMC Networks                           | 44        | 7.9%    |
| Microdia                               | 43        | 7.72%   |
| Logitech                               | 39        | 7%      |
| Acer                                   | 38        | 6.82%   |
| Realtek Semiconductor                  | 36        | 6.46%   |
| Sunplus Innovation Technology          | 24        | 4.31%   |
| Quanta                                 | 22        | 3.95%   |
| Suyin                                  | 19        | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 3.41%   |
| Apple                                  | 18        | 3.23%   |
| Syntek                                 | 12        | 2.15%   |
| Lite-On Technology                     | 11        | 1.97%   |
| Silicon Motion                         | 9         | 1.62%   |
| Lenovo                                 | 9         | 1.62%   |
| Microsoft                              | 7         | 1.26%   |
| Z-Star Microelectronics                | 4         | 0.72%   |
| Samsung Electronics                    | 4         | 0.72%   |
| Primax Electronics                     | 4         | 0.72%   |
| Ricoh                                  | 3         | 0.54%   |
| Alcor Micro                            | 3         | 0.54%   |
| Luxvisions Innotech Limited            | 2         | 0.36%   |
| Importek                               | 2         | 0.36%   |
| DigiTech                               | 2         | 0.36%   |
| ALi                                    | 2         | 0.36%   |
| Trust                                  | 1         | 0.18%   |
| Technologies                           | 1         | 0.18%   |
| SunplusIT                              | 1         | 0.18%   |
| Sonix Technology                       | 1         | 0.18%   |
| OnePlus                                | 1         | 0.18%   |
| Omnivision                             | 1         | 0.18%   |
| MacroSilicon                           | 1         | 0.18%   |
| LG Electronics                         | 1         | 0.18%   |
| Hewlett-Packard                        | 1         | 0.18%   |
| Google                                 | 1         | 0.18%   |
| Creative Technology                    | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 43        | 7.69%   |
| Microdia Integrated_Webcam_HD                       | 18        | 3.22%   |
| Acer Integrated Camera                              | 13        | 2.33%   |
| IMC Networks Integrated Camera                      | 12        | 2.15%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 1.97%   |
| Realtek Integrated_Webcam_HD                        | 10        | 1.79%   |
| Chicony HP HD Camera                                | 10        | 1.79%   |
| Logitech Webcam C270                                | 9         | 1.61%   |
| Logitech HD Pro Webcam C920                         | 8         | 1.43%   |
| Chicony HP HD Webcam                                | 8         | 1.43%   |
| Chicony HD WebCam                                   | 8         | 1.43%   |
| Syntek Integrated Camera                            | 7         | 1.25%   |
| Chicony FJ Camera                                   | 7         | 1.25%   |
| Acer Lenovo EasyCamera                              | 7         | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 6         | 1.07%   |
| Chicony USB2.0 HD UVC WebCam                        | 6         | 1.07%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 6         | 1.07%   |
| Chicony EasyCamera                                  | 6         | 1.07%   |
| Sunplus HD WebCam                                   | 5         | 0.89%   |
| Realtek Lenovo EasyCamera                           | 5         | 0.89%   |
| Quanta HP Webcam                                    | 5         | 0.89%   |
| Microsoft LifeCam HD-3000                           | 5         | 0.89%   |
| Chicony Integrated HP HD Webcam                     | 5         | 0.89%   |
| Chicony Integrated Camera [ThinkPad]                | 5         | 0.89%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 0.89%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 0.72%   |
| Samsung Galaxy A5 (MTP)                             | 4         | 0.72%   |
| Realtek USB Camera                                  | 4         | 0.72%   |
| Realtek Integrated Webcam HD                        | 4         | 0.72%   |
| Primax HP HD Webcam [Fixed]                         | 4         | 0.72%   |
| Microdia Integrated Webcam                          | 4         | 0.72%   |
| Logitech Webcam C930e                               | 4         | 0.72%   |
| Lite-On Integrated Camera                           | 4         | 0.72%   |
| Lenovo UVC Camera                                   | 4         | 0.72%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 0.72%   |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.72%   |
| Chicony Lenovo EasyCamera                           | 4         | 0.72%   |
| Chicony HP TrueVision HD Camera                     | 4         | 0.72%   |
| Chicony HP HD Webcam [Fixed]                        | 4         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 56        | 40.88%  |
| Synaptics                  | 28        | 20.44%  |
| Shenzhen Goodix Technology | 13        | 9.49%   |
| AuthenTec                  | 12        | 8.76%   |
| Upek                       | 10        | 7.3%    |
| STMicroelectronics         | 9         | 6.57%   |
| LighTuning Technology      | 6         | 4.38%   |
| Elan Microelectronics      | 2         | 1.46%   |
| Microsoft                  | 1         | 0.73%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 9.49%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 9.49%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 7.3%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 6.57%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 6.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 5.84%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 5.11%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 5.11%   |
| AuthenTec AES2810                                                          | 7         | 5.11%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 3.65%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 3.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.92%   |
| Validity Sensors VFS491                                                    | 3         | 2.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.19%   |
| Unknown                                                                    | 3         | 2.19%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.46%   |
| Synaptics  WBDI                                                            | 2         | 1.46%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.46%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.46%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.73%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.73%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.73%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.73%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.73%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.73%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.73%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.73%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.73%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 40        | 43.96%  |
| Broadcom                  | 27        | 29.67%  |
| Lenovo                    | 9         | 9.89%   |
| Upek                      | 5         | 5.49%   |
| SCM Microsystems          | 3         | 3.3%    |
| O2 Micro                  | 3         | 3.3%    |
| Fujitsu Siemens Computers | 3         | 3.3%    |
| Advanced Card Systems     | 1         | 1.1%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 40        | 43.96%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 9.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 9.89%   |
| Broadcom 5880                                                                | 9         | 9.89%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.49%   |
| Broadcom 58200                                                               | 5         | 5.49%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 3.3%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.3%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 3         | 3.3%    |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 3.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.1%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 736       | 67.46%  |
| 1     | 271       | 24.84%  |
| 2     | 64        | 5.87%   |
| 3     | 11        | 1.01%   |
| 5     | 4         | 0.37%   |
| 4     | 3         | 0.27%   |
| 6     | 2         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 136       | 29.96%  |
| Graphics card            | 81        | 17.84%  |
| Chipcard                 | 81        | 17.84%  |
| Net/wireless             | 50        | 11.01%  |
| Communication controller | 18        | 3.96%   |
| Multimedia controller    | 16        | 3.52%   |
| Bluetooth                | 11        | 2.42%   |
| Camera                   | 10        | 2.2%    |
| Unassigned class         | 9         | 1.98%   |
| Net/ethernet             | 9         | 1.98%   |
| Storage                  | 8         | 1.76%   |
| Sound                    | 7         | 1.54%   |
| Card reader              | 6         | 1.32%   |
| Modem                    | 3         | 0.66%   |
| Firewire controller      | 3         | 0.66%   |
| Storage/raid             | 2         | 0.44%   |
| Storage/nvme             | 1         | 0.22%   |
| Network                  | 1         | 0.22%   |
| Flash memory             | 1         | 0.22%   |
| Dvb card                 | 1         | 0.22%   |

