Ubuntu 21.10 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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
| HP            | 0AECh D                     | [b9550ddc31](https://linux-hardware.org/?probe=b9550ddc31) | Dec 03, 2021 |
| HP            | 0AECh D                     | [61d0324f27](https://linux-hardware.org/?probe=61d0324f27) | Dec 03, 2021 |
| MSI           | B450M-A PRO MAX             | [17a6983b50](https://linux-hardware.org/?probe=17a6983b50) | Dec 03, 2021 |
| Gigabyte      | 970A-DS3P                   | [054aa7b858](https://linux-hardware.org/?probe=054aa7b858) | Dec 02, 2021 |
| OEM           | TOP77D Ver1.0               | [8348cb42fc](https://linux-hardware.org/?probe=8348cb42fc) | Dec 02, 2021 |
| Lenovo        | NO DPK                      | [0d7784e414](https://linux-hardware.org/?probe=0d7784e414) | Dec 02, 2021 |
| Gigabyte      | X570 UD                     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [876f4598f0](https://linux-hardware.org/?probe=876f4598f0) | Dec 01, 2021 |
| HP            | 212B                        | [b8688e6712](https://linux-hardware.org/?probe=b8688e6712) | Dec 01, 2021 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [0e0cd0b225](https://linux-hardware.org/?probe=0e0cd0b225) | Dec 01, 2021 |
| OEM           | TOP77D Ver1.0               | [6b91b58b81](https://linux-hardware.org/?probe=6b91b58b81) | Nov 30, 2021 |
| MSI           | B460M-A PRO                 | [f972dc5e2a](https://linux-hardware.org/?probe=f972dc5e2a) | Nov 30, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [b3f648de8e](https://linux-hardware.org/?probe=b3f648de8e) | Nov 29, 2021 |
| ECS           | G31T-M7                     | [749da166c4](https://linux-hardware.org/?probe=749da166c4) | Nov 29, 2021 |
| ASRock        | G31M-VS                     | [b042297ea5](https://linux-hardware.org/?probe=b042297ea5) | Nov 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [8c2024b822](https://linux-hardware.org/?probe=8c2024b822) | Nov 28, 2021 |
| Dell          | 0WR7PY A01                  | [f886714ec5](https://linux-hardware.org/?probe=f886714ec5) | Nov 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | [17bd2e3558](https://linux-hardware.org/?probe=17bd2e3558) | Nov 28, 2021 |
| ASUSTek       | PRIME B450M-A               | [629e6cac75](https://linux-hardware.org/?probe=629e6cac75) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [88cf97c553](https://linux-hardware.org/?probe=88cf97c553) | Nov 27, 2021 |
| Gigabyte      | P35-S3G                     | [f8b94398df](https://linux-hardware.org/?probe=f8b94398df) | Nov 27, 2021 |
| ASRock        | A320M-HDV R4.0              | [59f124bbad](https://linux-hardware.org/?probe=59f124bbad) | Nov 27, 2021 |
| Pegatron      | 2A86E01                     | [17a1186394](https://linux-hardware.org/?probe=17a1186394) | Nov 26, 2021 |
| Gigabyte      | GA-MA770-UD3                | [551c45ed6b](https://linux-hardware.org/?probe=551c45ed6b) | Nov 26, 2021 |
| HP            | 2129                        | [8379f5fd56](https://linux-hardware.org/?probe=8379f5fd56) | Nov 26, 2021 |
| Gigabyte      | GA-MA770-UD3                | [58da56c671](https://linux-hardware.org/?probe=58da56c671) | Nov 26, 2021 |
| Gigabyte      | H77M-D3H                    | [a2606aebd8](https://linux-hardware.org/?probe=a2606aebd8) | Nov 26, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | [52d32ab3be](https://linux-hardware.org/?probe=52d32ab3be) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1c3cabc42a](https://linux-hardware.org/?probe=1c3cabc42a) | Nov 25, 2021 |
| MSI           | MPG Z590 GAMING CARBON W... | [651bc7560d](https://linux-hardware.org/?probe=651bc7560d) | Nov 25, 2021 |
| Acer          | G31T-M5                     | [a561aa834a](https://linux-hardware.org/?probe=a561aa834a) | Nov 25, 2021 |
| Gigabyte      | 970A-D3P                    | [76e0745afc](https://linux-hardware.org/?probe=76e0745afc) | Nov 24, 2021 |
| ASRock        | A320M-HDV R4.0              | [e7ab7b2011](https://linux-hardware.org/?probe=e7ab7b2011) | Nov 24, 2021 |
| MSI           | H510I PRO WIFI              | [b9b9b8c6ee](https://linux-hardware.org/?probe=b9b9b8c6ee) | Nov 24, 2021 |
| MSI           | H510I PRO WIFI              | [1abf510439](https://linux-hardware.org/?probe=1abf510439) | Nov 24, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [148f8b6de1](https://linux-hardware.org/?probe=148f8b6de1) | Nov 24, 2021 |
| ASUSTek       | PRIME X370-PRO              | [011f4ef64a](https://linux-hardware.org/?probe=011f4ef64a) | Nov 24, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [021d70dbf2](https://linux-hardware.org/?probe=021d70dbf2) | Nov 24, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [bcf9812525](https://linux-hardware.org/?probe=bcf9812525) | Nov 24, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [dab9856bd1](https://linux-hardware.org/?probe=dab9856bd1) | Nov 24, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9bd8ca78c3](https://linux-hardware.org/?probe=9bd8ca78c3) | Nov 24, 2021 |
| HP            | 3397                        | [5412dd8b52](https://linux-hardware.org/?probe=5412dd8b52) | Nov 23, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [2d5ec95a93](https://linux-hardware.org/?probe=2d5ec95a93) | Nov 23, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [3fcd092ee3](https://linux-hardware.org/?probe=3fcd092ee3) | Nov 23, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [8e73316539](https://linux-hardware.org/?probe=8e73316539) | Nov 23, 2021 |
| ASUSTek       | PRIME Z590-P                | [69fe9cde99](https://linux-hardware.org/?probe=69fe9cde99) | Nov 23, 2021 |
| Unknown       | Unknown                     | [57364e93b2](https://linux-hardware.org/?probe=57364e93b2) | Nov 23, 2021 |
| MSI           | PRO Z690-A DDR4             | [1022ba26e4](https://linux-hardware.org/?probe=1022ba26e4) | Nov 22, 2021 |
| JGINYUE       | H97I PLUS V2.0              | [fcefb22fe5](https://linux-hardware.org/?probe=fcefb22fe5) | Nov 22, 2021 |
| Gigabyte      | A320M-DS2-CF                | [02020c5820](https://linux-hardware.org/?probe=02020c5820) | Nov 22, 2021 |
| HP            | 0AECh D                     | [c2d85e5d81](https://linux-hardware.org/?probe=c2d85e5d81) | Nov 22, 2021 |
| Gigabyte      | B75M-D3H                    | [939cd87ee7](https://linux-hardware.org/?probe=939cd87ee7) | Nov 22, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [4c603f8b64](https://linux-hardware.org/?probe=4c603f8b64) | Nov 22, 2021 |
| Dell          | 0C27VV A00                  | [d3a7b5b39b](https://linux-hardware.org/?probe=d3a7b5b39b) | Nov 22, 2021 |
| Unknown       | Unknown                     | [ebc991da95](https://linux-hardware.org/?probe=ebc991da95) | Nov 22, 2021 |
| ASRock        | X99M Extreme4               | [3f738eedfc](https://linux-hardware.org/?probe=3f738eedfc) | Nov 22, 2021 |
| Lenovo        | 1036 SDK0T76457 WIN 3915... | [f894442edc](https://linux-hardware.org/?probe=f894442edc) | Nov 22, 2021 |
| ASRock        | Z390 Extreme4               | [12f1aecfc3](https://linux-hardware.org/?probe=12f1aecfc3) | Nov 21, 2021 |
| ASUSTek       | P5L-VM 1394                 | [a43426b94f](https://linux-hardware.org/?probe=a43426b94f) | Nov 21, 2021 |
| ASUSTek       | M2N                         | [06bba5770c](https://linux-hardware.org/?probe=06bba5770c) | Nov 21, 2021 |
| HP            | 0AECh D                     | [4edef515e0](https://linux-hardware.org/?probe=4edef515e0) | Nov 21, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [64591821a6](https://linux-hardware.org/?probe=64591821a6) | Nov 20, 2021 |
| Lenovo        | ThinkServer TS140           | [da5af2478e](https://linux-hardware.org/?probe=da5af2478e) | Nov 20, 2021 |
| MSI           | PRO Z690-A DDR4             | [64e545e8b1](https://linux-hardware.org/?probe=64e545e8b1) | Nov 20, 2021 |
| Dell          | 0Y5DDC A00                  | [9f04ac4715](https://linux-hardware.org/?probe=9f04ac4715) | Nov 20, 2021 |
| Fujitsu       | FujitsuTP7000 -1            | [a509f56734](https://linux-hardware.org/?probe=a509f56734) | Nov 20, 2021 |
| ASUSTek       | M2N                         | [dfc5087439](https://linux-hardware.org/?probe=dfc5087439) | Nov 20, 2021 |
| ASUSTek       | PRIME H510M-K               | [dc3ffc2288](https://linux-hardware.org/?probe=dc3ffc2288) | Nov 20, 2021 |
| ASRock        | Z690 Steel Legend           | [73afa3e4f2](https://linux-hardware.org/?probe=73afa3e4f2) | Nov 19, 2021 |
| ASUSTek       | Rampage IV EXTREME          | [50dbf1ce3d](https://linux-hardware.org/?probe=50dbf1ce3d) | Nov 19, 2021 |
| MSI           | Z170A SLI                   | [2705718ac8](https://linux-hardware.org/?probe=2705718ac8) | Nov 19, 2021 |
| Gigabyte      | A320M-H-CF                  | [8eeef70a27](https://linux-hardware.org/?probe=8eeef70a27) | Nov 19, 2021 |
| MSI           | Z270 GAMING PLUS            | [28b50f68d2](https://linux-hardware.org/?probe=28b50f68d2) | Nov 19, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | [a1261a6eca](https://linux-hardware.org/?probe=a1261a6eca) | Nov 19, 2021 |
| HP            | ProLiant ML350 Gen9         | [9a5ec34f4b](https://linux-hardware.org/?probe=9a5ec34f4b) | Nov 18, 2021 |
| HP            | 0AECh D                     | [e52cea7894](https://linux-hardware.org/?probe=e52cea7894) | Nov 18, 2021 |
| HP            | 304Ah                       | [988e1e374a](https://linux-hardware.org/?probe=988e1e374a) | Nov 18, 2021 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [61ba55d34f](https://linux-hardware.org/?probe=61ba55d34f) | Nov 18, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [c754a471ba](https://linux-hardware.org/?probe=c754a471ba) | Nov 17, 2021 |
| MSI           | Z97-G45 GAMING              | [fc7a1caa36](https://linux-hardware.org/?probe=fc7a1caa36) | Nov 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [8377977aee](https://linux-hardware.org/?probe=8377977aee) | Nov 17, 2021 |
| Gigabyte      | Z77X-UD5H                   | [f1cd45b49a](https://linux-hardware.org/?probe=f1cd45b49a) | Nov 17, 2021 |
| HP            | 1494                        | [a1e8628159](https://linux-hardware.org/?probe=a1e8628159) | Nov 17, 2021 |
| Gigabyte      | Z690 UD DDR4                | [8435741705](https://linux-hardware.org/?probe=8435741705) | Nov 17, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e460a37b0f](https://linux-hardware.org/?probe=e460a37b0f) | Nov 17, 2021 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [2c5829a148](https://linux-hardware.org/?probe=2c5829a148) | Nov 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3cc581951b](https://linux-hardware.org/?probe=3cc581951b) | Nov 17, 2021 |
| MSI           | H270 GAMING M3              | [d863ad50dd](https://linux-hardware.org/?probe=d863ad50dd) | Nov 16, 2021 |
| Dell          | 0FM586                      | [79a63f7f55](https://linux-hardware.org/?probe=79a63f7f55) | Nov 16, 2021 |
| MSI           | PRO Z690-A DDR4             | [63c901cb53](https://linux-hardware.org/?probe=63c901cb53) | Nov 16, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | [22cf0835fb](https://linux-hardware.org/?probe=22cf0835fb) | Nov 16, 2021 |
| Dell          | 0Y5DDC A00                  | [f90eb0a986](https://linux-hardware.org/?probe=f90eb0a986) | Nov 16, 2021 |
| Dell          | 088DT1 A00                  | [0a20b8ab82](https://linux-hardware.org/?probe=0a20b8ab82) | Nov 16, 2021 |
| MSI           | MEG B550 UNIFY-X            | [c50d253bab](https://linux-hardware.org/?probe=c50d253bab) | Nov 16, 2021 |
| MSI           | MEG B550 UNIFY-X            | [d9142d6737](https://linux-hardware.org/?probe=d9142d6737) | Nov 16, 2021 |
| HP            | 8056                        | [f62a924908](https://linux-hardware.org/?probe=f62a924908) | Nov 16, 2021 |
| ASRock        | Z590M-ITX/ax                | [aa81c59d8a](https://linux-hardware.org/?probe=aa81c59d8a) | Nov 16, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | [1eac89d527](https://linux-hardware.org/?probe=1eac89d527) | Nov 15, 2021 |
| Gigabyte      | A320M-H-CF                  | [a8e3d44c9e](https://linux-hardware.org/?probe=a8e3d44c9e) | Nov 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [1755230380](https://linux-hardware.org/?probe=1755230380) | Nov 15, 2021 |
| MSI           | MS-7250                     | [84c50a42f3](https://linux-hardware.org/?probe=84c50a42f3) | Nov 15, 2021 |
| Dell          | 0HJ054                      | [f7dee29940](https://linux-hardware.org/?probe=f7dee29940) | Nov 14, 2021 |
| Dell          | 0VRWRC A01                  | [e202cef308](https://linux-hardware.org/?probe=e202cef308) | Nov 14, 2021 |
| Pegatron      | 2AB6                        | [3f03379235](https://linux-hardware.org/?probe=3f03379235) | Nov 14, 2021 |
| HP            | 1998                        | [2e830badd5](https://linux-hardware.org/?probe=2e830badd5) | Nov 14, 2021 |
| ASUSTek       | PRIME Z370-A                | [01b7731b34](https://linux-hardware.org/?probe=01b7731b34) | Nov 14, 2021 |
| ASUSTek       | Z87-EXPERT                  | [445090e2b7](https://linux-hardware.org/?probe=445090e2b7) | Nov 14, 2021 |
| Dell          | 0HJ054                      | [298206106c](https://linux-hardware.org/?probe=298206106c) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b1edada81b](https://linux-hardware.org/?probe=b1edada81b) | Nov 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [7ae75212ce](https://linux-hardware.org/?probe=7ae75212ce) | Nov 13, 2021 |
| ASUSTek       | H110M-C                     | [594c61d37a](https://linux-hardware.org/?probe=594c61d37a) | Nov 13, 2021 |
| MSI           | MS-7346                     | [66b30282c8](https://linux-hardware.org/?probe=66b30282c8) | Nov 13, 2021 |
| Acer          | RS780DV                     | [415847f244](https://linux-hardware.org/?probe=415847f244) | Nov 13, 2021 |
| Dell          | 0Y5DDC A00                  | [66188284bd](https://linux-hardware.org/?probe=66188284bd) | Nov 13, 2021 |
| Dell          | 0WMJ54 A01                  | [12892e0de3](https://linux-hardware.org/?probe=12892e0de3) | Nov 13, 2021 |
| Acer          | RS780DV                     | [610927f2e1](https://linux-hardware.org/?probe=610927f2e1) | Nov 12, 2021 |
| Gigabyte      | Z690 UD DDR4                | [8ca8eff19e](https://linux-hardware.org/?probe=8ca8eff19e) | Nov 12, 2021 |
| Gigabyte      | Z690 UD DDR4                | [7f1c2cfc0b](https://linux-hardware.org/?probe=7f1c2cfc0b) | Nov 12, 2021 |
| Dell          | 0WMJ54 A01                  | [eccf63021f](https://linux-hardware.org/?probe=eccf63021f) | Nov 12, 2021 |
| MSI           | B75MA-P45                   | [8196870f95](https://linux-hardware.org/?probe=8196870f95) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-K               | [e995b26637](https://linux-hardware.org/?probe=e995b26637) | Nov 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [867958b2cc](https://linux-hardware.org/?probe=867958b2cc) | Nov 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [27171367d8](https://linux-hardware.org/?probe=27171367d8) | Nov 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [15600f6f21](https://linux-hardware.org/?probe=15600f6f21) | Nov 11, 2021 |
| Dell          | 08HPGT A02                  | [9bf3a3f311](https://linux-hardware.org/?probe=9bf3a3f311) | Nov 10, 2021 |
| ASRock        | Z370 Pro4                   | [e0856ca7fa](https://linux-hardware.org/?probe=e0856ca7fa) | Nov 10, 2021 |
| HP            | 1494                        | [b748a69ed1](https://linux-hardware.org/?probe=b748a69ed1) | Nov 10, 2021 |
| ASRock        | A300M-STX                   | [712e203294](https://linux-hardware.org/?probe=712e203294) | Nov 10, 2021 |
| Gigabyte      | GA-790XTA-UD4               | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| ASUSTek       | P5QP18L/T5-P5G41E           | [c64c41d162](https://linux-hardware.org/?probe=c64c41d162) | Nov 10, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [6f7902132b](https://linux-hardware.org/?probe=6f7902132b) | Nov 10, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [da9d9b9d1e](https://linux-hardware.org/?probe=da9d9b9d1e) | Nov 10, 2021 |
| EVGA          | 111-CS-E371                 | [fd202c951f](https://linux-hardware.org/?probe=fd202c951f) | Nov 09, 2021 |
| Gigabyte      | B85M-D2V                    | [6fbd588373](https://linux-hardware.org/?probe=6fbd588373) | Nov 09, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [2458e67cf5](https://linux-hardware.org/?probe=2458e67cf5) | Nov 09, 2021 |
| MSI           | B350M PRO-VDH               | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| HP            | 1998                        | [c2ab98c42f](https://linux-hardware.org/?probe=c2ab98c42f) | Nov 07, 2021 |
| ASUSTek       | H87-PLUS                    | [a699d4683c](https://linux-hardware.org/?probe=a699d4683c) | Nov 07, 2021 |
| MSI           | MAG B550M MORTAR            | [35b24a070f](https://linux-hardware.org/?probe=35b24a070f) | Nov 07, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [3cf5d9865c](https://linux-hardware.org/?probe=3cf5d9865c) | Nov 07, 2021 |
| HP            | 0A98h                       | [faff7d4f1b](https://linux-hardware.org/?probe=faff7d4f1b) | Nov 07, 2021 |
| MSI           | MEG X570 UNIFY              | [651ac91f37](https://linux-hardware.org/?probe=651ac91f37) | Nov 06, 2021 |
| Lenovo        | ThinkCentre A62 9935B5U     | [85db2ee229](https://linux-hardware.org/?probe=85db2ee229) | Nov 06, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [9ceab9ce1b](https://linux-hardware.org/?probe=9ceab9ce1b) | Nov 06, 2021 |
| Lenovo        | SHARKBAY No DPK             | [92be8f6c8b](https://linux-hardware.org/?probe=92be8f6c8b) | Nov 06, 2021 |
| HP            | Compaq 8200 Elite SFF PC    | [8227932323](https://linux-hardware.org/?probe=8227932323) | Nov 06, 2021 |
| Dell          | 088DT1 A00                  | [1c0647daa9](https://linux-hardware.org/?probe=1c0647daa9) | Nov 05, 2021 |
| Gigabyte      | H510M S2H                   | [1a749d9336](https://linux-hardware.org/?probe=1a749d9336) | Nov 05, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [6d1875bdd9](https://linux-hardware.org/?probe=6d1875bdd9) | Nov 04, 2021 |
| MSI           | A75MA-G55                   | [ccdd789559](https://linux-hardware.org/?probe=ccdd789559) | Nov 04, 2021 |
| MSI           | B150 PC MATE                | [3fdd2f72ac](https://linux-hardware.org/?probe=3fdd2f72ac) | Nov 04, 2021 |
| Dell          | 0NW73C A00                  | [b02dd0e75e](https://linux-hardware.org/?probe=b02dd0e75e) | Nov 04, 2021 |
| MSI           | 3664h                       | [f2547bae94](https://linux-hardware.org/?probe=f2547bae94) | Nov 03, 2021 |
| Gigabyte      | GA-MA74GMT-S2               | [a94050d3b2](https://linux-hardware.org/?probe=a94050d3b2) | Nov 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f8baadef0e](https://linux-hardware.org/?probe=f8baadef0e) | Nov 03, 2021 |
| Dell          | 0YXT71 A01                  | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| ASUSTek       | Z97-K                       | [1e136c311c](https://linux-hardware.org/?probe=1e136c311c) | Nov 03, 2021 |
| Dell          | 0N826N A03                  | [d7d0a0b507](https://linux-hardware.org/?probe=d7d0a0b507) | Nov 03, 2021 |
| Gigabyte      | EP45-UD3R                   | [30d809be04](https://linux-hardware.org/?probe=30d809be04) | Nov 03, 2021 |
| MSI           | Z370M MORTAR                | [b6d4cdb6b9](https://linux-hardware.org/?probe=b6d4cdb6b9) | Nov 03, 2021 |
| MSI           | Z370M MORTAR                | [af4e356569](https://linux-hardware.org/?probe=af4e356569) | Nov 03, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [2e8569e851](https://linux-hardware.org/?probe=2e8569e851) | Nov 02, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [290c114444](https://linux-hardware.org/?probe=290c114444) | Nov 02, 2021 |
| MSI           | 3664h                       | [61d2ff264b](https://linux-hardware.org/?probe=61d2ff264b) | Nov 02, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [ebaea435bf](https://linux-hardware.org/?probe=ebaea435bf) | Nov 02, 2021 |
| ASUSTek       | M3N78                       | [07562bbf08](https://linux-hardware.org/?probe=07562bbf08) | Nov 01, 2021 |
| MSI           | B550-A PRO                  | [ee7c2851a5](https://linux-hardware.org/?probe=ee7c2851a5) | Nov 01, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [e4aeb69a18](https://linux-hardware.org/?probe=e4aeb69a18) | Nov 01, 2021 |
| EVGA          | Z390 FTW                    | [22e9e0f01b](https://linux-hardware.org/?probe=22e9e0f01b) | Nov 01, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [2bee1e8a30](https://linux-hardware.org/?probe=2bee1e8a30) | Nov 01, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [3676c4f8f0](https://linux-hardware.org/?probe=3676c4f8f0) | Nov 01, 2021 |
| EVGA          | 134-KS-E377                 | [27e29303bc](https://linux-hardware.org/?probe=27e29303bc) | Nov 01, 2021 |
| EVGA          | 111-CS-E371                 | [2fc377709d](https://linux-hardware.org/?probe=2fc377709d) | Nov 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [068bee7912](https://linux-hardware.org/?probe=068bee7912) | Oct 31, 2021 |
| Gigabyte      | G1.Assassin                 | [40c84c9637](https://linux-hardware.org/?probe=40c84c9637) | Oct 31, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [5b55e39c35](https://linux-hardware.org/?probe=5b55e39c35) | Oct 31, 2021 |
| ASUSTek       | M2N-E                       | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| HP            | 1587h                       | [0d99c162a3](https://linux-hardware.org/?probe=0d99c162a3) | Oct 31, 2021 |
| HP            | 1587h                       | [2aeea457fd](https://linux-hardware.org/?probe=2aeea457fd) | Oct 31, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [46ebbae78b](https://linux-hardware.org/?probe=46ebbae78b) | Oct 31, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | [e13dd10e78](https://linux-hardware.org/?probe=e13dd10e78) | Oct 31, 2021 |
| Gigabyte      | G31M-ES2L                   | [23b6458508](https://linux-hardware.org/?probe=23b6458508) | Oct 30, 2021 |
| ASUSTek       | PRIME H310T R2.0            | [9f69e439bc](https://linux-hardware.org/?probe=9f69e439bc) | Oct 30, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [0184e22e18](https://linux-hardware.org/?probe=0184e22e18) | Oct 30, 2021 |
| ASRock        | 960GM/U3S3 FX               | [7a2ec5ecff](https://linux-hardware.org/?probe=7a2ec5ecff) | Oct 30, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [4f64db367f](https://linux-hardware.org/?probe=4f64db367f) | Oct 30, 2021 |
| HP            | 0AA8h                       | [40da7a8ae9](https://linux-hardware.org/?probe=40da7a8ae9) | Oct 30, 2021 |
| Dell          | 0N826N A03                  | [ffb75356ef](https://linux-hardware.org/?probe=ffb75356ef) | Oct 30, 2021 |
| MSI           | 3664h                       | [7d44291de8](https://linux-hardware.org/?probe=7d44291de8) | Oct 30, 2021 |
| MSI           | B450M MORTAR MAX            | [cadb142111](https://linux-hardware.org/?probe=cadb142111) | Oct 29, 2021 |
| MSI           | B150M BAZOOKA               | [b396e1c4f4](https://linux-hardware.org/?probe=b396e1c4f4) | Oct 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | [2ce7e668c7](https://linux-hardware.org/?probe=2ce7e668c7) | Oct 29, 2021 |
| Dell          | 0N826N A03                  | [db2a7eba35](https://linux-hardware.org/?probe=db2a7eba35) | Oct 29, 2021 |
| HP            | 0AECh D                     | [665bae2867](https://linux-hardware.org/?probe=665bae2867) | Oct 29, 2021 |
| Dell          | 0C3YXR A00                  | [3fbbe71d21](https://linux-hardware.org/?probe=3fbbe71d21) | Oct 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [89c1a7f472](https://linux-hardware.org/?probe=89c1a7f472) | Oct 28, 2021 |
| Dell          | 0773VG A00                  | [f17f22efdc](https://linux-hardware.org/?probe=f17f22efdc) | Oct 28, 2021 |
| ASUSTek       | CM6870                      | [1575e2c682](https://linux-hardware.org/?probe=1575e2c682) | Oct 28, 2021 |
| MSI           | A88X-G43                    | [1c7a02bd63](https://linux-hardware.org/?probe=1c7a02bd63) | Oct 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d10e4364a0](https://linux-hardware.org/?probe=d10e4364a0) | Oct 27, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [28ddff13b5](https://linux-hardware.org/?probe=28ddff13b5) | Oct 27, 2021 |
| Foxconn       | 2ABF                        | [380d5ab9f0](https://linux-hardware.org/?probe=380d5ab9f0) | Oct 27, 2021 |
| Dell          | 05CNYF A01                  | [95530db3a8](https://linux-hardware.org/?probe=95530db3a8) | Oct 27, 2021 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [0e8d69e9b8](https://linux-hardware.org/?probe=0e8d69e9b8) | Oct 27, 2021 |
| Acer          | Aspire X3450                | [8f27aff70b](https://linux-hardware.org/?probe=8f27aff70b) | Oct 27, 2021 |
| Gigabyte      | GA-970A-UD3                 | [aae0c56d3a](https://linux-hardware.org/?probe=aae0c56d3a) | Oct 27, 2021 |
| MSI           | H61M-P31                    | [e5bf692305](https://linux-hardware.org/?probe=e5bf692305) | Oct 26, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [16a6718949](https://linux-hardware.org/?probe=16a6718949) | Oct 26, 2021 |
| MSI           | Z270 PC MATE                | [24329438d1](https://linux-hardware.org/?probe=24329438d1) | Oct 26, 2021 |
| Unknown       | Unknown                     | [668f61352d](https://linux-hardware.org/?probe=668f61352d) | Oct 26, 2021 |
| ASRock        | Z590M-ITX/ax                | [1fcc4e6895](https://linux-hardware.org/?probe=1fcc4e6895) | Oct 26, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [f5ede0a97c](https://linux-hardware.org/?probe=f5ede0a97c) | Oct 25, 2021 |
| ASUSTek       | PRIME B350M-A               | [19eba77c24](https://linux-hardware.org/?probe=19eba77c24) | Oct 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [97620628a8](https://linux-hardware.org/?probe=97620628a8) | Oct 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [f15c4d9b54](https://linux-hardware.org/?probe=f15c4d9b54) | Oct 25, 2021 |
| Gigabyte      | P67A-UD3                    | [ecaeb257a3](https://linux-hardware.org/?probe=ecaeb257a3) | Oct 24, 2021 |
| Dell          | 0V8F20 A01                  | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| Dell          | 0J3C2F A01                  | [e8cf16b696](https://linux-hardware.org/?probe=e8cf16b696) | Oct 24, 2021 |
| AMI           | Cherry Trail CR             | [9333e233d6](https://linux-hardware.org/?probe=9333e233d6) | Oct 24, 2021 |
| AMI           | Cherry Trail CR             | [7d78a3c31f](https://linux-hardware.org/?probe=7d78a3c31f) | Oct 24, 2021 |
| ASUSTek       | H110M-C                     | [ba3ddf870d](https://linux-hardware.org/?probe=ba3ddf870d) | Oct 24, 2021 |
| ASUSTek       | PRIME Z390-P                | [681b537e82](https://linux-hardware.org/?probe=681b537e82) | Oct 23, 2021 |
| Lenovo        | NO DPK                      | [9c71a67df3](https://linux-hardware.org/?probe=9c71a67df3) | Oct 23, 2021 |
| Acer          | Aspire TC-281               | [5114976821](https://linux-hardware.org/?probe=5114976821) | Oct 23, 2021 |
| ASRock        | N3150DC-ITX                 | [6e3084cf7f](https://linux-hardware.org/?probe=6e3084cf7f) | Oct 23, 2021 |
| ASRock        | N3150DC-ITX                 | [c1808f5d2f](https://linux-hardware.org/?probe=c1808f5d2f) | Oct 23, 2021 |
| Dell          | 0T10XW A00                  | [971b85f5db](https://linux-hardware.org/?probe=971b85f5db) | Oct 23, 2021 |
| ASUSTek       | PRIME X470-PRO              | [48db1afdd3](https://linux-hardware.org/?probe=48db1afdd3) | Oct 23, 2021 |
| Supermicro    | X7DVL                       | [bcbe094156](https://linux-hardware.org/?probe=bcbe094156) | Oct 23, 2021 |
| Dell          | 051FJ8 A02                  | [d04dae2a56](https://linux-hardware.org/?probe=d04dae2a56) | Oct 23, 2021 |
| MSI           | MEG X570 UNIFY              | [7b9e7ec5f4](https://linux-hardware.org/?probe=7b9e7ec5f4) | Oct 23, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [e071387ed6](https://linux-hardware.org/?probe=e071387ed6) | Oct 22, 2021 |
| Lenovo        | NO DPK                      | [ad7c805198](https://linux-hardware.org/?probe=ad7c805198) | Oct 22, 2021 |
| Dell          | 0J3C2F A01                  | [a5ca7f2501](https://linux-hardware.org/?probe=a5ca7f2501) | Oct 22, 2021 |
| Gigabyte      | B550 AORUS PRO              | [f5c3648170](https://linux-hardware.org/?probe=f5c3648170) | Oct 22, 2021 |
| Gigabyte      | B75M-D3H                    | [74c2c9d725](https://linux-hardware.org/?probe=74c2c9d725) | Oct 22, 2021 |
| Dell          | 0N826N A03                  | [5fea6b8b9a](https://linux-hardware.org/?probe=5fea6b8b9a) | Oct 22, 2021 |
| Dell          | 0N826N A03                  | [eb508ab31e](https://linux-hardware.org/?probe=eb508ab31e) | Oct 22, 2021 |
| ICP / iEi     | SA58 V1.01                  | [bca4498e5d](https://linux-hardware.org/?probe=bca4498e5d) | Oct 21, 2021 |
| Dell          | 0200DY A01                  | [c67a8bb677](https://linux-hardware.org/?probe=c67a8bb677) | Oct 21, 2021 |
| Gigabyte      | B450M S2H                   | [71c19b42fc](https://linux-hardware.org/?probe=71c19b42fc) | Oct 21, 2021 |
| Google        | Guado                       | [5aba3d29f4](https://linux-hardware.org/?probe=5aba3d29f4) | Oct 21, 2021 |
| Google        | Guado                       | [2393c52b33](https://linux-hardware.org/?probe=2393c52b33) | Oct 21, 2021 |
| MSI           | B450M PRO-VDH MAX           | [b914028ca9](https://linux-hardware.org/?probe=b914028ca9) | Oct 20, 2021 |
| ASRock        | TRX40 Creator               | [8789f3f1e1](https://linux-hardware.org/?probe=8789f3f1e1) | Oct 20, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [1d5227420f](https://linux-hardware.org/?probe=1d5227420f) | Oct 20, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [b961168b44](https://linux-hardware.org/?probe=b961168b44) | Oct 20, 2021 |
| ASUSTek       | Q87M-E                      | [a549c95cbd](https://linux-hardware.org/?probe=a549c95cbd) | Oct 20, 2021 |
| MSI           | 2A9C                        | [a47442aa1f](https://linux-hardware.org/?probe=a47442aa1f) | Oct 19, 2021 |
| Gigabyte      | H61M-S1                     | [9978664bd7](https://linux-hardware.org/?probe=9978664bd7) | Oct 19, 2021 |
| Gigabyte      | H61M-S1                     | [b0fb0061f2](https://linux-hardware.org/?probe=b0fb0061f2) | Oct 19, 2021 |
| ASUSTek       | P7P55 LX                    | [d2e3eb969f](https://linux-hardware.org/?probe=d2e3eb969f) | Oct 18, 2021 |
| ASRock        | B450 Gaming K4              | [92647c0170](https://linux-hardware.org/?probe=92647c0170) | Oct 18, 2021 |
| ASRock        | B450 Gaming K4              | [c7372168fd](https://linux-hardware.org/?probe=c7372168fd) | Oct 18, 2021 |
| ASRock        | Z87 Extreme4                | [2ec87a3f6f](https://linux-hardware.org/?probe=2ec87a3f6f) | Oct 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [20ca9b4679](https://linux-hardware.org/?probe=20ca9b4679) | Oct 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7e6f5e6e9f](https://linux-hardware.org/?probe=7e6f5e6e9f) | Oct 18, 2021 |
| Acer          | Aspire XC600 v1.0           | [56dd661396](https://linux-hardware.org/?probe=56dd661396) | Oct 18, 2021 |
| Gigabyte      | GA-MA785GM-US2H             | [6522d9dc18](https://linux-hardware.org/?probe=6522d9dc18) | Oct 18, 2021 |
| HP            | 1998                        | [3228ce7734](https://linux-hardware.org/?probe=3228ce7734) | Oct 18, 2021 |
| EPSON DIRE... | ST170E                      | [dfa0ed56ab](https://linux-hardware.org/?probe=dfa0ed56ab) | Oct 18, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [fcc82222d9](https://linux-hardware.org/?probe=fcc82222d9) | Oct 17, 2021 |
| MSI           | Z77A-G45                    | [3d516c23c5](https://linux-hardware.org/?probe=3d516c23c5) | Oct 17, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [7313df4bd9](https://linux-hardware.org/?probe=7313df4bd9) | Oct 17, 2021 |
| Gigabyte      | Z77-D3H                     | [f7ffa54af0](https://linux-hardware.org/?probe=f7ffa54af0) | Oct 17, 2021 |
| Gigabyte      | M68MT-S2P                   | [d10202fe29](https://linux-hardware.org/?probe=d10202fe29) | Oct 17, 2021 |
| ASRock        | B560M-HDV                   | [200bfff8ba](https://linux-hardware.org/?probe=200bfff8ba) | Oct 17, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [122a03804e](https://linux-hardware.org/?probe=122a03804e) | Oct 17, 2021 |
| Intel         | DG31PR AAE39516-304         | [b6addf8d7b](https://linux-hardware.org/?probe=b6addf8d7b) | Oct 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [dd6513e107](https://linux-hardware.org/?probe=dd6513e107) | Oct 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [35b768567f](https://linux-hardware.org/?probe=35b768567f) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [8c1989ae75](https://linux-hardware.org/?probe=8c1989ae75) | Oct 16, 2021 |
| HP            | 870C                        | [8b056a8a9f](https://linux-hardware.org/?probe=8b056a8a9f) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [8b50d81590](https://linux-hardware.org/?probe=8b50d81590) | Oct 16, 2021 |
| Dell          | 0G214D A00                  | [69857eb3a8](https://linux-hardware.org/?probe=69857eb3a8) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7f15c21293](https://linux-hardware.org/?probe=7f15c21293) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [6c2357c3a8](https://linux-hardware.org/?probe=6c2357c3a8) | Oct 16, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [6e15fcad52](https://linux-hardware.org/?probe=6e15fcad52) | Oct 15, 2021 |
| Pegatron      | Eureka3                     | [6499d1cf77](https://linux-hardware.org/?probe=6499d1cf77) | Oct 15, 2021 |
| Pegatron      | Eureka3                     | [a456734f94](https://linux-hardware.org/?probe=a456734f94) | Oct 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [e646d30e4f](https://linux-hardware.org/?probe=e646d30e4f) | Oct 15, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [152b670fcb](https://linux-hardware.org/?probe=152b670fcb) | Oct 15, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [22b047f0a1](https://linux-hardware.org/?probe=22b047f0a1) | Oct 15, 2021 |
| ASRock        | 990FX Extreme3              | [5de7270820](https://linux-hardware.org/?probe=5de7270820) | Oct 11, 2021 |
| ASRock        | 990FX Extreme3              | [b4eb4dbe24](https://linux-hardware.org/?probe=b4eb4dbe24) | Oct 11, 2021 |
| Dell          | 0Y2MRG A00                  | [d60ca7a452](https://linux-hardware.org/?probe=d60ca7a452) | Oct 09, 2021 |
| HP            | 3647h                       | [729a9e9683](https://linux-hardware.org/?probe=729a9e9683) | Oct 05, 2021 |
| ASRock        | X370 Killer SLI/ac          | [52d4dd8f39](https://linux-hardware.org/?probe=52d4dd8f39) | Oct 02, 2021 |
| Dell          | 0RY007                      | [4e574a8988](https://linux-hardware.org/?probe=4e574a8988) | Oct 02, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [db26b44773](https://linux-hardware.org/?probe=db26b44773) | Oct 02, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [3be52ed98f](https://linux-hardware.org/?probe=3be52ed98f) | Oct 02, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [b6f82cf92b](https://linux-hardware.org/?probe=b6f82cf92b) | Sep 30, 2021 |
| Intel         | DG41WV AAE90316-103         | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| ASUSTek       | A68HM-PLUS                  | [8ea8e6afe8](https://linux-hardware.org/?probe=8ea8e6afe8) | Sep 30, 2021 |
| ASRock        | 990FX Extreme4              | [9c631b51b1](https://linux-hardware.org/?probe=9c631b51b1) | Sep 28, 2021 |
| Gigabyte      | H81M-D2V                    | [e8749db36a](https://linux-hardware.org/?probe=e8749db36a) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [aa1a6086e7](https://linux-hardware.org/?probe=aa1a6086e7) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | [b05cdb0bab](https://linux-hardware.org/?probe=b05cdb0bab) | Sep 26, 2021 |
| ASRock        | X399M Taichi                | [eba541c6b9](https://linux-hardware.org/?probe=eba541c6b9) | Sep 25, 2021 |
| Gigabyte      | H81M-S                      | [357f7466e6](https://linux-hardware.org/?probe=357f7466e6) | Sep 25, 2021 |
| ASRock        | Z390M Pro4                  | [138ae00012](https://linux-hardware.org/?probe=138ae00012) | Sep 23, 2021 |
| Medion        | B360H4-EM V1.0              | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Gigabyte      | B85M-D3H                    | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| HP            | 3032h                       | [3fad749d1a](https://linux-hardware.org/?probe=3fad749d1a) | Sep 12, 2021 |
| Huanan        | X99 F8D V2.2                | [c080ec772f](https://linux-hardware.org/?probe=c080ec772f) | Sep 03, 2021 |
| Huanan        | X99 F8D V2.2                | [30fe8d6bb3](https://linux-hardware.org/?probe=30fe8d6bb3) | Aug 26, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1a371ea24e](https://linux-hardware.org/?probe=1a371ea24e) | Aug 16, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| MSI           | MAG B550M MORTAR            | [912b2a77a2](https://linux-hardware.org/?probe=912b2a77a2) | Aug 05, 2021 |
| Huanan        | X99 F8D V2.2                | [74e4c61bbf](https://linux-hardware.org/?probe=74e4c61bbf) | Jul 23, 2021 |
| Huanan        | X99 F8D V2.2                | [02ad72fb54](https://linux-hardware.org/?probe=02ad72fb54) | Jul 21, 2021 |
| Gigabyte      | F2A55M-HD2                  | [6a69f09403](https://linux-hardware.org/?probe=6a69f09403) | Jul 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.13.0-21-generic           | 79       | 32.24%  |
| 5.13.0-20-generic           | 70       | 28.57%  |
| 5.13.0-19-generic           | 51       | 20.82%  |
| 5.13.0-22-generic           | 12       | 4.9%    |
| 5.13.0-16-generic           | 12       | 4.9%    |
| 5.15.2-051502-generic       | 4        | 1.63%   |
| 5.13.0-14-generic           | 3        | 1.22%   |
| 5.14.0-051400rc7-lowlatency | 2        | 0.82%   |
| 5.13.0-17-generic           | 2        | 0.82%   |
| 5.13.0-12-generic           | 2        | 0.82%   |
| 5.8.0-50-generic            | 1        | 0.41%   |
| 5.15.0                      | 1        | 0.41%   |
| 5.14.15                     | 1        | 0.41%   |
| 5.14.14-xanmod2             | 1        | 0.41%   |
| 5.14.14-051414-generic      | 1        | 0.41%   |
| 5.13.0-051300-generic       | 1        | 0.41%   |
| 5.11.0-25-generic           | 1        | 0.41%   |
| 5.11.0-20-generic           | 1        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 229      | 94.63%  |
| 5.15.2  | 4        | 1.65%   |
| 5.14.14 | 2        | 0.83%   |
| 5.14.0  | 2        | 0.83%   |
| 5.11.0  | 2        | 0.83%   |
| 5.8.0   | 1        | 0.41%   |
| 5.15.0  | 1        | 0.41%   |
| 5.14.15 | 1        | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 229      | 94.63%  |
| 5.15    | 5        | 2.07%   |
| 5.14    | 5        | 2.07%   |
| 5.11    | 2        | 0.83%   |
| 5.8     | 1        | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 240      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 216      | 89.63%  |
| Unknown         | 13       | 5.39%   |
| X-Cinnamon      | 5        | 2.07%   |
| GNOME Flashback | 3        | 1.24%   |
| i3              | 2        | 0.83%   |
| Unity           | 1        | 0.41%   |
| sway            | 1        | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 131      | 54.13%  |
| X11     | 100      | 41.32%  |
| Unknown | 6        | 2.48%   |
| Tty     | 5        | 2.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 166      | 69.17%  |
| GDM     | 46       | 19.17%  |
| Unknown | 22       | 9.17%   |
| LightDM | 5        | 2.08%   |
| SDDM    | 1        | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 88       | 36.67%  |
| de_DE | 39       | 16.25%  |
| fr_FR | 13       | 5.42%   |
| it_IT | 11       | 4.58%   |
| en_AU | 10       | 4.17%   |
| en_CA | 9        | 3.75%   |
| pl_PL | 8        | 3.33%   |
| en_GB | 8        | 3.33%   |
| ru_RU | 6        | 2.5%    |
| pt_BR | 6        | 2.5%    |
| nl_NL | 4        | 1.67%   |
| es_ES | 4        | 1.67%   |
| es_AR | 3        | 1.25%   |
| en_IN | 3        | 1.25%   |
| zh_CN | 2        | 0.83%   |
| nb_NO | 2        | 0.83%   |
| ja_JP | 2        | 0.83%   |
| et_EE | 2        | 0.83%   |
| es_PE | 2        | 0.83%   |
| es_MX | 2        | 0.83%   |
| de_CH | 2        | 0.83%   |
| tr_TR | 1        | 0.42%   |
| sv_SE | 1        | 0.42%   |
| sk_SK | 1        | 0.42%   |
| ru_UA | 1        | 0.42%   |
| ko_KR | 1        | 0.42%   |
| hu_HU | 1        | 0.42%   |
| fr_BE | 1        | 0.42%   |
| es_BO | 1        | 0.42%   |
| en_PH | 1        | 0.42%   |
| el_GR | 1        | 0.42%   |
| da_DK | 1        | 0.42%   |
| cs_CZ | 1        | 0.42%   |
| C     | 1        | 0.42%   |
| ar_EG | 1        | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 185      | 77.08%  |
| EFI  | 55       | 22.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 216      | 90%     |
| Overlay | 12       | 5%      |
| Zfs     | 6        | 2.5%    |
| Btrfs   | 4        | 1.67%   |
| Ext3    | 1        | 0.42%   |
| Ext2    | 1        | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 192      | 80%     |
| GPT     | 45       | 18.75%  |
| MBR     | 3        | 1.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 186      | 77.5%   |
| Yes       | 54       | 22.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 54.58%  |
| Yes       | 109      | 45.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 50       | 20.83%  |
| Gigabyte Technology | 43       | 17.92%  |
| MSI                 | 40       | 16.67%  |
| Dell                | 23       | 9.58%   |
| ASRock              | 22       | 9.17%   |
| Hewlett-Packard     | 19       | 7.92%   |
| Lenovo              | 12       | 5%      |
| Acer                | 6        | 2.5%    |
| Pegatron            | 3        | 1.25%   |
| Fujitsu             | 3        | 1.25%   |
| Intel               | 2        | 0.83%   |
| Huanan              | 2        | 0.83%   |
| Foxconn             | 2        | 0.83%   |
| EVGA                | 2        | 0.83%   |
| Supermicro          | 1        | 0.42%   |
| OEM                 | 1        | 0.42%   |
| Medion              | 1        | 0.42%   |
| JGINYUE             | 1        | 0.42%   |
| ICP / iEi           | 1        | 0.42%   |
| Google              | 1        | 0.42%   |
| EPSON DIRECT        | 1        | 0.42%   |
| ECS                 | 1        | 0.42%   |
| Apple               | 1        | 0.42%   |
| AMI                 | 1        | 0.42%   |
| Unknown             | 1        | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 4        | 1.67%   |
| MSI MS-7D25                          | 3        | 1.25%   |
| Dell OptiPlex 7010                   | 3        | 1.25%   |
| ASUS TUF GAMING X570-PLUS            | 3        | 1.25%   |
| MSI MS-7C94                          | 2        | 0.83%   |
| MSI MS-7C80                          | 2        | 0.83%   |
| MSI MS-7C35                          | 2        | 0.83%   |
| MSI MS-7A38                          | 2        | 0.83%   |
| HP Z800 Workstation                  | 2        | 0.83%   |
| HP EliteDesk 800 G1 SFF              | 2        | 0.83%   |
| HP Compaq 8200 Elite CMT PC          | 2        | 0.83%   |
| Gigabyte X570 AORUS MASTER           | 2        | 0.83%   |
| Dell OptiPlex 780                    | 2        | 0.83%   |
| Dell Inspiron 545                    | 2        | 0.83%   |
| ASUS H110M-C                         | 2        | 0.83%   |
| ASUS CROSSHAIR VI HERO               | 2        | 0.83%   |
| ASRock Z590M-ITX/ax                  | 2        | 0.83%   |
| Supermicro X7DVL                     | 1        | 0.42%   |
| Pegatron VC903AA-ABF p6145fr         | 1        | 0.42%   |
| Pegatron p6730de                     | 1        | 0.42%   |
| Pegatron HPE-590t                    | 1        | 0.42%   |
| OEM TOP77D                           | 1        | 0.42%   |
| MSI Pro 3000/3080                    | 1        | 0.42%   |
| MSI PPPPP-CCC#MMMMMMMM               | 1        | 0.42%   |
| MSI MS-7D16                          | 1        | 0.42%   |
| MSI MS-7D13                          | 1        | 0.42%   |
| MSI MS-7D06                          | 1        | 0.42%   |
| MSI MS-7C88                          | 1        | 0.42%   |
| MSI MS-7C79                          | 1        | 0.42%   |
| MSI MS-7C56                          | 1        | 0.42%   |
| MSI MS-7C52                          | 1        | 0.42%   |
| MSI MS-7C37                          | 1        | 0.42%   |
| MSI MS-7C02                          | 1        | 0.42%   |
| MSI MS-7B89                          | 1        | 0.42%   |
| MSI MS-7B54                          | 1        | 0.42%   |
| MSI MS-7B51                          | 1        | 0.42%   |
| MSI MS-7B09                          | 1        | 0.42%   |
| MSI MS-7A75                          | 1        | 0.42%   |
| MSI MS-7A72                          | 1        | 0.42%   |
| MSI MS-7A62                          | 1        | 0.42%   |
| MSI MS-7998                          | 1        | 0.42%   |
| MSI MS-7982                          | 1        | 0.42%   |
| MSI MS-7971                          | 1        | 0.42%   |
| MSI MS-7821                          | 1        | 0.42%   |
| MSI MS-7798                          | 1        | 0.42%   |
| MSI MS-7793                          | 1        | 0.42%   |
| MSI MS-7788                          | 1        | 0.42%   |
| MSI MS-7752                          | 1        | 0.42%   |
| MSI MS-7696                          | 1        | 0.42%   |
| MSI MS-7346                          | 1        | 0.42%   |
| MSI MS-7250                          | 1        | 0.42%   |
| Medion X87085                        | 1        | 0.42%   |
| Lenovo ThinkStation P520c 30BXCTO1WW | 1        | 0.42%   |
| Lenovo ThinkCentre M93p 10AAS2V200   | 1        | 0.42%   |
| Lenovo ThinkCentre M93p 10A8S3C100   | 1        | 0.42%   |
| Lenovo ThinkCentre M93p 10A7000HAU   | 1        | 0.42%   |
| Lenovo ThinkCentre M92p 2988E2U      | 1        | 0.42%   |
| Lenovo ThinkCentre M78 10BR0005US    | 1        | 0.42%   |
| Lenovo ThinkCentre M72e 3664AD7      | 1        | 0.42%   |
| Lenovo ThinkCentre M70e 0833A29      | 1        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 14       | 5.83%   |
| Dell OptiPlex          | 12       | 5%      |
| Lenovo ThinkCentre     | 8        | 3.33%   |
| HP Compaq              | 8        | 3.33%   |
| Dell Inspiron          | 5        | 2.08%   |
| ASUS ROG               | 5        | 2.08%   |
| HP EliteDesk           | 4        | 1.67%   |
| Gigabyte X570          | 4        | 1.67%   |
| ASUS All               | 4        | 1.67%   |
| Acer Aspire            | 4        | 1.67%   |
| MSI MS-7D25            | 3        | 1.25%   |
| ASUS TUF               | 3        | 1.25%   |
| MSI MS-7C94            | 2        | 0.83%   |
| MSI MS-7C80            | 2        | 0.83%   |
| MSI MS-7C35            | 2        | 0.83%   |
| MSI MS-7A38            | 2        | 0.83%   |
| HP Z800                | 2        | 0.83%   |
| Gigabyte X470          | 2        | 0.83%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.83%   |
| Gigabyte B550          | 2        | 0.83%   |
| Gigabyte B450M         | 2        | 0.83%   |
| Dell XPS               | 2        | 0.83%   |
| Dell Precision         | 2        | 0.83%   |
| ASUS H110M-C           | 2        | 0.83%   |
| ASUS CROSSHAIR         | 2        | 0.83%   |
| ASRock Z590M-ITX       | 2        | 0.83%   |
| ASRock 990FX           | 2        | 0.83%   |
| Supermicro X7DVL       | 1        | 0.42%   |
| Pegatron VC903AA-ABF   | 1        | 0.42%   |
| Pegatron p6730de       | 1        | 0.42%   |
| Pegatron HPE-590t      | 1        | 0.42%   |
| OEM TOP77D             | 1        | 0.42%   |
| MSI Pro                | 1        | 0.42%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.42%   |
| MSI MS-7D16            | 1        | 0.42%   |
| MSI MS-7D13            | 1        | 0.42%   |
| MSI MS-7D06            | 1        | 0.42%   |
| MSI MS-7C88            | 1        | 0.42%   |
| MSI MS-7C79            | 1        | 0.42%   |
| MSI MS-7C56            | 1        | 0.42%   |
| MSI MS-7C52            | 1        | 0.42%   |
| MSI MS-7C37            | 1        | 0.42%   |
| MSI MS-7C02            | 1        | 0.42%   |
| MSI MS-7B89            | 1        | 0.42%   |
| MSI MS-7B54            | 1        | 0.42%   |
| MSI MS-7B51            | 1        | 0.42%   |
| MSI MS-7B09            | 1        | 0.42%   |
| MSI MS-7A75            | 1        | 0.42%   |
| MSI MS-7A72            | 1        | 0.42%   |
| MSI MS-7A62            | 1        | 0.42%   |
| MSI MS-7998            | 1        | 0.42%   |
| MSI MS-7982            | 1        | 0.42%   |
| MSI MS-7971            | 1        | 0.42%   |
| MSI MS-7821            | 1        | 0.42%   |
| MSI MS-7798            | 1        | 0.42%   |
| MSI MS-7793            | 1        | 0.42%   |
| MSI MS-7788            | 1        | 0.42%   |
| MSI MS-7752            | 1        | 0.42%   |
| MSI MS-7696            | 1        | 0.42%   |
| MSI MS-7346            | 1        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 52       | 21.67%  |
| 2020 | 29       | 12.08%  |
| 2019 | 22       | 9.17%   |
| 2018 | 17       | 7.08%   |
| 2010 | 16       | 6.67%   |
| 2015 | 15       | 6.25%   |
| 2014 | 15       | 6.25%   |
| 2013 | 14       | 5.83%   |
| 2011 | 12       | 5%      |
| 2009 | 12       | 5%      |
| 2012 | 11       | 4.58%   |
| 2016 | 9        | 3.75%   |
| 2008 | 9        | 3.75%   |
| 2017 | 4        | 1.67%   |
| 2007 | 2        | 0.83%   |
| 2006 | 1        | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 240      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 235      | 97.92%  |
| Enabled  | 5        | 2.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 238      | 99.17%  |
| Yes  | 2        | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 55       | 22.82%  |
| 32.01-64.0  | 49       | 20.33%  |
| 4.01-8.0    | 43       | 17.84%  |
| 8.01-16.0   | 43       | 17.84%  |
| 3.01-4.0    | 25       | 10.37%  |
| 64.01-256.0 | 16       | 6.64%   |
| 24.01-32.0  | 7        | 2.9%    |
| 1.01-2.0    | 3        | 1.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 100      | 40.82%  |
| 2.01-3.0   | 67       | 27.35%  |
| 4.01-8.0   | 36       | 14.69%  |
| 3.01-4.0   | 30       | 12.24%  |
| 8.01-16.0  | 8        | 3.27%   |
| 0.51-1.0   | 3        | 1.22%   |
| 16.01-24.0 | 1        | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 36.1%   |
| 2      | 73       | 30.29%  |
| 3      | 30       | 12.45%  |
| 4      | 21       | 8.71%   |
| 5      | 17       | 7.05%   |
| 6      | 6        | 2.49%   |
| 7      | 3        | 1.24%   |
| 11     | 2        | 0.83%   |
| 8      | 1        | 0.41%   |
| 0      | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 52.08%  |
| Yes       | 115      | 47.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 238      | 99.17%  |
| No        | 2        | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 127      | 52.92%  |
| Yes       | 113      | 47.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 152      | 63.07%  |
| Yes       | 89       | 36.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 53       | 22.08%  |
| Germany      | 42       | 17.5%   |
| France       | 15       | 6.25%   |
| Italy        | 13       | 5.42%   |
| Poland       | 11       | 4.58%   |
| Canada       | 10       | 4.17%   |
| Australia    | 10       | 4.17%   |
| Brazil       | 8        | 3.33%   |
| UK           | 7        | 2.92%   |
| Russia       | 6        | 2.5%    |
| Switzerland  | 5        | 2.08%   |
| Mexico       | 5        | 2.08%   |
| Netherlands  | 4        | 1.67%   |
| Spain        | 3        | 1.25%   |
| Norway       | 3        | 1.25%   |
| Lithuania    | 3        | 1.25%   |
| India        | 3        | 1.25%   |
| Argentina    | 3        | 1.25%   |
| Ukraine      | 2        | 0.83%   |
| Sweden       | 2        | 0.83%   |
| South Korea  | 2        | 0.83%   |
| Peru         | 2        | 0.83%   |
| Japan        | 2        | 0.83%   |
| Greece       | 2        | 0.83%   |
| Estonia      | 2        | 0.83%   |
| Denmark      | 2        | 0.83%   |
| China        | 2        | 0.83%   |
| Belgium      | 2        | 0.83%   |
| Turkey       | 1        | 0.42%   |
| South Africa | 1        | 0.42%   |
| Serbia       | 1        | 0.42%   |
| Saudi Arabia | 1        | 0.42%   |
| Portugal     | 1        | 0.42%   |
| Philippines  | 1        | 0.42%   |
| New Zealand  | 1        | 0.42%   |
| Malaysia     | 1        | 0.42%   |
| Israel       | 1        | 0.42%   |
| Iran         | 1        | 0.42%   |
| Hungary      | 1        | 0.42%   |
| Finland      | 1        | 0.42%   |
| Egypt        | 1        | 0.42%   |
| Czechia      | 1        | 0.42%   |
| Chile        | 1        | 0.42%   |
| Bolivia      | 1        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Cleveland    | 6        | 2.5%    |
| Warsaw       | 3        | 1.25%   |
| Sydney       | 3        | 1.25%   |
| Berlin       | 3        | 1.25%   |
| Wroclaw      | 2        | 0.83%   |
| Wittlich     | 2        | 0.83%   |
| Washington   | 2        | 0.83%   |
| Vilnius      | 2        | 0.83%   |
| Tijuana      | 2        | 0.83%   |
| Poznan       | 2        | 0.83%   |
| Perth        | 2        | 0.83%   |
| Oslo         | 2        | 0.83%   |
| Oakland      | 2        | 0.83%   |
| Munich       | 2        | 0.83%   |
| Milan        | 2        | 0.83%   |
| Madrid       | 2        | 0.83%   |
| Lima         | 2        | 0.83%   |
| Houston      | 2        | 0.83%   |
| El Paso      | 2        | 0.83%   |
| Cannes       | 2        | 0.83%   |
| Brussels     | 2        | 0.83%   |
| Bodenheim    | 2        | 0.83%   |
| Birmingham   | 2        | 0.83%   |
| Athens       | 2        | 0.83%   |
| Zevenaar     | 1        | 0.42%   |
| Yakima       | 1        | 0.42%   |
| Wynau        | 1        | 0.42%   |
| Wuhan        | 1        | 0.42%   |
| Winnipeg     | 1        | 0.42%   |
| Wildeshausen | 1        | 0.42%   |
| Wiesbaden    | 1        | 0.42%   |
| Waterloo     | 1        | 0.42%   |
| Walthamstow  | 1        | 0.42%   |
| Wadern       | 1        | 0.42%   |
| Volgograd    | 1        | 0.42%   |
| Vladivostok  | 1        | 0.42%   |
| Vancouver    | 1        | 0.42%   |
| Utrera       | 1        | 0.42%   |
| Tulsa        | 1        | 0.42%   |
| Tucson       | 1        | 0.42%   |
| Trondheim    | 1        | 0.42%   |
| Trivandrum   | 1        | 0.42%   |
| Trapani      | 1        | 0.42%   |
| Trakai       | 1        | 0.42%   |
| Toronto      | 1        | 0.42%   |
| Telford      | 1        | 0.42%   |
| Tehran       | 1        | 0.42%   |
| Tartu        | 1        | 0.42%   |
| Tampere      | 1        | 0.42%   |
| Tallinn      | 1        | 0.42%   |
| Sumter       | 1        | 0.42%   |
| Stuttgart    | 1        | 0.42%   |
| Stittsville  | 1        | 0.42%   |
| Staufen      | 1        | 0.42%   |
| Stassfurt    | 1        | 0.42%   |
| Springfield  | 1        | 0.42%   |
| Southlake    | 1        | 0.42%   |
| Sonsbeck     | 1        | 0.42%   |
| Sollentuna   | 1        | 0.42%   |
| Solingen     | 1        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 80       | 119    | 18.35%  |
| Samsung Electronics       | 79       | 117    | 18.12%  |
| WDC                       | 75       | 110    | 17.2%   |
| Crucial                   | 27       | 29     | 6.19%   |
| Kingston                  | 26       | 34     | 5.96%   |
| Toshiba                   | 21       | 25     | 4.82%   |
| Hitachi                   | 19       | 22     | 4.36%   |
| SanDisk                   | 15       | 16     | 3.44%   |
| A-DATA Technology         | 9        | 10     | 2.06%   |
| Silicon Motion            | 8        | 10     | 1.83%   |
| Phison                    | 7        | 8      | 1.61%   |
| Intel                     | 7        | 8      | 1.61%   |
| HGST                      | 6        | 7      | 1.38%   |
| PNY                       | 5        | 7      | 1.15%   |
| Unknown                   | 4        | 6      | 0.92%   |
| Micron/Crucial Technology | 4        | 4      | 0.92%   |
| Intenso                   | 3        | 3      | 0.69%   |
| SABRENT                   | 2        | 2      | 0.46%   |
| Realtek Semiconductor     | 2        | 2      | 0.46%   |
| PLEXTOR                   | 2        | 2      | 0.46%   |
| Phison Electronics        | 2        | 2      | 0.46%   |
| MAXTOR                    | 2        | 2      | 0.46%   |
| LITEONIT                  | 2        | 2      | 0.46%   |
| LITEON                    | 2        | 2      | 0.46%   |
| LDLC                      | 2        | 2      | 0.46%   |
| KIOXIA-EXCERIA            | 2        | 2      | 0.46%   |
| Hewlett-Packard           | 2        | 2      | 0.46%   |
| GOODRAM                   | 2        | 3      | 0.46%   |
| China                     | 2        | 2      | 0.46%   |
| XPG                       | 1        | 1      | 0.23%   |
| Transcend                 | 1        | 1      | 0.23%   |
| SSSTC                     | 1        | 1      | 0.23%   |
| SPCC                      | 1        | 1      | 0.23%   |
| SK Hynix                  | 1        | 3      | 0.23%   |
| Q200                      | 1        | 2      | 0.23%   |
| Netac                     | 1        | 2      | 0.23%   |
| MARVELL                   | 1        | 1      | 0.23%   |
| KLEVV                     | 1        | 1      | 0.23%   |
| KingDian                  | 1        | 1      | 0.23%   |
| kimtigo                   | 1        | 1      | 0.23%   |
| JMicron                   | 1        | 1      | 0.23%   |
| INTEL SS                  | 1        | 1      | 0.23%   |
| Gigabyte Technology       | 1        | 1      | 0.23%   |
| ASMT                      | 1        | 1      | 0.23%   |
| 2-Power                   | 1        | 1      | 0.23%   |
| Unknown                   | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB        | 8        | 1.55%   |
| Kingston SA400S37240G 240GB SSD        | 8        | 1.55%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 7        | 1.36%   |
| Seagate ST2000DM008-2FR102 2TB         | 6        | 1.17%   |
| Seagate ST1000DM003-1CH162 1TB         | 6        | 1.17%   |
| Samsung SSD 860 EVO 500GB              | 6        | 1.17%   |
| Samsung NVMe SSD Drive 1TB             | 5        | 0.97%   |
| Kingston SA400S37120G 120GB SSD        | 5        | 0.97%   |
| Crucial CT500MX500SSD1 500GB           | 5        | 0.97%   |
| WDC WD10EZEX-08WN4A0 1TB               | 4        | 0.78%   |
| Seagate ST3250318AS 250GB              | 4        | 0.78%   |
| Samsung SSD 970 EVO 500GB              | 4        | 0.78%   |
| Samsung SSD 850 EVO 500GB              | 4        | 0.78%   |
| Kingston SA400S37480G 480GB SSD        | 4        | 0.78%   |
| WDC WD20EZRX-00D8PB0 2TB               | 3        | 0.58%   |
| Toshiba DT01ACA050 500GB               | 3        | 0.58%   |
| Silicon Motion NVMe SSD Drive 512GB    | 3        | 0.58%   |
| Silicon Motion NVMe SSD Drive 256GB    | 3        | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB         | 3        | 0.58%   |
| Seagate ST3160812AS 160GB              | 3        | 0.58%   |
| Seagate ST2000DL003-9VT166 2TB         | 3        | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB         | 3        | 0.58%   |
| Sandisk NVMe SSD Drive 1TB             | 3        | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB           | 3        | 0.58%   |
| Samsung SSD 870 EVO 250GB              | 3        | 0.58%   |
| Samsung SSD 860 EVO 1TB                | 3        | 0.58%   |
| Samsung SSD 850 EVO 250GB              | 3        | 0.58%   |
| Samsung NVMe SSD Drive 512GB           | 3        | 0.58%   |
| Samsung NVMe SSD Drive 500GB           | 3        | 0.58%   |
| Samsung HD501LJ 500GB                  | 3        | 0.58%   |
| Kingston SV300S37A120G 120GB SSD       | 3        | 0.58%   |
| Crucial CT240BX500SSD1 240GB           | 3        | 0.58%   |
| Crucial CT120BX500SSD1 120GB           | 3        | 0.58%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2        | 0.39%   |
| WDC WD80EZAZ-11TDBA0 8TB               | 2        | 0.39%   |
| WDC WD6400AACS-00G8B1 640GB            | 2        | 0.39%   |
| WDC WD5000AAKS-00UU3A0 500GB           | 2        | 0.39%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 2        | 0.39%   |
| WDC WD4003FZEX-00Z4SA0 4TB             | 2        | 0.39%   |
| WDC WD30EZRZ-00Z5HB0 3TB               | 2        | 0.39%   |
| WDC WD2500AAKX-753CA1 250GB            | 2        | 0.39%   |
| WDC WD10EZEX-08M2NA0 1TB               | 2        | 0.39%   |
| WDC WD10EZEX-00WN4A0 1TB               | 2        | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB               | 2        | 0.39%   |
| Unknown SD/MMC/MS PRO 394GB            | 2        | 0.39%   |
| Toshiba HDWD130 3TB                    | 2        | 0.39%   |
| Toshiba DT01ACA200 2TB                 | 2        | 0.39%   |
| Toshiba DT01ACA100 1TB                 | 2        | 0.39%   |
| Seagate ST3500418AS 500GB              | 2        | 0.39%   |
| Seagate ST3500320AS 500GB              | 2        | 0.39%   |
| Seagate ST31000524AS 1TB               | 2        | 0.39%   |
| Seagate ST3000DM007-1WY10G 3TB         | 2        | 0.39%   |
| Seagate ST3000DM001-1ER166 3TB         | 2        | 0.39%   |
| Seagate ST2000DM001-1ER164 2TB         | 2        | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB         | 2        | 0.39%   |
| Seagate ST1000DX001-1CM162 1TB         | 2        | 0.39%   |
| Seagate Expansion 1TB                  | 2        | 0.39%   |
| SanDisk Ultra II 480GB SSD             | 2        | 0.39%   |
| Sandisk NVMe SSD Drive 500GB           | 2        | 0.39%   |
| Samsung SSD 980 PRO 1TB                | 2        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 80       | 117    | 36.7%   |
| WDC                 | 70       | 103    | 32.11%  |
| Hitachi             | 19       | 22     | 8.72%   |
| Toshiba             | 18       | 22     | 8.26%   |
| Samsung Electronics | 17       | 22     | 7.8%    |
| HGST                | 6        | 7      | 2.75%   |
| Unknown             | 2        | 2      | 0.92%   |
| MAXTOR              | 2        | 2      | 0.92%   |
| MARVELL             | 1        | 1      | 0.46%   |
| Hewlett-Packard     | 1        | 1      | 0.46%   |
| ASMT                | 1        | 1      | 0.46%   |
| Unknown             | 1        | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 38       | 48     | 26.39%  |
| Kingston            | 24       | 32     | 16.67%  |
| Crucial             | 23       | 24     | 15.97%  |
| SanDisk             | 10       | 11     | 6.94%   |
| A-DATA Technology   | 7        | 8      | 4.86%   |
| Intel               | 6        | 7      | 4.17%   |
| WDC                 | 5        | 5      | 3.47%   |
| PNY                 | 4        | 5      | 2.78%   |
| Toshiba             | 2        | 2      | 1.39%   |
| PLEXTOR             | 2        | 2      | 1.39%   |
| LITEONIT            | 2        | 2      | 1.39%   |
| LITEON              | 2        | 2      | 1.39%   |
| LDLC                | 2        | 2      | 1.39%   |
| KIOXIA-EXCERIA      | 2        | 2      | 1.39%   |
| Intenso             | 2        | 2      | 1.39%   |
| China               | 2        | 2      | 1.39%   |
| Transcend           | 1        | 1      | 0.69%   |
| SK Hynix            | 1        | 1      | 0.69%   |
| Q200                | 1        | 2      | 0.69%   |
| Netac               | 1        | 2      | 0.69%   |
| KLEVV               | 1        | 1      | 0.69%   |
| KingDian            | 1        | 1      | 0.69%   |
| kimtigo             | 1        | 1      | 0.69%   |
| INTEL SS            | 1        | 1      | 0.69%   |
| Hewlett-Packard     | 1        | 1      | 0.69%   |
| GOODRAM             | 1        | 1      | 0.69%   |
| 2-Power             | 1        | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 161      | 301    | 44.48%  |
| SSD     | 119      | 169    | 32.87%  |
| NVMe    | 75       | 102    | 20.72%  |
| Unknown | 6        | 8      | 1.66%   |
| MMC     | 1        | 1      | 0.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 212      | 457    | 69.28%  |
| NVMe | 75       | 100    | 24.51%  |
| SAS  | 18       | 23     | 5.88%   |
| MMC  | 1        | 1      | 0.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 148      | 249    | 48.37%  |
| 0.51-1.0   | 89       | 121    | 29.08%  |
| 1.01-2.0   | 34       | 42     | 11.11%  |
| 3.01-4.0   | 14       | 25     | 4.58%   |
| 2.01-3.0   | 12       | 16     | 3.92%   |
| 4.01-10.0  | 6        | 14     | 1.96%   |
| 10.01-20.0 | 2        | 2      | 0.65%   |
| 0          | 1        | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 60       | 24.9%   |
| 501-1000       | 49       | 20.33%  |
| 251-500        | 40       | 16.6%   |
| 1001-2000      | 28       | 11.62%  |
| More than 3000 | 19       | 7.88%   |
| 1-20           | 17       | 7.05%   |
| 2001-3000      | 16       | 6.64%   |
| 51-100         | 7        | 2.9%    |
| 21-50          | 4        | 1.66%   |
| Unknown        | 1        | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 78       | 32.23%  |
| 21-50          | 41       | 16.94%  |
| 101-250        | 36       | 14.88%  |
| 51-100         | 26       | 10.74%  |
| 501-1000       | 19       | 7.85%   |
| 251-500        | 17       | 7.02%   |
| More than 3000 | 10       | 4.13%   |
| 1001-2000      | 10       | 4.13%   |
| 2001-3000      | 4        | 1.65%   |
| Unknown        | 1        | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST1000DM003-1CH162 1TB     | 2        | 2      | 22.22%  |
| WDC WD5000AAKX-083CA1 500GB        | 1        | 1      | 11.11%  |
| WDC WD30EZRX-00DC0B0 3TB           | 1        | 1      | 11.11%  |
| WDC WD2500HHTZ-04N21V0 250GB       | 1        | 1      | 11.11%  |
| Toshiba MQ01ABD100 1TB             | 1        | 1      | 11.11%  |
| Seagate ST3500320AS 500GB          | 1        | 1      | 11.11%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 11.11%  |
| MAXTOR 6G160E0 160GB               | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 44.44%  |
| WDC     | 3        | 3      | 33.33%  |
| Toshiba | 1        | 1      | 11.11%  |
| MAXTOR  | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 44.44%  |
| WDC     | 3        | 3      | 33.33%  |
| Toshiba | 1        | 1      | 11.11%  |
| MAXTOR  | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 9      | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 186      | 426    | 74.4%   |
| Works    | 56       | 146    | 22.4%   |
| Malfunc  | 8        | 9      | 3.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 156      | 44.57%  |
| AMD                          | 74       | 21.14%  |
| Samsung Electronics          | 38       | 10.86%  |
| Phison Electronics           | 11       | 3.14%   |
| ASMedia Technology           | 10       | 2.86%   |
| Silicon Motion               | 9        | 2.57%   |
| Micron/Crucial Technology    | 8        | 2.29%   |
| Marvell Technology Group     | 7        | 2%      |
| Nvidia                       | 6        | 1.71%   |
| Sandisk                      | 5        | 1.43%   |
| JMicron Technology           | 5        | 1.43%   |
| LSI Logic / Symbios Logic    | 3        | 0.86%   |
| ADATA Technology             | 3        | 0.86%   |
| Realtek Semiconductor        | 2        | 0.57%   |
| Kingston Technology Company  | 2        | 0.57%   |
| Broadcom / LSI               | 2        | 0.57%   |
| VIA Technologies             | 1        | 0.29%   |
| Toshiba America Info Systems | 1        | 0.29%   |
| SK Hynix                     | 1        | 0.29%   |
| Silicon Image                | 1        | 0.29%   |
| Shenzhen Longsys Electronics | 1        | 0.29%   |
| Lite-On IT Corp. / Plextor   | 1        | 0.29%   |
| Hewlett-Packard              | 1        | 0.29%   |
| Advanced System Products     | 1        | 0.29%   |
| 3ware                        | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 43       | 9.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 24       | 5.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 4.14%   |
| Intel SATA Controller [RAID mode]                                                       | 15       | 3.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 2.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12       | 2.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 2.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 2.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10       | 2.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9        | 2.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.07%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 2.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 2.07%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 8        | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 1.84%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 8        | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 1.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6        | 1.38%   |
| Intel 600 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.15%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.92%   |
| Phison E12 NVMe Controller                                                              | 4        | 0.92%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4        | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.92%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 4        | 0.92%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.92%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.92%   |
| AMD FCH SATA Controller D                                                               | 4        | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 0.92%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.69%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.69%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 0.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.69%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.46%   |
| Sandisk Non-Volatile memory controller                                                  | 2        | 0.46%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.46%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 0.46%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 2        | 0.46%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.46%   |
| Nvidia MCP55 SATA Controller                                                            | 2        | 0.46%   |
| Nvidia MCP55 IDE                                                                        | 2        | 0.46%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.46%   |
| Micron/Crucial Non-Volatile memory controller                                           | 2        | 0.46%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2        | 0.46%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 2        | 0.46%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.46%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 2        | 0.46%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.46%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.46%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.46%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.46%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 0.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.46%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 184      | 52.57%  |
| NVMe | 74       | 21.14%  |
| IDE  | 58       | 16.57%  |
| RAID | 27       | 7.71%   |
| SCSI | 5        | 1.43%   |
| SAS  | 2        | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 159      | 66.25%  |
| AMD    | 81       | 33.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 8        | 3.33%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 2.5%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 5        | 2.08%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 1.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 1.67%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 1.67%   |
| AMD FX-6300 Six-Core Processor              | 4        | 1.67%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 1.25%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 1.25%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 1.25%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.25%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.25%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 1.25%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 1.25%   |
| AMD FX-8320 Eight-Core Processor            | 3        | 1.25%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.83%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 2        | 0.83%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.83%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.83%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.83%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.83%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.83%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 0.83%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.83%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.83%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 2        | 0.83%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 2        | 0.83%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.83%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.83%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 0.83%   |
| Intel 12th Gen Core i5-12600K               | 2        | 0.83%   |
| Intel 11th Gen Core i5-11500 @ 2.70GHz      | 2        | 0.83%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 0.83%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 0.83%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 0.83%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 0.83%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 0.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 0.83%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 0.83%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 0.83%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.83%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 0.83%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 2        | 0.83%   |
| Intel Xeon W-2133 CPU @ 3.60GHz             | 1        | 0.42%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 0.42%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1        | 0.42%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.42%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.42%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 0.42%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz         | 1        | 0.42%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.42%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 0.42%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.42%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 0.42%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.42%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.42%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 41       | 17.08%  |
| Intel Core i5           | 40       | 16.67%  |
| AMD Ryzen 5             | 22       | 9.17%   |
| Intel Core i3           | 15       | 6.25%   |
| AMD Ryzen 7             | 15       | 6.25%   |
| Intel Xeon              | 13       | 5.42%   |
| AMD FX                  | 10       | 4.17%   |
| Other                   | 9        | 3.75%   |
| Intel Core 2 Duo        | 9        | 3.75%   |
| Intel Pentium Dual-Core | 7        | 2.92%   |
| AMD Ryzen 9             | 7        | 2.92%   |
| Intel Core i9           | 6        | 2.5%    |
| Intel Core 2 Quad       | 6        | 2.5%    |
| Intel Celeron           | 5        | 2.08%   |
| AMD Ryzen Threadripper  | 4        | 1.67%   |
| AMD Ryzen 3             | 4        | 1.67%   |
| AMD Athlon 64 X2        | 4        | 1.67%   |
| Intel Pentium           | 3        | 1.25%   |
| AMD A8                  | 3        | 1.25%   |
| Intel Pentium Dual      | 2        | 0.83%   |
| AMD Athlon II X2        | 2        | 0.83%   |
| Intel Pentium D         | 1        | 0.42%   |
| Intel Genuine           | 1        | 0.42%   |
| Intel Atom              | 1        | 0.42%   |
| AMD Phenom II X6        | 1        | 0.42%   |
| AMD Phenom II X4        | 1        | 0.42%   |
| AMD Phenom II X2        | 1        | 0.42%   |
| AMD Phenom              | 1        | 0.42%   |
| AMD Athlon II X4        | 1        | 0.42%   |
| AMD Athlon Dual Core    | 1        | 0.42%   |
| AMD Athlon              | 1        | 0.42%   |
| AMD A6                  | 1        | 0.42%   |
| AMD A4                  | 1        | 0.42%   |
| AMD A10                 | 1        | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 87       | 36.25%  |
| 2      | 53       | 22.08%  |
| 6      | 40       | 16.67%  |
| 8      | 30       | 12.5%   |
| 12     | 9        | 3.75%   |
| 3      | 7        | 2.92%   |
| 10     | 6        | 2.5%    |
| 16     | 4        | 1.67%   |
| 32     | 1        | 0.42%   |
| 28     | 1        | 0.42%   |
| 24     | 1        | 0.42%   |
| 1      | 1        | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 234      | 97.5%   |
| 2      | 6        | 2.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 136      | 56.67%  |
| 1      | 104      | 43.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 240      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 170      | 70.25%  |
| 0x306a9    | 7        | 2.89%   |
| 0x306c3    | 6        | 2.48%   |
| 0x906ea    | 4        | 1.65%   |
| 0x90672    | 4        | 1.65%   |
| 0x206a7    | 4        | 1.65%   |
| 0xa0671    | 3        | 1.24%   |
| 0xa0655    | 3        | 1.24%   |
| 0x906ed    | 3        | 1.24%   |
| 0x906e9    | 3        | 1.24%   |
| 0x0a201016 | 3        | 1.24%   |
| 0x0a201009 | 3        | 1.24%   |
| 0x0800820d | 3        | 1.24%   |
| 0x06000852 | 3        | 1.24%   |
| 0x206d7    | 2        | 0.83%   |
| 0x0a50000c | 2        | 0.83%   |
| 0x08701013 | 2        | 0.83%   |
| 0xf47      | 1        | 0.41%   |
| 0x906ec    | 1        | 0.41%   |
| 0x506e8    | 1        | 0.41%   |
| 0x506e3    | 1        | 0.41%   |
| 0x50654    | 1        | 0.41%   |
| 0x406c3    | 1        | 0.41%   |
| 0x306f2    | 1        | 0.41%   |
| 0x306d4    | 1        | 0.41%   |
| 0x106a5    | 1        | 0.41%   |
| 0x1067a    | 1        | 0.41%   |
| 0x08701021 | 1        | 0.41%   |
| 0x08600103 | 1        | 0.41%   |
| 0x08108109 | 1        | 0.41%   |
| 0x08001138 | 1        | 0.41%   |
| 0x08001137 | 1        | 0.41%   |
| 0x06006118 | 1        | 0.41%   |
| 0x010000db | 1        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 27       | 11.25%  |
| KabyLake         | 26       | 10.83%  |
| Penryn           | 23       | 9.58%   |
| IvyBridge        | 20       | 8.33%   |
| SandyBridge      | 18       | 7.5%    |
| Zen 3            | 17       | 7.08%   |
| Zen 2            | 14       | 5.83%   |
| Piledriver       | 13       | 5.42%   |
| Zen              | 12       | 5%      |
| Zen+             | 10       | 4.17%   |
| CometLake        | 10       | 4.17%   |
| Skylake          | 7        | 2.92%   |
| K10              | 7        | 2.92%   |
| K8 Hammer        | 5        | 2.08%   |
| Core             | 5        | 2.08%   |
| Nehalem          | 4        | 1.67%   |
| Alderlake Hybrid | 4        | 1.67%   |
| Westmere         | 3        | 1.25%   |
| Icelake          | 3        | 1.25%   |
| Broadwell        | 3        | 1.25%   |
| Silvermont       | 2        | 0.83%   |
| Unknown          | 2        | 0.83%   |
| NetBurst         | 1        | 0.42%   |
| K10 Llano        | 1        | 0.42%   |
| Goldmont plus    | 1        | 0.42%   |
| Excavator        | 1        | 0.42%   |
| Bulldozer        | 1        | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 100      | 40.16%  |
| AMD    | 77       | 30.92%  |
| Intel  | 72       | 28.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13       | 5.1%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 11       | 4.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8        | 3.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8        | 3.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 2.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5        | 1.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 1.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 1.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5        | 1.96%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 1.57%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4        | 1.57%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 1.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.57%   |
| Intel HD Graphics 630                                                                    | 4        | 1.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 1.57%   |
| Intel AlderLake-S GT1                                                                    | 4        | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 1.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 1.57%   |
| AMD Cezanne                                                                              | 4        | 1.57%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4        | 1.57%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3        | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 3        | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 1.18%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3        | 1.18%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 3        | 1.18%   |
| AMD Richland [Radeon HD 8570D]                                                           | 3        | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.18%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3        | 1.18%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 3        | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2        | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2        | 0.78%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 0.78%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 0.78%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.78%   |
| Nvidia GF106 [GeForce GT 440]                                                            | 2        | 0.78%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 2        | 0.78%   |
| Intel HD Graphics 530                                                                    | 2        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 0.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.78%   |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 2        | 0.78%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                             | 2        | 0.78%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 0.78%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.39%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.39%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.39%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1        | 0.39%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 0.39%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.39%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.39%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.39%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.39%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.39%   |
| Nvidia NV44 [GeForce 6200 LE]                                                            | 1        | 0.39%   |
| Nvidia NV43 [GeForce 6600 GT]                                                            | 1        | 0.39%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.39%   |
| Nvidia GT200GL [Quadro FX 4800]                                                          | 1        | 0.39%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 1        | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 92       | 38.33%  |
| 1 x AMD        | 71       | 29.58%  |
| 1 x Intel      | 65       | 27.08%  |
| 2 x Nvidia     | 3        | 1.25%   |
| Intel + Nvidia | 3        | 1.25%   |
| Intel + AMD    | 3        | 1.25%   |
| 2 x AMD        | 2        | 0.83%   |
| AMD + Nvidia   | 1        | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 177      | 73.44%  |
| Proprietary | 57       | 23.65%  |
| Unknown     | 7        | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 171      | 70.95%  |
| 1.01-2.0   | 22       | 9.13%   |
| 7.01-8.0   | 11       | 4.56%   |
| 0.51-1.0   | 11       | 4.56%   |
| 3.01-4.0   | 7        | 2.9%    |
| 8.01-16.0  | 6        | 2.49%   |
| 5.01-6.0   | 5        | 2.07%   |
| 2.01-3.0   | 5        | 2.07%   |
| 0.01-0.5   | 3        | 1.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 41       | 15.71%  |
| Dell                 | 33       | 12.64%  |
| Goldstar             | 30       | 11.49%  |
| Acer                 | 15       | 5.75%   |
| Philips              | 14       | 5.36%   |
| Hewlett-Packard      | 14       | 5.36%   |
| BenQ                 | 13       | 4.98%   |
| Ancor Communications | 13       | 4.98%   |
| AOC                  | 11       | 4.21%   |
| ViewSonic            | 7        | 2.68%   |
| Iiyama               | 7        | 2.68%   |
| Sony                 | 6        | 2.3%    |
| Lenovo               | 5        | 1.92%   |
| ASUSTek Computer     | 5        | 1.92%   |
| NEC Computers        | 4        | 1.53%   |
| Vizio                | 3        | 1.15%   |
| MSI                  | 3        | 1.15%   |
| Unknown              | 2        | 0.77%   |
| Sceptre Tech         | 2        | 0.77%   |
| Packard Bell         | 2        | 0.77%   |
| Medion               | 2        | 0.77%   |
| Hyundai ImageQuest   | 2        | 0.77%   |
| HannStar             | 2        | 0.77%   |
| Fujitsu Siemens      | 2        | 0.77%   |
| Compaq Computer      | 2        | 0.77%   |
| VIZ                  | 1        | 0.38%   |
| VIE                  | 1        | 0.38%   |
| Toshiba              | 1        | 0.38%   |
| Sun                  | 1        | 0.38%   |
| SKY                  | 1        | 0.38%   |
| Sanyo                | 1        | 0.38%   |
| SAC                  | 1        | 0.38%   |
| PZG                  | 1        | 0.38%   |
| Panasonic            | 1        | 0.38%   |
| NVISION              | 1        | 0.38%   |
| NUL                  | 1        | 0.38%   |
| MStar                | 1        | 0.38%   |
| LYC                  | 1        | 0.38%   |
| LG Electronics       | 1        | 0.38%   |
| IPS                  | 1        | 0.38%   |
| HannStar Display     | 1        | 0.38%   |
| Grundig              | 1        | 0.38%   |
| CVT                  | 1        | 0.38%   |
| Belinea              | 1        | 0.38%   |
| AUS                  | 1        | 0.38%   |
| Unknown              | 1        | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3        | 1.08%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 509x286mm 23.0-inch           | 3        | 1.08%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 2        | 0.72%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 600x340mm 27.2-inch               | 2        | 0.72%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 2        | 0.72%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.72%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2        | 0.72%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                    | 2        | 0.72%   |
| Compaq Computer Compaq Q1859 CPQ2826 1366x768 410x230mm 18.5-inch     | 2        | 0.72%   |
| BenQ GL2580 BNQ78E5 1920x1080 544x303mm 24.5-inch                     | 2        | 0.72%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 2        | 0.72%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 480x270mm 21.7-inch | 2        | 0.72%   |
| Vizio D55-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                    | 1        | 0.36%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                    | 1        | 0.36%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                   | 1        | 0.36%   |
| VIZ LCD Monitor V405-H9 3840x2160                                     | 1        | 0.36%   |
| ViewSonic XG270QC VSCC438 2560x1440 597x336mm 27.0-inch               | 1        | 0.36%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                | 1        | 0.36%   |
| ViewSonic VP2468 Series VSCB032 1920x1080 527x296mm 23.8-inch         | 1        | 0.36%   |
| ViewSonic VA721 VSC6E19 1280x1024 340x270mm 17.1-inch                 | 1        | 0.36%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1        | 0.36%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                | 1        | 0.36%   |
| ViewSonic PF790-2 VSC4500 1600x1200 353x265mm 17.4-inch               | 1        | 0.36%   |
| VIE A2256 VIEE001 1920x1080 509x286mm 23.0-inch                       | 1        | 0.36%   |
| Unknown LCD Monitor Sanyo Electric Co.,Ltd. SANYO-TV 1360x765         | 1        | 0.36%   |
| Unknown LCD Monitor Maxdata/XXXXXXX BelArtist22W 5520x2160            | 1        | 0.36%   |
| Toshiba TV TSB0108 1920x1080 890x500mm 40.2-inch                      | 1        | 0.36%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                | 1        | 0.36%   |
| Sony TV SNY5501 1024x768 1600x900mm 72.3-inch                         | 1        | 0.36%   |
| Sony TV SNY2801 1920x1080 1600x900mm 72.3-inch                        | 1        | 0.36%   |
| Sony TV *00 SNY8604 3840x2160 1218x685mm 55.0-inch                    | 1        | 0.36%   |
| Sony TV *00 SNY4B04 3840x2160 1600x900mm 72.3-inch                    | 1        | 0.36%   |
| Sony SDM-HS74P SNY3070 1280x1024 338x270mm 17.0-inch                  | 1        | 0.36%   |
| Sony LCD Monitor TV 1360x768                                          | 1        | 0.36%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                  | 1        | 0.36%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch         | 1        | 0.36%   |
| Sceptre Tech E205W-1600 SPT080D 1600x900 477x268mm 21.5-inch          | 1        | 0.36%   |
| Sanyo TV SAN0206 1920x1080 1600x900mm 72.3-inch                       | 1        | 0.36%   |
| Samsung Electronics V32F390 SAM0D5C 1920x1080 700x390mm 31.5-inch     | 1        | 0.36%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1        | 0.36%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.36%   |
| Samsung Electronics U24E590 SAM0CD2 3840x2160 521x293mm 23.5-inch     | 1        | 0.36%   |
| Samsung Electronics T22C350 SAM0AB7 1920x1080 477x268mm 21.5-inch     | 1        | 0.36%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 1        | 0.36%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1        | 0.36%   |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch  | 1        | 0.36%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch  | 1        | 0.36%   |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch  | 1        | 0.36%   |
| Samsung Electronics SyncMaster SAM02B5 1920x1200 518x324mm 24.1-inch  | 1        | 0.36%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.36%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 1        | 0.36%   |
| Samsung Electronics SMS24A450 SAM0839 1920x1200 518x324mm 24.1-inch   | 1        | 0.36%   |
| Samsung Electronics SMS19A450 SAM0848 1280x1024 376x301mm 19.0-inch   | 1        | 0.36%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch    | 1        | 0.36%   |
| Samsung Electronics SMBX2050 SAM0718 1600x900 443x249mm 20.0-inch     | 1        | 0.36%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1        | 0.36%   |
| Samsung Electronics S24F350 SAM0D21 1680x1050 520x290mm 23.4-inch     | 1        | 0.36%   |
| Samsung Electronics S24E390 SAM0C19 1920x1080 521x293mm 23.5-inch     | 1        | 0.36%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 1        | 0.36%   |
| Samsung Electronics S23E650 SAM0CAF 1920x1080 510x287mm 23.0-inch     | 1        | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 114      | 45.06%  |
| 3840x2160 (4K)     | 25       | 9.88%   |
| 1280x1024 (SXGA)   | 21       | 8.3%    |
| 2560x1440 (QHD)    | 16       | 6.32%   |
| 1680x1050 (WSXGA+) | 15       | 5.93%   |
| 1920x1200 (WUXGA)  | 10       | 3.95%   |
| Unknown            | 8        | 3.16%   |
| 1440x900 (WXGA+)   | 6        | 2.37%   |
| 1360x768           | 6        | 2.37%   |
| 3440x1440          | 5        | 1.98%   |
| 2560x1080          | 5        | 1.98%   |
| 1366x768 (WXGA)    | 5        | 1.98%   |
| 3840x1080          | 4        | 1.58%   |
| 1600x900 (HD+)     | 4        | 1.58%   |
| 5520x2160          | 1        | 0.4%    |
| 4480x1440          | 1        | 0.4%    |
| 4480x1080          | 1        | 0.4%    |
| 3840x1600          | 1        | 0.4%    |
| 3200x1080          | 1        | 0.4%    |
| 2560x1600          | 1        | 0.4%    |
| 1920x540           | 1        | 0.4%    |
| 1360x765           | 1        | 0.4%    |
| 1280x768           | 1        | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 43       | 17.06%  |
| 23      | 32       | 12.7%   |
| 24      | 30       | 11.9%   |
| 21      | 27       | 10.71%  |
| Unknown | 23       | 9.13%   |
| 19      | 14       | 5.56%   |
| 22      | 13       | 5.16%   |
| 17      | 12       | 4.76%   |
| 18      | 9        | 3.57%   |
| 34      | 8        | 3.17%   |
| 31      | 7        | 2.78%   |
| 72      | 6        | 2.38%   |
| 20      | 4        | 1.59%   |
| 40      | 3        | 1.19%   |
| 26      | 3        | 1.19%   |
| 84      | 2        | 0.79%   |
| 65      | 2        | 0.79%   |
| 49      | 2        | 0.79%   |
| 59      | 1        | 0.4%    |
| 57      | 1        | 0.4%    |
| 52      | 1        | 0.4%    |
| 48      | 1        | 0.4%    |
| 42      | 1        | 0.4%    |
| 41      | 1        | 0.4%    |
| 38      | 1        | 0.4%    |
| 37      | 1        | 0.4%    |
| 33      | 1        | 0.4%    |
| 32      | 1        | 0.4%    |
| 30      | 1        | 0.4%    |
| 15      | 1        | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 98       | 39.84%  |
| 401-500     | 55       | 22.36%  |
| Unknown     | 23       | 9.35%   |
| 601-700     | 14       | 5.69%   |
| 301-350     | 12       | 4.88%   |
| 351-400     | 11       | 4.47%   |
| 701-800     | 10       | 4.07%   |
| 1501-2000   | 8        | 3.25%   |
| 1001-1500   | 8        | 3.25%   |
| 801-900     | 5        | 2.03%   |
| 901-1000    | 2        | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 147      | 62.55%  |
| 16/10   | 31       | 13.19%  |
| 5/4     | 21       | 8.94%   |
| Unknown | 21       | 8.94%   |
| 21/9    | 10       | 4.26%   |
| 4/3     | 2        | 0.85%   |
| 3/2     | 2        | 0.85%   |
| 6/5     | 1        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 81       | 32.79%  |
| 301-350        | 45       | 18.22%  |
| 151-200        | 27       | 10.93%  |
| Unknown        | 23       | 9.31%   |
| 351-500        | 18       | 7.29%   |
| More than 1000 | 16       | 6.48%   |
| 141-150        | 15       | 6.07%   |
| 251-300        | 14       | 5.67%   |
| 501-1000       | 7        | 2.83%   |
| 101-110        | 1        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 140      | 58.82%  |
| 101-120 | 45       | 18.91%  |
| Unknown | 23       | 9.66%   |
| 1-50    | 15       | 6.3%    |
| 121-160 | 9        | 3.78%   |
| 161-240 | 6        | 2.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 179      | 73.97%  |
| 2     | 47       | 19.42%  |
| 0     | 9        | 3.72%   |
| 3     | 7        | 2.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 148      | 42.41%  |
| Intel                           | 112      | 32.09%  |
| Qualcomm Atheros                | 20       | 5.73%   |
| Broadcom                        | 13       | 3.72%   |
| TP-Link                         | 8        | 2.29%   |
| Ralink Technology               | 5        | 1.43%   |
| Ralink                          | 4        | 1.15%   |
| Nvidia                          | 4        | 1.15%   |
| Aquantia                        | 4        | 1.15%   |
| Qualcomm Atheros Communications | 3        | 0.86%   |
| Marvell Technology Group        | 3        | 0.86%   |
| Linksys                         | 3        | 0.86%   |
| ASUSTek Computer                | 3        | 0.86%   |
| NetGear                         | 2        | 0.57%   |
| Micro Star International        | 2        | 0.57%   |
| DisplayLink                     | 2        | 0.57%   |
| VIA Technologies                | 1        | 0.29%   |
| Tenda                           | 1        | 0.29%   |
| STMicroelectronics              | 1        | 0.29%   |
| SILICON Laboratories            | 1        | 0.29%   |
| Samsung Electronics             | 1        | 0.29%   |
| Microsoft                       | 1        | 0.29%   |
| Microchip Technology            | 1        | 0.29%   |
| GDMicroelectronics              | 1        | 0.29%   |
| D-Link System                   | 1        | 0.29%   |
| D-Link                          | 1        | 0.29%   |
| Broadcom Limited                | 1        | 0.29%   |
| AVM                             | 1        | 0.29%   |
| ASIX Electronics                | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 104      | 26.53%  |
| Realtek RTL8125 2.5GbE Controller                                          | 22       | 5.61%   |
| Intel Wi-Fi 6 AX200                                                        | 17       | 4.34%   |
| Intel I211 Gigabit Network Connection                                      | 17       | 4.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 14       | 3.57%   |
| Intel Ethernet Connection (2) I219-V                                       | 10       | 2.55%   |
| Intel Ethernet Connection I217-LM                                          | 9        | 2.3%    |
| Intel Ethernet Connection (7) I219-V                                       | 8        | 2.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 6        | 1.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 5        | 1.28%   |
| Intel Wireless-AC 9260                                                     | 5        | 1.28%   |
| Intel Ethernet Controller I225-V                                           | 5        | 1.28%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 5        | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 4        | 1.02%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 4        | 1.02%   |
| Realtek 802.11ac NIC                                                       | 4        | 1.02%   |
| Ralink MT7601U Wireless Adapter                                            | 4        | 1.02%   |
| Intel Ethernet Connection (14) I219-V                                      | 4        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 4        | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 4        | 1.02%   |
| TP-Link TL WN823N RTL8192EU                                                | 3        | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 3        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 3        | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                            | 3        | 0.77%   |
| Intel Wireless 7260                                                        | 3        | 0.77%   |
| Intel Ethernet Connection I217-V                                           | 3        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3        | 0.77%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 2        | 0.51%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 2        | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2        | 0.51%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 2        | 0.51%   |
| Nvidia MCP61 Ethernet                                                      | 2        | 0.51%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 2        | 0.51%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                          | 2        | 0.51%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 0.51%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2        | 0.51%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                     | 2        | 0.51%   |
| Intel 600 Series Chipset Family Wireless-AC 9560                           | 2        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 0.51%   |
| Broadcom Network controller                                                | 2        | 0.51%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.51%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]             | 2        | 0.51%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]          | 2        | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]          | 2        | 0.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 1        | 0.26%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]            | 1        | 0.26%   |
| TP-Link Archer T4U ver.3                                                   | 1        | 0.26%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1        | 0.26%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 0.26%   |
| TP-Link 802.11ac WLAN Adapter                                              | 1        | 0.26%   |
| Tenda U12                                                                  | 1        | 0.26%   |
| STMicroelectronics Virtual COM Port                                        | 1        | 0.26%   |
| SILICON Laboratories Intel 537 [Winmodem]                                  | 1        | 0.26%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 47       | 39.17%  |
| Realtek Semiconductor           | 21       | 17.5%   |
| Qualcomm Atheros                | 10       | 8.33%   |
| TP-Link                         | 7        | 5.83%   |
| Broadcom                        | 7        | 5.83%   |
| Ralink Technology               | 5        | 4.17%   |
| Ralink                          | 4        | 3.33%   |
| Qualcomm Atheros Communications | 3        | 2.5%    |
| Linksys                         | 3        | 2.5%    |
| ASUSTek Computer                | 3        | 2.5%    |
| NetGear                         | 2        | 1.67%   |
| Micro Star International        | 2        | 1.67%   |
| Tenda                           | 1        | 0.83%   |
| Microsoft                       | 1        | 0.83%   |
| D-Link System                   | 1        | 0.83%   |
| D-Link                          | 1        | 0.83%   |
| Broadcom Limited                | 1        | 0.83%   |
| AVM                             | 1        | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                         | 17       | 14.17%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 6        | 5%      |
| Intel Wireless-AC 9260                                                      | 5        | 4.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 4        | 3.33%   |
| Realtek 802.11ac NIC                                                        | 4        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                             | 4        | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 4        | 3.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 4        | 3.33%   |
| TP-Link TL WN823N RTL8192EU                                                 | 3        | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                          | 3        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 3        | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                             | 3        | 2.5%    |
| Intel Wireless 7260                                                         | 3        | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 3        | 2.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 2        | 1.67%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                             | 2        | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2        | 1.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 2        | 1.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 2        | 1.67%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]  | 2        | 1.67%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                           | 2        | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 2        | 1.67%   |
| Intel 600 Series Chipset Family Wireless-AC 9560                            | 2        | 1.67%   |
| Broadcom Network controller                                                 | 2        | 1.67%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]              | 2        | 1.67%   |
| TP-Link Archer T4U ver.3                                                    | 1        | 0.83%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                      | 1        | 0.83%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 0.83%   |
| TP-Link 802.11ac WLAN Adapter                                               | 1        | 0.83%   |
| Tenda U12                                                                   | 1        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1        | 0.83%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 0.83%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                     | 1        | 0.83%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                    | 1        | 0.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 1        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1        | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1        | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                   | 1        | 0.83%   |
| Ralink RT2800 802.11n PCI                                                   | 1        | 0.83%   |
| Ralink RT2561/RT61 rev B 802.11g                                            | 1        | 0.83%   |
| Ralink RT2561/RT61 802.11g PCI                                              | 1        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 1        | 0.83%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]                      | 1        | 0.83%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                 | 1        | 0.83%   |
| Microsoft Xbox 360 Wireless Adapter                                         | 1        | 0.83%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 0.83%   |
| Intel Wireless 8265 / 8275                                                  | 1        | 0.83%   |
| Intel Wireless 8260                                                         | 1        | 0.83%   |
| Intel Wireless 7265                                                         | 1        | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                              | 1        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                              | 1        | 0.83%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]           | 1        | 0.83%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]        | 1        | 0.83%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1        | 0.83%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                        | 1        | 0.83%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                    | 1        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 137      | 51.89%  |
| Intel                    | 93       | 35.23%  |
| Qualcomm Atheros         | 10       | 3.79%   |
| Broadcom                 | 6        | 2.27%   |
| Nvidia                   | 4        | 1.52%   |
| Aquantia                 | 4        | 1.52%   |
| Marvell Technology Group | 3        | 1.14%   |
| DisplayLink              | 2        | 0.76%   |
| VIA Technologies         | 1        | 0.38%   |
| TP-Link                  | 1        | 0.38%   |
| Samsung Electronics      | 1        | 0.38%   |
| Microchip Technology     | 1        | 0.38%   |
| ASIX Electronics         | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 104      | 38.66%  |
| Realtek RTL8125 2.5GbE Controller                                             | 22       | 8.18%   |
| Intel I211 Gigabit Network Connection                                         | 17       | 6.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14       | 5.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 10       | 3.72%   |
| Intel Ethernet Connection I217-LM                                             | 9        | 3.35%   |
| Intel Ethernet Connection (7) I219-V                                          | 8        | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5        | 1.86%   |
| Intel Ethernet Controller I225-V                                              | 5        | 1.86%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 5        | 1.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 1.49%   |
| Intel Ethernet Connection (14) I219-V                                         | 4        | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 1.12%   |
| Intel Ethernet Connection I217-V                                              | 3        | 1.12%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.12%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2        | 0.74%   |
| Nvidia MCP61 Ethernet                                                         | 2        | 0.74%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 0.74%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.74%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 2        | 0.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.74%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 2        | 0.74%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 0.74%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.37%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]               | 1        | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.37%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1        | 0.37%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1        | 0.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.37%   |
| Nvidia MCP55 Ethernet                                                         | 1        | 0.37%   |
| Nvidia MCP51 Ethernet Controller                                              | 1        | 0.37%   |
| Microchip LAN9500A/LAN9500Ai                                                  | 1        | 0.37%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 1        | 0.37%   |
| Marvell Group 88E8070 based Ethernet Controller                               | 1        | 0.37%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1        | 0.37%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.37%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.37%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.37%   |
| Intel Ethernet Connection (11) I219-LM                                        | 1        | 0.37%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.37%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.37%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.37%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 0.37%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.37%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.37%   |
| DisplayLink USB3.0 Dual Video Dock                                            | 1        | 0.37%   |
| DisplayLink USB3.0 5K Graphic Docking                                         | 1        | 0.37%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 0.37%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.37%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 238      | 67.23%  |
| WiFi     | 113      | 31.92%  |
| Modem    | 3        | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 193      | 69.93%  |
| WiFi     | 83       | 30.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 147      | 61.25%  |
| 2     | 71       | 29.58%  |
| 3     | 17       | 7.08%   |
| 0     | 2        | 0.83%   |
| 6     | 1        | 0.42%   |
| 5     | 1        | 0.42%   |
| 4     | 1        | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 156      | 64.73%  |
| Yes  | 85       | 35.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 43       | 48.31%  |
| Cambridge Silicon Radio         | 25       | 28.09%  |
| Realtek Semiconductor           | 4        | 4.49%   |
| Qualcomm Atheros Communications | 4        | 4.49%   |
| Broadcom                        | 4        | 4.49%   |
| ASUSTek Computer                | 4        | 4.49%   |
| Micro Star International        | 2        | 2.25%   |
| Belkin Components               | 2        | 2.25%   |
| Apple                           | 1        | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 25       | 28.09%  |
| Intel AX200 Bluetooth                                 | 16       | 17.98%  |
| Intel Bluetooth wireless interface                    | 6        | 6.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 5        | 5.62%   |
| Intel Bluetooth Device                                | 5        | 5.62%   |
| Intel AX210 Bluetooth                                 | 5        | 5.62%   |
| Realtek Bluetooth Radio                               | 4        | 4.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 4        | 4.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 4.49%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 2.25%   |
| Micro Star International Bluetooth Device             | 2        | 2.25%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 2.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 2.25%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 1.12%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 1.12%   |
| Belkin Components F8T001v2 Bluetooth                  | 1        | 1.12%   |
| ASUS Bluetooth Adapter                                | 1        | 1.12%   |
| ASUS ASUS USB-BT500                                   | 1        | 1.12%   |
| Apple Bluetooth HCI                                   | 1        | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 147      | 37.03%  |
| Nvidia                     | 97       | 24.43%  |
| AMD                        | 96       | 24.18%  |
| Creative Labs              | 12       | 3.02%   |
| C-Media Electronics        | 9        | 2.27%   |
| Logitech                   | 4        | 1.01%   |
| GN Netcom                  | 4        | 1.01%   |
| ASUSTek Computer           | 3        | 0.76%   |
| VIA Technologies           | 2        | 0.5%    |
| Generalplus Technology     | 2        | 0.5%    |
| Corsair                    | 2        | 0.5%    |
| XMOS                       | 1        | 0.25%   |
| Unknown                    | 1        | 0.25%   |
| Texas Instruments          | 1        | 0.25%   |
| Samson Technologies        | 1        | 0.25%   |
| Realtek Semiconductor      | 1        | 0.25%   |
| Razer USA                  | 1        | 0.25%   |
| PreSonus Audio Electronics | 1        | 0.25%   |
| Panasonic (Matsushita)     | 1        | 0.25%   |
| Micro Star International   | 1        | 0.25%   |
| MAG Technology             | 1        | 0.25%   |
| JMTek                      | 1        | 0.25%   |
| Focusrite-Novation         | 1        | 0.25%   |
| FIFINE Microphones         | 1        | 0.25%   |
| Digidesign                 | 1        | 0.25%   |
| Creative Technology        | 1        | 0.25%   |
| Cambridge Silicon Radio    | 1        | 0.25%   |
| Bose                       | 1        | 0.25%   |
| Audio-Technica             | 1        | 0.25%   |
| Astro Gaming               | 1        | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 25       | 5.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 20       | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 19       | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 17       | 3.66%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 17       | 3.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 16       | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 3.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 13       | 2.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 12       | 2.59%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 12       | 2.59%   |
| Intel 200 Series PCH HD Audio                                                     | 11       | 2.37%   |
| Nvidia GP106 High Definition Audio Controller                                     | 9        | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                        | 9        | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9        | 1.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 8        | 1.72%   |
| Nvidia High Definition Audio Controller                                           | 7        | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.51%   |
| Nvidia GP104 High Definition Audio Controller                                     | 6        | 1.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5        | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5        | 1.08%   |
| Intel Audio device                                                                | 5        | 1.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 1.08%   |
| Intel 600 Series Chipset Family Smart Sound Technology (SST) Audio Controller     | 5        | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5        | 1.08%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                         | 5        | 1.08%   |
| AMD Navi 10 HDMI Audio                                                            | 5        | 1.08%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.08%   |
| Nvidia TU104 HD Audio Controller                                                  | 4        | 0.86%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 0.86%   |
| Nvidia GF119 HDMI Audio Controller                                                | 4        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 0.86%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 4        | 0.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4        | 0.86%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 4        | 0.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 0.86%   |
| AMD Trinity HDMI Audio Controller                                                 | 4        | 0.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.65%   |
| Nvidia GF106 High Definition Audio Controller                                     | 3        | 0.65%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 0.65%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.65%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 0.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.65%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 3        | 0.65%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 3        | 0.65%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2        | 0.43%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.43%   |
| Nvidia MCP55 High Definition Audio                                                | 2        | 0.43%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2        | 0.43%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.43%   |
| Nvidia GK110 High Definition Audio Controller                                     | 2        | 0.43%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.43%   |
| Nvidia Audio device                                                               | 2        | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 13       | 13.4%   |
| G.Skill             | 13       | 13.4%   |
| Corsair             | 13       | 13.4%   |
| Crucial             | 12       | 12.37%  |
| Samsung Electronics | 11       | 11.34%  |
| Unknown             | 10       | 10.31%  |
| SK Hynix            | 4        | 4.12%   |
| Micron Technology   | 4        | 4.12%   |
| Team                | 3        | 3.09%   |
| Patriot             | 3        | 3.09%   |
| PNY                 | 2        | 2.06%   |
| Nanya Technology    | 2        | 2.06%   |
| Transcend           | 1        | 1.03%   |
| Hewlett-Packard     | 1        | 1.03%   |
| GEIL                | 1        | 1.03%   |
| Elpida              | 1        | 1.03%   |
| ASint Technology    | 1        | 1.03%   |
| A-DATA Technology   | 1        | 1.03%   |
| Unknown             | 1        | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 4        | 3.81%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 3        | 2.86%   |
| G.Skill RAM F3-2133C9-8GXH 8GB DIMM DDR3 2133MT/s       | 2        | 1.9%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 1.9%    |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s               | 1        | 0.95%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.95%   |
| Unknown RAM Module 8GB DIMM 400MT/s                     | 1        | 0.95%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.95%   |
| Unknown RAM Module 4GB DDR3 1600MT/s                    | 1        | 0.95%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 0.95%   |
| Unknown RAM Module 1GB DIMM 800MT/s                     | 1        | 0.95%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s   | 1        | 0.95%   |
| Transcend RAM TS512MLK72W6H 4GB DIMM DDR3 1600MT/s      | 1        | 0.95%   |
| Team RAM TEAMGROUP-UD4-3600 8192MB DIMM DDR4 3600MT/s   | 1        | 0.95%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s      | 1        | 0.95%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s      | 1        | 0.95%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.95%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s   | 1        | 0.95%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 0.95%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.95%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2048MB DIMM DDR3 1600MT/s | 1        | 0.95%   |
| Samsung RAM Module 32GB DIMM DDR4 2933MT/s              | 1        | 0.95%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s  | 1        | 0.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB DIMM DDR4 2667MT/s     | 1        | 0.95%   |
| Samsung RAM M393B1K70DH0 8GB DIMM DDR3 1866MT/s         | 1        | 0.95%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |
| Samsung RAM M378B5673FH0-CF8 2048MB DIMM DDR3 1067MT/s  | 1        | 0.95%   |
| Samsung RAM M378B5273DH0-CH9 4GB SODIMM DDR3 1333MT/s   | 1        | 0.95%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s  | 1        | 0.95%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2400MT/s     | 1        | 0.95%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s     | 1        | 0.95%   |
| PNY RAM 8GBF1X08RHLL42-135-K 8GB DIMM DDR4 2667MT/s     | 1        | 0.95%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s    | 1        | 0.95%   |
| Patriot RAM 4400 C19 Series 8GB DIMM DDR4 4266MT/s      | 1        | 0.95%   |
| Patriot RAM 2133 CL11 Series 8GB DIMM DDR3 2400MT/s     | 1        | 0.95%   |
| Patriot RAM 2133 C14 Series 4GB DIMM DDR4 2133MT/s      | 1        | 0.95%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s      | 1        | 0.95%   |
| Nanya RAM M2F4GH64CB8HB6N-CG 4GB DIMM DDR3 1333MT/s     | 1        | 0.95%   |
| Micron RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s    | 1        | 0.95%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2800MT/s     | 1        | 0.95%   |
| Micron RAM 18HTF25672AY-800G1 2GB DIMM DDR2 1600MT/s    | 1        | 0.95%   |
| Micron RAM 16HTF25664AZ-800H1 2GB DIMM DDR2 800MT/s     | 1        | 0.95%   |
| Kingston RAM Module 1GB DIMM DDR 533MT/s                | 1        | 0.95%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s  | 1        | 0.95%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s    | 1        | 0.95%   |
| Kingston RAM KHX2666C13/8GX 8192MB DIMM DDR4 2667MT/s   | 1        | 0.95%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s     | 1        | 0.95%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s  | 1        | 0.95%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1867MT/s  | 1        | 0.95%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s   | 1        | 0.95%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s     | 1        | 0.95%   |
| Kingston RAM CL16-18-18 D4-3200 8GB DIMM DDR4 3200MT/s  | 1        | 0.95%   |
| Kingston RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s  | 1        | 0.95%   |
| Kingston RAM ACR26D4U9S8MH-8 8GB DIMM DDR4 2400MT/s     | 1        | 0.95%   |
| Kingston RAM 9905678-023.A00G 8GB DIMM DDR4 2134MT/s    | 1        | 0.95%   |
| HP RAM 752369-081 16GB DIMM DDR4 2133MT/s               | 1        | 0.95%   |
| HP RAM 752368-081 8GB DIMM DDR4 2133MT/s                | 1        | 0.95%   |
| GEIL RAM CL16-18-18 D4-3200 8GB DIMM DDR4 3200MT/s      | 1        | 0.95%   |
| G.Skill RAM F4-5333C22-8GTRS 8GB DIMM DDR4 2133MT/s     | 1        | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 54       | 64.29%  |
| DDR3    | 21       | 25%     |
| Unknown | 6        | 7.14%   |
| DDR2    | 2        | 2.38%   |
| DDR     | 1        | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 80       | 95.24%  |
| SODIMM  | 3        | 3.57%   |
| Unknown | 1        | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 41       | 43.16%  |
| 16384 | 19       | 20%     |
| 4096  | 18       | 18.95%  |
| 32768 | 9        | 9.47%   |
| 2048  | 6        | 6.32%   |
| 1024  | 2        | 2.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 20       | 21.28%  |
| 1600  | 10       | 10.64%  |
| 3600  | 9        | 9.57%   |
| 2667  | 8        | 8.51%   |
| 1333  | 8        | 8.51%   |
| 2133  | 7        | 7.45%   |
| 2400  | 5        | 5.32%   |
| 2933  | 2        | 2.13%   |
| 1867  | 2        | 2.13%   |
| 1800  | 2        | 2.13%   |
| 800   | 2        | 2.13%   |
| 49926 | 1        | 1.06%   |
| 4266  | 1        | 1.06%   |
| 4000  | 1        | 1.06%   |
| 3800  | 1        | 1.06%   |
| 3733  | 1        | 1.06%   |
| 3533  | 1        | 1.06%   |
| 3400  | 1        | 1.06%   |
| 3266  | 1        | 1.06%   |
| 3067  | 1        | 1.06%   |
| 3000  | 1        | 1.06%   |
| 2800  | 1        | 1.06%   |
| 2666  | 1        | 1.06%   |
| 2134  | 1        | 1.06%   |
| 2048  | 1        | 1.06%   |
| 2000  | 1        | 1.06%   |
| 1866  | 1        | 1.06%   |
| 1067  | 1        | 1.06%   |
| 533   | 1        | 1.06%   |
| 400   | 1        | 1.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 38.89%  |
| Canon               | 5        | 27.78%  |
| Hewlett-Packard     | 3        | 16.67%  |
| Brother Industries  | 3        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung SCX-3400 Series              | 2        | 11.11%  |
| Samsung M283x Series                 | 2        | 11.11%  |
| Samsung ML-216x Series Laser Printer | 1        | 5.56%   |
| Samsung ML-1865                      | 1        | 5.56%   |
| Samsung C43x Series                  | 1        | 5.56%   |
| HP ENVY Photo 6200 series            | 1        | 5.56%   |
| HP DeskJet F4100 Printer series      | 1        | 5.56%   |
| HP DeskJet 3700 series               | 1        | 5.56%   |
| Canon TR8600 series                  | 1        | 5.56%   |
| Canon TR4500 series                  | 1        | 5.56%   |
| Canon PIXMA MP280                    | 1        | 5.56%   |
| Canon PIXMA MG3600 Series            | 1        | 5.56%   |
| Canon MF731C/733C                    | 1        | 5.56%   |
| Brother Printer                      | 1        | 5.56%   |
| Brother HL-3140CW series             | 1        | 5.56%   |
| Brother HL-1430 Laser Printer        | 1        | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 4        | 57.14%  |
| Seiko Epson | 3        | 42.86%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                       | 2        | 28.57%  |
| Seiko Epson Scanner                           | 1        | 14.29%  |
| Seiko Epson GT-9400UF [Perfection 3170]       | 1        | 14.29%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1        | 14.29%  |
| Canon CanoScan N1240U/LiDE 30                 | 1        | 14.29%  |
| Canon CanoScan LiDE 200                       | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 23       | 46.94%  |
| Microsoft                     | 5        | 10.2%   |
| Microdia                      | 3        | 6.12%   |
| Generalplus Technology        | 3        | 6.12%   |
| ARC International             | 3        | 6.12%   |
| Apple                         | 3        | 6.12%   |
| Sunplus Innovation Technology | 2        | 4.08%   |
| Z-Star Microelectronics       | 1        | 2.04%   |
| Unknown                       | 1        | 2.04%   |
| Samsung Electronics           | 1        | 2.04%   |
| PrehKeyTec                    | 1        | 2.04%   |
| Philips (or NXP)              | 1        | 2.04%   |
| Huawei Technologies           | 1        | 2.04%   |
| Creative Technology           | 1        | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 5        | 10.2%   |
| Logitech HD Pro Webcam C920               | 4        | 8.16%   |
| Logitech Webcam C930e                     | 3        | 6.12%   |
| ARC International Camera                  | 3        | 6.12%   |
| Microsoft LifeCam HD-3000                 | 2        | 4.08%   |
| Logitech HD Webcam C910                   | 2        | 4.08%   |
| Logitech C922 Pro Stream Webcam           | 2        | 4.08%   |
| Logitech BRIO Ultra HD Webcam             | 2        | 4.08%   |
| Generalplus 808 Camera                    | 2        | 4.08%   |
| Z-Star Lenovo USB 2.0 UVC Camera          | 1        | 2.04%   |
| Unknown HD camera                         | 1        | 2.04%   |
| Sunplus HD 720P webcam                    | 1        | 2.04%   |
| Sunplus FHD Camera Microphone             | 1        | 2.04%   |
| Samsung Galaxy A5 (MTP)                   | 1        | 2.04%   |
| PrehKeyTec TA-0120-AS                     | 1        | 2.04%   |
| Philips (or NXP) SPC 520/525NC PC Camera  | 1        | 2.04%   |
| Microsoft LifeCam VX-7000 (UVC-compliant) | 1        | 2.04%   |
| Microsoft LifeCam Studio                  | 1        | 2.04%   |
| Microsoft LifeCam HD-5000                 | 1        | 2.04%   |
| Microdia Webcam Vitade AF                 | 1        | 2.04%   |
| Microdia USB 2.0 Camera                   | 1        | 2.04%   |
| Microdia Sonix USB 2.0 Camera             | 1        | 2.04%   |
| Logitech Webcam C310                      | 1        | 2.04%   |
| Logitech Webcam C300                      | 1        | 2.04%   |
| Logitech QuickCam Pro for Notebooks       | 1        | 2.04%   |
| Logitech HD Webcam C615                   | 1        | 2.04%   |
| Logitech HD Webcam B910                   | 1        | 2.04%   |
| Huawei HiCamera                           | 1        | 2.04%   |
| Generalplus GENERAL WEBCAM                | 1        | 2.04%   |
| Creative Live! Cam Chat HD [VF0700]       | 1        | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE                 | 1        | 2.04%   |
| Apple iPhone 4S                           | 1        | 2.04%   |
| Apple iPhone 4                            | 1        | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 209      | 86.72%  |
| 1     | 29       | 12.03%  |
| 2     | 3        | 1.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 33.33%  |
| Net/wireless             | 9        | 27.27%  |
| Unassigned class         | 5        | 15.15%  |
| Multimedia controller    | 2        | 6.06%   |
| Storage/raid             | 1        | 3.03%   |
| Sound                    | 1        | 3.03%   |
| Modem                    | 1        | 3.03%   |
| Fingerprint reader       | 1        | 3.03%   |
| Communication controller | 1        | 3.03%   |
| Card reader              | 1        | 3.03%   |

