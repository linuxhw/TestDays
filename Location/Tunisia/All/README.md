Linux in Tunisia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Tunisia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Tunisia/Desktop/README.md) and [notebooks](/Location/Tunisia/Notebook/README.md).

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

Total: 312

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [c3e8a9f8e9](https://linux-hardware.org/?probe=c3e8a9f8e9) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [689f8869db](https://linux-hardware.org/?probe=689f8869db) | Jan 01, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [14f7c6a9df](https://linux-hardware.org/?probe=14f7c6a9df) | Dec 31, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [851f0386b3](https://linux-hardware.org/?probe=851f0386b3) | Dec 21, 2023 |
| Lenovo        | ThinkPad T430 2349QM6       | Notebook    | [398d3beb97](https://linux-hardware.org/?probe=398d3beb97) | Dec 16, 2023 |
| ECS           | G31T-M9                     | Desktop     | [30204f2a00](https://linux-hardware.org/?probe=30204f2a00) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [5ec5788395](https://linux-hardware.org/?probe=5ec5788395) | Dec 13, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [936fe9e153](https://linux-hardware.org/?probe=936fe9e153) | Nov 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [d322062b88](https://linux-hardware.org/?probe=d322062b88) | Nov 22, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [f8a086226b](https://linux-hardware.org/?probe=f8a086226b) | Nov 18, 2023 |
| ECS           | G31T-M9                     | Desktop     | [783af811f2](https://linux-hardware.org/?probe=783af811f2) | Nov 16, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [32874ad264](https://linux-hardware.org/?probe=32874ad264) | Nov 08, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [81ff23096c](https://linux-hardware.org/?probe=81ff23096c) | Nov 08, 2023 |
| HP            | Pavilion g6                 | Notebook    | [e6f697f0c0](https://linux-hardware.org/?probe=e6f697f0c0) | Nov 02, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [e8ea93da6d](https://linux-hardware.org/?probe=e8ea93da6d) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [6cbfd91e78](https://linux-hardware.org/?probe=6cbfd91e78) | Oct 30, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [1eed0a53b6](https://linux-hardware.org/?probe=1eed0a53b6) | Oct 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [d91ad654e6](https://linux-hardware.org/?probe=d91ad654e6) | Oct 18, 2023 |
| ASUSTek       | X556UJ                      | Notebook    | [010c7b3e14](https://linux-hardware.org/?probe=010c7b3e14) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | Notebook    | [e9065ad0d2](https://linux-hardware.org/?probe=e9065ad0d2) | Oct 17, 2023 |
| Toshiba       | Satellite C855-1KF          | Notebook    | [1dbc7c0de3](https://linux-hardware.org/?probe=1dbc7c0de3) | Oct 15, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [3c4e1ac4b0](https://linux-hardware.org/?probe=3c4e1ac4b0) | Oct 05, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [97bb5f9ea1](https://linux-hardware.org/?probe=97bb5f9ea1) | Sep 28, 2023 |
| Intel         | H81                         | Desktop     | [34f1a336e3](https://linux-hardware.org/?probe=34f1a336e3) | Sep 14, 2023 |
| Dell          | 0J8G6F A03                  | Desktop     | [490dd7a710](https://linux-hardware.org/?probe=490dd7a710) | Sep 04, 2023 |
| Intel         | H81                         | Desktop     | [98f445e831](https://linux-hardware.org/?probe=98f445e831) | Sep 03, 2023 |
| Dell          | G15 5530                    | Notebook    | [ababfa6c5e](https://linux-hardware.org/?probe=ababfa6c5e) | Aug 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [885c22f859](https://linux-hardware.org/?probe=885c22f859) | Aug 30, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [35aa466ca4](https://linux-hardware.org/?probe=35aa466ca4) | Aug 26, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [3e63b3dec0](https://linux-hardware.org/?probe=3e63b3dec0) | Aug 09, 2023 |
| HP            | ProBook 4740s               | Notebook    | [1c56daf13e](https://linux-hardware.org/?probe=1c56daf13e) | Aug 09, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [a036ddad16](https://linux-hardware.org/?probe=a036ddad16) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [732b1abb2d](https://linux-hardware.org/?probe=732b1abb2d) | Aug 03, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [1b07e3c9b2](https://linux-hardware.org/?probe=1b07e3c9b2) | Jul 31, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8d94c58c16](https://linux-hardware.org/?probe=8d94c58c16) | Jul 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f22c6fa671](https://linux-hardware.org/?probe=f22c6fa671) | Jul 15, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [df243ca59d](https://linux-hardware.org/?probe=df243ca59d) | Jul 08, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [7973ce0535](https://linux-hardware.org/?probe=7973ce0535) | Jun 28, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [58fc9f200f](https://linux-hardware.org/?probe=58fc9f200f) | Jun 25, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [22a8a9d964](https://linux-hardware.org/?probe=22a8a9d964) | Jun 10, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [ae3bf8f79c](https://linux-hardware.org/?probe=ae3bf8f79c) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [30f7b973cd](https://linux-hardware.org/?probe=30f7b973cd) | May 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1bd26fc56f](https://linux-hardware.org/?probe=1bd26fc56f) | May 10, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fc978d0a03](https://linux-hardware.org/?probe=fc978d0a03) | May 09, 2023 |
| HP            | Pavilion g6                 | Notebook    | [26830f860f](https://linux-hardware.org/?probe=26830f860f) | May 06, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a78e3941f5](https://linux-hardware.org/?probe=a78e3941f5) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [eb559d913e](https://linux-hardware.org/?probe=eb559d913e) | Apr 30, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [a4515227d6](https://linux-hardware.org/?probe=a4515227d6) | Apr 24, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [594ceb6023](https://linux-hardware.org/?probe=594ceb6023) | Apr 19, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [eeba9d18fa](https://linux-hardware.org/?probe=eeba9d18fa) | Apr 01, 2023 |
| Dell          | 0HMX8D A01                  | Desktop     | [36b8532260](https://linux-hardware.org/?probe=36b8532260) | Mar 31, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [d22c35c46d](https://linux-hardware.org/?probe=d22c35c46d) | Mar 29, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [2f1e23e614](https://linux-hardware.org/?probe=2f1e23e614) | Mar 24, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [23c4dc4c7c](https://linux-hardware.org/?probe=23c4dc4c7c) | Mar 17, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [9a13411e08](https://linux-hardware.org/?probe=9a13411e08) | Mar 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [be4f604d4f](https://linux-hardware.org/?probe=be4f604d4f) | Mar 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [4094f2a910](https://linux-hardware.org/?probe=4094f2a910) | Mar 14, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [8659fe0f82](https://linux-hardware.org/?probe=8659fe0f82) | Mar 07, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [33b5924e71](https://linux-hardware.org/?probe=33b5924e71) | Mar 07, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [c5d5b5f2c9](https://linux-hardware.org/?probe=c5d5b5f2c9) | Mar 04, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [167394f685](https://linux-hardware.org/?probe=167394f685) | Mar 04, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [42d050d5ff](https://linux-hardware.org/?probe=42d050d5ff) | Feb 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [09df6de7db](https://linux-hardware.org/?probe=09df6de7db) | Feb 23, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [1c8bb5ecfc](https://linux-hardware.org/?probe=1c8bb5ecfc) | Feb 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4cb7a5f214](https://linux-hardware.org/?probe=4cb7a5f214) | Jan 30, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [0eb0b40b2b](https://linux-hardware.org/?probe=0eb0b40b2b) | Jan 23, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [391c3404d3](https://linux-hardware.org/?probe=391c3404d3) | Jan 20, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [993adedd8e](https://linux-hardware.org/?probe=993adedd8e) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a279a876f3](https://linux-hardware.org/?probe=a279a876f3) | Jan 17, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [a48fadfcbd](https://linux-hardware.org/?probe=a48fadfcbd) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [11202d4caa](https://linux-hardware.org/?probe=11202d4caa) | Dec 11, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [8a112e02eb](https://linux-hardware.org/?probe=8a112e02eb) | Dec 11, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [00c90e5b24](https://linux-hardware.org/?probe=00c90e5b24) | Dec 08, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [307022e985](https://linux-hardware.org/?probe=307022e985) | Nov 30, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [778a84af28](https://linux-hardware.org/?probe=778a84af28) | Nov 28, 2022 |
| HP            | Pavilion g6                 | Notebook    | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [50c70cb811](https://linux-hardware.org/?probe=50c70cb811) | Nov 20, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [27756e9ad7](https://linux-hardware.org/?probe=27756e9ad7) | Nov 20, 2022 |
| Intel         | H81                         | Desktop     | [f99a623867](https://linux-hardware.org/?probe=f99a623867) | Nov 17, 2022 |
| Intel         | H81                         | Desktop     | [5bfd56a1f8](https://linux-hardware.org/?probe=5bfd56a1f8) | Nov 17, 2022 |
| AZW           | Gemini M                    | Desktop     | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [9c732b8892](https://linux-hardware.org/?probe=9c732b8892) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [f7cd80c534](https://linux-hardware.org/?probe=f7cd80c534) | Nov 14, 2022 |
| ASUSTek       | UX330CAK                    | Notebook    | [bd7d377985](https://linux-hardware.org/?probe=bd7d377985) | Nov 14, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [bc0831aa5e](https://linux-hardware.org/?probe=bc0831aa5e) | Nov 13, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c4811dfc5e](https://linux-hardware.org/?probe=c4811dfc5e) | Nov 12, 2022 |
| Pegatron      | Benicia                     | Desktop     | [f345c0beb9](https://linux-hardware.org/?probe=f345c0beb9) | Nov 11, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [122263e850](https://linux-hardware.org/?probe=122263e850) | Nov 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7b65a89d4f](https://linux-hardware.org/?probe=7b65a89d4f) | Nov 04, 2022 |
| HP            | 14                          | Notebook    | [7611c14813](https://linux-hardware.org/?probe=7611c14813) | Oct 31, 2022 |
| Lenovo        | ThinkPad E15 20RD001QFE     | Notebook    | [cc9f8c3aad](https://linux-hardware.org/?probe=cc9f8c3aad) | Oct 26, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [bb2647f6c8](https://linux-hardware.org/?probe=bb2647f6c8) | Oct 24, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [bec3ad2194](https://linux-hardware.org/?probe=bec3ad2194) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [f80eb01da1](https://linux-hardware.org/?probe=f80eb01da1) | Oct 13, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [f44ca565c1](https://linux-hardware.org/?probe=f44ca565c1) | Oct 11, 2022 |
| MSI           | MS-B0A41                    | Desktop     | [a0d7f23a22](https://linux-hardware.org/?probe=a0d7f23a22) | Oct 05, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [ad367d006a](https://linux-hardware.org/?probe=ad367d006a) | Sep 22, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [eed790913e](https://linux-hardware.org/?probe=eed790913e) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [22a1cba716](https://linux-hardware.org/?probe=22a1cba716) | Sep 02, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [4fdb057f33](https://linux-hardware.org/?probe=4fdb057f33) | Sep 02, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [659506d72f](https://linux-hardware.org/?probe=659506d72f) | Sep 02, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [739cbda612](https://linux-hardware.org/?probe=739cbda612) | Sep 02, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [a557da948a](https://linux-hardware.org/?probe=a557da948a) | Aug 31, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| HP            | 2AF7                        | Desktop     | [7605e926c4](https://linux-hardware.org/?probe=7605e926c4) | Aug 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [f3facd36da](https://linux-hardware.org/?probe=f3facd36da) | Aug 24, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [f0d245ec0f](https://linux-hardware.org/?probe=f0d245ec0f) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f4fedfb271](https://linux-hardware.org/?probe=f4fedfb271) | Aug 14, 2022 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [7dab66307c](https://linux-hardware.org/?probe=7dab66307c) | Aug 09, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [c57b484523](https://linux-hardware.org/?probe=c57b484523) | Aug 07, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [672cb969fb](https://linux-hardware.org/?probe=672cb969fb) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [edfabf845b](https://linux-hardware.org/?probe=edfabf845b) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 20RA000KFE     | Notebook    | [7193e153ff](https://linux-hardware.org/?probe=7193e153ff) | Jul 20, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Packard Be... | EasyNote ML65               | Notebook    | [c8c6125dc3](https://linux-hardware.org/?probe=c8c6125dc3) | Jul 06, 2022 |
| Packard Be... | EasyNote ML65               | Notebook    | [09d1580fd5](https://linux-hardware.org/?probe=09d1580fd5) | Jul 06, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [2459fb8d6e](https://linux-hardware.org/?probe=2459fb8d6e) | Jul 03, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [81e318d1d5](https://linux-hardware.org/?probe=81e318d1d5) | Jul 03, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [2218dd9966](https://linux-hardware.org/?probe=2218dd9966) | Jun 07, 2022 |
| Dell          | 05842Y A00                  | Desktop     | [7c67079823](https://linux-hardware.org/?probe=7c67079823) | May 19, 2022 |
| ASUSTek       | X556UV                      | Notebook    | [39b927dfdc](https://linux-hardware.org/?probe=39b927dfdc) | May 11, 2022 |
| Dell          | Latitude 3540               | Notebook    | [a97573f3cf](https://linux-hardware.org/?probe=a97573f3cf) | Apr 29, 2022 |
| Dell          | Latitude 3540               | Notebook    | [a6b8509194](https://linux-hardware.org/?probe=a6b8509194) | Apr 29, 2022 |
| Toshiba       | Satellite Pro L850-B339     | Notebook    | [d884eeae8f](https://linux-hardware.org/?probe=d884eeae8f) | Apr 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [af0e50e873](https://linux-hardware.org/?probe=af0e50e873) | Apr 14, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [9597b0a2d9](https://linux-hardware.org/?probe=9597b0a2d9) | Apr 09, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [03b34db583](https://linux-hardware.org/?probe=03b34db583) | Apr 05, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [e7a152d30a](https://linux-hardware.org/?probe=e7a152d30a) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7c0d1ce382](https://linux-hardware.org/?probe=7c0d1ce382) | Mar 29, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [bc07a3de3d](https://linux-hardware.org/?probe=bc07a3de3d) | Mar 15, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [ddbc85ab3a](https://linux-hardware.org/?probe=ddbc85ab3a) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [4b2b4e7f5a](https://linux-hardware.org/?probe=4b2b4e7f5a) | Mar 10, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [7803f9b898](https://linux-hardware.org/?probe=7803f9b898) | Feb 24, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [49a3015875](https://linux-hardware.org/?probe=49a3015875) | Feb 10, 2022 |
| Intel         | H61                         | Desktop     | [6d80839afa](https://linux-hardware.org/?probe=6d80839afa) | Feb 09, 2022 |
| HP            | Pavilion dv7                | Notebook    | [3bd981aa35](https://linux-hardware.org/?probe=3bd981aa35) | Feb 09, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEP... | Notebook    | [f814537586](https://linux-hardware.org/?probe=f814537586) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [09caab8240](https://linux-hardware.org/?probe=09caab8240) | Feb 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [75acdd40a6](https://linux-hardware.org/?probe=75acdd40a6) | Feb 07, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [06f3844911](https://linux-hardware.org/?probe=06f3844911) | Jan 30, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [0665a1599c](https://linux-hardware.org/?probe=0665a1599c) | Jan 26, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [22dd608151](https://linux-hardware.org/?probe=22dd608151) | Jan 07, 2022 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [391458138f](https://linux-hardware.org/?probe=391458138f) | Jan 07, 2022 |
| HP            | EliteBook 8740w             | Notebook    | [6f583dfeaf](https://linux-hardware.org/?probe=6f583dfeaf) | Dec 27, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [45a5de08c7](https://linux-hardware.org/?probe=45a5de08c7) | Dec 25, 2021 |
| HP            | Notebook                    | Notebook    | [032be84586](https://linux-hardware.org/?probe=032be84586) | Dec 09, 2021 |
| Toshiba       | Satellite C50-A489          | Notebook    | [4d29ea3b9c](https://linux-hardware.org/?probe=4d29ea3b9c) | Dec 04, 2021 |
| Lenovo        | ThinkPad X240 20AMA0WRFR    | Notebook    | [13fe3346fd](https://linux-hardware.org/?probe=13fe3346fd) | Dec 02, 2021 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [d0a08a7a23](https://linux-hardware.org/?probe=d0a08a7a23) | Nov 22, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [507c380abb](https://linux-hardware.org/?probe=507c380abb) | Nov 22, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [d49eff3d64](https://linux-hardware.org/?probe=d49eff3d64) | Nov 21, 2021 |
| Lenovo        | ThinkPad E15 20RD001SFE     | Notebook    | [358e3547b9](https://linux-hardware.org/?probe=358e3547b9) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD001SFE     | Notebook    | [694f05492e](https://linux-hardware.org/?probe=694f05492e) | Nov 17, 2021 |
| HP            | Compaq 6735s                | Notebook    | [6571a6fe6d](https://linux-hardware.org/?probe=6571a6fe6d) | Nov 15, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | Notebook    | [4bc0687791](https://linux-hardware.org/?probe=4bc0687791) | Nov 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [dcd2956978](https://linux-hardware.org/?probe=dcd2956978) | Nov 05, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a509e62c95](https://linux-hardware.org/?probe=a509e62c95) | Nov 05, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [60e3fe1197](https://linux-hardware.org/?probe=60e3fe1197) | Oct 26, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [8f6efb8dbe](https://linux-hardware.org/?probe=8f6efb8dbe) | Oct 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9b0872b3d4](https://linux-hardware.org/?probe=9b0872b3d4) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [9b74440deb](https://linux-hardware.org/?probe=9b74440deb) | Oct 07, 2021 |
| Acer          | Swift SF514-53T             | Notebook    | [e97a52d3d9](https://linux-hardware.org/?probe=e97a52d3d9) | Sep 28, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b882e1c0f7](https://linux-hardware.org/?probe=b882e1c0f7) | Sep 22, 2021 |
| HP            | 1494                        | Desktop     | [ae5165603a](https://linux-hardware.org/?probe=ae5165603a) | Sep 09, 2021 |
| HP            | 1494                        | Desktop     | [62e74e0c1a](https://linux-hardware.org/?probe=62e74e0c1a) | Sep 09, 2021 |
| HP            | 250 G4                      | Notebook    | [b5177b1c13](https://linux-hardware.org/?probe=b5177b1c13) | Sep 08, 2021 |
| HP            | 250 G4                      | Notebook    | [32899cab30](https://linux-hardware.org/?probe=32899cab30) | Sep 08, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e57d0a5518](https://linux-hardware.org/?probe=e57d0a5518) | Sep 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4cdb976c2](https://linux-hardware.org/?probe=d4cdb976c2) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [633e5a9649](https://linux-hardware.org/?probe=633e5a9649) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [58fb87de66](https://linux-hardware.org/?probe=58fb87de66) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8d891b7431](https://linux-hardware.org/?probe=8d891b7431) | Aug 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [726ed18d47](https://linux-hardware.org/?probe=726ed18d47) | Jul 25, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [a347415235](https://linux-hardware.org/?probe=a347415235) | Jul 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [98862925dc](https://linux-hardware.org/?probe=98862925dc) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6ce3d213a](https://linux-hardware.org/?probe=b6ce3d213a) | Jul 06, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [af8d7a6b6f](https://linux-hardware.org/?probe=af8d7a6b6f) | Jun 22, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [77faf70869](https://linux-hardware.org/?probe=77faf70869) | Jun 14, 2021 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [8488c59a11](https://linux-hardware.org/?probe=8488c59a11) | May 18, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [fe125a0b5f](https://linux-hardware.org/?probe=fe125a0b5f) | May 10, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [89cfbb6a0e](https://linux-hardware.org/?probe=89cfbb6a0e) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [884b3d6f69](https://linux-hardware.org/?probe=884b3d6f69) | Apr 21, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [50e1fa29fb](https://linux-hardware.org/?probe=50e1fa29fb) | Apr 16, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [be7a218721](https://linux-hardware.org/?probe=be7a218721) | Apr 12, 2021 |
| Dell          | Latitude E6420              | Notebook    | [901b94b26d](https://linux-hardware.org/?probe=901b94b26d) | Mar 10, 2021 |
| Dell          | Latitude E6420              | Notebook    | [c0d9f82152](https://linux-hardware.org/?probe=c0d9f82152) | Mar 10, 2021 |
| Dell          | Latitude E5440              | Notebook    | [89089cf0ad](https://linux-hardware.org/?probe=89089cf0ad) | Mar 05, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [347d45179a](https://linux-hardware.org/?probe=347d45179a) | Jan 30, 2021 |
| Acer          | Aspire V5-561G              | Notebook    | [4829da6130](https://linux-hardware.org/?probe=4829da6130) | Jan 30, 2021 |
| Dell          | Latitude 7410               | Notebook    | [19e75431d4](https://linux-hardware.org/?probe=19e75431d4) | Jan 30, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [07f0354547](https://linux-hardware.org/?probe=07f0354547) | Jan 29, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [5b18be0dd0](https://linux-hardware.org/?probe=5b18be0dd0) | Jan 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [cb1f74adbd](https://linux-hardware.org/?probe=cb1f74adbd) | Jan 17, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [f4c57eb290](https://linux-hardware.org/?probe=f4c57eb290) | Jan 17, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [95610ff17c](https://linux-hardware.org/?probe=95610ff17c) | Jan 14, 2021 |
| Dell          | Inspiron 3520               | Notebook    | [c1e7a232e0](https://linux-hardware.org/?probe=c1e7a232e0) | Dec 29, 2020 |
| eMachines     | E725                        | Notebook    | [aa660241b3](https://linux-hardware.org/?probe=aa660241b3) | Dec 22, 2020 |
| Dell          | Latitude 7490               | Notebook    | [d42995d26a](https://linux-hardware.org/?probe=d42995d26a) | Dec 21, 2020 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [f52e267cc9](https://linux-hardware.org/?probe=f52e267cc9) | Dec 19, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [e4ab77e8b0](https://linux-hardware.org/?probe=e4ab77e8b0) | Dec 11, 2020 |
| Lenovo        | ThinkPad E15 20RD001QFE     | Notebook    | [d02175d76c](https://linux-hardware.org/?probe=d02175d76c) | Dec 10, 2020 |
| ASUSTek       | UX310UQK                    | Notebook    | [bb566782bc](https://linux-hardware.org/?probe=bb566782bc) | Dec 04, 2020 |
| HP            | Convertible x360 11-ab0X... | Convertible | [6b543e87f8](https://linux-hardware.org/?probe=6b543e87f8) | Nov 26, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [963065205e](https://linux-hardware.org/?probe=963065205e) | Nov 26, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [c1aeee5a95](https://linux-hardware.org/?probe=c1aeee5a95) | Nov 26, 2020 |
| ASUSTek       | X550VX                      | Notebook    | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [563be9ddd8](https://linux-hardware.org/?probe=563be9ddd8) | Nov 21, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [59de1f8260](https://linux-hardware.org/?probe=59de1f8260) | Nov 20, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [64cce3acaa](https://linux-hardware.org/?probe=64cce3acaa) | Nov 04, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [97dee881c4](https://linux-hardware.org/?probe=97dee881c4) | Nov 01, 2020 |
| Dell          | 0TTDMJ A00                  | Desktop     | [aef24f2346](https://linux-hardware.org/?probe=aef24f2346) | Oct 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [a236e15c5d](https://linux-hardware.org/?probe=a236e15c5d) | Oct 25, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [f81c8f31d1](https://linux-hardware.org/?probe=f81c8f31d1) | Oct 10, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [bb4464e5f1](https://linux-hardware.org/?probe=bb4464e5f1) | Oct 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7bf6a7c3a4](https://linux-hardware.org/?probe=7bf6a7c3a4) | Sep 16, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [cdce66a7de](https://linux-hardware.org/?probe=cdce66a7de) | Jul 07, 2020 |
| ASUSTek       | UX360CA                     | Notebook    | [9d6a79d7ac](https://linux-hardware.org/?probe=9d6a79d7ac) | Jun 11, 2020 |
| ASUSTek       | UX360CA                     | Notebook    | [24742e9ec9](https://linux-hardware.org/?probe=24742e9ec9) | Jun 11, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [1cb682ea0f](https://linux-hardware.org/?probe=1cb682ea0f) | Jun 06, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [65d6dca78e](https://linux-hardware.org/?probe=65d6dca78e) | May 27, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [31501ab61b](https://linux-hardware.org/?probe=31501ab61b) | May 11, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [b8e2396d82](https://linux-hardware.org/?probe=b8e2396d82) | May 11, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4ff939d0e2](https://linux-hardware.org/?probe=4ff939d0e2) | Apr 28, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [31b3c13f93](https://linux-hardware.org/?probe=31b3c13f93) | Apr 28, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [73f10216d6](https://linux-hardware.org/?probe=73f10216d6) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [b5721fa9d5](https://linux-hardware.org/?probe=b5721fa9d5) | Apr 22, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [b391bbea48](https://linux-hardware.org/?probe=b391bbea48) | Apr 12, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [30a8d59bdc](https://linux-hardware.org/?probe=30a8d59bdc) | Apr 09, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [fc6eaad779](https://linux-hardware.org/?probe=fc6eaad779) | Apr 09, 2020 |
| ASUSTek       | X556UV                      | Notebook    | [cb5da8627a](https://linux-hardware.org/?probe=cb5da8627a) | Apr 07, 2020 |
| MSI           | MS-7502 Fab D               | Desktop     | [242c5b8d0d](https://linux-hardware.org/?probe=242c5b8d0d) | Mar 30, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [71dbec47eb](https://linux-hardware.org/?probe=71dbec47eb) | Mar 27, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [cc439d9e0f](https://linux-hardware.org/?probe=cc439d9e0f) | Mar 27, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [cb7137a57a](https://linux-hardware.org/?probe=cb7137a57a) | Mar 16, 2020 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [64628c8c11](https://linux-hardware.org/?probe=64628c8c11) | Mar 12, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [7c6e2d2c29](https://linux-hardware.org/?probe=7c6e2d2c29) | Mar 10, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [77bc52c3d9](https://linux-hardware.org/?probe=77bc52c3d9) | Mar 02, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [84ee26b4e7](https://linux-hardware.org/?probe=84ee26b4e7) | Mar 02, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [33ae5ebabc](https://linux-hardware.org/?probe=33ae5ebabc) | Feb 18, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [a1fa3183ed](https://linux-hardware.org/?probe=a1fa3183ed) | Feb 15, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [97b5418b6d](https://linux-hardware.org/?probe=97b5418b6d) | Feb 03, 2020 |
| Lenovo        | ThinkPad T440s 20AQ005NU... | Notebook    | [55d9286a1b](https://linux-hardware.org/?probe=55d9286a1b) | Jan 27, 2020 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [7878eb9e27](https://linux-hardware.org/?probe=7878eb9e27) | Dec 30, 2019 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [21f916c3ef](https://linux-hardware.org/?probe=21f916c3ef) | Dec 30, 2019 |
| Acer          | Aspire E1-570               | Notebook    | [9d92944e6c](https://linux-hardware.org/?probe=9d92944e6c) | Dec 21, 2019 |
| Acer          | Aspire E1-570               | Notebook    | [64702aadcd](https://linux-hardware.org/?probe=64702aadcd) | Dec 21, 2019 |
| Lenovo        | Unknown                     | Notebook    | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Sony          | VPCEH36EF                   | Notebook    | [5b1adbe8f0](https://linux-hardware.org/?probe=5b1adbe8f0) | Dec 10, 2019 |
| Sony          | VPCEH36EF                   | Notebook    | [6518790628](https://linux-hardware.org/?probe=6518790628) | Nov 27, 2019 |
| Dell          | Latitude E6420              | Notebook    | [3f252a50fb](https://linux-hardware.org/?probe=3f252a50fb) | Nov 12, 2019 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [1b5ae66e6f](https://linux-hardware.org/?probe=1b5ae66e6f) | Nov 10, 2019 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [a9cc2a8ea0](https://linux-hardware.org/?probe=a9cc2a8ea0) | Nov 01, 2019 |
| Unknown       | Pine Trail - M CRB          | Desktop     | [ef1e6295a8](https://linux-hardware.org/?probe=ef1e6295a8) | Oct 30, 2019 |
| Foxconn       | 2ABF                        | Desktop     | [4521f814c9](https://linux-hardware.org/?probe=4521f814c9) | Sep 17, 2019 |
| Foxconn       | 2ABF                        | Desktop     | [6a57b2ea85](https://linux-hardware.org/?probe=6a57b2ea85) | Sep 17, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b57e5735a5](https://linux-hardware.org/?probe=b57e5735a5) | Sep 13, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [708bc2c339](https://linux-hardware.org/?probe=708bc2c339) | Sep 13, 2019 |
| HP            | 630                         | Notebook    | [8cb4c328bb](https://linux-hardware.org/?probe=8cb4c328bb) | Sep 10, 2019 |
| Acer          | Aspire V5-572G              | Notebook    | [7d046c01d0](https://linux-hardware.org/?probe=7d046c01d0) | Sep 07, 2019 |
| HP            | Pavilion g6                 | Notebook    | [6eebb27f65](https://linux-hardware.org/?probe=6eebb27f65) | Aug 28, 2019 |
| HP            | Laptop                      | Notebook    | [de71114421](https://linux-hardware.org/?probe=de71114421) | Aug 21, 2019 |
| Acer          | Aspire V5-572G              | Notebook    | [90d2c432d6](https://linux-hardware.org/?probe=90d2c432d6) | Aug 17, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [26b5185afb](https://linux-hardware.org/?probe=26b5185afb) | Aug 14, 2019 |
| Pegatron      | 2A94h                       | Desktop     | [3b6656bb11](https://linux-hardware.org/?probe=3b6656bb11) | Jul 04, 2019 |
| Acer          | TravelMate P259-M           | Notebook    | [3693d52bff](https://linux-hardware.org/?probe=3693d52bff) | Nov 09, 2018 |
| Acer          | TravelMate P259-M           | Notebook    | [a951fd5ef9](https://linux-hardware.org/?probe=a951fd5ef9) | Nov 09, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [83d0682234](https://linux-hardware.org/?probe=83d0682234) | Sep 20, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e2076e8303](https://linux-hardware.org/?probe=e2076e8303) | Sep 19, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [24599e9990](https://linux-hardware.org/?probe=24599e9990) | Sep 19, 2018 |
| HP            | Pavilion g6                 | Notebook    | [c93294c4ab](https://linux-hardware.org/?probe=c93294c4ab) | Sep 18, 2018 |
| HP            | Pavilion g6                 | Notebook    | [efc4afba58](https://linux-hardware.org/?probe=efc4afba58) | Aug 10, 2018 |
| HP            | Pavilion g6                 | Notebook    | [494e0c0416](https://linux-hardware.org/?probe=494e0c0416) | Aug 10, 2018 |
| Foxconn       | 2ABF                        | Desktop     | [f6873739a8](https://linux-hardware.org/?probe=f6873739a8) | Mar 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 43        | 19.46%  |
| Ubuntu 22.04        | 20        | 9.05%   |
| Ubuntu 18.04        | 17        | 7.69%   |
| Ubuntu 21.10        | 6         | 2.71%   |
| OpenMandriva 4.2    | 5         | 2.26%   |
| Linux Mint 21.2     | 5         | 2.26%   |
| Pop!_OS 22.04       | 4         | 1.81%   |
| OpenMandriva 4.3    | 4         | 1.81%   |
| OpenMandriva 23.08  | 4         | 1.81%   |
| OpenMandriva 23.03  | 4         | 1.81%   |
| KDE neon 22.04      | 4         | 1.81%   |
| Fedora 38           | 4         | 1.81%   |
| Debian 11           | 4         | 1.81%   |
| Zorin 16            | 3         | 1.36%   |
| Zorin 15            | 3         | 1.36%   |
| Ubuntu 19.10        | 3         | 1.36%   |
| Ubuntu 16.04        | 3         | 1.36%   |
| Linux Mint 21.1     | 3         | 1.36%   |
| KDE neon 20.04      | 3         | 1.36%   |
| Debian 10           | 3         | 1.36%   |
| ArcoLinux Rolling   | 3         | 1.36%   |
| Ubuntu 21.04        | 2         | 0.9%    |
| Ubuntu 20.10        | 2         | 0.9%    |
| ROSA R10            | 2         | 0.9%    |
| ROSA 12.3           | 2         | 0.9%    |
| Pop!_OS 21.04       | 2         | 0.9%    |
| OpenMandriva 23.07  | 2         | 0.9%    |
| Manjaro 21.1.0      | 2         | 0.9%    |
| LMDE 4              | 2         | 0.9%    |
| Linux Mint 20.3     | 2         | 0.9%    |
| Linux Mint 20.2     | 2         | 0.9%    |
| Linux Mint 20       | 2         | 0.9%    |
| Gentoo 2.8          | 2         | 0.9%    |
| Gentoo 2.7          | 2         | 0.9%    |
| Fedora 35           | 2         | 0.9%    |
| Fedora 33           | 2         | 0.9%    |
| EndeavourOS Rolling | 2         | 0.9%    |
| Arch Rolling        | 2         | 0.9%    |
| Arch                | 2         | 0.9%    |
| Xubuntu 18.04       | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 91        | 43.13%  |
| OpenMandriva | 19        | 9%      |
| Linux Mint   | 16        | 7.58%   |
| Fedora       | 9         | 4.27%   |
| Debian       | 9         | 4.27%   |
| Pop!_OS      | 7         | 3.32%   |
| Zorin        | 6         | 2.84%   |
| ROSA         | 6         | 2.84%   |
| Manjaro      | 6         | 2.84%   |
| KDE neon     | 5         | 2.37%   |
| Endless      | 4         | 1.9%    |
| Arch         | 4         | 1.9%    |
| Gentoo       | 3         | 1.42%   |
| ArcoLinux    | 3         | 1.42%   |
| Lubuntu      | 2         | 0.95%   |
| LMDE         | 2         | 0.95%   |
| Kali         | 2         | 0.95%   |
| EndeavourOS  | 2         | 0.95%   |
| Elementary   | 2         | 0.95%   |
| Xubuntu      | 1         | 0.47%   |
| Xero         | 1         | 0.47%   |
| Ubuntu Unity | 1         | 0.47%   |
| TUXEDO OS    | 1         | 0.47%   |
| SteamOS      | 1         | 0.47%   |
| Sodalite     | 1         | 0.47%   |
| Nobara       | 1         | 0.47%   |
| MX           | 1         | 0.47%   |
| Kubuntu      | 1         | 0.47%   |
| Garuda Linux | 1         | 0.47%   |
| Devuan       | 1         | 0.47%   |
| Deepin       | 1         | 0.47%   |
| BlackPanther | 1         | 0.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.15.0-58-generic               | 5         | 2.06%   |
| 5.10.14-desktop-1omv4002        | 5         | 2.06%   |
| 6.4.11-desktop-1omv2390         | 4         | 1.65%   |
| 6.2.6-desktop-1omv2390          | 4         | 1.65%   |
| 5.16.7-desktop-1omv4003         | 4         | 1.65%   |
| 5.15.0-52-generic               | 4         | 1.65%   |
| 5.15.0-46-generic               | 4         | 1.65%   |
| 5.13.0-28-generic               | 4         | 1.65%   |
| 6.2.0-36-generic                | 3         | 1.23%   |
| 5.3.0-46-generic                | 3         | 1.23%   |
| 5.3.0-40-generic                | 3         | 1.23%   |
| 5.15.0-56-generic               | 3         | 1.23%   |
| 5.15.0-53-generic               | 3         | 1.23%   |
| 5.15.0-43-generic               | 3         | 1.23%   |
| 5.11.0-38-generic               | 3         | 1.23%   |
| 5.11.0-27-generic               | 3         | 1.23%   |
| 6.3.5-desktop-3omv2390          | 2         | 0.82%   |
| 5.8.0-38-generic                | 2         | 0.82%   |
| 5.8.0-14-generic                | 2         | 0.82%   |
| 5.4.0-72-generic                | 2         | 0.82%   |
| 5.4.0-58-generic                | 2         | 0.82%   |
| 5.4.0-52-generic                | 2         | 0.82%   |
| 5.4.0-42-generic                | 2         | 0.82%   |
| 5.4.0-26-generic                | 2         | 0.82%   |
| 5.3.0-28-generic                | 2         | 0.82%   |
| 5.19.0-45-generic               | 2         | 0.82%   |
| 5.15.84-v8+                     | 2         | 0.82%   |
| 5.15.0-41-generic               | 2         | 0.82%   |
| 5.13.0-44-generic               | 2         | 0.82%   |
| 5.13.0-40-generic               | 2         | 0.82%   |
| 5.11.0-7620-generic             | 2         | 0.82%   |
| 5.11.0-40-generic               | 2         | 0.82%   |
| 5.10.27-gentoo                  | 2         | 0.82%   |
| 5.10.0-12-amd64                 | 2         | 0.82%   |
| 5.0.0-25-generic                | 2         | 0.82%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.82%   |
| 4.19.0-6-amd64                  | 2         | 0.82%   |
| 4.15.0-91-generic               | 2         | 0.82%   |
| 6.5.8-200.fc38.x86_64           | 1         | 0.41%   |
| 6.5.7-arch1-1                   | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 33        | 14.22%  |
| 5.4.0   | 27        | 11.64%  |
| 5.13.0  | 15        | 6.47%   |
| 5.11.0  | 13        | 5.6%    |
| 5.8.0   | 11        | 4.74%   |
| 5.3.0   | 11        | 4.74%   |
| 4.15.0  | 10        | 4.31%   |
| 5.19.0  | 9         | 3.88%   |
| 5.0.0   | 7         | 3.02%   |
| 6.2.0   | 5         | 2.16%   |
| 5.10.14 | 5         | 2.16%   |
| 4.19.0  | 5         | 2.16%   |
| 6.4.11  | 4         | 1.72%   |
| 6.2.6   | 4         | 1.72%   |
| 5.16.7  | 4         | 1.72%   |
| 6.5.0   | 3         | 1.29%   |
| 6.3.5   | 3         | 1.29%   |
| 5.10.0  | 3         | 1.29%   |
| 4.18.0  | 3         | 1.29%   |
| 6.5.7   | 2         | 0.86%   |
| 6.3.6   | 2         | 0.86%   |
| 5.18.0  | 2         | 0.86%   |
| 5.17.5  | 2         | 0.86%   |
| 5.15.84 | 2         | 0.86%   |
| 5.15.75 | 2         | 0.86%   |
| 5.10.27 | 2         | 0.86%   |
| 4.9.60  | 2         | 0.86%   |
| 6.5.8   | 1         | 0.43%   |
| 6.5.6   | 1         | 0.43%   |
| 6.4.12  | 1         | 0.43%   |
| 6.2.9   | 1         | 0.43%   |
| 6.2.5   | 1         | 0.43%   |
| 6.2.11  | 1         | 0.43%   |
| 6.1.31  | 1         | 0.43%   |
| 6.1.29  | 1         | 0.43%   |
| 6.1.19  | 1         | 0.43%   |
| 6.1.11  | 1         | 0.43%   |
| 6.1.0   | 1         | 0.43%   |
| 5.9.9   | 1         | 0.43%   |
| 5.9.1   | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 41        | 18.14%  |
| 5.4     | 29        | 12.83%  |
| 5.13    | 16        | 7.08%   |
| 5.11    | 15        | 6.64%   |
| 6.2     | 12        | 5.31%   |
| 5.8     | 12        | 5.31%   |
| 5.3     | 12        | 5.31%   |
| 5.10    | 12        | 5.31%   |
| 5.19    | 10        | 4.42%   |
| 4.15    | 10        | 4.42%   |
| 6.5     | 7         | 3.1%    |
| 5.0     | 7         | 3.1%    |
| 5.16    | 6         | 2.65%   |
| 6.4     | 5         | 2.21%   |
| 6.3     | 5         | 2.21%   |
| 4.19    | 5         | 2.21%   |
| 6.1     | 4         | 1.77%   |
| 5.17    | 3         | 1.33%   |
| 4.9     | 3         | 1.33%   |
| 4.18    | 3         | 1.33%   |
| 5.9     | 2         | 0.88%   |
| 5.18    | 2         | 0.88%   |
| 5.6     | 1         | 0.44%   |
| 5.14    | 1         | 0.44%   |
| 5.12    | 1         | 0.44%   |
| 4.4     | 1         | 0.44%   |
| 3.13    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 199       | 97.55%  |
| i686    | 3         | 1.47%   |
| aarch64 | 2         | 0.98%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 115       | 54.25%  |
| KDE5            | 37        | 17.45%  |
| Unknown         | 17        | 8.02%   |
| X-Cinnamon      | 15        | 7.08%   |
| XFCE            | 9         | 4.25%   |
| KDE4            | 4         | 1.89%   |
| Pantheon        | 3         | 1.42%   |
| MATE            | 2         | 0.94%   |
| GNOME Flashback | 2         | 0.94%   |
| Unity           | 1         | 0.47%   |
| LXQt            | 1         | 0.47%   |
| LXDE            | 1         | 0.47%   |
| i3              | 1         | 0.47%   |
| GNOME Classic   | 1         | 0.47%   |
| DWM             | 1         | 0.47%   |
| Deepin          | 1         | 0.47%   |
| Cinnamon        | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 155       | 73.46%  |
| Wayland | 46        | 21.8%   |
| Tty     | 5         | 2.37%   |
| Unknown | 5         | 2.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 81        | 38.39%  |
| GDM     | 49        | 23.22%  |
| SDDM    | 32        | 15.17%  |
| GDM3    | 29        | 13.74%  |
| LightDM | 16        | 7.58%   |
| KDM     | 4         | 1.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 98        | 47.34%  |
| fr_FR   | 64        | 30.92%  |
| Unknown | 19        | 9.18%   |
| en_GB   | 11        | 5.31%   |
| C       | 5         | 2.42%   |
| pt_BR   | 2         | 0.97%   |
| ar_TN   | 2         | 0.97%   |
| fr_CA   | 1         | 0.48%   |
| en_IN   | 1         | 0.48%   |
| en_CA   | 1         | 0.48%   |
| en_AU   | 1         | 0.48%   |
| en_AG   | 1         | 0.48%   |
| de_DE   | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 115       | 54.5%   |
| BIOS | 96        | 45.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 168       | 81.95%  |
| Overlay | 16        | 7.8%    |
| Btrfs   | 11        | 5.37%   |
| Unknown | 6         | 2.93%   |
| Tmpfs   | 3         | 1.46%   |
| Xfs     | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 90        | 43.06%  |
| GPT     | 83        | 39.71%  |
| MBR     | 36        | 17.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 176       | 84.62%  |
| Yes       | 32        | 15.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 135       | 66.5%   |
| Yes       | 68        | 33.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 49        | 24.14%  |
| Hewlett-Packard         | 34        | 16.75%  |
| ASUSTek Computer        | 34        | 16.75%  |
| Dell                    | 30        | 14.78%  |
| Acer                    | 13        | 6.4%    |
| MSI                     | 12        | 5.91%   |
| Toshiba                 | 8         | 3.94%   |
| Pegatron                | 4         | 1.97%   |
| Intel                   | 3         | 1.48%   |
| Samsung Electronics     | 2         | 0.99%   |
| Raspberry Pi Foundation | 2         | 0.99%   |
| Foxconn                 | 2         | 0.99%   |
| Valve                   | 1         | 0.49%   |
| Sony                    | 1         | 0.49%   |
| Packard Bell            | 1         | 0.49%   |
| LORD ELECTRONICS        | 1         | 0.49%   |
| Gigabyte Technology     | 1         | 0.49%   |
| eMachines               | 1         | 0.49%   |
| ECS                     | 1         | 0.49%   |
| AZW                     | 1         | 0.49%   |
| ASRock                  | 1         | 0.49%   |
| Unknown                 | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| HP Pavilion g6                            | 6         | 2.96%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK     | 3         | 1.48%   |
| Lenovo IdeaPad 3 15ADA05 81W1             | 3         | 1.48%   |
| Dell Inspiron 5570                        | 3         | 1.48%   |
| Pegatron VS342AA-AB6 m9801af              | 2         | 0.99%   |
| MSI GF63 Thin 10SCXR                      | 2         | 0.99%   |
| Lenovo IdeaPad 700-15ISK 80RU             | 2         | 0.99%   |
| Lenovo IdeaPad 5 15ITL05 82FG             | 2         | 0.99%   |
| Lenovo IdeaPad 130-15IKB 81H7             | 2         | 0.99%   |
| Intel H81                                 | 2         | 0.99%   |
| HP Pavilion Gaming Laptop 15-ec1xxx       | 2         | 0.99%   |
| Foxconn Pro 3400 Series MT                | 2         | 0.99%   |
| Dell Inspiron N5110                       | 2         | 0.99%   |
| ASUS X556UV                               | 2         | 0.99%   |
| ASUS X553MA                               | 2         | 0.99%   |
| ASUS X550JX                               | 2         | 0.99%   |
| Acer Aspire E5-571G                       | 2         | 0.99%   |
| Unknown                                   | 2         | 0.99%   |
| Valve Jupiter                             | 1         | 0.49%   |
| Toshiba Satellite Pro L850-B339           | 1         | 0.49%   |
| Toshiba Satellite L550                    | 1         | 0.49%   |
| Toshiba Satellite L500                    | 1         | 0.49%   |
| Toshiba Satellite C855-1KF                | 1         | 0.49%   |
| Toshiba Satellite C650D                   | 1         | 0.49%   |
| Toshiba Satellite C55-C                   | 1         | 0.49%   |
| Toshiba Satellite C50-A489                | 1         | 0.49%   |
| Toshiba Satellite A300                    | 1         | 0.49%   |
| Sony VPCEH36EF                            | 1         | 0.49%   |
| Samsung 530U3BI/530U4BI/530U4BH           | 1         | 0.49%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV   | 1         | 0.49%   |
| RPi Raspberry Pi Compute Module 4 Rev 1.0 | 1         | 0.49%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 1         | 0.49%   |
| Pegatron Pro 3010 Microtower PC           | 1         | 0.49%   |
| Pegatron FL437AA-ABF a6641af              | 1         | 0.49%   |
| Packard Bell EasyNote ML65                | 1         | 0.49%   |
| MSI PRO H510 DP21 (MS-B0A4)               | 1         | 0.49%   |
| MSI MS-7C95                               | 1         | 0.49%   |
| MSI MS-7C52                               | 1         | 0.49%   |
| MSI MS-7C09                               | 1         | 0.49%   |
| MSI MS-7A15                               | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 26        | 12.81%  |
| HP Pavilion           | 13        | 6.4%    |
| Dell Inspiron         | 13        | 6.4%    |
| Lenovo ThinkPad       | 10        | 4.93%   |
| Acer Aspire           | 9         | 4.43%   |
| Toshiba Satellite     | 8         | 3.94%   |
| Dell OptiPlex         | 7         | 3.45%   |
| Dell Latitude         | 6         | 2.96%   |
| HP ProBook            | 5         | 2.46%   |
| HP Laptop             | 5         | 2.46%   |
| ASUS TUF              | 4         | 1.97%   |
| MSI GF63              | 3         | 1.48%   |
| Dell Vostro           | 3         | 1.48%   |
| ASUS VivoBook         | 3         | 1.48%   |
| ASUS PRIME            | 3         | 1.48%   |
| RPi Raspberry         | 2         | 0.99%   |
| Pegatron VS342AA-AB6  | 2         | 0.99%   |
| Intel H81             | 2         | 0.99%   |
| HP EliteBook          | 2         | 0.99%   |
| HP Compaq             | 2         | 0.99%   |
| HP 250                | 2         | 0.99%   |
| Foxconn Pro           | 2         | 0.99%   |
| ASUS ZenBook          | 2         | 0.99%   |
| ASUS X556UV           | 2         | 0.99%   |
| ASUS X553MA           | 2         | 0.99%   |
| ASUS X550JX           | 2         | 0.99%   |
| ASUS ROG              | 2         | 0.99%   |
| ASUS ASUS             | 2         | 0.99%   |
| Acer Swift            | 2         | 0.99%   |
| Unknown               | 2         | 0.99%   |
| Valve Jupiter         | 1         | 0.49%   |
| Sony VPCEH36EF        | 1         | 0.49%   |
| Samsung 530U3BI       | 1         | 0.49%   |
| Samsung 300E5EV       | 1         | 0.49%   |
| Pegatron Pro          | 1         | 0.49%   |
| Pegatron FL437AA-ABF  | 1         | 0.49%   |
| Packard Bell EasyNote | 1         | 0.49%   |
| MSI PRO               | 1         | 0.49%   |
| MSI MS-7C95           | 1         | 0.49%   |
| MSI MS-7C52           | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 27        | 13.3%   |
| 2019    | 21        | 10.34%  |
| 2011    | 18        | 8.87%   |
| 2017    | 17        | 8.37%   |
| 2021    | 14        | 6.9%    |
| 2015    | 14        | 6.9%    |
| 2013    | 14        | 6.9%    |
| 2018    | 13        | 6.4%    |
| 2012    | 13        | 6.4%    |
| 2014    | 12        | 5.91%   |
| 2016    | 11        | 5.42%   |
| 2009    | 9         | 4.43%   |
| 2010    | 7         | 3.45%   |
| 2008    | 6         | 2.96%   |
| 2023    | 2         | 0.99%   |
| 2022    | 2         | 0.99%   |
| Unknown | 2         | 0.99%   |
| 2007    | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 161       | 79.31%  |
| Desktop        | 38        | 18.72%  |
| System on chip | 2         | 0.99%   |
| Convertible    | 2         | 0.99%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 189       | 92.2%   |
| Enabled  | 16        | 7.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 203       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 69        | 33.66%  |
| 3.01-4.0   | 41        | 20%     |
| 16.01-24.0 | 38        | 18.54%  |
| 8.01-16.0  | 37        | 18.05%  |
| 32.01-64.0 | 7         | 3.41%   |
| 1.01-2.0   | 6         | 2.93%   |
| 2.01-3.0   | 4         | 1.95%   |
| 0.51-1.0   | 2         | 0.98%   |
| 24.01-32.0 | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 69        | 30.67%  |
| 1.01-2.0  | 67        | 29.78%  |
| 4.01-8.0  | 36        | 16%     |
| 3.01-4.0  | 34        | 15.11%  |
| 0.51-1.0  | 7         | 3.11%   |
| 8.01-16.0 | 6         | 2.67%   |
| 0.01-0.5  | 5         | 2.22%   |
| Unknown   | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 146       | 69.52%  |
| 2      | 58        | 27.62%  |
| 4      | 3         | 1.43%   |
| 3      | 2         | 0.95%   |
| 0      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 54.63%  |
| Yes       | 93        | 45.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 173       | 85.22%  |
| No        | 30        | 14.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 88.24%  |
| No        | 24        | 11.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 73.91%  |
| No        | 54        | 26.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Tunisia | 203       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tunis              | 114       | 49.14%  |
| Aryanah            | 15        | 6.47%   |
| Sousse             | 11        | 4.74%   |
| Nabeul             | 10        | 4.31%   |
| Sfax               | 8         | 3.45%   |
| Bizerte            | 7         | 3.02%   |
| Monastir           | 5         | 2.16%   |
| Ben Arous          | 4         | 1.72%   |
| Mateur             | 3         | 1.29%   |
| Centre Urbain Nord | 3         | 1.29%   |
| Rades              | 2         | 0.86%   |
| Masakin            | 2         | 0.86%   |
| Manouba            | 2         | 0.86%   |
| Mahdia             | 2         | 0.86%   |
| Kairouan           | 2         | 0.86%   |
| Jedeida            | 2         | 0.86%   |
| Houmt Souk         | 2         | 0.86%   |
| Hammamet           | 2         | 0.86%   |
| Gafsa              | 2         | 0.86%   |
| Zarzis             | 1         | 0.43%   |
| Zaouiat Djedidi    | 1         | 0.43%   |
| Wadi Maliz         | 1         | 0.43%   |
| Tebourba           | 1         | 0.43%   |
| Tataouine          | 1         | 0.43%   |
| Tabarka            | 1         | 0.43%   |
| Soliman            | 1         | 0.43%   |
| Sidi Abbes         | 1         | 0.43%   |
| Rafraf             | 1         | 0.43%   |
| Oued Lill          | 1         | 0.43%   |
| Le Bardo           | 1         | 0.43%   |
| La Mohammedia      | 1         | 0.43%   |
| La Marsa           | 1         | 0.43%   |
| La Goulette        | 1         | 0.43%   |
| Ksar Hellal        | 1         | 0.43%   |
| Kelaa Kebira       | 1         | 0.43%   |
| Jendouba           | 1         | 0.43%   |
| Hergla             | 1         | 0.43%   |
| Hammam Sousse      | 1         | 0.43%   |
| Gremda             | 1         | 0.43%   |
| Ezzouhour          | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 56        | 70     | 21.71%  |
| WDC                         | 38        | 50     | 14.73%  |
| Toshiba                     | 32        | 36     | 12.4%   |
| Samsung Electronics         | 19        | 36     | 7.36%   |
| Team                        | 13        | 15     | 5.04%   |
| SK hynix                    | 13        | 17     | 5.04%   |
| Hitachi                     | 11        | 11     | 4.26%   |
| SanDisk                     | 9         | 11     | 3.49%   |
| Micron Technology           | 8         | 8      | 3.1%    |
| Unknown                     | 7         | 11     | 2.71%   |
| Intel                       | 7         | 8      | 2.71%   |
| HGST                        | 7         | 8      | 2.71%   |
| Kingston                    | 6         | 8      | 2.33%   |
| A-DATA Technology           | 5         | 6      | 1.94%   |
| PNY                         | 4         | 4      | 1.55%   |
| Fujitsu                     | 3         | 3      | 1.16%   |
| Emtec                       | 2         | 4      | 0.78%   |
| UMIS                        | 1         | 1      | 0.39%   |
| TwinMOS                     | 1         | 1      | 0.39%   |
| SPCC                        | 1         | 1      | 0.39%   |
| SATAFIRM                    | 1         | 1      | 0.39%   |
| Realtek Semiconductor       | 1         | 1      | 0.39%   |
| Phison Electronics          | 1         | 1      | 0.39%   |
| Phison                      | 1         | 1      | 0.39%   |
| Patriot                     | 1         | 1      | 0.39%   |
| OCZ                         | 1         | 1      | 0.39%   |
| O2 Micro                    | 1         | 1      | 0.39%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.39%   |
| LITEON                      | 1         | 1      | 0.39%   |
| Lexar                       | 1         | 1      | 0.39%   |
| KVST                        | 1         | 1      | 0.39%   |
| HS-SSD-E100                 | 1         | 2      | 0.39%   |
| China                       | 1         | 1      | 0.39%   |
| addlink                     | 1         | 1      | 0.39%   |
| ADATA Technology            | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 16        | 5.99%   |
| Seagate ST500LT012-1DG142 500GB       | 8         | 3%      |
| Seagate ST2000LM007-1R8174 2TB        | 6         | 2.25%   |
| Hitachi HTS545050A7E380 500GB         | 6         | 2.25%   |
| Toshiba MQ04ABF100 1TB                | 5         | 1.87%   |
| Seagate ST1000DM010-2EP102 1TB        | 4         | 1.5%    |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 1.12%   |
| Toshiba MQ01ABD100 1TB                | 3         | 1.12%   |
| Toshiba MQ01ABD075 752GB              | 3         | 1.12%   |
| Intel SSDPEKNW512GZL 512GB            | 3         | 1.12%   |
| HGST HTS545050A7E380 500GB            | 3         | 1.12%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 0.75%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 0.75%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 0.75%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 0.75%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 0.75%   |
| WDC WD10EADS-65M2B0 1TB               | 2         | 0.75%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 2         | 0.75%   |
| Toshiba MQ01ABF050 500GB              | 2         | 0.75%   |
| Toshiba MK5076GSX 500GB               | 2         | 0.75%   |
| Toshiba MK3275GSX 320GB               | 2         | 0.75%   |
| Toshiba DT01ACA050 500GB              | 2         | 0.75%   |
| Team T253X2512G 512GB SSD             | 2         | 0.75%   |
| Team T253X1480G 480GB SSD             | 2         | 0.75%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 0.75%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 0.75%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 2         | 0.75%   |
| Seagate ST9500325AS 500GB             | 2         | 0.75%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 0.75%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 0.75%   |
| SanDisk NVMe SSD Drive 512GB          | 2         | 0.75%   |
| Samsung SSD 980 500GB                 | 2         | 0.75%   |
| Samsung SSD 860 EVO 500GB             | 2         | 0.75%   |
| PNY CS900 240GB SSD                   | 2         | 0.75%   |
| Micron 2210_MTFDHBA512QFD 512GB       | 2         | 0.75%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 0.75%   |
| Fujitsu MHV2100BH PL 100GB            | 2         | 0.75%   |
| A-DATA SU750 256GB SSD                | 2         | 0.75%   |
| WDC WD6400AAKS-65A7B0 640GB           | 1         | 0.37%   |
| WDC WD5000LPZX-60Z10T0 500GB          | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 69     | 38.73%  |
| WDC                 | 33        | 44     | 23.24%  |
| Toshiba             | 32        | 36     | 22.54%  |
| Hitachi             | 11        | 11     | 7.75%   |
| HGST                | 7         | 8      | 4.93%   |
| Fujitsu             | 3         | 3      | 2.11%   |
| Samsung Electronics | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 9         | 11     | 17.65%  |
| Samsung Electronics | 7         | 11     | 13.73%  |
| SK hynix            | 6         | 9      | 11.76%  |
| SanDisk             | 5         | 6      | 9.8%    |
| PNY                 | 4         | 4      | 7.84%   |
| A-DATA Technology   | 3         | 4      | 5.88%   |
| Micron Technology   | 2         | 2      | 3.92%   |
| Kingston            | 2         | 2      | 3.92%   |
| Emtec               | 2         | 4      | 3.92%   |
| TwinMOS             | 1         | 1      | 1.96%   |
| SPCC                | 1         | 1      | 1.96%   |
| SATAFIRM            | 1         | 1      | 1.96%   |
| Patriot             | 1         | 1      | 1.96%   |
| OCZ                 | 1         | 1      | 1.96%   |
| LITEON              | 1         | 1      | 1.96%   |
| Lexar               | 1         | 1      | 1.96%   |
| KVST                | 1         | 1      | 1.96%   |
| HS-SSD-E100         | 1         | 2      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| addlink             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 137       | 172    | 55.69%  |
| NVMe    | 52        | 76     | 21.14%  |
| SSD     | 49        | 65     | 19.92%  |
| MMC     | 6         | 10     | 2.44%   |
| Unknown | 2         | 2      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 162       | 235    | 72.32%  |
| NVMe | 52        | 76     | 23.21%  |
| MMC  | 6         | 10     | 2.68%   |
| SAS  | 4         | 4      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 107       | 133    | 58.47%  |
| 0.51-1.0   | 66        | 92     | 36.07%  |
| 1.01-2.0   | 10        | 12     | 5.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 64        | 30.19%  |
| 101-250        | 59        | 27.83%  |
| 501-1000       | 33        | 15.57%  |
| 1001-2000      | 16        | 7.55%   |
| 51-100         | 13        | 6.13%   |
| 1-20           | 12        | 5.66%   |
| 21-50          | 8         | 3.77%   |
| 2001-3000      | 3         | 1.42%   |
| Unknown        | 3         | 1.42%   |
| More than 3000 | 1         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 81        | 36.65%  |
| 21-50     | 43        | 19.46%  |
| 101-250   | 39        | 17.65%  |
| 51-100    | 31        | 14.03%  |
| 251-500   | 9         | 4.07%   |
| 501-1000  | 8         | 3.62%   |
| 1001-2000 | 7         | 3.17%   |
| Unknown   | 3         | 1.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Hitachi HTS545050A7E380 500GB                       | 4         | 4      | 13.33%  |
| Seagate ST9500325AS 500GB                           | 2         | 2      | 6.67%   |
| HGST HTS545050A7E380 500GB                          | 2         | 3      | 6.67%   |
| WDC WD6400AAKS-65A7B0 640GB                         | 1         | 1      | 3.33%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 3.33%   |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 3.33%   |
| WDC WD5000BEVT-22A0RT0 500GB                        | 1         | 1      | 3.33%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 3.33%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 3.33%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 3.33%   |
| Seagate ST9320325AS 320GB                           | 1         | 2      | 3.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.33%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 3.33%   |
| Seagate ST3320813AS 320GB                           | 1         | 1      | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 3.33%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 3.33%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 3.33%   |
| Hitachi HTS547575A9E384 752GB                       | 1         | 1      | 3.33%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 3.33%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 3.33%   |
| Emtec X250 512GB                                    | 1         | 2      | 3.33%   |
| A-DATA Technology SX8100NP 512GB                    | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 9         | 12     | 30%     |
| Hitachi           | 7         | 7      | 23.33%  |
| Toshiba           | 5         | 6      | 16.67%  |
| WDC               | 4         | 5      | 13.33%  |
| HGST              | 2         | 3      | 6.67%   |
| Micron Technology | 1         | 1      | 3.33%   |
| Emtec             | 1         | 2      | 3.33%   |
| A-DATA Technology | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 12     | 33.33%  |
| Hitachi | 7         | 7      | 25.93%  |
| Toshiba | 5         | 6      | 18.52%  |
| WDC     | 4         | 5      | 14.81%  |
| HGST    | 2         | 3      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 33     | 89.29%  |
| SSD  | 2         | 3      | 7.14%   |
| NVMe | 1         | 1      | 3.57%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK1646GSX 160GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 99        | 141    | 45.21%  |
| Works    | 91        | 146    | 41.55%  |
| Malfunc  | 28        | 37     | 12.79%  |
| Failed   | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 167       | 70.17%  |
| AMD                          | 22        | 9.24%   |
| Samsung Electronics          | 11        | 4.62%   |
| SanDisk                      | 8         | 3.36%   |
| SK hynix                     | 7         | 2.94%   |
| Micron Technology            | 6         | 2.52%   |
| Phison Electronics           | 4         | 1.68%   |
| Kingston Technology Company  | 4         | 1.68%   |
| Realtek Semiconductor        | 3         | 1.26%   |
| Union Memory (Shenzhen)      | 1         | 0.42%   |
| Silicon Motion               | 1         | 0.42%   |
| Shenzhen Longsys Electronics | 1         | 0.42%   |
| O2 Micro                     | 1         | 0.42%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.42%   |
| ADATA Technology             | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 6.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 6.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 4.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 4.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 12        | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 3.85%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 9         | 3.46%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 9         | 3.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 3.08%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 7         | 2.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 2.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 2.31%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 2.31%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6         | 2.31%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 5         | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.92%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 4         | 1.54%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 4         | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 1.15%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 3         | 1.15%   |
| Phison E12 NVMe Controller                                                              | 3         | 1.15%   |
| Intel SSD 660P Series                                                                   | 3         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.15%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 1.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.15%   |
| SK hynix BC511 NVMe SSD                                                                 | 2         | 0.77%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 2         | 0.77%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 2         | 0.77%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 2         | 0.77%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.77%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 154       | 63.11%  |
| NVMe | 52        | 21.31%  |
| RAID | 23        | 9.43%   |
| IDE  | 15        | 6.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 172       | 84.73%  |
| AMD    | 29        | 14.29%  |
| ARM    | 2         | 0.99%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 2.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 2.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 2.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.97%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 1.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.48%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.48%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.48%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.48%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.48%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.48%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 0.99%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.99%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.99%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.99%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.99%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.99%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.99%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.99%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.99%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.99%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.99%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.99%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 0.99%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2         | 0.99%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2         | 0.99%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 0.99%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.99%   |
| ARM Processor                                 | 2         | 0.99%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 51        | 25.12%  |
| Intel Core i7           | 39        | 19.21%  |
| Intel Core i3           | 31        | 15.27%  |
| Other                   | 21        | 10.34%  |
| AMD Ryzen 5             | 11        | 5.42%   |
| Intel Pentium           | 10        | 4.93%   |
| Intel Celeron           | 8         | 3.94%   |
| Intel Core 2 Quad       | 7         | 3.45%   |
| Intel Core 2 Duo        | 5         | 2.46%   |
| AMD Ryzen 7             | 3         | 1.48%   |
| Intel Pentium Dual-Core | 2         | 0.99%   |
| AMD Ryzen 3             | 2         | 0.99%   |
| Intel Xeon              | 1         | 0.49%   |
| Intel Core m3           | 1         | 0.49%   |
| Intel Atom              | 1         | 0.49%   |
| AMD Sempron             | 1         | 0.49%   |
| AMD Ryzen 5 PRO         | 1         | 0.49%   |
| AMD FX                  | 1         | 0.49%   |
| AMD E2                  | 1         | 0.49%   |
| AMD E                   | 1         | 0.49%   |
| AMD Athlon              | 1         | 0.49%   |
| AMD A8                  | 1         | 0.49%   |
| AMD A6                  | 1         | 0.49%   |
| AMD A4                  | 1         | 0.49%   |
| AMD A10                 | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 99        | 48.77%  |
| 4       | 75        | 36.95%  |
| 6       | 15        | 7.39%   |
| 8       | 7         | 3.45%   |
| 10      | 2         | 0.99%   |
| 1       | 2         | 0.99%   |
| 14      | 1         | 0.49%   |
| 12      | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 203       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 154       | 75.49%  |
| 1       | 49        | 24.02%  |
| Unknown | 1         | 0.49%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 202       | 99.51%  |
| Unknown        | 1         | 0.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 30.66%  |
| 0x206a7    | 15        | 7.08%   |
| 0x40651    | 9         | 4.25%   |
| 0x1067a    | 9         | 4.25%   |
| 0x806ea    | 8         | 3.77%   |
| 0x806c1    | 8         | 3.77%   |
| 0x306a9    | 8         | 3.77%   |
| 0xa0652    | 7         | 3.3%    |
| 0x806ec    | 7         | 3.3%    |
| 0x906ea    | 6         | 2.83%   |
| 0x506e3    | 6         | 2.83%   |
| 0x406e3    | 5         | 2.36%   |
| 0x306c3    | 5         | 2.36%   |
| 0x08108109 | 5         | 2.36%   |
| 0x806e9    | 3         | 1.42%   |
| 0x706e5    | 3         | 1.42%   |
| 0x306d4    | 3         | 1.42%   |
| 0x20655    | 3         | 1.42%   |
| 0x706a8    | 2         | 0.94%   |
| 0x406c4    | 2         | 0.94%   |
| 0x30678    | 2         | 0.94%   |
| 0x08600106 | 2         | 0.94%   |
| 0x08108102 | 2         | 0.94%   |
| 0x06006705 | 2         | 0.94%   |
| 0x06006704 | 2         | 0.94%   |
| 0xa0671    | 1         | 0.47%   |
| 0xa0653    | 1         | 0.47%   |
| 0x906e9    | 1         | 0.47%   |
| 0x906a4    | 1         | 0.47%   |
| 0x906a3    | 1         | 0.47%   |
| 0x90672    | 1         | 0.47%   |
| 0x6fd      | 1         | 0.47%   |
| 0x6fb      | 1         | 0.47%   |
| 0x506c9    | 1         | 0.47%   |
| 0x40661    | 1         | 0.47%   |
| 0x20652    | 1         | 0.47%   |
| 0x106ca    | 1         | 0.47%   |
| 0x10677    | 1         | 0.47%   |
| 0x0a50000d | 1         | 0.47%   |
| 0x0a50000c | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 18.23%  |
| Haswell          | 23        | 11.33%  |
| SandyBridge      | 21        | 10.34%  |
| Skylake          | 14        | 6.9%    |
| Penryn           | 12        | 5.91%   |
| TigerLake        | 11        | 5.42%   |
| Zen+             | 9         | 4.43%   |
| IvyBridge        | 9         | 4.43%   |
| CometLake        | 9         | 4.43%   |
| Westmere         | 7         | 3.45%   |
| Unknown          | 7         | 3.45%   |
| Icelake          | 6         | 2.96%   |
| Broadwell        | 6         | 2.96%   |
| Silvermont       | 5         | 2.46%   |
| Zen 2            | 4         | 1.97%   |
| Goldmont plus    | 4         | 1.97%   |
| Excavator        | 4         | 1.97%   |
| Zen 3            | 3         | 1.48%   |
| Piledriver       | 2         | 0.99%   |
| Core             | 2         | 0.99%   |
| Alderlake Hybrid | 2         | 0.99%   |
| Zen              | 1         | 0.49%   |
| Puma             | 1         | 0.49%   |
| K8 & K10 hybrid  | 1         | 0.49%   |
| Goldmont         | 1         | 0.49%   |
| Bonnell          | 1         | 0.49%   |
| Bobcat           | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 150       | 52.63%  |
| Nvidia | 85        | 29.82%  |
| AMD    | 50        | 17.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 5.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.48%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 3.14%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 3.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 2.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.44%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.09%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 1.74%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 1.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.74%   |
| Intel HD Graphics 620                                                                    | 5         | 1.74%   |
| Intel HD Graphics 530                                                                    | 5         | 1.74%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 1.39%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.39%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.39%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.39%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.39%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.05%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.05%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 1.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.05%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.05%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.05%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.7%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.7%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 35.47%  |
| Intel + Nvidia | 58        | 28.57%  |
| 1 x AMD        | 24        | 11.82%  |
| 1 x Nvidia     | 20        | 9.85%   |
| Intel + AMD    | 17        | 8.37%   |
| AMD + Nvidia   | 7         | 3.45%   |
| Other          | 2         | 0.99%   |
| 2 x AMD        | 2         | 0.99%   |
| 2 x Intel      | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 159       | 76.08%  |
| Proprietary | 42        | 20.1%   |
| Unknown     | 8         | 3.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 57.42%  |
| 1.01-2.0   | 36        | 17.22%  |
| 3.01-4.0   | 15        | 7.18%   |
| 0.51-1.0   | 15        | 7.18%   |
| 0.01-0.5   | 15        | 7.18%   |
| 5.01-6.0   | 5         | 2.39%   |
| 2.01-3.0   | 2         | 0.96%   |
| 7.01-8.0   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 41        | 18.98%  |
| Chimei Innolux          | 36        | 16.67%  |
| AU Optronics            | 35        | 16.2%   |
| BOE                     | 32        | 14.81%  |
| LG Display              | 23        | 10.65%  |
| Hewlett-Packard         | 13        | 6.02%   |
| Chi Mei Optoelectronics | 4         | 1.85%   |
| MSI                     | 3         | 1.39%   |
| Lenovo                  | 3         | 1.39%   |
| Dell                    | 3         | 1.39%   |
| Acer                    | 3         | 1.39%   |
| Philips                 | 2         | 0.93%   |
| PANDA                   | 2         | 0.93%   |
| Packard Bell            | 2         | 0.93%   |
| HKC                     | 2         | 0.93%   |
| BenQ                    | 2         | 0.93%   |
| Valve                   | 1         | 0.46%   |
| S2-Tek                  | 1         | 0.46%   |
| PKB                     | 1         | 0.46%   |
| Medion                  | 1         | 0.46%   |
| LG Philips              | 1         | 0.46%   |
| ITE                     | 1         | 0.46%   |
| HPN                     | 1         | 0.46%   |
| Goldstar                | 1         | 0.46%   |
| GDH                     | 1         | 0.46%   |
| ASUSTek Computer        | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 8         | 3.65%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 6         | 2.74%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 4         | 1.83%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 4         | 1.83%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 4         | 1.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 3         | 1.37%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch | 3         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 3         | 1.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 1.37%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 3         | 1.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.37%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.91%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 2         | 0.91%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.91%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch          | 2         | 0.91%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch           | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch      | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 2         | 0.91%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 2         | 0.91%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch       | 2         | 0.91%   |
| Acer V193HQV ACR0133 1366x768 410x230mm 18.5-inch                    | 2         | 0.91%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch | 1         | 0.46%   |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch    | 1         | 0.46%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1         | 0.46%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 92        | 45.32%  |
| 1366x768 (WXGA)    | 76        | 37.44%  |
| 1600x900 (HD+)     | 14        | 6.9%    |
| 1280x1024 (SXGA)   | 5         | 2.46%   |
| 3840x2160 (4K)     | 4         | 1.97%   |
| 1680x1050 (WSXGA+) | 3         | 1.48%   |
| 1280x800 (WXGA)    | 3         | 1.48%   |
| 800x1280           | 1         | 0.49%   |
| 3840x1100          | 1         | 0.49%   |
| 2560x1440 (QHD)    | 1         | 0.49%   |
| 1440x900 (WXGA+)   | 1         | 0.49%   |
| 1024x600           | 1         | 0.49%   |
| Unknown            | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 118       | 54.63%  |
| 23      | 15        | 6.94%   |
| 17      | 13        | 6.02%   |
| 14      | 11        | 5.09%   |
| 21      | 9         | 4.17%   |
| 24      | 8         | 3.7%    |
| 13      | 8         | 3.7%    |
| 20      | 6         | 2.78%   |
| 27      | 5         | 2.31%   |
| 18      | 4         | 1.85%   |
| 19      | 3         | 1.39%   |
| 11      | 3         | 1.39%   |
| Unknown | 3         | 1.39%   |
| 31      | 2         | 0.93%   |
| 22      | 2         | 0.93%   |
| 12      | 2         | 0.93%   |
| 52      | 1         | 0.46%   |
| 42      | 1         | 0.46%   |
| 10      | 1         | 0.46%   |
| 7       | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 61.79%  |
| 501-600     | 27        | 12.74%  |
| 401-500     | 21        | 9.91%   |
| 351-400     | 16        | 7.55%   |
| 201-300     | 9         | 4.25%   |
| Unknown     | 3         | 1.42%   |
| 601-700     | 2         | 0.94%   |
| 1001-1500   | 1         | 0.47%   |
| 901-1000    | 1         | 0.47%   |
| 1-100       | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 174       | 89.69%  |
| 16/10   | 9         | 4.64%   |
| 5/4     | 5         | 2.58%   |
| Unknown | 3         | 1.55%   |
| 3/2     | 1         | 0.52%   |
| 3.40    | 1         | 0.52%   |
| 0.67    | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 118       | 54.63%  |
| 201-250        | 31        | 14.35%  |
| 81-90          | 15        | 6.94%   |
| 151-200        | 10        | 4.63%   |
| 121-130        | 8         | 3.7%    |
| 141-150        | 7         | 3.24%   |
| 301-350        | 5         | 2.31%   |
| 51-60          | 4         | 1.85%   |
| 71-80          | 3         | 1.39%   |
| Unknown        | 3         | 1.39%   |
| 61-70          | 2         | 0.93%   |
| 351-500        | 2         | 0.93%   |
| 251-300        | 2         | 0.93%   |
| 131-140        | 2         | 0.93%   |
| More than 1000 | 1         | 0.46%   |
| 41-50          | 1         | 0.46%   |
| 1-40           | 1         | 0.46%   |
| 501-1000       | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 73        | 34.93%  |
| 121-160       | 65        | 31.1%   |
| 51-100        | 58        | 27.75%  |
| 161-240       | 5         | 2.39%   |
| 1-50          | 3         | 1.44%   |
| Unknown       | 3         | 1.44%   |
| More than 240 | 2         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 169       | 82.04%  |
| 2     | 29        | 14.08%  |
| 0     | 8         | 3.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 149       | 45.71%  |
| Intel                             | 72        | 22.09%  |
| Qualcomm Atheros                  | 43        | 13.19%  |
| Broadcom                          | 20        | 6.13%   |
| Ralink                            | 11        | 3.37%   |
| Ralink Technology                 | 10        | 3.07%   |
| Broadcom Limited                  | 5         | 1.53%   |
| MediaTek                          | 2         | 0.61%   |
| Ericsson Business Mobile Networks | 2         | 0.61%   |
| D-Link                            | 2         | 0.61%   |
| TP-Link                           | 1         | 0.31%   |
| Sierra Wireless                   | 1         | 0.31%   |
| Samsung Electronics               | 1         | 0.31%   |
| OPPO Electronics                  | 1         | 0.31%   |
| Microchip Technology              | 1         | 0.31%   |
| Marvell Technology Group          | 1         | 0.31%   |
| IMC Networks                      | 1         | 0.31%   |
| ICS Advent                        | 1         | 0.31%   |
| Huawei Technologies               | 1         | 0.31%   |
| D-Link System                     | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 98        | 26.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 10.64%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 13        | 3.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12        | 3.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 2.39%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 2.39%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 9         | 2.39%   |
| Broadcom BCM43142 802.11b/g/n                                          | 9         | 2.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 2.13%   |
| Ralink MT7601U Wireless Adapter                                        | 6         | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 6         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 1.06%   |
| Intel Wireless 7265                                                    | 4         | 1.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3         | 0.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.8%    |
| Intel Wireless 8265 / 8275                                             | 3         | 0.8%    |
| Intel Wireless 8260                                                    | 3         | 0.8%    |
| Intel WiFi Link 5100                                                   | 3         | 0.8%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.53%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.53%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2         | 0.53%   |
| Intel Wireless 7260                                                    | 2         | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.53%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 0.53%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.53%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 66        | 33.67%  |
| Qualcomm Atheros                  | 40        | 20.41%  |
| Realtek Semiconductor             | 39        | 19.9%   |
| Broadcom                          | 16        | 8.16%   |
| Ralink                            | 11        | 5.61%   |
| Ralink Technology                 | 10        | 5.1%    |
| Broadcom Limited                  | 5         | 2.55%   |
| MediaTek                          | 2         | 1.02%   |
| D-Link                            | 2         | 1.02%   |
| TP-Link                           | 1         | 0.51%   |
| Sierra Wireless                   | 1         | 0.51%   |
| IMC Networks                      | 1         | 0.51%   |
| Ericsson Business Mobile Networks | 1         | 0.51%   |
| D-Link System                     | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 6.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 6.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 4.57%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 4.57%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 4.57%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 4.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 4.06%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 3.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 3.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 2.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.03%   |
| Intel Wireless 7265                                            | 4         | 2.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3         | 1.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.52%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.52%   |
| Intel Wireless 8260                                            | 3         | 1.52%   |
| Intel WiFi Link 5100                                           | 3         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.02%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.02%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2         | 1.02%   |
| Intel Wireless 7260                                            | 2         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.02%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.02%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.02%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.02%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.02%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.02%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.51%   |
| Sierra Wireless EM7455                                         | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 141       | 79.66%  |
| Intel                    | 20        | 11.3%   |
| Qualcomm Atheros         | 5         | 2.82%   |
| Broadcom                 | 5         | 2.82%   |
| Samsung Electronics      | 1         | 0.56%   |
| OPPO Electronics         | 1         | 0.56%   |
| Microchip Technology     | 1         | 0.56%   |
| Marvell Technology Group | 1         | 0.56%   |
| ICS Advent               | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 98        | 55.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 22.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 1.12%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.12%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.12%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.56%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.56%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 1         | 0.56%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 1         | 0.56%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.56%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.56%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 0.56%   |
| Intel 82562V-2 10/100 Network Connection                               | 1         | 0.56%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1         | 0.56%   |
| Huawei TIT-L01                                                         | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 180       | 50.85%  |
| Ethernet | 173       | 48.87%  |
| Modem    | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 150       | 71.43%  |
| Ethernet | 60        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 144       | 70.59%  |
| 1     | 58        | 28.43%  |
| 0     | 2         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 203       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 37.25%  |
| Qualcomm Atheros Communications | 27        | 17.65%  |
| Realtek Semiconductor           | 24        | 15.69%  |
| Lite-On Technology              | 11        | 7.19%   |
| Broadcom                        | 8         | 5.23%   |
| IMC Networks                    | 7         | 4.58%   |
| Ralink                          | 6         | 3.92%   |
| Cambridge Silicon Radio         | 4         | 2.61%   |
| Toshiba                         | 3         | 1.96%   |
| Foxconn / Hon Hai               | 3         | 1.96%   |
| Realtek                         | 1         | 0.65%   |
| Hewlett-Packard                 | 1         | 0.65%   |
| Dell                            | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 21        | 13.73%  |
| Intel Bluetooth wireless interface                  | 19        | 12.42%  |
| Realtek Bluetooth Radio                             | 18        | 11.76%  |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 9.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 7.84%   |
| Ralink RT3290 Bluetooth                             | 6         | 3.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 3.27%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.27%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.61%   |
| Lite-On Bluetooth Device                            | 4         | 2.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 2.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 1.96%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.96%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.31%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.31%   |
| Lite-On BCM43142A0                                  | 2         | 1.31%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.31%   |
| Intel Bluetooth Device                              | 2         | 1.31%   |
| IMC Networks Wireless_Device                        | 2         | 1.31%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.31%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.31%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.65%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.65%   |
| Toshiba BCM43142A0                                  | 1         | 0.65%   |
| Realtek Bluetooth Radio                             | 1         | 0.65%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.65%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.65%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.65%   |
| Broadcom HP Portable Valentine                      | 1         | 0.65%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.65%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 173       | 66.54%  |
| Nvidia                    | 42        | 16.15%  |
| AMD                       | 37        | 14.23%  |
| C-Media Electronics       | 3         | 1.15%   |
| Xiamen VBeT Electronics   | 1         | 0.38%   |
| Sennheiser Communications | 1         | 0.38%   |
| Razer USA                 | 1         | 0.38%   |
| Lenovo                    | 1         | 0.38%   |
| JMTek                     | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 5.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 4.68%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 4.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 4.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 3.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 3.34%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 3.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 2.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.01%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.01%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.67%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.34%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1%      |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1%      |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia Audio device                                                                               | 2         | 0.67%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 27.85%  |
| SK hynix            | 31        | 19.62%  |
| Micron Technology   | 20        | 12.66%  |
| Team                | 15        | 9.49%   |
| A-DATA Technology   | 9         | 5.7%    |
| Unknown             | 8         | 5.06%   |
| Crucial             | 5         | 3.16%   |
| Nanya Technology    | 4         | 2.53%   |
| Ramaxel Technology  | 3         | 1.9%    |
| Kingston            | 3         | 1.9%    |
| Elpida              | 3         | 1.9%    |
| TwinMOS             | 2         | 1.27%   |
| Toshiba             | 2         | 1.27%   |
| Unknown (ABCD)      | 1         | 0.63%   |
| Transcend           | 1         | 0.63%   |
| PNY                 | 1         | 0.63%   |
| Patriot             | 1         | 0.63%   |
| Melco               | 1         | 0.63%   |
| Hikvision           | 1         | 0.63%   |
| GOODRAM             | 1         | 0.63%   |
| ASint Technology    | 1         | 0.63%   |
| 0BBA00000000        | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 4         | 2.42%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s           | 3         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 3         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 3         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 3         | 1.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 1.82%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                    | 3         | 1.82%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s          | 2         | 1.21%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s           | 2         | 1.21%   |
| Team RAM TEAMGROUP-SD4-3200 8GB Row Of Chips DDR4 2400MT/s     | 2         | 1.21%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 2         | 1.21%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s          | 2         | 1.21%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s           | 2         | 1.21%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s       | 2         | 1.21%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s       | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 2         | 1.21%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 1.21%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.21%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB Row Of Chips DDR4 3200MT/s | 2         | 1.21%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s        | 2         | 1.21%   |
| Micron RAM MT40A512M16TB-062E:R 4GB SODIMM DDR4 3200MT/s       | 2         | 1.21%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 2         | 1.21%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3                               | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                  | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                         | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.61%   |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s               | 1         | 0.61%   |
| TwinMOS RAM 9D7TBNZB-TATP 4096MB DIMM DDR3 1066MT/s            | 1         | 0.61%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s              | 1         | 0.61%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s            | 1         | 0.61%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s            | 1         | 0.61%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 71        | 57.26%  |
| DDR3    | 36        | 29.03%  |
| DDR2    | 5         | 4.03%   |
| SDRAM   | 4         | 3.23%   |
| LPDDR4  | 3         | 2.42%   |
| LPDDR3  | 2         | 1.61%   |
| DDR5    | 2         | 1.61%   |
| Unknown | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 93        | 73.81%  |
| DIMM         | 20        | 15.87%  |
| Row Of Chips | 12        | 9.52%   |
| Chip         | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 50        | 33.78%  |
| 4096  | 49        | 33.11%  |
| 16384 | 22        | 14.86%  |
| 2048  | 16        | 10.81%  |
| 32768 | 8         | 5.41%   |
| 1024  | 3         | 2.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 31        | 21.83%  |
| 2667    | 31        | 21.83%  |
| 1600    | 20        | 14.08%  |
| 2400    | 13        | 9.15%   |
| 1334    | 10        | 7.04%   |
| 1333    | 6         | 4.23%   |
| 1066    | 4         | 2.82%   |
| 3266    | 3         | 2.11%   |
| 2133    | 3         | 2.11%   |
| 1867    | 3         | 2.11%   |
| 667     | 3         | 2.11%   |
| 8400    | 2         | 1.41%   |
| 4800    | 2         | 1.41%   |
| 4199    | 2         | 1.41%   |
| Unknown | 2         | 1.41%   |
| 49926   | 1         | 0.7%    |
| 3800    | 1         | 0.7%    |
| 3000    | 1         | 0.7%    |
| 1648    | 1         | 0.7%    |
| 1067    | 1         | 0.7%    |
| 975     | 1         | 0.7%    |
| 800     | 1         | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 75%     |
| Seiko Epson     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP LaserJet P1005       | 2         | 50%     |
| Seiko Epson L365 Series | 1         | 25%     |
| HP DeskJet 5810 series  | 1         | 25%     |

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
| Chicony Electronics                    | 35        | 22.88%  |
| IMC Networks                           | 20        | 13.07%  |
| Realtek Semiconductor                  | 17        | 11.11%  |
| Bison Electronics                      | 13        | 8.5%    |
| Microdia                               | 12        | 7.84%   |
| Suyin                                  | 9         | 5.88%   |
| Syntek                                 | 8         | 5.23%   |
| Sunplus Innovation Technology          | 7         | 4.58%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.58%   |
| Quanta                                 | 5         | 3.27%   |
| Luxvisions Innotech Limited            | 5         | 3.27%   |
| Lite-On Technology                     | 5         | 3.27%   |
| Silicon Motion                         | 1         | 0.65%   |
| Samsung Electronics                    | 1         | 0.65%   |
| Ricoh                                  | 1         | 0.65%   |
| Lenovo                                 | 1         | 0.65%   |
| Importek                               | 1         | 0.65%   |
| Cubeternet                             | 1         | 0.65%   |
| Apple                                  | 1         | 0.65%   |
| Alcor Micro                            | 1         | 0.65%   |
| Acer                                   | 1         | 0.65%   |
| A4Tech                                 | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 5.88%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 8         | 5.23%   |
| Bison Integrated Camera                                     | 7         | 4.58%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 3.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 5         | 3.27%   |
| IMC Networks Integrated Camera                              | 5         | 3.27%   |
| Chicony HD WebCam                                           | 5         | 3.27%   |
| Syntek Integrated Camera                                    | 4         | 2.61%   |
| Realtek USB Camera                                          | 4         | 2.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 4         | 2.61%   |
| Syntek EasyCamera                                           | 3         | 1.96%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 1.96%   |
| Realtek Integrated_Webcam_HD                                | 3         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 3         | 1.96%   |
| Microdia Integrated_Webcam_HD                               | 3         | 1.96%   |
| Lite-On Integrated Camera                                   | 3         | 1.96%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.96%   |
| Suyin Integrated_Webcam_HD                                  | 2         | 1.31%   |
| Suyin HP TrueVision HD                                      | 2         | 1.31%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.31%   |
| Realtek EasyCamera                                          | 2         | 1.31%   |
| Quanta HD WebCam                                            | 2         | 1.31%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.31%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.31%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.31%   |
| Chicony EasyCamera                                          | 2         | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.31%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.31%   |
| Bison HD Webcam                                             | 2         | 1.31%   |
| Bison EasyCamera                                            | 2         | 1.31%   |
| Syntek Integrated RGB Camera                                | 1         | 0.65%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.65%   |
| Suyin Laptop_Integrated_Webcam_2HDM                         | 1         | 0.65%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.65%   |
| Suyin HD WebCam                                             | 1         | 0.65%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.65%   |
| Sunplus HD User Facing                                      | 1         | 0.65%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.65%   |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 50%     |
| Shenzhen Goodix Technology | 2         | 16.67%  |
| LighTuning Technology      | 2         | 16.67%  |
| Upek                       | 1         | 8.33%   |
| Synaptics                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 16.67%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                        | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner                   | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Alcor Micro | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 156       | 72.22%  |
| 1     | 48        | 22.22%  |
| 3     | 5         | 2.31%   |
| 2     | 5         | 2.31%   |
| 5     | 1         | 0.46%   |
| 4     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 20        | 26.67%  |
| Net/wireless             | 15        | 20%     |
| Fingerprint reader       | 12        | 16%     |
| Bluetooth                | 8         | 10.67%  |
| Communication controller | 5         | 6.67%   |
| Chipcard                 | 4         | 5.33%   |
| Storage                  | 2         | 2.67%   |
| Sound                    | 2         | 2.67%   |
| Net/ethernet             | 2         | 2.67%   |
| Camera                   | 2         | 2.67%   |
| Network                  | 1         | 1.33%   |
| Multimedia controller    | 1         | 1.33%   |
| Card reader              | 1         | 1.33%   |

