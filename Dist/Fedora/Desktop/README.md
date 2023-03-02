Fedora - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 5624

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550M-A               | [48c5c743c9](https://linux-hardware.org/?probe=48c5c743c9) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| HP            | 158A                        | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| MSI           | X99A RAIDER                 | [f27314deb8](https://linux-hardware.org/?probe=f27314deb8) | Feb 28, 2023 |
| ASRock        | H81M-HG4 R4.0               | [47ed7baef0](https://linux-hardware.org/?probe=47ed7baef0) | Feb 28, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | [3a9683fbb7](https://linux-hardware.org/?probe=3a9683fbb7) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| Gigabyte      | Z170MX-Gaming 5             | [1f0e9197f9](https://linux-hardware.org/?probe=1f0e9197f9) | Feb 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [a121d0545a](https://linux-hardware.org/?probe=a121d0545a) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c56cf68cef](https://linux-hardware.org/?probe=c56cf68cef) | Feb 26, 2023 |
| Gigabyte      | EX58-UD5                    | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| Gigabyte      | H510M S2                    | [24ea8468ca](https://linux-hardware.org/?probe=24ea8468ca) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [c204192a4b](https://linux-hardware.org/?probe=c204192a4b) | Feb 26, 2023 |
| Gigabyte      | H310M D3H                   | [058fac57c2](https://linux-hardware.org/?probe=058fac57c2) | Feb 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | [420520e3ab](https://linux-hardware.org/?probe=420520e3ab) | Feb 25, 2023 |
| Dell          | 0W2F8G A01                  | [1d0d54843b](https://linux-hardware.org/?probe=1d0d54843b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| MSI           | X99A RAIDER                 | [d6c6778bb7](https://linux-hardware.org/?probe=d6c6778bb7) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | [27fa5a62b6](https://linux-hardware.org/?probe=27fa5a62b6) | Feb 24, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| MSI           | B350M PRO-VDH               | [748d109cb3](https://linux-hardware.org/?probe=748d109cb3) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [5d901ddc4e](https://linux-hardware.org/?probe=5d901ddc4e) | Feb 24, 2023 |
| MSI           | X99A RAIDER                 | [7b4981d722](https://linux-hardware.org/?probe=7b4981d722) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| MSI           | Z170A PC MATE               | [5ee58b9271](https://linux-hardware.org/?probe=5ee58b9271) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [acdea94715](https://linux-hardware.org/?probe=acdea94715) | Feb 23, 2023 |
| MSI           | MEG Z390 GODLIKE            | [5f091de01b](https://linux-hardware.org/?probe=5f091de01b) | Feb 23, 2023 |
| Gateway       | SX2185                      | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASRock        | B450M Pro4                  | [193a97dfb1](https://linux-hardware.org/?probe=193a97dfb1) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [eade3920d9](https://linux-hardware.org/?probe=eade3920d9) | Feb 23, 2023 |
| ASUSTek       | P5L-MX                      | [cc19e49d3c](https://linux-hardware.org/?probe=cc19e49d3c) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| ASUSTek       | P5L-MX                      | [9eb9ca3cfb](https://linux-hardware.org/?probe=9eb9ca3cfb) | Feb 22, 2023 |
| MSI           | MEG Z390 GODLIKE            | [974ae4135b](https://linux-hardware.org/?probe=974ae4135b) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| ASRock        | AB350 Pro4                  | [aaad317fe4](https://linux-hardware.org/?probe=aaad317fe4) | Feb 22, 2023 |
| ASRockRack    | X470D4U                     | [162a5279bc](https://linux-hardware.org/?probe=162a5279bc) | Feb 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| ASRock        | B550M Steel Legend          | [c3f49d4cee](https://linux-hardware.org/?probe=c3f49d4cee) | Feb 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [8fd85f724b](https://linux-hardware.org/?probe=8fd85f724b) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH X99              | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| ASRock        | X670E Pro RS                | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f9314a0aa9](https://linux-hardware.org/?probe=f9314a0aa9) | Feb 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6eda9f2592](https://linux-hardware.org/?probe=6eda9f2592) | Feb 19, 2023 |
| ASUSTek       | P5Q SE2                     | [37b0d0609f](https://linux-hardware.org/?probe=37b0d0609f) | Feb 18, 2023 |
| ASRock        | H110 Pro BTC+               | [bce117c4dc](https://linux-hardware.org/?probe=bce117c4dc) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| MSI           | H410M PRO-VH                | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| MSI           | X99A RAIDER                 | [8dabbaa31c](https://linux-hardware.org/?probe=8dabbaa31c) | Feb 18, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [f9fb638882](https://linux-hardware.org/?probe=f9fb638882) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [750c0f6337](https://linux-hardware.org/?probe=750c0f6337) | Feb 17, 2023 |
| ASRock        | X470 Taichi                 | [71685845fe](https://linux-hardware.org/?probe=71685845fe) | Feb 17, 2023 |
| MSI           | X99A RAIDER                 | [991b8b4361](https://linux-hardware.org/?probe=991b8b4361) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | [a19a7a2edd](https://linux-hardware.org/?probe=a19a7a2edd) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| ASRock        | Z370 Pro4                   | [bafba5486b](https://linux-hardware.org/?probe=bafba5486b) | Feb 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f4e8b0e952](https://linux-hardware.org/?probe=f4e8b0e952) | Feb 16, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [ca54397755](https://linux-hardware.org/?probe=ca54397755) | Feb 15, 2023 |
| Supermicro    | X10DRG-Q                    | [5af331bc84](https://linux-hardware.org/?probe=5af331bc84) | Feb 15, 2023 |
| MSI           | FM2-A75MA-E35               | [a7f2ca398d](https://linux-hardware.org/?probe=a7f2ca398d) | Feb 15, 2023 |
| Gigabyte      | H410M DS2V                  | [b2e8c15dc4](https://linux-hardware.org/?probe=b2e8c15dc4) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7d8c3e7e48](https://linux-hardware.org/?probe=7d8c3e7e48) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [0033422c4d](https://linux-hardware.org/?probe=0033422c4d) | Feb 14, 2023 |
| HP            | 8714                        | [19a66b5101](https://linux-hardware.org/?probe=19a66b5101) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [43dff5bee7](https://linux-hardware.org/?probe=43dff5bee7) | Feb 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | [10c8101c9b](https://linux-hardware.org/?probe=10c8101c9b) | Feb 14, 2023 |
| MSI           | X99A RAIDER                 | [387ec47efe](https://linux-hardware.org/?probe=387ec47efe) | Feb 14, 2023 |
| ASUSTek       | Z170-A                      | [6cf7a75c9e](https://linux-hardware.org/?probe=6cf7a75c9e) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | 0KWVT8 A03                  | [eec95070bb](https://linux-hardware.org/?probe=eec95070bb) | Feb 13, 2023 |
| Dell          | 0R6PCT A01                  | [4126ed8507](https://linux-hardware.org/?probe=4126ed8507) | Feb 13, 2023 |
| Pegatron      | 2AB6                        | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASUSTek       | PRIME B550M-A               | [2d63c8d887](https://linux-hardware.org/?probe=2d63c8d887) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| ASUSTek       | Z97-P                       | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASRock        | Z790 Pro RS WiFi            | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| ASRock        | A300M-STX                   | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| HP            | 8714                        | [3938395f75](https://linux-hardware.org/?probe=3938395f75) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [70b81f3738](https://linux-hardware.org/?probe=70b81f3738) | Feb 09, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [0b05e41c64](https://linux-hardware.org/?probe=0b05e41c64) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1adfd2bb79](https://linux-hardware.org/?probe=1adfd2bb79) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [3482c24991](https://linux-hardware.org/?probe=3482c24991) | Feb 08, 2023 |
| MSI           | H110M PRO-VD PLUS           | [c296dedf74](https://linux-hardware.org/?probe=c296dedf74) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [a12cca2eeb](https://linux-hardware.org/?probe=a12cca2eeb) | Feb 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [b02b8779fc](https://linux-hardware.org/?probe=b02b8779fc) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [147b5315c5](https://linux-hardware.org/?probe=147b5315c5) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH X79              | [21910f6687](https://linux-hardware.org/?probe=21910f6687) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Lenovo        | ThinkServer TS140           | [1bac17097f](https://linux-hardware.org/?probe=1bac17097f) | Feb 07, 2023 |
| ASUSTek       | SABERTOOTH X79              | [ace0ce95b9](https://linux-hardware.org/?probe=ace0ce95b9) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [47153e938c](https://linux-hardware.org/?probe=47153e938c) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [0376f0c65f](https://linux-hardware.org/?probe=0376f0c65f) | Feb 07, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e82192ba4c](https://linux-hardware.org/?probe=e82192ba4c) | Feb 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d91fe3e151](https://linux-hardware.org/?probe=d91fe3e151) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31a56f80dd](https://linux-hardware.org/?probe=31a56f80dd) | Feb 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [ff01db5c9a](https://linux-hardware.org/?probe=ff01db5c9a) | Feb 06, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f1e58aba53](https://linux-hardware.org/?probe=f1e58aba53) | Feb 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [10cf328828](https://linux-hardware.org/?probe=10cf328828) | Feb 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [781dc9da09](https://linux-hardware.org/?probe=781dc9da09) | Feb 06, 2023 |
| Compal        | DIP00                       | [632d4c313a](https://linux-hardware.org/?probe=632d4c313a) | Feb 06, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [522dd694da](https://linux-hardware.org/?probe=522dd694da) | Feb 05, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [99d0ce5421](https://linux-hardware.org/?probe=99d0ce5421) | Feb 05, 2023 |
| HP            | 1589                        | [1872d63c2b](https://linux-hardware.org/?probe=1872d63c2b) | Feb 05, 2023 |
| HP            | 1589                        | [69c0ab962c](https://linux-hardware.org/?probe=69c0ab962c) | Feb 05, 2023 |
| Intel         | X99                         | [e8790caf8d](https://linux-hardware.org/?probe=e8790caf8d) | Feb 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [944149e350](https://linux-hardware.org/?probe=944149e350) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| Gigabyte      | Z77MX-D3H                   | [a17959ea9b](https://linux-hardware.org/?probe=a17959ea9b) | Feb 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3633683d62](https://linux-hardware.org/?probe=3633683d62) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [f2578f11e1](https://linux-hardware.org/?probe=f2578f11e1) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5e9c75d478](https://linux-hardware.org/?probe=5e9c75d478) | Feb 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [e680a7484e](https://linux-hardware.org/?probe=e680a7484e) | Feb 03, 2023 |
| HP            | 8714                        | [b8abceccbc](https://linux-hardware.org/?probe=b8abceccbc) | Feb 03, 2023 |
| Pegatron      | IPXSB-H61                   | [a694854d87](https://linux-hardware.org/?probe=a694854d87) | Feb 02, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [09811b1f20](https://linux-hardware.org/?probe=09811b1f20) | Feb 02, 2023 |
| Acer          | Veriton M2631 V:1.0         | [28e1975b51](https://linux-hardware.org/?probe=28e1975b51) | Feb 02, 2023 |
| MSI           | X99S SLI PLUS               | [6b007d74de](https://linux-hardware.org/?probe=6b007d74de) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [9b8d82dfcd](https://linux-hardware.org/?probe=9b8d82dfcd) | Feb 02, 2023 |
| Gigabyte      | J1900M-D2P                  | [c7b6222f08](https://linux-hardware.org/?probe=c7b6222f08) | Feb 02, 2023 |
| ASRock        | Z77 Extreme4                | [6598bc47dd](https://linux-hardware.org/?probe=6598bc47dd) | Feb 02, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [15c523ee98](https://linux-hardware.org/?probe=15c523ee98) | Feb 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f2919f7135](https://linux-hardware.org/?probe=f2919f7135) | Feb 01, 2023 |
| ASRock        | B450M Pro4 R2.0             | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| ASUSTek       | H81M-A/BR                   | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [d35cf58f46](https://linux-hardware.org/?probe=d35cf58f46) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| MSI           | Z170A PC MATE               | [ff305089b2](https://linux-hardware.org/?probe=ff305089b2) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [779b723b67](https://linux-hardware.org/?probe=779b723b67) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [5f2948351d](https://linux-hardware.org/?probe=5f2948351d) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| AZW           | U59                         | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Gigabyte      | H97M-D3H                    | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [318b0a5ecb](https://linux-hardware.org/?probe=318b0a5ecb) | Jan 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [6a4a26884d](https://linux-hardware.org/?probe=6a4a26884d) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [8e4f1d2ed2](https://linux-hardware.org/?probe=8e4f1d2ed2) | Jan 30, 2023 |
| ASUSTek       | PRIME B550M-A               | [585c3c8f85](https://linux-hardware.org/?probe=585c3c8f85) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASRock        | N68-S UCC                   | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| ASUSTek       | GA15DH                      | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [ef43edeee5](https://linux-hardware.org/?probe=ef43edeee5) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| ASRock        | X570M Pro4                  | [e72f7f2fb1](https://linux-hardware.org/?probe=e72f7f2fb1) | Jan 29, 2023 |
| Acer          | FMP55                       | [d091fbc8d3](https://linux-hardware.org/?probe=d091fbc8d3) | Jan 29, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [d9f9d4bc89](https://linux-hardware.org/?probe=d9f9d4bc89) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| ASRock        | 970 Pro3 R2.0               | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [e619db262a](https://linux-hardware.org/?probe=e619db262a) | Jan 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [c0ea09ef3c](https://linux-hardware.org/?probe=c0ea09ef3c) | Jan 27, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | [812c00440c](https://linux-hardware.org/?probe=812c00440c) | Jan 26, 2023 |
| ASRock        | AD2700-ITX                  | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [decfe6ab97](https://linux-hardware.org/?probe=decfe6ab97) | Jan 25, 2023 |
| Dell          | 0XFWHV A00                  | [52ee3df163](https://linux-hardware.org/?probe=52ee3df163) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d1c6e3c96f](https://linux-hardware.org/?probe=d1c6e3c96f) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Dell          | 0X30MX A00                  | [c323a1a215](https://linux-hardware.org/?probe=c323a1a215) | Jan 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [2f215e1ce7](https://linux-hardware.org/?probe=2f215e1ce7) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| Dell          | 0Y56T3 A00                  | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| MSI           | H510M PRO                   | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ASRock        | J3455B-ITX                  | [b4419e8fce](https://linux-hardware.org/?probe=b4419e8fce) | Jan 22, 2023 |
| MSI           | B450-A PRO                  | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| AZW           | GTR V02                     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [5bbd614c0f](https://linux-hardware.org/?probe=5bbd614c0f) | Jan 20, 2023 |
| HP            | 0AECh D                     | [b2ea95f507](https://linux-hardware.org/?probe=b2ea95f507) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | [7f36411ac1](https://linux-hardware.org/?probe=7f36411ac1) | Jan 20, 2023 |
| Dell          | 0GY6Y8 A02                  | [33b364ed89](https://linux-hardware.org/?probe=33b364ed89) | Jan 19, 2023 |
| ASRock        | Z690 PG Riptide             | [582e3e3026](https://linux-hardware.org/?probe=582e3e3026) | Jan 19, 2023 |
| ASRock        | X300M-STX                   | [8303a9c2a0](https://linux-hardware.org/?probe=8303a9c2a0) | Jan 18, 2023 |
| Dell          | 0XFRWW A00                  | [2b96d4b6f6](https://linux-hardware.org/?probe=2b96d4b6f6) | Jan 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [011b9a41cd](https://linux-hardware.org/?probe=011b9a41cd) | Jan 18, 2023 |
| MSI           | X99A RAIDER                 | [8da5286795](https://linux-hardware.org/?probe=8da5286795) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | 0KRC95 A02                  | [01cf6039d0](https://linux-hardware.org/?probe=01cf6039d0) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| ASUSTek       | Z97-K                       | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [8753bd8277](https://linux-hardware.org/?probe=8753bd8277) | Jan 17, 2023 |
| Gigabyte      | G41MT-D3                    | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| MSI           | X99A RAIDER                 | [9f280d24f5](https://linux-hardware.org/?probe=9f280d24f5) | Jan 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [f26dbd644c](https://linux-hardware.org/?probe=f26dbd644c) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d5843b83af](https://linux-hardware.org/?probe=d5843b83af) | Jan 16, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [dd16b56d30](https://linux-hardware.org/?probe=dd16b56d30) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Dell          | 0M863N A01                  | [1dff7cb016](https://linux-hardware.org/?probe=1dff7cb016) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b68ce1375d](https://linux-hardware.org/?probe=b68ce1375d) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK               | [978682daa6](https://linux-hardware.org/?probe=978682daa6) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| AZW           | GTR V02                     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| Dell          | 0W2F8G A01                  | [999fcca032](https://linux-hardware.org/?probe=999fcca032) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| MSI           | X99A RAIDER                 | [7e67b2b3a0](https://linux-hardware.org/?probe=7e67b2b3a0) | Jan 14, 2023 |
| HP            | 8753                        | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| MSI           | X99A RAIDER                 | [3128a21a3a](https://linux-hardware.org/?probe=3128a21a3a) | Jan 13, 2023 |
| ASUSTek       | H170 PRO GAMING             | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [f9846c0e18](https://linux-hardware.org/?probe=f9846c0e18) | Jan 13, 2023 |
| HP            | 3047h                       | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| HP            | 3047h                       | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Unknown       | X79                         | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| MSI           | B550-A PRO                  | [28d13d17ba](https://linux-hardware.org/?probe=28d13d17ba) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [eec3fcf9ff](https://linux-hardware.org/?probe=eec3fcf9ff) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [760cc2eaed](https://linux-hardware.org/?probe=760cc2eaed) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [7c7c8175c0](https://linux-hardware.org/?probe=7c7c8175c0) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| AZW           | GTR V02                     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | [9eac6e2b97](https://linux-hardware.org/?probe=9eac6e2b97) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| MSI           | MEG X570 ACE                | [853f3c06ce](https://linux-hardware.org/?probe=853f3c06ce) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | [d3e35671cd](https://linux-hardware.org/?probe=d3e35671cd) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| MSI           | X99A RAIDER                 | [b8ac11cfd3](https://linux-hardware.org/?probe=b8ac11cfd3) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| MSI           | X99A RAIDER                 | [c8a281879a](https://linux-hardware.org/?probe=c8a281879a) | Jan 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| ASUSTek       | H61M-C                      | [494e552521](https://linux-hardware.org/?probe=494e552521) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | [94d61ca559](https://linux-hardware.org/?probe=94d61ca559) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e417e45252](https://linux-hardware.org/?probe=e417e45252) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e7b27ba60c](https://linux-hardware.org/?probe=e7b27ba60c) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| MSI           | X99A RAIDER                 | [01b93cba09](https://linux-hardware.org/?probe=01b93cba09) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Positivo      | POS-PIQ57BQA                | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| Gigabyte      | Z690 UD DDR4                | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Dell          | 0KRC95 A02                  | [8e30a9a43e](https://linux-hardware.org/?probe=8e30a9a43e) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| HP            | 8459                        | [18f44a4e07](https://linux-hardware.org/?probe=18f44a4e07) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| ASUSTek       | PRIME X570-P                | [f1962e0076](https://linux-hardware.org/?probe=f1962e0076) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| Dell          | 0KRC95 A02                  | [d7c57c2bae](https://linux-hardware.org/?probe=d7c57c2bae) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [4e900247e4](https://linux-hardware.org/?probe=4e900247e4) | Jan 02, 2023 |
| ASRock        | Z77 Professional            | [bf09b21dc7](https://linux-hardware.org/?probe=bf09b21dc7) | Jan 02, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| ASUSTek       | H81M-PLUS                   | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3b6d1593c8](https://linux-hardware.org/?probe=3b6d1593c8) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | [178dcba2a5](https://linux-hardware.org/?probe=178dcba2a5) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |
| Shuttle       | SH570                       | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| ASRock        | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| MSI           | X99A RAIDER                 | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [8f06578f10](https://linux-hardware.org/?probe=8f06578f10) | Dec 31, 2022 |
| Shuttle       | SH570                       | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | X79 Extreme6                | [5ea31811b4](https://linux-hardware.org/?probe=5ea31811b4) | Dec 30, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| ASRock        | B450M Pro4                  | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| ASUSTek       | Z87-PRO                     | [eafab9edba](https://linux-hardware.org/?probe=eafab9edba) | Dec 30, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bdc5158ffb](https://linux-hardware.org/?probe=bdc5158ffb) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [4cf9d40c0d](https://linux-hardware.org/?probe=4cf9d40c0d) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [7e53808767](https://linux-hardware.org/?probe=7e53808767) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| MSI           | X99A RAIDER                 | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | [b89e7eb1c9](https://linux-hardware.org/?probe=b89e7eb1c9) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | [7c6adb6279](https://linux-hardware.org/?probe=7c6adb6279) | Dec 28, 2022 |
| Dell          | 0N4YC8 A00                  | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | [59b38f9b63](https://linux-hardware.org/?probe=59b38f9b63) | Dec 28, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [7bb247e453](https://linux-hardware.org/?probe=7bb247e453) | Dec 28, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| Gigabyte      | B650I AORUS ULTRA           | [3c25f43c23](https://linux-hardware.org/?probe=3c25f43c23) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [731f916db1](https://linux-hardware.org/?probe=731f916db1) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | 3397                        | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [4c97c87b61](https://linux-hardware.org/?probe=4c97c87b61) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [46705eb79f](https://linux-hardware.org/?probe=46705eb79f) | Dec 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [e853f645cf](https://linux-hardware.org/?probe=e853f645cf) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| MSI           | Z270M MORTAR                | [70564a2846](https://linux-hardware.org/?probe=70564a2846) | Dec 24, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bf8f02ac85](https://linux-hardware.org/?probe=bf8f02ac85) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| MSI           | X99A RAIDER                 | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [926850a516](https://linux-hardware.org/?probe=926850a516) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [8428e68855](https://linux-hardware.org/?probe=8428e68855) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Dell          | 02YRK5 A02                  | [f5f6093483](https://linux-hardware.org/?probe=f5f6093483) | Dec 21, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| ASRock        | Z790 Pro RS WiFi            | [d54c198ec8](https://linux-hardware.org/?probe=d54c198ec8) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| MSI           | X99A RAIDER                 | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [60dbf09ee4](https://linux-hardware.org/?probe=60dbf09ee4) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [6a964b9d6b](https://linux-hardware.org/?probe=6a964b9d6b) | Dec 19, 2022 |
| MSI           | Boston                      | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| Gigabyte      | A520M DS3H                  | [4251c08b5d](https://linux-hardware.org/?probe=4251c08b5d) | Dec 18, 2022 |
| Dell          | 0KRC95 A02                  | [e7bb083869](https://linux-hardware.org/?probe=e7bb083869) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | [53c582a7f6](https://linux-hardware.org/?probe=53c582a7f6) | Dec 18, 2022 |
| MSI           | X99A RAIDER                 | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| Gigabyte      | J1900M-D2P                  | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [6dddb93518](https://linux-hardware.org/?probe=6dddb93518) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [54132f7285](https://linux-hardware.org/?probe=54132f7285) | Dec 17, 2022 |
| HP            | 82F2 A01                    | [859d719a2a](https://linux-hardware.org/?probe=859d719a2a) | Dec 16, 2022 |
| Gigabyte      | Z77MX-D3H                   | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-K               | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Lenovo        | 31900003 STD                | [81dea8d96e](https://linux-hardware.org/?probe=81dea8d96e) | Dec 15, 2022 |
| ASRock        | X670E Steel Legend          | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B550-A PRO B02              | [3a1ebe10f8](https://linux-hardware.org/?probe=3a1ebe10f8) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| MSI           | X99A RAIDER                 | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [572f0231a5](https://linux-hardware.org/?probe=572f0231a5) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a0d17e1d50](https://linux-hardware.org/?probe=a0d17e1d50) | Dec 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| Intel         | DQ67SW AAG12527-309         | [3b826b42e0](https://linux-hardware.org/?probe=3b826b42e0) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [fa4afa166d](https://linux-hardware.org/?probe=fa4afa166d) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [5cde0cdcc4](https://linux-hardware.org/?probe=5cde0cdcc4) | Dec 14, 2022 |
| HP            | 18E4                        | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| MSI           | X370 SLI PLUS               | [7c32d0f453](https://linux-hardware.org/?probe=7c32d0f453) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1ccd39b328](https://linux-hardware.org/?probe=1ccd39b328) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| Dell          | 0YJMC0 A01                  | [59de758672](https://linux-hardware.org/?probe=59de758672) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1800fc9efb](https://linux-hardware.org/?probe=1800fc9efb) | Dec 14, 2022 |
| Intel         | DB75EN AAG39650-400         | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [469dfe26a6](https://linux-hardware.org/?probe=469dfe26a6) | Dec 13, 2022 |
| MSI           | MEG B550 UNIFY              | [e9a996b54a](https://linux-hardware.org/?probe=e9a996b54a) | Dec 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| ASRock        | X79 Extreme6                | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| Gigabyte      | H370M DS3H-CF               | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | [6bf96cf0fc](https://linux-hardware.org/?probe=6bf96cf0fc) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | P5K Deluxe                  | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Lenovo        | ThinkStation S30 056851U    | [8c7b6cfca0](https://linux-hardware.org/?probe=8c7b6cfca0) | Dec 10, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| MSI           | H97M-G43                    | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7d6b3699e7](https://linux-hardware.org/?probe=7d6b3699e7) | Dec 10, 2022 |
| ASRock        | X670E Steel Legend          | [11df680f78](https://linux-hardware.org/?probe=11df680f78) | Dec 09, 2022 |
| Gigabyte      | G31_ICH7                    | [d433eed3f1](https://linux-hardware.org/?probe=d433eed3f1) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Gigabyte      | Z77MX-D3H                   | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [a875eabf3d](https://linux-hardware.org/?probe=a875eabf3d) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [6ab58fe686](https://linux-hardware.org/?probe=6ab58fe686) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [07e4a8072a](https://linux-hardware.org/?probe=07e4a8072a) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [172c6c1300](https://linux-hardware.org/?probe=172c6c1300) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| MSI           | H97M-G43                    | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| MSI           | X99A RAIDER                 | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [551e0142a8](https://linux-hardware.org/?probe=551e0142a8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| MSI           | B550-A PRO                  | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d655b34178](https://linux-hardware.org/?probe=d655b34178) | Dec 07, 2022 |
| Gigabyte      | X570 GAMING X               | [811b0e1a71](https://linux-hardware.org/?probe=811b0e1a71) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5be32d156a](https://linux-hardware.org/?probe=5be32d156a) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-A               | [f8e78fbf31](https://linux-hardware.org/?probe=f8e78fbf31) | Dec 06, 2022 |
| HP            | 8767 A                      | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| Acer          | FMP55                       | [78aabc71bf](https://linux-hardware.org/?probe=78aabc71bf) | Dec 05, 2022 |
| Unknown       | HX90                        | [9f3f9dec0b](https://linux-hardware.org/?probe=9f3f9dec0b) | Dec 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| HP            | 8860 A                      | [23fde1381a](https://linux-hardware.org/?probe=23fde1381a) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| MSI           | X370 SLI PLUS               | [e6941ba491](https://linux-hardware.org/?probe=e6941ba491) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | 0M017G A00                  | [d6b5487094](https://linux-hardware.org/?probe=d6b5487094) | Dec 05, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [b5c74add87](https://linux-hardware.org/?probe=b5c74add87) | Dec 04, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [db7cd6f0dc](https://linux-hardware.org/?probe=db7cd6f0dc) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cff58a3529](https://linux-hardware.org/?probe=cff58a3529) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| HP            | 158B                        | [5652b24e0d](https://linux-hardware.org/?probe=5652b24e0d) | Dec 04, 2022 |
| HP            | 158B                        | [015085e084](https://linux-hardware.org/?probe=015085e084) | Dec 04, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [0a626fffe5](https://linux-hardware.org/?probe=0a626fffe5) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| Gigabyte      | GA-970A-DS3                 | [8c06e98cf8](https://linux-hardware.org/?probe=8c06e98cf8) | Dec 03, 2022 |
| Dell          | 0N826N A02                  | [e9f0634dd6](https://linux-hardware.org/?probe=e9f0634dd6) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80bba2043d](https://linux-hardware.org/?probe=80bba2043d) | Dec 03, 2022 |
| Unknown       | HX90                        | [40847bd89b](https://linux-hardware.org/?probe=40847bd89b) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [07a15db1a6](https://linux-hardware.org/?probe=07a15db1a6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [9cd70143b5](https://linux-hardware.org/?probe=9cd70143b5) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | PRIME X370-PRO              | [aa87dfdc13](https://linux-hardware.org/?probe=aa87dfdc13) | Dec 01, 2022 |
| MSI           | X99A RAIDER                 | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Gigabyte      | X570 GAMING X               | [7ea2de1a3b](https://linux-hardware.org/?probe=7ea2de1a3b) | Nov 30, 2022 |
| Unknown       | X99H                        | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| MSI           | X570-A PRO                  | [92ddd925db](https://linux-hardware.org/?probe=92ddd925db) | Nov 28, 2022 |
| ASUSTek       | GA15DH                      | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [207d763813](https://linux-hardware.org/?probe=207d763813) | Nov 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [8fa53292bf](https://linux-hardware.org/?probe=8fa53292bf) | Nov 27, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [81a61c4765](https://linux-hardware.org/?probe=81a61c4765) | Nov 27, 2022 |
| Foxconn       | 2ABF                        | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Gigabyte      | B550 GAMING X               | [b9264b2557](https://linux-hardware.org/?probe=b9264b2557) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [33f5823764](https://linux-hardware.org/?probe=33f5823764) | Nov 25, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| Biostar       | H310MHC2                    | [49e09047c4](https://linux-hardware.org/?probe=49e09047c4) | Nov 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6f867d822a](https://linux-hardware.org/?probe=6f867d822a) | Nov 25, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bf1722d4d6](https://linux-hardware.org/?probe=bf1722d4d6) | Nov 25, 2022 |
| MSI           | X99A RAIDER                 | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| MSI           | H81M-E33                    | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [7f0ba24aad](https://linux-hardware.org/?probe=7f0ba24aad) | Nov 24, 2022 |
| ASUSTek       | GA15DH                      | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee5b760222](https://linux-hardware.org/?probe=ee5b760222) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [8de6a24029](https://linux-hardware.org/?probe=8de6a24029) | Nov 24, 2022 |
| Dell          | 0J3C2F A02                  | [0cfd78c6bb](https://linux-hardware.org/?probe=0cfd78c6bb) | Nov 23, 2022 |
| ASRock        | Z370 Pro4                   | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b0e5869f2d](https://linux-hardware.org/?probe=b0e5869f2d) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [e89ecf8da4](https://linux-hardware.org/?probe=e89ecf8da4) | Nov 23, 2022 |
| MSI           | 2A9C                        | [ee8683a595](https://linux-hardware.org/?probe=ee8683a595) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | 2A9C                        | [77dd7e3fbc](https://linux-hardware.org/?probe=77dd7e3fbc) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| ASUSTek       | Maximus IX HERO             | [587aa317bd](https://linux-hardware.org/?probe=587aa317bd) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [990ff088e8](https://linux-hardware.org/?probe=990ff088e8) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE V2               | [d126214b62](https://linux-hardware.org/?probe=d126214b62) | Nov 22, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0GY6Y8 A02                  | [8789b14e39](https://linux-hardware.org/?probe=8789b14e39) | Nov 21, 2022 |
| HP            | 3647h                       | [8f77a73e9b](https://linux-hardware.org/?probe=8f77a73e9b) | Nov 21, 2022 |
| Gigabyte      | B75M-D3H                    | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [8478dece38](https://linux-hardware.org/?probe=8478dece38) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b41f6ec236](https://linux-hardware.org/?probe=b41f6ec236) | Nov 21, 2022 |
| ASUSTek       | PRIME Z270-A                | [540d321764](https://linux-hardware.org/?probe=540d321764) | Nov 21, 2022 |
| HP            | 18E7                        | [0b963b44fb](https://linux-hardware.org/?probe=0b963b44fb) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| Dell          | 0HY9JP A02                  | [fa0e9792f0](https://linux-hardware.org/?probe=fa0e9792f0) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d3412020ec](https://linux-hardware.org/?probe=d3412020ec) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASUSTek       | PRIME Z370-A                | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d304f26226](https://linux-hardware.org/?probe=d304f26226) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [1755321c80](https://linux-hardware.org/?probe=1755321c80) | Nov 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [050e6cfd68](https://linux-hardware.org/?probe=050e6cfd68) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Acer          | FMP55                       | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASRock        | X300-ITX                    | [54f7198f58](https://linux-hardware.org/?probe=54f7198f58) | Nov 18, 2022 |
| Gigabyte      | H61M-USB3V                  | [e034e5bbb2](https://linux-hardware.org/?probe=e034e5bbb2) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [a8847bb3ad](https://linux-hardware.org/?probe=a8847bb3ad) | Nov 18, 2022 |
| Dell          | 0X30MX A00                  | [c3657c7f97](https://linux-hardware.org/?probe=c3657c7f97) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| MSI           | X99A RAIDER                 | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4c86f7c670](https://linux-hardware.org/?probe=4c86f7c670) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9f45de6ee3](https://linux-hardware.org/?probe=9f45de6ee3) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2eb90688b5](https://linux-hardware.org/?probe=2eb90688b5) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| Intel         | DX79SR AAG57199-200         | [b12b9ec8d5](https://linux-hardware.org/?probe=b12b9ec8d5) | Nov 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [9cd3d86efc](https://linux-hardware.org/?probe=9cd3d86efc) | Nov 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| Dell          | 06X1TJ A00                  | [4a19565db2](https://linux-hardware.org/?probe=4a19565db2) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [256503ef7e](https://linux-hardware.org/?probe=256503ef7e) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | [c73b422075](https://linux-hardware.org/?probe=c73b422075) | Nov 12, 2022 |
| MSI           | X99A RAIDER                 | [dffde21ad4](https://linux-hardware.org/?probe=dffde21ad4) | Nov 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5006a2d188](https://linux-hardware.org/?probe=5006a2d188) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| MSI           | 2A9C                        | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [578b9c0e61](https://linux-hardware.org/?probe=578b9c0e61) | Nov 11, 2022 |
| MSI           | 2A9C                        | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a311d2c018](https://linux-hardware.org/?probe=a311d2c018) | Nov 11, 2022 |
| MSI           | X99A RAIDER                 | [b7d21d229b](https://linux-hardware.org/?probe=b7d21d229b) | Nov 11, 2022 |
| Dell          | 0DR845                      | [c4d2b18dd8](https://linux-hardware.org/?probe=c4d2b18dd8) | Nov 10, 2022 |
| MSI           | Z390-A PRO                  | [e851ddd11a](https://linux-hardware.org/?probe=e851ddd11a) | Nov 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [009f3d82e9](https://linux-hardware.org/?probe=009f3d82e9) | Nov 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [faf531627e](https://linux-hardware.org/?probe=faf531627e) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| ASRock        | H310M-STX                   | [cb421b22a5](https://linux-hardware.org/?probe=cb421b22a5) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| ASRock        | Z77 Pro4-M                  | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0b65e26932](https://linux-hardware.org/?probe=0b65e26932) | Nov 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Dell          | 09WH54 A00                  | [c7723a2b2f](https://linux-hardware.org/?probe=c7723a2b2f) | Nov 07, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [6987230f73](https://linux-hardware.org/?probe=6987230f73) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| ASUSTek       | PRIME Z370-A                | [d87a3e023a](https://linux-hardware.org/?probe=d87a3e023a) | Nov 07, 2022 |
| Gigabyte      | B450M GAMING                | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | A320M-H-CF                  | [fa33ccff27](https://linux-hardware.org/?probe=fa33ccff27) | Nov 05, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| Dell          | 096JG8 A01                  | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| ASUSTek       | PRO H410T                   | [66a809ab24](https://linux-hardware.org/?probe=66a809ab24) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [02104ae91b](https://linux-hardware.org/?probe=02104ae91b) | Nov 05, 2022 |
| ASRock        | X570 Taichi                 | [d9902c03cb](https://linux-hardware.org/?probe=d9902c03cb) | Nov 05, 2022 |
| MSI           | X99A RAIDER                 | [95fb6a845e](https://linux-hardware.org/?probe=95fb6a845e) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [36e78b1c17](https://linux-hardware.org/?probe=36e78b1c17) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [56db615f30](https://linux-hardware.org/?probe=56db615f30) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [108df7bc6d](https://linux-hardware.org/?probe=108df7bc6d) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a2c8fe2afa](https://linux-hardware.org/?probe=a2c8fe2afa) | Nov 05, 2022 |
| MSI           | Z390-A PRO                  | [5cfd4967b0](https://linux-hardware.org/?probe=5cfd4967b0) | Nov 05, 2022 |
| ASRock        | X370 Taichi                 | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | 339A                        | [77ddeeda51](https://linux-hardware.org/?probe=77ddeeda51) | Nov 04, 2022 |
| HP            | 339A                        | [8ebb8b6522](https://linux-hardware.org/?probe=8ebb8b6522) | Nov 04, 2022 |
| Gigabyte      | H97-HD3                     | [bb8dbe6d52](https://linux-hardware.org/?probe=bb8dbe6d52) | Nov 04, 2022 |
| HP            | 8459                        | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| HP            | 2B05                        | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| MSI           | X99A RAIDER                 | [b3eefc89d6](https://linux-hardware.org/?probe=b3eefc89d6) | Nov 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [653a03dee6](https://linux-hardware.org/?probe=653a03dee6) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| ASUSTek       | PRIME Z270-P                | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9bdccc90c4](https://linux-hardware.org/?probe=9bdccc90c4) | Nov 03, 2022 |
| MSI           | X99A RAIDER                 | [0036848bf2](https://linux-hardware.org/?probe=0036848bf2) | Nov 03, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [86bf890d23](https://linux-hardware.org/?probe=86bf890d23) | Nov 02, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9b093574b9](https://linux-hardware.org/?probe=9b093574b9) | Nov 02, 2022 |
| Gigabyte      | B550 UD AC                  | [c5a5219cf3](https://linux-hardware.org/?probe=c5a5219cf3) | Nov 01, 2022 |
| ASUSTek       | B150 PRO GAMING             | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| MSI           | H81M-E33                    | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| HP            | 339A                        | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| MSI           | PRO B660M-A DDR4            | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| MSI           | X99A RAIDER                 | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4ac9bf1711](https://linux-hardware.org/?probe=4ac9bf1711) | Oct 31, 2022 |
| MSI           | B250M GAMING PRO            | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| MSI           | X99A RAIDER                 | [782207dfcf](https://linux-hardware.org/?probe=782207dfcf) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [75b050a9f0](https://linux-hardware.org/?probe=75b050a9f0) | Oct 29, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [ce9a718851](https://linux-hardware.org/?probe=ce9a718851) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| ASRock        | X99 Extreme4                | [72102d6890](https://linux-hardware.org/?probe=72102d6890) | Oct 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [38135da604](https://linux-hardware.org/?probe=38135da604) | Oct 28, 2022 |
| MSI           | H81M-E33                    | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | B450M MORTAR                | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| Gigabyte      | H97N-WIFI                   | [aa2345213b](https://linux-hardware.org/?probe=aa2345213b) | Oct 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd9367f2b7](https://linux-hardware.org/?probe=bd9367f2b7) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [6c7c7fa216](https://linux-hardware.org/?probe=6c7c7fa216) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [317d318d85](https://linux-hardware.org/?probe=317d318d85) | Oct 26, 2022 |
| HP            | ProLiant ML350 G6           | [d080f0956b](https://linux-hardware.org/?probe=d080f0956b) | Oct 26, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | [10e0a497e9](https://linux-hardware.org/?probe=10e0a497e9) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Acer          | Veriton M2631 V:1.0         | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | [601e080563](https://linux-hardware.org/?probe=601e080563) | Oct 25, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [3f6368ca5a](https://linux-hardware.org/?probe=3f6368ca5a) | Oct 24, 2022 |
| HP            | 3048h                       | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [2a57a65990](https://linux-hardware.org/?probe=2a57a65990) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| HP            | 2B05                        | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| ASRock        | P45TS                       | [484f63b830](https://linux-hardware.org/?probe=484f63b830) | Oct 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b9e4b934ee](https://linux-hardware.org/?probe=b9e4b934ee) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| ASUSTek       | Z170-A                      | [22a96186fa](https://linux-hardware.org/?probe=22a96186fa) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b42893c91e](https://linux-hardware.org/?probe=b42893c91e) | Oct 22, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [b633b478aa](https://linux-hardware.org/?probe=b633b478aa) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b7ad660d88](https://linux-hardware.org/?probe=b7ad660d88) | Oct 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| Dell          | 0PP150 A00                  | [0e07990bda](https://linux-hardware.org/?probe=0e07990bda) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [77b57dbe12](https://linux-hardware.org/?probe=77b57dbe12) | Oct 21, 2022 |
| Unknown       | X79                         | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| HP            | 8459                        | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | [f03f1bb041](https://linux-hardware.org/?probe=f03f1bb041) | Oct 20, 2022 |
| HP            | 8433 11                     | [7e28f54181](https://linux-hardware.org/?probe=7e28f54181) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| NZXT          | N7 B550                     | [f699b7e1d2](https://linux-hardware.org/?probe=f699b7e1d2) | Oct 20, 2022 |
| HP            | 8459                        | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [13f4800fa8](https://linux-hardware.org/?probe=13f4800fa8) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [76c0902958](https://linux-hardware.org/?probe=76c0902958) | Oct 19, 2022 |
| Gigabyte      | P67A-UD3                    | [96b72bfa8a](https://linux-hardware.org/?probe=96b72bfa8a) | Oct 19, 2022 |
| Shuttle       | FH67H                       | [6679449225](https://linux-hardware.org/?probe=6679449225) | Oct 19, 2022 |
| MSI           | Z97 GAMING 5                | [980d0d7bb2](https://linux-hardware.org/?probe=980d0d7bb2) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [da8a11aac5](https://linux-hardware.org/?probe=da8a11aac5) | Oct 19, 2022 |
| ASUSTek       | PRIME B550M-K               | [41d2e6298d](https://linux-hardware.org/?probe=41d2e6298d) | Oct 19, 2022 |
| ASUSTek       | P5B-Deluxe                  | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [495c7fdc3d](https://linux-hardware.org/?probe=495c7fdc3d) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P FX                | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d53b4edda1](https://linux-hardware.org/?probe=d53b4edda1) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e618e79bd5](https://linux-hardware.org/?probe=e618e79bd5) | Oct 17, 2022 |
| Dell          | 0WR7PY A02                  | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-A                | [50fe9fcad5](https://linux-hardware.org/?probe=50fe9fcad5) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [77f04d4628](https://linux-hardware.org/?probe=77f04d4628) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6de814388c](https://linux-hardware.org/?probe=6de814388c) | Oct 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [1200f4104f](https://linux-hardware.org/?probe=1200f4104f) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| MSI           | FM2-A55M-E33                | [1fe306ae1e](https://linux-hardware.org/?probe=1fe306ae1e) | Oct 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [a6083f4dfe](https://linux-hardware.org/?probe=a6083f4dfe) | Oct 13, 2022 |
| ASUSTek       | Z97-K                       | [47394cb2b5](https://linux-hardware.org/?probe=47394cb2b5) | Oct 13, 2022 |
| ASUSTek       | P8P67 LE                    | [0c7961c445](https://linux-hardware.org/?probe=0c7961c445) | Oct 13, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2412a53d05](https://linux-hardware.org/?probe=2412a53d05) | Oct 12, 2022 |
| BESSTAR Te... | UM350                       | [f58608a000](https://linux-hardware.org/?probe=f58608a000) | Oct 11, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [60037612c1](https://linux-hardware.org/?probe=60037612c1) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| ASRock        | X570 PG Velocita            | [ec3a819326](https://linux-hardware.org/?probe=ec3a819326) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | B450 GAMING PLUS            | [6f95e1591a](https://linux-hardware.org/?probe=6f95e1591a) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| MSI           | A320M-A PRO MAX             | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| MSI           | B550M PRO-VDH               | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [4aa8b37ac5](https://linux-hardware.org/?probe=4aa8b37ac5) | Oct 09, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [30ff2d0e8f](https://linux-hardware.org/?probe=30ff2d0e8f) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| ASUSTek       | PRIME Z270-A                | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| Dell          | 0RY007                      | [745f69ec3d](https://linux-hardware.org/?probe=745f69ec3d) | Oct 08, 2022 |
| HP            | 3647h                       | [ddffa21a6e](https://linux-hardware.org/?probe=ddffa21a6e) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8895a815c6](https://linux-hardware.org/?probe=8895a815c6) | Oct 07, 2022 |
| Unknown       | Intel X79                   | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| HP            | 0AECh D                     | [8fd13e9017](https://linux-hardware.org/?probe=8fd13e9017) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6a5822719f](https://linux-hardware.org/?probe=6a5822719f) | Oct 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [20b6b5f918](https://linux-hardware.org/?probe=20b6b5f918) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [7f2b63950d](https://linux-hardware.org/?probe=7f2b63950d) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [51c401fd4e](https://linux-hardware.org/?probe=51c401fd4e) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [07d4cf95ec](https://linux-hardware.org/?probe=07d4cf95ec) | Oct 04, 2022 |
| Gigabyte      | B85M-D2V                    | [4e6047ec5b](https://linux-hardware.org/?probe=4e6047ec5b) | Oct 03, 2022 |
| Gigabyte      | B85M-D3V-A                  | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [48e867fba8](https://linux-hardware.org/?probe=48e867fba8) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| MSI           | B350 TOMAHAWK               | [253e143d94](https://linux-hardware.org/?probe=253e143d94) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6121fee541](https://linux-hardware.org/?probe=6121fee541) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| Gigabyte      | B550M DS3H                  | [2f8557640c](https://linux-hardware.org/?probe=2f8557640c) | Oct 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a0d36f3810](https://linux-hardware.org/?probe=a0d36f3810) | Oct 02, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| Gigabyte      | B75M-D3H                    | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| ASRock        | H270M-ITX/ac                | [c6ae2f8a45](https://linux-hardware.org/?probe=c6ae2f8a45) | Sep 29, 2022 |
| ASUSTek       | PRIME Z270-A                | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Dell          | 0YGYJY A01                  | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| Intel         | DP35DP AAD81073-208         | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| Acer          | Aspire X1900                | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| ASRock        | Z170M Extreme4              | [bd1e98639b](https://linux-hardware.org/?probe=bd1e98639b) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| ASUSTek       | PRIME B365M-A               | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31f1acf273](https://linux-hardware.org/?probe=31f1acf273) | Sep 23, 2022 |
| ASUSTek       | PRIME B250M-C               | [2e45736b42](https://linux-hardware.org/?probe=2e45736b42) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| Gigabyte      | Z270P-D3-CF                 | [79509e063b](https://linux-hardware.org/?probe=79509e063b) | Sep 23, 2022 |
| MSI           | FM2-A55M-E33                | [4867faffbf](https://linux-hardware.org/?probe=4867faffbf) | Sep 23, 2022 |
| Foxconn       | H61M-S/H61M                 | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| MSI           | H310M PRO-VH                | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Fedora 36 | 664      | 17.45%  |
| Fedora 33 | 565      | 14.85%  |
| Fedora 35 | 533      | 14.01%  |
| Fedora 34 | 518      | 13.61%  |
| Fedora 32 | 518      | 13.61%  |
| Fedora 37 | 421      | 11.06%  |
| Fedora 31 | 343      | 9.01%   |
| Fedora 30 | 132      | 3.47%   |
| Fedora 29 | 75       | 1.97%   |
| Fedora 28 | 14       | 0.37%   |
| Fedora 27 | 9        | 0.24%   |
| Fedora 38 | 5        | 0.13%   |
| Fedora 25 | 2        | 0.05%   |
| Fedora 24 | 2        | 0.05%   |
| Fedora 4  | 1        | 0.03%   |
| Fedora 21 | 1        | 0.03%   |
| Fedora 17 | 1        | 0.03%   |
| Fedora 14 | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Fedora | 3291     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.9.16-200.fc33.x86_64  | 58       | 1.33%   |
| 5.16.18-200.fc35.x86_64 | 57       | 1.31%   |
| 5.17.5-300.fc36.x86_64  | 47       | 1.08%   |
| 6.0.15-300.fc37.x86_64  | 45       | 1.03%   |
| 6.0.12-300.fc37.x86_64  | 44       | 1.01%   |
| 5.18.13-200.fc36.x86_64 | 42       | 0.96%   |
| 5.19.16-200.fc36.x86_64 | 39       | 0.89%   |
| 5.13.12-200.fc34.x86_64 | 39       | 0.89%   |
| 5.14.10-300.fc35.x86_64 | 36       | 0.82%   |
| 6.0.5-200.fc36.x86_64   | 35       | 0.8%    |
| 5.11.12-300.fc34.x86_64 | 35       | 0.8%    |
| 5.8.4-200.fc32.x86_64   | 33       | 0.76%   |
| 5.8.15-301.fc33.x86_64  | 33       | 0.76%   |
| 5.18.16-200.fc36.x86_64 | 32       | 0.73%   |
| 6.0.11-300.fc37.x86_64  | 31       | 0.71%   |
| 5.19.9-200.fc36.x86_64  | 31       | 0.71%   |
| 5.18.11-200.fc36.x86_64 | 31       | 0.71%   |
| 5.6.19-300.fc32.x86_64  | 30       | 0.69%   |
| 5.18.5-200.fc36.x86_64  | 30       | 0.69%   |
| 5.12.13-300.fc34.x86_64 | 30       | 0.69%   |
| 5.8.18-300.fc33.x86_64  | 29       | 0.66%   |
| 5.15.6-200.fc35.x86_64  | 29       | 0.66%   |
| 5.8.16-300.fc33.x86_64  | 28       | 0.64%   |
| 6.0.8-300.fc37.x86_64   | 27       | 0.62%   |
| 6.0.7-301.fc37.x86_64   | 27       | 0.62%   |
| 6.0.9-300.fc37.x86_64   | 26       | 0.6%    |
| 5.9.11-200.fc33.x86_64  | 26       | 0.6%    |
| 5.3.16-300.fc31.x86_64  | 26       | 0.6%    |
| 5.7.10-201.fc32.x86_64  | 25       | 0.57%   |
| 5.16.16-200.fc35.x86_64 | 25       | 0.57%   |
| 5.11.11-200.fc33.x86_64 | 25       | 0.57%   |
| 5.9.8-200.fc33.x86_64   | 24       | 0.55%   |
| 5.11.16-300.fc34.x86_64 | 24       | 0.55%   |
| 5.19.6-200.fc36.x86_64  | 23       | 0.53%   |
| 5.17.6-300.fc36.x86_64  | 23       | 0.53%   |
| 5.14.9-200.fc34.x86_64  | 23       | 0.53%   |
| 5.12.8-300.fc34.x86_64  | 23       | 0.53%   |
| 6.1.8-200.fc37.x86_64   | 22       | 0.5%    |
| 5.8.11-200.fc32.x86_64  | 22       | 0.5%    |
| 5.7.15-200.fc32.x86_64  | 22       | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 67       | 1.54%   |
| 5.16.18 | 65       | 1.49%   |
| 5.17.5  | 63       | 1.44%   |
| 5.19.16 | 58       | 1.33%   |
| 5.8.15  | 53       | 1.21%   |
| 6.0.15  | 50       | 1.15%   |
| 6.0.12  | 50       | 1.15%   |
| 5.8.18  | 47       | 1.08%   |
| 5.18.13 | 43       | 0.99%   |
| 6.0.7   | 40       | 0.92%   |
| 5.8.16  | 40       | 0.92%   |
| 5.13.12 | 40       | 0.92%   |
| 5.19.9  | 39       | 0.89%   |
| 6.0.8   | 38       | 0.87%   |
| 6.0.5   | 38       | 0.87%   |
| 5.14.10 | 38       | 0.87%   |
| 5.11.12 | 37       | 0.85%   |
| 5.11.11 | 37       | 0.85%   |
| 6.0.9   | 36       | 0.83%   |
| 6.0.11  | 34       | 0.78%   |
| 5.18.5  | 34       | 0.78%   |
| 5.8.4   | 33       | 0.76%   |
| 5.18.16 | 33       | 0.76%   |
| 5.14.18 | 33       | 0.76%   |
| 5.18.11 | 32       | 0.73%   |
| 5.12.13 | 32       | 0.73%   |
| 5.6.19  | 31       | 0.71%   |
| 6.0.10  | 30       | 0.69%   |
| 5.12.8  | 30       | 0.69%   |
| 5.15.6  | 29       | 0.66%   |
| 5.9.11  | 28       | 0.64%   |
| 5.19.6  | 28       | 0.64%   |
| 5.17.6  | 28       | 0.64%   |
| 5.14.9  | 28       | 0.64%   |
| 5.6.6   | 27       | 0.62%   |
| 5.17.11 | 27       | 0.62%   |
| 5.11.16 | 27       | 0.62%   |
| 5.9.8   | 26       | 0.6%    |
| 5.7.15  | 26       | 0.6%    |
| 5.3.16  | 26       | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 340      | 8.22%   |
| 5.8     | 307      | 7.42%   |
| 5.11    | 257      | 6.22%   |
| 5.19    | 255      | 6.17%   |
| 5.18    | 250      | 6.05%   |
| 5.17    | 245      | 5.93%   |
| 5.16    | 223      | 5.39%   |
| 5.9     | 209      | 5.05%   |
| 5.10    | 206      | 4.98%   |
| 5.14    | 203      | 4.91%   |
| 5.6     | 195      | 4.72%   |
| 5.13    | 191      | 4.62%   |
| 5.15    | 178      | 4.3%    |
| 5.12    | 176      | 4.26%   |
| 5.7     | 171      | 4.14%   |
| 6.1     | 148      | 3.58%   |
| 5.4     | 135      | 3.26%   |
| 5.5     | 121      | 2.93%   |
| 5.3     | 115      | 2.78%   |
| 5.2     | 55       | 1.33%   |
| 5.0     | 48       | 1.16%   |
| 5.1     | 25       | 0.6%    |
| 4.19    | 22       | 0.53%   |
| 4.18    | 19       | 0.46%   |
| 4.20    | 18       | 0.44%   |
| 4.16    | 5        | 0.12%   |
| 6.2     | 3        | 0.07%   |
| 4.15    | 3        | 0.07%   |
| 4.17    | 2        | 0.05%   |
| 4.13    | 2        | 0.05%   |
| 4.11    | 2        | 0.05%   |
| 4.14    | 1        | 0.02%   |
| 4.1     | 1        | 0.02%   |
| 3.9     | 1        | 0.02%   |
| 3.17    | 1        | 0.02%   |
| 2.6.35  | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 3288     | 99.88%  |
| i686    | 3        | 0.09%   |
| Unknown | 1        | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 2249     | 66.26%  |
| KDE5                         | 428      | 12.61%  |
| Unknown                      | 253      | 7.45%   |
| KDE                          | 115      | 3.39%   |
| XFCE                         | 85       | 2.5%    |
| X-Cinnamon                   | 66       | 1.94%   |
| Cinnamon                     | 58       | 1.71%   |
| MATE                         | 56       | 1.65%   |
| GNOME Classic                | 25       | 0.74%   |
| LXQt                         | 10       | 0.29%   |
| LXDE                         | 10       | 0.29%   |
| Deepin                       | 10       | 0.29%   |
| i3                           | 8        | 0.24%   |
| KDE4                         | 6        | 0.18%   |
| awesome                      | 3        | 0.09%   |
| openbox                      | 2        | 0.06%   |
| DWM                          | 2        | 0.06%   |
| sway                         | 1        | 0.03%   |
| qtile                        | 1        | 0.03%   |
| Pantheon                     | 1        | 0.03%   |
| NsCDE                        | 1        | 0.03%   |
| GNUstep                      | 1        | 0.03%   |
| GNOME Flashback              | 1        | 0.03%   |
| bspwm                        | 1        | 0.03%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 1711     | 49.42%  |
| X11     | 1498     | 43.27%  |
| Unknown | 132      | 3.81%   |
| Tty     | 116      | 3.35%   |
| Web     | 5        | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1876     | 55.4%   |
| GDM     | 1002     | 29.59%  |
| SDDM    | 266      | 7.86%   |
| LightDM | 152      | 4.49%   |
| TDM     | 73       | 2.16%   |
| XDM     | 7        | 0.21%   |
| KDM     | 7        | 0.21%   |
| LXDM    | 2        | 0.06%   |
| SLiM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1557     | 46.37%  |
| Unknown | 245      | 7.3%    |
| en_GB   | 241      | 7.18%   |
| pt_BR   | 164      | 4.88%   |
| ru_RU   | 158      | 4.71%   |
| de_DE   | 146      | 4.35%   |
| fr_FR   | 109      | 3.25%   |
| en_AU   | 97       | 2.89%   |
| en_CA   | 94       | 2.8%    |
| it_IT   | 70       | 2.08%   |
| pl_PL   | 54       | 1.61%   |
| es_ES   | 46       | 1.37%   |
| cs_CZ   | 26       | 0.77%   |
| en_IN   | 22       | 0.66%   |
| en_NZ   | 19       | 0.57%   |
| es_MX   | 18       | 0.54%   |
| nl_BE   | 13       | 0.39%   |
| ja_JP   | 13       | 0.39%   |
| es_AR   | 13       | 0.39%   |
| fi_FI   | 12       | 0.36%   |
| en_IE   | 12       | 0.36%   |
| es_CO   | 11       | 0.33%   |
| uk_UA   | 10       | 0.3%    |
| sv_SE   | 10       | 0.3%    |
| nl_NL   | 10       | 0.3%    |
| C       | 10       | 0.3%    |
| tr_TR   | 9        | 0.27%   |
| de_AT   | 9        | 0.27%   |
| zh_CN   | 8        | 0.24%   |
| ru_UA   | 8        | 0.24%   |
| hu_HU   | 8        | 0.24%   |
| fr_CH   | 8        | 0.24%   |
| sk_SK   | 6        | 0.18%   |
| pt_PT   | 6        | 0.18%   |
| ko_KR   | 6        | 0.18%   |
| es_CL   | 6        | 0.18%   |
| en_DK   | 6        | 0.18%   |
| nb_NO   | 5        | 0.15%   |
| el_GR   | 5        | 0.15%   |
| fr_CA   | 4        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 2098     | 62.68%  |
| BIOS | 1249     | 37.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 1719     | 50.83%  |
| Ext4                | 1349     | 39.89%  |
| Xfs                 | 167      | 4.94%   |
| Unknown             | 132      | 3.9%    |
| Overlay             | 5        | 0.15%   |
| Ext3                | 4        | 0.12%   |
| Zfs                 | 3        | 0.09%   |
| F2fs                | 2        | 0.06%   |
| Fuse.fuse-overlayfs | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1836     | 54.14%  |
| GPT     | 1203     | 35.48%  |
| MBR     | 352      | 10.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2850     | 84.44%  |
| Yes       | 525      | 15.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2644     | 78.88%  |
| Yes       | 708      | 21.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 977      | 29.69%  |
| Gigabyte Technology | 657      | 19.96%  |
| MSI                 | 483      | 14.68%  |
| ASRock              | 347      | 10.54%  |
| Dell                | 225      | 6.84%   |
| Hewlett-Packard     | 173      | 5.26%   |
| Lenovo              | 92       | 2.8%    |
| Intel               | 53       | 1.61%   |
| Unknown             | 39       | 1.19%   |
| Acer                | 34       | 1.03%   |
| Pegatron            | 17       | 0.52%   |
| Biostar             | 17       | 0.52%   |
| ECS                 | 15       | 0.46%   |
| BESSTAR Tech        | 14       | 0.43%   |
| Fujitsu             | 12       | 0.36%   |
| Supermicro          | 11       | 0.33%   |
| Foxconn             | 11       | 0.33%   |
| Huanan              | 10       | 0.3%    |
| Shuttle             | 8        | 0.24%   |
| Positivo            | 7        | 0.21%   |
| Apple               | 7        | 0.21%   |
| Alienware           | 7        | 0.21%   |
| PCWare              | 4        | 0.12%   |
| Medion              | 4        | 0.12%   |
| EVGA                | 4        | 0.12%   |
| System76            | 3        | 0.09%   |
| Packard Bell        | 3        | 0.09%   |
| MACHINIST           | 3        | 0.09%   |
| eMachines           | 3        | 0.09%   |
| AZW                 | 3        | 0.09%   |
| ABIT                | 3        | 0.09%   |
| ZOTAC               | 2        | 0.06%   |
| XFX                 | 2        | 0.06%   |
| OEM                 | 2        | 0.06%   |
| JINGSHA             | 2        | 0.06%   |
| Itautec             | 2        | 0.06%   |
| Google              | 2        | 0.06%   |
| Gateway             | 2        | 0.06%   |
| ASRockRack          | 2        | 0.06%   |
| AMI                 | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 101      | 3.07%   |
| Unknown                        | 42       | 1.28%   |
| MSI MS-7C37                    | 36       | 1.09%   |
| ASUS TUF Gaming X570-PLUS      | 25       | 0.76%   |
| Gigabyte B450M DS3H            | 23       | 0.7%    |
| MSI MS-7C02                    | 21       | 0.64%   |
| MSI MS-7A38                    | 21       | 0.64%   |
| MSI MS-7B86                    | 17       | 0.52%   |
| Dell OptiPlex 7010             | 17       | 0.52%   |
| ASUS ROG STRIX B550-F GAMING   | 16       | 0.49%   |
| MSI MS-7C91                    | 15       | 0.46%   |
| MSI MS-7C56                    | 15       | 0.46%   |
| ASUS PRIME X370-PRO            | 15       | 0.46%   |
| ASUS ROG STRIX B450-F GAMING   | 14       | 0.43%   |
| MSI MS-7C84                    | 13       | 0.4%    |
| MSI MS-7B79                    | 13       | 0.4%    |
| Dell OptiPlex 9020             | 13       | 0.4%    |
| ASUS ROG STRIX X570-F GAMING   | 13       | 0.4%    |
| Gigabyte B450 AORUS ELITE      | 12       | 0.36%   |
| Gigabyte A320M-S2H             | 12       | 0.36%   |
| ASUS TUF Gaming B550M-PLUS     | 12       | 0.36%   |
| ASUS ROG STRIX X570-E GAMING   | 12       | 0.36%   |
| ASUS ROG STRIX B550-I GAMING   | 12       | 0.36%   |
| ASUS PRIME X470-PRO            | 12       | 0.36%   |
| ASRock B450M Pro4              | 12       | 0.36%   |
| Gigabyte X570 I AORUS PRO WIFI | 11       | 0.33%   |
| Gigabyte B450 AORUS M          | 11       | 0.33%   |
| Gigabyte 970A-DS3P             | 11       | 0.33%   |
| ASUS ROG CROSSHAIR VII HERO    | 11       | 0.33%   |
| MSI MS-7B89                    | 10       | 0.3%    |
| MSI MS-7A34                    | 10       | 0.3%    |
| Gigabyte X570 AORUS MASTER     | 10       | 0.3%    |
| Gigabyte X570 AORUS ELITE      | 10       | 0.3%    |
| ASUS Z170-A                    | 10       | 0.3%    |
| ASUS TUF Gaming B550-PLUS      | 10       | 0.3%    |
| ASUS PRIME B350-PLUS           | 10       | 0.3%    |
| ASUS PRIME A320M-K             | 10       | 0.3%    |
| Dell OptiPlex 3020             | 9        | 0.27%   |
| ASRock B450M Steel Legend      | 9        | 0.27%   |
| ASRock AB350 Pro4              | 9        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 199      | 6.05%   |
| ASUS PRIME         | 193      | 5.86%   |
| Dell OptiPlex      | 114      | 3.46%   |
| ASUS TUF           | 106      | 3.22%   |
| ASUS All           | 101      | 3.07%   |
| Gigabyte X570      | 61       | 1.85%   |
| Lenovo ThinkCentre | 52       | 1.58%   |
| Dell Precision     | 43       | 1.31%   |
| HP Compaq          | 42       | 1.28%   |
| Gigabyte B450      | 42       | 1.28%   |
| Unknown            | 42       | 1.28%   |
| Gigabyte B450M     | 37       | 1.12%   |
| MSI MS-7C37        | 36       | 1.09%   |
| HP EliteDesk       | 31       | 0.94%   |
| Dell XPS           | 25       | 0.76%   |
| Dell Inspiron      | 25       | 0.76%   |
| ASRock B450M       | 25       | 0.76%   |
| Acer Aspire        | 24       | 0.73%   |
| ASRock X570        | 23       | 0.7%    |
| Gigabyte B550      | 22       | 0.67%   |
| MSI MS-7C02        | 21       | 0.64%   |
| MSI MS-7A38        | 21       | 0.64%   |
| HP ProDesk         | 19       | 0.58%   |
| ASRock B450        | 18       | 0.55%   |
| MSI MS-7B86        | 17       | 0.52%   |
| ASUS P8Z77-V       | 16       | 0.49%   |
| MSI MS-7C91        | 15       | 0.46%   |
| MSI MS-7C56        | 15       | 0.46%   |
| ASUS M5A78L-M      | 15       | 0.46%   |
| Gigabyte Z390      | 14       | 0.43%   |
| Gigabyte B550M     | 14       | 0.43%   |
| Gigabyte A320M-S2H | 14       | 0.43%   |
| ASUS SABERTOOTH    | 14       | 0.43%   |
| ASUS M5A97         | 14       | 0.43%   |
| MSI MS-7C84        | 13       | 0.4%    |
| MSI MS-7B79        | 13       | 0.4%    |
| ASUS ProArt        | 13       | 0.4%    |
| ASUS P8Z68-V       | 13       | 0.4%    |
| ASUS Maximus       | 13       | 0.4%    |
| Gigabyte X470      | 12       | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 454      | 13.8%   |
| 2019    | 399      | 12.12%  |
| 2020    | 341      | 10.36%  |
| 2017    | 291      | 8.84%   |
| 2012    | 263      | 7.99%   |
| 2013    | 229      | 6.96%   |
| 2014    | 214      | 6.5%    |
| 2021    | 186      | 5.65%   |
| 2011    | 167      | 5.07%   |
| 2015    | 159      | 4.83%   |
| 2016    | 152      | 4.62%   |
| 2009    | 114      | 3.46%   |
| 2010    | 109      | 3.31%   |
| 2008    | 83       | 2.52%   |
| 2022    | 68       | 2.07%   |
| 2007    | 37       | 1.12%   |
| 2006    | 19       | 0.58%   |
| 2005    | 4        | 0.12%   |
| Unknown | 2        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3291     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3114     | 93.77%  |
| Enabled  | 207      | 6.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3289     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1019     | 30.22%  |
| 32.01-64.0      | 767      | 22.75%  |
| 8.01-16.0       | 584      | 17.32%  |
| 4.01-8.0        | 371      | 11%     |
| 64.01-256.0     | 258      | 7.65%   |
| 3.01-4.0        | 214      | 6.35%   |
| 24.01-32.0      | 117      | 3.47%   |
| 1.01-2.0        | 20       | 0.59%   |
| 2.01-3.0        | 16       | 0.47%   |
| Unknown         | 4        | 0.12%   |
| More than 256.0 | 1        | 0.03%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1051     | 27.46%  |
| 2.01-3.0    | 960      | 25.08%  |
| 3.01-4.0    | 750      | 19.6%   |
| 1.01-2.0    | 528      | 13.8%   |
| 8.01-16.0   | 356      | 9.3%    |
| 16.01-24.0  | 66       | 1.72%   |
| 0.51-1.0    | 56       | 1.46%   |
| 24.01-32.0  | 26       | 0.68%   |
| 32.01-64.0  | 13       | 0.34%   |
| 0.01-0.5    | 12       | 0.31%   |
| Unknown     | 6        | 0.16%   |
| 64.01-256.0 | 3        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 1072     | 30.73%  |
| 1      | 936      | 26.83%  |
| 3      | 712      | 20.41%  |
| 4      | 375      | 10.75%  |
| 5      | 182      | 5.22%   |
| 6      | 95       | 2.72%   |
| 7      | 51       | 1.46%   |
| 8      | 24       | 0.69%   |
| 9      | 12       | 0.34%   |
| 0      | 10       | 0.29%   |
| 10     | 5        | 0.14%   |
| 11     | 4        | 0.11%   |
| 12     | 3        | 0.09%   |
| 15     | 2        | 0.06%   |
| 14     | 2        | 0.06%   |
| 27     | 1        | 0.03%   |
| 24     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |
| 13     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2131     | 63.82%  |
| Yes       | 1208     | 36.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3271     | 99.36%  |
| No        | 21       | 0.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1766     | 52.81%  |
| Yes       | 1578     | 47.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1983     | 59.12%  |
| Yes       | 1371     | 40.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 790      | 23.87%  |
| Germany     | 255      | 7.7%    |
| Brazil      | 236      | 7.13%   |
| Russia      | 212      | 6.4%    |
| Canada      | 136      | 4.11%   |
| UK          | 133      | 4.02%   |
| France      | 130      | 3.93%   |
| Italy       | 118      | 3.56%   |
| Australia   | 107      | 3.23%   |
| Poland      | 95       | 2.87%   |
| Spain       | 79       | 2.39%   |
| Sweden      | 57       | 1.72%   |
| Netherlands | 51       | 1.54%   |
| India       | 51       | 1.54%   |
| Czechia     | 48       | 1.45%   |
| Switzerland | 45       | 1.36%   |
| Ukraine     | 38       | 1.15%   |
| Belgium     | 38       | 1.15%   |
| Finland     | 33       | 1%      |
| Austria     | 33       | 1%      |
| Mexico      | 32       | 0.97%   |
| Romania     | 31       | 0.94%   |
| Norway      | 31       | 0.94%   |
| Turkey      | 29       | 0.88%   |
| Argentina   | 29       | 0.88%   |
| Greece      | 22       | 0.66%   |
| New Zealand | 21       | 0.63%   |
| Japan       | 21       | 0.63%   |
| Portugal    | 20       | 0.6%    |
| Hungary     | 18       | 0.54%   |
| Indonesia   | 17       | 0.51%   |
| Colombia    | 15       | 0.45%   |
| Denmark     | 14       | 0.42%   |
| Philippines | 13       | 0.39%   |
| Chile       | 13       | 0.39%   |
| Slovakia    | 12       | 0.36%   |
| Belarus     | 12       | 0.36%   |
| South Korea | 11       | 0.33%   |
| China       | 11       | 0.33%   |
| Israel      | 10       | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 55       | 1.55%   |
| Sydney         | 42       | 1.18%   |
| Berlin         | 31       | 0.87%   |
| St Petersburg  | 28       | 0.79%   |
| Warsaw         | 26       | 0.73%   |
| Sao Paulo      | 23       | 0.65%   |
| Vienna         | 21       | 0.59%   |
| Paris          | 18       | 0.51%   |
| Brisbane       | 18       | 0.51%   |
| Hamburg        | 17       | 0.48%   |
| Toronto        | 16       | 0.45%   |
| Melbourne      | 16       | 0.45%   |
| Auckland       | 16       | 0.45%   |
| Zurich         | 15       | 0.42%   |
| Rome           | 15       | 0.42%   |
| Prague         | 15       | 0.42%   |
| Athens         | 14       | 0.39%   |
| Rio de Janeiro | 13       | 0.37%   |
| Porto Alegre   | 13       | 0.37%   |
| Madrid         | 13       | 0.37%   |
| London         | 13       | 0.37%   |
| Buenos Aires   | 13       | 0.37%   |
| Munich         | 12       | 0.34%   |
| Istanbul       | 12       | 0.34%   |
| Helsinki       | 12       | 0.34%   |
| Amsterdam      | 12       | 0.34%   |
| Yekaterinburg  | 11       | 0.31%   |
| Vancouver      | 11       | 0.31%   |
| Seattle        | 11       | 0.31%   |
| Milan          | 11       | 0.31%   |
| Krakow         | 11       | 0.31%   |
| Belo Horizonte | 11       | 0.31%   |
| Wroclaw        | 10       | 0.28%   |
| Montreal       | 10       | 0.28%   |
| Los Angeles    | 10       | 0.28%   |
| Cologne        | 10       | 0.28%   |
| Budapest       | 10       | 0.28%   |
| Bucharest      | 10       | 0.28%   |
| Austin         | 10       | 0.28%   |
| Ufa            | 9        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 1243     | 2452   | 18.48%  |
| WDC                       | 1231     | 2393   | 18.3%   |
| Seagate                   | 1116     | 2060   | 16.59%  |
| Kingston                  | 462      | 696    | 6.87%   |
| Crucial                   | 347      | 535    | 5.16%   |
| Toshiba                   | 346      | 540    | 5.14%   |
| SanDisk                   | 325      | 455    | 4.83%   |
| Hitachi                   | 179      | 293    | 2.66%   |
| Intel                     | 153      | 268    | 2.28%   |
| A-DATA Technology         | 118      | 164    | 1.75%   |
| Phison                    | 108      | 151    | 1.61%   |
| HGST                      | 66       | 133    | 0.98%   |
| Corsair                   | 53       | 80     | 0.79%   |
| Unknown                   | 51       | 83     | 0.76%   |
| SPCC                      | 50       | 80     | 0.74%   |
| Micron/Crucial Technology | 48       | 64     | 0.71%   |
| China                     | 46       | 59     | 0.68%   |
| SK hynix                  | 42       | 49     | 0.62%   |
| Silicon Motion            | 36       | 48     | 0.54%   |
| OCZ                       | 36       | 47     | 0.54%   |
| PNY                       | 35       | 49     | 0.52%   |
| Phison Electronics        | 33       | 52     | 0.49%   |
| Patriot                   | 32       | 50     | 0.48%   |
| Micron Technology         | 32       | 46     | 0.48%   |
| XPG                       | 24       | 34     | 0.36%   |
| Maxtor                    | 23       | 27     | 0.34%   |
| Transcend                 | 21       | 28     | 0.31%   |
| Team                      | 20       | 30     | 0.3%    |
| Plextor                   | 20       | 28     | 0.3%    |
| Intenso                   | 19       | 27     | 0.28%   |
| Gigabyte Technology       | 19       | 34     | 0.28%   |
| Hewlett-Packard           | 18       | 22     | 0.27%   |
| GOODRAM                   | 17       | 25     | 0.25%   |
| ASMT                      | 17       | 19     | 0.25%   |
| Apacer                    | 15       | 26     | 0.22%   |
| SABRENT                   | 13       | 16     | 0.19%   |
| KingSpec                  | 13       | 21     | 0.19%   |
| Realtek Semiconductor     | 12       | 14     | 0.18%   |
| LITEON                    | 11       | 14     | 0.16%   |
| JMicron Technology        | 11       | 17     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 117      | 1.44%   |
| Kingston SA400S37240G 240GB SSD                     | 98       | 1.2%    |
| Samsung SSD 860 EVO 500GB                           | 97       | 1.19%   |
| Seagate ST1000DM010-2EP102 1TB                      | 91       | 1.12%   |
| Samsung NVMe SSD Drive 500GB                        | 91       | 1.12%   |
| Seagate ST2000DM008-2FR102 2TB                      | 87       | 1.07%   |
| Samsung SSD 850 EVO 500GB                           | 85       | 1.04%   |
| Samsung SSD 860 EVO 1TB                             | 81       | 0.99%   |
| Seagate ST500DM002-1BD142 500GB                     | 70       | 0.86%   |
| Samsung NVMe SSD Drive 1TB                          | 69       | 0.85%   |
| Kingston SA400S37120G 120GB SSD                     | 62       | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 61       | 0.75%   |
| Toshiba DT01ACA100 1TB                              | 60       | 0.74%   |
| Kingston SA400S37480G 480GB SSD                     | 56       | 0.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 53       | 0.65%   |
| Crucial CT500MX500SSD1 500GB                        | 50       | 0.61%   |
| Crucial CT1000MX500SSD1 1TB                         | 48       | 0.59%   |
| Samsung SSD 970 EVO Plus 500GB                      | 44       | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB                      | 42       | 0.52%   |
| SanDisk NVMe SSD Drive 1TB                          | 40       | 0.49%   |
| Samsung SSD 860 EVO 250GB                           | 39       | 0.48%   |
| Kingston SV300S37A120G 120GB SSD                    | 39       | 0.48%   |
| Seagate ST4000DM004-2CV104 4TB                      | 38       | 0.47%   |
| SanDisk NVMe SSD Drive 500GB                        | 38       | 0.47%   |
| Toshiba HDWD110 1TB                                 | 37       | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB                      | 37       | 0.45%   |
| Toshiba DT01ACA200 2TB                              | 36       | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB                      | 34       | 0.42%   |
| Samsung SSD 860 QVO 1TB                             | 34       | 0.42%   |
| Samsung SSD 840 EVO 250GB                           | 34       | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 33       | 0.41%   |
| Seagate ST3500418AS 500GB                           | 33       | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                        | 33       | 0.41%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 33       | 0.41%   |
| Crucial CT240BX500SSD1 240GB                        | 33       | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 31       | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 30       | 0.37%   |
| Seagate ST31000528AS 1TB                            | 30       | 0.37%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 28       | 0.34%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 27       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1084     | 1995   | 37%     |
| WDC                 | 1059     | 2029   | 36.14%  |
| Toshiba             | 299      | 450    | 10.2%   |
| Hitachi             | 179      | 293    | 6.11%   |
| Samsung Electronics | 131      | 212    | 4.47%   |
| HGST                | 66       | 133    | 2.25%   |
| Maxtor              | 22       | 25     | 0.75%   |
| Unknown             | 15       | 21     | 0.51%   |
| SABRENT             | 11       | 13     | 0.38%   |
| Fujitsu             | 9        | 11     | 0.31%   |
| ASMT                | 9        | 10     | 0.31%   |
| JMicron Technology  | 7        | 11     | 0.24%   |
| Hewlett-Packard     | 5        | 6      | 0.17%   |
| Apple               | 4        | 4      | 0.14%   |
| MaxDigital          | 3        | 3      | 0.1%    |
| Intenso             | 3        | 6      | 0.1%    |
| USB3.0              | 2        | 2      | 0.07%   |
| USB                 | 2        | 2      | 0.07%   |
| Synology            | 2        | 3      | 0.07%   |
| LaCie               | 2        | 4      | 0.07%   |
| ASMT109x            | 2        | 2      | 0.07%   |
| USB 3.0             | 1        | 3      | 0.03%   |
| Unknown (583)       | 1        | 1      | 0.03%   |
| SAGE                | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| PHD 3.0             | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| KESU                | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| External            | 1        | 1      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| ASMT106x            | 1        | 2      | 0.03%   |
| ASMedia             | 1        | 1      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 747      | 1336   | 29.01%  |
| Kingston            | 383      | 583    | 14.87%  |
| Crucial             | 313      | 488    | 12.16%  |
| SanDisk             | 191      | 248    | 7.42%   |
| WDC                 | 173      | 254    | 6.72%   |
| A-DATA Technology   | 98       | 136    | 3.81%   |
| Intel               | 71       | 136    | 2.76%   |
| China               | 46       | 59     | 1.79%   |
| SPCC                | 40       | 61     | 1.55%   |
| OCZ                 | 36       | 47     | 1.4%    |
| PNY                 | 35       | 48     | 1.36%   |
| Toshiba             | 30       | 43     | 1.17%   |
| Patriot             | 29       | 46     | 1.13%   |
| Corsair             | 28       | 42     | 1.09%   |
| Micron Technology   | 25       | 36     | 0.97%   |
| Transcend           | 21       | 28     | 0.82%   |
| SK hynix            | 18       | 19     | 0.7%    |
| Plextor             | 18       | 25     | 0.7%    |
| Team                | 17       | 27     | 0.66%   |
| GOODRAM             | 17       | 25     | 0.66%   |
| Seagate             | 13       | 16     | 0.5%    |
| KingSpec            | 13       | 21     | 0.5%    |
| Intenso             | 13       | 18     | 0.5%    |
| Apacer              | 13       | 23     | 0.5%    |
| Gigabyte Technology | 12       | 20     | 0.47%   |
| LITEON              | 11       | 14     | 0.43%   |
| KingDian            | 10       | 11     | 0.39%   |
| Unknown             | 9        | 9      | 0.35%   |
| LITEONIT            | 9        | 10     | 0.35%   |
| Hewlett-Packard     | 8        | 9      | 0.31%   |
| Verbatim            | 7        | 10     | 0.27%   |
| Mushkin             | 7        | 11     | 0.27%   |
| Lexar               | 7        | 11     | 0.27%   |
| Leven               | 7        | 8      | 0.27%   |
| ASMT                | 6        | 7      | 0.23%   |
| OWC                 | 4        | 6      | 0.16%   |
| KingFast            | 4        | 4      | 0.16%   |
| Drevo               | 4        | 4      | 0.16%   |
| Radeon              | 3        | 4      | 0.12%   |
| Inateck             | 3        | 8      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2218     | 5252   | 39.43%  |
| SSD     | 2066     | 4009   | 36.73%  |
| NVMe    | 1243     | 2164   | 22.1%   |
| Unknown | 90       | 133    | 1.6%    |
| MMC     | 8        | 9      | 0.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2946     | 8968   | 65.99%  |
| NVMe | 1242     | 2156   | 27.82%  |
| SAS  | 268      | 434    | 6%      |
| MMC  | 8        | 9      | 0.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 2175     | 4456   | 45.08%  |
| 0.51-1.0        | 1455     | 2573   | 30.16%  |
| 1.01-2.0        | 594      | 976    | 12.31%  |
| 3.01-4.0        | 248      | 485    | 5.14%   |
| 2.01-3.0        | 166      | 326    | 3.44%   |
| 4.01-10.0       | 160      | 380    | 3.32%   |
| 10.01-20.0      | 26       | 62     | 0.54%   |
| More than 100.0 | 1        | 3      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 642      | 18.09%  |
| 1001-2000      | 631      | 17.78%  |
| 251-500        | 549      | 15.47%  |
| More than 3000 | 547      | 15.42%  |
| 101-250        | 461      | 12.99%  |
| 2001-3000      | 296      | 8.34%   |
| 1-20           | 165      | 4.65%   |
| Unknown        | 133      | 3.75%   |
| 51-100         | 89       | 2.51%   |
| 21-50          | 35       | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 641      | 17.2%   |
| 101-250        | 515      | 13.82%  |
| 21-50          | 471      | 12.64%  |
| 501-1000       | 461      | 12.37%  |
| 251-500        | 457      | 12.27%  |
| 51-100         | 403      | 10.82%  |
| 1001-2000      | 337      | 9.04%   |
| More than 3000 | 178      | 4.78%   |
| Unknown        | 133      | 3.57%   |
| 2001-3000      | 129      | 3.46%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 15       | 40     | 3.09%   |
| Seagate ST3500418AS 500GB           | 7        | 12     | 1.44%   |
| Seagate ST31000528AS 1TB            | 7        | 9      | 1.44%   |
| Samsung Electronics SSD 870 EVO 1TB | 7        | 7      | 1.44%   |
| Seagate ST31000524AS 1TB            | 5        | 5      | 1.03%   |
| Seagate ST1000DM010-2EP102 1TB      | 5        | 5      | 1.03%   |
| Samsung Electronics HD322HJ 320GB   | 5        | 7      | 1.03%   |
| Intel SSDSC2CT120A3 120GB           | 5        | 25     | 1.03%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4        | 4      | 0.82%   |
| Toshiba MQ01ABD050 500GB            | 4        | 5      | 0.82%   |
| Seagate ST31500341AS 1TB            | 4        | 4      | 0.82%   |
| Seagate ST2000DM001-1CH164 2TB      | 4        | 4      | 0.82%   |
| Samsung Electronics HD501LJ 500GB   | 4        | 29     | 0.82%   |
| Crucial CT275MX300SSD1 275GB        | 4        | 4      | 0.82%   |
| Crucial CT240M500SSD1 240GB         | 4        | 4      | 0.82%   |
| Crucial CT128MX100SSD1 128GB        | 4        | 6      | 0.82%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 3        | 3      | 0.62%   |
| WDC WD20EZRX-00D8PB0 2TB            | 3        | 4      | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 4      | 0.62%   |
| WDC WD10EZEX-00WN4A0 1TB            | 3        | 3      | 0.62%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 3        | 3      | 0.62%   |
| Toshiba DT01ACA100 1TB              | 3        | 3      | 0.62%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 3      | 0.62%   |
| Seagate ST3000DM008-2DM166 3TB      | 3        | 3      | 0.62%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 3      | 0.62%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 3      | 0.62%   |
| Hitachi HDS721010DLE630 1TB         | 3        | 5      | 0.62%   |
| Hitachi HDS721010CLA332 1TB         | 3        | 3      | 0.62%   |
| Hitachi HDP725050GLA360 500GB       | 3        | 3      | 0.62%   |
| WDC WD5000AAKX-753CA1 500GB         | 2        | 2      | 0.41%   |
| WDC WD5000AAKX-003CA0 500GB         | 2        | 2      | 0.41%   |
| WDC WD40PURZ-85AKKY0 4TB            | 2        | 2      | 0.41%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 2      | 0.41%   |
| WDC WD30EZRX-00D8PB0 3TB            | 2        | 2      | 0.41%   |
| WDC WD30EFRX-68AX9N0 3TB            | 2        | 2      | 0.41%   |
| WDC WD20EFRX-68AX9N0 2TB            | 2        | 6      | 0.41%   |
| WDC WD1600AVVS-63L2B0 160GB         | 2        | 5      | 0.41%   |
| WDC WD1600AABS-00H4A0 160GB         | 2        | 2      | 0.41%   |
| WDC WD10EZRX-00A8LB0 1TB            | 2        | 2      | 0.41%   |
| WDC WD10EZEX-60ZF5A0 1TB            | 2        | 2      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 122      | 192    | 26.75%  |
| WDC                 | 118      | 174    | 25.88%  |
| Samsung Electronics | 42       | 75     | 9.21%   |
| Hitachi             | 34       | 47     | 7.46%   |
| Toshiba             | 28       | 33     | 6.14%   |
| Intel               | 19       | 41     | 4.17%   |
| Crucial             | 18       | 20     | 3.95%   |
| SanDisk             | 13       | 13     | 2.85%   |
| Kingston            | 10       | 11     | 2.19%   |
| A-DATA Technology   | 9        | 9      | 1.97%   |
| Maxtor              | 6        | 6      | 1.32%   |
| Corsair             | 5        | 8      | 1.1%    |
| OCZ                 | 4        | 5      | 0.88%   |
| SK hynix            | 3        | 3      | 0.66%   |
| LITEON              | 3        | 3      | 0.66%   |
| HGST                | 3        | 5      | 0.66%   |
| SPCC                | 2        | 3      | 0.44%   |
| OCZ-VERTEX3         | 2        | 2      | 0.44%   |
| Fujitsu             | 2        | 2      | 0.44%   |
| Verbatim            | 1        | 1      | 0.22%   |
| Unknown             | 1        | 1      | 0.22%   |
| Team                | 1        | 4      | 0.22%   |
| PNY                 | 1        | 1      | 0.22%   |
| ORICO               | 1        | 1      | 0.22%   |
| Micron Technology   | 1        | 1      | 0.22%   |
| KingDian            | 1        | 1      | 0.22%   |
| Hewlett-Packard     | 1        | 1      | 0.22%   |
| BIWIN               | 1        | 1      | 0.22%   |
| ASMT                | 1        | 1      | 0.22%   |
| ASMedia             | 1        | 1      | 0.22%   |
| Apacer              | 1        | 1      | 0.22%   |
| AMD                 | 1        | 2      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 122      | 192    | 35.99%  |
| WDC                 | 117      | 173    | 34.51%  |
| Hitachi             | 34       | 47     | 10.03%  |
| Toshiba             | 28       | 33     | 8.26%   |
| Samsung Electronics | 25       | 56     | 7.37%   |
| Maxtor              | 6        | 6      | 1.77%   |
| HGST                | 3        | 5      | 0.88%   |
| Fujitsu             | 2        | 2      | 0.59%   |
| Hewlett-Packard     | 1        | 1      | 0.29%   |
| ASMT                | 1        | 1      | 0.29%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 307      | 516    | 72.58%  |
| SSD  | 106      | 143    | 25.06%  |
| NVMe | 10       | 10     | 2.36%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BEVT-00ZAT0 500GB       | 1        | 2      | 12.5%   |
| Toshiba HDWD130 3TB               | 1        | 1      | 12.5%   |
| SPCC M.2 PCIe SSD 2TB             | 1        | 1      | 12.5%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 12.5%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 12.5%   |
| Samsung Electronics SSD 980 500GB | 1        | 2      | 12.5%   |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 12.5%   |
| Hitachi HDS721010DLE630 1TB       | 1        | 6      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 2      | 25%     |
| Samsung Electronics | 2        | 4      | 25%     |
| WDC                 | 1        | 2      | 12.5%   |
| Toshiba             | 1        | 1      | 12.5%   |
| SPCC                | 1        | 1      | 12.5%   |
| Hitachi             | 1        | 6      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1930     | 6478   | 50.34%  |
| Works    | 1486     | 4404   | 38.76%  |
| Malfunc  | 411      | 669    | 10.72%  |
| Failed   | 7        | 16     | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 1858     | 36.23%  |
| AMD                            | 1400     | 27.3%   |
| Samsung Electronics            | 566      | 11.04%  |
| ASMedia Technology             | 220      | 4.29%   |
| SanDisk                        | 206      | 4.02%   |
| Phison Electronics             | 171      | 3.33%   |
| Marvell Technology Group       | 104      | 2.03%   |
| Kingston Technology Company    | 96       | 1.87%   |
| Micron/Crucial Technology      | 81       | 1.58%   |
| JMicron Technology             | 79       | 1.54%   |
| Nvidia                         | 51       | 0.99%   |
| Silicon Motion                 | 46       | 0.9%    |
| ADATA Technology               | 42       | 0.82%   |
| Toshiba America Info Systems   | 25       | 0.49%   |
| SK hynix                       | 24       | 0.47%   |
| Realtek Semiconductor          | 21       | 0.41%   |
| LSI Logic / Symbios Logic      | 21       | 0.41%   |
| Broadcom / LSI                 | 18       | 0.35%   |
| Seagate Technology             | 14       | 0.27%   |
| Silicon Image                  | 12       | 0.23%   |
| VIA Technologies               | 10       | 0.19%   |
| Micron Technology              | 9        | 0.18%   |
| MAXIO Technology (Hangzhou)    | 9        | 0.18%   |
| Lite-On Technology             | 9        | 0.18%   |
| KIOXIA                         | 6        | 0.12%   |
| Adaptec                        | 6        | 0.12%   |
| Integrated Technology Express  | 4        | 0.08%   |
| Hewlett-Packard                | 3        | 0.06%   |
| ULi Electronics                | 2        | 0.04%   |
| Solid State Storage Technology | 2        | 0.04%   |
| Netac Technology               | 2        | 0.04%   |
| Lite-On IT Corp. / Plextor     | 2        | 0.04%   |
| INNOGRIT                       | 2        | 0.04%   |
| HighPoint Technologies         | 2        | 0.04%   |
| 3ware                          | 2        | 0.04%   |
| Union Memory (Shenzhen)        | 1        | 0.02%   |
| Solidigm                       | 1        | 0.02%   |
| Shenzhen Longsys Electronics   | 1        | 0.02%   |
| Biwin Storage Technology       | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 897      | 14.25%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 354      | 5.62%   |
| AMD 400 Series Chipset SATA Controller                                                  | 351      | 5.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 219      | 3.48%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 211      | 3.35%   |
| AMD 500 Series Chipset SATA Controller                                                  | 198      | 3.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 188      | 2.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 182      | 2.89%   |
| Intel SATA Controller [RAID mode]                                                       | 142      | 2.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 135      | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 134      | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 125      | 1.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 123      | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 122      | 1.94%   |
| Phison E12 NVMe Controller                                                              | 98       | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 97       | 1.54%   |
| AMD 300 Series Chipset SATA Controller                                                  | 96       | 1.53%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 90       | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 87       | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 75       | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 62       | 0.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 61       | 0.97%   |
| AMD FCH SATA Controller D                                                               | 57       | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 54       | 0.86%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 52       | 0.83%   |
| AMD X370 Series Chipset SATA Controller                                                 | 52       | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 45       | 0.71%   |
| Intel SSD 660P Series                                                                   | 44       | 0.7%    |
| Samsung NVMe SSD Controller 980                                                         | 42       | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41       | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 41       | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 40       | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 40       | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 39       | 0.62%   |
| Kingston Company A2000 NVMe SSD                                                         | 38       | 0.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 37       | 0.59%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 37       | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 36       | 0.57%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 35       | 0.56%   |
| Kingston Company Company Non-Volatile memory controller                                 | 31       | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2860     | 58.13%  |
| NVMe | 1245     | 25.3%   |
| IDE  | 515      | 10.47%  |
| RAID | 251      | 5.1%    |
| SAS  | 38       | 0.77%   |
| SCSI | 11       | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1840     | 55.91%  |
| AMD    | 1451     | 44.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 117      | 3.53%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 90       | 2.72%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 68       | 2.05%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 56       | 1.69%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 53       | 1.6%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 51       | 1.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 47       | 1.42%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 46       | 1.39%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 44       | 1.33%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 43       | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 40       | 1.21%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 38       | 1.15%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 35       | 1.06%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 34       | 1.03%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 34       | 1.03%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 34       | 1.03%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 33       | 1%      |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 33       | 1%      |
| Intel Core i5-6500 CPU @ 3.20GHz            | 32       | 0.97%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 32       | 0.97%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 31       | 0.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 31       | 0.94%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 30       | 0.91%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 30       | 0.91%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 28       | 0.85%   |
| AMD FX-6300 Six-Core Processor              | 28       | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 27       | 0.82%   |
| AMD FX-8350 Eight-Core Processor            | 27       | 0.82%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 25       | 0.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 25       | 0.76%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 25       | 0.76%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 24       | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 24       | 0.72%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 24       | 0.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 24       | 0.72%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 23       | 0.69%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 21       | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 21       | 0.63%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 21       | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 20       | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 561      | 17%     |
| Intel Core i7           | 537      | 16.27%  |
| AMD Ryzen 5             | 465      | 14.09%  |
| AMD Ryzen 7             | 328      | 9.94%   |
| AMD Ryzen 9             | 196      | 5.94%   |
| Intel Core i3           | 176      | 5.33%   |
| Intel Xeon              | 170      | 5.15%   |
| AMD FX                  | 124      | 3.76%   |
| Other                   | 95       | 2.88%   |
| Intel Core 2 Duo        | 70       | 2.12%   |
| AMD Ryzen 3             | 53       | 1.61%   |
| Intel Core 2 Quad       | 47       | 1.42%   |
| Intel Core i9           | 45       | 1.36%   |
| Intel Pentium           | 42       | 1.27%   |
| AMD Ryzen Threadripper  | 40       | 1.21%   |
| Intel Celeron           | 38       | 1.15%   |
| AMD Phenom II X4        | 31       | 0.94%   |
| AMD A10                 | 26       | 0.79%   |
| AMD A8                  | 25       | 0.76%   |
| Intel Pentium Dual-Core | 23       | 0.7%    |
| AMD A6                  | 19       | 0.58%   |
| AMD Athlon II X2        | 18       | 0.55%   |
| AMD Phenom II X6        | 16       | 0.48%   |
| AMD Athlon              | 15       | 0.45%   |
| Intel Core 2            | 13       | 0.39%   |
| AMD Phenom              | 12       | 0.36%   |
| AMD Athlon 64 X2        | 12       | 0.36%   |
| Intel Atom              | 11       | 0.33%   |
| AMD Ryzen 7 PRO         | 9        | 0.27%   |
| AMD Athlon X4           | 8        | 0.24%   |
| AMD A4                  | 8        | 0.24%   |
| AMD Ryzen 5 PRO         | 7        | 0.21%   |
| AMD Athlon II X4        | 7        | 0.21%   |
| AMD Phenom II X2        | 6        | 0.18%   |
| Intel Pentium Gold      | 4        | 0.12%   |
| Intel Pentium Dual      | 4        | 0.12%   |
| Intel Genuine           | 4        | 0.12%   |
| AMD Athlon Dual Core    | 4        | 0.12%   |
| Intel Pentium D         | 3        | 0.09%   |
| AMD Athlon 64           | 3        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1243     | 37.64%  |
| 6      | 676      | 20.47%  |
| 2      | 495      | 14.99%  |
| 8      | 469      | 14.2%   |
| 12     | 174      | 5.27%   |
| 16     | 103      | 3.12%   |
| 3      | 47       | 1.42%   |
| 10     | 35       | 1.06%   |
| 1      | 29       | 0.88%   |
| 24     | 13       | 0.39%   |
| 32     | 10       | 0.3%    |
| 14     | 5        | 0.15%   |
| 28     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3250     | 98.75%  |
| 2      | 41       | 1.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2246     | 68.1%   |
| 1      | 1052     | 31.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3203     | 96.83%  |
| Unknown        | 105      | 3.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 312      | 9.22%   |
| 0x08701021 | 260      | 7.69%   |
| Unknown    | 192      | 5.68%   |
| 0x306a9    | 179      | 5.29%   |
| 0x506e3    | 166      | 4.91%   |
| 0x0800820d | 139      | 4.11%   |
| 0x206a7    | 134      | 3.96%   |
| 0x906ea    | 128      | 3.78%   |
| 0x906e9    | 116      | 3.43%   |
| 0x08701013 | 112      | 3.31%   |
| 0x1067a    | 88       | 2.6%    |
| 0x06000852 | 73       | 2.16%   |
| 0x0a201016 | 71       | 2.1%    |
| 0x0a201009 | 62       | 1.83%   |
| 0x08001138 | 58       | 1.71%   |
| 0x906ed    | 56       | 1.66%   |
| 0x08001137 | 47       | 1.39%   |
| 0x90672    | 46       | 1.36%   |
| 0x08108109 | 46       | 1.36%   |
| 0xa0655    | 42       | 1.24%   |
| 0x306f2    | 42       | 1.24%   |
| 0x0a50000c | 42       | 1.24%   |
| 0x010000c8 | 40       | 1.18%   |
| 0xa0653    | 38       | 1.12%   |
| 0x08101016 | 37       | 1.09%   |
| 0x206d7    | 33       | 0.98%   |
| 0x06001119 | 33       | 0.98%   |
| 0x20655    | 28       | 0.83%   |
| 0x106a5    | 27       | 0.8%    |
| 0xa0671    | 26       | 0.77%   |
| 0x6fb      | 26       | 0.77%   |
| 0x10676    | 26       | 0.77%   |
| 0x906eb    | 25       | 0.74%   |
| 0x106e5    | 24       | 0.71%   |
| 0x906ec    | 22       | 0.65%   |
| 0x0800820b | 21       | 0.62%   |
| 0x06003106 | 20       | 0.59%   |
| 0x0a50000d | 19       | 0.56%   |
| 0x0a20120a | 19       | 0.56%   |
| 0x0810100b | 19       | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 413      | 12.5%   |
| KabyLake         | 372      | 11.26%  |
| Haswell          | 372      | 11.26%  |
| Zen 3            | 256      | 7.75%   |
| Zen+             | 234      | 7.08%   |
| IvyBridge        | 205      | 6.2%    |
| Zen              | 193      | 5.84%   |
| Skylake          | 193      | 5.84%   |
| SandyBridge      | 179      | 5.42%   |
| Piledriver       | 137      | 4.15%   |
| Penryn           | 128      | 3.87%   |
| K10              | 95       | 2.88%   |
| CometLake        | 82       | 2.48%   |
| Alderlake Hybrid | 60       | 1.82%   |
| Nehalem          | 57       | 1.73%   |
| Westmere         | 54       | 1.63%   |
| Core             | 54       | 1.63%   |
| Unknown          | 30       | 0.91%   |
| Steamroller      | 26       | 0.79%   |
| Icelake          | 26       | 0.79%   |
| Excavator        | 22       | 0.67%   |
| Bulldozer        | 21       | 0.64%   |
| K8 Hammer        | 19       | 0.58%   |
| Silvermont       | 15       | 0.45%   |
| Broadwell        | 14       | 0.42%   |
| Bonnell          | 9        | 0.27%   |
| NetBurst         | 7        | 0.21%   |
| K10 Llano        | 7        | 0.21%   |
| Jaguar           | 6        | 0.18%   |
| Bobcat           | 5        | 0.15%   |
| Goldmont         | 4        | 0.12%   |
| Puma             | 3        | 0.09%   |
| Goldmont plus    | 3        | 0.09%   |
| Tremont          | 2        | 0.06%   |
| TigerLake        | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1447     | 40.26%  |
| AMD                        | 1329     | 36.98%  |
| Intel                      | 801      | 22.29%  |
| ASPEED Technology          | 9        | 0.25%   |
| Matrox Electronics Systems | 7        | 0.19%   |
| S3 Graphics                | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 279      | 7.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 138      | 3.72%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 118      | 3.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 97       | 2.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 92       | 2.48%   |
| Intel HD Graphics 530                                                       | 87       | 2.34%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 87       | 2.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 75       | 2.02%   |
| Intel HD Graphics 630                                                       | 64       | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 58       | 1.56%   |
| Nvidia GK208B [GeForce GT 710]                                              | 57       | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 56       | 1.51%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 55       | 1.48%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 49       | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 48       | 1.29%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 48       | 1.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 48       | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 44       | 1.19%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 41       | 1.1%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 41       | 1.1%    |
| Nvidia GT218 [GeForce 210]                                                  | 40       | 1.08%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 40       | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 39       | 1.05%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 39       | 1.05%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 39       | 1.05%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 38       | 1.02%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 37       | 1%      |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 36       | 0.97%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 35       | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 34       | 0.92%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 34       | 0.92%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 33       | 0.89%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 32       | 0.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 30       | 0.81%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 30       | 0.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 28       | 0.75%   |
| Nvidia GK208B [GeForce GT 730]                                              | 27       | 0.73%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 26       | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 26       | 0.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 25       | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1310     | 39.15%  |
| 1 x AMD                  | 1219     | 36.43%  |
| 1 x Intel                | 592      | 17.69%  |
| Intel + Nvidia           | 72       | 2.15%   |
| 2 x AMD                  | 47       | 1.4%    |
| AMD + Nvidia             | 38       | 1.14%   |
| Intel + AMD              | 23       | 0.69%   |
| 2 x Nvidia               | 20       | 0.6%    |
| 1 x ASPEED               | 5        | 0.15%   |
| 1 x Matrox               | 4        | 0.12%   |
| 2 x Intel                | 3        | 0.09%   |
| Nvidia + Matrox          | 2        | 0.06%   |
| Nvidia + ASPEED          | 2        | 0.06%   |
| Other                    | 1        | 0.03%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.03%   |
| 1 x S3 Graphics          | 1        | 0.03%   |
| Intel + 2 x Nvidia       | 1        | 0.03%   |
| Intel + 2 x AMD          | 1        | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.03%   |
| AMD + 2 x Nvidia         | 1        | 0.03%   |
| AMD + Matrox             | 1        | 0.03%   |
| AMD + ASPEED             | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2448     | 72.86%  |
| Proprietary | 820      | 24.4%   |
| Unknown     | 92       | 2.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1146     | 33.34%  |
| 7.01-8.0   | 529      | 15.39%  |
| 1.01-2.0   | 454      | 13.21%  |
| 3.01-4.0   | 372      | 10.82%  |
| 0.51-1.0   | 333      | 9.69%   |
| 0.01-0.5   | 232      | 6.75%   |
| 5.01-6.0   | 162      | 4.71%   |
| 8.01-16.0  | 153      | 4.45%   |
| 2.01-3.0   | 47       | 1.37%   |
| 16.01-24.0 | 9        | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 581      | 14.89%  |
| Dell                 | 532      | 13.63%  |
| Goldstar             | 503      | 12.89%  |
| Acer                 | 276      | 7.07%   |
| AOC                  | 231      | 5.92%   |
| Hewlett-Packard      | 229      | 5.87%   |
| BenQ                 | 220      | 5.64%   |
| Ancor Communications | 198      | 5.07%   |
| Philips              | 158      | 4.05%   |
| ViewSonic            | 101      | 2.59%   |
| Iiyama               | 87       | 2.23%   |
| Lenovo               | 82       | 2.1%    |
| ASUSTek Computer     | 76       | 1.95%   |
| Sony                 | 37       | 0.95%   |
| MSI                  | 37       | 0.95%   |
| Eizo                 | 36       | 0.92%   |
| Sceptre Tech         | 35       | 0.9%    |
| Unknown              | 31       | 0.79%   |
| HannStar             | 28       | 0.72%   |
| Gigabyte Technology  | 26       | 0.67%   |
| NEC Computers        | 24       | 0.61%   |
| Vizio                | 18       | 0.46%   |
| Insignia             | 15       | 0.38%   |
| LG Electronics       | 13       | 0.33%   |
| Mi                   | 12       | 0.31%   |
| ___                  | 11       | 0.28%   |
| Panasonic            | 11       | 0.28%   |
| Fujitsu Siemens      | 11       | 0.28%   |
| Pixio                | 10       | 0.26%   |
| Gateway              | 10       | 0.26%   |
| Vestel Elektronik    | 7        | 0.18%   |
| RTK                  | 7        | 0.18%   |
| ONN                  | 7        | 0.18%   |
| Sharp                | 6        | 0.15%   |
| Hitachi              | 6        | 0.15%   |
| Apple                | 6        | 0.15%   |
| Unknown (XXX)        | 5        | 0.13%   |
| Toshiba              | 5        | 0.13%   |
| Planar               | 5        | 0.13%   |
| Packard Bell         | 5        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 32       | 0.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 26       | 0.61%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 25       | 0.59%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 22       | 0.52%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 20       | 0.47%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 19       | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 17       | 0.4%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 16       | 0.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 16       | 0.38%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 15       | 0.35%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 15       | 0.35%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 15       | 0.35%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 14       | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 14       | 0.33%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 14       | 0.33%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 14       | 0.33%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 13       | 0.3%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 13       | 0.3%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 12       | 0.28%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 12       | 0.28%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 11       | 0.26%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 11       | 0.26%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 11       | 0.26%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11       | 0.26%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 10       | 0.23%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 10       | 0.23%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 9        | 0.21%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 9        | 0.21%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 9        | 0.21%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                     | 9        | 0.21%   |
| MSI MAG341CQ MSI1462 3440x1440 797x334mm 34.0-inch                    | 8        | 0.19%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 8        | 0.19%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 8        | 0.19%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 8        | 0.19%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 8        | 0.19%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 8        | 0.19%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                       | 8        | 0.19%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 8        | 0.19%   |
| ___ LCDTV16 ___0101 1360x768                                          | 7        | 0.16%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch             | 7        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1691     | 45.12%  |
| 2560x1440 (QHD)    | 458      | 12.22%  |
| 3840x2160 (4K)     | 435      | 11.61%  |
| 1280x1024 (SXGA)   | 157      | 4.19%   |
| 1680x1050 (WSXGA+) | 148      | 3.95%   |
| 1920x1200 (WUXGA)  | 136      | 3.63%   |
| 3440x1440          | 114      | 3.04%   |
| 1366x768 (WXGA)    | 104      | 2.77%   |
| 1440x900 (WXGA+)   | 100      | 2.67%   |
| 2560x1080          | 87       | 2.32%   |
| 1600x900 (HD+)     | 70       | 1.87%   |
| 1360x768           | 44       | 1.17%   |
| 3840x1080          | 36       | 0.96%   |
| Unknown            | 36       | 0.96%   |
| 1600x1200          | 20       | 0.53%   |
| 2560x1600          | 14       | 0.37%   |
| 2288x1287          | 14       | 0.37%   |
| 1024x768 (XGA)     | 14       | 0.37%   |
| 1920x540           | 13       | 0.35%   |
| 1280x720 (HD)      | 7        | 0.19%   |
| 2048x1152          | 6        | 0.16%   |
| 3840x1600          | 5        | 0.13%   |
| 1280x960           | 5        | 0.13%   |
| 2160x1200          | 3        | 0.08%   |
| 5760x2160          | 2        | 0.05%   |
| 3840x1200          | 2        | 0.05%   |
| 1280x768           | 2        | 0.05%   |
| 7680x2160          | 1        | 0.03%   |
| 7680x1440          | 1        | 0.03%   |
| 7120x1080          | 1        | 0.03%   |
| 6784x2160          | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 6400x1080          | 1        | 0.03%   |
| 5760x1200          | 1        | 0.03%   |
| 5760x1080          | 1        | 0.03%   |
| 5120x1440          | 1        | 0.03%   |
| 4864x2160          | 1        | 0.03%   |
| 4480x1200          | 1        | 0.03%   |
| 4480x1080          | 1        | 0.03%   |
| 4160x1440          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 741      | 18.8%   |
| 24      | 687      | 17.43%  |
| 23      | 485      | 12.31%  |
| 21      | 456      | 11.57%  |
| 31      | 196      | 4.97%   |
| 19      | 180      | 4.57%   |
| 34      | 176      | 4.47%   |
| 22      | 129      | 3.27%   |
| 18      | 129      | 3.27%   |
| Unknown | 115      | 2.92%   |
| 20      | 91       | 2.31%   |
| 17      | 58       | 1.47%   |
| 32      | 51       | 1.29%   |
| 72      | 50       | 1.27%   |
| 25      | 46       | 1.17%   |
| 84      | 44       | 1.12%   |
| 40      | 32       | 0.81%   |
| 15      | 31       | 0.79%   |
| 48      | 25       | 0.63%   |
| 54      | 24       | 0.61%   |
| 26      | 19       | 0.48%   |
| 42      | 18       | 0.46%   |
| 29      | 13       | 0.33%   |
| 28      | 13       | 0.33%   |
| 142     | 12       | 0.3%    |
| 49      | 11       | 0.28%   |
| 16      | 11       | 0.28%   |
| 46      | 10       | 0.25%   |
| 52      | 9        | 0.23%   |
| 37      | 8        | 0.2%    |
| 13      | 8        | 0.2%    |
| 65      | 7        | 0.18%   |
| 35      | 6        | 0.15%   |
| 39      | 5        | 0.13%   |
| 30      | 5        | 0.13%   |
| 69      | 4        | 0.1%    |
| 50      | 4        | 0.1%    |
| 43      | 4        | 0.1%    |
| 36      | 4        | 0.1%    |
| 33      | 4        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1707     | 45.86%  |
| 401-500        | 837      | 22.49%  |
| 601-700        | 308      | 8.28%   |
| 701-800        | 234      | 6.29%   |
| 351-400        | 136      | 3.65%   |
| Unknown        | 115      | 3.09%   |
| 1501-2000      | 100      | 2.69%   |
| 1001-1500      | 95       | 2.55%   |
| 301-350        | 89       | 2.39%   |
| 801-900        | 51       | 1.37%   |
| 901-1000       | 26       | 0.7%    |
| More than 2000 | 14       | 0.38%   |
| 201-300        | 10       | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2484     | 71.56%  |
| 16/10   | 438      | 12.62%  |
| 21/9    | 193      | 5.56%   |
| 5/4     | 156      | 4.49%   |
| Unknown | 79       | 2.28%   |
| 4/3     | 52       | 1.5%    |
| 32/9    | 28       | 0.81%   |
| 6/5     | 13       | 0.37%   |
| 1.00    | 12       | 0.35%   |
| 3/2     | 9        | 0.26%   |
| 1.96    | 4        | 0.12%   |
| 3.20    | 1        | 0.03%   |
| 0.89    | 1        | 0.03%   |
| 0.80    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1316     | 34.54%  |
| 301-350        | 755      | 19.82%  |
| 351-500        | 439      | 11.52%  |
| 151-200        | 422      | 11.08%  |
| 251-300        | 273      | 7.17%   |
| More than 1000 | 164      | 4.3%    |
| 141-150        | 144      | 3.78%   |
| 501-1000       | 118      | 3.1%    |
| Unknown        | 115      | 3.02%   |
| 101-110        | 27       | 0.71%   |
| 131-140        | 11       | 0.29%   |
| 111-120        | 6        | 0.16%   |
| 91-100         | 6        | 0.16%   |
| 71-80          | 5        | 0.13%   |
| 121-130        | 5        | 0.13%   |
| 81-90          | 4        | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2107     | 58.54%  |
| 101-120 | 905      | 25.15%  |
| 121-160 | 207      | 5.75%   |
| 1-50    | 148      | 4.11%   |
| 161-240 | 117      | 3.25%   |
| Unknown | 115      | 3.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2359     | 69.3%   |
| 2     | 805      | 23.65%  |
| 0     | 116      | 3.41%   |
| 3     | 105      | 3.08%   |
| 4     | 15       | 0.44%   |
| 5     | 4        | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1923     | 40.48%  |
| Intel                           | 1652     | 34.77%  |
| Qualcomm Atheros                | 272      | 5.73%   |
| Broadcom                        | 126      | 2.65%   |
| TP-Link                         | 96       | 2.02%   |
| Ralink Technology               | 95       | 2%      |
| Microsoft                       | 44       | 0.93%   |
| Aquantia                        | 44       | 0.93%   |
| Ralink                          | 43       | 0.91%   |
| MediaTek                        | 43       | 0.91%   |
| Nvidia                          | 42       | 0.88%   |
| Qualcomm Atheros Communications | 29       | 0.61%   |
| ASUSTek Computer                | 28       | 0.59%   |
| Marvell Technology Group        | 22       | 0.46%   |
| D-Link                          | 22       | 0.46%   |
| Xiaomi                          | 18       | 0.38%   |
| NetGear                         | 18       | 0.38%   |
| Samsung Electronics             | 17       | 0.36%   |
| Edimax Technology               | 15       | 0.32%   |
| ASIX Electronics                | 12       | 0.25%   |
| Huawei Technologies             | 10       | 0.21%   |
| Google                          | 10       | 0.21%   |
| Broadcom Limited                | 10       | 0.21%   |
| Mellanox Technologies           | 9        | 0.19%   |
| D-Link System                   | 9        | 0.19%   |
| Motorola PCS                    | 8        | 0.17%   |
| Linksys                         | 8        | 0.17%   |
| Arduino SA                      | 8        | 0.17%   |
| Belkin Components               | 7        | 0.15%   |
| Apple                           | 7        | 0.15%   |
| ICS Advent                      | 6        | 0.13%   |
| DisplayLink                     | 6        | 0.13%   |
| Qualcomm                        | 5        | 0.11%   |
| AVM                             | 5        | 0.11%   |
| Wilocity                        | 4        | 0.08%   |
| Microchip Technology            | 4        | 0.08%   |
| InterBiometrics                 | 4        | 0.08%   |
| HMD Global                      | 4        | 0.08%   |
| OPPO                            | 3        | 0.06%   |
| OpenMoko                        | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1513     | 27.37%  |
| Intel I211 Gigabit Network Connection                             | 360      | 6.51%   |
| Intel Wi-Fi 6 AX200                                               | 320      | 5.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 208      | 3.76%   |
| Intel Ethernet Connection (2) I219-V                              | 196      | 3.55%   |
| Intel Ethernet Controller I225-V                                  | 136      | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 106      | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 94       | 1.7%    |
| Intel Ethernet Connection (7) I219-V                              | 83       | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 66       | 1.19%   |
| Intel Wireless-AC 9260                                            | 63       | 1.14%   |
| Intel Ethernet Connection (2) I218-V                              | 63       | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 51       | 0.92%   |
| Intel 82574L Gigabit Network Connection                           | 46       | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 45       | 0.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44       | 0.8%    |
| Intel 82579V Gigabit Network Connection                           | 44       | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 43       | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41       | 0.74%   |
| Ralink MT7601U Wireless Adapter                                   | 37       | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 35       | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 35       | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 32       | 0.58%   |
| Intel Wireless 7260                                               | 32       | 0.58%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 32       | 0.58%   |
| Intel Wireless 8260                                               | 30       | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25       | 0.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 25       | 0.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 23       | 0.42%   |
| Intel I210 Gigabit Network Connection                             | 23       | 0.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 23       | 0.42%   |
| Qualcomm Atheros AR9271 802.11n                                   | 22       | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 22       | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 21       | 0.38%   |
| Intel Wireless 7265                                               | 21       | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 20       | 0.36%   |
| Ralink RT5370 Wireless Adapter                                    | 20       | 0.36%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 20       | 0.36%   |
| Intel Wireless 8265 / 8275                                        | 20       | 0.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 19       | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 746      | 43.96%  |
| Realtek Semiconductor                 | 270      | 15.91%  |
| Qualcomm Atheros                      | 144      | 8.49%   |
| Ralink Technology                     | 95       | 5.6%    |
| TP-Link                               | 94       | 5.54%   |
| Broadcom                              | 64       | 3.77%   |
| Ralink                                | 43       | 2.53%   |
| Microsoft                             | 43       | 2.53%   |
| MediaTek                              | 42       | 2.47%   |
| Qualcomm Atheros Communications       | 29       | 1.71%   |
| ASUSTek Computer                      | 26       | 1.53%   |
| D-Link                                | 18       | 1.06%   |
| NetGear                               | 17       | 1%      |
| Edimax Technology                     | 15       | 0.88%   |
| Linksys                               | 8        | 0.47%   |
| Belkin Components                     | 7        | 0.41%   |
| D-Link System                         | 6        | 0.35%   |
| AVM                                   | 5        | 0.29%   |
| Wilocity                              | 4        | 0.24%   |
| Broadcom Limited                      | 3        | 0.18%   |
| Xiaomi                                | 2        | 0.12%   |
| IMC Networks                          | 2        | 0.12%   |
| BUFFALO                               | 2        | 0.12%   |
| AboCom Systems                        | 2        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.12%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.06%   |
| Toshiba                               | 1        | 0.06%   |
| Sitecom Europe                        | 1        | 0.06%   |
| Sierra Wireless                       | 1        | 0.06%   |
| Samsung Electronics                   | 1        | 0.06%   |
| PLANEX                                | 1        | 0.06%   |
| Mercucys                              | 1        | 0.06%   |
| Gemtek                                | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 320      | 18.65%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 94       | 5.48%   |
| Intel Wireless-AC 9260                                         | 63       | 3.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 51       | 2.97%   |
| Ralink MT7601U Wireless Adapter                                | 37       | 2.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 35       | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 32       | 1.86%   |
| Intel Wireless 7260                                            | 32       | 1.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 32       | 1.86%   |
| Intel Wireless 8260                                            | 30       | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25       | 1.46%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 25       | 1.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 23       | 1.34%   |
| Qualcomm Atheros AR9271 802.11n                                | 22       | 1.28%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 21       | 1.22%   |
| Intel Wireless 7265                                            | 21       | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 20       | 1.17%   |
| Ralink RT5370 Wireless Adapter                                 | 20       | 1.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 20       | 1.17%   |
| Intel Wireless 8265 / 8275                                     | 20       | 1.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 19       | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 19       | 1.11%   |
| Realtek 802.11ac NIC                                           | 19       | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19       | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 19       | 1.11%   |
| TP-Link 802.11ac NIC                                           | 18       | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18       | 1.05%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 17       | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 17       | 0.99%   |
| Microsoft Xbox 360 Wireless Adapter                            | 17       | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 17       | 0.99%   |
| Intel Wireless 3165                                            | 17       | 0.99%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 15       | 0.87%   |
| Microsoft XBOX ACC                                             | 14       | 0.82%   |
| Intel Wireless 3160                                            | 13       | 0.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 13       | 0.76%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 12       | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 12       | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 12       | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 12       | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1806     | 50.15%  |
| Intel                                  | 1328     | 36.88%  |
| Qualcomm Atheros                       | 144      | 4%      |
| Broadcom                               | 62       | 1.72%   |
| Aquantia                               | 44       | 1.22%   |
| Nvidia                                 | 42       | 1.17%   |
| Marvell Technology Group               | 22       | 0.61%   |
| Xiaomi                                 | 16       | 0.44%   |
| Samsung Electronics                    | 16       | 0.44%   |
| ASIX Electronics                       | 12       | 0.33%   |
| Google                                 | 10       | 0.28%   |
| Motorola PCS                           | 8        | 0.22%   |
| Mellanox Technologies                  | 8        | 0.22%   |
| Broadcom Limited                       | 7        | 0.19%   |
| Apple                                  | 7        | 0.19%   |
| ICS Advent                             | 6        | 0.17%   |
| DisplayLink                            | 6        | 0.17%   |
| Qualcomm                               | 5        | 0.14%   |
| Huawei Technologies                    | 5        | 0.14%   |
| HMD Global                             | 4        | 0.11%   |
| D-Link                                 | 4        | 0.11%   |
| OPPO                                   | 3        | 0.08%   |
| D-Link System                          | 3        | 0.08%   |
| ADMtek                                 | 3        | 0.08%   |
| VIA Technologies                       | 2        | 0.06%   |
| TP-Link                                | 2        | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.06%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.06%   |
| Lenovo                                 | 2        | 0.06%   |
| Davicom Semiconductor                  | 2        | 0.06%   |
| ASUSTek Computer                       | 2        | 0.06%   |
| Accton Technology                      | 2        | 0.06%   |
| 3Com                                   | 2        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.03%   |
| Xilinx                                 | 1        | 0.03%   |
| vivo                                   | 1        | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.03%   |
| QNAP System                            | 1        | 0.03%   |
| OpenMoko                               | 1        | 0.03%   |
| NetXen Incorporated                    | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1513     | 40.18%  |
| Intel I211 Gigabit Network Connection                                         | 360      | 9.56%   |
| Realtek RTL8125 2.5GbE Controller                                             | 208      | 5.52%   |
| Intel Ethernet Connection (2) I219-V                                          | 196      | 5.2%    |
| Intel Ethernet Controller I225-V                                              | 136      | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 106      | 2.81%   |
| Intel Ethernet Connection (7) I219-V                                          | 83       | 2.2%    |
| Intel Ethernet Connection I217-LM                                             | 66       | 1.75%   |
| Intel Ethernet Connection (2) I218-V                                          | 63       | 1.67%   |
| Intel 82574L Gigabit Network Connection                                       | 46       | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                                         | 45       | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 44       | 1.17%   |
| Intel 82579V Gigabit Network Connection                                       | 44       | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 43       | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 41       | 1.09%   |
| Intel Ethernet Connection I217-V                                              | 35       | 0.93%   |
| Intel I210 Gigabit Network Connection                                         | 23       | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 23       | 0.61%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 22       | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 19       | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 19       | 0.5%    |
| Nvidia MCP61 Ethernet                                                         | 19       | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 16       | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 15       | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 15       | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                                         | 15       | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 14       | 0.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 14       | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 12       | 0.32%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]           | 12       | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 11       | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 11       | 0.29%   |
| Intel 82578DM Gigabit Network Connection                                      | 11       | 0.29%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11       | 0.29%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 11       | 0.29%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 11       | 0.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 10       | 0.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 10       | 0.27%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 10       | 0.27%   |
| Intel Ethernet Connection (2) I218-LM                                         | 9        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3269     | 66.82%  |
| WiFi     | 1578     | 32.26%  |
| Modem    | 40       | 0.82%   |
| Unknown  | 5        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2636     | 75.44%  |
| WiFi     | 858      | 24.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1919     | 57.47%  |
| 2     | 1142     | 34.2%   |
| 3     | 209      | 6.26%   |
| 4     | 26       | 0.78%   |
| 0     | 19       | 0.57%   |
| 5     | 15       | 0.45%   |
| 6     | 6        | 0.18%   |
| 9     | 2        | 0.06%   |
| 8     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 2790     | 82.76%  |
| Yes     | 578      | 17.15%  |
| Unknown | 3        | 0.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 696      | 49.08%  |
| Cambridge Silicon Radio         | 308      | 21.72%  |
| ASUSTek Computer                | 105      | 7.4%    |
| Realtek Semiconductor           | 75       | 5.29%   |
| Broadcom                        | 72       | 5.08%   |
| Qualcomm Atheros Communications | 31       | 2.19%   |
| MediaTek                        | 24       | 1.69%   |
| TP-Link                         | 22       | 1.55%   |
| IMC Networks                    | 18       | 1.27%   |
| Apple                           | 15       | 1.06%   |
| Foxconn / Hon Hai               | 8        | 0.56%   |
| Belkin Components               | 7        | 0.49%   |
| HTC (High Tech Computer)        | 6        | 0.42%   |
| Edimax Technology               | 6        | 0.42%   |
| Lite-On Technology              | 4        | 0.28%   |
| Integrated System Solution      | 4        | 0.28%   |
| Dynex                           | 4        | 0.28%   |
| Dell                            | 3        | 0.21%   |
| Toshiba                         | 2        | 0.14%   |
| SINO WEALTH                     | 2        | 0.14%   |
| Hewlett-Packard                 | 2        | 0.14%   |
| Kensington                      | 1        | 0.07%   |
| D-Link System                   | 1        | 0.07%   |
| Creative Technology             | 1        | 0.07%   |
| BUFFALO                         | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 308      | 21.64%  |
| Intel AX200 Bluetooth                                                | 301      | 21.15%  |
| Intel Bluetooth wireless interface                                   | 122      | 8.57%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 93       | 6.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 59       | 4.15%   |
| Realtek Bluetooth Radio                                              | 55       | 3.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 50       | 3.51%   |
| Intel AX210 Bluetooth                                                | 48       | 3.37%   |
| Intel AX201 Bluetooth                                                | 43       | 3.02%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 41       | 2.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 26       | 1.83%   |
| MediaTek Wireless_Device                                             | 24       | 1.69%   |
| TP-Link TPuLink UB500 Adapter                                        | 22       | 1.55%   |
| ASUS Bluetooth Radio                                                 | 19       | 1.34%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 13       | 0.91%   |
| ASUS Bluetooth Adapter                                               | 13       | 0.91%   |
| ASUS ASUS USB-BT500                                                  | 11       | 0.77%   |
| Qualcomm Atheros  Bluetooth Device                                   | 9        | 0.63%   |
| Apple Bluetooth USB Host Controller                                  | 9        | 0.63%   |
| ASUS BCM20702A0                                                      | 8        | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 7        | 0.49%   |
| IMC Networks Bluetooth Radio                                         | 7        | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                                    | 7        | 0.49%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 6        | 0.42%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 6        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.42%   |
| ASUS Bluetooth Device                                                | 6        | 0.42%   |
| Realtek RTL8821A Bluetooth                                           | 5        | 0.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 5        | 0.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 5        | 0.35%   |
| IMC Networks Bluetooth Device                                        | 5        | 0.35%   |
| Edimax Bluetooth Adapter                                             | 5        | 0.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4        | 0.28%   |
| Lite-On Bluetooth Device                                             | 4        | 0.28%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 0.28%   |
| Intel Bluetooth Device                                               | 4        | 0.28%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 4        | 0.28%   |
| Broadcom BCM2045 Bluetooth                                           | 4        | 0.28%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 4        | 0.28%   |
| Integrated System Solution Bluetooth Device                          | 3        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1799     | 29.13%  |
| Intel                                | 1765     | 28.58%  |
| Nvidia                               | 1390     | 22.51%  |
| C-Media Electronics                  | 212      | 3.43%   |
| Logitech                             | 101      | 1.64%   |
| Creative Labs                        | 68       | 1.1%    |
| SteelSeries ApS                      | 42       | 0.68%   |
| Kingston Technology                  | 42       | 0.68%   |
| JMTek                                | 40       | 0.65%   |
| Focusrite-Novation                   | 40       | 0.65%   |
| Texas Instruments                    | 39       | 0.63%   |
| Corsair                              | 38       | 0.62%   |
| Razer USA                            | 37       | 0.6%    |
| Creative Technology                  | 35       | 0.57%   |
| Generalplus Technology               | 26       | 0.42%   |
| ASUSTek Computer                     | 25       | 0.4%    |
| Blue Microphones                     | 24       | 0.39%   |
| Plantronics                          | 23       | 0.37%   |
| GN Netcom                            | 21       | 0.34%   |
| GYROCOM C&C                          | 19       | 0.31%   |
| Sony                                 | 17       | 0.28%   |
| Samson Technologies                  | 15       | 0.24%   |
| Realtek Semiconductor                | 15       | 0.24%   |
| XMOS                                 | 13       | 0.21%   |
| RODE Microphones                     | 12       | 0.19%   |
| Giga-Byte Technology                 | 12       | 0.19%   |
| Tenx Technology                      | 11       | 0.18%   |
| Micro Star International             | 10       | 0.16%   |
| DSEA A/S                             | 10       | 0.16%   |
| Cambridge Silicon Radio              | 10       | 0.16%   |
| VIA Technologies                     | 9        | 0.15%   |
| Dell                                 | 9        | 0.15%   |
| Schiit Audio                         | 8        | 0.13%   |
| SAVITECH                             | 8        | 0.13%   |
| Lenovo                               | 7        | 0.11%   |
| FiiO Electronics Technology          | 7        | 0.11%   |
| Yamaha                               | 6        | 0.1%    |
| Thesycon Systemsoftware & Consulting | 6        | 0.1%    |
| PreSonus Audio Electronics           | 6        | 0.1%    |
| M-Audio                              | 6        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 556      | 7.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 307      | 4.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 281      | 3.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 227      | 3.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 224      | 3.05%   |
| Intel 200 Series PCH HD Audio                                              | 205      | 2.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 194      | 2.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 184      | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 181      | 2.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 155      | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 154      | 2.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 149      | 2.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 143      | 1.95%   |
| AMD Navi 10 HDMI Audio                                                     | 141      | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 140      | 1.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 127      | 1.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 127      | 1.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 97       | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                              | 96       | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 95       | 1.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 94       | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 93       | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 91       | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 88       | 1.2%    |
| AMD FCH Azalia Controller                                                  | 78       | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                              | 72       | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 72       | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 62       | 0.85%   |
| Nvidia TU104 HD Audio Controller                                           | 61       | 0.83%   |
| Intel Alder Lake-S HD Audio Controller                                     | 60       | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 59       | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 55       | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                              | 55       | 0.75%   |
| Nvidia GA104 High Definition Audio Controller                              | 55       | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                              | 54       | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 54       | 0.74%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 48       | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                              | 47       | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 45       | 0.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 41       | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 346      | 19.41%  |
| Corsair                      | 300      | 16.83%  |
| G.Skill                      | 223      | 12.51%  |
| Unknown                      | 190      | 10.66%  |
| Crucial                      | 145      | 8.13%   |
| Samsung Electronics          | 130      | 7.29%   |
| SK hynix                     | 128      | 7.18%   |
| Micron Technology            | 76       | 4.26%   |
| A-DATA Technology            | 36       | 2.02%   |
| Team                         | 32       | 1.79%   |
| Patriot                      | 32       | 1.79%   |
| Ramaxel Technology           | 13       | 0.73%   |
| Nanya Technology             | 13       | 0.73%   |
| Unknown                      | 13       | 0.73%   |
| Elpida                       | 9        | 0.5%    |
| GOODRAM                      | 7        | 0.39%   |
| GeIL                         | 6        | 0.34%   |
| Transcend                    | 5        | 0.28%   |
| Smart                        | 5        | 0.28%   |
| Silicon Power                | 5        | 0.28%   |
| AMD                          | 5        | 0.28%   |
| Qimonda                      | 4        | 0.22%   |
| PNY                          | 4        | 0.22%   |
| Avant                        | 4        | 0.22%   |
| Qumo                         | 3        | 0.17%   |
| Apacer                       | 3        | 0.17%   |
| Unifosa                      | 2        | 0.11%   |
| OCZ                          | 2        | 0.11%   |
| MINPO                        | 2        | 0.11%   |
| Goldkey                      | 2        | 0.11%   |
| Golden Empire                | 2        | 0.11%   |
| Gold Key                     | 2        | 0.11%   |
| CSX                          | 2        | 0.11%   |
| zApacer                      | 1        | 0.06%   |
| V-GeN                        | 1        | 0.06%   |
| V-Color                      | 1        | 0.06%   |
| Unknown (ABCD)               | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (9B)                 | 1        | 0.06%   |
| Unknown (0xF7F7F7F7F7F7E300) | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 34       | 1.75%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s   | 24       | 1.24%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 19       | 0.98%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 17       | 0.88%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 17       | 0.88%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 15       | 0.77%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 14       | 0.72%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 14       | 0.72%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 13       | 0.67%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 13       | 0.67%   |
| Unknown                                                 | 13       | 0.67%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s | 11       | 0.57%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 11       | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 10       | 0.52%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s      | 10       | 0.52%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 10       | 0.52%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s  | 10       | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 9        | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 9        | 0.46%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s     | 9        | 0.46%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 8        | 0.41%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s     | 8        | 0.41%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 8        | 0.41%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 8        | 0.41%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s      | 8        | 0.41%   |
| G.Skill RAM F4-2400C15-8GVR . 8GB DIMM DDR4 3200MT/s    | 8        | 0.41%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s   | 8        | 0.41%   |
| SK hynix RAM HMT451U6BFR8C-PB 4096MB DIMM DDR3 1600MT/s | 7        | 0.36%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 7        | 0.36%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s       | 7        | 0.36%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 7        | 0.36%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s  | 7        | 0.36%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s  | 7        | 0.36%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 6        | 0.31%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 6        | 0.31%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 6        | 0.31%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s     | 6        | 0.31%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s  | 6        | 0.31%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 6        | 0.31%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s   | 6        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 912      | 57.29%  |
| DDR3    | 460      | 28.89%  |
| Unknown | 85       | 5.34%   |
| DDR2    | 60       | 3.77%   |
| SDRAM   | 36       | 2.26%   |
| DDR5    | 25       | 1.57%   |
| DDR     | 10       | 0.63%   |
| LPDDR3  | 3        | 0.19%   |
| LPDDR4  | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1495     | 94.98%  |
| SODIMM       | 66       | 4.19%   |
| RIMM         | 8        | 0.51%   |
| FB-DIMM      | 3        | 0.19%   |
| Row Of Chips | 2        | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 705      | 41.25%  |
| 16384 | 357      | 20.89%  |
| 4096  | 354      | 20.71%  |
| 2048  | 160      | 9.36%   |
| 32768 | 92       | 5.38%   |
| 1024  | 36       | 2.11%   |
| 512   | 4        | 0.23%   |
| 256   | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 265      | 15.19%  |
| 3200    | 206      | 11.81%  |
| 3600    | 165      | 9.46%   |
| 1333    | 147      | 8.43%   |
| 2400    | 119      | 6.82%   |
| 2133    | 93       | 5.33%   |
| 2667    | 76       | 4.36%   |
| 800     | 56       | 3.21%   |
| 3400    | 48       | 2.75%   |
| 3000    | 48       | 2.75%   |
| 3466    | 45       | 2.58%   |
| 667     | 39       | 2.24%   |
| 1867    | 37       | 2.12%   |
| 3800    | 28       | 1.61%   |
| 2666    | 28       | 1.61%   |
| 3733    | 26       | 1.49%   |
| 1866    | 23       | 1.32%   |
| 3866    | 22       | 1.26%   |
| Unknown | 22       | 1.26%   |
| 2800    | 21       | 1.2%    |
| 2933    | 20       | 1.15%   |
| 1066    | 18       | 1.03%   |
| 4800    | 15       | 0.86%   |
| 3266    | 15       | 0.86%   |
| 1800    | 15       | 0.86%   |
| 3666    | 11       | 0.63%   |
| 1067    | 10       | 0.57%   |
| 3333    | 8        | 0.46%   |
| 3100    | 8        | 0.46%   |
| 1334    | 8        | 0.46%   |
| 5200    | 6        | 0.34%   |
| 533     | 6        | 0.34%   |
| 3334    | 5        | 0.29%   |
| 2733    | 5        | 0.29%   |
| 2000    | 5        | 0.29%   |
| 400     | 5        | 0.29%   |
| 3151    | 4        | 0.23%   |
| 333     | 4        | 0.23%   |
| 4400    | 3        | 0.17%   |
| 4000    | 3        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 60       | 39.22%  |
| Brother Industries    | 38       | 24.84%  |
| Canon                 | 16       | 10.46%  |
| Samsung Electronics   | 11       | 7.19%   |
| Seiko Epson           | 9        | 5.88%   |
| Prolific Technology   | 5        | 3.27%   |
| Lexmark International | 4        | 2.61%   |
| Xerox                 | 2        | 1.31%   |
| Kyocera               | 2        | 1.31%   |
| Star Micronics        | 1        | 0.65%   |
| QinHeng Electronics   | 1        | 0.65%   |
| Graphtec America      | 1        | 0.65%   |
| Dymo-CoStar           | 1        | 0.65%   |
| Dell                  | 1        | 0.65%   |
| Boca Systems          | 1        | 0.65%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                | 5        | 3.25%   |
| Samsung M2070 Series                         | 4        | 2.6%    |
| HP LaserJet Professional P 1102w             | 4        | 2.6%    |
| Brother HL-L2340D series                     | 4        | 2.6%    |
| HP ENVY 5000 series                          | 3        | 1.95%   |
| HP ENVY 4520 series                          | 3        | 1.95%   |
| HP DeskJet F300 series                       | 3        | 1.95%   |
| Brother Printer                              | 3        | 1.95%   |
| Brother HL-1110 series                       | 3        | 1.95%   |
| Seiko Epson Printer                          | 2        | 1.3%    |
| Samsung ML-216x Series Laser Printer         | 2        | 1.3%    |
| HP OfficeJet 6950                            | 2        | 1.3%    |
| HP DeskJet 3700 series                       | 2        | 1.3%    |
| HP DeskJet 3630 series                       | 2        | 1.3%    |
| HP DeskJet 2620 All-in-One Printer           | 2        | 1.3%    |
| HP DeskJet 2130 series                       | 2        | 1.3%    |
| Canon TS3300 series                          | 2        | 1.3%    |
| Canon TR4500 series                          | 2        | 1.3%    |
| Canon CanoScan LiDE 300                      | 2        | 1.3%    |
| Brother MFC-9330CDW                          | 2        | 1.3%    |
| Brother HL-2230 series                       | 2        | 1.3%    |
| Xerox Phaser 6500DN                          | 1        | 0.65%   |
| Xerox Phaser 3010                            | 1        | 0.65%   |
| Star Micronics TUP592 (STR_T-001)            | 1        | 0.65%   |
| Seiko Epson XP-100 Series                    | 1        | 0.65%   |
| Seiko Epson WF-2510 Series                   | 1        | 0.65%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.65%   |
| Seiko Epson L3110 Series                     | 1        | 0.65%   |
| Seiko Epson L300 Series                      | 1        | 0.65%   |
| Seiko Epson L220 Series                      | 1        | 0.65%   |
| Seiko Epson L100 Series                      | 1        | 0.65%   |
| Samsung Xerox Phaser 3117 Laser Printer      | 1        | 0.65%   |
| Samsung SCX-4300 Series                      | 1        | 0.65%   |
| Samsung ML-2855 Series                       | 1        | 0.65%   |
| Samsung ML-2010P Mono Laser Printer          | 1        | 0.65%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 0.65%   |
| QinHeng CH340S                               | 1        | 0.65%   |
| Lexmark International Lexmark MS521dn        | 1        | 0.65%   |
| Lexmark International Laser Printer E232     | 1        | 0.65%   |
| Lexmark International B2236dw                | 1        | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 22       | 57.89%  |
| Seiko Epson     | 10       | 26.32%  |
| Hewlett-Packard | 4        | 10.53%  |
| UMAX            | 1        | 2.63%   |
| Mustek Systems  | 1        | 2.63%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                   | 4        | 10.53%  |
| Canon CanoScan LiDE 210                                 | 4        | 10.53%  |
| Canon CanoScan LIDE 25                                  | 3        | 7.89%   |
| Canon CanoScan LiDE 220                                 | 3        | 7.89%   |
| Canon CanoScan LiDE 100                                 | 3        | 7.89%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2        | 5.26%   |
| Canon CanoScan LiDE 110                                 | 2        | 5.26%   |
| UMAX Astra 2200/2200SU                                  | 1        | 2.63%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1        | 2.63%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1        | 2.63%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 2.63%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]             | 1        | 2.63%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1        | 2.63%   |
| Seiko Epson GT-6600U [Perfection 610]                   | 1        | 2.63%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1        | 2.63%   |
| HP ScanJet G4050                                        | 1        | 2.63%   |
| HP ScanJet 5590                                         | 1        | 2.63%   |
| HP ScanJet 3400cse                                      | 1        | 2.63%   |
| HP ScanJet 2400c                                        | 1        | 2.63%   |
| Canon CanoScan N1240U/LiDE 30                           | 1        | 2.63%   |
| Canon CanoScan LiDE 70                                  | 1        | 2.63%   |
| Canon CanoScan LiDE 200                                 | 1        | 2.63%   |
| Canon CanoScan LiDE 120                                 | 1        | 2.63%   |
| Canon CanoScan 4400F                                    | 1        | 2.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 390      | 45.61%  |
| Microsoft                     | 70       | 8.19%   |
| Microdia                      | 50       | 5.85%   |
| Apple                         | 31       | 3.63%   |
| Samsung Electronics           | 29       | 3.39%   |
| Sunplus Innovation Technology | 27       | 3.16%   |
| KYE Systems (Mouse Systems)   | 20       | 2.34%   |
| Realtek Semiconductor         | 18       | 2.11%   |
| Creative Technology           | 15       | 1.75%   |
| Chicony Electronics           | 15       | 1.75%   |
| Generalplus Technology        | 12       | 1.4%    |
| Cubeternet                    | 12       | 1.4%    |
| ARC International             | 10       | 1.17%   |
| Z-Star Microelectronics       | 9        | 1.05%   |
| 2M UVC CAMERA                 | 9        | 1.05%   |
| Jieli Technology              | 8        | 0.94%   |
| Razer USA                     | 7        | 0.82%   |
| Lenovo                        | 7        | 0.82%   |
| Hewlett-Packard               | 7        | 0.82%   |
| GEMBIRD                       | 7        | 0.82%   |
| Trust                         | 6        | 0.7%    |
| MacroSilicon                  | 6        | 0.7%    |
| LG Electronics                | 5        | 0.58%   |
| AVerMedia Technologies        | 5        | 0.58%   |
| Arkmicro Technologies         | 5        | 0.58%   |
| Unknown                       | 4        | 0.47%   |
| Aveo Technology               | 4        | 0.47%   |
| OmniVision Technologies       | 3        | 0.35%   |
| Huawei Technologies           | 3        | 0.35%   |
| Genesys Logic                 | 3        | 0.35%   |
| Alcor Micro                   | 3        | 0.35%   |
| A4Tech                        | 3        | 0.35%   |
| Valve Software                | 2        | 0.23%   |
| SunplusIT                     | 2        | 0.23%   |
| Sunplus IT                    | 2        | 0.23%   |
| Sonix Technology              | 2        | 0.23%   |
| SJ-180517-N                   | 2        | 0.23%   |
| Linux Foundation              | 2        | 0.23%   |
| Intel                         | 2        | 0.23%   |
| HD WEBCAM                     | 2        | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 92       | 10.6%   |
| Logitech Webcam C270                       | 86       | 9.91%   |
| Samsung Galaxy A5 (MTP)                    | 28       | 3.23%   |
| Logitech HD Webcam C525                    | 28       | 3.23%   |
| Apple iPhone 5/5C/5S/6/SE                  | 26       | 3%      |
| Microsoft LifeCam HD-3000                  | 25       | 2.88%   |
| Microdia Webcam Vitade AF                  | 21       | 2.42%   |
| Logitech C922 Pro Stream Webcam            | 20       | 2.3%    |
| Microsoft LifeCam Cinema                   | 17       | 1.96%   |
| Logitech Webcam C310                       | 16       | 1.84%   |
| Logitech HD Webcam C615                    | 16       | 1.84%   |
| Logitech Webcam Pro 9000                   | 14       | 1.61%   |
| Logitech Webcam C170                       | 13       | 1.5%    |
| Logitech BRIO Ultra HD Webcam              | 12       | 1.38%   |
| Logitech Webcam C930e                      | 11       | 1.27%   |
| Logitech Webcam C925e                      | 11       | 1.27%   |
| Realtek FULL HD 1080P Webcam               | 10       | 1.15%   |
| ARC International Camera                   | 10       | 1.15%   |
| Logitech StreamCam                         | 9        | 1.04%   |
| Logitech C920 PRO HD Webcam                | 9        | 1.04%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam       | 9        | 1.04%   |
| Sunplus HD 720P webcam                     | 8        | 0.92%   |
| Microdia CameraA                           | 8        | 0.92%   |
| Logitech QuickCam Pro 9000                 | 8        | 0.92%   |
| Jieli USB PHY 2.0                          | 8        | 0.92%   |
| Microdia Camera                            | 7        | 0.81%   |
| Microsoft LifeCam VX-5000                  | 6        | 0.69%   |
| Logitech BRIO 4K Stream Edition            | 6        | 0.69%   |
| Razer USA Razer Kiyo                       | 5        | 0.58%   |
| Microsoft LifeCam Studio                   | 5        | 0.58%   |
| Microdia USB 2.0 Camera                    | 5        | 0.58%   |
| MacroSilicon USB Video                     | 5        | 0.58%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 5        | 0.58%   |
| Generalplus GENERAL WEBCAM                 | 5        | 0.58%   |
| Creative Live! Cam Sync HD [VF0770]        | 5        | 0.58%   |
| Creative Live! Cam Sync 1080p              | 5        | 0.58%   |
| Sunplus Canyon CNS CWC5 Webcam             | 4        | 0.46%   |
| Realtek NexiGo N960E FHD Webcam            | 4        | 0.46%   |
| Microsoft MicrosoftÂ LifeCam Cinema       | 4        | 0.46%   |
| Microsoft LifeCam VX-500 [1357]            | 4        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 20%     |
| Elan Microelectronics | 2        | 20%     |
| DigitalPersona        | 2        | 20%     |
| Synaptics             | 1        | 10%     |
| Microsoft             | 1        | 10%     |
| Dell                  | 1        | 10%     |
| AuthenTec             | 1        | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 2        | 20%     |
| DigitalPersona Fingerprint Reader              | 2        | 20%     |
| Synaptics  WBDI Fingerprint Reader - USB 052   | 1        | 10%     |
| Microsoft Fingerprint Reader                   | 1        | 10%     |
| LighTuning Fingerprint Sensor                  | 1        | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor    | 1        | 10%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 10%     |
| AuthenTec AES1600                              | 1        | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 5        | 14.71%  |
| Alcor Micro                       | 5        | 14.71%  |
| SCM Microsystems                  | 4        | 11.76%  |
| Realtek Semiconductor             | 4        | 11.76%  |
| VASCO Data Security International | 3        | 8.82%   |
| OmniKey                           | 3        | 8.82%   |
| Gemalto (was Gemplus)             | 2        | 5.88%   |
| Aktiv                             | 2        | 5.88%   |
| Fujitsu Siemens Computers         | 1        | 2.94%   |
| Feitian Technologies              | 1        | 2.94%   |
| Clay Logic                        | 1        | 2.94%   |
| Chicony Electronics               | 1        | 2.94%   |
| Cherry                            | 1        | 2.94%   |
| Advanced Card Systems             | 1        | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 11.76%  |
| Yubico.com Yubikey 4 U2F+CCID                                   | 3        | 8.82%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 3        | 8.82%   |
| Alcor Micro AU9540 Smartcard Reader                             | 3        | 8.82%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 5.88%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 2        | 5.88%   |
| Alcor Micro Watchdata W 1981                                    | 2        | 5.88%   |
| Aktiv Rutoken lite                                              | 2        | 5.88%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                             | 1        | 2.94%   |
| Yubico.com Yubikey 4/5 CCID                                     | 1        | 2.94%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 2.94%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader      | 1        | 2.94%   |
| OmniKey CardMan 3121 (HID Technologies)                         | 1        | 2.94%   |
| OmniKey CardMan 3021 / 3121                                     | 1        | 2.94%   |
| OmniKey CardMan 1021                                            | 1        | 2.94%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                   | 1        | 2.94%   |
| Feitian Technologies FT SCR310                                  | 1        | 2.94%   |
| Clay Logic Nitrokey Pro                                         | 1        | 2.94%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 1        | 2.94%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 2.94%   |
| Advanced Card Systems ACR122U                                   | 1        | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2886     | 85.69%  |
| 1     | 418      | 12.41%  |
| 2     | 43       | 1.28%   |
| 3     | 10       | 0.3%    |
| 4     | 5        | 0.15%   |
| 5     | 4        | 0.12%   |
| 8     | 1        | 0.03%   |
| 6     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 159      | 29.55%  |
| Graphics card            | 143      | 26.58%  |
| Unassigned class         | 53       | 9.85%   |
| Sound                    | 32       | 5.95%   |
| Multimedia controller    | 28       | 5.2%    |
| Communication controller | 28       | 5.2%    |
| Camera                   | 28       | 5.2%    |
| Storage/raid             | 11       | 2.04%   |
| Network                  | 10       | 1.86%   |
| Fingerprint reader       | 9        | 1.67%   |
| Bluetooth                | 9        | 1.67%   |
| Net/ethernet             | 5        | 0.93%   |
| Modem                    | 5        | 0.93%   |
| Chipcard                 | 5        | 0.93%   |
| Card reader              | 5        | 0.93%   |
| Firewire controller      | 2        | 0.37%   |
| Dvb card                 | 2        | 0.37%   |
| Wireless                 | 1        | 0.19%   |
| Tv card                  | 1        | 0.19%   |
| Storage/ata              | 1        | 0.19%   |
| Storage                  | 1        | 0.19%   |

