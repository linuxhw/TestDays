Pop!_OS 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 1984

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
| ASUSTek       | M5A78L-M/USB3               | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| Lenovo        | 102F SBB0J05441 WIN 3305... | [ea890b85f3](https://linux-hardware.org/?probe=ea890b85f3) | Feb 22, 2023 |
| Gigabyte      | H81M-HD3                    | [d19e079879](https://linux-hardware.org/?probe=d19e079879) | Feb 22, 2023 |
| ASRock        | B550 Extreme4               | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [7dd9134373](https://linux-hardware.org/?probe=7dd9134373) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [fafea002be](https://linux-hardware.org/?probe=fafea002be) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [c0c41ca089](https://linux-hardware.org/?probe=c0c41ca089) | Feb 21, 2023 |
| Alienware     | 0NWN7M A00                  | [eef5c2f68f](https://linux-hardware.org/?probe=eef5c2f68f) | Feb 21, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 6.2.6-76060206-generic   | 303      | 19.26%  |
| 6.0.12-76060006-generic  | 174      | 11.06%  |
| 5.17.5-76051705-generic  | 159      | 10.11%  |
| 5.19.0-76051900-generic  | 144      | 9.15%   |
| 6.5.6-76060506-generic   | 112      | 7.12%   |
| 6.0.6-76060006-generic   | 102      | 6.48%   |
| 6.4.6-76060406-generic   | 89       | 5.66%   |
| 6.6.6-76060606-generic   | 85       | 5.4%    |
| 5.18.10-76051810-generic | 72       | 4.58%   |
| 5.17.15-76051715-generic | 66       | 4.2%    |
| 6.5.4-76060504-generic   | 53       | 3.37%   |
| 5.16.19-76051619-generic | 40       | 2.54%   |
| 6.2.0-76060200-generic   | 37       | 2.35%   |
| 6.1.11-76060111-generic  | 29       | 1.84%   |
| 6.0.2-76060002-generic   | 28       | 1.78%   |
| 5.19.16-76051916-generic | 18       | 1.14%   |
| 6.6.10-76060610-generic  | 14       | 0.89%   |
| 6.0.3-76060003-generic   | 14       | 0.89%   |
| 6.3.7-060307-generic     | 3        | 0.19%   |
| 6.1.0-x64v1-xanmod1      | 2        | 0.13%   |
| 6.7.1-1-liquorix-amd64   | 1        | 0.06%   |
| 6.7.1-060701-generic     | 1        | 0.06%   |
| 6.5.7-x64v3-xanmod1      | 1        | 0.06%   |
| 6.5.5-x64v3-xanmod1      | 1        | 0.06%   |
| 6.5.12-x64v3-xanmod1     | 1        | 0.06%   |
| 6.5.10-x64v3-xanmod1     | 1        | 0.06%   |
| 6.4.8-x64v3-xanmod1      | 1        | 0.06%   |
| 6.3.4-x64v1-xanmod1      | 1        | 0.06%   |
| 6.3.4-060304-generic     | 1        | 0.06%   |
| 6.3.1-x64v1-xanmod1      | 1        | 0.06%   |
| 6.2.9-060209-generic     | 1        | 0.06%   |
| 6.2.8-060208-generic     | 1        | 0.06%   |
| 6.2.2-x64v3-xanmod1      | 1        | 0.06%   |
| 6.1.8-060108-generic     | 1        | 0.06%   |
| 6.1.13-x64v3-xanmod1     | 1        | 0.06%   |
| 6.1.12-x64v3-xanmod1     | 1        | 0.06%   |
| 6.1.0-060100rc5-generic  | 1        | 0.06%   |
| 6.0.9-060009-generic     | 1        | 0.06%   |
| 6.0.8-x64v1-xanmod1      | 1        | 0.06%   |
| 6.0.6-060006-generic     | 1        | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.6   | 303      | 19.26%  |
| 6.0.12  | 175      | 11.13%  |
| 5.17.5  | 159      | 10.11%  |
| 5.19.0  | 144      | 9.15%   |
| 6.5.6   | 112      | 7.12%   |
| 6.0.6   | 103      | 6.55%   |
| 6.4.6   | 89       | 5.66%   |
| 6.6.6   | 85       | 5.4%    |
| 5.18.10 | 72       | 4.58%   |
| 5.17.15 | 66       | 4.2%    |
| 6.5.4   | 53       | 3.37%   |
| 5.16.19 | 40       | 2.54%   |
| 6.2.0   | 37       | 2.35%   |
| 6.1.11  | 29       | 1.84%   |
| 6.0.2   | 29       | 1.84%   |
| 5.19.16 | 18       | 1.14%   |
| 6.6.10  | 14       | 0.89%   |
| 6.0.3   | 14       | 0.89%   |
| 6.3.7   | 3        | 0.19%   |
| 6.1.0   | 3        | 0.19%   |
| 6.7.1   | 2        | 0.13%   |
| 6.3.4   | 2        | 0.13%   |
| 6.5.7   | 1        | 0.06%   |
| 6.5.5   | 1        | 0.06%   |
| 6.5.12  | 1        | 0.06%   |
| 6.5.10  | 1        | 0.06%   |
| 6.4.8   | 1        | 0.06%   |
| 6.3.1   | 1        | 0.06%   |
| 6.2.9   | 1        | 0.06%   |
| 6.2.8   | 1        | 0.06%   |
| 6.2.2   | 1        | 0.06%   |
| 6.1.8   | 1        | 0.06%   |
| 6.1.13  | 1        | 0.06%   |
| 6.1.12  | 1        | 0.06%   |
| 6.0.9   | 1        | 0.06%   |
| 6.0.8   | 1        | 0.06%   |
| 5.4.210 | 1        | 0.06%   |
| 5.19.6  | 1        | 0.06%   |
| 5.18.0  | 1        | 0.06%   |
| 5.17.4  | 1        | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 337      | 21.76%  |
| 6.0     | 316      | 20.4%   |
| 5.17    | 220      | 14.2%   |
| 6.5     | 167      | 10.78%  |
| 5.19    | 162      | 10.46%  |
| 6.6     | 98       | 6.33%   |
| 6.4     | 90       | 5.81%   |
| 5.18    | 73       | 4.71%   |
| 5.16    | 41       | 2.65%   |
| 6.1     | 35       | 2.26%   |
| 6.3     | 6        | 0.39%   |
| 6.7     | 2        | 0.13%   |
| 5.4     | 1        | 0.06%   |
| 5.15    | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1387     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 1333     | 95.69%  |
| KDE5            | 34       | 2.44%   |
| X-Cinnamon      | 8        | 0.57%   |
| Unknown         | 8        | 0.57%   |
| GNOME Flashback | 3        | 0.22%   |
| LXQt            | 2        | 0.14%   |
| i3              | 2        | 0.14%   |
| XFCE            | 1        | 0.07%   |
| UKUI            | 1        | 0.07%   |
| Cinnamon        | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1348     | 96.7%   |
| Wayland | 40       | 2.87%   |
| Unknown | 5        | 0.36%   |
| Tty     | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1124     | 80.75%  |
| GDM3    | 255      | 18.32%  |
| SDDM    | 9        | 0.65%   |
| GDM     | 3        | 0.22%   |
| LightDM | 1        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 819      | 58.5%   |
| en_GB   | 93       | 6.64%   |
| de_DE   | 88       | 6.29%   |
| pt_BR   | 73       | 5.21%   |
| C       | 55       | 3.93%   |
| en_AU   | 35       | 2.5%    |
| en_CA   | 33       | 2.36%   |
| fr_FR   | 28       | 2%      |
| it_IT   | 22       | 1.57%   |
| ru_RU   | 13       | 0.93%   |
| pl_PL   | 13       | 0.93%   |
| es_ES   | 12       | 0.86%   |
| sv_SE   | 9        | 0.64%   |
| Unknown | 8        | 0.57%   |
| fi_FI   | 7        | 0.5%    |
| es_CL   | 7        | 0.5%    |
| da_DK   | 7        | 0.5%    |
| en_IN   | 6        | 0.43%   |
| pt_PT   | 5        | 0.36%   |
| nl_NL   | 5        | 0.36%   |
| ja_JP   | 5        | 0.36%   |
| de_AT   | 5        | 0.36%   |
| nb_NO   | 4        | 0.29%   |
| es_AR   | 4        | 0.29%   |
| en_ZA   | 4        | 0.29%   |
| en_DK   | 4        | 0.29%   |
| zh_TW   | 3        | 0.21%   |
| de_CH   | 3        | 0.21%   |
| ro_RO   | 2        | 0.14%   |
| nl_BE   | 2        | 0.14%   |
| fr_CH   | 2        | 0.14%   |
| fr_CA   | 2        | 0.14%   |
| fr_BE   | 2        | 0.14%   |
| en_NZ   | 2        | 0.14%   |
| en_FI   | 2        | 0.14%   |
| cs_CZ   | 2        | 0.14%   |
| zh_CN   | 1        | 0.07%   |
| sk_SK   | 1        | 0.07%   |
| lv_LV   | 1        | 0.07%   |
| ko_KR   | 1        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1156     | 82.99%  |
| EFI  | 237      | 17.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1322     | 95.04%  |
| Overlay | 31       | 2.23%   |
| Btrfs   | 31       | 2.23%   |
| Xfs     | 3        | 0.22%   |
| Zfs     | 2        | 0.14%   |
| Tmpfs   | 1        | 0.07%   |
| Unknown | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1119     | 80.39%  |
| GPT     | 253      | 18.18%  |
| MBR     | 20       | 1.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1332     | 95.76%  |
| Yes       | 59       | 4.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1232     | 88.57%  |
| Yes       | 159      | 11.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 423      | 30.5%   |
| Gigabyte Technology                  | 248      | 17.88%  |
| MSI                                  | 225      | 16.22%  |
| ASRock                               | 117      | 8.44%   |
| Dell                                 | 90       | 6.49%   |
| Hewlett-Packard                      | 72       | 5.19%   |
| Lenovo                               | 39       | 2.81%   |
| Intel                                | 25       | 1.8%    |
| System76                             | 13       | 0.94%   |
| Unknown                              | 13       | 0.94%   |
| Acer                                 | 11       | 0.79%   |
| Alienware                            | 10       | 0.72%   |
| Fujitsu                              | 9        | 0.65%   |
| BESSTAR Tech                         | 8        | 0.58%   |
| Biostar                              | 7        | 0.5%    |
| Apple                                | 7        | 0.5%    |
| MACHINIST                            | 6        | 0.43%   |
| Foxconn                              | 6        | 0.43%   |
| AZW                                  | 5        | 0.36%   |
| Positivo                             | 4        | 0.29%   |
| Pegatron                             | 4        | 0.29%   |
| NZXT                                 | 4        | 0.29%   |
| Huanan                               | 4        | 0.29%   |
| Supermicro                           | 3        | 0.22%   |
| Samsung Electronics                  | 3        | 0.22%   |
| EVGA                                 | 3        | 0.22%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.14%   |
| ECS                                  | 2        | 0.14%   |
| ASRockRack                           | 2        | 0.14%   |
| ZOTAC                                | 1        | 0.07%   |
| Win element                          | 1        | 0.07%   |
| SZMZ                                 | 1        | 0.07%   |
| Soyo                                 | 1        | 0.07%   |
| SIEMENS                              | 1        | 0.07%   |
| PS                                   | 1        | 0.07%   |
| Packard Bell                         | 1        | 0.07%   |
| Minix                                | 1        | 0.07%   |
| Medion                               | 1        | 0.07%   |
| MAXSUN                               | 1        | 0.07%   |
| LattePanda                           | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 28       | 2.02%   |
| ASUS ROG STRIX B550-F GAMING      | 18       | 1.3%    |
| Unknown                           | 13       | 0.94%   |
| ASUS ROG STRIX B450-F GAMING      | 11       | 0.79%   |
| ASUS TUF Gaming X570-PLUS         | 10       | 0.72%   |
| ASUS ROG STRIX B550-I GAMING      | 10       | 0.72%   |
| Gigabyte X570 AORUS ELITE         | 9        | 0.65%   |
| MSI MS-7C95                       | 8        | 0.58%   |
| MSI MS-7B86                       | 8        | 0.58%   |
| Gigabyte B450 AORUS M             | 8        | 0.58%   |
| ASUS TUF Gaming B550-PLUS         | 8        | 0.58%   |
| MSI MS-7C91                       | 7        | 0.5%    |
| MSI MS-7C37                       | 7        | 0.5%    |
| MSI MS-7C02                       | 7        | 0.5%    |
| MSI MS-7A38                       | 7        | 0.5%    |
| ASUS PRIME B450M-A                | 7        | 0.5%    |
| System76 Thelio                   | 6        | 0.43%   |
| MSI MS-7D54                       | 6        | 0.43%   |
| MSI MS-7C56                       | 6        | 0.43%   |
| Gigabyte B550M DS3H               | 6        | 0.43%   |
| Gigabyte B550I AORUS PRO AX       | 6        | 0.43%   |
| Gigabyte A320M-S2H                | 6        | 0.43%   |
| ASUS TUF Gaming B550M-PLUS        | 6        | 0.43%   |
| ASUS PRIME B550M-A                | 6        | 0.43%   |
| ASUS PRIME A320M-K                | 6        | 0.43%   |
| MSI MS-7D32                       | 5        | 0.36%   |
| MSI MS-7D25                       | 5        | 0.36%   |
| MSI MS-7C35                       | 5        | 0.36%   |
| MSI MS-7A34                       | 5        | 0.36%   |
| MSI MS-7693                       | 5        | 0.36%   |
| Gigabyte X570 I AORUS PRO WIFI    | 5        | 0.36%   |
| Gigabyte X570 AORUS MASTER        | 5        | 0.36%   |
| Gigabyte B450M DS3H               | 5        | 0.36%   |
| Dell OptiPlex 9020                | 5        | 0.36%   |
| Dell OptiPlex 7010                | 5        | 0.36%   |
| Dell OptiPlex 3020                | 5        | 0.36%   |
| ASUS ROG CROSSHAIR VIII HERO      | 5        | 0.36%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 5        | 0.36%   |
| ASUS PRIME Z390-A                 | 5        | 0.36%   |
| ASUS PRIME X570-PRO               | 5        | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 135      | 9.73%   |
| ASUS PRIME             | 77       | 5.55%   |
| ASUS TUF               | 60       | 4.33%   |
| Dell OptiPlex          | 44       | 3.17%   |
| ASUS All               | 28       | 2.02%   |
| Gigabyte X570          | 26       | 1.87%   |
| Lenovo ThinkCentre     | 23       | 1.66%   |
| HP Compaq              | 20       | 1.44%   |
| Gigabyte B450          | 20       | 1.44%   |
| Dell Precision         | 19       | 1.37%   |
| Gigabyte B550          | 14       | 1.01%   |
| System76 Thelio        | 13       | 0.94%   |
| HP EliteDesk           | 13       | 0.94%   |
| Unknown                | 13       | 0.94%   |
| Gigabyte B450M         | 12       | 0.87%   |
| Gigabyte B550M         | 11       | 0.79%   |
| ASRock X570            | 11       | 0.79%   |
| Dell XPS               | 10       | 0.72%   |
| Dell Inspiron          | 10       | 0.72%   |
| ASRock B450            | 9        | 0.65%   |
| Alienware Aurora       | 9        | 0.65%   |
| MSI MS-7C95            | 8        | 0.58%   |
| MSI MS-7B86            | 8        | 0.58%   |
| Fujitsu ESPRIMO        | 8        | 0.58%   |
| ASRock B550            | 8        | 0.58%   |
| MSI MS-7C91            | 7        | 0.5%    |
| MSI MS-7C37            | 7        | 0.5%    |
| MSI MS-7C02            | 7        | 0.5%    |
| MSI MS-7A38            | 7        | 0.5%    |
| Lenovo IdeaCentre      | 7        | 0.5%    |
| Gigabyte A320M-S2H     | 7        | 0.5%    |
| ASRock B450M           | 7        | 0.5%    |
| Acer Aspire            | 7        | 0.5%    |
| MSI MS-7D54            | 6        | 0.43%   |
| MSI MS-7C56            | 6        | 0.43%   |
| HP ProDesk             | 6        | 0.43%   |
| HP OMEN                | 6        | 0.43%   |
| Gigabyte Z390          | 6        | 0.43%   |
| Gigabyte GA-78LMT-USB3 | 6        | 0.43%   |
| Gigabyte B550I         | 6        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 206      | 14.85%  |
| 2018 | 166      | 11.97%  |
| 2019 | 141      | 10.17%  |
| 2021 | 136      | 9.81%   |
| 2022 | 129      | 9.3%    |
| 2012 | 84       | 6.06%   |
| 2017 | 83       | 5.98%   |
| 2013 | 80       | 5.77%   |
| 2014 | 78       | 5.62%   |
| 2011 | 58       | 4.18%   |
| 2015 | 52       | 3.75%   |
| 2016 | 45       | 3.24%   |
| 2010 | 38       | 2.74%   |
| 2009 | 35       | 2.52%   |
| 2023 | 30       | 2.16%   |
| 2008 | 15       | 1.08%   |
| 2007 | 9        | 0.65%   |
| 2006 | 1        | 0.07%   |
| 2005 | 1        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1387     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1384     | 99.71%  |
| Enabled  | 4        | 0.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1387     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 439      | 31.13%  |
| 32.01-64.0      | 398      | 28.23%  |
| 8.01-16.0       | 186      | 13.19%  |
| 64.01-256.0     | 147      | 10.43%  |
| 4.01-8.0        | 113      | 8.01%   |
| 24.01-32.0      | 64       | 4.54%   |
| 3.01-4.0        | 54       | 3.83%   |
| 1.01-2.0        | 4        | 0.28%   |
| More than 256.0 | 3        | 0.21%   |
| 2.01-3.0        | 2        | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 569      | 37.29%  |
| 3.01-4.0    | 308      | 20.18%  |
| 2.01-3.0    | 286      | 18.74%  |
| 8.01-16.0   | 218      | 14.29%  |
| 1.01-2.0    | 98       | 6.42%   |
| 16.01-24.0  | 26       | 1.7%    |
| 32.01-64.0  | 10       | 0.66%   |
| 24.01-32.0  | 9        | 0.59%   |
| 64.01-256.0 | 1        | 0.07%   |
| 0.51-1.0    | 1        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 458      | 32.05%  |
| 1      | 417      | 29.18%  |
| 3      | 272      | 19.03%  |
| 4      | 142      | 9.94%   |
| 5      | 71       | 4.97%   |
| 6      | 35       | 2.45%   |
| 7      | 16       | 1.12%   |
| 9      | 4        | 0.28%   |
| 8      | 4        | 0.28%   |
| 0      | 4        | 0.28%   |
| 11     | 2        | 0.14%   |
| 10     | 2        | 0.14%   |
| 26     | 1        | 0.07%   |
| 19     | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1030     | 73.84%  |
| Yes       | 365      | 26.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1372     | 98.92%  |
| No        | 15       | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 798      | 57.25%  |
| No        | 596      | 42.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 730      | 52.29%  |
| Yes       | 666      | 47.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 502      | 35.99%  |
| Germany      | 129      | 9.25%   |
| Brazil       | 102      | 7.31%   |
| Canada       | 74       | 5.3%    |
| UK           | 67       | 4.8%    |
| Australia    | 48       | 3.44%   |
| Italy        | 43       | 3.08%   |
| France       | 39       | 2.8%    |
| Netherlands  | 26       | 1.86%   |
| Sweden       | 25       | 1.79%   |
| Poland       | 25       | 1.79%   |
| Russia       | 22       | 1.58%   |
| Finland      | 22       | 1.58%   |
| Spain        | 16       | 1.15%   |
| Norway       | 16       | 1.15%   |
| Greece       | 14       | 1%      |
| Austria      | 13       | 0.93%   |
| Mexico       | 12       | 0.86%   |
| India        | 12       | 0.86%   |
| Denmark      | 11       | 0.79%   |
| Switzerland  | 10       | 0.72%   |
| Portugal     | 10       | 0.72%   |
| South Africa | 9        | 0.65%   |
| Japan        | 9        | 0.65%   |
| Hungary      | 9        | 0.65%   |
| Belgium      | 9        | 0.65%   |
| Hong Kong    | 8        | 0.57%   |
| Chile        | 8        | 0.57%   |
| Argentina    | 8        | 0.57%   |
| Romania      | 7        | 0.5%    |
| Malaysia     | 5        | 0.36%   |
| Ireland      | 5        | 0.36%   |
| Czechia      | 5        | 0.36%   |
| Slovakia     | 4        | 0.29%   |
| Serbia       | 4        | 0.29%   |
| Philippines  | 4        | 0.29%   |
| New Zealand  | 4        | 0.29%   |
| Lithuania    | 4        | 0.29%   |
| Indonesia    | 4        | 0.29%   |
| Thailand     | 3        | 0.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Rio de Janeiro | 13       | 0.89%   |
| Berlin         | 12       | 0.83%   |
| Sydney         | 11       | 0.76%   |
| Seattle        | 10       | 0.69%   |
| Sao Paulo      | 10       | 0.69%   |
| Helsinki       | 10       | 0.69%   |
| Melbourne      | 8        | 0.55%   |
| Vienna         | 7        | 0.48%   |
| Toronto        | 7        | 0.48%   |
| Milan          | 7        | 0.48%   |
| Hamburg        | 7        | 0.48%   |
| Denver         | 7        | 0.48%   |
| Cleveland      | 7        | 0.48%   |
| Chicago        | 7        | 0.48%   |
| Edmonton       | 6        | 0.41%   |
| Central        | 6        | 0.41%   |
| Brisbane       | 6        | 0.41%   |
| San Francisco  | 5        | 0.34%   |
| Moscow         | 5        | 0.34%   |
| Miami          | 5        | 0.34%   |
| Mannheim       | 5        | 0.34%   |
| Juiz de Fora   | 5        | 0.34%   |
| Cologne        | 5        | 0.34%   |
| Amsterdam      | 5        | 0.34%   |
| Adelaide       | 5        | 0.34%   |
| Yekaterinburg  | 4        | 0.28%   |
| Weimar         | 4        | 0.28%   |
| Springfield    | 4        | 0.28%   |
| Rome           | 4        | 0.28%   |
| Richmond       | 4        | 0.28%   |
| Portland       | 4        | 0.28%   |
| Perth          | 4        | 0.28%   |
| Nuremberg      | 4        | 0.28%   |
| New York       | 4        | 0.28%   |
| Montreal       | 4        | 0.28%   |
| Madrid         | 4        | 0.28%   |
| Madison        | 4        | 0.28%   |
| Johannesburg   | 4        | 0.28%   |
| Dublin         | 4        | 0.28%   |
| Dallas         | 4        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 540      | 902    | 19.06%  |
| Seagate                     | 418      | 643    | 14.75%  |
| WDC                         | 382      | 574    | 13.48%  |
| Sandisk                     | 194      | 248    | 6.85%   |
| Crucial                     | 157      | 231    | 5.54%   |
| Kingston                    | 155      | 200    | 5.47%   |
| Toshiba                     | 106      | 131    | 3.74%   |
| Phison Electronics          | 61       | 95     | 2.15%   |
| Hitachi                     | 55       | 85     | 1.94%   |
| A-DATA Technology           | 48       | 51     | 1.69%   |
| Micron/Crucial Technology   | 47       | 62     | 1.66%   |
| Intel                       | 47       | 68     | 1.66%   |
| China                       | 36       | 50     | 1.27%   |
| Silicon Motion              | 35       | 44     | 1.24%   |
| PNY                         | 30       | 37     | 1.06%   |
| Kingston Technology Company | 30       | 37     | 1.06%   |
| Phison                      | 29       | 38     | 1.02%   |
| Unknown                     | 28       | 62     | 0.99%   |
| SK hynix                    | 26       | 36     | 0.92%   |
| SPCC                        | 24       | 38     | 0.85%   |
| HGST                        | 22       | 29     | 0.78%   |
| Realtek Semiconductor       | 17       | 19     | 0.6%    |
| Micron Technology           | 17       | 19     | 0.6%    |
| Team                        | 15       | 20     | 0.53%   |
| OCZ                         | 15       | 21     | 0.53%   |
| Patriot                     | 13       | 16     | 0.46%   |
| Intenso                     | 13       | 18     | 0.46%   |
| ADATA Technology            | 13       | 16     | 0.46%   |
| Apple                       | 12       | 13     | 0.42%   |
| Netac                       | 11       | 13     | 0.39%   |
| XPG                         | 10       | 13     | 0.35%   |
| JMicron Technology          | 10       | 21     | 0.35%   |
| Lexar                       | 8        | 10     | 0.28%   |
| Hewlett-Packard             | 8        | 11     | 0.28%   |
| Gigabyte Technology         | 8        | 8      | 0.28%   |
| Corsair                     | 8        | 14     | 0.28%   |
| Unknown                     | 8        | 8      | 0.28%   |
| Verbatim                    | 6        | 10     | 0.21%   |
| Transcend                   | 6        | 8      | 0.21%   |
| T-FORCE                     | 6        | 8      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 81       | 2.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 56       | 1.69%   |
| Seagate ST2000DM008-2FR102 2TB                        | 41       | 1.24%   |
| Samsung SSD 860 EVO 1TB                               | 40       | 1.21%   |
| Samsung SSD 850 EVO 250GB                             | 38       | 1.15%   |
| Kingston SA400S37240G 240GB SSD                       | 36       | 1.09%   |
| Samsung SSD 850 EVO 500GB                             | 35       | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB                        | 31       | 0.94%   |
| Crucial CT1000MX500SSD1 1TB                           | 28       | 0.85%   |
| Samsung SSD 860 EVO 500GB                             | 26       | 0.79%   |
| Samsung NVMe SSD Drive 1TB                            | 25       | 0.76%   |
| Seagate ST4000DM004-2CV104 4TB                        | 24       | 0.73%   |
| Samsung SSD 980 1TB                                   | 24       | 0.73%   |
| Phison E12 NVMe Controller 1TB                        | 24       | 0.73%   |
| Seagate ST500DM002-1BD142 500GB                       | 22       | 0.66%   |
| Samsung SSD 870 QVO 1TB                               | 22       | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 21       | 0.63%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 21       | 0.63%   |
| Kingston SA400S37480G 480GB SSD                       | 21       | 0.63%   |
| Kingston SA400S37120G 120GB SSD                       | 21       | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 19       | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB                        | 19       | 0.57%   |
| SanDisk NVMe SSD Drive 1TB                            | 19       | 0.57%   |
| Crucial CT500MX500SSD1 500GB                          | 19       | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 18       | 0.54%   |
| Samsung NVMe SSD Drive 500GB                          | 18       | 0.54%   |
| Toshiba DT01ACA100 1TB                                | 17       | 0.51%   |
| Crucial CT1000BX500SSD1 1TB                           | 15       | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB                        | 14       | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                          | 14       | 0.42%   |
| Seagate Expansion 1TB                                 | 13       | 0.39%   |
| Sandisk WD Black SN850 1024GB                         | 13       | 0.39%   |
| Samsung SSD 870 EVO 1TB                               | 13       | 0.39%   |
| Phison E16 PCIe4 NVMe Controller 2TB                  | 13       | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                      | 13       | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 12       | 0.36%   |
| Toshiba DT01ACA200 2TB                                | 12       | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB                        | 12       | 0.36%   |
| Samsung SSD 980 PRO 1TB                               | 12       | 0.36%   |
| Samsung SSD 980 500GB                                 | 12       | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 402      | 607    | 41.4%   |
| WDC                 | 316      | 474    | 32.54%  |
| Toshiba             | 94       | 118    | 9.68%   |
| Hitachi             | 55       | 85     | 5.66%   |
| Samsung Electronics | 41       | 50     | 4.22%   |
| HGST                | 22       | 29     | 2.27%   |
| Unknown             | 9        | 13     | 0.93%   |
| JMicron Technology  | 8        | 16     | 0.82%   |
| Apple               | 8        | 8      | 0.82%   |
| TO Exter            | 3        | 3      | 0.31%   |
| Maxtor              | 3        | 3      | 0.31%   |
| SABRENT             | 2        | 3      | 0.21%   |
| Fujitsu             | 2        | 6      | 0.21%   |
| WD MediaMax         | 1        | 2      | 0.1%    |
| RSH-339             | 1        | 1      | 0.1%    |
| MaxDigital          | 1        | 1      | 0.1%    |
| LaCie               | 1        | 2      | 0.1%    |
| ASMT                | 1        | 1      | 0.1%    |
| Unknown             | 1        | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 272      | 420    | 26.67%  |
| Crucial             | 134      | 190    | 13.14%  |
| Kingston            | 125      | 156    | 12.25%  |
| SanDisk             | 70       | 86     | 6.86%   |
| WDC                 | 65       | 79     | 6.37%   |
| A-DATA Technology   | 40       | 43     | 3.92%   |
| China               | 35       | 49     | 3.43%   |
| PNY                 | 30       | 37     | 2.94%   |
| SPCC                | 20       | 26     | 1.96%   |
| Intel               | 20       | 31     | 1.96%   |
| OCZ                 | 15       | 21     | 1.47%   |
| Team                | 13       | 17     | 1.27%   |
| Patriot             | 13       | 16     | 1.27%   |
| SK hynix            | 12       | 16     | 1.18%   |
| Intenso             | 10       | 15     | 0.98%   |
| Netac               | 9        | 11     | 0.88%   |
| Micron Technology   | 7        | 7      | 0.69%   |
| Transcend           | 6        | 8      | 0.59%   |
| Seagate             | 6        | 7      | 0.59%   |
| Lexar               | 6        | 8      | 0.59%   |
| KingSpec            | 6        | 6      | 0.59%   |
| Hewlett-Packard     | 6        | 9      | 0.59%   |
| Apacer              | 6        | 7      | 0.59%   |
| Toshiba             | 5        | 6      | 0.49%   |
| Gigabyte Technology | 5        | 5      | 0.49%   |
| Corsair             | 5        | 7      | 0.49%   |
| Verbatim            | 4        | 8      | 0.39%   |
| SABRENT             | 4        | 4      | 0.39%   |
| Mushkin             | 4        | 5      | 0.39%   |
| GOODRAM             | 4        | 4      | 0.39%   |
| Apple               | 4        | 5      | 0.39%   |
| LITEONIT            | 3        | 3      | 0.29%   |
| LITEON              | 3        | 5      | 0.29%   |
| T-FORCE             | 2        | 2      | 0.2%    |
| Plextor             | 2        | 2      | 0.2%    |
| KingDian            | 2        | 6      | 0.2%    |
| Integral            | 2        | 2      | 0.2%    |
| Fanxiang            | 2        | 2      | 0.2%    |
| Dogfish             | 2        | 2      | 0.2%    |
| ASMT                | 2        | 3      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 813      | 1383   | 34.61%  |
| HDD     | 753      | 1423   | 32.06%  |
| NVMe    | 715      | 1197   | 30.44%  |
| Unknown | 62       | 121    | 2.64%   |
| MMC     | 6        | 7      | 0.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1135     | 2690   | 57.18%  |
| NVMe | 713      | 1191   | 35.92%  |
| SAS  | 131      | 243    | 6.6%    |
| MMC  | 6        | 7      | 0.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 756      | 1246   | 43.13%  |
| 0.51-1.0   | 537      | 824    | 30.63%  |
| 1.01-2.0   | 258      | 391    | 14.72%  |
| 3.01-4.0   | 92       | 159    | 5.25%   |
| 4.01-10.0  | 64       | 116    | 3.65%   |
| 2.01-3.0   | 38       | 55     | 2.17%   |
| 10.01-20.0 | 8        | 15     | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 319      | 21.92%  |
| 251-500        | 269      | 18.49%  |
| 101-250        | 263      | 18.08%  |
| 1001-2000      | 223      | 15.33%  |
| More than 3000 | 181      | 12.44%  |
| 2001-3000      | 102      | 7.01%   |
| 1-20           | 37       | 2.54%   |
| 51-100         | 37       | 2.54%   |
| 21-50          | 13       | 0.89%   |
| Unknown        | 11       | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 326      | 21.43%  |
| 21-50          | 270      | 17.75%  |
| 101-250        | 227      | 14.92%  |
| 251-500        | 172      | 11.31%  |
| 51-100         | 167      | 10.98%  |
| 501-1000       | 138      | 9.07%   |
| 1001-2000      | 103      | 6.77%   |
| More than 3000 | 69       | 4.54%   |
| 2001-3000      | 38       | 2.5%    |
| Unknown        | 11       | 0.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| Seagate ST3250310AS 250GB                   | 2        | 4      | 3.08%   |
| Samsung Electronics SSD 850 EVO 250GB       | 2        | 2      | 3.08%   |
| WDC WD60EFRX-68L0BN1 6TB                    | 1        | 1      | 1.54%   |
| WDC WD5001AALS-00J7B1 500GB                 | 1        | 1      | 1.54%   |
| WDC WD5000AADS-00S9B0 500GB                 | 1        | 1      | 1.54%   |
| WDC WD20PURZ-85AKKY0 2TB                    | 1        | 1      | 1.54%   |
| WDC WD20PURX-64P6ZY0 2TB                    | 1        | 1      | 1.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB                    | 1        | 1      | 1.54%   |
| WDC WD20EFRX-68EUZN0 2TB                    | 1        | 1      | 1.54%   |
| WDC WD20EFRX-68AX9N0 2TB                    | 1        | 8      | 1.54%   |
| WDC WD15EADS-00P8B0 1TB                     | 1        | 1      | 1.54%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1        | 1      | 1.54%   |
| WDC WD10EZEX-60ZF5A0 1TB                    | 1        | 1      | 1.54%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1        | 1      | 1.54%   |
| WDC WD10EZEX-00BN5A0 1TB                    | 1        | 1      | 1.54%   |
| WDC WD10EARS-00MVWB0 1TB                    | 1        | 1      | 1.54%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1        | 1      | 1.54%   |
| WDC WD1001FALS-00E8B0 1TB                   | 1        | 1      | 1.54%   |
| Toshiba MK1655GSX 160GB                     | 1        | 1      | 1.54%   |
| Team T253X1120G 120GB SSD                   | 1        | 1      | 1.54%   |
| Seagate STM3500418AS 500GB                  | 1        | 1      | 1.54%   |
| Seagate ST6000AS0002-1N917X 6TB             | 1        | 1      | 1.54%   |
| Seagate ST500DM002-1BD142 500GB             | 1        | 1      | 1.54%   |
| Seagate ST5000LM000-2AN170 5TB              | 1        | 1      | 1.54%   |
| Seagate ST4000LM024-2AN17V 4TB              | 1        | 1      | 1.54%   |
| Seagate ST4000DX001-1CE168 4TB              | 1        | 1      | 1.54%   |
| Seagate ST320LM001 HN-M320MBB 320GB         | 1        | 1      | 1.54%   |
| Seagate ST2000DM008-2FR102 2TB              | 1        | 1      | 1.54%   |
| Seagate ST2000DM006-2DM164 2TB              | 1        | 1      | 1.54%   |
| Seagate ST2000DM001-1CH164 2TB              | 1        | 1      | 1.54%   |
| Seagate ST2000DL004 HD204UI 2TB             | 1        | 1      | 1.54%   |
| Seagate ST1500DL003-9VT16L 1TB              | 1        | 1      | 1.54%   |
| Seagate Expansion Desk 8TB                  | 1        | 1      | 1.54%   |
| SanDisk SSD PLUS 1000GB                     | 1        | 1      | 1.54%   |
| SanDisk SD8TB8U-256G-1006 256GB SSD         | 1        | 1      | 1.54%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1        | 1      | 1.54%   |
| Samsung Electronics SSD 970 EVO Plus 1TB    | 1        | 1      | 1.54%   |
| Samsung Electronics SSD 870 EVO 1TB         | 1        | 1      | 1.54%   |
| Samsung Electronics SSD 850 PRO 256GB       | 1        | 1      | 1.54%   |
| Samsung Electronics SSD 850 EVO 1TB         | 1        | 1      | 1.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 23     | 25%     |
| Seagate             | 13       | 17     | 21.67%  |
| Samsung Electronics | 11       | 13     | 18.33%  |
| Hitachi             | 3        | 3      | 5%      |
| SanDisk             | 2        | 2      | 3.33%   |
| Kingston            | 2        | 3      | 3.33%   |
| HGST                | 2        | 2      | 3.33%   |
| Crucial             | 2        | 2      | 3.33%   |
| A-DATA Technology   | 2        | 2      | 3.33%   |
| Toshiba             | 1        | 1      | 1.67%   |
| Team                | 1        | 1      | 1.67%   |
| SABRENT             | 1        | 1      | 1.67%   |
| Plextor             | 1        | 1      | 1.67%   |
| Flashwar            | 1        | 1      | 1.67%   |
| China               | 1        | 1      | 1.67%   |
| BAITITON            | 1        | 1      | 1.67%   |
| Apple               | 1        | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 23     | 39.47%  |
| Seagate             | 13       | 17     | 34.21%  |
| Samsung Electronics | 3        | 3      | 7.89%   |
| Hitachi             | 3        | 3      | 7.89%   |
| HGST                | 2        | 2      | 5.26%   |
| Toshiba             | 1        | 1      | 2.63%   |
| Apple               | 1        | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 50     | 61.02%  |
| SSD  | 20       | 22     | 33.9%   |
| NVMe | 3        | 3      | 5.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1154     | 3356   | 77.24%  |
| Works    | 285      | 699    | 19.08%  |
| Malfunc  | 54       | 75     | 3.61%   |
| Failed   | 1        | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 706      | 29.37%  |
| AMD                            | 673      | 28%     |
| Samsung Electronics            | 317      | 13.19%  |
| SanDisk                        | 144      | 5.99%   |
| Phison Electronics             | 94       | 3.91%   |
| ASMedia Technology             | 89       | 3.7%    |
| Micron/Crucial Technology      | 73       | 3.04%   |
| Kingston Technology Company    | 62       | 2.58%   |
| Silicon Motion                 | 40       | 1.66%   |
| Marvell Technology Group       | 30       | 1.25%   |
| Realtek Semiconductor          | 24       | 1%      |
| ADATA Technology               | 24       | 1%      |
| JMicron Technology             | 20       | 0.83%   |
| SK hynix                       | 15       | 0.62%   |
| Nvidia                         | 13       | 0.54%   |
| Seagate Technology             | 12       | 0.5%    |
| Micron Technology              | 11       | 0.46%   |
| Toshiba America Info Systems   | 8        | 0.33%   |
| MAXIO Technology (Hangzhou)    | 7        | 0.29%   |
| Broadcom / LSI                 | 7        | 0.29%   |
| Solidigm                       | 6        | 0.25%   |
| LSI Logic / Symbios Logic      | 5        | 0.21%   |
| KIOXIA                         | 4        | 0.17%   |
| INNOGRIT                       | 4        | 0.17%   |
| VIA Technologies               | 3        | 0.12%   |
| Lite-On Technology             | 3        | 0.12%   |
| Solid State Storage Technology | 2        | 0.08%   |
| Silicon Image                  | 2        | 0.08%   |
| Shenzhen Longsys Electronics   | 2        | 0.08%   |
| Union Memory (Shenzhen)        | 1        | 0.04%   |
| Netac Technology               | 1        | 0.04%   |
| Biwin Storage Technology       | 1        | 0.04%   |
| Adaptec                        | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 349      | 12.29%  |
| AMD 500 Series Chipset SATA Controller                                                  | 163      | 5.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 160      | 5.64%   |
| AMD 400 Series Chipset SATA Controller                                                  | 142      | 5%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 93       | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 82       | 2.89%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 82       | 2.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 60       | 2.11%   |
| Intel SATA Controller [RAID mode]                                                       | 57       | 2.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 57       | 2.01%   |
| AMD 600 Series Chipset SATA Controller                                                  | 54       | 1.9%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 49       | 1.73%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 46       | 1.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 43       | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 42       | 1.48%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 40       | 1.41%   |
| Phison E12 NVMe Controller                                                              | 39       | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 39       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 35       | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 33       | 1.16%   |
| AMD 300 Series Chipset SATA Controller                                                  | 33       | 1.16%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 32       | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 31       | 1.09%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 30       | 1.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 30       | 1.06%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 26       | 0.92%   |
| AMD FCH SATA Controller D                                                               | 26       | 0.92%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 23       | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 21       | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21       | 0.74%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 20       | 0.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 20       | 0.7%    |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 20       | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 20       | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 20       | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 19       | 0.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 19       | 0.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 17       | 0.6%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 17       | 0.6%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 16       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1235     | 55.61%  |
| NVMe | 713      | 32.1%   |
| IDE  | 161      | 7.25%   |
| RAID | 96       | 4.32%   |
| SAS  | 14       | 0.63%   |
| SCSI | 2        | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 698      | 50.32%  |
| AMD    | 689      | 49.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 45       | 3.23%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 39       | 2.8%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 38       | 2.73%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 33       | 2.37%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 32       | 2.3%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 30       | 2.16%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 27       | 1.94%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 27       | 1.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 22       | 1.58%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 19       | 1.36%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 18       | 1.29%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 17       | 1.22%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 17       | 1.22%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 16       | 1.15%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 15       | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 14       | 1.01%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 14       | 1.01%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 13       | 0.93%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 13       | 0.93%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 13       | 0.93%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 13       | 0.93%   |
| AMD FX-8350 Eight-Core Processor            | 13       | 0.93%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 12       | 0.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 12       | 0.86%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 11       | 0.79%   |
| Intel 12th Gen Core i9-12900K               | 11       | 0.79%   |
| AMD Ryzen 7 7700X 8-Core Processor          | 11       | 0.79%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 11       | 0.79%   |
| AMD Ryzen 5 5600 6-Core Processor           | 11       | 0.79%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11       | 0.79%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 10       | 0.72%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 10       | 0.72%   |
| AMD Ryzen 5 7600X 6-Core Processor          | 10       | 0.72%   |
| AMD FX-6300 Six-Core Processor              | 10       | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9        | 0.65%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 9        | 0.65%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 9        | 0.65%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 9        | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 0.57%   |
| Intel 13th Gen Core i7-13700K               | 8        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 234      | 16.81%  |
| Intel Core i7           | 205      | 14.73%  |
| AMD Ryzen 7             | 201      | 14.44%  |
| Intel Core i5           | 192      | 13.79%  |
| AMD Ryzen 9             | 114      | 8.19%   |
| Other                   | 90       | 6.47%   |
| Intel Xeon              | 67       | 4.81%   |
| Intel Core i3           | 53       | 3.81%   |
| AMD FX                  | 43       | 3.09%   |
| Intel Core i9           | 24       | 1.72%   |
| AMD Ryzen 3             | 17       | 1.22%   |
| Intel Celeron           | 13       | 0.93%   |
| AMD Ryzen Threadripper  | 13       | 0.93%   |
| Intel Pentium           | 12       | 0.86%   |
| Intel Core 2 Duo        | 12       | 0.86%   |
| Intel Core 2 Quad       | 11       | 0.79%   |
| AMD Athlon II X2        | 9        | 0.65%   |
| AMD Athlon II X4        | 7        | 0.5%    |
| AMD Phenom II X4        | 6        | 0.43%   |
| AMD A8                  | 6        | 0.43%   |
| Intel Pentium Gold      | 5        | 0.36%   |
| AMD Ryzen 5 PRO         | 5        | 0.36%   |
| AMD Athlon              | 5        | 0.36%   |
| AMD A4                  | 5        | 0.36%   |
| AMD A10                 | 5        | 0.36%   |
| AMD Phenom II X6        | 4        | 0.29%   |
| Intel Pentium Dual-Core | 3        | 0.22%   |
| Intel Pentium D         | 3        | 0.22%   |
| Intel Core 2            | 3        | 0.22%   |
| AMD Phenom              | 3        | 0.22%   |
| AMD Athlon X4           | 3        | 0.22%   |
| Intel Pentium Silver    | 2        | 0.14%   |
| Intel Pentium Dual      | 2        | 0.14%   |
| Intel Atom              | 2        | 0.14%   |
| AMD Phenom II X3        | 2        | 0.14%   |
| AMD A6                  | 2        | 0.14%   |
| AMD Sempron             | 1        | 0.07%   |
| AMD Ryzen Embedded      | 1        | 0.07%   |
| AMD Ryzen 7 PRO         | 1        | 0.07%   |
| AMD Ryzen 3 PRO         | 1        | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 437      | 31.39%  |
| 6      | 314      | 22.56%  |
| 8      | 268      | 19.25%  |
| 2      | 124      | 8.91%   |
| 12     | 86       | 6.18%   |
| 16     | 84       | 6.03%   |
| 10     | 26       | 1.87%   |
| 3      | 18       | 1.29%   |
| 24     | 11       | 0.79%   |
| 14     | 11       | 0.79%   |
| 1      | 7        | 0.5%    |
| 32     | 2        | 0.14%   |
| 18     | 2        | 0.14%   |
| 64     | 1        | 0.07%   |
| 36     | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1372     | 98.92%  |
| 2      | 15       | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 1056     | 76.14%  |
| 1      | 331      | 23.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1387     | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1186     | 84.53%  |
| 0x08701021 | 27       | 1.92%   |
| 0x0a601203 | 18       | 1.28%   |
| 0x0800820d | 17       | 1.21%   |
| 0x0a201016 | 15       | 1.07%   |
| 0x0a20120a | 13       | 0.93%   |
| 0x0a50000d | 8        | 0.57%   |
| 0x506e3    | 7        | 0.5%    |
| 0x90672    | 6        | 0.43%   |
| 0x306c3    | 6        | 0.43%   |
| 0x306a9    | 6        | 0.43%   |
| 0x08701013 | 6        | 0.43%   |
| 0x906ec    | 5        | 0.36%   |
| 0x206a7    | 5        | 0.36%   |
| 0x0a201205 | 5        | 0.36%   |
| 0x08108109 | 5        | 0.36%   |
| 0x08001137 | 5        | 0.36%   |
| 0x906e9    | 4        | 0.29%   |
| 0x0a201009 | 4        | 0.29%   |
| 0x08001138 | 4        | 0.29%   |
| 0xa0655    | 3        | 0.21%   |
| 0x906ea    | 3        | 0.21%   |
| 0x0a50000c | 3        | 0.21%   |
| 0x0a20102b | 3        | 0.21%   |
| 0x08101016 | 3        | 0.21%   |
| 0x06003106 | 3        | 0.21%   |
| 0x06000852 | 3        | 0.21%   |
| 0xa0671    | 2        | 0.14%   |
| 0xa0653    | 2        | 0.14%   |
| 0x50657    | 2        | 0.14%   |
| 0x0a601206 | 2        | 0.14%   |
| 0x0a601201 | 2        | 0.14%   |
| 0x0a201025 | 2        | 0.14%   |
| 0xb0671    | 1        | 0.07%   |
| 0x906ed    | 1        | 0.07%   |
| 0x906c0    | 1        | 0.07%   |
| 0x806d1    | 1        | 0.07%   |
| 0x406f1    | 1        | 0.07%   |
| 0x306e4    | 1        | 0.07%   |
| 0x0a404102 | 1        | 0.07%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 231      | 16.61%  |
| Zen 2            | 151      | 10.86%  |
| Haswell          | 145      | 10.42%  |
| Unknown          | 138      | 9.92%   |
| KabyLake         | 102      | 7.33%   |
| Zen+             | 84       | 6.04%   |
| IvyBridge        | 75       | 5.39%   |
| Skylake          | 72       | 5.18%   |
| SandyBridge      | 64       | 4.6%    |
| Zen              | 60       | 4.31%   |
| Piledriver       | 48       | 3.45%   |
| CometLake        | 46       | 3.31%   |
| K10              | 32       | 2.3%    |
| Nehalem          | 27       | 1.94%   |
| Penryn           | 23       | 1.65%   |
| Alderlake Hybrid | 20       | 1.44%   |
| Westmere         | 14       | 1.01%   |
| Steamroller      | 10       | 0.72%   |
| Core             | 10       | 0.72%   |
| Broadwell        | 10       | 0.72%   |
| Silvermont       | 4        | 0.29%   |
| Excavator        | 4        | 0.29%   |
| NetBurst         | 3        | 0.22%   |
| Icelake          | 3        | 0.22%   |
| Goldmont         | 3        | 0.22%   |
| Bulldozer        | 3        | 0.22%   |
| K8 Hammer        | 2        | 0.14%   |
| Jaguar           | 2        | 0.14%   |
| Goldmont plus    | 2        | 0.14%   |
| Tremont          | 1        | 0.07%   |
| K10 Llano        | 1        | 0.07%   |
| Gracemont        | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 736      | 48.17%  |
| AMD                        | 538      | 35.21%  |
| Intel                      | 253      | 16.56%  |
| Matrox Electronics Systems | 1        | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 79       | 4.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 59       | 3.71%   |
| AMD Raphael                                                                 | 47       | 2.96%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 38       | 2.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 37       | 2.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 36       | 2.26%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 35       | 2.2%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 35       | 2.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 34       | 2.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 27       | 1.7%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 25       | 1.57%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 24       | 1.51%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 23       | 1.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 23       | 1.45%   |
| Intel HD Graphics 530                                                       | 22       | 1.38%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 21       | 1.32%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 20       | 1.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 20       | 1.26%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 19       | 1.19%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 19       | 1.19%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 18       | 1.13%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 18       | 1.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 18       | 1.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 18       | 1.13%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 17       | 1.07%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 16       | 1.01%   |
| Nvidia GK208B [GeForce GT 710]                                              | 16       | 1.01%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 15       | 0.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 14       | 0.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 14       | 0.88%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 14       | 0.88%   |
| Intel AlderLake-S GT1                                                       | 14       | 0.88%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 14       | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 13       | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 13       | 0.82%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 13       | 0.82%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 13       | 0.82%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 13       | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 13       | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 12       | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 660      | 46.71%  |
| 1 x AMD              | 451      | 31.92%  |
| 1 x Intel            | 171      | 12.1%   |
| 2 x AMD              | 43       | 3.04%   |
| AMD + Nvidia         | 33       | 2.34%   |
| Intel + Nvidia       | 31       | 2.19%   |
| 2 x Nvidia           | 10       | 0.71%   |
| Intel + AMD          | 9        | 0.64%   |
| Other                | 1        | 0.07%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.07%   |
| 1 x Matrox           | 1        | 0.07%   |
| Intel + 2 x Nvidia   | 1        | 0.07%   |
| AMD + 2 x Nvidia     | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 733      | 51.95%  |
| Proprietary | 625      | 44.29%  |
| Unknown     | 53       | 3.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 989      | 69.55%  |
| 7.01-8.0   | 113      | 7.95%   |
| 8.01-16.0  | 86       | 6.05%   |
| 1.01-2.0   | 67       | 4.71%   |
| 3.01-4.0   | 63       | 4.43%   |
| 5.01-6.0   | 52       | 3.66%   |
| 0.51-1.0   | 14       | 0.98%   |
| 2.01-3.0   | 13       | 0.91%   |
| 16.01-24.0 | 13       | 0.91%   |
| 0.01-0.5   | 11       | 0.77%   |
| 32.01-64.0 | 1        | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 266      | 16.73%  |
| Goldstar             | 200      | 12.58%  |
| Dell                 | 167      | 10.5%   |
| Acer                 | 121      | 7.61%   |
| Hewlett-Packard      | 95       | 5.97%   |
| AOC                  | 95       | 5.97%   |
| BenQ                 | 70       | 4.4%    |
| Ancor Communications | 70       | 4.4%    |
| ASUSTek Computer     | 69       | 4.34%   |
| Philips              | 44       | 2.77%   |
| MSI                  | 30       | 1.89%   |
| Iiyama               | 29       | 1.82%   |
| Lenovo               | 27       | 1.7%    |
| ViewSonic            | 21       | 1.32%   |
| Gigabyte Technology  | 16       | 1.01%   |
| Sceptre Tech         | 15       | 0.94%   |
| Sony                 | 13       | 0.82%   |
| Vizio                | 11       | 0.69%   |
| NEC Computers        | 11       | 0.69%   |
| Mi                   | 8        | 0.5%    |
| Eizo                 | 8        | 0.5%    |
| Unknown              | 6        | 0.38%   |
| Sharp                | 6        | 0.38%   |
| Fujitsu Siemens      | 6        | 0.38%   |
| Valve                | 5        | 0.31%   |
| Unknown (XXX)        | 5        | 0.31%   |
| Toshiba              | 5        | 0.31%   |
| Panasonic            | 5        | 0.31%   |
| HKC                  | 5        | 0.31%   |
| Viotek               | 4        | 0.25%   |
| Vestel Elektronik    | 4        | 0.25%   |
| Pioneer              | 4        | 0.25%   |
| ONN                  | 4        | 0.25%   |
| Medion               | 4        | 0.25%   |
| Insignia             | 4        | 0.25%   |
| Hitachi              | 4        | 0.25%   |
| GDH                  | 4        | 0.25%   |
| Unknown              | 4        | 0.25%   |
| Xiaomi               | 3        | 0.19%   |
| Wacom                | 3        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 13       | 0.77%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 13       | 0.77%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 9        | 0.53%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                        | 9        | 0.53%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 8        | 0.47%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 7        | 0.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 7        | 0.41%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch        | 7        | 0.41%   |
| Samsung Electronics LC34G55T SAM711A 3440x1440 798x334mm 34.1-inch      | 6        | 0.35%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 6        | 0.35%   |
| Valve Index HMD VLV91A8                                                 | 5        | 0.3%    |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch    | 5        | 0.3%    |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 700x400mm 31.7-inch      | 5        | 0.3%    |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 5        | 0.3%    |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch                | 5        | 0.3%    |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                     | 5        | 0.3%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 5        | 0.3%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 5        | 0.3%    |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 5        | 0.3%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 5        | 0.3%    |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                     | 5        | 0.3%    |
| AOC 2460 AOC0001 1920x1080 531x299mm 24.0-inch                          | 5        | 0.3%    |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 5        | 0.3%    |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch   | 5        | 0.3%    |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch    | 4        | 0.24%   |
| Samsung Electronics LS49AG95 SAM71AC 3840x1080 1193x336mm 48.8-inch     | 4        | 0.24%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 4        | 0.24%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 4        | 0.24%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 697x392mm 31.5-inch       | 4        | 0.24%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 4        | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 4        | 0.24%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch                 | 4        | 0.24%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                 | 4        | 0.24%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch             | 4        | 0.24%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 4        | 0.24%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 4        | 0.24%   |
| GDH Digital TV GDH0030 1920x540                                         | 4        | 0.24%   |
| Dell S3422DWG DELD12C 3440x1440 797x334mm 34.0-inch                     | 4        | 0.24%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                       | 4        | 0.24%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch            | 4        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 673      | 44.1%   |
| 3840x2160 (4K)     | 243      | 15.92%  |
| 2560x1440 (QHD)    | 189      | 12.39%  |
| 3440x1440          | 79       | 5.18%   |
| 1366x768 (WXGA)    | 48       | 3.15%   |
| 2560x1080          | 45       | 2.95%   |
| 1680x1050 (WSXGA+) | 41       | 2.69%   |
| 1280x1024 (SXGA)   | 34       | 2.23%   |
| 1920x1200 (WUXGA)  | 32       | 2.1%    |
| 1600x900 (HD+)     | 32       | 2.1%    |
| 3840x1080          | 22       | 1.44%   |
| 1440x900 (WXGA+)   | 20       | 1.31%   |
| 1360x768           | 15       | 0.98%   |
| 1920x540           | 11       | 0.72%   |
| 3840x1600          | 9        | 0.59%   |
| Unknown            | 9        | 0.59%   |
| 1024x768 (XGA)     | 5        | 0.33%   |
| 2560x1600          | 4        | 0.26%   |
| 1600x1200          | 3        | 0.2%    |
| 4480x1440          | 2        | 0.13%   |
| 3840x1200          | 2        | 0.13%   |
| 1280x720 (HD)      | 2        | 0.13%   |
| 3280x1080          | 1        | 0.07%   |
| 3040x900           | 1        | 0.07%   |
| 2880x1600          | 1        | 0.07%   |
| 2288x1287          | 1        | 0.07%   |
| 2048x1152          | 1        | 0.07%   |
| 1280x800 (WXGA)    | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 318      | 19.95%  |
| 24      | 243      | 15.24%  |
| 23      | 186      | 11.67%  |
| 31      | 137      | 8.59%   |
| 21      | 122      | 7.65%   |
| 34      | 107      | 6.71%   |
| Unknown | 52       | 3.26%   |
| 19      | 42       | 2.63%   |
| 84      | 34       | 2.13%   |
| 22      | 32       | 2.01%   |
| 18      | 31       | 1.94%   |
| 32      | 30       | 1.88%   |
| 20      | 30       | 1.88%   |
| 48      | 23       | 1.44%   |
| 72      | 21       | 1.32%   |
| 17      | 20       | 1.25%   |
| 28      | 16       | 1%      |
| 54      | 15       | 0.94%   |
| 37      | 12       | 0.75%   |
| 15      | 12       | 0.75%   |
| 25      | 11       | 0.69%   |
| 40      | 9        | 0.56%   |
| 26      | 8        | 0.5%    |
| 52      | 7        | 0.44%   |
| 65      | 6        | 0.38%   |
| 35      | 6        | 0.38%   |
| 29      | 6        | 0.38%   |
| 12      | 6        | 0.38%   |
| 46      | 5        | 0.31%   |
| 36      | 5        | 0.31%   |
| 33      | 5        | 0.31%   |
| 44      | 4        | 0.25%   |
| 42      | 4        | 0.25%   |
| 16      | 4        | 0.25%   |
| 49      | 3        | 0.19%   |
| 38      | 3        | 0.19%   |
| 13      | 3        | 0.19%   |
| 74      | 2        | 0.13%   |
| 69      | 2        | 0.13%   |
| 57      | 2        | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 657      | 43.51%  |
| 401-500     | 232      | 15.36%  |
| 601-700     | 196      | 12.98%  |
| 701-800     | 140      | 9.27%   |
| 1001-1500   | 70       | 4.64%   |
| 1501-2000   | 60       | 3.97%   |
| Unknown     | 52       | 3.44%   |
| 801-900     | 35       | 2.32%   |
| 301-350     | 31       | 2.05%   |
| 351-400     | 22       | 1.46%   |
| 201-300     | 9        | 0.6%    |
| 901-1000    | 6        | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1052     | 74.93%  |
| 21/9    | 132      | 9.4%    |
| 16/10   | 118      | 8.4%    |
| 5/4     | 35       | 2.49%   |
| 32/9    | 26       | 1.85%   |
| Unknown | 22       | 1.57%   |
| 4/3     | 16       | 1.14%   |
| 3.20    | 2        | 0.14%   |
| 3/2     | 1        | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 451      | 29.19%  |
| 301-350        | 328      | 21.23%  |
| 351-500        | 289      | 18.71%  |
| 151-200        | 98       | 6.34%   |
| More than 1000 | 96       | 6.21%   |
| 251-300        | 90       | 5.83%   |
| 501-1000       | 66       | 4.27%   |
| Unknown        | 52       | 3.37%   |
| 141-150        | 49       | 3.17%   |
| 101-110        | 13       | 0.84%   |
| 71-80          | 9        | 0.58%   |
| 111-120        | 2        | 0.13%   |
| 131-140        | 1        | 0.06%   |
| 121-130        | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 873      | 60.12%  |
| 101-120       | 319      | 21.97%  |
| 121-160       | 91       | 6.27%   |
| 1-50          | 65       | 4.48%   |
| Unknown       | 52       | 3.58%   |
| 161-240       | 51       | 3.51%   |
| More than 240 | 1        | 0.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1003     | 71.29%  |
| 2     | 294      | 20.9%   |
| 0     | 59       | 4.19%   |
| 3     | 42       | 2.99%   |
| 4     | 7        | 0.5%    |
| 6     | 1        | 0.07%   |
| 5     | 1        | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 825      | 39.95%  |
| Intel                           | 723      | 35.01%  |
| Qualcomm Atheros                | 115      | 5.57%   |
| MediaTek                        | 66       | 3.2%    |
| Broadcom                        | 58       | 2.81%   |
| TP-Link                         | 41       | 1.99%   |
| Ralink Technology               | 24       | 1.16%   |
| Aquantia                        | 21       | 1.02%   |
| Microsoft                       | 20       | 0.97%   |
| NetGear                         | 19       | 0.92%   |
| Samsung Electronics             | 14       | 0.68%   |
| InterBiometrics                 | 13       | 0.63%   |
| Ralink                          | 12       | 0.58%   |
| Nvidia                          | 11       | 0.53%   |
| Google                          | 9        | 0.44%   |
| Linksys                         | 8        | 0.39%   |
| ASIX Electronics                | 8        | 0.39%   |
| Qualcomm Atheros Communications | 7        | 0.34%   |
| D-Link                          | 7        | 0.34%   |
| Xiaomi                          | 6        | 0.29%   |
| D-Link System                   | 6        | 0.29%   |
| Broadcom Limited                | 6        | 0.29%   |
| Mellanox Technologies           | 4        | 0.19%   |
| Marvell Technology Group        | 4        | 0.19%   |
| Huawei Technologies             | 4        | 0.19%   |
| ASUSTek Computer                | 4        | 0.19%   |
| QinHeng Electronics             | 2        | 0.1%    |
| OPPO Electronics                | 2        | 0.1%    |
| Belkin Components               | 2        | 0.1%    |
| Wacom                           | 1        | 0.05%   |
| VIA Technologies                | 1        | 0.05%   |
| U-Blox                          | 1        | 0.05%   |
| T & A Mobile Phones             | 1        | 0.05%   |
| STMicroelectronics              | 1        | 0.05%   |
| Sitecom Europe                  | 1        | 0.05%   |
| SIEMENS                         | 1        | 0.05%   |
| ROCCAT                          | 1        | 0.05%   |
| Qualcomm Technologies           | 1        | 0.05%   |
| Qualcomm                        | 1        | 0.05%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 571      | 23.39%  |
| Realtek RTL8125 2.5GbE Controller                                              | 173      | 7.09%   |
| Intel Wi-Fi 6 AX200                                                            | 159      | 6.51%   |
| Intel I211 Gigabit Network Connection                                          | 151      | 6.19%   |
| Intel Ethernet Controller I225-V                                               | 127      | 5.2%    |
| Intel Ethernet Connection (2) I219-V                                           | 49       | 2.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 46       | 1.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 45       | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 40       | 1.64%   |
| Intel Ethernet Connection I217-LM                                              | 36       | 1.47%   |
| Realtek 802.11ac NIC                                                           | 31       | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 29       | 1.19%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 29       | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                           | 26       | 1.07%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 25       | 1.02%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 23       | 0.94%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 20       | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 19       | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                           | 19       | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 17       | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 16       | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 16       | 0.66%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                              | 15       | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 14       | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 14       | 0.57%   |
| Intel Ethernet Connection I217-V                                               | 14       | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 13       | 0.53%   |
| InterBiometrics Io                                                             | 13       | 0.53%   |
| Intel 82579V Gigabit Network Connection                                        | 13       | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 12       | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 12       | 0.49%   |
| Ralink MT7601U Wireless Adapter                                                | 11       | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 11       | 0.45%   |
| Intel Wireless 7260                                                            | 11       | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                                          | 11       | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 11       | 0.45%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 11       | 0.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 10       | 0.41%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 10       | 0.41%   |
| Microsoft Xbox 360 Wireless Adapter                                            | 10       | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 384      | 45.28%  |
| Realtek Semiconductor           | 141      | 16.63%  |
| MediaTek                        | 66       | 7.78%   |
| Qualcomm Atheros                | 60       | 7.08%   |
| Broadcom                        | 43       | 5.07%   |
| TP-Link                         | 37       | 4.36%   |
| Ralink Technology               | 24       | 2.83%   |
| Microsoft                       | 20       | 2.36%   |
| NetGear                         | 19       | 2.24%   |
| Ralink                          | 12       | 1.42%   |
| Linksys                         | 8        | 0.94%   |
| Qualcomm Atheros Communications | 7        | 0.83%   |
| D-Link                          | 6        | 0.71%   |
| D-Link System                   | 5        | 0.59%   |
| ASUSTek Computer                | 4        | 0.47%   |
| Broadcom Limited                | 3        | 0.35%   |
| Belkin Components               | 2        | 0.24%   |
| Wacom                           | 1        | 0.12%   |
| Sitecom Europe                  | 1        | 0.12%   |
| Micro Star International        | 1        | 0.12%   |
| IMC Networks                    | 1        | 0.12%   |
| Gemtek                          | 1        | 0.12%   |
| Edimax Technology               | 1        | 0.12%   |
| AVM                             | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 159      | 18.57%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 46       | 5.37%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 45       | 5.26%   |
| Realtek 802.11ac NIC                                          | 31       | 3.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 29       | 3.39%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 29       | 3.39%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 25       | 2.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 23       | 2.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 20       | 2.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 16       | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 16       | 1.87%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 15       | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 14       | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 12       | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 12       | 1.4%    |
| Ralink MT7601U Wireless Adapter                               | 11       | 1.29%   |
| Intel Wireless 7260                                           | 11       | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                | 11       | 1.29%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 10       | 1.17%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 10       | 1.17%   |
| Microsoft Xbox 360 Wireless Adapter                           | 10       | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 10       | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 9        | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 9        | 1.05%   |
| Intel Wireless 8265 / 8275                                    | 9        | 1.05%   |
| Intel Wireless 7265                                           | 9        | 1.05%   |
| TP-Link 802.11ac NIC                                          | 8        | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 8        | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 8        | 0.93%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]   | 8        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 7        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 7        | 0.82%   |
| Qualcomm Atheros AR9271 802.11n                               | 7        | 0.82%   |
| NetGear A6210                                                 | 7        | 0.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 6        | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 6        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 6        | 0.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 5        | 0.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 5        | 0.58%   |
| Intel Wireless 3165                                           | 5        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 770      | 51.03%  |
| Intel                    | 563      | 37.31%  |
| Qualcomm Atheros         | 61       | 4.04%   |
| Aquantia                 | 21       | 1.39%   |
| Broadcom                 | 19       | 1.26%   |
| Samsung Electronics      | 14       | 0.93%   |
| Nvidia                   | 11       | 0.73%   |
| Google                   | 9        | 0.6%    |
| ASIX Electronics         | 8        | 0.53%   |
| Xiaomi                   | 6        | 0.4%    |
| TP-Link                  | 4        | 0.27%   |
| Marvell Technology Group | 4        | 0.27%   |
| Mellanox Technologies    | 3        | 0.2%    |
| Huawei Technologies      | 3        | 0.2%    |
| Broadcom Limited         | 3        | 0.2%    |
| OPPO Electronics         | 2        | 0.13%   |
| VIA Technologies         | 1        | 0.07%   |
| T & A Mobile Phones      | 1        | 0.07%   |
| Qualcomm                 | 1        | 0.07%   |
| Lenovo                   | 1        | 0.07%   |
| DisplayLink              | 1        | 0.07%   |
| D-Link System            | 1        | 0.07%   |
| D-Link                   | 1        | 0.07%   |
| American Megatrends      | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 571      | 36.67%  |
| Realtek RTL8125 2.5GbE Controller                                               | 173      | 11.11%  |
| Intel I211 Gigabit Network Connection                                           | 151      | 9.7%    |
| Intel Ethernet Controller I225-V                                                | 127      | 8.16%   |
| Intel Ethernet Connection (2) I219-V                                            | 49       | 3.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 40       | 2.57%   |
| Intel Ethernet Connection I217-LM                                               | 36       | 2.31%   |
| Intel Ethernet Connection (7) I219-V                                            | 26       | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 19       | 1.22%   |
| Intel Ethernet Connection (2) I218-V                                            | 19       | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 17       | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 14       | 0.9%    |
| Intel Ethernet Connection I217-V                                                | 14       | 0.9%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 13       | 0.83%   |
| Intel 82579V Gigabit Network Connection                                         | 13       | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 11       | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                           | 11       | 0.71%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 11       | 0.71%   |
| Intel Ethernet Controller I226-V                                                | 10       | 0.64%   |
| Intel 82574L Gigabit Network Connection                                         | 10       | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 9        | 0.58%   |
| Nvidia MCP61 Ethernet                                                           | 9        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 7        | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                  | 7        | 0.45%   |
| Intel I210 Gigabit Network Connection                                           | 7        | 0.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                | 7        | 0.45%   |
| Intel Ethernet Connection (2) I218-LM                                           | 6        | 0.39%   |
| Intel Ethernet Connection (11) I219-V                                           | 6        | 0.39%   |
| Intel 82567LM-3 Gigabit Network Connection                                      | 6        | 0.39%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 6        | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                     | 5        | 0.32%   |
| Realtek Killer E2600 GbE Controller                                             | 5        | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 5        | 0.32%   |
| Intel Ethernet Connection (17) I219-V                                           | 5        | 0.32%   |
| Intel 82578DM Gigabit Network Connection                                        | 5        | 0.32%   |
| Google Pixel 8                                                                  | 5        | 0.32%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 5        | 0.32%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                 | 4        | 0.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                 | 4        | 0.26%   |
| Intel Ethernet Connection (5) I219-LM                                           | 4        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1373     | 62.38%  |
| WiFi     | 800      | 36.35%  |
| Modem    | 20       | 0.91%   |
| Unknown  | 8        | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1038     | 70.04%  |
| WiFi     | 444      | 29.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 701      | 50.4%   |
| 2     | 581      | 41.77%  |
| 3     | 88       | 6.33%   |
| 0     | 11       | 0.79%   |
| 4     | 7        | 0.5%    |
| 5     | 3        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 930      | 65.96%  |
| Yes  | 480      | 34.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 352      | 51.16%  |
| Cambridge Silicon Radio         | 104      | 15.12%  |
| Realtek Semiconductor           | 49       | 7.12%   |
| MediaTek                        | 42       | 6.1%    |
| ASUSTek Computer                | 33       | 4.8%    |
| Qualcomm Atheros Communications | 18       | 2.62%   |
| Apple                           | 16       | 2.33%   |
| TP-Link                         | 14       | 2.03%   |
| Broadcom                        | 13       | 1.89%   |
| IMC Networks                    | 12       | 1.74%   |
| Foxconn / Hon Hai               | 11       | 1.6%    |
| Dynex                           | 6        | 0.87%   |
| Actions                         | 4        | 0.58%   |
| Realtek                         | 2        | 0.29%   |
| Lite-On Technology              | 2        | 0.29%   |
| Integrated System Solution      | 2        | 0.29%   |
| Edimax Technology               | 2        | 0.29%   |
| SINO WEALTH                     | 1        | 0.15%   |
| Micro Star International        | 1        | 0.15%   |
| Logitech                        | 1        | 0.15%   |
| HTC (High Tech Computer)        | 1        | 0.15%   |
| Dell                            | 1        | 0.15%   |
| Belkin Components               | 1        | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                    | 144      | 20.9%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 104      | 15.09%  |
| MediaTek Wireless_Device                                 | 42       | 6.1%    |
| Intel Wireless-AC 3168 Bluetooth                         | 42       | 6.1%    |
| Intel AX210 Bluetooth                                    | 40       | 5.81%   |
| Realtek Bluetooth Radio                                  | 39       | 5.66%   |
| Intel AX201 Bluetooth                                    | 39       | 5.66%   |
| Intel Bluetooth wireless interface                       | 32       | 4.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 19       | 2.76%   |
| Intel Bluetooth Device                                   | 18       | 2.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 17       | 2.47%   |
| TP-Link UB500 Adapter                                    | 14       | 2.03%   |
| Qualcomm Atheros  Bluetooth Device                       | 11       | 1.6%    |
| ASUS Bluetooth Radio                                     | 10       | 1.45%   |
| ASUS ASUS USB-BT500                                      | 10       | 1.45%   |
| Realtek  Bluetooth 4.2 Adapter                           | 9        | 1.31%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 9        | 1.31%   |
| Apple Bluetooth Host Controller                          | 9        | 1.31%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 8        | 1.16%   |
| IMC Networks Bluetooth Radio                             | 6        | 0.87%   |
| Foxconn / Hon Hai Wireless_Device                        | 6        | 0.87%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 6        | 0.87%   |
| IMC Networks Wireless_Device                             | 5        | 0.73%   |
| Actions general adapter                                  | 4        | 0.58%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 3        | 0.44%   |
| Foxconn / Hon Hai Bluetooth Device                       | 3        | 0.44%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 3        | 0.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 3        | 0.44%   |
| Realtek Bluetooth Radio                                  | 2        | 0.29%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2        | 0.29%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth              | 2        | 0.29%   |
| Edimax Bluetooth Adapter                                 | 2        | 0.29%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 2        | 0.29%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 0.29%   |
| Apple Bluetooth USB Host Controller                      | 2        | 0.29%   |
| Apple Bluetooth HCI                                      | 2        | 0.29%   |
| SINO WEALTH RK Bluetooth Keyboar                         | 1        | 0.15%   |
| Realtek Bluetooth 5.3 Radio                              | 1        | 0.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 1        | 0.15%   |
| Qualcomm Atheros Bluetooth                               | 1        | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 817      | 28.75%  |
| Nvidia                               | 722      | 25.4%   |
| Intel                                | 677      | 23.82%  |
| C-Media Electronics                  | 81       | 2.85%   |
| Logitech                             | 45       | 1.58%   |
| Kingston Technology                  | 36       | 1.27%   |
| ASUSTek Computer                     | 36       | 1.27%   |
| Razer USA                            | 34       | 1.2%    |
| Creative Labs                        | 30       | 1.06%   |
| Micro Star International             | 29       | 1.02%   |
| Focusrite-Novation                   | 25       | 0.88%   |
| JMTek                                | 22       | 0.77%   |
| SteelSeries ApS                      | 21       | 0.74%   |
| Corsair                              | 16       | 0.56%   |
| Creative Technology                  | 14       | 0.49%   |
| Texas Instruments                    | 12       | 0.42%   |
| Generalplus Technology               | 12       | 0.42%   |
| Blue Microphones                     | 12       | 0.42%   |
| KTMicro                              | 8        | 0.28%   |
| GN Netcom                            | 8        | 0.28%   |
| DSEA A/S                             | 8        | 0.28%   |
| Valve Software                       | 7        | 0.25%   |
| Tenx Technology                      | 6        | 0.21%   |
| Plantronics                          | 6        | 0.21%   |
| Giga-Byte Technology                 | 6        | 0.21%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.18%   |
| Realtek Semiconductor                | 5        | 0.18%   |
| Dell                                 | 5        | 0.18%   |
| BEHRINGER International              | 5        | 0.18%   |
| Astro Gaming                         | 5        | 0.18%   |
| Medeli Electronics                   | 4        | 0.14%   |
| M-Audio                              | 4        | 0.14%   |
| Yamaha                               | 3        | 0.11%   |
| Trust                                | 3        | 0.11%   |
| Sony                                 | 3        | 0.11%   |
| Schiit Audio                         | 3        | 0.11%   |
| SAVITECH                             | 3        | 0.11%   |
| RODE Microphones                     | 3        | 0.11%   |
| PreSonus Audio Electronics           | 3        | 0.11%   |
| Native Instruments                   | 3        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 299      | 8.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 157      | 4.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 131      | 3.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 103      | 3.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 96       | 2.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 86       | 2.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 76       | 2.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 75       | 2.23%   |
| Intel 200 Series PCH HD Audio                                              | 66       | 1.97%   |
| Nvidia TU116 High Definition Audio Controller                              | 62       | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 62       | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 60       | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 60       | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 60       | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 59       | 1.76%   |
| Nvidia GA102 High Definition Audio Controller                              | 57       | 1.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 57       | 1.7%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 50       | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 49       | 1.46%   |
| Nvidia GP106 High Definition Audio Controller                              | 47       | 1.4%    |
| Intel Alder Lake-S HD Audio Controller                                     | 44       | 1.31%   |
| Intel Cannon Lake PCH cAVS                                                 | 42       | 1.25%   |
| AMD Navi 10 HDMI Audio                                                     | 42       | 1.25%   |
| Nvidia TU104 HD Audio Controller                                           | 40       | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 39       | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 38       | 1.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 33       | 0.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 31       | 0.92%   |
| Micro Star International USB Audio                                         | 29       | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 29       | 0.86%   |
| ASUSTek Computer USB Audio                                                 | 27       | 0.8%    |
| AMD Navi 31 HDMI/DP Audio                                                  | 27       | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 26       | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 25       | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 23       | 0.69%   |
| Nvidia Audio device                                                        | 23       | 0.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 22       | 0.66%   |
| Intel Raptor Lake High Definition Audio Controller                         | 21       | 0.63%   |
| Intel Comet Lake PCH cAVS                                                  | 21       | 0.63%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 21       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 87       | 27.19%  |
| G.Skill                      | 53       | 16.56%  |
| Kingston                     | 48       | 15%     |
| Crucial                      | 26       | 8.13%   |
| Samsung Electronics          | 23       | 7.19%   |
| Team                         | 20       | 6.25%   |
| SK hynix                     | 13       | 4.06%   |
| Unknown                      | 12       | 3.75%   |
| Micron Technology            | 10       | 3.13%   |
| A-DATA Technology            | 7        | 2.19%   |
| Unknown                      | 5        | 1.56%   |
| Patriot                      | 4        | 1.25%   |
| Unknown (ABCD)               | 1        | 0.31%   |
| Teikon                       | 1        | 0.31%   |
| Patriot Memory (PDP Systems) | 1        | 0.31%   |
| Patriot Memory               | 1        | 0.31%   |
| Neo Forza                    | 1        | 0.31%   |
| Juhor                        | 1        | 0.31%   |
| Goldkey                      | 1        | 0.31%   |
| GeIL                         | 1        | 0.31%   |
| Colorful                     | 1        | 0.31%   |
| Avant                        | 1        | 0.31%   |
| Asgard                       | 1        | 0.31%   |
| Apacer                       | 1        | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 11       | 3.23%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s    | 9        | 2.64%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 7        | 2.05%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 7        | 2.05%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 5        | 1.47%   |
| Unknown                                                  | 5        | 1.47%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s      | 4        | 1.17%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 4        | 1.17%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s       | 3        | 0.88%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 3        | 0.88%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s   | 3        | 0.88%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s    | 3        | 0.88%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 3        | 0.88%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s   | 3        | 0.88%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s             | 3        | 0.88%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s       | 2        | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s | 2        | 0.59%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s      | 2        | 0.59%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 2        | 0.59%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 0.59%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 2        | 0.59%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s        | 2        | 0.59%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s         | 2        | 0.59%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s    | 2        | 0.59%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s       | 2        | 0.59%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s     | 2        | 0.59%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s     | 2        | 0.59%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s       | 2        | 0.59%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s     | 2        | 0.59%   |
| G.Skill RAM F4-3600C18-32GVK 32GB DIMM DDR4 3600MT/s     | 2        | 0.59%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s     | 2        | 0.59%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s   | 2        | 0.59%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 2        | 0.59%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 2        | 0.59%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s      | 2        | 0.59%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s    | 2        | 0.59%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16GB DIMM DDR4 3400MT/s | 2        | 0.59%   |
| Corsair RAM CMK64GX5M2B5200C40 32GB DIMM DDR5 5200MT/s   | 2        | 0.59%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3266MT/s   | 2        | 0.59%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s   | 2        | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 211      | 70.57%  |
| DDR3    | 45       | 15.05%  |
| DDR5    | 34       | 11.37%  |
| DDR2    | 3        | 1%      |
| Unknown | 3        | 1%      |
| LPDDR4  | 2        | 0.67%   |
| SDRAM   | 1        | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 285      | 95.64%  |
| SODIMM       | 12       | 4.03%   |
| Row Of Chips | 1        | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 120      | 38.46%  |
| 16384 | 106      | 33.97%  |
| 32768 | 45       | 14.42%  |
| 4096  | 36       | 11.54%  |
| 2048  | 4        | 1.28%   |
| 1024  | 1        | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 56       | 17.34%  |
| 3200  | 38       | 11.76%  |
| 1600  | 36       | 11.15%  |
| 3800  | 20       | 6.19%   |
| 2667  | 16       | 4.95%   |
| 3733  | 15       | 4.64%   |
| 2400  | 13       | 4.02%   |
| 4800  | 12       | 3.72%   |
| 3533  | 9        | 2.79%   |
| 2133  | 9        | 2.79%   |
| 1333  | 8        | 2.48%   |
| 6000  | 7        | 2.17%   |
| 3534  | 7        | 2.17%   |
| 3000  | 6        | 1.86%   |
| 2666  | 6        | 1.86%   |
| 5200  | 5        | 1.55%   |
| 2933  | 5        | 1.55%   |
| 5600  | 4        | 1.24%   |
| 3400  | 4        | 1.24%   |
| 1866  | 4        | 1.24%   |
| 6400  | 3        | 0.93%   |
| 4000  | 3        | 0.93%   |
| 3866  | 3        | 0.93%   |
| 3266  | 3        | 0.93%   |
| 2800  | 3        | 0.93%   |
| 4400  | 2        | 0.62%   |
| 3666  | 2        | 0.62%   |
| 3466  | 2        | 0.62%   |
| 3333  | 2        | 0.62%   |
| 3100  | 2        | 0.62%   |
| 3066  | 2        | 0.62%   |
| 1867  | 2        | 0.62%   |
| 800   | 2        | 0.62%   |
| 667   | 2        | 0.62%   |
| 12800 | 1        | 0.31%   |
| 6800  | 1        | 0.31%   |
| 6600  | 1        | 0.31%   |
| 3500  | 1        | 0.31%   |
| 2733  | 1        | 0.31%   |
| 2600  | 1        | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 18       | 35.29%  |
| Brother Industries  | 9        | 17.65%  |
| Canon               | 7        | 13.73%  |
| Samsung Electronics | 6        | 11.76%  |
| Seiko Epson         | 4        | 7.84%   |
| Dymo-CoStar         | 3        | 5.88%   |
| STMicroelectronics  | 1        | 1.96%   |
| QinHeng Electronics | 1        | 1.96%   |
| Prolific Technology | 1        | 1.96%   |
| Dell                | 1        | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Brother HL-2130 series                       | 3        | 5.77%   |
| Seiko Epson WF-4830 Series                   | 2        | 3.85%   |
| HP ENVY Pro 6400 series                      | 2        | 3.85%   |
| Dymo-CoStar LabelWriter 450                  | 2        | 3.85%   |
| STMicroelectronics USB Printer P             | 1        | 1.92%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.92%   |
| Seiko Epson ET-2800 Series                   | 1        | 1.92%   |
| Samsung SCX-4500 Laser Printer               | 1        | 1.92%   |
| Samsung SCX-3400 Series                      | 1        | 1.92%   |
| Samsung ML-216x Series Laser Printer         | 1        | 1.92%   |
| Samsung ML-191x/ML-252x Laser Printer        | 1        | 1.92%   |
| Samsung M2070 Series                         | 1        | 1.92%   |
| Samsung C460 Series                          | 1        | 1.92%   |
| QinHeng CH340S                               | 1        | 1.92%   |
| Prolific PL2305 Parallel Port                | 1        | 1.92%   |
| HP PSC-1315/PSC-1317                         | 1        | 1.92%   |
| HP OfficeJet Pro 9010 series                 | 1        | 1.92%   |
| HP Officejet 4500 G510a-f                    | 1        | 1.92%   |
| HP LaserJet Professional P1102w              | 1        | 1.92%   |
| HP LaserJet Professional P 1102w             | 1        | 1.92%   |
| HP LaserJet Pro M201dw                       | 1        | 1.92%   |
| HP LaserJet Pro M118-M119                    | 1        | 1.92%   |
| HP LaserJet P2035                            | 1        | 1.92%   |
| HP LaserJet M203-M206                        | 1        | 1.92%   |
| HP LaserJet 3050                             | 1        | 1.92%   |
| HP LaserJet 1018                             | 1        | 1.92%   |
| HP Ink Tank 110 series                       | 1        | 1.92%   |
| HP HP LaserJet M14-M17                       | 1        | 1.92%   |
| HP Deskjet F2280 series                      | 1        | 1.92%   |
| HP Deskjet 3520 series                       | 1        | 1.92%   |
| HP DeskJet 2600 series                       | 1        | 1.92%   |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1        | 1.92%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 1        | 1.92%   |
| Dell Laser Printer 1720                      | 1        | 1.92%   |
| Canon TS9100 series                          | 1        | 1.92%   |
| Canon TR8500 series                          | 1        | 1.92%   |
| Canon TR4700 series                          | 1        | 1.92%   |
| Canon Pro9000II series                       | 1        | 1.92%   |
| Canon PIXMA MX490 Series                     | 1        | 1.92%   |
| Canon PIXMA MP240                            | 1        | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 4        | 36.36%  |
| Canon           | 4        | 36.36%  |
| Hewlett-Packard | 2        | 18.18%  |
| Mustek Systems  | 1        | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1        | 9.09%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 9.09%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 9.09%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1        | 9.09%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 9.09%   |
| HP Scanjet G2710                                        | 1        | 9.09%   |
| HP ScanJet 82x0C                                        | 1        | 9.09%   |
| Canon CanoScan N650U/N656U                              | 1        | 9.09%   |
| Canon CanoScan LiDE 60                                  | 1        | 9.09%   |
| Canon CanoScan LiDE 200                                 | 1        | 9.09%   |
| Canon CanoScan 9000F Mark II                            | 1        | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 134      | 40.98%  |
| Microdia                      | 33       | 10.09%  |
| Sunplus Innovation Technology | 19       | 5.81%   |
| Microsoft                     | 16       | 4.89%   |
| Apple                         | 13       | 3.98%   |
| Samsung Electronics           | 8        | 2.45%   |
| Razer USA                     | 7        | 2.14%   |
| Jieli Technology              | 7        | 2.14%   |
| Valve Software                | 6        | 1.83%   |
| Creative Technology           | 6        | 1.83%   |
| ARC International             | 6        | 1.83%   |
| Realtek Semiconductor         | 5        | 1.53%   |
| Generalplus Technology        | 5        | 1.53%   |
| MacroSilicon                  | 4        | 1.22%   |
| Cubeternet                    | 4        | 1.22%   |
| YGTek                         | 3        | 0.92%   |
| Trust                         | 3        | 0.92%   |
| LG Electronics                | 3        | 0.92%   |
| Hewlett-Packard               | 3        | 0.92%   |
| Chicony Electronics           | 3        | 0.92%   |
| Z-Star Microelectronics       | 2        | 0.61%   |
| Sunplus IT                    | 2        | 0.61%   |
| Ruision                       | 2        | 0.61%   |
| OmniVision Technologies       | 2        | 0.61%   |
| eMeet                         | 2        | 0.61%   |
| Elgato Systems                | 2        | 0.61%   |
| AVerMedia Technologies        | 2        | 0.61%   |
| 04004000_P040200_SN0002       | 2        | 0.61%   |
| YT-221117-J                   | 1        | 0.31%   |
| Xiaomi                        | 1        | 0.31%   |
| XHT-210518                    | 1        | 0.31%   |
| webcamvendor                  | 1        | 0.31%   |
| WaveRider Communications      | 1        | 0.31%   |
| ValueHD                       | 1        | 0.31%   |
| USB Camera                    | 1        | 0.31%   |
| Unknown                       | 1        | 0.31%   |
| SunplusIT                     | 1        | 0.31%   |
| Polycom                       | 1        | 0.31%   |
| Philips (or NXP)              | 1        | 0.31%   |
| Owon                          | 1        | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 30       | 9.09%   |
| Logitech HD Pro Webcam C920                           | 25       | 7.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                    | 13       | 3.94%   |
| Logitech C920 PRO HD Webcam                           | 12       | 3.64%   |
| Microdia Webcam Vitade AF                             | 11       | 3.33%   |
| Microdia USB 2.0 Camera                               | 11       | 3.33%   |
| Logitech C922 Pro Stream Webcam                       | 11       | 3.33%   |
| Samsung Galaxy series, misc. (MTP mode)               | 8        | 2.42%   |
| Logitech BRIO Ultra HD Webcam                         | 8        | 2.42%   |
| Logitech Webcam C925e                                 | 7        | 2.12%   |
| Jieli USB PHY 2.0                                     | 7        | 2.12%   |
| Valve Software 3D Camera                              | 6        | 1.82%   |
| Microsoft LifeCam HD-3000                             | 6        | 1.82%   |
| Logitech HD Webcam C615                               | 6        | 1.82%   |
| Logitech HD Webcam C525                               | 6        | 1.82%   |
| ARC International Camera                              | 6        | 1.82%   |
| Razer USA Gaming Webcam [Kiyo]                        | 5        | 1.52%   |
| Logitech Webcam C930e                                 | 5        | 1.52%   |
| Generalplus GENERAL WEBCAM                            | 5        | 1.52%   |
| Sunplus Full HD webcam                                | 4        | 1.21%   |
| Microsoft LifeCam Cinema                              | 4        | 1.21%   |
| MacroSilicon USB3. 0 capture                          | 4        | 1.21%   |
| Logitech StreamCam                                    | 4        | 1.21%   |
| YGTek Webcam                                          | 3        | 0.91%   |
| Sunplus FHD Capture                                   | 3        | 0.91%   |
| Sunplus FHD Camera Microphone                         | 3        | 0.91%   |
| Microdia Camera                                       | 3        | 0.91%   |
| Microdia AUKEY-W1                                     | 3        | 0.91%   |
| Logitech BRIO 4K Stream Edition                       | 3        | 0.91%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 3        | 0.91%   |
| Trust USB Camera                                      | 2        | 0.61%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                    | 2        | 0.61%   |
| Sunplus SPCA2281 Web Camera                           | 2        | 0.61%   |
| Sunplus HD 720P webcam                                | 2        | 0.61%   |
| Ruision UVC Camera                                    | 2        | 0.61%   |
| Realtek Full HD webcam                                | 2        | 0.61%   |
| Microdia Integrated Camera                            | 2        | 0.61%   |
| Logitech Webcam C310                                  | 2        | 0.61%   |
| Logitech Webcam C170                                  | 2        | 0.61%   |
| Logitech HD Webcam C910                               | 2        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 33.33%  |
| Elan Microelectronics | 1        | 33.33%  |
| DigitalPersona        | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor               | 1        | 33.33%  |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 33.33%  |
| DigitalPersona Fingerprint Reader           | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Alcor Micro           | 2        | 40%     |
| SCM Microsystems      | 1        | 20%     |
| Realtek Semiconductor | 1        | 20%     |
| Advanced Card Systems | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 20%     |
| Realtek Semiconductor Smart Card Reader Interface      | 1        | 20%     |
| Alcor Micro Watchdata W 1981                           | 1        | 20%     |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 20%     |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1166     | 82.34%  |
| 1     | 228      | 16.1%   |
| 2     | 20       | 1.41%   |
| 3     | 2        | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 90       | 33.96%  |
| Graphics card            | 74       | 27.92%  |
| Unassigned class         | 23       | 8.68%   |
| Bluetooth                | 17       | 6.42%   |
| Sound                    | 11       | 4.15%   |
| Multimedia controller    | 11       | 4.15%   |
| Net/ethernet             | 8        | 3.02%   |
| Communication controller | 8        | 3.02%   |
| Storage/raid             | 6        | 2.26%   |
| Chipcard                 | 4        | 1.51%   |
| Fingerprint reader       | 3        | 1.13%   |
| Camera                   | 3        | 1.13%   |
| Storage/nvme             | 2        | 0.75%   |
| Network                  | 2        | 0.75%   |
| Tv card                  | 1        | 0.38%   |
| Storage/ide              | 1        | 0.38%   |
| Firewire controller      | 1        | 0.38%   |

