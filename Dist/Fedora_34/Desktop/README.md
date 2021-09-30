Fedora 34 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 34.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-34

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MEG X570 UNIFY              | [98852179e1](https://linux-hardware.org/?probe=98852179e1) | Sep 30, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1e96ea621f](https://linux-hardware.org/?probe=1e96ea621f) | Sep 29, 2021 |
| ASUSTek       | P7H55-M LX                  | [a47ae6e7b0](https://linux-hardware.org/?probe=a47ae6e7b0) | Sep 29, 2021 |
| Gigabyte      | GA-MA69GM-S2H               | [b1f14324be](https://linux-hardware.org/?probe=b1f14324be) | Sep 29, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [40295a8f09](https://linux-hardware.org/?probe=40295a8f09) | Sep 29, 2021 |
| HP            | 1998                        | [bb31e60922](https://linux-hardware.org/?probe=bb31e60922) | Sep 28, 2021 |
| ASRock        | H170M Pro4                  | [062fe3bada](https://linux-hardware.org/?probe=062fe3bada) | Sep 28, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [9682e59e98](https://linux-hardware.org/?probe=9682e59e98) | Sep 28, 2021 |
| Foxconn       | 2ABF                        | [2acf5e4c6d](https://linux-hardware.org/?probe=2acf5e4c6d) | Sep 28, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| HP            | 8053                        | [e74bf378e7](https://linux-hardware.org/?probe=e74bf378e7) | Sep 27, 2021 |
| ECS           | H61H2-CM                    | [4571e36b80](https://linux-hardware.org/?probe=4571e36b80) | Sep 26, 2021 |
| Gigabyte      | EP45-DS3L                   | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASUSTek       | H110M-CS/BR                 | [1c65589814](https://linux-hardware.org/?probe=1c65589814) | Sep 26, 2021 |
| HP            | 8056                        | [a87f2d61fc](https://linux-hardware.org/?probe=a87f2d61fc) | Sep 26, 2021 |
| Gigabyte      | H81M-S2H                    | [4199c35f38](https://linux-hardware.org/?probe=4199c35f38) | Sep 25, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [08d8affc67](https://linux-hardware.org/?probe=08d8affc67) | Sep 25, 2021 |
| MSI           | MAG B550M BAZOOKA           | [d06dd7e0ec](https://linux-hardware.org/?probe=d06dd7e0ec) | Sep 25, 2021 |
| ASUSTek       | GD30CI                      | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [aa7607a2b7](https://linux-hardware.org/?probe=aa7607a2b7) | Sep 24, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [6dad1e6449](https://linux-hardware.org/?probe=6dad1e6449) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [4688937b63](https://linux-hardware.org/?probe=4688937b63) | Sep 24, 2021 |
| ASUSTek       | H81M-E R2.0                 | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| HP            | 0B4Ch D                     | [f56bf148bf](https://linux-hardware.org/?probe=f56bf148bf) | Sep 24, 2021 |
| ASRock        | Z390 Pro4                   | [7ab201b716](https://linux-hardware.org/?probe=7ab201b716) | Sep 24, 2021 |
| MSI           | X570-A PRO                  | [9813ead17b](https://linux-hardware.org/?probe=9813ead17b) | Sep 23, 2021 |
| MSI           | Z370-A PRO                  | [694fab3776](https://linux-hardware.org/?probe=694fab3776) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-A               | [c4a94c7628](https://linux-hardware.org/?probe=c4a94c7628) | Sep 23, 2021 |
| ASUSTek       | P8H61-M LX                  | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| System76      | Thelio Mira thelio-mira-... | [f6580e7358](https://linux-hardware.org/?probe=f6580e7358) | Sep 22, 2021 |
| ASUSTek       | X99-S                       | [454c9e999e](https://linux-hardware.org/?probe=454c9e999e) | Sep 22, 2021 |
| Dell          | 05XGC8 A01                  | [ea9f525cf5](https://linux-hardware.org/?probe=ea9f525cf5) | Sep 22, 2021 |
| Dell          | 0GC080                      | [0297b84b90](https://linux-hardware.org/?probe=0297b84b90) | Sep 22, 2021 |
| Dell          | 0GC080                      | [d66102b7f1](https://linux-hardware.org/?probe=d66102b7f1) | Sep 22, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [50bccc87d3](https://linux-hardware.org/?probe=50bccc87d3) | Sep 21, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [9f131c2aec](https://linux-hardware.org/?probe=9f131c2aec) | Sep 21, 2021 |
| MSI           | E3M WORKSTATION V5          | [6924705831](https://linux-hardware.org/?probe=6924705831) | Sep 20, 2021 |
| ASUSTek       | PRIME X399-A                | [edd8b3c5b2](https://linux-hardware.org/?probe=edd8b3c5b2) | Sep 20, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [a460a3a6fb](https://linux-hardware.org/?probe=a460a3a6fb) | Sep 19, 2021 |
| HP            | 8055                        | [12a1144916](https://linux-hardware.org/?probe=12a1144916) | Sep 18, 2021 |
| HP            | 8055                        | [0404bcffca](https://linux-hardware.org/?probe=0404bcffca) | Sep 18, 2021 |
| MSI           | E3M WORKSTATION V5          | [d1d3f1ae4b](https://linux-hardware.org/?probe=d1d3f1ae4b) | Sep 18, 2021 |
| HP            | 8056                        | [9431176663](https://linux-hardware.org/?probe=9431176663) | Sep 17, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [ceba17a8cc](https://linux-hardware.org/?probe=ceba17a8cc) | Sep 16, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [4a7b56da33](https://linux-hardware.org/?probe=4a7b56da33) | Sep 16, 2021 |
| ASUSTek       | P8Z77-V LK                  | [203e58b1d1](https://linux-hardware.org/?probe=203e58b1d1) | Sep 16, 2021 |
| MSI           | B85-G43 GAMING              | [da6e58ed2a](https://linux-hardware.org/?probe=da6e58ed2a) | Sep 16, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [ad193a0b9c](https://linux-hardware.org/?probe=ad193a0b9c) | Sep 16, 2021 |
| ASRock        | H170M Pro4                  | [7d604a0a22](https://linux-hardware.org/?probe=7d604a0a22) | Sep 15, 2021 |
| Gigabyte      | G41MT-D3                    | [ccacfc0b86](https://linux-hardware.org/?probe=ccacfc0b86) | Sep 15, 2021 |
| ECS           | G41T-M7                     | [42e72694fc](https://linux-hardware.org/?probe=42e72694fc) | Sep 15, 2021 |
| Dell          | 0GC080                      | [e7be152af1](https://linux-hardware.org/?probe=e7be152af1) | Sep 15, 2021 |
| EVGA          | 111-SS-E172                 | [b9c8f1f9e8](https://linux-hardware.org/?probe=b9c8f1f9e8) | Sep 15, 2021 |
| Gigabyte      | EP45-DS3L                   | [ddf06500d6](https://linux-hardware.org/?probe=ddf06500d6) | Sep 14, 2021 |
| ASRock        | X570M Pro4                  | [297bbaf6a4](https://linux-hardware.org/?probe=297bbaf6a4) | Sep 14, 2021 |
| Gigabyte      | G41MT-D3                    | [3983c92565](https://linux-hardware.org/?probe=3983c92565) | Sep 14, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [8dcc482baf](https://linux-hardware.org/?probe=8dcc482baf) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [e0948f8a85](https://linux-hardware.org/?probe=e0948f8a85) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [981d2b7173](https://linux-hardware.org/?probe=981d2b7173) | Sep 14, 2021 |
| ASRock        | H170M Pro4                  | [59ab06bdda](https://linux-hardware.org/?probe=59ab06bdda) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [1fa62f847b](https://linux-hardware.org/?probe=1fa62f847b) | Sep 14, 2021 |
| ASUSTek       | SABERTOOTH X79              | [79242cc1bb](https://linux-hardware.org/?probe=79242cc1bb) | Sep 13, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [66154dd009](https://linux-hardware.org/?probe=66154dd009) | Sep 13, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [0b058e8bd8](https://linux-hardware.org/?probe=0b058e8bd8) | Sep 13, 2021 |
| Acer          | Aspire X3470                | [1a3f77423d](https://linux-hardware.org/?probe=1a3f77423d) | Sep 13, 2021 |
| Acer          | Aspire X3470                | [f53f569155](https://linux-hardware.org/?probe=f53f569155) | Sep 13, 2021 |
| HP            | 1587h                       | [5447d2e6c3](https://linux-hardware.org/?probe=5447d2e6c3) | Sep 12, 2021 |
| ASRock        | AD2700-ITX                  | [3f1fade2ca](https://linux-hardware.org/?probe=3f1fade2ca) | Sep 12, 2021 |
| Gigabyte      | B150M-D3H-CF                | [d13739db96](https://linux-hardware.org/?probe=d13739db96) | Sep 11, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [bea54b0e05](https://linux-hardware.org/?probe=bea54b0e05) | Sep 11, 2021 |
| Intel         | DG41RQ AAE54511-201         | [14957a27ad](https://linux-hardware.org/?probe=14957a27ad) | Sep 11, 2021 |
| Intel         | DG41RQ AAE54511-201         | [f525bfb156](https://linux-hardware.org/?probe=f525bfb156) | Sep 11, 2021 |
| Gigabyte      | B85M-D3V-A                  | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [bbfc6ac323](https://linux-hardware.org/?probe=bbfc6ac323) | Sep 10, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [2f73a651d4](https://linux-hardware.org/?probe=2f73a651d4) | Sep 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [74d478552c](https://linux-hardware.org/?probe=74d478552c) | Sep 10, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [afb539ff26](https://linux-hardware.org/?probe=afb539ff26) | Sep 10, 2021 |
| ASUSTek       | AM1M-A                      | [ab6a989deb](https://linux-hardware.org/?probe=ab6a989deb) | Sep 09, 2021 |
| Gigabyte      | X99-Gaming 5                | [0a8ee7324e](https://linux-hardware.org/?probe=0a8ee7324e) | Sep 09, 2021 |
| ASUSTek       | AM1M-A                      | [bc4f850240](https://linux-hardware.org/?probe=bc4f850240) | Sep 09, 2021 |
| ASUSTek       | SABERTOOTH X79              | [7f60ba417d](https://linux-hardware.org/?probe=7f60ba417d) | Sep 09, 2021 |
| Acer          | WG43M                       | [35c29a05ff](https://linux-hardware.org/?probe=35c29a05ff) | Sep 09, 2021 |
| ASRock        | Z390 Taichi                 | [8052fb9273](https://linux-hardware.org/?probe=8052fb9273) | Sep 09, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [03aad3f850](https://linux-hardware.org/?probe=03aad3f850) | Sep 09, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [bd88876ddf](https://linux-hardware.org/?probe=bd88876ddf) | Sep 08, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [d387648c16](https://linux-hardware.org/?probe=d387648c16) | Sep 08, 2021 |
| Intel         | DG33BU AAD79951-407         | [69bbaa38d9](https://linux-hardware.org/?probe=69bbaa38d9) | Sep 08, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [b6b99a61a3](https://linux-hardware.org/?probe=b6b99a61a3) | Sep 07, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [e6b54f6ad3](https://linux-hardware.org/?probe=e6b54f6ad3) | Sep 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [feff42e39c](https://linux-hardware.org/?probe=feff42e39c) | Sep 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | [dcd49ffb0e](https://linux-hardware.org/?probe=dcd49ffb0e) | Sep 06, 2021 |
| ASUSTek       | PRIME X470-PRO              | [8275c1d1e8](https://linux-hardware.org/?probe=8275c1d1e8) | Sep 06, 2021 |
| ASRock        | H170M Pro4                  | [a1ef6a3a8b](https://linux-hardware.org/?probe=a1ef6a3a8b) | Sep 06, 2021 |
| HP            | 2AF7                        | [ea75e63661](https://linux-hardware.org/?probe=ea75e63661) | Sep 06, 2021 |
| ASUSTek       | G11CD-K                     | [c4364afff6](https://linux-hardware.org/?probe=c4364afff6) | Sep 05, 2021 |
| Gigabyte      | Z370N WIFI-CF               | [cc4ad372df](https://linux-hardware.org/?probe=cc4ad372df) | Sep 05, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [ffa4f6aef7](https://linux-hardware.org/?probe=ffa4f6aef7) | Sep 05, 2021 |
| HP            | 2AF7                        | [63afb7c7f5](https://linux-hardware.org/?probe=63afb7c7f5) | Sep 04, 2021 |
| HP            | 2B5E                        | [51682d8e81](https://linux-hardware.org/?probe=51682d8e81) | Sep 03, 2021 |
| HP            | 2B5E                        | [9fd111c3eb](https://linux-hardware.org/?probe=9fd111c3eb) | Sep 03, 2021 |
| HP            | 8056                        | [b9c18a445b](https://linux-hardware.org/?probe=b9c18a445b) | Sep 03, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [c55d1ba8bf](https://linux-hardware.org/?probe=c55d1ba8bf) | Sep 03, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [43894b89a7](https://linux-hardware.org/?probe=43894b89a7) | Sep 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [167e800e3a](https://linux-hardware.org/?probe=167e800e3a) | Sep 02, 2021 |
| ASRock        | P55M Pro                    | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [724ad5d6a2](https://linux-hardware.org/?probe=724ad5d6a2) | Sep 02, 2021 |
| ASRock        | X300M-STX                   | [79afad37d2](https://linux-hardware.org/?probe=79afad37d2) | Sep 01, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [d2f0fba8f9](https://linux-hardware.org/?probe=d2f0fba8f9) | Sep 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [7bb30a79c1](https://linux-hardware.org/?probe=7bb30a79c1) | Sep 01, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [37c4ed4ed7](https://linux-hardware.org/?probe=37c4ed4ed7) | Sep 01, 2021 |
| Gigabyte      | B550M DS3H                  | [20389db1bd](https://linux-hardware.org/?probe=20389db1bd) | Aug 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [3ccd4032a1](https://linux-hardware.org/?probe=3ccd4032a1) | Aug 31, 2021 |
| HP            | 2AF7                        | [38b5cbf28d](https://linux-hardware.org/?probe=38b5cbf28d) | Aug 31, 2021 |
| ASRock        | H97M Pro4                   | [96d9d18052](https://linux-hardware.org/?probe=96d9d18052) | Aug 31, 2021 |
| ASRock        | H97M Pro4                   | [fb5e0539da](https://linux-hardware.org/?probe=fb5e0539da) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [e014d83782](https://linux-hardware.org/?probe=e014d83782) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [0cdd08839f](https://linux-hardware.org/?probe=0cdd08839f) | Aug 31, 2021 |
| ASUSTek       | P5Q-E                       | [997ce785b2](https://linux-hardware.org/?probe=997ce785b2) | Aug 31, 2021 |
| Gigabyte      | B150M-D3H-CF                | [6f0e81a6d9](https://linux-hardware.org/?probe=6f0e81a6d9) | Aug 31, 2021 |
| Gigabyte      | F2A68HM-S1                  | [dcc0bda879](https://linux-hardware.org/?probe=dcc0bda879) | Aug 30, 2021 |
| Gigabyte      | 970A-DS3P                   | [9a3be042e0](https://linux-hardware.org/?probe=9a3be042e0) | Aug 30, 2021 |
| HP            | 8056                        | [8614fae216](https://linux-hardware.org/?probe=8614fae216) | Aug 30, 2021 |
| HP            | 198E                        | [82d1a8a5a7](https://linux-hardware.org/?probe=82d1a8a5a7) | Aug 29, 2021 |
| Gigabyte      | 970A-DS3P                   | [e539faacf5](https://linux-hardware.org/?probe=e539faacf5) | Aug 29, 2021 |
| Gigabyte      | G41MT-D3                    | [d2b4c85e96](https://linux-hardware.org/?probe=d2b4c85e96) | Aug 29, 2021 |
| MSI           | MEG X570 UNIFY              | [cf5f33a843](https://linux-hardware.org/?probe=cf5f33a843) | Aug 28, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [5fd92a80fa](https://linux-hardware.org/?probe=5fd92a80fa) | Aug 28, 2021 |
| Lenovo        | Board                       | [ec9c58b54e](https://linux-hardware.org/?probe=ec9c58b54e) | Aug 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4331eedde2](https://linux-hardware.org/?probe=4331eedde2) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [614ac09d36](https://linux-hardware.org/?probe=614ac09d36) | Aug 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [3c31559d95](https://linux-hardware.org/?probe=3c31559d95) | Aug 28, 2021 |
| MSI           | X570-A PRO                  | [830bfb129f](https://linux-hardware.org/?probe=830bfb129f) | Aug 27, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| MSI           | X570-A PRO                  | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| MSI           | A320M-A PRO M2              | [fda90307d4](https://linux-hardware.org/?probe=fda90307d4) | Aug 27, 2021 |
| ASUSTek       | P6T                         | [ad049817af](https://linux-hardware.org/?probe=ad049817af) | Aug 27, 2021 |
| HP            | 8056                        | [e64dab1375](https://linux-hardware.org/?probe=e64dab1375) | Aug 27, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [a0ed3c6558](https://linux-hardware.org/?probe=a0ed3c6558) | Aug 27, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [adde1df1d0](https://linux-hardware.org/?probe=adde1df1d0) | Aug 27, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [63104dc43a](https://linux-hardware.org/?probe=63104dc43a) | Aug 26, 2021 |
| ASUSTek       | PRIME Z390-A                | [6e2699cc9e](https://linux-hardware.org/?probe=6e2699cc9e) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3e39cc51a8](https://linux-hardware.org/?probe=3e39cc51a8) | Aug 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [74a9538d04](https://linux-hardware.org/?probe=74a9538d04) | Aug 25, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [11d9254c35](https://linux-hardware.org/?probe=11d9254c35) | Aug 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [778e5aa3ae](https://linux-hardware.org/?probe=778e5aa3ae) | Aug 25, 2021 |
| ASRock        | FM2A55M-VG3+                | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| Dell          | 0HH807                      | [fe3659d065](https://linux-hardware.org/?probe=fe3659d065) | Aug 24, 2021 |
| ASRock        | 980DE3/U3S3                 | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Biostar       | A68I-450 DELUXE             | [3e0a375af7](https://linux-hardware.org/?probe=3e0a375af7) | Aug 23, 2021 |
| ASUSTek       | PRIME A320M-K               | [847e7f4c1a](https://linux-hardware.org/?probe=847e7f4c1a) | Aug 23, 2021 |
| MSI           | E3M WORKSTATION V5          | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [014af10464](https://linux-hardware.org/?probe=014af10464) | Aug 23, 2021 |
| HP            | 8056                        | [d604c95726](https://linux-hardware.org/?probe=d604c95726) | Aug 23, 2021 |
| Dell          | 0F3KHR A01                  | [b5bc473971](https://linux-hardware.org/?probe=b5bc473971) | Aug 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [07d9074437](https://linux-hardware.org/?probe=07d9074437) | Aug 23, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| ASRock        | H170M Pro4                  | [0cd9bde7b4](https://linux-hardware.org/?probe=0cd9bde7b4) | Aug 23, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f983e2baca](https://linux-hardware.org/?probe=f983e2baca) | Aug 22, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [b2190e55e8](https://linux-hardware.org/?probe=b2190e55e8) | Aug 22, 2021 |
| ASUSTek       | Z77-A                       | [971dc3b5c7](https://linux-hardware.org/?probe=971dc3b5c7) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [edc2f605d1](https://linux-hardware.org/?probe=edc2f605d1) | Aug 21, 2021 |
| MSI           | X370 SLI PLUS               | [4a611b712a](https://linux-hardware.org/?probe=4a611b712a) | Aug 21, 2021 |
| HP            | 2AF7                        | [beb4167201](https://linux-hardware.org/?probe=beb4167201) | Aug 21, 2021 |
| ASUSTek       | AM1M-A                      | [433d420dd4](https://linux-hardware.org/?probe=433d420dd4) | Aug 20, 2021 |
| ASUSTek       | P6T                         | [d0495a4765](https://linux-hardware.org/?probe=d0495a4765) | Aug 20, 2021 |
| ASRock        | AD2700-ITX                  | [1d1d8a4620](https://linux-hardware.org/?probe=1d1d8a4620) | Aug 20, 2021 |
| ASRock        | B450 Steel Legend           | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [4b37f6047e](https://linux-hardware.org/?probe=4b37f6047e) | Aug 20, 2021 |
| Gigabyte      | G41MT-D3                    | [e49dbd40b5](https://linux-hardware.org/?probe=e49dbd40b5) | Aug 20, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [41874518ea](https://linux-hardware.org/?probe=41874518ea) | Aug 20, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [78feb5ae08](https://linux-hardware.org/?probe=78feb5ae08) | Aug 20, 2021 |
| BESSTAR Te... | HM80                        | [60fdee03d6](https://linux-hardware.org/?probe=60fdee03d6) | Aug 19, 2021 |
| HP            | 83E9                        | [21b492b0bf](https://linux-hardware.org/?probe=21b492b0bf) | Aug 19, 2021 |
| HP            | 83E9                        | [7cb2c3256a](https://linux-hardware.org/?probe=7cb2c3256a) | Aug 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [84153c2a8d](https://linux-hardware.org/?probe=84153c2a8d) | Aug 19, 2021 |
| Gigabyte      | B150M-D3H-CF                | [2aed19ac0a](https://linux-hardware.org/?probe=2aed19ac0a) | Aug 19, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [5c3e90c735](https://linux-hardware.org/?probe=5c3e90c735) | Aug 19, 2021 |
| Gigabyte      | P55-USB3                    | [5e6a1d1926](https://linux-hardware.org/?probe=5e6a1d1926) | Aug 19, 2021 |
| HP            | 8056                        | [44b754f972](https://linux-hardware.org/?probe=44b754f972) | Aug 19, 2021 |
| ASUSTek       | AM1M-A                      | [c0653de55c](https://linux-hardware.org/?probe=c0653de55c) | Aug 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6eaf105bca](https://linux-hardware.org/?probe=6eaf105bca) | Aug 18, 2021 |
| HP            | 2AF7                        | [909c6f5c0a](https://linux-hardware.org/?probe=909c6f5c0a) | Aug 18, 2021 |
| ASRock        | X399 Taichi                 | [efead486a3](https://linux-hardware.org/?probe=efead486a3) | Aug 18, 2021 |
| HP            | 82F2 A01                    | [b6847d9605](https://linux-hardware.org/?probe=b6847d9605) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| ASRock        | B460M-ITX/ac                | [2eb3e6f3f6](https://linux-hardware.org/?probe=2eb3e6f3f6) | Aug 17, 2021 |
| Gigabyte      | G41MT-S2P                   | [63a8a28fd9](https://linux-hardware.org/?probe=63a8a28fd9) | Aug 17, 2021 |
| HP            | 8056                        | [5607e09042](https://linux-hardware.org/?probe=5607e09042) | Aug 17, 2021 |
| Dell          | 0Y2YM6 A00                  | [4d3d87b641](https://linux-hardware.org/?probe=4d3d87b641) | Aug 17, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [78a3158393](https://linux-hardware.org/?probe=78a3158393) | Aug 16, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| HP            | 198E                        | [d1c56bffb1](https://linux-hardware.org/?probe=d1c56bffb1) | Aug 15, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [86f9693894](https://linux-hardware.org/?probe=86f9693894) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [419995b0da](https://linux-hardware.org/?probe=419995b0da) | Aug 15, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [f931b86af5](https://linux-hardware.org/?probe=f931b86af5) | Aug 15, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [cd8825c8d0](https://linux-hardware.org/?probe=cd8825c8d0) | Aug 15, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [d34022df3b](https://linux-hardware.org/?probe=d34022df3b) | Aug 15, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [5f49d58f42](https://linux-hardware.org/?probe=5f49d58f42) | Aug 14, 2021 |
| Dell          | 0NKW6Y A00                  | [7d0c7834be](https://linux-hardware.org/?probe=7d0c7834be) | Aug 14, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [05bfca3339](https://linux-hardware.org/?probe=05bfca3339) | Aug 13, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [32bc94c4e2](https://linux-hardware.org/?probe=32bc94c4e2) | Aug 13, 2021 |
| Intel         | B75                         | [2bac7a8140](https://linux-hardware.org/?probe=2bac7a8140) | Aug 13, 2021 |
| Gigabyte      | Z390 D                      | [8bfd432fba](https://linux-hardware.org/?probe=8bfd432fba) | Aug 13, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [5e9853124d](https://linux-hardware.org/?probe=5e9853124d) | Aug 13, 2021 |
| Gigabyte      | G41MT-D3                    | [13558f63ab](https://linux-hardware.org/?probe=13558f63ab) | Aug 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [0b46a87be6](https://linux-hardware.org/?probe=0b46a87be6) | Aug 13, 2021 |
| Dell          | 03NVJ6 A01                  | [ef0028e285](https://linux-hardware.org/?probe=ef0028e285) | Aug 12, 2021 |
| MSI           | X570-A PRO                  | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3ed6340d82](https://linux-hardware.org/?probe=3ed6340d82) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | [5f70360eea](https://linux-hardware.org/?probe=5f70360eea) | Aug 12, 2021 |
| ASRock        | FM2A88X-ITX+                | [aeec0ec477](https://linux-hardware.org/?probe=aeec0ec477) | Aug 12, 2021 |
| Acer          | Aspire TC-705               | [bbf5c161d3](https://linux-hardware.org/?probe=bbf5c161d3) | Aug 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [3fd838012c](https://linux-hardware.org/?probe=3fd838012c) | Aug 12, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [f1eabffafd](https://linux-hardware.org/?probe=f1eabffafd) | Aug 12, 2021 |
| HP            | 8056                        | [afe5072bf8](https://linux-hardware.org/?probe=afe5072bf8) | Aug 12, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6808748401](https://linux-hardware.org/?probe=6808748401) | Aug 10, 2021 |
| Dell          | 0KWVT8 A02                  | [d8e685c049](https://linux-hardware.org/?probe=d8e685c049) | Aug 10, 2021 |
| MSI           | B75MA-E33                   | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [8ad0df4157](https://linux-hardware.org/?probe=8ad0df4157) | Aug 09, 2021 |
| ASRock        | AD2700-ITX                  | [fac88c2a70](https://linux-hardware.org/?probe=fac88c2a70) | Aug 09, 2021 |
| Biostar       | X370GTN                     | [eeff407867](https://linux-hardware.org/?probe=eeff407867) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [ec3a3d05e5](https://linux-hardware.org/?probe=ec3a3d05e5) | Aug 08, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [795328301d](https://linux-hardware.org/?probe=795328301d) | Aug 08, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [a81ec533a8](https://linux-hardware.org/?probe=a81ec533a8) | Aug 08, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [1a68be3ffe](https://linux-hardware.org/?probe=1a68be3ffe) | Aug 08, 2021 |
| Gigabyte      | G41MT-D3                    | [feacdb6873](https://linux-hardware.org/?probe=feacdb6873) | Aug 08, 2021 |
| HP            | 1998                        | [38acf34efb](https://linux-hardware.org/?probe=38acf34efb) | Aug 08, 2021 |
| MSI           | MAG B560 TORPEDO            | [8e1e7782d9](https://linux-hardware.org/?probe=8e1e7782d9) | Aug 08, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | [f51ff5d22f](https://linux-hardware.org/?probe=f51ff5d22f) | Aug 07, 2021 |
| MSI           | MAG B560 TORPEDO            | [4d2a5f5d27](https://linux-hardware.org/?probe=4d2a5f5d27) | Aug 07, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [4c87b2ff27](https://linux-hardware.org/?probe=4c87b2ff27) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f74df24802](https://linux-hardware.org/?probe=f74df24802) | Aug 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [2fbf46c559](https://linux-hardware.org/?probe=2fbf46c559) | Aug 05, 2021 |
| MSI           | B450-A PRO MAX              | [a096b9bb71](https://linux-hardware.org/?probe=a096b9bb71) | Aug 05, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [2c843a3d35](https://linux-hardware.org/?probe=2c843a3d35) | Aug 04, 2021 |
| Gigabyte      | EP45-DS3L                   | [dfb3b0302c](https://linux-hardware.org/?probe=dfb3b0302c) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | [b3ae79f78f](https://linux-hardware.org/?probe=b3ae79f78f) | Aug 04, 2021 |
| ASRockRack    | X470D4U                     | [a124194272](https://linux-hardware.org/?probe=a124194272) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | [dce96ae07e](https://linux-hardware.org/?probe=dce96ae07e) | Aug 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | [345ce8fb64](https://linux-hardware.org/?probe=345ce8fb64) | Aug 04, 2021 |
| HP            | 82F2 A01                    | [b6b124c434](https://linux-hardware.org/?probe=b6b124c434) | Aug 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [f776a4eb93](https://linux-hardware.org/?probe=f776a4eb93) | Aug 03, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [ad5bc52a88](https://linux-hardware.org/?probe=ad5bc52a88) | Aug 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [39919aab55](https://linux-hardware.org/?probe=39919aab55) | Aug 02, 2021 |
| ASRock        | B450 Pro4                   | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [454fecb7fb](https://linux-hardware.org/?probe=454fecb7fb) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [c18e0a53fc](https://linux-hardware.org/?probe=c18e0a53fc) | Aug 01, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | [052a6762c4](https://linux-hardware.org/?probe=052a6762c4) | Jul 31, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2b00e34271](https://linux-hardware.org/?probe=2b00e34271) | Jul 31, 2021 |
| Lenovo        | MAHOBAY NOK                 | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [b5a0d25d72](https://linux-hardware.org/?probe=b5a0d25d72) | Jul 30, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [e842eefc11](https://linux-hardware.org/?probe=e842eefc11) | Jul 29, 2021 |
| Gigabyte      | F2A78M-HD2                  | [ae31c59ee8](https://linux-hardware.org/?probe=ae31c59ee8) | Jul 29, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [20e3d5c8af](https://linux-hardware.org/?probe=20e3d5c8af) | Jul 29, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [21bcfb6822](https://linux-hardware.org/?probe=21bcfb6822) | Jul 29, 2021 |
| ASUSTek       | PRIME Z390-A                | [c6239b2672](https://linux-hardware.org/?probe=c6239b2672) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| ASUSTek       | M5A97 R2.0                  | [fe0953d7db](https://linux-hardware.org/?probe=fe0953d7db) | Jul 27, 2021 |
| ASRock        | X399 Professional Gaming    | [5e769c8137](https://linux-hardware.org/?probe=5e769c8137) | Jul 26, 2021 |
| Gigabyte      | H61N-USB3                   | [25961dfa1f](https://linux-hardware.org/?probe=25961dfa1f) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte      | H97M-DS3P                   | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| HP            | 2AF7                        | [a24b46f292](https://linux-hardware.org/?probe=a24b46f292) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [f2c2beb7da](https://linux-hardware.org/?probe=f2c2beb7da) | Jul 24, 2021 |
| Lenovo        | MAHOBAY NOK                 | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Unknown       | Unknown                     | [0bf537187a](https://linux-hardware.org/?probe=0bf537187a) | Jul 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Unknown       | Unknown                     | [8681aef84a](https://linux-hardware.org/?probe=8681aef84a) | Jul 23, 2021 |
| Acer          | WG43M                       | [9efd66b779](https://linux-hardware.org/?probe=9efd66b779) | Jul 22, 2021 |
| Dell          | 0W0CHX A01                  | [d4f3e21abc](https://linux-hardware.org/?probe=d4f3e21abc) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [0b87f80aa9](https://linux-hardware.org/?probe=0b87f80aa9) | Jul 22, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [114ecaea11](https://linux-hardware.org/?probe=114ecaea11) | Jul 22, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | [831024faec](https://linux-hardware.org/?probe=831024faec) | Jul 22, 2021 |
| Intel         | H81                         | [166b35fa7f](https://linux-hardware.org/?probe=166b35fa7f) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | [437aef57fd](https://linux-hardware.org/?probe=437aef57fd) | Jul 21, 2021 |
| ASRock        | 980DE3/U3S3                 | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Gigabyte      | G41M-Combo                  | [785c30284d](https://linux-hardware.org/?probe=785c30284d) | Jul 21, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [4dd5b903b6](https://linux-hardware.org/?probe=4dd5b903b6) | Jul 21, 2021 |
| HP            | 83E1                        | [977631dbb5](https://linux-hardware.org/?probe=977631dbb5) | Jul 20, 2021 |
| ASUSTek       | CM1740                      | [bddfad8365](https://linux-hardware.org/?probe=bddfad8365) | Jul 20, 2021 |
| ASUSTek       | CM1740                      | [2dcaee58ab](https://linux-hardware.org/?probe=2dcaee58ab) | Jul 20, 2021 |
| Gigabyte      | B450 AORUS M                | [ebed27d481](https://linux-hardware.org/?probe=ebed27d481) | Jul 20, 2021 |
| Gigabyte      | H61N-USB3                   | [54677110b4](https://linux-hardware.org/?probe=54677110b4) | Jul 20, 2021 |
| ASUSTek       | P8B75-M                     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| Gigabyte      | EP45-DS3L                   | [3e9218d801](https://linux-hardware.org/?probe=3e9218d801) | Jul 19, 2021 |
| ASUSTek       | P5LD2                       | [9e97498649](https://linux-hardware.org/?probe=9e97498649) | Jul 19, 2021 |
| MSI           | Z390-A PRO                  | [811ff5b5d4](https://linux-hardware.org/?probe=811ff5b5d4) | Jul 19, 2021 |
| Gigabyte      | G41M-Combo                  | [5f182f7f80](https://linux-hardware.org/?probe=5f182f7f80) | Jul 18, 2021 |
| HP            | 3646h                       | [b4dd06e5ce](https://linux-hardware.org/?probe=b4dd06e5ce) | Jul 18, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [d51165f3df](https://linux-hardware.org/?probe=d51165f3df) | Jul 17, 2021 |
| Gigabyte      | M61PME-S2P                  | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [6f6f7c6f5b](https://linux-hardware.org/?probe=6f6f7c6f5b) | Jul 16, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [02c451c80b](https://linux-hardware.org/?probe=02c451c80b) | Jul 16, 2021 |
| Biostar       | X370GTN                     | [22114c765e](https://linux-hardware.org/?probe=22114c765e) | Jul 16, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [15a186d484](https://linux-hardware.org/?probe=15a186d484) | Jul 16, 2021 |
| Gigabyte      | B560M AORUS PRO AX          | [38067d7d6d](https://linux-hardware.org/?probe=38067d7d6d) | Jul 15, 2021 |
| HP            | 8056                        | [bff5c3bb8d](https://linux-hardware.org/?probe=bff5c3bb8d) | Jul 15, 2021 |
| ASRock        | 990FX Extreme3              | [0621ec449f](https://linux-hardware.org/?probe=0621ec449f) | Jul 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [24a13881c1](https://linux-hardware.org/?probe=24a13881c1) | Jul 14, 2021 |
| ASRock        | A320M-HDV R4.0              | [663c98e1f6](https://linux-hardware.org/?probe=663c98e1f6) | Jul 13, 2021 |
| HP            | 872B                        | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [c7fad2195c](https://linux-hardware.org/?probe=c7fad2195c) | Jul 13, 2021 |
| ASRock        | A320M-HD                    | [d3700506ef](https://linux-hardware.org/?probe=d3700506ef) | Jul 13, 2021 |
| SYWZ          | S200 Series                 | [842ae5d4a3](https://linux-hardware.org/?probe=842ae5d4a3) | Jul 12, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [6f04de798d](https://linux-hardware.org/?probe=6f04de798d) | Jul 12, 2021 |
| Dell          | 0C2KJT A00                  | [891d514a94](https://linux-hardware.org/?probe=891d514a94) | Jul 12, 2021 |
| EVGA          | 111-KS-E272                 | [a97173038d](https://linux-hardware.org/?probe=a97173038d) | Jul 12, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [16799202de](https://linux-hardware.org/?probe=16799202de) | Jul 11, 2021 |
| Dell          | 0DF42J A00                  | [8a76db0ada](https://linux-hardware.org/?probe=8a76db0ada) | Jul 11, 2021 |
| ASUSTek       | EX-B250-V7                  | [32e09fdf66](https://linux-hardware.org/?probe=32e09fdf66) | Jul 11, 2021 |
| Gigabyte      | Z270-Gaming K3              | [731361283a](https://linux-hardware.org/?probe=731361283a) | Jul 10, 2021 |
| Gigabyte      | G41MT-D3                    | [9a275b8307](https://linux-hardware.org/?probe=9a275b8307) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [89ed1de959](https://linux-hardware.org/?probe=89ed1de959) | Jul 10, 2021 |
| Dell          | 0VRWRC A00                  | [3ec458e478](https://linux-hardware.org/?probe=3ec458e478) | Jul 10, 2021 |
| Gigabyte      | P31-ES3G                    | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [f008db5308](https://linux-hardware.org/?probe=f008db5308) | Jul 10, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [e1049532a5](https://linux-hardware.org/?probe=e1049532a5) | Jul 09, 2021 |
| MSI           | MS-B1711                    | [ad46286aa7](https://linux-hardware.org/?probe=ad46286aa7) | Jul 09, 2021 |
| HP            | 1497                        | [eecafd7c6c](https://linux-hardware.org/?probe=eecafd7c6c) | Jul 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [07e45f519d](https://linux-hardware.org/?probe=07e45f519d) | Jul 09, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [413c28caa0](https://linux-hardware.org/?probe=413c28caa0) | Jul 08, 2021 |
| HP            | 8056                        | [c35a7e4e65](https://linux-hardware.org/?probe=c35a7e4e65) | Jul 08, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [785027f8f6](https://linux-hardware.org/?probe=785027f8f6) | Jul 08, 2021 |
| ASRock        | X399 Phantom Gaming 6       | [d93e096489](https://linux-hardware.org/?probe=d93e096489) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | [9314761de4](https://linux-hardware.org/?probe=9314761de4) | Jul 08, 2021 |
| Unknown       | DH61BR G32662-203           | [c658575abc](https://linux-hardware.org/?probe=c658575abc) | Jul 08, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [f0474e6193](https://linux-hardware.org/?probe=f0474e6193) | Jul 08, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [25fdba4c4f](https://linux-hardware.org/?probe=25fdba4c4f) | Jul 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [47e2b55bb5](https://linux-hardware.org/?probe=47e2b55bb5) | Jul 07, 2021 |
| HP            | 8056                        | [f40b845088](https://linux-hardware.org/?probe=f40b845088) | Jul 07, 2021 |
| ASUSTek       | X99-A II                    | [d84c3b80a1](https://linux-hardware.org/?probe=d84c3b80a1) | Jul 07, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [a7ffc7e0dd](https://linux-hardware.org/?probe=a7ffc7e0dd) | Jul 07, 2021 |
| Gigabyte      | H61N-USB3                   | [4533c4325a](https://linux-hardware.org/?probe=4533c4325a) | Jul 07, 2021 |
| Dell          | 0PC5F7 A02                  | [ea43204b3b](https://linux-hardware.org/?probe=ea43204b3b) | Jul 06, 2021 |
| ASUSTek       | Z170-A                      | [04b8667d2e](https://linux-hardware.org/?probe=04b8667d2e) | Jul 06, 2021 |
| Gigabyte      | H61N-USB3                   | [936f2b1169](https://linux-hardware.org/?probe=936f2b1169) | Jul 06, 2021 |
| ASRock        | AD2700-ITX                  | [9b868b0c9b](https://linux-hardware.org/?probe=9b868b0c9b) | Jul 06, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [5758df25ec](https://linux-hardware.org/?probe=5758df25ec) | Jul 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [a44525ea2d](https://linux-hardware.org/?probe=a44525ea2d) | Jul 05, 2021 |
| Gigabyte      | G41MT-D3                    | [faa3279fc6](https://linux-hardware.org/?probe=faa3279fc6) | Jul 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | [3aa1e79866](https://linux-hardware.org/?probe=3aa1e79866) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | [6fdc284c1a](https://linux-hardware.org/?probe=6fdc284c1a) | Jul 05, 2021 |
| MSI           | B450M BAZOOKA V2            | [efe8014efa](https://linux-hardware.org/?probe=efe8014efa) | Jul 05, 2021 |
| Gigabyte      | H61N-USB3                   | [7fe084720d](https://linux-hardware.org/?probe=7fe084720d) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | [13f5ecaf06](https://linux-hardware.org/?probe=13f5ecaf06) | Jul 04, 2021 |
| Alienware     | 0N4R4N A00                  | [9219336156](https://linux-hardware.org/?probe=9219336156) | Jul 04, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [9e7e50fd74](https://linux-hardware.org/?probe=9e7e50fd74) | Jul 04, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| Gigabyte      | H61N-USB3                   | [5b2d86e06f](https://linux-hardware.org/?probe=5b2d86e06f) | Jul 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [de1eb87e32](https://linux-hardware.org/?probe=de1eb87e32) | Jul 04, 2021 |
| HP            | 8056                        | [56f294962a](https://linux-hardware.org/?probe=56f294962a) | Jul 04, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| MSI           | MS-B9321                    | [93243d00da](https://linux-hardware.org/?probe=93243d00da) | Jul 03, 2021 |
| Google        | Panther                     | [043feff8fe](https://linux-hardware.org/?probe=043feff8fe) | Jul 03, 2021 |
| ASRock        | J3160DC-ITX                 | [cfd320c331](https://linux-hardware.org/?probe=cfd320c331) | Jul 03, 2021 |
| Chuwi         | LarkBox Pro                 | [0b050f9b1d](https://linux-hardware.org/?probe=0b050f9b1d) | Jul 03, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0e5e9b16b8](https://linux-hardware.org/?probe=0e5e9b16b8) | Jul 03, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [f61ba12c20](https://linux-hardware.org/?probe=f61ba12c20) | Jul 03, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [36c64a337b](https://linux-hardware.org/?probe=36c64a337b) | Jul 03, 2021 |
| MSI           | H110M PRO-VD                | [55cdedffc2](https://linux-hardware.org/?probe=55cdedffc2) | Jul 03, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [f3ef9d51b3](https://linux-hardware.org/?probe=f3ef9d51b3) | Jul 02, 2021 |
| MSI           | MS-B1711                    | [21ec3e7523](https://linux-hardware.org/?probe=21ec3e7523) | Jul 02, 2021 |
| AMD           | A320IPC VER:1.00            | [f165ce8a70](https://linux-hardware.org/?probe=f165ce8a70) | Jul 01, 2021 |
| HP            | 8056                        | [d10cd539f1](https://linux-hardware.org/?probe=d10cd539f1) | Jul 01, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [48bef18c1a](https://linux-hardware.org/?probe=48bef18c1a) | Jul 01, 2021 |
| Gigabyte      | G41MT-D3                    | [ed64b27c12](https://linux-hardware.org/?probe=ed64b27c12) | Jul 01, 2021 |
| Gigabyte      | H61N-USB3                   | [d6bf3eece4](https://linux-hardware.org/?probe=d6bf3eece4) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [a37dd487ac](https://linux-hardware.org/?probe=a37dd487ac) | Jun 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e6cda3b64b](https://linux-hardware.org/?probe=e6cda3b64b) | Jun 30, 2021 |
| Dell          | 08NPPY A00                  | [28dd0487c3](https://linux-hardware.org/?probe=28dd0487c3) | Jun 30, 2021 |
| ASRock        | A320M-HD                    | [ce332204a6](https://linux-hardware.org/?probe=ce332204a6) | Jun 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [a8268a0c9d](https://linux-hardware.org/?probe=a8268a0c9d) | Jun 29, 2021 |
| Lenovo        | Board                       | [1e1ba598d3](https://linux-hardware.org/?probe=1e1ba598d3) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | [1185271556](https://linux-hardware.org/?probe=1185271556) | Jun 29, 2021 |
| ASUSTek       | PRIME Z370-A                | [0369ff2b06](https://linux-hardware.org/?probe=0369ff2b06) | Jun 29, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [353a5052a1](https://linux-hardware.org/?probe=353a5052a1) | Jun 29, 2021 |
| Dell          | 06D7TR A00                  | [52e029b58e](https://linux-hardware.org/?probe=52e029b58e) | Jun 28, 2021 |
| SYWZ          | S200 Series                 | [a848b9e433](https://linux-hardware.org/?probe=a848b9e433) | Jun 28, 2021 |
| Positivo      | POS-MI945AA                 | [fd4be0982e](https://linux-hardware.org/?probe=fd4be0982e) | Jun 27, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [a6b799f108](https://linux-hardware.org/?probe=a6b799f108) | Jun 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [62c1b02c31](https://linux-hardware.org/?probe=62c1b02c31) | Jun 27, 2021 |
| HP            | 8436                        | [617d5e50fd](https://linux-hardware.org/?probe=617d5e50fd) | Jun 27, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [f479cb95d4](https://linux-hardware.org/?probe=f479cb95d4) | Jun 26, 2021 |
| Dell          | 08NPPY A00                  | [3c33ace801](https://linux-hardware.org/?probe=3c33ace801) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [c1e9364997](https://linux-hardware.org/?probe=c1e9364997) | Jun 26, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [533712977b](https://linux-hardware.org/?probe=533712977b) | Jun 26, 2021 |
| Unknown       | NF-MCP78                    | [39a0c32be8](https://linux-hardware.org/?probe=39a0c32be8) | Jun 26, 2021 |
| Gigabyte      | G41MT-D3                    | [03a472ae41](https://linux-hardware.org/?probe=03a472ae41) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [68cd01f446](https://linux-hardware.org/?probe=68cd01f446) | Jun 25, 2021 |
| HP            | 8056                        | [3cce894f08](https://linux-hardware.org/?probe=3cce894f08) | Jun 25, 2021 |
| ASUSTek       | PRIME B460M-A               | [95a80b91fd](https://linux-hardware.org/?probe=95a80b91fd) | Jun 25, 2021 |
| Gigabyte      | B150M-D3H-CF                | [02924c7c01](https://linux-hardware.org/?probe=02924c7c01) | Jun 25, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [7f19e67108](https://linux-hardware.org/?probe=7f19e67108) | Jun 24, 2021 |
| Gigabyte      | H110M-H-CF                  | [f8a74fc57a](https://linux-hardware.org/?probe=f8a74fc57a) | Jun 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b5d17f5b99](https://linux-hardware.org/?probe=b5d17f5b99) | Jun 24, 2021 |
| ASRock        | A320M-HD                    | [121770a05e](https://linux-hardware.org/?probe=121770a05e) | Jun 23, 2021 |
| MSI           | Z97 GAMING 5                | [8edc5f4d03](https://linux-hardware.org/?probe=8edc5f4d03) | Jun 23, 2021 |
| ASRock        | B550M Steel Legend          | [e1346ace5c](https://linux-hardware.org/?probe=e1346ace5c) | Jun 23, 2021 |
| Gigabyte      | G41MT-D3                    | [c69a0b8125](https://linux-hardware.org/?probe=c69a0b8125) | Jun 23, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7a6f9e9890](https://linux-hardware.org/?probe=7a6f9e9890) | Jun 22, 2021 |
| ASRock        | H77 Pro4-M                  | [643c704c39](https://linux-hardware.org/?probe=643c704c39) | Jun 22, 2021 |
| Lenovo        | 3714 SDK0R32862 WIN 3258... | [b20ad5477a](https://linux-hardware.org/?probe=b20ad5477a) | Jun 22, 2021 |
| HP            | 198E                        | [b614ce2528](https://linux-hardware.org/?probe=b614ce2528) | Jun 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ca17e02509](https://linux-hardware.org/?probe=ca17e02509) | Jun 22, 2021 |
| Unknown       | NF-MCP78                    | [b9ad532089](https://linux-hardware.org/?probe=b9ad532089) | Jun 22, 2021 |
| ASRock        | H97M Pro4                   | [b57edde05d](https://linux-hardware.org/?probe=b57edde05d) | Jun 22, 2021 |
| HP            | ProLiant ML150 G5           | [dd931cb4e6](https://linux-hardware.org/?probe=dd931cb4e6) | Jun 21, 2021 |
| ASRock        | Z97 Extreme4                | [9974950d4a](https://linux-hardware.org/?probe=9974950d4a) | Jun 21, 2021 |
| MSI           | B450 TOMAHAWK               | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [4ac446c37b](https://linux-hardware.org/?probe=4ac446c37b) | Jun 21, 2021 |
| Gigabyte      | H77N-WIFI                   | [0c1eb0be4f](https://linux-hardware.org/?probe=0c1eb0be4f) | Jun 21, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [5af8c6f41c](https://linux-hardware.org/?probe=5af8c6f41c) | Jun 21, 2021 |
| ASUSTek       | PRIME B460M-A               | [5050b7baad](https://linux-hardware.org/?probe=5050b7baad) | Jun 21, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [59fa18019a](https://linux-hardware.org/?probe=59fa18019a) | Jun 20, 2021 |
| ASUSTek       | PRIME A320M-E               | [edb0b62fe0](https://linux-hardware.org/?probe=edb0b62fe0) | Jun 19, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e3e63b4e4c](https://linux-hardware.org/?probe=e3e63b4e4c) | Jun 19, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [ed109bbeda](https://linux-hardware.org/?probe=ed109bbeda) | Jun 19, 2021 |
| Dell          | 0F8101                      | [a33d01212c](https://linux-hardware.org/?probe=a33d01212c) | Jun 19, 2021 |
| HP            | 8056                        | [f1b5c0d45e](https://linux-hardware.org/?probe=f1b5c0d45e) | Jun 18, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [8e3aa30f32](https://linux-hardware.org/?probe=8e3aa30f32) | Jun 18, 2021 |
| ASRock        | H97 Killer                  | [acc4773b1b](https://linux-hardware.org/?probe=acc4773b1b) | Jun 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ecdf88f402](https://linux-hardware.org/?probe=ecdf88f402) | Jun 18, 2021 |
| HP            | 81C5 MVB                    | [eb5550cdef](https://linux-hardware.org/?probe=eb5550cdef) | Jun 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [419ff5b1e5](https://linux-hardware.org/?probe=419ff5b1e5) | Jun 17, 2021 |
| Gigabyte      | H77N-WIFI                   | [c9cf129666](https://linux-hardware.org/?probe=c9cf129666) | Jun 17, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [d17aa6436e](https://linux-hardware.org/?probe=d17aa6436e) | Jun 17, 2021 |
| Intel         | MIR1 RVP7                   | [b0a36a3845](https://linux-hardware.org/?probe=b0a36a3845) | Jun 17, 2021 |
| ASUSTek       | P5N73-CM                    | [5320c39497](https://linux-hardware.org/?probe=5320c39497) | Jun 16, 2021 |
| ASUSTek       | P5N73-CM                    | [096e520c57](https://linux-hardware.org/?probe=096e520c57) | Jun 16, 2021 |
| ASRock        | Z170 Extreme7+              | [180e2dcad0](https://linux-hardware.org/?probe=180e2dcad0) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [caee94b554](https://linux-hardware.org/?probe=caee94b554) | Jun 16, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [28f64a2715](https://linux-hardware.org/?probe=28f64a2715) | Jun 15, 2021 |
| Gigabyte      | G41MT-D3                    | [6d61e60824](https://linux-hardware.org/?probe=6d61e60824) | Jun 15, 2021 |
| Gigabyte      | G41MT-D3                    | [7e4f2022c8](https://linux-hardware.org/?probe=7e4f2022c8) | Jun 15, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [b30a75edb2](https://linux-hardware.org/?probe=b30a75edb2) | Jun 15, 2021 |
| Gigabyte      | H77N-WIFI                   | [8fa18de364](https://linux-hardware.org/?probe=8fa18de364) | Jun 15, 2021 |
| Gigabyte      | EP45-DS3L                   | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [692dcceeee](https://linux-hardware.org/?probe=692dcceeee) | Jun 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3b280580e0](https://linux-hardware.org/?probe=3b280580e0) | Jun 14, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [c89aa8ea82](https://linux-hardware.org/?probe=c89aa8ea82) | Jun 13, 2021 |
| ASRock        | B450M-HDV R4.0              | [b5b8d7a195](https://linux-hardware.org/?probe=b5b8d7a195) | Jun 13, 2021 |
| Intel         | SHARKBAY                    | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| ASUSTek       | M2N-E SLI                   | [c1805791ab](https://linux-hardware.org/?probe=c1805791ab) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3f74265d6d](https://linux-hardware.org/?probe=3f74265d6d) | Jun 12, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [2dcbc551cd](https://linux-hardware.org/?probe=2dcbc551cd) | Jun 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [0a78275a12](https://linux-hardware.org/?probe=0a78275a12) | Jun 12, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [edcaa9a1be](https://linux-hardware.org/?probe=edcaa9a1be) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [92f48178fc](https://linux-hardware.org/?probe=92f48178fc) | Jun 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [94d4ada14e](https://linux-hardware.org/?probe=94d4ada14e) | Jun 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [7805e2e2a1](https://linux-hardware.org/?probe=7805e2e2a1) | Jun 11, 2021 |
| HP            | 3397                        | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| Gigabyte      | EP41-UD3L                   | [aa273ff14d](https://linux-hardware.org/?probe=aa273ff14d) | Jun 10, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | [405b055ebd](https://linux-hardware.org/?probe=405b055ebd) | Jun 10, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [565cd46886](https://linux-hardware.org/?probe=565cd46886) | Jun 10, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [ebca8fe85a](https://linux-hardware.org/?probe=ebca8fe85a) | Jun 09, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [0023c36bb4](https://linux-hardware.org/?probe=0023c36bb4) | Jun 09, 2021 |
| Gigabyte      | Z270-HD3P-CF                | [85ad270405](https://linux-hardware.org/?probe=85ad270405) | Jun 09, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [783d8a89bd](https://linux-hardware.org/?probe=783d8a89bd) | Jun 09, 2021 |
| Gigabyte      | G41MT-D3                    | [a1cfc1d335](https://linux-hardware.org/?probe=a1cfc1d335) | Jun 09, 2021 |
| ASRock        | A300M-STX                   | [d5fbd4c05d](https://linux-hardware.org/?probe=d5fbd4c05d) | Jun 08, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [0604956adc](https://linux-hardware.org/?probe=0604956adc) | Jun 08, 2021 |
| MSI           | Z390-A PRO                  | [8d4983662d](https://linux-hardware.org/?probe=8d4983662d) | Jun 08, 2021 |
| HP            | 843C                        | [391865c5a2](https://linux-hardware.org/?probe=391865c5a2) | Jun 08, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [c493d4cdf9](https://linux-hardware.org/?probe=c493d4cdf9) | Jun 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2c66c12e1b](https://linux-hardware.org/?probe=2c66c12e1b) | Jun 07, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [13eaba8cd2](https://linux-hardware.org/?probe=13eaba8cd2) | Jun 07, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [872d0ecc32](https://linux-hardware.org/?probe=872d0ecc32) | Jun 07, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [521f3e1bde](https://linux-hardware.org/?probe=521f3e1bde) | Jun 07, 2021 |
| Gateway       | DX4860                      | [bd9a842eec](https://linux-hardware.org/?probe=bd9a842eec) | Jun 07, 2021 |
| Gateway       | DX4860                      | [a26d972766](https://linux-hardware.org/?probe=a26d972766) | Jun 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [d5b58807dd](https://linux-hardware.org/?probe=d5b58807dd) | Jun 07, 2021 |
| ASRock        | B560M Steel Legend          | [c87d28e8c0](https://linux-hardware.org/?probe=c87d28e8c0) | Jun 07, 2021 |
| ASRock        | H97M Pro4                   | [8ba65755ff](https://linux-hardware.org/?probe=8ba65755ff) | Jun 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7e68daad35](https://linux-hardware.org/?probe=7e68daad35) | Jun 06, 2021 |
| ASUSTek       | Z170-A                      | [ba3e1c4e32](https://linux-hardware.org/?probe=ba3e1c4e32) | Jun 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d94c194ba5](https://linux-hardware.org/?probe=d94c194ba5) | Jun 05, 2021 |
| Intel         | H61                         | [607d6e5e33](https://linux-hardware.org/?probe=607d6e5e33) | Jun 05, 2021 |
| Intel         | H61                         | [8ed3e75d2d](https://linux-hardware.org/?probe=8ed3e75d2d) | Jun 05, 2021 |
| HP            | 8768 A                      | [f239501901](https://linux-hardware.org/?probe=f239501901) | Jun 05, 2021 |
| MSI           | A78M-E35                    | [4d4959df32](https://linux-hardware.org/?probe=4d4959df32) | Jun 04, 2021 |
| MSI           | A78M-E35                    | [7dc4db6092](https://linux-hardware.org/?probe=7dc4db6092) | Jun 04, 2021 |
| ASRock        | AB350 Pro4                  | [557557b4eb](https://linux-hardware.org/?probe=557557b4eb) | Jun 04, 2021 |
| HP            | 0AECh D                     | [0a0a487efe](https://linux-hardware.org/?probe=0a0a487efe) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [4931426516](https://linux-hardware.org/?probe=4931426516) | Jun 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1cb5b38d5e](https://linux-hardware.org/?probe=1cb5b38d5e) | Jun 03, 2021 |
| ASUSTek       | Z170-A                      | [221e440b21](https://linux-hardware.org/?probe=221e440b21) | Jun 03, 2021 |
| ASUSTek       | PRIME H310M-D               | [5f98fdcb02](https://linux-hardware.org/?probe=5f98fdcb02) | Jun 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1c0016dc30](https://linux-hardware.org/?probe=1c0016dc30) | Jun 03, 2021 |
| ASUSTek       | A8R32-MVP Deluxe            | [0e54cb2214](https://linux-hardware.org/?probe=0e54cb2214) | Jun 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [290d70d292](https://linux-hardware.org/?probe=290d70d292) | Jun 03, 2021 |
| Gigabyte      | H77N-WIFI                   | [ceb72d0ae7](https://linux-hardware.org/?probe=ceb72d0ae7) | Jun 03, 2021 |
| Gigabyte      | G41MT-D3                    | [9bae888d70](https://linux-hardware.org/?probe=9bae888d70) | Jun 03, 2021 |
| Lenovo        | ThinkCentre M58p 7220A72    | [4c17a95dc1](https://linux-hardware.org/?probe=4c17a95dc1) | Jun 03, 2021 |
| Dell          | 0427JK A00                  | [0cde3de43d](https://linux-hardware.org/?probe=0cde3de43d) | Jun 03, 2021 |
| ASUSTek       | Maximus VII HERO            | [dbfeab0bb4](https://linux-hardware.org/?probe=dbfeab0bb4) | Jun 02, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [1a7c5aee0e](https://linux-hardware.org/?probe=1a7c5aee0e) | Jun 02, 2021 |
| ASUSTek       | M2N-E SLI                   | [203b62c458](https://linux-hardware.org/?probe=203b62c458) | Jun 02, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ad37db1da8](https://linux-hardware.org/?probe=ad37db1da8) | Jun 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [f5dafbe2de](https://linux-hardware.org/?probe=f5dafbe2de) | Jun 01, 2021 |
| Gigabyte      | GA-MA785G-UD3H              | [f7ca87e974](https://linux-hardware.org/?probe=f7ca87e974) | Jun 01, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [b8d0e81636](https://linux-hardware.org/?probe=b8d0e81636) | Jun 01, 2021 |
| Gigabyte      | 990XA-UD3                   | [77fcb9cf4a](https://linux-hardware.org/?probe=77fcb9cf4a) | Jun 01, 2021 |
| Gigabyte      | Z97-HD3                     | [e0277e3530](https://linux-hardware.org/?probe=e0277e3530) | May 31, 2021 |
| Dell          | 0R849J A00                  | [7a75936b55](https://linux-hardware.org/?probe=7a75936b55) | May 31, 2021 |
| Dell          | 0GXM1W A01                  | [4daf9fdc0d](https://linux-hardware.org/?probe=4daf9fdc0d) | May 31, 2021 |
| ASUSTek       | PRIME B460M-A               | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| MSI           | X570-A PRO                  | [9b20a88d5e](https://linux-hardware.org/?probe=9b20a88d5e) | May 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [65310866eb](https://linux-hardware.org/?probe=65310866eb) | May 31, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ff3d2367ee](https://linux-hardware.org/?probe=ff3d2367ee) | May 30, 2021 |
| HP            | 8056                        | [fc6d4c2e7d](https://linux-hardware.org/?probe=fc6d4c2e7d) | May 30, 2021 |
| Huanan        | X79 VAA1                    | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| ASRock        | FM2A55M-VG3+                | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| Dell          | 00V62H A01                  | [73da9f35d4](https://linux-hardware.org/?probe=73da9f35d4) | May 29, 2021 |
| ASUSTek       | A88X-PRO                    | [bdb612797a](https://linux-hardware.org/?probe=bdb612797a) | May 29, 2021 |
| Gigabyte      | H370N WIFI-CF               | [197e319075](https://linux-hardware.org/?probe=197e319075) | May 29, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [06bb083e38](https://linux-hardware.org/?probe=06bb083e38) | May 29, 2021 |
| Gigabyte      | B360M D3H-CF                | [f23de0d726](https://linux-hardware.org/?probe=f23de0d726) | May 28, 2021 |
| Gigabyte      | H61M-S2PH                   | [e88de55691](https://linux-hardware.org/?probe=e88de55691) | May 28, 2021 |
| Dell          | 00V62H A01                  | [927f339e68](https://linux-hardware.org/?probe=927f339e68) | May 28, 2021 |
| ASRock        | B450M Pro4                  | [ccd56acb24](https://linux-hardware.org/?probe=ccd56acb24) | May 27, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [5474165f7b](https://linux-hardware.org/?probe=5474165f7b) | May 27, 2021 |
| Unknown       | X79                         | [c6dcb137fb](https://linux-hardware.org/?probe=c6dcb137fb) | May 27, 2021 |
| ASRock        | X99 Extreme4                | [6feb0aec47](https://linux-hardware.org/?probe=6feb0aec47) | May 26, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [172ab027e5](https://linux-hardware.org/?probe=172ab027e5) | May 26, 2021 |
| HP            | 21D0                        | [d6d7cbe7c5](https://linux-hardware.org/?probe=d6d7cbe7c5) | May 26, 2021 |
| HP            | 21D0                        | [68f25edcdd](https://linux-hardware.org/?probe=68f25edcdd) | May 26, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a6751fcc02](https://linux-hardware.org/?probe=a6751fcc02) | May 26, 2021 |
| ASRock        | A300M-STX                   | [4e5245a71d](https://linux-hardware.org/?probe=4e5245a71d) | May 25, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [b07793f86c](https://linux-hardware.org/?probe=b07793f86c) | May 25, 2021 |
| Gigabyte      | Z97N-Gaming 5               | [b1b61b4aa6](https://linux-hardware.org/?probe=b1b61b4aa6) | May 25, 2021 |
| Intel         | H61                         | [5b5682ab2e](https://linux-hardware.org/?probe=5b5682ab2e) | May 25, 2021 |
| ASRock        | A300M-STX                   | [cecc5ad69e](https://linux-hardware.org/?probe=cecc5ad69e) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [cf4e1cb0d6](https://linux-hardware.org/?probe=cf4e1cb0d6) | May 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [e65ad78e90](https://linux-hardware.org/?probe=e65ad78e90) | May 24, 2021 |
| HP            | 198E                        | [45fbf9c1d7](https://linux-hardware.org/?probe=45fbf9c1d7) | May 23, 2021 |
| Unknown       | Unknown                     | [ad90a50d8d](https://linux-hardware.org/?probe=ad90a50d8d) | May 22, 2021 |
| Unknown       | Unknown                     | [acaa4c3731](https://linux-hardware.org/?probe=acaa4c3731) | May 22, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d3762e2020](https://linux-hardware.org/?probe=d3762e2020) | May 21, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [662203ff7f](https://linux-hardware.org/?probe=662203ff7f) | May 21, 2021 |
| ASRock        | E3C226D2I                   | [195f9748ad](https://linux-hardware.org/?probe=195f9748ad) | May 20, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [a0188a80b1](https://linux-hardware.org/?probe=a0188a80b1) | May 20, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | [7911704f32](https://linux-hardware.org/?probe=7911704f32) | May 19, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| ASUSTek       | Z97-A                       | [0767c99abb](https://linux-hardware.org/?probe=0767c99abb) | May 19, 2021 |
| Unknown       | X79                         | [718089029d](https://linux-hardware.org/?probe=718089029d) | May 18, 2021 |
| Acer          | Veriton X2640G V:1.0        | [6e95528aca](https://linux-hardware.org/?probe=6e95528aca) | May 18, 2021 |
| ASUSTek       | PRIME Z370-A II             | [5a5c05e953](https://linux-hardware.org/?probe=5a5c05e953) | May 18, 2021 |
| ASUSTek       | Z77-A                       | [5569c32840](https://linux-hardware.org/?probe=5569c32840) | May 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [64c121a751](https://linux-hardware.org/?probe=64c121a751) | May 18, 2021 |
| ASRock        | Z370 Professional Gaming... | [2c915c81d9](https://linux-hardware.org/?probe=2c915c81d9) | May 18, 2021 |
| Dell          | 077RRV A00                  | [c9ed9d5dfa](https://linux-hardware.org/?probe=c9ed9d5dfa) | May 17, 2021 |
| ASRock        | Z270 Pro4                   | [ba92e877c3](https://linux-hardware.org/?probe=ba92e877c3) | May 17, 2021 |
| MSI           | H110I PRO AC                | [17722fe0bf](https://linux-hardware.org/?probe=17722fe0bf) | May 17, 2021 |
| Gigabyte      | Z370N WIFI-CF               | [ca8565e246](https://linux-hardware.org/?probe=ca8565e246) | May 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [43bbdc2153](https://linux-hardware.org/?probe=43bbdc2153) | May 16, 2021 |
| MSI           | X570-A PRO                  | [16c877dbfe](https://linux-hardware.org/?probe=16c877dbfe) | May 16, 2021 |
| ASUSTek       | P7P55 LX                    | [35257f4cf0](https://linux-hardware.org/?probe=35257f4cf0) | May 16, 2021 |
| Unknown       | NF-MCP78                    | [4af8e42b5a](https://linux-hardware.org/?probe=4af8e42b5a) | May 16, 2021 |
| ASRock        | FM2A55M-VG3+                | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [1d398072e8](https://linux-hardware.org/?probe=1d398072e8) | May 15, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [be75687645](https://linux-hardware.org/?probe=be75687645) | May 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [344858ad94](https://linux-hardware.org/?probe=344858ad94) | May 15, 2021 |
| Alienware     | 07HV66 A01                  | [016da6343d](https://linux-hardware.org/?probe=016da6343d) | May 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [c85191ea3e](https://linux-hardware.org/?probe=c85191ea3e) | May 15, 2021 |
| MSI           | B560M PRO-VDH WIFI          | [529fdcaf2a](https://linux-hardware.org/?probe=529fdcaf2a) | May 14, 2021 |
| Unknown       | NF-MCP78                    | [a419bff4a3](https://linux-hardware.org/?probe=a419bff4a3) | May 14, 2021 |
| ASRock        | X570 Creator                | [6ac8300ce8](https://linux-hardware.org/?probe=6ac8300ce8) | May 14, 2021 |
| ASUSTek       | M5A97                       | [3853338a60](https://linux-hardware.org/?probe=3853338a60) | May 14, 2021 |
| Acer          | Veriton X2640G V:1.0        | [924b420c67](https://linux-hardware.org/?probe=924b420c67) | May 13, 2021 |
| Dell          | 0HD5W2 A01                  | [3d9373090c](https://linux-hardware.org/?probe=3d9373090c) | May 13, 2021 |
| ASUSTek       | Benicia                     | [d8f52bab1c](https://linux-hardware.org/?probe=d8f52bab1c) | May 12, 2021 |
| ASUSTek       | Benicia                     | [a36fa0a3b4](https://linux-hardware.org/?probe=a36fa0a3b4) | May 12, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [22e9d3f5fd](https://linux-hardware.org/?probe=22e9d3f5fd) | May 12, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [fab7d18783](https://linux-hardware.org/?probe=fab7d18783) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | [370eb9dee4](https://linux-hardware.org/?probe=370eb9dee4) | May 12, 2021 |
| ASRock        | FM2A55M-VG3+                | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| MSI           | B350M GAMING PRO            | [565e8ea07c](https://linux-hardware.org/?probe=565e8ea07c) | May 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [702de808b0](https://linux-hardware.org/?probe=702de808b0) | May 11, 2021 |
| Gigabyte      | A320M-S2H-CF                | [cff0fbf297](https://linux-hardware.org/?probe=cff0fbf297) | May 11, 2021 |
| MSI           | H170A GAMING PRO            | [a7c97c0108](https://linux-hardware.org/?probe=a7c97c0108) | May 10, 2021 |
| HP            | 1494                        | [26a35b5f46](https://linux-hardware.org/?probe=26a35b5f46) | May 10, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [a3a6a201cf](https://linux-hardware.org/?probe=a3a6a201cf) | May 10, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [816b6507ca](https://linux-hardware.org/?probe=816b6507ca) | May 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [16ae1580d3](https://linux-hardware.org/?probe=16ae1580d3) | May 09, 2021 |
| ASUSTek       | ProArt B550-CREATOR         | [6969c309d4](https://linux-hardware.org/?probe=6969c309d4) | May 09, 2021 |
| Gigabyte      | H310M H                     | [993800d632](https://linux-hardware.org/?probe=993800d632) | May 08, 2021 |
| Gigabyte      | H87-HD3                     | [ef87a640ab](https://linux-hardware.org/?probe=ef87a640ab) | May 08, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [312ad18259](https://linux-hardware.org/?probe=312ad18259) | May 08, 2021 |
| Biostar       | H81MLC                      | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [d20858b78f](https://linux-hardware.org/?probe=d20858b78f) | May 08, 2021 |
| ASUSTek       | M5A78L-M LX3                | [d6af9c1156](https://linux-hardware.org/?probe=d6af9c1156) | May 07, 2021 |
| ASRock        | X570 Taichi                 | [a0c245e667](https://linux-hardware.org/?probe=a0c245e667) | May 07, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [73fd34e4a9](https://linux-hardware.org/?probe=73fd34e4a9) | May 07, 2021 |
| Acer          | Veriton S2660G              | [31f3a2c202](https://linux-hardware.org/?probe=31f3a2c202) | May 07, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [bdd3604cd8](https://linux-hardware.org/?probe=bdd3604cd8) | May 07, 2021 |
| HP            | 1497                        | [bd5ee666bd](https://linux-hardware.org/?probe=bd5ee666bd) | May 07, 2021 |
| HP            | 1497                        | [e52c3c2489](https://linux-hardware.org/?probe=e52c3c2489) | May 06, 2021 |
| HP            | 1791                        | [ad7ad34a9d](https://linux-hardware.org/?probe=ad7ad34a9d) | May 06, 2021 |
| ASUSTek       | PRIME X570-P                | [a34826ba77](https://linux-hardware.org/?probe=a34826ba77) | May 06, 2021 |
| Lenovo        | Board                       | [239c4bf44d](https://linux-hardware.org/?probe=239c4bf44d) | May 06, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [b411cc602f](https://linux-hardware.org/?probe=b411cc602f) | May 06, 2021 |
| Gigabyte      | B75M-D3P                    | [ab4f7cc66d](https://linux-hardware.org/?probe=ab4f7cc66d) | May 06, 2021 |
| ASUSTek       | P5QL-E                      | [1aee0fab6e](https://linux-hardware.org/?probe=1aee0fab6e) | May 05, 2021 |
| MSI           | P55-GD80                    | [e9002ad1ad](https://linux-hardware.org/?probe=e9002ad1ad) | May 04, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [2f8ba8af70](https://linux-hardware.org/?probe=2f8ba8af70) | May 04, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [523fba1dd3](https://linux-hardware.org/?probe=523fba1dd3) | May 04, 2021 |
| ASRock        | H310CM-HDV/M.2              | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| MSI           | B350I PRO AC                | [db10576980](https://linux-hardware.org/?probe=db10576980) | May 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [3ab07ff020](https://linux-hardware.org/?probe=3ab07ff020) | May 03, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [fec58faf85](https://linux-hardware.org/?probe=fec58faf85) | May 03, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [74bff35fdd](https://linux-hardware.org/?probe=74bff35fdd) | May 02, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [3551a877a0](https://linux-hardware.org/?probe=3551a877a0) | May 02, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [d0660819a7](https://linux-hardware.org/?probe=d0660819a7) | May 02, 2021 |
| HP            | 3029h                       | [f0912110eb](https://linux-hardware.org/?probe=f0912110eb) | May 02, 2021 |
| Gigabyte      | B450 AORUS M                | [fe7a0a48f9](https://linux-hardware.org/?probe=fe7a0a48f9) | May 02, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [1c48dea9a3](https://linux-hardware.org/?probe=1c48dea9a3) | May 02, 2021 |
| MSI           | P55-GD80                    | [2fc3e6dd6a](https://linux-hardware.org/?probe=2fc3e6dd6a) | May 01, 2021 |
| MSI           | P55-GD80                    | [a950a914fc](https://linux-hardware.org/?probe=a950a914fc) | May 01, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [e019fb0b7a](https://linux-hardware.org/?probe=e019fb0b7a) | May 01, 2021 |
| Biostar       | TB350-BTC                   | [905cd6f7b5](https://linux-hardware.org/?probe=905cd6f7b5) | May 01, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| MSI           | B365M PRO-VDH               | [e0ff71901e](https://linux-hardware.org/?probe=e0ff71901e) | Apr 30, 2021 |
| ASRock        | H81M-HG4 R4.0               | [3fb3ca76ae](https://linux-hardware.org/?probe=3fb3ca76ae) | Apr 30, 2021 |
| Lenovo        | SDK0J40700 WIN              | [000925bf4b](https://linux-hardware.org/?probe=000925bf4b) | Apr 30, 2021 |
| ASUSTek       | PRIME A520M-K               | [9f2a73a4d2](https://linux-hardware.org/?probe=9f2a73a4d2) | Apr 30, 2021 |
| Gigabyte      | B450 AORUS M                | [179e39ba13](https://linux-hardware.org/?probe=179e39ba13) | Apr 30, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [916b016881](https://linux-hardware.org/?probe=916b016881) | Apr 30, 2021 |
| ASRock        | B450 Pro4                   | [e66999f076](https://linux-hardware.org/?probe=e66999f076) | Apr 30, 2021 |
| ASRock        | A320M-HDV R4.0              | [3bb19f53e9](https://linux-hardware.org/?probe=3bb19f53e9) | Apr 30, 2021 |
| HP            | 82F2 A01                    | [abecc29894](https://linux-hardware.org/?probe=abecc29894) | Apr 30, 2021 |
| HP            | 82F2 A01                    | [6c0f1f15f5](https://linux-hardware.org/?probe=6c0f1f15f5) | Apr 30, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [fcfd291a4f](https://linux-hardware.org/?probe=fcfd291a4f) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fb11e4cdcc](https://linux-hardware.org/?probe=fb11e4cdcc) | Apr 29, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [a93721363c](https://linux-hardware.org/?probe=a93721363c) | Apr 29, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [a09dab9f9b](https://linux-hardware.org/?probe=a09dab9f9b) | Apr 29, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [492d410d60](https://linux-hardware.org/?probe=492d410d60) | Apr 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [ac1ae66d11](https://linux-hardware.org/?probe=ac1ae66d11) | Apr 29, 2021 |
| MSI           | GF615M-P33                  | [4219571ca8](https://linux-hardware.org/?probe=4219571ca8) | Apr 29, 2021 |
| ASUSTek       | H110M-K                     | [f323b316a2](https://linux-hardware.org/?probe=f323b316a2) | Apr 29, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [2ff23ca44c](https://linux-hardware.org/?probe=2ff23ca44c) | Apr 28, 2021 |
| MSI           | B250 PC MATE                | [4feda9bc8e](https://linux-hardware.org/?probe=4feda9bc8e) | Apr 28, 2021 |
| Medion        | Cattle24 1M                 | [2273e237c4](https://linux-hardware.org/?probe=2273e237c4) | Apr 28, 2021 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [69827caaf1](https://linux-hardware.org/?probe=69827caaf1) | Apr 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [97016e3ff3](https://linux-hardware.org/?probe=97016e3ff3) | Apr 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | [4a7617821f](https://linux-hardware.org/?probe=4a7617821f) | Apr 25, 2021 |
| ASRock        | K10N78D                     | [9b0a7f242b](https://linux-hardware.org/?probe=9b0a7f242b) | Apr 24, 2021 |
| Gigabyte      | B150M-D3H-CF                | [573385087f](https://linux-hardware.org/?probe=573385087f) | Apr 24, 2021 |
| MSI           | Z370-A PRO                  | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| Gigabyte      | B150M-D3H-CF                | [4ea82584ae](https://linux-hardware.org/?probe=4ea82584ae) | Apr 23, 2021 |
| eMachines     | EMCP73VT-PM                 | [4e2eabe9ea](https://linux-hardware.org/?probe=4e2eabe9ea) | Apr 21, 2021 |
| MSI           | MEG Z390 GODLIKE            | [320bab5ee4](https://linux-hardware.org/?probe=320bab5ee4) | Apr 21, 2021 |
| Gigabyte      | B450M DS3H V2               | [7b5da54a3b](https://linux-hardware.org/?probe=7b5da54a3b) | Apr 20, 2021 |
| MSI           | B350M PRO-VDH               | [50704a4b1b](https://linux-hardware.org/?probe=50704a4b1b) | Apr 20, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [3aa509bfc6](https://linux-hardware.org/?probe=3aa509bfc6) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [4046940d3e](https://linux-hardware.org/?probe=4046940d3e) | Apr 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [41035d03ea](https://linux-hardware.org/?probe=41035d03ea) | Apr 19, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [2fe3493737](https://linux-hardware.org/?probe=2fe3493737) | Apr 17, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [0691d30eea](https://linux-hardware.org/?probe=0691d30eea) | Apr 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [414dee060e](https://linux-hardware.org/?probe=414dee060e) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| ASRock        | AB350 Pro4                  | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [722e60e516](https://linux-hardware.org/?probe=722e60e516) | Apr 10, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a4b4d5abd6](https://linux-hardware.org/?probe=a4b4d5abd6) | Apr 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [0b127087c5](https://linux-hardware.org/?probe=0b127087c5) | Apr 09, 2021 |
| ASUSTek       | H110M-K                     | [b2c194ec6f](https://linux-hardware.org/?probe=b2c194ec6f) | Apr 09, 2021 |
| Lenovo        | Board                       | [d27988d8dd](https://linux-hardware.org/?probe=d27988d8dd) | Apr 09, 2021 |
| Gigabyte      | Z97N-WIFI                   | [6e9360be26](https://linux-hardware.org/?probe=6e9360be26) | Apr 09, 2021 |
| ASUSTek       | Maximus VII HERO            | [f1bdcd63e8](https://linux-hardware.org/?probe=f1bdcd63e8) | Apr 09, 2021 |
| Dell          | 0GWHMW A03                  | [a0ff0f4cf3](https://linux-hardware.org/?probe=a0ff0f4cf3) | Apr 08, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [b3b901029c](https://linux-hardware.org/?probe=b3b901029c) | Apr 07, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [2824275b63](https://linux-hardware.org/?probe=2824275b63) | Apr 07, 2021 |
| MSI           | B350M GAMING PRO            | [de5a14a4f3](https://linux-hardware.org/?probe=de5a14a4f3) | Apr 06, 2021 |
| ASUSTek       | Z87-DELUXE                  | [e4f7f8688b](https://linux-hardware.org/?probe=e4f7f8688b) | Apr 05, 2021 |
| Gigabyte      | H87-HD3                     | [a78f2d8699](https://linux-hardware.org/?probe=a78f2d8699) | Apr 05, 2021 |
| Gigabyte      | H310M H x.x                 | [ec750c2771](https://linux-hardware.org/?probe=ec750c2771) | Apr 05, 2021 |
| Unknown       | Unknown                     | [d38419f785](https://linux-hardware.org/?probe=d38419f785) | Apr 04, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [42b83bbd08](https://linux-hardware.org/?probe=42b83bbd08) | Apr 03, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [9e4b82fb49](https://linux-hardware.org/?probe=9e4b82fb49) | Apr 02, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ea8316fe72](https://linux-hardware.org/?probe=ea8316fe72) | Apr 01, 2021 |
| Gigabyte      | A520M DS3H                  | [6977cb0073](https://linux-hardware.org/?probe=6977cb0073) | Mar 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e6a1ba54cc](https://linux-hardware.org/?probe=e6a1ba54cc) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | [fcc9dabb3d](https://linux-hardware.org/?probe=fcc9dabb3d) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | [ed7f2979b9](https://linux-hardware.org/?probe=ed7f2979b9) | Mar 30, 2021 |
| Alienware     | 0FRTKJ A00                  | [e31c5f36aa](https://linux-hardware.org/?probe=e31c5f36aa) | Mar 28, 2021 |
| MSI           | Z490-A PRO                  | [cf1b5653e8](https://linux-hardware.org/?probe=cf1b5653e8) | Mar 28, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [b41b0c2610](https://linux-hardware.org/?probe=b41b0c2610) | Mar 28, 2021 |
| Gigabyte      | H87-HD3                     | [0f0ff492d9](https://linux-hardware.org/?probe=0f0ff492d9) | Mar 27, 2021 |
| Gigabyte      | H87-HD3                     | [87cb9f98e5](https://linux-hardware.org/?probe=87cb9f98e5) | Mar 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0e12cc8e95](https://linux-hardware.org/?probe=0e12cc8e95) | Mar 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [a0f771669c](https://linux-hardware.org/?probe=a0f771669c) | Mar 24, 2021 |
| Gigabyte      | A320M-H-CF                  | [01c43fc8b4](https://linux-hardware.org/?probe=01c43fc8b4) | Mar 23, 2021 |
| MSI           | 760GM-P21                   | [91a13be8c4](https://linux-hardware.org/?probe=91a13be8c4) | Mar 17, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6124e0aa83](https://linux-hardware.org/?probe=6124e0aa83) | Mar 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [07cd9eac56](https://linux-hardware.org/?probe=07cd9eac56) | Mar 17, 2021 |
| Gigabyte      | Z490 VISION D               | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | [6b611bf344](https://linux-hardware.org/?probe=6b611bf344) | Feb 26, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [fdc4baf022](https://linux-hardware.org/?probe=fdc4baf022) | Feb 23, 2021 |
| ECS           | MCP61M-M3                   | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| ASUSTek       | PRIME X570-PRO              | [e3a5631517](https://linux-hardware.org/?probe=e3a5631517) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [f695c35adf](https://linux-hardware.org/?probe=f695c35adf) | Oct 12, 2020 |
| Positivo      | POS-PARS760GCD              | [482e549764](https://linux-hardware.org/?probe=482e549764) | Sep 05, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                              | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| 5.13.12-200.fc34.x86_64                              | 39       | 7.71%   |
| 5.12.13-300.fc34.x86_64                              | 32       | 6.32%   |
| 5.11.12-300.fc34.x86_64                              | 27       | 5.34%   |
| 5.12.8-300.fc34.x86_64                               | 25       | 4.94%   |
| 5.11.16-300.fc34.x86_64                              | 23       | 4.55%   |
| 5.13.4-200.fc34.x86_64                               | 17       | 3.36%   |
| 5.11.17-300.fc34.x86_64                              | 17       | 3.36%   |
| 5.13.6-200.fc34.x86_64                               | 16       | 3.16%   |
| 5.12.9-300.fc34.x86_64                               | 16       | 3.16%   |
| 5.12.7-300.fc34.x86_64                               | 16       | 3.16%   |
| 5.12.15-300.fc34.x86_64                              | 16       | 3.16%   |
| 5.12.12-300.fc34.x86_64                              | 16       | 3.16%   |
| 5.13.9-200.fc34.x86_64                               | 15       | 2.96%   |
| 5.13.16-200.fc34.x86_64                              | 15       | 2.96%   |
| 5.13.14-200.fc34.x86_64                              | 15       | 2.96%   |
| 5.13.8-200.fc34.x86_64                               | 14       | 2.77%   |
| 5.12.14-300.fc34.x86_64                              | 14       | 2.77%   |
| 5.11.20-300.fc34.x86_64                              | 14       | 2.77%   |
| 5.11.19-300.fc34.x86_64                              | 14       | 2.77%   |
| 5.11.18-300.fc34.x86_64                              | 12       | 2.37%   |
| 5.11.11-300.fc34.x86_64                              | 12       | 2.37%   |
| 5.12.11-300.fc34.x86_64                              | 11       | 2.17%   |
| 5.13.10-200.fc34.x86_64                              | 10       | 1.98%   |
| 5.13.19-200.fc34.x86_64                              | 9        | 1.78%   |
| 5.12.6-300.fc34.x86_64                               | 9        | 1.78%   |
| 5.13.7-200.fc34.x86_64                               | 7        | 1.38%   |
| 5.13.15-200.fc34.x86_64                              | 7        | 1.38%   |
| 5.12.10-300.fc34.x86_64                              | 7        | 1.38%   |
| 5.13.13-200.fc34.x86_64                              | 6        | 1.19%   |
| 5.11.3-300.fc34.x86_64                               | 5        | 0.99%   |
| 5.13.5-200.fc34.x86_64                               | 4        | 0.79%   |
| 5.11.15-300.fc34.x86_64                              | 4        | 0.79%   |
| 5.11.10-300.fc34.x86_64                              | 4        | 0.79%   |
| 5.12.17-300.fc34.x86_64                              | 3        | 0.59%   |
| 5.11.9-300.fc34.x86_64                               | 3        | 0.59%   |
| 5.11.14-300.fc34.x86_64                              | 3        | 0.59%   |
| 5.11.13-300.fc34.x86_64                              | 3        | 0.59%   |
| 5.13.1-300.fc34.x86_64                               | 2        | 0.4%    |
| 5.12.5-300.fc34.x86_64                               | 2        | 0.4%    |
| 5.11.8-300.fc34.x86_64                               | 2        | 0.4%    |
| 5.11.21-300.fc34.x86_64                              | 2        | 0.4%    |
| 5.11.0-156.fc34.x86_64                               | 2        | 0.4%    |
| 5.9.0-0.rc8.20201009git7575fdda569b.32.fc34.x86_64   | 1        | 0.2%    |
| 5.13.8-xm1cacule.0.fc34.x86_64                       | 1        | 0.2%    |
| 5.13.4-201.fsync.fc34.x86_64                         | 1        | 0.2%    |
| 5.13.14-zen                                          | 1        | 0.2%    |
| 5.13.0-xm1.1.fc34.x86_64                             | 1        | 0.2%    |
| 5.12.7-16-Yeoreum                                    | 1        | 0.2%    |
| 5.12.2-300.fc34.x86_64                               | 1        | 0.2%    |
| 5.12.14-300.fc34.x86_64+debug                        | 1        | 0.2%    |
| 5.12.11-200.fc33.x86_64                              | 1        | 0.2%    |
| 5.12.0-xanmod1_cacule.0.fc34                         | 1        | 0.2%    |
| 5.11.6-300.fc34.x86_64                               | 1        | 0.2%    |
| 5.11.2-300.fc34.x86_64                               | 1        | 0.2%    |
| 5.11.0-0.rc5.20210127git2ab38c17aac1.136.fc34.x86_64 | 1        | 0.2%    |
| 5.10.47-1.fc32.qubes.x86_64                          | 1        | 0.2%    |
| 5.10.21-200.fc33.x86_64                              | 1        | 0.2%    |
| 5.10.0-0.rc1.20201028gited8780e3f2ec.57.fc34.x86_64  | 1        | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.12 | 39       | 7.71%   |
| 5.12.13 | 32       | 6.32%   |
| 5.11.12 | 27       | 5.34%   |
| 5.12.8  | 25       | 4.94%   |
| 5.11.16 | 23       | 4.55%   |
| 5.13.4  | 18       | 3.56%   |
| 5.12.7  | 17       | 3.36%   |
| 5.11.17 | 17       | 3.36%   |
| 5.13.6  | 16       | 3.16%   |
| 5.13.14 | 16       | 3.16%   |
| 5.12.9  | 16       | 3.16%   |
| 5.12.15 | 16       | 3.16%   |
| 5.12.12 | 16       | 3.16%   |
| 5.13.9  | 15       | 2.96%   |
| 5.13.8  | 15       | 2.96%   |
| 5.13.16 | 15       | 2.96%   |
| 5.12.14 | 15       | 2.96%   |
| 5.11.20 | 14       | 2.77%   |
| 5.11.19 | 14       | 2.77%   |
| 5.12.11 | 12       | 2.37%   |
| 5.11.18 | 12       | 2.37%   |
| 5.11.11 | 12       | 2.37%   |
| 5.13.10 | 10       | 1.98%   |
| 5.13.19 | 9        | 1.78%   |
| 5.12.6  | 9        | 1.78%   |
| 5.13.7  | 7        | 1.38%   |
| 5.13.15 | 7        | 1.38%   |
| 5.12.10 | 7        | 1.38%   |
| 5.13.13 | 6        | 1.19%   |
| 5.11.3  | 5        | 0.99%   |
| 5.13.5  | 4        | 0.79%   |
| 5.11.15 | 4        | 0.79%   |
| 5.11.10 | 4        | 0.79%   |
| 5.12.17 | 3        | 0.59%   |
| 5.11.9  | 3        | 0.59%   |
| 5.11.14 | 3        | 0.59%   |
| 5.11.13 | 3        | 0.59%   |
| 5.11.0  | 3        | 0.59%   |
| 5.13.1  | 2        | 0.4%    |
| 5.12.5  | 2        | 0.4%    |
| 5.11.8  | 2        | 0.4%    |
| 5.11.21 | 2        | 0.4%    |
| 5.9.0   | 1        | 0.2%    |
| 5.13.0  | 1        | 0.2%    |
| 5.12.2  | 1        | 0.2%    |
| 5.12.0  | 1        | 0.2%    |
| 5.11.6  | 1        | 0.2%    |
| 5.11.2  | 1        | 0.2%    |
| 5.10.47 | 1        | 0.2%    |
| 5.10.21 | 1        | 0.2%    |
| 5.10.0  | 1        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.12    | 158      | 34.35%  |
| 5.13    | 157      | 34.13%  |
| 5.11    | 141      | 30.65%  |
| 5.10    | 3        | 0.65%   |
| 5.9     | 1        | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 418      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 307      | 72.41%  |
| KDE           | 27       | 6.37%   |
| KDE5          | 23       | 5.42%   |
| Cinnamon      | 16       | 3.77%   |
| Unknown       | 16       | 3.77%   |
| X-Cinnamon    | 10       | 2.36%   |
| MATE          | 9        | 2.12%   |
| XFCE          | 6        | 1.42%   |
| GNOME Classic | 3        | 0.71%   |
| qtile         | 1        | 0.24%   |
| openbox       | 1        | 0.24%   |
| NsCDE         | 1        | 0.24%   |
| LXDE          | 1        | 0.24%   |
| KDE4          | 1        | 0.24%   |
| Deepin        | 1        | 0.24%   |
| awesome       | 1        | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 232      | 52.97%  |
| X11     | 180      | 41.1%   |
| Tty     | 18       | 4.11%   |
| Unknown | 8        | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 250      | 57.87%  |
| GDM     | 127      | 29.4%   |
| LightDM | 21       | 4.86%   |
| SDDM    | 19       | 4.4%    |
| TDM     | 14       | 3.24%   |
| KDM     | 1        | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 186      | 44.18%  |
| en_GB   | 37       | 8.79%   |
| pt_BR   | 28       | 6.65%   |
| ru_RU   | 23       | 5.46%   |
| fr_FR   | 19       | 4.51%   |
| en_CA   | 19       | 4.51%   |
| en_AU   | 19       | 4.51%   |
| de_DE   | 18       | 4.28%   |
| pl_PL   | 8        | 1.9%    |
| ja_JP   | 5        | 1.19%   |
| it_IT   | 5        | 1.19%   |
| es_ES   | 4        | 0.95%   |
| ru_UA   | 3        | 0.71%   |
| en_IN   | 3        | 0.71%   |
| cs_CZ   | 3        | 0.71%   |
| Unknown | 3        | 0.71%   |
| sk_SK   | 2        | 0.48%   |
| nl_NL   | 2        | 0.48%   |
| nl_BE   | 2        | 0.48%   |
| fr_CH   | 2        | 0.48%   |
| es_MX   | 2        | 0.48%   |
| es_CL   | 2        | 0.48%   |
| es_AR   | 2        | 0.48%   |
| en_SG   | 2        | 0.48%   |
| en_NZ   | 2        | 0.48%   |
| C       | 2        | 0.48%   |
| zh_TW   | 1        | 0.24%   |
| uk_UA   | 1        | 0.24%   |
| ko_KR   | 1        | 0.24%   |
| hu_HU   | 1        | 0.24%   |
| fi_FI   | 1        | 0.24%   |
| es_UY   | 1        | 0.24%   |
| es_PA   | 1        | 0.24%   |
| es_GT   | 1        | 0.24%   |
| es_EC   | 1        | 0.24%   |
| es_DO   | 1        | 0.24%   |
| en_ZA   | 1        | 0.24%   |
| en_IL   | 1        | 0.24%   |
| en_DK   | 1        | 0.24%   |
| el_GR   | 1        | 0.24%   |
| da_DK   | 1        | 0.24%   |
| ca_ES   | 1        | 0.24%   |
| ca_AD   | 1        | 0.24%   |
| ar_KW   | 1        | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 271      | 64.68%  |
| BIOS | 148      | 35.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 269      | 64.05%  |
| Ext4                | 124      | 29.52%  |
| Xfs                 | 24       | 5.71%   |
| Zfs                 | 2        | 0.48%   |
| Fuse.fuse-overlayfs | 1        | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 247      | 57.85%  |
| GPT     | 139      | 32.55%  |
| MBR     | 41       | 9.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 369      | 87.23%  |
| Yes       | 54       | 12.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 326      | 77.07%  |
| Yes       | 97       | 22.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 114      | 27.27%  |
| Gigabyte Technology | 88       | 21.05%  |
| MSI                 | 57       | 13.64%  |
| ASRock              | 48       | 11.48%  |
| Hewlett-Packard     | 27       | 6.46%   |
| Dell                | 23       | 5.5%    |
| Lenovo              | 10       | 2.39%   |
| Intel               | 8        | 1.91%   |
| Unknown             | 6        | 1.44%   |
| Biostar             | 5        | 1.2%    |
| Acer                | 5        | 1.2%    |
| Fujitsu             | 4        | 0.96%   |
| ECS                 | 3        | 0.72%   |
| Alienware           | 3        | 0.72%   |
| Huanan              | 2        | 0.48%   |
| EVGA                | 2        | 0.48%   |
| SYWZ                | 1        | 0.24%   |
| System76            | 1        | 0.24%   |
| Positivo            | 1        | 0.24%   |
| Medion              | 1        | 0.24%   |
| Google              | 1        | 0.24%   |
| Gateway             | 1        | 0.24%   |
| Foxconn             | 1        | 0.24%   |
| eMachines           | 1        | 0.24%   |
| Chuwi               | 1        | 0.24%   |
| BESSTAR Tech        | 1        | 0.24%   |
| ASRockRack          | 1        | 0.24%   |
| Apple               | 1        | 0.24%   |
| AMD                 | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 11       | 2.63%   |
| MSI MS-7C37                              | 7        | 1.67%   |
| Unknown                                  | 6        | 1.44%   |
| ASUS TUF GAMING X570-PLUS                | 4        | 0.96%   |
| MSI MS-7C84                              | 3        | 0.72%   |
| MSI MS-7C02                              | 3        | 0.72%   |
| Gigabyte B450M DS3H                      | 3        | 0.72%   |
| Gigabyte B450 I AORUS PRO WIFI           | 3        | 0.72%   |
| ASUS TUF GAMING B550M-PLUS               | 3        | 0.72%   |
| ASUS ROG STRIX X570-E GAMING             | 3        | 0.72%   |
| ASUS ROG STRIX B450-F GAMING             | 3        | 0.72%   |
| MSI MS-7C91                              | 2        | 0.48%   |
| MSI MS-7C35                              | 2        | 0.48%   |
| MSI MS-7B98                              | 2        | 0.48%   |
| MSI MS-7B85                              | 2        | 0.48%   |
| MSI MS-7B48                              | 2        | 0.48%   |
| MSI MS-7A38                              | 2        | 0.48%   |
| Intel H61                                | 2        | 0.48%   |
| HP EliteDesk 800 G1 SFF                  | 2        | 0.48%   |
| HP Compaq 6200 Pro SFF PC                | 2        | 0.48%   |
| Gigabyte Z370N WIFI                      | 2        | 0.48%   |
| Gigabyte Z170-D3H                        | 2        | 0.48%   |
| Gigabyte X570 AORUS PRO WIFI             | 2        | 0.48%   |
| Gigabyte X570 AORUS ELITE WIFI           | 2        | 0.48%   |
| Gigabyte B450 AORUS PRO WIFI             | 2        | 0.48%   |
| Gigabyte B250M-DS3H                      | 2        | 0.48%   |
| Gigabyte B150M-D3H                       | 2        | 0.48%   |
| Gigabyte A320M-S2H                       | 2        | 0.48%   |
| Dell OptiPlex GX620                      | 2        | 0.48%   |
| Dell OptiPlex 9020                       | 2        | 0.48%   |
| Dell OptiPlex 7040                       | 2        | 0.48%   |
| Dell OptiPlex 3050                       | 2        | 0.48%   |
| Biostar X370GTN                          | 2        | 0.48%   |
| ASUS TUF GAMING B550-PLUS                | 2        | 0.48%   |
| ASUS ROG STRIX Z370-H GAMING             | 2        | 0.48%   |
| ASUS ROG STRIX X570-F GAMING             | 2        | 0.48%   |
| ASUS ROG STRIX B550-I GAMING             | 2        | 0.48%   |
| ASUS ROG Maximus XI FORMULA              | 2        | 0.48%   |
| ASUS ROG CROSSHAIR VIII IMPACT           | 2        | 0.48%   |
| ASUS ROG CROSSHAIR VII HERO              | 2        | 0.48%   |
| ASUS PRIME Z390-A                        | 2        | 0.48%   |
| ASUS PRIME Z370-A                        | 2        | 0.48%   |
| ASUS PRIME X470-PRO                      | 2        | 0.48%   |
| ASUS PRIME B460M-A                       | 2        | 0.48%   |
| ASUS PRIME B450M-GAMING/BR               | 2        | 0.48%   |
| ASUS H110M-K                             | 2        | 0.48%   |
| ASUS A8R32-MVP Deluxe                    | 2        | 0.48%   |
| ASRock B450 Pro4                         | 2        | 0.48%   |
| ASRock AB350 Pro4                        | 2        | 0.48%   |
| ASRock A320M-HDV R4.0                    | 2        | 0.48%   |
| SYWZ S200 Series                         | 1        | 0.24%   |
| System76 Thelio Mira                     | 1        | 0.24%   |
| Positivo POS-MI945AA                     | 1        | 0.24%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1        | 0.24%   |
| MSI MS-7D18                              | 1        | 0.24%   |
| MSI MS-7D15                              | 1        | 0.24%   |
| MSI MS-7C95                              | 1        | 0.24%   |
| MSI MS-7C90                              | 1        | 0.24%   |
| MSI MS-7C82                              | 1        | 0.24%   |
| MSI MS-7C75                              | 1        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 31       | 7.42%   |
| ASUS PRIME           | 20       | 4.78%   |
| Dell OptiPlex        | 15       | 3.59%   |
| ASUS TUF             | 11       | 2.63%   |
| ASUS All             | 11       | 2.63%   |
| HP EliteDesk         | 8        | 1.91%   |
| Gigabyte B450        | 8        | 1.91%   |
| MSI MS-7C37          | 7        | 1.67%   |
| Lenovo ThinkCentre   | 6        | 1.44%   |
| HP Compaq            | 6        | 1.44%   |
| Gigabyte X570        | 6        | 1.44%   |
| Unknown              | 6        | 1.44%   |
| Gigabyte B450M       | 5        | 1.2%    |
| Fujitsu ESPRIMO      | 4        | 0.96%   |
| ASUS P8H61-M         | 4        | 0.96%   |
| ASRock B450          | 4        | 0.96%   |
| MSI MS-7C84          | 3        | 0.72%   |
| MSI MS-7C02          | 3        | 0.72%   |
| Gigabyte Z390        | 3        | 0.72%   |
| Dell XPS             | 3        | 0.72%   |
| ASRock X570          | 3        | 0.72%   |
| ASRock X399          | 3        | 0.72%   |
| ASRock B550          | 3        | 0.72%   |
| Acer Aspire          | 3        | 0.72%   |
| MSI MS-7C91          | 2        | 0.48%   |
| MSI MS-7C35          | 2        | 0.48%   |
| MSI MS-7B98          | 2        | 0.48%   |
| MSI MS-7B85          | 2        | 0.48%   |
| MSI MS-7B48          | 2        | 0.48%   |
| MSI MS-7A38          | 2        | 0.48%   |
| Intel H61            | 2        | 0.48%   |
| Huanan X79           | 2        | 0.48%   |
| HP ProDesk           | 2        | 0.48%   |
| HP Pavilion          | 2        | 0.48%   |
| Gigabyte Z370N       | 2        | 0.48%   |
| Gigabyte Z170-D3H    | 2        | 0.48%   |
| Gigabyte X470        | 2        | 0.48%   |
| Gigabyte H310M       | 2        | 0.48%   |
| Gigabyte B550        | 2        | 0.48%   |
| Gigabyte B250M-DS3H  | 2        | 0.48%   |
| Gigabyte B150M-D3H   | 2        | 0.48%   |
| Gigabyte A320M-S2H   | 2        | 0.48%   |
| Biostar X370GTN      | 2        | 0.48%   |
| ASUS SABERTOOTH      | 2        | 0.48%   |
| ASUS M5A97           | 2        | 0.48%   |
| ASUS M5A78L-M        | 2        | 0.48%   |
| ASUS H110M-K         | 2        | 0.48%   |
| ASUS A8R32-MVP       | 2        | 0.48%   |
| ASRock Z390          | 2        | 0.48%   |
| ASRock AB350         | 2        | 0.48%   |
| ASRock A320M-HDV     | 2        | 0.48%   |
| Alienware Area-51    | 2        | 0.48%   |
| SYWZ S200            | 1        | 0.24%   |
| System76 Thelio      | 1        | 0.24%   |
| Positivo POS-MI945AA | 1        | 0.24%   |
| MSI Z390             | 1        | 0.24%   |
| MSI MS-7D18          | 1        | 0.24%   |
| MSI MS-7D15          | 1        | 0.24%   |
| MSI MS-7C95          | 1        | 0.24%   |
| MSI MS-7C90          | 1        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 71       | 16.99%  |
| 2020    | 71       | 16.99%  |
| 2019    | 63       | 15.07%  |
| 2018    | 45       | 10.77%  |
| 2016    | 22       | 5.26%   |
| 2010    | 20       | 4.78%   |
| 2015    | 19       | 4.55%   |
| 2013    | 19       | 4.55%   |
| 2017    | 17       | 4.07%   |
| 2014    | 16       | 3.83%   |
| 2012    | 15       | 3.59%   |
| 2011    | 13       | 3.11%   |
| 2009    | 13       | 3.11%   |
| 2008    | 6        | 1.44%   |
| 2006    | 4        | 0.96%   |
| 2007    | 2        | 0.48%   |
| 2005    | 1        | 0.24%   |
| Unknown | 1        | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 418      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 403      | 95.5%   |
| Enabled  | 19       | 4.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 417      | 99.76%  |
| Yes  | 1        | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 123      | 28.94%  |
| 32.01-64.0  | 103      | 24.24%  |
| 8.01-16.0   | 70       | 16.47%  |
| 4.01-8.0    | 50       | 11.76%  |
| 3.01-4.0    | 32       | 7.53%   |
| 64.01-256.0 | 27       | 6.35%   |
| 24.01-32.0  | 14       | 3.29%   |
| 2.01-3.0    | 4        | 0.94%   |
| 1.01-2.0    | 2        | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 134      | 28.82%  |
| 2.01-3.0   | 109      | 23.44%  |
| 3.01-4.0   | 90       | 19.35%  |
| 1.01-2.0   | 73       | 15.7%   |
| 8.01-16.0  | 31       | 6.67%   |
| 0.51-1.0   | 13       | 2.8%    |
| 16.01-24.0 | 6        | 1.29%   |
| 24.01-32.0 | 4        | 0.86%   |
| 0.01-0.5   | 4        | 0.86%   |
| 32.01-64.0 | 1        | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 117      | 27.27%  |
| 3      | 112      | 26.11%  |
| 1      | 99       | 23.08%  |
| 4      | 51       | 11.89%  |
| 5      | 23       | 5.36%   |
| 6      | 10       | 2.33%   |
| 8      | 7        | 1.63%   |
| 0      | 4        | 0.93%   |
| 7      | 3        | 0.7%    |
| 12     | 2        | 0.47%   |
| 9      | 1        | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 263      | 62.47%  |
| Yes       | 158      | 37.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 411      | 98.33%  |
| No        | 7        | 1.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 214      | 50.59%  |
| Yes       | 209      | 49.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 227      | 53.92%  |
| Yes       | 194      | 46.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 88       | 21%     |
| Brazil             | 34       | 8.11%   |
| Germany            | 31       | 7.4%    |
| Russia             | 23       | 5.49%   |
| Canada             | 22       | 5.25%   |
| Australia          | 22       | 5.25%   |
| France             | 19       | 4.53%   |
| UK                 | 18       | 4.3%    |
| Poland             | 12       | 2.86%   |
| Spain              | 11       | 2.63%   |
| Sweden             | 9        | 2.15%   |
| Italy              | 9        | 2.15%   |
| India              | 9        | 2.15%   |
| Ukraine            | 8        | 1.91%   |
| Switzerland        | 8        | 1.91%   |
| Belgium            | 6        | 1.43%   |
| Netherlands        | 5        | 1.19%   |
| Japan              | 5        | 1.19%   |
| Czechia            | 5        | 1.19%   |
| Chile              | 4        | 0.95%   |
| Belarus            | 4        | 0.95%   |
| Turkey             | 3        | 0.72%   |
| Slovakia           | 3        | 0.72%   |
| Norway             | 3        | 0.72%   |
| New Zealand        | 3        | 0.72%   |
| Mexico             | 3        | 0.72%   |
| Finland            | 3        | 0.72%   |
| Estonia            | 3        | 0.72%   |
| Argentina          | 3        | 0.72%   |
| Romania            | 2        | 0.48%   |
| Portugal           | 2        | 0.48%   |
| Pakistan           | 2        | 0.48%   |
| Malaysia           | 2        | 0.48%   |
| Hungary            | 2        | 0.48%   |
| Greece             | 2        | 0.48%   |
| Denmark            | 2        | 0.48%   |
| Venezuela          | 1        | 0.24%   |
| Uruguay            | 1        | 0.24%   |
| UAE                | 1        | 0.24%   |
| Taiwan             | 1        | 0.24%   |
| South Korea        | 1        | 0.24%   |
| South Africa       | 1        | 0.24%   |
| Slovenia           | 1        | 0.24%   |
| Singapore          | 1        | 0.24%   |
| Serbia             | 1        | 0.24%   |
| Philippines        | 1        | 0.24%   |
| Panama             | 1        | 0.24%   |
| Martinique         | 1        | 0.24%   |
| Macao              | 1        | 0.24%   |
| Luxembourg         | 1        | 0.24%   |
| Kuwait             | 1        | 0.24%   |
| Kenya              | 1        | 0.24%   |
| Ivory Coast        | 1        | 0.24%   |
| Israel             | 1        | 0.24%   |
| Iran               | 1        | 0.24%   |
| Indonesia          | 1        | 0.24%   |
| Guatemala          | 1        | 0.24%   |
| Egypt              | 1        | 0.24%   |
| Ecuador            | 1        | 0.24%   |
| Dominican Republic | 1        | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Sydney             | 16       | 3.69%   |
| St Petersburg      | 7        | 1.61%   |
| Yekaterinburg      | 3        | 0.69%   |
| Ufa                | 3        | 0.69%   |
| Riverside          | 3        | 0.69%   |
| Pymble             | 3        | 0.69%   |
| Paris              | 3        | 0.69%   |
| Overland Park      | 3        | 0.69%   |
| Moscow             | 3        | 0.69%   |
| Minsk              | 3        | 0.69%   |
| London             | 3        | 0.69%   |
| Kharkiv            | 3        | 0.69%   |
| Brasília          | 3        | 0.69%   |
| Berlin             | 3        | 0.69%   |
| Belo Horizonte     | 3        | 0.69%   |
| Zurich             | 2        | 0.46%   |
| Wroclaw            | 2        | 0.46%   |
| Vijayawada         | 2        | 0.46%   |
| Toronto            | 2        | 0.46%   |
| Tallinn            | 2        | 0.46%   |
| Santiago           | 2        | 0.46%   |
| Saitama            | 2        | 0.46%   |
| Saint Paul         | 2        | 0.46%   |
| Porto Alegre       | 2        | 0.46%   |
| Pflugerville       | 2        | 0.46%   |
| Naples             | 2        | 0.46%   |
| Munich             | 2        | 0.46%   |
| Milan              | 2        | 0.46%   |
| Miami              | 2        | 0.46%   |
| Melbourne          | 2        | 0.46%   |
| Madrid             | 2        | 0.46%   |
| Lodz               | 2        | 0.46%   |
| La Florida         | 2        | 0.46%   |
| Krakow             | 2        | 0.46%   |
| Kota Kinabalu      | 2        | 0.46%   |
| Istanbul           | 2        | 0.46%   |
| Honolulu           | 2        | 0.46%   |
| Hemhofen           | 2        | 0.46%   |
| Fort Worth         | 2        | 0.46%   |
| Dallas             | 2        | 0.46%   |
| Cologne            | 2        | 0.46%   |
| Cheyenne           | 2        | 0.46%   |
| Chemnitz           | 2        | 0.46%   |
| Chatel-Saint-Denis | 2        | 0.46%   |
| Brussels           | 2        | 0.46%   |
| Bratislava         | 2        | 0.46%   |
| Auckland           | 2        | 0.46%   |
| Zuidwolde          | 1        | 0.23%   |
| Zuccoli            | 1        | 0.23%   |
| Zhukovskiy         | 1        | 0.23%   |
| Zgorzelec          | 1        | 0.23%   |
| Zaporizhzhya       | 1        | 0.23%   |
| Zagreb             | 1        | 0.23%   |
| York               | 1        | 0.23%   |
| Yokohama           | 1        | 0.23%   |
| Yogyakarta         | 1        | 0.23%   |
| Worthing           | 1        | 0.23%   |
| Woodstock          | 1        | 0.23%   |
| Woodbridge         | 1        | 0.23%   |
| Winona             | 1        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 156      | 323    | 18.1%   |
| WDC                       | 147      | 245    | 17.05%  |
| Seagate                   | 140      | 242    | 16.24%  |
| Kingston                  | 60       | 75     | 6.96%   |
| Crucial                   | 50       | 76     | 5.8%    |
| Toshiba                   | 42       | 67     | 4.87%   |
| Sandisk                   | 39       | 44     | 4.52%   |
| Hitachi                   | 32       | 44     | 3.71%   |
| Intel                     | 24       | 39     | 2.78%   |
| Phison                    | 16       | 21     | 1.86%   |
| A-DATA Technology         | 12       | 15     | 1.39%   |
| Micron Technology         | 10       | 12     | 1.16%   |
| Corsair                   | 10       | 14     | 1.16%   |
| Unknown                   | 8        | 10     | 0.93%   |
| SK Hynix                  | 8        | 11     | 0.93%   |
| OCZ                       | 7        | 12     | 0.81%   |
| SPCC                      | 6        | 7      | 0.7%    |
| PNY                       | 6        | 9      | 0.7%    |
| Micron/Crucial Technology | 6        | 7      | 0.7%    |
| XPG                       | 5        | 6      | 0.58%   |
| HGST                      | 5        | 14     | 0.58%   |
| Gigabyte Technology       | 5        | 6      | 0.58%   |
| Silicon Motion            | 4        | 4      | 0.46%   |
| Patriot                   | 4        | 4      | 0.46%   |
| MAXTOR                    | 4        | 5      | 0.46%   |
| Team                      | 3        | 4      | 0.35%   |
| SABRENT                   | 3        | 3      | 0.35%   |
| KingSpec                  | 3        | 6      | 0.35%   |
| GOODRAM                   | 3        | 3      | 0.35%   |
| Apple                     | 3        | 3      | 0.35%   |
| Transcend                 | 2        | 2      | 0.23%   |
| Phison Electronics        | 2        | 3      | 0.23%   |
| LITEONIT                  | 2        | 2      | 0.23%   |
| Hewlett-Packard           | 2        | 2      | 0.23%   |
| China                     | 2        | 2      | 0.23%   |
| ASMT                      | 2        | 2      | 0.23%   |
| Apacer                    | 2        | 3      | 0.23%   |
| USB 3.0                   | 1        | 1      | 0.12%   |
| Union Memory              | 1        | 1      | 0.12%   |
| Ugreen                    | 1        | 1      | 0.12%   |
| Synology                  | 1        | 1      | 0.12%   |
| SSK                       | 1        | 1      | 0.12%   |
| Smartbuy                  | 1        | 1      | 0.12%   |
| SMART                     | 1        | 1      | 0.12%   |
| Realtek Semiconductor     | 1        | 1      | 0.12%   |
| PLEXTOR                   | 1        | 2      | 0.12%   |
| PHD 3.0                   | 1        | 1      | 0.12%   |
| OWC                       | 1        | 1      | 0.12%   |
| Mushkin                   | 1        | 3      | 0.12%   |
| MG                        | 1        | 1      | 0.12%   |
| MaxDigital                | 1        | 1      | 0.12%   |
| Magnetic Data             | 1        | 1      | 0.12%   |
| LITEON                    | 1        | 1      | 0.12%   |
| Lexar                     | 1        | 1      | 0.12%   |
| KLEVV                     | 1        | 1      | 0.12%   |
| JMicron                   | 1        | 1      | 0.12%   |
| Intenso                   | 1        | 1      | 0.12%   |
| Inateck                   | 1        | 1      | 0.12%   |
| Hoodisk                   | 1        | 2      | 0.12%   |
| DREVO                     | 1        | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB       | 20       | 1.88%   |
| Samsung SSD 860 EVO 1TB            | 18       | 1.69%   |
| Seagate ST2000DM008-2FR102 2TB     | 15       | 1.41%   |
| Samsung SSD 860 EVO 500GB          | 14       | 1.32%   |
| Kingston SA400S37240G 240GB SSD    | 12       | 1.13%   |
| Samsung SSD 850 EVO 500GB          | 11       | 1.04%   |
| Samsung SSD 850 EVO 250GB          | 11       | 1.04%   |
| Samsung NVMe SSD Drive 250GB       | 11       | 1.04%   |
| Samsung NVMe SSD Drive 1TB         | 11       | 1.04%   |
| Toshiba DT01ACA100 1TB             | 10       | 0.94%   |
| Seagate ST500DM002-1BD142 500GB    | 10       | 0.94%   |
| Seagate ST1000DM010-2EP102 1TB     | 10       | 0.94%   |
| Sandisk NVMe SSD Drive 500GB       | 9        | 0.85%   |
| Crucial CT500MX500SSD1 500GB       | 9        | 0.85%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 8        | 0.75%   |
| Samsung SSD 860 QVO 1TB            | 8        | 0.75%   |
| Kingston SA400S37480G 480GB SSD    | 8        | 0.75%   |
| Kingston SA400S37120G 120GB SSD    | 8        | 0.75%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 6        | 0.56%   |
| Toshiba DT01ACA200 2TB             | 6        | 0.56%   |
| Seagate ST3500418AS 500GB          | 6        | 0.56%   |
| Seagate ST1000DM003-1ER162 1TB     | 6        | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB     | 6        | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB       | 6        | 0.56%   |
| Samsung SSD 840 EVO 250GB          | 6        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB        | 6        | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB           | 5        | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB     | 5        | 0.47%   |
| Seagate ST1000DM003-1SB102 1TB     | 5        | 0.47%   |
| Sandisk NVMe SSD Drive 1TB         | 5        | 0.47%   |
| Samsung SSD 970 EVO 500GB          | 5        | 0.47%   |
| Phison NVMe SSD Drive 1024GB       | 5        | 0.47%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 5        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD   | 5        | 0.47%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 4        | 0.38%   |
| WDC WD10EZEX-08M2NA0 1TB           | 4        | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4        | 0.38%   |
| Unknown SD/MMC/MS PRO 128GB        | 4        | 0.38%   |
| Toshiba HDWD110 1TB                | 4        | 0.38%   |
| Seagate ST8000DM004-2CX188 8TB     | 4        | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB     | 4        | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4        | 0.38%   |
| Seagate ST1000DM003-1CH162 1TB     | 4        | 0.38%   |
| Samsung SSD 980 PRO 1TB            | 4        | 0.38%   |
| Samsung SSD 870 EVO 1TB            | 4        | 0.38%   |
| Samsung SSD 850 PRO 256GB          | 4        | 0.38%   |
| Samsung NVMe SSD Drive 512GB       | 4        | 0.38%   |
| Intel NVMe SSD Drive 512GB         | 4        | 0.38%   |
| Hitachi HDS721050CLA362 500GB      | 4        | 0.38%   |
| Hitachi HDS721010CLA332 1TB        | 4        | 0.38%   |
| Crucial CT240BX500SSD1 240GB       | 4        | 0.38%   |
| Crucial CT1000BX500SSD1 1TB        | 4        | 0.38%   |
| XPG NVMe SSD Drive 512GB           | 3        | 0.28%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 3        | 0.28%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 3        | 0.28%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 3        | 0.28%   |
| WDC WD40EFRX-68N32N0 4TB           | 3        | 0.28%   |
| WDC WD30EFRX-68EUZN0 3TB           | 3        | 0.28%   |
| WDC WD10EZEX-75WN4A0 1TB           | 3        | 0.28%   |
| WDC WD10EADS-00L5B1 1TB            | 3        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 135      | 230    | 37.6%   |
| WDC                 | 122      | 200    | 33.98%  |
| Hitachi             | 32       | 44     | 8.91%   |
| Toshiba             | 31       | 50     | 8.64%   |
| Samsung Electronics | 18       | 28     | 5.01%   |
| HGST                | 5        | 14     | 1.39%   |
| Unknown             | 4        | 5      | 1.11%   |
| MAXTOR              | 3        | 3      | 0.84%   |
| Hewlett-Packard     | 2        | 2      | 0.56%   |
| Synology            | 1        | 1      | 0.28%   |
| PHD 3.0             | 1        | 1      | 0.28%   |
| MaxDigital          | 1        | 1      | 0.28%   |
| Magnetic Data       | 1        | 1      | 0.28%   |
| Inateck             | 1        | 1      | 0.28%   |
| ASMT106x            | 1        | 1      | 0.28%   |
| Apple               | 1        | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 99       | 174    | 28.7%   |
| Kingston            | 48       | 61     | 13.91%  |
| Crucial             | 45       | 70     | 13.04%  |
| SanDisk             | 23       | 24     | 6.67%   |
| WDC                 | 20       | 25     | 5.8%    |
| A-DATA Technology   | 12       | 15     | 3.48%   |
| Intel               | 9        | 17     | 2.61%   |
| Toshiba             | 8        | 9      | 2.32%   |
| Micron Technology   | 8        | 10     | 2.32%   |
| OCZ                 | 7        | 12     | 2.03%   |
| PNY                 | 6        | 8      | 1.74%   |
| SK Hynix            | 5        | 5      | 1.45%   |
| SPCC                | 4        | 5      | 1.16%   |
| Patriot             | 4        | 4      | 1.16%   |
| Team                | 3        | 4      | 0.87%   |
| SABRENT             | 3        | 3      | 0.87%   |
| KingSpec            | 3        | 6      | 0.87%   |
| GOODRAM             | 3        | 3      | 0.87%   |
| Gigabyte Technology | 3        | 4      | 0.87%   |
| Unknown             | 2        | 2      | 0.58%   |
| Transcend           | 2        | 2      | 0.58%   |
| LITEONIT            | 2        | 2      | 0.58%   |
| Corsair             | 2        | 3      | 0.58%   |
| China               | 2        | 2      | 0.58%   |
| ASMT                | 2        | 2      | 0.58%   |
| Apple               | 2        | 2      | 0.58%   |
| Apacer              | 2        | 3      | 0.58%   |
| Smartbuy            | 1        | 1      | 0.29%   |
| SMART               | 1        | 1      | 0.29%   |
| Seagate             | 1        | 1      | 0.29%   |
| PLEXTOR             | 1        | 2      | 0.29%   |
| OWC                 | 1        | 1      | 0.29%   |
| Mushkin             | 1        | 3      | 0.29%   |
| MG                  | 1        | 1      | 0.29%   |
| MAXTOR              | 1        | 2      | 0.29%   |
| LITEON              | 1        | 1      | 0.29%   |
| Lexar               | 1        | 1      | 0.29%   |
| KLEVV               | 1        | 1      | 0.29%   |
| Intenso             | 1        | 1      | 0.29%   |
| Hoodisk             | 1        | 2      | 0.29%   |
| DREVO               | 1        | 1      | 0.29%   |
| DOGFISH             | 1        | 1      | 0.29%   |
| CT1000P1            | 1        | 2      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 277      | 499    | 38.26%  |
| HDD     | 271      | 583    | 37.43%  |
| NVMe    | 166      | 282    | 22.93%  |
| Unknown | 9        | 14     | 1.24%   |
| MMC     | 1        | 1      | 0.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 384      | 1049   | 65.42%  |
| NVMe | 165      | 281    | 28.11%  |
| SAS  | 37       | 48     | 6.3%    |
| MMC  | 1        | 1      | 0.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 281      | 525    | 44.89%  |
| 0.51-1.0   | 197      | 320    | 31.47%  |
| 1.01-2.0   | 76       | 110    | 12.14%  |
| 3.01-4.0   | 28       | 46     | 4.47%   |
| 4.01-10.0  | 25       | 51     | 3.99%   |
| 2.01-3.0   | 15       | 20     | 2.4%    |
| 10.01-20.0 | 4        | 10     | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 79       | 18.16%  |
| 1001-2000      | 70       | 16.09%  |
| 251-500        | 68       | 15.63%  |
| More than 3000 | 64       | 14.71%  |
| 101-250        | 62       | 14.25%  |
| 2001-3000      | 37       | 8.51%   |
| 1-20           | 23       | 5.29%   |
| Unknown        | 18       | 4.14%   |
| 51-100         | 9        | 2.07%   |
| 21-50          | 5        | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 84       | 18.75%  |
| 21-50          | 63       | 14.06%  |
| 501-1000       | 63       | 14.06%  |
| 101-250        | 62       | 13.84%  |
| 251-500        | 46       | 10.27%  |
| 51-100         | 45       | 10.04%  |
| 1001-2000      | 39       | 8.71%   |
| More than 3000 | 18       | 4.02%   |
| Unknown        | 18       | 4.02%   |
| 2001-3000      | 10       | 2.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 3        | 15     | 6.98%   |
| Intel SSDSC2CT120A3 120GB          | 3        | 7      | 6.98%   |
| WDC WD1003FBYX-01Y7B1 752GB        | 2        | 2      | 4.65%   |
| Toshiba DT01ACA200 2TB             | 2        | 4      | 4.65%   |
| WDC WD60EFAX-68SHWN0 6TB           | 1        | 1      | 2.33%   |
| WDC WD40PURZ-85AKKY0 4TB           | 1        | 1      | 2.33%   |
| WDC WD30EZRX-00AZ6B0 3TB           | 1        | 1      | 2.33%   |
| WDC WD15EARS-00Z5B1 1TB            | 1        | 1      | 2.33%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 1        | 1      | 2.33%   |
| Seagate ST4000DM000-1F2168 4TB     | 1        | 1      | 2.33%   |
| Seagate ST3500630AS 500GB          | 1        | 1      | 2.33%   |
| Seagate ST3500418AS 500GB          | 1        | 1      | 2.33%   |
| Seagate ST31000524AS 1TB           | 1        | 1      | 2.33%   |
| Seagate ST31000340NS 1TB           | 1        | 1      | 2.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 2.33%   |
| Seagate ST1000DX001-1CM162 1TB     | 1        | 1      | 2.33%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 2.33%   |
| SanDisk SSD U100 64GB              | 1        | 1      | 2.33%   |
| SanDisk SSD PLUS 480GB             | 1        | 1      | 2.33%   |
| SanDisk SDSSDX240GG25 240GB        | 1        | 1      | 2.33%   |
| Samsung Electronics SP2514N 250GB  | 1        | 1      | 2.33%   |
| Samsung Electronics SP2004C 200GB  | 1        | 1      | 2.33%   |
| Samsung Electronics HM160HI 160GB  | 1        | 2      | 2.33%   |
| Samsung Electronics HD501LJ 500GB  | 1        | 6      | 2.33%   |
| Samsung Electronics HD322HJ 320GB  | 1        | 1      | 2.33%   |
| Kingston SA400S37240G 240GB SSD    | 1        | 1      | 2.33%   |
| Intel SSDSC2BW240A4 240GB          | 1        | 1      | 2.33%   |
| Intel SSDPEKKW128G7 128GB          | 1        | 1      | 2.33%   |
| Hitachi HTS725050A7E630 500GB      | 1        | 1      | 2.33%   |
| Hitachi HTS542560K9SA00 64GB       | 1        | 1      | 2.33%   |
| Hitachi HDS721050CLA362 500GB      | 1        | 1      | 2.33%   |
| Hitachi HDS721010CLA330 1TB        | 1        | 1      | 2.33%   |
| Hewlett-Packard MB1000CBZQE 1TB    | 1        | 1      | 2.33%   |
| Crucial CT275MX300SSD1 275GB       | 1        | 1      | 2.33%   |
| Crucial CT128MX100SSD1 128GB       | 1        | 1      | 2.33%   |
| A-DATA Technology SP900 256GB SSD  | 1        | 1      | 2.33%   |
| A-DATA Technology SP900 128GB SSD  | 1        | 2      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 23     | 25.58%  |
| WDC                 | 7        | 7      | 16.28%  |
| Samsung Electronics | 5        | 11     | 11.63%  |
| Intel               | 5        | 9      | 11.63%  |
| Hitachi             | 4        | 4      | 9.3%    |
| SanDisk             | 3        | 3      | 6.98%   |
| Toshiba             | 2        | 4      | 4.65%   |
| Crucial             | 2        | 2      | 4.65%   |
| A-DATA Technology   | 2        | 3      | 4.65%   |
| Kingston            | 1        | 1      | 2.33%   |
| Hewlett-Packard     | 1        | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 23     | 36.67%  |
| WDC                 | 7        | 7      | 23.33%  |
| Samsung Electronics | 5        | 11     | 16.67%  |
| Hitachi             | 4        | 4      | 13.33%  |
| Toshiba             | 2        | 4      | 6.67%   |
| Hewlett-Packard     | 1        | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 50     | 68.29%  |
| SSD  | 12       | 17     | 29.27%  |
| NVMe | 1        | 1      | 2.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Hitachi HDS721010DLE630 1TB | 1        | 4      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 258      | 783    | 54.43%  |
| Works    | 175      | 524    | 36.92%  |
| Malfunc  | 40       | 68     | 8.44%   |
| Failed   | 1        | 4      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 235      | 35.34%  |
| AMD                          | 176      | 26.47%  |
| Samsung Electronics          | 75       | 11.28%  |
| ASMedia Technology           | 32       | 4.81%   |
| Sandisk                      | 29       | 4.36%   |
| Phison Electronics           | 29       | 4.36%   |
| Kingston Technology Company  | 12       | 1.8%    |
| Micron/Crucial Technology    | 11       | 1.65%   |
| Nvidia                       | 8        | 1.2%    |
| Marvell Technology Group     | 8        | 1.2%    |
| JMicron Technology           | 7        | 1.05%   |
| Toshiba America Info Systems | 6        | 0.9%    |
| ADATA Technology             | 6        | 0.9%    |
| Silicon Motion               | 4        | 0.6%    |
| Broadcom / LSI               | 4        | 0.6%    |
| SK Hynix                     | 3        | 0.45%   |
| LSI Logic / Symbios Logic    | 3        | 0.45%   |
| VIA Technologies             | 2        | 0.3%    |
| ULi Electronics              | 2        | 0.3%    |
| Silicon Image                | 2        | 0.3%    |
| Seagate Technology           | 2        | 0.3%    |
| Realtek Semiconductor        | 2        | 0.3%    |
| Micron Technology            | 2        | 0.3%    |
| Adaptec                      | 2        | 0.3%    |
| Union Memory (Shenzhen)      | 1        | 0.15%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.15%   |
| Hewlett-Packard              | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 120      | 14.93%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 51       | 6.34%   |
| AMD 400 Series Chipset SATA Controller                                                  | 44       | 5.47%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 31       | 3.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 29       | 3.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 29       | 3.61%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 27       | 3.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 3.11%   |
| Intel SATA Controller [RAID mode]                                                       | 19       | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18       | 2.24%   |
| Phison E12 NVMe Controller                                                              | 15       | 1.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 15       | 1.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 1.74%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 12       | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12       | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12       | 1.49%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 11       | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 1.37%   |
| AMD 300 Series Chipset SATA Controller                                                  | 11       | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10       | 1.24%   |
| AMD FCH SATA Controller D                                                               | 10       | 1.24%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 9        | 1.12%   |
| Kingston Company A2000 NVMe SSD                                                         | 7        | 0.87%   |
| Intel SSD 660P Series                                                                   | 7        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 0.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 0.75%   |
| AMD X399 Series Chipset SATA Controller                                                 | 6        | 0.75%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 5        | 0.62%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.62%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 0.62%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5        | 0.62%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 0.62%   |
| Sandisk WD Black SN850                                                                  | 4        | 0.5%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4        | 0.5%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 0.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.5%    |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.5%    |
| AMD FCH IDE Controller                                                                  | 4        | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.37%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.37%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.37%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 0.37%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.37%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 3        | 0.37%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 3        | 0.37%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.37%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.37%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.37%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.37%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.37%   |
| ULi ULi M5288 SATA                                                                      | 2        | 0.25%   |
| ULi M5229 IDE                                                                           | 2        | 0.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2        | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 358      | 57.65%  |
| NVMe | 164      | 26.41%  |
| IDE  | 64       | 10.31%  |
| RAID | 30       | 4.83%   |
| SCSI | 3        | 0.48%   |
| SAS  | 2        | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 233      | 55.74%  |
| AMD    | 185      | 44.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 17       | 4.06%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 12       | 2.86%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 11       | 2.63%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 10       | 2.39%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 10       | 2.39%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 7        | 1.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 7        | 1.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 7        | 1.67%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 7        | 1.67%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 7        | 1.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 6        | 1.43%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 6        | 1.43%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 6        | 1.43%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 6        | 1.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 5        | 1.19%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 5        | 1.19%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 5        | 1.19%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 5        | 1.19%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 5        | 1.19%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 5        | 1.19%   |
| Intel Core i9-9900K CPU @ 3.60GHz               | 4        | 0.95%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 4        | 0.95%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 4        | 0.95%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 4        | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 4        | 0.95%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 4        | 0.95%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 4        | 0.95%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 4        | 0.95%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 4        | 0.95%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 3        | 0.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 3        | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 3        | 0.72%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 3        | 0.72%   |
| Intel Core i7-10700K CPU @ 3.80GHz              | 3        | 0.72%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 3        | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 3        | 0.72%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 3        | 0.72%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 3        | 0.72%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 3        | 0.72%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 3        | 0.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 3        | 0.72%   |
| AMD FX-8350 Eight-Core Processor                | 3        | 0.72%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+      | 3        | 0.72%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 3        | 0.72%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz              | 2        | 0.48%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz             | 2        | 0.48%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 2        | 0.48%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 2        | 0.48%   |
| Intel Pentium CPU G620 @ 2.60GHz                | 2        | 0.48%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 2        | 0.48%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 2        | 0.48%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 2        | 0.48%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 2        | 0.48%   |
| Intel Core i7-6800K CPU @ 3.40GHz               | 2        | 0.48%   |
| Intel Core i7-6700T CPU @ 2.80GHz               | 2        | 0.48%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 2        | 0.48%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 2        | 0.48%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 2        | 0.48%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 2        | 0.48%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 2        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 70       | 16.75%  |
| Intel Core i5           | 67       | 16.03%  |
| AMD Ryzen 5             | 65       | 15.55%  |
| AMD Ryzen 7             | 32       | 7.66%   |
| AMD Ryzen 9             | 30       | 7.18%   |
| Intel Xeon              | 23       | 5.5%    |
| Intel Core i3           | 23       | 5.5%    |
| AMD FX                  | 9        | 2.15%   |
| AMD Ryzen 3             | 8        | 1.91%   |
| Intel Pentium           | 7        | 1.67%   |
| Intel Core i9           | 7        | 1.67%   |
| Intel Core 2 Quad       | 7        | 1.67%   |
| Intel Core 2 Duo        | 7        | 1.67%   |
| Intel Celeron           | 7        | 1.67%   |
| AMD Ryzen Threadripper  | 7        | 1.67%   |
| Intel Pentium Dual-Core | 5        | 1.2%    |
| AMD A10                 | 5        | 1.2%    |
| Other                   | 4        | 0.96%   |
| AMD Athlon 64 X2        | 4        | 0.96%   |
| AMD Phenom II X2        | 3        | 0.72%   |
| AMD Athlon Dual Core    | 3        | 0.72%   |
| Intel Pentium D         | 2        | 0.48%   |
| AMD Ryzen 7 PRO         | 2        | 0.48%   |
| AMD Ryzen 5 PRO         | 2        | 0.48%   |
| AMD Phenom II X6        | 2        | 0.48%   |
| AMD Phenom II X4        | 2        | 0.48%   |
| AMD Athlon II X2        | 2        | 0.48%   |
| AMD A6                  | 2        | 0.48%   |
| Intel Pentium Dual      | 1        | 0.24%   |
| Intel Pentium 4         | 1        | 0.24%   |
| Intel Core 2            | 1        | 0.24%   |
| Intel Atom              | 1        | 0.24%   |
| AMD E2                  | 1        | 0.24%   |
| AMD E                   | 1        | 0.24%   |
| AMD Athlon X2           | 1        | 0.24%   |
| AMD Athlon II X4        | 1        | 0.24%   |
| AMD Athlon              | 1        | 0.24%   |
| AMD A8                  | 1        | 0.24%   |
| AMD A4                  | 1        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 155      | 36.99%  |
| 6      | 93       | 22.2%   |
| 2      | 70       | 16.71%  |
| 8      | 56       | 13.37%  |
| 12     | 22       | 5.25%   |
| 16     | 14       | 3.34%   |
| 1      | 4        | 0.95%   |
| 3      | 2        | 0.48%   |
| 32     | 1        | 0.24%   |
| 24     | 1        | 0.24%   |
| 10     | 1        | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 412      | 98.56%  |
| 2      | 6        | 1.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 273      | 65%     |
| 1      | 147      | 35%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 418      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 37       | 8.81%   |
| 0x08701021 | 37       | 8.81%   |
| 0x506e3    | 25       | 5.95%   |
| Unknown    | 25       | 5.95%   |
| 0x306a9    | 19       | 4.52%   |
| 0x906e9    | 18       | 4.29%   |
| 0x1067a    | 18       | 4.29%   |
| 0x0a201009 | 18       | 4.29%   |
| 0x0800820d | 18       | 4.29%   |
| 0x906ea    | 17       | 4.05%   |
| 0x206a7    | 17       | 4.05%   |
| 0x08701013 | 15       | 3.57%   |
| 0x906ed    | 9        | 2.14%   |
| 0x0a201016 | 9        | 2.14%   |
| 0x08108109 | 8        | 1.9%    |
| 0xa0655    | 7        | 1.67%   |
| 0x08101016 | 6        | 1.43%   |
| 0x08001138 | 6        | 1.43%   |
| 0x906ec    | 5        | 1.19%   |
| 0x106e5    | 5        | 1.19%   |
| 0x08001137 | 5        | 1.19%   |
| 0xa0671    | 4        | 0.95%   |
| 0xa0653    | 4        | 0.95%   |
| 0x306f2    | 4        | 0.95%   |
| 0x106a5    | 4        | 0.95%   |
| 0x906eb    | 3        | 0.71%   |
| 0x206d7    | 3        | 0.71%   |
| 0x0a50000c | 3        | 0.71%   |
| 0x08600103 | 3        | 0.71%   |
| 0x0810100b | 3        | 0.71%   |
| 0x06003106 | 3        | 0.71%   |
| 0x06001119 | 3        | 0.71%   |
| 0x010000c8 | 3        | 0.71%   |
| 0xf47      | 2        | 0.48%   |
| 0xf43      | 2        | 0.48%   |
| 0x806ea    | 2        | 0.48%   |
| 0x6fb      | 2        | 0.48%   |
| 0x6f6      | 2        | 0.48%   |
| 0x50654    | 2        | 0.48%   |
| 0x406f1    | 2        | 0.48%   |
| 0x08108102 | 2        | 0.48%   |
| 0x08001129 | 2        | 0.48%   |
| 0x06000822 | 2        | 0.48%   |
| 0x0600081c | 2        | 0.48%   |
| 0x06000817 | 2        | 0.48%   |
| 0x06000629 | 2        | 0.48%   |
| 0x00000000 | 2        | 0.48%   |
| 0x706a8    | 1        | 0.24%   |
| 0x706a1    | 1        | 0.24%   |
| 0x6fd      | 1        | 0.24%   |
| 0x50657    | 1        | 0.24%   |
| 0x406c4    | 1        | 0.24%   |
| 0x40651    | 1        | 0.24%   |
| 0x30661    | 1        | 0.24%   |
| 0x20655    | 1        | 0.24%   |
| 0x106a4    | 1        | 0.24%   |
| 0x10677    | 1        | 0.24%   |
| 0x10676    | 1        | 0.24%   |
| 0x08600106 | 1        | 0.24%   |
| 0x08600104 | 1        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 59       | 14.11%  |
| KabyLake      | 58       | 13.88%  |
| Haswell       | 45       | 10.77%  |
| Zen+          | 33       | 7.89%   |
| Zen 3         | 30       | 7.18%   |
| Skylake       | 28       | 6.7%    |
| Zen           | 24       | 5.74%   |
| SandyBridge   | 20       | 4.78%   |
| Penryn        | 20       | 4.78%   |
| IvyBridge     | 20       | 4.78%   |
| CometLake     | 12       | 2.87%   |
| K10           | 11       | 2.63%   |
| Piledriver    | 10       | 2.39%   |
| Nehalem       | 10       | 2.39%   |
| K8 Hammer     | 7        | 1.67%   |
| Core          | 5        | 1.2%    |
| NetBurst      | 4        | 0.96%   |
| Icelake       | 4        | 0.96%   |
| Steamroller   | 3        | 0.72%   |
| Goldmont plus | 2        | 0.48%   |
| Excavator     | 2        | 0.48%   |
| Bulldozer     | 2        | 0.48%   |
| Broadwell     | 2        | 0.48%   |
| Westmere      | 1        | 0.24%   |
| Silvermont    | 1        | 0.24%   |
| Puma          | 1        | 0.24%   |
| K10 Llano     | 1        | 0.24%   |
| Jaguar        | 1        | 0.24%   |
| Bonnell       | 1        | 0.24%   |
| Bobcat        | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 189      | 41.36%  |
| AMD                        | 162      | 35.45%  |
| Intel                      | 104      | 22.76%  |
| Matrox Electronics Systems | 1        | 0.22%   |
| ASPEED Technology          | 1        | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 39       | 8.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 18       | 3.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 18       | 3.85%   |
| Intel HD Graphics 530                                                       | 14       | 3%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 13       | 2.78%   |
| Nvidia GK208B [GeForce GT 710]                                              | 12       | 2.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 11       | 2.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11       | 2.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11       | 2.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 2.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 9        | 1.93%   |
| Intel HD Graphics 630                                                       | 9        | 1.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 9        | 1.93%   |
| AMD Picasso                                                                 | 9        | 1.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 1.5%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 1.28%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.28%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 1.28%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 6        | 1.28%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 5        | 1.07%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1.07%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 1.07%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 5        | 1.07%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.07%   |
| AMD Renoir                                                                  | 5        | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.86%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 0.86%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 4        | 0.86%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 4        | 0.86%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.86%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.86%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 0.86%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 4        | 0.86%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.64%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.64%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 3        | 0.64%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 3        | 0.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 0.64%   |
| AMD RV530 [Radeon X1600] (Secondary)                                        | 3        | 0.64%   |
| AMD RV530 [Radeon X1600 PRO]                                                | 3        | 0.64%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 3        | 0.64%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 0.64%   |
| AMD Cezanne                                                                 | 3        | 0.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 0.64%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.43%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.43%   |
| Nvidia GP107GL [Quadro P1000]                                               | 2        | 0.43%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 0.43%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.43%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.43%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.43%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.43%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 2        | 0.43%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 166      | 39.34%  |
| 1 x AMD        | 148      | 35.07%  |
| 1 x Intel      | 73       | 17.3%   |
| Intel + Nvidia | 14       | 3.32%   |
| 2 x Nvidia     | 6        | 1.42%   |
| 2 x AMD        | 5        | 1.18%   |
| AMD + Nvidia   | 4        | 0.95%   |
| Other          | 2        | 0.47%   |
| Intel + AMD    | 2        | 0.47%   |
| 1 x Matrox     | 1        | 0.24%   |
| 1 x ASPEED     | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 312      | 73.76%  |
| Proprietary | 101      | 23.88%  |
| Unknown     | 10       | 2.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 135      | 31.54%  |
| 7.01-8.0   | 66       | 15.42%  |
| 1.01-2.0   | 58       | 13.55%  |
| 3.01-4.0   | 51       | 11.92%  |
| 0.51-1.0   | 46       | 10.75%  |
| 0.01-0.5   | 26       | 6.07%   |
| 5.01-6.0   | 23       | 5.37%   |
| 8.01-16.0  | 17       | 3.97%   |
| 2.01-3.0   | 5        | 1.17%   |
| 16.01-24.0 | 1        | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 74       | 15.26%  |
| Samsung Electronics  | 69       | 14.23%  |
| Dell                 | 58       | 11.96%  |
| Acer                 | 34       | 7.01%   |
| BenQ                 | 31       | 6.39%   |
| AOC                  | 27       | 5.57%   |
| Hewlett-Packard      | 25       | 5.15%   |
| Iiyama               | 22       | 4.54%   |
| Philips              | 21       | 4.33%   |
| Ancor Communications | 18       | 3.71%   |
| Lenovo               | 10       | 2.06%   |
| ViewSonic            | 9        | 1.86%   |
| ASUSTek Computer     | 8        | 1.65%   |
| Sceptre Tech         | 6        | 1.24%   |
| ___                  | 5        | 1.03%   |
| Unknown              | 5        | 1.03%   |
| Sony                 | 5        | 1.03%   |
| MSI                  | 5        | 1.03%   |
| Vizio                | 4        | 0.82%   |
| NEC Computers        | 4        | 0.82%   |
| Vestel Elektronik    | 2        | 0.41%   |
| Mitsubishi           | 2        | 0.41%   |
| Mi                   | 2        | 0.41%   |
| Insignia             | 2        | 0.41%   |
| HannStar             | 2        | 0.41%   |
| eMachines            | 2        | 0.41%   |
| Element              | 2        | 0.41%   |
| Eizo                 | 2        | 0.41%   |
| Zoran                | 1        | 0.21%   |
| Unknown (XXX)        | 1        | 0.21%   |
| Toshiba              | 1        | 0.21%   |
| RZR                  | 1        | 0.21%   |
| RIS                  | 1        | 0.21%   |
| Pixio                | 1        | 0.21%   |
| Packard Bell         | 1        | 0.21%   |
| OUT                  | 1        | 0.21%   |
| Onkyo                | 1        | 0.21%   |
| Novatek              | 1        | 0.21%   |
| NEW                  | 1        | 0.21%   |
| Microstep            | 1        | 0.21%   |
| Medion Akoya         | 1        | 0.21%   |
| Medion               | 1        | 0.21%   |
| Marantz              | 1        | 0.21%   |
| LG Electronics       | 1        | 0.21%   |
| KTC                  | 1        | 0.21%   |
| IPS                  | 1        | 0.21%   |
| IBM                  | 1        | 0.21%   |
| HYO                  | 1        | 0.21%   |
| Huion                | 1        | 0.21%   |
| Hitachi              | 1        | 0.21%   |
| GKK                  | 1        | 0.21%   |
| Gigabyte Technology  | 1        | 0.21%   |
| Fujitsu Siemens      | 1        | 0.21%   |
| Envision Peripherals | 1        | 0.21%   |
| Envision             | 1        | 0.21%   |
| CHE                  | 1        | 0.21%   |
| Apple                | 1        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch                           | 7        | 1.32%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch                     | 4        | 0.75%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                                  | 4        | 0.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                                | 4        | 0.75%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                                | 4        | 0.75%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                                     | 4        | 0.75%   |
| ___ Monitor ranges (GTF): 48-62Hz V, 14-68kHz H, max dotclock 150MHz ___9000 1440x900 | 3        | 0.56%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch                         | 3        | 0.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch                     | 3        | 0.56%   |
| Goldstar W2442 GSM56D9 1680x1050 530x300mm 24.0-inch                                  | 3        | 0.56%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                             | 3        | 0.56%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                                      | 3        | 0.56%   |
| AOC 2757M AOC2757 1920x1080 598x336mm 27.0-inch                                       | 3        | 0.56%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                                    | 2        | 0.38%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch                | 2        | 0.38%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                                    | 2        | 0.38%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                                   | 2        | 0.38%   |
| Sceptre Tech E275W-1920 SPT0ABF 1920x1080 443x249mm 20.0-inch                         | 2        | 0.38%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 410x260mm 19.1-inch                   | 2        | 0.38%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 530x300mm 24.0-inch                     | 2        | 0.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch                     | 2        | 0.38%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch                | 2        | 0.38%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch                    | 2        | 0.38%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch                    | 2        | 0.38%   |
| Samsung Electronics C27HG7x SAM0E16 2560x1440 598x336mm 27.0-inch                     | 2        | 0.38%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                               | 2        | 0.38%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                               | 2        | 0.38%   |
| MSI G27C5 MSI3CA9 1920x1080 598x336mm 27.0-inch                                       | 2        | 0.38%   |
| Mitsubishi RDT234WLM MEL4887 1920x1080 509x286mm 23.0-inch                            | 2        | 0.38%   |
| Lenovo LEN LT1712p LEN13B7 1280x1024 338x270mm 17.0-inch                              | 2        | 0.38%   |
| Iiyama PL1906 IVM483C 1280x1024 376x301mm 19.0-inch                                   | 2        | 0.38%   |
| Hewlett-Packard ZR22w HWP2867 1920x1080 475x267mm 21.5-inch                           | 2        | 0.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                             | 2        | 0.38%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                               | 2        | 0.38%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                                 | 2        | 0.38%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch                               | 2        | 0.38%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                                     | 2        | 0.38%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                                    | 2        | 0.38%   |
| Dell P2319H DELD0D7 1920x1080 509x286mm 23.0-inch                                     | 2        | 0.38%   |
| Dell P1917S DELD091 1280x1024 375x300mm 18.9-inch                                     | 2        | 0.38%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch                               | 2        | 0.38%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                                     | 2        | 0.38%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                                     | 2        | 0.38%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                                    | 2        | 0.38%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch                          | 2        | 0.38%   |
| AOC 2790 AOC2790 1920x1080 598x336mm 27.0-inch                                        | 2        | 0.38%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                                       | 2        | 0.38%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                                        | 2        | 0.38%   |
| AOC 22B1W AOC2201 1920x1080 476x268mm 21.5-inch                                       | 2        | 0.38%   |
| Ancor Communications VG248 ACI24A5 1920x1080 531x299mm 24.0-inch                      | 2        | 0.38%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch                 | 2        | 0.38%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 480x270mm 21.7-inch                 | 2        | 0.38%   |
| Acer XF270H B ACR064D 1920x1080 598x336mm 27.0-inch                                   | 2        | 0.38%   |
| Acer X223HQ ACR0098 1920x1080 470x270mm 21.3-inch                                     | 2        | 0.38%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                                     | 2        | 0.38%   |
| Zoran ZORAN ZRN02E9 1280x720 440x250mm 19.9-inch                                      | 1        | 0.19%   |
| Vizio V405-H9 VIZ1039 3840x2160 870x480mm 39.1-inch                                   | 1        | 0.19%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                                  | 1        | 0.19%   |
| Vizio E190VA VIZ0067 1360x768 410x230mm 18.5-inch                                     | 1        | 0.19%   |
| Vizio D43-C1 VIZ0098 1920x1080 940x529mm 42.5-inch                                    | 1        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 219      | 46.6%   |
| 2560x1440 (QHD)    | 59       | 12.55%  |
| 3840x2160 (4K)     | 54       | 11.49%  |
| 1280x1024 (SXGA)   | 19       | 4.04%   |
| 2560x1080          | 18       | 3.83%   |
| 1440x900 (WXGA+)   | 16       | 3.4%    |
| 1366x768 (WXGA)    | 15       | 3.19%   |
| 1920x1200 (WUXGA)  | 14       | 2.98%   |
| 3440x1440          | 8        | 1.7%    |
| 1680x1050 (WSXGA+) | 8        | 1.7%    |
| 1600x900 (HD+)     | 8        | 1.7%    |
| 1360x768           | 8        | 1.7%    |
| 3840x1080          | 6        | 1.28%   |
| Unknown            | 4        | 0.85%   |
| 1024x768 (XGA)     | 3        | 0.64%   |
| 2048x1152          | 2        | 0.43%   |
| 1600x1200          | 2        | 0.43%   |
| 7680x1440          | 1        | 0.21%   |
| 7120x1080          | 1        | 0.21%   |
| 2560x1600          | 1        | 0.21%   |
| 2288x1287          | 1        | 0.21%   |
| 1920x540           | 1        | 0.21%   |
| 1280x960           | 1        | 0.21%   |
| 1280x720 (HD)      | 1        | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 100      | 20.37%  |
| 24      | 88       | 17.92%  |
| 21      | 59       | 12.02%  |
| 23      | 54       | 11%     |
| 19      | 29       | 5.91%   |
| 34      | 25       | 5.09%   |
| 31      | 21       | 4.28%   |
| 18      | 18       | 3.67%   |
| Unknown | 14       | 2.85%   |
| 72      | 12       | 2.44%   |
| 20      | 9        | 1.83%   |
| 22      | 8        | 1.63%   |
| 15      | 8        | 1.63%   |
| 48      | 6        | 1.22%   |
| 32      | 6        | 1.22%   |
| 84      | 5        | 1.02%   |
| 25      | 5        | 1.02%   |
| 28      | 4        | 0.81%   |
| 17      | 4        | 0.81%   |
| 49      | 3        | 0.61%   |
| 42      | 2        | 0.41%   |
| 26      | 2        | 0.41%   |
| 16      | 2        | 0.41%   |
| 54      | 1        | 0.2%    |
| 43      | 1        | 0.2%    |
| 40      | 1        | 0.2%    |
| 38      | 1        | 0.2%    |
| 33      | 1        | 0.2%    |
| 30      | 1        | 0.2%    |
| 13      | 1        | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 217      | 46.97%  |
| 401-500     | 99       | 21.43%  |
| 601-700     | 33       | 7.14%   |
| 701-800     | 32       | 6.93%   |
| 351-400     | 22       | 4.76%   |
| 1501-2000   | 17       | 3.68%   |
| Unknown     | 14       | 3.03%   |
| 301-350     | 12       | 2.6%    |
| 1001-1500   | 10       | 2.16%   |
| 901-1000    | 3        | 0.65%   |
| 801-900     | 2        | 0.43%   |
| 201-300     | 1        | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 320      | 74.42%  |
| 16/10   | 38       | 8.84%   |
| 21/9    | 26       | 6.05%   |
| 5/4     | 20       | 4.65%   |
| 4/3     | 8        | 1.86%   |
| Unknown | 8        | 1.86%   |
| 32/9    | 5        | 1.16%   |
| 6/5     | 2        | 0.47%   |
| 3/2     | 2        | 0.47%   |
| 1.96    | 1        | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 155      | 32.22%  |
| 301-350        | 101      | 21%     |
| 151-200        | 61       | 12.68%  |
| 351-500        | 57       | 11.85%  |
| 251-300        | 33       | 6.86%   |
| More than 1000 | 20       | 4.16%   |
| 141-150        | 15       | 3.12%   |
| Unknown        | 14       | 2.91%   |
| 501-1000       | 11       | 2.29%   |
| 101-110        | 6        | 1.25%   |
| 131-140        | 4        | 0.83%   |
| 91-100         | 3        | 0.62%   |
| 111-120        | 1        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 265      | 58.11%  |
| 101-120 | 120      | 26.32%  |
| 121-160 | 29       | 6.36%   |
| 1-50    | 16       | 3.51%   |
| Unknown | 14       | 3.07%   |
| 161-240 | 12       | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 293      | 68.94%  |
| 2     | 105      | 24.71%  |
| 0     | 14       | 3.29%   |
| 3     | 13       | 3.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 238      | 39.34%  |
| Intel                           | 233      | 38.51%  |
| Qualcomm Atheros                | 34       | 5.62%   |
| Ralink Technology               | 15       | 2.48%   |
| Broadcom                        | 15       | 2.48%   |
| Aquantia                        | 10       | 1.65%   |
| TP-Link                         | 8        | 1.32%   |
| Nvidia                          | 5        | 0.83%   |
| Xiaomi                          | 4        | 0.66%   |
| Ralink                          | 4        | 0.66%   |
| Marvell Technology Group        | 4        | 0.66%   |
| Broadcom Limited                | 4        | 0.66%   |
| NetGear                         | 3        | 0.5%    |
| Huawei Technologies             | 3        | 0.5%    |
| Qualcomm Atheros Communications | 2        | 0.33%   |
| Motorola PCS                    | 2        | 0.33%   |
| Microsoft                       | 2        | 0.33%   |
| ICS Advent                      | 2        | 0.33%   |
| D-Link System                   | 2        | 0.33%   |
| ASUSTek Computer                | 2        | 0.33%   |
| Wilocity                        | 1        | 0.17%   |
| Qualcomm                        | 1        | 0.17%   |
| Oculus VR                       | 1        | 0.17%   |
| Microchip Technology            | 1        | 0.17%   |
| Mellanox Technologies           | 1        | 0.17%   |
| Linksys                         | 1        | 0.17%   |
| InterBiometrics                 | 1        | 0.17%   |
| IMC Networks                    | 1        | 0.17%   |
| D-Link                          | 1        | 0.17%   |
| Arduino SA                      | 1        | 0.17%   |
| Apple                           | 1        | 0.17%   |
| Adafruit                        | 1        | 0.17%   |
| Accton Technology               | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 179      | 24.45%  |
| Intel Wi-Fi 6 AX200                                                           | 64       | 8.74%   |
| Intel I211 Gigabit Network Connection                                         | 56       | 7.65%   |
| Realtek RTL8125 2.5GbE Controller                                             | 31       | 4.23%   |
| Intel Ethernet Connection (2) I219-V                                          | 30       | 4.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 19       | 2.6%    |
| Intel Wireless-AC 9260                                                        | 14       | 1.91%   |
| Intel Ethernet Connection (7) I219-V                                          | 12       | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12       | 1.64%   |
| Intel Ethernet Controller I225-V                                              | 11       | 1.5%    |
| Intel Ethernet Connection (2) I218-V                                          | 11       | 1.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9        | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 8        | 1.09%   |
| Intel Wireless 7260                                                           | 8        | 1.09%   |
| Intel Ethernet Connection I217-LM                                             | 8        | 1.09%   |
| Realtek 802.11ac NIC                                                          | 7        | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7        | 0.96%   |
| Intel Wireless 8260                                                           | 7        | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 0.82%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 0.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 6        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5        | 0.68%   |
| Ralink MT7601U Wireless Adapter                                               | 5        | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5        | 0.68%   |
| Intel Ethernet Connection I217-V                                              | 5        | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 5        | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 5        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.55%   |
| Ralink RT5370 Wireless Adapter                                                | 4        | 0.55%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 0.55%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.55%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 4        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 3        | 0.41%   |
| TP-Link Archer T4U ver.3                                                      | 3        | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 0.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 3        | 0.41%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 3        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3        | 0.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 3        | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3        | 0.41%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.41%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 3        | 0.41%   |
| Intel Wireless 8265 / 8275                                                    | 3        | 0.41%   |
| Intel Ethernet Connection (12) I219-V                                         | 3        | 0.41%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.41%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 3        | 0.41%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 3        | 0.41%   |
| TP-Link 802.11ac NIC                                                          | 2        | 0.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.27%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                           | 2        | 0.27%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.27%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 2        | 0.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 2        | 0.27%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 2        | 0.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 0.27%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2        | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 128      | 55.9%   |
| Realtek Semiconductor           | 33       | 14.41%  |
| Qualcomm Atheros                | 19       | 8.3%    |
| Ralink Technology               | 15       | 6.55%   |
| TP-Link                         | 8        | 3.49%   |
| Broadcom                        | 7        | 3.06%   |
| Ralink                          | 4        | 1.75%   |
| NetGear                         | 3        | 1.31%   |
| Qualcomm Atheros Communications | 2        | 0.87%   |
| Microsoft                       | 2        | 0.87%   |
| ASUSTek Computer                | 2        | 0.87%   |
| Xiaomi                          | 1        | 0.44%   |
| Wilocity                        | 1        | 0.44%   |
| Linksys                         | 1        | 0.44%   |
| IMC Networks                    | 1        | 0.44%   |
| D-Link System                   | 1        | 0.44%   |
| Broadcom Limited                | 1        | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 64       | 27.83%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 19       | 8.26%   |
| Intel Wireless-AC 9260                                                        | 14       | 6.09%   |
| Intel Wireless 7260                                                           | 8        | 3.48%   |
| Realtek 802.11ac NIC                                                          | 7        | 3.04%   |
| Intel Wireless 8260                                                           | 7        | 3.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5        | 2.17%   |
| Ralink MT7601U Wireless Adapter                                               | 5        | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5        | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 5        | 2.17%   |
| Ralink RT5370 Wireless Adapter                                                | 4        | 1.74%   |
| TP-Link Archer T4U ver.3                                                      | 3        | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3        | 1.3%    |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 3        | 1.3%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 3        | 1.3%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 3        | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3        | 1.3%    |
| Intel Wireless 8265 / 8275                                                    | 3        | 1.3%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 3        | 1.3%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 3        | 1.3%    |
| TP-Link 802.11ac NIC                                                          | 2        | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.87%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                           | 2        | 0.87%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.87%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 2        | 0.87%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 2        | 0.87%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 2        | 0.87%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2        | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2        | 0.87%   |
| NetGear A6210                                                                 | 2        | 0.87%   |
| Microsoft XBOX ACC                                                            | 2        | 0.87%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                             | 1        | 0.43%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                            | 1        | 0.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.43%   |
| TP-Link TL-WN722N v2                                                          | 1        | 0.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.43%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1        | 0.43%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                          | 1        | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.43%   |
| Ralink RT2760 Wireless 802.11n 1T/2R                                          | 1        | 0.43%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1        | 0.43%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 1        | 0.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.43%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.43%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1        | 0.43%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.43%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]        | 1        | 0.43%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]              | 1        | 0.43%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]        | 1        | 0.43%   |
| Intel Wireless 7265                                                           | 1        | 0.43%   |
| Intel Wireless 3165                                                           | 1        | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 0.43%   |
| Intel Ultimate N WiFi Link 5300                                               | 1        | 0.43%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 0.43%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 0.43%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 225      | 48.49%  |
| Intel                    | 175      | 37.72%  |
| Qualcomm Atheros         | 19       | 4.09%   |
| Aquantia                 | 10       | 2.16%   |
| Broadcom                 | 8        | 1.72%   |
| Nvidia                   | 5        | 1.08%   |
| Marvell Technology Group | 4        | 0.86%   |
| Xiaomi                   | 3        | 0.65%   |
| Broadcom Limited         | 3        | 0.65%   |
| Motorola PCS             | 2        | 0.43%   |
| ICS Advent               | 2        | 0.43%   |
| Huawei Technologies      | 2        | 0.43%   |
| Qualcomm                 | 1        | 0.22%   |
| Mellanox Technologies    | 1        | 0.22%   |
| D-Link System            | 1        | 0.22%   |
| D-Link                   | 1        | 0.22%   |
| Apple                    | 1        | 0.22%   |
| Accton Technology        | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 179      | 36.09%  |
| Intel I211 Gigabit Network Connection                                         | 56       | 11.29%  |
| Realtek RTL8125 2.5GbE Controller                                             | 31       | 6.25%   |
| Intel Ethernet Connection (2) I219-V                                          | 30       | 6.05%   |
| Intel Ethernet Connection (7) I219-V                                          | 12       | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12       | 2.42%   |
| Intel Ethernet Controller I225-V                                              | 11       | 2.22%   |
| Intel Ethernet Connection (2) I218-V                                          | 11       | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9        | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 8        | 1.61%   |
| Intel Ethernet Connection I217-LM                                             | 8        | 1.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7        | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 1.21%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 1.21%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 6        | 1.21%   |
| Intel Ethernet Connection I217-V                                              | 5        | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 5        | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 0.81%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 0.81%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.81%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 4        | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 3        | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3        | 0.6%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.6%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 3        | 0.6%    |
| Intel Ethernet Connection (12) I219-V                                         | 3        | 0.6%    |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.6%    |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2        | 0.4%    |
| Nvidia MCP77 Ethernet                                                         | 2        | 0.4%    |
| Motorola PCS moto e5                                                          | 2        | 0.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.4%    |
| Huawei SPN-AL00                                                               | 2        | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.4%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                       | 2        | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1        | 0.2%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.2%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.2%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.2%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.2%    |
| Qualcomm Android                                                              | 1        | 0.2%    |
| Nvidia MCP73 Ethernet                                                         | 1        | 0.2%    |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.2%    |
| Nvidia CK804 Ethernet Controller                                              | 1        | 0.2%    |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.2%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.2%    |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.2%    |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.2%    |
| Intel Ethernet Connection (10) I219-V                                         | 1        | 0.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 0.2%    |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 0.2%    |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 0.2%    |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.2%    |
| Intel 82546GB Gigabit Ethernet Controller                                     | 1        | 0.2%    |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                            | 1        | 0.2%    |
| Intel 82545GM Gigabit Ethernet Controller                                     | 1        | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 411      | 65.76%  |
| WiFi     | 208      | 33.28%  |
| Modem    | 6        | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 379      | 70.84%  |
| WiFi     | 156      | 29.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 211      | 50%     |
| 2     | 161      | 38.15%  |
| 3     | 37       | 8.77%   |
| 4     | 6        | 1.42%   |
| 5     | 3        | 0.71%   |
| 0     | 3        | 0.71%   |
| 9     | 1        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 322      | 76.48%  |
| Yes  | 99       | 23.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 121      | 60.8%   |
| Cambridge Silicon Radio         | 33       | 16.58%  |
| Broadcom                        | 14       | 7.04%   |
| ASUSTek Computer                | 10       | 5.03%   |
| Realtek Semiconductor           | 7        | 3.52%   |
| IMC Networks                    | 5        | 2.51%   |
| Qualcomm Atheros Communications | 4        | 2.01%   |
| Lite-On Technology              | 1        | 0.5%    |
| Edimax Technology               | 1        | 0.5%    |
| Dynex                           | 1        | 0.5%    |
| D-Link System                   | 1        | 0.5%    |
| Apple                           | 1        | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                   | 58       | 29.15%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 33       | 16.58%  |
| Intel Bluetooth Device                                  | 32       | 16.08%  |
| Intel Bluetooth wireless interface                      | 16       | 8.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 15       | 7.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 11       | 5.53%   |
| Realtek Bluetooth Radio                                 | 5        | 2.51%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 4        | 2.01%   |
| IMC Networks Bluetooth Device                           | 3        | 1.51%   |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 2        | 1.01%   |
| ASUS Bluetooth Radio                                    | 2        | 1.01%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                       | 1        | 0.5%    |
| Lite-On Bluetooth Device                                | 1        | 0.5%    |
| IMC Networks Bluetooth Radio                            | 1        | 0.5%    |
| IMC Networks Bluetooth Module                           | 1        | 0.5%    |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 0.5%    |
| Dynex BCM20702A0                                        | 1        | 0.5%    |
| D-Link System DBT-122 Bluetooth                         | 1        | 0.5%    |
| Broadcom HP Portable Bumble Bee                         | 1        | 0.5%    |
| Broadcom BCM20702A0                                     | 1        | 0.5%    |
| Broadcom BCM2045 Bluetooth                              | 1        | 0.5%    |
| ASUS Qualcomm Bluetooth 4.1                             | 1        | 0.5%    |
| ASUS Bluetooth Device                                   | 1        | 0.5%    |
| ASUS BCM20702A0                                         | 1        | 0.5%    |
| ASUS ASUS USB-BT500                                     | 1        | 0.5%    |
| Apple Bluetooth USB Host Controller                     | 1        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 224      | 29.24%  |
| AMD                         | 221      | 28.85%  |
| Nvidia                      | 183      | 23.89%  |
| C-Media Electronics         | 25       | 3.26%   |
| Logitech                    | 11       | 1.44%   |
| Creative Technology         | 10       | 1.31%   |
| Creative Labs               | 6        | 0.78%   |
| Corsair                     | 6        | 0.78%   |
| SteelSeries ApS             | 5        | 0.65%   |
| Kingston Technology         | 5        | 0.65%   |
| Generalplus Technology      | 5        | 0.65%   |
| Focusrite-Novation          | 5        | 0.65%   |
| Blue Microphones            | 5        | 0.65%   |
| Razer USA                   | 4        | 0.52%   |
| Plantronics                 | 4        | 0.52%   |
| Samson Technologies         | 3        | 0.39%   |
| RODE Microphones            | 3        | 0.39%   |
| GYROCOM C&C                 | 3        | 0.39%   |
| ULi Electronics             | 2        | 0.26%   |
| Tenx Technology             | 2        | 0.26%   |
| Schiit Audio                | 2        | 0.26%   |
| GN Netcom                   | 2        | 0.26%   |
| Cambridge Silicon Radio     | 2        | 0.26%   |
| ASUSTek Computer            | 2        | 0.26%   |
| Yamaha                      | 1        | 0.13%   |
| Xilinx                      | 1        | 0.13%   |
| VIA Technologies            | 1        | 0.13%   |
| USB MICROPHONE              | 1        | 0.13%   |
| Thermaltake                 | 1        | 0.13%   |
| Texas Instruments           | 1        | 0.13%   |
| Sony                        | 1        | 0.13%   |
| Shenzhen Riitek Technology  | 1        | 0.13%   |
| PreSonus Audio Electronics  | 1        | 0.13%   |
| Meridian                    | 1        | 0.13%   |
| Medeli Electronics          | 1        | 0.13%   |
| Mark of the Unicorn         | 1        | 0.13%   |
| Lenovo                      | 1        | 0.13%   |
| JMTek                       | 1        | 0.13%   |
| JBL                         | 1        | 0.13%   |
| iPassion Technology         | 1        | 0.13%   |
| iCreate Technologies        | 1        | 0.13%   |
| Griffin Technology          | 1        | 0.13%   |
| Giga-Byte Technology        | 1        | 0.13%   |
| FiiO Electronics Technology | 1        | 0.13%   |
| FIFINE Microphones          | 1        | 0.13%   |
| EGO SYStems                 | 1        | 0.13%   |
| BEHRINGER International     | 1        | 0.13%   |
| Astro Gaming                | 1        | 0.13%   |
| Apogee Electronics          | 1        | 0.13%   |
| Alesis                      | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 80       | 8.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 40       | 4.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 35       | 3.89%   |
| Intel 200 Series PCH HD Audio                                                     | 33       | 3.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 30       | 3.33%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 28       | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 24       | 2.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 23       | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 20       | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                        | 19       | 2.11%   |
| AMD Navi 10 HDMI Audio                                                            | 19       | 2.11%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 18       | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 18       | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                                      | 18       | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 18       | 2%      |
| Nvidia GP106 High Definition Audio Controller                                     | 17       | 1.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 17       | 1.89%   |
| Nvidia GP104 High Definition Audio Controller                                     | 15       | 1.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 15       | 1.67%   |
| Nvidia TU116 High Definition Audio Controller                                     | 14       | 1.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14       | 1.56%   |
| Nvidia TU106 High Definition Audio Controller                                     | 12       | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 10       | 1.11%   |
| Nvidia GM204 High Definition Audio Controller                                     | 9        | 1%      |
| AMD FCH Azalia Controller                                                         | 9        | 1%      |
| Nvidia TU104 HD Audio Controller                                                  | 8        | 0.89%   |
| Nvidia GA104 High Definition Audio Controller                                     | 8        | 0.89%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                    | 8        | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8        | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 8        | 0.89%   |
| Nvidia High Definition Audio Controller                                           | 7        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 7        | 0.78%   |
| C-Media Electronics USB Audio Device                                              | 7        | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 7        | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                                     | 6        | 0.67%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 6        | 0.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6        | 0.67%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                         | 6        | 0.67%   |
| Nvidia TU102 High Definition Audio Controller                                     | 5        | 0.56%   |
| Nvidia GP108 High Definition Audio Controller                                     | 5        | 0.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 0.56%   |
| Generalplus Technology Usb Audio Device                                           | 5        | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 5        | 0.56%   |
| SteelSeries ApS SteelSeries Arctis 7                                              | 4        | 0.44%   |
| Nvidia GP102 HDMI Audio Controller                                                | 4        | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 0.44%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4        | 0.44%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 0.44%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 4        | 0.44%   |
| C-Media Electronics Blue Snowball                                                 | 4        | 0.44%   |
| Blue Microphones Yeti Stereo Microphone                                           | 4        | 0.44%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 4        | 0.44%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 0.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 0.33%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 0.33%   |
| Nvidia GF116 High Definition Audio Controller                                     | 3        | 0.33%   |
| Nvidia Audio device                                                               | 3        | 0.33%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.33%   |
| Intel Audio device                                                                | 3        | 0.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3        | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 46       | 20.91%  |
| Corsair             | 42       | 19.09%  |
| G.Skill             | 33       | 15%     |
| Unknown             | 26       | 11.82%  |
| Samsung Electronics | 17       | 7.73%   |
| SK Hynix            | 13       | 5.91%   |
| Crucial             | 13       | 5.91%   |
| Micron Technology   | 11       | 5%      |
| GOODRAM             | 3        | 1.36%   |
| Elpida              | 3        | 1.36%   |
| A-DATA Technology   | 3        | 1.36%   |
| Patriot             | 2        | 0.91%   |
| Unknown (ABCD)      | 1        | 0.45%   |
| Transcend           | 1        | 0.45%   |
| Teikon              | 1        | 0.45%   |
| Team                | 1        | 0.45%   |
| Smart               | 1        | 0.45%   |
| Silicon Power       | 1        | 0.45%   |
| pqi                 | 1        | 0.45%   |
| Nanya Technology    | 1        | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 667MT/s                               | 3        | 1.23%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s              | 3        | 1.23%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s               | 3        | 1.23%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s            | 3        | 1.23%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s           | 3        | 1.23%   |
| Corsair RAM CMW16GX4M2C3200C16 8192MB DIMM DDR4 3266MT/s          | 3        | 1.23%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3466MT/s          | 3        | 1.23%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3000MT/s            | 3        | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                         | 2        | 0.82%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                           | 2        | 0.82%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s           | 2        | 0.82%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 2        | 0.82%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 2        | 0.82%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s                        | 2        | 0.82%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                 | 2        | 0.82%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                 | 2        | 0.82%   |
| Kingston RAM KHX2133C14D4/8G 8192MB DIMM 2667MT/s                 | 2        | 0.82%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s            | 2        | 0.82%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3600MT/s             | 2        | 0.82%   |
| G.Skill RAM F4-3600C19-16GVRB 16GB DIMM DDR4 3600MT/s             | 2        | 0.82%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s            | 2        | 0.82%   |
| Corsair RAM CMW32GX4M2C3200C16 16384MB DIMM DDR4 3200MT/s         | 2        | 0.82%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s              | 2        | 0.82%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s            | 2        | 0.82%   |
| Corsair RAM CMK32GX4M2B3000C15 16384MB DIMM DDR4 3000MT/s         | 2        | 0.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s          | 2        | 0.82%   |
| Corsair RAM CMK16GX4M2A2666C16 8192MB DIMM DDR4 3200MT/s          | 2        | 0.82%   |
| Unknown RAM TL48G32S8KGRGB16 8GB DIMM DDR4 3200MT/s               | 1        | 0.41%   |
| Unknown RAM RXD4P12008GA 8GB DIMM DDR4 2400MT/s                   | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR 1333MT/s                          | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM SDRAM                               | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                         | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM 800MT/s                               | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM 400MT/s                               | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 4GB DIMM                                       | 1        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                         | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                          | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM 400MT/s                               | 1        | 0.41%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1        | 0.41%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                          | 1        | 0.41%   |
| Unknown RAM Module 1GB DIMM DDR2 1066MT/s                         | 1        | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM LPDDR4 2400MT/s | 1        | 0.41%   |
| Transcend RAM TS512MLK72V6N 4GB DIMM DDR3 1600MT/s                | 1        | 0.41%   |
| Teikon RAM TMT351U6EFR8C-PBHJ 4GB DIMM DDR3 1600MT/s              | 1        | 0.41%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3200MT/s             | 1        | 0.41%   |
| Smart RAM SH564128FH8N6TNSQG 4096MB DIMM DDR3 1600MT/s            | 1        | 0.41%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1        | 0.41%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 0.41%   |
| SK Hynix RAM HMT451U7BFR8C-RD 4GB DIMM DDR3 1333MT/s              | 1        | 0.41%   |
| SK Hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 0.41%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 1600MT/s           | 1        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 118      | 61.78%  |
| DDR3    | 51       | 26.7%   |
| DDR2    | 8        | 4.19%   |
| Unknown | 8        | 4.19%   |
| DDR     | 4        | 2.09%   |
| SDRAM   | 1        | 0.52%   |
| LPDDR4  | 1        | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 182      | 95.29%  |
| SODIMM | 8        | 4.19%   |
| RIMM   | 1        | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 81       | 38.94%  |
| 16384 | 49       | 23.56%  |
| 4096  | 37       | 17.79%  |
| 2048  | 27       | 12.98%  |
| 32768 | 7        | 3.37%   |
| 1024  | 6        | 2.88%   |
| 512   | 1        | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 35       | 16.2%   |
| 1600    | 32       | 14.81%  |
| 3600    | 19       | 8.8%    |
| 1333    | 17       | 7.87%   |
| 2400    | 15       | 6.94%   |
| 2133    | 13       | 6.02%   |
| 2667    | 10       | 4.63%   |
| 3000    | 9        | 4.17%   |
| 2800    | 6        | 2.78%   |
| 667     | 6        | 2.78%   |
| 1067    | 5        | 2.31%   |
| 1867    | 4        | 1.85%   |
| 800     | 4        | 1.85%   |
| 3800    | 3        | 1.39%   |
| 3733    | 3        | 1.39%   |
| 3466    | 3        | 1.39%   |
| 3400    | 3        | 1.39%   |
| 3266    | 3        | 1.39%   |
| 2933    | 3        | 1.39%   |
| 1066    | 3        | 1.39%   |
| 333     | 3        | 1.39%   |
| 3533    | 2        | 0.93%   |
| 2666    | 2        | 0.93%   |
| 1866    | 2        | 0.93%   |
| 1800    | 2        | 0.93%   |
| Unknown | 2        | 0.93%   |
| 3866    | 1        | 0.46%   |
| 3666    | 1        | 0.46%   |
| 3467    | 1        | 0.46%   |
| 3100    | 1        | 0.46%   |
| 2134    | 1        | 0.46%   |
| 933     | 1        | 0.46%   |
| 400     | 1        | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 12       | 46.15%  |
| Brother Industries  | 6        | 23.08%  |
| Seiko Epson         | 2        | 7.69%   |
| Canon               | 2        | 7.69%   |
| Xerox               | 1        | 3.85%   |
| Samsung Electronics | 1        | 3.85%   |
| Prolific Technology | 1        | 3.85%   |
| Dymo-CoStar         | 1        | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP OfficeJet 6950                            | 2        | 7.69%   |
| HP DeskJet 2600 series                       | 2        | 7.69%   |
| Xerox Phaser 3010                            | 1        | 3.85%   |
| Seiko Epson PX-045A Series                   | 1        | 3.85%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 3.85%   |
| Samsung M2070 Series                         | 1        | 3.85%   |
| Prolific PL2305 Parallel Port                | 1        | 3.85%   |
| HP Neverstop Laser 100x                      | 1        | 3.85%   |
| HP LaserJet Professional P 1102w             | 1        | 3.85%   |
| HP LaserJet P1006                            | 1        | 3.85%   |
| HP Ink Tank 310 series                       | 1        | 3.85%   |
| HP ENVY 5000 series                          | 1        | 3.85%   |
| HP DeskJet F4100 Printer series              | 1        | 3.85%   |
| HP Deskjet D2500 series                      | 1        | 3.85%   |
| HP DeskJet 4530 series                       | 1        | 3.85%   |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1        | 3.85%   |
| Canon PIXMA MP270 All-In-One Printer         | 1        | 3.85%   |
| Canon LiDE 300                               | 1        | 3.85%   |
| Brother Printer                              | 1        | 3.85%   |
| Brother MFC-9330CDW                          | 1        | 3.85%   |
| Brother MFC-9325CW                           | 1        | 3.85%   |
| Brother HL-L2340D series                     | 1        | 3.85%   |
| Brother HL-1430 Laser Printer                | 1        | 3.85%   |
| Brother DCP-7040                             | 1        | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 4        | 44.44%  |
| Canon           | 4        | 44.44%  |
| Hewlett-Packard | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1        | 11.11%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 11.11%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 11.11%  |
| Seiko Epson GT-F670 [Perfection V200 Photo]             | 1        | 11.11%  |
| HP ScanJet G4050                                        | 1        | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                           | 1        | 11.11%  |
| Canon CanoScan LiDE 70                                  | 1        | 11.11%  |
| Canon CanoScan LiDE 220                                 | 1        | 11.11%  |
| Canon CanoScan 4400F                                    | 1        | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 49       | 42.98%  |
| Microsoft                     | 7        | 6.14%   |
| Microdia                      | 6        | 5.26%   |
| Sunplus Innovation Technology | 5        | 4.39%   |
| Realtek Semiconductor         | 5        | 4.39%   |
| SHENZHEN Fullhan              | 4        | 3.51%   |
| Samsung Electronics           | 4        | 3.51%   |
| Jieli Technology              | 3        | 2.63%   |
| Z-Star Microelectronics       | 2        | 1.75%   |
| Unknown                       | 2        | 1.75%   |
| Trust                         | 2        | 1.75%   |
| Razer USA                     | 2        | 1.75%   |
| HD WEBCAM                     | 2        | 1.75%   |
| Generalplus Technology        | 2        | 1.75%   |
| Creative Technology           | 2        | 1.75%   |
| AVerMedia Technologies        | 2        | 1.75%   |
| ARC International             | 2        | 1.75%   |
| Apple                         | 2        | 1.75%   |
| Alcor Micro                   | 2        | 1.75%   |
| Sony                          | 1        | 0.88%   |
| OmniVision Technologies       | 1        | 0.88%   |
| LG Electronics                | 1        | 0.88%   |
| Lenovo                        | 1        | 0.88%   |
| KYE Systems (Mouse Systems)   | 1        | 0.88%   |
| INOGENI                       | 1        | 0.88%   |
| Hewlett-Packard               | 1        | 0.88%   |
| BUFFALO                       | 1        | 0.88%   |
| Alcorlink                     | 1        | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 16       | 13.56%  |
| Logitech HD Pro Webcam C920                     | 10       | 8.47%   |
| Logitech HD Webcam C525                         | 6        | 5.08%   |
| Microdia USB 2.0 Camera                         | 5        | 4.24%   |
| SHENZHEN Fullhan webcam                         | 4        | 3.39%   |
| Samsung Galaxy series, misc. (MTP mode)         | 4        | 3.39%   |
| Microsoft LifeCam Cinema                        | 4        | 3.39%   |
| Logitech Webcam C925e                           | 3        | 2.54%   |
| Logitech StreamCam                              | 3        | 2.54%   |
| Jieli USB PHY 2.0                               | 3        | 2.54%   |
| Sunplus HD 720P webcam                          | 2        | 1.69%   |
| Realtek FULL HD 1080P Webcam                    | 2        | 1.69%   |
| Razer USA Razer Kiyo                            | 2        | 1.69%   |
| Logitech Webcam C930e                           | 2        | 1.69%   |
| Logitech QuickCam Pro for Notebooks             | 2        | 1.69%   |
| Logitech C922 Pro Stream Webcam                 | 2        | 1.69%   |
| HD WEBCAM NexiGo N660 FHD Webcam                | 2        | 1.69%   |
| Generalplus 808 Camera                          | 2        | 1.69%   |
| Creative Live! Cam Sync 1080p                   | 2        | 1.69%   |
| ARC International Camera                        | 2        | 1.69%   |
| Apple iPhone5/5C/5S/6                           | 2        | 1.69%   |
| Alcor Micro USB 2.0 PC Camera                   | 2        | 1.69%   |
| Z-Star Venus USB2.0 Camera                      | 1        | 0.85%   |
| Z-Star A4 TECH USB2.0 PC Camera J               | 1        | 0.85%   |
| Unknown HD Camera                               | 1        | 0.85%   |
| Unknown HD 720P                                 | 1        | 0.85%   |
| Trust Widescreen 3MP Webcam                     | 1        | 0.85%   |
| Trust USB Camera                                | 1        | 0.85%   |
| Sunplus UHD Capture                             | 1        | 0.85%   |
| Sunplus FanNicao S20                            | 1        | 0.85%   |
| Sunplus ezcap U3 capture-04                     | 1        | 0.85%   |
| Sony CEVCECM                                    | 1        | 0.85%   |
| Realtek USB Camera                              | 1        | 0.85%   |
| Realtek Streaming Webcam                        | 1        | 0.85%   |
| Realtek NexiGo N960E FHD Webcam                 | 1        | 0.85%   |
| OmniVision Monitor Webcam                       | 1        | 0.85%   |
| Microsoft LifeCam VX-2000                       | 1        | 0.85%   |
| Microsoft LifeCam Studio                        | 1        | 0.85%   |
| Microsoft LifeCam HD-3000                       | 1        | 0.85%   |
| Microdia Integrated Camera                      | 1        | 0.85%   |
| Logitech Webcam C310                            | 1        | 0.85%   |
| Logitech Webcam C210                            | 1        | 0.85%   |
| Logitech Webcam C170                            | 1        | 0.85%   |
| Logitech Webcam C120                            | 1        | 0.85%   |
| Logitech QuickCam Pro 9000                      | 1        | 0.85%   |
| Logitech HD Webcam C615                         | 1        | 0.85%   |
| Logitech BRIO 4K Stream Edition                 | 1        | 0.85%   |
| Logitech BRIO                                   | 1        | 0.85%   |
| LG VS996                                        | 1        | 0.85%   |
| Lenovo FHD Webcam                               | 1        | 0.85%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 0.85%   |
| INOGENI 1C3E-INOGENI SDI2USB3                   | 1        | 0.85%   |
| HP HD-4110 Webcam                               | 1        | 0.85%   |
| BUFFALO USB 2.0 Camera                          | 1        | 0.85%   |
| BUFFALO BUFFALO BSWHD06M USB Camera             | 1        | 0.85%   |
| AVerMedia Live Streamer CAM 313                 | 1        | 0.85%   |
| AVerMedia Live Gamer Ultra-Video                | 1        | 0.85%   |
| Alcorlink USB 2.0 Camera                        | 1        | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 50%     |
| OmniKey               | 1        | 25%     |
| Cherry                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 50%     |
| OmniKey CardMan 3021 / 3121                       | 1        | 25%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC       | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 372      | 87.53%  |
| 1     | 49       | 11.53%  |
| 2     | 4        | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 19       | 35.19%  |
| Graphics card            | 14       | 25.93%  |
| Unassigned class         | 8        | 14.81%  |
| Camera                   | 3        | 5.56%   |
| Sound                    | 2        | 3.7%    |
| Multimedia controller    | 2        | 3.7%    |
| Network                  | 1        | 1.85%   |
| Fingerprint reader       | 1        | 1.85%   |
| Dvb card                 | 1        | 1.85%   |
| Communication controller | 1        | 1.85%   |
| Card reader              | 1        | 1.85%   |
| Bluetooth                | 1        | 1.85%   |

