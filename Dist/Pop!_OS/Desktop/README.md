Pop!_OS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 5805

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4N72-E                     | [815b251540](https://linux-hardware.org/?probe=815b251540) | Feb 02, 2024 |
| Dell          | 0V8WGR A00                  | [9762a633ab](https://linux-hardware.org/?probe=9762a633ab) | Feb 01, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | [a5425cfc63](https://linux-hardware.org/?probe=a5425cfc63) | Feb 01, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | [67539ba367](https://linux-hardware.org/?probe=67539ba367) | Feb 01, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | [54beeb17dc](https://linux-hardware.org/?probe=54beeb17dc) | Jan 31, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | [65272ffc77](https://linux-hardware.org/?probe=65272ffc77) | Jan 31, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [5222452ba4](https://linux-hardware.org/?probe=5222452ba4) | Jan 30, 2024 |
| Gigabyte      | Z690 UD DDR4                | [454433be44](https://linux-hardware.org/?probe=454433be44) | Jan 30, 2024 |
| Alienware     | 07HV66 A01                  | [732d349380](https://linux-hardware.org/?probe=732d349380) | Jan 29, 2024 |
| SZMZ          | X99-S3                      | [acf24ed760](https://linux-hardware.org/?probe=acf24ed760) | Jan 29, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [4e6d22c388](https://linux-hardware.org/?probe=4e6d22c388) | Jan 28, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [a7826ae1af](https://linux-hardware.org/?probe=a7826ae1af) | Jan 28, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f80e16d62d](https://linux-hardware.org/?probe=f80e16d62d) | Jan 28, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [d5f5ab4b3f](https://linux-hardware.org/?probe=d5f5ab4b3f) | Jan 27, 2024 |
| ASUSTek       | Z170-A                      | [0f1f062eda](https://linux-hardware.org/?probe=0f1f062eda) | Jan 27, 2024 |
| Dell          | 0DF42J A00                  | [f0ac1844ad](https://linux-hardware.org/?probe=f0ac1844ad) | Jan 27, 2024 |
| ASUSTek       | PRIME A320M-K               | [b1d979bcb3](https://linux-hardware.org/?probe=b1d979bcb3) | Jan 27, 2024 |
| Foxconn       | 2ABF                        | [91412d213a](https://linux-hardware.org/?probe=91412d213a) | Jan 26, 2024 |
| Gigabyte      | Z97X-SLI-CF                 | [1eb12a361c](https://linux-hardware.org/?probe=1eb12a361c) | Jan 26, 2024 |
| ASUSTek       | P5QPL-AM                    | [1f2bb560a8](https://linux-hardware.org/?probe=1f2bb560a8) | Jan 26, 2024 |
| ASRock        | B550M-HDV                   | [afbea953be](https://linux-hardware.org/?probe=afbea953be) | Jan 26, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [068df25275](https://linux-hardware.org/?probe=068df25275) | Jan 26, 2024 |
| Huanan        | X99-8M-F V1.4               | [65388b76e1](https://linux-hardware.org/?probe=65388b76e1) | Jan 25, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [4cedf6ee3a](https://linux-hardware.org/?probe=4cedf6ee3a) | Jan 25, 2024 |
| Gigabyte      | X99-Gaming 5P               | [e306ef8710](https://linux-hardware.org/?probe=e306ef8710) | Jan 24, 2024 |
| MSI           | B460M PRO-VDH WIFI          | [8b3e1a6d31](https://linux-hardware.org/?probe=8b3e1a6d31) | Jan 24, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | [340fdb1832](https://linux-hardware.org/?probe=340fdb1832) | Jan 24, 2024 |
| MSI           | H55M-E33                    | [2935476b48](https://linux-hardware.org/?probe=2935476b48) | Jan 23, 2024 |
| MSI           | B350M MORTAR                | [f728e7ad76](https://linux-hardware.org/?probe=f728e7ad76) | Jan 22, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [ed9635f427](https://linux-hardware.org/?probe=ed9635f427) | Jan 22, 2024 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [d248b6e5a9](https://linux-hardware.org/?probe=d248b6e5a9) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [66cf4b0b5a](https://linux-hardware.org/?probe=66cf4b0b5a) | Jan 21, 2024 |
| MSI           | B450 TOMAHAWK MAX           | [41a62ec1d4](https://linux-hardware.org/?probe=41a62ec1d4) | Jan 21, 2024 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [d36c2b07fd](https://linux-hardware.org/?probe=d36c2b07fd) | Jan 20, 2024 |
| MSI           | PRO X670-P WIFI             | [a0637d4400](https://linux-hardware.org/?probe=a0637d4400) | Jan 20, 2024 |
| Dell          | 0GDG8Y A00                  | [8f41b6b7f9](https://linux-hardware.org/?probe=8f41b6b7f9) | Jan 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [af503dbdd1](https://linux-hardware.org/?probe=af503dbdd1) | Jan 20, 2024 |
| ASUSTek       | H97M-E                      | [d6fe598f33](https://linux-hardware.org/?probe=d6fe598f33) | Jan 20, 2024 |
| Dell          | 0TTDMJ A00                  | [e5d9f41477](https://linux-hardware.org/?probe=e5d9f41477) | Jan 19, 2024 |
| Gigabyte      | B450 AORUS M                | [06cced7a39](https://linux-hardware.org/?probe=06cced7a39) | Jan 18, 2024 |
| ASRock        | H670 PG Riptide             | [d1a75ad00a](https://linux-hardware.org/?probe=d1a75ad00a) | Jan 18, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [42e7298c19](https://linux-hardware.org/?probe=42e7298c19) | Jan 17, 2024 |
| MSI           | PRO X670-P WIFI             | [3b62b0b588](https://linux-hardware.org/?probe=3b62b0b588) | Jan 17, 2024 |
| ASRock        | FM2A68M-HD+                 | [8ba2ab423f](https://linux-hardware.org/?probe=8ba2ab423f) | Jan 17, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [a5bd71f259](https://linux-hardware.org/?probe=a5bd71f259) | Jan 17, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [48399b3fc4](https://linux-hardware.org/?probe=48399b3fc4) | Jan 16, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | [be6d425c5a](https://linux-hardware.org/?probe=be6d425c5a) | Jan 16, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | [58d64e6a70](https://linux-hardware.org/?probe=58d64e6a70) | Jan 16, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [adb9343764](https://linux-hardware.org/?probe=adb9343764) | Jan 16, 2024 |
| MSI           | PRO B650M-A WIFI            | [cb4fc4f2da](https://linux-hardware.org/?probe=cb4fc4f2da) | Jan 16, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [8e26115f48](https://linux-hardware.org/?probe=8e26115f48) | Jan 16, 2024 |
| MSI           | Z68A-G43                    | [9ab9ae7952](https://linux-hardware.org/?probe=9ab9ae7952) | Jan 15, 2024 |
| MSI           | PRO B650M-A WIFI            | [75e74c82af](https://linux-hardware.org/?probe=75e74c82af) | Jan 15, 2024 |
| Dell          | 0J8H4R A00                  | [ce34102531](https://linux-hardware.org/?probe=ce34102531) | Jan 15, 2024 |
| ASUSTek       | P8P67 LE                    | [8e77609cb6](https://linux-hardware.org/?probe=8e77609cb6) | Jan 14, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | [fe987e391e](https://linux-hardware.org/?probe=fe987e391e) | Jan 14, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [08074470dd](https://linux-hardware.org/?probe=08074470dd) | Jan 13, 2024 |
| Gigabyte      | 970A-DS3P                   | [1b6a4a4985](https://linux-hardware.org/?probe=1b6a4a4985) | Jan 13, 2024 |
| Gigabyte      | H610M H DDR4                | [7ad8786f92](https://linux-hardware.org/?probe=7ad8786f92) | Jan 13, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [dbcc44707c](https://linux-hardware.org/?probe=dbcc44707c) | Jan 13, 2024 |
| Dell          | 04Y8V0 A02                  | [e5e36f25f0](https://linux-hardware.org/?probe=e5e36f25f0) | Jan 12, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | [50ff1c2eb6](https://linux-hardware.org/?probe=50ff1c2eb6) | Jan 12, 2024 |
| Gigabyte      | B450M S2H                   | [5ff6a8a29a](https://linux-hardware.org/?probe=5ff6a8a29a) | Jan 12, 2024 |
| Gigabyte      | B450M S2H                   | [ea8bf22b21](https://linux-hardware.org/?probe=ea8bf22b21) | Jan 12, 2024 |
| MSI           | MPG Z590 GAMING PLUS        | [b9fe694efb](https://linux-hardware.org/?probe=b9fe694efb) | Jan 12, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [4ec27cc26b](https://linux-hardware.org/?probe=4ec27cc26b) | Jan 10, 2024 |
| Gigabyte      | H610M S2H                   | [c2a2c8a049](https://linux-hardware.org/?probe=c2a2c8a049) | Jan 09, 2024 |
| Gigabyte      | H610M S2H                   | [8a7432cd09](https://linux-hardware.org/?probe=8a7432cd09) | Jan 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [50ff3c4620](https://linux-hardware.org/?probe=50ff3c4620) | Jan 08, 2024 |
| HP            | 8434 11                     | [3c7307cadb](https://linux-hardware.org/?probe=3c7307cadb) | Jan 08, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | [f63753ff07](https://linux-hardware.org/?probe=f63753ff07) | Jan 08, 2024 |
| MSI           | B250M PRO-VD                | [46148b3b7a](https://linux-hardware.org/?probe=46148b3b7a) | Jan 07, 2024 |
| Unknown       | Unknown                     | [8f7440e4aa](https://linux-hardware.org/?probe=8f7440e4aa) | Jan 06, 2024 |
| ASRock        | B550M-HDV                   | [b247cc09d2](https://linux-hardware.org/?probe=b247cc09d2) | Jan 06, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [cae755fe43](https://linux-hardware.org/?probe=cae755fe43) | Jan 06, 2024 |
| MSI           | B560M PRO-E                 | [0fd8636acb](https://linux-hardware.org/?probe=0fd8636acb) | Jan 05, 2024 |
| ASRock        | X470 Taichi Ultimate        | [204ff304cf](https://linux-hardware.org/?probe=204ff304cf) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [18ebf2cf02](https://linux-hardware.org/?probe=18ebf2cf02) | Jan 04, 2024 |
| Gigabyte      | H81M-D2V                    | [1c7845bdee](https://linux-hardware.org/?probe=1c7845bdee) | Jan 04, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | [4c587bc867](https://linux-hardware.org/?probe=4c587bc867) | Jan 04, 2024 |
| ASUSTek       | Z87-K                       | [4bd9034918](https://linux-hardware.org/?probe=4bd9034918) | Jan 04, 2024 |
| ASUSTek       | PRIME Z390-A                | [8bb04983f7](https://linux-hardware.org/?probe=8bb04983f7) | Jan 02, 2024 |
| ASUSTek       | Z87-K                       | [3f1ffd98e9](https://linux-hardware.org/?probe=3f1ffd98e9) | Jan 02, 2024 |
| Unknown       | X99H                        | [61c57cb006](https://linux-hardware.org/?probe=61c57cb006) | Jan 01, 2024 |
| ASUSTek       | P6T                         | [7b5a14566d](https://linux-hardware.org/?probe=7b5a14566d) | Jan 01, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | [58557ae7c7](https://linux-hardware.org/?probe=58557ae7c7) | Jan 01, 2024 |
| Gigabyte      | H97N-WIFI                   | [eb47ce9900](https://linux-hardware.org/?probe=eb47ce9900) | Jan 01, 2024 |
| ASUSTek       | M4N72-E                     | [7d21517ee3](https://linux-hardware.org/?probe=7d21517ee3) | Dec 31, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa478c5226](https://linux-hardware.org/?probe=fa478c5226) | Dec 31, 2023 |
| ASUSTek       | PRIME Z690-A                | [faf34bf75f](https://linux-hardware.org/?probe=faf34bf75f) | Dec 30, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b1b1057a4b](https://linux-hardware.org/?probe=b1b1057a4b) | Dec 30, 2023 |
| HP            | 802E                        | [a519d89c9e](https://linux-hardware.org/?probe=a519d89c9e) | Dec 29, 2023 |
| MSI           | MEG X570S ACE MAX           | [e0e92720cb](https://linux-hardware.org/?probe=e0e92720cb) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [94b90795bb](https://linux-hardware.org/?probe=94b90795bb) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2d2449e5d7](https://linux-hardware.org/?probe=2d2449e5d7) | Dec 28, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [f52a281bd2](https://linux-hardware.org/?probe=f52a281bd2) | Dec 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [61116b6285](https://linux-hardware.org/?probe=61116b6285) | Dec 27, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [0927068d89](https://linux-hardware.org/?probe=0927068d89) | Dec 27, 2023 |
| ASRock        | B450M Pro4                  | [77d5e43585](https://linux-hardware.org/?probe=77d5e43585) | Dec 26, 2023 |
| SZMZ          | X99-S3                      | [85c9abf0f3](https://linux-hardware.org/?probe=85c9abf0f3) | Dec 26, 2023 |
| ASRock        | B450M Pro4 R2.0             | [96aa7493e0](https://linux-hardware.org/?probe=96aa7493e0) | Dec 25, 2023 |
| Gigabyte      | H510M H                     | [f9cf1edcee](https://linux-hardware.org/?probe=f9cf1edcee) | Dec 24, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [8decde512f](https://linux-hardware.org/?probe=8decde512f) | Dec 23, 2023 |
| Gigabyte      | H87M-HD3                    | [00781519db](https://linux-hardware.org/?probe=00781519db) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [de502eec48](https://linux-hardware.org/?probe=de502eec48) | Dec 22, 2023 |
| Alienware     | 0K9TKY A00                  | [ec6847b7f2](https://linux-hardware.org/?probe=ec6847b7f2) | Dec 22, 2023 |
| Gigabyte      | H610M S2H                   | [6c554a9668](https://linux-hardware.org/?probe=6c554a9668) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9515cb0c90](https://linux-hardware.org/?probe=9515cb0c90) | Dec 22, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [b49d16daf5](https://linux-hardware.org/?probe=b49d16daf5) | Dec 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | [1b8100314e](https://linux-hardware.org/?probe=1b8100314e) | Dec 21, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [67098aebca](https://linux-hardware.org/?probe=67098aebca) | Dec 20, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | [d2ed93003e](https://linux-hardware.org/?probe=d2ed93003e) | Dec 20, 2023 |
| System76      | Thelio thelio-r3            | [86b686b3cf](https://linux-hardware.org/?probe=86b686b3cf) | Dec 19, 2023 |
| MSI           | Z77A-G45                    | [047feb8e76](https://linux-hardware.org/?probe=047feb8e76) | Dec 19, 2023 |
| Biostar       | A320MH                      | [9ec714a02b](https://linux-hardware.org/?probe=9ec714a02b) | Dec 19, 2023 |
| ASUSTek       | PRIME Z390-P                | [29169b6700](https://linux-hardware.org/?probe=29169b6700) | Dec 19, 2023 |
| ASRock        | B450M/ac                    | [1375b869d1](https://linux-hardware.org/?probe=1375b869d1) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [0759f6c04f](https://linux-hardware.org/?probe=0759f6c04f) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [939c3a4be6](https://linux-hardware.org/?probe=939c3a4be6) | Dec 19, 2023 |
| Gigabyte      | Z590I VISION D              | [92531d60e9](https://linux-hardware.org/?probe=92531d60e9) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [8efe53adcb](https://linux-hardware.org/?probe=8efe53adcb) | Dec 18, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [2e837d2a52](https://linux-hardware.org/?probe=2e837d2a52) | Dec 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [85358f7505](https://linux-hardware.org/?probe=85358f7505) | Dec 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [825b7230bc](https://linux-hardware.org/?probe=825b7230bc) | Dec 18, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | [2d78f7257c](https://linux-hardware.org/?probe=2d78f7257c) | Dec 17, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [3a10e23529](https://linux-hardware.org/?probe=3a10e23529) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [b9029b0475](https://linux-hardware.org/?probe=b9029b0475) | Dec 17, 2023 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | [47bc0a39bf](https://linux-hardware.org/?probe=47bc0a39bf) | Dec 17, 2023 |
| Dell          | 0J8H4R A00                  | [4f6031c3b2](https://linux-hardware.org/?probe=4f6031c3b2) | Dec 16, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [51a1a58859](https://linux-hardware.org/?probe=51a1a58859) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [976a5e3ec2](https://linux-hardware.org/?probe=976a5e3ec2) | Dec 16, 2023 |
| Gigabyte      | H410M H V3                  | [7da400b028](https://linux-hardware.org/?probe=7da400b028) | Dec 16, 2023 |
| Dell          | 0J8H4R A00                  | [17fcc16842](https://linux-hardware.org/?probe=17fcc16842) | Dec 14, 2023 |
| Intel         | DH61BF AAG81311-101         | [9d6455339e](https://linux-hardware.org/?probe=9d6455339e) | Dec 14, 2023 |
| ASUSTek       | P7P55D-E                    | [3280eaaea1](https://linux-hardware.org/?probe=3280eaaea1) | Dec 14, 2023 |
| ASUSTek       | M4A79XTD EVO                | [b7bef0ec08](https://linux-hardware.org/?probe=b7bef0ec08) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [c132a249e4](https://linux-hardware.org/?probe=c132a249e4) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [913708c3f0](https://linux-hardware.org/?probe=913708c3f0) | Dec 13, 2023 |
| ASUSTek       | P7P55D-E                    | [3f2ed65cf0](https://linux-hardware.org/?probe=3f2ed65cf0) | Dec 13, 2023 |
| Gigabyte      | Q87M-MK                     | [25a03e3488](https://linux-hardware.org/?probe=25a03e3488) | Dec 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | [ca9ceaf4a0](https://linux-hardware.org/?probe=ca9ceaf4a0) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [efba53721c](https://linux-hardware.org/?probe=efba53721c) | Dec 11, 2023 |
| MSI           | H610M BOMBER DDR4           | [7ea9e34c4c](https://linux-hardware.org/?probe=7ea9e34c4c) | Dec 11, 2023 |
| ASRock        | B650 PG Lightning           | [7b2a48d751](https://linux-hardware.org/?probe=7b2a48d751) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | [90fce6c777](https://linux-hardware.org/?probe=90fce6c777) | Dec 11, 2023 |
| ASRock        | B450 Steel Legend           | [18df358540](https://linux-hardware.org/?probe=18df358540) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | [6c83c2bec6](https://linux-hardware.org/?probe=6c83c2bec6) | Dec 11, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [ad9ec5bc5b](https://linux-hardware.org/?probe=ad9ec5bc5b) | Dec 10, 2023 |
| HP            | 2AF7                        | [e7a6fd7a82](https://linux-hardware.org/?probe=e7a6fd7a82) | Dec 10, 2023 |
| ASRock        | B760M PG Riptide            | [ef47cf6d30](https://linux-hardware.org/?probe=ef47cf6d30) | Dec 10, 2023 |
| MSI           | B350M GAMING PRO            | [981334c448](https://linux-hardware.org/?probe=981334c448) | Dec 08, 2023 |
| ASRock        | A520M-HDV                   | [8c7f7f9b91](https://linux-hardware.org/?probe=8c7f7f9b91) | Dec 08, 2023 |
| MSI           | Z270 GAMING M3              | [68bd979ae6](https://linux-hardware.org/?probe=68bd979ae6) | Dec 07, 2023 |
| ASRock        | B450M/ac                    | [895b027832](https://linux-hardware.org/?probe=895b027832) | Dec 07, 2023 |
| MSI           | MEG X570 ACE                | [18c7fcf897](https://linux-hardware.org/?probe=18c7fcf897) | Dec 06, 2023 |
| MSI           | B550M PRO-VDH               | [49e317cfc8](https://linux-hardware.org/?probe=49e317cfc8) | Dec 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eeb3db62db](https://linux-hardware.org/?probe=eeb3db62db) | Dec 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5160cc41b9](https://linux-hardware.org/?probe=5160cc41b9) | Dec 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [be8fd86ad0](https://linux-hardware.org/?probe=be8fd86ad0) | Dec 05, 2023 |
| ASRock        | B550M-HDV                   | [4ae43e0af1](https://linux-hardware.org/?probe=4ae43e0af1) | Dec 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [973530edc6](https://linux-hardware.org/?probe=973530edc6) | Dec 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [67d1badc93](https://linux-hardware.org/?probe=67d1badc93) | Dec 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [1f66aaf874](https://linux-hardware.org/?probe=1f66aaf874) | Dec 05, 2023 |
| ASUSTek       | X99-A/USB                   | [474cae9549](https://linux-hardware.org/?probe=474cae9549) | Dec 05, 2023 |
| Dell          | 0HY9JP A00                  | [c5bdb91907](https://linux-hardware.org/?probe=c5bdb91907) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | [98567fb8e0](https://linux-hardware.org/?probe=98567fb8e0) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | [00da9d31bd](https://linux-hardware.org/?probe=00da9d31bd) | Dec 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c7a7d555a6](https://linux-hardware.org/?probe=c7a7d555a6) | Dec 02, 2023 |
| Dell          | 0HY9JP A00                  | [0714d912db](https://linux-hardware.org/?probe=0714d912db) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | [7488b95d21](https://linux-hardware.org/?probe=7488b95d21) | Dec 02, 2023 |
| ASUSTek       | P5Q                         | [31ac2917e3](https://linux-hardware.org/?probe=31ac2917e3) | Dec 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [92a2b35bc8](https://linux-hardware.org/?probe=92a2b35bc8) | Dec 01, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | [53bc6eba90](https://linux-hardware.org/?probe=53bc6eba90) | Dec 01, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | [11e0af1d39](https://linux-hardware.org/?probe=11e0af1d39) | Nov 30, 2023 |
| HP            | 8299                        | [7d01726c17](https://linux-hardware.org/?probe=7d01726c17) | Nov 30, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [e43b293d0e](https://linux-hardware.org/?probe=e43b293d0e) | Nov 30, 2023 |
| MSI           | A320M-A PRO                 | [43e0c71549](https://linux-hardware.org/?probe=43e0c71549) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | [707797695c](https://linux-hardware.org/?probe=707797695c) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | [a05b28f5b1](https://linux-hardware.org/?probe=a05b28f5b1) | Nov 29, 2023 |
| HP            | 0B40h                       | [9875f70785](https://linux-hardware.org/?probe=9875f70785) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [977a25b18b](https://linux-hardware.org/?probe=977a25b18b) | Nov 29, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [a193c9a207](https://linux-hardware.org/?probe=a193c9a207) | Nov 29, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [f502294656](https://linux-hardware.org/?probe=f502294656) | Nov 28, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [1f793dc2d3](https://linux-hardware.org/?probe=1f793dc2d3) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [78e9bae926](https://linux-hardware.org/?probe=78e9bae926) | Nov 26, 2023 |
| Gigabyte      | X570 AORUS PRO              | [d6f36dff1d](https://linux-hardware.org/?probe=d6f36dff1d) | Nov 26, 2023 |
| Dell          | 0RY206                      | [7115b05660](https://linux-hardware.org/?probe=7115b05660) | Nov 25, 2023 |
| MSI           | Z87-S02                     | [2d40c55867](https://linux-hardware.org/?probe=2d40c55867) | Nov 25, 2023 |
| Gigabyte      | H410M S2 V2                 | [c6955988fb](https://linux-hardware.org/?probe=c6955988fb) | Nov 25, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ab26a80bc5](https://linux-hardware.org/?probe=ab26a80bc5) | Nov 25, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [98b666cd95](https://linux-hardware.org/?probe=98b666cd95) | Nov 24, 2023 |
| MSI           | MEG X570 ACE                | [9e25aa3d8f](https://linux-hardware.org/?probe=9e25aa3d8f) | Nov 24, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3730101bfb](https://linux-hardware.org/?probe=3730101bfb) | Nov 24, 2023 |
| HP            | 2AF7                        | [5594c88f44](https://linux-hardware.org/?probe=5594c88f44) | Nov 23, 2023 |
| ASUSTek       | Z170M-PLUS                  | [b6e4999e4f](https://linux-hardware.org/?probe=b6e4999e4f) | Nov 22, 2023 |
| MSI           | B350M PRO-VDH               | [b8a0ad5987](https://linux-hardware.org/?probe=b8a0ad5987) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [21257dcbad](https://linux-hardware.org/?probe=21257dcbad) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [b69760e673](https://linux-hardware.org/?probe=b69760e673) | Nov 22, 2023 |
| Gigabyte      | H510M S2H V2                | [00c164e154](https://linux-hardware.org/?probe=00c164e154) | Nov 21, 2023 |
| MSI           | B450 TOMAHAWK               | [be7c395cc7](https://linux-hardware.org/?probe=be7c395cc7) | Nov 21, 2023 |
| ASRock        | X570 Taichi                 | [96172d652b](https://linux-hardware.org/?probe=96172d652b) | Nov 21, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a166dbb3cf](https://linux-hardware.org/?probe=a166dbb3cf) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [ece8c390b1](https://linux-hardware.org/?probe=ece8c390b1) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [55dac497f4](https://linux-hardware.org/?probe=55dac497f4) | Nov 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f58ea2a820](https://linux-hardware.org/?probe=f58ea2a820) | Nov 20, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [a4f7b1d9d3](https://linux-hardware.org/?probe=a4f7b1d9d3) | Nov 20, 2023 |
| HP            | 8054                        | [2ccc2c67f2](https://linux-hardware.org/?probe=2ccc2c67f2) | Nov 20, 2023 |
| MSI           | B350M PRO-VDH               | [56cd0716d9](https://linux-hardware.org/?probe=56cd0716d9) | Nov 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [a7d065988a](https://linux-hardware.org/?probe=a7d065988a) | Nov 19, 2023 |
| ASRock        | B760M PG Riptide            | [fca337aea5](https://linux-hardware.org/?probe=fca337aea5) | Nov 19, 2023 |
| ASRock        | B760M PG Riptide            | [7c45a9b620](https://linux-hardware.org/?probe=7c45a9b620) | Nov 19, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [ae962a2552](https://linux-hardware.org/?probe=ae962a2552) | Nov 18, 2023 |
| Dell          | 0KWVT8 A03                  | [0619c3b255](https://linux-hardware.org/?probe=0619c3b255) | Nov 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [d402c27e5c](https://linux-hardware.org/?probe=d402c27e5c) | Nov 17, 2023 |
| HP            | 83E8                        | [393ca40cd9](https://linux-hardware.org/?probe=393ca40cd9) | Nov 16, 2023 |
| Gigabyte      | Z270-Gaming K3              | [9b4ca9cc96](https://linux-hardware.org/?probe=9b4ca9cc96) | Nov 16, 2023 |
| HC Technol... | HCAR5000-MI                 | [e4ac0f919f](https://linux-hardware.org/?probe=e4ac0f919f) | Nov 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [6a6b0096bb](https://linux-hardware.org/?probe=6a6b0096bb) | Nov 15, 2023 |
| MSI           | Z390-A PRO                  | [c3c068a998](https://linux-hardware.org/?probe=c3c068a998) | Nov 14, 2023 |
| Gigabyte      | H510M S2H V2                | [7b17ba0f7f](https://linux-hardware.org/?probe=7b17ba0f7f) | Nov 14, 2023 |
| HP            | 2AF7                        | [dd8d87a916](https://linux-hardware.org/?probe=dd8d87a916) | Nov 14, 2023 |
| Gigabyte      | H170N-WIFI-CF               | [73ef67d393](https://linux-hardware.org/?probe=73ef67d393) | Nov 13, 2023 |
| AMI           | Intel                       | [7c96434a18](https://linux-hardware.org/?probe=7c96434a18) | Nov 13, 2023 |
| MSI           | Z170A GAMING M3             | [cac951f39c](https://linux-hardware.org/?probe=cac951f39c) | Nov 13, 2023 |
| MSI           | Z170A GAMING M3             | [a6083e5df9](https://linux-hardware.org/?probe=a6083e5df9) | Nov 12, 2023 |
| Gigabyte      | B550M DS3H AC               | [f3b49f17b1](https://linux-hardware.org/?probe=f3b49f17b1) | Nov 12, 2023 |
| ASUSTek       | SABERTOOTH P67              | [61994e2e2e](https://linux-hardware.org/?probe=61994e2e2e) | Nov 12, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | [0e6185c9db](https://linux-hardware.org/?probe=0e6185c9db) | Nov 11, 2023 |
| Intel         | DH61WW AAG23116-206         | [75735f5b69](https://linux-hardware.org/?probe=75735f5b69) | Nov 11, 2023 |
| Gigabyte      | H97M-D3H                    | [9c77400bbf](https://linux-hardware.org/?probe=9c77400bbf) | Nov 11, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [ecc5d08bd8](https://linux-hardware.org/?probe=ecc5d08bd8) | Nov 10, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1473413ce2](https://linux-hardware.org/?probe=1473413ce2) | Nov 09, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | [8ca7abbf03](https://linux-hardware.org/?probe=8ca7abbf03) | Nov 08, 2023 |
| MSI           | PRO Z790-A WIFI             | [a675ce6c08](https://linux-hardware.org/?probe=a675ce6c08) | Nov 07, 2023 |
| ASUSTek       | Z87M-PLUS                   | [4075eda03c](https://linux-hardware.org/?probe=4075eda03c) | Nov 07, 2023 |
| ASUSTek       | P8B75-M                     | [c88dde8f18](https://linux-hardware.org/?probe=c88dde8f18) | Nov 07, 2023 |
| ASRock        | Z97 Killer                  | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| ASRock        | Z68 Pro3                    | [e6c695d4a7](https://linux-hardware.org/?probe=e6c695d4a7) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [6f11758faa](https://linux-hardware.org/?probe=6f11758faa) | Nov 04, 2023 |
| Gigabyte      | H410M S2H V2                | [8bbce8a378](https://linux-hardware.org/?probe=8bbce8a378) | Nov 04, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [f27bded4c1](https://linux-hardware.org/?probe=f27bded4c1) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | [26aff1917e](https://linux-hardware.org/?probe=26aff1917e) | Nov 04, 2023 |
| Intel         | X79 V1.0                    | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [d35fc5aa78](https://linux-hardware.org/?probe=d35fc5aa78) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [9a5c45e54b](https://linux-hardware.org/?probe=9a5c45e54b) | Nov 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [fc0052213d](https://linux-hardware.org/?probe=fc0052213d) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | [7812f09d39](https://linux-hardware.org/?probe=7812f09d39) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | [b45e25ec01](https://linux-hardware.org/?probe=b45e25ec01) | Nov 02, 2023 |
| HP            | 2AF7                        | [65ac8348d7](https://linux-hardware.org/?probe=65ac8348d7) | Nov 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [cd018c7ab7](https://linux-hardware.org/?probe=cd018c7ab7) | Nov 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [523fd59139](https://linux-hardware.org/?probe=523fd59139) | Nov 01, 2023 |
| ASRock        | X470 Taichi Ultimate        | [d85d5f59c2](https://linux-hardware.org/?probe=d85d5f59c2) | Nov 01, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [39f8a7c959](https://linux-hardware.org/?probe=39f8a7c959) | Nov 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [38d664802f](https://linux-hardware.org/?probe=38d664802f) | Nov 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [037e92aebd](https://linux-hardware.org/?probe=037e92aebd) | Nov 01, 2023 |
| ASRock        | B85M Pro4                   | [0ea7f00b4e](https://linux-hardware.org/?probe=0ea7f00b4e) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [7d5fd28d41](https://linux-hardware.org/?probe=7d5fd28d41) | Nov 01, 2023 |
| Unknown       | Unknown                     | [d58a78a617](https://linux-hardware.org/?probe=d58a78a617) | Oct 31, 2023 |
| eMachines     | EL1352G                     | [e133fecf3e](https://linux-hardware.org/?probe=e133fecf3e) | Oct 31, 2023 |
| ASRock        | A520M Phantom Gaming 4      | [a63d934992](https://linux-hardware.org/?probe=a63d934992) | Oct 31, 2023 |
| HP            | 8299                        | [e45f46df9d](https://linux-hardware.org/?probe=e45f46df9d) | Oct 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e231035f6e](https://linux-hardware.org/?probe=e231035f6e) | Oct 30, 2023 |
| MSI           | PRO Z790-P WIFI             | [b62cfa508b](https://linux-hardware.org/?probe=b62cfa508b) | Oct 30, 2023 |
| HP            | 2AF7                        | [1960b3a243](https://linux-hardware.org/?probe=1960b3a243) | Oct 29, 2023 |
| Gigabyte      | B450 GAMING X               | [c1785bec94](https://linux-hardware.org/?probe=c1785bec94) | Oct 29, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6b8560a943](https://linux-hardware.org/?probe=6b8560a943) | Oct 28, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | [fdb96441a0](https://linux-hardware.org/?probe=fdb96441a0) | Oct 27, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | [dde83d5de1](https://linux-hardware.org/?probe=dde83d5de1) | Oct 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [880bf38f49](https://linux-hardware.org/?probe=880bf38f49) | Oct 27, 2023 |
| ASUSTek       | PRIME X570-PRO              | [815b0a4bc4](https://linux-hardware.org/?probe=815b0a4bc4) | Oct 27, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [61bdfadaa0](https://linux-hardware.org/?probe=61bdfadaa0) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [13ad3bb316](https://linux-hardware.org/?probe=13ad3bb316) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [a8d850eef8](https://linux-hardware.org/?probe=a8d850eef8) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [023bd4d497](https://linux-hardware.org/?probe=023bd4d497) | Oct 25, 2023 |
| MSI           | PRO Z690-A DDR4             | [638386d33c](https://linux-hardware.org/?probe=638386d33c) | Oct 25, 2023 |
| HP            | 3047h                       | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b7447f21b5](https://linux-hardware.org/?probe=b7447f21b5) | Oct 25, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [5ad24eb928](https://linux-hardware.org/?probe=5ad24eb928) | Oct 24, 2023 |
| Danuri        | B550M-PX                    | [e24df1ad61](https://linux-hardware.org/?probe=e24df1ad61) | Oct 24, 2023 |
| Intel         | H61 V124                    | [034689793f](https://linux-hardware.org/?probe=034689793f) | Oct 24, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [b1f52f8dc1](https://linux-hardware.org/?probe=b1f52f8dc1) | Oct 23, 2023 |
| Gigabyte      | 970A-DS3P                   | [a9af589ace](https://linux-hardware.org/?probe=a9af589ace) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | [cf347b4567](https://linux-hardware.org/?probe=cf347b4567) | Oct 23, 2023 |
| Dell          | 096JG8 A01                  | [ce5ff412d1](https://linux-hardware.org/?probe=ce5ff412d1) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | [e0f48fec00](https://linux-hardware.org/?probe=e0f48fec00) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [58a9a7a091](https://linux-hardware.org/?probe=58a9a7a091) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [9b380c5e6a](https://linux-hardware.org/?probe=9b380c5e6a) | Oct 22, 2023 |
| ASRock        | N68C-S UCC                  | [6468bd6335](https://linux-hardware.org/?probe=6468bd6335) | Oct 21, 2023 |
| Dell          | 00V62H A01                  | [85894d27fe](https://linux-hardware.org/?probe=85894d27fe) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| Dell          | 06FW8P A01                  | [356c2f38aa](https://linux-hardware.org/?probe=356c2f38aa) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | [ca61a8649a](https://linux-hardware.org/?probe=ca61a8649a) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | [6108985945](https://linux-hardware.org/?probe=6108985945) | Oct 21, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [e7cd525d35](https://linux-hardware.org/?probe=e7cd525d35) | Oct 21, 2023 |
| Intel         | DG965RY AAD41691-301        | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ed3ce7aaa6](https://linux-hardware.org/?probe=ed3ce7aaa6) | Oct 18, 2023 |
| MSI           | X470 GAMING PRO             | [e275cfc499](https://linux-hardware.org/?probe=e275cfc499) | Oct 18, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [d652b15856](https://linux-hardware.org/?probe=d652b15856) | Oct 17, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME E... | [3d5d8ee9e6](https://linux-hardware.org/?probe=3d5d8ee9e6) | Oct 17, 2023 |
| Gigabyte      | Z590 VISION D               | [f9d3acd4e2](https://linux-hardware.org/?probe=f9d3acd4e2) | Oct 16, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | [5631fc0230](https://linux-hardware.org/?probe=5631fc0230) | Oct 16, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [04afaee575](https://linux-hardware.org/?probe=04afaee575) | Oct 15, 2023 |
| ASUSTek       | PRIME B450M-A II            | [98224c65b6](https://linux-hardware.org/?probe=98224c65b6) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [47788537bf](https://linux-hardware.org/?probe=47788537bf) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [30723700f1](https://linux-hardware.org/?probe=30723700f1) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [e4dc0eeb72](https://linux-hardware.org/?probe=e4dc0eeb72) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | [abc6dc18ab](https://linux-hardware.org/?probe=abc6dc18ab) | Oct 15, 2023 |
| HP            | 212B                        | [c0b9765d6e](https://linux-hardware.org/?probe=c0b9765d6e) | Oct 15, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [5bbd5682e8](https://linux-hardware.org/?probe=5bbd5682e8) | Oct 15, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [5a1df4c4df](https://linux-hardware.org/?probe=5a1df4c4df) | Oct 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a8e7e9b968](https://linux-hardware.org/?probe=a8e7e9b968) | Oct 14, 2023 |
| Gigabyte      | Z590I VISION D              | [725929fa07](https://linux-hardware.org/?probe=725929fa07) | Oct 14, 2023 |
| ASRock        | H97M Anniversary            | [7df48c5c5d](https://linux-hardware.org/?probe=7df48c5c5d) | Oct 14, 2023 |
| Dell          | 0NW6H5 A00                  | [0594aaa28b](https://linux-hardware.org/?probe=0594aaa28b) | Oct 13, 2023 |
| Dell          | 0NW6H5 A00                  | [596e3973bc](https://linux-hardware.org/?probe=596e3973bc) | Oct 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [4d6379353d](https://linux-hardware.org/?probe=4d6379353d) | Oct 13, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [52fdfb249e](https://linux-hardware.org/?probe=52fdfb249e) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | [d7d6c5206f](https://linux-hardware.org/?probe=d7d6c5206f) | Oct 12, 2023 |
| Biostar       | B550GTQ                     | [63f1b39dd4](https://linux-hardware.org/?probe=63f1b39dd4) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | [5e2f8bdc4d](https://linux-hardware.org/?probe=5e2f8bdc4d) | Oct 12, 2023 |
| Shenzhen M... | F6BFC                       | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| System76      | Thelio Mega thelio-mega-... | [abb07364c1](https://linux-hardware.org/?probe=abb07364c1) | Oct 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4ce0d26e3c](https://linux-hardware.org/?probe=4ce0d26e3c) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [835f369588](https://linux-hardware.org/?probe=835f369588) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [9acd34e892](https://linux-hardware.org/?probe=9acd34e892) | Oct 11, 2023 |
| ASUSTek       | PRIME Z590-V                | [ee15914a37](https://linux-hardware.org/?probe=ee15914a37) | Oct 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [3d02079672](https://linux-hardware.org/?probe=3d02079672) | Oct 10, 2023 |
| Gigabyte      | X570 GAMING X               | [b09f4a3a8a](https://linux-hardware.org/?probe=b09f4a3a8a) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO             | [c39ce018d6](https://linux-hardware.org/?probe=c39ce018d6) | Oct 10, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2d033cba6c](https://linux-hardware.org/?probe=2d033cba6c) | Oct 08, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3d510e53b4](https://linux-hardware.org/?probe=3d510e53b4) | Oct 08, 2023 |
| MSI           | B450M-A PRO MAX             | [3ac34a911c](https://linux-hardware.org/?probe=3ac34a911c) | Oct 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [a3190a6c6d](https://linux-hardware.org/?probe=a3190a6c6d) | Oct 07, 2023 |
| Gigabyte      | B75M-D3V                    | [17cdd65d6b](https://linux-hardware.org/?probe=17cdd65d6b) | Oct 07, 2023 |
| Huanan        | X99-BD4 V1.33               | [9477d90e51](https://linux-hardware.org/?probe=9477d90e51) | Oct 07, 2023 |
| MSI           | PRO Z690-A WIFI             | [5ec4f81683](https://linux-hardware.org/?probe=5ec4f81683) | Oct 06, 2023 |
| Dell          | 0WR7PY A02                  | [6507df947b](https://linux-hardware.org/?probe=6507df947b) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a308ec4180](https://linux-hardware.org/?probe=a308ec4180) | Oct 06, 2023 |
| Gigabyte      | X570 GAMING X               | [ebbd23f352](https://linux-hardware.org/?probe=ebbd23f352) | Oct 05, 2023 |
| Unknown       | Unknown                     | [3f779c87f6](https://linux-hardware.org/?probe=3f779c87f6) | Oct 05, 2023 |
| HP            | 0AA4h                       | [8e4a645689](https://linux-hardware.org/?probe=8e4a645689) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5932daaa4e](https://linux-hardware.org/?probe=5932daaa4e) | Oct 03, 2023 |
| ASRock        | Z790 PG Riptide             | [82630a534f](https://linux-hardware.org/?probe=82630a534f) | Oct 03, 2023 |
| Kllisre       | X79 V1.2                    | [fb9b29c804](https://linux-hardware.org/?probe=fb9b29c804) | Oct 03, 2023 |
| ASUSTek       | P8H77-M PRO                 | [bc03d7f758](https://linux-hardware.org/?probe=bc03d7f758) | Oct 02, 2023 |
| ASUSTek       | B150M-C/BR                  | [2435f20a18](https://linux-hardware.org/?probe=2435f20a18) | Oct 02, 2023 |
| MSI           | B450M-A PRO MAX             | [57ddb0f758](https://linux-hardware.org/?probe=57ddb0f758) | Oct 01, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [d16a64a7e1](https://linux-hardware.org/?probe=d16a64a7e1) | Oct 01, 2023 |
| Gigabyte      | H61M-S2PV                   | [691c015f6f](https://linux-hardware.org/?probe=691c015f6f) | Oct 01, 2023 |
| HP            | 8054                        | [20f337b1e7](https://linux-hardware.org/?probe=20f337b1e7) | Sep 29, 2023 |
| AZW           | SER V1                      | [10660522cb](https://linux-hardware.org/?probe=10660522cb) | Sep 28, 2023 |
| ASRock        | A520M-HDV                   | [d19f334f02](https://linux-hardware.org/?probe=d19f334f02) | Sep 28, 2023 |
| MSI           | PRO Z690-A WIFI             | [2ede90f6eb](https://linux-hardware.org/?probe=2ede90f6eb) | Sep 28, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [240ff7b72a](https://linux-hardware.org/?probe=240ff7b72a) | Sep 27, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5a73611f4d](https://linux-hardware.org/?probe=5a73611f4d) | Sep 26, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [0a5cc18946](https://linux-hardware.org/?probe=0a5cc18946) | Sep 26, 2023 |
| ASUSTek       | P5QPL-AM                    | [4259a21921](https://linux-hardware.org/?probe=4259a21921) | Sep 26, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | [2fe436c443](https://linux-hardware.org/?probe=2fe436c443) | Sep 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [a58111d9ae](https://linux-hardware.org/?probe=a58111d9ae) | Sep 25, 2023 |
| ASUSTek       | M4A79T Deluxe               | [ac151127e1](https://linux-hardware.org/?probe=ac151127e1) | Sep 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [3346cccd71](https://linux-hardware.org/?probe=3346cccd71) | Sep 24, 2023 |
| MSI           | B350 TOMAHAWK               | [7119229a1b](https://linux-hardware.org/?probe=7119229a1b) | Sep 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [a3e2e5f3c0](https://linux-hardware.org/?probe=a3e2e5f3c0) | Sep 24, 2023 |
| Unknown       | Unknown                     | [9be7572b83](https://linux-hardware.org/?probe=9be7572b83) | Sep 23, 2023 |
| Unknown       | Unknown                     | [b063963175](https://linux-hardware.org/?probe=b063963175) | Sep 23, 2023 |
| MSI           | X399 SLI PLUS               | [1c755bb49f](https://linux-hardware.org/?probe=1c755bb49f) | Sep 23, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | [32b162a364](https://linux-hardware.org/?probe=32b162a364) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [6656c28ec7](https://linux-hardware.org/?probe=6656c28ec7) | Sep 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [9867cb03bb](https://linux-hardware.org/?probe=9867cb03bb) | Sep 23, 2023 |
| Dell          | 0GWHMW A00                  | [d344d1e396](https://linux-hardware.org/?probe=d344d1e396) | Sep 23, 2023 |
| ASUSTek       | Crosshair IV Formula        | [4679088d4e](https://linux-hardware.org/?probe=4679088d4e) | Sep 22, 2023 |
| Hardkernel    | ODROID-H3                   | [19d1333b4f](https://linux-hardware.org/?probe=19d1333b4f) | Sep 21, 2023 |
| Dell          | 0F6X5P A00                  | [5e45e8b196](https://linux-hardware.org/?probe=5e45e8b196) | Sep 21, 2023 |
| ASUSTek       | M5A78L/USB3                 | [e1805d26c3](https://linux-hardware.org/?probe=e1805d26c3) | Sep 17, 2023 |
| ASRockRack    | Z490D4U-2L2T                | [0d43dbb11d](https://linux-hardware.org/?probe=0d43dbb11d) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [e0371fc03e](https://linux-hardware.org/?probe=e0371fc03e) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [43bf92a01b](https://linux-hardware.org/?probe=43bf92a01b) | Sep 17, 2023 |
| Gigabyte      | Z270X-UD5-CF                | [5c77a043ae](https://linux-hardware.org/?probe=5c77a043ae) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [efda5ec51a](https://linux-hardware.org/?probe=efda5ec51a) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [ebac37bdbd](https://linux-hardware.org/?probe=ebac37bdbd) | Sep 14, 2023 |
| ASRock        | X470 Taichi                 | [49aca37979](https://linux-hardware.org/?probe=49aca37979) | Sep 13, 2023 |
| Lenovo        | 3717 NO DPK                 | [13870a17b4](https://linux-hardware.org/?probe=13870a17b4) | Sep 13, 2023 |
| Dell          | 0YXT71 A01                  | [36991ac5a6](https://linux-hardware.org/?probe=36991ac5a6) | Sep 11, 2023 |
| Shenzhen M... | F6BFC                       | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [56bef39b59](https://linux-hardware.org/?probe=56bef39b59) | Sep 10, 2023 |
| ASUSTek       | Z170-A                      | [a812c1659b](https://linux-hardware.org/?probe=a812c1659b) | Sep 09, 2023 |
| MSI           | MAG B560M BAZOOKA           | [c3ba2033e2](https://linux-hardware.org/?probe=c3ba2033e2) | Sep 09, 2023 |
| Gigabyte      | Q87M-MK                     | [1c45c834fe](https://linux-hardware.org/?probe=1c45c834fe) | Sep 09, 2023 |
| HP            | 1495                        | [b56f622d7a](https://linux-hardware.org/?probe=b56f622d7a) | Sep 09, 2023 |
| Gigabyte      | F2A68HM-H                   | [bad7c8bf82](https://linux-hardware.org/?probe=bad7c8bf82) | Sep 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| Dell          | 0WN7Y6 A02                  | [aaf64e4624](https://linux-hardware.org/?probe=aaf64e4624) | Sep 07, 2023 |
| Biostar       | A58MD                       | [40f078fcfc](https://linux-hardware.org/?probe=40f078fcfc) | Sep 06, 2023 |
| MSI           | H310M PRO-VH PLUS           | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B460-H GAMING     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [e9faf4759d](https://linux-hardware.org/?probe=e9faf4759d) | Sep 03, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | [ffc201e884](https://linux-hardware.org/?probe=ffc201e884) | Sep 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [b4907a6220](https://linux-hardware.org/?probe=b4907a6220) | Sep 02, 2023 |
| MSI           | A320M-A PRO M2              | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [6ddc9b767d](https://linux-hardware.org/?probe=6ddc9b767d) | Sep 01, 2023 |
| MSI           | 760GM-P23                   | [76b83d4e93](https://linux-hardware.org/?probe=76b83d4e93) | Sep 01, 2023 |
| System76      | Thelio thelio-r3            | [d0cdea5d23](https://linux-hardware.org/?probe=d0cdea5d23) | Sep 01, 2023 |
| Gigabyte      | H97-HD3                     | [ba11958a48](https://linux-hardware.org/?probe=ba11958a48) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | [158ed240bf](https://linux-hardware.org/?probe=158ed240bf) | Aug 31, 2023 |
| ASRock        | Q1900B-ITX                  | [875427cd72](https://linux-hardware.org/?probe=875427cd72) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [085b3d4330](https://linux-hardware.org/?probe=085b3d4330) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [98b18bb67a](https://linux-hardware.org/?probe=98b18bb67a) | Aug 31, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [45f86c066d](https://linux-hardware.org/?probe=45f86c066d) | Aug 30, 2023 |
| Unknown       | Unknown                     | [ebebe5ddf7](https://linux-hardware.org/?probe=ebebe5ddf7) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Dell          | 0VRWRC A00                  | [e3a47f55c9](https://linux-hardware.org/?probe=e3a47f55c9) | Aug 26, 2023 |
| MSI           | PRO Z790-A WIFI             | [f3874bf2fc](https://linux-hardware.org/?probe=f3874bf2fc) | Aug 26, 2023 |
| ASUSTek       | PRIME B365M-A               | [8d952e28e1](https://linux-hardware.org/?probe=8d952e28e1) | Aug 25, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [51d4eefbc9](https://linux-hardware.org/?probe=51d4eefbc9) | Aug 25, 2023 |
| System76      | Thelio Major thelio-majo... | [e5caa63b77](https://linux-hardware.org/?probe=e5caa63b77) | Aug 25, 2023 |
| HP            | 0B4Ch D                     | [958521d2be](https://linux-hardware.org/?probe=958521d2be) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [254f8aee40](https://linux-hardware.org/?probe=254f8aee40) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [6f72852248](https://linux-hardware.org/?probe=6f72852248) | Aug 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c0bf920a5b](https://linux-hardware.org/?probe=c0bf920a5b) | Aug 24, 2023 |
| ASRock        | B450 Steel Legend           | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| HP            | 0B4Ch D                     | [5abce3a991](https://linux-hardware.org/?probe=5abce3a991) | Aug 23, 2023 |
| HP            | 18E7                        | [a78496c36e](https://linux-hardware.org/?probe=a78496c36e) | Aug 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [145d800029](https://linux-hardware.org/?probe=145d800029) | Aug 23, 2023 |
| ASUSTek       | P7P55-M                     | [0f5028d5fc](https://linux-hardware.org/?probe=0f5028d5fc) | Aug 22, 2023 |
| AZW           | GTR V02                     | [d699113f95](https://linux-hardware.org/?probe=d699113f95) | Aug 21, 2023 |
| NZXT          | N7 B550                     | [1f105eadd8](https://linux-hardware.org/?probe=1f105eadd8) | Aug 20, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [31861c8357](https://linux-hardware.org/?probe=31861c8357) | Aug 20, 2023 |
| Gigabyte      | Z270X-UD5-CF                | [04df52e837](https://linux-hardware.org/?probe=04df52e837) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [63d06430e4](https://linux-hardware.org/?probe=63d06430e4) | Aug 18, 2023 |
| HP            | 0266                        | [636546711d](https://linux-hardware.org/?probe=636546711d) | Aug 18, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [53c4af621d](https://linux-hardware.org/?probe=53c4af621d) | Aug 18, 2023 |
| HP            | 2AF7                        | [4e55d08586](https://linux-hardware.org/?probe=4e55d08586) | Aug 17, 2023 |
| MSI           | Z87-GD65 GAMING             | [7c09135f98](https://linux-hardware.org/?probe=7c09135f98) | Aug 17, 2023 |
| Positivo      | POS-RIQ470EN 11190998       | [1eec60309a](https://linux-hardware.org/?probe=1eec60309a) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0927025cfc](https://linux-hardware.org/?probe=0927025cfc) | Aug 15, 2023 |
| Intel         | B75A                        | [c081fb2ca8](https://linux-hardware.org/?probe=c081fb2ca8) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0b194349eb](https://linux-hardware.org/?probe=0b194349eb) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [9a8e4bc08d](https://linux-hardware.org/?probe=9a8e4bc08d) | Aug 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [302fb03dce](https://linux-hardware.org/?probe=302fb03dce) | Aug 13, 2023 |
| ASUSTek       | PRIME B350M-A               | [2c2aca991d](https://linux-hardware.org/?probe=2c2aca991d) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [ee66d3a81c](https://linux-hardware.org/?probe=ee66d3a81c) | Aug 13, 2023 |
| MSI           | X99A GODLIKE GAMING         | [b87f112952](https://linux-hardware.org/?probe=b87f112952) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | [edf714498f](https://linux-hardware.org/?probe=edf714498f) | Aug 13, 2023 |
| Alienware     | 0K9TKY A00                  | [213d229837](https://linux-hardware.org/?probe=213d229837) | Aug 13, 2023 |
| Intel         | B75A                        | [91f9e56ace](https://linux-hardware.org/?probe=91f9e56ace) | Aug 12, 2023 |
| HP            | 8643 SMVB                   | [2832e701f2](https://linux-hardware.org/?probe=2832e701f2) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [2c92ed92eb](https://linux-hardware.org/?probe=2c92ed92eb) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [580fda2e6b](https://linux-hardware.org/?probe=580fda2e6b) | Aug 12, 2023 |
| MSI           | A55M-E33                    | [7d538db764](https://linux-hardware.org/?probe=7d538db764) | Aug 12, 2023 |
| MSI           | A55M-E33                    | [9e64865fbc](https://linux-hardware.org/?probe=9e64865fbc) | Aug 12, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [a6d2358585](https://linux-hardware.org/?probe=a6d2358585) | Aug 11, 2023 |
| Unknown       | Unknown                     | [cf0d6729b4](https://linux-hardware.org/?probe=cf0d6729b4) | Aug 11, 2023 |
| ASRock        | B650M-HDV/M.2               | [ffd395aee0](https://linux-hardware.org/?probe=ffd395aee0) | Aug 11, 2023 |
| Gigabyte      | H410M S2 V2                 | [d4c5a12d06](https://linux-hardware.org/?probe=d4c5a12d06) | Aug 10, 2023 |
| HP            | 2AF9                        | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Gigabyte      | B450 AORUS M                | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | [b1a8fc0704](https://linux-hardware.org/?probe=b1a8fc0704) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | [920797388b](https://linux-hardware.org/?probe=920797388b) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [13b739e83a](https://linux-hardware.org/?probe=13b739e83a) | Aug 09, 2023 |
| NZXT          | N7 Z590                     | [3831033bdc](https://linux-hardware.org/?probe=3831033bdc) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| ASUSTek       | P5Q                         | [f485bf4b6e](https://linux-hardware.org/?probe=f485bf4b6e) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [58208c1f16](https://linux-hardware.org/?probe=58208c1f16) | Aug 08, 2023 |
| Unknown       | Unknown                     | [45fe14954d](https://linux-hardware.org/?probe=45fe14954d) | Aug 07, 2023 |
| Unknown       | Unknown                     | [d1bca9ae8b](https://linux-hardware.org/?probe=d1bca9ae8b) | Aug 07, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [ac2bdfc67b](https://linux-hardware.org/?probe=ac2bdfc67b) | Aug 06, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [93917e587f](https://linux-hardware.org/?probe=93917e587f) | Aug 06, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [4e0084cd74](https://linux-hardware.org/?probe=4e0084cd74) | Aug 05, 2023 |
| MSI           | 760GM-P23                   | [5746742389](https://linux-hardware.org/?probe=5746742389) | Aug 04, 2023 |
| ASRock        | X370 Taichi                 | [af453d6ef1](https://linux-hardware.org/?probe=af453d6ef1) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| Dell          | 0KWVT8 A03                  | [6ec952b536](https://linux-hardware.org/?probe=6ec952b536) | Aug 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [983329d56b](https://linux-hardware.org/?probe=983329d56b) | Aug 03, 2023 |
| JHZD          | X830                        | [7de7f6bb75](https://linux-hardware.org/?probe=7de7f6bb75) | Aug 03, 2023 |
| JHZD          | X830                        | [4fed3648c0](https://linux-hardware.org/?probe=4fed3648c0) | Aug 03, 2023 |
| ASUSTek       | P5QPL-AM                    | [2254be2ae2](https://linux-hardware.org/?probe=2254be2ae2) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| Dell          | 07PR60 A00                  | [590695e09f](https://linux-hardware.org/?probe=590695e09f) | Aug 02, 2023 |
| HP            | 8054                        | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| HP            | 8309                        | [6cb1cfc925](https://linux-hardware.org/?probe=6cb1cfc925) | Aug 02, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [41d4bd6cfe](https://linux-hardware.org/?probe=41d4bd6cfe) | Aug 01, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [3a655f04e1](https://linux-hardware.org/?probe=3a655f04e1) | Aug 01, 2023 |
| ASRock        | B450M/ac                    | [82be4b3dfb](https://linux-hardware.org/?probe=82be4b3dfb) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c44863a1c](https://linux-hardware.org/?probe=1c44863a1c) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [030f8afe2d](https://linux-hardware.org/?probe=030f8afe2d) | Jul 31, 2023 |
| ASUSTek       | Z87-K                       | [ed53779d9a](https://linux-hardware.org/?probe=ed53779d9a) | Jul 31, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [d1d59592c3](https://linux-hardware.org/?probe=d1d59592c3) | Jul 30, 2023 |
| ASUSTek       | Z170-PRO                    | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [44937ea360](https://linux-hardware.org/?probe=44937ea360) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| HP            | 3646h                       | [e00952810b](https://linux-hardware.org/?probe=e00952810b) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASRock        | X670E PG Lightning          | [b5fec7d5ff](https://linux-hardware.org/?probe=b5fec7d5ff) | Jul 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [f4941e530b](https://linux-hardware.org/?probe=f4941e530b) | Jul 28, 2023 |
| System76      | Thelio Mira thelio-mira-... | [785fb534be](https://linux-hardware.org/?probe=785fb534be) | Jul 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| Gigabyte      | H61M-S2PV                   | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| Gigabyte      | B550 VISION D-P             | [2c300ff820](https://linux-hardware.org/?probe=2c300ff820) | Jul 27, 2023 |
| Dell          | 07PR60 A00                  | [67ef05bdd5](https://linux-hardware.org/?probe=67ef05bdd5) | Jul 27, 2023 |
| Intel         | H81                         | [6fa9f0cd2d](https://linux-hardware.org/?probe=6fa9f0cd2d) | Jul 27, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [247f6d8816](https://linux-hardware.org/?probe=247f6d8816) | Jul 27, 2023 |
| Dell          | 0YXG0N A00                  | [fb365f50a0](https://linux-hardware.org/?probe=fb365f50a0) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Gigabyte      | H81M-H                      | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bf4dff1328](https://linux-hardware.org/?probe=bf4dff1328) | Jul 23, 2023 |
| MSI           | Boston                      | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| ASRock        | B550M Pro4                  | [46283ad18b](https://linux-hardware.org/?probe=46283ad18b) | Jul 22, 2023 |
| MSI           | Z97 PC Mate                 | [f4cddb5e86](https://linux-hardware.org/?probe=f4cddb5e86) | Jul 22, 2023 |
| Intel         | X99H                        | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| MSI           | Z370-A PRO                  | [9a1d731109](https://linux-hardware.org/?probe=9a1d731109) | Jul 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d23dfad700](https://linux-hardware.org/?probe=d23dfad700) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ebb1eed757](https://linux-hardware.org/?probe=ebb1eed757) | Jul 20, 2023 |
| ASUSTek       | Z97-A                       | [fe36d4fde0](https://linux-hardware.org/?probe=fe36d4fde0) | Jul 19, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [1dc0977942](https://linux-hardware.org/?probe=1dc0977942) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1f57cb78e8](https://linux-hardware.org/?probe=1f57cb78e8) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d3413475e2](https://linux-hardware.org/?probe=d3413475e2) | Jul 18, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | [199e0d2e12](https://linux-hardware.org/?probe=199e0d2e12) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| MSI           | MAG B550M MORTAR            | [83175318ff](https://linux-hardware.org/?probe=83175318ff) | Jul 16, 2023 |
| Alienware     | 0XJKKD A01                  | [b47699e30d](https://linux-hardware.org/?probe=b47699e30d) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| Dell          | 02YYK5 A01                  | [e984f2562d](https://linux-hardware.org/?probe=e984f2562d) | Jul 16, 2023 |
| Gigabyte      | 970A-DS3P                   | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| MSI           | PRO Z790-A WIFI             | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| HP            | 0B40h                       | [b452ab2c8d](https://linux-hardware.org/?probe=b452ab2c8d) | Jul 14, 2023 |
| ASUSTek       | B85M-G                      | [2afe11b7e4](https://linux-hardware.org/?probe=2afe11b7e4) | Jul 13, 2023 |
| HP            | 0AA8h                       | [297e7364cb](https://linux-hardware.org/?probe=297e7364cb) | Jul 13, 2023 |
| ASUSTek       | P8B75-M                     | [df7a7f2c36](https://linux-hardware.org/?probe=df7a7f2c36) | Jul 13, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [2f5bf1f247](https://linux-hardware.org/?probe=2f5bf1f247) | Jul 12, 2023 |
| HP            | 0AA8h                       | [db16057ca8](https://linux-hardware.org/?probe=db16057ca8) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | [a95cc808e9](https://linux-hardware.org/?probe=a95cc808e9) | Jul 12, 2023 |
| ASUSTek       | Z87-K                       | [d962460a5e](https://linux-hardware.org/?probe=d962460a5e) | Jul 12, 2023 |
| ASUSTek       | PRIME B550M-A               | [d08295d5f4](https://linux-hardware.org/?probe=d08295d5f4) | Jul 12, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [ee2dc6ac7b](https://linux-hardware.org/?probe=ee2dc6ac7b) | Jul 11, 2023 |
| Biostar       | A960D+V2                    | [e6bfab517b](https://linux-hardware.org/?probe=e6bfab517b) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [b581326f50](https://linux-hardware.org/?probe=b581326f50) | Jul 10, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [a4650f89f7](https://linux-hardware.org/?probe=a4650f89f7) | Jul 10, 2023 |
| Gigabyte      | Z270-Gaming K3              | [3937b5d17a](https://linux-hardware.org/?probe=3937b5d17a) | Jul 09, 2023 |
| Gigabyte      | Z270-Gaming K3              | [0aea3d9721](https://linux-hardware.org/?probe=0aea3d9721) | Jul 09, 2023 |
| HP            | 8918                        | [af366ea249](https://linux-hardware.org/?probe=af366ea249) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [80164b7a44](https://linux-hardware.org/?probe=80164b7a44) | Jul 07, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [d122a1cedc](https://linux-hardware.org/?probe=d122a1cedc) | Jul 07, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| MSI           | Z97 PC Mate                 | [495b6e6e4a](https://linux-hardware.org/?probe=495b6e6e4a) | Jul 06, 2023 |
| MSI           | B350 GAMING PLUS            | [8115e08748](https://linux-hardware.org/?probe=8115e08748) | Jul 05, 2023 |
| MSI           | Z97 PC Mate                 | [0d9ce2b3d2](https://linux-hardware.org/?probe=0d9ce2b3d2) | Jul 05, 2023 |
| Unknown       | 1.31                        | [d34eb9e5d4](https://linux-hardware.org/?probe=d34eb9e5d4) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [6013dcdf1e](https://linux-hardware.org/?probe=6013dcdf1e) | Jul 04, 2023 |
| ASUSTek       | PRIME B365M-A               | [bc423a1cb9](https://linux-hardware.org/?probe=bc423a1cb9) | Jul 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [a44e9e946f](https://linux-hardware.org/?probe=a44e9e946f) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [cc5348e995](https://linux-hardware.org/?probe=cc5348e995) | Jul 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b8ff99b486](https://linux-hardware.org/?probe=b8ff99b486) | Jul 03, 2023 |
| ASRock        | B450M/ac                    | [1f5703db9b](https://linux-hardware.org/?probe=1f5703db9b) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [73015ee7be](https://linux-hardware.org/?probe=73015ee7be) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [6db9b5e42a](https://linux-hardware.org/?probe=6db9b5e42a) | Jul 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [73d4fb6c33](https://linux-hardware.org/?probe=73d4fb6c33) | Jul 02, 2023 |
| Dell          | 02GDWG A00                  | [228db73d17](https://linux-hardware.org/?probe=228db73d17) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | [38e6f08816](https://linux-hardware.org/?probe=38e6f08816) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [18b6484d81](https://linux-hardware.org/?probe=18b6484d81) | Jul 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a70ec8bdf1](https://linux-hardware.org/?probe=a70ec8bdf1) | Jul 01, 2023 |
| Gigabyte      | B550 UD AC                  | [7d7d37522c](https://linux-hardware.org/?probe=7d7d37522c) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [878e617ba4](https://linux-hardware.org/?probe=878e617ba4) | Jun 30, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [cdb77bf9b6](https://linux-hardware.org/?probe=cdb77bf9b6) | Jun 30, 2023 |
| Dell          | 0M6C7G A00                  | [d7dfcc4a38](https://linux-hardware.org/?probe=d7dfcc4a38) | Jun 30, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [323464eebb](https://linux-hardware.org/?probe=323464eebb) | Jun 28, 2023 |
| Dell          | 08NPPY A00                  | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| ASUSTek       | GA35DX                      | [a91acc04b6](https://linux-hardware.org/?probe=a91acc04b6) | Jun 28, 2023 |
| Dell          | 02YYK5 A01                  | [4054ebeac8](https://linux-hardware.org/?probe=4054ebeac8) | Jun 28, 2023 |
| Dell          | 0F6X5P A00                  | [cad43414b4](https://linux-hardware.org/?probe=cad43414b4) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [1bd3b2b912](https://linux-hardware.org/?probe=1bd3b2b912) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d436c6bcdf](https://linux-hardware.org/?probe=d436c6bcdf) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [3907252056](https://linux-hardware.org/?probe=3907252056) | Jun 25, 2023 |
| MSI           | B450M MORTAR                | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| Shenzhen M... | F6BFC                       | [7f13c620bf](https://linux-hardware.org/?probe=7f13c620bf) | Jun 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| MSI           | H77MA-G43                   | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [082d9a4988](https://linux-hardware.org/?probe=082d9a4988) | Jun 22, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [3c27e4a91d](https://linux-hardware.org/?probe=3c27e4a91d) | Jun 22, 2023 |
| ASUSTek       | PRIME Z490-A                | [f7c2ec659b](https://linux-hardware.org/?probe=f7c2ec659b) | Jun 22, 2023 |
| Intel         | H55                         | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 89B5 A                      | [01e8a85a35](https://linux-hardware.org/?probe=01e8a85a35) | Jun 21, 2023 |
| ASUSTek       | Maximus VI HERO             | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | [1d14950f1e](https://linux-hardware.org/?probe=1d14950f1e) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | [46baecef13](https://linux-hardware.org/?probe=46baecef13) | Jun 20, 2023 |
| BESSTAR Te... | HM90                        | [796769b68a](https://linux-hardware.org/?probe=796769b68a) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| ASRock        | B450 Steel Legend           | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| ASUSTek       | Maximus VI HERO             | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| HP            | 8949 11                     | [bd6b95fc23](https://linux-hardware.org/?probe=bd6b95fc23) | Jun 18, 2023 |
| Biostar       | A320MH                      | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| ASRock        | Z77 Extreme4                | [c45aea7474](https://linux-hardware.org/?probe=c45aea7474) | Jun 18, 2023 |
| BESSTAR Te... | B550                        | [6c2811bbf5](https://linux-hardware.org/?probe=6c2811bbf5) | Jun 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | [c2f10ad55c](https://linux-hardware.org/?probe=c2f10ad55c) | Jun 17, 2023 |
| ASUSTek       | P5QPL-AM                    | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| MSI           | H67MA-E35                   | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| Gigabyte      | B450M S2H                   | [1bcfd50d08](https://linux-hardware.org/?probe=1bcfd50d08) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | [04b5148080](https://linux-hardware.org/?probe=04b5148080) | Jun 15, 2023 |
| ASUSTek       | P6T DELUXE V2               | [887bfc11d5](https://linux-hardware.org/?probe=887bfc11d5) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [5281ad2271](https://linux-hardware.org/?probe=5281ad2271) | Jun 13, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| Pegatron      | NARRA5                      | [3e7cbbb991](https://linux-hardware.org/?probe=3e7cbbb991) | Jun 12, 2023 |
| MSI           | MEG X570 UNIFY              | [1f4d0ebdc1](https://linux-hardware.org/?probe=1f4d0ebdc1) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a9bb4cfb62](https://linux-hardware.org/?probe=a9bb4cfb62) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9c0f9bf219](https://linux-hardware.org/?probe=9c0f9bf219) | Jun 12, 2023 |
| BESSTAR Te... | B550                        | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| Pegatron      | NARRA5                      | [609c2921d3](https://linux-hardware.org/?probe=609c2921d3) | Jun 11, 2023 |
| BESSTAR Te... | HM90                        | [86c52dcc7a](https://linux-hardware.org/?probe=86c52dcc7a) | Jun 11, 2023 |
| HP            | 89B5 A                      | [7bf638dc35](https://linux-hardware.org/?probe=7bf638dc35) | Jun 10, 2023 |
| MSI           | X99A GODLIKE GAMING         | [19511501c7](https://linux-hardware.org/?probe=19511501c7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| HP            | 8949 11                     | [f5e1f4b6c9](https://linux-hardware.org/?probe=f5e1f4b6c9) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [cac24c37e5](https://linux-hardware.org/?probe=cac24c37e5) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS M                | [280baa2765](https://linux-hardware.org/?probe=280baa2765) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | [50b022f065](https://linux-hardware.org/?probe=50b022f065) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1189f6696f](https://linux-hardware.org/?probe=1189f6696f) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| AZW           | SEi                         | [2b085e7ed2](https://linux-hardware.org/?probe=2b085e7ed2) | Jun 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | [70c409a2b8](https://linux-hardware.org/?probe=70c409a2b8) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| System76      | Thelio Mira thelio-mira-... | [d7d155d89d](https://linux-hardware.org/?probe=d7d155d89d) | Jun 07, 2023 |
| HP            | 8949 11                     | [06bca18276](https://linux-hardware.org/?probe=06bca18276) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| MSI           | A55M-E33                    | [336b7f877d](https://linux-hardware.org/?probe=336b7f877d) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Foxconn       | A74ML-K                     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| HP            | 8949 11                     | [f06749002f](https://linux-hardware.org/?probe=f06749002f) | Jun 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [5c280bbd6c](https://linux-hardware.org/?probe=5c280bbd6c) | Jun 03, 2023 |
| MSI           | B150M MORTAR                | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [b86be4f1de](https://linux-hardware.org/?probe=b86be4f1de) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| Dell          | 0GY6Y8 A02                  | [7f2c514dff](https://linux-hardware.org/?probe=7f2c514dff) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| HP            | 212A                        | [a0e56b03e2](https://linux-hardware.org/?probe=a0e56b03e2) | Jun 01, 2023 |
| MSI           | B350M BAZOOKA               | [a494d94087](https://linux-hardware.org/?probe=a494d94087) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| MSI           | B350M PRO-VD PLUS           | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| BESSTAR Te... | HM90                        | [cb78f83d80](https://linux-hardware.org/?probe=cb78f83d80) | May 30, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [4cbc2f9044](https://linux-hardware.org/?probe=4cbc2f9044) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| ASUSTek       | M5A97                       | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Dell          | 0NM64V A01                  | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| ASUSTek       | Crosshair IV Formula        | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| AZW           | EQ                          | [8e6c18ebbb](https://linux-hardware.org/?probe=8e6c18ebbb) | May 28, 2023 |
| AZW           | EQ                          | [98e5ea581c](https://linux-hardware.org/?probe=98e5ea581c) | May 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [46460561e1](https://linux-hardware.org/?probe=46460561e1) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Gigabyte      | H61M-S2PV                   | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASRock        | X300M-STX                   | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 0AA4h                       | [41ec821e77](https://linux-hardware.org/?probe=41ec821e77) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| ASUSTek       | G20AJ                       | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| HP            | 212A                        | [87b3c9809f](https://linux-hardware.org/?probe=87b3c9809f) | May 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [8604115d8b](https://linux-hardware.org/?probe=8604115d8b) | May 23, 2023 |
| MSI           | B150M MORTAR                | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [e781194fb3](https://linux-hardware.org/?probe=e781194fb3) | May 23, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [7384b29d21](https://linux-hardware.org/?probe=7384b29d21) | May 20, 2023 |
| Samsung       | DeskTop System              | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e16a632eca](https://linux-hardware.org/?probe=e16a632eca) | May 20, 2023 |
| Gigabyte      | H61M-S2PV                   | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [75d3691dae](https://linux-hardware.org/?probe=75d3691dae) | May 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [994adfd229](https://linux-hardware.org/?probe=994adfd229) | May 18, 2023 |
| Dell          | 0KWVT8 A03                  | [e28f96322d](https://linux-hardware.org/?probe=e28f96322d) | May 18, 2023 |
| Gigabyte      | H410M S2 V2                 | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [06003cbcc2](https://linux-hardware.org/?probe=06003cbcc2) | May 18, 2023 |
| PS            | X570 Pro4                   | [cde38918e6](https://linux-hardware.org/?probe=cde38918e6) | May 18, 2023 |
| Gigabyte      | B450M H                     | [a1cb84300e](https://linux-hardware.org/?probe=a1cb84300e) | May 18, 2023 |
| Dell          | 048DY8 A01                  | [aaf390dad1](https://linux-hardware.org/?probe=aaf390dad1) | May 17, 2023 |
| EVGA          | 151-HE-E999                 | [aa87f447d5](https://linux-hardware.org/?probe=aa87f447d5) | May 16, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [9a08def3ae](https://linux-hardware.org/?probe=9a08def3ae) | May 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [d35caae2b6](https://linux-hardware.org/?probe=d35caae2b6) | May 15, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [829665d7bf](https://linux-hardware.org/?probe=829665d7bf) | May 15, 2023 |
| HP            | 3398                        | [7339f433ef](https://linux-hardware.org/?probe=7339f433ef) | May 15, 2023 |
| MSI           | H61M-P23                    | [e6b643867b](https://linux-hardware.org/?probe=e6b643867b) | May 15, 2023 |
| Dell          | 02GDWG A00                  | [38a459c2e0](https://linux-hardware.org/?probe=38a459c2e0) | May 14, 2023 |
| EVGA          | 151-HE-E999                 | [a431f34e2b](https://linux-hardware.org/?probe=a431f34e2b) | May 14, 2023 |
| MSI           | H110I PRO                   | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [676c25e644](https://linux-hardware.org/?probe=676c25e644) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [415306aabf](https://linux-hardware.org/?probe=415306aabf) | May 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cf7c801d5c](https://linux-hardware.org/?probe=cf7c801d5c) | May 12, 2023 |
| Apple         | Mac-F221BEC8                | [ffffd119fb](https://linux-hardware.org/?probe=ffffd119fb) | May 12, 2023 |
| MSI           | 970A-G46                    | [6ad3215735](https://linux-hardware.org/?probe=6ad3215735) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| HP            | 158A                        | [a085c7a516](https://linux-hardware.org/?probe=a085c7a516) | May 11, 2023 |
| Dell          | 0T2HR0 A01                  | [96c6b065e8](https://linux-hardware.org/?probe=96c6b065e8) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [5d50ca41ef](https://linux-hardware.org/?probe=5d50ca41ef) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [0e8fab037b](https://linux-hardware.org/?probe=0e8fab037b) | May 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4276c0fd28](https://linux-hardware.org/?probe=4276c0fd28) | May 11, 2023 |
| Gigabyte      | H97N-WIFI                   | [ceebdc263a](https://linux-hardware.org/?probe=ceebdc263a) | May 10, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [5f3555ab64](https://linux-hardware.org/?probe=5f3555ab64) | May 10, 2023 |
| ASUSTek       | Z170-K                      | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [c40e865226](https://linux-hardware.org/?probe=c40e865226) | May 08, 2023 |
| ASUSTek       | M3N WS                      | [fb7920c5f9](https://linux-hardware.org/?probe=fb7920c5f9) | May 08, 2023 |
| ASUSTek       | P8P67-M                     | [386d7c9de4](https://linux-hardware.org/?probe=386d7c9de4) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | [1945ccd76d](https://linux-hardware.org/?probe=1945ccd76d) | May 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [894029cc14](https://linux-hardware.org/?probe=894029cc14) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | [a5c758152f](https://linux-hardware.org/?probe=a5c758152f) | May 07, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [8c5b603452](https://linux-hardware.org/?probe=8c5b603452) | May 07, 2023 |
| ASUSTek       | M4A87TD EVO                 | [ecb5894e85](https://linux-hardware.org/?probe=ecb5894e85) | May 06, 2023 |
| Gigabyte      | H310M H x.x                 | [fec056072d](https://linux-hardware.org/?probe=fec056072d) | May 05, 2023 |
| Dell          | 02GDWG A00                  | [7b9a0196b1](https://linux-hardware.org/?probe=7b9a0196b1) | May 05, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [95f75e1344](https://linux-hardware.org/?probe=95f75e1344) | May 04, 2023 |
| Gigabyte      | H410M H                     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| Dell          | 02GDWG A00                  | [46abb3e5c7](https://linux-hardware.org/?probe=46abb3e5c7) | May 03, 2023 |
| MSI           | B450M MORTAR                | [691239a442](https://linux-hardware.org/?probe=691239a442) | May 03, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [eae11b1ac4](https://linux-hardware.org/?probe=eae11b1ac4) | May 02, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [ee33a17baa](https://linux-hardware.org/?probe=ee33a17baa) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [d817c9a53f](https://linux-hardware.org/?probe=d817c9a53f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [a14544f923](https://linux-hardware.org/?probe=a14544f923) | May 02, 2023 |
| EVGA          | 151-HE-E999                 | [b293ade39d](https://linux-hardware.org/?probe=b293ade39d) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [37ba71ddb4](https://linux-hardware.org/?probe=37ba71ddb4) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [b61c6e5277](https://linux-hardware.org/?probe=b61c6e5277) | May 01, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [9b6f7cea89](https://linux-hardware.org/?probe=9b6f7cea89) | May 01, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [0d5e9310d3](https://linux-hardware.org/?probe=0d5e9310d3) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4ac7cbf111](https://linux-hardware.org/?probe=4ac7cbf111) | Apr 29, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| Intel         | DB75EN AAG39650-303         | [713c422641](https://linux-hardware.org/?probe=713c422641) | Apr 29, 2023 |
| HP            | 8054                        | [81a57b4a2f](https://linux-hardware.org/?probe=81a57b4a2f) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| MSI           | PRO X670-P WIFI             | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f1679a62d0](https://linux-hardware.org/?probe=f1679a62d0) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [4363ca582a](https://linux-hardware.org/?probe=4363ca582a) | Apr 26, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [f5de49d5b3](https://linux-hardware.org/?probe=f5de49d5b3) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [83453e6960](https://linux-hardware.org/?probe=83453e6960) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| Foxconn       | 2ABF                        | [d040f4ff16](https://linux-hardware.org/?probe=d040f4ff16) | Apr 26, 2023 |
| Intel         | X99H                        | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| ASRock        | Z370 Extreme4               | [0e46ae0751](https://linux-hardware.org/?probe=0e46ae0751) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [a06d7e1f82](https://linux-hardware.org/?probe=a06d7e1f82) | Apr 25, 2023 |
| Gigabyte      | B450M S2H                   | [db176db0db](https://linux-hardware.org/?probe=db176db0db) | Apr 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [0d6740c2a8](https://linux-hardware.org/?probe=0d6740c2a8) | Apr 24, 2023 |
| G7-2011       | X79                         | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| ASRock        | A320M Pro4                  | [bfe26862f0](https://linux-hardware.org/?probe=bfe26862f0) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [074135d4f4](https://linux-hardware.org/?probe=074135d4f4) | Apr 24, 2023 |
| Gigabyte      | B450M S2H                   | [f3c853b789](https://linux-hardware.org/?probe=f3c853b789) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| Packard Be... | IPOWER G3610                | [05de2306b0](https://linux-hardware.org/?probe=05de2306b0) | Apr 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [cd11cc0e25](https://linux-hardware.org/?probe=cd11cc0e25) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| Dell          | 0FDY5C A00                  | [c35628b7c7](https://linux-hardware.org/?probe=c35628b7c7) | Apr 22, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| MSI           | H110M PRO-D                 | [cc76c44731](https://linux-hardware.org/?probe=cc76c44731) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [4abccb30eb](https://linux-hardware.org/?probe=4abccb30eb) | Apr 18, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [e84a6f3538](https://linux-hardware.org/?probe=e84a6f3538) | Apr 18, 2023 |
| Dell          | 08WKV3 A00                  | [091f305ccb](https://linux-hardware.org/?probe=091f305ccb) | Apr 18, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| ASRock        | X670E Pro RS                | [cfc2be8311](https://linux-hardware.org/?probe=cfc2be8311) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | [be0c962cda](https://linux-hardware.org/?probe=be0c962cda) | Apr 16, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [8888f53504](https://linux-hardware.org/?probe=8888f53504) | Apr 16, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [e405d73576](https://linux-hardware.org/?probe=e405d73576) | Apr 15, 2023 |
| Dell          | 0HY9JP A02                  | [25a1ee5a25](https://linux-hardware.org/?probe=25a1ee5a25) | Apr 15, 2023 |
| Biostar       | A960D+V2                    | [da262e3956](https://linux-hardware.org/?probe=da262e3956) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [87b5989939](https://linux-hardware.org/?probe=87b5989939) | Apr 13, 2023 |
| HP            | 8433 11                     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [df59296148](https://linux-hardware.org/?probe=df59296148) | Apr 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [df185fb277](https://linux-hardware.org/?probe=df185fb277) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | [3acd31b3be](https://linux-hardware.org/?probe=3acd31b3be) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | [7a1d69f216](https://linux-hardware.org/?probe=7a1d69f216) | Apr 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | [d3ecd3c066](https://linux-hardware.org/?probe=d3ecd3c066) | Apr 12, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | [29ed28536e](https://linux-hardware.org/?probe=29ed28536e) | Apr 12, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [4c217a8a03](https://linux-hardware.org/?probe=4c217a8a03) | Apr 11, 2023 |
| Gigabyte      | G41MT-S2                    | [73233d1c4c](https://linux-hardware.org/?probe=73233d1c4c) | Apr 11, 2023 |
| MSI           | MEG X570 UNIFY              | [02d670e0db](https://linux-hardware.org/?probe=02d670e0db) | Apr 11, 2023 |
| MSI           | B350 GAMING PLUS            | [df2f924a6e](https://linux-hardware.org/?probe=df2f924a6e) | Apr 11, 2023 |
| MSI           | H81M-P33                    | [129abe0b90](https://linux-hardware.org/?probe=129abe0b90) | Apr 10, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [8302310eaf](https://linux-hardware.org/?probe=8302310eaf) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [645fe56eb3](https://linux-hardware.org/?probe=645fe56eb3) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [c963121074](https://linux-hardware.org/?probe=c963121074) | Apr 06, 2023 |
| Dell          | 09KPNV A01                  | [06d1f0e63f](https://linux-hardware.org/?probe=06d1f0e63f) | Apr 06, 2023 |
| Apple         | Mac-F221BEC8                | [d1f4197f52](https://linux-hardware.org/?probe=d1f4197f52) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| MSI           | 970 GAMING                  | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| PS            | X570 Pro4                   | [f67323ef28](https://linux-hardware.org/?probe=f67323ef28) | Apr 05, 2023 |
| ASUSTek       | M4A87TD EVO                 | [6f3f9cf977](https://linux-hardware.org/?probe=6f3f9cf977) | Apr 05, 2023 |
| ASRock        | B450M Steel Legend          | [fb0dc3cc20](https://linux-hardware.org/?probe=fb0dc3cc20) | Apr 05, 2023 |
| Unknown       | X99-GT                      | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [29dc58335f](https://linux-hardware.org/?probe=29dc58335f) | Apr 04, 2023 |
| Gigabyte      | B550M DS3H                  | [7a5ee5da76](https://linux-hardware.org/?probe=7a5ee5da76) | Apr 04, 2023 |
| Dell          | 0DF42J A00                  | [056818267b](https://linux-hardware.org/?probe=056818267b) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| Dell          | 0KWVT8 A03                  | [1e66b2ab37](https://linux-hardware.org/?probe=1e66b2ab37) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| Dell          | 0KWVT8 A03                  | [a700fbd33d](https://linux-hardware.org/?probe=a700fbd33d) | Apr 02, 2023 |
| MSI           | B350 GAMING PRO CARBON      | [0ffb7303f2](https://linux-hardware.org/?probe=0ffb7303f2) | Apr 02, 2023 |
| HP            | 0AA4h                       | [9b84d8c935](https://linux-hardware.org/?probe=9b84d8c935) | Apr 02, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [cf9da855fc](https://linux-hardware.org/?probe=cf9da855fc) | Apr 02, 2023 |
| BESSTAR Te... | HM80                        | [4242425ada](https://linux-hardware.org/?probe=4242425ada) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | [702890870e](https://linux-hardware.org/?probe=702890870e) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [5dddcdcb25](https://linux-hardware.org/?probe=5dddcdcb25) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [277d3c7f43](https://linux-hardware.org/?probe=277d3c7f43) | Apr 01, 2023 |
| Lenovo        | 4030                        | [7a23fd4fb4](https://linux-hardware.org/?probe=7a23fd4fb4) | Apr 01, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [f7c90851ac](https://linux-hardware.org/?probe=f7c90851ac) | Apr 01, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [fc44ad8c07](https://linux-hardware.org/?probe=fc44ad8c07) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [61e2653466](https://linux-hardware.org/?probe=61e2653466) | Mar 31, 2023 |
| ASUSTek       | P8H67-M LE                  | [11b3a7cdb1](https://linux-hardware.org/?probe=11b3a7cdb1) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| HP            | 0AA4h                       | [97457bb10c](https://linux-hardware.org/?probe=97457bb10c) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| Foxconn       | 2AB1 DVT                    | [a9e8e4d4b0](https://linux-hardware.org/?probe=a9e8e4d4b0) | Mar 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [81dda92e58](https://linux-hardware.org/?probe=81dda92e58) | Mar 30, 2023 |
| HP            | 8433 11                     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA4h                       | [801f843749](https://linux-hardware.org/?probe=801f843749) | Mar 29, 2023 |
| Win elemen... | M600                        | [7cf2343b6f](https://linux-hardware.org/?probe=7cf2343b6f) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| HP            | 09F0h                       | [540ec71101](https://linux-hardware.org/?probe=540ec71101) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [f17c95f91b](https://linux-hardware.org/?probe=f17c95f91b) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [1b67e2c4fd](https://linux-hardware.org/?probe=1b67e2c4fd) | Mar 28, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [cde470cb39](https://linux-hardware.org/?probe=cde470cb39) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c4bba42d7b](https://linux-hardware.org/?probe=c4bba42d7b) | Mar 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [adee3bbdde](https://linux-hardware.org/?probe=adee3bbdde) | Mar 28, 2023 |
| MSI           | B450M BAZOOKA V2            | [f6236c5962](https://linux-hardware.org/?probe=f6236c5962) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| MSI           | Z490 PLUS                   | [06032b5e04](https://linux-hardware.org/?probe=06032b5e04) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [fc01cd79a4](https://linux-hardware.org/?probe=fc01cd79a4) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c08caf1dee](https://linux-hardware.org/?probe=c08caf1dee) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [f6f4996c63](https://linux-hardware.org/?probe=f6f4996c63) | Mar 26, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [0f7d28bd43](https://linux-hardware.org/?probe=0f7d28bd43) | Mar 25, 2023 |
| ASUSTek       | SABERTOOTH X79              | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
| Dell          | 0PC5F7 A01                  | [61550296b7](https://linux-hardware.org/?probe=61550296b7) | Mar 24, 2023 |
| HP            | 212B                        | [266912cedd](https://linux-hardware.org/?probe=266912cedd) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | [7a3319972e](https://linux-hardware.org/?probe=7a3319972e) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [c06eaca849](https://linux-hardware.org/?probe=c06eaca849) | Mar 23, 2023 |
| Dell          | 0RK936                      | [af3e7f60cb](https://linux-hardware.org/?probe=af3e7f60cb) | Mar 22, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| Dell          | 0RK936                      | [6c2680e4e9](https://linux-hardware.org/?probe=6c2680e4e9) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [d4e033725b](https://linux-hardware.org/?probe=d4e033725b) | Mar 21, 2023 |
| Supermicro    | X9SAE                       | [01195f072e](https://linux-hardware.org/?probe=01195f072e) | Mar 21, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [5ea7504472](https://linux-hardware.org/?probe=5ea7504472) | Mar 21, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d0079fa594](https://linux-hardware.org/?probe=d0079fa594) | Mar 19, 2023 |
| Gigabyte      | X79-UD3                     | [0139691951](https://linux-hardware.org/?probe=0139691951) | Mar 19, 2023 |
| Dell          | 0WMJ54 A00                  | [bcb1a34cf2](https://linux-hardware.org/?probe=bcb1a34cf2) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c4bebd7028](https://linux-hardware.org/?probe=c4bebd7028) | Mar 17, 2023 |
| Unknown       | Unknown                     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [557a99333f](https://linux-hardware.org/?probe=557a99333f) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| HP            | 843F                        | [e444e0d76a](https://linux-hardware.org/?probe=e444e0d76a) | Mar 17, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b20fcd6878](https://linux-hardware.org/?probe=b20fcd6878) | Mar 17, 2023 |
| Dell          | 02GDWG A00                  | [c81ac4434e](https://linux-hardware.org/?probe=c81ac4434e) | Mar 16, 2023 |
| ASUSTek       | Z87-K                       | [fe2d844bfb](https://linux-hardware.org/?probe=fe2d844bfb) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [88c4c221af](https://linux-hardware.org/?probe=88c4c221af) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | [e8bbe7a962](https://linux-hardware.org/?probe=e8bbe7a962) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [0c74f7b048](https://linux-hardware.org/?probe=0c74f7b048) | Mar 15, 2023 |
| ASRock        | B550 Extreme4               | [9a139b5bad](https://linux-hardware.org/?probe=9a139b5bad) | Mar 14, 2023 |
| Gigabyte      | X58A-UD7                    | [95248fc9a0](https://linux-hardware.org/?probe=95248fc9a0) | Mar 14, 2023 |
| Dell          | 0RK936                      | [59cbc1f071](https://linux-hardware.org/?probe=59cbc1f071) | Mar 14, 2023 |
| ASUSTek       | PRIME A320M-K               | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| ASUSTek       | H97-PRO                     | [b03c056ee1](https://linux-hardware.org/?probe=b03c056ee1) | Mar 13, 2023 |
| Gateway       | WG43M                       | [c1ab165971](https://linux-hardware.org/?probe=c1ab165971) | Mar 13, 2023 |
| MSI           | A68HM-E33 V2                | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| Acer          | Aspire X1935                | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| Dell          | 0KC9NP A00                  | [873a2bf50c](https://linux-hardware.org/?probe=873a2bf50c) | Mar 11, 2023 |
| ASRock        | FM2A68M-HD+                 | [ccba86bda3](https://linux-hardware.org/?probe=ccba86bda3) | Mar 10, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [dbdadff4f2](https://linux-hardware.org/?probe=dbdadff4f2) | Mar 10, 2023 |
| ASRock        | B450 Steel Legend           | [e183f14e7e](https://linux-hardware.org/?probe=e183f14e7e) | Mar 10, 2023 |
| Positivo      | POS-PIQ77CL                 | [789838055a](https://linux-hardware.org/?probe=789838055a) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| Gigabyte      | H110M-DS2V DDR3-CF          | [d101f34459](https://linux-hardware.org/?probe=d101f34459) | Mar 09, 2023 |
| MSI           | X58 PLATINUM SLI            | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b99222314c](https://linux-hardware.org/?probe=b99222314c) | Mar 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4f64764c75](https://linux-hardware.org/?probe=4f64764c75) | Mar 08, 2023 |
| Dell          | 051FJ8 A02                  | [4c15877e95](https://linux-hardware.org/?probe=4c15877e95) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | [6ddf3ecd86](https://linux-hardware.org/?probe=6ddf3ecd86) | Mar 08, 2023 |
| ASRock        | 890GX Extreme3              | [4d59bfb158](https://linux-hardware.org/?probe=4d59bfb158) | Mar 08, 2023 |
| HP            | 83E9                        | [9a756f9158](https://linux-hardware.org/?probe=9a756f9158) | Mar 07, 2023 |
| ASRock        | G41M-GS3                    | [9e11e1f2af](https://linux-hardware.org/?probe=9e11e1f2af) | Mar 07, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [bfc1bf412e](https://linux-hardware.org/?probe=bfc1bf412e) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [da3b20e7c1](https://linux-hardware.org/?probe=da3b20e7c1) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [eb3f7a337f](https://linux-hardware.org/?probe=eb3f7a337f) | Mar 05, 2023 |
| Gigabyte      | B450M GAMING                | [b75483941a](https://linux-hardware.org/?probe=b75483941a) | Mar 05, 2023 |
| HP            | 339A                        | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [efd2d0c074](https://linux-hardware.org/?probe=efd2d0c074) | Mar 05, 2023 |
| MSI           | B350 GAMING PLUS            | [c3d6a142c0](https://linux-hardware.org/?probe=c3d6a142c0) | Mar 04, 2023 |
| ASUSTek       | PRIME Z390-A                | [87cdc5bd5a](https://linux-hardware.org/?probe=87cdc5bd5a) | Mar 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ca004eceae](https://linux-hardware.org/?probe=ca004eceae) | Mar 03, 2023 |
| Acer          | Aspire M3970                | [2708d5fa99](https://linux-hardware.org/?probe=2708d5fa99) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [141faab02f](https://linux-hardware.org/?probe=141faab02f) | Mar 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [c2d6b5218e](https://linux-hardware.org/?probe=c2d6b5218e) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [840dab3a7c](https://linux-hardware.org/?probe=840dab3a7c) | Mar 03, 2023 |
| Biostar       | H81MHV3 5.0                 | [6ea9159a52](https://linux-hardware.org/?probe=6ea9159a52) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8ce5103cac](https://linux-hardware.org/?probe=8ce5103cac) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [62c37af17b](https://linux-hardware.org/?probe=62c37af17b) | Mar 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [f942bae731](https://linux-hardware.org/?probe=f942bae731) | Mar 02, 2023 |
| ASRockRack    | X570D4U                     | [9c4b25d5dc](https://linux-hardware.org/?probe=9c4b25d5dc) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | [4207bf1ee6](https://linux-hardware.org/?probe=4207bf1ee6) | Mar 02, 2023 |
| ASUSTek       | Crosshair IV Formula        | [ed4f0e394a](https://linux-hardware.org/?probe=ed4f0e394a) | Mar 02, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [5b94fc8fa8](https://linux-hardware.org/?probe=5b94fc8fa8) | Mar 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [85456379c1](https://linux-hardware.org/?probe=85456379c1) | Mar 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [6126e81a28](https://linux-hardware.org/?probe=6126e81a28) | Mar 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b6930e4615](https://linux-hardware.org/?probe=b6930e4615) | Mar 01, 2023 |
| Gigabyte      | Z77X-UP4 TH                 | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [0e0b3360ba](https://linux-hardware.org/?probe=0e0b3360ba) | Feb 28, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [7f53a53eba](https://linux-hardware.org/?probe=7f53a53eba) | Feb 28, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| Dell          | 03KWTV A02                  | [8b6eae9fd5](https://linux-hardware.org/?probe=8b6eae9fd5) | Feb 26, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| MSI           | B450-A PRO MAX              | [f081452f55](https://linux-hardware.org/?probe=f081452f55) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [42fe607d11](https://linux-hardware.org/?probe=42fe607d11) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| ZOTAC         | MEK1                        | [a61a52d794](https://linux-hardware.org/?probe=a61a52d794) | Feb 24, 2023 |
| HP            | 8433 11                     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [59d0e692ef](https://linux-hardware.org/?probe=59d0e692ef) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [27a3c3c4c1](https://linux-hardware.org/?probe=27a3c3c4c1) | Feb 24, 2023 |
| Dell          | 0M6C7G A00                  | [8d8af65e26](https://linux-hardware.org/?probe=8d8af65e26) | Feb 23, 2023 |
| Dell          | 0M6C7G A00                  | [f8f5ea8885](https://linux-hardware.org/?probe=f8f5ea8885) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pop!_OS 22.04 | 1387     | 33.92%  |
| Pop!_OS 20.04 | 864      | 21.13%  |
| Pop!_OS 21.04 | 719      | 17.58%  |
| Pop!_OS 20.10 | 672      | 16.43%  |
| Pop!_OS 21.10 | 421      | 10.3%   |
| Pop!_OS 19.10 | 15       | 0.37%   |
| Pop!_OS 19.04 | 6        | 0.15%   |
| Pop!_OS 18.04 | 4        | 0.1%    |
| Pop!_OS 18.10 | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Pop!_OS | 3865     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.11.0-7620-generic      | 340      | 7.6%    |
| 5.8.0-7630-generic       | 315      | 7.04%   |
| 6.2.6-76060206-generic   | 303      | 6.77%   |
| 5.4.0-7634-generic       | 282      | 6.3%    |
| 5.8.0-7642-generic       | 203      | 4.54%   |
| 5.13.0-7614-generic      | 203      | 4.54%   |
| 5.4.0-7642-generic       | 187      | 4.18%   |
| 5.11.0-7614-generic      | 181      | 4.04%   |
| 5.17.5-76051705-generic  | 180      | 4.02%   |
| 6.0.12-76060006-generic  | 175      | 3.91%   |
| 5.13.0-7620-generic      | 171      | 3.82%   |
| 5.19.0-76051900-generic  | 144      | 3.22%   |
| 6.5.6-76060506-generic   | 112      | 2.5%    |
| 5.16.11-76051611-generic | 112      | 2.5%    |
| 5.15.15-76051515-generic | 109      | 2.44%   |
| 6.0.6-76060006-generic   | 102      | 2.28%   |
| 5.15.5-76051505-generic  | 92       | 2.06%   |
| 6.4.6-76060406-generic   | 89       | 1.99%   |
| 5.11.0-7612-generic      | 87       | 1.94%   |
| 6.6.6-76060606-generic   | 85       | 1.9%    |
| 5.8.0-7625-generic       | 78       | 1.74%   |
| 5.18.10-76051810-generic | 75       | 1.68%   |
| 5.11.0-7633-generic      | 71       | 1.59%   |
| 5.17.15-76051715-generic | 69       | 1.54%   |
| 5.16.19-76051619-generic | 65       | 1.45%   |
| 5.15.8-76051508-generic  | 63       | 1.41%   |
| 5.16.15-76051615-generic | 56       | 1.25%   |
| 6.5.4-76060504-generic   | 53       | 1.18%   |
| 5.15.11-76051511-generic | 47       | 1.05%   |
| 5.4.0-7626-generic       | 43       | 0.96%   |
| 6.2.0-76060200-generic   | 37       | 0.83%   |
| 6.1.11-76060111-generic  | 29       | 0.65%   |
| 5.15.23-76051523-generic | 29       | 0.65%   |
| 6.0.2-76060002-generic   | 28       | 0.63%   |
| 5.4.0-7625-generic       | 24       | 0.54%   |
| 5.4.0-7629-generic       | 21       | 0.47%   |
| 5.19.16-76051916-generic | 18       | 0.4%    |
| 6.6.10-76060610-generic  | 14       | 0.31%   |
| 6.0.3-76060003-generic   | 14       | 0.31%   |
| 5.3.0-7629-generic       | 5        | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 651      | 14.84%  |
| 5.8.0   | 568      | 12.95%  |
| 5.4.0   | 538      | 12.27%  |
| 5.13.0  | 371      | 8.46%   |
| 6.2.6   | 303      | 6.91%   |
| 6.0.12  | 180      | 4.1%    |
| 5.17.5  | 180      | 4.1%    |
| 5.19.0  | 144      | 3.28%   |
| 6.5.6   | 112      | 2.55%   |
| 5.16.11 | 112      | 2.55%   |
| 5.15.15 | 110      | 2.51%   |
| 6.0.6   | 103      | 2.35%   |
| 5.15.5  | 92       | 2.1%    |
| 6.4.6   | 89       | 2.03%   |
| 6.6.6   | 85       | 1.94%   |
| 5.18.10 | 75       | 1.71%   |
| 5.17.15 | 69       | 1.57%   |
| 5.16.19 | 65       | 1.48%   |
| 5.15.8  | 63       | 1.44%   |
| 5.16.15 | 56       | 1.28%   |
| 6.5.4   | 53       | 1.21%   |
| 5.15.11 | 47       | 1.07%   |
| 6.2.0   | 37       | 0.84%   |
| 6.1.11  | 29       | 0.66%   |
| 6.0.2   | 29       | 0.66%   |
| 5.15.23 | 29       | 0.66%   |
| 5.19.16 | 18       | 0.41%   |
| 5.3.0   | 17       | 0.39%   |
| 6.6.10  | 14       | 0.32%   |
| 6.0.3   | 14       | 0.32%   |
| 5.8.5   | 8        | 0.18%   |
| 5.0.0   | 6        | 0.14%   |
| 5.8.12  | 5        | 0.11%   |
| 6.3.7   | 3        | 0.07%   |
| 6.1.0   | 3        | 0.07%   |
| 5.7.8   | 3        | 0.07%   |
| 5.7.0   | 3        | 0.07%   |
| 5.6.16  | 3        | 0.07%   |
| 5.15.0  | 3        | 0.07%   |
| 6.7.1   | 2        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 653      | 15.06%  |
| 5.8     | 590      | 13.6%   |
| 5.4     | 540      | 12.45%  |
| 5.13    | 376      | 8.67%   |
| 5.15    | 343      | 7.91%   |
| 6.2     | 337      | 7.77%   |
| 6.0     | 321      | 7.4%    |
| 5.17    | 247      | 5.7%    |
| 5.16    | 224      | 5.16%   |
| 6.5     | 167      | 3.85%   |
| 5.19    | 162      | 3.74%   |
| 6.6     | 98       | 2.26%   |
| 6.4     | 90       | 2.08%   |
| 5.18    | 77       | 1.78%   |
| 6.1     | 35       | 0.81%   |
| 5.3     | 17       | 0.39%   |
| 5.7     | 14       | 0.32%   |
| 5.6     | 8        | 0.18%   |
| 5.10    | 8        | 0.18%   |
| 6.3     | 6        | 0.14%   |
| 5.0     | 6        | 0.14%   |
| 5.9     | 5        | 0.12%   |
| 5.14    | 5        | 0.12%   |
| 5.12    | 4        | 0.09%   |
| 6.7     | 2        | 0.05%   |
| 4.18    | 1        | 0.02%   |
| 4.15    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3865     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 3729     | 95.91%  |
| KDE5            | 47       | 1.21%   |
| KDE             | 33       | 0.85%   |
| Unknown         | 20       | 0.51%   |
| X-Cinnamon      | 19       | 0.49%   |
| MATE            | 9        | 0.23%   |
| XFCE            | 8        | 0.21%   |
| GNOME Flashback | 6        | 0.15%   |
| Cinnamon        | 5        | 0.13%   |
| i3              | 4        | 0.1%    |
| LXQt            | 3        | 0.08%   |
| Budgie          | 2        | 0.05%   |
| Unity           | 1        | 0.03%   |
| UKUI            | 1        | 0.03%   |
| Pantheon        | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3792     | 97.71%  |
| Wayland | 74       | 1.91%   |
| Unknown | 9        | 0.23%   |
| Tty     | 6        | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3273     | 84.07%  |
| GDM     | 345      | 8.86%   |
| GDM3    | 258      | 6.63%   |
| SDDM    | 12       | 0.31%   |
| TDM     | 3        | 0.08%   |
| LightDM | 2        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2199     | 56.37%  |
| en_GB   | 296      | 7.59%   |
| pt_BR   | 270      | 6.92%   |
| de_DE   | 221      | 5.67%   |
| C       | 140      | 3.59%   |
| en_AU   | 119      | 3.05%   |
| en_CA   | 106      | 2.72%   |
| fr_FR   | 77       | 1.97%   |
| it_IT   | 50       | 1.28%   |
| ru_RU   | 47       | 1.2%    |
| es_ES   | 43       | 1.1%    |
| pl_PL   | 34       | 0.87%   |
| nl_NL   | 28       | 0.72%   |
| sv_SE   | 26       | 0.67%   |
| Unknown | 23       | 0.59%   |
| pt_PT   | 15       | 0.38%   |
| fi_FI   | 15       | 0.38%   |
| es_AR   | 11       | 0.28%   |
| da_DK   | 11       | 0.28%   |
| fr_CA   | 10       | 0.26%   |
| es_CL   | 10       | 0.26%   |
| en_ZA   | 9        | 0.23%   |
| en_IN   | 9        | 0.23%   |
| en_DK   | 9        | 0.23%   |
| zh_TW   | 8        | 0.21%   |
| ja_JP   | 8        | 0.21%   |
| en_NZ   | 8        | 0.21%   |
| nl_BE   | 7        | 0.18%   |
| sk_SK   | 6        | 0.15%   |
| nb_NO   | 6        | 0.15%   |
| es_MX   | 5        | 0.13%   |
| de_AT   | 5        | 0.13%   |
| cs_CZ   | 5        | 0.13%   |
| zh_CN   | 4        | 0.1%    |
| tr_TR   | 4        | 0.1%    |
| hu_HU   | 4        | 0.1%    |
| hr_HR   | 4        | 0.1%    |
| fr_CH   | 4        | 0.1%    |
| de_CH   | 4        | 0.1%    |
| uk_UA   | 3        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3150     | 80.62%  |
| EFI  | 757      | 19.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3719     | 95.83%  |
| Overlay | 73       | 1.88%   |
| Btrfs   | 68       | 1.75%   |
| Xfs     | 8        | 0.21%   |
| Zfs     | 6        | 0.15%   |
| Unknown | 6        | 0.15%   |
| Tmpfs   | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3261     | 83.85%  |
| GPT     | 549      | 14.12%  |
| MBR     | 79       | 2.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3745     | 96.45%  |
| Yes       | 138      | 3.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3519     | 90.53%  |
| Yes       | 368      | 9.47%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1113     | 28.8%   |
| Gigabyte Technology                  | 744      | 19.25%  |
| MSI                                  | 590      | 15.27%  |
| ASRock                               | 375      | 9.7%    |
| Dell                                 | 289      | 7.48%   |
| Hewlett-Packard                      | 195      | 5.05%   |
| Lenovo                               | 93       | 2.41%   |
| Intel                                | 72       | 1.86%   |
| System76                             | 36       | 0.93%   |
| Acer                                 | 30       | 0.78%   |
| Unknown                              | 27       | 0.7%    |
| Pegatron                             | 25       | 0.65%   |
| Biostar                              | 22       | 0.57%   |
| Alienware                            | 21       | 0.54%   |
| Fujitsu                              | 19       | 0.49%   |
| Foxconn                              | 19       | 0.49%   |
| Apple                                | 16       | 0.41%   |
| ECS                                  | 15       | 0.39%   |
| Huanan                               | 13       | 0.34%   |
| Positivo                             | 12       | 0.31%   |
| Supermicro                           | 10       | 0.26%   |
| Medion                               | 10       | 0.26%   |
| BESSTAR Tech                         | 9        | 0.23%   |
| PCWare                               | 8        | 0.21%   |
| Gateway                              | 7        | 0.18%   |
| MACHINIST                            | 6        | 0.16%   |
| EVGA                                 | 6        | 0.16%   |
| Minix                                | 5        | 0.13%   |
| AZW                                  | 5        | 0.13%   |
| NZXT                                 | 4        | 0.1%    |
| Samsung Electronics                  | 3        | 0.08%   |
| OEM                                  | 3        | 0.08%   |
| MAXSUN                               | 3        | 0.08%   |
| eMachines                            | 3        | 0.08%   |
| AMI                                  | 3        | 0.08%   |
| TYAN Computer                        | 2        | 0.05%   |
| T-bao                                | 2        | 0.05%   |
| Shuttle                              | 2        | 0.05%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.05%   |
| Packard Bell                         | 2        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 96       | 2.48%   |
| ASUS TUF Gaming X570-PLUS      | 44       | 1.14%   |
| Gigabyte B450M DS3H            | 34       | 0.88%   |
| MSI MS-7C02                    | 33       | 0.85%   |
| ASUS ROG STRIX B550-F GAMING   | 32       | 0.83%   |
| ASUS ROG STRIX B450-F GAMING   | 31       | 0.8%    |
| MSI MS-7C37                    | 30       | 0.78%   |
| MSI MS-7B86                    | 29       | 0.75%   |
| Unknown                        | 28       | 0.72%   |
| Dell OptiPlex 9020             | 25       | 0.65%   |
| ASUS PRIME B450M-A             | 24       | 0.62%   |
| System76 Thelio                | 21       | 0.54%   |
| Gigabyte X570 AORUS ELITE      | 21       | 0.54%   |
| Dell OptiPlex 7010             | 19       | 0.49%   |
| Gigabyte A320M-S2H             | 18       | 0.47%   |
| MSI MS-7C91                    | 17       | 0.44%   |
| ASRock B450M Pro4              | 17       | 0.44%   |
| ASRock B450M Steel Legend      | 16       | 0.41%   |
| Gigabyte X570 AORUS MASTER     | 14       | 0.36%   |
| Gigabyte B450 AORUS PRO WIFI   | 14       | 0.36%   |
| Gigabyte B450 AORUS M          | 14       | 0.36%   |
| ASUS ROG STRIX B550-I GAMING   | 14       | 0.36%   |
| MSI MS-7C84                    | 13       | 0.34%   |
| MSI MS-7B89                    | 13       | 0.34%   |
| MSI MS-7B79                    | 13       | 0.34%   |
| Gigabyte B550I AORUS PRO AX    | 13       | 0.34%   |
| Gigabyte B450 I AORUS PRO WIFI | 13       | 0.34%   |
| ASUS PRIME B450M-GAMING/BR     | 13       | 0.34%   |
| MSI MS-7C95                    | 12       | 0.31%   |
| MSI MS-7A38                    | 12       | 0.31%   |
| ASUS TUF Gaming B550M-PLUS     | 12       | 0.31%   |
| ASUS PRIME A320M-K             | 12       | 0.31%   |
| MSI MS-7C56                    | 11       | 0.28%   |
| MSI MS-7A34                    | 11       | 0.28%   |
| MSI MS-7817                    | 11       | 0.28%   |
| MSI MS-7693                    | 11       | 0.28%   |
| HP Compaq 8200 Elite SFF PC    | 11       | 0.28%   |
| Gigabyte B75M-D3H              | 11       | 0.28%   |
| Dell OptiPlex 790              | 11       | 0.28%   |
| Dell OptiPlex 3020             | 11       | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 267      | 6.91%   |
| ASUS PRIME             | 210      | 5.43%   |
| Dell OptiPlex          | 160      | 4.14%   |
| ASUS TUF               | 141      | 3.65%   |
| ASUS All               | 96       | 2.48%   |
| Gigabyte X570          | 79       | 2.04%   |
| HP Compaq              | 60       | 1.55%   |
| Gigabyte B450          | 55       | 1.42%   |
| Lenovo ThinkCentre     | 52       | 1.35%   |
| Gigabyte B450M         | 51       | 1.32%   |
| Dell Precision         | 50       | 1.29%   |
| ASRock B450M           | 40       | 1.03%   |
| ASRock X570            | 37       | 0.96%   |
| System76 Thelio        | 36       | 0.93%   |
| Gigabyte B550          | 34       | 0.88%   |
| MSI MS-7C02            | 33       | 0.85%   |
| MSI MS-7C37            | 30       | 0.78%   |
| Dell Inspiron          | 30       | 0.78%   |
| MSI MS-7B86            | 29       | 0.75%   |
| Unknown                | 28       | 0.72%   |
| ASUS SABERTOOTH        | 24       | 0.62%   |
| ASRock B450            | 24       | 0.62%   |
| HP EliteDesk           | 23       | 0.6%    |
| Gigabyte A320M-S2H     | 22       | 0.57%   |
| Dell XPS               | 22       | 0.57%   |
| Gigabyte Z390          | 20       | 0.52%   |
| Acer Aspire            | 20       | 0.52%   |
| Gigabyte GA-78LMT-USB3 | 19       | 0.49%   |
| Gigabyte B550M         | 18       | 0.47%   |
| ASUS M5A78L-M          | 18       | 0.47%   |
| MSI MS-7C91            | 17       | 0.44%   |
| ASUS P8Z77-V           | 17       | 0.44%   |
| ASUS M5A97             | 17       | 0.44%   |
| Lenovo IdeaCentre      | 15       | 0.39%   |
| ASUS Crosshair         | 15       | 0.39%   |
| HP ProDesk             | 14       | 0.36%   |
| Alienware Aurora       | 14       | 0.36%   |
| MSI MS-7C84            | 13       | 0.34%   |
| MSI MS-7B89            | 13       | 0.34%   |
| MSI MS-7B79            | 13       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 590      | 15.27%  |
| 2020 | 449      | 11.62%  |
| 2019 | 443      | 11.46%  |
| 2012 | 302      | 7.81%   |
| 2017 | 275      | 7.12%   |
| 2013 | 262      | 6.78%   |
| 2014 | 230      | 5.95%   |
| 2011 | 220      | 5.69%   |
| 2021 | 218      | 5.64%   |
| 2015 | 160      | 4.14%   |
| 2016 | 149      | 3.86%   |
| 2010 | 138      | 3.57%   |
| 2022 | 132      | 3.42%   |
| 2009 | 126      | 3.26%   |
| 2008 | 73       | 1.89%   |
| 2007 | 55       | 1.42%   |
| 2023 | 30       | 0.78%   |
| 2006 | 12       | 0.31%   |
| 2005 | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3865     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3861     | 99.87%  |
| Enabled  | 5        | 0.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3863     | 99.95%  |
| Yes  | 2        | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1262     | 31.96%  |
| 32.01-64.0      | 881      | 22.31%  |
| 8.01-16.0       | 686      | 17.37%  |
| 4.01-8.0        | 366      | 9.27%   |
| 64.01-256.0     | 282      | 7.14%   |
| 3.01-4.0        | 274      | 6.94%   |
| 24.01-32.0      | 145      | 3.67%   |
| 1.01-2.0        | 32       | 0.81%   |
| 2.01-3.0        | 12       | 0.3%    |
| More than 256.0 | 8        | 0.2%    |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1083     | 25.35%  |
| 2.01-3.0    | 1071     | 25.06%  |
| 1.01-2.0    | 933      | 21.83%  |
| 3.01-4.0    | 758      | 17.74%  |
| 8.01-16.0   | 336      | 7.86%   |
| 16.01-24.0  | 45       | 1.05%   |
| 32.01-64.0  | 18       | 0.42%   |
| 24.01-32.0  | 18       | 0.42%   |
| 0.51-1.0    | 8        | 0.19%   |
| 64.01-256.0 | 3        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1291     | 32.19%  |
| 2      | 1214     | 30.27%  |
| 3      | 729      | 18.18%  |
| 4      | 424      | 10.57%  |
| 5      | 182      | 4.54%   |
| 6      | 81       | 2.02%   |
| 7      | 33       | 0.82%   |
| 0      | 18       | 0.45%   |
| 8      | 12       | 0.3%    |
| 11     | 8        | 0.2%    |
| 9      | 8        | 0.2%    |
| 10     | 3        | 0.07%   |
| 26     | 1        | 0.02%   |
| 23     | 1        | 0.02%   |
| 20     | 1        | 0.02%   |
| 19     | 1        | 0.02%   |
| 14     | 1        | 0.02%   |
| 13     | 1        | 0.02%   |
| 12     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2663     | 68.3%   |
| Yes       | 1236     | 31.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3818     | 98.76%  |
| No        | 48       | 1.24%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2098     | 53.73%  |
| No        | 1807     | 46.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2299     | 58.78%  |
| Yes       | 1612     | 41.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1337     | 34.41%  |
| Brazil       | 350      | 9.01%   |
| Germany      | 305      | 7.85%   |
| UK           | 213      | 5.48%   |
| Canada       | 206      | 5.3%    |
| Australia    | 143      | 3.68%   |
| Netherlands  | 88       | 2.27%   |
| Italy        | 87       | 2.24%   |
| France       | 86       | 2.21%   |
| Sweden       | 75       | 1.93%   |
| Poland       | 65       | 1.67%   |
| Russia       | 60       | 1.54%   |
| Spain        | 44       | 1.13%   |
| Finland      | 43       | 1.11%   |
| South Africa | 41       | 1.06%   |
| India        | 41       | 1.06%   |
| Switzerland  | 32       | 0.82%   |
| Norway       | 31       | 0.8%    |
| Austria      | 31       | 0.8%    |
| Mexico       | 30       | 0.77%   |
| Romania      | 29       | 0.75%   |
| Denmark      | 28       | 0.72%   |
| New Zealand  | 27       | 0.69%   |
| Greece       | 27       | 0.69%   |
| Argentina    | 27       | 0.69%   |
| Portugal     | 26       | 0.67%   |
| Belgium      | 25       | 0.64%   |
| Philippines  | 21       | 0.54%   |
| Japan        | 18       | 0.46%   |
| Hungary      | 18       | 0.46%   |
| Czechia      | 18       | 0.46%   |
| Bulgaria     | 18       | 0.46%   |
| Chile        | 16       | 0.41%   |
| Serbia       | 13       | 0.33%   |
| Malaysia     | 13       | 0.33%   |
| Ireland      | 13       | 0.33%   |
| Ukraine      | 12       | 0.31%   |
| Slovakia     | 12       | 0.31%   |
| Lithuania    | 12       | 0.31%   |
| Israel       | 11       | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 43       | 1.06%   |
| Sydney         | 40       | 0.99%   |
| Berlin         | 30       | 0.74%   |
| Melbourne      | 27       | 0.67%   |
| Rio de Janeiro | 25       | 0.62%   |
| Helsinki       | 21       | 0.52%   |
| Brisbane       | 21       | 0.52%   |
| Miami          | 20       | 0.49%   |
| Denver         | 19       | 0.47%   |
| Chicago        | 18       | 0.45%   |
| Vienna         | 17       | 0.42%   |
| Seattle        | 17       | 0.42%   |
| Browning       | 16       | 0.4%    |
| Warsaw         | 15       | 0.37%   |
| Toronto        | 15       | 0.37%   |
| Perth          | 15       | 0.37%   |
| Milan          | 15       | 0.37%   |
| Moscow         | 14       | 0.35%   |
| London         | 14       | 0.35%   |
| Edmonton       | 14       | 0.35%   |
| Phoenix        | 13       | 0.32%   |
| Hamburg        | 13       | 0.32%   |
| Dallas         | 13       | 0.32%   |
| Amsterdam      | 13       | 0.32%   |
| Adelaide       | 13       | 0.32%   |
| Sofia          | 12       | 0.3%    |
| Montreal       | 12       | 0.3%    |
| Auckland       | 12       | 0.3%    |
| Athens         | 12       | 0.3%    |
| Washington     | 11       | 0.27%   |
| St Louis       | 11       | 0.27%   |
| New York       | 11       | 0.27%   |
| Cologne        | 11       | 0.27%   |
| Cape Town      | 11       | 0.27%   |
| Calgary        | 11       | 0.27%   |
| Budapest       | 11       | 0.27%   |
| Atlanta        | 11       | 0.27%   |
| Rome           | 10       | 0.25%   |
| Johannesburg   | 10       | 0.25%   |
| Cleveland      | 10       | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1354     | 2336   | 17.72%  |
| Seagate                     | 1295     | 2045   | 16.95%  |
| WDC                         | 1229     | 1884   | 16.08%  |
| SanDisk                     | 478      | 641    | 6.25%   |
| Kingston                    | 463      | 615    | 6.06%   |
| Crucial                     | 362      | 511    | 4.74%   |
| Toshiba                     | 318      | 407    | 4.16%   |
| Hitachi                     | 184      | 251    | 2.41%   |
| Intel                       | 157      | 225    | 2.05%   |
| Phison                      | 154      | 227    | 2.02%   |
| A-DATA Technology           | 121      | 150    | 1.58%   |
| Micron/Crucial Technology   | 95       | 127    | 1.24%   |
| Silicon Motion              | 89       | 121    | 1.16%   |
| China                       | 89       | 130    | 1.16%   |
| PNY                         | 88       | 113    | 1.15%   |
| Unknown                     | 67       | 126    | 0.88%   |
| Phison Electronics          | 66       | 100    | 0.86%   |
| HGST                        | 59       | 79     | 0.77%   |
| SK hynix                    | 56       | 78     | 0.73%   |
| OCZ                         | 49       | 68     | 0.64%   |
| SPCC                        | 43       | 62     | 0.56%   |
| XPG                         | 40       | 54     | 0.52%   |
| Micron Technology           | 40       | 55     | 0.52%   |
| Realtek Semiconductor       | 38       | 45     | 0.5%    |
| Patriot                     | 34       | 48     | 0.44%   |
| Corsair                     | 34       | 47     | 0.44%   |
| Team                        | 33       | 40     | 0.43%   |
| Kingston Technology Company | 32       | 39     | 0.42%   |
| Maxtor                      | 31       | 32     | 0.41%   |
| Intenso                     | 26       | 33     | 0.34%   |
| Lexar                       | 18       | 21     | 0.24%   |
| JMicron Technology          | 18       | 30     | 0.24%   |
| Hewlett-Packard             | 18       | 26     | 0.24%   |
| Gigabyte Technology         | 18       | 18     | 0.24%   |
| Apple                       | 16       | 19     | 0.21%   |
| Transcend                   | 15       | 18     | 0.2%    |
| KingSpec                    | 15       | 19     | 0.2%    |
| ADATA Technology            | 15       | 18     | 0.2%    |
| SABRENT                     | 14       | 15     | 0.18%   |
| Netac                       | 14       | 16     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                         | 131      | 1.47%   |
| Kingston SA400S37240G 240GB SSD                    | 120      | 1.35%   |
| Samsung NVMe SSD Drive 500GB                       | 117      | 1.31%   |
| Seagate ST2000DM008-2FR102 2TB                     | 110      | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB                     | 103      | 1.16%   |
| Samsung SSD 850 EVO 250GB                          | 103      | 1.16%   |
| Samsung SSD 850 EVO 500GB                          | 91       | 1.02%   |
| Seagate ST500DM002-1BD142 500GB                    | 85       | 0.95%   |
| Samsung SSD 860 EVO 1TB                            | 85       | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 85       | 0.95%   |
| Samsung SSD 860 EVO 500GB                          | 83       | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 72       | 0.81%   |
| Kingston SA400S37120G 120GB SSD                    | 70       | 0.79%   |
| SanDisk NVMe SSD Drive 1TB                         | 68       | 0.76%   |
| SanDisk NVMe SSD Drive 500GB                       | 66       | 0.74%   |
| Crucial CT1000MX500SSD1 1TB                        | 61       | 0.68%   |
| Kingston SA400S37480G 480GB SSD                    | 58       | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 56       | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB                     | 53       | 0.59%   |
| Toshiba DT01ACA100 1TB                             | 50       | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB                     | 49       | 0.55%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 47       | 0.53%   |
| Crucial CT500MX500SSD1 500GB                       | 47       | 0.53%   |
| Phison NVMe SSD Drive 1TB                          | 43       | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB                     | 42       | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                   | 42       | 0.47%   |
| Samsung SSD 870 QVO 1TB                            | 39       | 0.44%   |
| Micron/Crucial NVMe SSD Drive 1TB                  | 37       | 0.42%   |
| Crucial CT240BX500SSD1 240GB                       | 37       | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                       | 35       | 0.39%   |
| Samsung SSD 860 EVO 250GB                          | 35       | 0.39%   |
| Samsung SSD 840 EVO 250GB                          | 34       | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 33       | 0.37%   |
| Toshiba HDWD110 1TB                                | 32       | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB                     | 32       | 0.36%   |
| Toshiba DT01ACA200 2TB                             | 31       | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB                     | 31       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB                     | 31       | 0.35%   |
| Samsung SSD 860 QVO 1TB                            | 30       | 0.34%   |
| Seagate Expansion 1TB                              | 29       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1258     | 1943   | 40.69%  |
| WDC                 | 1060     | 1596   | 34.28%  |
| Toshiba             | 283      | 362    | 9.15%   |
| Hitachi             | 184      | 251    | 5.95%   |
| Samsung Electronics | 127      | 153    | 4.11%   |
| HGST                | 59       | 79     | 1.91%   |
| Maxtor              | 27       | 28     | 0.87%   |
| Unknown             | 22       | 31     | 0.71%   |
| JMicron Technology  | 12       | 20     | 0.39%   |
| Apple               | 11       | 13     | 0.36%   |
| TO Exter            | 7        | 10     | 0.23%   |
| Fujitsu             | 5        | 9      | 0.16%   |
| ASMT                | 5        | 5      | 0.16%   |
| SABRENT             | 3        | 4      | 0.1%    |
| Hewlett-Packard     | 3        | 5      | 0.1%    |
| External            | 3        | 3      | 0.1%    |
| ExcelStor           | 3        | 3      | 0.1%    |
| USB                 | 2        | 3      | 0.06%   |
| Magnetic Data       | 2        | 2      | 0.06%   |
| LaCie               | 2        | 3      | 0.06%   |
| Unknown             | 2        | 3      | 0.06%   |
| XrayDisk            | 1        | 1      | 0.03%   |
| WD MediaMax         | 1        | 2      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| OEM                 | 1        | 1      | 0.03%   |
| MaxDigital          | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 2      | 0.03%   |
| HPE                 | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| Glyph               | 1        | 2      | 0.03%   |
| ASMT109x            | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 748      | 1188   | 26.7%   |
| Kingston            | 388      | 509    | 13.85%  |
| Crucial             | 327      | 454    | 11.67%  |
| SanDisk             | 237      | 311    | 8.46%   |
| WDC                 | 192      | 245    | 6.85%   |
| A-DATA Technology   | 105      | 132    | 3.75%   |
| China               | 88       | 129    | 3.14%   |
| PNY                 | 87       | 112    | 3.1%    |
| Intel               | 67       | 94     | 2.39%   |
| OCZ                 | 48       | 64     | 1.71%   |
| SPCC                | 38       | 48     | 1.36%   |
| Patriot             | 34       | 48     | 1.21%   |
| Team                | 30       | 36     | 1.07%   |
| SK hynix            | 30       | 44     | 1.07%   |
| Corsair             | 26       | 33     | 0.93%   |
| Micron Technology   | 23       | 27     | 0.82%   |
| Toshiba             | 19       | 21     | 0.68%   |
| Seagate             | 19       | 34     | 0.68%   |
| Intenso             | 19       | 26     | 0.68%   |
| Lexar               | 16       | 19     | 0.57%   |
| Transcend           | 15       | 18     | 0.54%   |
| KingSpec            | 15       | 19     | 0.54%   |
| Apacer              | 14       | 18     | 0.5%    |
| Hewlett-Packard     | 13       | 19     | 0.46%   |
| Gigabyte Technology | 12       | 12     | 0.43%   |
| SABRENT             | 11       | 11     | 0.39%   |
| Netac               | 11       | 13     | 0.39%   |
| GOODRAM             | 10       | 11     | 0.36%   |
| LITEONIT            | 9        | 10     | 0.32%   |
| Plextor             | 8        | 10     | 0.29%   |
| Mushkin             | 8        | 10     | 0.29%   |
| LITEON              | 7        | 12     | 0.25%   |
| KingDian            | 6        | 10     | 0.21%   |
| Verbatim            | 5        | 9      | 0.18%   |
| ASMT                | 5        | 10     | 0.18%   |
| OWC                 | 4        | 13     | 0.14%   |
| Maxtor              | 4        | 4      | 0.14%   |
| Integral            | 4        | 4      | 0.14%   |
| Dogfish             | 4        | 5      | 0.14%   |
| Apple               | 4        | 5      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2412     | 4541   | 37.68%  |
| SSD     | 2255     | 3918   | 35.23%  |
| NVMe    | 1574     | 2646   | 24.59%  |
| Unknown | 143      | 245    | 2.23%   |
| MMC     | 17       | 21     | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3352     | 8167   | 63.81%  |
| NVMe | 1572     | 2636   | 29.93%  |
| SAS  | 312      | 547    | 5.94%   |
| MMC  | 17       | 21     | 0.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 2433     | 4199   | 47.58%  |
| 0.51-1.0        | 1496     | 2363   | 29.26%  |
| 1.01-2.0        | 642      | 972    | 12.56%  |
| 3.01-4.0        | 224      | 388    | 4.38%   |
| 4.01-10.0       | 152      | 280    | 2.97%   |
| 2.01-3.0        | 144      | 209    | 2.82%   |
| 10.01-20.0      | 21       | 47     | 0.41%   |
| More than 100.0 | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 911      | 22.35%  |
| 251-500        | 809      | 19.85%  |
| 501-1000       | 807      | 19.8%   |
| 1001-2000      | 565      | 13.86%  |
| More than 3000 | 430      | 10.55%  |
| 2001-3000      | 242      | 5.94%   |
| 51-100         | 131      | 3.21%   |
| 1-20           | 94       | 2.31%   |
| 21-50          | 59       | 1.45%   |
| Unknown        | 28       | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1280     | 30.03%  |
| 21-50          | 726      | 17.03%  |
| 101-250        | 544      | 12.76%  |
| 51-100         | 444      | 10.42%  |
| 251-500        | 413      | 9.69%   |
| 501-1000       | 333      | 7.81%   |
| 1001-2000      | 246      | 5.77%   |
| More than 3000 | 159      | 3.73%   |
| 2001-3000      | 90       | 2.11%   |
| Unknown        | 28       | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4        | 4      | 2.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4        | 4      | 2.34%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3        | 4      | 1.75%   |
| Seagate ST1000DM003-9YN162 1TB        | 3        | 3      | 1.75%   |
| Samsung Electronics HD502HI 500GB     | 3        | 4      | 1.75%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 5      | 1.75%   |
| Kingston SA400S37120G 120GB SSD       | 3        | 5      | 1.75%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2        | 2      | 1.17%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2        | 2      | 1.17%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2        | 3      | 1.17%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 1.17%   |
| Toshiba HDWD110 1TB                   | 2        | 2      | 1.17%   |
| Seagate ST3250310AS 250GB             | 2        | 4      | 1.17%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 1.17%   |
| Samsung Electronics SSD 850 EVO 250GB | 2        | 2      | 1.17%   |
| Samsung Electronics HD103SJ 1TB       | 2        | 2      | 1.17%   |
| Hitachi HDS721010CLA332 1TB           | 2        | 2      | 1.17%   |
| Hitachi HDP725050GLA360 500GB         | 2        | 2      | 1.17%   |
| Crucial CT525MX300SSD1 528GB          | 2        | 2      | 1.17%   |
| China SSD 240GB                       | 2        | 2      | 1.17%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1        | 1      | 0.58%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1        | 1      | 0.58%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1        | 1      | 0.58%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1        | 1      | 0.58%   |
| WDC WD5001AALS-00J7B1 500GB           | 1        | 1      | 0.58%   |
| WDC WD5000LPLX-00ZNTT0 500GB          | 1        | 2      | 0.58%   |
| WDC WD5000BEVT-75A0RT0 500GB          | 1        | 2      | 0.58%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 0.58%   |
| WDC WD5000AAKX-753CA1 500GB           | 1        | 1      | 0.58%   |
| WDC WD5000AAKS-41YGA1 500GB           | 1        | 1      | 0.58%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 0.58%   |
| WDC WD5000AADS-00M2B0 500GB           | 1        | 1      | 0.58%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 0.58%   |
| WDC WD30EZRX-00SPEB0 3TB              | 1        | 1      | 0.58%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1        | 1      | 0.58%   |
| WDC WD20PURZ-85AKKY0 2TB              | 1        | 1      | 0.58%   |
| WDC WD20PURX-64P6ZY0 2TB              | 1        | 1      | 0.58%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 0.58%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 1      | 0.58%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 9      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 45       | 55     | 27.44%  |
| WDC                         | 42       | 55     | 25.61%  |
| Samsung Electronics         | 24       | 31     | 14.63%  |
| Kingston                    | 8        | 12     | 4.88%   |
| Toshiba                     | 7        | 7      | 4.27%   |
| Hitachi                     | 6        | 7      | 3.66%   |
| HGST                        | 6        | 6      | 3.66%   |
| Crucial                     | 4        | 4      | 2.44%   |
| SanDisk                     | 3        | 3      | 1.83%   |
| Intel                       | 2        | 2      | 1.22%   |
| China                       | 2        | 2      | 1.22%   |
| A-DATA Technology           | 2        | 2      | 1.22%   |
| Team                        | 1        | 1      | 0.61%   |
| SPCC                        | 1        | 1      | 0.61%   |
| SABRENT                     | 1        | 1      | 0.61%   |
| S3+                         | 1        | 1      | 0.61%   |
| Plextor                     | 1        | 1      | 0.61%   |
| Micron Technology           | 1        | 1      | 0.61%   |
| Maxtor                      | 1        | 1      | 0.61%   |
| Kingston Technology Company | 1        | 1      | 0.61%   |
| Intenso                     | 1        | 1      | 0.61%   |
| Flashwar                    | 1        | 1      | 0.61%   |
| BAITITON                    | 1        | 1      | 0.61%   |
| ASMT                        | 1        | 1      | 0.61%   |
| Apple                       | 1        | 1      | 0.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 45       | 55     | 37.82%  |
| WDC                 | 42       | 55     | 35.29%  |
| Samsung Electronics | 11       | 12     | 9.24%   |
| Toshiba             | 7        | 7      | 5.88%   |
| Hitachi             | 6        | 7      | 5.04%   |
| HGST                | 6        | 6      | 5.04%   |
| Maxtor              | 1        | 1      | 0.84%   |
| Apple               | 1        | 1      | 0.84%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 107      | 144    | 69.93%  |
| SSD  | 40       | 49     | 26.14%  |
| NVMe | 6        | 6      | 3.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 50%     |
| Patriot Pyro SSD 120GB          | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| Patriot | 1        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3308     | 9583   | 80.68%  |
| Works    | 646      | 1585   | 15.76%  |
| Malfunc  | 143      | 199    | 3.49%   |
| Failed   | 2        | 3      | 0.05%   |
| Limited  | 1        | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2084     | 33.75%  |
| AMD                              | 1750     | 28.34%  |
| Samsung Electronics              | 698      | 11.31%  |
| SanDisk                          | 277      | 4.49%   |
| ASMedia Technology               | 233      | 3.77%   |
| Phison Electronics               | 228      | 3.69%   |
| Micron/Crucial Technology        | 132      | 2.14%   |
| Kingston Technology Company      | 112      | 1.81%   |
| Silicon Motion                   | 97       | 1.57%   |
| Marvell Technology Group         | 97       | 1.57%   |
| JMicron Technology               | 88       | 1.43%   |
| Nvidia                           | 65       | 1.05%   |
| ADATA Technology                 | 62       | 1%      |
| Realtek Semiconductor            | 48       | 0.78%   |
| SK hynix                         | 27       | 0.44%   |
| Broadcom / LSI                   | 23       | 0.37%   |
| Micron Technology                | 20       | 0.32%   |
| Toshiba America Info Systems     | 19       | 0.31%   |
| Seagate Technology               | 19       | 0.31%   |
| LSI Logic / Symbios Logic        | 17       | 0.28%   |
| VIA Technologies                 | 12       | 0.19%   |
| Lite-On Technology               | 9        | 0.15%   |
| MAXIO Technology (Hangzhou)      | 7        | 0.11%   |
| Solidigm                         | 6        | 0.1%    |
| Silicon Image                    | 6        | 0.1%    |
| Shenzhen Longsys Electronics     | 6        | 0.1%    |
| INNOGRIT                         | 6        | 0.1%    |
| Adaptec                          | 5        | 0.08%   |
| KIOXIA                           | 4        | 0.06%   |
| HighPoint Technologies           | 3        | 0.05%   |
| Union Memory (Shenzhen)          | 2        | 0.03%   |
| Solid State Storage Technology   | 2        | 0.03%   |
| Silicon Integrated Systems [SiS] | 2        | 0.03%   |
| Hewlett-Packard                  | 2        | 0.03%   |
| OCZ Technology Group             | 1        | 0.02%   |
| Netac Technology                 | 1        | 0.02%   |
| Integrated Technology Express    | 1        | 0.02%   |
| Biwin Storage Technology         | 1        | 0.02%   |
| Beijing Starblaze Technology     | 1        | 0.02%   |
| Apple                            | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1087     | 14.41%  |
| AMD 400 Series Chipset SATA Controller                                                  | 480      | 6.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 423      | 5.61%   |
| AMD 500 Series Chipset SATA Controller                                                  | 279      | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 235      | 3.12%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 221      | 2.93%   |
| Intel SATA Controller [RAID Mode]                                                       | 188      | 2.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 179      | 2.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 170      | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 167      | 2.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 142      | 1.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 131      | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 120      | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 119      | 1.58%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 109      | 1.45%   |
| Phison E12 NVMe Controller                                                              | 106      | 1.41%   |
| AMD 300 Series Chipset SATA Controller                                                  | 89       | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 88       | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 86       | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 83       | 1.1%    |
| AMD FCH SATA Controller D                                                               | 82       | 1.09%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 78       | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 78       | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 77       | 1.02%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 75       | 0.99%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 73       | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 68       | 0.9%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 66       | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 64       | 0.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 60       | 0.8%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 57       | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 54       | 0.72%   |
| AMD 600 Series Chipset SATA Controller                                                  | 54       | 0.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 53       | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 52       | 0.69%   |
| Intel SSD 660P Series                                                                   | 51       | 0.68%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 47       | 0.62%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 47       | 0.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 47       | 0.62%   |
| Nvidia MCP61 SATA Controller                                                            | 46       | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3315     | 56.94%  |
| NVMe | 1574     | 27.04%  |
| IDE  | 603      | 10.36%  |
| RAID | 281      | 4.83%   |
| SAS  | 36       | 0.62%   |
| SCSI | 13       | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2054     | 53.14%  |
| AMD    | 1811     | 46.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 158      | 4.06%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 123      | 3.16%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 75       | 1.93%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 72       | 1.85%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 64       | 1.65%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 64       | 1.65%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 62       | 1.59%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 62       | 1.59%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 57       | 1.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 51       | 1.31%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 48       | 1.23%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 45       | 1.16%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 45       | 1.16%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 43       | 1.11%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 43       | 1.11%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 42       | 1.08%   |
| AMD FX-8350 Eight-Core Processor            | 39       | 1%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 38       | 0.98%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 37       | 0.95%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 37       | 0.95%   |
| AMD FX-6300 Six-Core Processor              | 36       | 0.93%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 35       | 0.9%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 34       | 0.87%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 34       | 0.87%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 34       | 0.87%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 31       | 0.8%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 31       | 0.8%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 30       | 0.77%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 28       | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 28       | 0.72%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 26       | 0.67%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 25       | 0.64%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 25       | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 25       | 0.64%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 25       | 0.64%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 23       | 0.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 22       | 0.57%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 22       | 0.57%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 22       | 0.57%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 22       | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 628      | 16.17%  |
| AMD Ryzen 5             | 620      | 15.97%  |
| Intel Core i7           | 587      | 15.12%  |
| AMD Ryzen 7             | 437      | 11.25%  |
| AMD Ryzen 9             | 230      | 5.92%   |
| Intel Core i3           | 188      | 4.84%   |
| Intel Xeon              | 186      | 4.79%   |
| AMD FX                  | 134      | 3.45%   |
| Other                   | 119      | 3.06%   |
| AMD Ryzen 3             | 69       | 1.78%   |
| Intel Core i9           | 66       | 1.7%    |
| Intel Core 2 Duo        | 58       | 1.49%   |
| AMD Ryzen Threadripper  | 52       | 1.34%   |
| Intel Pentium           | 51       | 1.31%   |
| Intel Core 2 Quad       | 51       | 1.31%   |
| Intel Celeron           | 43       | 1.11%   |
| AMD Phenom II X4        | 35       | 0.9%    |
| Intel Pentium Dual-Core | 31       | 0.8%    |
| AMD A10                 | 29       | 0.75%   |
| AMD A8                  | 27       | 0.7%    |
| AMD Athlon II X2        | 26       | 0.67%   |
| AMD Athlon              | 19       | 0.49%   |
| Intel Core 2            | 17       | 0.44%   |
| AMD Athlon II X4        | 17       | 0.44%   |
| AMD A6                  | 15       | 0.39%   |
| AMD Phenom II X6        | 14       | 0.36%   |
| AMD A4                  | 13       | 0.33%   |
| AMD Ryzen 5 PRO         | 12       | 0.31%   |
| AMD Athlon 64 X2        | 11       | 0.28%   |
| Intel Atom              | 10       | 0.26%   |
| AMD Phenom              | 9        | 0.23%   |
| Intel Pentium Dual      | 8        | 0.21%   |
| AMD Athlon X4           | 8        | 0.21%   |
| Intel Pentium Gold      | 7        | 0.18%   |
| Intel Pentium D         | 6        | 0.15%   |
| AMD Sempron             | 5        | 0.13%   |
| AMD Ryzen 7 PRO         | 5        | 0.13%   |
| AMD Ryzen 3 PRO         | 4        | 0.1%    |
| AMD Phenom II X3        | 4        | 0.1%    |
| AMD Athlon II X3        | 4        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1423     | 36.66%  |
| 6      | 826      | 21.28%  |
| 8      | 602      | 15.51%  |
| 2      | 516      | 13.29%  |
| 12     | 194      | 5%      |
| 16     | 123      | 3.17%   |
| 3      | 56       | 1.44%   |
| 10     | 48       | 1.24%   |
| 1      | 32       | 0.82%   |
| 24     | 25       | 0.64%   |
| 32     | 16       | 0.41%   |
| 14     | 13       | 0.33%   |
| 64     | 4        | 0.1%    |
| 18     | 2        | 0.05%   |
| 36     | 1        | 0.03%   |
| 28     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3823     | 98.91%  |
| 2      | 42       | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2686     | 69.35%  |
| 1      | 1187     | 30.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3861     | 99.9%   |
| Unknown        | 4        | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2891     | 73.12%  |
| 0x08701021 | 111      | 2.81%   |
| 0x0800820d | 79       | 2%      |
| 0x306c3    | 77       | 1.95%   |
| 0x08701013 | 74       | 1.87%   |
| 0x306a9    | 63       | 1.59%   |
| 0x206a7    | 50       | 1.26%   |
| 0x506e3    | 42       | 1.06%   |
| 0x906ea    | 38       | 0.96%   |
| 0x906e9    | 30       | 0.76%   |
| 0x08001138 | 28       | 0.71%   |
| 0x1067a    | 27       | 0.68%   |
| 0x0a201016 | 27       | 0.68%   |
| 0x08108109 | 25       | 0.63%   |
| 0x06000852 | 25       | 0.63%   |
| 0x0a601203 | 18       | 0.46%   |
| 0x0a201009 | 17       | 0.43%   |
| 0x906ec    | 15       | 0.38%   |
| 0x906ed    | 14       | 0.35%   |
| 0x08301039 | 14       | 0.35%   |
| 0x0a20120a | 13       | 0.33%   |
| 0x08001137 | 13       | 0.33%   |
| 0xa0655    | 11       | 0.28%   |
| 0x06001119 | 11       | 0.28%   |
| 0x010000c8 | 11       | 0.28%   |
| 0x306f2    | 9        | 0.23%   |
| 0x106a5    | 9        | 0.23%   |
| 0x06003106 | 9        | 0.23%   |
| 0xa0653    | 8        | 0.2%    |
| 0x206c2    | 8        | 0.2%    |
| 0x0a50000d | 8        | 0.2%    |
| 0xa0671    | 7        | 0.18%   |
| 0x906eb    | 7        | 0.18%   |
| 0x90672    | 7        | 0.18%   |
| 0x0a50000c | 7        | 0.18%   |
| 0x08101016 | 7        | 0.18%   |
| 0x6fd      | 6        | 0.15%   |
| 0x206d7    | 6        | 0.15%   |
| 0x20655    | 6        | 0.15%   |
| 0x6fb      | 5        | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 545      | 14.05%  |
| Haswell          | 406      | 10.47%  |
| Zen 3            | 348      | 8.97%   |
| KabyLake         | 336      | 8.66%   |
| Zen+             | 295      | 7.61%   |
| IvyBridge        | 266      | 6.86%   |
| SandyBridge      | 240      | 6.19%   |
| Skylake          | 196      | 5.05%   |
| Zen              | 192      | 4.95%   |
| Unknown          | 160      | 4.12%   |
| Piledriver       | 159      | 4.1%    |
| Penryn           | 118      | 3.04%   |
| K10              | 116      | 2.99%   |
| CometLake        | 111      | 2.86%   |
| Nehalem          | 81       | 2.09%   |
| Westmere         | 61       | 1.57%   |
| Core             | 59       | 1.52%   |
| Steamroller      | 27       | 0.7%    |
| Silvermont       | 21       | 0.54%   |
| Alderlake Hybrid | 21       | 0.54%   |
| K8 Hammer        | 19       | 0.49%   |
| Excavator        | 17       | 0.44%   |
| Bulldozer        | 14       | 0.36%   |
| K10 Llano        | 13       | 0.34%   |
| Broadwell        | 12       | 0.31%   |
| NetBurst         | 9        | 0.23%   |
| Goldmont plus    | 9        | 0.23%   |
| Icelake          | 8        | 0.21%   |
| Jaguar           | 7        | 0.18%   |
| Goldmont         | 4        | 0.1%    |
| Bobcat           | 4        | 0.1%    |
| Bonnell          | 2        | 0.05%   |
| Tremont          | 1        | 0.03%   |
| Puma             | 1        | 0.03%   |
| Gracemont        | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 2036     | 48.5%   |
| AMD                              | 1422     | 33.87%  |
| Intel                            | 733      | 17.46%  |
| Matrox Electronics Systems       | 5        | 0.12%   |
| Silicon Integrated Systems [SiS] | 2        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 282      | 6.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 148      | 3.4%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 128      | 2.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 115      | 2.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 87       | 2%      |
| Nvidia GP104 [GeForce GTX 1070]                                             | 87       | 2%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 84       | 1.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 75       | 1.72%   |
| Nvidia GK208B [GeForce GT 710]                                              | 72       | 1.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 68       | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 68       | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 65       | 1.49%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 65       | 1.49%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 61       | 1.4%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 56       | 1.29%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 55       | 1.26%   |
| Intel HD Graphics 530                                                       | 54       | 1.24%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 53       | 1.22%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 50       | 1.15%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 49       | 1.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 49       | 1.13%   |
| AMD Raphael                                                                 | 47       | 1.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 45       | 1.03%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 45       | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 43       | 0.99%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 41       | 0.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 40       | 0.92%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 39       | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 38       | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 36       | 0.83%   |
| Nvidia GT218 [GeForce 210]                                                  | 35       | 0.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 34       | 0.78%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 34       | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 33       | 0.76%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 33       | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 33       | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 32       | 0.73%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 32       | 0.73%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 32       | 0.73%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 31       | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1867     | 47.42%  |
| 1 x AMD              | 1257     | 31.93%  |
| 1 x Intel            | 528      | 13.41%  |
| 2 x AMD              | 77       | 1.96%   |
| Intel + Nvidia       | 66       | 1.68%   |
| AMD + Nvidia         | 61       | 1.55%   |
| 2 x Nvidia           | 37       | 0.94%   |
| Intel + AMD          | 29       | 0.74%   |
| 1 x Matrox           | 4        | 0.1%    |
| 1 x SiS              | 2        | 0.05%   |
| Intel + 2 x Nvidia   | 2        | 0.05%   |
| Other                | 1        | 0.03%   |
| 5 x Nvidia           | 1        | 0.03%   |
| 4 x Nvidia           | 1        | 0.03%   |
| 3 x Nvidia           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia     | 1        | 0.03%   |
| AMD + Matrox         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2045     | 52.02%  |
| Proprietary | 1666     | 42.38%  |
| Unknown     | 220      | 5.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2210     | 55.7%   |
| 7.01-8.0   | 491      | 12.37%  |
| 1.01-2.0   | 310      | 7.81%   |
| 3.01-4.0   | 300      | 7.56%   |
| 5.01-6.0   | 251      | 6.33%   |
| 8.01-16.0  | 179      | 4.51%   |
| 0.51-1.0   | 90       | 2.27%   |
| 2.01-3.0   | 51       | 1.29%   |
| 0.01-0.5   | 51       | 1.29%   |
| 16.01-24.0 | 30       | 0.76%   |
| 4.01-5.0   | 3        | 0.08%   |
| 32.01-64.0 | 1        | 0.03%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 708      | 16.43%  |
| Goldstar             | 493      | 11.44%  |
| Dell                 | 468      | 10.86%  |
| Acer                 | 382      | 8.86%   |
| Hewlett-Packard      | 263      | 6.1%    |
| AOC                  | 252      | 5.85%   |
| Ancor Communications | 205      | 4.76%   |
| BenQ                 | 197      | 4.57%   |
| ASUSTek Computer     | 148      | 3.43%   |
| Philips              | 131      | 3.04%   |
| ViewSonic            | 76       | 1.76%   |
| Lenovo               | 70       | 1.62%   |
| Iiyama               | 69       | 1.6%    |
| MSI                  | 60       | 1.39%   |
| Sony                 | 54       | 1.25%   |
| Sceptre Tech         | 43       | 1%      |
| Vizio                | 34       | 0.79%   |
| Gigabyte Technology  | 31       | 0.72%   |
| Toshiba              | 25       | 0.58%   |
| Unknown              | 23       | 0.53%   |
| Eizo                 | 21       | 0.49%   |
| Panasonic            | 20       | 0.46%   |
| NEC Computers        | 18       | 0.42%   |
| Fujitsu Siemens      | 18       | 0.42%   |
| Insignia             | 17       | 0.39%   |
| MStar                | 14       | 0.32%   |
| Mi                   | 14       | 0.32%   |
| LG Electronics       | 14       | 0.32%   |
| Hitachi              | 14       | 0.32%   |
| Vestel Elektronik    | 12       | 0.28%   |
| ONN                  | 10       | 0.23%   |
| HannStar             | 10       | 0.23%   |
| Valve                | 9        | 0.21%   |
| Sharp                | 9        | 0.21%   |
| Pixio                | 9        | 0.21%   |
| Medion               | 9        | 0.21%   |
| HKC                  | 9        | 0.21%   |
| Viotek               | 8        | 0.19%   |
| Videoseven           | 8        | 0.19%   |
| CVT                  | 8        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 45       | 0.98%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 35       | 0.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 26       | 0.57%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 21       | 0.46%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 20       | 0.44%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 18       | 0.39%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 17       | 0.37%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 16       | 0.35%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 15       | 0.33%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 14       | 0.31%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 14       | 0.31%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 13       | 0.28%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 12       | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 12       | 0.26%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 12       | 0.26%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 12       | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 12       | 0.26%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 12       | 0.26%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 11       | 0.24%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 11       | 0.24%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11       | 0.24%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 10       | 0.22%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 10       | 0.22%   |
| Ancor Communications VG248 ACI24A4 1920x1080 530x300mm 24.0-inch      | 10       | 0.22%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 10       | 0.22%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 10       | 0.22%   |
| Acer V246HQL ACR0424 1920x1080 521x293mm 23.5-inch                    | 10       | 0.22%   |
| Valve Index HMD VLV91A8                                               | 9        | 0.2%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 9        | 0.2%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 9        | 0.2%    |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 9        | 0.2%    |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 9        | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 9        | 0.2%    |
| Dell S2716DG DELA0D1 2560x1440 600x340mm 27.2-inch                    | 9        | 0.2%    |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 9        | 0.2%    |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 9        | 0.2%    |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 9        | 0.2%    |
| AOC Q2770 AOC2770 2560x1440 597x336mm 27.0-inch                       | 9        | 0.2%    |
| AOC 2460 AOC0001 1920x1080 531x299mm 24.0-inch                        | 9        | 0.2%    |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch               | 8        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1868     | 45.46%  |
| 3840x2160 (4K)     | 546      | 13.29%  |
| 2560x1440 (QHD)    | 438      | 10.66%  |
| 3440x1440          | 169      | 4.11%   |
| 1680x1050 (WSXGA+) | 155      | 3.77%   |
| 1280x1024 (SXGA)   | 145      | 3.53%   |
| 1366x768 (WXGA)    | 139      | 3.38%   |
| 2560x1080          | 125      | 3.04%   |
| 1920x1200 (WUXGA)  | 92       | 2.24%   |
| 1440x900 (WXGA+)   | 91       | 2.21%   |
| 1600x900 (HD+)     | 89       | 2.17%   |
| 1360x768           | 49       | 1.19%   |
| 3840x1080          | 39       | 0.95%   |
| 1920x540           | 34       | 0.83%   |
| Unknown            | 30       | 0.73%   |
| 3840x1600          | 16       | 0.39%   |
| 1024x768 (XGA)     | 12       | 0.29%   |
| 1600x1200          | 11       | 0.27%   |
| 1280x720 (HD)      | 11       | 0.27%   |
| 2560x1600          | 9        | 0.22%   |
| 2048x1152          | 5        | 0.12%   |
| 4480x1440          | 4        | 0.1%    |
| 3840x1200          | 4        | 0.1%    |
| 5120x1440          | 2        | 0.05%   |
| 2288x1287          | 2        | 0.05%   |
| 9840x3840          | 1        | 0.02%   |
| 8320x2160          | 1        | 0.02%   |
| 8160x4627          | 1        | 0.02%   |
| 7680x2160          | 1        | 0.02%   |
| 6400x1440          | 1        | 0.02%   |
| 5280x1080          | 1        | 0.02%   |
| 5200x2160          | 1        | 0.02%   |
| 4096x2160          | 1        | 0.02%   |
| 4080x2030          | 1        | 0.02%   |
| 4080x2026          | 1        | 0.02%   |
| 3360x1080          | 1        | 0.02%   |
| 3280x2048          | 1        | 0.02%   |
| 3280x1080          | 1        | 0.02%   |
| 3040x900           | 1        | 0.02%   |
| 2960x1050          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 759      | 17.61%  |
| 24      | 660      | 15.32%  |
| 23      | 512      | 11.88%  |
| 21      | 400      | 9.28%   |
| 31      | 283      | 6.57%   |
| 34      | 245      | 5.69%   |
| 19      | 163      | 3.78%   |
| Unknown | 144      | 3.34%   |
| 18      | 116      | 2.69%   |
| 22      | 115      | 2.67%   |
| 20      | 96       | 2.23%   |
| 84      | 90       | 2.09%   |
| 17      | 75       | 1.74%   |
| 32      | 70       | 1.62%   |
| 72      | 64       | 1.49%   |
| 15      | 53       | 1.23%   |
| 40      | 45       | 1.04%   |
| 54      | 44       | 1.02%   |
| 48      | 35       | 0.81%   |
| 26      | 31       | 0.72%   |
| 25      | 30       | 0.7%    |
| 28      | 26       | 0.6%    |
| 35      | 23       | 0.53%   |
| 52      | 20       | 0.46%   |
| 37      | 19       | 0.44%   |
| 65      | 18       | 0.42%   |
| 49      | 16       | 0.37%   |
| 29      | 16       | 0.37%   |
| 46      | 13       | 0.3%    |
| 36      | 13       | 0.3%    |
| 33      | 11       | 0.26%   |
| 42      | 10       | 0.23%   |
| 43      | 8        | 0.19%   |
| 12      | 8        | 0.19%   |
| 74      | 7        | 0.16%   |
| 38      | 7        | 0.16%   |
| 55      | 6        | 0.14%   |
| 44      | 5        | 0.12%   |
| 16      | 5        | 0.12%   |
| 75      | 4        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1723     | 41.84%  |
| 401-500        | 788      | 19.14%  |
| 601-700        | 425      | 10.32%  |
| 701-800        | 328      | 7.97%   |
| 1001-1500      | 178      | 4.32%   |
| 1501-2000      | 168      | 4.08%   |
| Unknown        | 144      | 3.5%    |
| 301-350        | 117      | 2.84%   |
| 801-900        | 105      | 2.55%   |
| 351-400        | 103      | 2.5%    |
| 901-1000       | 20       | 0.49%   |
| 201-300        | 18       | 0.44%   |
| More than 2000 | 1        | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2766     | 72.73%  |
| 16/10   | 403      | 10.6%   |
| 21/9    | 301      | 7.91%   |
| 5/4     | 141      | 3.71%   |
| Unknown | 81       | 2.13%   |
| 32/9    | 44       | 1.16%   |
| 4/3     | 40       | 1.05%   |
| 3/2     | 10       | 0.26%   |
| 6/5     | 7        | 0.18%   |
| 1.96    | 5        | 0.13%   |
| 3.20    | 4        | 0.11%   |
| 1.00    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1322     | 31.54%  |
| 301-350        | 779      | 18.58%  |
| 351-500        | 639      | 15.24%  |
| 151-200        | 368      | 8.78%   |
| More than 1000 | 281      | 6.7%    |
| 251-300        | 247      | 5.89%   |
| 501-1000       | 170      | 4.06%   |
| 141-150        | 158      | 3.77%   |
| Unknown        | 144      | 3.44%   |
| 101-110        | 44       | 1.05%   |
| 71-80          | 12       | 0.29%   |
| 131-140        | 8        | 0.19%   |
| 111-120        | 6        | 0.14%   |
| 91-100         | 6        | 0.14%   |
| 51-60          | 4        | 0.1%    |
| 121-130        | 4        | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2403     | 61.3%   |
| 101-120       | 849      | 21.66%  |
| 121-160       | 221      | 5.64%   |
| 1-50          | 206      | 5.26%   |
| Unknown       | 144      | 3.67%   |
| 161-240       | 96       | 2.45%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2752     | 69.55%  |
| 2     | 831      | 21%     |
| 0     | 253      | 6.39%   |
| 3     | 105      | 2.65%   |
| 4     | 13       | 0.33%   |
| 5     | 2        | 0.05%   |
| 6     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 2301     | 40.15%  |
| Intel                                 | 1896     | 33.08%  |
| Qualcomm Atheros                      | 333      | 5.81%   |
| Broadcom                              | 189      | 3.3%    |
| TP-Link                               | 113      | 1.97%   |
| Ralink Technology                     | 105      | 1.83%   |
| Microsoft                             | 75       | 1.31%   |
| MediaTek                              | 75       | 1.31%   |
| Nvidia                                | 53       | 0.92%   |
| Samsung Electronics                   | 49       | 0.85%   |
| Ralink                                | 49       | 0.85%   |
| NetGear                               | 42       | 0.73%   |
| Aquantia                              | 41       | 0.72%   |
| InterBiometrics                       | 38       | 0.66%   |
| Qualcomm Atheros Communications       | 37       | 0.65%   |
| Marvell Technology Group              | 24       | 0.42%   |
| Google                                | 23       | 0.4%    |
| Xiaomi                                | 22       | 0.38%   |
| Linksys                               | 20       | 0.35%   |
| D-Link                                | 19       | 0.33%   |
| Huawei Technologies                   | 18       | 0.31%   |
| Broadcom Limited                      | 17       | 0.3%    |
| ASIX Electronics                      | 17       | 0.3%    |
| ASUSTek Computer                      | 14       | 0.24%   |
| D-Link System                         | 11       | 0.19%   |
| Edimax Technology                     | 9        | 0.16%   |
| Belkin Components                     | 9        | 0.16%   |
| OPPO Electronics                      | 8        | 0.14%   |
| OnePlus Technology (Shenzhen)         | 8        | 0.14%   |
| Motorola PCS                          | 7        | 0.12%   |
| Mellanox Technologies                 | 6        | 0.1%    |
| DisplayLink                           | 6        | 0.1%    |
| AVM                                   | 6        | 0.1%    |
| VIA Technologies                      | 5        | 0.09%   |
| Sitecom Europe                        | 5        | 0.09%   |
| Gemtek                                | 5        | 0.09%   |
| Mercucys                              | 4        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.07%   |
| Qualcomm                              | 3        | 0.05%   |
| Microchip Technology                  | 3        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1753     | 26.24%  |
| Intel I211 Gigabit Network Connection                                          | 439      | 6.57%   |
| Intel Wi-Fi 6 AX200                                                            | 389      | 5.82%   |
| Realtek RTL8125 2.5GbE Controller                                              | 293      | 4.39%   |
| Intel Ethernet Controller I225-V                                               | 185      | 2.77%   |
| Intel Ethernet Connection (2) I219-V                                           | 164      | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 135      | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 112      | 1.68%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 103      | 1.54%   |
| Intel Ethernet Connection (7) I219-V                                           | 95       | 1.42%   |
| Intel Ethernet Connection I217-LM                                              | 88       | 1.32%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 65       | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 63       | 0.94%   |
| Realtek 802.11ac NIC                                                           | 63       | 0.94%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 59       | 0.88%   |
| Intel 82579V Gigabit Network Connection                                        | 57       | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 56       | 0.84%   |
| Intel Ethernet Connection (2) I218-V                                           | 52       | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 48       | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 48       | 0.72%   |
| Ralink MT7601U Wireless Adapter                                                | 46       | 0.69%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 46       | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 45       | 0.67%   |
| Intel Ethernet Connection I217-V                                               | 43       | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 42       | 0.63%   |
| Nvidia MCP61 Ethernet                                                          | 40       | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 37       | 0.55%   |
| InterBiometrics Io                                                             | 37       | 0.55%   |
| Qualcomm Atheros AR9271 802.11n                                                | 31       | 0.46%   |
| Intel Wireless 7265                                                            | 31       | 0.46%   |
| Intel 82574L Gigabit Network Connection                                        | 31       | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 30       | 0.45%   |
| Microsoft Xbox 360 Wireless Adapter                                            | 30       | 0.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 30       | 0.45%   |
| Intel Wireless 8265 / 8275                                                     | 30       | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 29       | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                                          | 29       | 0.43%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 29       | 0.43%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 28       | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 27       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 928      | 41.06%  |
| Realtek Semiconductor                 | 438      | 19.38%  |
| Qualcomm Atheros                      | 173      | 7.65%   |
| Broadcom                              | 115      | 5.09%   |
| TP-Link                               | 107      | 4.73%   |
| Ralink Technology                     | 105      | 4.65%   |
| Microsoft                             | 75       | 3.32%   |
| MediaTek                              | 71       | 3.14%   |
| Ralink                                | 49       | 2.17%   |
| NetGear                               | 42       | 1.86%   |
| Qualcomm Atheros Communications       | 37       | 1.64%   |
| Linksys                               | 19       | 0.84%   |
| D-Link                                | 18       | 0.8%    |
| ASUSTek Computer                      | 14       | 0.62%   |
| Edimax Technology                     | 9        | 0.4%    |
| Belkin Components                     | 9        | 0.4%    |
| D-Link System                         | 7        | 0.31%   |
| Broadcom Limited                      | 7        | 0.31%   |
| AVM                                   | 6        | 0.27%   |
| Sitecom Europe                        | 5        | 0.22%   |
| Gemtek                                | 5        | 0.22%   |
| Mercucys                              | 4        | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.18%   |
| IMC Networks                          | 3        | 0.13%   |
| ZyDAS                                 | 1        | 0.04%   |
| Wilocity                              | 1        | 0.04%   |
| Wacom                                 | 1        | 0.04%   |
| TRENDnet                              | 1        | 0.04%   |
| Texas Instruments                     | 1        | 0.04%   |
| Samsung Electronics                   | 1        | 0.04%   |
| Ovislink                              | 1        | 0.04%   |
| Micro Star International              | 1        | 0.04%   |
| BUFFALO                               | 1        | 0.04%   |
| Accton Technology                     | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 389      | 17.04%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 112      | 4.91%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 103      | 4.51%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 65       | 2.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 63       | 2.76%   |
| Realtek 802.11ac NIC                                           | 63       | 2.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 59       | 2.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 56       | 2.45%   |
| Ralink MT7601U Wireless Adapter                                | 46       | 2.01%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 46       | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 45       | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 37       | 1.62%   |
| Qualcomm Atheros AR9271 802.11n                                | 31       | 1.36%   |
| Intel Wireless 7265                                            | 31       | 1.36%   |
| Microsoft Xbox 360 Wireless Adapter                            | 30       | 1.31%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 30       | 1.31%   |
| Intel Wireless 8265 / 8275                                     | 30       | 1.31%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 29       | 1.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 29       | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 27       | 1.18%   |
| Intel Wireless 7260                                            | 27       | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 25       | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24       | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 24       | 1.05%   |
| Intel Wireless 8260                                            | 23       | 1.01%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 22       | 0.96%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 21       | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 19       | 0.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 18       | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18       | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 18       | 0.79%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 17       | 0.74%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 17       | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 16       | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 16       | 0.7%    |
| Ralink RT5370 Wireless Adapter                                 | 15       | 0.66%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 15       | 0.66%   |
| TP-Link 802.11ac NIC                                           | 14       | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 14       | 0.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 14       | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 2128     | 50.65%  |
| Intel                            | 1488     | 35.42%  |
| Qualcomm Atheros                 | 174      | 4.14%   |
| Broadcom                         | 82       | 1.95%   |
| Nvidia                           | 53       | 1.26%   |
| Samsung Electronics              | 48       | 1.14%   |
| Aquantia                         | 41       | 0.98%   |
| Marvell Technology Group         | 24       | 0.57%   |
| Google                           | 23       | 0.55%   |
| Xiaomi                           | 22       | 0.52%   |
| Huawei Technologies              | 17       | 0.4%    |
| ASIX Electronics                 | 17       | 0.4%    |
| Broadcom Limited                 | 10       | 0.24%   |
| OPPO Electronics                 | 8        | 0.19%   |
| TP-Link                          | 6        | 0.14%   |
| DisplayLink                      | 6        | 0.14%   |
| VIA Technologies                 | 5        | 0.12%   |
| OnePlus Technology (Shenzhen)    | 5        | 0.12%   |
| Motorola PCS                     | 5        | 0.12%   |
| Mellanox Technologies            | 4        | 0.1%    |
| MediaTek                         | 4        | 0.1%    |
| D-Link System                    | 4        | 0.1%    |
| Qualcomm                         | 3        | 0.07%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.05%   |
| Lenovo                           | 2        | 0.05%   |
| ICS Advent                       | 2        | 0.05%   |
| 3Com                             | 2        | 0.05%   |
| Tehuti Networks                  | 1        | 0.02%   |
| T & A Mobile Phones              | 1        | 0.02%   |
| Solarflare Communications        | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| QLogic                           | 1        | 0.02%   |
| Netchip Technology               | 1        | 0.02%   |
| Linksys                          | 1        | 0.02%   |
| LG Electronics                   | 1        | 0.02%   |
| JMicron Technology               | 1        | 0.02%   |
| HMD Global                       | 1        | 0.02%   |
| Hangzhou Silan Microelectronics  | 1        | 0.02%   |
| Emulex                           | 1        | 0.02%   |
| D-Link                           | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1753     | 40.59%  |
| Intel I211 Gigabit Network Connection                                          | 439      | 10.16%  |
| Realtek RTL8125 2.5GbE Controller                                              | 293      | 6.78%   |
| Intel Ethernet Controller I225-V                                               | 185      | 4.28%   |
| Intel Ethernet Connection (2) I219-V                                           | 164      | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 135      | 3.13%   |
| Intel Ethernet Connection (7) I219-V                                           | 95       | 2.2%    |
| Intel Ethernet Connection I217-LM                                              | 88       | 2.04%   |
| Intel 82579V Gigabit Network Connection                                        | 57       | 1.32%   |
| Intel Ethernet Connection (2) I218-V                                           | 52       | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 48       | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 48       | 1.11%   |
| Intel Ethernet Connection I217-V                                               | 43       | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 42       | 0.97%   |
| Nvidia MCP61 Ethernet                                                          | 40       | 0.93%   |
| Intel 82574L Gigabit Network Connection                                        | 31       | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 30       | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                          | 29       | 0.67%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 28       | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 27       | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 25       | 0.58%   |
| Intel I210 Gigabit Network Connection                                          | 25       | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 23       | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 22       | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 20       | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 18       | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 18       | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 16       | 0.37%   |
| Huawei STG-LX1                                                                 | 15       | 0.35%   |
| Google Nexus/Pixel Device (tether)                                             | 15       | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 14       | 0.32%   |
| Intel Ethernet Connection (2) I218-LM                                          | 13       | 0.3%    |
| Intel Ethernet Connection (14) I219-V                                          | 13       | 0.3%    |
| Intel Ethernet Connection (11) I219-V                                          | 13       | 0.3%    |
| Intel 82578DM Gigabit Network Connection                                       | 13       | 0.3%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 13       | 0.3%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 12       | 0.28%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 12       | 0.28%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12       | 0.28%   |
| Intel Ethernet Controller I226-V                                               | 10       | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3819     | 63.69%  |
| WiFi     | 2100     | 35.02%  |
| Modem    | 61       | 1.02%   |
| Unknown  | 16       | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2904     | 70.78%  |
| WiFi     | 1197     | 29.17%  |
| Unknown  | 2        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2212     | 56.86%  |
| 2     | 1410     | 36.25%  |
| 3     | 196      | 5.04%   |
| 0     | 35       | 0.9%    |
| 4     | 26       | 0.67%   |
| 5     | 7        | 0.18%   |
| 10    | 2        | 0.05%   |
| 6     | 2        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3007     | 76.2%   |
| Yes  | 939      | 23.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 859      | 52.06%  |
| Cambridge Silicon Radio         | 316      | 19.15%  |
| ASUSTek Computer                | 95       | 5.76%   |
| Realtek Semiconductor           | 93       | 5.64%   |
| Broadcom                        | 65       | 3.94%   |
| Qualcomm Atheros Communications | 48       | 2.91%   |
| MediaTek                        | 43       | 2.61%   |
| Apple                           | 31       | 1.88%   |
| IMC Networks                    | 19       | 1.15%   |
| TP-Link                         | 17       | 1.03%   |
| Foxconn / Hon Hai               | 15       | 0.91%   |
| Dynex                           | 8        | 0.48%   |
| Realtek                         | 4        | 0.24%   |
| Lite-On Technology              | 4        | 0.24%   |
| Integrated System Solution      | 4        | 0.24%   |
| HTC (High Tech Computer)        | 4        | 0.24%   |
| Actions                         | 4        | 0.24%   |
| Dell                            | 3        | 0.18%   |
| SINO WEALTH                     | 2        | 0.12%   |
| Ralink                          | 2        | 0.12%   |
| Logitech                        | 2        | 0.12%   |
| Hewlett-Packard                 | 2        | 0.12%   |
| Edimax Technology               | 2        | 0.12%   |
| Creative Technology             | 2        | 0.12%   |
| Conwise Technology              | 2        | 0.12%   |
| Belkin Components               | 2        | 0.12%   |
| Primax Electronics              | 1        | 0.06%   |
| Micro Star International        | 1        | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 360      | 21.77%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 316      | 19.11%  |
| Intel Bluetooth wireless interface                                   | 112      | 6.77%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 108      | 6.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 97       | 5.86%   |
| Realtek Bluetooth Radio                                              | 71       | 4.29%   |
| Intel AX201 Bluetooth                                                | 57       | 3.45%   |
| Intel AX210 Bluetooth                                                | 54       | 3.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 49       | 2.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 48       | 2.9%    |
| MediaTek Wireless_Device                                             | 43       | 2.6%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 31       | 1.87%   |
| Qualcomm Atheros  Bluetooth Device                                   | 26       | 1.57%   |
| ASUS Bluetooth Radio                                                 | 26       | 1.57%   |
| Intel Bluetooth Device                                               | 22       | 1.33%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 19       | 1.15%   |
| TP-Link UB500 Adapter                                                | 17       | 1.03%   |
| Apple Bluetooth Host Controller                                      | 15       | 0.91%   |
| ASUS ASUS USB-BT500                                                  | 13       | 0.79%   |
| IMC Networks Bluetooth Radio                                         | 12       | 0.73%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 8        | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 7        | 0.42%   |
| ASUS BCM20702A0                                                      | 7        | 0.42%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 7        | 0.42%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 6        | 0.36%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6        | 0.36%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 6        | 0.36%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 6        | 0.36%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 5        | 0.3%    |
| IMC Networks Wireless_Device                                         | 5        | 0.3%    |
| Apple Bluetooth HCI                                                  | 5        | 0.3%    |
| Realtek Bluetooth Radio                                              | 4        | 0.24%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 0.24%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.24%   |
| Apple Bluetooth USB Host Controller                                  | 4        | 0.24%   |
| Actions general adapter                                              | 4        | 0.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 3        | 0.18%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 3        | 0.18%   |
| ASUS Bluetooth Device                                                | 3        | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 2161     | 28.69%  |
| Nvidia                                          | 1971     | 26.17%  |
| Intel                                           | 1961     | 26.04%  |
| C-Media Electronics                             | 216      | 2.87%   |
| Logitech                                        | 108      | 1.43%   |
| Creative Labs                                   | 79       | 1.05%   |
| Razer USA                                       | 66       | 0.88%   |
| Kingston Technology                             | 66       | 0.88%   |
| JMTek                                           | 55       | 0.73%   |
| Corsair                                         | 54       | 0.72%   |
| ASUSTek Computer                                | 54       | 0.72%   |
| SteelSeries ApS                                 | 51       | 0.68%   |
| Focusrite-Novation                              | 47       | 0.62%   |
| Texas Instruments                               | 43       | 0.57%   |
| Creative Technology                             | 34       | 0.45%   |
| Micro Star International                        | 31       | 0.41%   |
| Blue Microphones                                | 31       | 0.41%   |
| Generalplus Technology                          | 26       | 0.35%   |
| Giga-Byte Technology                            | 19       | 0.25%   |
| GN Netcom                                       | 18       | 0.24%   |
| Astro Gaming                                    | 17       | 0.23%   |
| DSEA A/S                                        | 16       | 0.21%   |
| Sony                                            | 15       | 0.2%    |
| Plantronics                                     | 15       | 0.2%    |
| Valve Software                                  | 14       | 0.19%   |
| Tenx Technology                                 | 13       | 0.17%   |
| Realtek Semiconductor                           | 13       | 0.17%   |
| Samson Technologies                             | 12       | 0.16%   |
| M-Audio                                         | 12       | 0.16%   |
| Yamaha                                          | 11       | 0.15%   |
| Turtle Beach                                    | 11       | 0.15%   |
| Thesycon Systemsoftware & Consulting            | 11       | 0.15%   |
| SAVITECH                                        | 11       | 0.15%   |
| FiiO Electronics Technology                     | 9        | 0.12%   |
| BEHRINGER International                         | 9        | 0.12%   |
| Licensed by Sony Computer Entertainment America | 8        | 0.11%   |
| KTMicro                                         | 8        | 0.11%   |
| Dell                                            | 8        | 0.11%   |
| Audio-Technica                                  | 7        | 0.09%   |
| VIA Technologies                                | 6        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 771      | 8.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 332      | 3.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 290      | 3.29%   |
| AMD Family 17h/19h HD Audio Controller                                     | 283      | 3.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 262      | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 246      | 2.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 206      | 2.34%   |
| Nvidia GP104 High Definition Audio Controller                              | 195      | 2.21%   |
| Intel 200 Series PCH HD Audio                                              | 189      | 2.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 187      | 2.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 182      | 2.06%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 181      | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 158      | 1.79%   |
| AMD Navi 10 HDMI Audio                                                     | 156      | 1.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 154      | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 152      | 1.72%   |
| Nvidia GP106 High Definition Audio Controller                              | 135      | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 135      | 1.53%   |
| Nvidia TU104 HD Audio Controller                                           | 121      | 1.37%   |
| Nvidia GA104 High Definition Audio Controller                              | 117      | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 116      | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 105      | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 101      | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 99       | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 97       | 1.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 93       | 1.06%   |
| Nvidia GA102 High Definition Audio Controller                              | 91       | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 90       | 1.02%   |
| AMD FCH Azalia Controller                                                  | 89       | 1.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 88       | 1%      |
| Nvidia GM204 High Definition Audio Controller                              | 80       | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 68       | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 68       | 0.77%   |
| Nvidia GM206 High Definition Audio Controller                              | 61       | 0.69%   |
| Nvidia GP102 HDMI Audio Controller                                         | 55       | 0.62%   |
| Intel Alder Lake-S HD Audio Controller                                     | 55       | 0.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 55       | 0.62%   |
| Nvidia GK104 HDMI Audio Controller                                         | 53       | 0.6%    |
| Nvidia GA106 High Definition Audio Controller                              | 53       | 0.6%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 50       | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 180      | 23.17%  |
| Kingston                     | 134      | 17.25%  |
| G.Skill                      | 119      | 15.32%  |
| Crucial                      | 76       | 9.78%   |
| Unknown                      | 57       | 7.34%   |
| Samsung Electronics          | 47       | 6.05%   |
| SK hynix                     | 35       | 4.5%    |
| Team                         | 32       | 4.12%   |
| Micron Technology            | 23       | 2.96%   |
| A-DATA Technology            | 21       | 2.7%    |
| Patriot                      | 12       | 1.54%   |
| Unknown                      | 5        | 0.64%   |
| Ramaxel Technology           | 3        | 0.39%   |
| Patriot Memory               | 2        | 0.26%   |
| OLOY                         | 2        | 0.26%   |
| Neo Forza                    | 2        | 0.26%   |
| Goldkey                      | 2        | 0.26%   |
| Avant                        | 2        | 0.26%   |
| Apacer                       | 2        | 0.26%   |
| Unknown (ABCD)               | 1        | 0.13%   |
| Unifosa                      | 1        | 0.13%   |
| Transcend                    | 1        | 0.13%   |
| Toshiba                      | 1        | 0.13%   |
| Teikon                       | 1        | 0.13%   |
| Smart                        | 1        | 0.13%   |
| Silicon Power                | 1        | 0.13%   |
| Patriot Memory (PDP Systems) | 1        | 0.13%   |
| Nanya Technology             | 1        | 0.13%   |
| Juhor                        | 1        | 0.13%   |
| HMD                          | 1        | 0.13%   |
| Goodram                      | 1        | 0.13%   |
| GLOWAY                       | 1        | 0.13%   |
| GeIL                         | 1        | 0.13%   |
| EVGA                         | 1        | 0.13%   |
| Elpida                       | 1        | 0.13%   |
| CSX                          | 1        | 0.13%   |
| Colorful                     | 1        | 0.13%   |
| ASint Technology             | 1        | 0.13%   |
| Asgard                       | 1        | 0.13%   |
| AMD                          | 1        | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 23       | 2.78%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 14       | 1.69%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 12       | 1.45%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 10       | 1.21%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 10       | 1.21%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s    | 9        | 1.09%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 9        | 1.09%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 8        | 0.97%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 6        | 0.73%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s | 6        | 0.73%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s | 6        | 0.73%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s           | 6        | 0.73%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 5        | 0.6%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s    | 5        | 0.6%    |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 3000MT/s  | 5        | 0.6%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 5        | 0.6%    |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s    | 5        | 0.6%    |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 5        | 0.6%    |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s  | 5        | 0.6%    |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s   | 5        | 0.6%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 5        | 0.6%    |
| Unknown                                                | 5        | 0.6%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s     | 4        | 0.48%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 4        | 0.48%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 4        | 0.48%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 4        | 0.48%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s   | 4        | 0.48%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s   | 4        | 0.48%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s  | 4        | 0.48%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s | 4        | 0.48%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 4        | 0.48%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s | 4        | 0.48%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s  | 4        | 0.48%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s | 4        | 0.48%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 4        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 3        | 0.36%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s    | 3        | 0.36%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 0.36%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 0.36%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s    | 3        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 504      | 70.29%  |
| DDR3    | 139      | 19.39%  |
| DDR5    | 34       | 4.74%   |
| Unknown | 16       | 2.23%   |
| DDR2    | 13       | 1.81%   |
| SDRAM   | 7        | 0.98%   |
| LPDDR4  | 2        | 0.28%   |
| DDR     | 2        | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 688      | 96.49%  |
| SODIMM       | 23       | 3.23%   |
| Row Of Chips | 1        | 0.14%   |
| RIMM         | 1        | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 330      | 43.59%  |
| 16384 | 201      | 26.55%  |
| 4096  | 113      | 14.93%  |
| 32768 | 73       | 9.64%   |
| 2048  | 28       | 3.7%    |
| 1024  | 10       | 1.32%   |
| 512   | 2        | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 131      | 16.79%  |
| 3200    | 88       | 11.28%  |
| 1600    | 77       | 9.87%   |
| 2400    | 46       | 5.9%    |
| 1333    | 46       | 5.9%    |
| 3800    | 33       | 4.23%   |
| 2667    | 32       | 4.1%    |
| 3733    | 27       | 3.46%   |
| 3000    | 27       | 3.46%   |
| 2133    | 27       | 3.46%   |
| 3400    | 17       | 2.18%   |
| 3866    | 16       | 2.05%   |
| 1867    | 16       | 2.05%   |
| 3533    | 15       | 1.92%   |
| 2933    | 13       | 1.67%   |
| 2666    | 13       | 1.67%   |
| 4800    | 12       | 1.54%   |
| 3534    | 10       | 1.28%   |
| 800     | 10       | 1.28%   |
| 1866    | 9        | 1.15%   |
| 1800    | 8        | 1.03%   |
| 6000    | 7        | 0.9%    |
| 3466    | 7        | 0.9%    |
| 3066    | 7        | 0.9%    |
| 667     | 7        | 0.9%    |
| 4000    | 6        | 0.77%   |
| 5200    | 5        | 0.64%   |
| 4400    | 5        | 0.64%   |
| 3666    | 5        | 0.64%   |
| 2800    | 5        | 0.64%   |
| Unknown | 5        | 0.64%   |
| 5600    | 4        | 0.51%   |
| 6400    | 3        | 0.38%   |
| 3333    | 3        | 0.38%   |
| 3266    | 3        | 0.38%   |
| 3100    | 3        | 0.38%   |
| 4266    | 2        | 0.26%   |
| 3334    | 2        | 0.26%   |
| 3151    | 2        | 0.26%   |
| 2733    | 2        | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 54       | 33.54%  |
| Brother Industries    | 30       | 18.63%  |
| Canon                 | 24       | 14.91%  |
| Samsung Electronics   | 19       | 11.8%   |
| Seiko Epson           | 15       | 9.32%   |
| Dymo-CoStar           | 5        | 3.11%   |
| Fuji Xerox            | 3        | 1.86%   |
| STMicroelectronics    | 2        | 1.24%   |
| QinHeng Electronics   | 2        | 1.24%   |
| Xerox                 | 1        | 0.62%   |
| Prolific Technology   | 1        | 0.62%   |
| Oki Data              | 1        | 0.62%   |
| Lexmark International | 1        | 0.62%   |
| Kyocera               | 1        | 0.62%   |
| Dell                  | 1        | 0.62%   |
| Apple                 | 1        | 0.62%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| HP Deskjet 3050 J610 series                                | 4        | 2.47%   |
| Samsung SCX-3400 Series                                    | 3        | 1.85%   |
| HP LaserJet Professional P 1102w                           | 3        | 1.85%   |
| Brother Printer                                            | 3        | 1.85%   |
| Brother HL-2130 series                                     | 3        | 1.85%   |
| Seiko Epson WF-4830 Series                                 | 2        | 1.23%   |
| Seiko Epson L355 Series                                    | 2        | 1.23%   |
| Seiko Epson ET-2700 Series                                 | 2        | 1.23%   |
| Seiko Epson ET-2600 Series                                 | 2        | 1.23%   |
| Samsung ML-1640 Series Laser Printer                       | 2        | 1.23%   |
| Samsung M2070 Series                                       | 2        | 1.23%   |
| Samsung M2020 Series                                       | 2        | 1.23%   |
| QinHeng CH340S                                             | 2        | 1.23%   |
| HP HP LaserJet M14-M17                                     | 2        | 1.23%   |
| HP ENVY Pro 6400 series                                    | 2        | 1.23%   |
| HP ENVY Photo 6200 series                                  | 2        | 1.23%   |
| HP ENVY 4500 series                                        | 2        | 1.23%   |
| HP DeskJet F4100 Printer series                            | 2        | 1.23%   |
| HP Deskjet F2280 series                                    | 2        | 1.23%   |
| HP DeskJet 2600 series                                     | 2        | 1.23%   |
| HP Deskjet 1000 J110 series                                | 2        | 1.23%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2        | 1.23%   |
| Dymo-CoStar LabelWriter 450                                | 2        | 1.23%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2        | 1.23%   |
| Canon PIXMA MX920 Series                                   | 2        | 1.23%   |
| Canon PIXMA MG2500 Series                                  | 2        | 1.23%   |
| Brother HL-L3230CDW series                                 | 2        | 1.23%   |
| Brother HL-2270DW Laser Printer                            | 2        | 1.23%   |
| Brother HL-1110 series                                     | 2        | 1.23%   |
| Xerox Phaser 6000B                                         | 1        | 0.62%   |
| STMicroelectronics USB Printer P                           | 1        | 0.62%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1        | 0.62%   |
| Seiko Epson WF-3520 Series                                 | 1        | 0.62%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]               | 1        | 0.62%   |
| Seiko Epson L365 Series                                    | 1        | 0.62%   |
| Seiko Epson L3110 Series                                   | 1        | 0.62%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 0.62%   |
| Seiko Epson ET-3760 Series                                 | 1        | 0.62%   |
| Seiko Epson ET-2800 Series                                 | 1        | 0.62%   |
| Samsung SCX-4500 Laser Printer                             | 1        | 0.62%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 50%     |
| Seiko Epson     | 6        | 27.27%  |
| Hewlett-Packard | 4        | 18.18%  |
| Mustek Systems  | 1        | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30                           | 2        | 9.09%   |
| Canon CanoScan LiDE 210                                 | 2        | 9.09%   |
| Seiko Epson Scanner                                     | 1        | 4.55%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1        | 4.55%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 4.55%   |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1        | 4.55%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 4.55%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1        | 4.55%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 4.55%   |
| HP Scanjet G2710                                        | 1        | 4.55%   |
| HP ScanJet 82x0C                                        | 1        | 4.55%   |
| HP Scanjet 300                                          | 1        | 4.55%   |
| HP ScanJet 2400c                                        | 1        | 4.55%   |
| Canon CanoScan N650U/N656U                              | 1        | 4.55%   |
| Canon CanoScan LiDE 60                                  | 1        | 4.55%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1        | 4.55%   |
| Canon CanoScan LiDE 220                                 | 1        | 4.55%   |
| Canon CanoScan LiDE 200                                 | 1        | 4.55%   |
| Canon CanoScan LiDE 110                                 | 1        | 4.55%   |
| Canon CanoScan 9000F Mark II                            | 1        | 4.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 333      | 44.34%  |
| Microdia                      | 67       | 8.92%   |
| Microsoft                     | 40       | 5.33%   |
| Sunplus Innovation Technology | 28       | 3.73%   |
| Apple                         | 23       | 3.06%   |
| Generalplus Technology        | 20       | 2.66%   |
| ARC International             | 16       | 2.13%   |
| Samsung Electronics           | 15       | 2%      |
| Valve Software                | 13       | 1.73%   |
| Razer USA                     | 13       | 1.73%   |
| Realtek Semiconductor         | 12       | 1.6%    |
| Chicony Electronics           | 12       | 1.6%    |
| Z-Star Microelectronics       | 11       | 1.46%   |
| Jieli Technology              | 11       | 1.46%   |
| MacroSilicon                  | 10       | 1.33%   |
| Creative Technology           | 10       | 1.33%   |
| KYE Systems (Mouse Systems)   | 8        | 1.07%   |
| Hewlett-Packard               | 6        | 0.8%    |
| Cubeternet                    | 6        | 0.8%    |
| LG Electronics                | 5        | 0.67%   |
| Huawei Technologies           | 5        | 0.67%   |
| AVerMedia Technologies        | 5        | 0.67%   |
| YGTek                         | 4        | 0.53%   |
| Trust                         | 4        | 0.53%   |
| Aveo Technology               | 4        | 0.53%   |
| webcamvendor                  | 3        | 0.4%    |
| A4Tech                        | 3        | 0.4%    |
| WCM_USB                       | 2        | 0.27%   |
| ValueHD                       | 2        | 0.27%   |
| Unknown                       | 2        | 0.27%   |
| Sunplus IT                    | 2        | 0.27%   |
| Ruision                       | 2        | 0.27%   |
| OmniVision Technologies       | 2        | 0.27%   |
| Novatek Microelectronics      | 2        | 0.27%   |
| Intel                         | 2        | 0.27%   |
| HTC (High Tech Computer)      | 2        | 0.27%   |
| GenesysLogic Technology       | 2        | 0.27%   |
| Genesys Logic                 | 2        | 0.27%   |
| GEMBIRD                       | 2        | 0.27%   |
| eMeet                         | 2        | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 73       | 9.67%   |
| Logitech Webcam C270                    | 64       | 8.48%   |
| Logitech C922 Pro Stream Webcam         | 28       | 3.71%   |
| Microdia Webcam Vitade AF               | 25       | 3.31%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 22       | 2.91%   |
| Logitech BRIO Ultra HD Webcam           | 18       | 2.38%   |
| Generalplus GENERAL WEBCAM              | 18       | 2.38%   |
| Microsoft LifeCam HD-3000               | 16       | 2.12%   |
| Microdia USB 2.0 Camera                 | 16       | 2.12%   |
| ARC International Camera                | 16       | 2.12%   |
| Samsung Galaxy series, misc. (MTP mode) | 15       | 1.99%   |
| Logitech HD Webcam C615                 | 15       | 1.99%   |
| Logitech HD Webcam C525                 | 15       | 1.99%   |
| Logitech C920 PRO HD Webcam             | 15       | 1.99%   |
| Valve Software 3D Camera                | 13       | 1.72%   |
| Logitech Webcam C925e                   | 11       | 1.46%   |
| Jieli USB PHY 2.0                       | 11       | 1.46%   |
| Razer USA Gaming Webcam [Kiyo]          | 10       | 1.32%   |
| Logitech Webcam C930e                   | 10       | 1.32%   |
| Logitech Webcam C310                    | 10       | 1.32%   |
| Microsoft LifeCam Cinema                | 8        | 1.06%   |
| Microdia Integrated Camera              | 8        | 1.06%   |
| MacroSilicon USB3. 0 capture            | 8        | 1.06%   |
| Logitech Webcam Pro 9000                | 8        | 1.06%   |
| Logitech Webcam C170                    | 8        | 1.06%   |
| Logitech StreamCam                      | 8        | 1.06%   |
| Sunplus Full HD webcam                  | 6        | 0.79%   |
| Microdia Camera                         | 6        | 0.79%   |
| Chicony HP High Definition 1MP Webcam   | 6        | 0.79%   |
| Realtek Full HD webcam                  | 5        | 0.66%   |
| Logitech HD Webcam C910                 | 5        | 0.66%   |
| Logitech HD Webcam C510                 | 5        | 0.66%   |
| Huawei HiCamera                         | 5        | 0.66%   |
| AVerMedia Live Streamer CAM 313         | 5        | 0.66%   |
| YGTek webcam                            | 4        | 0.53%   |
| Sunplus USB 2.0 Camera                  | 4        | 0.53%   |
| Microdia Sonix USB 2.0 Camera           | 4        | 0.53%   |
| Logitech Logi Webcam C920e              | 4        | 0.53%   |
| Logitech BRIO 4K Stream Edition         | 4        | 0.53%   |
| Logitech B525 HD Webcam                 | 4        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 25%     |
| Elan Microelectronics | 2        | 25%     |
| Validity Sensors      | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| DigitalPersona        | 1        | 12.5%   |
| AuthenTec             | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 2        | 25%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 12.5%   |
| LighTuning Fingerprint Sensor                               | 1        | 12.5%   |
| DigitalPersona Fingerprint Reader                           | 1        | 12.5%   |
| AuthenTec Fingerprint Sensor                                | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 6        | 35.29%  |
| Realtek Semiconductor | 3        | 17.65%  |
| OmniKey               | 3        | 17.65%  |
| Alcor Micro           | 3        | 17.65%  |
| Chicony Electronics   | 1        | 5.88%   |
| Advanced Card Systems | 1        | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 4        | 23.53%  |
| Realtek Semiconductor Smart Card Reader Interface      | 3        | 17.65%  |
| OmniKey CardMan 3021 / 3121                            | 2        | 11.76%  |
| Alcor Micro Watchdata W 1981                           | 2        | 11.76%  |
| SCM Microsystems SCR3500 A Contact Reader              | 1        | 5.88%   |
| SCM Microsystems SCR331 SmartCard Reader               | 1        | 5.88%   |
| OmniKey CardMan 1021                                   | 1        | 5.88%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 5.88%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 5.88%   |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3198     | 80.82%  |
| 1     | 683      | 17.26%  |
| 2     | 64       | 1.62%   |
| 3     | 9        | 0.23%   |
| 7     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |
| 4     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 300      | 36.41%  |
| Graphics card            | 282      | 34.22%  |
| Unassigned class         | 56       | 6.8%    |
| Sound                    | 26       | 3.16%   |
| Multimedia controller    | 26       | 3.16%   |
| Bluetooth                | 25       | 3.03%   |
| Communication controller | 23       | 2.79%   |
| Storage/raid             | 17       | 2.06%   |
| Net/ethernet             | 15       | 1.82%   |
| Chipcard                 | 13       | 1.58%   |
| Network                  | 11       | 1.33%   |
| Fingerprint reader       | 8        | 0.97%   |
| Camera                   | 7        | 0.85%   |
| Storage/ide              | 4        | 0.49%   |
| Card reader              | 4        | 0.49%   |
| Storage/nvme             | 3        | 0.36%   |
| Firewire controller      | 2        | 0.24%   |
| Tv card                  | 1        | 0.12%   |
| Dvb card                 | 1        | 0.12%   |

