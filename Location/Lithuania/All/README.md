Linux in Lithuania - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Lithuania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Lithuania/Desktop/README.md) and [notebooks](/Location/Lithuania/Notebook/README.md).

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

Total: 471

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Iconia Tab W501             | Tablet      | [196d64e793](https://linux-hardware.org/?probe=196d64e793) | Dec 25, 2022 |
| Acer          | Iconia Tab W501             | Tablet      | [32f9cc7e0b](https://linux-hardware.org/?probe=32f9cc7e0b) | Dec 25, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [11fe73ea9d](https://linux-hardware.org/?probe=11fe73ea9d) | Dec 11, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [7a6ba7238f](https://linux-hardware.org/?probe=7a6ba7238f) | Dec 08, 2022 |
| Dell          | Vostro 5502                 | Notebook    | [862097a47c](https://linux-hardware.org/?probe=862097a47c) | Dec 05, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [b7ff70b9b2](https://linux-hardware.org/?probe=b7ff70b9b2) | Nov 14, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f6bfbc00ba](https://linux-hardware.org/?probe=f6bfbc00ba) | Nov 14, 2022 |
| HP            | 3397                        | Desktop     | [27c0a5213d](https://linux-hardware.org/?probe=27c0a5213d) | Nov 11, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [bdca860f08](https://linux-hardware.org/?probe=bdca860f08) | Nov 06, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [8598cf3c36](https://linux-hardware.org/?probe=8598cf3c36) | Nov 04, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [496a16216c](https://linux-hardware.org/?probe=496a16216c) | Nov 02, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | Desktop     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f38198e874](https://linux-hardware.org/?probe=f38198e874) | Oct 23, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| HP            | 3047h                       | Desktop     | [1a0f4c46f9](https://linux-hardware.org/?probe=1a0f4c46f9) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| Dell          | G3 3579                     | Notebook    | [2191706dd0](https://linux-hardware.org/?probe=2191706dd0) | Oct 11, 2022 |
| Dell          | G3 3579                     | Notebook    | [7f20851840](https://linux-hardware.org/?probe=7f20851840) | Oct 10, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| Dell          | 0F96C8 A00                  | All in one  | [5b19e47aa9](https://linux-hardware.org/?probe=5b19e47aa9) | Oct 03, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [258d99cc9e](https://linux-hardware.org/?probe=258d99cc9e) | Sep 06, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [5ee4e3aec0](https://linux-hardware.org/?probe=5ee4e3aec0) | Sep 02, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| HP            | ProBook 440 G3              | Notebook    | [e51d4ae241](https://linux-hardware.org/?probe=e51d4ae241) | Aug 20, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| Lenovo        | ThinkPad T590 20N4004EMH    | Notebook    | [42d130e184](https://linux-hardware.org/?probe=42d130e184) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [6440e9a054](https://linux-hardware.org/?probe=6440e9a054) | Aug 12, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [063c2efc80](https://linux-hardware.org/?probe=063c2efc80) | Aug 12, 2022 |
| MSI           | MS-16F1                     | Notebook    | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [f3a7c88015](https://linux-hardware.org/?probe=f3a7c88015) | Aug 11, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | Notebook    | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| Dell          | 07T4MC A11                  | Desktop     | [61d394116d](https://linux-hardware.org/?probe=61d394116d) | Jul 20, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| eMachines     | eME443                      | Notebook    | [9197e8ef17](https://linux-hardware.org/?probe=9197e8ef17) | Jul 11, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a6420a89b6](https://linux-hardware.org/?probe=a6420a89b6) | Jun 29, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f23b75e3ca](https://linux-hardware.org/?probe=f23b75e3ca) | Jun 19, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [8f2740e70e](https://linux-hardware.org/?probe=8f2740e70e) | Jun 18, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [0d78267c59](https://linux-hardware.org/?probe=0d78267c59) | Jun 16, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [bd3336efcb](https://linux-hardware.org/?probe=bd3336efcb) | Jun 14, 2022 |
| Panasonic     | CF-52VDA131M                | Notebook    | [aa40370193](https://linux-hardware.org/?probe=aa40370193) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [310aadd79a](https://linux-hardware.org/?probe=310aadd79a) | May 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [a068dc57c8](https://linux-hardware.org/?probe=a068dc57c8) | May 13, 2022 |
| Dell          | 0F96C8 A00                  | All in one  | [b0e5c67fda](https://linux-hardware.org/?probe=b0e5c67fda) | May 11, 2022 |
| Alienware     | 17                          | Notebook    | [b30786ba0e](https://linux-hardware.org/?probe=b30786ba0e) | May 10, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [96f6c5bf2a](https://linux-hardware.org/?probe=96f6c5bf2a) | May 10, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [3e171a4858](https://linux-hardware.org/?probe=3e171a4858) | May 09, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9e90322621](https://linux-hardware.org/?probe=9e90322621) | May 06, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [08e665f8bf](https://linux-hardware.org/?probe=08e665f8bf) | May 04, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [96fc510369](https://linux-hardware.org/?probe=96fc510369) | Apr 29, 2022 |
| Dell          | Latitude 5401               | Notebook    | [d115db916d](https://linux-hardware.org/?probe=d115db916d) | Apr 23, 2022 |
| Dell          | Latitude 5401               | Notebook    | [c9f380ea26](https://linux-hardware.org/?probe=c9f380ea26) | Apr 23, 2022 |
| ASUSTek       | X55A                        | Notebook    | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [a3bf1cf766](https://linux-hardware.org/?probe=a3bf1cf766) | Apr 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [f2e4d7052d](https://linux-hardware.org/?probe=f2e4d7052d) | Apr 16, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8ba327aee7](https://linux-hardware.org/?probe=8ba327aee7) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| ASUSTek       | X55A                        | Notebook    | [9b02d587bf](https://linux-hardware.org/?probe=9b02d587bf) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5d0113f42d](https://linux-hardware.org/?probe=5d0113f42d) | Mar 16, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [c6ad6edf70](https://linux-hardware.org/?probe=c6ad6edf70) | Mar 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4b0c952d9b](https://linux-hardware.org/?probe=4b0c952d9b) | Mar 09, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [573ff5a0d0](https://linux-hardware.org/?probe=573ff5a0d0) | Feb 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [54f55cc209](https://linux-hardware.org/?probe=54f55cc209) | Feb 16, 2022 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [12a1b54a3a](https://linux-hardware.org/?probe=12a1b54a3a) | Feb 16, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [130c778a64](https://linux-hardware.org/?probe=130c778a64) | Feb 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| ASUSTek       | X55A                        | Notebook    | [dbbb7b1213](https://linux-hardware.org/?probe=dbbb7b1213) | Feb 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5616230c16](https://linux-hardware.org/?probe=5616230c16) | Feb 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a7d1f29451](https://linux-hardware.org/?probe=a7d1f29451) | Jan 31, 2022 |
| Jumper        | EZbook                      | Notebook    | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [8f6a587ed3](https://linux-hardware.org/?probe=8f6a587ed3) | Jan 20, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [a5b43fd8b4](https://linux-hardware.org/?probe=a5b43fd8b4) | Jan 05, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [8e0b4fec6c](https://linux-hardware.org/?probe=8e0b4fec6c) | Dec 26, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d824937c84](https://linux-hardware.org/?probe=d824937c84) | Dec 22, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [1252e4adb0](https://linux-hardware.org/?probe=1252e4adb0) | Dec 18, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [113924cdba](https://linux-hardware.org/?probe=113924cdba) | Dec 12, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [bc5923cefe](https://linux-hardware.org/?probe=bc5923cefe) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [f8ed9dbcf4](https://linux-hardware.org/?probe=f8ed9dbcf4) | Dec 04, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [cc0c8de988](https://linux-hardware.org/?probe=cc0c8de988) | Nov 27, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [557bb216fc](https://linux-hardware.org/?probe=557bb216fc) | Nov 20, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [2f5b5e4c72](https://linux-hardware.org/?probe=2f5b5e4c72) | Nov 19, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [d998144d2e](https://linux-hardware.org/?probe=d998144d2e) | Nov 18, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [1907e644a0](https://linux-hardware.org/?probe=1907e644a0) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [3119a05196](https://linux-hardware.org/?probe=3119a05196) | Nov 15, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b1edada81b](https://linux-hardware.org/?probe=b1edada81b) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [b455b4457c](https://linux-hardware.org/?probe=b455b4457c) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| ASUSTek       | X55A                        | Notebook    | [a55961748f](https://linux-hardware.org/?probe=a55961748f) | Nov 10, 2021 |
| ASUSTek       | X55A                        | Notebook    | [8c59513ced](https://linux-hardware.org/?probe=8c59513ced) | Nov 10, 2021 |
| ASUSTek       | K52F                        | Notebook    | [f90cbb4d26](https://linux-hardware.org/?probe=f90cbb4d26) | Nov 04, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [fe22676441](https://linux-hardware.org/?probe=fe22676441) | Nov 03, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [54e81a5d8d](https://linux-hardware.org/?probe=54e81a5d8d) | Nov 02, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3adcb9ecf9](https://linux-hardware.org/?probe=3adcb9ecf9) | Oct 26, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [1876547e8e](https://linux-hardware.org/?probe=1876547e8e) | Oct 25, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [078863a9b7](https://linux-hardware.org/?probe=078863a9b7) | Oct 25, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [7b9e7ec5f4](https://linux-hardware.org/?probe=7b9e7ec5f4) | Oct 23, 2021 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [55468e657e](https://linux-hardware.org/?probe=55468e657e) | Oct 16, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [c49552f889](https://linux-hardware.org/?probe=c49552f889) | Oct 14, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [d606b23e02](https://linux-hardware.org/?probe=d606b23e02) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [5db12e2534](https://linux-hardware.org/?probe=5db12e2534) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [239dced9a1](https://linux-hardware.org/?probe=239dced9a1) | Sep 19, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [4db5d51b06](https://linux-hardware.org/?probe=4db5d51b06) | Sep 17, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [34c7038f6f](https://linux-hardware.org/?probe=34c7038f6f) | Sep 12, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [6c5f2b8c6d](https://linux-hardware.org/?probe=6c5f2b8c6d) | Sep 11, 2021 |
| HP            | 250 G4                      | Notebook    | [6c66581e62](https://linux-hardware.org/?probe=6c66581e62) | Sep 06, 2021 |
| HP            | 09F8h                       | Desktop     | [60e1a81b56](https://linux-hardware.org/?probe=60e1a81b56) | Sep 05, 2021 |
| HP            | 250 G4                      | Notebook    | [619fff9116](https://linux-hardware.org/?probe=619fff9116) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [057cfec49e](https://linux-hardware.org/?probe=057cfec49e) | Sep 01, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [626023b280](https://linux-hardware.org/?probe=626023b280) | Aug 24, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [523f5ca193](https://linux-hardware.org/?probe=523f5ca193) | Aug 23, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [9e64453373](https://linux-hardware.org/?probe=9e64453373) | Aug 23, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [90e24e0335](https://linux-hardware.org/?probe=90e24e0335) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1c59d4f975](https://linux-hardware.org/?probe=1c59d4f975) | Aug 19, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [c358dfd2e6](https://linux-hardware.org/?probe=c358dfd2e6) | Aug 18, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | Desktop     | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| HP            | Pavilion dv7                | Notebook    | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5d33b12497](https://linux-hardware.org/?probe=5d33b12497) | Aug 13, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [652f1a31e9](https://linux-hardware.org/?probe=652f1a31e9) | Aug 10, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [80648f256b](https://linux-hardware.org/?probe=80648f256b) | Aug 10, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| HP            | 250 G4                      | Notebook    | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4752d9cb90](https://linux-hardware.org/?probe=4752d9cb90) | Aug 01, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [ffde05f551](https://linux-hardware.org/?probe=ffde05f551) | Aug 01, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [ee3189a7be](https://linux-hardware.org/?probe=ee3189a7be) | Jul 11, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [714a2fb6ec](https://linux-hardware.org/?probe=714a2fb6ec) | Jul 02, 2021 |
| Gigabyte      | P41-ES3G                    | Desktop     | [653a634621](https://linux-hardware.org/?probe=653a634621) | Jun 29, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e78af672d3](https://linux-hardware.org/?probe=e78af672d3) | Jun 18, 2021 |
| Alienware     | 17                          | Notebook    | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4020e881a1](https://linux-hardware.org/?probe=4020e881a1) | Jun 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7fa170e5ca](https://linux-hardware.org/?probe=7fa170e5ca) | Jun 10, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [45b678cc45](https://linux-hardware.org/?probe=45b678cc45) | Jun 07, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [dab115ff9f](https://linux-hardware.org/?probe=dab115ff9f) | Jun 07, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [63b5d9a81a](https://linux-hardware.org/?probe=63b5d9a81a) | Jun 05, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [56308999d2](https://linux-hardware.org/?probe=56308999d2) | Jun 05, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [20b885e70c](https://linux-hardware.org/?probe=20b885e70c) | Jun 01, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [74979cf76a](https://linux-hardware.org/?probe=74979cf76a) | Jun 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [92db46133f](https://linux-hardware.org/?probe=92db46133f) | May 24, 2021 |
| Dell          | Precision M4700             | Notebook    | [1d14e22fbd](https://linux-hardware.org/?probe=1d14e22fbd) | May 22, 2021 |
| Dell          | Inspiron 5579               | Notebook    | [83c30b9084](https://linux-hardware.org/?probe=83c30b9084) | May 15, 2021 |
| MSI           | H81M-P33                    | Desktop     | [ab8a093d72](https://linux-hardware.org/?probe=ab8a093d72) | May 12, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [84b8a6331d](https://linux-hardware.org/?probe=84b8a6331d) | May 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [49aad4b320](https://linux-hardware.org/?probe=49aad4b320) | May 04, 2021 |
| Gigabyte      | M55S-S3                     | Desktop     | [7114f9857a](https://linux-hardware.org/?probe=7114f9857a) | Apr 29, 2021 |
| Lenovo        | ThinkPad P53 20QN0034MH     | Notebook    | [bcb2272cf0](https://linux-hardware.org/?probe=bcb2272cf0) | Apr 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [26133ce35a](https://linux-hardware.org/?probe=26133ce35a) | Apr 24, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [dc665ba00d](https://linux-hardware.org/?probe=dc665ba00d) | Apr 14, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [1e30c2850c](https://linux-hardware.org/?probe=1e30c2850c) | Apr 09, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [499ccddfc2](https://linux-hardware.org/?probe=499ccddfc2) | Apr 09, 2021 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [faca4e4038](https://linux-hardware.org/?probe=faca4e4038) | Apr 08, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [f7341fd5b2](https://linux-hardware.org/?probe=f7341fd5b2) | Apr 01, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [feedaccb5b](https://linux-hardware.org/?probe=feedaccb5b) | Mar 24, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| HP            | 805A                        | Desktop     | [76ad927d3b](https://linux-hardware.org/?probe=76ad927d3b) | Mar 18, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [ad58858e33](https://linux-hardware.org/?probe=ad58858e33) | Mar 17, 2021 |
| ASUSTek       | K50C                        | Notebook    | [4ccd0463c4](https://linux-hardware.org/?probe=4ccd0463c4) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480 20L50002MH    | Notebook    | [554173e0d7](https://linux-hardware.org/?probe=554173e0d7) | Mar 17, 2021 |
| ASUSTek       | K50C                        | Notebook    | [65941d7354](https://linux-hardware.org/?probe=65941d7354) | Mar 17, 2021 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [391c72b961](https://linux-hardware.org/?probe=391c72b961) | Mar 17, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [530ac66726](https://linux-hardware.org/?probe=530ac66726) | Mar 17, 2021 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [6a44f69309](https://linux-hardware.org/?probe=6a44f69309) | Mar 17, 2021 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [e671743616](https://linux-hardware.org/?probe=e671743616) | Mar 17, 2021 |
| Lenovo        | MIIX 2 10 20359             | Tablet      | [edff48d58f](https://linux-hardware.org/?probe=edff48d58f) | Mar 13, 2021 |
| Dell          | Latitude 7380               | Notebook    | [43510cebc1](https://linux-hardware.org/?probe=43510cebc1) | Mar 13, 2021 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [15c953bc70](https://linux-hardware.org/?probe=15c953bc70) | Mar 09, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d4e62a32a8](https://linux-hardware.org/?probe=d4e62a32a8) | Mar 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7ab4c4e090](https://linux-hardware.org/?probe=7ab4c4e090) | Mar 03, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [f371afba83](https://linux-hardware.org/?probe=f371afba83) | Feb 27, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d36796da44](https://linux-hardware.org/?probe=d36796da44) | Feb 27, 2021 |
| Lenovo        | ThinkPad T430 2347EV8       | Notebook    | [3bf5967320](https://linux-hardware.org/?probe=3bf5967320) | Feb 19, 2021 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [e4702a62a8](https://linux-hardware.org/?probe=e4702a62a8) | Feb 19, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ceffe7a79e](https://linux-hardware.org/?probe=ceffe7a79e) | Feb 16, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [446351d845](https://linux-hardware.org/?probe=446351d845) | Feb 15, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [b5e1004909](https://linux-hardware.org/?probe=b5e1004909) | Feb 12, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [504106eb2c](https://linux-hardware.org/?probe=504106eb2c) | Feb 12, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [c951026b91](https://linux-hardware.org/?probe=c951026b91) | Feb 07, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [80724d2ba1](https://linux-hardware.org/?probe=80724d2ba1) | Jan 31, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a398ccbc3d](https://linux-hardware.org/?probe=a398ccbc3d) | Jan 31, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XN0... | Notebook    | [f25ec6b2f3](https://linux-hardware.org/?probe=f25ec6b2f3) | Jan 31, 2021 |
| ASRock        | H61M/U3S3                   | Desktop     | [2d831a72bb](https://linux-hardware.org/?probe=2d831a72bb) | Jan 27, 2021 |
| Acer          | Extensa 5220                | Notebook    | [20ea0cd55c](https://linux-hardware.org/?probe=20ea0cd55c) | Jan 23, 2021 |
| Acer          | Extensa 5220                | Notebook    | [9fe95abf63](https://linux-hardware.org/?probe=9fe95abf63) | Jan 23, 2021 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [a38c700d1b](https://linux-hardware.org/?probe=a38c700d1b) | Jan 16, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [b7b3175352](https://linux-hardware.org/?probe=b7b3175352) | Jan 14, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [ed7d9bff15](https://linux-hardware.org/?probe=ed7d9bff15) | Jan 13, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [91885a7829](https://linux-hardware.org/?probe=91885a7829) | Jan 05, 2021 |
| ASUSTek       | Leonite2                    | Desktop     | [9867e750d0](https://linux-hardware.org/?probe=9867e750d0) | Jan 01, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [34198a369d](https://linux-hardware.org/?probe=34198a369d) | Dec 26, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [f4ab3e4295](https://linux-hardware.org/?probe=f4ab3e4295) | Dec 26, 2020 |
| Acer          | Aspire 1410                 | Notebook    | [3ff80e7b33](https://linux-hardware.org/?probe=3ff80e7b33) | Dec 26, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [44990d7fc0](https://linux-hardware.org/?probe=44990d7fc0) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [e6e91c5ea2](https://linux-hardware.org/?probe=e6e91c5ea2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [5b56323f14](https://linux-hardware.org/?probe=5b56323f14) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [2c7c774492](https://linux-hardware.org/?probe=2c7c774492) | Dec 15, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [649ea3d331](https://linux-hardware.org/?probe=649ea3d331) | Dec 10, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [48d0f1a04c](https://linux-hardware.org/?probe=48d0f1a04c) | Dec 08, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [5c89245f08](https://linux-hardware.org/?probe=5c89245f08) | Dec 02, 2020 |
| Dell          | Latitude E7470              | Notebook    | [3c76403f27](https://linux-hardware.org/?probe=3c76403f27) | Dec 01, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [a37a75cdcb](https://linux-hardware.org/?probe=a37a75cdcb) | Nov 29, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a58e43a971](https://linux-hardware.org/?probe=a58e43a971) | Nov 20, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [374504e0bd](https://linux-hardware.org/?probe=374504e0bd) | Nov 20, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [1310e54c33](https://linux-hardware.org/?probe=1310e54c33) | Nov 20, 2020 |
| Gigabyte      | H81M-D2V                    | Desktop     | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [574e7cc90c](https://linux-hardware.org/?probe=574e7cc90c) | Nov 18, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [778d8e5380](https://linux-hardware.org/?probe=778d8e5380) | Nov 18, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [fb41abdfb1](https://linux-hardware.org/?probe=fb41abdfb1) | Nov 13, 2020 |
| Alienware     | 17                          | Notebook    | [59fdbdd4d7](https://linux-hardware.org/?probe=59fdbdd4d7) | Nov 11, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [86837daf1c](https://linux-hardware.org/?probe=86837daf1c) | Nov 10, 2020 |
| ASRock        | 880GM-LE FX                 | Desktop     | [c16ef7ddf0](https://linux-hardware.org/?probe=c16ef7ddf0) | Nov 09, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [2788cb02ed](https://linux-hardware.org/?probe=2788cb02ed) | Nov 08, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cf2cbcbe72](https://linux-hardware.org/?probe=cf2cbcbe72) | Nov 05, 2020 |
| HP            | 3048h                       | Desktop     | [96c9bd0ab6](https://linux-hardware.org/?probe=96c9bd0ab6) | Nov 05, 2020 |
| MSI           | Z87M-G43                    | Desktop     | [9de0cc7bbf](https://linux-hardware.org/?probe=9de0cc7bbf) | Nov 03, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [39dcf2485b](https://linux-hardware.org/?probe=39dcf2485b) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [f507c9b3e5](https://linux-hardware.org/?probe=f507c9b3e5) | Oct 25, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1b2dd49d08](https://linux-hardware.org/?probe=1b2dd49d08) | Oct 20, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [b3e5017b13](https://linux-hardware.org/?probe=b3e5017b13) | Oct 20, 2020 |
| HP            | 0A64h                       | Desktop     | [88899b775b](https://linux-hardware.org/?probe=88899b775b) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [09fbf70f49](https://linux-hardware.org/?probe=09fbf70f49) | Oct 16, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [c69e6488fd](https://linux-hardware.org/?probe=c69e6488fd) | Oct 14, 2020 |
| Dell          | G5 5587                     | Notebook    | [ba6fbeb10c](https://linux-hardware.org/?probe=ba6fbeb10c) | Oct 09, 2020 |
| Dell          | G5 5587                     | Notebook    | [8b28232f32](https://linux-hardware.org/?probe=8b28232f32) | Oct 09, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [5b52249750](https://linux-hardware.org/?probe=5b52249750) | Oct 04, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [a5e1c0e5f3](https://linux-hardware.org/?probe=a5e1c0e5f3) | Oct 03, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [0362c406d8](https://linux-hardware.org/?probe=0362c406d8) | Oct 03, 2020 |
| HP            | ProBook 4720s               | Notebook    | [a882fdd653](https://linux-hardware.org/?probe=a882fdd653) | Oct 02, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [d4d74a6e34](https://linux-hardware.org/?probe=d4d74a6e34) | Sep 29, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [2acb54cb0d](https://linux-hardware.org/?probe=2acb54cb0d) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [b765d71b82](https://linux-hardware.org/?probe=b765d71b82) | Sep 28, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [87092c4768](https://linux-hardware.org/?probe=87092c4768) | Sep 21, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [48825acdce](https://linux-hardware.org/?probe=48825acdce) | Sep 18, 2020 |
| Gigabyte      | H81M-D2V                    | Desktop     | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [aef0cb23ec](https://linux-hardware.org/?probe=aef0cb23ec) | Sep 16, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [6fffc9928f](https://linux-hardware.org/?probe=6fffc9928f) | Sep 10, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [7465caa486](https://linux-hardware.org/?probe=7465caa486) | Sep 10, 2020 |
| Lenovo        | ThinkPad T460s 20F90058M... | Notebook    | [352f3932b4](https://linux-hardware.org/?probe=352f3932b4) | Sep 09, 2020 |
| Dell          | Latitude 5491               | Notebook    | [06d4120fc1](https://linux-hardware.org/?probe=06d4120fc1) | Sep 08, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4d40f1808](https://linux-hardware.org/?probe=d4d40f1808) | Sep 04, 2020 |
| Lenovo        | ThinkPad L440 20ASS10F00    | Notebook    | [cb6b544787](https://linux-hardware.org/?probe=cb6b544787) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [0097d71249](https://linux-hardware.org/?probe=0097d71249) | Sep 04, 2020 |
| Timi          | TM1701                      | Notebook    | [4c01fca357](https://linux-hardware.org/?probe=4c01fca357) | Aug 25, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4bd12a2bcc](https://linux-hardware.org/?probe=4bd12a2bcc) | Aug 25, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [a5338ac2ec](https://linux-hardware.org/?probe=a5338ac2ec) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [d053bf3f76](https://linux-hardware.org/?probe=d053bf3f76) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [2551496802](https://linux-hardware.org/?probe=2551496802) | Aug 18, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8a4f211ca2](https://linux-hardware.org/?probe=8a4f211ca2) | Aug 18, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [f6a94becbf](https://linux-hardware.org/?probe=f6a94becbf) | Aug 13, 2020 |
| Dell          | XPS M1330                   | Notebook    | [4a907eebb9](https://linux-hardware.org/?probe=4a907eebb9) | Aug 02, 2020 |
| MSI           | H81M-P33                    | Desktop     | [5d7abb7a5b](https://linux-hardware.org/?probe=5d7abb7a5b) | Jul 31, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [a52cd7499e](https://linux-hardware.org/?probe=a52cd7499e) | Jul 28, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [a4948f0d33](https://linux-hardware.org/?probe=a4948f0d33) | Jul 24, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [cd250d0e7b](https://linux-hardware.org/?probe=cd250d0e7b) | Jul 24, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [810f713a78](https://linux-hardware.org/?probe=810f713a78) | Jul 24, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4c09684767](https://linux-hardware.org/?probe=4c09684767) | Jul 23, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [f31ba594be](https://linux-hardware.org/?probe=f31ba594be) | Jul 19, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [90f3c751dc](https://linux-hardware.org/?probe=90f3c751dc) | Jul 19, 2020 |
| ASUSTek       | N71Ja                       | Notebook    | [db78759a1a](https://linux-hardware.org/?probe=db78759a1a) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [0fb6ac937d](https://linux-hardware.org/?probe=0fb6ac937d) | Jul 06, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [fc16d36603](https://linux-hardware.org/?probe=fc16d36603) | Jul 03, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [9c1c6b6919](https://linux-hardware.org/?probe=9c1c6b6919) | Jun 30, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [ab2ec330ab](https://linux-hardware.org/?probe=ab2ec330ab) | Jun 24, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [78351d2937](https://linux-hardware.org/?probe=78351d2937) | Jun 22, 2020 |
| Lenovo        | ThinkPad L460 20FU0007MH    | Notebook    | [27a87ca264](https://linux-hardware.org/?probe=27a87ca264) | Jun 18, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [9c0419884f](https://linux-hardware.org/?probe=9c0419884f) | Jun 17, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [ed27c7aa81](https://linux-hardware.org/?probe=ed27c7aa81) | Jun 10, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [574368a188](https://linux-hardware.org/?probe=574368a188) | Jun 09, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [feebe9e438](https://linux-hardware.org/?probe=feebe9e438) | Jun 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [ebac9eaefe](https://linux-hardware.org/?probe=ebac9eaefe) | Jun 02, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [85443edb8d](https://linux-hardware.org/?probe=85443edb8d) | May 22, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [368e9f53e5](https://linux-hardware.org/?probe=368e9f53e5) | May 22, 2020 |
| Samsung       | RC530/RC730                 | Notebook    | [7e180f5fd2](https://linux-hardware.org/?probe=7e180f5fd2) | May 21, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [04ed3686b1](https://linux-hardware.org/?probe=04ed3686b1) | May 19, 2020 |
| ASUSTek       | X51RL                       | Notebook    | [afee28a69b](https://linux-hardware.org/?probe=afee28a69b) | May 16, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Lenovo        | ThinkPad Edge E320 12985... | Notebook    | [e4a1ece1ec](https://linux-hardware.org/?probe=e4a1ece1ec) | Apr 28, 2020 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [6100c873a3](https://linux-hardware.org/?probe=6100c873a3) | Apr 26, 2020 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [cbc58485b8](https://linux-hardware.org/?probe=cbc58485b8) | Apr 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [70daf3ad77](https://linux-hardware.org/?probe=70daf3ad77) | Apr 20, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [c4b061e0f5](https://linux-hardware.org/?probe=c4b061e0f5) | Apr 19, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| ASUSTek       | M50SA                       | Notebook    | [a7381b478e](https://linux-hardware.org/?probe=a7381b478e) | Apr 10, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [38086a42be](https://linux-hardware.org/?probe=38086a42be) | Apr 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [2246b94acb](https://linux-hardware.org/?probe=2246b94acb) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [0552ab024f](https://linux-hardware.org/?probe=0552ab024f) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [0fd03337ad](https://linux-hardware.org/?probe=0fd03337ad) | Mar 29, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [055f9887c3](https://linux-hardware.org/?probe=055f9887c3) | Mar 29, 2020 |
| Lenovo        | G550 20023                  | Notebook    | [0e9b1fb324](https://linux-hardware.org/?probe=0e9b1fb324) | Mar 29, 2020 |
| HP            | 630                         | Notebook    | [fc76abe01b](https://linux-hardware.org/?probe=fc76abe01b) | Mar 29, 2020 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [23a0bdb230](https://linux-hardware.org/?probe=23a0bdb230) | Mar 19, 2020 |
| MSI           | H61M-P20                    | Desktop     | [bd9fc44d34](https://linux-hardware.org/?probe=bd9fc44d34) | Mar 17, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| MSI           | H61M-P20                    | Desktop     | [9111061475](https://linux-hardware.org/?probe=9111061475) | Mar 10, 2020 |
| ASUSTek       | K53E                        | Notebook    | [8729f56cdc](https://linux-hardware.org/?probe=8729f56cdc) | Mar 07, 2020 |
| MSI           | Z170A GAMING M5             | Desktop     | [f1eb3e7e12](https://linux-hardware.org/?probe=f1eb3e7e12) | Mar 01, 2020 |
| MSI           | Z170A GAMING M5             | Desktop     | [7058bdb7d6](https://linux-hardware.org/?probe=7058bdb7d6) | Mar 01, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [3b537b4a10](https://linux-hardware.org/?probe=3b537b4a10) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [816d9c42da](https://linux-hardware.org/?probe=816d9c42da) | Feb 28, 2020 |
| HP            | 1589                        | Desktop     | [0c9be85544](https://linux-hardware.org/?probe=0c9be85544) | Feb 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f08088a64d](https://linux-hardware.org/?probe=f08088a64d) | Feb 20, 2020 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [2d24c5a932](https://linux-hardware.org/?probe=2d24c5a932) | Feb 15, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [c95a831b3c](https://linux-hardware.org/?probe=c95a831b3c) | Feb 11, 2020 |
| HP            | ProBook 4740s               | Notebook    | [4d4d26ef02](https://linux-hardware.org/?probe=4d4d26ef02) | Feb 03, 2020 |
| Lenovo        | ThinkPad E590 20NB0065MH    | Notebook    | [e895371f73](https://linux-hardware.org/?probe=e895371f73) | Feb 03, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [226b976601](https://linux-hardware.org/?probe=226b976601) | Jan 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6973864306](https://linux-hardware.org/?probe=6973864306) | Jan 25, 2020 |
| Acer          | Aspire V3-772               | Notebook    | [17005306cd](https://linux-hardware.org/?probe=17005306cd) | Jan 24, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [4335a97dd6](https://linux-hardware.org/?probe=4335a97dd6) | Jan 24, 2020 |
| Dell          | G3 3579                     | Notebook    | [56f84db06b](https://linux-hardware.org/?probe=56f84db06b) | Jan 22, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [f22d44d39f](https://linux-hardware.org/?probe=f22d44d39f) | Jan 22, 2020 |
| Panasonic     | CF-52WEBBYDE                | Notebook    | [0d21ee7063](https://linux-hardware.org/?probe=0d21ee7063) | Jan 17, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [cf8ada0ad0](https://linux-hardware.org/?probe=cf8ada0ad0) | Jan 16, 2020 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | Notebook    | [f57bc0120b](https://linux-hardware.org/?probe=f57bc0120b) | Jan 15, 2020 |
| MSI           | B450M PRO-VDH               | Desktop     | [5b95761a5d](https://linux-hardware.org/?probe=5b95761a5d) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [660da3e630](https://linux-hardware.org/?probe=660da3e630) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH               | Desktop     | [f45d7203c0](https://linux-hardware.org/?probe=f45d7203c0) | Jan 03, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [b0c00423bd](https://linux-hardware.org/?probe=b0c00423bd) | Dec 31, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | Notebook    | [4ea8d503ae](https://linux-hardware.org/?probe=4ea8d503ae) | Dec 13, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | Notebook    | [a298251c28](https://linux-hardware.org/?probe=a298251c28) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [924e886e1f](https://linux-hardware.org/?probe=924e886e1f) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [4a5d98c236](https://linux-hardware.org/?probe=4a5d98c236) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [b919c0cb27](https://linux-hardware.org/?probe=b919c0cb27) | Dec 13, 2019 |
| ASRock        | H61M-VS                     | Desktop     | [6d7e3aa70a](https://linux-hardware.org/?probe=6d7e3aa70a) | Dec 11, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 856               | Notebook    | [80cf2af707](https://linux-hardware.org/?probe=80cf2af707) | Nov 22, 2019 |
| HP            | Pavilion dv6                | Notebook    | [6f6270eb8e](https://linux-hardware.org/?probe=6f6270eb8e) | Nov 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [c08e4bac64](https://linux-hardware.org/?probe=c08e4bac64) | Nov 16, 2019 |
| HP            | EliteBook 8460p             | Notebook    | [56a12d5f20](https://linux-hardware.org/?probe=56a12d5f20) | Nov 09, 2019 |
| Acer          | AOD260                      | Notebook    | [a911172500](https://linux-hardware.org/?probe=a911172500) | Nov 09, 2019 |
| ASUSTek       | H110M-R                     | Desktop     | [3068ae6e29](https://linux-hardware.org/?probe=3068ae6e29) | Nov 05, 2019 |
| Sony          | VGN-C260E                   | Notebook    | [c623de88ee](https://linux-hardware.org/?probe=c623de88ee) | Oct 24, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [36deb3b32d](https://linux-hardware.org/?probe=36deb3b32d) | Oct 13, 2019 |
| HP            | Pavilion dv6                | Notebook    | [c2264e7abd](https://linux-hardware.org/?probe=c2264e7abd) | Oct 11, 2019 |
| ASUSTek       | H110M-R                     | Desktop     | [dc23169db8](https://linux-hardware.org/?probe=dc23169db8) | Oct 10, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [77b1afae40](https://linux-hardware.org/?probe=77b1afae40) | Oct 09, 2019 |
| Fujitsu Si... | D2119 S26361-D2119          | Server      | [1a0dfe074e](https://linux-hardware.org/?probe=1a0dfe074e) | Oct 01, 2019 |
| Fujitsu Si... | D2119 S26361-D2119          | Server      | [7cad023dc8](https://linux-hardware.org/?probe=7cad023dc8) | Oct 01, 2019 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [ec4b0c74d2](https://linux-hardware.org/?probe=ec4b0c74d2) | Sep 27, 2019 |
| HP            | 0A60h                       | Desktop     | [e587b4122a](https://linux-hardware.org/?probe=e587b4122a) | Sep 22, 2019 |
| ASUSTek       | K53SV                       | Notebook    | [61f7ec13d8](https://linux-hardware.org/?probe=61f7ec13d8) | Sep 19, 2019 |
| ASUSTek       | K53E                        | Notebook    | [71fd2610fe](https://linux-hardware.org/?probe=71fd2610fe) | Sep 15, 2019 |
| ASUSTek       | K53E                        | Notebook    | [e435064ad7](https://linux-hardware.org/?probe=e435064ad7) | Sep 15, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [3baafefb84](https://linux-hardware.org/?probe=3baafefb84) | Aug 27, 2019 |
| Prestigio     | PSB141C02                   | Notebook    | [3e96d56c17](https://linux-hardware.org/?probe=3e96d56c17) | Aug 25, 2019 |
| ASUSTek       | K53E                        | Notebook    | [c1811b7ec3](https://linux-hardware.org/?probe=c1811b7ec3) | Aug 23, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [15419d9561](https://linux-hardware.org/?probe=15419d9561) | Aug 20, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7653d7fa4d](https://linux-hardware.org/?probe=7653d7fa4d) | Jul 29, 2019 |
| Lenovo        | G550 20023                  | Notebook    | [601d53f9eb](https://linux-hardware.org/?probe=601d53f9eb) | Jul 23, 2019 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5b8d494c04](https://linux-hardware.org/?probe=5b8d494c04) | Jul 12, 2019 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [fd394cc113](https://linux-hardware.org/?probe=fd394cc113) | Jun 05, 2019 |
| Lenovo        | ThinkPad R500 27327KG       | Notebook    | [c8b31c9d99](https://linux-hardware.org/?probe=c8b31c9d99) | Jun 04, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [23d8e1dd30](https://linux-hardware.org/?probe=23d8e1dd30) | May 31, 2019 |
| Acer          | TravelMate 5740G            | Notebook    | [0d4611c952](https://linux-hardware.org/?probe=0d4611c952) | May 25, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [be887070fe](https://linux-hardware.org/?probe=be887070fe) | May 17, 2019 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [c39268dff8](https://linux-hardware.org/?probe=c39268dff8) | May 13, 2019 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [e0d133befc](https://linux-hardware.org/?probe=e0d133befc) | May 13, 2019 |
| HP            | ProBook 6555b               | Notebook    | [598fc6c1ca](https://linux-hardware.org/?probe=598fc6c1ca) | May 13, 2019 |
| HP            | ProBook 4540s               | Notebook    | [2e61bfe1be](https://linux-hardware.org/?probe=2e61bfe1be) | Apr 28, 2019 |
| HP            | ProBook 4540s               | Notebook    | [8d460232a9](https://linux-hardware.org/?probe=8d460232a9) | Apr 28, 2019 |
| Dell          | Inspiron 5737               | Notebook    | [2c7d308e3a](https://linux-hardware.org/?probe=2c7d308e3a) | Apr 26, 2019 |
| Dell          | Inspiron 5737               | Notebook    | [dcf03f780e](https://linux-hardware.org/?probe=dcf03f780e) | Apr 26, 2019 |
| Acer          | TravelMate 5740G            | Notebook    | [6b69828c13](https://linux-hardware.org/?probe=6b69828c13) | Apr 07, 2019 |
| Sony          | VPCZ1390S                   | Notebook    | [eb4e58c4d9](https://linux-hardware.org/?probe=eb4e58c4d9) | Mar 05, 2019 |
| Sony          | VPCZ1390S                   | Notebook    | [8995c67e48](https://linux-hardware.org/?probe=8995c67e48) | Mar 05, 2019 |
| ASRock        | X370 Taichi                 | Desktop     | [283ce85ac6](https://linux-hardware.org/?probe=283ce85ac6) | Feb 20, 2019 |
| Lenovo        | ThinkPad X230 2325AEG       | Notebook    | [2b8bcfe576](https://linux-hardware.org/?probe=2b8bcfe576) | Feb 19, 2019 |
| ASUSTek       | X550LB                      | Notebook    | [992697103b](https://linux-hardware.org/?probe=992697103b) | Jan 18, 2019 |
| ASUSTek       | X550LB                      | Notebook    | [5228ac3dbc](https://linux-hardware.org/?probe=5228ac3dbc) | Jan 18, 2019 |
| Dell          | 0XFWHV A00                  | Desktop     | [f9e47efc1f](https://linux-hardware.org/?probe=f9e47efc1f) | Jan 12, 2019 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [dffa2ed3ef](https://linux-hardware.org/?probe=dffa2ed3ef) | Dec 20, 2018 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [e192353344](https://linux-hardware.org/?probe=e192353344) | Dec 20, 2018 |
| Lenovo        | G550 20023                  | Notebook    | [54fd0e13d2](https://linux-hardware.org/?probe=54fd0e13d2) | Oct 29, 2018 |
| MSI           | Z170A GAMING M5             | Desktop     | [68365011c2](https://linux-hardware.org/?probe=68365011c2) | Oct 26, 2018 |
| Lenovo        | G550 20023                  | Notebook    | [3011864d4b](https://linux-hardware.org/?probe=3011864d4b) | Oct 25, 2018 |
| Intel         | DB65AL AAG12530-302         | Desktop     | [be0b280760](https://linux-hardware.org/?probe=be0b280760) | Oct 25, 2018 |
| ASUSTek       | K53E                        | Notebook    | [0e63193763](https://linux-hardware.org/?probe=0e63193763) | Oct 21, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8a053e30bf](https://linux-hardware.org/?probe=8a053e30bf) | Sep 30, 2018 |
| HP            | 0A60h                       | Desktop     | [887d9e063a](https://linux-hardware.org/?probe=887d9e063a) | Sep 24, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8e1eab57d7](https://linux-hardware.org/?probe=8e1eab57d7) | Sep 03, 2018 |
| ASUSTek       | 1225B                       | Notebook    | [fb333d2cde](https://linux-hardware.org/?probe=fb333d2cde) | Aug 23, 2018 |
| HP            | 0A60h                       | Desktop     | [180ad06c55](https://linux-hardware.org/?probe=180ad06c55) | Aug 21, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8ebafe3965](https://linux-hardware.org/?probe=8ebafe3965) | Aug 04, 2018 |
| HP            | 0A60h                       | Desktop     | [4ed0a42e5c](https://linux-hardware.org/?probe=4ed0a42e5c) | Jun 30, 2018 |
| ASUSTek       | K53E                        | Notebook    | [58b632622d](https://linux-hardware.org/?probe=58b632622d) | Apr 15, 2018 |
| ASUSTek       | X555LN                      | Notebook    | [9760e114b0](https://linux-hardware.org/?probe=9760e114b0) | Apr 07, 2018 |
| ASUSTek       | X555LN                      | Notebook    | [c3f232766b](https://linux-hardware.org/?probe=c3f232766b) | Apr 07, 2018 |
| ASUSTek       | K53SV                       | Notebook    | [e3e865dedf](https://linux-hardware.org/?probe=e3e865dedf) | Apr 06, 2018 |
| ASUSTek       | M4A785T-M                   | Desktop     | [0f2664d3b1](https://linux-hardware.org/?probe=0f2664d3b1) | Mar 29, 2018 |
| ASUSTek       | M4A785T-M                   | Desktop     | [1a91c5f47f](https://linux-hardware.org/?probe=1a91c5f47f) | Mar 05, 2018 |
| Intel         | D102GGC2 AAD42789-201       | Desktop     | [d52ebc3540](https://linux-hardware.org/?probe=d52ebc3540) | Jan 09, 2018 |
| Intel         | D102GGC2 AAD42789-201       | Desktop     | [16d64740e8](https://linux-hardware.org/?probe=16d64740e8) | Jan 09, 2018 |
| ASUSTek       | K53SV                       | Notebook    | [041cd61823](https://linux-hardware.org/?probe=041cd61823) | Dec 14, 2017 |
| Acer          | Aspire 5610Z                | Notebook    | [c79786fae0](https://linux-hardware.org/?probe=c79786fae0) | Dec 12, 2017 |
| ASRock        | ALiveDual-eSATA2            | Desktop     | [7330a7e461](https://linux-hardware.org/?probe=7330a7e461) | Sep 27, 2017 |
| Dell          | Inspiron 3537               | Notebook    | [0cb8d57f73](https://linux-hardware.org/?probe=0cb8d57f73) | Sep 25, 2017 |
| ASUSTek       | M50Vc                       | Notebook    | [9224093b58](https://linux-hardware.org/?probe=9224093b58) | Aug 22, 2017 |
| ASUSTek       | K53SV                       | Notebook    | [366e5e884c](https://linux-hardware.org/?probe=366e5e884c) | Jun 23, 2017 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0ba3b01a3b](https://linux-hardware.org/?probe=0ba3b01a3b) | May 17, 2017 |
| ASRock        | 980DE3/U3S3 R2.0            | Desktop     | [ce9b629fa0](https://linux-hardware.org/?probe=ce9b629fa0) | Apr 21, 2017 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0a9d97b358](https://linux-hardware.org/?probe=0a9d97b358) | Apr 11, 2017 |
| Dell          | Precision M4600             | Notebook    | [2a09c39637](https://linux-hardware.org/?probe=2a09c39637) | Mar 15, 2017 |
| Dell          | Precision M4600             | Notebook    | [c9a115e18c](https://linux-hardware.org/?probe=c9a115e18c) | Mar 15, 2017 |
| ASRock        | G41M-VS3                    | Desktop     | [8915ed904a](https://linux-hardware.org/?probe=8915ed904a) | Mar 14, 2017 |
| Acer          | Aspire ES1-711              | Notebook    | [0f7625ddc4](https://linux-hardware.org/?probe=0f7625ddc4) | Mar 10, 2017 |
| Acer          | Aspire ES1-711              | Notebook    | [64cea7b4eb](https://linux-hardware.org/?probe=64cea7b4eb) | Mar 10, 2017 |
| ASRock        | G41C-VS                     | Desktop     | [3688013a36](https://linux-hardware.org/?probe=3688013a36) | Dec 02, 2016 |
| ASRock        | G41C-VS                     | Desktop     | [9f9c0116cd](https://linux-hardware.org/?probe=9f9c0116cd) | Nov 30, 2016 |
| ASRock        | G41C-VS                     | Desktop     | [a1993f9fc4](https://linux-hardware.org/?probe=a1993f9fc4) | Nov 28, 2016 |
| Dell          | Precision M4600             | Notebook    | [e851921cd7](https://linux-hardware.org/?probe=e851921cd7) | Oct 24, 2016 |
| Dell          | Latitude E6440              | Notebook    | [ea1b5da2e7](https://linux-hardware.org/?probe=ea1b5da2e7) | Dec 07, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 33        | 9.79%   |
| Ubuntu 18.04       | 27        | 8.01%   |
| Arch Rolling       | 11        | 3.26%   |
| Arch               | 10        | 2.97%   |
| Ubuntu 22.04       | 9         | 2.67%   |
| ROSA R11           | 8         | 2.37%   |
| Pop!_OS 21.04      | 8         | 2.37%   |
| ROSA R8.1          | 7         | 2.08%   |
| ROSA R10           | 7         | 2.08%   |
| OpenMandriva 4.2   | 7         | 2.08%   |
| KDE neon 20.04     | 7         | 2.08%   |
| Zorin 16           | 6         | 1.78%   |
| Ubuntu 19.10       | 6         | 1.78%   |
| Ubuntu 19.04       | 6         | 1.78%   |
| OpenMandriva 4.3   | 6         | 1.78%   |
| Manjaro            | 6         | 1.78%   |
| Xubuntu 20.04      | 5         | 1.48%   |
| Ubuntu 21.10       | 5         | 1.48%   |
| ROSA R9            | 5         | 1.48%   |
| Pop!_OS 22.04      | 5         | 1.48%   |
| Pop!_OS 21.10      | 5         | 1.48%   |
| Pop!_OS 20.04      | 5         | 1.48%   |
| Manjaro 20.2.1     | 5         | 1.48%   |
| Linux Mint 20      | 5         | 1.48%   |
| Fedora 33          | 5         | 1.48%   |
| Debian 10          | 5         | 1.48%   |
| ArcoLinux Rolling  | 5         | 1.48%   |
| Ubuntu 20.10       | 4         | 1.19%   |
| ROSA R11.1         | 4         | 1.19%   |
| Linux Mint 20.1    | 4         | 1.19%   |
| Fedora 36          | 4         | 1.19%   |
| Xubuntu 19.10      | 3         | 0.89%   |
| RHEL 8             | 3         | 0.89%   |
| Linux Mint 19.3    | 3         | 0.89%   |
| Fedora 34          | 3         | 0.89%   |
| Fedora 32          | 3         | 0.89%   |
| CentOS 8           | 3         | 0.89%   |
| Zorin 15           | 2         | 0.59%   |
| Ubuntu Unity 16.04 | 2         | 0.59%   |
| Ubuntu 16.04       | 2         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 90        | 28.66%  |
| ROSA         | 28        | 8.92%   |
| Pop!_OS      | 25        | 7.96%   |
| Manjaro      | 21        | 6.69%   |
| Arch         | 20        | 6.37%   |
| Linux Mint   | 19        | 6.05%   |
| Fedora       | 16        | 5.1%    |
| OpenMandriva | 13        | 4.14%   |
| Debian       | 9         | 2.87%   |
| Zorin        | 8         | 2.55%   |
| KDE neon     | 8         | 2.55%   |
| Xubuntu      | 7         | 2.23%   |
| Kubuntu      | 5         | 1.59%   |
| ArcoLinux    | 5         | 1.59%   |
| Lubuntu      | 4         | 1.27%   |
| Endless      | 4         | 1.27%   |
| Ubuntu Unity | 3         | 0.96%   |
| RHEL         | 3         | 0.96%   |
| openSUSE     | 3         | 0.96%   |
| Elementary   | 3         | 0.96%   |
| CentOS       | 3         | 0.96%   |
| RED          | 2         | 0.64%   |
| Gentoo       | 2         | 0.64%   |
| Artix        | 2         | 0.64%   |
| Ubuntu MATE  | 1         | 0.32%   |
| PostmarketOS | 1         | 0.32%   |
| Peppermint   | 1         | 0.32%   |
| Nobara       | 1         | 0.32%   |
| Manjaro-ARM  | 1         | 0.32%   |
| LMDE         | 1         | 0.32%   |
| Garuda Linux | 1         | 0.32%   |
| EndeavourOS  | 1         | 0.32%   |
| Drauger OS   | 1         | 0.32%   |
| Deepin       | 1         | 0.32%   |
| Clear Linux  | 1         | 0.32%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 7         | 1.91%   |
| 5.10.14-desktop-1omv4002        | 7         | 1.91%   |
| 5.13.0-40-generic               | 6         | 1.63%   |
| 5.4.0-48-generic                | 5         | 1.36%   |
| 5.16.7-desktop-1omv4003         | 5         | 1.36%   |
| 5.4.0-66-generic                | 4         | 1.09%   |
| 5.3.0-28-generic                | 4         | 1.09%   |
| 5.9.16-1-MANJARO                | 3         | 0.82%   |
| 5.4.0-70-generic                | 3         | 0.82%   |
| 5.4.0-47-generic                | 3         | 0.82%   |
| 5.3.0-26-generic                | 3         | 0.82%   |
| 5.3.0-23-generic                | 3         | 0.82%   |
| 5.11.0-7620-generic             | 3         | 0.82%   |
| 4.9.60-nrj-desktop-1rosa-i586   | 3         | 0.82%   |
| 4.9.41-nrj-desktop-1rosa-x86_64 | 3         | 0.82%   |
| 4.15.0-desktop-60.7rosa-i586    | 3         | 0.82%   |
| 4.15.0-91-generic               | 3         | 0.82%   |
| 5.8.3-zen1-1-zen                | 2         | 0.54%   |
| 5.8.12-200.fc32.x86_64          | 2         | 0.54%   |
| 5.8.0-48-generic                | 2         | 0.54%   |
| 5.8.0-44-generic                | 2         | 0.54%   |
| 5.4.0-7634-generic              | 2         | 0.54%   |
| 5.4.0-73-generic                | 2         | 0.54%   |
| 5.4.0-52-generic                | 2         | 0.54%   |
| 5.4.0-31-generic                | 2         | 0.54%   |
| 5.4.0-26-generic                | 2         | 0.54%   |
| 5.3.0-46-generic                | 2         | 0.54%   |
| 5.3.0-40-generic                | 2         | 0.54%   |
| 5.3.0-24-generic                | 2         | 0.54%   |
| 5.19.0-76051900-generic         | 2         | 0.54%   |
| 5.18.10-76051810-generic        | 2         | 0.54%   |
| 5.16.11-76051611-generic        | 2         | 0.54%   |
| 5.15.23-2-lts                   | 2         | 0.54%   |
| 5.15.15-76051515-generic        | 2         | 0.54%   |
| 5.15.0-50-generic               | 2         | 0.54%   |
| 5.15.0-47-generic               | 2         | 0.54%   |
| 5.15.0-46-generic               | 2         | 0.54%   |
| 5.15.0-43-generic               | 2         | 0.54%   |
| 5.13.0-7620-generic             | 2         | 0.54%   |
| 5.13.0-39-generic               | 2         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 49        | 14.24%  |
| 4.15.0  | 28        | 8.14%   |
| 5.3.0   | 22        | 6.4%    |
| 5.13.0  | 18        | 5.23%   |
| 5.15.0  | 16        | 4.65%   |
| 5.8.0   | 15        | 4.36%   |
| 5.11.0  | 13        | 3.78%   |
| 5.0.0   | 12        | 3.49%   |
| 5.16.7  | 7         | 2.03%   |
| 5.10.14 | 7         | 2.03%   |
| 4.18.0  | 7         | 2.03%   |
| 5.10.0  | 4         | 1.16%   |
| 4.9.60  | 4         | 1.16%   |
| 4.19.0  | 4         | 1.16%   |
| 5.9.16  | 3         | 0.87%   |
| 5.19.0  | 3         | 0.87%   |
| 4.9.9   | 3         | 0.87%   |
| 4.9.41  | 3         | 0.87%   |
| 4.9.20  | 3         | 0.87%   |
| 6.0.6   | 2         | 0.58%   |
| 6.0.0   | 2         | 0.58%   |
| 5.9.13  | 2         | 0.58%   |
| 5.8.3   | 2         | 0.58%   |
| 5.8.18  | 2         | 0.58%   |
| 5.8.12  | 2         | 0.58%   |
| 5.8.11  | 2         | 0.58%   |
| 5.7.17  | 2         | 0.58%   |
| 5.4.70  | 2         | 0.58%   |
| 5.4.13  | 2         | 0.58%   |
| 5.18.10 | 2         | 0.58%   |
| 5.17.5  | 2         | 0.58%   |
| 5.16.16 | 2         | 0.58%   |
| 5.16.11 | 2         | 0.58%   |
| 5.15.23 | 2         | 0.58%   |
| 5.15.15 | 2         | 0.58%   |
| 5.10.7  | 2         | 0.58%   |
| 5.10.16 | 2         | 0.58%   |
| 4.9.76  | 2         | 0.58%   |
| 4.4.16  | 2         | 0.58%   |
| 4.1.34  | 2         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 58        | 17.06%  |
| 5.15    | 29        | 8.53%   |
| 4.15    | 28        | 8.24%   |
| 5.10    | 26        | 7.65%   |
| 5.8     | 24        | 7.06%   |
| 5.3     | 22        | 6.47%   |
| 5.13    | 22        | 6.47%   |
| 4.9     | 18        | 5.29%   |
| 5.11    | 16        | 4.71%   |
| 5.16    | 14        | 4.12%   |
| 5.0     | 13        | 3.82%   |
| 5.19    | 7         | 2.06%   |
| 5.12    | 7         | 2.06%   |
| 4.18    | 7         | 2.06%   |
| 6.0     | 6         | 1.76%   |
| 5.9     | 6         | 1.76%   |
| 5.18    | 5         | 1.47%   |
| 4.19    | 5         | 1.47%   |
| 5.7     | 4         | 1.18%   |
| 5.17    | 4         | 1.18%   |
| 5.14    | 4         | 1.18%   |
| 4.14    | 4         | 1.18%   |
| 5.6     | 3         | 0.88%   |
| 4.4     | 3         | 0.88%   |
| 4.1     | 3         | 0.88%   |
| 5.5     | 1         | 0.29%   |
| 3.16    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 280       | 93.96%  |
| i686    | 16        | 5.37%   |
| armv7l  | 1         | 0.34%   |
| aarch64 | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 124       | 39.12%  |
| KDE5            | 46        | 14.51%  |
| Unknown         | 36        | 11.36%  |
| XFCE            | 27        | 8.52%   |
| KDE4            | 23        | 7.26%   |
| X-Cinnamon      | 16        | 5.05%   |
| KDE             | 13        | 4.1%    |
| LXQt            | 6         | 1.89%   |
| Unity           | 4         | 1.26%   |
| MATE            | 4         | 1.26%   |
| Pantheon        | 3         | 0.95%   |
| Cinnamon        | 3         | 0.95%   |
| GNOME Flashback | 2         | 0.63%   |
| Enlightenment   | 2         | 0.63%   |
| Deepin          | 2         | 0.63%   |
| awesome         | 2         | 0.63%   |
| LXDE            | 1         | 0.32%   |
| i3              | 1         | 0.32%   |
| dwm             | 1         | 0.32%   |
| Budgie          | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 245       | 79.03%  |
| Wayland | 40        | 12.9%   |
| Unknown | 15        | 4.84%   |
| Tty     | 10        | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 151       | 48.55%  |
| SDDM    | 40        | 12.86%  |
| GDM     | 38        | 12.22%  |
| LightDM | 27        | 8.68%   |
| KDM     | 22        | 7.07%   |
| GDM3    | 18        | 5.79%   |
| TDM     | 14        | 4.5%    |
| XDM     | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 172       | 56.03%  |
| Unknown | 55        | 17.92%  |
| lt_LT   | 45        | 14.66%  |
| en_GB   | 15        | 4.89%   |
| ru_RU   | 14        | 4.56%   |
| C       | 3         | 0.98%   |
| en_AU   | 2         | 0.65%   |
| uk_UA   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 166       | 54.79%  |
| EFI  | 137       | 45.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 230       | 75.91%  |
| Btrfs   | 23        | 7.59%   |
| Unknown | 23        | 7.59%   |
| Overlay | 16        | 5.28%   |
| Xfs     | 8         | 2.64%   |
| Zfs     | 1         | 0.33%   |
| SAMSUNG | 1         | 0.33%   |
| ExX4    | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 165       | 53.92%  |
| GPT     | 94        | 30.72%  |
| MBR     | 47        | 15.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 259       | 86.33%  |
| Yes       | 41        | 13.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 228       | 75.75%  |
| Yes       | 73        | 24.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 63        | 21.36%  |
| Lenovo                  | 60        | 20.34%  |
| Hewlett-Packard         | 36        | 12.2%   |
| Dell                    | 34        | 11.53%  |
| Gigabyte Technology     | 21        | 7.12%   |
| ASRock                  | 19        | 6.44%   |
| MSI                     | 18        | 6.1%    |
| Acer                    | 12        | 4.07%   |
| Intel                   | 6         | 2.03%   |
| Samsung Electronics     | 3         | 1.02%   |
| Toshiba                 | 2         | 0.68%   |
| Sony                    | 2         | 0.68%   |
| Panasonic               | 2         | 0.68%   |
| Fujitsu Siemens         | 2         | 0.68%   |
| Apple                   | 2         | 0.68%   |
| Timi                    | 1         | 0.34%   |
| Raspberry Pi Foundation | 1         | 0.34%   |
| Prestigio               | 1         | 0.34%   |
| Packard Bell            | 1         | 0.34%   |
| Microsoft               | 1         | 0.34%   |
| Jumper                  | 1         | 0.34%   |
| HUAWEI                  | 1         | 0.34%   |
| Fujitsu                 | 1         | 0.34%   |
| eMachines               | 1         | 0.34%   |
| BESSTAR Tech            | 1         | 0.34%   |
| AMI                     | 1         | 0.34%   |
| Alienware               | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| MSI MS-7A38                                           | 3         | 1.02%   |
| MSI MS-7C82                                           | 2         | 0.68%   |
| MSI MS-7823                                           | 2         | 0.68%   |
| MSI MS-7817                                           | 2         | 0.68%   |
| Lenovo ThinkPad T490 20N3000KMH                       | 2         | 0.68%   |
| Lenovo S40-40 F0AX00EAPB                              | 2         | 0.68%   |
| Lenovo Legion Y530-15ICH 81FV                         | 2         | 0.68%   |
| Lenovo IdeaPad Y700-15ISK 80NV                        | 2         | 0.68%   |
| Lenovo G550 20023                                     | 2         | 0.68%   |
| HP EliteBook 8460p                                    | 2         | 0.68%   |
| ASUS PRIME Z390-A                                     | 2         | 0.68%   |
| ASUS PRIME B450M-K                                    | 2         | 0.68%   |
| ASUS PRIME B450M-A                                    | 2         | 0.68%   |
| ASUS K53E                                             | 2         | 0.68%   |
| ASUS All Series                                       | 2         | 0.68%   |
| Toshiba Satellite L855                                | 1         | 0.34%   |
| Toshiba Satellite C50D-A-13G                          | 1         | 0.34%   |
| Timi TM1701                                           | 1         | 0.34%   |
| Sony VPCZ1390S                                        | 1         | 0.34%   |
| Sony VGN-C260E                                        | 1         | 0.34%   |
| Samsung RC530/RC730                                   | 1         | 0.34%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.34%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.34%   |
| RPi Raspberry Pi 4 Model B Rev 1.1                    | 1         | 0.34%   |
| Prestigio PSB141C02                                   | 1         | 0.34%   |
| Panasonic CF-52WEBBYDE                                | 1         | 0.34%   |
| Panasonic CF-52VDA131M                                | 1         | 0.34%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.34%   |
| MSI MS-7C35                                           | 1         | 0.34%   |
| MSI MS-7B89                                           | 1         | 0.34%   |
| MSI MS-7B18                                           | 1         | 0.34%   |
| MSI MS-7A71                                           | 1         | 0.34%   |
| MSI MS-7A34                                           | 1         | 0.34%   |
| MSI MS-7977                                           | 1         | 0.34%   |
| MSI MS-7788                                           | 1         | 0.34%   |
| MSI MS-16F1                                           | 1         | 0.34%   |
| MSI Bravo 15 A4DDR                                    | 1         | 0.34%   |
| Microsoft Surface with Windows RT                     | 1         | 0.34%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.34%   |
| Lenovo Yoga Creator 7 15IMH05 82DS                    | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 34        | 11.53%  |
| Dell Inspiron     | 11        | 3.73%   |
| ASUS PRIME        | 11        | 3.73%   |
| HP ProBook        | 10        | 3.39%   |
| HP EliteBook      | 8         | 2.71%   |
| Lenovo IdeaPad    | 7         | 2.37%   |
| HP Compaq         | 7         | 2.37%   |
| Dell Latitude     | 7         | 2.37%   |
| Acer Aspire       | 7         | 2.37%   |
| ASUS VivoBook     | 5         | 1.69%   |
| ASUS TUF          | 5         | 1.69%   |
| Dell XPS          | 4         | 1.36%   |
| Dell Vostro       | 4         | 1.36%   |
| MSI MS-7A38       | 3         | 1.02%   |
| Lenovo Yoga       | 3         | 1.02%   |
| Lenovo Legion     | 3         | 1.02%   |
| Gigabyte X570     | 3         | 1.02%   |
| Dell OptiPlex     | 3         | 1.02%   |
| Toshiba Satellite | 2         | 0.68%   |
| MSI MS-7C82       | 2         | 0.68%   |
| MSI MS-7823       | 2         | 0.68%   |
| MSI MS-7817       | 2         | 0.68%   |
| Lenovo S40-40     | 2         | 0.68%   |
| Lenovo G550       | 2         | 0.68%   |
| HP Pavilion       | 2         | 0.68%   |
| HP Laptop         | 2         | 0.68%   |
| HP ENVY           | 2         | 0.68%   |
| HP 250            | 2         | 0.68%   |
| Dell Precision    | 2         | 0.68%   |
| ASUS ZenBook      | 2         | 0.68%   |
| ASUS ROG          | 2         | 0.68%   |
| ASUS K53E         | 2         | 0.68%   |
| ASUS All          | 2         | 0.68%   |
| ASRock B450       | 2         | 0.68%   |
| Timi TM1701       | 1         | 0.34%   |
| Sony VPCZ1390S    | 1         | 0.34%   |
| Sony VGN-C260E    | 1         | 0.34%   |
| Samsung RC530     | 1         | 0.34%   |
| Samsung 530U3C    | 1         | 0.34%   |
| Samsung 300E5EV   | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 39        | 13.22%  |
| 2013 | 25        | 8.47%   |
| 2011 | 25        | 8.47%   |
| 2019 | 24        | 8.14%   |
| 2012 | 22        | 7.46%   |
| 2020 | 21        | 7.12%   |
| 2017 | 19        | 6.44%   |
| 2015 | 18        | 6.1%    |
| 2014 | 17        | 5.76%   |
| 2009 | 16        | 5.42%   |
| 2021 | 15        | 5.08%   |
| 2010 | 13        | 4.41%   |
| 2016 | 12        | 4.07%   |
| 2008 | 11        | 3.73%   |
| 2006 | 7         | 2.37%   |
| 2007 | 6         | 2.03%   |
| 2022 | 3         | 1.02%   |
| 2005 | 1         | 0.34%   |
| 2004 | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 174       | 58.98%  |
| Desktop        | 106       | 35.93%  |
| All in one     | 5         | 1.69%   |
| Tablet         | 3         | 1.02%   |
| Convertible    | 3         | 1.02%   |
| Server         | 2         | 0.68%   |
| System on chip | 1         | 0.34%   |
| Mini pc        | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 276       | 92.62%  |
| Enabled  | 22        | 7.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 295       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 72        | 24%     |
| 3.01-4.0    | 66        | 22%     |
| 4.01-8.0    | 57        | 19%     |
| 8.01-16.0   | 52        | 17.33%  |
| 32.01-64.0  | 22        | 7.33%   |
| 1.01-2.0    | 14        | 4.67%   |
| 64.01-256.0 | 6         | 2%      |
| 2.01-3.0    | 5         | 1.67%   |
| 24.01-32.0  | 3         | 1%      |
| 0.51-1.0    | 3         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 102       | 29.82%  |
| 2.01-3.0   | 84        | 24.56%  |
| 4.01-8.0   | 60        | 17.54%  |
| 3.01-4.0   | 40        | 11.7%   |
| 0.51-1.0   | 31        | 9.06%   |
| 8.01-16.0  | 18        | 5.26%   |
| 0.01-0.5   | 4         | 1.17%   |
| 16.01-24.0 | 2         | 0.58%   |
| 24.01-32.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 189       | 61.97%  |
| 2       | 79        | 25.9%   |
| 3       | 23        | 7.54%   |
| 4       | 8         | 2.62%   |
| 5       | 5         | 1.64%   |
| Unknown | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 187       | 62.13%  |
| Yes       | 114       | 37.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 266       | 89.86%  |
| No        | 30        | 10.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 72.05%  |
| No        | 83        | 27.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 54.82%  |
| No        | 136       | 45.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Lithuania | 295       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Vilnius      | 155       | 50.16%  |
| Kaunas       | 50        | 16.18%  |
| Šiauliai    | 20        | 6.47%   |
| Klaipėda    | 17        | 5.5%    |
| Mažeikiai   | 6         | 1.94%   |
| Alytus       | 6         | 1.94%   |
| Panevezys    | 5         | 1.62%   |
| Gargždai    | 4         | 1.29%   |
| Telšiai     | 3         | 0.97%   |
| Šilalė     | 3         | 0.97%   |
| Kėdainiai   | 3         | 0.97%   |
| Jonava       | 3         | 0.97%   |
| Visaginas    | 2         | 0.65%   |
| Ukmerge      | 2         | 0.65%   |
| Trakai       | 2         | 0.65%   |
| Tauragė     | 2         | 0.65%   |
| Palanga      | 2         | 0.65%   |
| Marijampolė | 2         | 0.65%   |
| Elektrėnai  | 2         | 0.65%   |
| Anykščiai  | 2         | 0.65%   |
| Želva       | 1         | 0.32%   |
| Vėžaičiai | 1         | 0.32%   |
| Vainutas     | 1         | 0.32%   |
| Utena        | 1         | 0.32%   |
| Serdokai     | 1         | 0.32%   |
| Šeduva      | 1         | 0.32%   |
| Rokiškis    | 1         | 0.32%   |
| Raseiniai    | 1         | 0.32%   |
| Plungė      | 1         | 0.32%   |
| Pasvalys     | 1         | 0.32%   |
| Nemenčinė  | 1         | 0.32%   |
| Molėtai     | 1         | 0.32%   |
| Mauruciai    | 1         | 0.32%   |
| Maneikiai    | 1         | 0.32%   |
| Lentvaris    | 1         | 0.32%   |
| Karkliniai   | 1         | 0.32%   |
| Druskininkai | 1         | 0.32%   |
| Drasuciai    | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 77        | 124    | 17.91%  |
| WDC                         | 57        | 79     | 13.26%  |
| Seagate                     | 52        | 71     | 12.09%  |
| Toshiba                     | 34        | 45     | 7.91%   |
| Kingston                    | 33        | 47     | 7.67%   |
| A-DATA Technology           | 26        | 29     | 6.05%   |
| SanDisk                     | 17        | 19     | 3.95%   |
| Crucial                     | 16        | 19     | 3.72%   |
| Intel                       | 15        | 17     | 3.49%   |
| Hitachi                     | 14        | 21     | 3.26%   |
| Patriot                     | 12        | 13     | 2.79%   |
| Unknown                     | 9         | 22     | 2.09%   |
| SK hynix                    | 8         | 8      | 1.86%   |
| HGST                        | 6         | 7      | 1.4%    |
| China                       | 5         | 7      | 1.16%   |
| Micron Technology           | 3         | 3      | 0.7%    |
| GOODRAM                     | 3         | 3      | 0.7%    |
| Apacer                      | 3         | 5      | 0.7%    |
| Transcend                   | 2         | 2      | 0.47%   |
| OCZ                         | 2         | 3      | 0.47%   |
| KingSpec                    | 2         | 2      | 0.47%   |
| JMicron Technology          | 2         | 2      | 0.47%   |
| Hewlett-Packard             | 2         | 5      | 0.47%   |
| FORESEE                     | 2         | 2      | 0.47%   |
| ASMT                        | 2         | 2      | 0.47%   |
| XrayDisk                    | 1         | 1      | 0.23%   |
| XPG                         | 1         | 1      | 0.23%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.23%   |
| Union Memory                | 1         | 1      | 0.23%   |
| Team                        | 1         | 1      | 0.23%   |
| StoreJet                    | 1         | 1      | 0.23%   |
| PNY                         | 1         | 1      | 0.23%   |
| Plextor                     | 1         | 1      | 0.23%   |
| Phison Electronics          | 1         | 2      | 0.23%   |
| Phison                      | 1         | 1      | 0.23%   |
| Netac                       | 1         | 1      | 0.23%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 0.23%   |
| LITEONIT                    | 1         | 1      | 0.23%   |
| LITEON                      | 1         | 2      | 0.23%   |
| Lite-On Technology          | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SV300S37A120G 120GB SSD       | 7         | 1.52%   |
| Seagate ST500DM002-1BD142 500GB        | 6         | 1.3%    |
| Samsung SSD 850 EVO 250GB              | 6         | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 1.08%   |
| SanDisk NVMe SSD Drive 256GB           | 5         | 1.08%   |
| Samsung SSD 860 EVO 250GB              | 5         | 1.08%   |
| Kingston SA400S37120G 120GB SSD        | 5         | 1.08%   |
| Intel NVMe SSD Drive 512GB             | 5         | 1.08%   |
| WDC WD20EFRX-68EUZN0 2TB               | 4         | 0.87%   |
| Seagate ST9500325AS 500GB              | 4         | 0.87%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 0.87%   |
| Kingston SA400S37240G 240GB SSD        | 4         | 0.87%   |
| A-DATA SU650 120GB SSD                 | 4         | 0.87%   |
| Unknown MMC Card  128GB                | 3         | 0.65%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.65%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.65%   |
| Toshiba DT01ACA100 1TB                 | 3         | 0.65%   |
| Toshiba BG3 NVMe SSD Controller 256GB  | 3         | 0.65%   |
| Seagate ST500LT012-1DG142 500GB        | 3         | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.65%   |
| Samsung SSD 860 EVO 500GB              | 3         | 0.65%   |
| Samsung SSD 850 EVO 500GB              | 3         | 0.65%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.65%   |
| Samsung NVMe SSD Drive 500GB           | 3         | 0.65%   |
| Samsung NVMe SSD Drive 1TB             | 3         | 0.65%   |
| Samsung HD501LJ 500GB                  | 3         | 0.65%   |
| Patriot Burst 480GB SSD                | 3         | 0.65%   |
| Patriot Burst 120GB SSD                | 3         | 0.65%   |
| GOODRAM SSD 120GB                      | 3         | 0.65%   |
| Crucial CT500MX500SSD1 500GB           | 3         | 0.65%   |
| A-DATA SX900 128GB SSD                 | 3         | 0.65%   |
| WDC WD800AAJS-60PSA0 80GB              | 2         | 0.43%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 2         | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB               | 2         | 0.43%   |
| Unknown MMC Card  64GB                 | 2         | 0.43%   |
| Toshiba NVMe SSD Drive 512GB           | 2         | 0.43%   |
| Toshiba NVMe SSD Drive 256GB           | 2         | 0.43%   |
| Toshiba MK3261GSYN 320GB               | 2         | 0.43%   |
| Toshiba HDWL110 1TB                    | 2         | 0.43%   |
| Toshiba HDWE140 4TB                    | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 71     | 33.12%  |
| WDC                 | 47        | 66     | 29.94%  |
| Toshiba             | 21        | 27     | 13.38%  |
| Hitachi             | 14        | 21     | 8.92%   |
| Samsung Electronics | 12        | 24     | 7.64%   |
| HGST                | 6         | 7      | 3.82%   |
| Unknown             | 1         | 1      | 0.64%   |
| Fujitsu             | 1         | 1      | 0.64%   |
| ExcelStor           | 1         | 1      | 0.64%   |
| ASMT                | 1         | 1      | 0.64%   |
| Apple               | 1         | 2      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 59     | 21.71%  |
| Kingston            | 30        | 43     | 17.14%  |
| A-DATA Technology   | 22        | 25     | 12.57%  |
| Crucial             | 14        | 16     | 8%      |
| Patriot             | 12        | 13     | 6.86%   |
| SanDisk             | 7         | 8      | 4%      |
| Intel               | 5         | 5      | 2.86%   |
| China               | 5         | 7      | 2.86%   |
| Toshiba             | 4         | 6      | 2.29%   |
| SK hynix            | 3         | 3      | 1.71%   |
| GOODRAM             | 3         | 3      | 1.71%   |
| Apacer              | 3         | 5      | 1.71%   |
| WDC                 | 2         | 5      | 1.14%   |
| Transcend           | 2         | 2      | 1.14%   |
| OCZ                 | 2         | 3      | 1.14%   |
| KingSpec            | 2         | 2      | 1.14%   |
| Hewlett-Packard     | 2         | 5      | 1.14%   |
| FORESEE             | 2         | 2      | 1.14%   |
| XrayDisk            | 1         | 1      | 0.57%   |
| Unknown             | 1         | 1      | 0.57%   |
| Team                | 1         | 1      | 0.57%   |
| StoreJet            | 1         | 1      | 0.57%   |
| PNY                 | 1         | 1      | 0.57%   |
| Plextor             | 1         | 1      | 0.57%   |
| Netac               | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| LITEON              | 1         | 2      | 0.57%   |
| Leven               | 1         | 3      | 0.57%   |
| JMicron Technology  | 1         | 1      | 0.57%   |
| Intenso             | 1         | 2      | 0.57%   |
| Gigabyte Technology | 1         | 1      | 0.57%   |
| Dahua               | 1         | 1      | 0.57%   |
| Corsair             | 1         | 1      | 0.57%   |
| Colorful            | 1         | 1      | 0.57%   |
| ASMT                | 1         | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 151       | 233    | 38.92%  |
| HDD     | 141       | 222    | 36.34%  |
| NVMe    | 86        | 111    | 22.16%  |
| MMC     | 8         | 22     | 2.06%   |
| Unknown | 2         | 2      | 0.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 229       | 439    | 67.75%  |
| NVMe | 86        | 111    | 25.44%  |
| SAS  | 15        | 18     | 4.44%   |
| MMC  | 8         | 22     | 2.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 199       | 338    | 68.38%  |
| 0.51-1.0   | 72        | 93     | 24.74%  |
| 1.01-2.0   | 11        | 13     | 3.78%   |
| 3.01-4.0   | 5         | 6      | 1.72%   |
| 2.01-3.0   | 2         | 3      | 0.69%   |
| 10.01-20.0 | 1         | 1      | 0.34%   |
| 4.01-10.0  | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 102       | 31.48%  |
| 251-500        | 80        | 24.69%  |
| 501-1000       | 40        | 12.35%  |
| 1001-2000      | 22        | 6.79%   |
| 51-100         | 21        | 6.48%   |
| 1-20           | 20        | 6.17%   |
| 21-50          | 15        | 4.63%   |
| Unknown        | 9         | 2.78%   |
| More than 3000 | 8         | 2.47%   |
| 2001-3000      | 7         | 2.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 132       | 39.29%  |
| 51-100         | 47        | 13.99%  |
| 101-250        | 45        | 13.39%  |
| 21-50          | 42        | 12.5%   |
| 251-500        | 30        | 8.93%   |
| 501-1000       | 13        | 3.87%   |
| 1001-2000      | 11        | 3.27%   |
| Unknown        | 9         | 2.68%   |
| More than 3000 | 6         | 1.79%   |
| 2001-3000      | 1         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-60PSA0 80GB                | 2         | 2      | 5.26%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 2         | 3      | 5.26%   |
| Toshiba MK3261GSYN 320GB                 | 2         | 2      | 5.26%   |
| WDC WD7500BPVX-60JC3T0 752GB             | 1         | 1      | 2.63%   |
| WDC WD6400BPVT-80HXZT1 640GB             | 1         | 1      | 2.63%   |
| WDC WD6400BPVT-22HXZT1 640GB             | 1         | 2      | 2.63%   |
| WDC WD5000AAKX-001CA0 500GB              | 1         | 1      | 2.63%   |
| WDC WD1003FBYX-01Y7B0 1TB                | 1         | 2      | 2.63%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 2.63%   |
| Toshiba MK1652GSX 160GB                  | 1         | 1      | 2.63%   |
| SK hynix HFS256G39TND-N210A 256GB SSD    | 1         | 1      | 2.63%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 1         | 1      | 2.63%   |
| Seagate ST9640320AS 640GB                | 1         | 2      | 2.63%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 2.63%   |
| Seagate ST500LX012-SSHD-8GB              | 1         | 1      | 2.63%   |
| Seagate ST3250410AS 250GB                | 1         | 1      | 2.63%   |
| Seagate ST3250318AS 250GB                | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 850 EVO 250GB    | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 840 Series 500GB | 1         | 2      | 2.63%   |
| Samsung Electronics HM641JI 640GB        | 1         | 1      | 2.63%   |
| Samsung Electronics HD501LJ 500GB        | 1         | 1      | 2.63%   |
| Samsung Electronics HD103SJ 1TB          | 1         | 1      | 2.63%   |
| Samsung Electronics HD080HJ/ 80GB        | 1         | 4      | 2.63%   |
| Leven JAJS300M240C 240GB                 | 1         | 3      | 2.63%   |
| Kingston SV300S37A120G 120GB SSD         | 1         | 1      | 2.63%   |
| Hitachi HTS547575A9E384 752GB            | 1         | 1      | 2.63%   |
| Hitachi HTS545050KTA300 500GB            | 1         | 1      | 2.63%   |
| Hitachi HTS545032B9A300 320GB            | 1         | 1      | 2.63%   |
| Hitachi HTS545025B9A300 250GB            | 1         | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 2.63%   |
| HGST HTS541010A9E680 1TB                 | 1         | 2      | 2.63%   |
| ExcelStor Technology J8160S 164GB        | 1         | 1      | 2.63%   |
| Crucial CT525MX300SSD1 528GB             | 1         | 1      | 2.63%   |
| Colorful SL300 120GB SSD                 | 1         | 1      | 2.63%   |
| A-DATA Technology SX900 128GB SSD        | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 24.32%  |
| Samsung Electronics | 6         | 10     | 16.22%  |
| Seagate             | 5         | 6      | 13.51%  |
| Hitachi             | 4         | 4      | 10.81%  |
| Toshiba             | 3         | 4      | 8.11%   |
| SK hynix            | 2         | 2      | 5.41%   |
| HGST                | 2         | 3      | 5.41%   |
| Leven               | 1         | 3      | 2.7%    |
| Kingston            | 1         | 1      | 2.7%    |
| ExcelStor           | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| Colorful            | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 32.14%  |
| Seagate             | 5         | 6      | 17.86%  |
| Samsung Electronics | 4         | 7      | 14.29%  |
| Hitachi             | 4         | 4      | 14.29%  |
| Toshiba             | 3         | 4      | 10.71%  |
| HGST                | 2         | 3      | 7.14%   |
| ExcelStor           | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 37     | 72.73%  |
| SSD  | 8         | 11     | 24.24%  |
| NVMe | 1         | 1      | 3.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate ST3160812A 160GB    | 1         | 2      | 50%     |
| Hitachi HTS541010A9E680 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 178       | 339    | 55.11%  |
| Works    | 111       | 199    | 34.37%  |
| Malfunc  | 32        | 49     | 9.91%   |
| Failed   | 2         | 3      | 0.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 205       | 56.79%  |
| AMD                              | 56        | 15.51%  |
| Samsung Electronics              | 31        | 8.59%   |
| SanDisk                          | 14        | 3.88%   |
| Toshiba America Info Systems     | 9         | 2.49%   |
| ASMedia Technology               | 6         | 1.66%   |
| SK hynix                         | 5         | 1.39%   |
| Nvidia                           | 4         | 1.11%   |
| JMicron Technology               | 4         | 1.11%   |
| ADATA Technology                 | 4         | 1.11%   |
| Micron Technology                | 3         | 0.83%   |
| Marvell Technology Group         | 3         | 0.83%   |
| Kingston Technology Company      | 3         | 0.83%   |
| Union Memory (Shenzhen)          | 2         | 0.55%   |
| Realtek Semiconductor            | 2         | 0.55%   |
| Phison Electronics               | 2         | 0.55%   |
| Micron/Crucial Technology        | 2         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| OCZ Technology Group             | 1         | 0.28%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.28%   |
| Lite-On Technology               | 1         | 0.28%   |
| KIOXIA                           | 1         | 0.28%   |
| Broadcom / LSI                   | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 8.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21        | 4.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 20        | 4.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 20        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 3.49%   |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 2.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 2.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 2.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8         | 1.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1.63%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 1.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.4%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 5         | 1.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 1.16%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 0.93%   |
| Intel SSD 660P Series                                                          | 4         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                         | 4         | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.7%    |
| Micron Non-Volatile memory controller                                          | 3         | 0.7%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.7%    |
| Intel Non-Volatile memory controller                                           | 3         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 208       | 57.62%  |
| NVMe | 86        | 23.82%  |
| IDE  | 45        | 12.47%  |
| RAID | 20        | 5.54%   |
| SAS  | 2         | 0.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 223       | 75.59%  |
| AMD    | 70        | 23.73%  |
| ARM    | 2         | 0.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 2.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 1.35%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 4         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 1.35%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.35%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 3         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 3         | 1.01%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 3         | 1.01%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 1.01%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 1.01%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.01%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3         | 1.01%   |
| AMD FX-8350 Eight-Core Processor            | 3         | 1.01%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.68%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2         | 0.68%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2         | 0.68%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 2         | 0.68%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 2         | 0.68%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.68%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 2         | 0.68%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.68%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 0.68%   |
| Intel Core i7 CPU M 640 @ 2.80GHz           | 2         | 0.68%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2         | 0.68%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 2         | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.68%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2         | 0.68%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.68%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 0.68%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 2         | 0.68%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 0.68%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.68%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2         | 0.68%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 0.68%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2         | 0.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 64        | 21.69%  |
| Intel Core i7           | 53        | 17.97%  |
| Intel Core i3           | 37        | 12.54%  |
| AMD Ryzen 5             | 25        | 8.47%   |
| AMD Ryzen 7             | 14        | 4.75%   |
| Other                   | 12        | 4.07%   |
| Intel Celeron           | 12        | 4.07%   |
| Intel Core 2 Duo        | 10        | 3.39%   |
| Intel Pentium Dual-Core | 8         | 2.71%   |
| Intel Pentium           | 6         | 2.03%   |
| Intel Core i9           | 5         | 1.69%   |
| Intel Xeon              | 4         | 1.36%   |
| AMD FX                  | 4         | 1.36%   |
| Intel Core 2            | 3         | 1.02%   |
| AMD Ryzen 9             | 3         | 1.02%   |
| AMD Athlon II X2        | 3         | 1.02%   |
| Intel Pentium D         | 2         | 0.68%   |
| Intel Pentium 4         | 2         | 0.68%   |
| Intel Genuine           | 2         | 0.68%   |
| Intel Atom              | 2         | 0.68%   |
| AMD Ryzen 7 PRO         | 2         | 0.68%   |
| AMD Ryzen 3             | 2         | 0.68%   |
| AMD Phenom II X4        | 2         | 0.68%   |
| AMD Phenom II           | 2         | 0.68%   |
| AMD Athlon 64 X2        | 2         | 0.68%   |
| AMD A8                  | 2         | 0.68%   |
| Intel Pentium Silver    | 1         | 0.34%   |
| Intel Core m7           | 1         | 0.34%   |
| Intel Core 2 Quad       | 1         | 0.34%   |
| AMD Sempron             | 1         | 0.34%   |
| AMD PRO A8              | 1         | 0.34%   |
| AMD E                   | 1         | 0.34%   |
| AMD C-60                | 1         | 0.34%   |
| AMD C-50                | 1         | 0.34%   |
| AMD Athlon II X4        | 1         | 0.34%   |
| AMD A6                  | 1         | 0.34%   |
| AMD A4                  | 1         | 0.34%   |
| AMD A10                 | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 125       | 42.09%  |
| 4       | 103       | 34.68%  |
| 6       | 35        | 11.78%  |
| 8       | 23        | 7.74%   |
| 1       | 5         | 1.68%   |
| 12      | 3         | 1.01%   |
| Unknown | 2         | 0.67%   |
| 16      | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 293       | 98.65%  |
| 2       | 3         | 1.01%   |
| Unknown | 1         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 202       | 68.01%  |
| 1       | 93        | 31.31%  |
| Unknown | 2         | 0.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 290       | 98.31%  |
| 32-bit         | 2         | 0.68%   |
| Unknown        | 2         | 0.68%   |
| 64-bit         | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 22.62%  |
| 0x306a9    | 23        | 7.54%   |
| 0x206a7    | 21        | 6.89%   |
| 0x306c3    | 20        | 6.56%   |
| 0x1067a    | 12        | 3.93%   |
| 0x806ea    | 10        | 3.28%   |
| 0x406e3    | 8         | 2.62%   |
| 0x906e9    | 6         | 1.97%   |
| 0x806c1    | 6         | 1.97%   |
| 0x40651    | 6         | 1.97%   |
| 0x20655    | 6         | 1.97%   |
| 0x010000c8 | 6         | 1.97%   |
| 0x906ea    | 5         | 1.64%   |
| 0x806ec    | 5         | 1.64%   |
| 0x506e3    | 5         | 1.64%   |
| 0x08701021 | 5         | 1.64%   |
| 0x306d4    | 4         | 1.31%   |
| 0x30678    | 4         | 1.31%   |
| 0xa0653    | 3         | 0.98%   |
| 0x906ed    | 3         | 0.98%   |
| 0x806eb    | 3         | 0.98%   |
| 0x20652    | 3         | 0.98%   |
| 0x0a50000c | 3         | 0.98%   |
| 0x08108109 | 3         | 0.98%   |
| 0x0800820d | 3         | 0.98%   |
| 0x08001137 | 3         | 0.98%   |
| 0xa0652    | 2         | 0.66%   |
| 0x706a1    | 2         | 0.66%   |
| 0x6fd      | 2         | 0.66%   |
| 0x106e5    | 2         | 0.66%   |
| 0x10676    | 2         | 0.66%   |
| 0x0a50000b | 2         | 0.66%   |
| 0x0a201009 | 2         | 0.66%   |
| 0x08608103 | 2         | 0.66%   |
| 0x08108102 | 2         | 0.66%   |
| 0x0700010f | 2         | 0.66%   |
| 0x05000119 | 2         | 0.66%   |
| 0xf65      | 1         | 0.33%   |
| 0xf47      | 1         | 0.33%   |
| 0xf43      | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 45        | 15.25%  |
| Haswell         | 30        | 10.17%  |
| IvyBridge       | 28        | 9.49%   |
| SandyBridge     | 24        | 8.14%   |
| Penryn          | 17        | 5.76%   |
| Skylake         | 16        | 5.42%   |
| Zen 2           | 13        | 4.41%   |
| Zen 3           | 12        | 4.07%   |
| Zen+            | 11        | 3.73%   |
| Westmere        | 11        | 3.73%   |
| CometLake       | 9         | 3.05%   |
| K10             | 8         | 2.71%   |
| Core            | 8         | 2.71%   |
| Unknown         | 8         | 2.71%   |
| Zen             | 7         | 2.37%   |
| TigerLake       | 7         | 2.37%   |
| Piledriver      | 6         | 2.03%   |
| Broadwell       | 5         | 1.69%   |
| Silvermont      | 4         | 1.36%   |
| NetBurst        | 4         | 1.36%   |
| Goldmont plus   | 4         | 1.36%   |
| Nehalem         | 3         | 1.02%   |
| Bobcat          | 3         | 1.02%   |
| K8 Hammer       | 2         | 0.68%   |
| Jaguar          | 2         | 0.68%   |
| IceLake         | 2         | 0.68%   |
| Goldmont        | 2         | 0.68%   |
| Steamroller     | 1         | 0.34%   |
| K8 & K10 hybrid | 1         | 0.34%   |
| Excavator       | 1         | 0.34%   |
| Bonnell         | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 170       | 48.16%  |
| Nvidia                           | 102       | 28.9%   |
| AMD                              | 79        | 22.38%  |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| Matrox Electronics Systems       | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 20        | 5.42%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 16        | 4.34%   |
| Intel UHD Graphics 620                                                        | 11        | 2.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 2.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 9         | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 1.9%    |
| Intel Core Processor Integrated Graphics Controller                           | 7         | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 6         | 1.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 6         | 1.63%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 5         | 1.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 5         | 1.36%   |
| AMD Renoir                                                                    | 5         | 1.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 1.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 5         | 1.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 1.36%   |
| Nvidia GP108M [GeForce MX150]                                                 | 4         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 4         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 1.08%   |
| Intel HD Graphics 630                                                         | 4         | 1.08%   |
| Intel HD Graphics 5500                                                        | 4         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 4         | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 4         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 0.81%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 3         | 0.81%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 3         | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 0.81%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 3         | 0.81%   |
| Intel HD Graphics 530                                                         | 3         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 3         | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 0.81%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 3         | 0.81%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                              | 3         | 0.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 114       | 38.26%  |
| 1 x AMD        | 59        | 19.8%   |
| 1 x Nvidia     | 56        | 18.79%  |
| Intel + Nvidia | 43        | 14.43%  |
| Intel + AMD    | 10        | 3.36%   |
| 2 x AMD        | 8         | 2.68%   |
| Other          | 2         | 0.67%   |
| 2 x Nvidia     | 2         | 0.67%   |
| AMD + Nvidia   | 2         | 0.67%   |
| 1 x SiS        | 1         | 0.34%   |
| 1 x Matrox     | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 236       | 78.15%  |
| Proprietary | 56        | 18.54%  |
| Unknown     | 10        | 3.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 45.6%   |
| 1.01-2.0   | 57        | 18.57%  |
| 0.01-0.5   | 36        | 11.73%  |
| 0.51-1.0   | 25        | 8.14%   |
| 3.01-4.0   | 24        | 7.82%   |
| 5.01-6.0   | 14        | 4.56%   |
| 7.01-8.0   | 6         | 1.95%   |
| 8.01-16.0  | 3         | 0.98%   |
| 2.01-3.0   | 1         | 0.33%   |
| 16.01-24.0 | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 48        | 14.37%  |
| AU Optronics            | 44        | 13.17%  |
| LG Display              | 41        | 12.28%  |
| Dell                    | 28        | 8.38%   |
| Chimei Innolux          | 21        | 6.29%   |
| BOE                     | 20        | 5.99%   |
| Lenovo                  | 17        | 5.09%   |
| Goldstar                | 17        | 5.09%   |
| Philips                 | 16        | 4.79%   |
| AOC                     | 16        | 4.79%   |
| Chi Mei Optoelectronics | 9         | 2.69%   |
| BenQ                    | 8         | 2.4%    |
| Hewlett-Packard         | 7         | 2.1%    |
| Ancor Communications    | 6         | 1.8%    |
| Sony                    | 4         | 1.2%    |
| PANDA                   | 4         | 1.2%    |
| Sharp                   | 2         | 0.6%    |
| LG Electronics          | 2         | 0.6%    |
| CSO                     | 2         | 0.6%    |
| ASUSTek Computer        | 2         | 0.6%    |
| ViewSonic               | 1         | 0.3%    |
| Unknown (XXX)           | 1         | 0.3%    |
| Unknown (AAA)           | 1         | 0.3%    |
| Toshiba                 | 1         | 0.3%    |
| NEC Computers           | 1         | 0.3%    |
| MStar                   | 1         | 0.3%    |
| Mi                      | 1         | 0.3%    |
| Medion                  | 1         | 0.3%    |
| LGD                     | 1         | 0.3%    |
| LG Philips              | 1         | 0.3%    |
| KDC                     | 1         | 0.3%    |
| JDI                     | 1         | 0.3%    |
| InfoVision              | 1         | 0.3%    |
| Iiyama                  | 1         | 0.3%    |
| IBM                     | 1         | 0.3%    |
| HannStar                | 1         | 0.3%    |
| Grundig                 | 1         | 0.3%    |
| DENON                   | 1         | 0.3%    |
| Apple                   | 1         | 0.3%    |
| AGO                     | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 1.15%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.15%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 3         | 0.86%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                     | 3         | 0.86%   |
| Dell P2719H DEL4184 1920x1080 600x340mm 27.2-inch                        | 3         | 0.86%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                        | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.86%   |
| Sony LCD Monitor MS_9005 1920x1200 331x207mm 15.4-inch                   | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.57%   |
| Samsung Electronics LCD Monitor C32HG7x 2560x1440                        | 2         | 0.57%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.57%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch                 | 2         | 0.57%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.57%   |
| Lenovo LBG AIO PC LEN8000 1920x1080 521x293mm 23.5-inch                  | 2         | 0.57%   |
| Dell U2419H DEL4148 1920x1080 527x296mm 23.8-inch                        | 2         | 0.57%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                         | 2         | 0.57%   |
| Dell P2314H DEL4099 1920x1080 509x286mm 23.0-inch                        | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 2         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.57%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch           | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.57%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 2         | 0.57%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.57%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                           | 2         | 0.57%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                    | 1         | 0.29%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch           | 1         | 0.29%   |
| Unknown (AAA) HDTV AAA0001 1360x768 575x323mm 26.0-inch                  | 1         | 0.29%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch                 | 1         | 0.29%   |
| Sony TV SNY2C02 1920x1080 708x398mm 32.0-inch                            | 1         | 0.29%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 531x299mm 24.0-inch    | 1         | 0.29%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.29%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch        | 1         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 147       | 46.52%  |
| 1366x768 (WXGA)    | 54        | 17.09%  |
| 2560x1440 (QHD)    | 22        | 6.96%   |
| 3840x2160 (4K)     | 18        | 5.7%    |
| 1600x900 (HD+)     | 17        | 5.38%   |
| 1280x1024 (SXGA)   | 16        | 5.06%   |
| 1920x1200 (WUXGA)  | 6         | 1.9%    |
| 1280x800 (WXGA)    | 6         | 1.9%    |
| 3440x1440          | 4         | 1.27%   |
| 1440x900 (WXGA+)   | 4         | 1.27%   |
| 2560x1080          | 3         | 0.95%   |
| Unknown            | 3         | 0.95%   |
| 3840x2400          | 2         | 0.63%   |
| 3840x1080          | 2         | 0.63%   |
| 1680x1050 (WSXGA+) | 2         | 0.63%   |
| 3840x1600          | 1         | 0.32%   |
| 3200x1080          | 1         | 0.32%   |
| 3000x2000          | 1         | 0.32%   |
| 2880x1800          | 1         | 0.32%   |
| 2560x1600          | 1         | 0.32%   |
| 2160x1440          | 1         | 0.32%   |
| 1360x768           | 1         | 0.32%   |
| 1280x720 (HD)      | 1         | 0.32%   |
| 1024x768 (XGA)     | 1         | 0.32%   |
| 1024x600           | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 104       | 31.23%  |
| 27      | 29        | 8.71%   |
| 24      | 28        | 8.41%   |
| 23      | 28        | 8.41%   |
| 13      | 24        | 7.21%   |
| 14      | 22        | 6.61%   |
| 17      | 19        | 5.71%   |
| 21      | 15        | 4.5%    |
| Unknown | 13        | 3.9%    |
| 19      | 9         | 2.7%    |
| 18      | 7         | 2.1%    |
| 34      | 5         | 1.5%    |
| 12      | 5         | 1.5%    |
| 40      | 3         | 0.9%    |
| 31      | 3         | 0.9%    |
| 20      | 3         | 0.9%    |
| 84      | 2         | 0.6%    |
| 54      | 2         | 0.6%    |
| 25      | 2         | 0.6%    |
| 10      | 2         | 0.6%    |
| 72      | 1         | 0.3%    |
| 55      | 1         | 0.3%    |
| 52      | 1         | 0.3%    |
| 50      | 1         | 0.3%    |
| 29      | 1         | 0.3%    |
| 22      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 11      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 146       | 44.65%  |
| 501-600     | 78        | 23.85%  |
| 401-500     | 26        | 7.95%   |
| 351-400     | 23        | 7.03%   |
| 201-300     | 17        | 5.2%    |
| Unknown     | 13        | 3.98%   |
| 601-700     | 8         | 2.45%   |
| 701-800     | 5         | 1.53%   |
| 1001-1500   | 5         | 1.53%   |
| 801-900     | 3         | 0.92%   |
| 1501-2000   | 3         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 230       | 79.04%  |
| 16/10   | 24        | 8.25%   |
| 5/4     | 15        | 5.15%   |
| Unknown | 12        | 4.12%   |
| 21/9    | 5         | 1.72%   |
| 3/2     | 3         | 1.03%   |
| 4/3     | 2         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 30.54%  |
| 201-250        | 61        | 18.26%  |
| 81-90          | 39        | 11.68%  |
| 301-350        | 29        | 8.68%   |
| 151-200        | 19        | 5.69%   |
| 141-150        | 13        | 3.89%   |
| Unknown        | 13        | 3.89%   |
| 121-130        | 11        | 3.29%   |
| 351-500        | 9         | 2.69%   |
| More than 1000 | 8         | 2.4%    |
| 251-300        | 8         | 2.4%    |
| 71-80          | 7         | 2.1%    |
| 61-70          | 4         | 1.2%    |
| 501-1000       | 3         | 0.9%    |
| 41-50          | 2         | 0.6%    |
| 111-120        | 2         | 0.6%    |
| 91-100         | 2         | 0.6%    |
| 51-60          | 1         | 0.3%    |
| 131-140        | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 113       | 35.2%   |
| 121-160       | 95        | 29.6%   |
| 101-120       | 76        | 23.68%  |
| 161-240       | 14        | 4.36%   |
| Unknown       | 13        | 4.05%   |
| More than 240 | 6         | 1.87%   |
| 1-50          | 4         | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 227       | 76.43%  |
| 2     | 57        | 19.19%  |
| 0     | 10        | 3.37%   |
| 3     | 3         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 155       | 35.8%   |
| Intel                             | 130       | 30.02%  |
| Qualcomm Atheros                  | 62        | 14.32%  |
| Broadcom                          | 28        | 6.47%   |
| Broadcom Limited                  | 7         | 1.62%   |
| TP-Link                           | 5         | 1.15%   |
| Ralink                            | 4         | 0.92%   |
| MediaTek                          | 4         | 0.92%   |
| Marvell Technology Group          | 4         | 0.92%   |
| Lenovo                            | 4         | 0.92%   |
| Nvidia                            | 3         | 0.69%   |
| D-Link                            | 3         | 0.69%   |
| Ralink Technology                 | 2         | 0.46%   |
| Qualcomm Atheros Communications   | 2         | 0.46%   |
| Microsoft                         | 2         | 0.46%   |
| JMicron Technology                | 2         | 0.46%   |
| Fibocom                           | 2         | 0.46%   |
| Ericsson Business Mobile Networks | 2         | 0.46%   |
| Dell                              | 2         | 0.46%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.23%   |
| Sierra Wireless                   | 1         | 0.23%   |
| Samsung Electronics               | 1         | 0.23%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |
| Edimax Technology                 | 1         | 0.23%   |
| D-Link System                     | 1         | 0.23%   |
| ASUSTek Computer                  | 1         | 0.23%   |
| ASIX Electronics                  | 1         | 0.23%   |
| 3Com                              | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 114       | 22.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 3.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 2.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 2.14%   |
| Intel Wireless 8265 / 8275                                              | 10        | 1.94%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 1.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 1.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 7         | 1.36%   |
| Intel Wireless 8260                                                     | 7         | 1.36%   |
| Intel Wireless 7260                                                     | 7         | 1.36%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.17%   |
| Intel I211 Gigabit Network Connection                                   | 6         | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 0.97%   |
| Intel Wireless 7265                                                     | 5         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                       | 4         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.78%   |
| Intel 82579V Gigabit Network Connection                                 | 4         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.58%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.58%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.58%   |
| Intel Wireless 3165                                                     | 3         | 0.58%   |
| Intel Ethernet Controller I225-V                                        | 3         | 0.58%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 0.58%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.58%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 45.58%  |
| Qualcomm Atheros                | 48        | 21.24%  |
| Realtek Semiconductor           | 24        | 10.62%  |
| Broadcom                        | 19        | 8.41%   |
| TP-Link                         | 5         | 2.21%   |
| Ralink                          | 4         | 1.77%   |
| MediaTek                        | 4         | 1.77%   |
| D-Link                          | 3         | 1.33%   |
| Ralink Technology               | 2         | 0.88%   |
| Qualcomm Atheros Communications | 2         | 0.88%   |
| Microsoft                       | 2         | 0.88%   |
| Fibocom                         | 2         | 0.88%   |
| Dell                            | 2         | 0.88%   |
| Broadcom Limited                | 2         | 0.88%   |
| Sierra Wireless                 | 1         | 0.44%   |
| Edimax Technology               | 1         | 0.44%   |
| D-Link System                   | 1         | 0.44%   |
| ASUSTek Computer                | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 6.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 4.87%   |
| Intel Wireless 8265 / 8275                                              | 10        | 4.42%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 4.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 3.54%   |
| Intel Wireless 8260                                                     | 7         | 3.1%    |
| Intel Wireless 7260                                                     | 7         | 3.1%    |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.21%   |
| Intel Wireless 7265                                                     | 5         | 2.21%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 2.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.33%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.33%   |
| Intel Wireless 3165                                                     | 3         | 1.33%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.88%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.88%   |
| Microsoft XBOX ACC                                                      | 2         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 147       | 52.88%  |
| Intel                         | 68        | 24.46%  |
| Qualcomm Atheros              | 25        | 8.99%   |
| Broadcom                      | 15        | 5.4%    |
| Broadcom Limited              | 5         | 1.8%    |
| Marvell Technology Group      | 4         | 1.44%   |
| Lenovo                        | 4         | 1.44%   |
| Nvidia                        | 3         | 1.08%   |
| JMicron Technology            | 2         | 0.72%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.36%   |
| Samsung Electronics           | 1         | 0.36%   |
| OnePlus Technology (Shenzhen) | 1         | 0.36%   |
| ASIX Electronics              | 1         | 0.36%   |
| 3Com                          | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 114       | 39.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 6.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 5.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 2.45%   |
| Intel I211 Gigabit Network Connection                             | 6         | 2.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.4%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.4%    |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 1.05%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.05%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.05%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.7%    |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.7%    |
| Intel 82578DC Gigabit Network Connection                          | 2         | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.7%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.7%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.7%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.7%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 2         | 0.7%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.7%    |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.35%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 266       | 55.19%  |
| WiFi     | 213       | 44.19%  |
| Modem    | 3         | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 53.63%  |
| Ethernet | 147       | 46.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 167       | 56.04%  |
| 1     | 120       | 40.27%  |
| 3     | 5         | 1.68%   |
| 0     | 5         | 1.68%   |
| 5     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 295       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 44.05%  |
| Qualcomm Atheros Communications | 22        | 13.1%   |
| Cambridge Silicon Radio         | 15        | 8.93%   |
| Broadcom                        | 14        | 8.33%   |
| IMC Networks                    | 12        | 7.14%   |
| Realtek Semiconductor           | 9         | 5.36%   |
| Foxconn / Hon Hai               | 5         | 2.98%   |
| Ralink                          | 3         | 1.79%   |
| Dell                            | 3         | 1.79%   |
| ASUSTek Computer                | 3         | 1.79%   |
| Toshiba                         | 2         | 1.19%   |
| Hewlett-Packard                 | 2         | 1.19%   |
| Apple                           | 2         | 1.19%   |
| Lite-On Technology              | 1         | 0.6%    |
| Edimax Technology               | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 17.86%  |
| Intel AX201 Bluetooth                                                               | 16        | 9.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 15        | 8.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 5.95%   |
| Intel AX200 Bluetooth                                                               | 9         | 5.36%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.76%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 4.76%   |
| Realtek Bluetooth Radio                                                             | 6         | 3.57%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.38%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.19%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.19%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 1.19%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.19%   |
| Broadcom BCM2046 Bluetooth Device                                                   | 2         | 1.19%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.19%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.19%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.6%    |
| Toshiba Bluetooth Device                                                            | 1         | 0.6%    |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.6%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.6%    |
| Intel AX210 Bluetooth                                                               | 1         | 0.6%    |
| IMC Networks Bluetooth Device                                                       | 1         | 0.6%    |
| IMC Networks BCM20702A0                                                             | 1         | 0.6%    |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 1         | 0.6%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.6%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.6%    |
| Foxconn / Hon Hai BT                                                                | 1         | 0.6%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.6%    |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 218       | 51.54%  |
| AMD                                             | 86        | 20.33%  |
| Nvidia                                          | 73        | 17.26%  |
| C-Media Electronics                             | 8         | 1.89%   |
| JMTek                                           | 6         | 1.42%   |
| Logitech                                        | 4         | 0.95%   |
| Lenovo                                          | 4         | 0.95%   |
| Yamaha                                          | 2         | 0.47%   |
| SteelSeries ApS                                 | 2         | 0.47%   |
| Realtek Semiconductor                           | 2         | 0.47%   |
| Creative Technology                             | 2         | 0.47%   |
| Sony                                            | 1         | 0.24%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.24%   |
| Sennheiser Communications                       | 1         | 0.24%   |
| Razer USA                                       | 1         | 0.24%   |
| PreSonus Audio Electronics                      | 1         | 0.24%   |
| Panasonic (Matsushita)                          | 1         | 0.24%   |
| Microsoft                                       | 1         | 0.24%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.24%   |
| Kingston Technology                             | 1         | 0.24%   |
| Hewlett-Packard                                 | 1         | 0.24%   |
| GN Netcom                                       | 1         | 0.24%   |
| Generalplus Technology                          | 1         | 0.24%   |
| Focusrite-Novation                              | 1         | 0.24%   |
| Creative Labs                                   | 1         | 0.24%   |
| ASUSTek Computer                                | 1         | 0.24%   |
| Allen&Heath                                     | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 4.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23        | 4.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 4.6%    |
| Intel Sunrise Point-LP HD Audio                                            | 22        | 4.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 3.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 3%      |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 2.6%    |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 2.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 2.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 2.4%    |
| Nvidia GF108 High Definition Audio Controller                              | 10        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 2%      |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.4%    |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 1.2%    |
| JMTek USB PnP Audio Device                                                 | 5         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1%      |
| Intel Broadwell-U Audio Controller                                         | 5         | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1%      |
| Intel 200 Series PCH HD Audio                                              | 5         | 1%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.8%    |
| AMD Navi 10 HDMI Audio                                                     | 4         | 0.8%    |
| AMD FCH Azalia Controller                                                  | 4         | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4         | 0.8%    |
| Nvidia GM204 High Definition Audio Controller                              | 3         | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 22.44%  |
| Kingston            | 37        | 18.05%  |
| SK hynix            | 28        | 13.66%  |
| Unknown             | 16        | 7.8%    |
| Crucial             | 14        | 6.83%   |
| Micron Technology   | 12        | 5.85%   |
| G.Skill             | 11        | 5.37%   |
| Ramaxel Technology  | 8         | 3.9%    |
| Patriot             | 7         | 3.41%   |
| Nanya Technology    | 5         | 2.44%   |
| Elpida              | 5         | 2.44%   |
| A-DATA Technology   | 5         | 2.44%   |
| Corsair             | 3         | 1.46%   |
| Transcend           | 2         | 0.98%   |
| Team                | 2         | 0.98%   |
| Unknown (ABCD)      | 1         | 0.49%   |
| Lexar               | 1         | 0.49%   |
| Atermiter           | 1         | 0.49%   |
| Unknown             | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 1.34%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 3         | 1.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 1.34%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 2         | 0.89%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s         | 2         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.89%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s     | 2         | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 0.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.89%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.89%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.89%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s     | 2         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 0.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.89%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.89%   |
| Patriot RAM PSD48G266681 8192MB DIMM DDR4 2934MT/s           | 2         | 0.89%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2         | 0.89%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s        | 2         | 0.89%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 2         | 0.89%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s        | 2         | 0.89%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 2         | 0.89%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4096MB SODIMM DDR3 1600MT/s     | 2         | 0.89%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 1         | 0.45%   |
| Unknown RAM Module 512MB DIMM 800MT/s                        | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1         | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM 400MT/s                          | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s               | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 1         | 0.45%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 1         | 0.45%   |
| Unknown RAM Module 1024MB DIMM DDR2 400MT/s                  | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 42.61%  |
| DDR3    | 71        | 40.34%  |
| LPDDR3  | 6         | 3.41%   |
| DDR2    | 6         | 3.41%   |
| Unknown | 6         | 3.41%   |
| SDRAM   | 5         | 2.84%   |
| LPDDR4  | 4         | 2.27%   |
| DRAM    | 1         | 0.57%   |
| DDR5    | 1         | 0.57%   |
| DDR     | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 101       | 57.71%  |
| DIMM         | 67        | 38.29%  |
| Row Of Chips | 7         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 69        | 37.3%   |
| 4096  | 62        | 33.51%  |
| 16384 | 25        | 13.51%  |
| 2048  | 19        | 10.27%  |
| 1024  | 6         | 3.24%   |
| 32768 | 2         | 1.08%   |
| 512   | 2         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 25.64%  |
| 2667    | 30        | 15.38%  |
| 3200    | 28        | 14.36%  |
| 1333    | 16        | 8.21%   |
| 2133    | 10        | 5.13%   |
| 1334    | 8         | 4.1%    |
| 2400    | 6         | 3.08%   |
| 1867    | 5         | 2.56%   |
| 667     | 5         | 2.56%   |
| 3600    | 4         | 2.05%   |
| 800     | 4         | 2.05%   |
| Unknown | 4         | 2.05%   |
| 2800    | 3         | 1.54%   |
| 2666    | 3         | 1.54%   |
| 1067    | 3         | 1.54%   |
| 3866    | 2         | 1.03%   |
| 3266    | 2         | 1.03%   |
| 2934    | 2         | 1.03%   |
| 400     | 2         | 1.03%   |
| 4800    | 1         | 0.51%   |
| 4267    | 1         | 0.51%   |
| 3800    | 1         | 0.51%   |
| 3733    | 1         | 0.51%   |
| 3466    | 1         | 0.51%   |
| 3400    | 1         | 0.51%   |
| 3000    | 1         | 0.51%   |
| 1066    | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 60%     |
| Hewlett-Packard     | 2         | 40%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 20%     |
| Samsung ML-1670 Series  | 1         | 20%     |
| Samsung M2070 Series    | 1         | 20%     |
| HP PSC-1315/PSC-1317    | 1         | 20%     |
| HP LaserJet 1020        | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 35        | 18.72%  |
| IMC Networks                           | 31        | 16.58%  |
| Microdia                               | 16        | 8.56%   |
| Sunplus Innovation Technology          | 14        | 7.49%   |
| Acer                                   | 14        | 7.49%   |
| Realtek Semiconductor                  | 11        | 5.88%   |
| Suyin                                  | 9         | 4.81%   |
| Logitech                               | 8         | 4.28%   |
| Syntek                                 | 5         | 2.67%   |
| Alcor Micro                            | 5         | 2.67%   |
| Lite-On Technology                     | 4         | 2.14%   |
| Silicon Motion                         | 3         | 1.6%    |
| Quanta                                 | 3         | 1.6%    |
| Luxvisions Innotech Limited            | 3         | 1.6%    |
| Sonix Technology                       | 2         | 1.07%   |
| Samsung Electronics                    | 2         | 1.07%   |
| OmniVision Technologies                | 2         | 1.07%   |
| DJJHFA1BIF5595                         | 2         | 1.07%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.07%   |
| Apple                                  | 2         | 1.07%   |
| Z-Star Microelectronics                | 1         | 0.53%   |
| Ricoh                                  | 1         | 0.53%   |
| Razer USA                              | 1         | 0.53%   |
| Primax Electronics                     | 1         | 0.53%   |
| Pixart Imaging                         | 1         | 0.53%   |
| Panasonic (Matsushita)                 | 1         | 0.53%   |
| Lenovo                                 | 1         | 0.53%   |
| Intel                                  | 1         | 0.53%   |
| Importek                               | 1         | 0.53%   |
| Huawei Technologies                    | 1         | 0.53%   |
| DigiTech                               | 1         | 0.53%   |
| Cubeternet                             | 1         | 0.53%   |
| Arkmicro Technologies                  | 1         | 0.53%   |
| ALi                                    | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 10        | 5.35%   |
| IMC Networks USB2.0 HD UVC WebCam                | 9         | 4.81%   |
| IMC Networks Integrated Camera                   | 9         | 4.81%   |
| Microdia Integrated_Webcam_HD                    | 7         | 3.74%   |
| Sunplus Integrated_Webcam_HD                     | 4         | 2.14%   |
| Acer Integrated Camera                           | 4         | 2.14%   |
| Syntek Lenovo EasyCamera                         | 3         | 1.6%    |
| Sunplus HP HD Webcam [Fixed]                     | 3         | 1.6%    |
| Realtek Integrated_Webcam_HD                     | 3         | 1.6%    |
| Logitech Webcam C270                             | 3         | 1.6%    |
| IMC Networks UVC VGA Webcam                      | 3         | 1.6%    |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 1.6%    |
| Chicony ThinkPad T490 Webcam                     | 3         | 1.6%    |
| Suyin HP Webcam                                  | 2         | 1.07%   |
| Sunplus HD WebCam                                | 2         | 1.07%   |
| Sunplus Asus Webcam                              | 2         | 1.07%   |
| Silicon Motion Lenovo EasyCamera                 | 2         | 1.07%   |
| Samsung Galaxy A5 (MTP)                          | 2         | 1.07%   |
| Realtek USB Camera                               | 2         | 1.07%   |
| Microdia Integrated Webcam                       | 2         | 1.07%   |
| Logitech HD Webcam C615                          | 2         | 1.07%   |
| Lite-On Integrated Camera                        | 2         | 1.07%   |
| IMC Networks VGA UVC WebCam                      | 2         | 1.07%   |
| IMC Networks 2M Integrated Webcam                | 2         | 1.07%   |
| DJJHFA1BIF5595 HP HD Camera                      | 2         | 1.07%   |
| Chicony Webcam                                   | 2         | 1.07%   |
| Chicony USB2.0 0.3M UVC WebCam                   | 2         | 1.07%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed] | 2         | 1.07%   |
| Chicony HP HD Webcam                             | 2         | 1.07%   |
| Chicony HP HD Camera                             | 2         | 1.07%   |
| Apple FaceTime HD Camera (Built-in)              | 2         | 1.07%   |
| Alcor Micro USB 2.0 Camera                       | 2         | 1.07%   |
| Alcor Micro Asus Integrated Webcam               | 2         | 1.07%   |
| Acer SunplusIT Integrated Camera                 | 2         | 1.07%   |
| Acer LENOVO LBG 1080P CAM                        | 2         | 1.07%   |
| Z-Star Venus USB2.0 Camera                       | 1         | 0.53%   |
| Syntek Sonix USB 2.0 Camera                      | 1         | 0.53%   |
| Syntek Integrated Camera                         | 1         | 0.53%   |
| Suyin WebCam                                     | 1         | 0.53%   |
| Suyin Laptop_Integrated_Webcam_HD                | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 17        | 40.48%  |
| Validity Sensors           | 10        | 23.81%  |
| Shenzhen Goodix Technology | 4         | 9.52%   |
| Elan Microelectronics      | 4         | 9.52%   |
| AuthenTec                  | 4         | 9.52%   |
| STMicroelectronics         | 2         | 4.76%   |
| LighTuning Technology      | 1         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 9         | 21.43%  |
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 7.14%   |
| Elan ELAN:Fingerprint                                      | 3         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 4.76%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.76%   |
| AuthenTec AES2810                                          | 2         | 4.76%   |
| AuthenTec AES1600                                          | 2         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.38%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 2.38%   |
| Validity Sensors VFS491                                    | 1         | 2.38%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.38%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.38%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.38%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.38%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 2.38%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2.38%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.38%   |
| Unknown                                                    | 1         | 2.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 11        | 55%     |
| Broadcom              | 5         | 25%     |
| Gemalto (was Gemplus) | 3         | 15%     |
| Upek                  | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 55%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 10%     |
| Broadcom 5880                                                                | 2         | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5%      |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5%      |
| Broadcom 58200                                                               | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 218       | 72.43%  |
| 1     | 61        | 20.27%  |
| 2     | 17        | 5.65%   |
| 3     | 4         | 1.33%   |
| 4     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 40        | 36.36%  |
| Graphics card            | 21        | 19.09%  |
| Chipcard                 | 18        | 16.36%  |
| Net/wireless             | 9         | 8.18%   |
| Multimedia controller    | 4         | 3.64%   |
| Camera                   | 4         | 3.64%   |
| Bluetooth                | 4         | 3.64%   |
| Communication controller | 3         | 2.73%   |
| Storage/raid             | 1         | 0.91%   |
| Storage                  | 1         | 0.91%   |
| Sound                    | 1         | 0.91%   |
| Network                  | 1         | 0.91%   |
| Net/ethernet             | 1         | 0.91%   |
| Flash memory             | 1         | 0.91%   |
| Card reader              | 1         | 0.91%   |

